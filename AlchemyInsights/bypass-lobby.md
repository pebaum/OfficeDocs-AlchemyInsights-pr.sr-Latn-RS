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
# <a name="control-lobby-settings-and-level-of-participation-in-teams"></a>Kontrola uvodnog postavljanja i nivo učešća u timovima

Ako želite da dozvolite svima, uključujući pozivne, spoljne i anonimne korisnike, da **zaobiđete lobi**, koristite funkciju PowerShell da biste izvršili ovaj zadatak. Evo primera menjanja globalnih smernica za sastanak za vašu organizaciju.

`Set-CsTeamsMeetingPolicy -Identity Global -AutoAdmittedUsers "Everyone" -AllowPSTNUsersToBypassLobby $True`

Ova cmdda je trenutno potrebna upotreba Skype-a za modul Business PowerShell. Da biste se konfigurisali za korišćenje ove cmdme komande, pogledajte [Upravljanje smernicama putem PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview#managing-policies-via-powershell).

Kada podesite smernice, potrebno je da je primenite na korisnike; ili, ako ste izmenili globalnu smernicu, ona će se automatski primenjivati na korisnike. Za sve promene u smernicama, potrebno je da sačekate najmanje **4 sata do 24 časa** da bi smernice stupile na snagu. 

Uverite se da ste pregledali dokumentaciju ispod pre nego što napravite ove promene da biste razumeli tačno šta to dozvoljava.


## <a name="understanding-teams-meeting-lobby-policy-controls"></a>Razumevanje timova sa kontrolama lobira za sastanke

Ove postavke kontrolišu koji učesnici sastanka čekaju u predvorju pre nego što budu primljeni na sastanak i nivo učešća koji su dozvoljeni na sastanku. Možete koristiti funkciju PowerShell da biste ažurirali postavke smernica za sastanke koje još uvek nisu primenjene (sa oznakom "dolazak uskoro") u okviru administratorskog centra timova. Pogledajte niže na primer, fascikla PowerShell cmdtime koja omogućava svim korisnicima da zaobiđu lobiranje.

- [Automatsko priznate osobe](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) su smernice po organizatoru koje kontrolišu da li se osobe direktno pridružuju sastanku ili čekaju u predvorju dok ih ne primi ovlašćeni korisnik.

- [Dozvoljavanje anonimnim osobama da započnu sastanak](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) je smernica po organizatoru koja kontroliše da li anonimni ljudi, uključujući B2B i federovane korisnike, mogu da se pridruže korisničkom sastanku bez autorizovanog korisnika iz organizacije.

- [Dozvoli korisnicima biranja broja da zaobiđu lobi](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**uskoro**) je smernica po organizatoru koja kontroliše da li se osobe koje se nalaze na telefonu pridružuju sastanku direktno ili čekaju u predvorju bez obzira na **Automatsko priznate postavke osobe** .

- [Dozvolite organizatorima da zamene "Postavljanje](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) " (**uskoro**) je smernica po organizatoru koja kontroliše da li organizator sastanka može da zameni postavke lobiraju koje je administrator postavio u **Automatski primi osobe** i **Dozvoli korisnicima biranja broja da zaobiđu lobiste** kada planiraju novi sastanak.

**Napomena:** Pročitajte [Upravljanje smernicama za sastanak u timovima](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams) za kompletan pregled smernica za sastanke Microsoft timova.
