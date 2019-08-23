---
title: Tok posla se ne pokreće
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 8/2/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000144"
- "1670"
ms.openlocfilehash: d4bfdb44c04eb6838f4a265e55a4873d14c78f6d
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36557998"
---
# <a name="workflow-is-not-starting"></a>Tok posla se ne pokreće

- SharePoint 2010 i SharePoint 2013 tokovi posla ne počinju.

    - Ako ne uspijete pokrenuti tok posla, postoji problem sa privremene servis gde korisnici iskusiti intervalni kašnjenja sa napredak toka posla. Proverite [Kontrolnu tablu zdravstvenih usluga](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) da vidim ako je uticala na vašu organizaciju.

    - Ako više od 24 sata je prošlo od kad ste prvi put videli ovaj problem, odjavite kartu za podršku. U mnogim slučajevima, već radimo na rešenje. Molim vas, dajte nam barem 24 sata da biste dovršili rešenje.

- Tokovi posla SharePoint 2010 odložen na start.

    - To se događa ako se tok posla je aktivirati u velikom loncu. (na primer, kada nekoliko stavke dodaju u isto vreme).

    - Tokovi posla nisu dizajnirani za pokretanje u realnom vremenu, tako da kašnjenja do dizajna ponašanje.

   -  Ako je tok posla kompleks Extensible objekat Markup Language (XMOL), kompilacije može biti sporo. Pogledajte [ovaj](https://support.microsoft.com/en-us/kb/3043697) članak.

    - Treba da pojednostavite toka posla ili redizajn i koristeći tip platforme Microsoft SharePoint 2013 toka posla.

    - Tok istorije je postala velika, možda ćete želeti da očisti stavke ili da kreirate novu listu istorije.

        Više informacija: da [Očisti tok istorije](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)


## <a name="related-topics"></a>Povezane teme
Da probamo Microsoft Flow u SharePoint Online?
- [Kreiranje toka](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [SharePoint i protok](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


