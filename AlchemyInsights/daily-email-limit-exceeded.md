---
title: Daily Mail ograničenje je prekoračeno. Tok posla je obustavljen.
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 7/25/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1227"
ms.openlocfilehash: 802aba696da61be5f0a6c12072842cbc3cd96499
ms.sourcegitcommit: 407f6c1e82f1a0be5cf53301fbf03cd25dcbf0ee
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/02/2019
ms.locfileid: "36059652"
---
# <a name="daily-email-limit-exceeded-workflow-is-suspended"></a>Daily Mail je prekoračeno ograničenje. Tok posla je obustavljen.

Ova greška može biti primljen u sljedećim scenarijima:

- Imate toka posla u SharePoint na mreži koja koristi SharePoint 2010 ili SharePoint 2013 toka posla platforma tip.
- Tok je konfigurisan da pošaljete poruku prilagođene e-pošte za više od 200 korisnika po jedan, više od 10 000 primalaca dnevno ili više od 30 poruka u minuti.
- Kada pokrenete tok posla, zar ne poslati poruku e-pošte i primetite na sljedeći način:
    - Za tok posla pomoću SharePoint 2013 tip platforme, pregledate na stranicu " **Status toka posla** ". Na stranici "Status toka posla", **Unutrašnja Status** je podešen na **pokrenuto**, a balon informacija prikazuje **nije moguće poslati primaocu**.

Da biste rešili ovaj problem, konfigurišite vaš tok posla za slanje e-poruka bez prekoračenja [ograničenja za Exchange Online pošiljaoca](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits). Na primer, koristite pauze u toku posla, pošaljite e-poštu grupi programa Office 365, grupi za distribuciju ili pošta omogućena bezbednost grupe ili manje od 200 primaocima istovremeno pošaljete poruku.


Za više informacija, pogledajte sledeći [članak](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or).

## <a name="related-topics"></a>Povezane teme
- [Kreiranje toka](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [SharePoint i protok](https://flow.microsoft.com/blog/sharepoint-and-flow/) 