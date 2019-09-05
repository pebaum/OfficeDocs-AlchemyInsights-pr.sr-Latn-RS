---
title: Razmenite klasičnu osnovnu lokaciju sa modernom lokacijom
ms.author: efrene
author: efrene
ms.date: 8/6/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000687"
- "2579"
ms.openlocfilehash: bd477d90ab7e6737aafffc57d931aad2bd0351e8
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/04/2019
ms.locfileid: "36749274"
---
# <a name="swap-your-classic-root-site-with-a-modern-site"></a><span data-ttu-id="23289-102">Razmenite klasičnu osnovnu lokaciju sa modernom lokacijom</span><span class="sxs-lookup"><span data-stu-id="23289-102">Swap your Classic root site with a Modern site</span></span>

<span data-ttu-id="23289-103">Ako je vaše okruženje podešeno pre aprila 2019, možete da promenite svoju osnovnu lokaciju na modernu lokaciju koristeći Microsoft PowerShell:</span><span class="sxs-lookup"><span data-stu-id="23289-103">If your environment was set up before April 2019, you can change your root site to a modern site by using Microsoft PowerShell:</span></span>

- <span data-ttu-id="23289-104">Ako imate drugu lokaciju koju želite da koristite kao svoju osnovnu lokaciju, možete da je zamenite [(razmenite) na osnovnoj lokaciji](https://docs.microsoft.com/sharepoint/modern-root-site) .</span><span class="sxs-lookup"><span data-stu-id="23289-104">If you have a different site that you want to use as your root site, you can replace [(swap) the root site](https://docs.microsoft.com/sharepoint/modern-root-site) with it.</span></span> 
    - <span data-ttu-id="23289-105">Koristite funkciju [Pozovi-Spoziteswap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) da biste zamenili lokaciju lokacije sa drugom lokacijom dok arhivirate originalnu lokaciju.</span><span class="sxs-lookup"><span data-stu-id="23289-105">Use [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) to swap the location of a site with another site while archiving the original site.</span></span> <span data-ttu-id="23289-106">Dostupna za obe strane tima (nije povezano sa grupom) i komunikaciona lokacija.</span><span class="sxs-lookup"><span data-stu-id="23289-106">Available for both Team Site (not connected to a group) and Communication Site.</span></span> 

- <span data-ttu-id="23289-107">Uskoro će biti uvedene dodatne mogućnosti koje će vam omogućiti da nastavite da koristite sadržaj na lokaciji, ali da tu postojeću lokaciju konvertujete na lokaciju za komunikaciju.</span><span class="sxs-lookup"><span data-stu-id="23289-107">Additional capabilities will be introduced soon that will allow you to keep using the content on the site, but convert the existing site to a communication site.</span></span> 
>[!Important]
><span data-ttu-id="23289-108">Ove mogućnosti će postepeno biti pregledano.</span><span class="sxs-lookup"><span data-stu-id="23289-108">These capabilities will be rolled out gradually.</span></span> <span data-ttu-id="23289-109">Nastavite da proveravate Office 365 centar za poruke da biste dobili ispravke.</span><span class="sxs-lookup"><span data-stu-id="23289-109">Continue to check the Office 365 Message Center for updates.</span></span> 

## <a name="known-issues-with-swapping-sites"></a><span data-ttu-id="23289-110">Poznati problemi sa lokacijama za zamenjivanje</span><span class="sxs-lookup"><span data-stu-id="23289-110">Known issues with swapping sites</span></span>

- <span data-ttu-id="23289-111">Ciljna lokacija može da vrati grešku "nije pronađeno" (HTTP 404) u kratkom vremenskom periodu.</span><span class="sxs-lookup"><span data-stu-id="23289-111">The target site may return a "not found" (HTTP 404) error for a short period of time.</span></span>
- <span data-ttu-id="23289-112">Sadržaj će morati da se ponovo ažurira da bi se ažurirao indeks pretrage.</span><span class="sxs-lookup"><span data-stu-id="23289-112">Content will need to be recrawled to update the search index.</span></span> <span data-ttu-id="23289-113">Nema potrebnog ručnog koraka-to će se uraditi automatski.</span><span class="sxs-lookup"><span data-stu-id="23289-113">There is no manual step required - this will be done automatically.</span></span>
- <span data-ttu-id="23289-114">Sve što zavisi od "statičnih" veza (kao što su sinhronizacija datoteka i OneNote datoteke) biće potrebno ručno korigovati.</span><span class="sxs-lookup"><span data-stu-id="23289-114">Anything dependent on "static" links (such as File Sync and OneNote files) will need to be manually corrected.</span></span>
- <span data-ttu-id="23289-115">Ako je izvorna lokacija bila lokacija za organizacione vesti, ažurirajte URL adresu.</span><span class="sxs-lookup"><span data-stu-id="23289-115">If the source site was an organizational news site, update the URL.</span></span><span data-ttu-id="23289-116">Nabavite listu svih lokacija organizacionih vesti.</span><span class="sxs-lookup"><span data-stu-id="23289-116"> Get a list of all organizational news sites.</span></span>
- <span data-ttu-id="23289-117">Možda će biti potrebno proveriti lokacije servera za Project da biste bili sigurni da su i dalje ispravno povezani.</span><span class="sxs-lookup"><span data-stu-id="23289-117">Project Server sites may need to be validated to ensure that they are still associated correctly.</span></span>





