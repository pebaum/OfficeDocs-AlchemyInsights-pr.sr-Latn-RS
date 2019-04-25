---
title: I Uroniti pravilo za broj kreditne kartice ne radi
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: e1d60c493a27efb7f724d57051e21fad5bd0242f
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32404536"
---
<span data-ttu-id="2485d-102">Imate li problema sa **Prevencije i gubitka podataka (Uroniti)** ne radi za sadržaj koji sadrži **Broj kreditne kartice** kada koristite Tip osetljive informacije i Uroniti u O365?</span><span class="sxs-lookup"><span data-stu-id="2485d-102">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Credit Card Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="2485d-103">Ako je tako, uverite se da vaš sadržaj sadrži potrebne informacije da izazovu u Dip politike kada se proceni.</span><span class="sxs-lookup"><span data-stu-id="2485d-103">If so, make sure your content contains the needed information to trigger the the DLP policy when it is evaluated.</span></span> <span data-ttu-id="2485d-104">Na primer, za **kreditnu karticu politiku** konfigurisan sa na nivo pouzdanosti od 85%, na sledeći način se vrednuju i mora da bude otkriven pravilo će se aktivirati:</span><span class="sxs-lookup"><span data-stu-id="2485d-104">For example, for a **Credit Card policy** configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span> 
  
- <span data-ttu-id="2485d-105">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 brojeva, koja može da bude oblikovan ili neoblikovan (dddddddddddddddd) i mora proći Luhn test.</span><span class="sxs-lookup"><span data-stu-id="2485d-105">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 digits which can be formatted or unformatted (dddddddddddddddd) and must pass the Luhn test.</span></span> 
    
- <span data-ttu-id="2485d-106">**[Obrazac:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Vrlo složen i robustan šare koje otkrije karte iz svih glavnih brendova širom sveta, uključujući Visa, Mastercard, Carda, JCB CARDS, American Express, poklon kartice i restoranu karte.</span><span class="sxs-lookup"><span data-stu-id="2485d-106">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Very complex and robust pattern that detects cards from all major brands worldwide, including Visa, MasterCard, Discover Card, JCB, American Express, gift cards, and diner cards.</span></span> 
    
- <span data-ttu-id="2485d-107">**[Kontrolni zbir:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Da, na Luhn kontrolni zbir</span><span class="sxs-lookup"><span data-stu-id="2485d-107">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Yes, the Luhn checksum</span></span> 
    
- <span data-ttu-id="2485d-108">**[Definicija:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** I Uroniti politika je 85% sigurni da je to otkrio ovu vrstu poverljive informacije ako, blizu 300 znakova:</span><span class="sxs-lookup"><span data-stu-id="2485d-108">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span> 
    
  - <span data-ttu-id="2485d-109">Funkcija Func_credit_card pronalazi sadržaj koji odgovara obrazac.</span><span class="sxs-lookup"><span data-stu-id="2485d-109">The function Func_credit_card finds content that matches the pattern.</span></span>
    
  - <span data-ttu-id="2485d-110">Je jedan od sledećih:</span><span class="sxs-lookup"><span data-stu-id="2485d-110">One of the following is true:</span></span> 
    
  - <span data-ttu-id="2485d-111">Nalazi se na ključnu reč iz Keyword_cc_verification.</span><span class="sxs-lookup"><span data-stu-id="2485d-111">A keyword from Keyword_cc_verification is found.</span></span>
    
  - <span data-ttu-id="2485d-112">Ključne reči iz Keyword_cc_name je našao.</span><span class="sxs-lookup"><span data-stu-id="2485d-112">A keyword from Keyword_cc_name is found</span></span>
    
  - <span data-ttu-id="2485d-113">Funkcija Func_expiration_date pronalazi datum u formatu datuma u pravu.</span><span class="sxs-lookup"><span data-stu-id="2485d-113">The function Func_expiration_date finds a date in the right date format.</span></span>
    
  - <span data-ttu-id="2485d-114">Kontrolni zbir prolazima</span><span class="sxs-lookup"><span data-stu-id="2485d-114">The checksum passes</span></span>
    
    <span data-ttu-id="2485d-115">Na primer, sledeći uzorak bi izazvalo Dip politici broj kreditne kartice:</span><span class="sxs-lookup"><span data-stu-id="2485d-115">For example, the following sample would trigger for a DLP Credit Card Number Policy:</span></span>
    
  - <span data-ttu-id="2485d-116">Viza: 4485 3647 3952 7352</span><span class="sxs-lookup"><span data-stu-id="2485d-116">Visa: 4485 3647 3952 7352</span></span> 
    
  - <span data-ttu-id="2485d-117">Ističe: 2/2009</span><span class="sxs-lookup"><span data-stu-id="2485d-117">Expires: 2/2009</span></span>
    
<span data-ttu-id="2485d-118">Za više informacija na ono što je neophodno za **Broj kreditne kartice** da ga otkriju za sadržaj, pogledajte sledeći odeljak u ovom članku: [Šta the osetljive tipova informacija potražite kreditnu karticu #](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span><span class="sxs-lookup"><span data-stu-id="2485d-118">For more information on what is required for a **Credit Card Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for Credit Card#](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span></span>
  
<span data-ttu-id="2485d-119">Pomoću različitih ugrađenih poverljive informacije tip, pogledajte sledeći članak za informacije na ono što je neophodno za druge tipove: [Šta je osetljiva tipova informacija potražite](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="2485d-119">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  

