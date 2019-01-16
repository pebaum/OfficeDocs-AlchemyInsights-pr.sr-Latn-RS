---
title: Premestite poruke e-pošte u poštansko sanduče arhive
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: 41d6825b568263fb7b09066b65235aa348415bae
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/15/2019
ms.locfileid: "28310405"
---
Arhiviranje stavki u poštansko sanduče arhive problema. Samo se pobrini da izvršite ove korake:
  
1. Potvrdi da je **arhiviranje poštansko sanduče** je omogućeno. U suprotnom, koristite korake u [ovom članku](https://docs.microsoft.com/en-us/office365/securitycompliance/enable-archive-mailboxes) da biste omogućili poštansko sanduče arhive. 
    
2. U centru za Admin Exchange, izaberite **Zadržavanja oznake** pod **Upravom usklađenosti**, kreirajte **oznake zadržavanja** uz radnju **premestite u arhivu** koja sadrži željenu **Zadržavanja godinama**.
    
3. U centru za Admin Exchange, izaberite **Smernice za zadržavanje**, kreiranje **Smernica za čuvanje** i dodajte oznaku za zadržavanje u **premestite u arhivu** te politike. 
    
4. [Dodelite smernice za zadržavanje](https://docs.microsoft.com/en-us/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) određene korisnikovom poštanskom sandučetu. Istu politiku će primeniti i na **primarnom** i poštansko sanduče na **arhive** . 
    
Korisnikovom poštanskom sandučetu sada bi trebalo da smernice za arhiviranje da premestite stavke u poštanskom sandučetu arhive. To može biti neophodno da prisili uspeo fasciklu pomoćnika (MFA) da biste pokrenuli i primeni nove postavke na korisnikovom poštanskom sandučetu. Pokrenite sljedeću naredbu dok je [povezan sa EXO PowerShell](https://docs.microsoft.com/en-us/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) početi uspeo pomoćnika za fascikle za određeni poštansko sanduče: 
  
```
Start-ManagedFolderAssistant -Identity <name of the mailbox>
```

Više informacija o podešavanju smernice za arhiviranje, vidim [Podešavanje smernice za arhiviranje i brisanje za Poštanske sandučiće](https://docs.microsoft.com/en-us/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).
  

