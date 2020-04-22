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
# <a name="enable-mailbox-auditing"></a>Omogućavanje nadgledanja poštanskog sandučeta

Da biste omogućili nadzor poštanskog sandučeta za jednog korisnika ili čitavu organizaciju, sledeće cmdlet se moraju pokretati iz udaljene ljuske napajanja:
  
 **Jedan korisnik**
  
Set-poštansko sanduče-identitet "Jane Dau"-AuditEnabled $true
  
 **Organizacija**
  
Preuzimanje-poštansko sanduče-veličina rezultata neograničenog-filter {RecipientTypeDetails-sa "Userpoštansko sanduče"} | Set-poštansko sanduče-AuditEnabled $true
  
[uči više](https://docs.microsoft.com/office365/securitycompliance/enable-mailbox-auditing)
  

