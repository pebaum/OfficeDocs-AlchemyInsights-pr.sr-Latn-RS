---
title: Opozivanje ili zamenjivanje e-poruke
ms.author: daeite
author: daeite
manager: joallard
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1860"
- "9000260"
ms.assetid: ''
ms.openlocfilehash: e958dab159e4dcc11f9c068bded3aa06ccd65c15
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44509470"
---
# <a name="recall-or-replace-an-email-message-in-microsoft-365"></a>Opozivanje ili zamenjivanje e-poruke u programu Microsoft 365

- Možete **samo da opozovete poruke koje se šalju osobama iz vaše organizacije**. Na primer, ako je poruka poslata na gmail adresu, ne možete je opozvati.
- Možete **samo da opozovete poruke poslate iz programa Outlook 2016 za računar**. Ako korisnik pošalje poruku pomoću programa Outlook za Mac ili Outlook na Webu, ne možete je opozvati.
- Ako ste administrator, možete da **opozovete poruke u ime korisnika pomoću programa PowerShell**. Ne možete da opozovete poruke iz administratorskog centra. Pomerite se nadole da biste dobili više informacija "potražite i izbrišite e-poruke u vašoj organizaciji".

**Opozivanje ili zamenjivanje e-poruke koju ste poslali**

1. U oknu sa fasciklama na levoj strani prozora programa Outlook Odaberite fasciklu "Poslate stavke".
2. Otvorite poruku koju želite da opozovete. Morate dvaput kliknuti da biste otvorili poruku. Ako izaberete poruku tako da se pojavi u oknu za čitanje, nećete dozvoliti da opozovete poruku.
3. Na kartici poruke izaberite **Radnje**  >  **Opozovi ovu poruku**.
4. Odaberite stavku " **Izbriši nepročitane kopije" ove poruke** ili **Izbrišite nepročitane kopije i zamenite ih novom porukom**, a zatim kliknite na **dugme "u redu"**.
5. Ako šaljete poruku za zamenu, napišite poruku, a zatim kliknite na dugme " **Pošalji**".
6. Uspeh ili neuspeh opoziva poruke zavisi od postavki primalaca u programu Outlook.

Za više informacija, uključujući i to kako da proverite opoziv, pogledajte odeljak [opoziv ili zamenjivanje e-poruke koju ste poslali](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

***Traženje i brisanje e-poruka u vašoj organizaciji*** Da biste potražili i izbrisali e-poruke u vašoj organizaciji, najlakše je ako ste globalni administrator. Ako niste globalni administrator, vaš nalog mora biti dodat grupi uloga eDiscovery Manager ili u ulogu upravljanja pretragom usaglašenosti. Da biste izbrisali poruke, potrebno je da se pridružite grupi uloga za upravljanje organizacijom ili u ulozi za pretraživanje i čišćenje. Dozvole za ove uloge se dodeljuju u okviru [bezbednosnog & centra za usaglašavanje](https://protection.office.com/).

1. [Kreirajte pretragu sadržaja](https://docs.microsoft.com/microsoft-365/compliance/content-search) da biste pronašli poruku za brisanje.
2. [Povezivanje sa bezbednošću & PowerShell centra za usaglašavanje](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps). 

Ako koristite MFA, pogledajte odeljak [Povezivanje sa programom Microsoft 365 security & PowerShell centra za usaglašavanje pomoću višefaktora potvrde identiteta](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps). 
