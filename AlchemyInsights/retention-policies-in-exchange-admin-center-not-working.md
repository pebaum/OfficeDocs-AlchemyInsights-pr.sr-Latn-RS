---
title: Smernice za zadržavanje u Exchange Admin centar ne radi
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: a48fd5fd-4af7-4d5f-b617-b0f9334ccaa7
ms.openlocfilehash: c9061fa728edaab6575a7b1027783e56739a6d14
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29935006"
---
# <a name="retention-policies-in-exchange-admin-center"></a><span data-ttu-id="6866e-102">Smernice za zadržavanje u Exchange Admin Center</span><span class="sxs-lookup"><span data-stu-id="6866e-102">Retention Policies in Exchange Admin Center</span></span>

 <span data-ttu-id="6866e-103">**Pitanje:** Novokreiranim ili ažurirani Restriktivne smernice u centru za Admin Exchange ne zatvarate sa poštanskim sandučićima ili stavke nisu se preselio u poštansko sanduče na arhive ili izbrisane.</span><span class="sxs-lookup"><span data-stu-id="6866e-103">**Issue:** Newly created or updated retention policies in the Exchange Admin Center are not applying to mailboxes or items are not moved to the archive mailbox or deleted.</span></span> 
  
 <span data-ttu-id="6866e-104">**Osnovni uzroci:**</span><span class="sxs-lookup"><span data-stu-id="6866e-104">**Root Causes:**</span></span>
  
- <span data-ttu-id="6866e-p101">Ovo možda za **Upravlja pomoćnik fascikla** još nije obrađen u korisnikovom poštanskom sandučetu. Upravlja pomoćnika za fascikle pokuša da obradi svaki poštansko sanduče u vašoj organizaciji zasnovano na jednom svakih sedam dana. Ako promenite oznaku zadržavanja ili primenite različite zadržavanja politiku sa poštanskim sandučetom, možete sačekati na uspeo fasciklu pomagati obrađuje poštansko sanduče, ili možete pokrenuti cmdlet na Start-ManagedFolderAssistant početi uspeo pomoćnika za fascikle za obradu sa određenim poštansko sanduče. Voditi ovaj cmdlet je korisno za testiranje ili rešavanje problema zadržavanja smernice ili postavke oznaka zadržavanja. Za više informacija posjetite [pokrenuti uspeo pomoćnika za fascikle](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).</span><span class="sxs-lookup"><span data-stu-id="6866e-p101">This may be because the **Managed Folder Assistant** has not processed the user's mailbox. The Managed Folder Assistant tries to process every mailbox in your cloud-based organization once every seven days. If you change a retention tag or apply a different retention policy to a mailbox, you can wait until the Managed Folder Assist processes the mailbox, or you can run the Start-ManagedFolderAssistant cmdlet to start the Managed Folder Assistant to process a specific mailbox. Running this cmdlet is useful for testing or troubleshooting a retention policy or retention tag settings. For more information, visit [Run the Managed Folder Assistant](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).</span></span>
    
  - <span data-ttu-id="6866e-110">**Rešenje:** Pokrenite sledeću komandu početi uspeo pomoćnika za fascikle za određeni poštansko sanduče:</span><span class="sxs-lookup"><span data-stu-id="6866e-110">**Solution:** Run the following command to start the Managed Folder Assistant for a specific mailbox:</span></span> 
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

- <span data-ttu-id="6866e-p102">Ovo može se pojaviti i ako **RetentionHold** je bilo **omogućeno** na poštanskom sandučetu. Ako poštansko sanduče je smještena na neki RetentionHold, smernice za zadržavanje na poštansko sanduče neće biti obrađen u tom periodu. Za više informacije na RetentionHold pogledajte postavku: [Poštansko sanduče zadržavanja držite](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).</span><span class="sxs-lookup"><span data-stu-id="6866e-p102">This may also be occur if **RetentionHold** has been **enabled** on the mailbox. If the mailbox has been placed on a RetentionHold, the retention policy on the mailbox will not be processed during that time. For more informaton on the RetentionHold setting see: [Mailbox Retention Hold](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).</span></span>
    
    <span data-ttu-id="6866e-114">**Rešenje:**</span><span class="sxs-lookup"><span data-stu-id="6866e-114">**Solution:**</span></span>
    
  - <span data-ttu-id="6866e-115">Provjerite status postavku "RetentionHold" na određenim poštanskim sandučetom u [EXO powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):</span><span class="sxs-lookup"><span data-stu-id="6866e-115">Check the status of the RetentionHold setting on the specific mailbox in [EXO powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):</span></span>
    
  ```
  Get-Mailbox -Identity <name of the mailbox> |fl *retentionHold*
  ```

  - <span data-ttu-id="6866e-116">Pokrenite sljedeću naredbu da **biste onemogućili** RetentionHold na određene poštansko sanduče:</span><span class="sxs-lookup"><span data-stu-id="6866e-116">Run the following command to **disable** RetentionHold on a specific mailbox:</span></span> 
    
  ```
  Set-Mailbox -RetentionHoldEnabled $false
  ```

  - <span data-ttu-id="6866e-117">Sada, ponovo pokrenuti fasciklu upravljanog pomoćnika:</span><span class="sxs-lookup"><span data-stu-id="6866e-117">Now, re-run the Managed folder Assistant:</span></span>
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

 <span data-ttu-id="6866e-118">**Napomena:** Ako poštansko sanduče je manja od 10 MB, uspeo pomoćnika za fascikle neće automatski obraditi poštansko sanduče.</span><span class="sxs-lookup"><span data-stu-id="6866e-118">**Note:** If a mailbox is smaller than 10 MB, the Managed Folder Assistant will not automatically process the mailbox.</span></span> 
  

