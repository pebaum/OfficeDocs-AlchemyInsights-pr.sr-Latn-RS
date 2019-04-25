---
title: Koristeći alatku za raspoređivanje Office
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 7ff7cc06-76d0-468f-bd66-3f2760750d04
ms.openlocfilehash: c7e0e96f225030590fdd516eaf3115c93a6335b6
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32423197"
---
# <a name="using-the-office-deployment-tool-odt"></a><span data-ttu-id="083a6-102">Koristeći alatku za raspoređivanje Office (ODT)</span><span class="sxs-lookup"><span data-stu-id="083a6-102">Using the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="083a6-103">Alat za raspoređivanje Office (ODT) se koristi za raspoređivanje Office 365 verzije sistema Office.</span><span class="sxs-lookup"><span data-stu-id="083a6-103">You use the Office Deployment Tool (ODT) to deploy Office 365 versions of Office.</span></span> <span data-ttu-id="083a6-104">Alatku za raspoređivanje Office (setup.exe) se pokreće iz komandne linije i koristi XML datoteku za konfiguraciju da biste utvrdili koje postavke da biste primenili prilikom primene Office.</span><span class="sxs-lookup"><span data-stu-id="083a6-104">The Office Deployment Tool (setup.exe) is run from the command line and uses a configuration XML file to determine what settings to apply when deploying Office.</span></span>
  
1. <span data-ttu-id="083a6-105">Preuzmite najnoviju verziju programa Office alatke za raspoređivanje sa lokacije [Microsoft Download Center](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="083a6-105">Download the latest version of the Office Deployment Tool from the [Microsoft Download Center](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>
    
2. <span data-ttu-id="083a6-106">[Alatka za prilagođavanje sistema Office (OCT)](https://config.office.com) koristite da biste izabrali željene opcije raspoređivanja i kreiranje XML datoteke za konfiguraciju.</span><span class="sxs-lookup"><span data-stu-id="083a6-106">Use the [Office Customization Tool (OCT)](https://config.office.com) to select your deployment preferences and create the configuration XML file.</span></span> <span data-ttu-id="083a6-107">Izvoz datoteke za konfiguraciju i to lokalno na istoj fascikli gde se nalazi na setup.exe.</span><span class="sxs-lookup"><span data-stu-id="083a6-107">Export the configuration file and place it locally on the same folder where the setup.exe resides.</span></span> 
    
    <span data-ttu-id="083a6-108">**Napomena:** Office instalacije problemi se obično pojaviti termin da misconfigured ili malformatted datoteke za konfiguraciju.</span><span class="sxs-lookup"><span data-stu-id="083a6-108">**Note:** Office installation issues commonly occur due to misconfigured or malformatted configuration files.</span></span> <span data-ttu-id="083a6-109">Da biste izbegli takvim pitanjima, preporučujemo da koristite alatku za prilagođavanje sistema Office da biste kreirali datoteku za konfiguraciju.</span><span class="sxs-lookup"><span data-stu-id="083a6-109">To avoid such issues, we recommend that you use the Office Customization Tool to create the configuration file.</span></span> <span data-ttu-id="083a6-110">Takođe, možete da uvezete postojeće datoteke za konfiguraciju u alatku za prilagođavanje sistema Office.</span><span class="sxs-lookup"><span data-stu-id="083a6-110">You can also import existing configuration files into the Office Customization Tool.</span></span> 
    
3. <span data-ttu-id="083a6-111">Iz komandnoj liniji, prebacite se na lokaciju gde se nalazi setup.exe i pokrenuti alatku za raspoređivanje Office u režimu za preuzimanje i navedite datoteku konfiguracije koju ste upravo sačuvali.</span><span class="sxs-lookup"><span data-stu-id="083a6-111">From an elevated command prompt, switch to the location where setup.exe resides and run the Office Deployment Tool in download mode and specify the configuration file you just saved.</span></span> <span data-ttu-id="083a6-112">U ovom primeru, konfiguracijska datoteka je koja se zove Configuration.xml:</span><span class="sxs-lookup"><span data-stu-id="083a6-112">In this example, the configuration file is named Configuration.xml:</span></span>
    
  ```
  setup.exe /download Configuration.xml  
  ```

4. <span data-ttu-id="083a6-113">Pokrenite alatku za raspoređivanje Office u podesite režim i navedite datoteku za konfiguraciju.</span><span class="sxs-lookup"><span data-stu-id="083a6-113">Run the Office Deployment Tool in configure mode and specify the configuration file.</span></span>
    
  ```
  setup.exe /configure Configuration.xml
  ```

    <span data-ttu-id="083a6-114">**Napomena:** Ovaj korak morate pokrenuti sa klijentskog računara na kojem želite da instalirate Office i morate imati lokalne administratorske dozvole na taj kompjuter.</span><span class="sxs-lookup"><span data-stu-id="083a6-114">**Note:** You must run this step from the client computer on which you want to install Office and you must have local administrator permissions on that computer.</span></span> 
    
<span data-ttu-id="083a6-115">Da biste saznali više o korišćenju alatka za primenu Office za Office 365 ProPlus scenariji primene, pogledajte [Pregled Office alatke za primenu](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="083a6-115">To learn more about using Office Deployment Tool for your Office 365 ProPlus deployment scenarios, see [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span> <span data-ttu-id="083a6-116">Za više detalja o tome kako se koristi alatka za prilagođavanje sistema Office, pogledajte [Pregled Office alatke za prilagođavanje](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).</span><span class="sxs-lookup"><span data-stu-id="083a6-116">For more details on how to use the Office Customization Tool, see [Overview of the Office Customization Tool](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).</span></span>
  

