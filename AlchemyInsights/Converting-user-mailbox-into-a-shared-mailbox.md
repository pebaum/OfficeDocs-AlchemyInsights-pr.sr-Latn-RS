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
ms.openlocfilehash: ab34b8939b95b29bedb797f640dd744bc783adef
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36496449"
---
# <a name="convert-a-user-mail-box-into-a-shared-mailbox"></a>Okvir za poštu korisnika pretvori Deljeno poštansko sanduče

Samo pretvaranja korisničko poštansko sanduče za Deljeno poštansko sanduče ako korisnik nema licencu za Exchange. Nakon što se konvertuje u poštansko sanduče, to će nastaviti da se pojavi u listi aktivnih korisnika, zato što ta lista uključuje deljene poštanskih sandučića. Međutim, poštansko sanduče na konvertovani će takođe se pojaviti na listi Deljeno poštansko sanduče. 
  
Ako pokušate da konvertujete u konzoli Admin Exchange poštansko sanduče, a konverzije ne uspe, opozovite svoje keša pregledača i kolačiće i pokušajte ponovo. Ako to i dalje ne radi, pokušajte da konvertujete poštansko sanduče u Exchange Management Shell tako što ćete pokrenuti sljedeću naredbu:
  
```
Set-Mailbox -Type Shared
```

Više informacija za konverziju poštansko sanduče dostupno je u [pretvorite poštansko sanduče korisnika sa deljenom poštanskim sandučetom](https://docs.microsoft.com/office365/admin/email/convert-user-mailbox-to-shared-mailbox).
  
