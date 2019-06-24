---
title: Popravljanje greške 0x8004de40 u OneDrive
ms.author: kirks
author: Techwriter40
ms.date: 6/20/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 2256fb66cb7a4e2adcff9fda16a80c87e2997f0c
ms.sourcegitcommit: 8f6a1be929b275faa295ba8aeeae17898a47c3b0
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/21/2019
ms.locfileid: "35133990"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a>Popravljanje greške 0x8004de40 u OneDrive

Ako dobijete grešku "0x8004de40" sa OneDrive:

- Ponovo pokrenite problematično računalo dok ste povezani sa simpozijima Directory domena.
- Ako ponovno pokretanje sistema ne reši problem, odvajanja i da se vratite u vaš uređaj sa azurno reklame. 

**Napomena**: treba da si na korporativnoj mreži tokom izvršavanja ovih koraka. Nemoj da izvršite ove korake kada ne možete da se povežete sa svoje korporativne infrastrukture (na primer, dok putujete). 

- Otvorite komandnoj liniji. 
- Da biste otvorili u komandnoj liniji, kliknite na dugme - **Start**, desnom tipkom miša kliknite **naredbeni redak**i zatim kliknite na dugme **Pokreni kao administrator**.
- Upišite *dsregcmd /leave* i pritisnite **Enter**.
- Kada bude završena, upišite *dsregcmd /join* i pritisnite **Enter**.
- Kada bude završena, zatvorite naredbeni redak.
- Ponovo pokrenite računalo i prijavite se na OneDrive.