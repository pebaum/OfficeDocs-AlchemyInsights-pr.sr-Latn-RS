---
title: Rešavanje problema sa zabranom pristupa porukama
ms.author: kirks
author: Techwriter40
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: c204f1889e03886fdfd3d1c760a4a2beb82b0836
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34760354"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a>Rešavanje problema sa zabranom pristupa porukama u Sharepoint/OneDrive Admin Center

Ako dobijate pristup nije dozvoljen poruka pri pokušaju da pregledaju Sharepoint/OneDrive Admin centru, uverite se da [dodelite dozvole za korisnika](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One). Ako korisnik ima dozvolu, obavezno takođe se uverite da su [dodeljene su ulogu administratora](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) koji možete da pristupite sa admin centrima.

Ovog problema takođe može doći kada korisnik je izbrisan i ponovo kreiran sa istom glavno ime korisnika (UPN). Novi nalog kreiran pomoću različitih PUID (jedinstveni Passport ID) vrednost. Kada korisnik pokuša da pristupi kolekciju lokacija ili njihove OneDrive, je jedan pogrešan PUID korisnika. Drugi scenario uključuje sinhronizacija direktorijuma sa organizacionih jedinica za Active Directory (OU). Ako su korisnici već prijavljeni na SharePoint, i onda su se preselili u različitim OU i najhrabriji sa SharePoint, oni su iskusiti ovaj problem.

Da biste rešili ovaj problem, trebalo da vratite u prethodno stanje originalnu UPN sa koracima u članku, [Vraćanje korisnik u Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).

Napomena: Ako centar za OneDrive ili SharePoint Admin nije dostupna za više korisnika koji su prethodno imali pristup, postoji problem sa privremene usluge.  [Proverite kontrolnu tablu zdravstvenih usluga](https://portal.office.com/adminportal/home#/servicehealth).


