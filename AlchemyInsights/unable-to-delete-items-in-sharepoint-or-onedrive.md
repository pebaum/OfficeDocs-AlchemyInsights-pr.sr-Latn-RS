---
title: Nije moguće izbrisati stavke u sistemu SharePoint ili OneDrive
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: abfcb91c6040aeed759d697ca63546ccea8ede97
ms.sourcegitcommit: c5e800313a6f211386a384716e5fa18e7fcc8c1c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/28/2020
ms.locfileid: "41571285"
---
# <a name="unable-to-delete-items"></a>Nije moguće izbrisati stavke

Smernice za zadržavanje mogu da prouzrokuju ovo, potrebno je da onemogućite ili izuzmete odgovarajuće zadršku koji uzrokuje ovaj problem. Nakon uklanjanja smernica za zadržavanje ili držanja, možda će biti potrebno najviše 24 sata da bi promena stupila na snagu. Uverite se da na stavci nema podešavanja [smernica za zadržavanje](https://docs.microsoft.com/office365/securitycompliance/retention-policies) .

Lokacija je možda prekoračila ograničenje prostora za skladištenje, povećala [kvotu lokacije](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) i izbrišite stavku.

Uverite se da stavka nije [odjavljena](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) na drugi korisnik.

Na kraju, administratori mogu da koriste [SharePoint obrasce i prakse](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PNP) koji sadrže biblioteku komandi PowerShell koje vam omogućavaju da izvršavate složene radnje upravljanja, kao što je sila brisanje tvrdoglavih stavki.
- [Ukloni PNP datoteku](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [Ukloni PNP fasciklu](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [Uklanjanje stavke PNP liste](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [Ukloni PNP listu](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [Ukloni PNP polje (kolona)](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)