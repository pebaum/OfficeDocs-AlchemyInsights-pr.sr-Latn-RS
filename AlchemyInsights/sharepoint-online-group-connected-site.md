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
ms.openlocfilehash: 6aea12d44a44a3e11eaf3fb1bd47ff3e9dbfd9e7
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36507861"
---
# <a name="issues-when-creating-or-group-connected-sites-in-sharepoint-online"></a><span data-ttu-id="62598-102">Problemi u povezivanju kreiranja ili grupe lokacije u SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="62598-102">Issues when creating or group connected sites in SharePoint Online</span></span>

<span data-ttu-id="62598-103">Postoji nekoliko uobičajenih problema naišao na povezivanju kreiranje ili ponovno Kreiranje grupe lokacija.</span><span class="sxs-lookup"><span data-stu-id="62598-103">There are a couple of common issues encountered when creating or re-creating a group connected site.</span></span>

 <span data-ttu-id="62598-104">Ako ste izbrisali grupu i njene povezanih lokacija i želimo da stvorimo neku drugu lokaciju sa istom URL adresom, moraćete da trajno uklonite prethodnu lokaciju.</span><span class="sxs-lookup"><span data-stu-id="62598-104">If you have deleted a group and its connected site and wish to create another site with the same URL, you'll need to permanently remove the previous site.</span></span>

<span data-ttu-id="62598-105">Preuzmite [SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span><span class="sxs-lookup"><span data-stu-id="62598-105">Download [SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span></span>

 <span data-ttu-id="62598-106">Za više informacija na prvi koraci u powershell, pogledajte [Prvi koraci sa SharePoint Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)</span><span class="sxs-lookup"><span data-stu-id="62598-106">For more info on getting started with powershell, see [Getting started with SharePoint Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)</span></span>

<span data-ttu-id="62598-107">Uklanjanje lokacije iz izbrisane lokacija koristi za [Uklanjanje SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) powershell cmdlet.</span><span class="sxs-lookup"><span data-stu-id="62598-107">Remove the Site from Deleted Sites using the [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) powershell cmdlet.</span></span>

<span data-ttu-id="62598-108">Ako kreirate grupe povezanih lokacija i dobijete upozorenje druga grupa sa istim imenom već postoji, proverite postojeće grupe iz [Office 365 iz centra za administraciju](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups).</span><span class="sxs-lookup"><span data-stu-id="62598-108">If you're creating a group connected site and receive a warning Another group with the same alias already exists, check the existing groups from the [Office 365 from the Admin Center](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups).</span></span> <span data-ttu-id="62598-109">Rešite problem, izbrišite postojeće grupe, ako to više nije potrebna ili kreirate lokaciju sa različitim pseudonim dodeljen.</span><span class="sxs-lookup"><span data-stu-id="62598-109">To resolve the issue, delete the existing group if it's no longer needed or create the site with a different alias assigned.</span></span>

<span data-ttu-id="62598-110">Postoje različiti načini za kreiranje i koriste moderne grupe sa SharePoint.</span><span class="sxs-lookup"><span data-stu-id="62598-110">There are different ways to create and use modern groups with SharePoint.</span></span>

<span data-ttu-id="62598-111">Možete da se povežete postojeće lokacije Office 365 grupi.</span><span class="sxs-lookup"><span data-stu-id="62598-111">You can connect existing sites to an Office 365 group.</span></span> <span data-ttu-id="62598-112">Za više informacija, potražite u odeljku [Povezivanje grupi programa Office 365 pomoću ineterface korisnika u SharePoint](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span><span class="sxs-lookup"><span data-stu-id="62598-112">For more info, see [Connect an Office 365 group using the SharePoint user ineterface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span></span>

<span data-ttu-id="62598-113">Da biste kreirali povezani lokaciju Office 365 grupe, moraćete da kreirate lokaciju tima.</span><span class="sxs-lookup"><span data-stu-id="62598-113">To create an Office 365 group connected site, you'll need to create a Team Site.</span></span> <span data-ttu-id="62598-114">Za više informacija, potražite u odeljku [Kreiranje lokaciju tima u sistemu SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).</span><span class="sxs-lookup"><span data-stu-id="62598-114">For more info, see [Create a team site in SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).</span></span>

