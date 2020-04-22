---
title: Kôd greške 0x15
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Ako dobijate grešku prilikom aktiviranja sistema Office 2013 u vezi sa raspoređivanje usluga udaljene radne površine (RDS), razmislite o omogućavanju ADAL uređivanjem registratora.
ms.openlocfilehash: 566d63cbe37d295b3546b9d7d5b14dfc8e8fe0ec
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703152"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a>Greška tokom aktivacije sistema Office 2013 u uslugama udaljene radne površine

Ako dobijate grešku prilikom aktiviranja sistema Office 2013 u vezi sa raspoređivanje usluga udaljene radne površine (RDS), razmislite o omogućavanju ADAL uređivanjem registratora.
  
|**Ključ registratora**|**Tip**|**Vrednost**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER \Software\microsoft\office\15.0\česta \Identity\enabpotencijalnog Al  <br/> |REG_DWORD  <br/> |1  <br/> |

Više informacija potražite u članku [Omogućavanje moderne potvrde identiteta za Office 2013 na Windows uređajima](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).
  
> [!NOTE]
>  ADAL je po podrazumevanoj vrednosti omogućen u Microsoft 365 aplikacijama za Enterprise i Office 2016. Usluge udaljene radne površine (RDS) prethodno su imenovane usluge terminala.
  