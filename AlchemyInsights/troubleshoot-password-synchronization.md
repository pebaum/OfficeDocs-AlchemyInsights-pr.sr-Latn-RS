---
title: Rešavanje problema sa sinhronizacijom lozinke
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "579"
- "1300006"
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: edd4f68466296f72c2dc0bafda45e6749d62d942
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43732524"
---
# <a name="troubleshoot-password-synchronization"></a>Rešavanje problema sa sinhronizacijom lozinke

Da biste rešili probleme na koje nema sinhronizovanih lozinki sa 1.1.614.0 ili novijim verzijama za Connect Azure:
  
1. Otvorite novu sesiju Windows PowerShell na serveru za povezivanje Azure oglasa sa opcijom " **Pokreni kao administrator** ".

2. Pokretanje **Set-izvršne smernice RemoteSigned** ili **Set-izvršne smernice neograničeno**.

3. Pokrenite čarobnjak za povezivanje "Azure AD".

4. Krećite se do stranice sa **dodatnim zadacima** , izaberite **Rešavanje problema**, a zatim kliknite na dugme **dalje**.

5. Na stranici rešavanje problema kliknite na dugme **Pokreni da biste pokrenuli meni rešavanje problema** u programu PowerShell.

6. U glavnom meniju izaberite stavku **Rešavanje problema pri sinhronizaciji lozinke**.

7. U podmeniju izaberite stavku " **Sinhronizacija lozinke" ne radi uopšte**.

**Razumevanje rezultata zadatka "Rešavanje problema"**
  
Zadatak rešavanja problema izvršava sledeće čekove:
  
- Proverava valjanost funkcije za sinhronizaciju lozinke za vaš Azure oglas.

- Proverava valjanost servera za povezivanje Azure oglasa nije u režimu za postavljanje.

- Za svaku postojeću liniju spajanja aktivnog direktorijuma (koja odgovara postojećoj šumi aktivnog direktorijuma):

- 
  - Proverava valjanost funkcije za sinhronizaciju lozinke.

  - Pretražuje događaje u sinhronizaciji lozinke u evidencijama događaja Windows aplikacije.

  - Za svaki domen aktivnog direktorijuma u okviru konektora aktivnog direktorijuma na prostoru:

  - Proverava valjanost domena koji se može pristupiti sa servera za povezivanje Azure oglasa.

  - Proverava valjanost naloga za usluge domena aktivnog direktorijuma (AD DS) koje koristi linija spajanja aktivnog direktorijuma na prostoru ima ispravno korisničko ime, lozinku i dozvole potrebne za sinhronizaciju lozinke.

Više pomoći za rešavanje problema sa lozinkom sinhronizacija potražite [u članku rešavanje problema sa sinhronizacijom lozinke pomoću programa AZURE AD Connect Sync](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).
  