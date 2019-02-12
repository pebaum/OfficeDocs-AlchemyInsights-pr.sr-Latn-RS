---
title: I Uroniti pravilo za U.S. / broj pasoša UK ne radi
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: bb80ef07364a575f6032bb105cff83cd8f95bd63
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29912123"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a>Problemi sa Dip - U.S. / UK brojeve pasoša

Imate li problema sa **Prevencije i gubitka podataka (Uroniti)** ne radi za sadržaja koji sadrži i **U.S. / broj pasoša UK** kada koristite Tip osetljive informacije i Uroniti u O365? Ako je tako, postarajte se da sadržaj sadrži potrebne informacije za šta je politika i Uroniti je u potrazi za kada se proceni. 
  
Na primer, za za **U.S. / broj pasoša UK** politiku konfigurisan sa na nivo pouzdanosti od 75%, na sledeći način se vrednuju i mora da bude otkriven pravilo će se aktivirati 
  
- **[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Devet cifara 
    
- **[Obrazac:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Devet uzastopnih cifara 
    
- **[Kontrolni zbir:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Nema ovde nema kontrolni zbir 
    
- **[Definicija:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** I Uroniti politika je 75% sigurni da je to otkrio ovu vrstu poverljive informacije ako, blizu 300 znakova: 
    
  - Funkcija Func_usa_uk_passport pronalazi sadržaj koji odgovara obrazac.
    
  - Nalazi se na ključnu reč iz Keyword_passport.
    
    Na primer, sledeći uzorak bi izazvalo za u **U.S. / broj pasoša UK** politiku: američki pasoš broj 123456789 
    
Za više informacija o tome šta je potrebno za savezni / broj pasoša UK bila otkrivena za sadržaj, pogledajte sledeći odeljak u ovom članku: [Vidi šta je osetljiva tipova informacija za U.S. / broj pasoša UK](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)
  
Pomoću različitih ugrađenih poverljive informacije tip, pogledajte sledeći članak za informacije na ono što je neophodno za druge tipove: [Šta je osetljiva tipova informacija potražite](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  

