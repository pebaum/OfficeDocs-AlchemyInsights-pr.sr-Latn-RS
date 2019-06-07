---
title: Dodavanje grupe na SharePoint lokaciji
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f7d730bf-0d6e-424c-970c-6137c71cb50b
ms.openlocfilehash: f0126f7f753275e9bbf8c3a09a6af5faf9a27862
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34758744"
---
# <a name="create-group-connected-site-in-sharepoint-online"></a>Kreiranje grupe povezanih lokacija u SharePoint Online

Postoji nekoliko uobičajenih problema naišao na povezivanju kreiranje ili ponovno Kreiranje grupe lokacija.

 Ako ste izbrisali grupu i njene povezanih lokacija i želimo da stvorimo neku drugu lokaciju sa istom URL adresom, moraćete da trajno uklonite prethodnu lokaciju.

Preuzmite [SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)

 Za više informacija na prvi koraci u powershell, pogledajte [Prvi koraci sa SharePoint Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)

Uklanjanje lokacije iz izbrisane lokacija koristi za [Uklanjanje SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) powershell cmdlet.

Ako kreirate grupe povezanih lokacija i dobijete upozorenje druga grupa sa istim imenom već postoji, proverite postojeće grupe iz [Office 365 iz centra za administraciju](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups). Rešite problem, izbrišite postojeće grupe, ako to više nije potrebna ili kreirate lokaciju sa različitim pseudonim dodeljen.

Postoje različiti načini za kreiranje i koriste moderne grupe sa SharePoint.

Možete da se povežete postojeće lokacije Office 365 grupi. Za više informacija, potražite u odeljku [Povezivanje grupi programa Office 365 pomoću ineterface korisnika u SharePoint](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).

Da biste kreirali povezani lokaciju Office 365 grupe, moraćete da kreirate lokaciju tima. Za više informacija, potražite u odeljku [Kreiranje lokaciju tima u sistemu SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).

