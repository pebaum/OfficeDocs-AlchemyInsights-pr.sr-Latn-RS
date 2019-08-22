---
title: Rešavanje problema pomoću otvori pomoću programa Explorer
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
ms.openlocfilehash: 6e67c2916e0c5739f6126064d45e175a7fd6f8d4
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36500229"
---
# <a name="fix-problems-with-open-with-explorer"></a><span data-ttu-id="b0674-102">Rješava probleme sa otvori pomoću programa Explorer</span><span class="sxs-lookup"><span data-stu-id="b0674-102">Fix problems with Open with Explorer</span></span>

<span data-ttu-id="b0674-103">Popravite uobičajene probleme sa otvaranjem biblioteka dokumenata na SharePoint ili OneDrive pomoću komande **Otvori pomoću programa Explorer** :</span><span class="sxs-lookup"><span data-stu-id="b0674-103">Fix common problems with opening a document library in SharePoint or OneDrive using the **Open with Explorer** command:</span></span> 
  
- <span data-ttu-id="b0674-104">Koristite Internet Explorer 10 ili Internet Explorer 11.</span><span class="sxs-lookup"><span data-stu-id="b0674-104">Use Internet Explorer 10 or Internet Explorer 11.</span></span> <span data-ttu-id="b0674-105">**Otvori pomoću programa Explorer** nije kompatibilan sa Microsoft Edge, Google Chrome, Firefox i drugi.</span><span class="sxs-lookup"><span data-stu-id="b0674-105">**Open with Explorer** isn't compatible with Microsoft Edge, Google Chrome, Firefox and others.</span></span> <span data-ttu-id="b0674-106">**Otvori pomoću programa Explorer** je onemogućen u svim pregledačima osim programa Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="b0674-106">**Open with Explorer** is disabled in all browsers except Internet Explorer.</span></span> 
    
- <span data-ttu-id="b0674-107">**Otvori pomoću programa Explorer** nije dostupno u moderne iskustvo za SharePoint biblioteke.</span><span class="sxs-lookup"><span data-stu-id="b0674-107">**Open with Explorer** is not available in the modern experience for SharePoint libraries.</span></span> <span data-ttu-id="b0674-108">Umesto toga, koristite **prikaz u datoteku programa Explorer** .</span><span class="sxs-lookup"><span data-stu-id="b0674-108">Use **View in File Explorer** instead.</span></span> <span data-ttu-id="b0674-109">Izaberite **Opcije za prikaz** \> **prikaz u datoteku programa Explorer**.</span><span class="sxs-lookup"><span data-stu-id="b0674-109">Select **View options** \> **View in File Explorer**.</span></span> <span data-ttu-id="b0674-110">Prikaz u programu Explorer datoteka nije kompatibilna sa Microsoft Edge, Google Chrome, Firefox i drugi.</span><span class="sxs-lookup"><span data-stu-id="b0674-110">View in File Explorer is not compatible with Microsoft Edge, Google Chrome, Firefox and others.</span></span> <span data-ttu-id="b0674-111">**Prikaz u datoteku Explorer** u dostupne samo u programu Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="b0674-111">**View in File Explorer** in available only in Internet Explorer.</span></span> 
    
- <span data-ttu-id="b0674-112">Uverite se da je WebClient usluga pokrenuta.</span><span class="sxs-lookup"><span data-stu-id="b0674-112">Make sure the WebClient service is running.</span></span> <span data-ttu-id="b0674-113">U polje za pretragu u Windows, unesite Pokreni, izaberite pokreni aplikaciju na radnoj površini, upišite services.msc i zatim pritisnite taster Enter.</span><span class="sxs-lookup"><span data-stu-id="b0674-113">In the Windows search box, type run, select the Run desktop app, type services.msc, and then press Enter.</span></span> <span data-ttu-id="b0674-114">Pomerite se do WebClient usluga i uverite se da **Status** kolona prikazuje „Pokretanje”.</span><span class="sxs-lookup"><span data-stu-id="b0674-114">Scroll down to the WebClient service and make sure the **Status** column displays "Running."</span></span> <span data-ttu-id="b0674-115">Ako ne, kliknite dvaput na uslugu, kliknite na dugme **Start**i onda kliknite na **OK**.</span><span class="sxs-lookup"><span data-stu-id="b0674-115">If it doesn't, double-click the service, click **Start**, and then click **OK**.</span></span> <span data-ttu-id="b0674-116">(Možda ćete morati prvo omogućiti uslugu tako što ćete izabrati ili **ručno** ili **automatski** u okviru **Tip pokretanja** .)</span><span class="sxs-lookup"><span data-stu-id="b0674-116">(You might need to first enable the service by selecting either **Manual** or **Automatic** in the **Startup type** box.)</span></span> 
    
> [!NOTE]
> <span data-ttu-id="b0674-117">Otvaranje biblioteke u datoteku Explorer je pri ruci, ako je potrebno da kopirate ili premestite više datoteka i fascikli, jednom, ali ako želite da redovno radite u biblioteci, preporučujemo da ga sa sinhronizacijom.</span><span class="sxs-lookup"><span data-stu-id="b0674-117">Opening a library in File Explorer is handy if you need to copy or move multiple files and folders once, but if you want to regularly work in the library, we recommend syncing it.</span></span> <span data-ttu-id="b0674-118">Rešavanje problema sa otvaranjem u datoteku programa Explorer, potražite [otvoren u Explorer](https://go.microsoft.com/fwlink/?linkid=871665).</span><span class="sxs-lookup"><span data-stu-id="b0674-118">To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665).</span></span> <span data-ttu-id="b0674-119">Za informacije o podešavanju sinhronizacije, vidim [SharePoint sinhronizacije datoteke sa novom klijentu sinhronizaciju OneDrive](https://go.microsoft.com/fwlink/?linkid=871666).</span><span class="sxs-lookup"><span data-stu-id="b0674-119">For info about setting up sync, see [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span>
  
<span data-ttu-id="b0674-120">Pogledajte članak [Kako da koristite komandu „otvori s Explorer” za rešavanje problema u SharePoint Online](https://support.office.com/article/How-to-use-the-Open-with-Explorer-command-to-troubleshoot-issues-in-SharePoint-Online-87155331-0c92-4224-a4c1-da5c21c4ade4) za više informacija.</span><span class="sxs-lookup"><span data-stu-id="b0674-120">Please see the article [How to use the "Open with Explorer" command to troubleshoot issues in SharePoint Online](https://support.office.com/article/How-to-use-the-Open-with-Explorer-command-to-troubleshoot-issues-in-SharePoint-Online-87155331-0c92-4224-a4c1-da5c21c4ade4) for more information.</span></span> 
  

