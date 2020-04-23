---
title: 929. pravila prijemnog poštanskog sandučeta za Deflektna pravila
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "929"
- "1800021"
ms.assetid: 9733ef4e-db8d-4345-a072-c251480875a1
ms.openlocfilehash: 6b6e64c0332a579e8f6132b08f2f89b15eb4de27
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43724606"
---
# <a name="mail-flow-rules-also-known-as-transport-rules"></a><span data-ttu-id="bf7a9-102">Pravila za tok pošte (poznata i kao pravila prevoza)</span><span class="sxs-lookup"><span data-stu-id="bf7a9-102">Mail flow rules (also known as transport rules)</span></span>

- <span data-ttu-id="bf7a9-103">Opšti pregled pravila toka pošte: [pravila protoka pošte (pravila transporta) u programu Exchange online](https://technet.microsoft.com/library/jj919238.aspx)</span><span class="sxs-lookup"><span data-stu-id="bf7a9-103">General overview of mail flow rules: [Mail flow rules (transport rules) in Exchange Online](https://technet.microsoft.com/library/jj919238.aspx)</span></span>

- <span data-ttu-id="bf7a9-104">Podešavanje pravila toka pošte: [procedure pravila toka pošte u programu Exchange online](https://technet.microsoft.com/library/dn600436.aspx)</span><span class="sxs-lookup"><span data-stu-id="bf7a9-104">Setup mail flow rules: [Mail flow rule procedures in Exchange Online](https://technet.microsoft.com/library/dn600436.aspx)</span></span>

- <span data-ttu-id="bf7a9-105">Kreiraj, izmeni i Izbriši pravila toka pošte: [Upravljanje pravilima protoka pošte](https://technet.microsoft.com/library/jj657505.aspx)</span><span class="sxs-lookup"><span data-stu-id="bf7a9-105">Create, modify, and delete mail flow rules: [Manage mail flow rules](https://technet.microsoft.com/library/jj657505.aspx)</span></span>

<span data-ttu-id="bf7a9-106">Pravila za tok pošte možete da upravljate i u Exchange online PowerShell.</span><span class="sxs-lookup"><span data-stu-id="bf7a9-106">You can also manage mail flow rules in Exchange Online PowerShell.</span></span> <span data-ttu-id="bf7a9-107">Za više informacija pogledajte odeljak " [Dobijanje-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrule) " (prikaz), [novi-transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/new-transportrule) (Kreiraj), [Ukloni-Transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/remove-transportrule) (Delete), [Set-prevoznika](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/set-transportrule) (izmeni postojeće), [Onemogući-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/disable-transportrule) (Onemogući postojeće) i [Omogući-transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/enable-transportrule) (Omogući postojeće).</span><span class="sxs-lookup"><span data-stu-id="bf7a9-107">For more information, see [Get-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrule) (view), [New-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/new-transportrule) (create), [Remove-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/remove-transportrule) (delete), [Set-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/set-transportrule) (modify existing), [Disable-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/disable-transportrule) (disable existing), and [Enable-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/enable-transportrule) (enable existing).</span></span>

<span data-ttu-id="bf7a9-108">Dodatno pravilo toka pošte cmdlet: [get-TransportRuleAction](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportruleaction) (lista dostupnih radnji), [get-TransportRulePredicate](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrulepredicate) (Lista raspoloživih uslova i izuzetaka), [izvoz-TransportRuleCollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/export-transportrulecollection) (izvozne pravila) i [Uvoz-TransportRuleCollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/import-transportrulecollection) (pravila uvoza).</span><span class="sxs-lookup"><span data-stu-id="bf7a9-108">Additional mail flow rule cmdlets: [Get-TransportRuleAction](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportruleaction) (list available actions), [Get-TransportRulePredicate](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrulepredicate) (list available conditions and exceptions), [Export-TransportRuleCollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/export-transportrulecollection) (export rules), and [Import-TransportRuleCollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/import-transportrulecollection) (import rules).</span></span>
