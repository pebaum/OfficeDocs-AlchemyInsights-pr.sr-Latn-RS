---
title: Promena zahteva jaku lozinku
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: 53affd2a347c004e7b21b353c2b3df98bc30a585
ms.sourcegitcommit: a7e5ca472000dfec471950bafd12eee8d7144f74
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 07/16/2019
ms.locfileid: "35701597"
---
# <a name="change-strong-password-requirement"></a>Promena zahteva jaku lozinku

Jake lozinke su potrebne po podrazumevanoj vrednosti. 

Koristeći PowerShell možete onemogućiti jakih lozinki za određene korisnike sa ovom komandom:<br>
*Set-MsolUser – UserPrincipalName <UserPrincipalName> – StrongPasswordRequired $false*

- [Više informacija o smernice za lozinke](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [Kako da se povežete sa O365 sa PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [Više informacija na PowerShell MsolUser komande](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)