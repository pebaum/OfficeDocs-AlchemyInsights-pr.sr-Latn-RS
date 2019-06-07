---
title: Korisnicima dali pristup SharePoint i OneDrive
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: a689769dab24e12832ddc0937bc5ddc3d71dbee3
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34759269"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a>Korisnicima dali pristup SharePoint i OneDrive

Do ovog problema najčešće dolazi kada korisnik je izbrisan i ponovo kreiran sa istom glavno ime korisnika (UPN). Novi nalog kreiran pomoću različitih PUID (jedinstveni Passport ID) vrednost. Kada korisnik pokuša da pristupi kolekciju lokacija ili njihove OneDrive, je jedan pogrešan PUID korisnika. Drugi scenario uključuje sinhronizacija direktorijuma sa organizacionih jedinica za Active Directory (OU). Ako su korisnici već prijavljeni na SharePoint, i onda su se preselili u različitim OU i najhrabriji sa SharePoint, oni su iskusiti ovaj problem.

Da biste rešili ovaj problem bi trebalo obnoviti originalne UPN sa koracima u članku,[Vraćanje korisnik u Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).

Nakon ovoga, možete da potvrdite da korisnik ima admin prava na OneDrive lokaciju tako što ćete pratiti korake za [Dodavanje admin je za korisnika OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)

Za više informacija o nivoima dozvola, potražite u članku, [Razumevanje nivoa dozvola u sistemu SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).
