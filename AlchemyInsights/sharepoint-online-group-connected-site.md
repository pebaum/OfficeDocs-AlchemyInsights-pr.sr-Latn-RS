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
ms.openlocfilehash: 14ad9dd094902c85eaf0398c76003cea20ad4c0a
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051115"
---
# <a name="issues-when-creating-or-group-connected-sites-in-sharepoint-online"></a><span data-ttu-id="a0e64-102">Problemi prilikom kreiranja ili grupisanja povezanih lokacija u sistemu SharePoint online</span><span class="sxs-lookup"><span data-stu-id="a0e64-102">Issues when creating or group connected sites in SharePoint Online</span></span>

<span data-ttu-id="a0e64-103">Došlo je do nekoliko uobičajenih problema prilikom kreiranja ili ponovnog kreiranja grupe povezane lokacije.</span><span class="sxs-lookup"><span data-stu-id="a0e64-103">There are a couple of common issues encountered when creating or re-creating a group connected site.</span></span>

 <span data-ttu-id="a0e64-104">Ako ste izbrisali grupu i povezanu lokaciju i želite da kreirate drugu lokaciju sa istom URL adresom, moraćete trajno da uklonite prethodnu lokaciju.</span><span class="sxs-lookup"><span data-stu-id="a0e64-104">If you have deleted a group and its connected site and wish to create another site with the same URL, you'll need to permanently remove the previous site.</span></span>

<span data-ttu-id="a0e64-105">Preuzimanje [ljuske za upravljanje SPO](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429) -a</span><span class="sxs-lookup"><span data-stu-id="a0e64-105">Download [SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span></span>

 <span data-ttu-id="a0e64-106">Više informacija o početku rada sa programom PowerShell potražite [u članku prvi koraci u usluzi SharePoint Shell Management ljuske](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)</span><span class="sxs-lookup"><span data-stu-id="a0e64-106">For more info on getting started with powershell, see [Getting started with SharePoint Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)</span></span>

<span data-ttu-id="a0e64-107">Uklonite lokaciju sa izbrisanih lokacija koristeći [stranicu ukloni-Prebrisedshell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) cmdto.</span><span class="sxs-lookup"><span data-stu-id="a0e64-107">Remove the Site from Deleted Sites using the [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) powershell cmdlet.</span></span>

<span data-ttu-id="a0e64-108">Ako kreirate grupu povezanu sa grupom i primite upozorenje druga grupa sa istim pseudonimom već postoji, proverite postojeće grupe iz [sistema Office 365 iz administratorskog centra](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups).</span><span class="sxs-lookup"><span data-stu-id="a0e64-108">If you're creating a group connected site and receive a warning Another group with the same alias already exists, check the existing groups from the [Office 365 from the Admin Center](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups).</span></span> <span data-ttu-id="a0e64-109">Da biste rešili problem, izbrišite postojeću grupu ako više nije potrebna ili kreirajte lokaciju sa dodeljenim drugim pseudonimom.</span><span class="sxs-lookup"><span data-stu-id="a0e64-109">To resolve the issue, delete the existing group if it's no longer needed or create the site with a different alias assigned.</span></span>

<span data-ttu-id="a0e64-110">Postoje različiti načini za kreiranje i korišćenje modernih grupa sa SharePoint-om.</span><span class="sxs-lookup"><span data-stu-id="a0e64-110">There are different ways to create and use modern groups with SharePoint.</span></span>

<span data-ttu-id="a0e64-111">Postojeće lokacije možete da povežete sa Office 365 grupom.</span><span class="sxs-lookup"><span data-stu-id="a0e64-111">You can connect existing sites to an Office 365 group.</span></span> <span data-ttu-id="a0e64-112">Više informacija potražite u članku [Povezivanje Office 365 grupe pomoću SharePoint korisnika koji je neodređen](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span><span class="sxs-lookup"><span data-stu-id="a0e64-112">For more info, see [Connect an Office 365 group using the SharePoint user ineterface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span></span>

<span data-ttu-id="a0e64-113">Potrebno je da kreirate lokaciju tima da biste kreirali Office 365 grupu povezanu lokaciju.</span><span class="sxs-lookup"><span data-stu-id="a0e64-113">To create an Office 365 group connected site, you'll need to create a Team Site.</span></span> <span data-ttu-id="a0e64-114">Više informacija potražite u članku [Kreiranje lokacije tima u sistemu SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).</span><span class="sxs-lookup"><span data-stu-id="a0e64-114">For more info, see [Create a team site in SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).</span></span>

