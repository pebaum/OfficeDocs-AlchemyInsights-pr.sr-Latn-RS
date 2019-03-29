---
title: Ograničite SharePoint Online na klasičan način
ms.author: kirks
author: Techwriter40
ms.date: 3/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6e99da1c-e61d-40ba-855e-1a8f346e42fd
ms.openlocfilehash: 6a7c0497243ef7425917f54815e61f1244838c54
ms.sourcegitcommit: b14aa00b42ce4ca9d7dc3aa1fd57e66eae115447
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/28/2019
ms.locfileid: "30953358"
---
# <a name="restrict-sharepoint-online-to-classic-mode"></a><span data-ttu-id="2d23c-102">Ograničite SharePoint Online na klasičan način</span><span class="sxs-lookup"><span data-stu-id="2d23c-102">Restrict SharePoint Online to classic mode</span></span>

<span data-ttu-id="2d23c-103">Neke organizacije su potrebni klasični režim iskustvo.</span><span class="sxs-lookup"><span data-stu-id="2d23c-103">Some organizations still require the Classic mode experience.</span></span> <span data-ttu-id="2d23c-104">Dok ga ne planira da se ukloni klasični režim na osnovnom nivou, početni April 1,2019, to više neće biti moguće je ograničiti celu organizaciju (stanar) u klasični režim za liste i biblioteke.</span><span class="sxs-lookup"><span data-stu-id="2d23c-104">While there are no plans to remove classic mode at a granular level, starting April 1,2019, it will no longer be possible to restrict an entire organization (tenant) to classic mode for lists and libraries.</span></span>

<span data-ttu-id="2d23c-105">U admin će imati sledeće opcije za upravljanje pojedinačnim listama i bibliotekama u klasični režimu pomoću zrnasti saglasnosti prekidači koje pružamo na sledeće nivoe:</span><span class="sxs-lookup"><span data-stu-id="2d23c-105">The admin will have the following options to manage individual lists and libraries in classic mode using granular opt-out switches that we provide at the following levels:</span></span>

<span data-ttu-id="2d23c-106">biblioteka--lokacije lista kolekcije--lokacija----</span><span class="sxs-lookup"><span data-stu-id="2d23c-106">-- site collection -- site -- list -- library</span></span>

<span data-ttu-id="2d23c-107">Pored toga, liste koje koriste određene funkcije i prilagođavanja koja ne podržava moderne će i dalje biti automatski prebacio na klasičan način.</span><span class="sxs-lookup"><span data-stu-id="2d23c-107">Additionally, lists that use certain features and customizations that are not supported by modern will still be automatically switched to classic mode.</span></span>

<span data-ttu-id="2d23c-108">Nakon 1. aprila, liste i biblioteke koje se nalaze u klasični režim kao rezultat stanar saglasnosti će automatski se vodi na nivou lokacije i nivo liste.</span><span class="sxs-lookup"><span data-stu-id="2d23c-108">After April 1, lists and libraries that are in classic mode as a result of tenant opt-out will automatically be managed at the site level and list level.</span></span>

<span data-ttu-id="2d23c-109">Ako je potrebno da klasični režimu pogledajte više informacija ovde i PnP Powershell instrukcija ovde koji opisuje alatke i opcije možete koristiti danas da se pripremi za uklanjanje je stanar nivo saglasnosti na 1 aprila.</span><span class="sxs-lookup"><span data-stu-id="2d23c-109">If you require classic mode please see more information here and PnP Powershell instruction here that describes options and tools you can use today to prepare for the removal of the tenant level opt-out on April 1.</span></span>
