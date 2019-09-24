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
# <a name="sharepoint-online-powershell"></a><span data-ttu-id="6f1bb-102">SharePoint online PowerShell</span><span class="sxs-lookup"><span data-stu-id="6f1bb-102">Sharepoint Online PowerShell</span></span>

<span data-ttu-id="6f1bb-103">Rad sa PowerShell ili skriptama u okviru SharePoint online-a?</span><span class="sxs-lookup"><span data-stu-id="6f1bb-103">Working with PowerShell or Scripts within Sharepoint Online?</span></span> <span data-ttu-id="6f1bb-104">Za više informacija posetite dole navedene veze.</span><span class="sxs-lookup"><span data-stu-id="6f1bb-104">Visit the links below for more information.</span></span>
- [<span data-ttu-id="6f1bb-105">Prvi koraci uz Internet Shell upravljanja na mreži</span><span class="sxs-lookup"><span data-stu-id="6f1bb-105">Getting started with SharePoint Online Management Shell</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps)
- [<span data-ttu-id="6f1bb-106">Povezivanje sa SPO-om PowerShell sa višeifaknim potvrdom verodostojnosti (MFA)</span><span class="sxs-lookup"><span data-stu-id="6f1bb-106">Connect to SPO PowerShell with multifactor authentication (MFA)</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps#to-connect-with-multifactor-authentication-mfa)
- <span data-ttu-id="6f1bb-107">[SharePoint obrasci i prakse (PNP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) sadrže biblioteku PowerShell komandi koje vam omogućavaju da izvršite složene radnje upravljanja prema SPO-u.</span><span class="sxs-lookup"><span data-stu-id="6f1bb-107">[SharePoint Patterns and Practices (PnP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) contains a library of PowerShell commands that allows you to perform complex management actions towards SPO.</span></span>

> [!NOTE]
> - <span data-ttu-id="6f1bb-108">Ako imate problema sa povezivanjem sa ljuske upravljanja SPO, uverite se da ste ažurirali najnoviju verziju i pokušajte da [ponovo uvezete modul](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) pomoću opcije *"Uvezi-modul Microsoft. na mreži. SharePoint. PowerShell"* .</span><span class="sxs-lookup"><span data-stu-id="6f1bb-108">If you are having issues connecting with the SPO management shell, make sure that you have updated to the latest version and try to [re-import the module](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) using *“Import-Module Microsoft.Online.SharePoint.PowerShell”.*</span></span>
> - <span data-ttu-id="6f1bb-109">Ako pokušavate da pokrenete skripte modela objekta sa klijentske strane, biće potrebno da na lokalnom računaru imate instaliran [SDK komponente za SharePoint klijente na mreži](https://www.microsoft.com/download/details.aspx?id=42038) .</span><span class="sxs-lookup"><span data-stu-id="6f1bb-109">If you are attempting to run client-side object model scripts, you will need to have the [Sharepoint Online Client Components SDK](https://www.microsoft.com/download/details.aspx?id=42038) installed on your local machine.</span></span>
> - <span data-ttu-id="6f1bb-110">Ako imate problema sa pokretanjem skripti iz programa PowerShell, možda ćete želeti da razmotrite pokretanje PowerShell kao administratora i promenu [smernica izvršenja](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span><span class="sxs-lookup"><span data-stu-id="6f1bb-110">If you are having issues running scripts from PowerShell, you may want to consider running PowerShell as an Administrator and changing the [Execution Policy](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span></span>