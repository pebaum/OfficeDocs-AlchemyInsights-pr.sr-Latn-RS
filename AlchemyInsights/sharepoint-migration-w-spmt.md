---
title: SharePoint migracija sa SPMT
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 9/18/19
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5300030"
- "2594"
ms.openlocfilehash: e7719d1fc6dda0d5bd340775219401dade2933fe
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931564"
---
# <a name="sharepoint-migration-with-spmt"></a><span data-ttu-id="94a8f-102">SharePoint migracija sa SPMT</span><span class="sxs-lookup"><span data-stu-id="94a8f-102">SharePoint Migration with SPMT</span></span>

<span data-ttu-id="94a8f-103">**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini.</span><span class="sxs-lookup"><span data-stu-id="94a8f-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="94a8f-104">Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje.</span><span class="sxs-lookup"><span data-stu-id="94a8f-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="94a8f-105">U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.</span><span class="sxs-lookup"><span data-stu-id="94a8f-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="94a8f-106">U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici.</span><span class="sxs-lookup"><span data-stu-id="94a8f-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="94a8f-107">Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena.</span><span class="sxs-lookup"><span data-stu-id="94a8f-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="94a8f-108">Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.</span><span class="sxs-lookup"><span data-stu-id="94a8f-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="94a8f-109">**Alatka za SharePoint migraciju**</span><span class="sxs-lookup"><span data-stu-id="94a8f-109">**SharePoint Migration Tool**</span></span>

<span data-ttu-id="94a8f-110">Dizajniran da se koristi za migraciju koje se kreću od najmanjeg skupa datoteka do velikog obima migracije preduzeća, alatka za SharePoint migraciju će vam omogućiti da prenesete informacije u oblak i iskoristite najnoviju saradnju, obaveštajne podatke i bezbednosna rešenja sa Office-om 365.</span><span class="sxs-lookup"><span data-stu-id="94a8f-110">Designed to be used for migrations ranging from the smallest set of files to a large scale enterprise migration, the SharePoint Migration Tool will allow you to transfer your information to the cloud and take advantage of the newest collaboration, intelligence, and security solutions with Office 365.</span></span>

- [<span data-ttu-id="94a8f-111">Preuzimanje i instaliranje alatke za SharePoint migraciju</span><span class="sxs-lookup"><span data-stu-id="94a8f-111">Download and install the SharePoint Migration Tool</span></span>](https://docs.microsoft.com/sharepointmigration/introducing-the-sharepoint-migration-tool)
- [<span data-ttu-id="94a8f-112">Rešavanje uobičajenih problema i grešaka u ŠMT</span><span class="sxs-lookup"><span data-stu-id="94a8f-112">Troubleshooting common SPMT issues and errors</span></span>](https://docs.microsoft.com/sharepointmigration/troubleshooting-common-spmt-issues)
- [<span data-ttu-id="94a8f-113">Rešavanje problema sa instalacijom instalacije</span><span class="sxs-lookup"><span data-stu-id="94a8f-113">Troubleshooting SPMT installation issues</span></span>](https://docs.microsoft.com/sharepointmigration/spmt-install-issues#troubleshooting-spmt-installation-issues)
