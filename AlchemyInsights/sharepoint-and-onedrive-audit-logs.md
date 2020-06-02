---
title: Klasični SharePoint izveštaji za evidenciju nadgledanja
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1372"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 0aedb549f11db54d3cd480671fb0767c60680ad3
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44509614"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a>SharePoint i OneDrive evidencije nadgledanja

## <a name="sharepoint-classic-audit-logs"></a>SharePoint Classic evidencija nadgledanja

Nasleđena revizija SPO-a je premeštena u jedinstvenu evidenciju nadgledanja (UAL). Sve zastarele revizorske izveštaje iz SPO-a sada će se provići kroz UAL, a signali nasleđene revizije su preseljeni u UAL.

Promene u ključu:

* Skraćivanje nije dostupno kao mogućnost.
* Izbor određenih događaja za reviziju nije dostupan. Pogledajte [ovaj dokument](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance) za kompletnu listu nadgledanog događaja koji su podrazumevano dostupni.
* Opcija " **lokacija** " u okviru **prilagođenog izveštaja** nije dostupna.
* Opcija " **Otvaranje" ili "preuzimanje dokumenata** " nije dostupna.

[Konfigurisanje postavki nadgledanja za kolekciju lokacija](https://support.office.com/article/Configure-audit-settings-for-a-site-collection-A9920C97-38C0-44F2-8BCB-4CF1E2AE22D2)

## <a name="sharepoint-and-onedrive-modern-unified-audit-logs-from-compliance"></a>SharePoint i OneDrive savremeno ujednačene evidencije nadgledanja iz usaglašenosti

* [Uključivanje/isključivanje ujednačene evidencije nadgledanja](https://docs.microsoft.com/microsoft-365/compliance/turn-audit-log-search-on-or-off) 

U sistemu SharePoint ili OneDrive nije potrebna dodatna konfiguracija.

Koristite pretragu vođenja evidencije nadgledanja da biste proverili aktivnost datoteka, fascikli, korisnika, dozvola:

* [Aktivnosti datoteka i stranica](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance)
* [Aktivnosti fascikle](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#folder-activities)
* [Deljenje i pristup aktivnostima zahteva](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
* [Aktivnosti sinhronizacije](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
* [Aktivnosti administracije lokacije](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)

Za više informacija o tome kako da preuzmete ove događaje pogledajte odeljak [pretraživanje evidencije nadgledanja](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).
