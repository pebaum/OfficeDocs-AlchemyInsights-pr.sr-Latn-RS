---
title: Vraćanje izbrisane lokacije u prethodno stanje
ms.author: kaarins
author: kaarins
manager: scotv
ms.date: 5/1/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cf7521c3-97b4-465a-97eb-6c0a41338a30
ms.openlocfilehash: 9e4e9ade058c60ecd7a6ce1b2a40c4996ac5676f
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/18/2019
ms.locfileid: "36552492"
---
# <a name="restore-a-deleted-site"></a><span data-ttu-id="56b0a-102">Vraćanje izbrisane lokacije u prethodno stanje</span><span class="sxs-lookup"><span data-stu-id="56b0a-102">Restore a deleted site</span></span>

<span data-ttu-id="56b0a-103">Kada administrator izbriše lokaciju, ona se smešta u korpu za otpatke kolekcije lokacija, gde se čuva već 93 dana pre nego što se trajno izbriše.</span><span class="sxs-lookup"><span data-stu-id="56b0a-103">When an admin deletes a site , it's placed in the site collection Recycle Bin, where it's kept for 93 days before it's permanently deleted.</span></span> <span data-ttu-id="56b0a-104">Da biste vratili lokaciju u prethodno stanje:</span><span class="sxs-lookup"><span data-stu-id="56b0a-104">To restore the site:</span></span>
  
1. <span data-ttu-id="56b0a-105">U novom SharePoint administratoru centra izaberite stavku **Korpa za otpatke** na glavnoj traci.</span><span class="sxs-lookup"><span data-stu-id="56b0a-105">In the new SharePoint admin center, click **Recycle Bin** on the ribbon.</span></span> 
    
2. <span data-ttu-id="56b0a-106">Potvrdite izbor u polju za potvrdu pored kolekcije lokacija koju želite da vratite u prethodno stanje.</span><span class="sxs-lookup"><span data-stu-id="56b0a-106">Select the check box next to the site collection you want to restore.</span></span>
    
3. <span data-ttu-id="56b0a-107">Kliknite na **obnovi izbrisane stavke**.</span><span class="sxs-lookup"><span data-stu-id="56b0a-107">Click **Restore Deleted Items**.</span></span>
    
<span data-ttu-id="56b0a-108">Da biste vratili izbrisanu komunikacionu lokaciju, možete koristiti novi SharePoint admin Center.</span><span class="sxs-lookup"><span data-stu-id="56b0a-108">To restore a deleted communication site, you can use the new SharePoint admin center.</span></span> <span data-ttu-id="56b0a-109">U suprotnom, treba da koristite Microsoft PowerShell.</span><span class="sxs-lookup"><span data-stu-id="56b0a-109">Otherwise, you need to use Microsoft PowerShell.</span></span> <span data-ttu-id="56b0a-110">Da biste vratili lokaciju koja pripada Office 365 grupi, potrebno je da vratite grupu u prethodno stanje u Exchange admin Center.</span><span class="sxs-lookup"><span data-stu-id="56b0a-110">To restore a site that belongs to an Office 365 group, you need to restore the group in the Exchange admin center.</span></span> <span data-ttu-id="56b0a-111">Grupe se mogu obnoviti na 30 dana nakon brisanja.</span><span class="sxs-lookup"><span data-stu-id="56b0a-111">Groups can be restored for 30 days after they're deleted.</span></span>
  

