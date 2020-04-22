---
title: Instaliranje sistema Office na Terminal serveru-nelicenciran
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "917"
- "2000020"
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 7252efdc0f55b8923e685ec89f9b3c63882aa6b0
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43763231"
---
# <a name="installing-office-on-a-terminal-server"></a>Instaliranje sistema Office na Terminal serveru

Za primenu aplikacija Microsoft 365 za Enterprise na Windows serveru pomoću usluga udaljene radne površine (RDS), prethodno imenovanih usluga terminala:
  
- Morate da imate Microsoft 365 pretplatu koja uključuje Microsoft 365 aplikacije za Enterprise, kao što je Office 365 Enterprise E3 ili Enterprise E5. Microsoft 365 aplikacije za poslovne i Microsoft 365 aplikacije za poslovne Premium planove ne uključuju Microsoft 365 aplikacije za Enterprise.

- Potrebno je da omogućite [deljenu aktivaciju računara](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).

Ako želite da instalirate Microsoft 365 aplikacije za Enterprise na RDS od Microsoft 365 admin Center, ***koji koristi podrazumevane postavke instalacije***, slijedite ove korake.

> [!TIP]
> Takođe možete preuzeti i pokrenuti [Microsoft pomoćnik za podršku i oporavak](https://aka.ms/SaRA_OfficeSCA_M365Portal) da biste instalirali Microsoft 365 aplikacije za Enterprise u režimu aktiviranja deljenog računara.
  
1. Proverite koju Microsoft 365 pretplatu imate. [Saznajte kako](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. Ako je potrebno, prebacite se na drugu Microsoft 365 pretplatu. [Saznajte kako](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. Ako je Office već instaliran na RDS serveru koristeći druge Microsoft 365 pretplate, deinstalirajte je. Na primer, tako što ćete otići na \> kontrolnu tablu deinstalirajte program. Deinstalirajte koristeći [Microsoft pomoć i pomoćnik za oporavak](https://aka.ms/SARA-OfficeUninstall-Alchemy) ako se radi o problemima.

4. Na RDS serveru, prijavite se u Microsoft 365 admin Center sa administratorskim nalogom i [instalirajte Microsoft 365 aplikacije za Enterprise](https://portal.office.com/OLS/MySoftware.aspx).

5. Nakon instalacije sistema Office, ***Nemojte da otvarate niti*** da se prijavljujete u bilo koju Office aplikaciju.

6. Na RDS serveru omogućite deljenu aktivaciju računara uređivanjem registratora tako što ćete slediti ove korake:

1. Kliknite desnim tasterom miša na dugme Windows u donjem levom uglu ekrana i izaberite stavku Pokreni. U polju otvori otkucajte **Regedit**, a zatim izaberite "u redu".

2. Kliknite na dugme "da" kada se od vas zatraži da dozvolite Registry Editoru da promeni vaš uređaj.

3. U programu Registry Editor Dodajte vrednost niske za **Sharedkompjuterlicenciranje** sa postavkom 1 u HKEY_LOCAL_MACHINE \SOFTWARE\Microsoft \Office\kliktorun\konfiguration.

7. Na RDS serveru prijavite se ***kao krajnji korisnik*** i [Proverite da li je aktivacija deljenog računara omogućena za Microsoft 365 aplikacije za Enterprise](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).

Za više detalja o preduslovi, uputstva za podešavanje i uputstva o prilagođenim instalacijama pomoću alatke za primenu sistema Office, pogledajte odeljak [Primena Microsoft 365 aplikacija za Enterprise pomoću usluga udaljene radne površine](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).
  
Da biste ispravili greške u vezi sa aktivacijom deljenog računara, pogledajte odeljak [Rešavanje problema sa aktivacijom deljenog računara za Microsoft 365 aplikacije za Enterprise](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).
  