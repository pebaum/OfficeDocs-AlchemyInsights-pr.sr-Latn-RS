---
title: Duplirani zapis uređaja u portalu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4386"
ms.openlocfilehash: 277afc59705e6040f0f9ae0c8cad965bd7d3ef65
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2020
ms.locfileid: "43790171"
---
# <a name="duplicate-device-record-in-the-portal"></a>Duplirani zapis uređaja u portalu

Možda ćete videti 2 zapisa za uređaj na portalu ako uređaj ne prijavi tačno prijavljivanje statusa za saradnju na sajt upravljača konfigurisanja. Da biste proverili status koordinatora uređaja, pregledajte **** kolonu za uređaj u alatki "Upravljač konfigurisanja" u okviru Konzola za upravljanje. Ako kolona nije vidljiva, možete da je dodate tako što ćete kliknuti desnim tasterom miša na bilo koje zaglavlja kolona i odabrati ga sa liste.

Zajednički kontrolisana vrednost mora da bude **Da**. Ako je vrednost **Ne**, otvorite aplet za Menadžer konfigurisanja klijenta na uređaju klijenta i potvrdite izbor u polju za potvrdu **Saradništvo** na kartici Opšte.

- Ako je vrednost **omogućena**, to ukazuje na probleme sa komunikacijom klijenta uz management Point. Pregledajte **CcmMessaging. log** na uređaju da biste istražili potencijalne probleme sa povezivanjem.

- Ako je vrednost **onemogućena**, a uređaj je upisan u Intune, uverite se da je uređaj primio smernice za saradnju tako što će pregledati **CoManagementHandler.log** na uređaju.
