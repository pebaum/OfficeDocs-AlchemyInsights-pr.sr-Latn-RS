---
title: DLP pravilo za SSN ne radi
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1242"
- "3200001"
ms.assetid: ac265ee6-c946-476e-9bf0-0ea0e8adc98a
ms.openlocfilehash: 0b83a858975ffe1bb70f16a7452a13d57dff5340
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932549"
---
# <a name="dlp-issues-with-social-security-numbers"></a>DLP problemi sa brojevima socijalnog osiguranja

**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini. Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje. U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.

U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici. Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena. Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.

**DLP problemi sa SSNs**

Da li imate problema sa **sprečavanjem gubitka podataka (DLP)** ne radi za sadržaj koji sadrži **broj socijalnog osiguranja (SSN)** kada koristite Tip poverljivih informacija u sistemu Office 365? Ako je tako, uverite se da sadržaj sadrži potrebne informacije za ono što traži DLP smernice. 
  
Na primer, za SSN smernice koje su konfigurisane sa nivoom pouzdanosti od 85%, sledeće se procenjuje i mora se otkriti da bi pravilo moglo da se aktivira:
  
- **[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 cifara, koji je možda u oblikovanoj ili neformatiranom obrascu

- **[Šara:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Četiri funkcije traže od SSNs u četiri različita modela:

  - Func_ssn pronalazi SSNs sa unapred 2011 snažnim oblikovanjem koje su oblikovane crtica ili razmacima (DDD-dd-dddd ili DDD dd dddd)

  - Func_unformatted_ssn pronalazi SSNs sa unapred 2011 jakom oblikovanjem koja nije formatirana kao devet uzastopnih cifara (ddddddddd)

  - Func_randomized_formatted_ssn pronalazi post-2011 SSNs koji su oblikovani crtica ili razmacima (DDD-dd-dddd ili DDD dd dddd)

  - Func_randomized_unformatted_ssn pronalazi post-2011 SSNs koji nisu oblikovani kao devet uzastopnih cifara (ddddddddd)

- **[Kontrolni zbir:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** Ne, ne postoji kontrolni zbir

- **[Definicija:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** DLP politika je 85% uverena da je otkrivena ova vrsta osetljivih informacija ako u blizini od 300 karaktera:

  - [Funkcija Func_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) pronalazi sadržaj koji se podudara sa obrascem.

  - Pronađena je ključna reč [Keyword_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn) . Primeri ključnih reči su: *socijalno osiguranje, socijalno osiguranje #, SPC sec, SSN* . Na primer, sledeći uzorak bi bio okidač za DLP SSN smernicu: **SSN: 489-36-8350**
  
Više informacija o tome šta je potrebno da bi se SNS detektuje za sadržaj potražite u sledećem odeljku ovog članka: [Šta osetljivi tipovi informacija traže od SNS](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)
  
Pomoću različitog ugrađenog tipa informacija pogledajte sledeći članak za informacije o tome šta je potrebno za druge tipove: [koje tipove osetljivih informacija traži](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  