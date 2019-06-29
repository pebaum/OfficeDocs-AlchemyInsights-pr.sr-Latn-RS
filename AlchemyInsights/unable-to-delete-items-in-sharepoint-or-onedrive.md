---
title: Nije moguće izbrisati stavke u SharePoint ili OneDrive
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: d25214f26a3168e3e350b5cc31ca870e65d48ad9
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/28/2019
ms.locfileid: "35366547"
---
# <a name="unable-to-delete-items"></a>Nije moguće izbrisati stavke

Imamo problema brisanja stavki?

- Uvek se uverite da imate [odgovarajuće dozvole](https://docs.microsoft.com/sharepoint/default-sharepoint-groups) da izbrišete stavku ili je [administrator kolekcije lokacija](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) pokušaj da biste uklonili stavku.

- Uverite se da tamo nije nameštaljka [smernica za čuvanje](https://docs.microsoft.com/office365/securitycompliance/retention-policies) na stavci.

- Uverite se da stavka nije [odjavio](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) drugi korisnik.

- Konačno, administratori mogu da koriste [SharePoint šare i prakse](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) koje sadrži biblioteku PowerShell komande koje vam dozvoljavaju da izvršite složene upravljanja radnje kao što je prisiliti da brisanja stavki tvrdoglav.
- [Uklonite PNP datoteku](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [Uklonite PNP fasciklu](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [Ukloni stavku PNP liste](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [Uklanjanje PNP liste](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [Uklonite PNP polje (kolona)](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)