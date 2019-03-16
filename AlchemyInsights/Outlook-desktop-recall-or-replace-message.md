---
title: Na radnoj površini opoziv programa Outlook "ili" zameni e-poruku
ms.author: daeite
author: daeite
manager: joallard
ms.date: 3/13/2019
ms.audience: Admin
ms.topic: article
ms.custom: 9000260
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: aced684777ef82860b969aea8825699b78b04c5a
ms.sourcegitcommit: aad9f863bc9fd7d5522c480bd1a7d15f3a80ff4f
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/15/2019
ms.locfileid: "30657057"
---
# <a name="recall-or-replace-an-email-message"></a>Opozovete ili zamenite e-poruku

- Kao administrator, možete **opoziv poruke u ime korisnika pomoću PowerShell**. Ne mogu da se setim poruke iz centra za administraciju.
- Možete **samo opoziv poruke koje se šalju osobe u vašoj organizaciji**. Ako je poruka poslata na Gmail adresu, na primer, da mogu da se setim to.
- Možete **samo opoziv poruke poslane iz Outlook 2016 na PC**. Ako korisnik pošalje poruku koristeći Outlook za Mac ili Outlook na Webu, mogu da se setim.

Da opozovete ili zamenite e-poruku:

1. U oknu fascikle na levoj strani prozora programa Outlook izaberite fasciklu poslate stavke.
1. Kliknite dvaput na poruku koju želite da se setim da biste je otvorili.
1. Izaberite karticu za **poruku** , a zatim izaberite **Radnje** > **Opozovi ovu poruku**.
1. Izaberite **Izbriši nepročitane kopije ove poruke** ili **Izbriši nepročitane kopije i zameni ih novom porukom**, a zatim izaberite **OK**.
1. Ako šaljete poruku zamenu, koristite za pisanje poruke, a zatim izaberite **Pošalji**.
1. Uspeh ili neuspeh opoziva poruke zavisi od primaoca postavke u programu Outlook. Korake da proveri opoziv, potražite u [ovom članku](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

Pronađite i izbrišite poruke e-pošte u vašoj organizaciji

- Ako ti nisi globalne admin, vaš račun mora da se doda na eDiscovery Manager ulogu ili ulogu upravljanja usklađenosti pretragu da biste pronašli poruke. Da biste izbrisali poruke, moraćete da se pridruži grupi uloga upravljanje organizacijom ili uloga za upravljanje pretraživanja i očisti. Dozvole za ove uloge dodeljuju na [Centar za sigurnost i usklađenosti](https://go.microsoft.com/fwlink/?linkid=2083731).
- [Kreiraj sadržaj pretragu](https://docs.microsoft.com/office365/securitycompliance/content-search) pronaći poruku da biste je izbrisali.
- [Povezivanje sa sigurnosti i usklađenosti centar PowerShell](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).

Ako koristite višestruku potvrdu identiteta, vidim da je [Povezivanje sa Office 365 sigurnosti i usklađenosti centar PowerShell koristeći višestruku potvrdu identiteta](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).