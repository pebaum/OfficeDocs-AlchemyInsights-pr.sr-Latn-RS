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
ms.custom: Adm_O365
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: 20b538846997c021b6e88596a1e8aff401ea935b
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29900900"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a><span data-ttu-id="d3987-102">Otklanjanje problema na deljenje SharePoint sadržaj sa spoljnim korisnicima</span><span class="sxs-lookup"><span data-stu-id="d3987-102">Fix problems sharing SharePoint content with external users</span></span>

<span data-ttu-id="d3987-103">Uverite se da spoljni je uključeno deljenje vaše organizacije:</span><span class="sxs-lookup"><span data-stu-id="d3987-103">Make sure external sharing is turned on for your organization:</span></span>
  
1. <span data-ttu-id="d3987-104">Idite na na [usluge &amp; programske dodatke stranice u centru za administraciju sistema Office 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), i kliknite na **lokacijama**.</span><span class="sxs-lookup"><span data-stu-id="d3987-104">Go to the [Services &amp; add-ins page in the Office 365 admin center](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), and click **Sites**.</span></span>
    
2. <span data-ttu-id="d3987-p101">Uverite se da postavka je pretvorila u „Aktivna”. Ako izaberete „Jedini postojeći spoljnim korisnicima”, uverite se da spoljni korisnik je naveden u centru za administraciju sistema Office 365.</span><span class="sxs-lookup"><span data-stu-id="d3987-p101">Make sure the setting is turned to "On." If "Only existing external users" is selected, make sure the external user is listed in the Office 365 admin center.</span></span>
    
<span data-ttu-id="d3987-p102">Uverite se eksterno dijeljenje to je uključeno za lokaciju. Za kolekciju klasične lokacija:</span><span class="sxs-lookup"><span data-stu-id="d3987-p102">Make sure external sharing it turned on for the site. For a classic site collection:</span></span>
  
1. <span data-ttu-id="d3987-109">U klasični SharePoint admin centru, u lijevom oknu, kliknite **kolekcije**.</span><span class="sxs-lookup"><span data-stu-id="d3987-109">In the classic SharePoint admin center, in the left pane, click **site collections**.</span></span>
    
2. <span data-ttu-id="d3987-110">Izaberite lokaciju ili lokacije, a na glavnoj traci kliknite **Deljenje**.</span><span class="sxs-lookup"><span data-stu-id="d3987-110">Select the site or sites, and on the ribbon, click **Sharing**.</span></span>
    
<span data-ttu-id="d3987-111">Za lokaciju tima koji pripada grupi programa Office 365 ili lokaciju za komunikaciju:</span><span class="sxs-lookup"><span data-stu-id="d3987-111">For a team site that belongs to an Office 365 group, or a communication site:</span></span>
  
- <span data-ttu-id="d3987-p103">Ovi novi tipovi lokacije imati isti deljenja postavljanje kao postavke vašeg širom organizacije, ako se širom organizacije postavka omogućava deljenje datoteka pomoću veze koje ne zahtevaju za prijavljivanje. U ovom slučaju, na lokacijama dozvoli deljenje sa novim i postojećim spoljnim korisnicima koji se prijavite. Da biste promenili postavke za pojedine lokacije, koristite novu SharePoint admin centar (pregled) ili PowerShell. I [Saznajte više](https://go.microsoft.com/fwlink/?linkid=871863).</span><span class="sxs-lookup"><span data-stu-id="d3987-p103">These new site types have the same sharing setting as your organization-wide setting, unless the organization-wide setting allows sharing files using links that don't require sign-in. In this case, the sites allow sharing with new and existing external users who sign in. To change the setting for specific sites, use the new SharePoint admin center (preview) or PowerShell. [Learn more](https://go.microsoft.com/fwlink/?linkid=871863).</span></span>
    
> [!NOTE]
> <span data-ttu-id="d3987-116">Spoljni deljenja postavku za bilo koju lokaciju može biti restriktivniji nego što je vaša postavka širom organizacije, ali ne više popustljivog nego postavku širom organizacije.</span><span class="sxs-lookup"><span data-stu-id="d3987-116">The external sharing setting for any site can be more restrictive than your organization-wide setting, but not more permissive than the organization-wide setting.</span></span> 
  

