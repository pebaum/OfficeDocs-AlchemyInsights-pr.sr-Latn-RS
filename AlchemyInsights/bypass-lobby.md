---
title: Zaobiđi lobi
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2673"
- "9000740"
ms.openlocfilehash: 729fc5d4213acbbdf74a9d07adacb42b34170717
ms.sourcegitcommit: ffbeb72c9199ab4ebcb0f1ad443ed3e2f4950efc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/23/2019
ms.locfileid: "37637791"
---
# <a name="control-lobby-settings-and-level-of-participation"></a><span data-ttu-id="95555-102">Kontrola uvodnog postavljanja i nivoa učestvovanja</span><span class="sxs-lookup"><span data-stu-id="95555-102">Control lobby settings and level of participation</span></span>

<span data-ttu-id="95555-103">Ako želite da dozvolite svima, uključujući pozivne, spoljne i anonimne korisnike za zaobilaženje lobija, možete da koristite funkciju PowerShell da biste to uradili.</span><span class="sxs-lookup"><span data-stu-id="95555-103">If you'd like to allow everyone, including Dial-in, external, and anonymous users to bypass the lobby, you can use PowerShell to do it.</span></span> <span data-ttu-id="95555-104">Evo primera menjanja globalnih smernica za sastanak za vašu organizaciju:</span><span class="sxs-lookup"><span data-stu-id="95555-104">Here's an example of modifying the global meeting policy for your organization:</span></span>

`Set-CsTeamsMeetingPolicy -Identity Global -AutoAdmittedUsers "Everyone" -AllowPSTNUsersToBypassLobby $True`

<span data-ttu-id="95555-105">Ova cmdda je trenutno potrebna upotreba Skype-a za modul Business PowerShell.</span><span class="sxs-lookup"><span data-stu-id="95555-105">This cmdlet currently requires the use of Skype for Business PowerShell module.</span></span> <span data-ttu-id="95555-106">Da biste dobili instalacioni program koji će koristiti ovu cmdsaciju, pogledajte Upravljanje smernicama putem PowerShell.</span><span class="sxs-lookup"><span data-stu-id="95555-106">To get setup to use this cmdlet, check out Managing policies via PowerShell.</span></span>

<span data-ttu-id="95555-107">Možete podesiti novu smernicu koju ćete zatim morati da primenite na korisnike.</span><span class="sxs-lookup"><span data-stu-id="95555-107">You can set up a new policy, which you'll then need to apply it to users.</span></span> <span data-ttu-id="95555-108">Ako izmenite globalnu smernicu ona će se automatski primenjivati na korisnike.</span><span class="sxs-lookup"><span data-stu-id="95555-108">If you modify the Global policy it'll automatically apply to users.</span></span> <span data-ttu-id="95555-109">Za sve promene smernica potrebno je da sačekate najmanje 4 sata i do 24 časa da bi smernice stupile na snagu.</span><span class="sxs-lookup"><span data-stu-id="95555-109">For any policy change you need to wait at least 4 hours and up to 24 hours for the policies to take effect.</span></span>

<span data-ttu-id="95555-110">Uverite se da ste pregledali dokumentaciju ispod pre nego što napravite ove promene da biste razumeli tačno šta to dozvoljava.</span><span class="sxs-lookup"><span data-stu-id="95555-110">Be sure to review the documentation below before making these changes to understand exactly what this allows.</span></span>

## <a name="understanding-teams-meeting-lobby-policy-controls"></a><span data-ttu-id="95555-111">Razumevanje timova sa kontrolama lobira za sastanke</span><span class="sxs-lookup"><span data-stu-id="95555-111">Understanding Teams meeting lobby policy controls</span></span>

- <span data-ttu-id="95555-112">[Automatsko priznate osobe](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) su smernice po organizatoru koje kontrolišu da li se osobe direktno pridružuju sastanku ili čekaju u predvorju dok ih ne primi ovlašćeni korisnik.</span><span class="sxs-lookup"><span data-stu-id="95555-112">[Automatically admit people](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) is a per-organizer policy that controls whether people join a meeting directly or wait in the lobby until they are admitted by an authenticated user.</span></span>

- <span data-ttu-id="95555-113">[Dozvoljavanje anonimnim osobama da započnu sastanak](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) je smernica po organizatoru koja kontroliše da li anonimni ljudi, uključujući B2B i federovane korisnike, mogu da se pridruže korisničkom sastanku bez autorizovanog korisnika iz organizacije.</span><span class="sxs-lookup"><span data-stu-id="95555-113">[Allow anonymous people to start a meeting](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) is a per-organizer policy that controls whether anonymous people, including B2B and federated users, can join the user's meeting without an authenticated user from the organization in attendance.</span></span>

- <span data-ttu-id="95555-114">[Dozvoli korisnicima biranja broja da zaobiđu lobi](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**uskoro**) je smernica po organizatoru koja kontroliše da li se osobe koje se nalaze na telefonu pridružuju sastanku direktno ili čekaju u predvorju bez obzira na **Automatsko priznate postavke osobe** .</span><span class="sxs-lookup"><span data-stu-id="95555-114">[Allow dial-in users to bypass the lobby](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**coming soon**) is a per-organizer policy that controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the **Automatically admit people** setting.</span></span>

- <span data-ttu-id="95555-115">[Dozvoli organizatorima da zamene "Postavljanje](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) " (**uskoro**) je smernica po organizatoru koja kontroliše da li organizator sastanka može da zameni postavke za uvodnu postavku koju je administrator postavio u **Automatski primi osobe** i **Dozvoli pozivnu vezu korisnici zaobilaze lobi** kada planiraju novi sastanak.</span><span class="sxs-lookup"><span data-stu-id="95555-115">[Allow organizers to override lobby settings](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**coming soon**) is a per-organizer policy that controls whether the meeting organizer can override the lobby settings that an admin set in **Automatically admit people** and **Allow dial-in users to bypass the lobby** when they schedule a new meeting.</span></span>

<span data-ttu-id="95555-116">**Napomena:** Pročitajte [Upravljanje smernicama za sastanak u timovima](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) za kompletan pregled smernica za sastanke Microsoft timova.</span><span class="sxs-lookup"><span data-stu-id="95555-116">**Note:** Read [Manage meeting policies in Teams](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) for a complete overview of Microsoft Teams meeting policies.</span></span>