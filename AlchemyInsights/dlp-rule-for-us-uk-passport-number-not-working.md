---
title: DLP pravilo za nas/britanski pasoš broj ne radi
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1319"
- "3200001"
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: 9d9615eccd1e245bf4ca32742bfc64321dd7a8cf
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43715000"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a><span data-ttu-id="21f0e-102">Problemi sa DLP-US/VB Passport brojevima</span><span class="sxs-lookup"><span data-stu-id="21f0e-102">Problems with DLP - US/UK passport numbers</span></span>

<span data-ttu-id="21f0e-103">**Važno**: Tokom ovih jedinstvenih vremena, preduzimamo sve korake da bismo se uverili da će usluge SharePoint Online i OneDrive ostati dostupne u najvećoj meri – više informacija potražite u članku [Privremena prilagođavanja funkcija u usluzi SharePoint Online](https://aka.ms/ODSPAdjustments).</span><span class="sxs-lookup"><span data-stu-id="21f0e-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="21f0e-104">**DLP problemi s američkim/VB pasošima**</span><span class="sxs-lookup"><span data-stu-id="21f0e-104">**DLP issues with US/UK passport numbers**</span></span>

<span data-ttu-id="21f0e-105">Da li imate problema sa **sprečavanjem gubitka podataka (DLP)** ne radi za sadržaj koji sadrži **američki/britanski pasoš** kada se koristi tip informacija "Dlp" u O365?</span><span class="sxs-lookup"><span data-stu-id="21f0e-105">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US/UK passport number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="21f0e-106">Ako je tako, uverite se da sadržaj sadrži potrebne informacije o onome što ova smernica za DLP traži kada se proceni.</span><span class="sxs-lookup"><span data-stu-id="21f0e-106">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span>
  
<span data-ttu-id="21f0e-107">Na primer, za pravilo **broja američko/britanske pasoške** podešene sa nivoom pouzdanosti od 75%, sledeći se procenjuje i mora se otkriti da bi pravilo moglo da se aktivira</span><span class="sxs-lookup"><span data-stu-id="21f0e-107">For example, for a **US/UK passport number** policy configured with a confidence level of 75%, the following are evaluated and must be detected for the rule to trigger</span></span>
  
- <span data-ttu-id="21f0e-108">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Devet cifara</span><span class="sxs-lookup"><span data-stu-id="21f0e-108">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Nine digits</span></span>

- <span data-ttu-id="21f0e-109">**[Šara:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Devet uzastopnih cifara</span><span class="sxs-lookup"><span data-stu-id="21f0e-109">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Nine consecutive digits</span></span>

- <span data-ttu-id="21f0e-110">**[Kontrolni zbir:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Ne, ne postoji kontrolni zbir</span><span class="sxs-lookup"><span data-stu-id="21f0e-110">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span>

- <span data-ttu-id="21f0e-111">**[Definicija:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** DLP politika je 75% uverena da je otkrivena ova vrsta osetljivih informacija ako u blizini od 300 karaktera:</span><span class="sxs-lookup"><span data-stu-id="21f0e-111">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="21f0e-112">Funkcija Func_usa_uk_passport pronalazi sadržaj koji se podudara sa obrascem.</span><span class="sxs-lookup"><span data-stu-id="21f0e-112">The function Func_usa_uk_passport finds content that matches the pattern.</span></span>

  - <span data-ttu-id="21f0e-113">Pronađena je ključna reč Keyword_passport.</span><span class="sxs-lookup"><span data-stu-id="21f0e-113">A keyword from Keyword_passport is found.</span></span>

    <span data-ttu-id="21f0e-114">Na primer, sledeći uzorak će se aktivirati za politiku **broja američkih i britanskih pasoša** : američki pasoš broj 123456789</span><span class="sxs-lookup"><span data-stu-id="21f0e-114">For example, the following sample would trigger for the **US/UK passport number** policy: U.S. Passport number 123456789</span></span>

<span data-ttu-id="21f0e-115">Za više informacija o tome šta je potrebno za detekcijom AMERIČKOG/VB pasoša za vaš sadržaj, pogledajte sledeći odeljak u ovom članku: [koji tipovi osetljivih informacija traže broj US/UK](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span><span class="sxs-lookup"><span data-stu-id="21f0e-115">For more information on what is required for a US/UK Passport Number to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US/UK Passport Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span></span>
  
<span data-ttu-id="21f0e-116">Pomoću različitog ugrađenog tipa informacija pogledajte sledeći članak za informacije o tome šta je potrebno za druge tipove: [koje tipove osetljivih informacija traži](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="21f0e-116">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  