---
title: Pitanje aktivacije-ne možemo odmah da se povežemo
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3408"
- "9001423"
ms.openlocfilehash: 56accf68f2cf41dbe6119281b74e2cb56b702789
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716186"
---
# <a name="fixing-the-office-apps-we-are-unable-to-connect-right-now-message"></a>Popravljanje Office aplikacija "ne možemo odmah da se povežemo" poruka

Ako dobijete ovu poruku, pokušajte sledeće:

1. Proverite zaštitni zid, antivirusni softver i proxy postavke da biste potvrdili da ne blokiraju pristup internetu u Office aplikacijama. Pogledajte [Microsoft URL adrese i OPSEGE IP adresa](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).

2. Idite na **početni ekran** > **Run**i otkucajte **usluge. msc**. Uverite se da su sve pokrenute sledeće usluge:
    - Automatsko podešavanje uređaja povezanih sa mrežom
    - Usluga liste mreža
    - Svest o mrežnoj lokaciji
    - Windows evidencija događaja

Ako neka od ovih usluga nije pokrenuta, pokušajte da ga pokrenete. Ako imate problem sa pokretanjem usluge, pokrenite sledeću komandu tako što ćete otvoriti komandnu liniju sa punim dozvolama:

**Sfc/scannow**

Nakon završetka ove komande, ponovo pokrenite računar.

Detaljnije informacije potražite u članku ["Nažalost, ne možemo da se povežemo sa vašim nalogom. Pokušajte ponovo kasnije "greška kada aktivirate Office sa Microsoft 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).