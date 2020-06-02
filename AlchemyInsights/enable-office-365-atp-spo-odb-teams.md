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
ms.openlocfilehash: 564a7f1f6a37e64dbd7d679878ebadbbe35f3fa0
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506932"
---
# <a name="enable-office-365-advanced-threat-protection-for-sharepoint-online-onedrive-and-microsoft-teams"></a>Omogućite Office 365 naprednu zaštitu pretnji za SharePoint online, OneDrive i Microsoft timove

1. Idite na lokaciju https://protection.office.com i prijavite se.
2. Odaberite **Threat management**  >  **Policy**  >  **bezbedne priloge**smernica za upravljanje pretnjama.
3. Izaberite opciju " **UKLJUČI ATP" za SharePoint, OneDrive i Microsoft timove**, a zatim kliknite na dugme **Sačuvaj**.
4. Preporučuje Kao globalni administrator ili SharePoint administrator na mreži, pokrenite [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) cmdpustiš sa **Disekalizacedfiledownload** parametrom postavljen na *TRUE*.
5. Preporučuje [Podesite obaveštenja](https://docs.microsoft.com/microsoft-365/security/office-365-security/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) za otkrivene datoteke.

> [!NOTE]
> ATP će da skenira svaku datoteku u SharePoint online, OneDrive ili Microsoft timovima. Datoteke se asinhrono skeniraju, putem procesa koji koristi događaje deljenja i gosta, zajedno sa pametnim heuristima i signalima pretnji za identifikovanje zlonamernih datoteka. Pogledajte [ATP za SharePoint, OneDrive i Microsoft timove](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams).