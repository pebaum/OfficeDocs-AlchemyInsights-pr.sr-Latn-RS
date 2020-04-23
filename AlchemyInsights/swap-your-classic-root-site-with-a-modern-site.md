---
title: Razmenite klasičnu osnovnu lokaciju sa modernom lokacijom
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000687"
- "2579"
ms.openlocfilehash: f4831c6a232a4dee0f8f5ac0c83e4307221cfe2d
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43741558"
---
# <a name="swap-your-classic-root-site-with-a-modern-site"></a>Razmenite klasičnu osnovnu lokaciju sa modernom lokacijom

Ako je vaše okruženje podešeno pre aprila 2019, možete da promenite svoju osnovnu lokaciju na modernu lokaciju koristeći Microsoft PowerShell:

- Ako imate drugu lokaciju koju želite da koristite kao svoju osnovnu lokaciju, možete da je zamenite [(razmenite) na osnovnoj lokaciji](https://docs.microsoft.com/sharepoint/modern-root-site) . 
    - Koristite funkciju [Pozovi-Spoziteswap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) da biste zamenili lokaciju lokacije sa drugom lokacijom dok arhivirate originalnu lokaciju. Dostupna za obe strane tima (nije povezano sa grupom) i komunikaciona lokacija. 

- Uskoro će biti uvedene dodatne mogućnosti koje će vam omogućiti da nastavite da koristite sadržaj na lokaciji, ali da tu postojeću lokaciju konvertujete na lokaciju za komunikaciju. 
>[!Important]
>Ove mogućnosti će postepeno biti pregledano. Nastavite da proveravate centar za poruke da biste dobili ispravke. 

## <a name="known-issues-with-swapping-sites"></a>Poznati problemi sa lokacijama za zamenjivanje

- Ciljna lokacija može da vrati grešku "nije pronađeno" (HTTP 404) u kratkom vremenskom periodu.
- Sadržaj će morati da se ponovo ažurira da bi se ažurirao indeks pretrage. Nema potrebnog ručnog koraka-to će se uraditi automatski.
- Sve što zavisi od "statičnih" veza (kao što su sinhronizacija datoteka i OneNote datoteke) biće potrebno ručno korigovati.
- Ako je izvorna lokacija bila lokacija za organizacione vesti, ažurirajte URL adresu.Nabavite listu svih lokacija organizacionih vesti.
- Možda će biti potrebno proveriti lokacije servera za Project da biste bili sigurni da su i dalje ispravno povezani.
