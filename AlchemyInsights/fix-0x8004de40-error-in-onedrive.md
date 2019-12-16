---
title: Fix 0x8004de40 greška u usluzi OneDrive
ms.author: pebaum
author: pebaum
ms.date: 6/20/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 48b29f57763ca22a71a23b2afddcac0e8e8a95db
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40052051"
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