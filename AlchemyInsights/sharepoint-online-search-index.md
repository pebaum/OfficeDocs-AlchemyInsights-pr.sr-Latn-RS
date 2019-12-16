---
title: Pretraga u sistemu SharePoint online
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: c4ff98f0cf928834c803542340b32da15a40d583
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40044057"
---
# <a name="content-crawling-and-indexing-in-sharepoint-online"></a><span data-ttu-id="c52bb-102">Popisivanje i indeksiranje sadržaja u sistemu SharePoint online</span><span class="sxs-lookup"><span data-stu-id="c52bb-102">Content crawling and indexing in SharePoint Online</span></span>

<span data-ttu-id="c52bb-103">Sadržaj mora biti popisan i dodat indeksu pretrage da bi korisnici pronašli ono što traže u sistemu SharePoint online.</span><span class="sxs-lookup"><span data-stu-id="c52bb-103">Content must be crawled and added to the search index for users to find what they're searching for in SharePoint Online.</span></span> <span data-ttu-id="c52bb-104">Sadržaj se automatski popisuje na osnovu unapred definisanog rasporeda popisivanja (raspored popisivanja ne može biti promenjen).</span><span class="sxs-lookup"><span data-stu-id="c52bb-104">Content is automatically crawled based on a pre-defined crawl schedule (the crawl schedule cannot be changed).</span></span> <span data-ttu-id="c52bb-105">Pauk bira sadržaj koji se promenio od poslednjeg popisivanja i ažurira indeks.</span><span class="sxs-lookup"><span data-stu-id="c52bb-105">The crawler picks up content that has changed since the last crawl and updates the index.</span></span> <span data-ttu-id="c52bb-106">Da biste se uverili da je sadržaj popisan, a indeks ažuriran, imajte na umu sledeće:</span><span class="sxs-lookup"><span data-stu-id="c52bb-106">To ensure content is crawled and the index is updated, note the following:</span></span>

- <span data-ttu-id="c52bb-107">Uverite se da sadržaj možete pronaći tako što ćete [izvršiti pretraživo sadržaj lokacije](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span><span class="sxs-lookup"><span data-stu-id="c52bb-107">Make sure content can be found by [making site content searchable](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span></span>

- <span data-ttu-id="c52bb-108">Kada promenite upravljano svojstvo ili kada ste promenili mapiranje popisanih i upravljanih svojstava, lokacija mora biti ponovo popisana pre nego što se promene odraze u indeks pretrage.</span><span class="sxs-lookup"><span data-stu-id="c52bb-108">When you have changed a managed property, or when you have changed the mapping of crawled and managed properties, the site must be re-crawled before your changes will be reflected in the search index.</span></span> 

    <span data-ttu-id="c52bb-109">Pošto su promene napravljene u šemi pretrage, a ne na trenutnoj lokaciji, pauk neće automatski ponovo indeksirati lokaciju.</span><span class="sxs-lookup"><span data-stu-id="c52bb-109">Because your changes are made in the search schema, and not to the actual site, the crawler will not automatically re-index the site.</span></span> 

    <span data-ttu-id="c52bb-110">Više informacija potražite u članku [ručno traženje popisivanja i ponovno indeksiranje lokacije, biblioteke ili liste](https://docs.microsoft.com/sharepoint/crawl-site-conten).</span><span class="sxs-lookup"><span data-stu-id="c52bb-110">For more info, see [Manually request crawling and re-indexing of a site, a library or a list](https://docs.microsoft.com/sharepoint/crawl-site-conten).</span></span>

- <span data-ttu-id="c52bb-111">Sačekajte najmanje 24 časa nakon što ručno zahtevate popisivanje i kompletan reindeks da biste videli da li i dalje dolazi do problema.</span><span class="sxs-lookup"><span data-stu-id="c52bb-111">Wait at least 24 hours after manually requesting a crawl and full re-index to see if you're still experiencing an issue.</span></span> 

    <span data-ttu-id="c52bb-112">Ako je prošlo više od 24 časa od kada ste pokrenuli popisivanje i puni ponovo indeks, evidentirali ste predmet podrške.</span><span class="sxs-lookup"><span data-stu-id="c52bb-112">If more than 24 hours have passed since you initiated the crawl and full re-index, please log a support case.</span></span> <span data-ttu-id="c52bb-113">U mnogim slučajevima već radimo na rešenju.</span><span class="sxs-lookup"><span data-stu-id="c52bb-113">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="c52bb-114">Molimo vas da nam date najmanje 24 sata da završimo rešenje.</span><span class="sxs-lookup"><span data-stu-id="c52bb-114">Please give us at least 24 hours to complete a solution.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="c52bb-115">Ako je lokacija, dokument (biblioteka) ili lista izbrisana, a i dalje prikazana u rezultatima pretrage, korisnici bi trebalo da dobiju **grešku 404 datoteku koja nije pronađena** kada pokušate da joj pristupite.</span><span class="sxs-lookup"><span data-stu-id="c52bb-115">If a site, document (library), or a list was deleted and still shows in the search results, users should receive an **Error 404 File Not Found** when trying to access it.</span></span> <span data-ttu-id="c52bb-116">Ovaj problem bi trebalo da bude evidentiran kao predmet podrške za dalju istragu.</span><span class="sxs-lookup"><span data-stu-id="c52bb-116">This issue should be logged as a support case for further investigation.</span></span> 



