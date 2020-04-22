---
title: Omogućite Office 365 ATP za SharePoint, OneDrive i Microsoft timove
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: fdfdc97a198898051a3388672d01994d96dd5e97
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703440"
---
# <a name="enable-office-365-advanced-threat-protection-for-sharepoint-online-onedrive-and-microsoft-teams"></a><span data-ttu-id="09e6a-102">Omogućite Office 365 naprednu zaštitu pretnji za SharePoint online, OneDrive i Microsoft timove</span><span class="sxs-lookup"><span data-stu-id="09e6a-102">Enable Office 365 Advanced Threat Protection for SharePoint Online, OneDrive, and Microsoft Teams</span></span>

1. <span data-ttu-id="09e6a-103">Idite na https://protection.office.com lokaciju i prijavite se.</span><span class="sxs-lookup"><span data-stu-id="09e6a-103">Go to https://protection.office.com and sign in.</span></span>
2. <span data-ttu-id="09e6a-104">Odaberite**bezbedne priloge** > **smernica** > za **Upravljanje pretnjama**.</span><span class="sxs-lookup"><span data-stu-id="09e6a-104">Choose **Threat management** > **Policy** > **Safe Attachments**.</span></span>
3. <span data-ttu-id="09e6a-105">Izaberite opciju " **UKLJUČI ATP" za SharePoint, OneDrive i Microsoft timove**, a zatim kliknite na dugme **Sačuvaj**.</span><span class="sxs-lookup"><span data-stu-id="09e6a-105">Select **Turn on ATP for SharePoint, OneDrive, and Microsoft Teams**, and then click **Save**.</span></span>
4. <span data-ttu-id="09e6a-106">Preporučuje Kao globalni administrator ili SharePoint administrator na mreži, pokrenite [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) cmdpustiš sa **Disekalizacedfiledownload** parametrom postavljen na *TRUE*.</span><span class="sxs-lookup"><span data-stu-id="09e6a-106">(Recommended) As a global administrator or a SharePoint Online administrator, run the [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) cmdlet with the **DisallowInfectedFileDownload** parameter set to *true*.</span></span>
5. <span data-ttu-id="09e6a-107">Preporučuje [Podesite obaveštenja](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) za otkrivene datoteke.</span><span class="sxs-lookup"><span data-stu-id="09e6a-107">(Recommended) [Set up alerts](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) for detected files.</span></span>

> [!NOTE]
> <span data-ttu-id="09e6a-108">ATP će da skenira svaku datoteku u SharePoint online, OneDrive ili Microsoft timovima.</span><span class="sxs-lookup"><span data-stu-id="09e6a-108">ATP will nto scan every single file in SharePoint Online, OneDrive, or Microsoft Teams.</span></span> <span data-ttu-id="09e6a-109">Datoteke se asinhrono skeniraju, putem procesa koji koristi događaje deljenja i gosta, zajedno sa pametnim heuristima i signalima pretnji za identifikovanje zlonamernih datoteka.</span><span class="sxs-lookup"><span data-stu-id="09e6a-109">Files are scanned asynchronously, through a process that uses sharing and guest activity events, along with smart heuristics and threat signals to identify malicious files.</span></span> <span data-ttu-id="09e6a-110">Vidite [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="09e6a-110">See [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span></span>