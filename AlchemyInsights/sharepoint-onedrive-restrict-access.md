---
title: Ograničavanje pristupa u sistemu SharePoint ili OneDrive
ms.author: pebaum
author: Techwriter40
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: bef0612903b9bb455aa34e90d35d6b7b9093b4e0
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/18/2019
ms.locfileid: "36750678"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a><span data-ttu-id="ef2be-102">Ograničavanje pristupa u sistemu SharePoint ili OneDrive</span><span class="sxs-lookup"><span data-stu-id="ef2be-102">Restrict access in SharePoint or OneDrive</span></span>

<span data-ttu-id="ef2be-103">Postoji mnogo načina da ograničite pristup SharePoint online/OneDrive uslugama.</span><span class="sxs-lookup"><span data-stu-id="ef2be-103">There are many ways to restrict access to SharePoint Online/OneDrive services.</span></span> <span data-ttu-id="ef2be-104">Ovi različiti metodi ograničenja pristupa su dole navedeni.</span><span class="sxs-lookup"><span data-stu-id="ef2be-104">These various access restriction methods are outlined below.</span></span> 

<span data-ttu-id="ef2be-105">**Ograničenje dozvole**</span><span class="sxs-lookup"><span data-stu-id="ef2be-105">**Permission Restriction**</span></span>

<span data-ttu-id="ef2be-106">U sistemu SharePoint Online i OneDrive za preduzeća ograničavamo pristup stavkama kao što su lokacije, datoteke i fascikle samo pružanjem pristupa tim grupama/pojedincima koji treba da imaju pristup.</span><span class="sxs-lookup"><span data-stu-id="ef2be-106">In SharePoint Online and OneDrive for Business, we restrict access to items like sites, files and folders by only granting access to those groups/individuals who should have access.</span></span>

- [<span data-ttu-id="ef2be-107">Prilagođavanje dozvola za SharePoint listu ili biblioteku</span><span class="sxs-lookup"><span data-stu-id="ef2be-107">Customize permissions for a SharePoint list or library</span></span>](https://support.office.com/article/Customize-permissions-for-a-SharePoint-list-or-library-02d770f3-59eb-4910-a608-5f84cc297782)

- [<span data-ttu-id="ef2be-108">Prilagođavanje dozvola za SharePoint lokaciju</span><span class="sxs-lookup"><span data-stu-id="ef2be-108">Customize SharePoint site permissions</span></span>](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions)

- [<span data-ttu-id="ef2be-109">Promena dozvola u potfascikli</span><span class="sxs-lookup"><span data-stu-id="ef2be-109">Change the permissions on a subfolder</span></span>](https://support.office.com/article/Change-the-permissions-on-a-subfolder-5427BD7C-F20A-4F75-8CF2-5359DD45A1A6)

- [<span data-ttu-id="ef2be-110">Kontrolisanje pristupa sa nekompletnog uređaja</span><span class="sxs-lookup"><span data-stu-id="ef2be-110">Control access from unmanaged devices</span></span>](https://docs.microsoft.com/sharepoint/control-access-from-unmanaged-devices)

<span data-ttu-id="ef2be-111">Kao SharePoint ili globalni administrator u sistemu Office 365, možete blokirati ili ograničiti pristup SharePoint i OneDrive sadržaju sa nekompletnog uređaja (a ne u hibridnim uređajima, koji nisu spojeni ili usaglašeni u usluzi Intune).</span><span class="sxs-lookup"><span data-stu-id="ef2be-111">As a SharePoint or global admin in Office 365, you can block or limit access to SharePoint and OneDrive content from unmanaged devices (those not hybrid AD joined or compliant in Intune).</span></span>

<span data-ttu-id="ef2be-112">**Ograničenje mrežne lokacije**</span><span class="sxs-lookup"><span data-stu-id="ef2be-112">**Network Location Restriction**</span></span>

<span data-ttu-id="ef2be-113">Kao IT administrator, možete kontrolisati pristup SharePoint i OneDrive resursima na osnovu definisanih mrežnih lokacija u koje imate poverenja.</span><span class="sxs-lookup"><span data-stu-id="ef2be-113">As an IT admin, you can control access to SharePoint and OneDrive resources based on defined network locations that you trust.</span></span> <span data-ttu-id="ef2be-114">To se naziva i smernica zasnovana na lokaciji.</span><span class="sxs-lookup"><span data-stu-id="ef2be-114">This is also known as location-based policy.</span></span> <span data-ttu-id="ef2be-115">Više informacija potražite u članku [Kontrola pristupa SharePoint Online i OneDrive podacima zasnovanim na mrežnoj lokaciji](https://docs.microsoft.com/sharepoint/control-access-based-on-network-location)</span><span class="sxs-lookup"><span data-stu-id="ef2be-115">For more information, please see [Control access to SharePoint Online and OneDrive data based on network location](https://docs.microsoft.com/sharepoint/control-access-based-on-network-location)</span></span>

<span data-ttu-id="ef2be-116">**Ograničenje zaključavanja lokacije**</span><span class="sxs-lookup"><span data-stu-id="ef2be-116">**Site Lock Restriction**</span></span> 

<span data-ttu-id="ef2be-117">U okviru lokacije SharePoint online imate mogućnost da zaključate kolekciju lokacija, tako da niko nema pristup.</span><span class="sxs-lookup"><span data-stu-id="ef2be-117">Within SharePoint Online you have the ability to lock down a site collection, so no one has access.</span></span> <span data-ttu-id="ef2be-118">Ovo je podešeno putem PowerShell i [SharePoint ljuske upravljanja na mreži](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) koristeći svojstvo [Set-sposit](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -lokstate.</span><span class="sxs-lookup"><span data-stu-id="ef2be-118">This is set via PowerShell and the [SharePoint Online Management Shell](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) using the [Set-SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -LockState property.</span></span>

<span data-ttu-id="ef2be-119">**Ograničavanje korisnika da kreiraju lokacije ili podlokacije**</span><span class="sxs-lookup"><span data-stu-id="ef2be-119">**Restrict users from creating sites or subsites**</span></span>

<span data-ttu-id="ef2be-120">Kao administrator SharePoint ili Office 365 Global admin, korisnicima možete dozvoliti da kreiraju i administriraju sopstvene SharePoint lokacije, da utvrde koje vrste lokacija mogu da kreiraju i da odrede lokaciju lokacija.</span><span class="sxs-lookup"><span data-stu-id="ef2be-120">As a SharePoint admin or Office 365 global admin, you can let your users create and administer their own SharePoint sites, determine what kind of sites they can create, and specify the location of the sites.</span></span> <span data-ttu-id="ef2be-121">Više informacija potražite [u članku Upravljanje kreiranjem lokacije u sistemu SharePoint online](https://docs.microsoft.com/sharepoint/manage-site-creation)</span><span class="sxs-lookup"><span data-stu-id="ef2be-121">For more information, please see [Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation)</span></span>

