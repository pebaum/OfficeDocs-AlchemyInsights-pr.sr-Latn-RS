---
title: SharePoint online reguliranje
ms.author: pebaum
author: pebaum
ms.date: 9/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.custom:
- "9000149"
- "1662"
- "3491"
ms.openlocfilehash: 59104ef96c95de4e4bc7744825245bdafba97d7c
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931240"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="530b4-102">SharePoint online reguliranje</span><span class="sxs-lookup"><span data-stu-id="530b4-102">SharePoint Online Throttling</span></span>

<span data-ttu-id="530b4-103">**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini.</span><span class="sxs-lookup"><span data-stu-id="530b4-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="530b4-104">Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje.</span><span class="sxs-lookup"><span data-stu-id="530b4-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="530b4-105">U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.</span><span class="sxs-lookup"><span data-stu-id="530b4-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="530b4-106">U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici.</span><span class="sxs-lookup"><span data-stu-id="530b4-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="530b4-107">Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena.</span><span class="sxs-lookup"><span data-stu-id="530b4-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="530b4-108">Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.</span><span class="sxs-lookup"><span data-stu-id="530b4-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="530b4-109">**503 server je zauzet greška**</span><span class="sxs-lookup"><span data-stu-id="530b4-109">**503 server is busy error**</span></span>

<span data-ttu-id="530b4-110">Korisnici mogu da prime 503 server je zauzet greškom prilikom pokušaja da se kreću na SharePoint ili OneDrive lokacije.</span><span class="sxs-lookup"><span data-stu-id="530b4-110">Users may receive a 503 server is busy error when attempting to navigate to SharePoint or OneDrive sites.</span></span> 

<span data-ttu-id="530b4-111">Ova greška može biti izazvana regulisanja u okviru SharePoint usluge.</span><span class="sxs-lookup"><span data-stu-id="530b4-111">This error can be caused by throttling within the SharePoint service.</span></span> <span data-ttu-id="530b4-112">SharePoint online koristi ograničavanje za održavanje optimalnih performansi i pouzdanosti SharePoint usluge na mreži.</span><span class="sxs-lookup"><span data-stu-id="530b4-112">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="530b4-113">Ograničavanje ograničava broj radnji korisnika ili uporedne pozive (po skripti ili kodu) da bi sprečio prekomerno korišćenje resursa.</span><span class="sxs-lookup"><span data-stu-id="530b4-113">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> 

<span data-ttu-id="530b4-114">Za više informacija o regulisanja pogledajte, [izbegavajte ograničavanje ili blokiranje na lokaciji SharePoint online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span><span class="sxs-lookup"><span data-stu-id="530b4-114">For more information on throttling see, [Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span></span>

<span data-ttu-id="530b4-115">Ako smatrate da ova greška nije u vezi sa regulisanja, možete da proverite da li je na vašem računaru došlo do aktivnog održavanja ako se krećete do [centra za poruke](https://portal.office.com/adminportal/home#/MessageCenter).</span><span class="sxs-lookup"><span data-stu-id="530b4-115">If you believe this error is unrelated to throttling, you can check if there is active maintenance occurring on your tenant by navigating to the [Message center](https://portal.office.com/adminportal/home#/MessageCenter).</span></span>

 <span data-ttu-id="530b4-116">Na kraju, uverite se da ste posetili stranicu " [zdravstvo usluge](https://portal.office.com/adminportal/home#/servicehealth) " da biste proverili da li postoje neki savetnici/incidenti koji se mogu naići.</span><span class="sxs-lookup"><span data-stu-id="530b4-116">Finally, ensure you visit the [Service Health](https://portal.office.com/adminportal/home#/servicehealth) page to check for any advisories/incidents that may be occurring.</span></span>

