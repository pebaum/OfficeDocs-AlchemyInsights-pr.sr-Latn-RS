---
title: E-poruka toka posla se ne šalje
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1586"
ms.openlocfilehash: 391d3a2dcc2676a405065115f375c802d2492119
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766147"
---
# <a name="workflow-email-is-not-being-sent-for-a-sharepoint-list-or-library"></a>E-poruka toka posla se ne šalje za SharePoint listu ili biblioteku

1. E-pošta iz tokova posla se ne šalje svim korisnicima ili samo određenim korisnicima ili vidite grešku **nije moguće poslati e-poruku. Uverite se da e-poruka ima važećeg primaoca**.

    Proverite da li korisnik postoji u grupi " **sve osobe** za dozvole" (Lista korisničkih informacija) za tu kolekciju lokacija.  Uzorak direktne URL adrese:<tenant>https://.<sitename>SharePoint.com/sites//_layouts/15/ljudi .aspx? Grupa špeditera = 0

    - Ako korisnik ne postoji, proverite da li je korisnik prijavljen na stranicu. 
    - Ako je to spoljni korisnik, uverite se da je poziv prihvaćen.
    - Ako korisnik ne postoji u grupi dozvola, uverite se da je e-adresa tačna.
    - Ako ne postavite adresu e-pošte korisnika, onda Kreirajte obaveštenje za tog korisnika koji primorava sinhronizaciju tog korisničkog naloga od korisničkih profila u ovoj kolekciji lokacija.
 
2. E-pošta iz tokova posla se šalje administratorima kolekcije lokacija, ali ne ostalim korisnicima i vidi grešku koju je **http zabranjen za <span>https:</span>//URL/_vti_bin/Client.XVC.SP.Utilities.Utility.sendemail**.
 

    [Za slanje e-poruke SharePoint grupi vidite zabranu pristupa](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).

    Takođe, proverite da li je u režimu za opciju "nije aktivna **dozvola za pristup** " za korisnike lokacije "Ograničeno".


## <a name="related-topics"></a>Povezane teme
Želite li da isprobate Microsoft protok na SharePoint mreži?
- [Kreiraj tok](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [SharePoint i protok](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


