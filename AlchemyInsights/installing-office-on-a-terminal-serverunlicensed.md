---
title: Instaliranje sistema office na Terminal serveru - bez dozvole
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
ms.openlocfilehash: edac051840594f13b22ccd83f5cd6e3da5f84cbc
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36498429"
---
# <a name="installing-office-on-a-terminal-server"></a>Instaliranje sistema Office na Terminal servera

Za primenu Office 365 ProPlus na Windows serveru koristeći usluge udaljene radne površine (RDS), nekadašnja po imenu Terminal Services:
  
- Morate imati plan za Office 365 koji uključuje Office 365 ProPlus, kao što je Office 365 Enterprise E3 ili Enterprise E5. Ne uključuj Office 365 ProPlus Office 365 Business i Office 365 poslovne Premium planove.

- Potrebno je da omogućite [aktivacija deljenih računara](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).

Ako želite da instalirate Office 365 ProPlus na RDS sa Office 365 portala, ***koji koristi podrazumevane postavke instalacije***, slijedite ove korake:
  
1. Pogledajte kakav plan Office 365, imate. [Saznajte kako](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. Ako je potrebno, prebaci se na drugu Office 365 planiraju. [Saznajte kako](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. Ako Office je već instaliran na serveru RDS pomoću neke druge planove za Office 365, deinstalirajte ga. Na primer, tako što ćete posetiti Kontrolna tabla \> Deinstaliranje programa. Deinstalirajte koristeći [Microsoft podršci i pomoćnik za oporavak](https://aka.ms/SARA-OfficeUninstall-Alchemy) Ako pokrećete u pitanjima.

4. Na serveru RDS, prijavite se Office 365 portal sa administratorskim nalogom i [Instalirajte Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).

5. Nakon instaliranja Office, ***ne otvori ili se prijavite u*** bilo koji Office aplikacijama.

6. Na serveru RDS, Omogućavanje aktivacije deljeni računar uređivanjem registra tako što ćete pratiti ove korake:

1. Kliknite desnim tasterom miša na Windows dugme u donjem levom uglu ekrana i izaberite stavku Pokreni. U polju otvori otkucajte **regedit**, a zatim izaberite OK.

2. Izaberite opciju da kada se od vas zatraži da dozvolite Registry Editor da biste promenili vaš uređaj.

3. U programu Registry Editor, dodajte vrednost niske od **SharedComputerLicensing** sa postavkom 1 pod HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.

7. Na serveru RDS, ***prijaviti se kao krajnji korisnik*** i [da li deljeni računar aktivacija omogućena za Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).

Za više detalja o preduslovi, uputstva za instalaciju i Vodič kroz prilagođene instalacije pomoću alatke za primenu za Office, pogledajte [Korištenje Office 365 ProPlus pomoću usluge udaljene radne površine](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).
  
Da biste popravili greške vezane za aktivaciju deljeni računar, pogledajte [Rešavanje problema sa aktivacija deljenih računara za Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).
  