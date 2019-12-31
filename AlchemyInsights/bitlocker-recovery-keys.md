---
title: BitLocker ključevi za oporavak
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1922"
- "9000220"
ms.openlocfilehash: 4e06e0e43b63836b9e9cf923e554dd474b82c671
ms.sourcegitcommit: 123e9fe46e99719dd271e75a66555861e968f4a2
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/30/2019
ms.locfileid: "40908828"
---
# <a name="accessing-bitlocker-recovery-keys"></a>Pristupanje BitLocker ključevima za oporavak

Prilikom konfigurisanja postavki funkcije BitLocker za zaštitu krajnjeg čvorišta, moguće je definisati da li informacije o BitLocker oporavku treba uskladištiti u Azure aktivnom direktorijumu.

Ako je ta postavka konfigurisana, uskladišteni podaci o oporavku trebalo bi da budu vidljivi Admin (Intune) kao deo podataka o uređaju "Intune uređajima" na dva načina:

Uređaji-Azure AD uređaji-> "uređaj" ili uređaji-> svi uređaji-> "Device"-> ključevi za oporavak

Osim toga, ako postoji administrativni pristup samom uređaju, ključ za oporavak (lozinka) može da se vidi pokretanjem sledeće komande iz pune komandne linije:

```
manage-bde -protectors c: -get
Example
Volume C: []
All Key Protectors
    TPM:
      ID: {8A5D13D6-7ED9-46C8-A74F-AC3ADF016EC8}
      PCR Validation Profile:
        0, 2, 4, 8, 9, 10, 11
    Numerical Password:
      ID: {DFA26333-XXXX-402C-YYYY-A8C40AF3ZZZZ}
      Password:
        393943-22222-281721-555554-577984-77777-194700-99999
```
Ako je uređaj šifrovan pre upisa u Intune, ključ za oporavak je možda povezan sa "Microsoft nalogom" (MSA) koji se koristi za prijavljivanje na uređaj tokom OOBE procesa. Ako je to slučaj, pristup https://onedrive.live.com/recoverykey i prijavljivanje sa tim MSA bi trebalo da prikaže uređaje za koje su uskladišteni ključevi za oporavak.
 
Ako je uređaj šifrovan kao rezultat konfigurisanja putem smernica grupe zasnovanih na domenu, informacije o oporavku mogu biti uskladištene u aktivnom direktorijumu "on-premisa".
 

