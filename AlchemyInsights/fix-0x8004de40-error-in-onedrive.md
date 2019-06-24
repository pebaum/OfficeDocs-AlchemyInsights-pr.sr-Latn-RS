---
title: Popravljanje greške 0x8004de40 u OneDrive
ms.author: kirks
author: Techwriter40
ms.date: 6/20/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 2256fb66cb7a4e2adcff9fda16a80c87e2997f0c
ms.sourcegitcommit: 8f6a1be929b275faa295ba8aeeae17898a47c3b0
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/21/2019
ms.locfileid: "35133990"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a><span data-ttu-id="e338b-102">Popravljanje greške 0x8004de40 u OneDrive</span><span class="sxs-lookup"><span data-stu-id="e338b-102">Fix 0x8004de40 error in OneDrive</span></span>

<span data-ttu-id="e338b-103">Ako dobijete grešku "0x8004de40" sa OneDrive:</span><span class="sxs-lookup"><span data-stu-id="e338b-103">If you receive an 0x8004de40 error with OneDrive:</span></span>

- <span data-ttu-id="e338b-104">Ponovo pokrenite problematično računalo dok ste povezani sa simpozijima Directory domena.</span><span class="sxs-lookup"><span data-stu-id="e338b-104">Reboot the affected computer while connected to your Acitve Directory domain.</span></span>
- <span data-ttu-id="e338b-105">Ako ponovno pokretanje sistema ne reši problem, odvajanja i da se vratite u vaš uređaj sa azurno reklame.</span><span class="sxs-lookup"><span data-stu-id="e338b-105">If a reboot doesn't fix the issue, unjoin and rejoin your device from Azure AD.</span></span> 

<span data-ttu-id="e338b-106">**Napomena**: treba da si na korporativnoj mreži tokom izvršavanja ovih koraka.</span><span class="sxs-lookup"><span data-stu-id="e338b-106">**Note**: You should be on your corporate network while performing these steps.</span></span> <span data-ttu-id="e338b-107">Nemoj da izvršite ove korake kada ne možete da se povežete sa svoje korporativne infrastrukture (na primer, dok putujete).</span><span class="sxs-lookup"><span data-stu-id="e338b-107">Don't perform these steps when you aren't able to connect to your corporate infrastructure (for example, while traveling).</span></span> 

- <span data-ttu-id="e338b-108">Otvorite komandnoj liniji.</span><span class="sxs-lookup"><span data-stu-id="e338b-108">Open an elevated command prompt.</span></span> 
- <span data-ttu-id="e338b-109">Da biste otvorili u komandnoj liniji, kliknite na dugme - **Start**, desnom tipkom miša kliknite **naredbeni redak**i zatim kliknite na dugme **Pokreni kao administrator**.</span><span class="sxs-lookup"><span data-stu-id="e338b-109">To open an elevated command prompt, click - **Start**, right-click **Command Prompt**, and then click **Run as administrator**.</span></span>
- <span data-ttu-id="e338b-110">Upišite *dsregcmd /leave* i pritisnite **Enter**.</span><span class="sxs-lookup"><span data-stu-id="e338b-110">Type *dsregcmd /leave* and press **Enter**.</span></span>
- <span data-ttu-id="e338b-111">Kada bude završena, upišite *dsregcmd /join* i pritisnite **Enter**.</span><span class="sxs-lookup"><span data-stu-id="e338b-111">When complete, type *dsregcmd /join* and press **Enter**.</span></span>
- <span data-ttu-id="e338b-112">Kada bude završena, zatvorite naredbeni redak.</span><span class="sxs-lookup"><span data-stu-id="e338b-112">When complete, close the command prompt.</span></span>
- <span data-ttu-id="e338b-113">Ponovo pokrenite računalo i prijavite se na OneDrive.</span><span class="sxs-lookup"><span data-stu-id="e338b-113">Reboot the computer, and log into OneDrive.</span></span>