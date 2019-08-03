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
ms.openlocfilehash: 2e79040c249b7825b964a19c51bcc42e5a6afb3f
ms.sourcegitcommit: 514ced512d0d7fff485b6fbf236cd27d6b4166e0
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/26/2019
ms.locfileid: "35250179"
---
# <a name="issues-with-mfa"></a>Problemi sa MFA
Postoje neke stvari provjeriti ako korisnici mogu da prijavite koristeći višestruku potvrdu identiteta (MLU)

1. Pogođenih korisnika može biti blokiran pristup u Azure Active Directory Portal. Ako je to slučaj, potvrda identiteta će pokušati da za to određeni korisnik će biti automatski odbijen. [Molim vas, pratite korake u ovom članku da biste deblokirali ih.](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#block-and-unblock-users)

2. Ako deblokiranje korisnika nije pomoglo ili korisnik nije blokiran možete pokušati da poništi MFA za korisnika i proci ce kroz proces enroll ponovo. [Molim vas, pratite korake u ovom članku.](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-userdevicesettings#require-users-to-provide-contact-methods-again)

Ako je ovo prvi put omogućen MFA i vaši korisnici niste u mogućnosti da se prijavi za klijente koji nisu pregledačima kao što su Outlook, Skype, itd, možda ADAL (aktivni direktorijum za potvrdu identiteta biblioteku) nije omogućena na pretplatu O365. U tom slučaju biće potrebno da biste se povezali sa Exchange Online Powershell i pokrenete ovu cmdlet:  *Set-OrganizationConfig-OAuth2ClientProfileEnabled: $true*