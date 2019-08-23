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
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36545193"
---
# <a name="issues-with-mfa"></a>Problemi sa MFA
Postoje neke stvari provjeriti ako korisnici mogu da prijavite koristeći višestruku potvrdu identiteta (MLU)

1. Pogođenih korisnika može biti blokiran pristup u Azure Active Directory Portal. Ako je to slučaj, potvrda identiteta će pokušati da za to određeni korisnik će biti automatski odbijen. [Molim vas, pratite korake u ovom članku da biste deblokirali ih.](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#block-and-unblock-users)

2. Ako deblokiranje korisnika nije pomoglo ili korisnik nije blokiran možete pokušati da poništi MFA za korisnika i proci ce kroz proces enroll ponovo. [Molim vas, pratite korake u ovom članku.](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-userdevicesettings#require-users-to-provide-contact-methods-again)

Ako je ovo prvi put omogućen MFA i vaši korisnici niste u mogućnosti da se prijavi za klijente koji nisu pregledačima kao što su Outlook, Skype, itd, možda ADAL (aktivni direktorijum za potvrdu identiteta biblioteku) nije omogućena na pretplatu O365. U tom slučaju biće potrebno da biste se povezali sa Exchange Online Powershell i pokrenete ovu cmdlet:  *Set-OrganizationConfig-OAuth2ClientProfileEnabled: $true*