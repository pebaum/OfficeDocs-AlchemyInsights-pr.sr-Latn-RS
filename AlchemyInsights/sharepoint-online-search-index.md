---
title: Pretraživanje na mreži u sistemu SharePoint
ms.author: efrene
author: efrene
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: 3c3f6384172b2b4d59db6059618572db11059228
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36507645"
---
# <a name="content-crawling-and-indexing-in-sharepoint-online"></a><span data-ttu-id="1111f-102">Sadržaja za pretraživanje i indeksiranje u SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1111f-102">Content crawling and indexing in SharePoint Online</span></span>

<span data-ttu-id="1111f-103">Sadržaj mora biti popisan i dodati indeks za pretraživanje korisnicima nalaženje su tražite u SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="1111f-103">Content must be crawled and added to the search index for users to find what they're searching for in SharePoint Online.</span></span> <span data-ttu-id="1111f-104">Sadržaj popisuje automatski na osnovu unapred definisanih popisivanja raspored (nije moguće promeniti raspored popisivanja).</span><span class="sxs-lookup"><span data-stu-id="1111f-104">Content is automatically crawled based on a pre-defined crawl schedule (the crawl schedule cannot be changed).</span></span> <span data-ttu-id="1111f-105">Pauk je pokupi sadržaja koji se promenio od poslednjeg popisivanja i ažurira indeks.</span><span class="sxs-lookup"><span data-stu-id="1111f-105">The crawler picks up content that has changed since the last crawl and updates the index.</span></span> <span data-ttu-id="1111f-106">Kako bi se sadržaj popisuje i ažurira indeks, obratite pažnju na sledeće:</span><span class="sxs-lookup"><span data-stu-id="1111f-106">To ensure content is crawled and the index is updated, note the following:</span></span>

- <span data-ttu-id="1111f-107">Uverite se da sadržaj možete pronaći tako [što mogu pretraživati sadržaj lokacije](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span><span class="sxs-lookup"><span data-stu-id="1111f-107">Make sure content can be found by [making site content searchable](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span></span>

- <span data-ttu-id="1111f-108">Kada promenite upravljanog svojstva ili kada promenite mapiranje od popisan i uspeo svojstva, lokacije mora biti ponovo popisanih promene će se odraziti u indeksu za pretraživanje.</span><span class="sxs-lookup"><span data-stu-id="1111f-108">When you have changed a managed property, or when you have changed the mapping of crawled and managed properties, the site must be re-crawled before your changes will be reflected in the search index.</span></span> 

    <span data-ttu-id="1111f-109">Jer tvoj promenama u šemi pretraživanja, a ne na stvarne lokacije, pauk neće automatski ponovo indeksirati na lokaciji.</span><span class="sxs-lookup"><span data-stu-id="1111f-109">Because your changes are made in the search schema, and not to the actual site, the crawler will not automatically re-index the site.</span></span> 

    <span data-ttu-id="1111f-110">Za više informacija, vidi [ručno zatražite pretraživanje i ponovno indeksiranje lokacije, u biblioteku ili listu](https://docs.microsoft.com/sharepoint/crawl-site-conten).</span><span class="sxs-lookup"><span data-stu-id="1111f-110">For more info, see [Manually request crawling and re-indexing of a site, a library or a list](https://docs.microsoft.com/sharepoint/crawl-site-conten).</span></span>

- <span data-ttu-id="1111f-111">Čekaj najmanje 24 sata nakon ručno zatražite popisivanja i pun ponovo indeksirati da vidim ako i dalje imate problem.</span><span class="sxs-lookup"><span data-stu-id="1111f-111">Wait at least 24 hours after manually requesting a crawl and full re-index to see if you're still experiencing an issue.</span></span> 

    <span data-ttu-id="1111f-112">Ako više od 24 sata je prošlo od kada si pokrenuo popisivanja i pun ponovo indeksirati, molim vas, zovite podršku slučaj.</span><span class="sxs-lookup"><span data-stu-id="1111f-112">If more than 24 hours have passed since you initiated the crawl and full re-index, please log a support case.</span></span> <span data-ttu-id="1111f-113">U mnogim slučajevima, već radimo na rešenje.</span><span class="sxs-lookup"><span data-stu-id="1111f-113">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="1111f-114">Molim vas, dajte nam barem 24 sata da biste dovršili rešenje.</span><span class="sxs-lookup"><span data-stu-id="1111f-114">Please give us at least 24 hours to complete a solution.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="1111f-115">Ako na lokaciju, dokumenta (biblioteka), ili lista je izbrisana i još uvek prikazuje u rezultatima pretraživanja, korisnici treba da dobiju neki **Greška 404 datoteka nije pronađena** pri pokušaju da joj pristupite.</span><span class="sxs-lookup"><span data-stu-id="1111f-115">If a site, document (library), or a list was deleted and still shows in the search results, users should receive an **Error 404 File Not Found** when trying to access it.</span></span> <span data-ttu-id="1111f-116">Ovaj problem bi trebalo da bude evidentirana kao predmet podršku za dalju istragu.</span><span class="sxs-lookup"><span data-stu-id="1111f-116">This issue should be logged as a support case for further investigation.</span></span> 



