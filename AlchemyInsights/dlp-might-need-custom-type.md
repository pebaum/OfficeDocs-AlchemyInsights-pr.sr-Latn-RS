---
title: DLP će možda trebati prilagođeni tip
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: ''
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1647"
- "3200001"
ms.assetid: ''
ms.openlocfilehash: 890bba57bc36c034c507e6124cd6593ef4d92af8
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932672"
---
# <a name="dlp-might-need-a-custom-type"></a>DLP će možda trebati prilagođeni tip

**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini. Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje. U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.

U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici. Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena. Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.

**DLP može zahtijevati prilagođeni tip informacija**

Pomoću smernica za sprečavanje gubitka podataka (DLP) možete da identifikujete i zaštitite osetljive podatke u vašoj organizaciji. U nekim slučajevima ćete možda morati da kreirate svoj **prilagođeni** tip poverljivih informacija da biste zaštitili podatke svoje organizacije.

Na primer, vaša organizacija će možda morati da identifikuje i zaštiti ID-ove zaposlenih ili druge podatke u nekom formatu koji je karakterističan za vaš org. Ako je tako, pogledajte sledeće članke za više informacija.
  
 **Prilagođavanje ugrađenog tipa poverljivih informacija**
  
Ako je u ugrađenom tipu sa poverljivim informacijama zadovoljeno vaše potrebe sa samo nekoliko tvitova, možete da [prilagodite ugrađeni tip osetljivih informacija](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type). Na primer, možete da dodate ili uklonite ključne reči ili da dodate ili uklonite prateće dokaze kao što su datum ili adresa.
  
 **Kreiranje prilagođenog osetljivog tipa informacija**
  
Međutim, ako je potrebno da potpuno identifikujete i zaštitite različite tipove osetljivih informacija, možete da [kreirate prilagođeni tip poverljivih informacija](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) u korisničkom interfejsu bezbednosnog & centra za usaglašavanje.
  
**Kreiranje prilagođenog tipa osetljivih informacija u bezbednosnom & PowerShell centra za usaglašavanje**

Na kraju, ako korisnički interfejs ne obezbedi sve opcije koje su vam potrebne, možete da [kreirate prilagođeni tip poverljivih informacija u bezbednosnom & PowerShell centra za usaglašavanje](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell). Ako započnete sa XML datotekom, možete da koristite svaku dostupnu opciju.
