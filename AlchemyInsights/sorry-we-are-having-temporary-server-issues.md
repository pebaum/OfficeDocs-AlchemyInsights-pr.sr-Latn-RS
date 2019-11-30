---
title: Popravljanje Office aplikacija Žao nam je, imamo poruke o privremenom serveru
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3420"
- "9001430"
ms.openlocfilehash: 4b90f843843416408d7f3091325fe436dc3ec9df
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/27/2019
ms.locfileid: "39628004"
---
# <a name="fixing-the-office-apps-sorry-we-are-having-temporary-server-issues-message"></a>Popravljanje Office aplikacija "Oprostite, imamo poruku o privremenim problemima na serveru"

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