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
ms.openlocfilehash: 311af365a94b788182bb6870bca3f67b2ad802d0
ms.sourcegitcommit: 932981641dd8e973e28dfe346bbdf9c923111b13
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/27/2019
ms.locfileid: "40889096"
---
# <a name="control-lobby-settings-and-level-of-participation-in-teams"></a><span data-ttu-id="39fe2-102">Kontrola uvodnog postavljanja i nivo učešća u timovima</span><span class="sxs-lookup"><span data-stu-id="39fe2-102">Control lobby settings and level of participation in Teams</span></span>

<span data-ttu-id="39fe2-103">Ako želite da dozvolite svima, uključujući pozivne, spoljne i anonimne korisnike, da **zaobiđete lobi**, koristite funkciju PowerShell da biste izvršili ovaj zadatak.</span><span class="sxs-lookup"><span data-stu-id="39fe2-103">If you'd like to allow everyone, including Dial-in, external, and anonymous users, to **bypass the lobby**, use PowerShell to accomplish this task.</span></span> <span data-ttu-id="39fe2-104">Evo primera menjanja globalnih smernica za sastanak za vašu organizaciju.</span><span class="sxs-lookup"><span data-stu-id="39fe2-104">Here's an example of modifying the global meeting policy for your organization.</span></span>

`Set-CsTeamsMeetingPolicy -Identity Global -AutoAdmittedUsers "Everyone" -AllowPSTNUsersToBypassLobby $True`

<span data-ttu-id="39fe2-105">Ova cmdda je trenutno potrebna upotreba Skype-a za modul Business PowerShell.</span><span class="sxs-lookup"><span data-stu-id="39fe2-105">This cmdlet currently requires the use of Skype for Business PowerShell module.</span></span> <span data-ttu-id="39fe2-106">Da biste se konfigurisali za korišćenje ove cmdme komande, pogledajte [Upravljanje smernicama putem PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview#managing-policies-via-powershell).</span><span class="sxs-lookup"><span data-stu-id="39fe2-106">To get set up to use this cmdlet, check out [Managing policies via PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview#managing-policies-via-powershell).</span></span>

<span data-ttu-id="39fe2-107">Kada podesite smernice, potrebno je da je primenite na korisnike; ili, ako ste izmenili globalnu smernicu, ona će se automatski primenjivati na korisnike.</span><span class="sxs-lookup"><span data-stu-id="39fe2-107">Once you’ve set up a policy, you need to apply it to users; or, if you modified the Global policy, it will automatically apply to users.</span></span> <span data-ttu-id="39fe2-108">Za sve promene u smernicama, potrebno je da sačekate najmanje **4 sata do 24 časa** da bi smernice stupile na snagu.</span><span class="sxs-lookup"><span data-stu-id="39fe2-108">For any policy change, you need to wait at least **4 hours up to 24 hours** for the policies to take effect.</span></span> 

<span data-ttu-id="39fe2-109">Uverite se da ste pregledali dokumentaciju ispod pre nego što napravite ove promene da biste razumeli tačno šta to dozvoljava.</span><span class="sxs-lookup"><span data-stu-id="39fe2-109">Be sure to review the documentation below before making these changes to understand exactly what this allows.</span></span>


## <a name="understanding-teams-meeting-lobby-policy-controls"></a><span data-ttu-id="39fe2-110">Razumevanje timova sa kontrolama lobira za sastanke</span><span class="sxs-lookup"><span data-stu-id="39fe2-110">Understanding Teams meeting lobby policy controls</span></span>

<span data-ttu-id="39fe2-111">Ove postavke kontrolišu koji učesnici sastanka čekaju u predvorju pre nego što budu primljeni na sastanak i nivo učešća koji su dozvoljeni na sastanku.</span><span class="sxs-lookup"><span data-stu-id="39fe2-111">These settings control which meeting participants wait in the lobby before they are admitted to the meeting and the level of participation they are allowed in a meeting.</span></span> <span data-ttu-id="39fe2-112">Možete koristiti funkciju PowerShell da biste ažurirali postavke smernica za sastanke koje još uvek nisu primenjene (sa oznakom "dolazak uskoro") u okviru administratorskog centra timova.</span><span class="sxs-lookup"><span data-stu-id="39fe2-112">You can use PowerShell to update meeting policy settings that haven't yet been implemented (labeled "coming soon") in the Teams admin center.</span></span> <span data-ttu-id="39fe2-113">Pogledajte niže na primer, fascikla PowerShell cmdtime koja omogućava svim korisnicima da zaobiđu lobiranje.</span><span class="sxs-lookup"><span data-stu-id="39fe2-113">See below for an example PowerShell cmdlet that allows all users to bypass the lobby.</span></span>

- <span data-ttu-id="39fe2-114">[Automatsko priznate osobe](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) su smernice po organizatoru koje kontrolišu da li se osobe direktno pridružuju sastanku ili čekaju u predvorju dok ih ne primi ovlašćeni korisnik.</span><span class="sxs-lookup"><span data-stu-id="39fe2-114">[Automatically admit people](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) is a per-organizer policy that controls whether people join a meeting directly or wait in the lobby until they are admitted by an authenticated user.</span></span>

- <span data-ttu-id="39fe2-115">[Dozvoljavanje anonimnim osobama da započnu sastanak](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) je smernica po organizatoru koja kontroliše da li anonimni ljudi, uključujući B2B i federovane korisnike, mogu da se pridruže korisničkom sastanku bez autorizovanog korisnika iz organizacije.</span><span class="sxs-lookup"><span data-stu-id="39fe2-115">[Allow anonymous people to start a meeting](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) is a per-organizer policy that controls whether anonymous people, including B2B and federated users, can join the user's meeting without an authenticated user from the organization in attendance.</span></span>

- <span data-ttu-id="39fe2-116">[Dozvoli korisnicima biranja broja da zaobiđu lobi](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**uskoro**) je smernica po organizatoru koja kontroliše da li se osobe koje se nalaze na telefonu pridružuju sastanku direktno ili čekaju u predvorju bez obzira na **Automatsko priznate postavke osobe** .</span><span class="sxs-lookup"><span data-stu-id="39fe2-116">[Allow dial-in users to bypass the lobby](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**coming soon**) is a per-organizer policy that controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the **Automatically admit people** setting.</span></span>

- <span data-ttu-id="39fe2-117">[Dozvolite organizatorima da zamene "Postavljanje](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) " (**uskoro**) je smernica po organizatoru koja kontroliše da li organizator sastanka može da zameni postavke lobiraju koje je administrator postavio u **Automatski primi osobe** i **Dozvoli korisnicima biranja broja da zaobiđu lobiste** kada planiraju novi sastanak.</span><span class="sxs-lookup"><span data-stu-id="39fe2-117">[Allow organizers to override lobby settings](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**coming soon**) is a per-organizer policy that controls whether the meeting organizer can override the lobby settings that an admin set in **Automatically admit people** and **Allow dial-in users to bypass the lobby** when they schedule a new meeting.</span></span>

<span data-ttu-id="39fe2-118">**Napomena:** Pročitajte [Upravljanje smernicama za sastanak u timovima](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams) za kompletan pregled smernica za sastanke Microsoft timova.</span><span class="sxs-lookup"><span data-stu-id="39fe2-118">**Note:** Read [Manage meeting policies in Teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams) for a complete overview of Microsoft Teams meeting policies.</span></span>
