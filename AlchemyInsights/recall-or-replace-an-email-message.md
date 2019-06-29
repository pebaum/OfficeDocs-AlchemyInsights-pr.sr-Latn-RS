---
title: Opozovete ili zamenite e-poruku
ms.author: daeite
author: daeite
manager: joallard
ms.date: 05/15/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1860"
- "9000260"
ms.assetid: ''
ms.openlocfilehash: 170fbd632f0289a45d9497ac26fbe7f90cf88318
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/28/2019
ms.locfileid: "35356611"
---
# <a name="recall-or-replace-an-email-message"></a>Opozovete ili zamenite e-poruku

- Možete **samo opoziv poruke koje se šalju osobe u vašoj organizaciji**. Ako je poruka poslata na Gmail adresu, na primer, da mogu da se setim to.
- Možete **samo opoziv poruke poslane iz Outlook 2016 za PC**. Ako korisnik pošalje poruku koristeći Outlook za Mac ili Outlook na Webu, mogu da se setim.
- Ako si ti neki admin, možete **opoziv poruke u ime korisnika pomoću PowerShell**. Ne mogu da se setim poruke iz centra za administraciju. Pomerite se do „Traženje i brisanje poruke e-pošte u vašoj organizaciji” za više informacija.

***Opozovete ili zamenite e-poruku koju ste poslali***

1. U oknu fascikle na levoj strani prozora programa Outlook, odaberite fasciklu poslate stavke.
2. Otvorite poruku koju želite da opozovete. Ti mora dvaput kliknite na ikonu da biste otvorili poruku. Što ćete izabrati poruku, tako da se pojavljuje u oknu za čitanje neće vam dozvoliti da opoziv poruke.
3. Na kartici poruka, izaberite **Radnje** > **Opozovi ovu poruku**.
4. Odaberite **Izbriši nepročitane kopije ove poruke** ili **Izbriši nepročitane kopije i zameni ih novom porukom**, a zatim izaberite **OK**.
5. Ako šaljete poruku zamenu, napišite poruku, a zatim izaberite **Pošalji**.
6. Uspeh ili neuspeh opoziva poruke zavisi od primalaca postavke u programu Outlook.

Za više informacija, uključujući i kako da proverim opoziva, pogledajte [opoziv "ili" zameni e-poruku koju ste poslali](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

***Traženje i brisanje poruke e-pošte u vašoj organizaciji*** Za pretraživanje i brisanje poruke e-pošte u vašoj organizaciji, to je najlakše, ako si globalne admin. Ako nisi globalne admin, vaš račun mora se dodati u grupu uloga Menadžera za eDiscovery, ili u ulogu upravljanja usklađenosti pretrage. Da biste izbrisali poruke, moraćete da se pridruži grupi uloga upravljanje organizacijom ili uloga za upravljanje pretraživanja i očisti. Dozvole za ove uloge dodeljuju na [Centar za sigurnost & usklađenosti](https://protection.office.com/).

1. [Kreiraj sadržaj pretragu](https://docs.microsoft.com/office365/securitycompliance/content-search) pronaći poruku da biste je izbrisali.
2. [Povezivanje sa bezbednosti & usklađenosti centar PowerShell](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps). 

Ako koristite MFA, vidim da je [Povezivanje sa Office 365 bezbednosti & usklađenosti centar PowerShell koristeći višestruku potvrdu identiteta](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps). 
