---
title: Pokretanje Windows dijagnostike memorije u operativnom sistemu Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002959"
- "5661"
ms.openlocfilehash: 3fedc52d02f1f70743429d0313eda0361306c3f3
ms.sourcegitcommit: 18b080c2a5d741af01ec589158effc35ea7cf449
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/19/2020
ms.locfileid: "44357783"
---
# <a name="run-windows-memory-diagnostics-in-windows-10"></a>Pokretanje Windows dijagnostike memorije u operativnom sistemu Windows 10

Ako se prozori i aplikacije na RAČUNARU pojave, zamrzavaju ili deluju na nestabilan način, možda imate problem sa memorijom računara (RAM). Windows dijagnostika memorije možete pokrenuti da biste proverili da li ima problema sa RAM-om računara.

U polju za pretragu na traci zadataka otkucajte **dijagnostiku memorije**, a zatim izaberite **Windows dijagnostika memorije**. 

Da biste pokrenuli dijagnostiku, potrebno je ponovo pokrenuti računar. Imate opciju da odmah ponovo pokrenete računar (Sačuvajte svoj rad i zatvorite otvorene dokumente i e-poruke) ili planirajte da se dijagnostika automatski pokreće sledeći put kada se računar ponovo pokrene:

![Windows dijagnostika memorije](media/windows-memory-diagnostic.png)

Kada se računar ponovo pokrene, **Windows alatka za dijagnostiku memorije** će se automatski pokrenuti. Status i napredak će biti prikazani u toku dijagnostike, a vi imate opciju otkazivanja dijagnostike tako što ćete na tastaturi udarati taster **Esc** .

Kada se dijagnostika dovrši, Windows će se normalno pokrenuti.
Odmah nakon ponovnog pokretanja, kada se pojavi radna površina, pojaviće se obaveštenje (pored ikone **centra aktivnosti** na traci zadataka) da biste označili da li su pronađene greške u memoriji. Na primer:

Evo ikone Centra aktivnosti: ![Ikona centra aktivnosti](media/action-center-icon.png) 

I uzorak obaveštenja: ![Nema grešaka u memoriji](media/no-memory-errors.png)

Ako ste propustili obaveštenje, možete da izaberete ikonu **centra aktivnosti** na traci zadataka da biste prikazali **Centar aktivnosti** i videli listu obaveštenja koja se može pomerati.

Da biste pregledali detaljne informacije, otkucajte **događaj** u polje za pretragu na traci zadataka, a zatim izaberite stavku " **Prikazivač događaja**". U oknu sa leve strane **prikazivača događaja**Krećite se do **Windows evidencije > sistem**. U oknu sa desne strane Skenirajte listu dok pregledate **izvornu** kolonu, dok ne vidite događaje sa izvornom vrednošću **memorisdijagnostike-rezultati**. Ističete svaki takav događaj i vidite informacije o rezultatu u okviru ispod kartice " **Opšte postavke** " ispod liste.
