---
title: 646 kako konfigurirati AADConnect
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 646
ms.assetid: 599698ac-6709-477a-a66f-169b3165064e
ms.openlocfilehash: 6cc4afb4b0f67fb76ecc7ff8f564b1cd36cc291c
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/22/2019
ms.locfileid: "30779525"
---
# <a name="configure-sync-features"></a>Podesite opcije sinhronizacije

Azurno AD povezivanje sadrži nekoliko funkcija koje su podrazumevano, ili to možete omogućiti kasnije. Neke funkcije zahtevaju dodatne konfiguracije u određenim sredinama.
  
- [Filtriranje](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) ograničenja objektima se sinhronizuju sa azurno AD. Podrazumevane, svi korisnici, kontakti, grupe i Windows 10 računara nalozi se sinhronizuju. Možete uključiti ili isključiti objekte na osnovu domeni, organizacione jedinice ili druge atribute. 
    
- [Lozinka hash sačekate](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) sinhronizuje lozinku hash iz lokalne aktivni direktorijum se azurno oglasa. Ovo omogućava upravljanje lozinkama na jednoj lokaciji, ali koristi istu lozinku u oba na više lokacija i zamagle okruženjima. Pošto je Active Directory autoritativnih izvora, možete da koristite polisa lozinku. 
    
- [Samouslužno gesla (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) omogućava korisnicima da poništi svoje lozinke u oblaku prilikom i dalje primene svoje lokalne smernice za lozinke. 
    
- [Writeback uređaj](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) dozvoljava registrirani uređaji u azurno AD za zapisivanje nazad aktivni direktorijum lokalne tako da može da se koristi za uslovnog pristupa. 
    
- [Sprečavanje slučajnog briše](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) se zadano sprečavanje brisanja previše istovremenih objekta (više od 500 objekata po sinhronizacije). Možete da promenite ovu postavku u susret potrebama vaše organizacije. 
    
- [Automatska nadogradnja](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) je zadano omogućen za Ekspresna instalacija i da se obezbedi tvoja verzija povezivanja Azure AD je uvek trenutni. 
    
