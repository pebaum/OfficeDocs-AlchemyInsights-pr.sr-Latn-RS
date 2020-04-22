---
title: Sadržaj se ne pojavljuje u rezultatima SharePoint pretrage
ms.author: tlarsen
author: tklarsen
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "750"
- "5300017"
ms.assetid: 693db84f-2737-4c21-b027-4ab3d121b4a8
ms.openlocfilehash: a21e0047b41390f740f9e13d31cba32b13990151
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43705675"
---
# <a name="content-doesnt-appear-in-sharepoint-search-results"></a>Sadržaj se ne pojavljuje u rezultatima SharePoint pretrage

Sledite ove korake za rešavanje problema kada se očekivani sadržaj ne pojavi u rezultatima pretrage:
  
1. Proverite da li je **lokacija** koja sadrži očekivani sadržaj podešena tako da dozvoli da se sadržaj pojavi u rezultatima pretrage. Sledite korake u programu [Prikaži sadržaj na lokaciji u rezultatima pretrage](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-on-a-site-in-search-results).

2. Proverite da li je **Lista** ili **Biblioteka** koja sadrži očekivani sadržaj podešena tako da dozvoli da se sadržaj pojavi u rezultatima pretrage. Sledite korake u polju [Prikaži sadržaj iz lista ili biblioteka u rezultatima pretrage](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-from-lists-or-libraries-in-search-results).

3. Proverite da li su stranica, dokument ili prilagođeni raspored na stranici objavljeni kao **glavna verzija.** Sledite korak 3 u [pretrazi ne vraća sve rezultate na SharePoint mreži](https://go.microsoft.com/fwlink/?linkid=874525).

4. Proverite da li korisnik ima **dozvole** za pregledanje sadržaja. Sledite korake u [razumevanju nivoa dozvola u sistemu SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).
    
5. Ako je šema pretrage promenjena dodavanjem novog upravljanog svojstva, uređivanjem upravljanog svojstva ili uklanjanjem upravljanog svojstva onda se zahteva popisivanje i ponovno indeksiranje. **Ponovo indeksirati** sadržaj tako što ćete slediti korake iz [ručnog popisivanja i ponovnog indeksiranja lokacije, biblioteke ili liste](https://docs.microsoft.com/sharepoint/crawl-site-content). Ovo može potrajati, sačekajte 24 sata pre nego što ponovo proverite rezultate.

Više informacija potražite u članku [Omogućavanje sadržaja na lokaciji da bude pretraživo](https://docs.microsoft.com/sharepoint/make-site-content-searchable). 
  
