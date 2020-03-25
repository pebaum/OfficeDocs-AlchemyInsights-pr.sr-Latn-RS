---
title: Opšta uputstva za performanse migracije
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 686e8f18-b871-4dd2-864f-8562947ab583
ms.collection: Adm_O365
ms.custom:
- "5300030"
- "3179"
ms.openlocfilehash: 10a0069c41d2e5128b2592425d815364a83b730f
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932492"
---
# <a name="general-migration-performance-guidance"></a><span data-ttu-id="006ed-102">Opšta uputstva za performanse migracije</span><span class="sxs-lookup"><span data-stu-id="006ed-102">General migration performance guidance</span></span>

<span data-ttu-id="006ed-103">**Važno**: Mnogi SharePoint Online i OneDrive klijenti pokreću aplikacije koje su kritične za poslovanje u odnosu na usluge koje se pokreću u pozadini.</span><span class="sxs-lookup"><span data-stu-id="006ed-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="006ed-104">One uključuju rešenja za migraciju sadržaja, sprečavanje gubitka podataka (DLP) i pravljenje rezervne kopije.</span><span class="sxs-lookup"><span data-stu-id="006ed-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="006ed-105">Tokom tih jedinstvenih vremena, preduzimamo korake da obezbedimo da SharePoint Online i OneDrive usluge ostanu u velikoj meri dostupne i pouzdane za vaše korisnike koji više nego ikada zavise od usluge u scenarijima daljinskog rada.</span><span class="sxs-lookup"><span data-stu-id="006ed-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="006ed-106">Kao podršku za ovaj cilj, primenili smo stroža ograničenja na aplikacije u pozadini (rešenja za migraciju, DLP i pravljenje rezervne kopije) tokom dana radnim danima.</span><span class="sxs-lookup"><span data-stu-id="006ed-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="006ed-107">Trebalo bi da očekujete da će ove aplikacije imati vrlo ograničen protok u tim vremenima.</span><span class="sxs-lookup"><span data-stu-id="006ed-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="006ed-108">Međutim, tokom večeri i vikendom nedeljno u vašem regionu, usluga će biti spremna za obradu znatno većih količina zahteva iz aplikacija u pozadini.</span><span class="sxs-lookup"><span data-stu-id="006ed-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="006ed-109">**Uputstva za performanse migracije**</span><span class="sxs-lookup"><span data-stu-id="006ed-109">**Migration performance guidance**</span></span>

<span data-ttu-id="006ed-110">Na performanse migracije mogu da utiču infrastruktura mreže, veličina datoteke, vreme migracije i ograničavanje.</span><span class="sxs-lookup"><span data-stu-id="006ed-110">Migration performance can be impacted by network infrastructure, file size, migration time, and throttling.</span></span> <span data-ttu-id="006ed-111">Ako to razumete, lakše ćete moći da planirate i uvećate efikasnost migracije.</span><span class="sxs-lookup"><span data-stu-id="006ed-111">Understanding these will help you plan and maximize the efficiency of your migration.</span></span>

- [<span data-ttu-id="006ed-112">Opšta uputstva za performanse migracije</span><span class="sxs-lookup"><span data-stu-id="006ed-112">General migration performance guidance</span></span>](https://docs.microsoft.com/sharepointmigration/sharepoint-online-and-onedrive-migration-speed)
