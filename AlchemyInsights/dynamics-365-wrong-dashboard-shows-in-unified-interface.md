---
title: Dynamics 365-pogrešna Kontrolna tabla u Dynamics 365 ujednačeni interfejs
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1484"
- "6200024"
ms.openlocfilehash: 3d7258bdd7366f679b048e93926ab7dfe0b956d9
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/15/2019
ms.locfileid: "36528565"
---
# <a name="wrong-dashboard-shows-in-dynamics-365-unified-interface"></a><span data-ttu-id="eded3-102">Pogrešna Kontrolna tabla pokazuje se u Dynamics 365 ujednačeni interfejs</span><span class="sxs-lookup"><span data-stu-id="eded3-102">Wrong dashboard shows in Dynamics 365 unified interface</span></span>

<span data-ttu-id="eded3-103">Postoji nekoliko razloga zbog kojih možete videti drugačiju kontrolnu tablu od one koju očekujete:</span><span class="sxs-lookup"><span data-stu-id="eded3-103">There are several reasons why you may see a different dashboard than the one you expect:</span></span>

## <a name="the-user-has-set-a-user-default-dashboard"></a><span data-ttu-id="eded3-104">Korisnik je podesio korisnički podrazumevanu kontrolnu tablu</span><span class="sxs-lookup"><span data-stu-id="eded3-104">The user has set a user default dashboard</span></span> 

<span data-ttu-id="eded3-105">Obično možete identifikovati da je podrazumevana Kontrolna tabla korisnika postavljena ako se dugme " **Postavi kao podrazumevano** " ne prikazuje na komandnoj traci kontrolne table.</span><span class="sxs-lookup"><span data-stu-id="eded3-105">Typically you can identify a user default dashboard is set if the **Set As Default** button does not show in the dashboard command bar.</span></span> <span data-ttu-id="eded3-106">Podrazumevana Kontrolna tabla korisnika će zameniti sve ostale podrazumevane kontrolne table, čak i ako se podrazumevana Kontrolna tabla korisnika ne nalazi u trenutnoj aplikaciji.</span><span class="sxs-lookup"><span data-stu-id="eded3-106">The user default dashboard will override all other default dashboards, even if the user's default dashboard is not in the current app.</span></span>

<span data-ttu-id="eded3-107">Koristite sledeće rešenje da biste razgruppostavili podrazumevanu kontrolnu tablu.</span><span class="sxs-lookup"><span data-stu-id="eded3-107">Use the following workaround to unset their default dashboard.</span></span>

1. <span data-ttu-id="eded3-108">Kreirajte novu ličnu kontrolnu tablu.</span><span class="sxs-lookup"><span data-stu-id="eded3-108">Create a new personal dashboard.</span></span>

2. <span data-ttu-id="eded3-109">Postavite novu kontrolnu tablu kao podrazumevanu vrednost za korisnika.</span><span class="sxs-lookup"><span data-stu-id="eded3-109">Set that new dashboard as the user default.</span></span>

3. <span data-ttu-id="eded3-110">Izbrišite kontrolnu tablu.</span><span class="sxs-lookup"><span data-stu-id="eded3-110">Delete that dashboard.</span></span>

## <a name="the-dashboard-is-set-in-the-sitemap"></a><span data-ttu-id="eded3-111">Kontrolna tabla je postavljena na "Mapa sajta"</span><span class="sxs-lookup"><span data-stu-id="eded3-111">The dashboard is set in the sitemap</span></span>

<span data-ttu-id="eded3-112">Možda ste podesili podrazumevanu kontrolnu tablu za organizaciju tako što ćete izabrati kontrolnu tablu i odabrati opciju "Postavi kao podrazumevanu" u okviru "Prilagodi sistem".</span><span class="sxs-lookup"><span data-stu-id="eded3-112">You may have set an organization default dashboard by selecting a dashboard and choosing 'Set As Default' under 'Customize The System'.</span></span> <span data-ttu-id="eded3-113">Međutim, Kontrolna tabla definisana u dizajneru mapa lokacije će imati prednost u odnosu na ovu kontrolnu tablu ako korisnik ima pristup.</span><span class="sxs-lookup"><span data-stu-id="eded3-113">But the dashboard defined in the sitemap designer will take precedence over this dashboard, if the user has access to it.</span></span>

<span data-ttu-id="eded3-114">Da bi korisnici videli kontrolnu tablu koju ste postavili kao podrazumevanu organizaciju, možete da:</span><span class="sxs-lookup"><span data-stu-id="eded3-114">To have users see the dashboard you've set as the organization default, you can either:</span></span>

* <span data-ttu-id="eded3-115">Postavite kontrolnu tablu na kontrolnoj tabli</span><span class="sxs-lookup"><span data-stu-id="eded3-115">Set that dashboard in the sitemap</span></span>

* <span data-ttu-id="eded3-116">Uklanjanje pristupa za tu lokaciju definisana Kontrolna tabla za ove korisnike</span><span class="sxs-lookup"><span data-stu-id="eded3-116">Remove access to the sitemap defined dashboard for those users</span></span>
