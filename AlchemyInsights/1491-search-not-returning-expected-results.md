---
title: 1491-Search-not-returning-expected-Results
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: ''
ms.openlocfilehash: 881a579d7098578452c994b7ac66fe22a1d90dc2
ms.sourcegitcommit: 5182c9a73641079be59740e4524434b2e8be613a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29964953"
---
# <a name="content-search-not-returning-expected-results"></a>Sadržaja pretrage ne daje očekivane rezultate

Pri pokretanju sadržaja pretrage iz Office 365 bezbednosti & usklađenosti Center, možda ćete dobiti neočekivane rezultate. Razmotrite sledeće stvari koje mogu da utiču na rezultate pretrage:

- **Sadržaja lokacije i uslove pretrage**: proverite da li ste izabrali odgovarajući sadržaj lokacije i pretražite uslove. Ako ste pokrenuli veliku potragu (sa više lokacija), Smatraj to razdvajanje u više pretraga.

- **Delimično indeksirane stavke**: [delimično indeksirane stavke](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) iz Poštanske sandučiće nalaze se u rezultatima pretrage otprilike. Međutim, delimično indeksirane stavke sa lokacija u SharePoint i OneDrive nisu uključene u pretrage procena.

- **Pretraživanje otkazivanja**: prilikom pretraživanja velikog broja poštanskih sandučića (preko 100 000 poštanskih sandučića), možda dobijete pretragu grešaka, sa kodovima greške kao što su CS008-009 i CS012-002). U ovom slučaju, ponovo pokušajte pretragu samo za propali sadržaja lokacije. Pogledajte [Ovaj članak](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) za više informacija.
