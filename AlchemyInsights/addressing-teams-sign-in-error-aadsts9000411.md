---
title: Adresiranje za prijavljivanje timova AADSTS9000411
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000744"
- "5689"
ms.openlocfilehash: b70f1320ea1dfa29e6fa489bd02acfcd1d92971b
ms.sourcegitcommit: 88d2918aa51f4ba10771527380c3e0db0f5a9147
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/20/2020
ms.locfileid: "44358370"
---
# <a name="addressing-teams-sign-in-error-aadsts9000411"></a><span data-ttu-id="bc79f-102">Adresiranje za prijavljivanje timova AADSTS9000411</span><span class="sxs-lookup"><span data-stu-id="bc79f-102">Addressing Teams sign-in error AADSTS9000411</span></span>

<span data-ttu-id="bc79f-103">Kada se prijavljujete u Microsoft timove, možete dobiti grešku: **Žao mi je, ali imamo problema sa prijavljivanjem u AADSTS9000411: zahtev nije ispravno oblikovan. "Login_hint" je duplirana.**</span><span class="sxs-lookup"><span data-stu-id="bc79f-103">When signing in to Microsoft Teams, you may receive the error: **Sorry, but we're having trouble with signing you in AADSTS9000411: The request is not properly formatted. The parameter "login_hint" is duplicated.**</span></span>

<span data-ttu-id="bc79f-104">Da biste rešili ovaj problem, proverite da li su vaši Microsoft timovi klijenti ažurirani.</span><span class="sxs-lookup"><span data-stu-id="bc79f-104">To address this issue, please ensure your Microsoft Teams clients are updated.</span></span> <span data-ttu-id="bc79f-105">Za više informacija o ažuriranju klijenta pogledajte odeljak [Ažuriranje Microsoft timova](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).</span><span class="sxs-lookup"><span data-stu-id="bc79f-105">For more information on updating your client, see [Update Microsoft Teams](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).</span></span>

<span data-ttu-id="bc79f-106">Ako ne možete da ažurirate klijenta iz nekog razloga, odjavljivanje sa klijenta će obrisati većinu keširanih podataka.</span><span class="sxs-lookup"><span data-stu-id="bc79f-106">If you cannot update your client for some reason, logging off the client will clear most cached data.</span></span> <span data-ttu-id="bc79f-107">Međutim, ako i dalje imate problema nakon odjavljivanja/prijavljivanja, napustite timove i obrišite keš memoriju na sledeći način:</span><span class="sxs-lookup"><span data-stu-id="bc79f-107">However, if you still have issues after logoff/logon, quit Teams and please clear your client cache by doing the following:</span></span>
1. <span data-ttu-id="bc79f-108">Zatvorite Microsoft timove.</span><span class="sxs-lookup"><span data-stu-id="bc79f-108">Close Microsoft Teams.</span></span>
2. <span data-ttu-id="bc79f-109">Posetite lokaciju:%AppData%\microsoft\teams i izbrišite sve datoteke.</span><span class="sxs-lookup"><span data-stu-id="bc79f-109">Go to: %appdata%\microsoft\teams and delete all the files.</span></span>
3. <span data-ttu-id="bc79f-110">Ponovo otvorite Microsoft timove.</span><span class="sxs-lookup"><span data-stu-id="bc79f-110">Reopen Microsoft Teams.</span></span>
