---
title: Nadgledanje Conditional Access
ms.author: pebaum
author: pebaum
ms.date: 8/1/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: dcb86c54-769e-4832-9f88-bc45f1e5f36c
ms.openlocfilehash: f4153f8a87a138d548c133142b0d48a319bd4b71
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/30/2019
ms.locfileid: "29656581"
---
# <a name="monitoring-conditional-access"></a>Nadgledanje Conditional Access

Korisnici na meti sa uslovnog pristupa će dobiti email sa obavijesti ako ne ispunjavaju zahteve za pristup vašoj organizaciji. Da biste riješili, preporučujemo jedan ili više od sledećih rešenja:
  
- Ako uređaj pretpostavlja se da budete upisani, savetujem da korisnik u kompaniji Portal aplikaciju i proverite da li je prikazan u kompaniji Portal. Ako ne, korisnik treba da upiše uređaj.
    
- U azurno portal idite do **Intune \> uređaj usklađenosti**. Izaberite **uređaj usklađenosti**ispod **monitora** . Prikazivanje izveštaja usklađenosti uređaj da biste potvrdili da je korisnikov uređaj označen kao usaglašeni. 
    
- U azurno portal idite do **Intune \> uređaj usklađenosti**. U okviru **Upravljanje**, kliknite na **politiku**. Na listi usklađenosti politike, provjerite profil je dodeljena vašem korisničkom uređaju. Ako nema profila je dodeljeno, onda Intune ne moći da potvrdi status usklađenosti uređaja. 
    
- Uredi zadatak uslovnog pristupa korisnika.
    
1. U azurno portal idite do **Intune \> Conditional access \> politiku**
    
2. Sa liste izaberite smernice
    
3. Kliknite na dugme **korisnici i grupe**
    
4. Da biste ciljali određene politiku na nekoga, ih dodati listi **uključenih** . Da biste bili sigurni da osoba je izostavljena iz polise, dodati ih na listu **izuzmete** . 
    
Opširnije: [Kako da Monitor Conditional Access uređaji](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)
  

