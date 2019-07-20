---
title: Nema rezultate pretrage sadržaja
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000661"
- "2527"
ms.openlocfilehash: 9f2c0273762f1a4a2b905487f461dc1d05db9209
ms.sourcegitcommit: 8f97342d8b46ab05f1e89018473caad9d35431df
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 07/19/2019
ms.locfileid: "35800570"
---
# <a name="no-results-from-content-searchexports"></a><span data-ttu-id="57658-102">Nema rezultata iz sadržaja pretraživanja/izvoz</span><span class="sxs-lookup"><span data-stu-id="57658-102">No results from Content Search/Exports</span></span>

<span data-ttu-id="57658-103">Problemi sa sadržaja pretraživanja/izvoz ne vraća nikakve podatke možda zbog određenih usklađenosti bezbednosti "Filter" koji je podešavanje određenih Admin i ne komuniciraju to da svi Admini.</span><span class="sxs-lookup"><span data-stu-id="57658-103">Issues with Content Search/Exports not returning any data may be due to certain Compliance Security Filter that was setup by a specific Admin and not communicating it to all Admins.</span></span>

<span data-ttu-id="57658-104">Da biste rešili ovo, proverite da li postoje filtere bezbednosti usklađenosti koji može biti uzrok ovome:</span><span class="sxs-lookup"><span data-stu-id="57658-104">To resolve this, check to see if there are any Compliance Security Filters that may be causing this:</span></span>
1. <span data-ttu-id="57658-105">Povezivanje sa sigurnosti i usklađenosti centar Powershell</span><span class="sxs-lookup"><span data-stu-id="57658-105">Connect to Security and Compliance Center Powershell</span></span>
2. <span data-ttu-id="57658-106">Pokrenite commandlets na sledeći način:</span><span class="sxs-lookup"><span data-stu-id="57658-106">Run the following commandlets:</span></span>
<br><span data-ttu-id="57658-107">$org = „yourdomain.com”</span><span class="sxs-lookup"><span data-stu-id="57658-107">$org = “yourdomain.com”</span></span>
<br><span data-ttu-id="57658-108">Po-ComplianceSecurityFilter-organizacija $org</span><span class="sxs-lookup"><span data-stu-id="57658-108">Get-ComplianceSecurityFilter -Organization $org</span></span>