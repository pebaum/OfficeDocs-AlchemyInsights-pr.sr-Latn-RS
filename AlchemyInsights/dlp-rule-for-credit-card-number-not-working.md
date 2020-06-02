---
title: DLP pravilo za broj kreditne kartice ne radi
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1270"
- "3200001"
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: e2e93bed44749b9017dc6ff919a151d46da7a3fc
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507420"
---
# <a name="dlp-issues-with-credit-card-numbers"></a>Problemi sa DLP-om sa brojevima kreditnih kartica

**Važno**: Tokom ovih jedinstvenih vremena, preduzimamo sve korake da bismo se uverili da će usluge SharePoint Online i OneDrive ostati dostupne u najvećoj meri – više informacija potražite u članku [Privremena prilagođavanja funkcija u usluzi SharePoint Online](https://aka.ms/ODSPAdjustments).

**Problemi sa DLP-om sa brojevima kreditnih kartica**

Da li imate problema sa **sprečavanjem gubitka podataka (DLP)** ne radi za sadržaj koji sadrži **broj kreditne kartice** kada koristite Tip informacija "Dlp" u O365? Ako je tako, uverite se da sadržaj sadrži potrebne informacije da bi se aktiviraju "DLP" smernice kada se ona proceni. Na primer, za **smernice za kreditne kartice** podešene sa nivoom pouzdanosti od 85%, sledeće se procenjuje i mora se otkriti da bi pravilo moglo da se aktivira:
  
- **[Format:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-19)** 16 cifara koji može biti oblikovan ili neoblikovan (dddddddddddddd) i mora da prođe luhn test.

- **[Šara:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-19)** Veoma složena i robusna šara koja detektuje karte od svih vodećih brendova širom sveta, uključujući Visa, MasterCard, otkrij karticu, JCB, američki Express, poklon-kartice i karte za večeru.

- **[Kontrolni zbir:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-19)** Da, "luhn kontrolni zbir"

- **[Definicija:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#definition-19)** DLP politika je 85% uverena da je otkrivena ova vrsta osetljivih informacija ako u blizini od 300 karaktera:

  - Funkcija Func_credit_card pronalazi sadržaj koji se podudara sa obrascem.

  - Nešto od sledećeg je tačno:

  - Pronađena je ključna reč Keyword_cc_verification.

  - Pronađena je ključna reč Keyword_cc_name

  - Funkcija Func_expiration_date pronalazi datum u formatu "pravi datum".

  - Kontrolni zbir prolazi

    Na primer, sledeći uzorak bi bio okidač za smernicu za brojeve sa DLP kreditnom karticom:

  - Visa: 4485 3647 3952 7352
  
  - Datum isteka: 2/2009

Više informacija o tome šta je potrebno da se otkrije **broj kreditne kartice** za sadržaj potražite u sledećem odeljku ovog članka: [koji tipovi osetljivih informacija traže kreditnu karticu #](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#credit-card-number)
  
Pomoću različitog ugrađenog tipa informacija pogledajte sledeći članak za informacije o tome šta je potrebno za druge tipove: [koje tipove osetljivih informacija traži](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)
  