---
title: 2419-nije moguće-da-omogući-nadzor
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 2419
ms.assetid: ''
ms.openlocfilehash: 3af01c03711eed646f0009afb5bea685bc358196
ms.sourcegitcommit: 87153fec6f6468b57893abf4aac073ba4068e67b
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/19/2019
ms.locfileid: "35065697"
---
# <a name="unable-to-enable-unified-auditing"></a>Ne može da omogući jedinstven nadzor

Kada pokušate da omogućite jedinstvenog nadgledanje za vašu organizaciju za Office 365, slične greške možete dobiti na sledeći način:

```
Request: /api/adminauditlogconfig/EnableUnifiedAuditLogIngestion Status code: 500 Exception message: {"Message":"The command you tried to run isn't currently allowed in your organization. To run this command, you first need to run the command: Enable-OrganizationCustomization."
```

Da biste riješili taj problem, slijedite ove korake:

1. Da [biste se povezali sa Exchange Online Powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell).

2. Pokrenite cmdlet na sledeći način:

   ```
   Enable-OrganizationCustomization
   ```

3. Čekaj 60 minuta za prethodnu postavku da bi stupio na snagu.

4. Pokrenite sledeću komandu u Exchange Online PowerShell:

   ```
   Set-AdminAuditLogConfig -UnifiedAuditLogIngestionEnabled $true
   ```

Dodatne informacije potražite u sljedećim člancima:

- [Povezivanje sa Exchange Online PowerShell koristeći višestruku potvrdu identiteta](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/mfa-connect-to-exchange-online-powershell)

-  [Pretraživanje evidencije nadgledanja Office 365 da uključite ili isključite](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off)
