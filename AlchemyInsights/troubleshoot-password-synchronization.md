---
title: Rešavanje problema sa lozinkom sinhronizacije
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "579"
- "1300006"
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: 2b0a1527ab1b16f56a97891445a2dcb4570302f5
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36533821"
---
# <a name="troubleshoot-password-synchronization"></a>Rešavanje problema sa lozinkom sinhronizacije

Da biste rešili probleme gde nema lozinke koje su sinhronizovane sa Azure AD povezivanje verzija 1.1.614.0 ili novija:
  
1. Otvorite novu sesiju Windows PowerShell na vašem serveru Azure AD povezivanje koristeći opciju " **Pokreni kao Administrator** ".

2. Pokretanje **Set-ExecutionPolicy RemoteSigned** ili **Set-ExecutionPolicy bez nadzora**.

3. Pokrenite čarobnjak za povezivanje Azure AD.

4. Pronađite **Dodatne zadatke** stranicu, izaberite **rešavanje**i kliknite na dugme **dalje**.

5. Na stranici za rešavanje problema, u meniju **start rešavanja problema, lansiranje** u PowerShell.

6. U glavnog menija, izaberite opciju **Sinhronizacije rešavanje problema sa lozinkom**.

7. U podmeniju, izaberite **lozinku sinhronizacije ne radi na svim**.

**Razumeju rezultate za rešavanje problema zadatka**
  
Rešavanje problema zadatka obavlja sledeće čekove:
  
- Proverava da li funkcije sinhronizacije lozinku omogućen za Azure AD podstanara.

- Valjanost Azure AD povezivanje server nije u organizovanje režimu.

- Za svaku postojeću lokalne Active Directory connector (koji odgovara na postojeće Active Directory šume):

- 
  - Proverava da li je omogućena funkcija sinhronizacije lozinku.

  - Traži lozinku sinhronizacije otkucaje srca događaja u evidencijama događaja Windows aplikacije.

  - Za svaku Active Directory domena ispod linije spajanja aktivnog direktorijuma na više lokacija:

  - Valjanost da domen je dostupan sa Azure AD povezivanje servera.

  - Valjanost da usluga domena aktivnog direktorijuma (AD DS) nalozi koje koriste lokalne Active Directory konektor ima ispravno korisničko ime, lozinku i dozvole potrebne za sinhronizaciju lozinku.

Za dodatnu pomoć u rešavanju problema sa lozinkom pri sinhronizaciji, vidim [rešavanje lozinku sinhronizacije sa Azure AD povezivanje sinhronizacije](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).
  