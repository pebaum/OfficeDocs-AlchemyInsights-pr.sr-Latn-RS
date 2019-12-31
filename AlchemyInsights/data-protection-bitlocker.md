---
title: DataProtection-BitLocker
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1802"
- "9000220"
ms.openlocfilehash: c23a2a2bde240900119382a9c1185a6e02520149
ms.sourcegitcommit: 123e9fe46e99719dd271e75a66555861e968f4a2
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/30/2019
ms.locfileid: "40908723"
---
# <a name="enabling-bitlocker-encryption-with-intune"></a>Omogućavanje BitLocker šifrovanja pomoću usluge Intune

 Smernice zaštite krajnje tačke za Intune mogu da se koriste za Konfigurisanje postavki BitLocker šifrovanja za Windows uređaje. Za više informacija pogledajte [Postavke operativnog sistema Windows 10 (i novije) da biste zaštitili uređaje pomoću funkcije Intune](https://docs.microsoft.com/intune/endpoint-protection-windows-10#windows-encryption).
 
Trebalo bi da znate da mnogi noviji uređaji koji rade pod operativnim sistemom Windows 10 podržavaju automatsko BitLocker šifrovanje, koje se pokreće bez primene "MDM" smernica. Ovo može da utiče na primenu smernica ako su konfigurisane postavke koje nisu podrazumevane. Više detalja potražite u sledećim FAQ.
 
Više informacija o rešavanju problema sa BitLocker šifrovanjem potražite [u članku rešavanje problema sa BitLocker smernicama u programu Microsoft Intune](https://docs.microsoft.com/intune/protect/troubleshoot-bitlocker-policies).
 
 
**Faq**

 Q: koja izdanja Windows šifrovanja uređaja podrške pomoću smernica za zaštitu krajnjeg čvorišta?<br>
 A: postavke u smernicama za zaštitu krajnje tačke u funkciji Intune primenjuju se pomoću [BITLOCKER CSP](https://docs.microsoft.com/windows/client-management/mdm/bitlocker-csp). Nisu sve izdanja ili verzije operativnog sistema Windows podržavaju BitLocker CSP. <br><br>
      U ovom trenutku podržane su sledeće Windows izdanja: Enterprise, obrazovanje, mobilni, mobilni Enterprise i profesionalni (verzija 1809 i novije).
 
Q: ako je uređaj već šifrovan pomoću funkcije BitLocker koristeći podrazumevane postavke OS za metod šifrovanja i snagu šifrovanja (XTS-AES-128), primenjiće se smernica sa različitim postavkama automatski aktivirati ponovno šifriranje disk jedinice sa novim postavkama?<br>
A: ne. Da biste primenili nove postavke za šifrovanje, disk jedinica prvo mora biti dešifrovana.<br><br>
**Napomena:** Za uređaje koji se upisuju na autopilot, automatsko šifrovanje koje će se pojaviti tokom OOBE datoteke se ne aktivira dok se ne proceni funkcija "Intune", što omogućava da se postavke zasnovane na smernicama koriste umesto podrazumevanih vrednosti OS.
 
Q: ako je uređaj šifrovan kao rezultat primjene programa Intune, da li će se dešifrovati kada se ta smernica ukloni?<br>
A: uklanjanje smernica vezanih za šifrovanje ne dovodi do dešifrovanja disk jedinica koje su konfigurisane.
 
Q: Zašto u skladu sa smernicama usaglašenosti pokazuje da moj uređaj nema omogućen BitLocker, čak i ako jeste?<br>
A: postavka "BitLocker Enabled" u smernicama usaglašenosti koristi Windows klijent za zaštitu od zdravlja uređaja (DHA). Ovaj klijent samo Meri stanje uređaja u trenutku pokretanja. Ako uređaj nije ponovo pokrenut otkako je BitLocker šifrovanje dovršeno, usluga DHA Client neće prijaviti BitLocker kao aktivnu.
 
 