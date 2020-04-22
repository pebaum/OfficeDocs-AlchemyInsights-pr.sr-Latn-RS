---
title: Ograničavanje pristupa u sistemu SharePoint ili OneDrive
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: 39aa8cd6e649eca4a1e196eeb589a825364d0977
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43692779"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a>Ograničavanje pristupa u sistemu SharePoint ili OneDrive

Postoji mnogo načina da ograničite pristup SharePoint online/OneDrive uslugama. Ovi različiti metodi ograničenja pristupa su dole navedeni. 

**Ograničenje dozvole**

U sistemu SharePoint Online i OneDrive za preduzeća ograničavamo pristup stavkama kao što su lokacije, datoteke i fascikle samo pružanjem pristupa tim grupama/pojedincima koji treba da imaju pristup.

- [Prilagođavanje dozvola za SharePoint listu ili biblioteku](https://support.office.com/article/Customize-permissions-for-a-SharePoint-list-or-library-02d770f3-59eb-4910-a608-5f84cc297782)

- [Prilagođavanje dozvola za SharePoint lokaciju](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions)

- [Promena dozvola u potfascikli](https://support.office.com/article/Change-the-permissions-on-a-subfolder-5427BD7C-F20A-4F75-8CF2-5359DD45A1A6)

- [Kontrolisanje pristupa sa nekompletnog uređaja](https://docs.microsoft.com/sharepoint/control-access-from-unmanaged-devices)

Kao SharePoint ili globalni admin, možete blokirati ili ograničiti pristup SharePoint i OneDrive sadržaju sa nekompletnog uređaja (oni nisu spojeni ili usaglašeni u usluzi Intune).

**Ograničenje mrežne lokacije**

Kao IT administrator, možete kontrolisati pristup SharePoint i OneDrive resursima na osnovu definisanih mrežnih lokacija u koje imate poverenja. To se naziva i smernica zasnovana na lokaciji. Više informacija potražite u članku [Kontrola pristupa SharePoint Online i OneDrive podacima zasnovanim na mrežnoj lokaciji](https://docs.microsoft.com/sharepoint/control-access-based-on-network-location)

**Ograničenje zaključavanja lokacije** 

U okviru lokacije SharePoint online imate mogućnost da zaključate kolekciju lokacija, tako da niko nema pristup. Ovo je podešeno putem PowerShell i [SharePoint ljuske upravljanja na mreži](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) koristeći svojstvo [Set-sposit](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -lokstate.

**Ograničavanje korisnika da kreiraju lokacije ili podlokacije**

Kao administrator za SharePoint ili globalni admin, korisnicima možete dozvoliti da kreiraju i administriraju sopstvene SharePoint lokacije, da utvrde koje vrste lokacija mogu da kreiraju i da odrede lokaciju lokacija. Više informacija potražite [u članku Upravljanje kreiranjem lokacije u sistemu SharePoint online](https://docs.microsoft.com/sharepoint/manage-site-creation)

