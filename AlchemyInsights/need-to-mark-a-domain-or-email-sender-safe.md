---
title: Potrebno je da označite domen ili pošiljaoca e-pošte bezbedno?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002921"
- "5673"
ms.openlocfilehash: 7dc1576fd61e87b319c7486c59ed125943b4d959
ms.sourcegitcommit: 43acdecef129bfffc8bbe8ebb08fdd581b238a03
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/18/2020
ms.locfileid: "44281185"
---
# <a name="need-to-mark-a-domain-or-email-sender-safe"></a>Potrebno je da označite domen ili pošiljaoca e-pošte bezbedno?

- Korišćenje **pouzdanih lista pošiljalaca se ne preporučuje** jer se u vašoj organizaciji otvara bezvredna pošta, Phish i lažno predstavljanje napada.
- Međutim, ako postoji poslovni uslov, **preporučujemo** da koristite pravila za **[tok pošte](https://docs.microsoft.com/microsoft-365/security/office-365-security/create-safe-sender-lists-in-office-365?view=o365-worldwide#recommended-use-mail-flow-rules)** . Naše smernice osigurava potvrdu identiteta pošiljaoca (verifikuje se da slanje domena nije lažno). **Napomena**: ne preporučujemo upravljanje lažnim imali greške pomoću liste pouzdanih pošiljalaca, zato što izuzeci od filtriranja bezvredne pošte mogu da otvore vašu organizaciju na bezbednosne napade. Ako vaši korisnici (e) primaju poruke koje su nepravilno označene kao bezvredne ili neželjene e-pošte, **[Prijavite poruke i datoteke korporaciji Microsoft](https://protection.office.com/reportsubmission)**.
- Pouzdani pošiljaoci u programu Outlook, dozvoljenih lista pošiljalaca ili dozvoljena lista domena u smernicama za borbu protiv bezvredne pošte **treba izbegavati** zato što pošiljaoci zaobilaze sve bezvredne pošte, spore i Phish zaštite i potvrdu identiteta pošiljaoca (SPF, dkim, dmark). Ovaj metod je najbolje koristiti samo za privremeno testiranje.
