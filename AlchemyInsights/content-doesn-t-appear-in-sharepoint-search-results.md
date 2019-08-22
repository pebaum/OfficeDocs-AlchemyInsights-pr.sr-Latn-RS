---
title: Sadržaj se ne pojavljuje u rezultatima pretraživanja za SharePoint
ms.author: tlarsen
author: tklarsen
ms.date: 1/8/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "750"
- "5300017"
ms.assetid: 693db84f-2737-4c21-b027-4ab3d121b4a8
ms.openlocfilehash: ffb6bf349f9e8c2323186a8fc3183325d1d7e1bf
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36517045"
---
# <a name="content-doesnt-appear-in-sharepoint-search-results"></a><span data-ttu-id="14cd9-102">Sadržaj se ne pojavljuje u rezultatima pretraživanja za SharePoint</span><span class="sxs-lookup"><span data-stu-id="14cd9-102">Content doesn't appear in SharePoint search results</span></span>

<span data-ttu-id="14cd9-103">Sledite ove korake za rešavanje problema kada očekivani sadržaj se ne pojavljuje u rezultatima pretrage:</span><span class="sxs-lookup"><span data-stu-id="14cd9-103">Follow these troubleshooting steps when expected content doesn't appear in search results:</span></span>
  
1. <span data-ttu-id="14cd9-104">Proverite da je na **lokaciji** koja sadrži sadržaj očekivanih postavljeno da dozvoli da se sadržaj pojavljuje u rezultatima pretraživanja.</span><span class="sxs-lookup"><span data-stu-id="14cd9-104">Check that the **site** that contains the expected content is set to allow content to appear in search results.</span></span> <span data-ttu-id="14cd9-105">Sledite korake u [Prikaži sadržaj na lokaciji u rezultatima pretrage](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-on-a-site-in-search-results).</span><span class="sxs-lookup"><span data-stu-id="14cd9-105">Follow the steps in [Show content on a site in search results](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-on-a-site-in-search-results).</span></span>

2. <span data-ttu-id="14cd9-106">Proveri da **listu** ili **biblioteku** koja sadrži očekivani sadržaj postavljen tako da dozvoljava sadržaja da se pojavljuju u rezultatima pretrage.</span><span class="sxs-lookup"><span data-stu-id="14cd9-106">Check that the **list** or **library** that contains the expected content is set to allow content to appear in search results.</span></span> <span data-ttu-id="14cd9-107">Sledite korake u [Prikaži sadržaj sa liste ili biblioteke u rezultatima pretrage](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-from-lists-or-libraries-in-search-results).</span><span class="sxs-lookup"><span data-stu-id="14cd9-107">Follow the steps in [Show content from lists or libraries in search results](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-from-lists-or-libraries-in-search-results).</span></span>

3. <span data-ttu-id="14cd9-108">Provjerite da na stranice, dokumenta ili prilagođene stranice raspored objavljuje kao na **glavnu verziju.**</span><span class="sxs-lookup"><span data-stu-id="14cd9-108">Verify that the page, document, or custom page layout is published as a **Major version.**</span></span> <span data-ttu-id="14cd9-109">Pratite korak 3 u [Pretraga ne vrati sve rezultate u SharePoint Online](https://go.microsoft.com/fwlink/?linkid=874525).</span><span class="sxs-lookup"><span data-stu-id="14cd9-109">Follow step 3 in [Search doesn't return all results in SharePoint Online](https://go.microsoft.com/fwlink/?linkid=874525).</span></span>

4. <span data-ttu-id="14cd9-110">Proverite da li korisnik ima **dozvole** za pregled sadržaja.</span><span class="sxs-lookup"><span data-stu-id="14cd9-110">Verify that the user has **permissions** to view the content.</span></span> <span data-ttu-id="14cd9-111">Sledite korake u [razumevanju nivoi dozvola u sistemu SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="14cd9-111">Follow the steps in [Understanding permission levels in SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span></span>
    
5. <span data-ttu-id="14cd9-112">Ako šemi pretraživanja je promenjen, tako što ćete dodati novo upravljano svojstvo za uređivanje upravljanog svojstva, odnosno uklanjanjem upravljanog svojstva onda zahteva puzanja i biće potrebno ponovno indeksiranje.</span><span class="sxs-lookup"><span data-stu-id="14cd9-112">If the search schema has been changed by adding a new managed property, by editing a managed property, or by removing a managed property then requesting a crawl and re-index will be required.</span></span> <span data-ttu-id="14cd9-113">**Ponovno indeksiranje** sadržaja tako što ćete pratiti korake u [ručno zatražite pretraživanje i ponovno indeksiranje lokacije, u biblioteku ili listu](https://docs.microsoft.com/sharepoint/crawl-site-content).</span><span class="sxs-lookup"><span data-stu-id="14cd9-113">**Re-index** the content by following the steps in [Manually request crawling and re-indexing of a site, a library or a list](https://docs.microsoft.com/sharepoint/crawl-site-content).</span></span> <span data-ttu-id="14cd9-114">Ovo može potrajati, čekaj 24 sata pre provere rezultate ponovo.</span><span class="sxs-lookup"><span data-stu-id="14cd9-114">This might take a while, wait 24 hours before checking the results again.</span></span>

<span data-ttu-id="14cd9-115">Za više informacija, pogledajte [Omogući sadržaj na lokaciji da budu pretražene](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span><span class="sxs-lookup"><span data-stu-id="14cd9-115">For more information, see [Enable content on a site to be searchable](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span></span> 
  
