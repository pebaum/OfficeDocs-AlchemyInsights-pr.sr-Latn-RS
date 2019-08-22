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
ms.openlocfilehash: 09cdbc3cb0465e0e0bc08872c49e283081ad3e92
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36516793"
---
# <a name="no-results-from-content-searchexports"></a>Nema rezultata iz sadržaja pretraživanja/izvoz

Problemi sa sadržaja pretraživanja/izvoz ne vraća nikakve podatke možda zbog određenih usklađenosti bezbednosti "Filter" koji je podešavanje određenih Admin i ne komuniciraju to da svi Admini.

Da biste rešili ovo, proverite da li postoje filtere bezbednosti usklađenosti koji može biti uzrok ovome:
1. Povezivanje sa sigurnosti i usklađenosti centar Powershell
2. Pokrenite commandlets na sledeći način:
<br>$org = „yourdomain.com”
<br>Po-ComplianceSecurityFilter-organizacija $org