---
title: 'AIP skener: instalacija i konfiguracija'
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002278"
- "5119"
ms.openlocfilehash: d059d411aef03ca57662b71fbd7d27aecd3e0e57
ms.sourcegitcommit: c46b8df485edbd13e8bb4d1b2ba1c2821ddc9da0
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/23/2020
ms.locfileid: "44358565"
---
# <a name="aip-scanner-installation-and-configuration"></a>AIP skener: instalacija i konfiguracija

**Pratite preporučene smernice da biste instalirali AIP skener**:

1. Ako nadograđujete i ne izvršavate čistu instalaciju, proverite da li ste pratili uputstva za [nadogradnju zaštitnog skenera za zaštitu informacija](https://docs.microsoft.com/azure/information-protection/rms-client/client-admin-guide#upgrading-the-azure-information-protection-scanner) i za objedinjenu korisnika, pogledajte odeljak [Nadogradnja skenera za zaštitu od Azure informacija](https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide#upgrading-the-azure-information-protection-scanner).
2. Proverite da li ste u skladu sa svim [zaštitnim zidovima i zahtevima za postavke mrežne infrastrukture](https://docs.microsoft.com/azure/information-protection/requirements#firewalls-and-network-infrastructure).
3. Uverite se da [su smernice podešene](https://docs.microsoft.com/azure/information-protection/configure-policy) za automatsko označavanje ili da imaju podrazumevanu oznaku u smernici.
4. Uverite se da je odgovarajući tip datoteke konfigurisan za oznaku/zaštitu kao što je opisano u [tipovima datoteka koje podržava "Azure" softver za zaštitu informacija](https://docs.microsoft.com/azure/information-protection/rms-client/client-admin-guide-file-types#supported-file-types-for-classification-and-protection). Pored toga, ako želite da promenite podrazumevano ponašanje, sledite ove smernice: [Promena podrazumevanog nivoa zaštite datoteka](https://docs.microsoft.com/azure/information-protection/rms-client/client-admin-guide-file-types#changing-the-default-protection-level-of-files).
5. Proverite da li korisnički nalog konfigurisan za pokretanje usluge skenera ima dozvole za pristup svim konfigurisanim depoa.
6. Ako i dalje budete imali problema, izvezite evidencije skenera i dodajte ih na kartu za podršku.

**Evidencija za izvoz Azure datoteka zaštite skenera**

1. Krećite se do%localappdata%\Microsoft\MSIP u okviru korisničkog konteksta koji koristi uslugu skenera.
2. Zip svi sadržaji u okviru MSIP fascikle.
3. Sačuvajte evidencije na izboru lokacije i priložite ih svom zahtevu za uslugu.
4. Takođe možete koristiti funkciju " [Izvezi-Aipevidencijama"-Onbpolof](https://docs.microsoft.com/powershell/module/azureinformationprotection/export-aiplogs?view=azureipps).

**Za dodatne informacije pogledajte**:
- [Primena skenera za zaštitu od Azure informacija radi automatskog klasifikivanja i zaštite datoteka](https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner)
- [Određivanje i korišćenje parametra tokena za podešavanje-Aipprovjeru autentičnosti](https://docs.microsoft.com/azure/information-protection/rms-client/client-admin-guide-powershell#specify-and-use-the-token-parameter-for-set-aipauthentication)
- [Pokretanje ciklusa otkrivanja i prikazivanje izveštaja za skener](https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner#run-a-discovery-cycle-and-view-reports-for-the-scanner)
- [Pregled dokumentacije za zaštitu od Azure informacija](https://docs.microsoft.com/azure/information-protection/what-is-information-protection)
- [Zahtevi za zaštitu od Azure informacija](https://docs.microsoft.com/azure/information-protection/get-started/requirements)
- [Preuzimanje programa za zaštitu od Azure informacija](https://www.microsoft.com/download/details.aspx?id=53018)
