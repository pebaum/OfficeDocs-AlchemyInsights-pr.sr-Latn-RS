---
title: Saveti za smernice za DLP ne rade
ms.author: deniseb
author: denisebmsft
manager: laurawims
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: c03d30be-474a-4a34-b3c0-240eb2a2c466
ms.custom:
- "1428"
- "3200001"
ms.openlocfilehash: 51b4472fa721443192eb542cac45965df67634df
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932600"
---
# <a name="dlp-policy-tip-issues"></a>Problemi sa savete za DLP smernice

**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini. Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje. U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.

U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici. Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena. Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.

**Savete za DLP smernice**

Kada koristite **Dlp smernice**, korisnici mogu biti obavešteni o kršenju pravila sa **savetima za smernice**. Administratori mogu da konfigurišu savete za smernice koji će se prikazivati prilikom testiranja njihovih DLP smernica ili kada je smernica u režimu potpunog sprovođenja.
  
Postupite na sledeći način da biste podesili savete za smernice u okviru "DLP" smernica u centru za bezbednost i usaglašenost u režimu potpunog sprovođenja.
  
- Uverite se da su saveti za smernice **omogućeni** u pravilu "dlp" koristeći korake koje [ovde](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)koristite.

- Uverite se da se **sadržaj podudara sa** onim što je **potrebno** za aktiviranje pravila iznetih u [ovom članku.](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)

- Saveti za smernice prikazuju se u OWI i Outlook. Međutim, ako koristite **Outlook 2013 ili noviji**, saveti za smernice su prikazani samo pod određenim uslovima. Ovi uslovi su ovde navedeni: [podržani uslovi za Outlook 2013 ili noviji za prikazivanje saveta o smernicama](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips#outlook-2013-and-later-supports-showing-policy-tips-for-only-some-conditions)

Za dodatne informacije o tasterskim savetima za DLP smernice pogledajte odeljak: [Prikazivanje saveta za smernice za DLP smernice](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)
  