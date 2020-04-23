---
title: Fix 0x8004de40 greška u usluzi OneDrive
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 5da4271f242597b195ef61d553fd4a2ffb313025
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716042"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a>Fix 0x8004de40 greška u usluzi OneDrive

Ako dobijete grešku 0x8004de40 u usluzi OneDrive:

- Ponovo pokrenite računar na koji je bio povezan sa domenom u vašem Akitve.
- Ako ponovno pokretanje ne reši problem, raspakovanje i ponovno pridruživanje uređaju iz Azure oglasa. 

**Napomena**: trebalo bi da budete na korporativnoj mreži dok izvršavate ove korake. Nemojte da izvršavate ove korake kada ne možete da se povežete sa korporativnom infrastrukturom (na primer, tokom putovanja). 

- Otvaranje pune komandne linije. 
- Kliknite desnim tasterom miša na **komandnu liniju** **, a**zatim izaberite stavku **Pokreni kao administrator**da biste otvorili sve pune komandne linije.
- Otkucajte *dsregcmd/napuštanje* i pritisnite taster **ENTER**.
- Kada dovršite, otkucajte *dsregcmd/JOIN* i pritisnite taster **ENTER**.
- Kada dovršite, zatvorite komandnu liniju.
- Ponovo pokrenite računar i prijavite se u OneDrive.