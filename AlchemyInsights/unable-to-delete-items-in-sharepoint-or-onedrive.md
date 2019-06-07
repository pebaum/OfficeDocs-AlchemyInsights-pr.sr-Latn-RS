---
title: Nije moguće izbrisati stavke u SharePoint ili OneDrive
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 82a19c8ea218834b71901e95747da0c99243893e
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34757938"
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