---
title: Penzione usluge pristupa
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "9000356"
- "2009"
ms.assetid: ''
ms.openlocfilehash: cb8123583b68e945ef878fdbaf211fd1d8205bb3
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40050503"
---
# <a name="access-services-retirement"></a>Penzione usluge pristupa

Kao što smo prvobitno objavili u MC97576, u martu 2017, i nastavila da komuniciramo u proteklih godinu dana Access servisi se penzioniraju iz Officea 365. Sledeća faza u ovom procesu će biti uklanjanje Access Web baza podataka koje koriste SharePoint liste kao svoje osnovno skladište podataka.

**Kako to utiče na mene?**

Počevši od juna 2019, Zaustavićemo kreiranje novih Access baza podataka u sistemu SharePoint Online i isključiti uslugu i sve preostale aplikacije do aprila 2020.

**Šta mi je potrebno da bih se pripremio za ovu promenu?**

Savetujemo vam da kreirate plan tranzicije za Web baze podataka u vašoj organizaciji. Administratori mogu da koriste [skener aplikacija za SharePoint Access](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) da bi nabavili popis Access aplikacija koje lokacije koriste.

Postoji nekoliko načina za migraciju podataka iz Access Web baza podataka:

- Uvozi u lokalnu Access bazu podataka (. ACCDB) ili u Excel datoteku.
- Takođe preporučujemo da istražujete Microsoft PowerApps kao alternativnu platformu da biste kreirali poslovnu rešenja za Web i mobilne uređaje.