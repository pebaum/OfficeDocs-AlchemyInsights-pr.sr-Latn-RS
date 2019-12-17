---
title: Problemi sa performansama-SharePoint ili OneDrive
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1133"
- "2397"
- "2418"
- "5200018"
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: aecbf4043c6456ece73f7deed6b068040f0691a2
ms.sourcegitcommit: 0fb89d8106fe409ab1b78e50f5357ffc2252f7c7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/17/2019
ms.locfileid: "40068430"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a>SharePoint ili OneDrive spore, nepristupačne ili nedostupne za više korisnika

SharePoint ili OneDrive mogu da budu spore, nepristupačne ili nedostupne ili mogu da prikažu usluge nedostupne ili 503 grešaka, iz nekoliko razloga:
  
- Ako je SharePoint ili OneDrive lokacija spora ili odložena za više korisnika, možda postoji problem sa privremenim servisom gde korisnici dovode do povremenih kašnjenja ili grešaka pri navigaciji prilikom pristupanja SharePoint lokacijama ili OneDrive sadržaju. Proverite da li je vaša organizacija uticala na [instrument za zdravstvo](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) .
  
- Korisnici mogu da prime *503 server je zauzet* greškom prilikom pokušaja da se kreću na SharePoint ili OneDrive lokacije. Ova greška može biti izazvana regulisanja u okviru SharePoint usluge. SharePoint online koristi ograničavanje za održavanje optimalnih performansi i pouzdanosti SharePoint usluge na mreži. Ograničavanje ograničava broj radnji korisnika ili uporedne pozive (po skripti ili kodu) da bi sprečio prekomerno korišćenje resursa. Za više informacija o regulisanja pogledajte, [izbegavajte ograničavanje ili blokiranje na lokaciji SharePoint online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).

- Ako dođe do sporih performansi sa **klasičnom** ili **modernom** SharePoint lokacijom ili stranicom, koristite [dijagnostičku alatku stranice](https://aka.ms/perftool) da biste analizirali stranice.
  
- Ako i dalje nailazite na opšte sporije performanse, pregledajte resurse na dnu ovog članka: [Uvod u podešavanje performansi za SharePoint online](https://go.microsoft.com/fwlink/?linkid=2024334)
  