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
ms.openlocfilehash: cc19fcb6603160032dac52b1ec9e194a90b7891f
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40049531"
---
# <a name="unable-to-delete-items"></a>Nije moguće izbrisati stavke

Imate li problema sa brisanjem SharePoint stavki?

- Uvek se uverite da imate [odgovarajuće dozvole](https://docs.microsoft.com/sharepoint/default-sharepoint-groups) za brisanje stavke ili ako je [administrator kolekcije lokacija](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) pokušao da ukloni stavku.

- Uverite se da na stavci nema podešavanja [smernica za zadržavanje](https://docs.microsoft.com/office365/securitycompliance/retention-policies) .

- Uverite se da stavka nije [odjavljena](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) na drugi korisnik.

- Na kraju, administratori mogu da koriste [SharePoint obrasce i prakse](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PNP) koji sadrže biblioteku komandi PowerShell koje vam omogućavaju da izvršavate složene radnje upravljanja, kao što je sila brisanje tvrdoglavih stavki.
- [Ukloni PNP datoteku](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [Ukloni PNP fasciklu](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [Uklanjanje stavke PNP liste](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [Ukloni PNP listu](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [Ukloni PNP polje (kolona)](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)