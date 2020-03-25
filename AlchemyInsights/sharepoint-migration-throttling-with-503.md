---
title: Ograničavanje SharePoint migracije sa 503 grešaka
ms.author: pebaum
author: pebaum
ms.date: 8/8/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000136"
- "2541"
ms.openlocfilehash: 7e12c74d33e3cee7c626ad899a4e7f2f0a409bca
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931672"
---
# <a name="sharepoint-migration-throttling-with-503-errors"></a>Ograničavanje SharePoint migracije sa 503 grešaka

**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini. Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje. U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.

U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici. Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena. Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.

**503 grešaka pri preseljenja na SharePoint online**

Izgleda da se migrirate na SharePoint Online i dobijate 503 grešaka. Pratite dolenavedene korake da bismo vam mogli pomoći u najkraćem mogućem roku. 

1. Izaberite stavku **Podrška za kontakt**, a zatim **novi zahtev za servis**.
2. Za naslov i opis, otkucajte " **ograničavanje SharePoint migracije" sa 503**.
3. Kada se karta prosledi, ažurirajte je sledećim informacijama:
    - Koliko je preostalo za migraciju (na primer, koliko TBs?).
    - Početni i krajnji datum migracije.
    - Opišite mesto na koje želite da migrirate sadržaj, kao što je SharePoint Server, box, Gdisk, deljeni resursi datoteka itd...
    - Procenite broj grešaka u regulisanja (na primer, x reguliranje po satu?) i kada se dogodi ograničavanje.
    - Koju alatku za migraciju koristite (na primer, SPMT ili ShareGate).


