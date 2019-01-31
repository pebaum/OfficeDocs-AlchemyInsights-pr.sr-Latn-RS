---
title: Rešavanje problema u Savetu bezbednosti za otkrivanje prevare proverava
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 96ebe3c5-66ea-4662-98b7-052c2181c2f3
ms.openlocfilehash: 06a0b5b8d29052e6033de5938b8ea67ceabc9848
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/30/2019
ms.locfileid: "29658129"
---
# <a name="troubleshooting-the-safety-tip-for-fraud-detection-checks"></a><span data-ttu-id="89acc-102">Rešavanje problema u Savetu bezbednosti za otkrivanje prevare proverava</span><span class="sxs-lookup"><span data-stu-id="89acc-102">Troubleshooting the safety tip for fraud detection checks</span></span>



<span data-ttu-id="89acc-p101">Ako ste dobiti napojnicu sigurnost koja kaže „pošiljalac nije uspelo čekove za otkrivanje prevare, i možda nije koji izgledaju kao da su”, a zatim pošiljalac nije uspjelo proći ili DKIM ili SPF provere identiteta. Najbolji metod da biste rešili ovo je za pošiljaoca da odobri sami sebe. Ako pošiljalac šalje u vaše ime, potrebno je da odobrite ih tako što ćete dodati IP adresu pošiljaoca na tvoj SPF zapis.</span><span class="sxs-lookup"><span data-stu-id="89acc-p101">If you are getting a safety tip that says "The sender failed our fraud detection checks and may not be who they appear to be", then the sender failed to pass either DKIM or SPF authentication checks. The best method to resolve this is for the sender to authorize themselves. If the sender is sending on your behalf, you need to authorize them by adding the sender's IP address to your SPF record.</span></span>
  
<span data-ttu-id="89acc-106">Vidim [Rešavanje problema vrh crvene (sumnjivo) sigurnost za otkrivanje prevare proverava](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) za više informacija.</span><span class="sxs-lookup"><span data-stu-id="89acc-106">See [Troubleshooting the red (suspicious) safety tip for fraud detection checks](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) for more info.</span></span> 
  
<span data-ttu-id="89acc-107">Evo nekih drugih veza koje vam mogu pomoći:</span><span class="sxs-lookup"><span data-stu-id="89acc-107">Here are some other links that can help:</span></span>
  
- [<span data-ttu-id="89acc-108">Kako Office 365 koristi pošiljaoca politički okvir (SPF) da biste sprečili obmane u vezi sa</span><span class="sxs-lookup"><span data-stu-id="89acc-108">How Office 365 uses sender policy framework (SPF) to prevent spoofing</span></span>](https://docs.microsoft.com/office365/SecurityCompliance/how-office-365-uses-spf-to-prevent-spoofing)
    
- [<span data-ttu-id="89acc-109">Podesite SPF u Office 365 da biste sprečili obmane u vezi sa</span><span class="sxs-lookup"><span data-stu-id="89acc-109">Set up SPF in Office 365 to help prevent spoofing</span></span>](https://docs.microsoft.com/office365/SecurityCompliance/set-up-spf-in-office-365-to-help-prevent-spoofing)
    

