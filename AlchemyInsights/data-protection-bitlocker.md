---
title: DataProtection-BitLocker
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1802"
- "9000220"
ms.openlocfilehash: c23a2a2bde240900119382a9c1185a6e02520149
ms.sourcegitcommit: 123e9fe46e99719dd271e75a66555861e968f4a2
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/30/2019
ms.locfileid: "40908723"
---
# <a name="enabling-bitlocker-encryption-with-intune"></a><span data-ttu-id="f759c-102">Omogućavanje BitLocker šifrovanja pomoću usluge Intune</span><span class="sxs-lookup"><span data-stu-id="f759c-102">Enabling Bitlocker encryption with Intune</span></span>

 <span data-ttu-id="f759c-103">Smernice zaštite krajnje tačke za Intune mogu da se koriste za Konfigurisanje postavki BitLocker šifrovanja za Windows uređaje.</span><span class="sxs-lookup"><span data-stu-id="f759c-103">Intune Endpoint Protection Policy can be used to configure Bitlocker encryption settings for Windows devices.</span></span> <span data-ttu-id="f759c-104">Za više informacija pogledajte [Postavke operativnog sistema Windows 10 (i novije) da biste zaštitili uređaje pomoću funkcije Intune](https://docs.microsoft.com/intune/endpoint-protection-windows-10#windows-encryption).</span><span class="sxs-lookup"><span data-stu-id="f759c-104">For more information, see [Windows 10 (and later) settings to protect devices using Intune](https://docs.microsoft.com/intune/endpoint-protection-windows-10#windows-encryption).</span></span>
 
<span data-ttu-id="f759c-105">Trebalo bi da znate da mnogi noviji uređaji koji rade pod operativnim sistemom Windows 10 podržavaju automatsko BitLocker šifrovanje, koje se pokreće bez primene "MDM" smernica.</span><span class="sxs-lookup"><span data-stu-id="f759c-105">You should be aware that many newer devices running Windows 10 support automatic Bitlocker encryption, which is triggered without the application of MDM policy.</span></span> <span data-ttu-id="f759c-106">Ovo može da utiče na primenu smernica ako su konfigurisane postavke koje nisu podrazumevane.</span><span class="sxs-lookup"><span data-stu-id="f759c-106">This may impact application of policy if non-default settings are configured.</span></span> <span data-ttu-id="f759c-107">Više detalja potražite u sledećim FAQ.</span><span class="sxs-lookup"><span data-stu-id="f759c-107">See the following FAQ for more detail.</span></span>
 
<span data-ttu-id="f759c-108">Više informacija o rešavanju problema sa BitLocker šifrovanjem potražite [u članku rešavanje problema sa BitLocker smernicama u programu Microsoft Intune](https://docs.microsoft.com/intune/protect/troubleshoot-bitlocker-policies).</span><span class="sxs-lookup"><span data-stu-id="f759c-108">For information about troubleshooting bitlocker issues, see [Troubleshoot BitLocker policies in Microsoft Intune](https://docs.microsoft.com/intune/protect/troubleshoot-bitlocker-policies).</span></span>
 
 
<span data-ttu-id="f759c-109">**Faq**</span><span class="sxs-lookup"><span data-stu-id="f759c-109">**FAQ**</span></span>

 <span data-ttu-id="f759c-110">Q: koja izdanja Windows šifrovanja uređaja podrške pomoću smernica za zaštitu krajnjeg čvorišta?</span><span class="sxs-lookup"><span data-stu-id="f759c-110">Q: Which editions of Windows support device encryption using the Endpoint Protection Policy?</span></span><br>
 <span data-ttu-id="f759c-111">A: postavke u smernicama za zaštitu krajnje tačke u funkciji Intune primenjuju se pomoću [BITLOCKER CSP](https://docs.microsoft.com/windows/client-management/mdm/bitlocker-csp).</span><span class="sxs-lookup"><span data-stu-id="f759c-111">A: The settings in Intune Endpoint Protection Policy  are implemented using the [Bitlocker CSP](https://docs.microsoft.com/windows/client-management/mdm/bitlocker-csp).</span></span> <span data-ttu-id="f759c-112">Nisu sve izdanja ili verzije operativnog sistema Windows podržavaju BitLocker CSP.</span><span class="sxs-lookup"><span data-stu-id="f759c-112">Not all editions or builds of Windows support the Bitlocker CSP.</span></span> <br><br>
      <span data-ttu-id="f759c-113">U ovom trenutku podržane su sledeće Windows izdanja: Enterprise, obrazovanje, mobilni, mobilni Enterprise i profesionalni (verzija 1809 i novije).</span><span class="sxs-lookup"><span data-stu-id="f759c-113">At this time, the following Windows editions are supported: Enterprise, Education, Mobile, Mobile Enterprise, and Professional (build 1809 and later).</span></span>
 
<span data-ttu-id="f759c-114">Q: ako je uređaj već šifrovan pomoću funkcije BitLocker koristeći podrazumevane postavke OS za metod šifrovanja i snagu šifrovanja (XTS-AES-128), primenjiće se smernica sa različitim postavkama automatski aktivirati ponovno šifriranje disk jedinice sa novim postavkama?</span><span class="sxs-lookup"><span data-stu-id="f759c-114">Q: If a device is already encrypted with Bitlocker using the OS default settings for encryption method and cipher strength (XTS-AES-128), will applying a policy with different settings automatically trigger re-encryption of the drive with the new settings?</span></span><br>
<span data-ttu-id="f759c-115">A: ne.</span><span class="sxs-lookup"><span data-stu-id="f759c-115">A: No.</span></span> <span data-ttu-id="f759c-116">Da biste primenili nove postavke za šifrovanje, disk jedinica prvo mora biti dešifrovana.</span><span class="sxs-lookup"><span data-stu-id="f759c-116">To apply the new cipher settings, the drive must first be decrypted.</span></span><br><br>
<span data-ttu-id="f759c-117">**Napomena:** Za uređaje koji se upisuju na autopilot, automatsko šifrovanje koje će se pojaviti tokom OOBE datoteke se ne aktivira dok se ne proceni funkcija "Intune", što omogućava da se postavke zasnovane na smernicama koriste umesto podrazumevanih vrednosti OS.</span><span class="sxs-lookup"><span data-stu-id="f759c-117">**Note:** For devices being enrolled with Autopilot, the automatic encryption that would occur during OOBE is not triggered until Intune policy is evaluated, which allows the policy-based settings to be used in place of the OS defaults.</span></span>
 
<span data-ttu-id="f759c-118">Q: ako je uređaj šifrovan kao rezultat primjene programa Intune, da li će se dešifrovati kada se ta smernica ukloni?</span><span class="sxs-lookup"><span data-stu-id="f759c-118">Q: If a device is encrypted as a result of the  application of Intune policy, will it be decrypted when that policy is removed?</span></span><br>
<span data-ttu-id="f759c-119">A: uklanjanje smernica vezanih za šifrovanje ne dovodi do dešifrovanja disk jedinica koje su konfigurisane.</span><span class="sxs-lookup"><span data-stu-id="f759c-119">A: Removal of encryption-related policy does NOT result in decryption of the drives that were configured.</span></span>
 
<span data-ttu-id="f759c-120">Q: Zašto u skladu sa smernicama usaglašenosti pokazuje da moj uređaj nema omogućen BitLocker, čak i ako jeste?</span><span class="sxs-lookup"><span data-stu-id="f759c-120">Q: Why does Intune Compliance Policy show that my device does not have Bitlocker enabled, even though it is?</span></span><br>
<span data-ttu-id="f759c-121">A: postavka "BitLocker Enabled" u smernicama usaglašenosti koristi Windows klijent za zaštitu od zdravlja uređaja (DHA).</span><span class="sxs-lookup"><span data-stu-id="f759c-121">A: The "Bitlocker enabled" setting in the Intune Compliance Policy utilizes the Windows Device Health Attestation  (DHA) client.</span></span> <span data-ttu-id="f759c-122">Ovaj klijent samo Meri stanje uređaja u trenutku pokretanja.</span><span class="sxs-lookup"><span data-stu-id="f759c-122">This client only measures device state at boot time.</span></span> <span data-ttu-id="f759c-123">Ako uređaj nije ponovo pokrenut otkako je BitLocker šifrovanje dovršeno, usluga DHA Client neće prijaviti BitLocker kao aktivnu.</span><span class="sxs-lookup"><span data-stu-id="f759c-123">So if a device has not been rebooted since Bitlocker encryption was completed, the DHA client service will not report Bitlocker as being active.</span></span>
 
 