---
title: Sinhronizacija profila
ms.author: arnek
author: arnek
ms.date: 6/20/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: b9b90dad6c5fa41afcd4e4c9a929594735eca066
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/18/2019
ms.locfileid: "36554347"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a><span data-ttu-id="88cad-102">Kada moj profil menja sinhronizaciju sa aplikacijom SharePoint korisnički profil?</span><span class="sxs-lookup"><span data-stu-id="88cad-102">When do my profile changes sync to the SharePoint User Profile Application?</span></span>

<span data-ttu-id="88cad-103">SharePoint online koristi posao tajmera u aktivnom direktorijumu (uvoz oglasa) za uvoz korisnika i grupa u aplikaciju korisničkog profila.</span><span class="sxs-lookup"><span data-stu-id="88cad-103">SharePoint Online uses the Active Directory Import timer job (AD Import) to import users and groups into the User Profile Application.</span></span> 
  
1. <span data-ttu-id="88cad-104">Uvoz oglasa sinhronizuje promene iz skladišta SharePoint kataloga na mreži u aplikaciju korisničkog profila.</span><span class="sxs-lookup"><span data-stu-id="88cad-104">AD Import syncs changes from the SharePoint Online Directory Store to the User Profile Application.</span></span> <span data-ttu-id="88cad-105">Ove promene se obrađuju u grupama.</span><span class="sxs-lookup"><span data-stu-id="88cad-105">These changes are processed in batches.</span></span>
    
2. <span data-ttu-id="88cad-106">Proces tajmera će se pokrenuti dok se promene ne sinhronizuju.</span><span class="sxs-lookup"><span data-stu-id="88cad-106">The timer job runs until the changes are synced.</span></span>
    
> [!NOTE]
> <span data-ttu-id="88cad-107">Vreme koje je potrebno za pokretanje posla zavisi od broja promena koje treba obraditi.</span><span class="sxs-lookup"><span data-stu-id="88cad-107">The time it takes the job to run depends on the number of changes to process.</span></span> <span data-ttu-id="88cad-108">Veliki broj promena traje duže.</span><span class="sxs-lookup"><span data-stu-id="88cad-108">A large number of changes takes longer.</span></span> <span data-ttu-id="88cad-109">Ugovor o nivou usluge (SLA) navodi da će se promena korisnika u direktorijumu SharePoint online direktorijuma odraziti u aplikaciji korisničkog profila u 24 časa.</span><span class="sxs-lookup"><span data-stu-id="88cad-109">The Service Level Agreement (SLA) states that a change to a user in the SharePoint Online Directory will be reflected in the User Profile Application in 24 hours.</span></span> 
  
[<span data-ttu-id="88cad-110">Više informacija o sinhronizaciji korisničkog profila u sistemu SharePoint online</span><span class="sxs-lookup"><span data-stu-id="88cad-110">More info about user profile sync in SharePoint Online</span></span>](https://go.microsoft.com/fwlink/?linkid=875671)
  

