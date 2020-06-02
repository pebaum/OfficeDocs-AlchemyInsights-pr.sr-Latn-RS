---
title: Problemi sa SharePoint dizajnerom
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 01ccc6bc28148f397fb6cd2b7a0eaaeb5b51973f
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511558"
---
# <a name="sharepoint-designer-connection-issues"></a><span data-ttu-id="7abb2-102">Problemi sa SharePoint dizajnerom</span><span class="sxs-lookup"><span data-stu-id="7abb2-102">SharePoint Designer connection issues</span></span> 

<span data-ttu-id="7abb2-103">Ako SharePoint Designer ima problema sa povezivanjem sa SharePoint lokacijama, isprobajte sledeća uobičajena rešenja.</span><span class="sxs-lookup"><span data-stu-id="7abb2-103">If SharePoint Designer is experiencing connection issues to SharePoint sites, please try the following common solutions.</span></span>

<span data-ttu-id="7abb2-104">1. korak: proverite da li se SharePoint Designer 2013 ažurira pomoću [SharePoint Designer servisnog paketa 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) i [2. avgusta, 2016 Update za SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).</span><span class="sxs-lookup"><span data-stu-id="7abb2-104">Step 1: Verify that SharePoint Designer 2013 is updated with [SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) and the [August 2, 2016 Update for SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).</span></span>



<span data-ttu-id="7abb2-105">2. korak: brisanje lokalnih datoteka keša:</span><span class="sxs-lookup"><span data-stu-id="7abb2-105">Step 2: Clear the local cache files:</span></span>

1. <span data-ttu-id="7abb2-106">Zatvorite SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="7abb2-106">Close SharePoint Designer 2013.</span></span>

2. <span data-ttu-id="7abb2-107">Na lokalnom računaru uklonite sve datoteke pronađene u svakoj od sledećih fascikli.</span><span class="sxs-lookup"><span data-stu-id="7abb2-107">On the local computer, remove all files found in each of the following folders.</span></span>

    - <span data-ttu-id="7abb2-108">%APPDATA%\Microsoft\Web% Ekstenioni\keš</span><span class="sxs-lookup"><span data-stu-id="7abb2-108">%APPDATA%\Microsoft\Web Server Extensions\Cache</span></span>
    - <span data-ttu-id="7abb2-109">%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache</span><span class="sxs-lookup"><span data-stu-id="7abb2-109">%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache</span></span>
    - <span data-ttu-id="7abb2-110">%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span><span class="sxs-lookup"><span data-stu-id="7abb2-110">%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span></span>

3. <span data-ttu-id="7abb2-111">Otvorite SharePoint Designer 2013 i ponovo unesite nalog da biste videli da li radi.</span><span class="sxs-lookup"><span data-stu-id="7abb2-111">Open SharePoint Designer 2013 and enter the account again to see if it works.</span></span>

<span data-ttu-id="7abb2-112">3. korak: [Omogućavanje moderne potvrde identiteta za Office 2013 na Windows uređajima](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="7abb2-112">Step 3: [Enable Modern Authentication for Office 2013 on Windows Devices](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).</span></span>

<span data-ttu-id="7abb2-113">4. korak: Administratori će morati da **dozvole prilagođenu skriptu** u postavkama sistema SharePoint admin Center da bi dozvolili povezivanje sa SharePoint dizajnerom.</span><span class="sxs-lookup"><span data-stu-id="7abb2-113">Step 4: Administrators will need to **Allow Custom Script** in the SharePoint Admin Center settings to allow the SharePoint Designer connection.</span></span> <span data-ttu-id="7abb2-114">Više informacija potražite u članku [Dozvoljavanje ili sprečavanje prilagođene skripte](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) .</span><span class="sxs-lookup"><span data-stu-id="7abb2-114">See [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) for more information.</span></span>


