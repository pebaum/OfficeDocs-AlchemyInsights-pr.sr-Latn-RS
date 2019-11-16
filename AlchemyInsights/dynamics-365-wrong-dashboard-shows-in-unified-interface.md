---
title: Dynamics 365-pogrešna Kontrolna tabla u Dynamics 365 ujednačeni interfejs
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1484"
- "6200024"
ms.openlocfilehash: 3d7258bdd7366f679b048e93926ab7dfe0b956d9
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/15/2019
ms.locfileid: "36528565"
---
# <a name="wrong-dashboard-shows-in-dynamics-365-unified-interface"></a>Pogrešna Kontrolna tabla pokazuje se u Dynamics 365 ujednačeni interfejs

Postoji nekoliko razloga zbog kojih možete videti drugačiju kontrolnu tablu od one koju očekujete:

## <a name="the-user-has-set-a-user-default-dashboard"></a>Korisnik je podesio korisnički podrazumevanu kontrolnu tablu 

Obično možete identifikovati da je podrazumevana Kontrolna tabla korisnika postavljena ako se dugme " **Postavi kao podrazumevano** " ne prikazuje na komandnoj traci kontrolne table. Podrazumevana Kontrolna tabla korisnika će zameniti sve ostale podrazumevane kontrolne table, čak i ako se podrazumevana Kontrolna tabla korisnika ne nalazi u trenutnoj aplikaciji.

Koristite sledeće rešenje da biste razgruppostavili podrazumevanu kontrolnu tablu.

1. Kreirajte novu ličnu kontrolnu tablu.

2. Postavite novu kontrolnu tablu kao podrazumevanu vrednost za korisnika.

3. Izbrišite kontrolnu tablu.

## <a name="the-dashboard-is-set-in-the-sitemap"></a>Kontrolna tabla je postavljena na "Mapa sajta"

Možda ste podesili podrazumevanu kontrolnu tablu za organizaciju tako što ćete izabrati kontrolnu tablu i odabrati opciju "Postavi kao podrazumevanu" u okviru "Prilagodi sistem". Međutim, Kontrolna tabla definisana u dizajneru mapa lokacije će imati prednost u odnosu na ovu kontrolnu tablu ako korisnik ima pristup.

Da bi korisnici videli kontrolnu tablu koju ste postavili kao podrazumevanu organizaciju, možete da:

* Postavite kontrolnu tablu na kontrolnoj tabli

* Uklanjanje pristupa za tu lokaciju definisana Kontrolna tabla za ove korisnike
