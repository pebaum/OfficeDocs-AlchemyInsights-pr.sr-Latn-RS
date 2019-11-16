---
title: Outlook radna površina se opoziva ili zamenjuje e-poruku
ms.author: daeite
author: daeite
manager: joallard
ms.date: 3/13/2019
ms.audience: Admin
ms.topic: article
ms.custom: 9000260
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: 3d3a6c253317137b7069a978b907c97d61bf7313
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/15/2019
ms.locfileid: "36496125"
---
# <a name="recall-or-replace-an-outlook-email-message"></a>Opozivanje ili zamenjivanje e-poruke programa Outlook

- Kao administrator, možete da **opozovete poruke u ime korisnika pomoću programa "PowerShell**". Ne možete da opozovete poruke iz administratorskog centra.
- Možete **samo da opozovete poruke koje se šalju osobama iz vaše organizacije**. Na primer, ako je poruka poslata na gmail adresu, ne možete je opozvati.
- Možete **samo da opozovete poruke poslate iz programa Outlook 2016 na računaru**. Ako korisnik pošalje poruku pomoću programa Outlook za Mac ili Outlook na Webu, ne možete je opozvati.

Da biste opozvali ili zamenili e-poruku:

1. U oknu sa leve strane prozora programa Outlook izaberite fasciklu "Poslate stavke".
1. Dvaput kliknite na poruku koju želite da opozovete da biste je otvorili.
1. Izaberite karticu **poruka** , a zatim izaberite **Radnje** > **Opozovi ovu poruku**.
1. Izaberite stavku **Izbriši nepročitane kopije ove poruke** ili **Izbrišite nepročitane kopije i zamenite ih novom porukom**, a zatim kliknite na **dugme u redu**.
1. Ako šaljete poruku za zamenu, napišite poruku, a zatim kliknite na dugme " **Pošalji**".
1. Uspeh ili neuspeh opoziva poruke zavisi od postavki primaoca u programu Outlook. Da biste mogli da proverite opoziv, pogledajte [Ovaj članak](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

Traženje i brisanje e-poruka u vašoj organizaciji

- Ako niste globalni administrator, vaš nalog mora biti dodat u ulogu eDiscovery menadžera ili u ulogu upravljanja pretragom usaglašenosti da biste potražili poruke. Da biste izbrisali poruke, potrebno je da se pridružite grupi uloga za upravljanje organizacijom ili u ulozi za pretraživanje i čišćenje. Dozvole za ove uloge se dodeljuju u [centru za bezbednost i usaglašenost](https://go.microsoft.com/fwlink/?linkid=2083731).
- [Kreirajte pretragu sadržaja](https://docs.microsoft.com/office365/securitycompliance/content-search) da biste pronašli poruku za brisanje.
- [Poveži se sa bezbednošću i PowerShell centra za usaglašavanje](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).

Ako koristite nepotvrdu identiteta sa više faktora, pogledajte odeljak [Povezivanje sa lokacijom Office 365 Security i centar za usaglašavanje pomoću višefaktora potvrde identiteta](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).