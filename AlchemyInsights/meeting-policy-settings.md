---
title: Postavke smernica za sastanke
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2657"
- "9000734"
ms.openlocfilehash: b5599c9974eb1c112835a9f42e4ebdc926071ea2
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/27/2019
ms.locfileid: "39627588"
---
# <a name="manage-meeting-policies-in-microsoft-teams"></a>Upravljanje smernicama za sastanke u Microsoft timovima

Smernice za sastanke se koriste za kontrolisanje funkcija koje su dostupne učesnicima sastanka za sastanke koje su zakazali korisnici u vašoj organizaciji. Neke funkcije smernica za sastanak možda neće biti primenjene u okviru administratorskog centra tima (one su označene kao "stižu uskoro" u dokumentaciji). U ovom slučaju, ili ako dobijate grešku kao što je "trenutno ne možemo da ažuriramo smernicu ali pokušajte ponovo kasnije" u okviru administratorskog centra Microsoft timova, preporučujemo da koristite funkciju PowerShell da biste kreirali ili izmenili smernice za sastanke timova. 

Za više informacija o smernicama za sastanke pogledajte sledeće resurse:

- Da biste saznali više o kreiranju smernica, pravljenju promena i dodeljivanju korisnika smernicama, pogledajte odeljak [Upravljanje smernicama za sastanke u timovima](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).

- Da biste izmenili smernice pomoću funkcije PowerShell cmdlet, pogledajte odeljak pregled smernica za [timove](https://docs.microsoft.com/microsoftteams/teams-powershell-overview). 
    - Potrebno je da koristite [modul Skype za poslovno PowerShell](https://www.microsoft.com/download/details.aspx?id=39366) za smernice za sastanke timova. 
    - Pregledajte [dokumentaciju *-CsTeamsMeetingPolicy cmdlet](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) za više informacija.

**Napomena:** Za korisnike može biti potrebno najviše 24 časa da bi promene stupile na snagu. Možda nećete moći odmah da unesete promene u novokreirane smernice; Sačekajte 4 sata i pokušajte ponovo da izmenite novokreiranu smernicu. Ako i dalje imate problema, pokušajte da imate kućište.  