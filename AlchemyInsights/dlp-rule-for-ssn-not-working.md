---
title: I Uroniti pravilo za SSN ne radi
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
ms.openlocfilehash: 757136c39700f12f40f839b29277a59b0e436f03
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36529882"
---
# <a name="dlp-issues-with-social-security-numbers"></a><span data-ttu-id="16fbc-102">I Uroniti pitanja sa brojeve socijalnog osiguranja</span><span class="sxs-lookup"><span data-stu-id="16fbc-102">DLP issues with Social Security Numbers</span></span>

<span data-ttu-id="16fbc-103">Imate li problema sa **Prevencije i gubitka podataka (Uroniti)** ne radi za sadržaj koji sadrži i **Broj socijalnog osiguranja (SSN)** kada koristite Tip poverljive informacije u Office 365?</span><span class="sxs-lookup"><span data-stu-id="16fbc-103">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Social Security Number (SSN)** when using a sensitive information type in Office 365?</span></span> <span data-ttu-id="16fbc-104">Ako je tako, uverite se da vaš sadržaj sadrži potrebne informacije za šta je politika i Uroniti u potrazi.</span><span class="sxs-lookup"><span data-stu-id="16fbc-104">If so, make sure your content contains the needed information for what the DLP policy is looking.</span></span> 
  
<span data-ttu-id="16fbc-105">Na primer, za smernice za SSN konfigurisan sa na nivo pouzdanosti od 85%, na sledeći način se vrednuju i mora da bude otkriven pravilo će se aktivirati:</span><span class="sxs-lookup"><span data-stu-id="16fbc-105">For example, for an SSN policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="16fbc-106">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 brojeva, što može biti uzorak oblikovan ili neoblikovan</span><span class="sxs-lookup"><span data-stu-id="16fbc-106">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 digits, which may be in a formatted or unformatted pattern</span></span>

- <span data-ttu-id="16fbc-107">**[Obrazac:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Četiri funkcije potražite SSNs u četiri različite obrasce:</span><span class="sxs-lookup"><span data-stu-id="16fbc-107">**[Pattern:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Four functions look for SSNs in four different patterns:</span></span>

  - <span data-ttu-id="16fbc-108">Func_ssn pronalazi SSNs sa pre-2011 jako oblikovanje koje su oblikovane pomoću crtice ili razmake (ddd-dd-dddd OR ddd dd dddd)</span><span class="sxs-lookup"><span data-stu-id="16fbc-108">Func_ssn finds SSNs with pre-2011 strong formatting that are formatted with dashes or spaces (ddd-dd-dddd OR ddd dd dddd)</span></span>

  - <span data-ttu-id="16fbc-109">Func_unformatted_ssn pronalazi SSNs sa pre-2011 jak oblikovanja koja su oblikovana kao devet uzastopnih cifre (ddddddddd)</span><span class="sxs-lookup"><span data-stu-id="16fbc-109">Func_unformatted_ssn finds SSNs with pre-2011 strong formatting that are unformatted as nine consecutive digits (ddddddddd)</span></span>

  - <span data-ttu-id="16fbc-110">Func_randomized_formatted_ssn pronalazi post-2011 SSNs koje su oblikovane pomoću crtice ili razmake (ddd-dd-dddd OR ddd dd dddd)</span><span class="sxs-lookup"><span data-stu-id="16fbc-110">Func_randomized_formatted_ssn finds post-2011 SSNs that are formatted with dashes or spaces (ddd-dd-dddd OR ddd dd dddd)</span></span>

  - <span data-ttu-id="16fbc-111">Func_randomized_unformatted_ssn pronalazi post-2011 SSNs koja su oblikovana kao devet uzastopnih cifre (ddddddddd)</span><span class="sxs-lookup"><span data-stu-id="16fbc-111">Func_randomized_unformatted_ssn finds post-2011 SSNs that are unformatted as nine consecutive digits (ddddddddd)</span></span>

- <span data-ttu-id="16fbc-112">**[Kontrolni zbir:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** Nema ovde nema kontrolni zbir</span><span class="sxs-lookup"><span data-stu-id="16fbc-112">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** No, there is no Checksum</span></span>

- <span data-ttu-id="16fbc-113">**[Definicija:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** I Uroniti politika je 85% sigurni da je to otkrio ovu vrstu poverljive informacije ako, blizu 300 znakova:</span><span class="sxs-lookup"><span data-stu-id="16fbc-113">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="16fbc-114">[Funkcija Func_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) pronalazi sadržaj koji odgovara obrazac.</span><span class="sxs-lookup"><span data-stu-id="16fbc-114">The [function Func_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) finds content that matches the pattern.</span></span>

  - <span data-ttu-id="16fbc-115">Nalazi se na ključnu reč iz [Keyword_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn) .</span><span class="sxs-lookup"><span data-stu-id="16fbc-115">A keyword from [Keyword_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn) is found.</span></span> <span data-ttu-id="16fbc-116">Primeri ključne reči uključuje: *socijalnog osiguranja socijalno osiguranje #, Šoć Sec, SSN* .</span><span class="sxs-lookup"><span data-stu-id="16fbc-116">Examples of keywords includes:  *Social Security, Social Security#, Soc Sec ,SSN*  .</span></span> <span data-ttu-id="16fbc-117">Na primer, sledeći uzorak bi izazvalo za Uroniti SSN smernice: **SSN: 489-36-8350**</span><span class="sxs-lookup"><span data-stu-id="16fbc-117">For example, the following sample would trigger for the DLP SSN policy: **SSN: 489-36-8350**</span></span>
  
<span data-ttu-id="16fbc-118">Za više informacija na ono što je neophodno za SSNs da ga otkriju za sadržaj, pogledajte sledeći odeljak u ovom članku: [Šta je osetljiva tipova informacija potražite SSNs](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)</span><span class="sxs-lookup"><span data-stu-id="16fbc-118">For more information on what is required for SSNs to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for SSNs](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)</span></span>
  
<span data-ttu-id="16fbc-119">Pomoću različitih ugrađenih poverljive informacije tip, pogledajte sledeći članak za informacije na ono što je neophodno za druge tipove: [Šta je osetljiva tipova informacija potražite](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="16fbc-119">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  