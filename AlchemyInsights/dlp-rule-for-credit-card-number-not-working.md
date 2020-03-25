---
title: DLP pravilo za broj kreditne kartice ne radi
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1270"
- "3200001"
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: 6b28534d072c024a98a9b05f6cb55bfdc3435db6
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932457"
---
# <a name="dlp-issues-with-credit-card-numbers"></a>Problemi sa DLP-om sa brojevima kreditnih kartica

**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini. Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje. U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.

U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici. Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena. Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.

**Problemi sa DLP-om sa brojevima kreditnih kartica**

Da li imate problema sa **sprečavanjem gubitka podataka (DLP)** ne radi za sadržaj koji sadrži **broj kreditne kartice** kada koristite Tip informacija "Dlp" u O365? Ako je tako, uverite se da sadržaj sadrži potrebne informacije da bi se aktiviraju "DLP" smernice kada se ona proceni. Na primer, za **smernice za kreditne kartice** podešene sa nivoom pouzdanosti od 85%, sledeće se procenjuje i mora se otkriti da bi pravilo moglo da se aktivira:
  
- **[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 cifara koji može biti oblikovan ili neoblikovan (dddddddddddddd) i mora da prođe luhn test.

- **[Šara:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Veoma složena i robusna šara koja detektuje karte od svih vodećih brendova širom sveta, uključujući Visa, MasterCard, otkrij karticu, JCB, američki Express, poklon-kartice i karte za večeru.

- **[Kontrolni zbir:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Da, "luhn kontrolni zbir"

- **[Definicija:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** DLP politika je 85% uverena da je otkrivena ova vrsta osetljivih informacija ako u blizini od 300 karaktera:

  - Funkcija Func_credit_card pronalazi sadržaj koji se podudara sa obrascem.

  - Nešto od sledećeg je tačno:

  - Pronađena je ključna reč Keyword_cc_verification.

  - Pronađena je ključna reč Keyword_cc_name

  - Funkcija Func_expiration_date pronalazi datum u formatu "pravi datum".

  - Kontrolni zbir prolazi

    Na primer, sledeći uzorak bi bio okidač za smernicu za brojeve sa DLP kreditnom karticom:

  - Visa: 4485 3647 3952 7352
  
  - Datum isteka: 2/2009

Više informacija o tome šta je potrebno da se otkrije **broj kreditne kartice** za sadržaj potražite u sledećem odeljku ovog članka: [koji tipovi osetljivih informacija traže kreditnu karticu #](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)
  
Pomoću različitog ugrađenog tipa informacija pogledajte sledeći članak za informacije o tome šta je potrebno za druge tipove: [koje tipove osetljivih informacija traži](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  