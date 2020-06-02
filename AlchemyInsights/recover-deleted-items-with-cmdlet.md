---
title: Spasi izbrisane stavke u cmddozvoli
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1800008"
- "5718"
ms.openlocfilehash: 86744d92a44096991079d1da3bdf4e95e58c55b7
ms.sourcegitcommit: 2afad0b107d03cd8c4de0b85b5bee38a13a7960d
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/26/2020
ms.locfileid: "44493431"
---
# <a name="recover-deleted-items-with-cmdlet"></a><span data-ttu-id="ca722-102">Spasi izbrisane stavke u cmddozvoli</span><span class="sxs-lookup"><span data-stu-id="ca722-102">Recover deleted items with cmdlet</span></span>

- <span data-ttu-id="ca722-103">Koristite [stavku "Preuzmi](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps) i ponovo oporavak" cmddozvoli prikaz izbrisanih stavki u poštanskim sandučićima.</span><span class="sxs-lookup"><span data-stu-id="ca722-103">Use the [Get-RecoverableItems](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps) cmdlet to view deleted items in mailboxes.</span></span> <span data-ttu-id="ca722-104">Nakon što pronađete izbrisane stavke, za vraćanje u prethodno stanje koristite [nepovratno stavke za oporavak](https://docs.microsoft.com/powershell/module/exchange/Restore-RecoverableItems?view=exchange-ps) .</span><span class="sxs-lookup"><span data-stu-id="ca722-104">After you find the deleted items, you use the [Restore-RecoverableItems](https://docs.microsoft.com/powershell/module/exchange/Restore-RecoverableItems?view=exchange-ps) cmdlet to restore them.</span></span>

- <span data-ttu-id="ca722-105">Pogledajte sve detalje u okviru [stavke "Get-oporavak](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps)".</span><span class="sxs-lookup"><span data-stu-id="ca722-105">See full details in [Get-RecoverableItems](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps).</span></span>

- <span data-ttu-id="ca722-106">Treba da budete dodeljeni ulozi izvoza za poštansko sanduče da biste mogli da pokrenete ovu cmddozvoli.</span><span class="sxs-lookup"><span data-stu-id="ca722-106">You need to be assigned the Mailbox Import Export role before you can run this cmdlet.</span></span> <span data-ttu-id="ca722-107">Za više informacija pogledajte [stavke za oporavak](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps) .</span><span class="sxs-lookup"><span data-stu-id="ca722-107">Please see [Get-RecoverableItems](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps) for more information.</span></span>
