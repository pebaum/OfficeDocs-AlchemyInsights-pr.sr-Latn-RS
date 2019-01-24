---
title: Smernice za zadržavanje u Exchange Admin centar ne radi
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: a48fd5fd-4af7-4d5f-b617-b0f9334ccaa7
ms.openlocfilehash: 0ceb1737040f0304bfe8b611241ce1deef487652
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/24/2019
ms.locfileid: "29487893"
---
 **Pitanje:** Novokreiranim ili ažurirani Restriktivne smernice u centru za Admin Exchange ne zatvarate sa poštanskim sandučićima ili stavke nisu se preselio u poštansko sanduče na arhive ili izbrisane. 
  
 **Osnovni uzroci:**
  
- Ovo možda za **Upravlja pomoćnik fascikla** još nije obrađen u korisnikovom poštanskom sandučetu. Upravlja pomoćnika za fascikle pokuša da obradi svaki poštansko sanduče u vašoj organizaciji zasnovano na jednom svakih sedam dana. Ako promenite oznaku zadržavanja ili primenite različite zadržavanja politiku sa poštanskim sandučetom, možete sačekati na uspeo fasciklu pomagati obrađuje poštansko sanduče, ili možete pokrenuti cmdlet na Start-ManagedFolderAssistant početi uspeo pomoćnika za fascikle za obradu sa određenim poštansko sanduče. Voditi ovaj cmdlet je korisno za testiranje ili rešavanje problema zadržavanja smernice ili postavke oznaka zadržavanja. Za više informacija posjetite [pokrenuti uspeo pomoćnika za fascikle](https://msdn.microsoft.com/en-us/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).
    
  - **Rešenje:** Pokrenite sledeću komandu početi uspeo pomoćnika za fascikle za određeni poštansko sanduče: 
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

- Ovo može se pojaviti i ako **RetentionHold** je bilo **omogućeno** na poštanskom sandučetu. Ako poštansko sanduče je smještena na neki RetentionHold, smernice za zadržavanje na poštansko sanduče neće biti obrađen u tom periodu. Za više informacije na RetentionHold pogledajte postavku: [Poštansko sanduče zadržavanja držite](https://docs.microsoft.com/en-us/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).
    
    **Rešenje:**
    
  - Provjerite status postavku "RetentionHold" na određenim poštanskim sandučetom u [EXO powershell](https://docs.microsoft.com/en-us/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):
    
  ```
  Get-Mailbox -Identity <name of the mailbox> |fl *retentionHold*
  ```

  - Pokrenite sljedeću naredbu da **biste onemogućili** RetentionHold na određene poštansko sanduče: 
    
  ```
  Set-Mailbox -RetentionHoldEnabled $false
  ```

  - Sada, ponovo pokrenuti fasciklu upravljanog pomoćnika:
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

 **Napomena:** Ako poštansko sanduče je manja od 10 MB, uspeo pomoćnika za fascikle neće automatski obraditi poštansko sanduče. 
  

