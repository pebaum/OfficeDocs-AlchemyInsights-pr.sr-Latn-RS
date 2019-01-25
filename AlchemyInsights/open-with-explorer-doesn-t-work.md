---
title: Otvoriti pomoću programa Explorer ne radi
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 12/10/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: b8f07022-69fe-4112-a2f6-d3a6cedb966c
ms.openlocfilehash: b55fc7bd5670e655334ef7be368b245c8899633a
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/24/2019
ms.locfileid: "29487121"
---
# <a name="open-with-explorer-isnt-working"></a><span data-ttu-id="bb1f3-102">Otvoriti pomoću programa Explorer ne radi</span><span class="sxs-lookup"><span data-stu-id="bb1f3-102">Open with Explorer isn't working</span></span>

<span data-ttu-id="bb1f3-p101">Ako **Otvori pomoću programa Explorer** ili **prikaz u datoteku Explorer** ne radi se WebClient servis je podešen da **radi** prateći korake ispod. Na primer, to može potrajati dugo vremena da biste otvorili biblioteku SharePoint ili OneDrive kada usluga nije pokrenuta.</span><span class="sxs-lookup"><span data-stu-id="bb1f3-p101">If **Open with Explorer** or **View in File Explorer** doesn't work make sure the WebClient service is set to **Running** by following the steps below. For example, it might take a long time to open a SharePoint or OneDrive library when the service is not running.</span></span> 
  
1. <span data-ttu-id="bb1f3-105">U polje za pretragu Windows, tip pokrenuli, izaberite pokreni aplikaciju na radnoj površini, upišite services.msc i zatim izaberite **Enter**.</span><span class="sxs-lookup"><span data-stu-id="bb1f3-105">In the Windows search box, type run, select the Run desktop app, type services.msc, and then select **Enter**.</span></span>
    
2. <span data-ttu-id="bb1f3-p102">Pomerite se do WebClient servis i proveri **Status** kolone. Ako WebClient status usluga nije **pokrenuta**, kliknite dvaput na uslugu, kliknite na dugme **Start**i onda kliknite na **OK**. Omogućite uslugu, ako je potrebno, tako što ćete izabrati ili **ručno** ili **automatski** u okviru **Tip pokretanja** .</span><span class="sxs-lookup"><span data-stu-id="bb1f3-p102">Scroll down to the WebClient service and check the **Status** column. If the WebClient service status is not **Running**, double-click the service, click **Start**, and then click **OK**. Enable the service, if needed, by selecting either **Manual** or **Automatic** in the **Startup type** box.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="bb1f3-p103">Rešavanje problema sa otvaranjem u datoteku programa Explorer, potražite [otvoren u Explorer](https://go.microsoft.com/fwlink/?linkid=871665). Istražite Prevod kao bolju alternativu: [SharePoint sinhronizacije datoteke sa novom klijentu sinhronizaciju OneDrive](https://go.microsoft.com/fwlink/?linkid=871666).</span><span class="sxs-lookup"><span data-stu-id="bb1f3-p103">To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665). Explore sync as a better alternative: [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span> 
  

