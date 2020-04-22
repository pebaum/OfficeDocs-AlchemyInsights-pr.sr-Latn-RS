---
title: Rešavanje problema sa greškama u potvrdi o toku
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: c15fed9f-65c6-422e-9d32-87e889a44b51
ms.openlocfilehash: 70451f074a65a4454faeadd188a31783be8e6c7e
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43759742"
---
# <a name="troubleshoot-flow-authentication-errors"></a><span data-ttu-id="1f16d-102">Rešavanje problema sa greškama u potvrdi o toku</span><span class="sxs-lookup"><span data-stu-id="1f16d-102">Troubleshoot Flow authentication errors</span></span>

<span data-ttu-id="1f16d-103">U mnogim slučajevima, tokovi nisu uspešni zbog greške u potvrdi identiteta.</span><span class="sxs-lookup"><span data-stu-id="1f16d-103">In many cases, flows fail because of an authentication error.</span></span> <span data-ttu-id="1f16d-104">Ako imate ovakav tip greške, poruka o grešci sadrži "neovlašćena" ili kôd greške 401 ili 403 se pojavljuje.</span><span class="sxs-lookup"><span data-stu-id="1f16d-104">If you have this type of error, the error message contains "Unauthorized," or an error code of 401 or 403 appears.</span></span> <span data-ttu-id="1f16d-105">Grešku u potvrdi identiteta obično možete popraviti tako što ćete ažurirati vezu:</span><span class="sxs-lookup"><span data-stu-id="1f16d-105">You can usually fix an authentication error by updating the connection:</span></span>
  
1. <span data-ttu-id="1f16d-106">Na vrhu Web portala kliknite ili dodirnite ikonu "oprema" da biste otvorili meni "Postavke", a zatim kliknite ili dodirnite **veze**.</span><span class="sxs-lookup"><span data-stu-id="1f16d-106">At the top of the web portal, click or tap the gear icon to open the Settings menu, and then click or tap **Connections**.</span></span>
    
2. <span data-ttu-id="1f16d-107">Pomerite se do veze za koju ste videli neovlašćenu poruku o grešci.</span><span class="sxs-lookup"><span data-stu-id="1f16d-107">Scroll to the connection for which you saw the Unauthorized error message.</span></span>
    
3. <span data-ttu-id="1f16d-108">Pored veze, kliknite ili dodirnite vezu **Verifikuj lozinku** u poruci o vezi koja nije potvrđena.</span><span class="sxs-lookup"><span data-stu-id="1f16d-108">Next to the connection, click or tap the **Verify password** link in the message about the connection not being authenticated.</span></span> 
    
4. <span data-ttu-id="1f16d-109">Proverite svoje akreditive prateći uputstva koja se pojavljuju, vratite se na neuspjeh u toku, a zatim kliknite ili dodirnite dugme za **ponovno**pokretanje.</span><span class="sxs-lookup"><span data-stu-id="1f16d-109">Verify your credentials by following the instructions that appear, return to your flow-run failure, and then click or tap **Resubmit**.</span></span>
    
<span data-ttu-id="1f16d-110">Više pomoći potražite u članku [Rešavanje problema toka](https://go.microsoft.com/fwlink/?linkid=872110).</span><span class="sxs-lookup"><span data-stu-id="1f16d-110">For more help, see [Troubleshooting a flow](https://go.microsoft.com/fwlink/?linkid=872110).</span></span>
  

