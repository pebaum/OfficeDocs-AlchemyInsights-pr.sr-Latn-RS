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
ms.openlocfilehash: 6352603a391ddcb44d2728c7587bf15a6cd97ebb
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507184"
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

- Vaša organizacija može da se poveže sa krajnje tačke u programu Azure, što je ** \* . BLOB.Core.Windows.net** (džoker znak predstavlja Jedinstveni identifikator za posao izvoza).

- Vi ste dodelili ulogu izvoza u Microsoft 365 &amp; centru za usaglašenost bezbednosti. Podrazumeva se da je ova uloga dodeljena samo grupi uloga menadžera eDiscovery. Pogledajte odeljak [dodeljivanje eDiscovery dozvola](https://docs.microsoft.com/microsoft-365/compliance/assign-ediscovery-permissions).

Više informacija potražite u članku [izvoz rezultata pretrage sadržaja](https://docs.microsoft.com/microsoft-365/compliance/export-search-results).
  