---
title: 646 kako konfigurisati AADConnect
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "646"
- "1300023"
ms.assetid: 599698ac-6709-477a-a66f-169b3165064e
ms.openlocfilehash: 713cda26e55f07f0438cb9ebe5aa9da86c4ebb3a
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43722577"
---
# <a name="configure-sync-features"></a>Konfigurisanje funkcija sinhronizacije

Azure Connect AD sadrži nekoliko funkcija koje su podrazumevano omogućene ili koje možete da omogućite kasnije. Neke funkcije zahtevaju dodatnu konfiguraciju u određenim okruženjima.

- [Filtriranje](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) ograničenja objekti se sinhronizuju sa Azure oglasima. Podrazumevano je da se svi korisnici, kontakti, grupe i Windows 10 računarski nalozi sinhronizuju. Objekte možete da uključite ili izuzmete na osnovu domena, ili drugih atributa.

- [Sinhronizacija hash sinhronizacije](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) sinhronizuje hash lozinku iz aktivnog direktorijuma na "AZURE" a.d.. Ovo omogućava upravljanje lozinkom na jednoj lokaciji, ali koristi istu lozinku i u okruženjima i u informatičkom oblaku. Pošto je aktivni direktorijum ovlašćeni izvor, možete da koristite sopstvene smernice za lozinke.

- [Uspostavljanje početne vrednosti lozinke za samouslugu (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) omogućava korisnicima da resetuje sopstvene lozinke u informatičkom oblaku dok i dalje primenjuje vaše smernice za lozinku.

- Zapisivanje [uređaja](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) dozvoljava da registrovani uređaji u Azure oglasnom programu budu napisani nazad u aktivni direktorijum na tom prostoru kako bi mogli da se koriste za uslovno pristupanje.

- [Sprečavanje nehotičnog](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) brisanja je podrazumevano omogućeno da bi se sprečilo da se spreči previše istovremenih brisanja objekata (više od 500 objekata po sinhronizaciji). Ovu postavku možete da promenite da bi zadovoljili potrebe vaše organizacije.

- [Automatsko nadograđivanje](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) je podrazumevano omogućeno za ekspresne instalacije i pomaže vam da se uverite da je vaša verzija programa Azure AD Connect uvek aktuelna.
