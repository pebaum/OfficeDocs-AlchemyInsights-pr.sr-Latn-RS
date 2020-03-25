---
title: Migracija na SharePoint na mreži putem menadžera migracije
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
- "3192"
ms.openlocfilehash: 5aebf7903670e74f616c8f151749d760caf1d642
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932193"
---
# <a name="migrating-to-sharepoint-online-via-migration-manager"></a><span data-ttu-id="cd97f-102">Migracija na SharePoint na mreži putem menadžera migracije</span><span class="sxs-lookup"><span data-stu-id="cd97f-102">Migrating to SharePoint Online via Migration Manager</span></span>

<span data-ttu-id="cd97f-103">**Važno**: Mnogi SharePoint Online i OneDrive klijenti pokreću aplikacije koje su kritične za poslovanje u odnosu na usluge koje se pokreću u pozadini.</span><span class="sxs-lookup"><span data-stu-id="cd97f-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="cd97f-104">One uključuju rešenja za migraciju sadržaja, sprečavanje gubitka podataka (DLP) i pravljenje rezervne kopije.</span><span class="sxs-lookup"><span data-stu-id="cd97f-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="cd97f-105">Tokom tih jedinstvenih vremena, preduzimamo korake da obezbedimo da SharePoint Online i OneDrive usluge ostanu u velikoj meri dostupne i pouzdane za vaše korisnike koji više nego ikada zavise od usluge u scenarijima daljinskog rada.</span><span class="sxs-lookup"><span data-stu-id="cd97f-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="cd97f-106">Kao podršku za ovaj cilj, primenili smo stroža ograničenja na aplikacije u pozadini (rešenja za migraciju, DLP i pravljenje rezervne kopije) tokom dana radnim danima.</span><span class="sxs-lookup"><span data-stu-id="cd97f-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="cd97f-107">Trebalo bi da očekujete da će ove aplikacije imati vrlo ograničen protok u tim vremenima.</span><span class="sxs-lookup"><span data-stu-id="cd97f-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="cd97f-108">Međutim, tokom večeri i vikendom nedeljno u vašem regionu, usluga će biti spremna za obradu znatno većih količina zahteva iz aplikacija u pozadini.</span><span class="sxs-lookup"><span data-stu-id="cd97f-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="cd97f-109">**Menadžer migracije**</span><span class="sxs-lookup"><span data-stu-id="cd97f-109">**Migration Manager**</span></span>

<span data-ttu-id="cd97f-110">Menadžer migracije nalazi se u modernom SharePoint centru administracije i vodi vas kroz instalaciju klijenata i kreiranje zadataka.</span><span class="sxs-lookup"><span data-stu-id="cd97f-110">Located in the modern SharePoint Admin Center, the Migration Manager guides you through the setup of your clients and the creation of your tasks.</span></span> <span data-ttu-id="cd97f-111">Možete da navedete globalne postavke ili postavke na nivou zadatka, da pregledate kompletan napredak zadatka i da preuzmete izveštaje o prikupljenim rezimeima i izveštaje na nivou zadatka.</span><span class="sxs-lookup"><span data-stu-id="cd97f-111">You can specify global or task-level settings, view all-up task progress, and download aggregated summary and task-level reports.</span></span>

- [<span data-ttu-id="cd97f-112">Prvi koraci uz menadžera migracije</span><span class="sxs-lookup"><span data-stu-id="cd97f-112">Get started with the Migration Manager</span></span>](https://docs.microsoft.com/sharepointmigration/mm-get-started)

- [<span data-ttu-id="cd97f-113">Instaliranje klijenata menadžera migracije</span><span class="sxs-lookup"><span data-stu-id="cd97f-113">Setup Migration Manager clients</span></span>](https://docs.microsoft.com/sharepointmigration/mm-setup-clients)

- [<span data-ttu-id="cd97f-114">Postavke menadžera migracije</span><span class="sxs-lookup"><span data-stu-id="cd97f-114">Migration Manager Settings</span></span>](https://docs.microsoft.com/sharepointmigration/mm-settings)
