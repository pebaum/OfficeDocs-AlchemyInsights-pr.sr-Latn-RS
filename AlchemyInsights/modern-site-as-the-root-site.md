---
title: Moderna lokaciju kao osnovne lokacije
ms.author: efrene
author: efrene
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1874"
- "9000265"
ms.openlocfilehash: b30fc3258bb76c0ab4bf10af0ec9317417f7c663
ms.sourcegitcommit: 8a83b508785c96c19648ed574f442bbef2c2dff9
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/07/2019
ms.locfileid: "36232729"
---
# <a name="modern-site-as-root-site"></a>Moderna lokaciju kao osnovna lokacija

Počele smo da bizarnom novu opciju koja će vam omogućiti da razmenite svoje klasične lokacije osnovna lokacija uz modernu lokaciju. Koristite [Invoke-SPSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) da razmenite adresu lokacije sa neke druge lokacije tokom arhiviranja originalne lokacije. Dostupno za lokaciju tima (nije povezan sa grupom), kao i komunikacija lokacije. 

>[!Important]
> Nemojte brisati svoje klasične osnovne lokacije da biste kreirali lokaciju moderne komunikacije. Ovo je Microsoft ne podržava. Brisanje osnovne lokacije će da sve SharePoint lokacije u vašoj organizaciji može pristupiti svim korisnicima, dok ne vraćanje lokacije ili da kreirate novu lokaciju na istom URL adresi. Komuniciramo ovu funkciju putem poruka centar. Možete očekivati funkcija biti uključena u tvojim podstanarom ubrzo.

## <a name="known-issues-with-swapping-sites"></a>Poznati problemi sa zamenjivanje lokacije
- Na ciljnoj lokaciji može vratiti grešku „nije pronađeno” (HTTP 404) kratak period vremena.
- Sadržaj će morati da bude recrawled da biste ažurirali indeks za pretraživanje. Nema ručnu stepeništa potreban ovde, to će biti urađeno automatski.
- Sve zavisi od „statična” veze (kao što je datoteka za sinhronizaciju i OneNote datoteke) će treba ispraviti ručno.
- Project Server lokacije možda će biti potrebno da se vrši da biste bili sigurni da su oni povezani i dalje ispravno. 
