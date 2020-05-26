---
title: Pokretanje Windows dijagnostike memorije u operativnom sistemu Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002959"
- "5661"
ms.openlocfilehash: 3fedc52d02f1f70743429d0313eda0361306c3f3
ms.sourcegitcommit: 18b080c2a5d741af01ec589158effc35ea7cf449
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/19/2020
ms.locfileid: "44357783"
---
# <a name="run-windows-memory-diagnostics-in-windows-10"></a><span data-ttu-id="f0121-102">Pokretanje Windows dijagnostike memorije u operativnom sistemu Windows 10</span><span class="sxs-lookup"><span data-stu-id="f0121-102">Run Windows Memory Diagnostics in Windows 10</span></span>

<span data-ttu-id="f0121-103">Ako se prozori i aplikacije na RAČUNARU pojave, zamrzavaju ili deluju na nestabilan način, možda imate problem sa memorijom računara (RAM).</span><span class="sxs-lookup"><span data-stu-id="f0121-103">If Windows and apps on your PC are crashing, freezing, or acting in an unstable manner, you may have a problem with the PC’s memory (RAM).</span></span> <span data-ttu-id="f0121-104">Windows dijagnostika memorije možete pokrenuti da biste proverili da li ima problema sa RAM-om računara.</span><span class="sxs-lookup"><span data-stu-id="f0121-104">You can run the Windows Memory Diagnostic to check for problems with the PC’s RAM.</span></span>

<span data-ttu-id="f0121-105">U polju za pretragu na traci zadataka otkucajte **dijagnostiku memorije**, a zatim izaberite **Windows dijagnostika memorije**.</span><span class="sxs-lookup"><span data-stu-id="f0121-105">In the search box on your taskbar, type **memory diagnostic**, and then select **Windows Memory Diagnostic**.</span></span> 

<span data-ttu-id="f0121-106">Da biste pokrenuli dijagnostiku, potrebno je ponovo pokrenuti računar.</span><span class="sxs-lookup"><span data-stu-id="f0121-106">To run the diagnostic, the PC needs to restart.</span></span> <span data-ttu-id="f0121-107">Imate opciju da odmah ponovo pokrenete računar (Sačuvajte svoj rad i zatvorite otvorene dokumente i e-poruke) ili planirajte da se dijagnostika automatski pokreće sledeći put kada se računar ponovo pokrene:</span><span class="sxs-lookup"><span data-stu-id="f0121-107">You have the option to restart immediately (please save your work and close open documents and e-mails first), or schedule the diagnostic to run automatically the next time the PC restarts:</span></span>

![Windows dijagnostika memorije](media/windows-memory-diagnostic.png)

<span data-ttu-id="f0121-109">Kada se računar ponovo pokrene, **Windows alatka za dijagnostiku memorije** će se automatski pokrenuti.</span><span class="sxs-lookup"><span data-stu-id="f0121-109">When the PC restarts, the **Windows Memory Diagnostics Tool** will run automatically.</span></span> <span data-ttu-id="f0121-110">Status i napredak će biti prikazani u toku dijagnostike, a vi imate opciju otkazivanja dijagnostike tako što ćete na tastaturi udarati taster **Esc** .</span><span class="sxs-lookup"><span data-stu-id="f0121-110">Status and progress will be displayed as the diagnostics run, and you have the option of cancelling the diagnostics by hitting the **ESC** key on your keyboard.</span></span>

<span data-ttu-id="f0121-111">Kada se dijagnostika dovrši, Windows će se normalno pokrenuti.</span><span class="sxs-lookup"><span data-stu-id="f0121-111">When the diagnostics are complete, Windows will start normally.</span></span>
<span data-ttu-id="f0121-112">Odmah nakon ponovnog pokretanja, kada se pojavi radna površina, pojaviće se obaveštenje (pored ikone **centra aktivnosti** na traci zadataka) da biste označili da li su pronađene greške u memoriji.</span><span class="sxs-lookup"><span data-stu-id="f0121-112">Immediately after restart, when the Desktop appears, a notification will appear (next to the **Action Center** icon on the taskbar), to indicate whether any memory errors were found.</span></span> <span data-ttu-id="f0121-113">Na primer:</span><span class="sxs-lookup"><span data-stu-id="f0121-113">For example:</span></span>

<span data-ttu-id="f0121-114">Evo ikone Centra aktivnosti:</span><span class="sxs-lookup"><span data-stu-id="f0121-114">Here's the Action Center icon:</span></span> ![Ikona centra aktivnosti](media/action-center-icon.png) 

<span data-ttu-id="f0121-116">I uzorak obaveštenja:</span><span class="sxs-lookup"><span data-stu-id="f0121-116">And a sample notification:</span></span> ![Nema grešaka u memoriji](media/no-memory-errors.png)

<span data-ttu-id="f0121-118">Ako ste propustili obaveštenje, možete da izaberete ikonu **centra aktivnosti** na traci zadataka da biste prikazali **Centar aktivnosti** i videli listu obaveštenja koja se može pomerati.</span><span class="sxs-lookup"><span data-stu-id="f0121-118">If you missed the notification, you can select the **Action Center** icon  on the taskbar to display the **Action Center** and see a scrollable list of notifications.</span></span>

<span data-ttu-id="f0121-119">Da biste pregledali detaljne informacije, otkucajte **događaj** u polje za pretragu na traci zadataka, a zatim izaberite stavku " **Prikazivač događaja**".</span><span class="sxs-lookup"><span data-stu-id="f0121-119">To review detailed information, type **event** into the search box on your taskbar, and then select **Event Viewer**.</span></span> <span data-ttu-id="f0121-120">U oknu sa leve strane **prikazivača događaja**Krećite se do **Windows evidencije > sistem**.</span><span class="sxs-lookup"><span data-stu-id="f0121-120">In the **Event Viewer**’s left-hand pane, navigate to **Windows Logs > System**.</span></span> <span data-ttu-id="f0121-121">U oknu sa desne strane Skenirajte listu dok pregledate **izvornu** kolonu, dok ne vidite događaje sa izvornom vrednošću **memorisdijagnostike-rezultati**.</span><span class="sxs-lookup"><span data-stu-id="f0121-121">In the right-hand pane, scan down the list while looking at the **Source** column, until you see events with Source value **MemoryDiagnostics-Results**.</span></span> <span data-ttu-id="f0121-122">Ističete svaki takav događaj i vidite informacije o rezultatu u okviru ispod kartice " **Opšte postavke** " ispod liste.</span><span class="sxs-lookup"><span data-stu-id="f0121-122">Highlight each such event and see the result information in the box under the **General** tab below the list.</span></span>
