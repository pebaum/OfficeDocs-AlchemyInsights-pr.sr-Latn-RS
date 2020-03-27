---
title: DLP ne radi na očekivani način
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1241"
- "3200001"
ms.assetid: f6fcf5ad-55a1-4f25-af27-1f7c1ce06409
ms.openlocfilehash: 574a8a43d8264e98c6af2bfeb1bb472475e6e334
ms.sourcegitcommit: d108a2da2f5dab05246e30b5108cca5173e09051
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/26/2020
ms.locfileid: "42977452"
---
# <a name="dlp-not-working-as-expected"></a><span data-ttu-id="c24d6-102">DLP ne radi na očekivani način</span><span class="sxs-lookup"><span data-stu-id="c24d6-102">DLP not working as expected</span></span>

<span data-ttu-id="c24d6-103">**Važno**: u ovakvim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive ostanu veoma dostupne – posetite [SharePoint online prilagođavanja](https://aka.ms/ODSPAdjustments) za više informacija.</span><span class="sxs-lookup"><span data-stu-id="c24d6-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

 <span data-ttu-id="c24d6-104">**Podešavanje DLP-a**</span><span class="sxs-lookup"><span data-stu-id="c24d6-104">**Setting up DLP**</span></span>

<span data-ttu-id="c24d6-105">Da li imate problema sa **sprečavanjem gubitka podataka (DLP)** u sistemu Office 365 ne radi na očekivani način?</span><span class="sxs-lookup"><span data-stu-id="c24d6-105">Are you having problems with **Data Loss Prevention (DLP)** in Office 365 not working as expected?</span></span> <span data-ttu-id="c24d6-106">Ako je tako, uverite se da je vaša **smernica za dlp** ispravno podešena i da podaci sadrže ono što ova **smernica za dlp** traži kada se proceni.</span><span class="sxs-lookup"><span data-stu-id="c24d6-106">If so, make sure that your **DLP policy** is set up correctly, and that your data contains what the **DLP policy** is looking for when it is being evaluated.</span></span>
  
<span data-ttu-id="c24d6-107">DLP smernice vam omogućavaju da identifikujete i zaštitite osetljive informacije u vašoj organizaciji.</span><span class="sxs-lookup"><span data-stu-id="c24d6-107">DLP policies allows you to identify and protect sensitive information in your organization.</span></span> <span data-ttu-id="c24d6-108">Da biste mogli da podesite DLP smernice, koristite [ovde](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp)informacije.</span><span class="sxs-lookup"><span data-stu-id="c24d6-108">To setup DLP policies, use the information [here](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span></span>
  
 <span data-ttu-id="c24d6-109">**Koje DLP smernice traže**</span><span class="sxs-lookup"><span data-stu-id="c24d6-109">**What DLP policies look for**</span></span>
  
<span data-ttu-id="c24d6-110">Prilikom korišćenja **ugrađenih tipova informacija** u sistemu Office 365 Security i centar za usaglašenost, dlp smernice traže određene šare i elemente kada otkrivaju ove osetljive tipove.</span><span class="sxs-lookup"><span data-stu-id="c24d6-110">When using the **built-in sensitive information types** in Office 365 Security and Compliance center, DLP policies look for specific patterns and elements when detecting these sensitive types.</span></span>
  
- <span data-ttu-id="c24d6-111">**Ugrađeni tipovi osetljivih informacija**</span><span class="sxs-lookup"><span data-stu-id="c24d6-111">**Built-in Sensitive Information Types**</span></span>

    <span data-ttu-id="c24d6-112">Za informacije o ugrađenim tipovima osetljivih tipova i o tome kako izgleda DLP smernica za otkrivanje osetljivih tipova, pogledajte: [koje tipove osetljivih informacija tražite](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span><span class="sxs-lookup"><span data-stu-id="c24d6-112">For information on the built-in Sensitive types and what a DLP policy looks for when detecting the Sensitive type, see: [What the sensitive information types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span></span>

- <span data-ttu-id="c24d6-113">**Prilagođeni tipovi poverljivih informacija**</span><span class="sxs-lookup"><span data-stu-id="c24d6-113">**Custom Sensitive Information Types**</span></span>

    <span data-ttu-id="c24d6-114">Ako pokušavate da kreirate prilagođene tipove poverljivih podataka, koristite sledeći članak za informacije o tome kako da kreirate prilagođeni tip osetljive prirode: [Kreirajte prilagođeni tip poverljivih informacija](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="c24d6-114">If you are trying to create custom sensitive information types, use the following article for information on how to create a custom sensitive type: [Create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span></span>

<span data-ttu-id="c24d6-115">**Testiranje smernica za DLP**</span><span class="sxs-lookup"><span data-stu-id="c24d6-115">**Test a DLP policy**</span></span>

<span data-ttu-id="c24d6-116">Da biste testirali podatke pomoću ugrađenog ili prilagođenog tipa sa osetljivim informacijama, koristite opciju " **tip testa** " u okviru liste sa**osetljivim informacijama o** **klasifikaciji** > .</span><span class="sxs-lookup"><span data-stu-id="c24d6-116">To test your data with a built-in or custom sensitive information type, use the **Test type** option under **Classifications** > **Sensitive info types**.</span></span> <span data-ttu-id="c24d6-117">Za više informacija pogledajte odeljak [testiranje prilagođenih osetljivih tipova informacija](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span><span class="sxs-lookup"><span data-stu-id="c24d6-117">For more information, see [Test custom sensitive information types](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span></span>

 <span data-ttu-id="c24d6-118">**Izveštaje**</span><span class="sxs-lookup"><span data-stu-id="c24d6-118">**Reports**</span></span>
  
- <span data-ttu-id="c24d6-119">Dobijte osetljive podatke u vezi sa [Dlp izveštajima.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span><span class="sxs-lookup"><span data-stu-id="c24d6-119">Get sensitive data insights with [DLP Reports.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span></span>

- <span data-ttu-id="c24d6-120">Pogledajte detaljne detalje o događaju sa [izveštajem o incidentu](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span><span class="sxs-lookup"><span data-stu-id="c24d6-120">See specific details of the event with an [Incident Report](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span></span>
