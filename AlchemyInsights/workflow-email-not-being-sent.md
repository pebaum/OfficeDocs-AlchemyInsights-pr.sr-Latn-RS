---
title: Tok posla e-mail ne šalje
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
- "1586"
ms.openlocfilehash: 783bf0a5721aa5db7088432c71e06cac6dc90513
ms.sourcegitcommit: 407f6c1e82f1a0be5cf53301fbf03cd25dcbf0ee
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/02/2019
ms.locfileid: "36059617"
---
# <a name="workflow-email-is-not-being-sent"></a>Tok posla e-mail ne šalje

1. Mejl od tokova posla ne šalju se svim korisnicima ili samo određenim korisnicima, ili vidite da je greška u **poruci e-pošte nije moguće poslati. Uverite se da e-poruka nema važećeg primaoca**.

Proveri da li korisnik postoje u **Svim ljudima** dozvole grupi (korisničke informacije lista) za tu kolekciju.  Uzorak direktni URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx? MembershipGroupId = 0

- Ako korisnik ne postoji, uverite se da korisnik bude potpisan u stranicu. 
- Ako je spoljnog korisnika, uverite se da je njihov poziv je prihvaćen.
- Ako je korisnik postoji u grupi dozvole, uverite se da je e-adresa tačna.
- Ako e-adresa korisnika podešen ovde, zatim kreirajte primer obaveštenja za tog korisnika koje obavezuje sinhronizacije za taj korisnički nalog iz SharePoint profila korisnika u ovoj kolekciji lokacija.
 
2. E-mail iz tokovi posla se šalju administratorima kolekcije lokacija, ali ne i ostalim korisnicima, i vidim grešku **HTTP zabranjeno da <spam> <spam> ** <spam> <spam>.
 

Vidim [Zabranjen pristup kada poslate e-poruke za grupe](https://docs.microsoft.com/sharepoint/support/server-admin/access-denied-when-send-an-email-to-groups).

Takođe, proverite da li funkciju kolekcije lokacija je **ograničen pristup korisnika dozvola pritajili** nije aktivan.

## <a name="related-topics"></a>Povezane teme
- [Kreiranje toka](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [SharePoint i protok](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


