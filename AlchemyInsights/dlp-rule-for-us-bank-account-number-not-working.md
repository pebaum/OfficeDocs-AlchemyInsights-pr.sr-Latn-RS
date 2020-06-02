---
title: DLP pravilo za nas broj računa u banci ne radi
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1287"
- "3200001"
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: b032a7c80e8b387114aeda95c4f6af7e57225517
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507348"
---
# <a name="dlp-issues-with-us-bank-account-numbers"></a>DLP problemi sa brojevima računa u banci

**Važno**: Tokom ovih jedinstvenih vremena, preduzimamo sve korake da bismo se uverili da će usluge SharePoint Online i OneDrive ostati dostupne u najvećoj meri – više informacija potražite u članku [Privremena prilagođavanja funkcija u usluzi SharePoint Online](https://aka.ms/ODSPAdjustments).

**DLP problemi sa brojevima računa u banci**

Da li imate problema sa **sprečavanjem gubitka podataka (DLP)** ne radi za sadržaj koji sadrži **američki broj računa u banci** kada koristite Tip informacija sa Dlp osetljivim na O365? Ako je tako, uverite se da sadržaj sadrži potrebne informacije o onome što ova smernica za DLP traži kada se proceni.
  
Na primer, za smernice za **broj računa u banci** podešene sa nivoom pouzdanosti od 85%, sledeće se procenjuje i mora se otkriti da bi pravilo moglo da se aktivira:
  
- **[Format:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-77)** 8-17 cifara

- **[Šara:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-77)** 8-17 uzastopnih cifara.

- **[Kontrolni zbir:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-76)** Ne, ne postoji kontrolni zbir

- **[Definicija:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)** DLP politika je 75% uverena da je otkrivena ova vrsta osetljivih informacija ako u blizini od 300 karaktera:

  - Običan izraz Regex_usa_bank_account_number pronalazi sadržaj koji odgovara obrascu

  - Pronađena je ključna reč Keyword_usa_Bank_Account.

    Na primer, sledeći uzorak bi bio okidač za politiku **broja računa u banci** : provera naloga 78344011

Za više informacija o tome šta je potrebno za pronalaženje **broja računa u banci** koji će biti otkriven za vaš sadržaj pogledajte sledeći odeljak u ovom članku: [Šta osetljivi tipovi informacija traže broj računa u banci](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#us-bank-account-number)
  
Pomoću različitog ugrađenog tipa informacija pogledajte sledeći članak za informacije o tome šta je potrebno za druge tipove: [koje tipove osetljivih informacija traži](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)
  