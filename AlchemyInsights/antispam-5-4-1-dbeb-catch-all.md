---
title: AntiSpam 5.4.1-sve
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001209"
- "3167"
ms.openlocfilehash: 4f531a063d63aff239ef7dead869bb526e17fb35
ms.sourcegitcommit: 2591e1f56e8943bddb9d3b77ba5b494ac49d4f30
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/15/2019
ms.locfileid: "38672447"
---
# <a name="fix-delivery-issues-for-error-code-550-541-relay-access-denied"></a><span data-ttu-id="8bdc5-102">Popravljanje problema sa isporukom za kôd greške 550 5.4.1 prenos pristup odbijen</span><span class="sxs-lookup"><span data-stu-id="8bdc5-102">Fix delivery issues for error code 550 5.4.1 Relay Access Denied</span></span>

<span data-ttu-id="8bdc5-103">Do ovog problema dolazi prilikom [provere da li je e-adresa važeća da bi se sprečilo pokretanje](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-directory-based-edge-blocking) pri unosu Office 365 mreže.</span><span class="sxs-lookup"><span data-stu-id="8bdc5-103">This problem occurs when [checking to see if an email address is valid to prevent bouncebacks](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-directory-based-edge-blocking) when entering the Office 365 network.</span></span> <span data-ttu-id="8bdc5-104">Pokušajte sledeće:</span><span class="sxs-lookup"><span data-stu-id="8bdc5-104">Try the following:</span></span>

1. <span data-ttu-id="8bdc5-105">Utvrdite da li je problem specifičan za ceo domen ili jednu e-adresu:</span><span class="sxs-lookup"><span data-stu-id="8bdc5-105">Determine whether the problem is specific to an entire domain or a single email address:</span></span>
    - <span data-ttu-id="8bdc5-106">Čitav domen: ponekad se domen mora sinhronizovati; Pokušajte da [podesite domen tako da bude interni, a zatim ponovo na pouzdane](https://docs.microsoft.com/exchange/mail-flow-best-practices/manage-accepted-domains/manage-accepted-domains).</span><span class="sxs-lookup"><span data-stu-id="8bdc5-106">Entire domain: Sometimes the domain needs to be synchronized; try [setting the domain to Internal and then back to Authoritative](https://docs.microsoft.com/exchange/mail-flow-best-practices/manage-accepted-domains/manage-accepted-domains).</span></span>
    - <span data-ttu-id="8bdc5-107">Jedna e-adresa: ponekad se adresa mora sinhronizovati; Promena SMTP proxy adrese, a zatim njegovo promena može da pomogne.</span><span class="sxs-lookup"><span data-stu-id="8bdc5-107">Single email address: Sometimes the address needs to be synchronized; changing the smtp proxy address and then changing it back can help.</span></span>
2. <span data-ttu-id="8bdc5-108">Utvrdite da li je problem specifičan za grupu ili javnu fasciklu.</span><span class="sxs-lookup"><span data-stu-id="8bdc5-108">Determine whether the problem is specific to a group or public folder.</span></span> <span data-ttu-id="8bdc5-109">Za neke tipove objekata, objekti će možda morati da se ručno kreiraju u Azure aktivnom direktorijumu.</span><span class="sxs-lookup"><span data-stu-id="8bdc5-109">For some object types, the objects may need to be manually created in Azure Active Directory.</span></span>

<span data-ttu-id="8bdc5-110">Ako vam je potrebna dodatna pomoć, otvorite tiket za podršku i odredite opseg problema ("includ" tip objekta koji šaljete) da bismo vam mogli bolje pomoći.</span><span class="sxs-lookup"><span data-stu-id="8bdc5-110">If you need additional help, please open a support ticket and specify the scope of the issue (includidng the type of object you're sending to) so we can assist you better.</span></span>