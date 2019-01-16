---
title: Omogućite nadgledanje poštansko sanduče
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: bd94ec10f9df2e72ec6e3d8552d2eb80212a9d78
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/15/2019
ms.locfileid: "28309244"
---
# <a name="enable-mailbox-auditing"></a><span data-ttu-id="3d5a9-102">Omogućite nadgledanje poštansko sanduče</span><span class="sxs-lookup"><span data-stu-id="3d5a9-102">Enable mailbox auditing</span></span>

<span data-ttu-id="3d5a9-103">Da biste omogućili nadzor poštanskog sandučeta za jednog korisnika ili za celu organizaciju sledeće cmdlets mora pokretati sa Remote Shell napajanja:</span><span class="sxs-lookup"><span data-stu-id="3d5a9-103">To enable Mailbox Auditing for either a single user or an entire organization the following cmdlets must be run from Remote Power Shell:</span></span>
  
 <span data-ttu-id="3d5a9-104">**Jedan korisnik**</span><span class="sxs-lookup"><span data-stu-id="3d5a9-104">**Single User**</span></span>
  
<span data-ttu-id="3d5a9-105">Setu-poštansko sanduče - identitet „Jane Dow” - AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="3d5a9-105">Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
  
 <span data-ttu-id="3d5a9-106">**Organizacija**</span><span class="sxs-lookup"><span data-stu-id="3d5a9-106">**Organization**</span></span>
  
<span data-ttu-id="3d5a9-107">Uzmi-poštansko sanduče - ResultSize neograničen - filtriranje {„UserMailbox” RecipientTypeDetails - eq} | Setu-poštansko sanduče - AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="3d5a9-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>
  
[<span data-ttu-id="3d5a9-108">Saznajte više</span><span class="sxs-lookup"><span data-stu-id="3d5a9-108">Learn more</span></span>](https://support.office.com/article/aaca8987-5b62-458b-9882-c28476a66918)
  

