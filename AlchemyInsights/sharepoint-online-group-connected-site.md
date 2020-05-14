---
title: Dodavanje grupe na SharePoint lokaciju
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f7d730bf-0d6e-424c-970c-6137c71cb50b
ms.openlocfilehash: b54457427ffa563b6a6323d85e1c8800191eca11
ms.sourcegitcommit: a98b25fa3cac9ebba983f4932881d774880aca93
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/13/2020
ms.locfileid: "44064407"
---
# <a name="issues-when-creating-a-group-connected-site-in-sharepoint"></a><span data-ttu-id="66af6-102">Problemi prilikom kreiranja grupe povezane lokacije u sistemu SharePoint</span><span class="sxs-lookup"><span data-stu-id="66af6-102">Issues when creating a group connected site in SharePoint</span></span>

1. <span data-ttu-id="66af6-103">Došlo je do nekih uobičajenih problema prilikom kreiranja ili ponovnog kreiranja grupe povezane lokacije.</span><span class="sxs-lookup"><span data-stu-id="66af6-103">Some common issues encountered when creating or re-creating a group connected site.</span></span>
<span data-ttu-id="66af6-104">Ako ste izbrisali grupu i povezanu lokaciju i želite da kreirate drugu lokaciju sa istom URL adresom, moraćete trajno da uklonite prethodnu lokaciju.</span><span class="sxs-lookup"><span data-stu-id="66af6-104">If you have deleted a group and its connected site and wish to create another site with the same URL, you'll need to permanently remove the previous site.</span></span>

   - <span data-ttu-id="66af6-105">Preuzimanje [ljuske za upravljanje SPO](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429) -a</span><span class="sxs-lookup"><span data-stu-id="66af6-105">Download [SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span></span>
   - <span data-ttu-id="66af6-106">Više informacija o početku rada sa programom PowerShell potražite u članku [Prvi koraci u usluzi SharePoint Shell Management ljuske](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite).</span><span class="sxs-lookup"><span data-stu-id="66af6-106">For more info on getting started with Powershell, see [Getting started with SharePoint Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite).</span></span>
   - <span data-ttu-id="66af6-107">Uklonite lokaciju sa izbrisanih lokacija koristeći [stranicu ukloni-Prebrisedshell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) cmdto.</span><span class="sxs-lookup"><span data-stu-id="66af6-107">Remove the Site from Deleted Sites using the [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) Powershell cmdlet.</span></span> <span data-ttu-id="66af6-108">PowerShell je potreban za trajno brisanje grupnih lokacija.</span><span class="sxs-lookup"><span data-stu-id="66af6-108">Powershell is required to permanently delete group sites.</span></span>

1. <span data-ttu-id="66af6-109">Ako kreirate grupu povezanu lokaciju i primite upozorenje: **druga grupa sa istim pseudonimom već postoji**, proverite postojeće grupe iz [Microsoft 365 admin Center](https://admin.microsoft.com/AdminPortal/Home#/groups).</span><span class="sxs-lookup"><span data-stu-id="66af6-109">If you're creating a group connected site and receive a warning: **Another group with the same alias already exists**, check the existing groups from the [Microsoft 365 admin center](https://admin.microsoft.com/AdminPortal/Home#/groups).</span></span> <span data-ttu-id="66af6-110">Da biste rešili problem, izbrišite postojeću grupu ako više nije potrebna ili kreirajte lokaciju sa dodeljenim drugim pseudonimom.</span><span class="sxs-lookup"><span data-stu-id="66af6-110">To resolve the issue, delete the existing group if it's no longer needed or create the site with a different alias assigned.</span></span>

1. <span data-ttu-id="66af6-111">Postoje različiti načini za kreiranje i korišćenje modernih grupa sa SharePoint-om.</span><span class="sxs-lookup"><span data-stu-id="66af6-111">There are different ways to create and use modern groups with SharePoint.</span></span>

   - <span data-ttu-id="66af6-112">Postojeće lokacije možete da povežete sa Microsoft 365 grupom.</span><span class="sxs-lookup"><span data-stu-id="66af6-112">You can connect existing sites to an Microsoft 365 group.</span></span> <span data-ttu-id="66af6-113">Više informacija potražite u članku [Povezivanje grupe Microsoft 365 pomoću SharePoint korisničkog interfejsa](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span><span class="sxs-lookup"><span data-stu-id="66af6-113">For more info, see [Connect an Microsoft 365 group using the SharePoint user interface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span></span>
   - <span data-ttu-id="66af6-114">Da biste kreirali povezanu lokaciju Microsoft 365 grupe, potrebno je da kreirate [lokaciju tima](https://admin.microsoft.com/sharepoint).</span><span class="sxs-lookup"><span data-stu-id="66af6-114">To create an Microsoft 365 group connected site, you'll need to create a [Team Site](https://admin.microsoft.com/sharepoint).</span></span>
