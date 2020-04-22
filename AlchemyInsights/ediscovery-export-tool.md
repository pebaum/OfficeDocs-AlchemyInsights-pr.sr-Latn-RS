---
title: eDiscovery za izvoz
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "263"
- "928"
- "1100001"
- "3100022"
ms.assetid: b16d310d-1134-4959-be68-d1c0ad463930
ms.openlocfilehash: 83f18d06006989e03ee6095e430aaf3eb5c72c09
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43714784"
---
# <a name="cant-install-or-run-the-ediscovery-export-tool"></a>Nije moguće instalirati ili pokrenuti alatku eDiscovery EXPORT?

Ako ne možete da instalirate ili pokrenete alatku za izvoz eDiscovery da biste preuzeli rezultate pretrage, proverite sledeće stvari:
  
- Računar koji koristite zadovoljava ove preduslove:

  - 32-ili 64-bitne verzije operativnog sistema Windows 7 i novije verzije

  - Microsoft .NET Framework 4,7

  - Podržani pregledač:

  - Microsoft Edge

    Ili

  - Internet Explorer 10 i novije verzije

    Drugi pregledači, kao što su Google Chrome i Mozilla Firefox, nisu podržani.

- Vaša organizacija može da se poveže sa krajnje tačke u programu Azure, što je ** \*. BLOB.Core.Windows.net** (džoker znak predstavlja Jedinstveni identifikator za posao izvoza).

- Vi ste dodelili ulogu izvoza u Microsoft 365 centru za usaglašenost &amp; bezbednosti. Podrazumeva se da je ova uloga dodeljena samo grupi uloga menadžera eDiscovery. Pogledajte odeljak [dodeljivanje eDiscovery dozvola](https://docs.microsoft.com/office365/securitycompliance/assign-ediscovery-permissions).

Više informacija potražite u članku [izvoz rezultata pretrage sadržaja](https://docs.microsoft.com/office365/securitycompliance/export-search-results).
  