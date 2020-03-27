---
title: Trajno brisanje sajta u sistemu SharePoint
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.custom: ''
ms.assetid:
- "5200006"
- "4391"
ms.openlocfilehash: 263317339d965d173a5a038fa006e0ce6f8476cc
ms.sourcegitcommit: da04e79b6072321caa16a6ceea6eb5f15de22394
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/25/2020
ms.locfileid: "42955239"
---
# <a name="permanently-delete-a-site-in-sharepoint"></a><span data-ttu-id="a7e66-102">Trajno brisanje sajta u sistemu SharePoint</span><span class="sxs-lookup"><span data-stu-id="a7e66-102">Permanently delete a site in SharePoint</span></span>

<span data-ttu-id="a7e66-103">Da biste ponovo koristili URL adresu sa izbrisanog sajta (radi ponovnog kreiranja sajta) ili da biste trajno izbrisali sajt zato što više nije u upotrebi, možete da koristite opciju **Trajno izbriši** u novom SharePoint centru administracije.</span><span class="sxs-lookup"><span data-stu-id="a7e66-103">To reuse a URL from a deleted site (to recreate a site), or to permanently delete a site because it's no longer in use, you can use **Permanently Delete** from the New SharePoint Admin Center.</span></span> 

1. <span data-ttu-id="a7e66-104">Idite na [stranicu „Izbrisani sajtovi“ u novom SharePoint centru administracije](https://admin.microsoft.com/sharepoint?page=recycleBin&modern=true) i prijavite se pomoću naloga koji ima administratorske dozvole za organizaciju.</span><span class="sxs-lookup"><span data-stu-id="a7e66-104">Go to the [Deleted sites page of the new SharePoint admin center](https://admin.microsoft.com/sharepoint?page=recycleBin&modern=true) and sign in with an account that has admin permissions for your organization.</span></span> 

2. <span data-ttu-id="a7e66-105">U levoj koloni izaberite sajt.</span><span class="sxs-lookup"><span data-stu-id="a7e66-105">In the left column, select a site.</span></span> 

3. <span data-ttu-id="a7e66-106">Izaberite stavku **Trajno izbriši**.</span><span class="sxs-lookup"><span data-stu-id="a7e66-106">Click **Permanently Delete**.</span></span> 

<span data-ttu-id="a7e66-107">**Napomena**: Nije moguće trajno izbrisati sajtove povezane sa grupama u novom SharePoint centru administracije.</span><span class="sxs-lookup"><span data-stu-id="a7e66-107">**Note**: Group-connected sites cannot be permanently deleted from the New SharePoint Admin Center.</span></span> <span data-ttu-id="a7e66-108">Umesto toga ćete morati da koristite [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-spodeletedsite).</span><span class="sxs-lookup"><span data-stu-id="a7e66-108">[Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-spodeletedsite) will need to be used instead.</span></span>  

<span data-ttu-id="a7e66-109">Više informacija potražite u članku [Trajno brisanje sajta](https://docs.microsoft.com/sharepoint/delete-site-collection#permanently-delete-a-site).</span><span class="sxs-lookup"><span data-stu-id="a7e66-109">For more info, see [Permanently delete a site](https://docs.microsoft.com/sharepoint/delete-site-collection#permanently-delete-a-site).</span></span> 
