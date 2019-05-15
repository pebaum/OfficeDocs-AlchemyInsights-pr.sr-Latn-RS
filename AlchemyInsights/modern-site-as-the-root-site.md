---
title: Moderna lokaciju kao osnovne lokacije
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 6166493f79379f44b1a9bbbaca6becfe624fe912
ms.sourcegitcommit: 22ce2315c8cf643137ab3420cdc1cda41433d44a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/14/2019
ms.locfileid: "34057767"
---
# <a name="modern-site-as-root-site"></a><span data-ttu-id="cbf13-102">Moderna lokaciju kao osnovna lokacija</span><span class="sxs-lookup"><span data-stu-id="cbf13-102">Modern site as root site</span></span>

<span data-ttu-id="cbf13-103">[Cilj izdavanja](https://docs.microsoft.com/en-us/office365/admin/manage/release-options-in-office-365?view=o365-worldwide) kupci sada može da omogući moderna komunikacija iskustvo lokacije na klasični matičnoj lokaciji od svoje SharePoint stanar.</span><span class="sxs-lookup"><span data-stu-id="cbf13-103">[Target Release](https://docs.microsoft.com/en-us/office365/admin/manage/release-options-in-office-365?view=o365-worldwide) customers can now enable the modern communication site experience at the classic root site of their SharePoint tenant.</span></span>

<span data-ttu-id="cbf13-104">Ovu funkciju možete aktivirati tako što ćete pokrenuti neki jednostavan PowerShell cmdlet.</span><span class="sxs-lookup"><span data-stu-id="cbf13-104">This feature can be activated by running a simple PowerShell cmdlet.</span></span> <span data-ttu-id="cbf13-105">Na uspešno izvršenje na PowerShell command(s), osnovne lokacije će imati novu matičnu stranicu lokacije komunikacije.</span><span class="sxs-lookup"><span data-stu-id="cbf13-105">On the successful execution of the PowerShell command(s), the root site will have a new communication site home page.</span></span> <span data-ttu-id="cbf13-106">Detalji o zahtevima za PowerShell cmdlet i funkcija dostupnih u članku [Omogući-SPOCommSite](https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/Enable-SPOCommSite?view=sharepoint-ps).</span><span class="sxs-lookup"><span data-stu-id="cbf13-106">Details about the PowerShell cmdlet and feature requirements are available in the article [Enable-SPOCommSite](https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/Enable-SPOCommSite?view=sharepoint-ps).</span></span> 

<span data-ttu-id="cbf13-107">Postepeno Valjaжemo se ovo, sa po podrazumevanoj vrednosti, na meti puštanje kupcima 2019 početkom maja, a slepi kolosek biće na raspolaganju širom sveta do kraja juna 2019.</span><span class="sxs-lookup"><span data-stu-id="cbf13-107">We'll be gradually rolling this out, off by default, to Targeted Release customers in early May 2019, and the roll out will be available worldwide by the end of June 2019.</span></span> <span data-ttu-id="cbf13-108">I dalje se odnose na [Centar za poruke](https://admin.microsoft.com/AdminPortal/Home#/MessageCenter) za druge nove funkcije sa modernom.</span><span class="sxs-lookup"><span data-stu-id="cbf13-108">Continue to refer to the [Message Center](https://admin.microsoft.com/AdminPortal/Home#/MessageCenter) for other new features with Modern.</span></span> 

<span data-ttu-id="cbf13-109">**Važno**: nemojte brisati svoje klasične osnovne lokacije da biste kreirali lokaciju moderne komunikacije.</span><span class="sxs-lookup"><span data-stu-id="cbf13-109">**Important**: Do not delete your classic root site to create a modern Communication Site.</span></span> <span data-ttu-id="cbf13-110">Ovo je Microsoft ne podržava.</span><span class="sxs-lookup"><span data-stu-id="cbf13-110">This is not supported by Microsoft.</span></span> <span data-ttu-id="cbf13-111">Brisanje osnovne lokacije će da sve SharePoint lokacije u vašoj organizaciji može pristupiti svim korisnicima, dok ne vraćanje lokacije ili da kreirate novu lokaciju na istom URL adresi.</span><span class="sxs-lookup"><span data-stu-id="cbf13-111">Deleting the root site will make all SharePoint sites in your organization inaccessible to all users, until you restore the site or create a new site at the same URL.</span></span> 
 
 