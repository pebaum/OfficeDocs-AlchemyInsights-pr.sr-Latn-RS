---
title: DLP pravilo za nas/britanski pasoš broj ne radi
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1319"
- "3200001"
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: c63e814059c897531109aa78725e9811b311fb27
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931276"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a>Problemi sa DLP-US/VB Passport brojevima

**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini. Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje. U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.

U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici. Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena. Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.

**DLP problemi s američkim/VB pasošima**

Da li imate problema sa **sprečavanjem gubitka podataka (DLP)** ne radi za sadržaj koji sadrži **američki/britanski pasoš** kada se koristi tip informacija "Dlp" u O365? Ako je tako, uverite se da sadržaj sadrži potrebne informacije o onome što ova smernica za DLP traži kada se proceni.
  
Na primer, za pravilo **broja američko/britanske pasoške** podešene sa nivoom pouzdanosti od 75%, sledeći se procenjuje i mora se otkriti da bi pravilo moglo da se aktivira
  
- **[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Devet cifara

- **[Šara:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Devet uzastopnih cifara

- **[Kontrolni zbir:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Ne, ne postoji kontrolni zbir

- **[Definicija:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** DLP politika je 75% uverena da je otkrivena ova vrsta osetljivih informacija ako u blizini od 300 karaktera:

  - Funkcija Func_usa_uk_passport pronalazi sadržaj koji se podudara sa obrascem.

  - Pronađena je ključna reč Keyword_passport.

    Na primer, sledeći uzorak će se aktivirati za politiku **broja američkih i britanskih pasoša** : američki pasoš broj 123456789

Za više informacija o tome šta je potrebno za detekcijom AMERIČKOG/VB pasoša za vaš sadržaj, pogledajte sledeći odeljak u ovom članku: [koji tipovi osetljivih informacija traže broj US/UK](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)
  
Pomoću različitog ugrađenog tipa informacija pogledajte sledeći članak za informacije o tome šta je potrebno za druge tipove: [koje tipove osetljivih informacija traži](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  