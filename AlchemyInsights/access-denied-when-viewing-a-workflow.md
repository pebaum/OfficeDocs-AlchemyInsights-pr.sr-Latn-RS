---
title: Zabranjen pristup prilikom prikazivanja toka posla
ms.author: kirks
author: Techwriter40
ms.date: 11/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: 43369c600687d6ac253f70a8535dc2bd0d41687e
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32389901"
---
# <a name="access-denied-when-viewing-a-workflow"></a>Zabranjen pristup prilikom prikazivanja toka posla

SharePoint 2013 tokove posla koji se pokušaj pošaljite email SharePoint grupi možete propasti sa poruku o grešci „Pristup je odbijen” ako članstva SharePoint grupe podešen prema svima.
  
 **Da biste rešili ovaj problem, izvršite ove korake:**
  
 1. Dozvoli svima da vide članovi SharePoint grupe. 
  
 2. Uklonite SharePoint grupu iz "za" i "CC red za e-poštu. 
  
 3. Eksplicitno dodati korisnike za ili kopija u red ako članstvo vidljivost nije moguće promeniti SharePoint grupe. 
  
Da biste prikazali više detalja pogledajte [HTTP Unauthorized da /_vti_bin/client.svc/sp.utilities.utility.SendEmail ](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).
  

