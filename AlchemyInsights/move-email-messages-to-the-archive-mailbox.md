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
<span data-ttu-id="d25c0-p101">Arhiviranje stavki u poštansko sanduče arhive problema. Samo se pobrini da izvršite ove korake:</span><span class="sxs-lookup"><span data-stu-id="d25c0-p101">Having problems archiving items to the Archive mailbox. Make sure you have performed the following steps:</span></span>
  
1. <span data-ttu-id="d25c0-p102">Potvrdi da je **arhiviranje poštansko sanduče** je omogućeno. U suprotnom, koristite korake u [ovom članku](https://docs.microsoft.com/en-us/office365/securitycompliance/enable-archive-mailboxes) da biste omogućili poštansko sanduče arhive.</span><span class="sxs-lookup"><span data-stu-id="d25c0-p102">Confirm that an **Archive mailbox** has been enabled. If not, use steps in [this article](https://docs.microsoft.com/en-us/office365/securitycompliance/enable-archive-mailboxes) to enable the archive mailbox.</span></span> 
    
2. <span data-ttu-id="d25c0-106">U centru za Admin Exchange, izaberite **Zadržavanja oznake** pod **Upravom usklađenosti**, kreirajte **oznake zadržavanja** uz radnju **premestite u arhivu** koja sadrži željenu **Zadržavanja godinama**.</span><span class="sxs-lookup"><span data-stu-id="d25c0-106">In the Exchange Admin Center, select **Retention Tags** under **Compliance Management**, create a **Retention tag** with the **Move to Archive** action containing the desired **Retention Age**.</span></span>
    
3. <span data-ttu-id="d25c0-107">U centru za Admin Exchange, izaberite **Smernice za zadržavanje**, kreiranje **Smernica za čuvanje** i dodajte oznaku za zadržavanje u **premestite u arhivu** te politike.</span><span class="sxs-lookup"><span data-stu-id="d25c0-107">In the Exchange Admin Center, select **Retention Policies**, create a **Retention Policy** and add your **Move to Archive** retention tag to that policy.</span></span> 
    
4. <span data-ttu-id="d25c0-p103">[Dodelite smernice za zadržavanje](https://docs.microsoft.com/en-us/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) određene korisnikovom poštanskom sandučetu. Istu politiku će primeniti i na **primarnom** i poštansko sanduče na **arhive** .</span><span class="sxs-lookup"><span data-stu-id="d25c0-p103">[Assign the Retention Policy](https://docs.microsoft.com/en-us/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) to the specific user's mailbox. The same policy will be applied to both the **Primary** and the **Archive** mailbox.</span></span> 
    
<span data-ttu-id="d25c0-p104">Korisnikovom poštanskom sandučetu sada bi trebalo da smernice za arhiviranje da premestite stavke u poštanskom sandučetu arhive. To može biti neophodno da prisili uspeo fasciklu pomoćnika (MFA) da biste pokrenuli i primeni nove postavke na korisnikovom poštanskom sandučetu. Pokrenite sljedeću naredbu dok je [povezan sa EXO PowerShell](https://docs.microsoft.com/en-us/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) početi uspeo pomoćnika za fascikle za određeni poštansko sanduče:</span><span class="sxs-lookup"><span data-stu-id="d25c0-p104">The user's mailbox should now have an Archive policy to move items to the Archive mailbox. It may be necessary to force the Managed Folder Assistant (MFA) to run and apply the new settings to the user's mailbox. Run the following command while [connected to EXO PowerShell](https://docs.microsoft.com/en-us/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) to start the Managed Folder Assistant for a specific mailbox:</span></span> 
  
```
Start-ManagedFolderAssistant -Identity <name of the mailbox>
```

<span data-ttu-id="d25c0-113">Više informacija o podešavanju smernice za arhiviranje, vidim [Podešavanje smernice za arhiviranje i brisanje za Poštanske sandučiće](https://docs.microsoft.com/en-us/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span><span class="sxs-lookup"><span data-stu-id="d25c0-113">Want more information on setting up an archive policy, see [Set up an archive and deletion policy for mailboxes](https://docs.microsoft.com/en-us/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span></span>
  

