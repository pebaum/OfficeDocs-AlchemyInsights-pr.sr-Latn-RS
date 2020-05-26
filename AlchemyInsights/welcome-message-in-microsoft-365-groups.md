---
title: Poruka dobrodošlice u Microsoft 365 grupama
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
- "5685"
ms.openlocfilehash: d82931ae6978a09e674b00640d1dd413bcce7cfd
ms.sourcegitcommit: b196100759b29aecd62b693a2bfedbbd25a697c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/19/2020
ms.locfileid: "44358338"
---
# <a name="welcome-message-in-microsoft-365-groups"></a><span data-ttu-id="9b6f8-102">Poruka dobrodošlice u Microsoft 365 grupama</span><span class="sxs-lookup"><span data-stu-id="9b6f8-102">Welcome message in Microsoft 365 Groups</span></span>

<span data-ttu-id="9b6f8-103">Novi korisnici koji se pridružuju Microsoft 365 grupi dobiće e-poruku dobrodošlice ako je svojstvo "UnifiedGroupWelcomeMessageEnabled" tačno.</span><span class="sxs-lookup"><span data-stu-id="9b6f8-103">New users joining Microsoft 365 group will receive welcome email if the "UnifiedGroupWelcomeMessageEnabled" property is True.</span></span>

<span data-ttu-id="9b6f8-104">U slučaju da želite da onemogućite poruku dobrodošlice, koristite sledeću komandu " [Exo PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps) ":</span><span class="sxs-lookup"><span data-stu-id="9b6f8-104">In case you want to disable the welcome message, use the following [EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps) command:</span></span>

`
Set-UnifiedGroup <groupname> -UnifiedGroupWelcomeMessageEnabled:$False
`
