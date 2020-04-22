---
title: UPN sinhronizacija onemogućena
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
ms.assetid: 2a3489fe-c2a8-4e43-96c2-be4b3c5e978c
ms.openlocfilehash: 33bc7e30d41ff70e2ce55d946202acf45dbcb0f2
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43726118"
---
# <a name="upn-sync-disabled"></a>UPN sinhronizacija onemogućena

Ako ste počeli sa sinhronizacijom na Azure oglas pre 30. marta, 2016, pokrenite sledeću Azure reklamu PowerShell cmddozvoli da omogući UPN Soft podudaranje samo za vašu organizaciju:
  
 **Set-Msoldirencfunkcija-funkcija Enablesoftpodudaronupn-omogućavanje $True**
  
UPN Soft podudaranje se automatski uključuje za organizacije koje su počele da se sinhronizuju sa Azure oglasnom Adom na ili posle 30 marta 2016.
  
Da biste saznali više o omogućavanju blagog podudaranja na UPN i drugim funkcijama sinhronizacije, pogledajte [funkcije za usluge za sinhronizaciju sa servisnim servisom](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).
  

