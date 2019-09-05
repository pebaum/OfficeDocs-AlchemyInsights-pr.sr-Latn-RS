---
title: Omogućavanje nadgledanja poštanskog sandučeta
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
ms.openlocfilehash: 73517f46935a67a4a8a3e4770090ac897fe67979
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/04/2019
ms.locfileid: "36736267"
---
# <a name="enable-mailbox-auditing"></a><span data-ttu-id="67995-102">Omogućavanje nadgledanja poštanskog sandučeta</span><span class="sxs-lookup"><span data-stu-id="67995-102">Enable mailbox auditing</span></span>

<span data-ttu-id="67995-103">Da biste omogućili nadzor poštanskog sandučeta za jednog korisnika ili čitavu organizaciju, sledeće cmdlet se moraju pokretati iz udaljene ljuske napajanja:</span><span class="sxs-lookup"><span data-stu-id="67995-103">To enable Mailbox Auditing for either a single user or an entire organization the following cmdlets must be run from Remote Power Shell:</span></span>
  
 <span data-ttu-id="67995-104">**Jedan korisnik**</span><span class="sxs-lookup"><span data-stu-id="67995-104">**Single User**</span></span>
  
<span data-ttu-id="67995-105">Set-poštansko sanduče-identitet "Jane Dau"-AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="67995-105">Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
  
 <span data-ttu-id="67995-106">**Organizacija**</span><span class="sxs-lookup"><span data-stu-id="67995-106">**Organization**</span></span>
  
<span data-ttu-id="67995-107">Preuzimanje-poštansko sanduče-veličina rezultata neograničenog-filter {RecipientTypeDetails-sa "Userpoštansko sanduče"} | Set-poštansko sanduče-AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="67995-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>
  
[<span data-ttu-id="67995-108">uči više</span><span class="sxs-lookup"><span data-stu-id="67995-108">Learn more</span></span>](https://docs.microsoft.com/office365/securitycompliance/enable-mailbox-auditing)
  

