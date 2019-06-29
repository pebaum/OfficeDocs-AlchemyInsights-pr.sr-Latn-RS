---
title: 1336 RecoverableItems fascikla je puna
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1336"
- "3700003"
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: 05e7b47a2200c3b0500e7d786166966ea301179a
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/28/2019
ms.locfileid: "35370401"
---
# <a name="the-recoverable-items-folder-is-full"></a>Spasen stavke fascikla je puna

Za Exchange Online poštanskih sandučića u Office 365, ograničenje skladištenja podrazumevanu fasciklu spasen stavke je 30 GB. Ograničenje prostora za fasciklu spasen stavke automatski se povećao na 100 GB, ako poštansko sanduče stavljen na parnice drži, drži eDiscovery, ili je dodeljen smernice za zadržavanje Office 365.

Kada fasciklu spasen stavke dostigne ograničenje prostora, funkcionalnost poštansko sanduče utiče na sledeće načine:

- Korisnika nije moguće izbrisati stavke iz poštansko sanduče.

- Upravlja pomoćnika za fascikle nije moguće izbrisati stavke na osnovu oznake zadržavanja ili postavke kontrolisane fascikle.

- Za Poštanske sandučiće koja sadrži jednu stavku za oporavak omogućen ili se nalaze na čekanju, proces zaštitu kopiranja pri upisivanju stranice ne mogu da održe verzije stavki uređivati od strane korisnika.

- Za Poštanske sandučiće koji imaju poštansko sanduče nadgledanja omogućeno evidentiranje, stavke evidencije nadgledanja nema poštansko sanduče se mogu sačuvati u u reviziju potfasciklu u fascikli spasen stavke.

Za Poštanske sandučiće koje se ne nalaze na čekanju, možete koristiti admini na `Search-Mailbox -SearchDumpsterOnly -DeleteContent` komandu u Exchange Online PowerShell da biste izbrisali stavke u fascikli spasen stavke. Za više informacija, pogledajte sljedeće teme:

- [Pretraživanje i brisanje poruka](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)

- [Pretraživanje-poštansko sanduče](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)

Za Poštanske sandučiće koje su na čekanju, admini morate da uklonite zadršku, pre nego što oni mogu izbrisanih stavki iz fascikle spasen stavke. Više informacija potražite u odeljku [Brisanje stavki u spasen stavki držite fasciklu od zasnovano na Poštanske sandučiće na](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).

Sprečavanja fasciklu spasen stavke postane puna, admini možete povećati ograničenje skladišta spasen stavki fascikle za Poštanske sandučiće na držite i podesite smernice za zadržavanje poštansko sanduče koje premešta stavke iz fascikle spasen stavke korisnikove arhivu poštansko sanduče. Vidim da [poveća spasen stavke kvote za Poštanske sandučiće na držite](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).
