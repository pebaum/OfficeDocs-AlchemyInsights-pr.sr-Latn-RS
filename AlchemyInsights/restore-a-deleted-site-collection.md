---
title: Vraćanje izbrisane lokacije u prethodno stanje
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cf7521c3-97b4-465a-97eb-6c0a41338a30
ms.openlocfilehash: edf851da951e163f30660d524049abe0798a8314
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40048810"
---
# <a name="restore-a-deleted-site"></a><span data-ttu-id="9d9c3-102">Vraćanje izbrisane lokacije u prethodno stanje</span><span class="sxs-lookup"><span data-stu-id="9d9c3-102">Restore a deleted site</span></span>

<span data-ttu-id="9d9c3-103">Kada administrator izbriše SharePoint lokaciju, ona se nalazi u korpi za otpatke kolekcije lokacija, gde se čuva već 93 dana pre nego što se trajno izbriše.</span><span class="sxs-lookup"><span data-stu-id="9d9c3-103">When an admin deletes a SharePoint site, it's placed in the site collection Recycle Bin, where it's kept for 93 days before it's permanently deleted.</span></span> <span data-ttu-id="9d9c3-104">Da biste vratili lokaciju u prethodno stanje:</span><span class="sxs-lookup"><span data-stu-id="9d9c3-104">To restore the site:</span></span>
  
1. <span data-ttu-id="9d9c3-105">U novom SharePoint administratoru centra izaberite stavku **Korpa za otpatke** na glavnoj traci.</span><span class="sxs-lookup"><span data-stu-id="9d9c3-105">In the new SharePoint admin center, click **Recycle Bin** on the ribbon.</span></span> 
    
2. <span data-ttu-id="9d9c3-106">Potvrdite izbor u polju za potvrdu pored kolekcije lokacija koju želite da vratite u prethodno stanje.</span><span class="sxs-lookup"><span data-stu-id="9d9c3-106">Select the check box next to the site collection you want to restore.</span></span>
    
3. <span data-ttu-id="9d9c3-107">Kliknite na **obnovi izbrisane stavke**.</span><span class="sxs-lookup"><span data-stu-id="9d9c3-107">Click **Restore Deleted Items**.</span></span>
    
<span data-ttu-id="9d9c3-108">Da biste vratili izbrisanu komunikacionu lokaciju, možete koristiti novi SharePoint admin Center.</span><span class="sxs-lookup"><span data-stu-id="9d9c3-108">To restore a deleted communication site, you can use the new SharePoint admin center.</span></span> <span data-ttu-id="9d9c3-109">U suprotnom, treba da koristite Microsoft PowerShell.</span><span class="sxs-lookup"><span data-stu-id="9d9c3-109">Otherwise, you need to use Microsoft PowerShell.</span></span> <span data-ttu-id="9d9c3-110">Da biste vratili lokaciju koja pripada Office 365 grupi, potrebno je da vratite grupu u prethodno stanje u Exchange admin Center.</span><span class="sxs-lookup"><span data-stu-id="9d9c3-110">To restore a site that belongs to an Office 365 group, you need to restore the group in the Exchange admin center.</span></span> <span data-ttu-id="9d9c3-111">Grupe se mogu obnoviti na 30 dana nakon brisanja.</span><span class="sxs-lookup"><span data-stu-id="9d9c3-111">Groups can be restored for 30 days after they're deleted.</span></span>
  

