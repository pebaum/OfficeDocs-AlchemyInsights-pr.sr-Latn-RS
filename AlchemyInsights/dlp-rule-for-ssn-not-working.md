---
title: DLP pravilo za SSN ne radi
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1242"
- "3200001"
ms.assetid: ac265ee6-c946-476e-9bf0-0ea0e8adc98a
ms.openlocfilehash: 4ec0df9d4954a8c65f0c34188d285dd8cf44a4f2
ms.sourcegitcommit: d108a2da2f5dab05246e30b5108cca5173e09051
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/26/2020
ms.locfileid: "42977320"
---
# <a name="dlp-issues-with-social-security-numbers"></a><span data-ttu-id="22c7b-102">DLP problemi sa brojevima socijalnog osiguranja</span><span class="sxs-lookup"><span data-stu-id="22c7b-102">DLP issues with Social Security Numbers</span></span>

<span data-ttu-id="22c7b-103">**Važno**: u ovakvim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive ostanu veoma dostupne – posetite [SharePoint online prilagođavanja](https://aka.ms/ODSPAdjustments) za više informacija.</span><span class="sxs-lookup"><span data-stu-id="22c7b-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="22c7b-104">**DLP problemi sa SSNs**</span><span class="sxs-lookup"><span data-stu-id="22c7b-104">**DLP issues with SSNs**</span></span>

<span data-ttu-id="22c7b-105">Da li imate problema sa **sprečavanjem gubitka podataka (DLP)** ne radi za sadržaj koji sadrži **broj socijalnog osiguranja (SSN)** kada koristite Tip poverljivih informacija u sistemu Office 365?</span><span class="sxs-lookup"><span data-stu-id="22c7b-105">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Social Security Number (SSN)** when using a sensitive information type in Office 365?</span></span> <span data-ttu-id="22c7b-106">Ako je tako, uverite se da sadržaj sadrži potrebne informacije za ono što traži DLP smernice.</span><span class="sxs-lookup"><span data-stu-id="22c7b-106">If so, make sure your content contains the needed information for what the DLP policy is looking.</span></span> 
  
<span data-ttu-id="22c7b-107">Na primer, za SSN smernice koje su konfigurisane sa nivoom pouzdanosti od 85%, sledeće se procenjuje i mora se otkriti da bi pravilo moglo da se aktivira:</span><span class="sxs-lookup"><span data-stu-id="22c7b-107">For example, for an SSN policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="22c7b-108">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 cifara, koji je možda u oblikovanoj ili neformatiranom obrascu</span><span class="sxs-lookup"><span data-stu-id="22c7b-108">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 digits, which may be in a formatted or unformatted pattern</span></span>

- <span data-ttu-id="22c7b-109">**[Šara:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Četiri funkcije traže od SSNs u četiri različita modela:</span><span class="sxs-lookup"><span data-stu-id="22c7b-109">**[Pattern:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Four functions look for SSNs in four different patterns:</span></span>

  - <span data-ttu-id="22c7b-110">Func_ssn pronalazi SSNs sa unapred 2011 snažnim oblikovanjem koje su oblikovane crtica ili razmacima (DDD-dd-dddd ili DDD dd dddd)</span><span class="sxs-lookup"><span data-stu-id="22c7b-110">Func_ssn finds SSNs with pre-2011 strong formatting that are formatted with dashes or spaces (ddd-dd-dddd OR ddd dd dddd)</span></span>

  - <span data-ttu-id="22c7b-111">Func_unformatted_ssn pronalazi SSNs sa unapred 2011 jakom oblikovanjem koja nije formatirana kao devet uzastopnih cifara (ddddddddd)</span><span class="sxs-lookup"><span data-stu-id="22c7b-111">Func_unformatted_ssn finds SSNs with pre-2011 strong formatting that are unformatted as nine consecutive digits (ddddddddd)</span></span>

  - <span data-ttu-id="22c7b-112">Func_randomized_formatted_ssn pronalazi post-2011 SSNs koji su oblikovani crtica ili razmacima (DDD-dd-dddd ili DDD dd dddd)</span><span class="sxs-lookup"><span data-stu-id="22c7b-112">Func_randomized_formatted_ssn finds post-2011 SSNs that are formatted with dashes or spaces (ddd-dd-dddd OR ddd dd dddd)</span></span>

  - <span data-ttu-id="22c7b-113">Func_randomized_unformatted_ssn pronalazi post-2011 SSNs koji nisu oblikovani kao devet uzastopnih cifara (ddddddddd)</span><span class="sxs-lookup"><span data-stu-id="22c7b-113">Func_randomized_unformatted_ssn finds post-2011 SSNs that are unformatted as nine consecutive digits (ddddddddd)</span></span>

- <span data-ttu-id="22c7b-114">**[Kontrolni zbir:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** Ne, ne postoji kontrolni zbir</span><span class="sxs-lookup"><span data-stu-id="22c7b-114">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** No, there is no Checksum</span></span>

- <span data-ttu-id="22c7b-115">**[Definicija:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** DLP politika je 85% uverena da je otkrivena ova vrsta osetljivih informacija ako u blizini od 300 karaktera:</span><span class="sxs-lookup"><span data-stu-id="22c7b-115">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="22c7b-116">[Funkcija Func_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) pronalazi sadržaj koji se podudara sa obrascem.</span><span class="sxs-lookup"><span data-stu-id="22c7b-116">The [function Func_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) finds content that matches the pattern.</span></span>

  - <span data-ttu-id="22c7b-117">Pronađena je ključna reč [Keyword_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn) .</span><span class="sxs-lookup"><span data-stu-id="22c7b-117">A keyword from [Keyword_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn) is found.</span></span> <span data-ttu-id="22c7b-118">Primeri ključnih reči su: *socijalno osiguranje, socijalno osiguranje #, SPC sec, SSN* .</span><span class="sxs-lookup"><span data-stu-id="22c7b-118">Examples of keywords includes:  *Social Security, Social Security#, Soc Sec ,SSN*  .</span></span> <span data-ttu-id="22c7b-119">Na primer, sledeći uzorak bi bio okidač za DLP SSN smernicu: **SSN: 489-36-8350**</span><span class="sxs-lookup"><span data-stu-id="22c7b-119">For example, the following sample would trigger for the DLP SSN policy: **SSN: 489-36-8350**</span></span>
  
<span data-ttu-id="22c7b-120">Više informacija o tome šta je potrebno da bi se SNS detektuje za sadržaj potražite u sledećem odeljku ovog članka: [Šta osetljivi tipovi informacija traže od SNS](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)</span><span class="sxs-lookup"><span data-stu-id="22c7b-120">For more information on what is required for SSNs to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for SSNs](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)</span></span>
  
<span data-ttu-id="22c7b-121">Pomoću različitog ugrađenog tipa informacija pogledajte sledeći članak za informacije o tome šta je potrebno za druge tipove: [koje tipove osetljivih informacija traži](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="22c7b-121">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  