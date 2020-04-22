---
title: Omogućavanje nadgledanja poštanskog sandučeta
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: ae11d6be0789a5662d202b85268480a3d42922c4
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703585"
---
# <a name="enable-mailbox-auditing"></a><span data-ttu-id="7f33a-102">Omogućavanje nadgledanja poštanskog sandučeta</span><span class="sxs-lookup"><span data-stu-id="7f33a-102">Enable mailbox auditing</span></span>

<span data-ttu-id="7f33a-103">Da biste omogućili nadzor poštanskog sandučeta za jednog korisnika ili čitavu organizaciju, sledeće cmdlet se moraju pokretati iz udaljene ljuske napajanja:</span><span class="sxs-lookup"><span data-stu-id="7f33a-103">To enable Mailbox Auditing for either a single user or an entire organization the following cmdlets must be run from Remote Power Shell:</span></span>
  
 <span data-ttu-id="7f33a-104">**Jedan korisnik**</span><span class="sxs-lookup"><span data-stu-id="7f33a-104">**Single User**</span></span>
  
<span data-ttu-id="7f33a-105">Set-poštansko sanduče-identitet "Jane Dau"-AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="7f33a-105">Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
  
 <span data-ttu-id="7f33a-106">**Organizacija**</span><span class="sxs-lookup"><span data-stu-id="7f33a-106">**Organization**</span></span>
  
<span data-ttu-id="7f33a-107">Preuzimanje-poštansko sanduče-veličina rezultata neograničenog-filter {RecipientTypeDetails-sa "Userpoštansko sanduče"} | Set-poštansko sanduče-AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="7f33a-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>
  
[<span data-ttu-id="7f33a-108">uči više</span><span class="sxs-lookup"><span data-stu-id="7f33a-108">Learn more</span></span>](https://docs.microsoft.com/office365/securitycompliance/enable-mailbox-auditing)
  

