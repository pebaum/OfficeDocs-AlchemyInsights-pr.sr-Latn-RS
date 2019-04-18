---
title: Identifikujte eksterni mail špedicije na Poštanske sandučiće u evidencije nadgledanja
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1369
ms.assetid: ''
ms.openlocfilehash: 7fb2c161c558a7eb961f86ca2b86e33750d902fd
ms.sourcegitcommit: ffe2f489b1ac3aae62aa784c959da6a41c3261eb
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/17/2019
ms.locfileid: "31909525"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a>Određivanje kada eksterni mail špedicije je podešen na Poštanske sandučiće

Kada korisnik podešava eksterni mail špedicije na poštansko sanduče, aktivnost je revizije u sklopu cmdlet na **Setu-poštansko sanduče** . Možete da vidite aktivnosti koristeći pretraživanje evidencija nadgledanja u bezbednosti & usklađenosti centar.

1. Prijavite se za [Office 365 bezbednosni & usklađenosti centar](https://protection.office.com/)

2. Izaberite **pretragu i istrage** i **Pretraživanje evidencije nadgledanja**.

3. Izaberite opseg datuma u poljima **datum početka** i **datum završetka** . Ne morate navesti korisničko ime. Provjerite **aktivnosti** polje postavljeno na **Prikaz rezultata za sve aktivnosti**.

4. Kliknite na dugme **za pretragu**.

Na listi rezultata kliknite **Rezultati filtriranja** i upišite **Setu-poštansko sanduče** u okviru aktivnosti filtera. Izaberite zapis o reviziji u rezultatima. U Potpaleta u **detalje** , kliknite na " **više informacija**". Morate da vidi detalje o svakom zapisu nadgledanja utvrditi ako se odnosi aktivnost u e-mail na špedicije.

- **ObjectId**: pseudonim vrednost poštanskog sandučeta izmene.

- **Parametri**: _ForwardingSmtpAddress_ ukazuje na adresu e-pošte meta.

- **ID korisnika**: korisnika koji je podešen email špedicije na poštansko sanduče u polju **ObjectId** .

Za više informacija, pogledajte [Determining ko podešavanje email Špedicija za poštansko sanduče](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).
