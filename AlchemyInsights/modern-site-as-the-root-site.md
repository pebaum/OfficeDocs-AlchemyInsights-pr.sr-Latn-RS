---
title: Moderna lokacija kao osnovna lokacija
ms.author: efrene
author: efrene
ms.audience: ITPro
ms.topic: article
ms.date: 8/7/2019
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000265"
- "1874"
ms.openlocfilehash: a3cf44d52a3948634fc0eed64c852ff17515fd9b
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/04/2019
ms.locfileid: "36753918"
---
# <a name="modern-site-as-root-site"></a><span data-ttu-id="5d616-102">Moderna lokacija kao osnovna lokacija</span><span class="sxs-lookup"><span data-stu-id="5d616-102">Modern site as root site</span></span>

<span data-ttu-id="5d616-103">Počeli smo da iskorimo novu funkciju koja će vam omogućiti da [svoju klasičnu lokaciju razmenite sa modernom lokacijom](https://docs.microsoft.com/sharepoint/modern-root-site).</span><span class="sxs-lookup"><span data-stu-id="5d616-103">We have begun to rollout a new feature that will allow you to [swap your classic site root site with a modern site](https://docs.microsoft.com/sharepoint/modern-root-site).</span></span> <span data-ttu-id="5d616-104">Koristite funkciju [Pozovi-Spoziteswap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) da biste zamenili lokaciju lokacije sa drugom lokacijom dok arhivirate originalnu lokaciju.</span><span class="sxs-lookup"><span data-stu-id="5d616-104">Use [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) to swap the location of a site with another site while archiving the original site.</span></span> <span data-ttu-id="5d616-105">Dostupna za obe strane tima (nije povezano sa grupom) i komunikaciona lokacija.</span><span class="sxs-lookup"><span data-stu-id="5d616-105">Available for both Team Site (not connected to a group) and Communication Site.</span></span>

>[!Important]
> <span data-ttu-id="5d616-106">Nemojte brisati klasičnu osnovnu lokaciju da biste kreirali modernu lokaciju za komunikaciju.</span><span class="sxs-lookup"><span data-stu-id="5d616-106">Do not delete your classic root site to create a modern Communication Site.</span></span> <span data-ttu-id="5d616-107">Microsoft ne podržava ovaj program.</span><span class="sxs-lookup"><span data-stu-id="5d616-107">This is not supported by Microsoft.</span></span> <span data-ttu-id="5d616-108">Brisanjem osnovne lokacije sve SharePoint lokacije u vašoj organizaciji neće biti moguće pristupiti svim korisnicima, dok ne vratite lokaciju ili ne kreirate novu lokaciju na istoj URL adresi.</span><span class="sxs-lookup"><span data-stu-id="5d616-108">Deleting the root site will make all SharePoint sites in your organization inaccessible to all users, until you restore the site or create a new site at the same URL.</span></span> <span data-ttu-id="5d616-109">Ovu karakteristiku ćemo komunicirati preko centra za poruke.</span><span class="sxs-lookup"><span data-stu-id="5d616-109">We’ll be communicating this feature via the message center.</span></span> <span data-ttu-id="5d616-110">Trebalo bi da očekujete da će funkcija uskoro biti uključena u vaš tenak.</span><span class="sxs-lookup"><span data-stu-id="5d616-110">You should expect the feature to be turned on in your tenant shortly.</span></span>

## <a name="known-issues-with-swapping-sites"></a><span data-ttu-id="5d616-111">Poznati problemi sa lokacijama za zamenjivanje</span><span class="sxs-lookup"><span data-stu-id="5d616-111">Known issues with swapping sites</span></span>
- <span data-ttu-id="5d616-112">Ciljna lokacija može da vrati grešku "nije pronađeno" (HTTP 404) u kratkom vremenskom periodu.</span><span class="sxs-lookup"><span data-stu-id="5d616-112">The target site may return a "not found" (HTTP 404) error for a short period of time.</span></span>
- <span data-ttu-id="5d616-113">Sadržaj će morati da se ponovo ažurira da bi se ažurirao indeks pretrage.</span><span class="sxs-lookup"><span data-stu-id="5d616-113">Content will need to be recrawled to update the search index.</span></span> <span data-ttu-id="5d616-114">Ovde nije potreban ručni korak, ovo će se automatski obaviti.</span><span class="sxs-lookup"><span data-stu-id="5d616-114">There is no manual step required here, this will be done automatically.</span></span>
- <span data-ttu-id="5d616-115">Sve što zavisi od "statičnih" veza (kao što su sinhronizacija datoteka i OneNote datoteke) biće potrebno ručno korigovati.</span><span class="sxs-lookup"><span data-stu-id="5d616-115">Anything dependent on "static" links (such as File Sync and OneNote files) will need to be manually corrected.</span></span>
- <span data-ttu-id="5d616-116">Možda će biti potrebno proveriti lokacije servera za Project da biste bili sigurni da su i dalje ispravno povezani.</span><span class="sxs-lookup"><span data-stu-id="5d616-116">Project Server sites may need to be validated to ensure that they are still associated correctly.</span></span> 
