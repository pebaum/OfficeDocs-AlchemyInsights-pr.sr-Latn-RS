---
title: Deljenje sa spoljnim korisnicima ne radi
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 5/18/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: 69e290e5a13f40ad045086791189a7d0af88240b
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32369512"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a><span data-ttu-id="62a36-102">Otklanjanje problema na deljenje SharePoint sadržaj sa spoljnim korisnicima</span><span class="sxs-lookup"><span data-stu-id="62a36-102">Fix problems sharing SharePoint content with external users</span></span>

<span data-ttu-id="62a36-103">Uverite se da spoljni je uključeno deljenje vaše organizacije:</span><span class="sxs-lookup"><span data-stu-id="62a36-103">Make sure external sharing is turned on for your organization:</span></span>
  
1. <span data-ttu-id="62a36-104">Idite na na [usluge &amp; programske dodatke stranice u Microsoft 365 admin centru](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), i kliknite na **lokacijama**.</span><span class="sxs-lookup"><span data-stu-id="62a36-104">Go to the [Services &amp; add-ins page in the Microsoft 365 admin center](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), and click **Sites**.</span></span>
    
2. <span data-ttu-id="62a36-105">Uverite se da postavka je pretvorila u „Aktivna”.</span><span class="sxs-lookup"><span data-stu-id="62a36-105">Make sure the setting is turned to "On."</span></span> <span data-ttu-id="62a36-106">Ako izaberete „Jedini postojeći spoljnim korisnicima”, uverite se da spoljni korisnik je naveden u centru za admin Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="62a36-106">If "Only existing external users" is selected, make sure the external user is listed in the Microsoft 365 admin center.</span></span>
    
<span data-ttu-id="62a36-107">Uverite se eksterno dijeljenje to je uključeno za lokaciju.</span><span class="sxs-lookup"><span data-stu-id="62a36-107">Make sure external sharing it turned on for the site.</span></span> <span data-ttu-id="62a36-108">Za kolekciju klasične lokacija:</span><span class="sxs-lookup"><span data-stu-id="62a36-108">For a classic site collection:</span></span>
  
1. <span data-ttu-id="62a36-109">U novu SharePoint admin centru, u lijevom oknu, kliknite na **lokacijama**.</span><span class="sxs-lookup"><span data-stu-id="62a36-109">In the new SharePoint admin center, in the left pane, click **sites**.</span></span>
    
2. <span data-ttu-id="62a36-110">Izaberite lokaciju ili lokacije, a na glavnoj traci kliknite **Deljenje**.</span><span class="sxs-lookup"><span data-stu-id="62a36-110">Select the site or sites, and on the ribbon, click **Sharing**.</span></span>
    
<span data-ttu-id="62a36-111">Za lokaciju tima koji pripada grupi programa Office 365 ili lokaciju za komunikaciju:</span><span class="sxs-lookup"><span data-stu-id="62a36-111">For a team site that belongs to an Office 365 group, or a communication site:</span></span>
  
- <span data-ttu-id="62a36-112">Ovi novi tipovi lokacije imati isti deljenja postavljanje kao postavke vašeg širom organizacije, ako se širom organizacije postavka omogućava deljenje datoteka pomoću veze koje ne zahtevaju za prijavljivanje.</span><span class="sxs-lookup"><span data-stu-id="62a36-112">These new site types have the same sharing setting as your organization-wide setting, unless the organization-wide setting allows sharing files using links that don't require sign-in.</span></span> <span data-ttu-id="62a36-113">U ovom slučaju, na lokacijama dozvoli deljenje sa novim i postojećim spoljnim korisnicima koji se prijavite.</span><span class="sxs-lookup"><span data-stu-id="62a36-113">In this case, the sites allow sharing with new and existing external users who sign in.</span></span> <span data-ttu-id="62a36-114">Da biste promenili postavke za pojedine lokacije, koristite novu SharePoint admin centar ili PowerShell.</span><span class="sxs-lookup"><span data-stu-id="62a36-114">To change the setting for specific sites, use the new SharePoint admin center or PowerShell.</span></span> <span data-ttu-id="62a36-115">I [Saznajte više](https://go.microsoft.com/fwlink/?linkid=871863).</span><span class="sxs-lookup"><span data-stu-id="62a36-115">[Learn more](https://go.microsoft.com/fwlink/?linkid=871863).</span></span>
    
> [!NOTE]
> <span data-ttu-id="62a36-116">Spoljni deljenja postavku za bilo koju lokaciju može biti restriktivniji nego što je vaša postavka širom organizacije, ali ne više popustljivog nego postavku širom organizacije.</span><span class="sxs-lookup"><span data-stu-id="62a36-116">The external sharing setting for any site can be more restrictive than your organization-wide setting, but not more permissive than the organization-wide setting.</span></span> 
  

