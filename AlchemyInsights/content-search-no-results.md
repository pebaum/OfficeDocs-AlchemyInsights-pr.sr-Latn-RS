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
# <a name="no-results-from-content-searchexports"></a>Nema rezultata iz sadržaja pretraživanja/izvoz

Problemi sa sadržaja pretraživanja/izvoz ne vraća nikakve podatke možda zbog određenih usklađenosti bezbednosti "Filter" koji je podešavanje određenih Admin i ne komuniciraju to da svi Admini.

Da biste rešili ovo, proverite da li postoje filtere bezbednosti usklađenosti koji može biti uzrok ovome:
1. Povezivanje sa sigurnosti i usklađenosti centar Powershell
2. Pokrenite commandlets na sledeći način:
<br>$org = „yourdomain.com”
<br>Po-ComplianceSecurityFilter-organizacija $org