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
ms.openlocfilehash: de665ca6defcd0d00d227435473e5a4ccf61bc82
ms.sourcegitcommit: 0495112ad4fd0e695140ec66d190e62f03030584
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/02/2019
ms.locfileid: "37376813"
---
# <a name="control-lobby-settings-and-level-of-participation"></a><span data-ttu-id="b8456-102">Kontrola uvodnog postavljanja i nivoa učestvovanja</span><span class="sxs-lookup"><span data-stu-id="b8456-102">Control lobby settings and level of participation</span></span>

<span data-ttu-id="b8456-103">Ove postavke kontrolišu koji učesnici sastanka čekaju u predvorju pre nego što budu primljeni na sastanak i nivo učešća koji su dozvoljeni na sastanku.</span><span class="sxs-lookup"><span data-stu-id="b8456-103">These settings control which meeting participants wait in the lobby before they are admitted to the meeting and the level of participation they are allowed in a meeting.</span></span> <span data-ttu-id="b8456-104">Možete koristiti funkciju PowerShell da biste ažurirali postavke smernica za sastanke koje još uvek nisu primenjene (sa oznakom "dolazak uskoro") u okviru administratorskog centra timova.</span><span class="sxs-lookup"><span data-stu-id="b8456-104">You can use Powershell to update meeting policy settings that haven't yet been implemented (labeled "coming soon") in the Teams admin center.</span></span>  <span data-ttu-id="b8456-105">Pogledajte niže na primer, fascikla PowerShell cmdtime koja omogućava svim korisnicima da zaobiđu lobiranje.</span><span class="sxs-lookup"><span data-stu-id="b8456-105">See below for an example PowerShell cmdlet that allows all users to bypass the lobby.</span></span>  

- <span data-ttu-id="b8456-106">[Automatsko priznate osobe](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) su smernice po organizatoru koje kontrolišu da li se osobe direktno pridružuju sastanku ili čekaju u predvorju dok ih ne primi ovlašćeni korisnik.</span><span class="sxs-lookup"><span data-stu-id="b8456-106">[Automatically admit people](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) is a per-organizer policy that controls whether people join a meeting directly or wait in the lobby until they are admitted by an authenticated user.</span></span>

- <span data-ttu-id="b8456-107">[Dozvoljavanje anonimnim osobama da započnu sastanak](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) je smernica po organizatoru koja kontroliše da li anonimni ljudi, uključujući B2B i federovane korisnike, mogu da se pridruže korisničkom sastanku bez autorizovanog korisnika iz organizacije.</span><span class="sxs-lookup"><span data-stu-id="b8456-107">[Allow anonymous people to start a meeting](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) is a per-organizer policy that controls whether anonymous people, including B2B and federated users, can join the user's meeting without an authenticated user from the organization in attendance.</span></span>

- <span data-ttu-id="b8456-108">[Dozvoli korisnicima biranja broja da zaobiđu lobi](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**uskoro**) je smernica po organizatoru koja kontroliše da li se osobe koje se nalaze na telefonu pridružuju sastanku direktno ili čekaju u predvorju bez obzira na **Automatsko priznate postavke osobe** .</span><span class="sxs-lookup"><span data-stu-id="b8456-108">[Allow dial-in users to bypass the lobby](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**coming soon**) is a per-organizer policy that controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the **Automatically admit people** setting.</span></span>

- <span data-ttu-id="b8456-109">[Dozvoli organizatorima da zamene "Postavljanje](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) " (**uskoro**) je smernica po organizatoru koja kontroliše da li organizator sastanka može da zameni postavke za uvodnu postavku koju je administrator postavio u **Automatski primi osobe** i **Dozvoli pozivnu vezu korisnici zaobilaze lobi** kada planiraju novi sastanak.</span><span class="sxs-lookup"><span data-stu-id="b8456-109">[Allow organizers to override lobby settings](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**coming soon**) is a per-organizer policy that controls whether the meeting organizer can override the lobby settings that an admin set in **Automatically admit people** and **Allow dial-in users to bypass the lobby** when they schedule a new meeting.</span></span>

<span data-ttu-id="b8456-110">**Napomena:** Pročitajte [Upravljanje smernicama za sastanak u timovima](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) za kompletan pregled smernica za sastanke Microsoft timova.</span><span class="sxs-lookup"><span data-stu-id="b8456-110">**Note:** Read [Manage meeting policies in Teams](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) for a complete overview of Microsoft Teams meeting policies.</span></span> 


<span data-ttu-id="b8456-111">**Primer PowerShell**</span><span class="sxs-lookup"><span data-stu-id="b8456-111">**PowerShell example**</span></span>

<span data-ttu-id="b8456-112">Ako želite da dozvolite svima, uključujući spoljne ili anonimne korisnike, da zaobiđete lobi, možete da koristite i funkciju PowerShell da biste izvršili ovaj zadatak.</span><span class="sxs-lookup"><span data-stu-id="b8456-112">If you'd like to allow everyone, including external or anonymous users, to bypass the lobby, you can also use PowerShell to accomplish this task.</span></span>  <span data-ttu-id="b8456-113">Evo primera menjanja globalnih smernica za sastanak za vašu organizaciju.</span><span class="sxs-lookup"><span data-stu-id="b8456-113">Here's an example of modifying the global meeting policy for your organization.</span></span>   

<span data-ttu-id="b8456-114">(Obavezno Pregledajte gorenavedenu dokumentaciju pre nego što napravite ove promene da biste razumeli tačno šta to dozvoljava.)</span><span class="sxs-lookup"><span data-stu-id="b8456-114">(Be sure to review the documentation above before making these changes to understand exactly what this allows.)</span></span>

<span data-ttu-id="b8456-115">Set-CsTeamsMeetingPolicy-identitet Global-Autoprijem-korisnici "svi"-Allowpstnuserstobypasslob$TRUE</span><span class="sxs-lookup"><span data-stu-id="b8456-115">Set-CsTeamsMeetingPolicy -Identity Global -AutoAdmittedUsers "Everyone" -AllowPSTNUsersToBypassLobby $True</span></span>

<span data-ttu-id="b8456-116">Više informacija potražite u članku [Set-CsTeamsMeetingPolicy](https://docs.microsoft.com/powershell/module/skype/set-csteamsmeetingpolicy?view=skype-ps).</span><span class="sxs-lookup"><span data-stu-id="b8456-116">For more information, see [Set-CsTeamsMeetingPolicy](https://docs.microsoft.com/powershell/module/skype/set-csteamsmeetingpolicy?view=skype-ps).</span></span>
