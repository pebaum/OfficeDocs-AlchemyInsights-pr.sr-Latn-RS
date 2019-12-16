---
title: Upravljanje šemom pretrage u sistemu SharePoint online
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: 9836cf139e97fc556995a8f0ad38c51c5c2392ac
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40042977"
---
# <a name="manage-search-schema-in-sharepoint-online"></a><span data-ttu-id="548f8-102">Upravljanje šemom pretrage u sistemu SharePoint online</span><span class="sxs-lookup"><span data-stu-id="548f8-102">Manage search schema in SharePoint Online</span></span>

<span data-ttu-id="548f8-103">Šema pretraživanja kontroliše šta korisnici mogu da pretražuju, kako korisnici mogu da je pretražuju i kako možete da predstavite rezultate na Veb lokacijama pretrage.</span><span class="sxs-lookup"><span data-stu-id="548f8-103">The search schema controls what users can search for, how users can search it, and how you can present the results on your search websites.</span></span> 

<span data-ttu-id="548f8-104">Pogledajte odeljak [Upravljanje šemom pretrage u sistemu SharePoint online](https://docs.microsoft.com/sharepoint/manage-search-schema) da biste saznali kako da:</span><span class="sxs-lookup"><span data-stu-id="548f8-104">See [Manage the Search Schema in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-search-schema) to learn how to:</span></span> 
- <span data-ttu-id="548f8-105">Promenite šemu pretraživanja.</span><span class="sxs-lookup"><span data-stu-id="548f8-105">Change the search schema.</span></span>
- <span data-ttu-id="548f8-106">Kreiranje upravljanih svojstava.</span><span class="sxs-lookup"><span data-stu-id="548f8-106">Create managed properties.</span></span>
- <span data-ttu-id="548f8-107">Mapiraj popisano mapiranje popisanih svojstava u upravljana svojstva.</span><span class="sxs-lookup"><span data-stu-id="548f8-107">Map crawled map crawled properties to managed properties.</span></span>

<span data-ttu-id="548f8-108">Obratite pažnju na sledeće u vezi sa upravljanjem šemom pretrage:</span><span class="sxs-lookup"><span data-stu-id="548f8-108">Note the following in regards to managing your Search Schema:</span></span>

- <span data-ttu-id="548f8-109">Ako dobijete upozorenje u kome se navodi da **je aplikacija pauzirana** kada se promeni šema, to je samo privremeno kada je došlo do održavanja usluge.</span><span class="sxs-lookup"><span data-stu-id="548f8-109">If you receive a warning stating **the application is paused** when making a schema change, this is only temporary as there is service maintenance occurring.</span></span> 

    <span data-ttu-id="548f8-110">Ako je prošlo više od 24 časa, a vi i dalje nailazite na upozorenje, zapisujte slučaj podrške.</span><span class="sxs-lookup"><span data-stu-id="548f8-110">If more than 24 hours have passed and you still experience the warning, please log a support case.</span></span>
- <span data-ttu-id="548f8-111">Kada promenite upravljana svojstva ili dodate nove, promene će stupiti na snagu tek nakon ponovnog popisivanja sadržaja.</span><span class="sxs-lookup"><span data-stu-id="548f8-111">When you change managed properties or add new ones, the changes take effect only after the content has been re-crawled.</span></span> <span data-ttu-id="548f8-112">U sistemu SharePoint online popisivanje se automatski izvršava na osnovu definisanog rasporeda popisivanja.</span><span class="sxs-lookup"><span data-stu-id="548f8-112">In SharePoint Online, crawling happens automatically based on the defined crawl schedule.</span></span>
- <span data-ttu-id="548f8-113">Da biste se uverili da su promene popisane, možete posebno da [zatražite ponovno indeksiranje liste ili biblioteke](https://docs.microsoft.com/sharepoint/manage-search-schema#request-re-indexing-of-a-document-library-or-list)</span><span class="sxs-lookup"><span data-stu-id="548f8-113">To make sure that your changes are crawled, you can specifically [request a re-indexing of the list or library](https://docs.microsoft.com/sharepoint/manage-search-schema#request-re-indexing-of-a-document-library-or-list)</span></span> 

<span data-ttu-id="548f8-114">Potpun pregled šeme pretrage potražite u članku [Uvod u šemu pretrage](https://blogs.technet.microsoft.com/tothesharepoint/2012/11/25/introducing-search-schema-for-sharepoint-2013/)</span><span class="sxs-lookup"><span data-stu-id="548f8-114">For a complete overview of the Search Schema, see [Introducing Search Schema](https://blogs.technet.microsoft.com/tothesharepoint/2012/11/25/introducing-search-schema-for-sharepoint-2013/)</span></span> 


