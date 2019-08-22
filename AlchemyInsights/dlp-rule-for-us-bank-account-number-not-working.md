---
title: I Uroniti pravilo za nas broj računa u banci ne radi
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
ms.openlocfilehash: 0a32708b5ac8d95ec6777ada2d151a15f90d65bf
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36529895"
---
# <a name="dlp-issues-with-us-bank-account-numbers"></a><span data-ttu-id="a08d4-102">I Uroniti pitanja sa nama brojeve računa u banci</span><span class="sxs-lookup"><span data-stu-id="a08d4-102">DLP issues with US Bank Account Numbers</span></span>

<span data-ttu-id="a08d4-103">Imate li problema sa **Prevencije i gubitka podataka (Uroniti)** ne radi za sadržaj koji sadrži **Broj računa u banci AMERIČKI** kada koristite Tip osetljive informacije i Uroniti u O365?</span><span class="sxs-lookup"><span data-stu-id="a08d4-103">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US Bank Account Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="a08d4-104">Ako je tako, postarajte se da sadržaj sadrži potrebne informacije za šta je politika i Uroniti je u potrazi za kada se proceni.</span><span class="sxs-lookup"><span data-stu-id="a08d4-104">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span>
  
<span data-ttu-id="a08d4-105">Na primer, za **Broj računa u banci AMERIČKI** politiku konfigurisan sa na nivo pouzdanosti od 85%, na sledeći način se vrednuju i mora da bude otkriven pravilo će se aktivirati:</span><span class="sxs-lookup"><span data-stu-id="a08d4-105">For example, for a **US Bank Account Number** policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="a08d4-106">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 cifre</span><span class="sxs-lookup"><span data-stu-id="a08d4-106">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 digits</span></span>

- <span data-ttu-id="a08d4-107">**[Obrazac:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 uzastopnih cifre.</span><span class="sxs-lookup"><span data-stu-id="a08d4-107">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 consecutive digits.</span></span>

- <span data-ttu-id="a08d4-108">**[Kontrolni zbir:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Nema ovde nema kontrolni zbir</span><span class="sxs-lookup"><span data-stu-id="a08d4-108">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span>

- <span data-ttu-id="a08d4-109">**[Definicija:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** I Uroniti politika je 75% sigurni da je to otkrio ovu vrstu poverljive informacije ako, blizu 300 znakova:</span><span class="sxs-lookup"><span data-stu-id="a08d4-109">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="a08d4-110">Regularni izraz Regex_usa_bank_account_number pronalazi sadržaj koji odgovara uzorak</span><span class="sxs-lookup"><span data-stu-id="a08d4-110">The regular expression Regex_usa_bank_account_number finds content that matches the pattern</span></span>

  - <span data-ttu-id="a08d4-111">Nalazi se na ključnu reč iz Keyword_usa_Bank_Account.</span><span class="sxs-lookup"><span data-stu-id="a08d4-111">A keyword from Keyword_usa_Bank_Account is found.</span></span>

    <span data-ttu-id="a08d4-112">Na primer, sledeći uzorak bi izazvalo polise **AMERIČKI broj računa u banci** : tekući račun 78344011</span><span class="sxs-lookup"><span data-stu-id="a08d4-112">For example, the following sample would trigger for the **US Bank Account Number** policy: Checking Account 78344011</span></span>

<span data-ttu-id="a08d4-113">Za više informacija na ono što je neophodno za **AMERIČKI broj računa u banci** da ga otkriju za sadržaj, pogledajte sledeći odeljak u ovom članku: [Šta the osetljive tipova informacija potražite AMERIČKI broj računa u banci](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span><span class="sxs-lookup"><span data-stu-id="a08d4-113">For more information on what is required for a **US Bank Account Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US Bank Account Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span></span>
  
<span data-ttu-id="a08d4-114">Pomoću različitih ugrađenih poverljive informacije tip, pogledajte sledeći članak za informacije na ono što je neophodno za druge tipove: [Šta je osetljiva tipova informacija potražite](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="a08d4-114">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  