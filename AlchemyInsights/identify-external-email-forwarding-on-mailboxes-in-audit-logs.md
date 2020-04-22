---
title: Identifikovanje spoljnog prosleđivanja e-pošte na poštanskim sandučićima u evidencijama nadgledanja
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1369"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 156fd0044cdc42230ace0a5db16f49af572bb6fa
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716474"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a>Prepoznavanje kada je spoljna Prosleđivanje e-pošte konfigurisana u poštanskim sandučićima

Kada Microsoft 365 korisnik konfiguriše spoljnu Prosleđivanje e-pošte u poštanskom sandučetu, aktivnost se nadgleda kao deo " **Set-poštansko sanduče** " cmd. Aktivnost možete da vidite koristeći pretragu za evidenciju nadzora u centru za bezbednost &.

1. Prijavite se na [Microsoft 365 Security & centar za usaglašavanje](https://protection.office.com/).

2. Idite na stranicu za**pretraživanje evidencije nadgledanja** **pretraživanja** > .

3. Izaberite opseg datuma u poljima **Početni datum** i **Krajnji datum** . Nije potrebno da navedete korisničko ime. Proverite da li je polje **aktivnosti** podešeno da **prikazuje rezultate za sve aktivnosti**.

4. Kliknite na dugme **Pretraži**.

U rezultatima, u okviru za filter aktivnosti kliknite na dugme **Filtriraj rezultate** i otkucajte **Set-poštansko sanduče** . Izaberite zapis nadgledanja u rezultatima. Kliknite na dugme " **više informacija**" u prozoru " **Detalji** ". Morate da pogledate detalje svakog zapisa nadgledanja da biste utvrdili da li je aktivnost povezana sa prosleđivanjem e-pošte.

- **ID objekta**: vrednost pseudonima koja je izmenjena.

- **Parametri**: da bi se na njemu naznačila ciljna e _-Adresa._

- **ID korisnika**: korisnik koji je podesio Prosleđivanje e-pošte na poštansko sanduče u polju **ID objekta** .

Više informacija potražite u članku [Utvrđivanje ko je podesio Prosleđivanje e-pošte za poštansko sanduče](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).
