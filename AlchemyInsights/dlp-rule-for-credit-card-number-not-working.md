---
title: I Uroniti pravilo za broj kreditne kartice ne radi
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: a56f32b54e6cb32fa044d26d08868bac8c368de5
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/24/2019
ms.locfileid: "29488111"
---
Imate li problema sa **Prevencije i gubitka podataka (Uroniti)** ne radi za sadržaj koji sadrži **Broj kreditne kartice** kada koristite Tip osetljive informacije i Uroniti u O365? Ako je tako, uverite se da vaš sadržaj sadrži potrebne informacije da izazovu u Dip politike kada se proceni. Na primer, za **kreditnu karticu politiku** konfigurisan sa na nivo pouzdanosti od 85%, na sledeći način se vrednuju i mora da bude otkriven pravilo će se aktivirati: 
  
- **[Format:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 brojeva, koja može da bude oblikovan ili neoblikovan (dddddddddddddddd) i mora proći Luhn test. 
    
- **[Obrazac:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Vrlo složen i robustan šare koje otkrije karte iz svih glavnih brendova širom sveta, uključujući Visa, Mastercard, Carda, JCB CARDS, American Express, poklon kartice i restoranu karte. 
    
- **[Kontrolni zbir:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Da, na Luhn kontrolni zbir 
    
- **[Definicija:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** I Uroniti politika je 85% sigurni da je to otkrio ovu vrstu poverljive informacije ako, blizu 300 znakova: 
    
  - Funkcija Func_credit_card pronalazi sadržaj koji odgovara obrazac.
    
  - Je jedan od sledećih: 
    
  - Nalazi se na ključnu reč iz Keyword_cc_verification.
    
  - Ključne reči iz Keyword_cc_name je našao.
    
  - Funkcija Func_expiration_date pronalazi datum u formatu datuma u pravu.
    
  - Kontrolni zbir prolazima
    
    Na primer, sledeći uzorak bi izazvalo Dip politici broj kreditne kartice:
    
  - Viza: 4485 3647 3952 7352 
    
  - Ističe: 2/2009
    
Za više informacija na ono što je neophodno za **Broj kreditne kartice** da ga otkriju za sadržaj, pogledajte sledeći odeljak u ovom članku: [Šta the osetljive tipova informacija potražite kreditnu karticu #](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)
  
Pomoću različitih ugrađenih poverljive informacije tip, pogledajte sledeći članak za informacije na ono što je neophodno za druge tipove: [Šta je osetljiva tipova informacija potražite](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  

