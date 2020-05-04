---
title: Primena aplikacija Microsoft 365 za Enterprise za deljenu upotrebu na RDS, Terminal serveru ili VDI
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001419"
- "3411"
ms.openlocfilehash: 51512b29f8d37ce6c39ece5bb704cb01e88e463d
ms.sourcegitcommit: 7e06d9ec1dd462cbd882f088c997d012a032f04d
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/04/2020
ms.locfileid: "44010268"
---
# <a name="deploying-microsoft-365-apps-for-enterprise-for-shared-use-on-rds-terminal-server-or-vdi"></a>Primena aplikacija Microsoft 365 za Enterprise za deljenu upotrebu na RDS, Terminal serveru ili VDI

Da biste primenili Microsoft 365 aplikacije za Enterprise pomoću usluga udaljene radne površine (RDS), prethodno imenovane usluge terminala:
- Morate da imate Microsoft 365 za poslovni plan ili Office 365 plan koji uključuje Microsoft 365 aplikacije za Enterprise, kao što je Office 365 Enterprise E3 ili Enterprise E5.
   > [!NOTE] 
   > Microsoft 365 aplikacije za poslovne i Microsoft 365 Business Premium standardne planove ne uključuju Microsoft 365 aplikacije za Enterprise.
- Morate da omogućite [deljenu aktivaciju računara](https://docs.microsoft.com/DeployOffice/overview-shared-computer-activation).

> [!NOTE]
> Takođe možete preuzeti i pokrenuti [Microsoft pomoćnik za podršku i oporavak](https://aka.ms/SaRA_OfficeSCA_M365Portal) da biste instalirali Microsoft 365 aplikacije za Enterprise u režimu aktiviranja deljenog računara.

Za više informacija o preduslovi, uputstvima za instalaciju i uputstvima za prilagođene instalacije pomoću alatke za primenu sistema Office pogledajte odeljak [Primena Microsoft 365 aplikacija za Enterprise pomoću usluga udaljene radne površine](https://docs.microsoft.com/DeployOffice/deploy-microsoft-365-apps-remote-desktop-services).

Da biste ispravili greške u vezi sa aktivacijom deljenog računara:
- Pogledajte odeljak [Rešavanje problema sa aktivacijom deljenog računara za Microsoft 365 aplikacije za Enterprise](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation).
- Pogledajte članak [Resetovanje stanja aktivacije usluge Microsoft 365 Apps za preduzeće](https://go.microsoft.com/fwlink/?linkid=2109218).

Ako želite da instalirate Microsoft 365 aplikacije za Enterprise na RDS od Microsoft 365 admin Center, ***koji koristi podrazumevane postavke instalacije***, slijedite ove korake:

1.    Proverite koju pretplatu imate. [Saznajte kako](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have).
2.    Ako je potrebno, prebacite se na drugu pretplatu. [Saznajte kako](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan).
3.    Ako je Office već instaliran na RDS serveru koristeći druge Microsoft pretplate, deinstalirajte je. Na primer, tako što ćete otići na **kontrolnu tablu** > **deinstalirajte program**. Deinstalirajte koristeći [Microsoft pomoć i pomoćnik za oporavak](https://aka.ms/SARA-OfficeUninstall-Alchemy) ako se radi o problemima.
4.    Na RDS serveru, prijavite se u Microsoft 365 admin Center sa administratorskim nalogom i [instalirajte Microsoft 365 aplikacije za Enterprise](https://portal.office.com/OLS/MySoftware.aspx).
5.    Nakon instalacije sistema Office, ***Nemojte da otvarate niti*** da se prijavljujete u bilo koju Office aplikaciju.
6.    Na RDS serveru omogućite deljenu aktivaciju računara uređivanjem registratora tako što ćete slediti ove korake:
   1. Kliknite desnim tasterom miša na dugme "Windows" u donjem levom uglu ekrana i izaberite stavku **Pokreni**. U polju otvori otkucajte **Regedit**, a zatim izaberite **"u redu"**.
   2. Kliknite na **dugme "da** " kada se od vas zatraži da dozvolite Registry Editoru da promeni vaš uređaj.
   3. U programu Registry Editor Dodajte vrednost niske za **Sharedkompjuterlicenciranje** sa postavkom 1 u HKEY_LOCAL_MACHINE \SOFTWARE\Microsoft \Office\kliktorun\konfiguration.
   4. Na RDS serveru prijavite se ***kao krajnji korisnik*** i [Proverite da li je aktivacija deljenog računara omogućena za Microsoft 365 aplikacije za Enterprise](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation#verify-that-activation-for-microsoft-365-apps-succeeded).

