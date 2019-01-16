---
title: Profil sinhronizacije
ms.author: arnek
author: arnek
ms.date: 6/20/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: a32cf9e623d1be7a2c85ef4951c6eb7f001b7db0
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/15/2019
ms.locfileid: "28309803"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a><span data-ttu-id="8179a-102">Kada uradim moj profil promene izvršiti sinhronizaciju SharePoint aplikaciji profila korisnika?</span><span class="sxs-lookup"><span data-stu-id="8179a-102">When do my profile changes sync to the SharePoint User Profile Application?</span></span>

<span data-ttu-id="8179a-103">SharePoint Online koristi Active Directory uvoz tajmera (AD uvoza) da biste uvezli korisnike i grupe u aplikaciju korisničkog profila.</span><span class="sxs-lookup"><span data-stu-id="8179a-103">SharePoint Online uses the Active Directory Import timer job (AD Import) to import users and groups into the User Profile Application.</span></span> 
  
1. <span data-ttu-id="8179a-p101">AD uvoz sinhronizuje promene iz SharePoint Online kataloga skladišta u aplikaciju korisničkog profila. Ove promene se obrađuju u grupama.</span><span class="sxs-lookup"><span data-stu-id="8179a-p101">AD Import syncs changes from the SharePoint Online Directory Store to the User Profile Application. These changes are processed in batches.</span></span>
    
2. <span data-ttu-id="8179a-106">Tajmera se izvršava sve dok promene koje se sinhronizuju.</span><span class="sxs-lookup"><span data-stu-id="8179a-106">The timer job runs until the changes are synced.</span></span>
    
> [!NOTE]
> <span data-ttu-id="8179a-p102">Vreme koje je potrebno za pokretanje posla zavisi od broja promene u obradi. Veliki broj promene traje duže. Sporazum o nivou servisa (SLA) navodi da promena na korisnika u SharePoint Online katalog odraziti u aplikaciji profila korisnika u 24 sata.</span><span class="sxs-lookup"><span data-stu-id="8179a-p102">The time it takes the job to run depends on the number of changes to process. A large number of changes takes longer. The Service Level Agreement (SLA) states that a change to a user in the SharePoint Online Directory will be reflected in the User Profile Application in 24 hours.</span></span> 
  
[<span data-ttu-id="8179a-110">Više informacija o sinhronizaciji profil korisnika u SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="8179a-110">More info about user profile sync in SharePoint Online</span></span>](https://go.microsoft.com/fwlink/?linkid=875671)
  

