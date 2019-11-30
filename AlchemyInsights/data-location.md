---
title: Lokacija podataka
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "945"
- "5300023"
ms.assetid: 3bab036c-dbaa-406a-8b73-1e5f31993436
ms.openlocfilehash: ec8fb91dfe77cb251579ce23eb0579b114b101d9
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/27/2019
ms.locfileid: "39627860"
---
# <a name="data-location"></a><span data-ttu-id="cfd3b-102">Lokacija podataka</span><span class="sxs-lookup"><span data-stu-id="cfd3b-102">Data location</span></span>

<span data-ttu-id="cfd3b-103">Možete da prikažete lokaciju Office 365 tenanta u okviru administratorskog centra ili tako što ćete se povezati sa Exchange online putem PowerShell.</span><span class="sxs-lookup"><span data-stu-id="cfd3b-103">You can view the location of your Office 365 tenant in the admin center or by connecting to Exchange Online via PowerShell.</span></span>


<span data-ttu-id="cfd3b-104">**Admin Center:**</span><span class="sxs-lookup"><span data-stu-id="cfd3b-104">**Admin center:**</span></span>
1. <span data-ttu-id="cfd3b-105">Prijavite se u [admin Center](https://admin.microsoft.com/Adminportal/Home).</span><span class="sxs-lookup"><span data-stu-id="cfd3b-105">Log in to the [admin center](https://admin.microsoft.com/Adminportal/Home).</span></span>
2. <span data-ttu-id="cfd3b-106">Izaberite **Postavke** > za**Organizacioni profil**.</span><span class="sxs-lookup"><span data-stu-id="cfd3b-106">Select **Settings** > **Organization profile**.</span></span>
3. <span data-ttu-id="cfd3b-107">U okviru **lokacije sa podacima**izaberite stavku **Prikaži detalje**.</span><span class="sxs-lookup"><span data-stu-id="cfd3b-107">Under **Data location**, select **View details**.</span></span>


<span data-ttu-id="cfd3b-108">**PowerShell**</span><span class="sxs-lookup"><span data-stu-id="cfd3b-108">**PowerShell:**</span></span>
1. <span data-ttu-id="cfd3b-109">Povezivanje sa Exchange mrežom pomoću Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="cfd3b-109">Connect to Exchange Online by using Windows PowerShell.</span></span>
2. <span data-ttu-id="cfd3b-110">Izvođenje " [get-Organizacionalne jedinice](https://docs.microsoft.com/powershell/module/exchange/active-directory/get-organizationalunit) " cmdme da biste prikazali listu svojih staničnih svojstava.</span><span class="sxs-lookup"><span data-stu-id="cfd3b-110">Execute the [Get-OrganizationalUnit](https://docs.microsoft.com/powershell/module/exchange/active-directory/get-organizationalunit) cmdlet to display a list of your tenant’s properties.</span></span> 
3. <span data-ttu-id="cfd3b-111">Pogledajte svojstvo "OrganizationId".</span><span class="sxs-lookup"><span data-stu-id="cfd3b-111">Look at the OrganizationId property.</span></span>

<span data-ttu-id="cfd3b-112">Kada imate lokaciju podataka za EXO i SPO, možete da utvrdite lokaciju podataka za druge usluge koje možete koristiti sa [mesta na kojima se podaci nalaze](https://products.office.com/where-is-your-data-located).</span><span class="sxs-lookup"><span data-stu-id="cfd3b-112">When you have the data location for EXO and SPO, you can determine the data location for other services you may use from [Where your data is located](https://products.office.com/where-is-your-data-located).</span></span>