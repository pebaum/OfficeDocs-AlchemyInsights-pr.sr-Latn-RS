---
title: SharePoint online PowerShell
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 9/18/19
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000266"
- "1867"
ms.openlocfilehash: 00ec337ce34da9d3c3fba0a71602c3078a556552
ms.sourcegitcommit: 6b102e079a7d30298105fd811a67efb707d6d5bf
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/23/2019
ms.locfileid: "37123012"
---
# <a name="sharepoint-online-powershell"></a>SharePoint online PowerShell

Rad sa PowerShell ili skriptama u okviru SharePoint online-a? Za više informacija posetite dole navedene veze.
- [Prvi koraci uz Internet Shell upravljanja na mreži](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps)
- [Povezivanje sa SPO-om PowerShell sa višeifaknim potvrdom verodostojnosti (MFA)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps#to-connect-with-multifactor-authentication-mfa)
- [SharePoint obrasci i prakse (PNP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) sadrže biblioteku PowerShell komandi koje vam omogućavaju da izvršite složene radnje upravljanja prema SPO-u.

> [!NOTE]
> - Ako imate problema sa povezivanjem sa ljuske upravljanja SPO, uverite se da ste ažurirali najnoviju verziju i pokušajte da [ponovo uvezete modul](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) pomoću opcije *"Uvezi-modul Microsoft. na mreži. SharePoint. PowerShell"* .
> - Ako pokušavate da pokrenete skripte modela objekta sa klijentske strane, biće potrebno da na lokalnom računaru imate instaliran [SDK komponente za SharePoint klijente na mreži](https://www.microsoft.com/download/details.aspx?id=42038) .
> - Ako imate problema sa pokretanjem skripti iz programa PowerShell, možda ćete želeti da razmotrite pokretanje PowerShell kao administratora i promenu [smernica izvršenja](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).