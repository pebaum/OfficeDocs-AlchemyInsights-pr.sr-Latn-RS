---
title: Greška u timovima 4c7
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3472"
- "9001211"
ms.openlocfilehash: 0945a341c6456ee4178c0485f3bfb9232fa78a11
ms.sourcegitcommit: 802537a54ef8bde1bdd758ee9a60b6c19d37d6e1
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/19/2019
ms.locfileid: "40796344"
---
# <a name="4c7-error-in-microsoft-teams"></a>4c7 greška u Microsoft timovima

Ova greška se javlja zato što Microsoft timovi zahtevaju potvrdu identiteta obrazaca. Kada primenite usluge Federacije aktivnog direktorijuma (AD FS), provera identiteta obrazaca podrazumevano nije omogućena za internu mrežu. Ako Windows integrisana potvrda identiteta ne uspe, od vas će se zatražiti da se prijavite pomoću provere identiteta obrazaca.

Da biste rešili ovaj problem, omogućite potvrdu identiteta obrazaca pomoću proširenja konzole "AD FS Microsoft Management Console (MMC)" na računaru koji ima lokalnu kopiju aktivnog direktorijuma. Da biste to uradili, sledite ove korake: 

1. U oknu za navigaciju potražite smernice za **potvrdu identiteta**.
2. U okviru **stavke Radnje** u oknu sa detaljima izaberite stavku **Uredi globalnu primarnu potvrdu identiteta**.
3. Na kartici " **interna mreža** " izaberite stavku " **Provera identiteta obrazaca**".
4. Izaberite **"u redu"** (ili **Primijeni**).