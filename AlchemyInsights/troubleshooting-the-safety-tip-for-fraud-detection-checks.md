---
title: Rešavanje problema u Savetu bezbednosti za otkrivanje prevare proverava
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 96ebe3c5-66ea-4662-98b7-052c2181c2f3
ms.openlocfilehash: 24842e8cc5c6e47fb0eb637e6a3211637ede1ed8
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/15/2019
ms.locfileid: "28310196"
---
# <a name="troubleshooting-the-safety-tip-for-fraud-detection-checks"></a><span data-ttu-id="1463b-102">Rešavanje problema u Savetu bezbednosti za otkrivanje prevare proverava</span><span class="sxs-lookup"><span data-stu-id="1463b-102">Troubleshooting the safety tip for fraud detection checks</span></span>

<span data-ttu-id="1463b-p101">Ako ste dobiti napojnicu sigurnost koja kaže „pošiljalac nije uspelo čekove za otkrivanje prevare, i možda nije koji izgledaju kao da su”, a zatim pošiljalac nije uspjelo proći ili DKIM ili SPF provere identiteta. Najbolji metod da biste rešili ovo je za pošiljaoca da odobri sami sebe. Ako pošiljalac šalje u vaše ime, potrebno je da odobrite ih tako što ćete dodati IP adresu pošiljaoca na tvoj SPF zapis.</span><span class="sxs-lookup"><span data-stu-id="1463b-p101">If you are getting a safety tip that says "The sender failed our fraud detection checks and may not be who they appear to be", then the sender failed to pass either DKIM or SPF authentication checks. The best method to resolve this is for the sender to authorize themselves. If the sender is sending on your behalf, you need to authorize them by adding the sender's IP address to your SPF record.</span></span>
  
<span data-ttu-id="1463b-106">Vidim [Rešavanje problema vrh crvene (sumnjivo) sigurnost za otkrivanje prevare proverava](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) za više informacija.</span><span class="sxs-lookup"><span data-stu-id="1463b-106">See [Troubleshooting the red (suspicious) safety tip for fraud detection checks](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) for more info.</span></span> 
  
<span data-ttu-id="1463b-107">Evo nekih drugih veza koje vam mogu pomoći:</span><span class="sxs-lookup"><span data-stu-id="1463b-107">Here are some other links that can help:</span></span>
  
- [<span data-ttu-id="1463b-108">Kako Office 365 koristi pošiljaoca politički okvir (SPF) da biste sprečili obmane u vezi sa</span><span class="sxs-lookup"><span data-stu-id="1463b-108">How Office 365 uses sender policy framework (SPF) to prevent spoofing</span></span>](https://docs.microsoft.com/en-us/office365/SecurityCompliance/how-office-365-uses-spf-to-prevent-spoofing)
    
- [<span data-ttu-id="1463b-109">Podesite SPF u Office 365 da biste sprečili obmane u vezi sa</span><span class="sxs-lookup"><span data-stu-id="1463b-109">Set up SPF in Office 365 to help prevent spoofing</span></span>](https://docs.microsoft.com/en-us/office365/SecurityCompliance/set-up-spf-in-office-365-to-help-prevent-spoofing)
    

