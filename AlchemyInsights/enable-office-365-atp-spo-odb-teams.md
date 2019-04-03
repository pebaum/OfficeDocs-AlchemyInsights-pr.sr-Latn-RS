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
# <a name="enable-office-365-advanced-threat-protection-for-sharepoint-online-onedrive-and-microsoft-teams"></a>Omogućite Office 365 napredne pretnja zaštitu za SharePoint Online, OneDrive, a Microsoft timova

1. Idite na https://protection.office.com i prijavite se.
2. Odaberite **prijetnje** > **politiku** > **Sigurnom priloge**.
3. Izaberite **Uključi ATP za SharePoint, OneDrive, a Microsoft timova**, a zatim kliknite na dugme **Sačuvaj**.
4. (Preporučuje se) Kao globalni administrator ili administrator SharePoint Online, pokrenete na cmdlet [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) s parametrom **DisallowInfectedFileDownload** na *true*.
5. (Preporučuje se) [Podešavanje upozorenja](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) pronađenih datoteka.

> [!NOTE]
> ATP će nda skeniranje svaki jednu datoteku u SharePoint Online, OneDrive ili Microsoft Teams. Datoteke su skenirane asinhrono, kroz proces koji koristi deljenje i gostujućih događaja aktivnosti, zajedno sa pametan heuristiku i pretnje signale za identifikovanje zlonamernog datoteke. Vidim [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).