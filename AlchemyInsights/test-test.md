---
title: Nedostaju uslovi iz skladišta za SharePoint online
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1243"
- "5200021"
ms.openlocfilehash: 54ac2dbc1f45f88541c2338f3b55a777b4b57123
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766867"
---
# <a name="enabling-bitlocker-encryption-with-intune"></a>Omogućavanje BitLocker šifrovanja pomoću usluge Intune

Smernice za zaštitu krajnje tačke funkcije Intune mogu da se koriste za Konfigurisanje postavki Boitlocker šifrovanja za Windows uređaje kao što je opisano u: Windows10 (i novijim) postavkama za zaštitu uređaja pomoću funkcije Intune

Trebalo bi da znate da mnogi noviji uređaji koji rade pod operativnim sistemom Windows 10 podržavaju automatsko BitLocker šifrovanje koje se aktivira bez zatvaranja smernica MDM. Ovo može da utiče na primenu smernica ako su konfigurisane postavke koje nisu podrazumevane. Za više detalja pogledajte najčešća pitanja.


Najčešća  pitanja Q: koja izdanja Windows šifrovanja uređaja podrške pomoću smernica za zaštitu krajnjeg čvorišta?
 A: postavke u smernicama za zaštitu krajnje tačke u funkciji Intune primenjuju se pomoću BitLocker CSP.Nisu sve izdanja ni verzije operativnog sistema Windows koje podržavaju BitLocker CSP. 
      U ovom trenutku Windows izdanja: Enterprise; Podržano je obrazovanje, mobilni, mobilni poduhvat i stručni (od izrade 1809 na osnovu).




Q: ako je uređaj već šifrovan pomoću funkcije BitLocker koristeći podrazumevane postavke OS za metod šifrovanja i snagu šifrovanja (XTS-AES-128), primenjiće se smernica sa različitim postavkama automatski aktivirati ponovno šifriranje disk jedinice sa novim postavkama?

A: ne. Da bi primenio nove postavke za šifrovanje, disk jedinica se prvo mora dešifrovati.

Napomena za uređaje koji se upisuju sa autopilot automatsko šifrovanje koje bi se dešalo tokom OOBE-a nije izazvano dok se ne proceni da se postavke zasnovane na smernicama koriste umesto podrazumevanih vrednosti OS




Q ako je uređaj šifrovan kao rezultat zatvaranja smernica za Intune, biće dešifrovan kada se ta smernica ukloni?

A: uklanjanje smernica vezanih za šifrovanje ne dovodi do dešifrovanja disk jedinica koje su konfigurisane.




Q: Zašto u skladu sa smernicama usaglašenosti pokazuju da moj uređaj nema "BitLocker omogućeno", ali jeste?

A: postavka "BitLocker Enabled" u smernicama usaglašenosti koristi Windows klijent za zaštitu od zdravlja uređaja (DHA). Ovaj klijent samo Meri stanje uređaja u trenutku pokretanja. Dakle, ako uređaj nije ponovo pokrenut otkako je BitLocker šifrovanje dovršeno, usluga DHA Client neće prijaviti BitLocker kao aktivnu.