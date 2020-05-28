---
title: Teams klijent otkazuje?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002323"
- "4512"
ms.openlocfilehash: ac1cc05adfa33626ff34d30dca6c77f1bb96477a
ms.sourcegitcommit: c46b8df485edbd13e8bb4d1b2ba1c2821ddc9da0
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/23/2020
ms.locfileid: "44354067"
---
# <a name="teams-client-crashing"></a><span data-ttu-id="381c4-102">Teams klijent otkazuje?</span><span class="sxs-lookup"><span data-stu-id="381c4-102">Teams client crashing?</span></span>

<span data-ttu-id="381c4-103">Ukoliko Teams klijent otkazuje, pokušajte sledeće:</span><span class="sxs-lookup"><span data-stu-id="381c4-103">If your Teams client is crashing, try the following:</span></span>

- <span data-ttu-id="381c4-104">Ako koristite Teams aplikaciju za stone računare, [ uverite se da je aplikacija potpuno ažurirana](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).</span><span class="sxs-lookup"><span data-stu-id="381c4-104">If you are using the Teams desktop app, [make sure the app is fully updated](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).</span></span>

- <span data-ttu-id="381c4-105">Uverite se da su sve [Microsoft 365 URL adrese i opsezi adresa](https://docs.microsoft.com/microsoftteams/connectivity-issues) dostupni.</span><span class="sxs-lookup"><span data-stu-id="381c4-105">Make sure all the [Microsoft 365 URLs and address ranges](https://docs.microsoft.com/microsoftteams/connectivity-issues) are accessible.</span></span>

- <span data-ttu-id="381c4-106">Prijavite se koristeći svoj nalog za administraciju i proverite da li postoji usluga [zdravstvenog stanja usluge](https://docs.microsoft.com/office365/enterprise/view-service-health) da biste proverili da li postoji nebrojanje ili degradacija usluge.</span><span class="sxs-lookup"><span data-stu-id="381c4-106">Log in with your tenant admin account and check your [Service Health Dashboard](https://docs.microsoft.com/office365/enterprise/view-service-health) to verify that no outage or service degradation exists.</span></span>

- <span data-ttu-id="381c4-107">Deinstalirajte i ponovo instalirajte aplikaciju "timovi" (veza)</span><span class="sxs-lookup"><span data-stu-id="381c4-107">Uninstall and reinstall the Teams Application (link)</span></span>
    - <span data-ttu-id="381c4-108">Potražite fasciklu "%appdata%\Microsoft\teams\" na računaru i izbrišite sve datoteke u tom direktorijumu.</span><span class="sxs-lookup"><span data-stu-id="381c4-108">Browse to the %appdata%\Microsoft\teams\ folder on your computer and delete all files in that directory.</span></span>
    - <span data-ttu-id="381c4-109">[Preuzmite i instalirajte aplikaciju "timovi](https://www.microsoft.com/microsoft-365/microsoft-teams/group-chat-software#office-DesktopAppDownload-ofoushy)" i ako je moguće, instalirajte timove kao administrator (kliknite desnim tasterom miša na instalator timova i izaberite opciju "Pokreni kao administrator" Ako je dostupan).</span><span class="sxs-lookup"><span data-stu-id="381c4-109">[Download and install the Teams App](https://www.microsoft.com/microsoft-365/microsoft-teams/group-chat-software#office-DesktopAppDownload-ofoushy), and if possible, install Teams as an administrator (right click the Teams installer and select "Run as administrator" if available).</span></span>

<span data-ttu-id="381c4-110">Ako se vaši timovi još uvek nalaze u sporu, možete li da ga ponovo reprodukujete?</span><span class="sxs-lookup"><span data-stu-id="381c4-110">If your Teams client is still crashing, can you reproduce the issue?</span></span> <span data-ttu-id="381c4-111">Ako je tako:</span><span class="sxs-lookup"><span data-stu-id="381c4-111">If so:</span></span>

1. <span data-ttu-id="381c4-112">Koristite zapisivač koraka da biste hvatali korake.</span><span class="sxs-lookup"><span data-stu-id="381c4-112">Use the Steps Recorder to capture your steps.</span></span>
    - <span data-ttu-id="381c4-113">Zatvorite sve nepotrebne ili poverljive aplikacije.</span><span class="sxs-lookup"><span data-stu-id="381c4-113">Close ALL unnecessary or confidential applications.</span></span>
    - <span data-ttu-id="381c4-114">Pokretanje zapisivača za korake i reprodukovanje problema prilikom prijavljivanja pomoću korisničkog naloga koji je pogođen.</span><span class="sxs-lookup"><span data-stu-id="381c4-114">Launch the Steps Recorder and reproduce the issue while logged in with the affected user account.</span></span>
    - <span data-ttu-id="381c4-115">[Prikupite zapisnike timova koji hvatate zapisne REPRO korake](https://docs.microsoft.com/microsoftteams/log-files).</span><span class="sxs-lookup"><span data-stu-id="381c4-115">[Collect the teams logs that capture the recorded repro steps](https://docs.microsoft.com/microsoftteams/log-files).</span></span> <span data-ttu-id="381c4-116">**Napomena**: uverite se da ste uhvatili adresu za prijavljivanje koje je uticala korisnik.</span><span class="sxs-lookup"><span data-stu-id="381c4-116">**Note**: Make sure you capture the sign-in address of the impacted user.</span></span>
    - <span data-ttu-id="381c4-117">Prikupite informacije o promeni stanja memorije i/ili u vezi sa podacima o kvarovima (Windows).</span><span class="sxs-lookup"><span data-stu-id="381c4-117">Collect the dump and/or Fault bucket info (Windows).</span></span> <span data-ttu-id="381c4-118">Pokrenite Windows PowerShell na računaru na kom se pojavljuje nesreća i pokrenite sledeće komande:</span><span class="sxs-lookup"><span data-stu-id="381c4-118">Launch Windows Powershell on the machine where the crash is occurring and run the following commands:</span></span>

        `
        PS C:\Users\user01> cd $env:temp
        PS C:\Users\user01\AppData\Local\Temp> Get-EventLog -LogName Application -Message "*Teams.exe*" -InstanceId 1001 | Select-Object -First 10 | Format-List > FaultBuckets.txt
        PS C:\Users\user01\AppData\Local\Temp> notepad .\FaultBuckets.txt
        `
    
2. <span data-ttu-id="381c4-119">Priložite datoteku u kućište podrške.</span><span class="sxs-lookup"><span data-stu-id="381c4-119">Attach the file to your support case.</span></span>
