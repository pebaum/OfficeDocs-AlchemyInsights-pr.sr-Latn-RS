---
title: Zabranjen pristup prilikom prikazivanja toka posla
ms.author: kirks
author: Techwriter40
ms.date: 11/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: cced887b03876eef527e0166a5a3c9be4b553029
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/24/2019
ms.locfileid: "29487600"
---
# <a name="access-denied-when-viewing-a-workflow"></a>Zabranjen pristup prilikom prikazivanja toka posla

SharePoint 2013 tokove posla koji se pokušaj pošaljite email SharePoint grupi možete propasti sa poruku o grešci „Pristup je odbijen” ako članstva SharePoint grupe podešen prema svima.
  
 **Da biste rešili ovaj problem, izvršite ove korake:**
  
 1. Dozvoli svima da vide članovi SharePoint grupe. 
  
 2. Uklonite SharePoint grupu iz "za" i "CC red za e-poštu. 
  
 3. Eksplicitno dodati korisnike za ili kopija u red ako članstvo vidljivost nije moguće promeniti SharePoint grupe. 
  
Da biste prikazali više detalja pogledajte [HTTP Unauthorized da /_vti_bin/client.svc/sp.utilities.utility.SendEmail ](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).
  

