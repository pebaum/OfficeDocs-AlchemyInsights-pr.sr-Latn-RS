---
title: DLP pravilo za broj kreditne kartice ne radi
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1270"
- "3200001"
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: e2e93bed44749b9017dc6ff919a151d46da7a3fc
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507420"
---
# <a name="dlp-issues-with-credit-card-numbers"></a><span data-ttu-id="1e3ab-102">Problemi sa DLP-om sa brojevima kreditnih kartica</span><span class="sxs-lookup"><span data-stu-id="1e3ab-102">DLP issues with credit card numbers</span></span>

<span data-ttu-id="1e3ab-103">**Važno**: Tokom ovih jedinstvenih vremena, preduzimamo sve korake da bismo se uverili da će usluge SharePoint Online i OneDrive ostati dostupne u najvećoj meri – više informacija potražite u članku [Privremena prilagođavanja funkcija u usluzi SharePoint Online](https://aka.ms/ODSPAdjustments).</span><span class="sxs-lookup"><span data-stu-id="1e3ab-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="1e3ab-104">**Problemi sa DLP-om sa brojevima kreditnih kartica**</span><span class="sxs-lookup"><span data-stu-id="1e3ab-104">**DLP issues with credit card numbers**</span></span>

<span data-ttu-id="1e3ab-105">Da li imate problema sa **sprečavanjem gubitka podataka (DLP)** ne radi za sadržaj koji sadrži **broj kreditne kartice** kada koristite Tip informacija "Dlp" u O365?</span><span class="sxs-lookup"><span data-stu-id="1e3ab-105">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Credit Card Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="1e3ab-106">Ako je tako, uverite se da sadržaj sadrži potrebne informacije da bi se aktiviraju "DLP" smernice kada se ona proceni.</span><span class="sxs-lookup"><span data-stu-id="1e3ab-106">If so, make sure your content contains the needed information to trigger the the DLP policy when it is evaluated.</span></span> <span data-ttu-id="1e3ab-107">Na primer, za **smernice za kreditne kartice** podešene sa nivoom pouzdanosti od 85%, sledeće se procenjuje i mora se otkriti da bi pravilo moglo da se aktivira:</span><span class="sxs-lookup"><span data-stu-id="1e3ab-107">For example, for a **Credit Card policy** configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="1e3ab-108">**[Format:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-19)** 16 cifara koji može biti oblikovan ili neoblikovan (dddddddddddddd) i mora da prođe luhn test.</span><span class="sxs-lookup"><span data-stu-id="1e3ab-108">**[Format:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-19)** 16 digits which can be formatted or unformatted (dddddddddddddddd) and must pass the Luhn test.</span></span>

- <span data-ttu-id="1e3ab-109">**[Šara:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-19)** Veoma složena i robusna šara koja detektuje karte od svih vodećih brendova širom sveta, uključujući Visa, MasterCard, otkrij karticu, JCB, američki Express, poklon-kartice i karte za večeru.</span><span class="sxs-lookup"><span data-stu-id="1e3ab-109">**[Pattern:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-19)** Very complex and robust pattern that detects cards from all major brands worldwide, including Visa, MasterCard, Discover Card, JCB, American Express, gift cards, and diner cards.</span></span>

- <span data-ttu-id="1e3ab-110">**[Kontrolni zbir:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-19)** Da, "luhn kontrolni zbir"</span><span class="sxs-lookup"><span data-stu-id="1e3ab-110">**[Checksum:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-19)** Yes, the Luhn checksum</span></span>

- <span data-ttu-id="1e3ab-111">**[Definicija:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#definition-19)** DLP politika je 85% uverena da je otkrivena ova vrsta osetljivih informacija ako u blizini od 300 karaktera:</span><span class="sxs-lookup"><span data-stu-id="1e3ab-111">**[Definition:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#definition-19)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="1e3ab-112">Funkcija Func_credit_card pronalazi sadržaj koji se podudara sa obrascem.</span><span class="sxs-lookup"><span data-stu-id="1e3ab-112">The function Func_credit_card finds content that matches the pattern.</span></span>

  - <span data-ttu-id="1e3ab-113">Nešto od sledećeg je tačno:</span><span class="sxs-lookup"><span data-stu-id="1e3ab-113">One of the following is true:</span></span>

  - <span data-ttu-id="1e3ab-114">Pronađena je ključna reč Keyword_cc_verification.</span><span class="sxs-lookup"><span data-stu-id="1e3ab-114">A keyword from Keyword_cc_verification is found.</span></span>

  - <span data-ttu-id="1e3ab-115">Pronađena je ključna reč Keyword_cc_name</span><span class="sxs-lookup"><span data-stu-id="1e3ab-115">A keyword from Keyword_cc_name is found</span></span>

  - <span data-ttu-id="1e3ab-116">Funkcija Func_expiration_date pronalazi datum u formatu "pravi datum".</span><span class="sxs-lookup"><span data-stu-id="1e3ab-116">The function Func_expiration_date finds a date in the right date format.</span></span>

  - <span data-ttu-id="1e3ab-117">Kontrolni zbir prolazi</span><span class="sxs-lookup"><span data-stu-id="1e3ab-117">The checksum passes</span></span>

    <span data-ttu-id="1e3ab-118">Na primer, sledeći uzorak bi bio okidač za smernicu za brojeve sa DLP kreditnom karticom:</span><span class="sxs-lookup"><span data-stu-id="1e3ab-118">For example, the following sample would trigger for a DLP Credit Card Number Policy:</span></span>

  - <span data-ttu-id="1e3ab-119">Visa: 4485 3647 3952 7352</span><span class="sxs-lookup"><span data-stu-id="1e3ab-119">Visa: 4485 3647 3952 7352</span></span>
  
  - <span data-ttu-id="1e3ab-120">Datum isteka: 2/2009</span><span class="sxs-lookup"><span data-stu-id="1e3ab-120">Expires: 2/2009</span></span>

<span data-ttu-id="1e3ab-121">Više informacija o tome šta je potrebno da se otkrije **broj kreditne kartice** za sadržaj potražite u sledećem odeljku ovog članka: [koji tipovi osetljivih informacija traže kreditnu karticu #](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#credit-card-number)</span><span class="sxs-lookup"><span data-stu-id="1e3ab-121">For more information on what is required for a **Credit Card Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for Credit Card#](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#credit-card-number)</span></span>
  
<span data-ttu-id="1e3ab-122">Pomoću različitog ugrađenog tipa informacija pogledajte sledeći članak za informacije o tome šta je potrebno za druge tipove: [koje tipove osetljivih informacija traži](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)</span><span class="sxs-lookup"><span data-stu-id="1e3ab-122">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)</span></span>
  