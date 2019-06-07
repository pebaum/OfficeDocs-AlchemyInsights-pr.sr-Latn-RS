---
title: Identifikujte eksterni mail špedicije na Poštanske sandučiće u evidencije nadgledanja
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1369
ms.assetid: ''
ms.openlocfilehash: 518e4dd485ee7c54ce83e65794152e32f4c3a836
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34752033"
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
