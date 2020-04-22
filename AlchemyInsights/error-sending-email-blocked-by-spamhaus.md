---
title: Greška pri slanju e-poruke blokiranu spam Haus
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "255"
- "3100003"
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: 3ff4f7a155fe74f5b42a1bd43e67ef0a751d7fbd
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43714272"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a>Greška pri slanju e-poruke: host klijenta je blokirana pomoću bezvredne pošte

IP adresa koja je poslala poruku nalazi se na listi blokiranih poruka u vlasništvu [spam Haus](https://go.microsoft.com/fwlink/p/?linkid=123245). Razlozi za blokiranje bezvredne pošte uključuju kompromitovana konta, ugrožene mašine koje dele javnu IP adresu i smernice dobavljača Internet usluga (ISP). Moguća rešenja su:
  
- Za blokirane dolazne poruke u kojima kontrolišete izvorni server e-pošte, potrebno je da utvrdite uzrok i uklonite blok sa Web lokacije "spam Haus".

- Za blokirane dolazne poruke gde izvorna IP adresa pripada nekom drugom, vlasnik adrese treba da ukloni blok sa Web lokacije "spam Haus". Ako se IP adresa nalazi na listi blokiranih smernica (PBL), vlasnik može da dodeli drugačiju statičnu IP adresu ili da ukloni adresu iz PBL-a.

- Za blokirane odlazne poruke iz domena povezanog sa korporacijom Microsoft, ovu grešku možete dobiti ako se poruke usmeravaju preko usluge nezavisnog proizvođača. Da biste pronašli blokirani IP adresu, možete da koristite alatku za pronalaženje koja se može koristiti.
