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
# <a name="fix-delivery-issues-for-error-code-550-541-relay-access-denied"></a>Popravljanje problema sa isporukom za kôd greške 550 5.4.1 prenos pristup odbijen

Do ovog problema dolazi prilikom [provere da li je e-adresa važeća da bi se sprečilo pokretanje](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-directory-based-edge-blocking) pri unosu Office 365 mreže. Pokušajte sledeće:

1. Utvrdite da li je problem specifičan za ceo domen ili jednu e-adresu:
    - Čitav domen: ponekad se domen mora sinhronizovati; Pokušajte da [podesite domen tako da bude interni, a zatim ponovo na pouzdane](https://docs.microsoft.com/exchange/mail-flow-best-practices/manage-accepted-domains/manage-accepted-domains).
    - Jedna e-adresa: ponekad se adresa mora sinhronizovati; Promena SMTP proxy adrese, a zatim njegovo promena može da pomogne.
2. Utvrdite da li je problem specifičan za grupu ili javnu fasciklu. Za neke tipove objekata, objekti će možda morati da se ručno kreiraju u Azure aktivnom direktorijumu.

Ako vam je potrebna dodatna pomoć, otvorite tiket za podršku i odredite opseg problema ("includ" tip objekta koji šaljete) da bismo vam mogli bolje pomoći.