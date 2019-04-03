---
title: Omogućite Office 365 ATP za SharePoint, OneDrive, a Microsoft timova
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/01/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: ae2f574663ae3233a056589c2d5a578171f3b2f4
ms.sourcegitcommit: 601aec31e6556286fe5e0fd62827a037cbb6fe17
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/02/2019
ms.locfileid: "31031078"
---
# <a name="enable-office-365-advanced-threat-protection-for-sharepoint-online-onedrive-and-microsoft-teams"></a><span data-ttu-id="52165-102">Omogućite Office 365 napredne pretnja zaštitu za SharePoint Online, OneDrive, a Microsoft timova</span><span class="sxs-lookup"><span data-stu-id="52165-102">Enable Office 365 Advanced Threat Protection for SharePoint Online, OneDrive, and Microsoft Teams</span></span>

1. <span data-ttu-id="52165-103">Idite na https://protection.office.com i prijavite se.</span><span class="sxs-lookup"><span data-stu-id="52165-103">Go to https://protection.office.com and sign in.</span></span>
2. <span data-ttu-id="52165-104">Odaberite **prijetnje** > **politiku** > **Sigurnom priloge**.</span><span class="sxs-lookup"><span data-stu-id="52165-104">Choose **Threat management** > **Policy** > **Safe Attachments**.</span></span>
3. <span data-ttu-id="52165-105">Izaberite **Uključi ATP za SharePoint, OneDrive, a Microsoft timova**, a zatim kliknite na dugme **Sačuvaj**.</span><span class="sxs-lookup"><span data-stu-id="52165-105">Select **Turn on ATP for SharePoint, OneDrive, and Microsoft Teams**, and then click **Save**.</span></span>
4. <span data-ttu-id="52165-106">(Preporučuje se) Kao globalni administrator ili administrator SharePoint Online, pokrenete na cmdlet [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) s parametrom **DisallowInfectedFileDownload** na *true*.</span><span class="sxs-lookup"><span data-stu-id="52165-106">(Recommended) As a global administrator or a SharePoint Online administrator, run the [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) cmdlet with the **DisallowInfectedFileDownload** parameter set to *true*.</span></span>
5. <span data-ttu-id="52165-107">(Preporučuje se) [Podešavanje upozorenja](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) pronađenih datoteka.</span><span class="sxs-lookup"><span data-stu-id="52165-107">(Recommended) [Set up alerts](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) for detected files.</span></span>

> [!NOTE]
> <span data-ttu-id="52165-108">ATP će nda skeniranje svaki jednu datoteku u SharePoint Online, OneDrive ili Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="52165-108">ATP will nto scan every single file in SharePoint Online, OneDrive, or Microsoft Teams.</span></span> <span data-ttu-id="52165-109">Datoteke su skenirane asinhrono, kroz proces koji koristi deljenje i gostujućih događaja aktivnosti, zajedno sa pametan heuristiku i pretnje signale za identifikovanje zlonamernog datoteke.</span><span class="sxs-lookup"><span data-stu-id="52165-109">Files are scanned asynchronously, through a process that uses sharing and guest activity events, along with smart heuristics and threat signals to identify malicious files.</span></span> <span data-ttu-id="52165-110">Vidim [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="52165-110">See [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span></span>