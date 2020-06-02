---
title: Rešavanje problema sa sigurnosnim savjet za proveru otkrivanja prevara
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 96ebe3c5-66ea-4662-98b7-052c2181c2f3
ms.custom:
- "275"
- "3100004"
ms.openlocfilehash: 74913492a086de688067d588e95dd87e6946743b
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44504997"
---
# <a name="troubleshooting-the-safety-tip-for-fraud-detection-checks"></a><span data-ttu-id="bac90-102">Rešavanje problema sa sigurnosnim savjet za proveru otkrivanja prevara</span><span class="sxs-lookup"><span data-stu-id="bac90-102">Troubleshooting the safety tip for fraud detection checks</span></span>

<span data-ttu-id="bac90-103">Ako dobijate bezbednosni savet koji kaže "Pošiljalac nije uspeo da proveri da li je potrebno otkrivanje prevara i ne bude ono što se čini", onda pošiljalac nije uspeo da prosledi ili DKIM ili SPF proveru identiteta.</span><span class="sxs-lookup"><span data-stu-id="bac90-103">If you are getting a safety tip that says "The sender failed our fraud detection checks and may not be who they appear to be", then the sender failed to pass either DKIM or SPF authentication checks.</span></span> <span data-ttu-id="bac90-104">Najbolji metod za rješavanje ovog načina je da se pošiljalac ovlasti.</span><span class="sxs-lookup"><span data-stu-id="bac90-104">The best method to resolve this is for the sender to authorize themselves.</span></span> <span data-ttu-id="bac90-105">Ako pošiljalac šalje vaše ime, potrebno je da ih ovlastite tako što ćete dodati IP adresu pošiljaoca u vaš SPF zapis.</span><span class="sxs-lookup"><span data-stu-id="bac90-105">If the sender is sending on your behalf, you need to authorize them by adding the sender's IP address to your SPF record.</span></span>
  
<span data-ttu-id="bac90-106">Više informacija potražite [u članku rešavanje problema sa crvenim (sumnjivom) bezbednošću za proveru za otkrivanje prevara](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) .</span><span class="sxs-lookup"><span data-stu-id="bac90-106">See [Troubleshooting the red (suspicious) safety tip for fraud detection checks](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) for more info.</span></span>
  
<span data-ttu-id="bac90-107">Evo nekih drugih veza koje mogu da vam pomognu:</span><span class="sxs-lookup"><span data-stu-id="bac90-107">Here are some other links that can help:</span></span>
  
- [<span data-ttu-id="bac90-108">Kako Microsoft koristi okvir smernica za pošiljaoca (SPF) kako bi sprečio lažno korišćenje</span><span class="sxs-lookup"><span data-stu-id="bac90-108">How Microsoft uses sender policy framework (SPF) to prevent spoofing</span></span>](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-office-365-uses-spf-to-prevent-spoofing)

- [<span data-ttu-id="bac90-109">Podešavanje SPF-a za sprečavanje lažno prikazivanje</span><span class="sxs-lookup"><span data-stu-id="bac90-109">Set up SPF to help prevent spoofing</span></span>](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-spf-in-office-365-to-help-prevent-spoofing)
