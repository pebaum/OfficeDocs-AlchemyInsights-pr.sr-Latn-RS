---
title: Pristup odbijen prilikom prikazivanja toka posla
ms.author: pebaum
author: pebaum
ms.date: 11/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: 1cfda8e08ada05858a28f2bede8c31261f9de351
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40050539"
---
# <a name="access-denied-when-viewing-a-workflow"></a>Pristup odbijen prilikom prikazivanja toka posla

SharePoint 2013 tokovi posla koji pokušaju da pošalju e-poruku SharePoint grupi mogu da uspeju sa porukom o grešci "pristup nije dozvoljen" Ako članstvo SharePoint grupe nije postavljeno na svakoga.
  
 **Da biste rešili ovaj problem, izvršite ove korake:**
  
 1. Dozvolite svima da vide članove SharePoint grupe.
  
 2. Uklonite SharePoint grupu iz reda "za" ili "CC" e-poruke.
  
 3. Izričito dodajte korisnike u red "za" ili "CC" Ako se ne može promeniti vidljivost članstva za SharePoint grupu.
  
Da biste prikazali više detalja, pogledajte [http neovlašćen do/_vti_bin/Client.svc/SP.Utilities.Utility.sendemail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).
  