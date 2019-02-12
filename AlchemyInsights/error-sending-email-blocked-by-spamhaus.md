---
title: Greška prilikom slanja e-pošte blokiran od strane SpamHaus
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 2/23/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: 249f16d057b0539d71dc514ac35df28ab78fa061
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29912362"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a>Greška prilikom slanja e-pošte: klijent domaćina blokirane pomoću Spamhaus

IP adresu koja je poslala poruku je na listu bloka koja je u vlasništvu [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245). Razlozi za blokirana od strane Spamhaus uključuju kompromitovane račune, kompromitovan mašine Deljenje javne IP adrese, a dobavljač Internet usluga (ISP) politike. Moguće ispravke su:
  
- Za ulazni blokirane poruke Office 365 gde ti kontrolisati izvornom serveru e-pošte, morate utvrditi uzrok i ukloniti iz bloka sa Spamhaus Internet.
    
- Za blokirane dolazne poruke Office 365 gde IP adresu izvora pripada nekom drugom, vlasnik adresa mora ukloniti blok sa Spamhaus Internet. Ako IP adresa je na blok listi politike (PBL), vlasnik možete da dodelite različite statičnu IP adresu ili adresu uklanjanje u PBL.
    
- Za izlazni blokirane poruke iz domena svoje Office 365, da primate ovu grešku ako poruke usmeravaju kroz uslugu 3 partije. Možete koristiti alat za pronalaženje ko je pronaci vlasnika blokiranih IP adresa.
    

