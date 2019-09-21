---
title: Klasični SharePoint izveštaji za evidenciju nadgledanja
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1372"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: af5b3c76b82db13bc89c917247e41fa1d8779b68
ms.sourcegitcommit: d5bf97a0bf0547f36b6da9684ce9f16a13a7749e
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/20/2019
ms.locfileid: "37068037"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a>SharePoint i OneDrive evidencije nadgledanja

**SharePoint i OneDrive savremeno ujednačene evidencije nadgledanja iz usaglašenosti**

- [Uključivanje/isključivanje ujednačene evidencije nadgledanja](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off) 

U sistemu SharePoint ili OneDrive nije potrebna dodatna konfiguracija.

- Koristite pretragu vođenja evidencije nadgledanja da biste proverili aktivnost datoteka, fascikli, korisnika, dozvola:

    - [Aktivnosti datoteka i stranica](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)
    - [Aktivnosti fascikle](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#folder-activities)
    - [Deljenje i pristup aktivnostima zahteva](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
    - [Aktivnosti sinhronizacije](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
    - [Aktivnosti administracije lokacije](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)
- Za više informacija o tome kako da preuzmete ove događaje pogledajte odeljak [pretraživanje evidencije nadgledanja](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).

**SharePoint Classic evidencija nadgledanja**

Preselili smo iz SPO-a da bi se ujedinio evidencija nadgledanja (UAL). To u suštini znači da će celokupan izveštaj o nadzoru iz SPO-a sada biti uključen u UAL, a da su signali nasleđene revizije preseljeni u UAL.

Promene u ključu:

- Skraćivanje kao mogućnost nije dostupno.
- Odeljak u kome birate određene događaje za reviziju nije dostupan. Pogledajte [ovaj dokument](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) za kompletnu listu nadgledanog događaja koji su podrazumevano dostupni.
- Opcija "lokacija" u okviru **prilagođenog izveštaja** nije dostupna. 
- Događaj "otvaranje ili preuzimanje dokumenata" nije dostupan. 

