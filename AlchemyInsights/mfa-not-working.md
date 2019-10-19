---
title: Problemi sa MFA
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.custom:
- "2417"
- "9000557"
ms.openlocfilehash: 276f6b2212c9d85df726cb46a46dee7828b34c89
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/18/2019
ms.locfileid: "36545193"
---
# <a name="issues-with-mfa"></a>Problemi sa MFA
Postoji nekoliko stvari koje treba da proverite da li korisnici ne mogu da se prijave upotrebom provere identiteta sa više faktora (MFA)

1. Moguće je da je korisnik blokiran u programu Azure. Ako je to slučaj, potvrda identiteta za tog određenog korisnika biće automatski odbijena. [Molimo vas da sledite korake iz ovog članka da biste ih deblokirali.](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#block-and-unblock-users)

2. Ako deblokiranje korisnika nije pomoglo ili korisnik nije blokiran, možete pokušati da ponovo pokrenete MFA za korisnika i oni će ponovo proći proces prijave. [Sledite korake u ovom članku.](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-userdevicesettings#require-users-to-provide-contact-methods-again)

Ako je ovo prvi put da ste omogućili MFA, a korisnici nisu u mogućnosti da se prijave na klijente koji nisu pregledači, kao što su Outlook, Skype i sl, možda ADAL (biblioteka potvrde identiteta aktivnog direktorijuma) nije omogućena na O365 pretplati. U ovom slučaju moraćete da se povežete sa Exchange online PowerShell i pokrenete ovu cmddozvoli:  *Set-OrganizationConfig-OAuth2ClientProfileEnabled: $TRUE*