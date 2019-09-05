---
title: Kreiranje SharePoint lokacije
ms.author: efrene
author: efrene
ms.date: 1/16/2019
ms.audience: ITPro
ms.topic: article
ms.collection: Adm_O365
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "5200004"
- "1386"
- "2303"
ms.assetid: e62b9f80-b017-42dc-9464-f4e32c19d6c9
ms.openlocfilehash: 30c51d84005534cc1de9e8b8136da1a07be57b73
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/04/2019
ms.locfileid: "36738211"
---
# <a name="create-a-sharepoint-site"></a><span data-ttu-id="b7905-102">Kreiranje SharePoint lokacije</span><span class="sxs-lookup"><span data-stu-id="b7905-102">Create a SharePoint site</span></span>

<span data-ttu-id="b7905-103">Za informacije o kreiranju SharePoint lokacija možete da vidite sledeće:</span><span class="sxs-lookup"><span data-stu-id="b7905-103">You can see the following for information about SharePoint site creation:</span></span>
- <span data-ttu-id="b7905-104">[Upravljajte lokacijama u novom SharePoint admin centru](https://docs.microsoft.com/sharepoint/manage-site-creation): Saznajte više o opcijama kreiranja lokacije, uključujući i kako da kreirate klasičnu lokaciju ili lokaciju timova koja ne sadrži Office 365 grupu.</span><span class="sxs-lookup"><span data-stu-id="b7905-104">[Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-site-creation): Learn about site creation options, including how to create a classic site or a teams site that doesn't include an Office 365 group.</span></span>
- <span data-ttu-id="b7905-105">[Kreirajte lokaciju tima u sistemu SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d): Saznajte kako da kreirate lokaciju tima.</span><span class="sxs-lookup"><span data-stu-id="b7905-105">[Create a team site in SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d): Learn how to create a team site.</span></span>
- <span data-ttu-id="b7905-106">[Kreirajte lokaciju za komunikaciju u sistemu SharePoint online](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb): Saznajte kako da kreirate lokaciju za komunikaciju.</span><span class="sxs-lookup"><span data-stu-id="b7905-106">[Create a communication site in SharePoint Online](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb): Learn how to create a communications site.</span></span>
- <span data-ttu-id="b7905-107">[Upravljanje lokacijama u novom SharePoint admin centru](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site): Saznajte kako da kreirate klasičnu lokaciju ili lokaciju tima koja ne sadrži Office 365 grupu.</span><span class="sxs-lookup"><span data-stu-id="b7905-107">[Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site):  Learn how to create a classic site or a team site that doesn't include an Office 365 group.</span></span>


  
> <span data-ttu-id="b7905-108">[! Saveti</span><span class="sxs-lookup"><span data-stu-id="b7905-108">[!Tips]</span></span>
> - <span data-ttu-id="b7905-109">Ne možete da kreirate lokaciju sa istom URL adresom postojeće lokacije.</span><span class="sxs-lookup"><span data-stu-id="b7905-109">You cannot create a site with the same URL of an existing site.</span></span> <span data-ttu-id="b7905-110">Ako ste izbrisali lokaciju i želite da ponovo koristite URL adresu, moguće je da izbrisana lokacija još uvek postoji pod **izbrisanim lokacijama**.</span><span class="sxs-lookup"><span data-stu-id="b7905-110">If you deleted a site and are wishing to re-use the URL, it's possible the deleted site still exists under **Deleted sites**.</span></span> <span data-ttu-id="b7905-111">Da biste upravljali izbrisanim lokacijama pogledajte, [Izbrišite lokaciju](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site).</span><span class="sxs-lookup"><span data-stu-id="b7905-111">To manage deleted sites see, [Delete a Site](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site).</span></span> <span data-ttu-id="b7905-112">Da biste potpuno uklonili lokaciju sa programom PowerShell, pogledajte primer " [Ukloni-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) ".</span><span class="sxs-lookup"><span data-stu-id="b7905-112">To completely remove a site with Powershell, see the [Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) cmdlet example.</span></span>
> - <span data-ttu-id="b7905-113">Neki korisnici možda neće moći da kreiraju lokaciju.</span><span class="sxs-lookup"><span data-stu-id="b7905-113">Some users may not be able to create a site.</span></span> <span data-ttu-id="b7905-114">Pogledajte odeljak [Upravljanje kreiranjem lokacije na lokaciji SharePoint online](https://docs.microsoft.com/sharepoint/manage-site-creation).</span><span class="sxs-lookup"><span data-stu-id="b7905-114">See [Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).</span></span>
> - <span data-ttu-id="b7905-115">Moguće je da je lokacija zaglavljena pri **kreiranju** duže od očekivanog.</span><span class="sxs-lookup"><span data-stu-id="b7905-115">It's possible the site appears stuck at **Creating** longer than expected.</span></span> <span data-ttu-id="b7905-116">Ako je prošlo više od 24 časa od kada ste prvi put videli ovaj problem, molimo vas da prijavite tiket za podršku.</span><span class="sxs-lookup"><span data-stu-id="b7905-116">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="b7905-117">U mnogim slučajevima već radimo na rešenju.</span><span class="sxs-lookup"><span data-stu-id="b7905-117">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="b7905-118">Molimo vas da nam date najmanje 24 sata da završimo rešenje.</span><span class="sxs-lookup"><span data-stu-id="b7905-118">Please give us at least 24 hours to complete a solution.</span></span>
> - <span data-ttu-id="b7905-119">Ako je potrebno da kreirate novu timsku lokaciju koja ne sadrži Office 365 grupu,</span><span class="sxs-lookup"><span data-stu-id="b7905-119">If you need to create a new team site that doesn't include an Office 365 group,</span></span> 


