---
title: Moderna lokacija kao osnovna lokacija
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.date: 04/21/2020
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000265"
- "1874"
ms.openlocfilehash: 0388f95e2b7815dcbbb6aca200f44e55e9c5724f
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713805"
---
# <a name="modern-site-as-root-site"></a>Moderna lokacija kao osnovna lokacija

Počeli smo da iskorimo novu funkciju koja će vam omogućiti da [svoju klasičnu lokaciju razmenite sa modernom lokacijom](https://docs.microsoft.com/sharepoint/modern-root-site). Koristite funkciju [Pozovi-Spoziteswap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) da biste zamenili lokaciju lokacije sa drugom lokacijom dok arhivirate originalnu lokaciju. Dostupna za obe strane tima (nije povezano sa grupom) i komunikaciona lokacija.

>[!Important]
> Nemojte brisati klasičnu osnovnu lokaciju da biste kreirali modernu lokaciju za komunikaciju. Microsoft ne podržava ovaj program. Brisanjem osnovne lokacije sve SharePoint lokacije u vašoj organizaciji neće biti moguće pristupiti svim korisnicima, dok ne vratite lokaciju ili ne kreirate novu lokaciju na istoj URL adresi. Ovu karakteristiku ćemo komunicirati preko centra za poruke. Trebalo bi da očekujete da će funkcija uskoro biti uključena u vaš tenak.

## <a name="known-issues-with-swapping-sites"></a>Poznati problemi sa lokacijama za zamenjivanje
- Ciljna lokacija može da vrati grešku "nije pronađeno" (HTTP 404) u kratkom vremenskom periodu.
- Sadržaj će morati da se ponovo ažurira da bi se ažurirao indeks pretrage. Ovde nije potreban ručni korak, ovo će se automatski obaviti.
- Sve što zavisi od "statičnih" veza (kao što su sinhronizacija datoteka i OneNote datoteke) biće potrebno ručno korigovati.
- Možda će biti potrebno proveriti lokacije servera za Project da biste bili sigurni da su i dalje ispravno povezani. 
