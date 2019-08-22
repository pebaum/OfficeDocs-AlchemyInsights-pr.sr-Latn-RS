---
title: I Uroniti pravilo za nas broj računa u banci ne radi
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1287"
- "3200001"
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: 0a32708b5ac8d95ec6777ada2d151a15f90d65bf
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36529895"
---
# <a name="dlp-issues-with-us-bank-account-numbers"></a>I Uroniti pitanja sa nama brojeve računa u banci

Imate li problema sa **Prevencije i gubitka podataka (Uroniti)** ne radi za sadržaj koji sadrži **Broj računa u banci AMERIČKI** kada koristite Tip osetljive informacije i Uroniti u O365? Ako je tako, postarajte se da sadržaj sadrži potrebne informacije za šta je politika i Uroniti je u potrazi za kada se proceni.
  
Na primer, za **Broj računa u banci AMERIČKI** politiku konfigurisan sa na nivo pouzdanosti od 85%, na sledeći način se vrednuju i mora da bude otkriven pravilo će se aktivirati:
  
- **[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 cifre

- **[Obrazac:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 uzastopnih cifre.

- **[Kontrolni zbir:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Nema ovde nema kontrolni zbir

- **[Definicija:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** I Uroniti politika je 75% sigurni da je to otkrio ovu vrstu poverljive informacije ako, blizu 300 znakova:

  - Regularni izraz Regex_usa_bank_account_number pronalazi sadržaj koji odgovara uzorak

  - Nalazi se na ključnu reč iz Keyword_usa_Bank_Account.

    Na primer, sledeći uzorak bi izazvalo polise **AMERIČKI broj računa u banci** : tekući račun 78344011

Za više informacija na ono što je neophodno za **AMERIČKI broj računa u banci** da ga otkriju za sadržaj, pogledajte sledeći odeljak u ovom članku: [Šta the osetljive tipova informacija potražite AMERIČKI broj računa u banci](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)
  
Pomoću različitih ugrađenih poverljive informacije tip, pogledajte sledeći članak za informacije na ono što je neophodno za druge tipove: [Šta je osetljiva tipova informacija potražite](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  