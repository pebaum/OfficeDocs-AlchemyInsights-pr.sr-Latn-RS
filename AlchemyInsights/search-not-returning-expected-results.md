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
ms.openlocfilehash: 57421d459ef03049d6f931db659a5f9b253f5002
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44510586"
---
# <a name="content-search-not-returning-expected-results"></a>Pretraga sadržaja ne vraća očekivane rezultate

Kada se izvršavaju pretrage sadržaja sa Microsoft 365 bezbednosnog & centra za usaglašavanje, možda ćete dobiti neočekivane rezultate pretrage. Razmotrite sledeće radnje koje mogu da utiču na rezultate pretrage:

- **Lokacije sadržaja i uslovi pretraživanja**: proverite da li ste izabrali odgovarajuće lokacije sadržaja i uslove pretrage. Ako ste pokrenuli veliku pretragu (sa mnogim lokacijama), razmislite o tome da je razdelite u više pretraga.

- **Delimično indeksirane stavke**: [delimično indeksirane stavke](https://docs.microsoft.com/microsoft-365/compliance/partially-indexed-items-in-content-search) iz poštanskih sandučića su uključene u procenjene rezultate pretrage. Međutim, delimično indeksirane stavke sa lokacija u sistemu SharePoint i OneDrive nisu uključene u procenu pretrage.

- **Otkazivanja pretrage**: prilikom pretraživanja velikog broja poštanskih sandučića (preko 100.000 poštanskih sandučića), možda ćete dobiti greške pri pretraživanju, uz kodove grešaka kao što su CS008-009 i CS012-002). U ovom slučaju, pokušajte da pretražite samo za neuspele lokacije sadržaja. Više informacija potražite u [ovom članku](https://docs.microsoft.com/microsoft-365/compliance/retry-failed-content-search) .
