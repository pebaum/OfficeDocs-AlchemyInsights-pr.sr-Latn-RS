---
title: 1491-pretraga-ne-povratak-očekivani-rezultati
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1491"
- "3200003"
ms.assetid: ''
ms.openlocfilehash: d0707af19b0299f7257a10a20ab38f47860308fb
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43709241"
---
# <a name="content-search-not-returning-expected-results"></a><span data-ttu-id="87cf2-102">Pretraga sadržaja ne vraća očekivane rezultate</span><span class="sxs-lookup"><span data-stu-id="87cf2-102">Content Search not returning expected results</span></span>

<span data-ttu-id="87cf2-103">Kada se izvršavaju pretrage sadržaja sa Microsoft 365 bezbednosnog & centra za usaglašavanje, možda ćete dobiti neočekivane rezultate pretrage.</span><span class="sxs-lookup"><span data-stu-id="87cf2-103">When running Content Searches from the Microsoft 365 security & Compliance Center, you may receive unexpected search results.</span></span> <span data-ttu-id="87cf2-104">Razmotrite sledeće radnje koje mogu da utiču na rezultate pretrage:</span><span class="sxs-lookup"><span data-stu-id="87cf2-104">Consider the following things that can affect your search results:</span></span>

- <span data-ttu-id="87cf2-105">**Lokacije sadržaja i uslovi pretraživanja**: proverite da li ste izabrali odgovarajuće lokacije sadržaja i uslove pretrage.</span><span class="sxs-lookup"><span data-stu-id="87cf2-105">**Content locations and search conditions**: Make sure you have selected the proper content locations and search conditions.</span></span> <span data-ttu-id="87cf2-106">Ako ste pokrenuli veliku pretragu (sa mnogim lokacijama), razmislite o tome da je razdelite u više pretraga.</span><span class="sxs-lookup"><span data-stu-id="87cf2-106">If you ran a large search (with many locations), consider splitting it into multiple searches.</span></span>

- <span data-ttu-id="87cf2-107">**Delimično indeksirane stavke**: [delimično indeksirane stavke](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) iz poštanskih sandučića su uključene u procenjene rezultate pretrage.</span><span class="sxs-lookup"><span data-stu-id="87cf2-107">**Partially indexed items**:  [Partially indexed items](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) from mailboxes are included in the estimated search results.</span></span> <span data-ttu-id="87cf2-108">Međutim, delimično indeksirane stavke sa lokacija u sistemu SharePoint i OneDrive nisu uključene u procenu pretrage.</span><span class="sxs-lookup"><span data-stu-id="87cf2-108">However, partially indexed items from sites in SharePoint and OneDrive aren't included in the search estimate.</span></span>

- <span data-ttu-id="87cf2-109">**Otkazivanja pretrage**: prilikom pretraživanja velikog broja poštanskih sandučića (preko 100.000 poštanskih sandučića), možda ćete dobiti greške pri pretraživanju, uz kodove grešaka kao što su CS008-009 i CS012-002).</span><span class="sxs-lookup"><span data-stu-id="87cf2-109">**Search failures**: When searching a large number of mailboxes (over 100,000 mailboxes), you may get search errors, with error codes such as CS008-009 and CS012-002).</span></span> <span data-ttu-id="87cf2-110">U ovom slučaju, pokušajte da pretražite samo za neuspele lokacije sadržaja.</span><span class="sxs-lookup"><span data-stu-id="87cf2-110">In this case, retry the search only for the failed content locations.</span></span> <span data-ttu-id="87cf2-111">Više informacija potražite u [ovom članku](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) .</span><span class="sxs-lookup"><span data-stu-id="87cf2-111">See  [this article](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) for more information.</span></span>
