---
title: 1336 fascikla za oporavak datoteke je puna
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1336"
- "3700003"
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: 4f0cba480fcc05114abd8f370b84e9a37e5f2804
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44510766"
---
# <a name="the-recoverable-items-folder-is-full"></a>Fascikla "spasti stavke" je puna

Za Poštanske sandučiće za Exchange online, podrazumevano ograničenje prostora za skladištenje za fasciklu "Spasne stavke" je 30 GB. Ograničenje prostora za skladištenje za fasciklu "spasti stavke" se automatski povećava na 100 GB ako je poštansko sanduče postavljeno na čekanje, eDiscovery zadrške ili je dodeljeno smernicama za zadržavanje.

Kada fascikla "spasti stavke" dostigne ograničenje skladištenja, funkcionalnost poštanskog sandučeta utiče na sledeće načine:

- Korisnik ne može da izbriše stavke iz poštanskog sandučeta.

- Pomoćnik kontrolisane fascikle ne može da izbriše stavke zasnovane na oznaci zadržavanja ili postavkama kontrolisane fascikle.

- Za Poštanske sandučiće koji imaju omogućenu podršku za jedan artikal ili su postavljeni na čekanju, proces zaštite stranice "Kopiraj na upisivanje" ne može da održava verzije stavki koje korisnik uređuje.

- Za Poštanske sandučiće koji imaju omogućenu evidenciju nadgledanja u poštanskom sandučetu, nijedna stavka evidencije nadgledanja poštanskog sandučeta ne može biti sačuvana u potfascikli za reviziju u fascikli "Spasničke stavke".

Za Poštanske sandučiće koji nisu na čekanju, administratori mogu `Search-Mailbox -SearchDumpsterOnly -DeleteContent` da koriste komandu u Exchange online PowerShell za brisanje stavki u fascikli "Spasne stavke". Za više informacija pogledajte sledeće teme:

- [Traženje i brisanje poruka](https://docs.microsoft.com/microsoft-365/compliance/search-for-and-delete-messagesadmin-help)

- [Pretraga-poštansko sanduče](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)

Za Poštanske sandučiće koji su na čekanju, administratori moraju da uklone zadrške da bi mogli da izbrišu stavke iz fascikle "spasti stavke". Više informacija potražite u članku [Brisanje stavki u fascikli "spasne stavke" Poštanske sandučiće na čekanju](https://docs.microsoft.com/microsoft-365/compliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).

Da bi sprečio da fascikla "spasti stavke" postane puna, administratori mogu da povećaju ograničenje prostora za skladištenje fascikli "spasdatoteke" za Poštanske sandučiće na čekanju i da postave smernice za zadržavanje poštanskog sandučeta koje premešta stavke iz fascikle "spasti stavke" u poštansko sanduče "arhiviranje". Pogledajte odeljak [Povećavanje kvote za stavke koje se spasavaju za Poštanske sandučiće na čekanju](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold).
