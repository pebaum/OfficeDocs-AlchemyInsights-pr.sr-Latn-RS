---
title: 1491-Search-not-returning-expected-Results
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1491"
- "3200003"
ms.assetid: ''
ms.openlocfilehash: 094da9d75013aae56ca219b7ae03e85736ce5ee0
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36551429"
---
# <a name="content-search-not-returning-expected-results"></a><span data-ttu-id="a0806-102">Sadržaja pretrage ne daje očekivane rezultate</span><span class="sxs-lookup"><span data-stu-id="a0806-102">Content Search not returning expected results</span></span>

<span data-ttu-id="a0806-103">Pri pokretanju sadržaja pretrage iz Office 365 bezbednosti & usklađenosti Center, možda ćete dobiti neočekivane rezultate.</span><span class="sxs-lookup"><span data-stu-id="a0806-103">When running Content Searches from the Office 365 Security & Compliance Center, you may receive unexpected search results.</span></span> <span data-ttu-id="a0806-104">Razmotrite sledeće stvari koje mogu da utiču na rezultate pretrage:</span><span class="sxs-lookup"><span data-stu-id="a0806-104">Consider the following things that can affect your search results:</span></span>

- <span data-ttu-id="a0806-105">**Sadržaja lokacije i uslove pretrage**: proverite da li ste izabrali odgovarajući sadržaj lokacije i pretražite uslove.</span><span class="sxs-lookup"><span data-stu-id="a0806-105">**Content locations and search conditions**: Make sure you have selected the proper content locations and search conditions.</span></span> <span data-ttu-id="a0806-106">Ako ste pokrenuli veliku potragu (sa više lokacija), Smatraj to razdvajanje u više pretraga.</span><span class="sxs-lookup"><span data-stu-id="a0806-106">If you ran a large search (with many locations), consider splitting it into multiple searches.</span></span>

- <span data-ttu-id="a0806-107">**Delimično indeksirane stavke**: [delimično indeksirane stavke](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) iz Poštanske sandučiće nalaze se u rezultatima pretrage otprilike.</span><span class="sxs-lookup"><span data-stu-id="a0806-107">**Partially indexed items**:  [Partially indexed items](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) from mailboxes are included in the estimated search results.</span></span> <span data-ttu-id="a0806-108">Međutim, delimično indeksirane stavke sa lokacija u SharePoint i OneDrive nisu uključene u pretrage procena.</span><span class="sxs-lookup"><span data-stu-id="a0806-108">However, partially indexed items from sites in SharePoint and OneDrive aren't included in the search estimate.</span></span>

- <span data-ttu-id="a0806-109">**Pretraživanje otkazivanja**: prilikom pretraživanja velikog broja poštanskih sandučića (preko 100 000 poštanskih sandučića), možda dobijete pretragu grešaka, sa kodovima greške kao što su CS008-009 i CS012-002).</span><span class="sxs-lookup"><span data-stu-id="a0806-109">**Search failures**: When searching a large number of mailboxes (over 100,000 mailboxes), you may get search errors, with error codes such as CS008-009 and CS012-002).</span></span> <span data-ttu-id="a0806-110">U ovom slučaju, ponovo pokušajte pretragu samo za propali sadržaja lokacije.</span><span class="sxs-lookup"><span data-stu-id="a0806-110">In this case, retry the search only for the failed content locations.</span></span> <span data-ttu-id="a0806-111">Pogledajte [Ovaj članak](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) za više informacija.</span><span class="sxs-lookup"><span data-stu-id="a0806-111">See  [this article](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) for more information.</span></span>
