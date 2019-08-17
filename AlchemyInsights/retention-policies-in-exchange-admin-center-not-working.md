---
title: Smernice za zadržavanje u Exchange Admin centar ne radi
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "308"
- "3100007"
ms.assetid: a48fd5fd-4af7-4d5f-b617-b0f9334ccaa7
ms.openlocfilehash: d0af4c933f262fe1ec4c2a6ff16d5f6195398b0d
ms.sourcegitcommit: e98443a049108e0dc83d63895af66944bdb1f108
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/16/2019
ms.locfileid: "36444822"
---
# <a name="retention-policies-in-exchange-admin-center"></a>Smernice za zadržavanje u Exchange Admin Center

 **Pitanje:** Novokreiranim ili ažurirani Restriktivne smernice u centru za Admin Exchange ne zatvarate sa poštanskim sandučićima ili stavke nisu se preselio u poštansko sanduče na arhive ili izbrisane. 
  
 **Osnovni uzroci:**
  
- Ovo možda za **Upravlja pomoćnik fascikla** još nije obrađen u korisnikovom poštanskom sandučetu. Upravlja pomoćnika za fascikle pokuša da obradi svaki poštansko sanduče u vašoj organizaciji zasnovano na jednom svakih sedam dana. Ako promenite oznaku zadržavanja ili primenite različite zadržavanja politiku sa poštanskim sandučetom, možete sačekati na uspeo fasciklu pomagati obrađuje poštansko sanduče, ili možete pokrenuti cmdlet na Start-ManagedFolderAssistant početi uspeo pomoćnika za fascikle za obradu sa određenim poštansko sanduče. Voditi ovaj cmdlet je korisno za testiranje ili rešavanje problema zadržavanja smernice ili postavke oznaka zadržavanja. Za više informacija posjetite [pokrenuti uspeo pomoćnika za fascikle](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).
    
  - **Rešenje:** Pokrenite sledeću komandu početi uspeo pomoćnika za fascikle za određeni poštansko sanduče:
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

- Ovo može se pojaviti i ako **RetentionHold** je bilo **omogućeno** na poštanskom sandučetu. Ako poštansko sanduče je smještena na neki RetentionHold, smernice za zadržavanje na poštansko sanduče neće biti obrađen u tom periodu. Za više informacije na RetentionHold pogledajte postavku: [Poštansko sanduče zadržavanja držite](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).
    
    **Rešenje:**
    
  - Provjerite status postavku "RetentionHold" na određenim poštanskim sandučetom u [EXO powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):
    
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
 
Za više informacija o restriktivnim smernicama u centru za Admin Exchange, pogledajte:
- [Oznake zadržavanja i smernice za zadržavanje](https://docs.microsoft.com/en-us/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies)
- [Primeni politiku zadržavanja na Poštanske sandučiće](https://docs.microsoft.com/en-us/exchange/security-and-compliance/messaging-records-management/apply-retention-policy)
- [Dodavanje ili uklanjanje oznaka zadržavanja](https://docs.microsoft.com/en-us/exchange/security-and-compliance/messaging-records-management/add-or-remove-retention-tags)
- [Kako se određuju tip drži stavljen na poštanskom sandučiću](https://docs.microsoft.com/en-us/office365/securitycompliance/identify-a-hold-on-an-exchange-online-mailbox)
