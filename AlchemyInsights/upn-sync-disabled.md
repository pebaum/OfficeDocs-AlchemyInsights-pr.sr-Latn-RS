---
title: UPN sinhronizacija onemogućena
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 2a3489fe-c2a8-4e43-96c2-be4b3c5e978c
ms.openlocfilehash: d00f10688ec775c22d60a9089e291c265ada46f1
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/15/2019
ms.locfileid: "28310400"
---
# <a name="upn-sync-disabled"></a>UPN sinhronizacija onemogućena

Ako ste pokrenuli sinhronizovanje da azurno AD pre 30. marta 2016, pokrenite sledeću Azure AD PowerShell cmdlet da biste omogućili UPN meke odgovara vašoj organizaciji samo:
  
 **Set-MsolDirSyncFeature-karakteristika EnableSoftMatchOnUpn-omogući $True**
  
UPN meke poklapa se automatski uključuje za organizacije koja je počela da se sinhronizuje sa azurno AD ili posle 30. marta 2016..
  
Da biste saznali više o omogućavanju meke meč na UPN i druge funkcije sinhronizacije, pogledajte [Azure AD povezivanje opcije usluge za sinhronizaciju](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).
  

