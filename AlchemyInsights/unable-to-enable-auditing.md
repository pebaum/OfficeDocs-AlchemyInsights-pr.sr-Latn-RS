---
title: 2419-ne može-to-nadgledanje-revizija
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 2419
ms.assetid: ''
ms.openlocfilehash: 23ad07a6dd943d61d1bd45453089a771cfd51b58
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44510442"
---
# <a name="unable-to-enable-unified-auditing"></a>Nije moguće omogućiti ujednačeni nadzor

Kada pokušate da omogućite ujednačeni nadzor za vašu organizaciju, možda ćete dobiti grešku sličnu sledećoj:

```
Request: /api/adminauditlogconfig/EnableUnifiedAuditLogIngestion Status code: 500 Exception message: {"Message":"The command you tried to run isn't currently allowed in your organization. To run this command, you first need to run the command: Enable-OrganizationCustomization."
```

Da biste riješili taj problem, slijedite ove korake:

1. [Poveži se sa Exchange online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell).

2. Pokrenite sljedeće cmdpusti:

   ```
   Enable-OrganizationCustomization
   ```

3. Sačekajte 60 minuta da bi prethodna postavka stupila na snagu.

4. Pokrenite sledeću komandu u Exchange online PowerShell:

   ```
   Set-AdminAuditLogConfig -UnifiedAuditLogIngestionEnabled $true
   ```

Dodatne informacije potražite u sledećim člancima:

- [Poveži se na Exchange online PowerShell koristeći višefaktoru provjeru autentičnosti](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/mfa-connect-to-exchange-online-powershell)

-  [Uključivanje ili isključivanje pretrage za evidenciju nadgledanja](https://docs.microsoft.com/microsoft-365/compliance/turn-audit-log-search-on-or-off)
