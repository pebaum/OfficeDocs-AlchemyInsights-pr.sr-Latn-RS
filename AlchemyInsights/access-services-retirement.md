---
title: Pristup uslugama penzije
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "9000356"
- "2009"
ms.assetid: ''
ms.openlocfilehash: 8886d7a6fad49e942e17f6a2f3c98542f87aae0b
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36495765"
---
# <a name="access-services-retirement"></a>Pristup uslugama penzije

Kao što smo prvobitno najavio u MC97576, u martu 2017, i nastavio da komuniciraju u proteklih godinu dana usluge pristupa su mirovinu iz Office 365. Naredni u ovaj proces će biti uklanjanje Access Web baze podataka koje koriste SharePoint liste kao svoje osnovno skladište podataka.

**Kako to utiče na mene?**

Počev od juna 2019, zaustavit ćemo stvaranje nove Access baze podataka u SharePoint Online se i isključite servis i preostale aplikacije do aprila 2020.

**Što trebam napraviti da se pripremite za ova promena?**

Savetujemo vam da napravite plan tranzicije za vaše organizacije Access web baze podataka. Admini možete da koristite [SharePoint Access aplikacija za skener](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) da biste nabavili inventar Access aplikacija koje koriste lokacije.

Postoji nekoliko načina da biste migrirali podatke iz baze podataka programa Access web:

- Uvoz u lokalnoj bazi podataka programa Access (. ACCDB) ili u Excel datoteku.
- Takođe preporučujemo da istraživanje Microsoft PowerApps kao je alternativna platforma za kreiranje bez koda poslovnih rešenja za web i mobilne uređaje.