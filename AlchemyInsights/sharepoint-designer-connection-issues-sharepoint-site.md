---
title: Nivoi dozvola SharePoint Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 356fef8e02f2c1fd9d209c68194685bb0acaa367
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34760706"
---
# <a name="sharepoint-designer-connection-issues"></a><span data-ttu-id="41047-102">Pitanja za povezivanje SharePoint Designer</span><span class="sxs-lookup"><span data-stu-id="41047-102">SharePoint Designer connection issues</span></span> 

<span data-ttu-id="41047-103">Ako SharePoint Designer se suočava sa pitanjima za povezivanje sa SharePoint lokacijama, molim vas pokušati sledeća uobičajene rešenja.</span><span class="sxs-lookup"><span data-stu-id="41047-103">If SharePoint Designer is experiencing connection issues to SharePoint sites, please attempt the following common solutions.</span></span>

<span data-ttu-id="41047-104">1. korak: Provjerite ažuriranja SharePoint Designer.</span><span class="sxs-lookup"><span data-stu-id="41047-104">Step 1: Verify SharePoint Designer is updated.</span></span>

- [<span data-ttu-id="41047-105">SharePoint Designer 2013</span><span class="sxs-lookup"><span data-stu-id="41047-105">SharePoint Designer 2013</span></span>](https://www.microsoft.com/download/details.aspx?id=35491)

- [<span data-ttu-id="41047-106">SharePoint Designer servisni paket 1 (SP1)</span><span class="sxs-lookup"><span data-stu-id="41047-106">SharePoint Designer Service Pack 1 (SP1)</span></span>](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1)

- [<span data-ttu-id="41047-107">Ažuriranje za SharePoint Designer 2013 (KB3114721)</span><span class="sxs-lookup"><span data-stu-id="41047-107">Update for SharePoint Designer 2013 (KB3114721)</span></span>](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721)

<span data-ttu-id="41047-108">2. korak: Brisanje datoteke lokalnog keša</span><span class="sxs-lookup"><span data-stu-id="41047-108">Step 2: Clear the local cache files</span></span>

- <span data-ttu-id="41047-109">Zatvorite SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="41047-109">Close SharePoint Designer 2013.</span></span>

- <span data-ttu-id="41047-110">Na lokalnom računaru, pronađite sljedeće mape da biste uklonili keširane datoteke.</span><span class="sxs-lookup"><span data-stu-id="41047-110">On the local computer, browse to the following folders to remove cached files.</span></span>

- <span data-ttu-id="41047-111">Kliknite na dugme Start, Run i izbrisati sve datoteke pronađene ispod svakog je ispod lokacije.</span><span class="sxs-lookup"><span data-stu-id="41047-111">Click Start, Run and delete all files found under each of the below locations.</span></span>

<span data-ttu-id="41047-112">Server za %APPDATA%\Microsoft\Web Extensions\Cache %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span><span class="sxs-lookup"><span data-stu-id="41047-112">%APPDATA%\Microsoft\Web Server Extensions\Cache %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span></span>

<span data-ttu-id="41047-113">Otvorite SharePoint Designer 2013 i unesite račun da vidimo da li radi.</span><span class="sxs-lookup"><span data-stu-id="41047-113">Open SharePoint Designer 2013 and enter the account again to see if it works.</span></span>

<span data-ttu-id="41047-114">3. korak: [Omogućavanje moderne potvrde identiteta za Office 2013 na uređajima Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide)</span><span class="sxs-lookup"><span data-stu-id="41047-114">Step 3: [Enable Modern Authentication for Office 2013 on Windows Devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide)</span></span>

<span data-ttu-id="41047-115">4. korak: Administratori morat ćete omogućiti prilagođena skripta da dozvolite vezu SharePoint Designer.</span><span class="sxs-lookup"><span data-stu-id="41047-115">Step 4: Administrators will need to Allow Custom Script to allow the SharePoint Designer connection.</span></span>

<span data-ttu-id="41047-116">Detaljni koraci, primeri i razmatranja potražite u [Dozvoli ili sprečavaju adaptirani scenario](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span><span class="sxs-lookup"><span data-stu-id="41047-116">For detailed steps, examples and considerations see [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span></span>


