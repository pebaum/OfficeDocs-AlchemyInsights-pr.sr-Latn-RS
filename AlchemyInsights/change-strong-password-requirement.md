---
title: Promeni jaku potrebu za lozinkom
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: a054735a0c139c90d76098297bb9984d37464d3b
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43706575"
---
# <a name="change-strong-password-requirement"></a>Promeni jaku potrebu za lozinkom

Microsoft zahteva jake lozinke po podrazumevanoj vrednosti. 

Pomoću programa PowerShell možete onemogućiti jake lozinke za određene korisnike pomoću ove komande:<br>
*Set-MsolUser – korisnički Principalname <UserPrincipalName> – obavezna $FALSE*

- [Više informacija o smernicama za lozinke](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [Kako se povezati sa programom Microsoft 365 sa programom PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [Više informacija o komandama PowerShell MsolUser](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)
