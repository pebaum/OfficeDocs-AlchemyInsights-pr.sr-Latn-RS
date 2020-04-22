---
title: Korišćenje alatke za primenu sistema Office
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "918"
- "2000022"
ms.assetid: 7ff7cc06-76d0-468f-bd66-3f2760750d04
ms.openlocfilehash: fa40fef0de9b2e0e1fc329269c24e8bca9ed4146
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43726262"
---
# <a name="using-the-office-deployment-tool-odt"></a>Korišćenje alatke za primenu sistema Office (ODT)

Koristite alatku za primenu sistema Office (ODT) da biste primenili Office 365 verzije sistema Office. Alatka za primenu sistema Office (Setup. exe) se pokreće sa komandne linije i koristi XML datoteku za konfiguraciju da bi utvrdila koje postavke treba primeniti prilikom primene sistema Office.
  
1. Preuzmite najnoviju verziju alatke za primenu sistema Office sa [lokacije Microsoft Download Center](https://go.microsoft.com/fwlink/p/?LinkID=626065).

2. Koristite [alatku za prilagođavanje sistema Office (OCT)](https://config.office.com) da biste izabrali željene postavke za raspoređivanje i kreirali XML datoteku za konfiguraciju. Izvezite datoteku za konfiguraciju i smestite je lokalno u istu fasciklu u kojoj se nalazi datoteka Setup. exe.

    **Napomena:** Problemi sa instalacijom sistema Office se obično javljaju zbog pogrešno konfigurisanih ili neoblikovanih datoteka za konfiguraciju. Da biste izbegli takve probleme, preporučujemo da koristite alatku za prilagođavanje sistema Office da biste kreirali datoteku za konfiguraciju. Postojeće datoteke za konfiguraciju možete da uvezete i u alatku za prilagođavanje sistema Office.

3. Na osnovu pune komandne linije prebacite se na lokaciju na kojoj se nalazi instalacija. exe i pokrenite alatku za primenu sistema Office u režimu preuzimanja i navedite datoteku za konfiguraciju koju ste upravo sačuvali. U ovom primeru, Konfiguraciona datoteka se zove konfiguracija. XML:
    
  ```
  setup.exe /download Configuration.xml  
  ```

4. Pokrenite alatku za primenu sistema Office u režimu konfigurisanja i navedite datoteku za konfiguraciju.
    
  ```
  setup.exe /configure Configuration.xml
  ```

    **Napomena:** Morate da pokrenete ovaj korak sa klijentskog računara na kojem želite da instalirate Office i morate imati lokalne administratorske dozvole na tom računaru.

Pogledajte odeljak [pregled alatke za primenu sistema Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)da biste saznali više o korišćenju alatke za primenu sistema Office za Microsoft 365 aplikacije za scenarije raspoređivanja poslovnih informacija. Više detalja o korišćenju alatke za prilagođavanje sistema Office potražite u članku [pregled alatke za prilagođavanje sistema Office](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).
