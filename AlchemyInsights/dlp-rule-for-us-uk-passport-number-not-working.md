---
title: I Uroniti pravilo za U.S. / broj pasoša UK ne radi
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: bb80ef07364a575f6032bb105cff83cd8f95bd63
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32404395"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a><span data-ttu-id="ba359-102">Problemi sa Dip - U.S. / UK brojeve pasoša</span><span class="sxs-lookup"><span data-stu-id="ba359-102">Problems with DLP - US/UK Passport Numbers</span></span>

<span data-ttu-id="ba359-103">Imate li problema sa **Prevencije i gubitka podataka (Uroniti)** ne radi za sadržaja koji sadrži i **U.S. / broj pasoša UK** kada koristite Tip osetljive informacije i Uroniti u O365?</span><span class="sxs-lookup"><span data-stu-id="ba359-103">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US/UK Passport Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="ba359-104">Ako je tako, postarajte se da sadržaj sadrži potrebne informacije za šta je politika i Uroniti je u potrazi za kada se proceni.</span><span class="sxs-lookup"><span data-stu-id="ba359-104">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span> 
  
<span data-ttu-id="ba359-105">Na primer, za za **U.S. / broj pasoša UK** politiku konfigurisan sa na nivo pouzdanosti od 75%, na sledeći način se vrednuju i mora da bude otkriven pravilo će se aktivirati</span><span class="sxs-lookup"><span data-stu-id="ba359-105">For example, for a **US/UK Passport Number** policy configured with a confidence level of 75%, the following are evaluated and must be detected for the rule to trigger</span></span> 
  
- <span data-ttu-id="ba359-106">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Devet cifara</span><span class="sxs-lookup"><span data-stu-id="ba359-106">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Nine digits</span></span> 
    
- <span data-ttu-id="ba359-107">**[Obrazac:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Devet uzastopnih cifara</span><span class="sxs-lookup"><span data-stu-id="ba359-107">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Nine consecutive digits</span></span> 
    
- <span data-ttu-id="ba359-108">**[Kontrolni zbir:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Nema ovde nema kontrolni zbir</span><span class="sxs-lookup"><span data-stu-id="ba359-108">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span> 
    
- <span data-ttu-id="ba359-109">**[Definicija:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** I Uroniti politika je 75% sigurni da je to otkrio ovu vrstu poverljive informacije ako, blizu 300 znakova:</span><span class="sxs-lookup"><span data-stu-id="ba359-109">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span> 
    
  - <span data-ttu-id="ba359-110">Funkcija Func_usa_uk_passport pronalazi sadržaj koji odgovara obrazac.</span><span class="sxs-lookup"><span data-stu-id="ba359-110">The function Func_usa_uk_passport finds content that matches the pattern.</span></span>
    
  - <span data-ttu-id="ba359-111">Nalazi se na ključnu reč iz Keyword_passport.</span><span class="sxs-lookup"><span data-stu-id="ba359-111">A keyword from Keyword_passport is found.</span></span>
    
    <span data-ttu-id="ba359-112">Na primer, sledeći uzorak bi izazvalo za u **U.S. / broj pasoša UK** politiku: američki pasoš broj 123456789</span><span class="sxs-lookup"><span data-stu-id="ba359-112">For example, the following sample would trigger for the **US/UK Passport Number** policy: U.S. Passport number 123456789</span></span> 
    
<span data-ttu-id="ba359-113">Za više informacija o tome šta je potrebno za savezni / broj pasoša UK bila otkrivena za sadržaj, pogledajte sledeći odeljak u ovom članku: [Vidi šta je osetljiva tipova informacija za U.S. / broj pasoša UK](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span><span class="sxs-lookup"><span data-stu-id="ba359-113">For more information on what is required for a US/UK Passport Number to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US/UK Passport Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span></span>
  
<span data-ttu-id="ba359-114">Pomoću različitih ugrađenih poverljive informacije tip, pogledajte sledeći članak za informacije na ono što je neophodno za druge tipove: [Šta je osetljiva tipova informacija potražite](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="ba359-114">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  

