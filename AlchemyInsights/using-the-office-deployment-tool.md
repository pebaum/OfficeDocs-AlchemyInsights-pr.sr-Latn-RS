---
title: Korišćenje alatke za primenu sistema Office
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "918"
- "2000022"
ms.assetid: 7ff7cc06-76d0-468f-bd66-3f2760750d04
ms.openlocfilehash: fa40fef0de9b2e0e1fc329269c24e8bca9ed4146
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43726262"
---
# <a name="using-the-office-deployment-tool-odt"></a><span data-ttu-id="67d82-102">Korišćenje alatke za primenu sistema Office (ODT)</span><span class="sxs-lookup"><span data-stu-id="67d82-102">Using the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="67d82-103">Koristite alatku za primenu sistema Office (ODT) da biste primenili Office 365 verzije sistema Office.</span><span class="sxs-lookup"><span data-stu-id="67d82-103">You use the Office Deployment Tool (ODT) to deploy Office 365 versions of Office.</span></span> <span data-ttu-id="67d82-104">Alatka za primenu sistema Office (Setup. exe) se pokreće sa komandne linije i koristi XML datoteku za konfiguraciju da bi utvrdila koje postavke treba primeniti prilikom primene sistema Office.</span><span class="sxs-lookup"><span data-stu-id="67d82-104">The Office Deployment Tool (setup.exe) is run from the command line and uses a configuration XML file to determine what settings to apply when deploying Office.</span></span>
  
1. <span data-ttu-id="67d82-105">Preuzmite najnoviju verziju alatke za primenu sistema Office sa [lokacije Microsoft Download Center](https://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="67d82-105">Download the latest version of the Office Deployment Tool from the [Microsoft Download Center](https://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>

2. <span data-ttu-id="67d82-106">Koristite [alatku za prilagođavanje sistema Office (OCT)](https://config.office.com) da biste izabrali željene postavke za raspoređivanje i kreirali XML datoteku za konfiguraciju.</span><span class="sxs-lookup"><span data-stu-id="67d82-106">Use the [Office Customization Tool (OCT)](https://config.office.com) to select your deployment preferences and create the configuration XML file.</span></span> <span data-ttu-id="67d82-107">Izvezite datoteku za konfiguraciju i smestite je lokalno u istu fasciklu u kojoj se nalazi datoteka Setup. exe.</span><span class="sxs-lookup"><span data-stu-id="67d82-107">Export the configuration file and place it locally on the same folder where the setup.exe resides.</span></span>

    <span data-ttu-id="67d82-108">**Napomena:** Problemi sa instalacijom sistema Office se obično javljaju zbog pogrešno konfigurisanih ili neoblikovanih datoteka za konfiguraciju.</span><span class="sxs-lookup"><span data-stu-id="67d82-108">**Note:** Office installation issues commonly occur due to misconfigured or malformatted configuration files.</span></span> <span data-ttu-id="67d82-109">Da biste izbegli takve probleme, preporučujemo da koristite alatku za prilagođavanje sistema Office da biste kreirali datoteku za konfiguraciju.</span><span class="sxs-lookup"><span data-stu-id="67d82-109">To avoid such issues, we recommend that you use the Office Customization Tool to create the configuration file.</span></span> <span data-ttu-id="67d82-110">Postojeće datoteke za konfiguraciju možete da uvezete i u alatku za prilagođavanje sistema Office.</span><span class="sxs-lookup"><span data-stu-id="67d82-110">You can also import existing configuration files into the Office Customization Tool.</span></span>

3. <span data-ttu-id="67d82-111">Na osnovu pune komandne linije prebacite se na lokaciju na kojoj se nalazi instalacija. exe i pokrenite alatku za primenu sistema Office u režimu preuzimanja i navedite datoteku za konfiguraciju koju ste upravo sačuvali.</span><span class="sxs-lookup"><span data-stu-id="67d82-111">From an elevated command prompt, switch to the location where setup.exe resides and run the Office Deployment Tool in download mode and specify the configuration file you just saved.</span></span> <span data-ttu-id="67d82-112">U ovom primeru, Konfiguraciona datoteka se zove konfiguracija. XML:</span><span class="sxs-lookup"><span data-stu-id="67d82-112">In this example, the configuration file is named Configuration.xml:</span></span>
    
  ```
  setup.exe /download Configuration.xml  
  ```

4. <span data-ttu-id="67d82-113">Pokrenite alatku za primenu sistema Office u režimu konfigurisanja i navedite datoteku za konfiguraciju.</span><span class="sxs-lookup"><span data-stu-id="67d82-113">Run the Office Deployment Tool in configure mode and specify the configuration file.</span></span>
    
  ```
  setup.exe /configure Configuration.xml
  ```

    <span data-ttu-id="67d82-114">**Napomena:** Morate da pokrenete ovaj korak sa klijentskog računara na kojem želite da instalirate Office i morate imati lokalne administratorske dozvole na tom računaru.</span><span class="sxs-lookup"><span data-stu-id="67d82-114">**Note:** You must run this step from the client computer on which you want to install Office and you must have local administrator permissions on that computer.</span></span>

<span data-ttu-id="67d82-115">Pogledajte odeljak [pregled alatke za primenu sistema Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)da biste saznali više o korišćenju alatke za primenu sistema Office za Microsoft 365 aplikacije za scenarije raspoređivanja poslovnih informacija.</span><span class="sxs-lookup"><span data-stu-id="67d82-115">To learn more about using Office Deployment Tool for your Microsoft 365 Apps for enterprise deployment scenarios, see [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span> <span data-ttu-id="67d82-116">Više detalja o korišćenju alatke za prilagođavanje sistema Office potražite u članku [pregled alatke za prilagođavanje sistema Office](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).</span><span class="sxs-lookup"><span data-stu-id="67d82-116">For more details on how to use the Office Customization Tool, see [Overview of the Office Customization Tool](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).</span></span>
