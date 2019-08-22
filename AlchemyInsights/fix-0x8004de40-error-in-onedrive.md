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
ms.openlocfilehash: d436184bdc0e283db217ea734fb2c8e05f85b4e7
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36525073"
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