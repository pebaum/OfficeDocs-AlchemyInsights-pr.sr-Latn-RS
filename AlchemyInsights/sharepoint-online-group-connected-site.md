---
title: Dodavanje grupe na SharePoint lokaciju
ms.author: pebaum
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f7d730bf-0d6e-424c-970c-6137c71cb50b
ms.openlocfilehash: 423db4e5bbb85e75aee3548d5b6b46a64ebc6fa0
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/18/2019
ms.locfileid: "36750534"
---
# <a name="issues-when-creating-or-group-connected-sites-in-sharepoint-online"></a>Problemi prilikom kreiranja ili grupisanja povezanih lokacija u sistemu SharePoint online

Došlo je do nekoliko uobičajenih problema prilikom kreiranja ili ponovnog kreiranja grupe povezane lokacije.

 Ako ste izbrisali grupu i povezanu lokaciju i želite da kreirate drugu lokaciju sa istom URL adresom, moraćete trajno da uklonite prethodnu lokaciju.

Preuzimanje [ljuske za upravljanje SPO](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429) -a

 Više informacija o početku rada sa programom PowerShell potražite [u članku prvi koraci u usluzi SharePoint Shell Management ljuske](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)

Uklonite lokaciju sa izbrisanih lokacija koristeći [stranicu ukloni-Prebrisedshell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) cmdto.

Ako kreirate grupu povezanu sa grupom i primite upozorenje druga grupa sa istim pseudonimom već postoji, proverite postojeće grupe iz [sistema Office 365 iz administratorskog centra](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups). Da biste rešili problem, izbrišite postojeću grupu ako više nije potrebna ili kreirajte lokaciju sa dodeljenim drugim pseudonimom.

Postoje različiti načini za kreiranje i korišćenje modernih grupa sa SharePoint-om.

Postojeće lokacije možete da povežete sa Office 365 grupom. Više informacija potražite u članku [Povezivanje Office 365 grupe pomoću SharePoint korisnika koji je neodređen](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).

Potrebno je da kreirate lokaciju tima da biste kreirali Office 365 grupu povezanu lokaciju. Više informacija potražite u članku [Kreiranje lokacije tima u sistemu SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).

