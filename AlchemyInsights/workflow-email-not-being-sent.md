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
ms.openlocfilehash: 261fe1b1bc815dd4ad568051cfefad1e214b957e
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36530902"
---
# <a name="workflow-email-is-not-being-sent-for-a-sharepoint-list-or-library"></a>Tok posla e-mail ne šalje za SharePoint liste ili biblioteke

1. Mejl od tokova posla ne šalju se svim korisnicima ili samo određenim korisnicima, ili vidite da je greška u **poruci e-pošte nije moguće poslati. Uverite se da e-poruka nema važećeg primaoca**.

    Proveri da li korisnik postoje u **Svim ljudima** dozvole grupi (korisničke informacije lista) za tu kolekciju.  Uzorak direktni URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx? MembershipGroupId = 0

    - Ako korisnik ne postoji, uverite se da korisnik bude potpisan u stranicu. 
    - Ako je spoljnog korisnika, uverite se da je njihov poziv je prihvaćen.
    - Ako je korisnik postoji u grupi dozvole, uverite se da je e-adresa tačna.
    - Ako e-adresa korisnika podešen ovde, zatim kreirajte primer obaveštenja za tog korisnika koje obavezuje sinhronizacije za taj korisnički nalog iz SharePoint profila korisnika u ovoj kolekciji lokacija.
 
2. E-mail iz tokovi posla se šalju administratorima kolekcije lokacija, ali ne i ostalim korisnicima, i vidim grešku **HTTP zabranjeno da <span>https:</span>//URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**.
 

    Vidim [Zabranjen pristup kada šaljete e-mail na SharePoint grupa](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).

    Takođe, proverite da li funkciju kolekcije lokacija je **ograničen pristup korisnika dozvola pritajili** nije aktivan.


## <a name="related-topics"></a>Povezane teme
Da probamo Microsoft Flow u SharePoint Online?
- [Kreiranje toka](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [SharePoint i protok](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


