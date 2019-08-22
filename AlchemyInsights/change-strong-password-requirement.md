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
# <a name="change-strong-password-requirement"></a><span data-ttu-id="197b2-102">Promena zahteva jaku lozinku</span><span class="sxs-lookup"><span data-stu-id="197b2-102">Change strong password requirement</span></span>

<span data-ttu-id="197b2-103">Microsoft zahteva jake lozinke po podrazumevanoj vrednosti.</span><span class="sxs-lookup"><span data-stu-id="197b2-103">Microsoft requires strong passwords by default.</span></span> 

<span data-ttu-id="197b2-104">Koristite PowerShell, možete da onemogućite jakih lozinki za određene korisnike sa ovom komandom:</span><span class="sxs-lookup"><span data-stu-id="197b2-104">Using PowerShell, you can disable strong passwords for specific users with this command:</span></span><br>
<span data-ttu-id="197b2-105">*Set-MsolUser – UserPrincipalName <UserPrincipalName> – StrongPasswordRequired $false*</span><span class="sxs-lookup"><span data-stu-id="197b2-105">*Set-MsolUser –UserPrincipalName <UserPrincipalName> –StrongPasswordRequired  $false*</span></span>

- [<span data-ttu-id="197b2-106">Više informacija o smernice za lozinke</span><span class="sxs-lookup"><span data-stu-id="197b2-106">More information on password policy</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [<span data-ttu-id="197b2-107">Kako da se povežete sa Office 365 sa PowerShell</span><span class="sxs-lookup"><span data-stu-id="197b2-107">How to connect to Office 365 with PowerShell</span></span>](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [<span data-ttu-id="197b2-108">Više informacija na PowerShell MsolUser komande</span><span class="sxs-lookup"><span data-stu-id="197b2-108">More information on PowerShell MsolUser commands</span></span>](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)