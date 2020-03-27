---
title: DLP pravilo za nas broj računa u banci ne radi
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1287"
- "3200001"
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: bb7d8ca91af73fa4ebed5992ec848128beb18830
ms.sourcegitcommit: d108a2da2f5dab05246e30b5108cca5173e09051
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/26/2020
ms.locfileid: "42977176"
---
# <a name="dlp-issues-with-us-bank-account-numbers"></a><span data-ttu-id="2b76f-102">DLP problemi sa brojevima računa u banci</span><span class="sxs-lookup"><span data-stu-id="2b76f-102">DLP issues with US bank account numbers</span></span>

<span data-ttu-id="2b76f-103">**Važno**: u ovakvim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive ostanu veoma dostupne – posetite [SharePoint online prilagođavanja](https://aka.ms/ODSPAdjustments) za više informacija.</span><span class="sxs-lookup"><span data-stu-id="2b76f-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="2b76f-104">**DLP problemi sa brojevima računa u banci**</span><span class="sxs-lookup"><span data-stu-id="2b76f-104">**DLP issues with US bank account numbers**</span></span>

<span data-ttu-id="2b76f-105">Da li imate problema sa **sprečavanjem gubitka podataka (DLP)** ne radi za sadržaj koji sadrži **američki broj računa u banci** kada koristite Tip informacija sa Dlp osetljivim na O365?</span><span class="sxs-lookup"><span data-stu-id="2b76f-105">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US Bank Account Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="2b76f-106">Ako je tako, uverite se da sadržaj sadrži potrebne informacije o onome što ova smernica za DLP traži kada se proceni.</span><span class="sxs-lookup"><span data-stu-id="2b76f-106">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span>
  
<span data-ttu-id="2b76f-107">Na primer, za smernice za **broj računa u banci** podešene sa nivoom pouzdanosti od 85%, sledeće se procenjuje i mora se otkriti da bi pravilo moglo da se aktivira:</span><span class="sxs-lookup"><span data-stu-id="2b76f-107">For example, for a **US Bank Account Number** policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="2b76f-108">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 cifara</span><span class="sxs-lookup"><span data-stu-id="2b76f-108">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 digits</span></span>

- <span data-ttu-id="2b76f-109">**[Šara:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 uzastopnih cifara.</span><span class="sxs-lookup"><span data-stu-id="2b76f-109">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 consecutive digits.</span></span>

- <span data-ttu-id="2b76f-110">**[Kontrolni zbir:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Ne, ne postoji kontrolni zbir</span><span class="sxs-lookup"><span data-stu-id="2b76f-110">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span>

- <span data-ttu-id="2b76f-111">**[Definicija:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** DLP politika je 75% uverena da je otkrivena ova vrsta osetljivih informacija ako u blizini od 300 karaktera:</span><span class="sxs-lookup"><span data-stu-id="2b76f-111">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="2b76f-112">Običan izraz Regex_usa_bank_account_number pronalazi sadržaj koji odgovara obrascu</span><span class="sxs-lookup"><span data-stu-id="2b76f-112">The regular expression Regex_usa_bank_account_number finds content that matches the pattern</span></span>

  - <span data-ttu-id="2b76f-113">Pronađena je ključna reč Keyword_usa_Bank_Account.</span><span class="sxs-lookup"><span data-stu-id="2b76f-113">A keyword from Keyword_usa_Bank_Account is found.</span></span>

    <span data-ttu-id="2b76f-114">Na primer, sledeći uzorak bi bio okidač za politiku **broja računa u banci** : provera naloga 78344011</span><span class="sxs-lookup"><span data-stu-id="2b76f-114">For example, the following sample would trigger for the **US Bank Account Number** policy: Checking Account 78344011</span></span>

<span data-ttu-id="2b76f-115">Za više informacija o tome šta je potrebno za pronalaženje **broja računa u banci** koji će biti otkriven za vaš sadržaj pogledajte sledeći odeljak u ovom članku: [Šta osetljivi tipovi informacija traže broj računa u banci](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span><span class="sxs-lookup"><span data-stu-id="2b76f-115">For more information on what is required for a **US Bank Account Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US Bank Account Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span></span>
  
<span data-ttu-id="2b76f-116">Pomoću različitog ugrađenog tipa informacija pogledajte sledeći članak za informacije o tome šta je potrebno za druge tipove: [koje tipove osetljivih informacija traži](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="2b76f-116">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  