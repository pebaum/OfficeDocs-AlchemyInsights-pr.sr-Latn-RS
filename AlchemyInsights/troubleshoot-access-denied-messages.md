---
title: Rešavanje problema sa programom Access je porekao poruke
ms.author: pebaum
author: pebaum
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 05d12aee49b449e8a29e84021b41298fb9983859
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40050719"
---
# <a name="troubleshoot-access-denied-messages"></a><span data-ttu-id="594bd-102">Rešavanje problema sa programom Access je porekao poruke</span><span class="sxs-lookup"><span data-stu-id="594bd-102">Troubleshoot Access Denied messages</span></span>

<span data-ttu-id="594bd-103">Ako je neko dobio poruku "pristup je odbijen" u deljenoj fascikli u sistemu SharePoint, administrator kolekcije lokacija je možda omogućio "režim zaključenja korisnika ograničenog pristupa".</span><span class="sxs-lookup"><span data-stu-id="594bd-103">If someone got an "Access Denied" message to a shared folder in SharePoint, the site collection administrator might have enabled "Limited-access user permission lockdown mode."</span></span> <span data-ttu-id="594bd-104">Da biste isključili ovu opciju:</span><span class="sxs-lookup"><span data-stu-id="594bd-104">To turn this off:</span></span> 
  
1. <span data-ttu-id="594bd-105">Potražite lokaciju, kliknite na ikonu postavke, a zatim izaberite stavku **Postavke lokacije**.</span><span class="sxs-lookup"><span data-stu-id="594bd-105">Browse to the site, click the Settings icon, and then click **Site Settings**.</span></span>
    
2. <span data-ttu-id="594bd-106">U okviru stavke **Administracija kolekcije lokacija**izaberite stavku **funkcije kolekcije lokacija**.</span><span class="sxs-lookup"><span data-stu-id="594bd-106">Under **Site Collection Administration**, click **Site collection features**.</span></span>
    
3. <span data-ttu-id="594bd-107">Kliknite na dugme " **Deaktiviraj**" pored **Access režima za zaključavanje ograničenog pristupa**.</span><span class="sxs-lookup"><span data-stu-id="594bd-107">Next to **Limited-access user permission lockdown mode**, click **Deactivate**.</span></span>
    
<span data-ttu-id="594bd-108">Poruka koja je odbijena za pristup može da se pojavi i za deljene fascikle ako je lokacija lokacija za objavljivanje.</span><span class="sxs-lookup"><span data-stu-id="594bd-108">An Access Denied message can also occur for shared folders if the site is a publishing site.</span></span> <span data-ttu-id="594bd-109">Za informacije pogledajte odeljak " [pristup nije dozvoljen" prilikom pristupanja deljenoj fascikli](https://go.microsoft.com/fwlink/?linkid=2004317).</span><span class="sxs-lookup"><span data-stu-id="594bd-109">For info, see [Access Denied when accessing a shared folder](https://go.microsoft.com/fwlink/?linkid=2004317).</span></span>
  
<span data-ttu-id="594bd-110">Ako je neko dobio poruku "pristup odbijen" prilikom pokušaja prikaza zahteva za pristup, korisnik mora da bude dodat kao administrator kolekcije lokacija ili član grupe vlasnika lokacije.</span><span class="sxs-lookup"><span data-stu-id="594bd-110">If a someone got an "Access Denied" message when trying to view access requests, the user needs to be added as either a site collection administrator or a member of the Owners group for the site.</span></span> <span data-ttu-id="594bd-111">Više informacija potražite u članku [zabranjen pristup listi zahteva za pristup](https://go.microsoft.com/fwlink/?linkid=2004220).</span><span class="sxs-lookup"><span data-stu-id="594bd-111">For more info, see [Access Denied to Access Requests list](https://go.microsoft.com/fwlink/?linkid=2004220).</span></span>
  
<span data-ttu-id="594bd-112">Ako je korisnik dobio poruku "pristup je odbijen" Nakon uklanjanja iz aktivnog direktorijuma u okviru objekta, a zatim ponovo dodat, pogledajte odeljak " [pristup odbijen kada se korisnički nalog sinhronizuje sa Office 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span><span class="sxs-lookup"><span data-stu-id="594bd-112">If a user got an "Access Denied" message after they were removed from Active Directory on-premises and then added back, see [Access Denied when a user account is synced to Office 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span></span>
  

