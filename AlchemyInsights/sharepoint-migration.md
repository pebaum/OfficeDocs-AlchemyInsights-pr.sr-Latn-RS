---
title: Migriraj opcije na SharePoint online
ms.author: pebaum
author: v-miegge
manager: v-cojank
ms.date: 11/04/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: c8c339c9-2e50-4daa-aa91-3eb5053e2bc6
ms.openlocfilehash: 830b39c51658cbc02f4be81acdfdf3b164a8df70
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932744"
---
# <a name="migrate-options-to-sharepoint-online"></a><span data-ttu-id="5c8fd-102">Migriraj opcije na SharePoint online</span><span class="sxs-lookup"><span data-stu-id="5c8fd-102">Migrate options to SharePoint Online</span></span>

<span data-ttu-id="5c8fd-103">**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini.</span><span class="sxs-lookup"><span data-stu-id="5c8fd-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="5c8fd-104">Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje.</span><span class="sxs-lookup"><span data-stu-id="5c8fd-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="5c8fd-105">U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.</span><span class="sxs-lookup"><span data-stu-id="5c8fd-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="5c8fd-106">U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici.</span><span class="sxs-lookup"><span data-stu-id="5c8fd-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="5c8fd-107">Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena.</span><span class="sxs-lookup"><span data-stu-id="5c8fd-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="5c8fd-108">Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.</span><span class="sxs-lookup"><span data-stu-id="5c8fd-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="5c8fd-109">**Opcije migracije**</span><span class="sxs-lookup"><span data-stu-id="5c8fd-109">**Migration options**</span></span>

<span data-ttu-id="5c8fd-110">Postoje različite opcije za migraciju sadržaja na SharePoint online, u zavisnosti od veličine i količine datoteka koje treba da premestite, pogledajte listu opcija koje [se ovde nalaze](https://docs.microsoft.com/sharepointmigration/migrate-to-sharepoint-online).</span><span class="sxs-lookup"><span data-stu-id="5c8fd-110">There are different options available to migrate content to SharePoint Online, depending on the size and quantity of files you need to move, please see a list of options [located here](https://docs.microsoft.com/sharepointmigration/migrate-to-sharepoint-online).</span></span>

<span data-ttu-id="5c8fd-111">Za više informacija o migracijama sadržaja, posetite dolenavedena linka.</span><span class="sxs-lookup"><span data-stu-id="5c8fd-111">For more information on content migration, please visit the links below.</span></span>

- [<span data-ttu-id="5c8fd-112">Alatka za SharePoint migraciju</span><span class="sxs-lookup"><span data-stu-id="5c8fd-112">Sharepoint Migration Tool</span></span>](https://docs.microsoft.com/sharepointmigration/introducing-the-sharepoint-migration-tool)

- [<span data-ttu-id="5c8fd-113">Početak sa Menadžerom za migraciju</span><span class="sxs-lookup"><span data-stu-id="5c8fd-113">Get started with the Migration Manager</span></span>](https://docs.microsoft.com/sharepointmigration/mm-get-started)

- [<span data-ttu-id="5c8fd-114">Brzina migracije za SharePoint Online i ODB</span><span class="sxs-lookup"><span data-stu-id="5c8fd-114">Sharepoint Online and ODB Migration Speed</span></span>](https://docs.microsoft.com/sharepointmigration/sharepoint-online-and-onedrive-migration-speed)

- [<span data-ttu-id="5c8fd-115">Izbegavanje preuzimanja ili blokiranja na SharePoint mreži</span><span class="sxs-lookup"><span data-stu-id="5c8fd-115">Avoid getting throttled or blocked in SharePoint Online</span></span>](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online)

- [<span data-ttu-id="5c8fd-116">Alatka za procenu SharePoint migracije (SMAT)</span><span class="sxs-lookup"><span data-stu-id="5c8fd-116">SharePoint Migration Assessment Tool (SMAT)</span></span>](https://www.microsoft.com/download/details.aspx?id=53598&amp;751be11f-ede8-5a0c-058c-2ee190a24fa6=True)

<span data-ttu-id="5c8fd-117">**Napomena**: ova alatka za SharePoint migraciju podržava samo migracije sa SharePoint 2010 i 2013.</span><span class="sxs-lookup"><span data-stu-id="5c8fd-117">**Note**: Currently the SharePoint Migration tool only support migrations from SharePoint 2010  and 2013.</span></span> <span data-ttu-id="5c8fd-118">Trenutno nije podržana verzija 2016 ili 2019.</span><span class="sxs-lookup"><span data-stu-id="5c8fd-118">Version 2016 or 2019 are not supported at this time.</span></span>
