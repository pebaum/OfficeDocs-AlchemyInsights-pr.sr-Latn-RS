---
title: SharePoint online reguliranje
ms.author: pebaum
author: pebaum
ms.date: 9/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.custom:
- "9000149"
- "1662"
- "3491"
ms.openlocfilehash: 59104ef96c95de4e4bc7744825245bdafba97d7c
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931240"
---
# <a name="sharepoint-online-throttling"></a>SharePoint online reguliranje

**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini. Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje. U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.

U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici. Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena. Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.

**503 server je zauzet greška**

Korisnici mogu da prime 503 server je zauzet greškom prilikom pokušaja da se kreću na SharePoint ili OneDrive lokacije. 

Ova greška može biti izazvana regulisanja u okviru SharePoint usluge. SharePoint online koristi ograničavanje za održavanje optimalnih performansi i pouzdanosti SharePoint usluge na mreži. Ograničavanje ograničava broj radnji korisnika ili uporedne pozive (po skripti ili kodu) da bi sprečio prekomerno korišćenje resursa. 

Za više informacija o regulisanja pogledajte, [izbegavajte ograničavanje ili blokiranje na lokaciji SharePoint online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).

Ako smatrate da ova greška nije u vezi sa regulisanja, možete da proverite da li je na vašem računaru došlo do aktivnog održavanja ako se krećete do [centra za poruke](https://portal.office.com/adminportal/home#/MessageCenter).

 Na kraju, uverite se da ste posetili stranicu " [zdravstvo usluge](https://portal.office.com/adminportal/home#/servicehealth) " da biste proverili da li postoje neki savetnici/incidenti koji se mogu naići.

