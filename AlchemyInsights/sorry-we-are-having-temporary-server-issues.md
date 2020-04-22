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
ms.openlocfilehash: a1ac62f3587e318d563cfea1df8db23b720358a6
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43764131"
---
# <a name="fixing-the-office-apps-sorry-we-are-having-temporary-server-issues-message"></a>Popravljanje Office aplikacija "Oprostite, imamo poruku o privremenim problemima na serveru"

Ako dobijete ovu poruku, pokušajte sledeće:

1. Proverite zaštitni zid, antivirusni softver i proxy postavke da biste potvrdili da ne blokiraju pristup internetu u Office aplikacijama. Pogledajte [URL adrese i OPSEGE IP adresa](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).

2. Idite na **početni ekran** > **Run**i otkucajte **usluge. msc**. Uverite se da su sve pokrenute sledeće usluge:
    - Automatsko podešavanje uređaja povezanih sa mrežom
    - Usluga liste mreža
    - Svest o mrežnoj lokaciji
    - Windows evidencija događaja

Ako neka od ovih usluga nije pokrenuta, pokušajte da ga pokrenete. Ako imate problem sa pokretanjem usluge, pokrenite sledeću komandu tako što ćete otvoriti komandnu liniju sa punim dozvolama:

**Sfc/scannow**

Nakon završetka ove komande, ponovo pokrenite računar.

Detaljnije informacije potražite u članku ["Nažalost, ne možemo da se povežemo sa vašim nalogom. Pokušajte ponovo kasnije "Greška prilikom aktiviranja](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).