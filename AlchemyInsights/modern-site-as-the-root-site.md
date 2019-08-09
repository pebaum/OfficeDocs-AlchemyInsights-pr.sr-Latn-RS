---
title: Moderna lokaciju kao osnovne lokacije
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
ms.openlocfilehash: 260048db6c439183da8e0bb0c2dfa3c7475fca79
ms.sourcegitcommit: 631e527967f4d641bc9227642ffe38967ae87a00
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/09/2019
ms.locfileid: "36269390"
---
# <a name="modern-site-as-root-site"></a><span data-ttu-id="4eec4-102">Moderna lokaciju kao osnovna lokacija</span><span class="sxs-lookup"><span data-stu-id="4eec4-102">Modern site as root site</span></span>

<span data-ttu-id="4eec4-103">Počele smo da bizarnom novu opciju koja će vam omogućiti da razmenite svoje klasične lokacije osnovna lokacija uz modernu lokaciju.</span><span class="sxs-lookup"><span data-stu-id="4eec4-103">We have begun to rollout a new feature that will allow you to swap your classic site root site with a modern site.</span></span> <span data-ttu-id="4eec4-104">Koristite [Invoke-SPSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) da razmenite adresu lokacije sa neke druge lokacije tokom arhiviranja originalne lokacije.</span><span class="sxs-lookup"><span data-stu-id="4eec4-104">Use [Invoke-SPSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) to swap the location of a site with another site while archiving the original site.</span></span> <span data-ttu-id="4eec4-105">Dostupno za lokaciju tima (nije povezan sa grupom), kao i komunikacija lokacije.</span><span class="sxs-lookup"><span data-stu-id="4eec4-105">Available for both Team Site (not connected to a group) and Communication Site.</span></span> 

>[!Important]
> <span data-ttu-id="4eec4-106">Nemojte brisati svoje klasične osnovne lokacije da biste kreirali lokaciju moderne komunikacije.</span><span class="sxs-lookup"><span data-stu-id="4eec4-106">Do not delete your classic root site to create a modern Communication Site.</span></span> <span data-ttu-id="4eec4-107">Ovo je Microsoft ne podržava.</span><span class="sxs-lookup"><span data-stu-id="4eec4-107">This is not supported by Microsoft.</span></span> <span data-ttu-id="4eec4-108">Brisanje osnovne lokacije će da sve SharePoint lokacije u vašoj organizaciji može pristupiti svim korisnicima, dok ne vraćanje lokacije ili da kreirate novu lokaciju na istom URL adresi.</span><span class="sxs-lookup"><span data-stu-id="4eec4-108">Deleting the root site will make all SharePoint sites in your organization inaccessible to all users, until you restore the site or create a new site at the same URL.</span></span> <span data-ttu-id="4eec4-109">Komuniciramo ovu funkciju putem poruka centar.</span><span class="sxs-lookup"><span data-stu-id="4eec4-109">We’ll be communicating this feature via the message center.</span></span> <span data-ttu-id="4eec4-110">Možete očekivati funkcija biti uključena u tvojim podstanarom ubrzo.</span><span class="sxs-lookup"><span data-stu-id="4eec4-110">You should expect the feature to be turned on in your tenant shortly.</span></span>

## <a name="known-issues-with-swapping-sites"></a><span data-ttu-id="4eec4-111">Poznati problemi sa zamenjivanje lokacije</span><span class="sxs-lookup"><span data-stu-id="4eec4-111">Known issues with swapping sites</span></span>
- <span data-ttu-id="4eec4-112">Na ciljnoj lokaciji može vratiti grešku „nije pronađeno” (HTTP 404) kratak period vremena.</span><span class="sxs-lookup"><span data-stu-id="4eec4-112">The target site may return a "not found" (HTTP 404) error for a short period of time.</span></span>
- <span data-ttu-id="4eec4-113">Sadržaj će morati da bude recrawled da biste ažurirali indeks za pretraživanje.</span><span class="sxs-lookup"><span data-stu-id="4eec4-113">Content will need to be recrawled to update the search index.</span></span> <span data-ttu-id="4eec4-114">Nema ručnu stepeništa potreban ovde, to će biti urađeno automatski.</span><span class="sxs-lookup"><span data-stu-id="4eec4-114">There is no manual step required here, this will be done automatically.</span></span>
- <span data-ttu-id="4eec4-115">Sve zavisi od „statična” veze (kao što je datoteka za sinhronizaciju i OneNote datoteke) će treba ispraviti ručno.</span><span class="sxs-lookup"><span data-stu-id="4eec4-115">Anything dependent on "static" links (such as File Sync and OneNote files) will need to be manually corrected.</span></span>
- <span data-ttu-id="4eec4-116">Project Server lokacije možda će biti potrebno da se vrši da biste bili sigurni da su oni povezani i dalje ispravno.</span><span class="sxs-lookup"><span data-stu-id="4eec4-116">Project Server sites may need to be validated to ensure that they are still associated correctly.</span></span> 
