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
# <a name="restrict-access-in-sharepoint-or-onedrive"></a>Ograniči pristup u SharePoint ili OneDrive

Postoji mnogo načina da biste ograničili pristup uslugama SharePoint Online/OneDrive. Ove različite metode ograničenja pristupa je izložio ispod. 

**Ograničenje dozvole**

U SharePoint Online i OneDrive za posao, smo ograničite pristup stavki kao što su lokacije, datoteke i fascikle koje samo omogućavanjem pristupa tim grupama/pojedinaca koji bi trebalo da imaju pristup.

- [Prilagodite dozvolama za SharePoint liste ili biblioteke](https://support.office.com/article/Customize-permissions-for-a-SharePoint-list-or-library-02d770f3-59eb-4910-a608-5f84cc297782)

- [Prilagođavanje SharePoint lokacija dozvole](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions)

- [Promenite dozvole za potfasciklu](https://support.office.com/article/Change-the-permissions-on-a-subfolder-5427BD7C-F20A-4F75-8CF2-5359DD45A1A6)

- [Kontrola pristupa sa nekontrolisana uređaja](https://docs.microsoft.com/sharepoint/control-access-from-unmanaged-devices)

Kao SharePoint ili globalne admin u Office 365, možete blokirati ili ograničiti pristup SharePoint i OneDrive sadržaja sa nekontrolisana uređaja (onih hibrida AD spojenih ili usaglašeni u Intune).

**Ograničenje mrežne lokacije**

Kao neki IT administrator, možete da kontrolišete pristup SharePoint i OneDrive resurse na osnovu definisanih mrežne lokacije koje smatrate pouzdanim. Ovo je takođe poznat kao politika zasnovanih na lokaciji. Za više informacija, pogledajte [da kontroliše pristup SharePoint Online i OneDrive podataka na osnovu mrežne lokacije](https://docs.microsoft.com/sharepoint/control-access-based-on-network-location)

**Lokacija Lock ograničenja** 

U okviru SharePoint Online, imate mogućnost da zatvorimo kolekcije lokacija, tako da niko nema pristup. Ovo je postavljen preko PowerShell i [SharePoint Online Management Shell](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) koristeći svojstvo [Set-SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) - LockState.

**Ograničavanje korisnika da kreirate lokacije ili podlokacije**

Kao SharePoint admin ili Office 365 globalne admin, možete da omogućite korisnicima da kreirate i administrirate sopstvene SharePoint lokacije, utvrdite koja vrsta lokacije mogu da kreiraju, i Navedite lokaciju na lokacijama. Za više informacija, pogledajte [Upravljanje Kreiranje lokacije u SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation)

