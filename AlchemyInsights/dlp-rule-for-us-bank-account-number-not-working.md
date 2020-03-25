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
ms.openlocfilehash: 0b5c1fb175275028c56e47080708520fe115fb38
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932564"
---
# <a name="dlp-issues-with-us-bank-account-numbers"></a><span data-ttu-id="deaee-102">DLP problemi sa brojevima računa u banci</span><span class="sxs-lookup"><span data-stu-id="deaee-102">DLP issues with US bank account numbers</span></span>

<span data-ttu-id="deaee-103">**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini.</span><span class="sxs-lookup"><span data-stu-id="deaee-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="deaee-104">Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje.</span><span class="sxs-lookup"><span data-stu-id="deaee-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="deaee-105">U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.</span><span class="sxs-lookup"><span data-stu-id="deaee-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="deaee-106">U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici.</span><span class="sxs-lookup"><span data-stu-id="deaee-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="deaee-107">Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena.</span><span class="sxs-lookup"><span data-stu-id="deaee-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="deaee-108">Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.</span><span class="sxs-lookup"><span data-stu-id="deaee-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="deaee-109">**DLP problemi sa brojevima računa u banci**</span><span class="sxs-lookup"><span data-stu-id="deaee-109">**DLP issues with US bank account numbers**</span></span>

<span data-ttu-id="deaee-110">Da li imate problema sa **sprečavanjem gubitka podataka (DLP)** ne radi za sadržaj koji sadrži **američki broj računa u banci** kada koristite Tip informacija sa Dlp osetljivim na O365?</span><span class="sxs-lookup"><span data-stu-id="deaee-110">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US Bank Account Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="deaee-111">Ako je tako, uverite se da sadržaj sadrži potrebne informacije o onome što ova smernica za DLP traži kada se proceni.</span><span class="sxs-lookup"><span data-stu-id="deaee-111">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span>
  
<span data-ttu-id="deaee-112">Na primer, za smernice za **broj računa u banci** podešene sa nivoom pouzdanosti od 85%, sledeće se procenjuje i mora se otkriti da bi pravilo moglo da se aktivira:</span><span class="sxs-lookup"><span data-stu-id="deaee-112">For example, for a **US Bank Account Number** policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="deaee-113">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 cifara</span><span class="sxs-lookup"><span data-stu-id="deaee-113">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 digits</span></span>

- <span data-ttu-id="deaee-114">**[Šara:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 uzastopnih cifara.</span><span class="sxs-lookup"><span data-stu-id="deaee-114">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 consecutive digits.</span></span>

- <span data-ttu-id="deaee-115">**[Kontrolni zbir:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Ne, ne postoji kontrolni zbir</span><span class="sxs-lookup"><span data-stu-id="deaee-115">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span>

- <span data-ttu-id="deaee-116">**[Definicija:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** DLP politika je 75% uverena da je otkrivena ova vrsta osetljivih informacija ako u blizini od 300 karaktera:</span><span class="sxs-lookup"><span data-stu-id="deaee-116">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="deaee-117">Običan izraz Regex_usa_bank_account_number pronalazi sadržaj koji odgovara obrascu</span><span class="sxs-lookup"><span data-stu-id="deaee-117">The regular expression Regex_usa_bank_account_number finds content that matches the pattern</span></span>

  - <span data-ttu-id="deaee-118">Pronađena je ključna reč Keyword_usa_Bank_Account.</span><span class="sxs-lookup"><span data-stu-id="deaee-118">A keyword from Keyword_usa_Bank_Account is found.</span></span>

    <span data-ttu-id="deaee-119">Na primer, sledeći uzorak bi bio okidač za politiku **broja računa u banci** : provera naloga 78344011</span><span class="sxs-lookup"><span data-stu-id="deaee-119">For example, the following sample would trigger for the **US Bank Account Number** policy: Checking Account 78344011</span></span>

<span data-ttu-id="deaee-120">Za više informacija o tome šta je potrebno za pronalaženje **broja računa u banci** koji će biti otkriven za vaš sadržaj pogledajte sledeći odeljak u ovom članku: [Šta osetljivi tipovi informacija traže broj računa u banci](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span><span class="sxs-lookup"><span data-stu-id="deaee-120">For more information on what is required for a **US Bank Account Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US Bank Account Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span></span>
  
<span data-ttu-id="deaee-121">Pomoću različitog ugrađenog tipa informacija pogledajte sledeći članak za informacije o tome šta je potrebno za druge tipove: [koje tipove osetljivih informacija traži](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="deaee-121">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  