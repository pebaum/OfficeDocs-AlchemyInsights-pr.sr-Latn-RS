---
title: Sadržaj se ne pojavljuje u rezultatima pretraživanja za SharePoint
ms.author: tlarsen
author: tklarsen
ms.date: 1/8/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "750"
- "5300017"
ms.assetid: 693db84f-2737-4c21-b027-4ab3d121b4a8
ms.openlocfilehash: 8215b0a5cde5adffa3bec37d6699418557f914dd
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/28/2019
ms.locfileid: "35363833"
---
# <a name="content-doesnt-appear-in-sharepoint-search-results"></a>Sadržaj se ne pojavljuje u rezultatima pretraživanja za SharePoint

Sledite ove korake za rešavanje problema kada očekivani sadržaj se ne pojavljuje u rezultatima pretrage:
  
1. Proverite da je na **lokaciji** koja sadrži sadržaj očekivanih postavljeno da dozvoli da se sadržaj pojavljuje u rezultatima pretraživanja. Sledite korake u [Prikaži sadržaj na lokaciji u rezultatima pretrage](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-on-a-site-in-search-results).

2. Proveri da **listu** ili **biblioteku** koja sadrži očekivani sadržaj postavljen tako da dozvoljava sadržaja da se pojavljuju u rezultatima pretrage. Sledite korake u [Prikaži sadržaj sa liste ili biblioteke u rezultatima pretrage](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-from-lists-or-libraries-in-search-results).

3. Provjerite da na stranice, dokumenta ili prilagođene stranice raspored objavljuje kao na **glavnu verziju.** Pratite korak 3 u [Pretraga ne vrati sve rezultate u SharePoint Online](https://go.microsoft.com/fwlink/?linkid=874525).

4. Proverite da li korisnik ima **dozvole** za pregled sadržaja. Sledite korake u [razumevanju nivoi dozvola u sistemu SharePoint](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).
    
5. Ako šemi pretraživanja je promenjen, tako što ćete dodati novo upravljano svojstvo za uređivanje upravljanog svojstva, odnosno uklanjanjem upravljanog svojstva onda zahteva puzanja i biće potrebno ponovno indeksiranje. **Ponovno indeksiranje** sadržaja tako što ćete pratiti korake u [ručno zatražite pretraživanje i ponovno indeksiranje lokacije, u biblioteku ili listu](https://docs.microsoft.com/sharepoint/crawl-site-content). Ovo može potrajati, čekaj 24 sata pre provere rezultate ponovo.

Za više informacija, pogledajte [Omogući sadržaj na lokaciji da budu pretražene](https://docs.microsoft.com/sharepoint/make-site-content-searchable). 
  
