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
ms.openlocfilehash: 9f4a175239bc20aaf489615da63ef35002030a70
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/28/2019
ms.locfileid: "35369679"
---
# <a name="retention-policies-in-exchange-admin-center"></a><span data-ttu-id="cc301-102">Smernice za zadržavanje u Exchange Admin Center</span><span class="sxs-lookup"><span data-stu-id="cc301-102">Retention Policies in Exchange Admin Center</span></span>

 <span data-ttu-id="cc301-103">**Pitanje:** Novokreiranim ili ažurirani Restriktivne smernice u centru za Admin Exchange ne zatvarate sa poštanskim sandučićima ili stavke nisu se preselio u poštansko sanduče na arhive ili izbrisane.</span><span class="sxs-lookup"><span data-stu-id="cc301-103">**Issue:** Newly created or updated retention policies in the Exchange Admin Center are not applying to mailboxes or items are not moved to the archive mailbox or deleted.</span></span> 
  
 <span data-ttu-id="cc301-104">**Osnovni uzroci:**</span><span class="sxs-lookup"><span data-stu-id="cc301-104">**Root Causes:**</span></span>
  
- <span data-ttu-id="cc301-105">Ovo možda za **Upravlja pomoćnik fascikla** još nije obrađen u korisnikovom poštanskom sandučetu.</span><span class="sxs-lookup"><span data-stu-id="cc301-105">This may be because the **Managed Folder Assistant** has not processed the user's mailbox.</span></span> <span data-ttu-id="cc301-106">Upravlja pomoćnika za fascikle pokuša da obradi svaki poštansko sanduče u vašoj organizaciji zasnovano na jednom svakih sedam dana.</span><span class="sxs-lookup"><span data-stu-id="cc301-106">The Managed Folder Assistant tries to process every mailbox in your cloud-based organization once every seven days.</span></span> <span data-ttu-id="cc301-107">Ako promenite oznaku zadržavanja ili primenite različite zadržavanja politiku sa poštanskim sandučetom, možete sačekati na uspeo fasciklu pomagati obrađuje poštansko sanduče, ili možete pokrenuti cmdlet na Start-ManagedFolderAssistant početi uspeo pomoćnika za fascikle za obradu sa određenim poštansko sanduče.</span><span class="sxs-lookup"><span data-stu-id="cc301-107">If you change a retention tag or apply a different retention policy to a mailbox, you can wait until the Managed Folder Assist processes the mailbox, or you can run the Start-ManagedFolderAssistant cmdlet to start the Managed Folder Assistant to process a specific mailbox.</span></span> <span data-ttu-id="cc301-108">Voditi ovaj cmdlet je korisno za testiranje ili rešavanje problema zadržavanja smernice ili postavke oznaka zadržavanja.</span><span class="sxs-lookup"><span data-stu-id="cc301-108">Running this cmdlet is useful for testing or troubleshooting a retention policy or retention tag settings.</span></span> <span data-ttu-id="cc301-109">Za više informacija posjetite [pokrenuti uspeo pomoćnika za fascikle](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).</span><span class="sxs-lookup"><span data-stu-id="cc301-109">For more information, visit [Run the Managed Folder Assistant](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).</span></span>
    
  - <span data-ttu-id="cc301-110">**Rešenje:** Pokrenite sledeću komandu početi uspeo pomoćnika za fascikle za određeni poštansko sanduče:</span><span class="sxs-lookup"><span data-stu-id="cc301-110">**Solution:** Run the following command to start the Managed Folder Assistant for a specific mailbox:</span></span>
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

- <span data-ttu-id="cc301-111">Ovo može se pojaviti i ako **RetentionHold** je bilo **omogućeno** na poštanskom sandučetu.</span><span class="sxs-lookup"><span data-stu-id="cc301-111">This may also be occur if **RetentionHold** has been **enabled** on the mailbox.</span></span> <span data-ttu-id="cc301-112">Ako poštansko sanduče je smještena na neki RetentionHold, smernice za zadržavanje na poštansko sanduče neće biti obrađen u tom periodu.</span><span class="sxs-lookup"><span data-stu-id="cc301-112">If the mailbox has been placed on a RetentionHold, the retention policy on the mailbox will not be processed during that time.</span></span> <span data-ttu-id="cc301-113">Za više informacije na RetentionHold pogledajte postavku: [Poštansko sanduče zadržavanja držite](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).</span><span class="sxs-lookup"><span data-stu-id="cc301-113">For more informaton on the RetentionHold setting see: [Mailbox Retention Hold](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).</span></span>
    
    <span data-ttu-id="cc301-114">**Rešenje:**</span><span class="sxs-lookup"><span data-stu-id="cc301-114">**Solution:**</span></span>
    
  - <span data-ttu-id="cc301-115">Provjerite status postavku "RetentionHold" na određenim poštanskim sandučetom u [EXO powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):</span><span class="sxs-lookup"><span data-stu-id="cc301-115">Check the status of the RetentionHold setting on the specific mailbox in [EXO powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):</span></span>
    
  ```
  Get-Mailbox -Identity <name of the mailbox> |fl *retentionHold*
  ```

  - <span data-ttu-id="cc301-116">Pokrenite sljedeću naredbu da **biste onemogućili** RetentionHold na određene poštansko sanduče:</span><span class="sxs-lookup"><span data-stu-id="cc301-116">Run the following command to **disable** RetentionHold on a specific mailbox:</span></span>
    
  ```
  Set-Mailbox -RetentionHoldEnabled $false
  ```

  - <span data-ttu-id="cc301-117">Sada, ponovo pokrenuti fasciklu upravljanog pomoćnika:</span><span class="sxs-lookup"><span data-stu-id="cc301-117">Now, re-run the Managed folder Assistant:</span></span>
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

 <span data-ttu-id="cc301-118">**Napomena:** Ako poštansko sanduče je manja od 10 MB, uspeo pomoćnika za fascikle neće automatski obraditi poštansko sanduče.</span><span class="sxs-lookup"><span data-stu-id="cc301-118">**Note:** If a mailbox is smaller than 10 MB, the Managed Folder Assistant will not automatically process the mailbox.</span></span>
  