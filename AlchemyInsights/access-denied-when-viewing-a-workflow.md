---
title: Pristup odbijen prilikom prikazivanja toka posla
ms.author: pebaum
author: Techwriter40
ms.date: 11/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: 4ca65583fbd98867026e9e3cc8f36fe38798aa85
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/18/2019
ms.locfileid: "36747762"
---
# <a name="access-denied-when-viewing-a-workflow"></a>Pristup odbijen prilikom prikazivanja toka posla

SharePoint 2013 tokovi posla koji pokušaju da pošalju e-poruku SharePoint grupi mogu da uspeju sa porukom o grešci "pristup nije dozvoljen" Ako članstvo SharePoint grupe nije postavljeno na svakoga.
  
 **Da biste rešili ovaj problem, izvršite ove korake:**
  
 1. Dozvolite svima da vide članove SharePoint grupe.
  
 2. Uklonite SharePoint grupu iz reda "za" ili "CC" e-poruke.
  
 3. Izričito dodajte korisnike u red "za" ili "CC" Ako se ne može promeniti vidljivost članstva za SharePoint grupu.
  
Da biste prikazali više detalja, pogledajte [http neautorizovano za/_vti_bin/Client.svc/SP.Utilities.Utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).
  