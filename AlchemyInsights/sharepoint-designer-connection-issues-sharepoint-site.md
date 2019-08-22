---
title: Pitanja za povezivanje SharePoint Designer
ms.author: efrene
author: efrene
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: a4aeaeaea5743c276b907c78317ff30f5610be81
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36508437"
---
# <a name="sharepoint-designer-connection-issues"></a><span data-ttu-id="b0ffa-102">Pitanja za povezivanje SharePoint Designer</span><span class="sxs-lookup"><span data-stu-id="b0ffa-102">SharePoint Designer connection issues</span></span> 

<span data-ttu-id="b0ffa-103">Ako SharePoint Designer se suočava sa pitanjima za povezivanje sa SharePoint lokacijama, pokušajte sledeće zajedničkim rešenjima.</span><span class="sxs-lookup"><span data-stu-id="b0ffa-103">If SharePoint Designer is experiencing connection issues to SharePoint sites, please try the following common solutions.</span></span>

<span data-ttu-id="b0ffa-104">1. korak: Provjerite da SharePoint Designer 2013 se ažurira sa [SharePoint Designer sa servisnim paketom 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) i [2. avgust 2016 ažuriranje za SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).</span><span class="sxs-lookup"><span data-stu-id="b0ffa-104">Step 1: Verify that SharePoint Designer 2013 is updated with [SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) and the [August 2, 2016 Update for SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).</span></span>



<span data-ttu-id="b0ffa-105">2. korak: Brisanje datoteke lokalnog keša:</span><span class="sxs-lookup"><span data-stu-id="b0ffa-105">Step 2: Clear the local cache files:</span></span>

1. <span data-ttu-id="b0ffa-106">Zatvorite SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="b0ffa-106">Close SharePoint Designer 2013.</span></span>

2. <span data-ttu-id="b0ffa-107">Na lokalnom računaru, uklonite sve datoteke pronađene u svakoj od sljedećih mapa.</span><span class="sxs-lookup"><span data-stu-id="b0ffa-107">On the local computer, remove all files found in each of the following folders.</span></span>

    - <span data-ttu-id="b0ffa-108">%APPDATA%\Microsoft\Web server Extensions\Cache</span><span class="sxs-lookup"><span data-stu-id="b0ffa-108">%APPDATA%\Microsoft\Web Server Extensions\Cache</span></span>
    - <span data-ttu-id="b0ffa-109">%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache</span><span class="sxs-lookup"><span data-stu-id="b0ffa-109">%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache</span></span>
    - <span data-ttu-id="b0ffa-110">%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span><span class="sxs-lookup"><span data-stu-id="b0ffa-110">%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span></span>

3. <span data-ttu-id="b0ffa-111">Otvorite SharePoint Designer 2013 i unesite račun da vidimo da li radi.</span><span class="sxs-lookup"><span data-stu-id="b0ffa-111">Open SharePoint Designer 2013 and enter the account again to see if it works.</span></span>

<span data-ttu-id="b0ffa-112">3. korak: [Omogućavanje moderne potvrde identiteta za Office 2013 na uređajima Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="b0ffa-112">Step 3: [Enable Modern Authentication for Office 2013 on Windows Devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide).</span></span>

<span data-ttu-id="b0ffa-113">4. korak: Administratori morat ćete **Omogućiti prilagođena skripta** u SharePoint Admin Center postavkama da biste dozvolili povezivanje na SharePoint Designer.</span><span class="sxs-lookup"><span data-stu-id="b0ffa-113">Step 4: Administrators will need to **Allow Custom Script** in the SharePoint Admin Center settings to allow the SharePoint Designer connection.</span></span> <span data-ttu-id="b0ffa-114">Vidim [Dozvoli ili sprečavaju adaptirani scenario](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) za više informacija.</span><span class="sxs-lookup"><span data-stu-id="b0ffa-114">See [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) for more information.</span></span>


