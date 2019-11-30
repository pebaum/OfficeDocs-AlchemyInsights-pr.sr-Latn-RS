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
# <a name="manage-meeting-policies-in-microsoft-teams"></a><span data-ttu-id="1db0d-102">Upravljanje smernicama za sastanke u Microsoft timovima</span><span class="sxs-lookup"><span data-stu-id="1db0d-102">Manage meeting policies in Microsoft Teams</span></span>

<span data-ttu-id="1db0d-103">Smernice za sastanke se koriste za kontrolisanje funkcija koje su dostupne učesnicima sastanka za sastanke koje su zakazali korisnici u vašoj organizaciji.</span><span class="sxs-lookup"><span data-stu-id="1db0d-103">Meeting policies are used to control the features that are available to meeting participants for meetings that are scheduled by users in your organization.</span></span> <span data-ttu-id="1db0d-104">Neke funkcije smernica za sastanak možda neće biti primenjene u okviru administratorskog centra tima (one su označene kao "stižu uskoro" u dokumentaciji).</span><span class="sxs-lookup"><span data-stu-id="1db0d-104">Some features of meeting policies might not be implemented in the Teams admin center yet (these are labeled "coming soon" in the documentation).</span></span> <span data-ttu-id="1db0d-105">U ovom slučaju, ili ako dobijate grešku kao što je "trenutno ne možemo da ažuriramo smernicu ali pokušajte ponovo kasnije" u okviru administratorskog centra Microsoft timova, preporučujemo da koristite funkciju PowerShell da biste kreirali ili izmenili smernice za sastanke timova.</span><span class="sxs-lookup"><span data-stu-id="1db0d-105">In this case, or if you are getting an error like "We can't update the policy right now but try it again later" in the Microsoft Teams admin center, we recommend that you use PowerShell to create or modify Teams meeting policies.</span></span> 

<span data-ttu-id="1db0d-106">Za više informacija o smernicama za sastanke pogledajte sledeće resurse:</span><span class="sxs-lookup"><span data-stu-id="1db0d-106">For more information about meeting policies, see the following resources:</span></span>

- <span data-ttu-id="1db0d-107">Da biste saznali više o kreiranju smernica, pravljenju promena i dodeljivanju korisnika smernicama, pogledajte odeljak [Upravljanje smernicama za sastanke u timovima](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).</span><span class="sxs-lookup"><span data-stu-id="1db0d-107">To learn about creating policies, making changes, and assigning users to the policy, see [Manage meeting policies in Teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).</span></span>

- <span data-ttu-id="1db0d-108">Da biste izmenili smernice pomoću funkcije PowerShell cmdlet, pogledajte odeljak pregled smernica za [timove](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span><span class="sxs-lookup"><span data-stu-id="1db0d-108">To make policy changes using PowerShell cmdlets, see [Teams PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span></span> 
    - <span data-ttu-id="1db0d-109">Potrebno je da koristite [modul Skype za poslovno PowerShell](https://www.microsoft.com/download/details.aspx?id=39366) za smernice za sastanke timova.</span><span class="sxs-lookup"><span data-stu-id="1db0d-109">You need to use the [Skype for Business PowerShell module](https://www.microsoft.com/download/details.aspx?id=39366) for Teams meeting policies.</span></span> 
    - <span data-ttu-id="1db0d-110">Pregledajte [dokumentaciju \*-CsTeamsMeetingPolicy cmdlet](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) za više informacija.</span><span class="sxs-lookup"><span data-stu-id="1db0d-110">Review the [\*-CsTeamsMeetingPolicy cmdlets documentation](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) for more information.</span></span>

<span data-ttu-id="1db0d-111">**Napomena:** Za korisnike može biti potrebno najviše 24 časa da bi promene stupile na snagu.</span><span class="sxs-lookup"><span data-stu-id="1db0d-111">**Note:** It can take up to 24 hours for policy changes to take effect for users.</span></span> <span data-ttu-id="1db0d-112">Možda nećete moći odmah da unesete promene u novokreirane smernice; Sačekajte 4 sata i pokušajte ponovo da izmenite novokreiranu smernicu.</span><span class="sxs-lookup"><span data-stu-id="1db0d-112">You might not be able to make changes to newly created policies immediately; wait 4 hours and attempt to modify a newly created policy again.</span></span> <span data-ttu-id="1db0d-113">Ako i dalje imate problema, pokušajte da imate kućište.</span><span class="sxs-lookup"><span data-stu-id="1db0d-113">If you're still having problems, try PowerShell.</span></span>  