---
title: Pristup uslugama penzije
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: f5a1e88e4443fdf43cdd4f07cf9e784810df7540
ms.sourcegitcommit: 136b8209c52c2a05d0f2fdaab93b2cd92253fa2c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34769468"
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