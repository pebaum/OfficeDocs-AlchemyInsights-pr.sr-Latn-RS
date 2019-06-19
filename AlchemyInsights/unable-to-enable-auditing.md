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
# <a name="unable-to-enable-unified-auditing"></a><span data-ttu-id="30edd-102">Ne može da omogući jedinstven nadzor</span><span class="sxs-lookup"><span data-stu-id="30edd-102">Unable to enable unified auditing</span></span>

<span data-ttu-id="30edd-103">Kada pokušate da omogućite jedinstvenog nadgledanje za vašu organizaciju za Office 365, slične greške možete dobiti na sledeći način:</span><span class="sxs-lookup"><span data-stu-id="30edd-103">When you try to enable unified auditing for your Office 365 organization, you may receive an error similar the following:</span></span>

```
Request: /api/adminauditlogconfig/EnableUnifiedAuditLogIngestion Status code: 500 Exception message: {"Message":"The command you tried to run isn't currently allowed in your organization. To run this command, you first need to run the command: Enable-OrganizationCustomization."
```

<span data-ttu-id="30edd-104">Da biste riješili taj problem, slijedite ove korake:</span><span class="sxs-lookup"><span data-stu-id="30edd-104">To resolve this issue, follow these steps:</span></span>

1. <span data-ttu-id="30edd-105">Da [biste se povezali sa Exchange Online Powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell).</span><span class="sxs-lookup"><span data-stu-id="30edd-105">[Connect to Exchange Online Powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell).</span></span>

2. <span data-ttu-id="30edd-106">Pokrenite cmdlet na sledeći način:</span><span class="sxs-lookup"><span data-stu-id="30edd-106">Run the following cmdlet:</span></span>

   ```
   Enable-OrganizationCustomization
   ```

3. <span data-ttu-id="30edd-107">Čekaj 60 minuta za prethodnu postavku da bi stupio na snagu.</span><span class="sxs-lookup"><span data-stu-id="30edd-107">Wait for 60 minutes for the previous setting to take effect.</span></span>

4. <span data-ttu-id="30edd-108">Pokrenite sledeću komandu u Exchange Online PowerShell:</span><span class="sxs-lookup"><span data-stu-id="30edd-108">Run the following command in Exchange Online PowerShell:</span></span>

   ```
   Set-AdminAuditLogConfig -UnifiedAuditLogIngestionEnabled $true
   ```

<span data-ttu-id="30edd-109">Dodatne informacije potražite u sljedećim člancima:</span><span class="sxs-lookup"><span data-stu-id="30edd-109">For additional information, see the following articles:</span></span>

- [<span data-ttu-id="30edd-110">Povezivanje sa Exchange Online PowerShell koristeći višestruku potvrdu identiteta</span><span class="sxs-lookup"><span data-stu-id="30edd-110">Connect to Exchange Online PowerShell using multi-factor authentication</span></span>](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/mfa-connect-to-exchange-online-powershell)

-  [<span data-ttu-id="30edd-111">Pretraživanje evidencije nadgledanja Office 365 da uključite ili isključite</span><span class="sxs-lookup"><span data-stu-id="30edd-111">Turn Office 365 audit log search on or off</span></span>](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off)
