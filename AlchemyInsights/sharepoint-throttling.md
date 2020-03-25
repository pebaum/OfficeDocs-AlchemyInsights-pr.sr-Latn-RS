---
title: SharePoint online reguliranje
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.openlocfilehash: 9af4f09d50992c04a1f3d5a164093049a3ec3517
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931456"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="af6f0-102">SharePoint online reguliranje</span><span class="sxs-lookup"><span data-stu-id="af6f0-102">SharePoint Online throttling</span></span>

<span data-ttu-id="af6f0-103">**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini.</span><span class="sxs-lookup"><span data-stu-id="af6f0-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="af6f0-104">Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje.</span><span class="sxs-lookup"><span data-stu-id="af6f0-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="af6f0-105">U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.</span><span class="sxs-lookup"><span data-stu-id="af6f0-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="af6f0-106">U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici.</span><span class="sxs-lookup"><span data-stu-id="af6f0-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="af6f0-107">Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena.</span><span class="sxs-lookup"><span data-stu-id="af6f0-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="af6f0-108">Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.</span><span class="sxs-lookup"><span data-stu-id="af6f0-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="af6f0-109">**SharePoint online reguliranje**</span><span class="sxs-lookup"><span data-stu-id="af6f0-109">**SharePoint Online throttling**</span></span>

<span data-ttu-id="af6f0-110">SharePoint online koristi ograničavanje za održavanje optimalnih performansi i pouzdanosti SharePoint usluge na mreži.</span><span class="sxs-lookup"><span data-stu-id="af6f0-110">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="af6f0-111">Ograničavanje ograničava broj radnji korisnika ili uporedne pozive (po skripti ili kodu) da bi sprečio prekomerno korišćenje resursa.</span><span class="sxs-lookup"><span data-stu-id="af6f0-111">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> <span data-ttu-id="af6f0-112">Za više informacija, molimo vas da posetite dole navedene veze.</span><span class="sxs-lookup"><span data-stu-id="af6f0-112">For more information, please visit the links below.</span></span>

- [<span data-ttu-id="af6f0-113">Izbegavanje preuzimanja ili blokiranja na SharePoint mreži</span><span class="sxs-lookup"><span data-stu-id="af6f0-113">Avoid getting throttled or blocked in SharePoint Online</span></span>](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online)

- [<span data-ttu-id="af6f0-114">Migracija podataka i SPO-gas</span><span class="sxs-lookup"><span data-stu-id="af6f0-114">Data Migration and SPO Throttling </span></span>](https://blogs.technet.microsoft.com/sposupport/2017/08/12/data-migration-and-spo-service-throttling/)

- [<span data-ttu-id="af6f0-115">Brzina migracije SharePoint Online i OneDrive</span><span class="sxs-lookup"><span data-stu-id="af6f0-115">SharePoint Online and OneDrive Migration Speed</span></span>](https://docs.microsoft.com/sharepointmigration/sharepoint-online-and-onedrive-migration-speed)

 - [<span data-ttu-id="af6f0-116">Rukovanje SharePoint online reguliranje pomoću eksponencijalnog isključivanja</span><span class="sxs-lookup"><span data-stu-id="af6f0-116">Handle SharePoint Online throttling by using exponential back off</span></span>](https://docs.microsoft.com/sharepoint/dev/solution-guidance/handle-sharepoint-online-throttling-by-using-exponential-back-off)

- [<span data-ttu-id="af6f0-117">Planiranje kapaciteta i učitavanje testiranja na SharePoint mreži</span><span class="sxs-lookup"><span data-stu-id="af6f0-117">Capacity planning and load testing SharePoint Online</span></span>](https://docs.microsoft.com/office365/enterprise/capacity-planning-and-load-testing-sharepoint-online)

