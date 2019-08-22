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
# <a name="unable-to-set-primary-email-address-or-change-user-attributes"></a><span data-ttu-id="2c9a1-102">Nije moguće podesiti primarnu e-adresu ili promeniti korisničke atribute</span><span class="sxs-lookup"><span data-stu-id="2c9a1-102">Unable to set primary email address or change user attributes</span></span>

<span data-ttu-id="2c9a1-103">Ako sinhronizacija direktorijuma omogućena za vašu okolinu, neki atributi korisnika ili objekta nije moguće promeniti pomoću Microsoft 365 administrativni centar.</span><span class="sxs-lookup"><span data-stu-id="2c9a1-103">If directory synchronization is enabled for your environment, some user or object attributes cannot be changed using the Microsoft 365 admin center.</span></span>

<span data-ttu-id="2c9a1-104">Da u potpunosti upravlja sinhronizovanih korisnike i sve svoje atribute, koristite svoje lokalne aktivnog direktorijuma korisnicima i grupama konzolu za upravljanje (adsiedit.msc).</span><span class="sxs-lookup"><span data-stu-id="2c9a1-104">To fully manage synchronized users and all their attributes, use your local active directory users and groups management console (adsiedit.msc).</span></span>  

<span data-ttu-id="2c9a1-105">Alternativno, možete da promenite pojedinačne korisnike ili atribute za sinhronizovane korisnici koriste powershell kao što je prikazano u ove uobičajene primere:</span><span class="sxs-lookup"><span data-stu-id="2c9a1-105">Alternatively, you can change individual users or attributes for synchronized users using powershell such as shown in these common examples:</span></span> 
- <span data-ttu-id="2c9a1-106">Set-MsolUser - UserPrincipalName user@yourdomain.onmicrosoft.com - AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="2c9a1-106">Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com</span></span>
- <span data-ttu-id="2c9a1-107">Set-MsolUser - UserPrincipalName „user@yourdomain.onmicrosoft.com” - DisplayName „Test korisnika”-"prezime” „Korisnik”-naslov „Menadžer”-Department „HR”</span><span class="sxs-lookup"><span data-stu-id="2c9a1-107">Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"</span></span>
- <span data-ttu-id="2c9a1-108">Ukloni-MsolUser - UserPrincipalName „user@yourdomain.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="2c9a1-108">Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com</span></span>