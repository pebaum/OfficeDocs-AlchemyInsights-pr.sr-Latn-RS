---
title: Profil sinhronizacije
ms.author: arnek
author: arnek
ms.date: 6/20/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: d1a72a85767e36fefbfa8eee266befcaf2e48af0
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32371998"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a><span data-ttu-id="62363-102">Kada uradim moj profil promene izvršiti sinhronizaciju SharePoint aplikaciji profila korisnika?</span><span class="sxs-lookup"><span data-stu-id="62363-102">When do my profile changes sync to the SharePoint User Profile Application?</span></span>

<span data-ttu-id="62363-103">SharePoint Online koristi Active Directory uvoz tajmera (AD uvoza) da biste uvezli korisnike i grupe u aplikaciju korisničkog profila.</span><span class="sxs-lookup"><span data-stu-id="62363-103">SharePoint Online uses the Active Directory Import timer job (AD Import) to import users and groups into the User Profile Application.</span></span> 
  
1. <span data-ttu-id="62363-104">AD uvoz sinhronizuje promene iz SharePoint Online kataloga skladišta u aplikaciju korisničkog profila.</span><span class="sxs-lookup"><span data-stu-id="62363-104">AD Import syncs changes from the SharePoint Online Directory Store to the User Profile Application.</span></span> <span data-ttu-id="62363-105">Ove promene se obrađuju u grupama.</span><span class="sxs-lookup"><span data-stu-id="62363-105">These changes are processed in batches.</span></span>
    
2. <span data-ttu-id="62363-106">Tajmera se izvršava sve dok promene koje se sinhronizuju.</span><span class="sxs-lookup"><span data-stu-id="62363-106">The timer job runs until the changes are synced.</span></span>
    
> [!NOTE]
> <span data-ttu-id="62363-107">Vreme koje je potrebno za pokretanje posla zavisi od broja promene u obradi.</span><span class="sxs-lookup"><span data-stu-id="62363-107">The time it takes the job to run depends on the number of changes to process.</span></span> <span data-ttu-id="62363-108">Veliki broj promene traje duže.</span><span class="sxs-lookup"><span data-stu-id="62363-108">A large number of changes takes longer.</span></span> <span data-ttu-id="62363-109">Sporazum o nivou servisa (SLA) navodi da promena na korisnika u SharePoint Online katalog odraziti u aplikaciji profila korisnika u 24 sata.</span><span class="sxs-lookup"><span data-stu-id="62363-109">The Service Level Agreement (SLA) states that a change to a user in the SharePoint Online Directory will be reflected in the User Profile Application in 24 hours.</span></span> 
  
[<span data-ttu-id="62363-110">Više informacija o sinhronizaciji profil korisnika u SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="62363-110">More info about user profile sync in SharePoint Online</span></span>](https://go.microsoft.com/fwlink/?linkid=875671)
  

