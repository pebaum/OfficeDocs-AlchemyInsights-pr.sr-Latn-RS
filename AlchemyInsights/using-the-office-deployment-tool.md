---
title: Koristeći alatku za raspoređivanje Office
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "918"
- "2000022"
ms.assetid: 7ff7cc06-76d0-468f-bd66-3f2760750d04
ms.openlocfilehash: 998f914f38fa9d1925f7003e634d7f11550f47da
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/28/2019
ms.locfileid: "35365539"
---
# <a name="using-the-office-deployment-tool-odt"></a>Koristeći alatku za raspoređivanje Office (ODT)

Alat za raspoređivanje Office (ODT) se koristi za raspoređivanje Office 365 verzije sistema Office. Alatku za raspoređivanje Office (setup.exe) se pokreće iz komandne linije i koristi XML datoteku za konfiguraciju da biste utvrdili koje postavke da biste primenili prilikom primene Office.
  
1. Preuzmite najnoviju verziju programa Office alatke za raspoređivanje sa lokacije [Microsoft Download Center](http://go.microsoft.com/fwlink/p/?LinkID=626065).

2. [Alatka za prilagođavanje sistema Office (OCT)](https://config.office.com) koristite da biste izabrali željene opcije raspoređivanja i kreiranje XML datoteke za konfiguraciju. Izvoz datoteke za konfiguraciju i to lokalno na istoj fascikli gde se nalazi na setup.exe.

    **Napomena:** Office instalacije problemi se obično pojaviti termin da misconfigured ili malformatted datoteke za konfiguraciju. Da biste izbegli takvim pitanjima, preporučujemo da koristite alatku za prilagođavanje sistema Office da biste kreirali datoteku za konfiguraciju. Takođe, možete da uvezete postojeće datoteke za konfiguraciju u alatku za prilagođavanje sistema Office.

3. Iz komandnoj liniji, prebacite se na lokaciju gde se nalazi setup.exe i pokrenuti alatku za raspoređivanje Office u režimu za preuzimanje i navedite datoteku konfiguracije koju ste upravo sačuvali. U ovom primeru, konfiguracijska datoteka je koja se zove Configuration.xml:
    
  ```
  setup.exe /download Configuration.xml  
  ```

4. Pokrenite alatku za raspoređivanje Office u podesite režim i navedite datoteku za konfiguraciju.
    
  ```
  setup.exe /configure Configuration.xml
  ```

    **Napomena:** Ovaj korak morate pokrenuti sa klijentskog računara na kojem želite da instalirate Office i morate imati lokalne administratorske dozvole na taj kompjuter.

Da biste saznali više o korišćenju alatka za primenu Office za Office 365 ProPlus scenariji primene, pogledajte [Pregled Office alatke za primenu](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool). Za više detalja o tome kako se koristi alatka za prilagođavanje sistema Office, pogledajte [Pregled Office alatke za prilagođavanje](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).
