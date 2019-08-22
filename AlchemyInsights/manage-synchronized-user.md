---
title: Upravljanje sinhronizovanih korisnika
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000609"
- "2444"
ms.openlocfilehash: a943c59d67c512e6326856dacd0053db121f6aa3
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36542017"
---
# <a name="unable-to-set-primary-email-address-or-change-user-attributes"></a>Nije moguće podesiti primarnu e-adresu ili promeniti korisničke atribute

Ako sinhronizacija direktorijuma omogućena za vašu okolinu, neki atributi korisnika ili objekta nije moguće promeniti pomoću Microsoft 365 administrativni centar.

Da u potpunosti upravlja sinhronizovanih korisnike i sve svoje atribute, koristite svoje lokalne aktivnog direktorijuma korisnicima i grupama konzolu za upravljanje (adsiedit.msc).  

Alternativno, možete da promenite pojedinačne korisnike ili atribute za sinhronizovane korisnici koriste powershell kao što je prikazano u ove uobičajene primere: 
- Set-MsolUser - UserPrincipalName user@yourdomain.onmicrosoft.com - AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com
- Set-MsolUser - UserPrincipalName „user@yourdomain.onmicrosoft.com” - DisplayName „Test korisnika”-"prezime” „Korisnik”-naslov „Menadžer”-Department „HR”
- Ukloni-MsolUser - UserPrincipalName „user@yourdomain.onmicrosoft.com