---
title: Kako onemogućiti spoljne grupe?
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "966"
- "6000006"
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: b2328ea85d3ff6ec722cc56d8a46395d8438f79c
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/15/2019
ms.locfileid: "36739507"
---
# <a name="how-to-disable-external-groups"></a>Kako onemogućiti spoljne grupe?

Na mreži Yammer spoljne poruke primenjuje Exchange transportne pravila (ETRs), skup proaktivne kontrole kako bi se sprečilo deljenje informacija o preduzeću. Da biste ograničili korisnike da kreiraju spoljne grupe, potrebno je da konfigurišete pravilo za prenos Exchange servera (ETR), a zatim da podesite Yammer da koristi Exchange prenos da biste blokirali spoljne poruke.
  
Nakon što ste kreirali pravilo u programu Exchange online admin Center, sledite ove korake da biste podesili ETR da se primeni na Yammer:
  
- Prijavite se na Yammer kao verifikovani administrator i u okviru **administratorskog centra za Yammer**, idite na C **sadržaj i bezbednosne \> postavke bezbednosti.**

- U okviru stavke **"spoljna razmena poruka**" izaberite stavku **Primeni pravila transporta Exchange servera (etrs) na mreži Yammer.**

- Kliknite na dugme **Sačuvaj**.

Više informacija potražite u članku [Onemogućavanje spoljnih poruka na mreži Yammer](https://docs.microsoft.com/yammer/work-with-external-users/disable-external-messaging).
  