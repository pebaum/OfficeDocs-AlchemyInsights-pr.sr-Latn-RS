---
title: SharePoint online reguliranje
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.openlocfilehash: 9af4f09d50992c04a1f3d5a164093049a3ec3517
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931456"
---
# <a name="sharepoint-online-throttling"></a>SharePoint online reguliranje

**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini. Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje. U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.

U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici. Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena. Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.

**SharePoint online reguliranje**

SharePoint online koristi ograničavanje za održavanje optimalnih performansi i pouzdanosti SharePoint usluge na mreži. Ograničavanje ograničava broj radnji korisnika ili uporedne pozive (po skripti ili kodu) da bi sprečio prekomerno korišćenje resursa. Za više informacija, molimo vas da posetite dole navedene veze.

- [Izbegavanje preuzimanja ili blokiranja na SharePoint mreži](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online)

- [Migracija podataka i SPO-gas](https://blogs.technet.microsoft.com/sposupport/2017/08/12/data-migration-and-spo-service-throttling/)

- [Brzina migracije SharePoint Online i OneDrive](https://docs.microsoft.com/sharepointmigration/sharepoint-online-and-onedrive-migration-speed)

 - [Rukovanje SharePoint online reguliranje pomoću eksponencijalnog isključivanja](https://docs.microsoft.com/sharepoint/dev/solution-guidance/handle-sharepoint-online-throttling-by-using-exponential-back-off)

- [Planiranje kapaciteta i učitavanje testiranja na SharePoint mreži](https://docs.microsoft.com/office365/enterprise/capacity-planning-and-load-testing-sharepoint-online)

