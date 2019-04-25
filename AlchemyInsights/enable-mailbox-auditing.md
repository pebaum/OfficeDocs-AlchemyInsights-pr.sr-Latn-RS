---
title: Omogućite nadgledanje poštansko sanduče
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 81041685cf383a231a9a9739d6daffd6039b4602
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32403761"
---
# <a name="enable-mailbox-auditing"></a><span data-ttu-id="609e1-102">Omogućite nadgledanje poštansko sanduče</span><span class="sxs-lookup"><span data-stu-id="609e1-102">Enable mailbox auditing</span></span>

<span data-ttu-id="609e1-103">Da biste omogućili nadzor poštanskog sandučeta za jednog korisnika ili za celu organizaciju sledeće cmdlets mora pokretati sa Remote Shell napajanja:</span><span class="sxs-lookup"><span data-stu-id="609e1-103">To enable Mailbox Auditing for either a single user or an entire organization the following cmdlets must be run from Remote Power Shell:</span></span>
  
 <span data-ttu-id="609e1-104">**Jedan korisnik**</span><span class="sxs-lookup"><span data-stu-id="609e1-104">**Single User**</span></span>
  
<span data-ttu-id="609e1-105">Setu-poštansko sanduče - identitet „Jane Dow” - AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="609e1-105">Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
  
 <span data-ttu-id="609e1-106">**Organizacija**</span><span class="sxs-lookup"><span data-stu-id="609e1-106">**Organization**</span></span>
  
<span data-ttu-id="609e1-107">Uzmi-poštansko sanduče - ResultSize neograničen - filtriranje {„UserMailbox” RecipientTypeDetails - eq} | Setu-poštansko sanduče - AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="609e1-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>
  
[<span data-ttu-id="609e1-108">uči više</span><span class="sxs-lookup"><span data-stu-id="609e1-108">Learn more</span></span>](https://support.office.com/article/aaca8987-5b62-458b-9882-c28476a66918)
  

