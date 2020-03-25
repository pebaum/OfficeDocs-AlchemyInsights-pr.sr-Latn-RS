---
title: DLP pravilo za broj kreditne kartice ne radi
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1270"
- "3200001"
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: 6b28534d072c024a98a9b05f6cb55bfdc3435db6
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932457"
---
# <a name="dlp-issues-with-credit-card-numbers"></a><span data-ttu-id="a99ed-102">Problemi sa DLP-om sa brojevima kreditnih kartica</span><span class="sxs-lookup"><span data-stu-id="a99ed-102">DLP issues with credit card numbers</span></span>

<span data-ttu-id="a99ed-103">**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini.</span><span class="sxs-lookup"><span data-stu-id="a99ed-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="a99ed-104">Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje.</span><span class="sxs-lookup"><span data-stu-id="a99ed-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="a99ed-105">U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.</span><span class="sxs-lookup"><span data-stu-id="a99ed-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="a99ed-106">U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici.</span><span class="sxs-lookup"><span data-stu-id="a99ed-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="a99ed-107">Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena.</span><span class="sxs-lookup"><span data-stu-id="a99ed-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="a99ed-108">Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.</span><span class="sxs-lookup"><span data-stu-id="a99ed-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="a99ed-109">**Problemi sa DLP-om sa brojevima kreditnih kartica**</span><span class="sxs-lookup"><span data-stu-id="a99ed-109">**DLP issues with credit card numbers**</span></span>

<span data-ttu-id="a99ed-110">Da li imate problema sa **sprečavanjem gubitka podataka (DLP)** ne radi za sadržaj koji sadrži **broj kreditne kartice** kada koristite Tip informacija "Dlp" u O365?</span><span class="sxs-lookup"><span data-stu-id="a99ed-110">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Credit Card Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="a99ed-111">Ako je tako, uverite se da sadržaj sadrži potrebne informacije da bi se aktiviraju "DLP" smernice kada se ona proceni.</span><span class="sxs-lookup"><span data-stu-id="a99ed-111">If so, make sure your content contains the needed information to trigger the the DLP policy when it is evaluated.</span></span> <span data-ttu-id="a99ed-112">Na primer, za **smernice za kreditne kartice** podešene sa nivoom pouzdanosti od 85%, sledeće se procenjuje i mora se otkriti da bi pravilo moglo da se aktivira:</span><span class="sxs-lookup"><span data-stu-id="a99ed-112">For example, for a **Credit Card policy** configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="a99ed-113">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 cifara koji može biti oblikovan ili neoblikovan (dddddddddddddd) i mora da prođe luhn test.</span><span class="sxs-lookup"><span data-stu-id="a99ed-113">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 digits which can be formatted or unformatted (dddddddddddddddd) and must pass the Luhn test.</span></span>

- <span data-ttu-id="a99ed-114">**[Šara:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Veoma složena i robusna šara koja detektuje karte od svih vodećih brendova širom sveta, uključujući Visa, MasterCard, otkrij karticu, JCB, američki Express, poklon-kartice i karte za večeru.</span><span class="sxs-lookup"><span data-stu-id="a99ed-114">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Very complex and robust pattern that detects cards from all major brands worldwide, including Visa, MasterCard, Discover Card, JCB, American Express, gift cards, and diner cards.</span></span>

- <span data-ttu-id="a99ed-115">**[Kontrolni zbir:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Da, "luhn kontrolni zbir"</span><span class="sxs-lookup"><span data-stu-id="a99ed-115">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Yes, the Luhn checksum</span></span>

- <span data-ttu-id="a99ed-116">**[Definicija:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** DLP politika je 85% uverena da je otkrivena ova vrsta osetljivih informacija ako u blizini od 300 karaktera:</span><span class="sxs-lookup"><span data-stu-id="a99ed-116">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="a99ed-117">Funkcija Func_credit_card pronalazi sadržaj koji se podudara sa obrascem.</span><span class="sxs-lookup"><span data-stu-id="a99ed-117">The function Func_credit_card finds content that matches the pattern.</span></span>

  - <span data-ttu-id="a99ed-118">Nešto od sledećeg je tačno:</span><span class="sxs-lookup"><span data-stu-id="a99ed-118">One of the following is true:</span></span>

  - <span data-ttu-id="a99ed-119">Pronađena je ključna reč Keyword_cc_verification.</span><span class="sxs-lookup"><span data-stu-id="a99ed-119">A keyword from Keyword_cc_verification is found.</span></span>

  - <span data-ttu-id="a99ed-120">Pronađena je ključna reč Keyword_cc_name</span><span class="sxs-lookup"><span data-stu-id="a99ed-120">A keyword from Keyword_cc_name is found</span></span>

  - <span data-ttu-id="a99ed-121">Funkcija Func_expiration_date pronalazi datum u formatu "pravi datum".</span><span class="sxs-lookup"><span data-stu-id="a99ed-121">The function Func_expiration_date finds a date in the right date format.</span></span>

  - <span data-ttu-id="a99ed-122">Kontrolni zbir prolazi</span><span class="sxs-lookup"><span data-stu-id="a99ed-122">The checksum passes</span></span>

    <span data-ttu-id="a99ed-123">Na primer, sledeći uzorak bi bio okidač za smernicu za brojeve sa DLP kreditnom karticom:</span><span class="sxs-lookup"><span data-stu-id="a99ed-123">For example, the following sample would trigger for a DLP Credit Card Number Policy:</span></span>

  - <span data-ttu-id="a99ed-124">Visa: 4485 3647 3952 7352</span><span class="sxs-lookup"><span data-stu-id="a99ed-124">Visa: 4485 3647 3952 7352</span></span>
  
  - <span data-ttu-id="a99ed-125">Datum isteka: 2/2009</span><span class="sxs-lookup"><span data-stu-id="a99ed-125">Expires: 2/2009</span></span>

<span data-ttu-id="a99ed-126">Više informacija o tome šta je potrebno da se otkrije **broj kreditne kartice** za sadržaj potražite u sledećem odeljku ovog članka: [koji tipovi osetljivih informacija traže kreditnu karticu #](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span><span class="sxs-lookup"><span data-stu-id="a99ed-126">For more information on what is required for a **Credit Card Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for Credit Card#](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span></span>
  
<span data-ttu-id="a99ed-127">Pomoću različitog ugrađenog tipa informacija pogledajte sledeći članak za informacije o tome šta je potrebno za druge tipove: [koje tipove osetljivih informacija traži](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="a99ed-127">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  