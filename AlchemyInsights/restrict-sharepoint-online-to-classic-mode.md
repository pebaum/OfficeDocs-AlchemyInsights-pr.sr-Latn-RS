---
title: Ograniči SharePoint Online na klasični režim
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6e99da1c-e61d-40ba-855e-1a8f346e42fd
ms.custom:
- "1835"
- "1889"
- "9000225"
ms.openlocfilehash: c5ea5d264b62e4c349623bd431776207b38da470
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43742483"
---
# <a name="restrict-sharepoint-online-to-classic-mode"></a><span data-ttu-id="62a33-102">Ograniči SharePoint Online na klasični režim</span><span class="sxs-lookup"><span data-stu-id="62a33-102">Restrict SharePoint Online to classic mode</span></span>

<span data-ttu-id="62a33-103">Neke organizacije i dalje zahtevaju klasičan režim rada.</span><span class="sxs-lookup"><span data-stu-id="62a33-103">Some organizations still require the Classic mode experience.</span></span> <span data-ttu-id="62a33-104">Iako nema planova za uklanjanje klasičnog režima na nivou Granulat, više nije moguće ograničiti čitavu organizaciju (Tenant) u klasični režim za liste i biblioteke.</span><span class="sxs-lookup"><span data-stu-id="62a33-104">While there are no plans to remove classic mode at a granular level, it is no longer possible to restrict an entire organization (tenant) to classic mode for lists and libraries.</span></span>

<span data-ttu-id="62a33-105">Admin će imati sledeće opcije za upravljanje pojedinačnim listama i bibliotekama u klasičnom režimu uz pomoć prekidača za odbijanje saglasnosti koje pružamo na sledećim nivoima:</span><span class="sxs-lookup"><span data-stu-id="62a33-105">The admin will have the following options to manage individual lists and libraries in classic mode using granular opt-out switches that we provide at the following levels:</span></span>

- <span data-ttu-id="62a33-106">kolekciju lokacija</span><span class="sxs-lookup"><span data-stu-id="62a33-106">site collection</span></span>
- <span data-ttu-id="62a33-107">Lokacije</span><span class="sxs-lookup"><span data-stu-id="62a33-107">site</span></span>
- <span data-ttu-id="62a33-108">Liste</span><span class="sxs-lookup"><span data-stu-id="62a33-108">list</span></span>
- <span data-ttu-id="62a33-109">Biblioteku</span><span class="sxs-lookup"><span data-stu-id="62a33-109">library</span></span>

<span data-ttu-id="62a33-110">Pored toga, liste koje koriste određene funkcije i prilagođavanja koje ne podržavaju moderni će i dalje biti automatski zamenjeni klasičnom režimu.</span><span class="sxs-lookup"><span data-stu-id="62a33-110">Additionally, lists that use certain features and customizations that are not supported by modern will still be automatically switched to classic mode.</span></span>

<span data-ttu-id="62a33-111">Početak 1 April 2019, proces onemogućavanja nivoa koji se izuzima na nivou od moderne liste i biblioteka počeće i trajaće do 2019 31.</span><span class="sxs-lookup"><span data-stu-id="62a33-111">Beginning April 1, 2019, the process to disable the tenant level opt out of modern list and libraries will start and continue through May 31, 2019.</span></span>  <span data-ttu-id="62a33-112">Liste i biblioteke koje se nalaze u klasičnom režimu kao rezultat za odbijanje saglasnosti će automatski biti pomerene na moderan način.</span><span class="sxs-lookup"><span data-stu-id="62a33-112">The lists and libraries that are in classic mode as a result of tenant opt-out will automatically be shifted to modern.</span></span>

<span data-ttu-id="62a33-113">Ako vam je potreban klasičan režim, pogledajte više informacija [ovde](https://techcommunity.microsoft.com/t5/Microsoft-SharePoint-Blog/Delivering-SharePoint-modern-experiences/ba-p/315023) i uputstvo za PNP funkciju koja opisuje opcije i [Alatke koje danas](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries-optout) možete koristiti za korišćenje klasičnog režima rada.</span><span class="sxs-lookup"><span data-stu-id="62a33-113">If you require classic mode please see more information [here](https://techcommunity.microsoft.com/t5/Microsoft-SharePoint-Blog/Delivering-SharePoint-modern-experiences/ba-p/315023) and PnP Powershell instruction [here](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries-optout) that describes options and tools you can use today to use the classic mode experience.</span></span>
