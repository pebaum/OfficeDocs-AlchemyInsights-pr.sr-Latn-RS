---
title: Rešavanje problema sa greškama protok potvrda identiteta
ms.author: kaarins
author: kaarins
ms.date: 6/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: c15fed9f-65c6-422e-9d32-87e889a44b51
ms.openlocfilehash: e578149e37c86178b98cf6073f6ed6325f42c455
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29941090"
---
# <a name="troubleshoot-flow-authentication-errors"></a><span data-ttu-id="baeff-102">Rešavanje problema sa greškama protok potvrda identiteta</span><span class="sxs-lookup"><span data-stu-id="baeff-102">Troubleshoot Flow authentication errors</span></span>

<span data-ttu-id="baeff-p101">U mnogim slučajevima, tokova propasti zbog greške u potvrdi identiteta. Ako imate ovaj tip greške, poruka o grešci sadrži „Unauthorized” ili kôd greške 401 ili 403 se pojavljuje. Obično, mogu da popravim greške u potvrdi identiteta tako što ćete ažurirati vezu:</span><span class="sxs-lookup"><span data-stu-id="baeff-p101">In many cases, flows fail because of an authentication error. If you have this type of error, the error message contains "Unauthorized," or an error code of 401 or 403 appears. You can usually fix an authentication error by updating the connection:</span></span>
  
1. <span data-ttu-id="baeff-106">Na vrhu web portala, kliknite na dugme ili tapnite na ikonu opremu za otvaranje menija "Postavke", a zatim kliknite ili dodirnite **veze**.</span><span class="sxs-lookup"><span data-stu-id="baeff-106">At the top of the web portal, click or tap the gear icon to open the Settings menu, and then click or tap **Connections**.</span></span>
    
2. <span data-ttu-id="baeff-107">Pomerite se vezu za koju si video poruku o grešci nedozvoljeno.</span><span class="sxs-lookup"><span data-stu-id="baeff-107">Scroll to the connection for which you saw the Unauthorized error message.</span></span>
    
3. <span data-ttu-id="baeff-108">Pored veze, kliknite ili dodirnite vezu u poruci o vezi nije bio verodostojnost **Verifikujte lozinku** .</span><span class="sxs-lookup"><span data-stu-id="baeff-108">Next to the connection, click or tap the **Verify password** link in the message about the connection not being authenticated.</span></span> 
    
4. <span data-ttu-id="baeff-109">Provjerite vaše akreditive prateći uputstva koja se pojavljuju se vratiti na tvoju propast protok vode, i zatim izaberite stavku ili Tapnite da **prosledite**.</span><span class="sxs-lookup"><span data-stu-id="baeff-109">Verify your credentials by following the instructions that appear, return to your flow-run failure, and then click or tap **Resubmit**.</span></span>
    
<span data-ttu-id="baeff-110">Dodatnu pomoć potražite u [rešavanju problema tok](https://go.microsoft.com/fwlink/?linkid=872110).</span><span class="sxs-lookup"><span data-stu-id="baeff-110">For more help, see [Troubleshooting a flow](https://go.microsoft.com/fwlink/?linkid=872110).</span></span>
  

