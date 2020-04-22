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
# <a name="enable-office-365-advanced-threat-protection-for-sharepoint-online-onedrive-and-microsoft-teams"></a>Omogućite Office 365 naprednu zaštitu pretnji za SharePoint online, OneDrive i Microsoft timove

1. Idite na https://protection.office.com lokaciju i prijavite se.
2. Odaberite**bezbedne priloge** > **smernica** > za **Upravljanje pretnjama**.
3. Izaberite opciju " **UKLJUČI ATP" za SharePoint, OneDrive i Microsoft timove**, a zatim kliknite na dugme **Sačuvaj**.
4. Preporučuje Kao globalni administrator ili SharePoint administrator na mreži, pokrenite [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) cmdpustiš sa **Disekalizacedfiledownload** parametrom postavljen na *TRUE*.
5. Preporučuje [Podesite obaveštenja](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) za otkrivene datoteke.

> [!NOTE]
> ATP će da skenira svaku datoteku u SharePoint online, OneDrive ili Microsoft timovima. Datoteke se asinhrono skeniraju, putem procesa koji koristi događaje deljenja i gosta, zajedno sa pametnim heuristima i signalima pretnji za identifikovanje zlonamernih datoteka. Vidite [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).