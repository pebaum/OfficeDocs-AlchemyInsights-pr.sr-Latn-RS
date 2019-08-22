---
title: Promena zahteva jaku lozinku
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
ms.openlocfilehash: f8790a26ec7c5de57f5dbfc9e1c162767c599f03
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36518773"
---
# <a name="change-strong-password-requirement"></a>Promena zahteva jaku lozinku

Microsoft zahteva jake lozinke po podrazumevanoj vrednosti. 

Koristite PowerShell, možete da onemogućite jakih lozinki za određene korisnike sa ovom komandom:<br>
*Set-MsolUser – UserPrincipalName <UserPrincipalName> – StrongPasswordRequired $false*

- [Više informacija o smernice za lozinke](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [Kako da se povežete sa Office 365 sa PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [Više informacija na PowerShell MsolUser komande](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)