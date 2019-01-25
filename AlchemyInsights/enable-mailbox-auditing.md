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
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/24/2019
ms.locfileid: "29500296"
---
# <a name="enable-mailbox-auditing"></a>Omogućite nadgledanje poštansko sanduče

Da biste omogućili nadzor poštanskog sandučeta za jednog korisnika ili za celu organizaciju sledeće cmdlets mora pokretati sa Remote Shell napajanja:
  
 **Jedan korisnik**
  
Setu-poštansko sanduče - identitet „Jane Dow” - AuditEnabled $true
  
 **Organizacija**
  
Uzmi-poštansko sanduče - ResultSize neograničen - filtriranje {„UserMailbox” RecipientTypeDetails - eq} | Setu-poštansko sanduče - AuditEnabled $true
  
Saznajte više
  

