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
# <a name="issues-with-mfa"></a><span data-ttu-id="0f7a1-102">Problemi sa MFA</span><span class="sxs-lookup"><span data-stu-id="0f7a1-102">Issues with MFA</span></span>
<span data-ttu-id="0f7a1-103">Postoje neke stvari provjeriti ako korisnici mogu da prijavite koristeći višestruku potvrdu identiteta (MLU)</span><span class="sxs-lookup"><span data-stu-id="0f7a1-103">There are a couple of things to check if users cannot login using multi-factor authentication (MFA)</span></span>

1. <span data-ttu-id="0f7a1-104">Pogođenih korisnika može biti blokiran pristup u Azure Active Directory Portal.</span><span class="sxs-lookup"><span data-stu-id="0f7a1-104">The affected user may be blocked in Azure Active Directory Portal.</span></span> <span data-ttu-id="0f7a1-105">Ako je to slučaj, potvrda identiteta će pokušati da za to određeni korisnik će biti automatski odbijen.</span><span class="sxs-lookup"><span data-stu-id="0f7a1-105">If that is the case, Authentication attempts for that specific user will be automatically denied.</span></span> [<span data-ttu-id="0f7a1-106">Molim vas, pratite korake u ovom članku da biste deblokirali ih.</span><span class="sxs-lookup"><span data-stu-id="0f7a1-106">Please follow the steps in this article to unblock them.</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#block-and-unblock-users)

2. <span data-ttu-id="0f7a1-107">Ako deblokiranje korisnika nije pomoglo ili korisnik nije blokiran možete pokušati da poništi MFA za korisnika i proci ce kroz proces enroll ponovo.</span><span class="sxs-lookup"><span data-stu-id="0f7a1-107">If unblocking the user didn't help or the user is not blocked you can try to reset MFA for the user and they will go through the enroll process again.</span></span> [<span data-ttu-id="0f7a1-108">Molim vas, pratite korake u ovom članku.</span><span class="sxs-lookup"><span data-stu-id="0f7a1-108">Please follow the steps in this article.</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-userdevicesettings#require-users-to-provide-contact-methods-again)

<span data-ttu-id="0f7a1-109">Ako je ovo prvi put omogućen MFA i vaši korisnici niste u mogućnosti da se prijavi za klijente koji nisu pregledačima kao što su Outlook, Skype, itd, možda ADAL (aktivni direktorijum za potvrdu identiteta biblioteku) nije omogućena na pretplatu O365.</span><span class="sxs-lookup"><span data-stu-id="0f7a1-109">If this is the first time you enabled MFA and your users are unable to login to non-browsers clients such as Outlook, Skype, etc, perhaps ADAL (Active Directory Authentication Library) is not enabled on your O365 subscription.</span></span> <span data-ttu-id="0f7a1-110">U tom slučaju biće potrebno da biste se povezali sa Exchange Online Powershell i pokrenete ovu cmdlet:  *Set-OrganizationConfig-OAuth2ClientProfileEnabled: $true*</span><span class="sxs-lookup"><span data-stu-id="0f7a1-110">In this case you will need to connect to Exchange Online Powershell and run this cmdlet:  *Set-OrganizationConfig -OAuth2ClientProfileEnabled:$true*</span></span>