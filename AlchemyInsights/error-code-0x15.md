---
title: Kôd greške 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Ako dobijete grešku prilikom aktivacije Office 2013 na usluge udaljene radne površine (RDS) raspoređivanje, razmislite o omogućavanju ADAL uređivanjem registra.
ms.openlocfilehash: 6d4076ecb5c6ee3c3cf4c4610ad4aa29ab477d8a
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29929103"
---
Ako dobijete grešku prilikom aktivacije Office 2013 na usluge udaljene radne površine (RDS) raspoređivanje, razmislite o omogućavanju ADAL uređivanjem registra. 
  
|**Ključ registratora**|**Ukucajte **|**Vrednost**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL  <br/> |REG_DWORD  <br/> |1  <br/> |
   
Za više informacija, pogledajte [Omogući moderne potvrda identiteta za Office 2013 na uređajima Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).
  
> [!NOTE]
>  ADAL je podrazumevano omogućena u Office 365 ProPlus i Office 2016. > usluge udaljene radne površine (RDS) prethodno proglašena je usluga terminala. 
  

