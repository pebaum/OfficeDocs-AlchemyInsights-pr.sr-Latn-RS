---
title: Rešavanje problema koji koriste opciju "Otvori pomoću programa Explorer"
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
ms.assetid: ed852342-e33f-4450-8400-63d30df09476
ms.openlocfilehash: a9ab7dd27e4dc1bd76c93cc81260616063e638ed
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/04/2019
ms.locfileid: "36742747"
---
# <a name="fix-problems-with-open-with-explorer"></a><span data-ttu-id="467d4-102">Rešavanje problema sa otvorenim programom Explorer</span><span class="sxs-lookup"><span data-stu-id="467d4-102">Fix problems with Open with Explorer</span></span>

<span data-ttu-id="467d4-103">Rešavanje uobičajenih problema sa otvaranjem biblioteke dokumenata u sistemu SharePoint ili OneDrive pomoću komande " **Otvori pomoću programa Explorer** ":</span><span class="sxs-lookup"><span data-stu-id="467d4-103">Fix common problems with opening a document library in SharePoint or OneDrive using the **Open with Explorer** command:</span></span> 
  
- <span data-ttu-id="467d4-104">Koristite Internet Explorer 10 ili Internet Explorer 11.</span><span class="sxs-lookup"><span data-stu-id="467d4-104">Use Internet Explorer 10 or Internet Explorer 11.</span></span> <span data-ttu-id="467d4-105">**Otvorite sa programom Explorer** nije kompatibilan sa sistemom Microsoft Edge, Google hrom, Firefox i drugi.</span><span class="sxs-lookup"><span data-stu-id="467d4-105">**Open with Explorer** isn't compatible with Microsoft Edge, Google Chrome, Firefox and others.</span></span> <span data-ttu-id="467d4-106">**Otvaranje sa programom Explorer** je onemogućeno u svim pregledačima osim programa Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="467d4-106">**Open with Explorer** is disabled in all browsers except Internet Explorer.</span></span> 
    
- <span data-ttu-id="467d4-107">**Otvaranje pomoću programa Explorer** nije dostupno u modernom iskustvu za SharePoint biblioteke.</span><span class="sxs-lookup"><span data-stu-id="467d4-107">**Open with Explorer** is not available in the modern experience for SharePoint libraries.</span></span> <span data-ttu-id="467d4-108">Umesto toga, koristite **prikaz u istraživaču datoteka** .</span><span class="sxs-lookup"><span data-stu-id="467d4-108">Use **View in File Explorer** instead.</span></span> <span data-ttu-id="467d4-109">Izaberite prikaz **opcija** \> prikaza **u istraživaču datoteka**.</span><span class="sxs-lookup"><span data-stu-id="467d4-109">Select **View options** \> **View in File Explorer**.</span></span> <span data-ttu-id="467d4-110">Prikaz u istraživaču datoteka nije kompatibilan sa sistemom Microsoft Edge, Google hrom, Firefox i drugi.</span><span class="sxs-lookup"><span data-stu-id="467d4-110">View in File Explorer is not compatible with Microsoft Edge, Google Chrome, Firefox and others.</span></span> <span data-ttu-id="467d4-111">**Prikaži u istraživaču datoteka** dostupnim samo u programu Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="467d4-111">**View in File Explorer** in available only in Internet Explorer.</span></span> 
    
- <span data-ttu-id="467d4-112">Proverite da li je usluga WebClient pokrenuta.</span><span class="sxs-lookup"><span data-stu-id="467d4-112">Make sure the WebClient service is running.</span></span> <span data-ttu-id="467d4-113">U okviru Windows pretrage, otkucajte Pokreni, izaberite aplikaciju Pokreni radnu površinu, otkucajte usluge. msc, a zatim pritisnite taster ENTER.</span><span class="sxs-lookup"><span data-stu-id="467d4-113">In the Windows search box, type run, select the Run desktop app, type services.msc, and then press Enter.</span></span> <span data-ttu-id="467d4-114">Pomerite se nadole do usluge WebClient i uverite se da kolona " **status** " prikazuje "pokrenuto".</span><span class="sxs-lookup"><span data-stu-id="467d4-114">Scroll down to the WebClient service and make sure the **Status** column displays "Running."</span></span> <span data-ttu-id="467d4-115">Ako ne postoji, kliknite dvaput na uslugu, kliknite na dugme " **Start**" i zatim kliknite na dugme **"u redu"**.</span><span class="sxs-lookup"><span data-stu-id="467d4-115">If it doesn't, double-click the service, click **Start**, and then click **OK**.</span></span> <span data-ttu-id="467d4-116">(Možda ćete prvo morati da omogućite uslugu tako što ćete u okviru " **Tip pokretanja** " izabrati opciju " **ručno** " ili " **Automatsko** ".)</span><span class="sxs-lookup"><span data-stu-id="467d4-116">(You might need to first enable the service by selecting either **Manual** or **Automatic** in the **Startup type** box.)</span></span> 
    
> [!NOTE]
> <span data-ttu-id="467d4-117">Otvaranje biblioteke u istraživaču datoteka je korisno ako je potrebno da kopirate ili premestite više datoteka i fascikli, ali ako želite redovno da radite u biblioteci, preporučujemo da je sinhronizujete.</span><span class="sxs-lookup"><span data-stu-id="467d4-117">Opening a library in File Explorer is handy if you need to copy or move multiple files and folders once, but if you want to regularly work in the library, we recommend syncing it.</span></span> <span data-ttu-id="467d4-118">Da biste rešili probleme sa otvaranjem u istraživaču datoteka, pogledajte odeljak [Otvaranje u programu Explorer](https://go.microsoft.com/fwlink/?linkid=871665).</span><span class="sxs-lookup"><span data-stu-id="467d4-118">To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665).</span></span> <span data-ttu-id="467d4-119">Više informacija o podešavanju sinhronizacije potražite u članku [Sinhronizovanje SharePoint datoteka sa novim OneDrive klijentom za sinhronizaciju](https://go.microsoft.com/fwlink/?linkid=871666).</span><span class="sxs-lookup"><span data-stu-id="467d4-119">For info about setting up sync, see [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span>
  
<span data-ttu-id="467d4-120">Pogledajte članak [Kako da koristite komandu "Otvori pomoću programa Explorer" za više informacija o rešavanju problema na lokaciji SharePoint online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/troubleshoot-issues-using-open-with-explorer) .</span><span class="sxs-lookup"><span data-stu-id="467d4-120">Please see the article [How to use the "Open with Explorer" command to troubleshoot issues in SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/troubleshoot-issues-using-open-with-explorer) for more information.</span></span> 
  

