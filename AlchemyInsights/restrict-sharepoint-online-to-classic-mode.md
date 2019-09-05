---
title: Ograniči SharePoint Online na klasični režim
ms.author: pebaum
author: Techwriter40
ms.date: 3/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6e99da1c-e61d-40ba-855e-1a8f346e42fd
ms.custom:
- "1835"
- "1889"
- "9000225"
ms.openlocfilehash: 18d263593d99f24c3020336ae601df14dbbf5411
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/04/2019
ms.locfileid: "36752082"
---
# <a name="restrict-sharepoint-online-to-classic-mode"></a><span data-ttu-id="ec027-102">Ograniči SharePoint Online na klasični režim</span><span class="sxs-lookup"><span data-stu-id="ec027-102">Restrict SharePoint Online to classic mode</span></span>

<span data-ttu-id="ec027-103">Neke organizacije i dalje zahtevaju klasičan režim rada.</span><span class="sxs-lookup"><span data-stu-id="ec027-103">Some organizations still require the Classic mode experience.</span></span> <span data-ttu-id="ec027-104">Iako nema planova za uklanjanje klasičnog režima na nivou Granulat, više nije moguće ograničiti čitavu organizaciju (Tenant) u klasični režim za liste i biblioteke.</span><span class="sxs-lookup"><span data-stu-id="ec027-104">While there are no plans to remove classic mode at a granular level, it is no longer possible to restrict an entire organization (tenant) to classic mode for lists and libraries.</span></span>

<span data-ttu-id="ec027-105">Admin će imati sledeće opcije za upravljanje pojedinačnim listama i bibliotekama u klasičnom režimu uz pomoć prekidača za odbijanje saglasnosti koje pružamo na sledećim nivoima:</span><span class="sxs-lookup"><span data-stu-id="ec027-105">The admin will have the following options to manage individual lists and libraries in classic mode using granular opt-out switches that we provide at the following levels:</span></span>

- <span data-ttu-id="ec027-106">kolekciju lokacija</span><span class="sxs-lookup"><span data-stu-id="ec027-106">site collection</span></span>
- <span data-ttu-id="ec027-107">Lokacije</span><span class="sxs-lookup"><span data-stu-id="ec027-107">site</span></span>
- <span data-ttu-id="ec027-108">Liste</span><span class="sxs-lookup"><span data-stu-id="ec027-108">list</span></span>
- <span data-ttu-id="ec027-109">Biblioteku</span><span class="sxs-lookup"><span data-stu-id="ec027-109">library</span></span>

<span data-ttu-id="ec027-110">Pored toga, liste koje koriste određene funkcije i prilagođavanja koje ne podržavaju moderni će i dalje biti automatski zamenjeni klasičnom režimu.</span><span class="sxs-lookup"><span data-stu-id="ec027-110">Additionally, lists that use certain features and customizations that are not supported by modern will still be automatically switched to classic mode.</span></span>

<span data-ttu-id="ec027-111">Početak 1 April 2019, proces onemogućavanja nivoa koji se izuzima na nivou od moderne liste i biblioteka počeće i trajaće do 2019 31.</span><span class="sxs-lookup"><span data-stu-id="ec027-111">Beginning April 1, 2019, the process to disable the tenant level opt out of modern list and libraries will start and continue through May 31, 2019.</span></span>  <span data-ttu-id="ec027-112">Liste i biblioteke koje se nalaze u klasičnom režimu kao rezultat za odbijanje saglasnosti će automatski biti pomerene na moderan način.</span><span class="sxs-lookup"><span data-stu-id="ec027-112">The lists and libraries that are in classic mode as a result of tenant opt-out will automatically be shifted to modern.</span></span>

<span data-ttu-id="ec027-113">Ako vam je potreban klasičan režim, pogledajte više informacija [ovde](https://techcommunity.microsoft.com/t5/Microsoft-SharePoint-Blog/Delivering-SharePoint-modern-experiences/ba-p/315023) i uputstvo za PNP funkciju koja opisuje opcije i [Alatke koje danas](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries-optout) možete koristiti za korišćenje klasičnog režima rada.</span><span class="sxs-lookup"><span data-stu-id="ec027-113">If you require classic mode please see more information [here](https://techcommunity.microsoft.com/t5/Microsoft-SharePoint-Blog/Delivering-SharePoint-modern-experiences/ba-p/315023) and PnP Powershell instruction [here](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries-optout) that describes options and tools you can use today to use the classic mode experience.</span></span>
