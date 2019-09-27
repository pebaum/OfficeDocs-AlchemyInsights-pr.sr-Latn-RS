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
ms.openlocfilehash: 51d1a66fdf9774bbe58bfdbe89317bc93834be09
ms.sourcegitcommit: 5e6a805fb0b41d714ca1cf90e23b8e2daa90f90e
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/26/2019
ms.locfileid: "37205423"
---
# <a name="installing-office-on-a-terminal-server"></a>Instaliranje sistema Office na Terminal serveru

Za primenu sistema Office 365 ProPlus na Windows serveru pomoću usluga udaljene radne površine (RDS), prethodno imenovanih usluga terminala:
  
- Morate imati Office 365 plan koji uključuje Office 365 ProPlus, kao što je Office 365 Enterprise E3 ili Enterprise E5. Office 365 Business i Office 365 Business Premium planovi ne uključuju Office 365 ProPlus.

- Potrebno je da omogućite [deljenu aktivaciju računara](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).

Ako želite da instalirate Office 365 ProPlus na RDS iz Microsoft 365 admin Center, ***koji koristi podrazumevane postavke instalacije***, slijedite ove korake.

> [!TIP]
> Takođe možete da preuzmete i pokrenete [Microsoft pomoćnik za podršku i oporavak](https://aka.ms/SaRA_OfficeSCA_M365Portal) da biste instalirali Office 365 proplus u režimu aktivacije računara.
  
1. Proverite koji Office 365 plan imate. [Saznajte kako](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. Prebacite se na drugi Office 365 plan ako je potrebno. [Saznajte kako](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. Ako je Office već instaliran na RDS serveru koristeći bilo koji drugi Office 365 plan, deinstalirajte ga. Na primer, tako što ćete otići na \> kontrolnu tablu deinstalirajte program. Deinstalirajte koristeći [Microsoft pomoć i pomoćnik za oporavak](https://aka.ms/SARA-OfficeUninstall-Alchemy) ako se radi o problemima.

4. Na RDS serveru, prijavite se u Microsoft 365 admin Center sa administratorskim nalogom i [Instalirajte Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).

5. Nakon instalacije sistema Office, ***Nemojte da otvarate niti*** da se prijavljujete u bilo koju Office aplikaciju.

6. Na RDS serveru omogućite deljenu aktivaciju računara uređivanjem registratora tako što ćete slediti ove korake:

1. Kliknite desnim tasterom miša na dugme Windows u donjem levom uglu ekrana i izaberite stavku Pokreni. U polju otvori otkucajte **Regedit**, a zatim izaberite "u redu".

2. Kliknite na dugme "da" kada se od vas zatraži da dozvolite Registry Editoru da promeni vaš uređaj.

3. U programu Registry Editor Dodajte vrednost niske za **Sharedkompjuterlicenciranje** sa postavkom 1 pod HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\kliktorun\konfiguration.

7. Na RDS serveru prijavite se ***kao krajnji korisnik*** i [Proverite da li je aktivacija deljenog računara omogućena za Office 365 proplus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).

Za više detalja o preduslovi, uputstva za podešavanje i uputstva o prilagođenim instalacijama pomoću alatke za primenu sistema Office, pogledajte odeljak [Primena sistema office 365 ProPlus pomoću usluga udaljene radne površine](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).
  
Da biste ispravili greške u vezi sa aktivacijom deljenog računara, pogledajte odeljak [Rešavanje problema sa aktivacijom deljenog računara za Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).
  