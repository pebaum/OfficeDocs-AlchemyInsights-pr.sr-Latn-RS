---
title: Kreiranje SharePoint lokacije
ms.author: pebaum
author: todmccoy
ms.audience: Admin
ms.topic: article
ms.collection: Adm_O365
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "5200004"
- "3911416"
- "1386"
- "2303"
ms.assetid: e62b9f80-b017-42dc-9464-f4e32c19d6c9
ms.openlocfilehash: e1e71ae9401448ed18058f6307302dcbaf773649
ms.sourcegitcommit: 317eeed39c7777a922442992d67733726c41d9e1
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/04/2020
ms.locfileid: "41770869"
---
# <a name="create-a-sharepoint-site"></a><span data-ttu-id="2963f-102">Kreiranje SharePoint lokacije</span><span class="sxs-lookup"><span data-stu-id="2963f-102">Create a SharePoint site</span></span>

<span data-ttu-id="2963f-103">Kreirajte ili Upravljajte lokacijama sa [aktivnih lokacija](https://admin.microsoft.com/sharepoint?page=sitemanagement&modern=true) u sistemu SharePoint admin Center.</span><span class="sxs-lookup"><span data-stu-id="2963f-103">Create or manage sites from [Active Sites](https://admin.microsoft.com/sharepoint?page=sitemanagement&modern=true) in the SharePoint Admin Center.</span></span> <span data-ttu-id="2963f-104">Više informacija potražite u članku [Upravljanje lokacijama u novom SharePoint administratoru centra](https://docs.microsoft.com/sharepoint/manage-site-creation).</span><span class="sxs-lookup"><span data-stu-id="2963f-104">For more info, see [Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-site-creation).</span></span> 

## <a name="tips"></a><span data-ttu-id="2963f-105">Saveti:</span><span class="sxs-lookup"><span data-stu-id="2963f-105">Tips:</span></span>

- <span data-ttu-id="2963f-106">**Ne možete** da kreirate lokaciju sa istom URL adresom postojeće lokacije.</span><span class="sxs-lookup"><span data-stu-id="2963f-106">You **cannot** create a site with the same URL of an existing site.</span></span> <span data-ttu-id="2963f-107">Ako ste izbrisali lokaciju i želite da ponovo koristite URL adresu, moguće je da izbrisana lokacija još uvek postoji pod [izbrisanim lokacijama](https://admin.microsoft.com/sharepoint?page=recyclebin&modern=true).</span><span class="sxs-lookup"><span data-stu-id="2963f-107">If you deleted a site and are wishing to re-use the URL, it's possible the deleted site still exists under [Deleted sites](https://admin.microsoft.com/sharepoint?page=recyclebin&modern=true).</span></span> <span data-ttu-id="2963f-108">Ova lokacija će morati da bude trajno izbrisana da bi se ponovo koristila URL adresa.</span><span class="sxs-lookup"><span data-stu-id="2963f-108">The site will need to be permanently deleted to re-use the URL.</span></span> <span data-ttu-id="2963f-109">Da biste potpuno uklonili lokaciju sa programom PowerShell, pogledajte primer " [Ukloni-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) ".</span><span class="sxs-lookup"><span data-stu-id="2963f-109">To completely remove a site with Powershell, see the [Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) cmdlet example.</span></span>
- <span data-ttu-id="2963f-110">Neki korisnici možda neće moći da kreiraju lokaciju.</span><span class="sxs-lookup"><span data-stu-id="2963f-110">Some users may not be able to create a site.</span></span> <span data-ttu-id="2963f-111">[Pogledajte odeljak upravljanje kreiranjem lokacije na lokaciji SharePoint online](https://docs.microsoft.com/sharepoint/manage-site-creation).</span><span class="sxs-lookup"><span data-stu-id="2963f-111">[See Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).</span></span>
- <span data-ttu-id="2963f-112">Moguće je da je lokacija zaglavljena pri **kreiranju** duže od očekivanog.</span><span class="sxs-lookup"><span data-stu-id="2963f-112">It's possible the site appears stuck at **Creating** longer than expected.</span></span> <span data-ttu-id="2963f-113">Ako je prošlo više od 24 časa od kada ste prvi put videli ovaj problem, molimo vas da prijavite tiket za podršku.</span><span class="sxs-lookup"><span data-stu-id="2963f-113">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="2963f-114">U mnogim slučajevima već radimo na rešenju.</span><span class="sxs-lookup"><span data-stu-id="2963f-114">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="2963f-115">Molimo vas da nam date najmanje 24 sata da završimo rešenje.</span><span class="sxs-lookup"><span data-stu-id="2963f-115">Please give us at least 24 hours to complete a solution.</span></span>
