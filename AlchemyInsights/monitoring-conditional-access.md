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
ms.openlocfilehash: 06307b57475e8828e6d4e5e01625d5100576f12b
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/15/2019
ms.locfileid: "28310440"
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
    
Opširnije: [Kako da Monitor Conditional Access uređaji](https://docs.microsoft.com/en-us/intune/conditional-access-exchange-monitor)
  

