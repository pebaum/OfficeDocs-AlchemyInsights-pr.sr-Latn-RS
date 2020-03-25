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
ms.openlocfilehash: a56e18ddadef3a2f9056978b8542c1dba8f29665
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932636"
---
# <a name="dlp-not-working-as-expected"></a><span data-ttu-id="f6e74-102">DLP ne radi na očekivani način</span><span class="sxs-lookup"><span data-stu-id="f6e74-102">DLP not working as expected</span></span>

<span data-ttu-id="f6e74-103">**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini.</span><span class="sxs-lookup"><span data-stu-id="f6e74-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="f6e74-104">Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje.</span><span class="sxs-lookup"><span data-stu-id="f6e74-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="f6e74-105">U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.</span><span class="sxs-lookup"><span data-stu-id="f6e74-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="f6e74-106">U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici.</span><span class="sxs-lookup"><span data-stu-id="f6e74-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="f6e74-107">Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena.</span><span class="sxs-lookup"><span data-stu-id="f6e74-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="f6e74-108">Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.</span><span class="sxs-lookup"><span data-stu-id="f6e74-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

 <span data-ttu-id="f6e74-109">**Podešavanje DLP-a**</span><span class="sxs-lookup"><span data-stu-id="f6e74-109">**Setting up DLP**</span></span>

<span data-ttu-id="f6e74-110">Da li imate problema sa **sprečavanjem gubitka podataka (DLP)** u sistemu Office 365 ne radi na očekivani način?</span><span class="sxs-lookup"><span data-stu-id="f6e74-110">Are you having problems with **Data Loss Prevention (DLP)** in Office 365 not working as expected?</span></span> <span data-ttu-id="f6e74-111">Ako je tako, uverite se da je vaša **smernica za dlp** ispravno podešena i da podaci sadrže ono što ova **smernica za dlp** traži kada se proceni.</span><span class="sxs-lookup"><span data-stu-id="f6e74-111">If so, make sure that your **DLP policy** is set up correctly, and that your data contains what the **DLP policy** is looking for when it is being evaluated.</span></span>
  
<span data-ttu-id="f6e74-112">DLP smernice vam omogućavaju da identifikujete i zaštitite osetljive informacije u vašoj organizaciji.</span><span class="sxs-lookup"><span data-stu-id="f6e74-112">DLP policies allows you to identify and protect sensitive information in your organization.</span></span> <span data-ttu-id="f6e74-113">Da biste mogli da podesite DLP smernice, koristite [ovde](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp)informacije.</span><span class="sxs-lookup"><span data-stu-id="f6e74-113">To setup DLP policies, use the information [here](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span></span>
  
 <span data-ttu-id="f6e74-114">**Koje DLP smernice traže**</span><span class="sxs-lookup"><span data-stu-id="f6e74-114">**What DLP policies look for**</span></span>
  
<span data-ttu-id="f6e74-115">Prilikom korišćenja **ugrađenih tipova informacija** u sistemu Office 365 Security i centar za usaglašenost, dlp smernice traže određene šare i elemente kada otkrivaju ove osetljive tipove.</span><span class="sxs-lookup"><span data-stu-id="f6e74-115">When using the **built-in sensitive information types** in Office 365 Security and Compliance center, DLP policies look for specific patterns and elements when detecting these sensitive types.</span></span>
  
- <span data-ttu-id="f6e74-116">**Ugrađeni tipovi osetljivih informacija**</span><span class="sxs-lookup"><span data-stu-id="f6e74-116">**Built-in Sensitive Information Types**</span></span>

    <span data-ttu-id="f6e74-117">Za informacije o ugrađenim tipovima osetljivih tipova i o tome kako izgleda DLP smernica za otkrivanje osetljivih tipova, pogledajte: [koje tipove osetljivih informacija tražite](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span><span class="sxs-lookup"><span data-stu-id="f6e74-117">For information on the built-in Sensitive types and what a DLP policy looks for when detecting the Sensitive type, see: [What the sensitive information types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span></span>

- <span data-ttu-id="f6e74-118">**Prilagođeni tipovi poverljivih informacija**</span><span class="sxs-lookup"><span data-stu-id="f6e74-118">**Custom Sensitive Information Types**</span></span>

    <span data-ttu-id="f6e74-119">Ako pokušavate da kreirate prilagođene tipove poverljivih podataka, koristite sledeći članak za informacije o tome kako da kreirate prilagođeni tip osetljive prirode: [Kreirajte prilagođeni tip poverljivih informacija](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="f6e74-119">If you are trying to create custom sensitive information types, use the following article for information on how to create a custom sensitive type: [Create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span></span>

<span data-ttu-id="f6e74-120">**Testiranje smernica za DLP**</span><span class="sxs-lookup"><span data-stu-id="f6e74-120">**Test a DLP policy**</span></span>

<span data-ttu-id="f6e74-121">Da biste testirali podatke pomoću ugrađenog ili prilagođenog tipa sa osetljivim informacijama, koristite opciju " **tip testa** " u okviru liste sa**osetljivim informacijama o** **klasifikaciji** > .</span><span class="sxs-lookup"><span data-stu-id="f6e74-121">To test your data with a built-in or custom sensitive information type, use the **Test type** option under **Classifications** > **Sensitive info types**.</span></span> <span data-ttu-id="f6e74-122">Za više informacija pogledajte odeljak [testiranje prilagođenih osetljivih tipova informacija](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span><span class="sxs-lookup"><span data-stu-id="f6e74-122">For more information, see [Test custom sensitive information types](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span></span>

 <span data-ttu-id="f6e74-123">**Izveštaje**</span><span class="sxs-lookup"><span data-stu-id="f6e74-123">**Reports**</span></span>
  
- <span data-ttu-id="f6e74-124">Dobijte osetljive podatke u vezi sa [Dlp izveštajima.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span><span class="sxs-lookup"><span data-stu-id="f6e74-124">Get sensitive data insights with [DLP Reports.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span></span>

- <span data-ttu-id="f6e74-125">Pogledajte detaljne detalje o događaju sa [izveštajem o incidentu](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span><span class="sxs-lookup"><span data-stu-id="f6e74-125">See specific details of the event with an [Incident Report](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span></span>
