---
title: Rešavanje problema pristup nije dozvoljen poruke OneDrive za poslovne lokacije
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: d47ce80bdd07a25d9724057edf0289808a00a3db
ms.sourcegitcommit: 8a83b508785c96c19648ed574f442bbef2c2dff9
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/07/2019
ms.locfileid: "36232552"
---
# <a name="troubleshooting-access-denied-messages-to-onedrive-for-business-sites"></a>Rešavanje problema pristup nije dozvoljen poruke OneDrive za poslovne lokacije

Do ovog problema najčešće dolazi kada korisnik je izbrisan i ponovo kreiran sa istom glavno ime korisnika (UPN). Novi nalog kreiran pomoću različitih PUID (jedinstveni Passport ID) vrednost. Kada korisnik pokuša da pristupi kolekciju lokacija ili njihove OneDrive, je jedan pogrešan PUID korisnika. Drugi scenario uključuje sinhronizacija direktorijuma sa organizacionih jedinica za Active Directory (OU). Ako su korisnici već prijavljeni na SharePoint, i onda su se preselili u različitim OU i najhrabriji sa SharePoint, oni su iskusiti ovaj problem.

1. Da biste rešili ovaj problem bi trebalo obnoviti originalne UPN sa koracima u članku,[Vraćanje korisnik u Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).
2. Ako nije moguće vratiti originalni korisnik treba da uklonite stari korisnika na OneDrive lokaciji koristeći ove korake, [Uklanjanje korisnika iz liste sa informacijama korisnika](). 
3. Nakon ovoga, možete da potvrdite da korisnik ima admin prava na OneDrive lokaciju tako što ćete pratiti korake za [Dodavanje admin je za korisnika OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)

Za više informacija o nivoima dozvola, potražite u članku, [Razumevanje nivoa dozvola u sistemu SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).
