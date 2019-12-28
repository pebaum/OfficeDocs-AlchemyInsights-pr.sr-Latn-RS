---
title: Pošalji korisnička obaveštenja pomoću Intune
ms.author: brenduns
author: brenduns
manager: dougeby
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000679"
- "2565"
ms.openlocfilehash: 969649084a2ac536ee1b41f225c3be5415a27c4b
ms.sourcegitcommit: 2572c4e5a981d5f3f556835061c568cfd08b78da
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/27/2019
ms.locfileid: "40886871"
---
# <a name="how-to-send-custom-notifications-to-the-users-of-managed-ios-and-android-devices"></a>Kako slati prilagođena obaveštenja korisnicima kontrolisanih iOS i Android uređaja

Na korisničkom uređaju obrađuje se prilagođena obaveštenja za Intune. Aplikacija zatim kreira push obaveštenja na tom uređaju.

Slede preduslovi za uređaje za podržavanje prijema prilagođenih obaveštenja, kao i za aplikaciju koja zatim kreira Push obaveštenje:

- Uređaj mora imati instaliranu aplikaciju "portal kompanije".  

- Uređaj mora da dozvoli aplikaciji Company da šalje push obaveštenja. Kada se aplikacija instalira ili ažurira, on će zatražiti od korisnika da dozvoli obaveštenja.

- Android uređaji moraju imati instalirane usluge Google Play Services.

- Uređaj mora biti upisan uz Intune.

Više informacija o tome kako da pošaljete poruku potražite u [dokumentaciji funkcije](https://docs.microsoft.com/intune/custom-notifications).
