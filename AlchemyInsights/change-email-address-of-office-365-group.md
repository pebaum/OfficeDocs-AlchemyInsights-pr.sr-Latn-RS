---
title: Promena e-adrese Microsoft 365 grupe
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "4704"
ms.openlocfilehash: 0a07e6279f533a4c26a4e90c10651421a5df8860
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/27/2020
ms.locfileid: "44283259"
---
# <a name="change-email-address-of-an-microsoft-365-group"></a><span data-ttu-id="02807-102">Promena e-adrese Microsoft 365 grupe</span><span class="sxs-lookup"><span data-stu-id="02807-102">Change email address of an Microsoft 365 group</span></span>

<span data-ttu-id="02807-103">E-adresu Microsoft 365 grupe možete da promenite pomoću administratorskog centra.</span><span class="sxs-lookup"><span data-stu-id="02807-103">You can change the email address of an Microsoft 365 group by using the admin center.</span></span> <span data-ttu-id="02807-104">Samo izaberite grupu i izaberite @edit e-adresu.</span><span class="sxs-lookup"><span data-stu-id="02807-104">Just select the group and select @edit email address.</span></span>

<span data-ttu-id="02807-105">Takođe možete koristiti sledeću komandu "EXO PowerShell" da biste promenili primarnu SMTP adresu Microsoft 365 grupe:</span><span class="sxs-lookup"><span data-stu-id="02807-105">You can also use following the EXO PowerShell command to change the primary SMTP address of an Microsoft 365 group:</span></span>

<span data-ttu-id="02807-106">Set-UnifiedGroup <Group Name> -PrimarySmtpAddress<new SMTP Address></span><span class="sxs-lookup"><span data-stu-id="02807-106">Set-UnifiedGroup <Group Name> -PrimarySmtpAddress <new SMTP Address></span></span>

<span data-ttu-id="02807-107">Primer:</span><span class="sxs-lookup"><span data-stu-id="02807-107">Example:</span></span>

```
    Set-UnifiedGroup Marketing -PrimarySmtpAddress marketing@contoso.com
```
