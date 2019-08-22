---
title: Dynamics 365 - naopako kontrolne table prikazuje u jedinstvenoj interfejs Dynamics 365
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
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36528565"
---
# <a name="wrong-dashboard-shows-in-dynamics-365-unified-interface"></a><span data-ttu-id="13b9a-102">U redu kontrolne table prikazuje u jedinstvenoj interfejs Dynamics 365</span><span class="sxs-lookup"><span data-stu-id="13b9a-102">Wrong dashboard shows in Dynamics 365 unified interface</span></span>

<span data-ttu-id="13b9a-103">Postoji nekoliko razloga zašto možda ćete videti različite instrument-tabli od one koju očekujete:</span><span class="sxs-lookup"><span data-stu-id="13b9a-103">There are several reasons why you may see a different dashboard than the one you expect:</span></span>

## <a name="the-user-has-set-a-user-default-dashboard"></a><span data-ttu-id="13b9a-104">Korisnik je odredio korisnik podrazumevanu kontrolnu tablu</span><span class="sxs-lookup"><span data-stu-id="13b9a-104">The user has set a user default dashboard</span></span> 

<span data-ttu-id="13b9a-105">Obično možete da identifikujete korisnika podrazumevanu kontrolnu tablu postavljeno ako **Postavi kao podrazumevano** dugme ne prikazuje u kontrolnoj tabli komandna traka.</span><span class="sxs-lookup"><span data-stu-id="13b9a-105">Typically you can identify a user default dashboard is set if the **Set As Default** button does not show in the dashboard command bar.</span></span> <span data-ttu-id="13b9a-106">Podrazumevane kontrolne table korisnika će poništiti sve druge podrazumevane kontrolne table, čak i ako korisnikove podrazumevane kontrolne table nije u trenutnoj molbi.</span><span class="sxs-lookup"><span data-stu-id="13b9a-106">The user default dashboard will override all other default dashboards, even if the user's default dashboard is not in the current app.</span></span>

<span data-ttu-id="13b9a-107">Koristite sledeće rešenje za uklanjanje svoju podrazumevanu kontrolnu tablu.</span><span class="sxs-lookup"><span data-stu-id="13b9a-107">Use the following workaround to unset their default dashboard.</span></span>

1. <span data-ttu-id="13b9a-108">Kreirajte novu ličnu kontrolnu tablu.</span><span class="sxs-lookup"><span data-stu-id="13b9a-108">Create a new personal dashboard.</span></span>

2. <span data-ttu-id="13b9a-109">Da postavite novi instrument tabli kao zadanog korisnika.</span><span class="sxs-lookup"><span data-stu-id="13b9a-109">Set that new dashboard as the user default.</span></span>

3. <span data-ttu-id="13b9a-110">Izbriši instrument tabli.</span><span class="sxs-lookup"><span data-stu-id="13b9a-110">Delete that dashboard.</span></span>

## <a name="the-dashboard-is-set-in-the-sitemap"></a><span data-ttu-id="13b9a-111">Kontrolna tabla je postavljena u Mapa sajta</span><span class="sxs-lookup"><span data-stu-id="13b9a-111">The dashboard is set in the sitemap</span></span>

<span data-ttu-id="13b9a-112">Možda ste postavili organizaciju podrazumevanu kontrolnu tablu od strane izabrati instrument-tabli i „Postavi kao podrazumevano” pod „Prilagođavanje sistema”.</span><span class="sxs-lookup"><span data-stu-id="13b9a-112">You may have set an organization default dashboard by selecting a dashboard and choosing 'Set As Default' under 'Customize The System'.</span></span> <span data-ttu-id="13b9a-113">Ali, Kontrolna tabla definisan u dizajneru sitemap će prednost nad ovu kontrolnu tablu, ako korisnik ima pristup njemu.</span><span class="sxs-lookup"><span data-stu-id="13b9a-113">But the dashboard defined in the sitemap designer will take precedence over this dashboard, if the user has access to it.</span></span>

<span data-ttu-id="13b9a-114">Da bi korisnici vide kontrolne table ste postavili kao podrazumevani organizaciji, možete:</span><span class="sxs-lookup"><span data-stu-id="13b9a-114">To have users see the dashboard you've set as the organization default, you can either:</span></span>

* <span data-ttu-id="13b9a-115">Postavite instrument tabli u Mapa sajta</span><span class="sxs-lookup"><span data-stu-id="13b9a-115">Set that dashboard in the sitemap</span></span>

* <span data-ttu-id="13b9a-116">Uklanjanje pristupa na kontrolnu tablu sitemap definisan za one korisnike</span><span class="sxs-lookup"><span data-stu-id="13b9a-116">Remove access to the sitemap defined dashboard for those users</span></span>
