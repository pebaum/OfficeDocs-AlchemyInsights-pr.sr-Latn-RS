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
ms.openlocfilehash: 84e3a7700558ad8a5fad5b7ded6354fe8736e0f7
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/27/2019
ms.locfileid: "39628256"
---
# <a name="fixing-the-office-apps-we-are-unable-to-connect-right-now-message"></a>Popravljanje Office aplikacija "ne možemo odmah da se povežemo" poruka

Ako dobijete ovu poruku, pokušajte sledeće:

1. Proverite zaštitni zid, antivirusni softver i proxy postavke da biste potvrdili da ne blokiraju pristup internetu u Office aplikacijama. Pogledajte [Office 365 URL adrese i OPSEGE IP adresa](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).

2. Idite na **početni ekran** > **** i otkucajte **usluge. msc**. Uverite se da su sve pokrenute sledeće usluge:
    - Automatsko podešavanje uređaja povezanih sa mrežom
    - Usluga liste mreža
    - Svest o mrežnoj lokaciji
    - Windows evidencija događaja

Ako neka od ovih usluga nije pokrenuta, pokušajte da ga pokrenete. Ako imate problem sa pokretanjem usluge, pokrenite sledeću komandu tako što ćete otvoriti komandnu liniju sa punim dozvolama:

**Sfc/scannow**

Nakon završetka ove komande, ponovo pokrenite računar.

Detaljnije informacije potražite u članku ["Nažalost, ne možemo da se povežemo sa vašim nalogom. Pokušajte ponovo kasnije "Greška prilikom aktiviranja sistema Office sa verzije Office 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).