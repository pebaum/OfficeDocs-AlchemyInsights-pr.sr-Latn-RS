---
title: DLP pravilo za SSN ne radi
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1242"
- "3200001"
ms.assetid: ac265ee6-c946-476e-9bf0-0ea0e8adc98a
ms.openlocfilehash: 5af843c2b70b5b2e1aaf82c9f01356546929d840
ms.sourcegitcommit: 6a3748f5c05693ca0c19a829287cb8f30635940c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43788716"
---
# <a name="dlp-issues-with-social-security-numbers"></a>DLP problemi sa brojevima socijalnog osiguranja

**Važno**: Tokom ovih jedinstvenih vremena, preduzimamo korake da bismo se uverili da će usluge SharePoint Online i OneDrive ostati dostupne u velikoj meri – Posetite [SharePoint Online privremena prilagođavanja funkcija](https://aka.ms/ODSPAdjustments) za više informacija.

**DLP problemi sa SSNs**

Da li imate problema sa **sprečavanjem gubitka podataka (DLP)** ne radi za sadržaj koji sadrži **broj socijalnog osiguranja (SSN)** kada koristite Tip poverljivih informacija u programu Microsoft 365? Ako je tako, uverite se da sadržaj sadrži potrebne informacije za ono što traži DLP smernice. 
  
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
  