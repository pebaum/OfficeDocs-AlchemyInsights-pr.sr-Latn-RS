---
title: Pitanja o tome kako koristiti alat za raspoređivanje Office (ODT)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/26/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: 604fc200517316de6e0194bd64e6eb3039cfa61b
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36553554"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a><span data-ttu-id="6e525-102">Pitanja o tome kako koristiti alat za raspoređivanje Office (ODT)</span><span class="sxs-lookup"><span data-stu-id="6e525-102">Questions about how to use the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="6e525-103">Preuzmite alatku za raspoređivanje Office iz [Microsoft centra za preuzimanje](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="6e525-103">Download the Office Deployment Tool from the [Microsoft Download Center](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>
  
<span data-ttu-id="6e525-104">Nakon preuzimanja datoteke, pokrene na izvršnu datoteku, koja sadrži Office raspoređivanja alatku za izvršne (setup.exe) i datoteku za konfiguraciju uzorka (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="6e525-104">After downloading the file, run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span>
  
 <span data-ttu-id="6e525-105">**Da isključite ili uklonite Office 365 ProPlus proizvodi iz klijentske računare:**</span><span class="sxs-lookup"><span data-stu-id="6e525-105">**To exclude or remove Office 365 ProPlus products from client computers:**</span></span>
  
<span data-ttu-id="6e525-106">Kada instalirate Office 365 ProPlus, možete da isključite specifične proizvode.</span><span class="sxs-lookup"><span data-stu-id="6e525-106">When installing Office 365 ProPlus, you can exclude specific products.</span></span> <span data-ttu-id="6e525-107">Da biste to učinili, slijedite korake za instalaciju Office uz na ODT, ali uključuju ExcludeApp element u datoteci za konfiguraciju.</span><span class="sxs-lookup"><span data-stu-id="6e525-107">To do so, follow the steps for installing Office with the ODT, but include the ExcludeApp element in your configuration file.</span></span> <span data-ttu-id="6e525-108">Na primer, datoteka za konfiguraciju instalira Office 365 ProPlus proizvode osim izdavača:</span><span class="sxs-lookup"><span data-stu-id="6e525-108">For example, this configuration file installs all the Office 365 ProPlus products except Publisher:</span></span>
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[<span data-ttu-id="6e525-109">Pregled sistema Office alatke za raspoređivanje</span><span class="sxs-lookup"><span data-stu-id="6e525-109">Overview of the Office Deployment Tool</span></span>](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  

