---
title: 2609-ili-ediscovery-održavanje
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2609"
- "9000048"
ms.openlocfilehash: 85c41995545efd8e1526d9f7dce4a23929f85be5
ms.sourcegitcommit: 24e8248b0f061a76af50bf566d7a13fc24d29d99
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/05/2019
ms.locfileid: "37994092"
---
# <a name="unable-to-delete-items-in-sharepoint-online-or-onedrive-for-business"></a>Nije moguće izbrisati stavke u sistemu SharePoint Online ili OneDrive za posao

Vi ili vaši korisnici možda nećete moći da izbrišete stavke na SharePoint mreži ili u usluzi OneDrive za posao zato što se smernice za zadržavanje, lokacija za zadržavanje ili eDiscovery zadršku primenjuju na SharePoint OneDrive lokaciju ili na određenu stavku. Ovo podrazumeva da nije moguće izbrisati dokument, verziju dokumenta, fasciklu, biblioteku dokumenata, listu, aplikaciju, lokaciju ili kolekciju lokacija. Evo nekih primera poruka o grešci koje možete da primite ako pokušate da izbrišete stavku koja se zadržava:

- "Nije moguće izbrisati ovu lokaciju zato što je uključena u eDiscovery zadršku ili zadržavanja"
- "Ova lokacija ima smernice za usaglašenost podešene da blokiraju brisanje"
- "Smernice usaglašenosti trenutno blokiraju brisanje ove lokacije"
- "Ova kolekcija lokacija ne može da se izbriše jer sadrži lokacije koje su uključene u smernice za eDiscovery zadržavanje ili zadržavanje"
- "Morate da izbrišete sve stavke u ovoj fascikli pre nego što izbrišete fasciklu"
- "Nije moguće izbrisati verzije ove stavke zato što je uključena u smernice za čekanje ili zadržavanje"
- "Stavka se ne može izbrisati dok je na čekanju"
- "Oznaka koja je primenjena na ovu stavku sprečava uređivanje ili brisanje"
- "Nije moguće izbrisati listu dok ste na smernicama za čekanje ili zadržavanje"
- "Nije moguće izbrisati listu ako je blokirana ili ako je primenjena smernica za zadržavanje"

Da biste izbrisali stavke u jednom od ovih scenarija, moraju biti uklonjene smernice za zadržavanje, oznaka zadržavanja ili eDiscovery zadrška (ili lokacija mora biti isključena iz smernica za zadržavanje). Potrebno je da onemogućite ili isključite odgovarajući zadrška koji uzrokuje ovaj problem. Nakon uklanjanja smernica za zadržavanje ili držanja, možda će biti potrebno najviše 24 sata da bi promena stupila na snagu. 

Više informacija o različitim funkcijama zadržavanja i držanja koje se mogu primeniti na SharePoint lokacije i OneDrive naloge potražite u nekoj od sledećih tema.

- [Pregled smernica za zadržavanje](https://docs.microsoft.com/microsoft-365/compliance/retention-policies)

- [Pregled nalepnica za zadržavanje](https://docs.microsoft.com/microsoft-365/compliance/labels)

- [Upravljaj zadrškama u naprednim eDiscovery](https://docs.microsoft.com/microsoft-365/compliance/managing-holds)

- [eDiscovery ima](https://docs.microsoft.com/microsoft-365/compliance/ediscovery-cases#step-4-place-content-locations-on-hold)

- [Naslijeđena pravila o zatvaranju i brisanju lokacije](https://support.office.com/article/Use-policies-for-site-closure-and-deletion-A8280D82-27FD-48C5-9ADF-8A5431208BA5)
