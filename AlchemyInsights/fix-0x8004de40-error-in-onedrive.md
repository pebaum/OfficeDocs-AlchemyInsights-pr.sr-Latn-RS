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
ms.openlocfilehash: d436184bdc0e283db217ea734fb2c8e05f85b4e7
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36525073"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a><span data-ttu-id="4ef3f-102">Popravljanje greške 0x8004de40 u OneDrive</span><span class="sxs-lookup"><span data-stu-id="4ef3f-102">Fix 0x8004de40 error in OneDrive</span></span>

<span data-ttu-id="4ef3f-103">Ako dobijete grešku "0x8004de40" sa OneDrive:</span><span class="sxs-lookup"><span data-stu-id="4ef3f-103">If you receive an 0x8004de40 error with OneDrive:</span></span>

- <span data-ttu-id="4ef3f-104">Ponovo pokrenite problematično računalo dok ste povezani sa simpozijima Directory domena.</span><span class="sxs-lookup"><span data-stu-id="4ef3f-104">Reboot the affected computer while connected to your Acitve Directory domain.</span></span>
- <span data-ttu-id="4ef3f-105">Ako ponovno pokretanje sistema ne reši problem, odvajanja i da se vratite u vaš uređaj sa azurno reklame.</span><span class="sxs-lookup"><span data-stu-id="4ef3f-105">If a reboot doesn't fix the issue, unjoin and rejoin your device from Azure AD.</span></span> 

<span data-ttu-id="4ef3f-106">**Napomena**: treba da si na korporativnoj mreži tokom izvršavanja ovih koraka.</span><span class="sxs-lookup"><span data-stu-id="4ef3f-106">**Note**: You should be on your corporate network while performing these steps.</span></span> <span data-ttu-id="4ef3f-107">Nemoj da izvršite ove korake kada ne možete da se povežete sa svoje korporativne infrastrukture (na primer, dok putujete).</span><span class="sxs-lookup"><span data-stu-id="4ef3f-107">Don't perform these steps when you aren't able to connect to your corporate infrastructure (for example, while traveling).</span></span> 

- <span data-ttu-id="4ef3f-108">Otvorite komandnoj liniji.</span><span class="sxs-lookup"><span data-stu-id="4ef3f-108">Open an elevated command prompt.</span></span> 
- <span data-ttu-id="4ef3f-109">Da biste otvorili u komandnoj liniji, kliknite na dugme - **Start**, desnom tipkom miša kliknite **naredbeni redak**i zatim kliknite na dugme **Pokreni kao administrator**.</span><span class="sxs-lookup"><span data-stu-id="4ef3f-109">To open an elevated command prompt, click - **Start**, right-click **Command Prompt**, and then click **Run as administrator**.</span></span>
- <span data-ttu-id="4ef3f-110">Upišite *dsregcmd /leave* i pritisnite **Enter**.</span><span class="sxs-lookup"><span data-stu-id="4ef3f-110">Type *dsregcmd /leave* and press **Enter**.</span></span>
- <span data-ttu-id="4ef3f-111">Kada bude završena, upišite *dsregcmd /join* i pritisnite **Enter**.</span><span class="sxs-lookup"><span data-stu-id="4ef3f-111">When complete, type *dsregcmd /join* and press **Enter**.</span></span>
- <span data-ttu-id="4ef3f-112">Kada bude završena, zatvorite naredbeni redak.</span><span class="sxs-lookup"><span data-stu-id="4ef3f-112">When complete, close the command prompt.</span></span>
- <span data-ttu-id="4ef3f-113">Ponovo pokrenite računalo i prijavite se na OneDrive.</span><span class="sxs-lookup"><span data-stu-id="4ef3f-113">Reboot the computer, and log into OneDrive.</span></span>