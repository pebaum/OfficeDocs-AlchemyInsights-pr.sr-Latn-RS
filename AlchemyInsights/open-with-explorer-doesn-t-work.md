---
title: Otvoriti pomoću programa Explorer ne radi
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 12/10/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: b8f07022-69fe-4112-a2f6-d3a6cedb966c
ms.openlocfilehash: 73d33e50449345c312abdd39afcc36e0c95fd1c4
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/22/2019
ms.locfileid: "30764922"
---
# <a name="open-with-explorer-isnt-working"></a><span data-ttu-id="efee5-102">Otvoriti pomoću programa Explorer ne radi</span><span class="sxs-lookup"><span data-stu-id="efee5-102">Open with Explorer isn't working</span></span>

<span data-ttu-id="efee5-103">Ako **Otvori pomoću programa Explorer** ili **prikaz u datoteku Explorer** ne radi se WebClient servis je podešen da **radi** prateći korake ispod.</span><span class="sxs-lookup"><span data-stu-id="efee5-103">If **Open with Explorer** or **View in File Explorer** doesn't work make sure the WebClient service is set to **Running** by following the steps below.</span></span> <span data-ttu-id="efee5-104">Na primer, to može potrajati dugo vremena da biste otvorili biblioteku SharePoint ili OneDrive kada usluga nije pokrenuta.</span><span class="sxs-lookup"><span data-stu-id="efee5-104">For example, it might take a long time to open a SharePoint or OneDrive library when the service is not running.</span></span> 
  
1. <span data-ttu-id="efee5-105">U polje za pretragu Windows, tip pokrenuli, izaberite pokreni aplikaciju na radnoj površini, upišite services.msc i zatim izaberite **Enter**.</span><span class="sxs-lookup"><span data-stu-id="efee5-105">In the Windows search box, type run, select the Run desktop app, type services.msc, and then select **Enter**.</span></span>
    
2. <span data-ttu-id="efee5-106">Pomerite se do WebClient servis i proveri **Status** kolone.</span><span class="sxs-lookup"><span data-stu-id="efee5-106">Scroll down to the WebClient service and check the **Status** column.</span></span> <span data-ttu-id="efee5-107">Ako WebClient status usluga nije **pokrenuta**, kliknite dvaput na uslugu, kliknite na dugme **Start**i onda kliknite na **OK**.</span><span class="sxs-lookup"><span data-stu-id="efee5-107">If the WebClient service status is not **Running**, double-click the service, click **Start**, and then click **OK**.</span></span> <span data-ttu-id="efee5-108">Omogućite uslugu, ako je potrebno, tako što ćete izabrati ili **ručno** ili **automatski** u okviru **Tip pokretanja** .</span><span class="sxs-lookup"><span data-stu-id="efee5-108">Enable the service, if needed, by selecting either **Manual** or **Automatic** in the **Startup type** box.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="efee5-109">Rešavanje problema sa otvaranjem u datoteku programa Explorer, potražite [otvoren u Explorer](https://go.microsoft.com/fwlink/?linkid=871665).</span><span class="sxs-lookup"><span data-stu-id="efee5-109">To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665).</span></span> <span data-ttu-id="efee5-110">Istražite Prevod kao bolju alternativu: [SharePoint sinhronizacije datoteke sa novom klijentu sinhronizaciju OneDrive](https://go.microsoft.com/fwlink/?linkid=871666).</span><span class="sxs-lookup"><span data-stu-id="efee5-110">Explore sync as a better alternative: [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span> 
  

