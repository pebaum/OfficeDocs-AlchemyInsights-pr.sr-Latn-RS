---
title: Rešavanje problema sa sigurnosnim savjet za proveru otkrivanja prevara
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 96ebe3c5-66ea-4662-98b7-052c2181c2f3
ms.custom:
- "275"
- "3100004"
ms.openlocfilehash: 61159391f7a9876750cd7fefc40c54054fb9bec9
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43759526"
---
# <a name="troubleshooting-the-safety-tip-for-fraud-detection-checks"></a>Rešavanje problema sa sigurnosnim savjet za proveru otkrivanja prevara

Ako dobijate bezbednosni savet koji kaže "Pošiljalac nije uspeo da proveri da li je potrebno otkrivanje prevara i ne bude ono što se čini", onda pošiljalac nije uspeo da prosledi ili DKIM ili SPF proveru identiteta. Najbolji metod za rješavanje ovog načina je da se pošiljalac ovlasti. Ako pošiljalac šalje vaše ime, potrebno je da ih ovlastite tako što ćete dodati IP adresu pošiljaoca u vaš SPF zapis.
  
Više informacija potražite [u članku rešavanje problema sa crvenim (sumnjivom) bezbednošću za proveru za otkrivanje prevara](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) .
  
Evo nekih drugih veza koje mogu da vam pomognu:
  
- [Kako Microsoft koristi okvir smernica za pošiljaoca (SPF) kako bi sprečio lažno korišćenje](https://docs.microsoft.com/office365/SecurityCompliance/how-office-365-uses-spf-to-prevent-spoofing)

- [Podešavanje SPF-a za sprečavanje lažno prikazivanje](https://docs.microsoft.com/office365/SecurityCompliance/set-up-spf-in-office-365-to-help-prevent-spoofing)
