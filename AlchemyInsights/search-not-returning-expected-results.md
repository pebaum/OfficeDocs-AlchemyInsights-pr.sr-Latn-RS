---
title: 1491-pretraga-ne-povratak-očekivani-rezultati
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1491"
- "3200003"
ms.assetid: ''
ms.openlocfilehash: d0707af19b0299f7257a10a20ab38f47860308fb
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43709241"
---
# <a name="content-search-not-returning-expected-results"></a>Pretraga sadržaja ne vraća očekivane rezultate

Kada se izvršavaju pretrage sadržaja sa Microsoft 365 bezbednosnog & centra za usaglašavanje, možda ćete dobiti neočekivane rezultate pretrage. Razmotrite sledeće radnje koje mogu da utiču na rezultate pretrage:

- **Lokacije sadržaja i uslovi pretraživanja**: proverite da li ste izabrali odgovarajuće lokacije sadržaja i uslove pretrage. Ako ste pokrenuli veliku pretragu (sa mnogim lokacijama), razmislite o tome da je razdelite u više pretraga.

- **Delimično indeksirane stavke**: [delimično indeksirane stavke](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) iz poštanskih sandučića su uključene u procenjene rezultate pretrage. Međutim, delimično indeksirane stavke sa lokacija u sistemu SharePoint i OneDrive nisu uključene u procenu pretrage.

- **Otkazivanja pretrage**: prilikom pretraživanja velikog broja poštanskih sandučića (preko 100.000 poštanskih sandučića), možda ćete dobiti greške pri pretraživanju, uz kodove grešaka kao što su CS008-009 i CS012-002). U ovom slučaju, pokušajte da pretražite samo za neuspele lokacije sadržaja. Više informacija potražite u [ovom članku](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) .
