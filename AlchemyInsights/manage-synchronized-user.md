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
# <a name="unable-to-set-primary-email-address-or-change-user-attributes"></a><span data-ttu-id="02623-102">Nije moguće podesiti primarnu e-adresu ili promeniti korisničke atribute</span><span class="sxs-lookup"><span data-stu-id="02623-102">Unable to set primary email address or change user attributes</span></span>

<span data-ttu-id="02623-103">Ako sinhronizacija direktorijuma je omogućena za vaše okruženje neki atributi korisnika ili objekta nije moguće promeniti pomoću Admin centar.</span><span class="sxs-lookup"><span data-stu-id="02623-103">If directory synchronization is enabled for your environment some user or object attributes cannot be changed using the Admin Center.</span></span>
<span data-ttu-id="02623-104">Da u potpunosti upravlja sinhronizovanih korisnike i sve svoje atribute, koristite svoje lokalne aktivnog direktorijuma korisnicima i grupama konzolu za upravljanje (adsiedit.msc).</span><span class="sxs-lookup"><span data-stu-id="02623-104">To fully manage synchronized users and all their attributes, use your local active directory users and groups management console (adsiedit.msc).</span></span>  

<span data-ttu-id="02623-105">Alternativno, možete da promenite pojedinačne korisnike ili atribute za sinhronizovane korisnici koriste powershell kao što je prikazano u ove uobičajene primere:</span><span class="sxs-lookup"><span data-stu-id="02623-105">Alternatively, you can change individual users or attributes for synchronized users using powershell such as shown in these common examples:</span></span> 
- <span data-ttu-id="02623-106">Set-MsolUser - UserPrincipalName user@yourdomain.onmicrosoft.com - AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="02623-106">Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com</span></span>
- <span data-ttu-id="02623-107">Set-MsolUser - UserPrincipalName „user@yourdomain.onmicrosoft.com” - DisplayName „Test korisnika”-"prezime” „Korisnik”-naslov „Menadžer”-Department „HR”</span><span class="sxs-lookup"><span data-stu-id="02623-107">Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"</span></span>
- <span data-ttu-id="02623-108">Ukloni-MsolUser - UserPrincipalName „user@yourdomain.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="02623-108">Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com</span></span>