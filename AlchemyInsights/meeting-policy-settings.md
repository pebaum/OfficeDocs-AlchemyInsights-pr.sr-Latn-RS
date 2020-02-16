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
- "9000734"
- "2657"
ms.openlocfilehash: 509bd0c686830c04ed27f97372411677c0a7f4a4
ms.sourcegitcommit: 9aaa61d717e0fd475d2e9f0507c42aa40d073b5f
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/15/2020
ms.locfileid: "42042858"
---
# <a name="manage-meeting-policies-in-microsoft-teams"></a><span data-ttu-id="dafe0-102">Upravljanje smernicama za sastanke u Microsoft timovima</span><span class="sxs-lookup"><span data-stu-id="dafe0-102">Manage meeting policies in Microsoft Teams</span></span>

<span data-ttu-id="dafe0-103">**Napomena: do 24 časa može da se promeni promena za korisnike.**</span><span class="sxs-lookup"><span data-stu-id="dafe0-103">**Note: It can take up to 24 hours for policy changes to take effect for users.**</span></span> <span data-ttu-id="dafe0-104">Možda nećete moći odmah da unesete promene u novokreirane smernice; Sačekajte 4 sata i pokušajte ponovo da izmenite novokreiranu smernicu.</span><span class="sxs-lookup"><span data-stu-id="dafe0-104">You might not be able to make changes to newly created policies immediately; wait 4 hours and attempt to modify a newly created policy again.</span></span>

<span data-ttu-id="dafe0-105">Smernice za sastanke se koriste za kontrolisanje funkcija koje su dostupne učesnicima sastanka za sastanke koje su zakazali korisnici u vašoj organizaciji.</span><span class="sxs-lookup"><span data-stu-id="dafe0-105">Meeting policies are used to control the features that are available to meeting participants for meetings that are scheduled by users in your organization.</span></span> <span data-ttu-id="dafe0-106">Neke funkcije smernica za sastanak možda neće biti primenjene u okviru administratorskog centra tima (one su označene kao "stižu uskoro" u dokumentaciji).</span><span class="sxs-lookup"><span data-stu-id="dafe0-106">Some features of meeting policies might not be implemented in the Teams admin center yet (these are labeled "coming soon" in the documentation).</span></span> <span data-ttu-id="dafe0-107">U ovom slučaju, ili ako dobijate grešku kao što je "trenutno ne možemo da ažuriramo smernicu ali pokušajte ponovo kasnije" u okviru administratorskog centra Microsoft timova, preporučujemo da koristite funkciju PowerShell da biste kreirali ili izmenili smernice za sastanke timova.</span><span class="sxs-lookup"><span data-stu-id="dafe0-107">In this case, or if you are getting an error like "We can't update the policy right now but try it again later" in the Microsoft Teams admin center, we recommend that you use PowerShell to create or modify Teams meeting policies.</span></span> 

<span data-ttu-id="dafe0-108">Za više informacija o smernicama za sastanke pogledajte sledeće resurse:</span><span class="sxs-lookup"><span data-stu-id="dafe0-108">For more information about meeting policies, see the following resources:</span></span>

- <span data-ttu-id="dafe0-109">Da biste saznali više o kreiranju smernica, pravljenju promena i dodeljivanju korisnika smernicama, pogledajte odeljak [Upravljanje smernicama za sastanke u timovima](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).</span><span class="sxs-lookup"><span data-stu-id="dafe0-109">To learn about creating policies, making changes, and assigning users to the policy, see [Manage meeting policies in Teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).</span></span>

- <span data-ttu-id="dafe0-110">Da biste izmenili smernice pomoću funkcije PowerShell cmdlet, pogledajte odeljak pregled smernica za [timove](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span><span class="sxs-lookup"><span data-stu-id="dafe0-110">To make policy changes using PowerShell cmdlets, see [Teams PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span></span> 
    - <span data-ttu-id="dafe0-111">Potrebno je da koristite [modul Skype za poslovno PowerShell](https://www.microsoft.com/download/details.aspx?id=39366) za smernice za sastanke timova.</span><span class="sxs-lookup"><span data-stu-id="dafe0-111">You need to use the [Skype for Business PowerShell module](https://www.microsoft.com/download/details.aspx?id=39366) for Teams meeting policies.</span></span> 
    - <span data-ttu-id="dafe0-112">Pregledajte [dokumentaciju \*-CsTeamsMeetingPolicy cmdlet](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) za više informacija.</span><span class="sxs-lookup"><span data-stu-id="dafe0-112">Review the [\*-CsTeamsMeetingPolicy cmdlets documentation](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) for more information.</span></span>

