---
title: Nedostaju uslovi iz skladišta za SharePoint online
ms.author: pebaum
author: pebaum
ms.date: 10/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1243"
- "5200021"
ms.openlocfilehash: 28913b8e57e39d51e8957b7408c19337a119c589
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40053527"
---
# <a name="enabling-bitlocker-encryption-with-intune"></a><span data-ttu-id="fc577-102">Omogućavanje BitLocker šifrovanja pomoću usluge Intune</span><span class="sxs-lookup"><span data-stu-id="fc577-102">Enabling Bitlocker Encryption with Intune</span></span>

<span data-ttu-id="fc577-103">Smernice za zaštitu krajnje tačke funkcije Intune mogu da se koriste za Konfigurisanje postavki Boitlocker šifrovanja za Windows uređaje kao što je opisano u: Windows10 (i novijim) postavkama za zaštitu uređaja pomoću funkcije Intune</span><span class="sxs-lookup"><span data-stu-id="fc577-103">Intune Endpoint Protection Policy can be used to configure Boitlocker encryption settings for Windows devices as described in : Windows10 (and later) settings to protect devices using Intune</span></span>

<span data-ttu-id="fc577-104">Trebalo bi da znate da mnogi noviji uređaji koji rade pod operativnim sistemom Windows 10 podržavaju automatsko BitLocker šifrovanje koje se aktivira bez zatvaranja smernica MDM.</span><span class="sxs-lookup"><span data-stu-id="fc577-104">You should be aware that many newer devices running Windows 10 support automatic bitlocker encryption which is triggered without the application of MDM policy.</span></span> <span data-ttu-id="fc577-105">Ovo može da utiče na primenu smernica ako su konfigurisane postavke koje nisu podrazumevane.</span><span class="sxs-lookup"><span data-stu-id="fc577-105">This may impact application of policy if non default settings are configured.</span></span> <span data-ttu-id="fc577-106">Za više detalja pogledajte najčešća pitanja.</span><span class="sxs-lookup"><span data-stu-id="fc577-106">See FAQ for more detail.</span></span>


<span data-ttu-id="fc577-107">Najčešća  pitanja Q: koja izdanja Windows šifrovanja uređaja podrške pomoću smernica za zaštitu krajnjeg čvorišta?</span><span class="sxs-lookup"><span data-stu-id="fc577-107">FAQ  Q: Which editions of Windows support device encryption using the Endpoint Protection Policy?</span></span>
<span data-ttu-id="fc577-108"> A: postavke u smernicama za zaštitu krajnje tačke u funkciji Intune primenjuju se pomoću BitLocker CSP.</span><span class="sxs-lookup"><span data-stu-id="fc577-108"> A: The settings in Intune Endpoint Protection Policy  are implemented using the Bitlocker CSP.</span></span><span data-ttu-id="fc577-109">Nisu sve izdanja ni verzije operativnog sistema Windows koje podržavaju BitLocker CSP. 
     </span><span class="sxs-lookup"><span data-stu-id="fc577-109">  Not all editions nor builds of Windows support the Bitlocker CSP. 
     </span></span> <span data-ttu-id="fc577-110">U ovom trenutku Windows izdanja: Enterprise; Podržano je obrazovanje, mobilni, mobilni poduhvat i stručni (od izrade 1809 na osnovu).</span><span class="sxs-lookup"><span data-stu-id="fc577-110">At this time Windows Editions: Enterprise; Education, Mobile, Mobile Enterprise and Professional (from build 1809 onwards) are supported.</span></span>




<span data-ttu-id="fc577-111">Q: ako je uređaj već šifrovan pomoću funkcije BitLocker koristeći podrazumevane postavke OS za metod šifrovanja i snagu šifrovanja (XTS-AES-128), primenjiće se smernica sa različitim postavkama automatski aktivirati ponovno šifriranje disk jedinice sa novim postavkama?</span><span class="sxs-lookup"><span data-stu-id="fc577-111">Q: If a device is already encrypted with Bitlocker using the OS default settings for encryption method and cipher strength (XTS-AES-128)  will applying a policy with different settings automatically trigger re-encryption of the drive with the new settings?</span></span>

<span data-ttu-id="fc577-112">A: ne.</span><span class="sxs-lookup"><span data-stu-id="fc577-112">A: No.</span></span> <span data-ttu-id="fc577-113">Da bi primenio nove postavke za šifrovanje, disk jedinica se prvo mora dešifrovati.</span><span class="sxs-lookup"><span data-stu-id="fc577-113">In order to apply the new cipher settings the drive must first be decrypted.</span></span>

<span data-ttu-id="fc577-114">Napomena za uređaje koji se upisuju sa autopilot automatsko šifrovanje koje bi se dešalo tokom OOBE-a nije izazvano dok se ne proceni da se postavke zasnovane na smernicama koriste umesto podrazumevanih vrednosti OS</span><span class="sxs-lookup"><span data-stu-id="fc577-114">Note For devices being enrolled with Autopilot the automatic encryption that would occur during OOBE is not triggered until Intune policy is evaluated which allows the policy based settings to be used in place of the OS defaults</span></span>




<span data-ttu-id="fc577-115">Q ako je uređaj šifrovan kao rezultat zatvaranja smernica za Intune, biće dešifrovan kada se ta smernica ukloni?</span><span class="sxs-lookup"><span data-stu-id="fc577-115">Q If a device is encrypted as a result of the  application of Intune policy will it be decrypted when that policy is removed?</span></span>

<span data-ttu-id="fc577-116">A: uklanjanje smernica vezanih za šifrovanje ne dovodi do dešifrovanja disk jedinica koje su konfigurisane.</span><span class="sxs-lookup"><span data-stu-id="fc577-116">A: Removal of encryption related policy does NOT result in decryption of the drives which were configured.</span></span>




<span data-ttu-id="fc577-117">Q: Zašto u skladu sa smernicama usaglašenosti pokazuju da moj uređaj nema "BitLocker omogućeno", ali jeste?</span><span class="sxs-lookup"><span data-stu-id="fc577-117">Q: Why does intune Compliance policy show that my device does not have "Bitlocker Enabled" but it is?</span></span>

<span data-ttu-id="fc577-118">A: postavka "BitLocker Enabled" u smernicama usaglašenosti koristi Windows klijent za zaštitu od zdravlja uređaja (DHA).</span><span class="sxs-lookup"><span data-stu-id="fc577-118">A: The "Bitlocker enabled" setting in intune compliance policy utilizes the Windows Device Health Attestation  (DHA) client.</span></span> <span data-ttu-id="fc577-119">Ovaj klijent samo Meri stanje uređaja u trenutku pokretanja.</span><span class="sxs-lookup"><span data-stu-id="fc577-119">This client only measures device state at boot time.</span></span> <span data-ttu-id="fc577-120">Dakle, ako uređaj nije ponovo pokrenut otkako je BitLocker šifrovanje dovršeno, usluga DHA Client neće prijaviti BitLocker kao aktivnu.</span><span class="sxs-lookup"><span data-stu-id="fc577-120">So if a device has not been rebooted since bitlocker encryption was completed the DHA client service will not report bitlocker as being active.</span></span>