---
title: Dodavanje grupe na SharePoint lokaciji
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f7d730bf-0d6e-424c-970c-6137c71cb50b
ms.openlocfilehash: f0126f7f753275e9bbf8c3a09a6af5faf9a27862
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34758744"
---
# <a name="create-group-connected-site-in-sharepoint-online"></a><span data-ttu-id="3a437-102">Kreiranje grupe povezanih lokacija u SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="3a437-102">Create group connected site in SharePoint Online</span></span>

<span data-ttu-id="3a437-103">Postoji nekoliko uobičajenih problema naišao na povezivanju kreiranje ili ponovno Kreiranje grupe lokacija.</span><span class="sxs-lookup"><span data-stu-id="3a437-103">There are a couple of common issues encountered when creating or re-creating a group connected site.</span></span>

 <span data-ttu-id="3a437-104">Ako ste izbrisali grupu i njene povezanih lokacija i želimo da stvorimo neku drugu lokaciju sa istom URL adresom, moraćete da trajno uklonite prethodnu lokaciju.</span><span class="sxs-lookup"><span data-stu-id="3a437-104">If you have deleted a group and its connected site and wish to create another site with the same URL, you'll need to permanently remove the previous site.</span></span>

<span data-ttu-id="3a437-105">Preuzmite [SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span><span class="sxs-lookup"><span data-stu-id="3a437-105">Download [SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span></span>

 <span data-ttu-id="3a437-106">Za više informacija na prvi koraci u powershell, pogledajte [Prvi koraci sa SharePoint Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)</span><span class="sxs-lookup"><span data-stu-id="3a437-106">For more info on getting started with powershell, see [Getting started with SharePoint Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)</span></span>

<span data-ttu-id="3a437-107">Uklanjanje lokacije iz izbrisane lokacija koristi za [Uklanjanje SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) powershell cmdlet.</span><span class="sxs-lookup"><span data-stu-id="3a437-107">Remove the Site from Deleted Sites using the [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) powershell cmdlet.</span></span>

<span data-ttu-id="3a437-108">Ako kreirate grupe povezanih lokacija i dobijete upozorenje druga grupa sa istim imenom već postoji, proverite postojeće grupe iz [Office 365 iz centra za administraciju](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups).</span><span class="sxs-lookup"><span data-stu-id="3a437-108">If you're creating a group connected site and receive a warning Another group with the same alias already exists, check the existing groups from the [Office 365 from the Admin Center](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups).</span></span> <span data-ttu-id="3a437-109">Rešite problem, izbrišite postojeće grupe, ako to više nije potrebna ili kreirate lokaciju sa različitim pseudonim dodeljen.</span><span class="sxs-lookup"><span data-stu-id="3a437-109">To resolve the issue, delete the existing group if it's no longer needed or create the site with a different alias assigned.</span></span>

<span data-ttu-id="3a437-110">Postoje različiti načini za kreiranje i koriste moderne grupe sa SharePoint.</span><span class="sxs-lookup"><span data-stu-id="3a437-110">There are different ways to create and use modern groups with SharePoint.</span></span>

<span data-ttu-id="3a437-111">Možete da se povežete postojeće lokacije Office 365 grupi.</span><span class="sxs-lookup"><span data-stu-id="3a437-111">You can connect existing sites to an Office 365 group.</span></span> <span data-ttu-id="3a437-112">Za više informacija, potražite u odeljku [Povezivanje grupi programa Office 365 pomoću ineterface korisnika u SharePoint](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span><span class="sxs-lookup"><span data-stu-id="3a437-112">For more info, see [Connect an Office 365 group using the SharePoint user ineterface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span></span>

<span data-ttu-id="3a437-113">Da biste kreirali povezani lokaciju Office 365 grupe, moraćete da kreirate lokaciju tima.</span><span class="sxs-lookup"><span data-stu-id="3a437-113">To create an Office 365 group connected site, you'll need to create a Team Site.</span></span> <span data-ttu-id="3a437-114">Za više informacija, potražite u odeljku [Kreiranje lokaciju tima u sistemu SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).</span><span class="sxs-lookup"><span data-stu-id="3a437-114">For more info, see [Create a team site in SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).</span></span>

