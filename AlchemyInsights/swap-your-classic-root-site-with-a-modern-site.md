---
title: Razmenite tvoj Classic osnovna lokacija sa modernim lokacije
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
ms.openlocfilehash: ffb1466fe436d6cab7ae5fdd60c671f5dd2654dd
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36501093"
---
# <a name="swap-your-classic-root-site-with-a-modern-site"></a><span data-ttu-id="c271a-102">Razmenite tvoj Classic osnovna lokacija sa modernim lokacije</span><span class="sxs-lookup"><span data-stu-id="c271a-102">Swap your Classic root site with a Modern site</span></span>

<span data-ttu-id="c271a-103">Ako vaše okruženje je uspostavljen pre aprila 2019, možete da promenite svoje osnovne lokacije na moderne lokaciju koristeći Microsoft PowerShell:</span><span class="sxs-lookup"><span data-stu-id="c271a-103">If your environment was set up before April 2019, you can change your root site to a modern site by using Microsoft PowerShell:</span></span>

- <span data-ttu-id="c271a-104">Ako imate neku drugu lokaciju na koju želite da koristite kao svoje osnovne lokacije, možete zameniti () osnovne sajtu to.</span><span class="sxs-lookup"><span data-stu-id="c271a-104">If you have a different site that you want to use as your root site, you can replace (swap) the root site with it.</span></span> 
    - <span data-ttu-id="c271a-105">Koristite [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) da razmenite adresu lokacije sa neke druge lokacije tokom arhiviranja originalne lokacije.</span><span class="sxs-lookup"><span data-stu-id="c271a-105">Use [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) to swap the location of a site with another site while archiving the original site.</span></span> <span data-ttu-id="c271a-106">Dostupno za lokaciju tima (nije povezan sa grupom), kao i komunikacija lokacije.</span><span class="sxs-lookup"><span data-stu-id="c271a-106">Available for both Team Site (not connected to a group) and Communication Site.</span></span> 

- <span data-ttu-id="c271a-107">Dodatne mogućnosti će biti uveden uskoro to će vam omogućiti da nastavite da koristite sadržaj na lokaciji, ali konvertovanje postojeće lokacije na lokaciju za komunikaciju.</span><span class="sxs-lookup"><span data-stu-id="c271a-107">Additional capabilities will be introduced soon that will allow you to keep using the content on the site, but convert the existing site to a communication site.</span></span> 
>[!Important]
><span data-ttu-id="c271a-108">Ove mogućnosti će biti poništena postepeno.</span><span class="sxs-lookup"><span data-stu-id="c271a-108">These capabilities will be rolled out gradually.</span></span> <span data-ttu-id="c271a-109">Nastavite da proverite u Office 365 centar za poruke za ispravke.</span><span class="sxs-lookup"><span data-stu-id="c271a-109">Continue to check the Office 365 Message Center for updates.</span></span> 

## <a name="known-issues-with-swapping-sites"></a><span data-ttu-id="c271a-110">Poznati problemi sa zamenjivanje lokacije</span><span class="sxs-lookup"><span data-stu-id="c271a-110">Known issues with swapping sites</span></span>

- <span data-ttu-id="c271a-111">Na ciljnoj lokaciji može vratiti grešku „nije pronađeno” (HTTP 404) kratak period vremena.</span><span class="sxs-lookup"><span data-stu-id="c271a-111">The target site may return a "not found" (HTTP 404) error for a short period of time.</span></span>
- <span data-ttu-id="c271a-112">Sadržaj će morati da bude recrawled da biste ažurirali indeks za pretraživanje.</span><span class="sxs-lookup"><span data-stu-id="c271a-112">Content will need to be recrawled to update the search index.</span></span> <span data-ttu-id="c271a-113">Nema ručnu stepeništa potrebno - to će biti urađeno automatski.</span><span class="sxs-lookup"><span data-stu-id="c271a-113">There is no manual step required - this will be done automatically.</span></span>
- <span data-ttu-id="c271a-114">Sve zavisi od „statična” veze (kao što je datoteka za sinhronizaciju i OneNote datoteke) će treba ispraviti ručno.</span><span class="sxs-lookup"><span data-stu-id="c271a-114">Anything dependent on "static" links (such as File Sync and OneNote files) will need to be manually corrected.</span></span>
- <span data-ttu-id="c271a-115">Ako izvorna lokacija bila lokaciju organizacione vesti, ažurirati URL adrese.</span><span class="sxs-lookup"><span data-stu-id="c271a-115">If the source site was an organizational news site, update the URL.</span></span><span data-ttu-id="c271a-116">Dobijete listu svih organizacionih nove sajtove.</span><span class="sxs-lookup"><span data-stu-id="c271a-116"> Get a list of all organizational news sites.</span></span>
- <span data-ttu-id="c271a-117">Project Server lokacije možda će biti potrebno da se vrši da biste bili sigurni da su oni povezani i dalje ispravno.</span><span class="sxs-lookup"><span data-stu-id="c271a-117">Project Server sites may need to be validated to ensure that they are still associated correctly.</span></span>





