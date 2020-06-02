---
title: DLP pravilo za nas/britanski pasoš broj ne radi
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1319"
- "3200001"
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: 3d3b7dc2d9510376bc9eef6ec69b87ad7c681b05
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507312"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a>Problemi sa DLP-US/VB Passport brojevima

**Važno**: Tokom ovih jedinstvenih vremena, preduzimamo sve korake da bismo se uverili da će usluge SharePoint Online i OneDrive ostati dostupne u najvećoj meri – više informacija potražite u članku [Privremena prilagođavanja funkcija u usluzi SharePoint Online](https://aka.ms/ODSPAdjustments).

**DLP problemi s američkim/VB pasošima**

Da li imate problema sa **sprečavanjem gubitka podataka (DLP)** ne radi za sadržaj koji sadrži **američki/britanski pasoš** kada se koristi tip informacija "Dlp" u O365? Ako je tako, uverite se da sadržaj sadrži potrebne informacije o onome što ova smernica za DLP traži kada se proceni.
  
Na primer, za pravilo **broja američko/britanske pasoške** podešene sa nivoom pouzdanosti od 75%, sledeći se procenjuje i mora se otkriti da bi pravilo moglo da se aktivira
  
- **[Format:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-77)** Devet cifara

- **[Šara:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-77)** Devet uzastopnih cifara

- **[Kontrolni zbir:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-76)** Ne, ne postoji kontrolni zbir

- **[Definicija:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#definition-77)** DLP politika je 75% uverena da je otkrivena ova vrsta osetljivih informacija ako u blizini od 300 karaktera:

  - Funkcija Func_usa_uk_passport pronalazi sadržaj koji se podudara sa obrascem.

  - Pronađena je ključna reč Keyword_passport.

    Na primer, sledeći uzorak će se aktivirati za politiku **broja američkih i britanskih pasoša** : američki pasoš broj 123456789

Za više informacija o tome šta je potrebno za detekcijom AMERIČKOG/VB pasoša za vaš sadržaj, pogledajte sledeći odeljak u ovom članku: [koji tipovi osetljivih informacija traže broj US/UK](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#us--uk-passport-number)
  
Pomoću različitog ugrađenog tipa informacija pogledajte sledeći članak za informacije o tome šta je potrebno za druge tipove: [koje tipove osetljivih informacija traži](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)
  