---
title: DLP pravilo za nas broj računa u banci ne radi
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
ms.openlocfilehash: 0b5c1fb175275028c56e47080708520fe115fb38
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932564"
---
# <a name="dlp-issues-with-us-bank-account-numbers"></a>DLP problemi sa brojevima računa u banci

**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini. Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje. U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.

U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici. Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena. Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.

**DLP problemi sa brojevima računa u banci**

Da li imate problema sa **sprečavanjem gubitka podataka (DLP)** ne radi za sadržaj koji sadrži **američki broj računa u banci** kada koristite Tip informacija sa Dlp osetljivim na O365? Ako je tako, uverite se da sadržaj sadrži potrebne informacije o onome što ova smernica za DLP traži kada se proceni.
  
Na primer, za smernice za **broj računa u banci** podešene sa nivoom pouzdanosti od 85%, sledeće se procenjuje i mora se otkriti da bi pravilo moglo da se aktivira:
  
- **[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 cifara

- **[Šara:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 uzastopnih cifara.

- **[Kontrolni zbir:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Ne, ne postoji kontrolni zbir

- **[Definicija:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** DLP politika je 75% uverena da je otkrivena ova vrsta osetljivih informacija ako u blizini od 300 karaktera:

  - Običan izraz Regex_usa_bank_account_number pronalazi sadržaj koji odgovara obrascu

  - Pronađena je ključna reč Keyword_usa_Bank_Account.

    Na primer, sledeći uzorak bi bio okidač za politiku **broja računa u banci** : provera naloga 78344011

Za više informacija o tome šta je potrebno za pronalaženje **broja računa u banci** koji će biti otkriven za vaš sadržaj pogledajte sledeći odeljak u ovom članku: [Šta osetljivi tipovi informacija traže broj računa u banci](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)
  
Pomoću različitog ugrađenog tipa informacija pogledajte sledeći članak za informacije o tome šta je potrebno za druge tipove: [koje tipove osetljivih informacija traži](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  