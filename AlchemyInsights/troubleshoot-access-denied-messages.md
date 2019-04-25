---
title: Rešavanje problema sa zabranom pristupa porukama
ms.author: kaarins
author: kaarins
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: f1a4803838b6511ef4fe7f03cafa4aa13b3c9734
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32420714"
---
# <a name="troubleshoot-access-denied-messages"></a><span data-ttu-id="22588-102">Rešavanje problema sa zabranom pristupa porukama</span><span class="sxs-lookup"><span data-stu-id="22588-102">Troubleshoot Access Denied messages</span></span>

<span data-ttu-id="22588-103">Ako je neko dobio poruku „Zabranjen pristup” u deljenu fasciklu, administrator kolekcije lokacija možda ste omogućili „ograničen pristup korisnika dozvola pritajili”.</span><span class="sxs-lookup"><span data-stu-id="22588-103">If someone got an "Access Denied" message to a shared folder, the site collection administrator might have enabled "Limited-access user permission lockdown mode."</span></span> <span data-ttu-id="22588-104">Da biste ovo isključili:</span><span class="sxs-lookup"><span data-stu-id="22588-104">To turn this off:</span></span> 
  
1. <span data-ttu-id="22588-105">Pretraživanje lokacije, kliknite na ikonu za postavke i zatim kliknite na dugme **Postavke lokacije**.</span><span class="sxs-lookup"><span data-stu-id="22588-105">Browse to the site, click the Settings icon, and then click **Site Settings**.</span></span>
    
2. <span data-ttu-id="22588-106">Pod **Administracija kolekcije lokacija**, kliknite na dugme **Opcije kolekcije lokacija**.</span><span class="sxs-lookup"><span data-stu-id="22588-106">Under **Site Collection Administration**, click **Site collection features**.</span></span>
    
3. <span data-ttu-id="22588-107">Pored **ograničen pristup korisnika dozvola pritajili**, kliknite **Deaktiviraj**.</span><span class="sxs-lookup"><span data-stu-id="22588-107">Next to **Limited-access user permission lockdown mode**, click **Deactivate**.</span></span>
    
<span data-ttu-id="22588-108">Poruci zabranjen pristup takođe može doći zbog deljenim fasciklama ako se lokacija lokaciji za objavljivanje.</span><span class="sxs-lookup"><span data-stu-id="22588-108">An Access Denied message can also occur for shared folders if the site is a publishing site.</span></span> <span data-ttu-id="22588-109">Info, potražite [Zabranjen pristup prilikom pristupanja deljenu fasciklu](https://go.microsoft.com/fwlink/?linkid=2004317).</span><span class="sxs-lookup"><span data-stu-id="22588-109">For info, see [Access Denied when accessing a shared folder](https://go.microsoft.com/fwlink/?linkid=2004317).</span></span>
  
<span data-ttu-id="22588-110">Ako je neko dobio poruku „Zabranjen pristup” pri pokušaju da se prikažete zahtevima za odobrenje pristupa, korisnik treba dodati kao administrator kolekcije lokacija ili član grupe vlasnika lokacije.</span><span class="sxs-lookup"><span data-stu-id="22588-110">If a someone got an "Access Denied" message when trying to view access requests, the user needs to be added as either a site collection administrator or a member of the Owners group for the site.</span></span> <span data-ttu-id="22588-111">Za više informacija, vidi [Zabranjen pristup zahtevima za odobrenje pristupa listi](https://go.microsoft.com/fwlink/?linkid=2004220).</span><span class="sxs-lookup"><span data-stu-id="22588-111">For more info, see [Access Denied to Access Requests list](https://go.microsoft.com/fwlink/?linkid=2004220).</span></span>
  
<span data-ttu-id="22588-112">Ako korisnik je dobio poruku „Zabranjen pristup” nakon što su uklonjeni iz aktivnog direktorijuma na više lokacija i zatim dodaje nazad, vidimo da je [Zabranjen pristup kada korisnički nalog sinhronizovan Office 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span><span class="sxs-lookup"><span data-stu-id="22588-112">If a user got an "Access Denied" message after they were removed from Active Directory on-premises and then added back, see [Access Denied when a user account is synced to Office 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span></span>
  

