---
title: Ograniči pristup u SharePoint ili OneDrive
ms.author: kirks
author: Techwriter40
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: 84f2d4b6e5fd2380a2fa96e30953c68aab203cd3
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36559891"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a><span data-ttu-id="41d9d-102">Ograniči pristup u SharePoint ili OneDrive</span><span class="sxs-lookup"><span data-stu-id="41d9d-102">Restrict access in SharePoint or OneDrive</span></span>

<span data-ttu-id="41d9d-103">Postoji mnogo načina da biste ograničili pristup uslugama SharePoint Online/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="41d9d-103">There are many ways to restrict access to SharePoint Online/OneDrive services.</span></span> <span data-ttu-id="41d9d-104">Ove različite metode ograničenja pristupa je izložio ispod.</span><span class="sxs-lookup"><span data-stu-id="41d9d-104">These various access restriction methods are outlined below.</span></span> 

<span data-ttu-id="41d9d-105">**Ograničenje dozvole**</span><span class="sxs-lookup"><span data-stu-id="41d9d-105">**Permission Restriction**</span></span>

<span data-ttu-id="41d9d-106">U SharePoint Online i OneDrive za posao, smo ograničite pristup stavki kao što su lokacije, datoteke i fascikle koje samo omogućavanjem pristupa tim grupama/pojedinaca koji bi trebalo da imaju pristup.</span><span class="sxs-lookup"><span data-stu-id="41d9d-106">In SharePoint Online and OneDrive for Business, we restrict access to items like sites, files and folders by only granting access to those groups/individuals who should have access.</span></span>

- [<span data-ttu-id="41d9d-107">Prilagodite dozvolama za SharePoint liste ili biblioteke</span><span class="sxs-lookup"><span data-stu-id="41d9d-107">Customize permissions for a SharePoint list or library</span></span>](https://support.office.com/article/Customize-permissions-for-a-SharePoint-list-or-library-02d770f3-59eb-4910-a608-5f84cc297782)

- [<span data-ttu-id="41d9d-108">Prilagođavanje SharePoint lokacija dozvole</span><span class="sxs-lookup"><span data-stu-id="41d9d-108">Customize SharePoint site permissions</span></span>](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions)

- [<span data-ttu-id="41d9d-109">Promenite dozvole za potfasciklu</span><span class="sxs-lookup"><span data-stu-id="41d9d-109">Change the permissions on a subfolder</span></span>](https://support.office.com/article/Change-the-permissions-on-a-subfolder-5427BD7C-F20A-4F75-8CF2-5359DD45A1A6)

- [<span data-ttu-id="41d9d-110">Kontrola pristupa sa nekontrolisana uređaja</span><span class="sxs-lookup"><span data-stu-id="41d9d-110">Control access from unmanaged devices</span></span>](https://docs.microsoft.com/sharepoint/control-access-from-unmanaged-devices)

<span data-ttu-id="41d9d-111">Kao SharePoint ili globalne admin u Office 365, možete blokirati ili ograničiti pristup SharePoint i OneDrive sadržaja sa nekontrolisana uređaja (onih hibrida AD spojenih ili usaglašeni u Intune).</span><span class="sxs-lookup"><span data-stu-id="41d9d-111">As a SharePoint or global admin in Office 365, you can block or limit access to SharePoint and OneDrive content from unmanaged devices (those not hybrid AD joined or compliant in Intune).</span></span>

<span data-ttu-id="41d9d-112">**Ograničenje mrežne lokacije**</span><span class="sxs-lookup"><span data-stu-id="41d9d-112">**Network Location Restriction**</span></span>

<span data-ttu-id="41d9d-113">Kao neki IT administrator, možete da kontrolišete pristup SharePoint i OneDrive resurse na osnovu definisanih mrežne lokacije koje smatrate pouzdanim.</span><span class="sxs-lookup"><span data-stu-id="41d9d-113">As an IT admin, you can control access to SharePoint and OneDrive resources based on defined network locations that you trust.</span></span> <span data-ttu-id="41d9d-114">Ovo je takođe poznat kao politika zasnovanih na lokaciji.</span><span class="sxs-lookup"><span data-stu-id="41d9d-114">This is also known as location-based policy.</span></span> <span data-ttu-id="41d9d-115">Za više informacija, pogledajte [da kontroliše pristup SharePoint Online i OneDrive podataka na osnovu mrežne lokacije](https://docs.microsoft.com/sharepoint/control-access-based-on-network-location)</span><span class="sxs-lookup"><span data-stu-id="41d9d-115">For more information, please see [Control access to SharePoint Online and OneDrive data based on network location](https://docs.microsoft.com/sharepoint/control-access-based-on-network-location)</span></span>

<span data-ttu-id="41d9d-116">**Lokacija Lock ograničenja**</span><span class="sxs-lookup"><span data-stu-id="41d9d-116">**Site Lock Restriction**</span></span> 

<span data-ttu-id="41d9d-117">U okviru SharePoint Online, imate mogućnost da zatvorimo kolekcije lokacija, tako da niko nema pristup.</span><span class="sxs-lookup"><span data-stu-id="41d9d-117">Within SharePoint Online you have the ability to lock down a site collection, so no one has access.</span></span> <span data-ttu-id="41d9d-118">Ovo je postavljen preko PowerShell i [SharePoint Online Management Shell](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) koristeći svojstvo [Set-SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) - LockState.</span><span class="sxs-lookup"><span data-stu-id="41d9d-118">This is set via PowerShell and the [SharePoint Online Management Shell](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) using the [Set-SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -LockState property.</span></span>

<span data-ttu-id="41d9d-119">**Ograničavanje korisnika da kreirate lokacije ili podlokacije**</span><span class="sxs-lookup"><span data-stu-id="41d9d-119">**Restrict users from creating sites or subsites**</span></span>

<span data-ttu-id="41d9d-120">Kao SharePoint admin ili Office 365 globalne admin, možete da omogućite korisnicima da kreirate i administrirate sopstvene SharePoint lokacije, utvrdite koja vrsta lokacije mogu da kreiraju, i Navedite lokaciju na lokacijama.</span><span class="sxs-lookup"><span data-stu-id="41d9d-120">As a SharePoint admin or Office 365 global admin, you can let your users create and administer their own SharePoint sites, determine what kind of sites they can create, and specify the location of the sites.</span></span> <span data-ttu-id="41d9d-121">Za više informacija, pogledajte [Upravljanje Kreiranje lokacije u SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation)</span><span class="sxs-lookup"><span data-stu-id="41d9d-121">For more information, please see [Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation)</span></span>

