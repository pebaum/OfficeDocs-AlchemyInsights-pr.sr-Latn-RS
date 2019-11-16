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
ms.openlocfilehash: a415116b9ba437cb13426896119cd1b40d9ab491
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/15/2019
ms.locfileid: "37768851"
---
# <a name="issues-with-azure-mfa"></a><span data-ttu-id="17cb1-102">Problemi sa Azure MFA</span><span class="sxs-lookup"><span data-stu-id="17cb1-102">Issues with Azure MFA</span></span>
<span data-ttu-id="17cb1-103">Postoji nekoliko stvari koje treba da proverite ako korisnik ne može da se prijavi pomoću opcije za potvrdu identiteta sa više faktora (MFA)</span><span class="sxs-lookup"><span data-stu-id="17cb1-103">There are a couple of things to check if users cannot log in using multi-factor authentication (MFA)</span></span>

1. <span data-ttu-id="17cb1-104">Moguće je da je korisnik blokiran u programu Azure.</span><span class="sxs-lookup"><span data-stu-id="17cb1-104">The affected user may be blocked in Azure Active Directory Portal.</span></span> <span data-ttu-id="17cb1-105">Ako je to slučaj, potvrda identiteta za tog određenog korisnika biće automatski odbijena.</span><span class="sxs-lookup"><span data-stu-id="17cb1-105">If that is the case, Authentication attempts for that specific user will be automatically denied.</span></span> [<span data-ttu-id="17cb1-106">Molimo vas da sledite korake iz ovog članka da biste ih deblokirali.</span><span class="sxs-lookup"><span data-stu-id="17cb1-106">Please follow the steps in this article to unblock them.</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#block-and-unblock-users)

2. <span data-ttu-id="17cb1-107">Ako deblokiranje korisnika nije pomoglo ili korisnik nije blokiran, možete pokušati da ponovo pokrenete MFA za korisnika i oni će ponovo proći proces prijave.</span><span class="sxs-lookup"><span data-stu-id="17cb1-107">If unblocking the user didn't help or the user is not blocked you can try to reset MFA for the user and they will go through the enroll process again.</span></span> [<span data-ttu-id="17cb1-108">Sledite korake u ovom članku.</span><span class="sxs-lookup"><span data-stu-id="17cb1-108">Please follow the steps in this article.</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-userdevicesettings#require-users-to-provide-contact-methods-again)

<span data-ttu-id="17cb1-109">Ako je ovo prvi put da ste omogućili MFA, a korisnici nisu u mogućnosti da se prijave na klijente koji nisu pregledači, kao što su Outlook, Skype i sl, možda ADAL (biblioteka potvrde identiteta aktivnog direktorijuma) nije omogućena na O365 pretplati.</span><span class="sxs-lookup"><span data-stu-id="17cb1-109">If this is the first time you enabled MFA and your users are unable to login to non-browsers clients such as Outlook, Skype, etc, perhaps ADAL (Active Directory Authentication Library) is not enabled on your O365 subscription.</span></span> <span data-ttu-id="17cb1-110">U ovom slučaju moraćete da se povežete sa Exchange online PowerShell i pokrenete ovu cmddozvoli:  *Set-OrganizationConfig-OAuth2ClientProfileEnabled: $TRUE*</span><span class="sxs-lookup"><span data-stu-id="17cb1-110">In this case you will need to connect to Exchange Online Powershell and run this cmdlet:  *Set-OrganizationConfig -OAuth2ClientProfileEnabled:$true*</span></span>