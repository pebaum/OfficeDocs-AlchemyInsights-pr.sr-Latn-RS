---
title: Instaliranje sistema Office na Terminal serveru-nelicenciran
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "917"
- "2000020"
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 53071224a7c33532d864cd70b84bf0e3cc6a992f
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/04/2019
ms.locfileid: "36735403"
---
# <a name="installing-office-on-a-terminal-server"></a>Instaliranje sistema Office na Terminal serveru

Za primenu sistema Office 365 ProPlus na Windows serveru pomoću usluga udaljene radne površine (RDS), prethodno imenovanih usluga terminala:
  
- Morate imati Office 365 plan koji uključuje Office 365 ProPlus, kao što je Office 365 Enterprise E3 ili Enterprise E5. Office 365 Business i Office 365 Business Premium planovi ne uključuju Office 365 ProPlus.

- Potrebno je da omogućite [deljenu aktivaciju računara](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).

Ako želite da instalirate Office 365 ProPlus na RDS iz Microsoft 365 admin Center, ***koji koristi podrazumevane postavke instalacije***, sledite ove korake:
  
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
  