---
title: Došlo je do greške greška u proveri valjanosti oznake programa Access tokom provere radne površine na Interu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2536"
- "9000657"
ms.openlocfilehash: 7472af5c4e19e5697b5fb4802ed1cbb2c74f1d19
ms.sourcegitcommit: f1fad2129d09660ec42dbce03ce2c6b4cfc9555a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/18/2019
ms.locfileid: "40741262"
---
# <a name="there-was-an-error-validating-access-token-error-during-desktop-analytics-onboarding"></a><span data-ttu-id="04650-102">"Došlo je do greške pri proveri oznake za pristup" tokom programa za analitiku na radnoj površini</span><span class="sxs-lookup"><span data-stu-id="04650-102">"There was an error validating access token" error during Desktop Analytics onboarding</span></span>

<span data-ttu-id="04650-103">Ova greška se obično posmatra kada istekne oznaka potvrde identiteta.</span><span class="sxs-lookup"><span data-stu-id="04650-103">This error is normally observed when the authentication token expires.</span></span> <span data-ttu-id="04650-104">Obično osvežavanje stranice osvežava oznaku.</span><span class="sxs-lookup"><span data-stu-id="04650-104">Usually, refreshing the page refreshes the token.</span></span> <span data-ttu-id="04650-105">Međutim, ovaj problem može da potraje ako postoje neke smernice uslovnog pristupa koje se primenjuju na nalog koji se koristi za analitiku na tabli za radnu površinu.</span><span class="sxs-lookup"><span data-stu-id="04650-105">However, this issue can persist if there are any Conditional Access policies applied to the account being used to on-board Desktop Analytics.</span></span> <span data-ttu-id="04650-106">Možete da pregledate znak Azure oglasa u evidencijama na Azure portalu da biste videli da li postoje bilo kakve greške pri prijavljivanju za nalog koji se koristi za "analitiku" za pregled radne površine.</span><span class="sxs-lookup"><span data-stu-id="04650-106">You can review the Azure AD Sign In logs in the Azure Portal to see if there are any sign-in failures for the account being used for Desktop Analytics onboarding.</span></span>

<span data-ttu-id="04650-107">Više informacija o uslovnom pristupu potražite u [planu primene uslovnog pristupa](https://docs.microsoft.com/azure/active-directory/conditional-access/plan-conditional-access).</span><span class="sxs-lookup"><span data-stu-id="04650-107">For more information about Conditional Access, visit [Plan your Conditional Access deployment](https://docs.microsoft.com/azure/active-directory/conditional-access/plan-conditional-access).</span></span>