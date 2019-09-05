---
title: Fix 0x8004de40 greška u usluzi OneDrive
ms.author: pebaum
author: Techwriter40
ms.date: 6/20/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: aa0e0a63ac1e365a7cdce018626740446040a664
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/04/2019
ms.locfileid: "36755862"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a>Fix 0x8004de40 greška u usluzi OneDrive

Ako dobijete grešku 0x8004de40 u usluzi OneDrive:

- Ponovo pokrenite računar na koji je bio povezan sa domenom u vašem Akitve.
- Ako ponovno pokretanje ne reši problem, raspakovanje i ponovno pridruživanje uređaju iz Azure oglasa. 

**Napomena**: trebalo bi da budete na korporativnoj mreži dok izvršavate ove korake. Nemojte da izvršavate ove korake kada ne možete da se povežete sa korporativnom infrastrukturom (na primer, tokom putovanja). 

- Otvaranje pune komandne linije. 
- Kliknite desnim tasterom miša na **komandnu liniju**, a **** zatim izaberite stavku **Pokreni kao administrator**da biste otvorili sve pune komandne linije.
- Otkucajte *dsregcmd/napuštanje* i pritisnite taster **ENTER**.
- Kada dovršite, otkucajte *dsregcmd/JOIN* i pritisnite taster **ENTER**.
- Kada dovršite, zatvorite komandnu liniju.
- Ponovo pokrenite računar i prijavite se u OneDrive.