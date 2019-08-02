---
title: Raspoređivanje timova kao samostalni ili sa nove ili postojeće Office instalacije
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.date: 08/01/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000660"
- "2509"
ms.openlocfilehash: 3318e1b17cc99e927e1011f7ca9eca8dec616d59
ms.sourcegitcommit: 4600dd4fb577bf5f5482a24616c2d9a6b81e8052
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/01/2019
ms.locfileid: "36054244"
---
# <a name="deploying-teams-as-standalone-or-with-new-or-existing-office-installations"></a>Raspoređivanje timova kao samostalni ili sa nove ili postojeće Office instalacije

Microsoft Teams je sada uključena u sklopu ***nove instalacije*** Office 365 ProPlus, Office 365 Business i Office za Mac Za više informacija, pogledajte [kada će Microsoft Teams početi da bude uključen u nove instalacije sistema Office?](https://docs.microsoft.com/deployoffice/teams-install#when-will-microsoft-teams-start-being-included-with-new-installations-of-office-365-proplus)

Pored toga, počevši od verzije 1906 u jednom mesečno kanala, timovi će biti ***dodati u postojeće instalacije*** Office 365 ProPlus (i Office 365 Business) na uređajima koji koristi Windows kada ažurirate postojeću instalaciju na najnoviju verziju. Za više informacija, pogledajte [a postojeće instalacije sistema Office?](https://docs.microsoft.com/deployoffice/teams-install#what-about-existing-installations-of-office-365-proplus)

> [!NOTE]
> Ako ne želite čekati na ovom bizarnom raspored, možete da rasporedite timove kao samostalni za korisnike tako što ćete [pratiti ove instrukcije](https://docs.microsoft.com/MicrosoftTeams/msi-deployment) ili može vaših korisnika instalirajte timove za sebe iz [https://teams.microsoft.com/downloads](https://teams.microsoft.com/downloads).

Ako vaša organizacija nije spremna da rasporedi timove, imamo korake koje možete preduzeti da ***izuzmete timovi*** iz [nove](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-office-365-proplus) ili [postojeće](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams) instalacije programa Office. Ako želite da timovi biti instaliran, ali ne želim timove za automatsko pokretanje za korisnika kada ga instalirate, da vidim [Sprečavanju Microsoft timova iz počinje automatski nakon instalacije](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation).

Da ***deinstalirate timova*** sa uređaja koji koristi Windows, pogledajte [Deinstalirajte Microsoft timova](https://support.office.com/article/3b159754-3c26-4952-abe7-57d27f5f4c81). Da za čišćenje Microsoft Teams iz više ciljnim računarima ili korisnicima, pogledajte [Microsoft timova za raspoređivanje očisti](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up).

Ako koristite deljene računare, usluge udaljene radne površine (RDS) ili infrastrukture virtualne radne površine (VDI), pogledajte odeljak [deljenih računara i VDI okruženjima sa Microsoft timovima](https://docs.microsoft.com/deployoffice/teams-install#shared-computer-and-vdi-environments-with-microsoft-teams).

Ako koristite Office za Mac, video [Instalacija Microsoft timova na Mac](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac).

> [!NOTE]
> Nakon instaliranja timova, je [automatski ažuriraju](https://docs.microsoft.com/deployoffice/teams-install#feature-and-quality-updates-for-microsoft-teams) otprilike dva tjedna sa novim funkcijama i kvaliteta ispravke. 