---
title: Kôd greške 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Ako dobijete grešku prilikom aktivacije Office 2013 na usluge udaljene radne površine (RDS) raspoređivanje, razmislite o omogućavanju ADAL uređivanjem registra.
ms.openlocfilehash: 4ef2943e5a529368fa2c614e4431cf180924fbb8
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36527055"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a>Greška prilikom aktiviranja Office 2013 na usluge udaljene radne površine

Ako dobijete grešku prilikom aktivacije Office 2013 na usluge udaljene radne površine (RDS) raspoređivanje, razmislite o omogućavanju ADAL uređivanjem registra.
  
|**Ključ registratora**|**Tip**|**Vrednost**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL  <br/> |REG_DWORD  <br/> |1  <br/> |

Za više informacija, pogledajte [Omogući moderne potvrda identiteta za Office 2013 na uređajima Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).
  
> [!NOTE]
>  ADAL je podrazumevano omogućena u Office 365 ProPlus i Office 2016. Usluge udaljene radne površine (RDS) prethodno proglašena je usluga terminala.
  