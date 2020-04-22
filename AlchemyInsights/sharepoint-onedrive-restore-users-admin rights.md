---
title: Rešavanje problema sa programom Access je zabranio poruke za poslovne lokacije u usluzi OneDrive
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: a83936acf969926c113b28ceb22b006cdb96e2b4
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43692815"
---
# <a name="troubleshooting-access-denied-messages-to-onedrive-for-business-sites"></a>Rešavanje problema sa programom Access je zabranio poruke za poslovne lokacije u usluzi OneDrive

Do ovog problema najčešće dolazi kada se korisnik izbriše i ponovo kreira sa istim glavnim korisničkim imenom (UPN). Novi nalog se kreira koristeći drugačiju PUID (Passport jedinstveni ID) vrednost. Kada korisnik pokuša da pristupi kolekciji lokacija ili usluzi OneDrive, korisnik ima neispravan PUID. Drugi scenario uključuje sinhronizaciju direktorijuma sa organizacionom jedinicom aktivnog direktorijuma (OU). Ako su korisnici već prijavljeni na SharePoint, a zatim se premeštaju u drugu i ponovo povezani sa SharePoint, može doći do ovog problema.

1. Da biste rešili ovaj problem, trebalo bi da vratite originalni UPN sa koracima u članku, [vratite korisnika u aplikaciji Microsoft 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).
2. Ako ne možete da vratite prvobitni korisnik u prethodno stanje, trebalo bi da uklonite starog korisnika sa lokacije OneDrive koristeći ove korake, [uklonite korisnika sa liste korisničkih informacija](). 
3. Kada se to uradi, možete da proverite da li korisnik ima administratorska prava za OneDrive lokaciju tako što ćete slediti korake za [Dodavanje admin-a za korisnike usluge OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles)

Više informacija o nivoima dozvola potražite u članku, [Razumevanje nivoa dozvola u sistemu SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).
