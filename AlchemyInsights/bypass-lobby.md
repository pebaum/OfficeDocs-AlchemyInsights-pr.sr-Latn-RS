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
# <a name="control-lobby-settings-and-level-of-participation"></a>Kontrola uvodnog postavljanja i nivoa učestvovanja

Ove postavke kontrolišu koji učesnici sastanka čekaju u predvorju pre nego što budu primljeni na sastanak i nivo učešća koji su dozvoljeni na sastanku. Možete koristiti funkciju PowerShell da biste ažurirali postavke smernica za sastanke koje još uvek nisu primenjene (sa oznakom "dolazak uskoro") u okviru administratorskog centra timova.  Pogledajte niže na primer, fascikla PowerShell cmdtime koja omogućava svim korisnicima da zaobiđu lobiranje.  

- [Automatsko priznate osobe](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) su smernice po organizatoru koje kontrolišu da li se osobe direktno pridružuju sastanku ili čekaju u predvorju dok ih ne primi ovlašćeni korisnik.

- [Dozvoljavanje anonimnim osobama da započnu sastanak](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) je smernica po organizatoru koja kontroliše da li anonimni ljudi, uključujući B2B i federovane korisnike, mogu da se pridruže korisničkom sastanku bez autorizovanog korisnika iz organizacije.

- [Dozvoli korisnicima biranja broja da zaobiđu lobi](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**uskoro**) je smernica po organizatoru koja kontroliše da li se osobe koje se nalaze na telefonu pridružuju sastanku direktno ili čekaju u predvorju bez obzira na **Automatsko priznate postavke osobe** .

- [Dozvoli organizatorima da zamene "Postavljanje](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) " (**uskoro**) je smernica po organizatoru koja kontroliše da li organizator sastanka može da zameni postavke za uvodnu postavku koju je administrator postavio u **Automatski primi osobe** i **Dozvoli pozivnu vezu korisnici zaobilaze lobi** kada planiraju novi sastanak.

**Napomena:** Pročitajte [Upravljanje smernicama za sastanak u timovima](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) za kompletan pregled smernica za sastanke Microsoft timova. 


**Primer PowerShell**

Ako želite da dozvolite svima, uključujući spoljne ili anonimne korisnike, da zaobiđete lobi, možete da koristite i funkciju PowerShell da biste izvršili ovaj zadatak.  Evo primera menjanja globalnih smernica za sastanak za vašu organizaciju.   

(Obavezno Pregledajte gorenavedenu dokumentaciju pre nego što napravite ove promene da biste razumeli tačno šta to dozvoljava.)

Set-CsTeamsMeetingPolicy-identitet Global-Autoprijem-korisnici "svi"-Allowpstnuserstobypasslob$TRUE

Više informacija potražite u članku [Set-CsTeamsMeetingPolicy](https://docs.microsoft.com/powershell/module/skype/set-csteamsmeetingpolicy?view=skype-ps).
