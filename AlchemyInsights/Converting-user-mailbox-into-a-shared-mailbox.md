---
title: Pretvaranje korisničko poštansko sanduče u Deljeno poštansko sanduče?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ROBOTS: NOINDEX, NOFOLLOW
description: ''
ms.openlocfilehash: 4da54121763fd33aa111f3bb3c26963cd271dc51
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29906746"
---
Samo pretvaranja korisničko poštansko sanduče za Deljeno poštansko sanduče ako korisnik nema licencu za Exchange. Nakon što se konvertuje u poštansko sanduče, to će nastaviti da se pojavi u listi aktivnih korisnika, zato što ta lista uključuje deljene poštanskih sandučića. Međutim, poštansko sanduče na konvertovani će takođe se pojaviti na listi Deljeno poštansko sanduče. 
  
Ako pokušate da konvertujete u konzoli Admin Exchange poštansko sanduče, a konverzije ne uspe, opozovite svoje keša pregledača i kolačiće i pokušajte ponovo. Ako to i dalje ne radi, pokušajte da konvertujete poštansko sanduče u Exchange Management Shell tako što ćete pokrenuti sljedeću naredbu:
  
```
Set-Mailbox -Type Shared
```

Više informacija za konverziju poštansko sanduče dostupno je u [pretvorite poštansko sanduče korisnika sa deljenom poštanskim sandučetom](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).
  
