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
ms.openlocfilehash: 5a383bdd17c5fa055c35a923ca36e0e0f6d429e4
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/28/2019
ms.locfileid: "35380519"
---
# <a name="unable-to-set-primary-email-address-or-change-user-attributes"></a>Nije moguće podesiti primarnu e-adresu ili promeniti korisničke atribute

Ako sinhronizacija direktorijuma je omogućena za vaše okruženje neki atributi korisnika ili objekta nije moguće promeniti pomoću Admin centar.
Da u potpunosti upravlja sinhronizovanih korisnike i sve svoje atribute, koristite svoje lokalne aktivnog direktorijuma korisnicima i grupama konzolu za upravljanje (adsiedit.msc).  

Alternativno, možete da promenite pojedinačne korisnike ili atribute za sinhronizovane korisnici koriste powershell kao što je prikazano u ove uobičajene primere: 
- Set-MsolUser - UserPrincipalName user@yourdomain.onmicrosoft.com - AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com
- Set-MsolUser - UserPrincipalName „user@yourdomain.onmicrosoft.com” - DisplayName „Test korisnika”-"prezime” „Korisnik”-naslov „Menadžer”-Department „HR”
- Ukloni-MsolUser - UserPrincipalName „user@yourdomain.onmicrosoft.com