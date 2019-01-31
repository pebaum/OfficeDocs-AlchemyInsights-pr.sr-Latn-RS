---
title: I Uroniti pravilo za SSN ne radi
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: ac265ee6-c946-476e-9bf0-0ea0e8adc98a
ms.openlocfilehash: 7242bf2b101b45fec0fe00ab33fa6db150004ee5
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/30/2019
ms.locfileid: "29657373"
---
Imate li problema sa **Prevencije i gubitka podataka (Uroniti)** ne radi za sadržaj koji sadrži i **Broj socijalnog osiguranja (SSN)** kada koristite Tip poverljive informacije u Office 365? Ako je tako, uverite se da vaš sadržaj sadrži potrebne informacije za šta je politika i Uroniti u potrazi. 
  
Na primer, za smernice za SSN konfigurisan sa na nivo pouzdanosti od 85%, na sledeći način se vrednuju i mora da bude otkriven pravilo će se aktivirati:
  
- **[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 brojeva, što može biti uzorak oblikovan ili neoblikovan 
    
- **[Obrazac:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Četiri funkcije potražite SSNs u četiri različite obrasce: 
    
  - Func_ssn pronalazi SSNs sa pre-2011 jako oblikovanje koje su oblikovane pomoću crtice ili razmake (ddd-dd-dddd OR ddd dd dddd)
    
  - Func_unformatted_ssn pronalazi SSNs sa pre-2011 jak oblikovanja koja su oblikovana kao devet uzastopnih cifre (ddddddddd)
    
  - Func_randomized_formatted_ssn pronalazi post-2011 SSNs koje su oblikovane pomoću crtice ili razmake (ddd-dd-dddd OR ddd dd dddd)
    
  - Func_randomized_unformatted_ssn pronalazi post-2011 SSNs koja su oblikovana kao devet uzastopnih cifre (ddddddddd)
    
- **[Kontrolni zbir:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** Nema ovde nema kontrolni zbir 
    
- **[Definicija:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** I Uroniti politika je 85% sigurni da je to otkrio ovu vrstu poverljive informacije ako, blizu 300 znakova: 
    
  - [Funkcija Func_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) pronalazi sadržaj koji odgovara obrazac. 
    
  - Nalazi se na ključnu reč iz [Keyword_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn) . Primeri ključne reči uključuje: *socijalnog osiguranja socijalno osiguranje #, Šoć Sec, SSN* . Na primer, sledeći uzorak bi izazvalo za Uroniti SSN smernice: **SSN: 489-36-8350**
    
Za više informacija na ono što je neophodno za SSNs da ga otkriju za sadržaj, pogledajte sledeći odeljak u ovom članku: [Šta je osetljiva tipova informacija potražite SSNs](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)
  
Pomoću različitih ugrađenih poverljive informacije tip, pogledajte sledeći članak za informacije na ono što je neophodno za druge tipove: [Šta je osetljiva tipova informacija potražite](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  

