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
ms.openlocfilehash: 0e683c8266d425be95e87c590d4cb5d56108721a
ms.sourcegitcommit: 71978e2bb779b5955fd113f84512b83321b26912
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/26/2019
ms.locfileid: "37207275"
---
# <a name="data-location"></a><span data-ttu-id="fdd52-102">Lokacija podataka</span><span class="sxs-lookup"><span data-stu-id="fdd52-102">Data location</span></span>

<span data-ttu-id="fdd52-103">Možete da prikažete lokaciju Office 365 tenanta u okviru administratorskog centra ili tako što ćete se povezati sa Exchange online putem PowerShell.</span><span class="sxs-lookup"><span data-stu-id="fdd52-103">You can view the location of your Office 365 tenant in the admin center or by connecting to Exchange Online via PowerShell.</span></span>


<span data-ttu-id="fdd52-104">**Admin Center:**</span><span class="sxs-lookup"><span data-stu-id="fdd52-104">**Admin center:**</span></span>
1. <span data-ttu-id="fdd52-105">Prijavite se u [admin Center](https://admin.microsoft.com/Adminportal/Home).</span><span class="sxs-lookup"><span data-stu-id="fdd52-105">Log in to the [admin center](https://admin.microsoft.com/Adminportal/Home).</span></span>
2. <span data-ttu-id="fdd52-106">Izaberite **Postavke** > za**Organizacioni profil**.</span><span class="sxs-lookup"><span data-stu-id="fdd52-106">Select **Settings** > **Organization profile**.</span></span>
3. <span data-ttu-id="fdd52-107">U okviru **lokacije sa podacima**izaberite stavku **Prikaži detalje**.</span><span class="sxs-lookup"><span data-stu-id="fdd52-107">Under **Data location**, select **View details**.</span></span>


<span data-ttu-id="fdd52-108">**PowerShell**</span><span class="sxs-lookup"><span data-stu-id="fdd52-108">**PowerShell:**</span></span>
1. <span data-ttu-id="fdd52-109">Povezivanje sa Exchange mrežom pomoću Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="fdd52-109">Connect to Exchange Online by using Windows PowerShell.</span></span>
2. <span data-ttu-id="fdd52-110">Izvođenje " [get-Organizacionalne jedinice](https://docs.microsoft.com/en-us/powershell/module/exchange/active-directory/get-organizationalunit) " cmdme da biste prikazali listu svojih staničnih svojstava.</span><span class="sxs-lookup"><span data-stu-id="fdd52-110">Execute the [Get-OrganizationalUnit](https://docs.microsoft.com/en-us/powershell/module/exchange/active-directory/get-organizationalunit) cmdlet to display a list of your tenant’s properties.</span></span> 
3. <span data-ttu-id="fdd52-111">Pogledajte svojstvo "OrganizationId".</span><span class="sxs-lookup"><span data-stu-id="fdd52-111">Look at the OrganizationId property.</span></span>

<span data-ttu-id="fdd52-112">Kada imate lokaciju podataka za EXO i SPO, možete da utvrdite lokaciju podataka za druge usluge koje možete koristiti sa [mesta na kojima se podaci nalaze](https://products.office.com/where-is-your-data-located).</span><span class="sxs-lookup"><span data-stu-id="fdd52-112">When you have the data location for EXO and SPO, you can determine the data location for other services you may use from [Where your data is located](https://products.office.com/where-is-your-data-located).</span></span>