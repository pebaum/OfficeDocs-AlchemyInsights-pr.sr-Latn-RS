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
# <a name="teams-client-crashing"></a>Teams klijent otkazuje?

Ukoliko Teams klijent otkazuje, pokušajte sledeće:

- Ako koristite Teams aplikaciju za stone računare, [ uverite se da je aplikacija potpuno ažurirana](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).

- Uverite se da su sve [Microsoft 365 URL adrese i opsezi adresa](https://docs.microsoft.com/microsoftteams/connectivity-issues) dostupni.

- Prijavite se koristeći svoj nalog za administraciju i proverite da li postoji usluga [zdravstvenog stanja usluge](https://docs.microsoft.com/office365/enterprise/view-service-health) da biste proverili da li postoji nebrojanje ili degradacija usluge.

- Deinstalirajte i ponovo instalirajte aplikaciju "timovi" (veza)
    - Potražite fasciklu "%appdata%\Microsoft\teams\" na računaru i izbrišite sve datoteke u tom direktorijumu.
    - [Preuzmite i instalirajte aplikaciju "timovi](https://www.microsoft.com/microsoft-365/microsoft-teams/group-chat-software#office-DesktopAppDownload-ofoushy)" i ako je moguće, instalirajte timove kao administrator (kliknite desnim tasterom miša na instalator timova i izaberite opciju "Pokreni kao administrator" Ako je dostupan).

Ako se vaši timovi još uvek nalaze u sporu, možete li da ga ponovo reprodukujete? Ako je tako:

1. Koristite zapisivač koraka da biste hvatali korake.
    - Zatvorite sve nepotrebne ili poverljive aplikacije.
    - Pokretanje zapisivača za korake i reprodukovanje problema prilikom prijavljivanja pomoću korisničkog naloga koji je pogođen.
    - [Prikupite zapisnike timova koji hvatate zapisne REPRO korake](https://docs.microsoft.com/microsoftteams/log-files). **Napomena**: uverite se da ste uhvatili adresu za prijavljivanje koje je uticala korisnik.
    - Prikupite informacije o promeni stanja memorije i/ili u vezi sa podacima o kvarovima (Windows). Pokrenite Windows PowerShell na računaru na kom se pojavljuje nesreća i pokrenite sledeće komande:

        `
        PS C:\Users\user01> cd $env:temp
        PS C:\Users\user01\AppData\Local\Temp> Get-EventLog -LogName Application -Message "*Teams.exe*" -InstanceId 1001 | Select-Object -First 10 | Format-List > FaultBuckets.txt
        PS C:\Users\user01\AppData\Local\Temp> notepad .\FaultBuckets.txt
        `
    
2. Priložite datoteku u kućište podrške.
