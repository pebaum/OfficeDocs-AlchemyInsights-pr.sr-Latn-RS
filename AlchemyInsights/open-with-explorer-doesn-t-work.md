---
title: Otvori pomoću programa Explorer ne radi
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: b8f07022-69fe-4112-a2f6-d3a6cedb966c
ms.openlocfilehash: dc939a3451ff4fe95e4aa5a999839a2c532b398c
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713048"
---
# <a name="open-with-explorer-isnt-working"></a><span data-ttu-id="e1c87-102">Otvori pomoću programa Explorer ne radi</span><span class="sxs-lookup"><span data-stu-id="e1c87-102">Open with Explorer isn't working</span></span>

<span data-ttu-id="e1c87-103">Ako se **Otvori pomoću programa Explorer** ili **prikaz u istraživaču datoteka** ne radi uverite se da je usluga Web klijenta podešena tako da se **izvršava** sledeći koraci ispod.</span><span class="sxs-lookup"><span data-stu-id="e1c87-103">If **Open with Explorer** or **View in File Explorer** doesn't work make sure the WebClient service is set to **Running** by following the steps below.</span></span> <span data-ttu-id="e1c87-104">Na primer, možda će biti potrebno mnogo vremena da otvori SharePoint ili OneDrive biblioteku kada usluga nije pokrenuta.</span><span class="sxs-lookup"><span data-stu-id="e1c87-104">For example, it might take a long time to open a SharePoint or OneDrive library when the service is not running.</span></span> 
  
1. <span data-ttu-id="e1c87-105">U okviru Windows pretrage, otkucajte Pokreni, izaberite aplikaciju Pokreni radnu površinu, otkucajte usluge. msc, a zatim izaberite stavku **ENTER**.</span><span class="sxs-lookup"><span data-stu-id="e1c87-105">In the Windows search box, type run, select the Run desktop app, type services.msc, and then select **Enter**.</span></span>
    
2. <span data-ttu-id="e1c87-106">Pomerite se do usluge WebClient i proverite kolonu **statusa** .</span><span class="sxs-lookup"><span data-stu-id="e1c87-106">Scroll down to the WebClient service and check the **Status** column.</span></span> <span data-ttu-id="e1c87-107">Ako status usluge WebClient nije **pokrenut**, dvaput kliknite na uslugu, kliknite na dugme **Start**, a zatim kliknite na dugme **u redu**.</span><span class="sxs-lookup"><span data-stu-id="e1c87-107">If the WebClient service status is not **Running**, double-click the service, click **Start**, and then click **OK**.</span></span> <span data-ttu-id="e1c87-108">Ako je potrebno, omogućite uslugu tako što ćete u okviru " **Tip pokretanja** " izabrati opciju " **ručno** " ili " **Automatsko** ".</span><span class="sxs-lookup"><span data-stu-id="e1c87-108">Enable the service, if needed, by selecting either **Manual** or **Automatic** in the **Startup type** box.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="e1c87-109">Da biste rešili probleme sa otvaranjem u istraživaču datoteka, pogledajte odeljak [Otvaranje u programu Explorer](https://go.microsoft.com/fwlink/?linkid=871665).</span><span class="sxs-lookup"><span data-stu-id="e1c87-109">To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665).</span></span> <span data-ttu-id="e1c87-110">Istražite sinhronizaciju kao bolju alternativu: [sinhronizujte SharePoint datoteke sa novim klijentskim klijentom za sinhronizaciju](https://go.microsoft.com/fwlink/?linkid=871666).</span><span class="sxs-lookup"><span data-stu-id="e1c87-110">Explore sync as a better alternative: [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span> 
  

