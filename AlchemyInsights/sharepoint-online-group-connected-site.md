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
ms.openlocfilehash: 352bad1b8fe219f95a37c9ac268c6c4dd8801dfc
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/04/2019
ms.locfileid: "34719495"
---
# <a name="create-group-connected-site-in-sharepoint-online"></a>Kreiranje grupe povezanih lokacija u SharePoint Online

<p><strong>Postoji nekoliko uobičajenih problema naišao na povezivanju kreiranje ili ponovno Kreiranje grupe lokacija.&nbsp;</strong></p>  <p>1.Ako ste izbrisali grupu i njene povezanih lokacija i želimo da stvorimo neku drugu lokaciju sa istom URL adresom, moraćete da trajno uklonite prethodnu lokaciju.</p>  <ul>  <li>Preuzmite <a title="SPO Management Shell" href="https://support.office.com/en-ie/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429">SPO Management Shell</a> - za više informacija na prvi koraci u powershell, vidim <a title="prvi koraci u programu SharePoint Online Management Shell" href="https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps">Prvi koraci u programu SharePoint Online Management Shell</a>. <br /><br /></li>  <li>Uklanjanje lokacije iz izbrisane lokacije koristeći se <a title="ukloni SPODeletedSite" href="https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps">Ukloni SPODeletedSite</a> powershell cmdlet.</li>  </ul>  <p>Ako kreirate grupe povezanih lokacija i dobijete upozorenje <strong>„druga grupa sa istim imenom već postoji”</strong>, proveri postojeće grupe iz u <a title="Office 365 iz centra za Admin" href="https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups">Office 365 iz centra za Admin</a>. Rešite problem, izbrišite postojeće grupe, ako to više nije potrebna ili kreirate lokaciju sa različitim pseudonim dodeljen.&nbsp;</p>  <p><strong>Postoje različiti načini za kreiranje i koriste moderne grupe sa SharePoint.&nbsp;</strong></p>  <ol>  <li>Možete da se povežete postojeće lokacije Office 365 grupi. Za više informacija, pogledajte <a title="povezivanje grupi programa Office 365 pomoću ineterface korisnika u SharePoint" href="https://docs.microsoft.com/en-us/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface">Povezivanje grupi programa Office 365 pomoću ineterface korisnika u SharePoint</a>.</li>  <li>Da biste kreirali povezani lokaciju Office 365 grupe, moraćete da kreirate lokaciju tima. Za više informacija, pogledajte <a title="kreirate lokaciju tima u sistemu SharePoint" href="https://support.office.com/en-us/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d">Kreiranje lokacija tima u sistemu SharePoint.</a></li>  </ol>

