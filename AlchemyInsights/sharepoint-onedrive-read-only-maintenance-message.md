---
title: Samo za čitanje za održavanje poruku kada pokušate da koristite SharePoint ili OneDrive
ms.author: efrene
author: efrene
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "127"
- "128"
ms.assetid: de7b6877-f3f9-4402-8072-c73783aaccaa
ms.openlocfilehash: 5b1e56253d6deeb0f9ba2f753eff5c00ff9c51a2
ms.sourcegitcommit: cd79ecca88b2cb166f78f44ab8bc4e8136729418
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/23/2019
ms.locfileid: "36620737"
---
# <a name="read-only-for-maintenance-message-when-attempting-to-use-sharepoint-or-onedrive"></a><span data-ttu-id="f3e5e-102">Samo za čitanje za održavanje poruku kada pokušate da koristite SharePoint ili OneDrive</span><span class="sxs-lookup"><span data-stu-id="f3e5e-102">Read-Only for Maintenance message when attempting to use SharePoint or OneDrive</span></span>

<span data-ttu-id="f3e5e-103">Korisnici mogu dobiti poruku **Samo za čitanje za održavanje** kada pokušaju da koriste SharePoint ili OneDrive za jedan od sledećih scenarija.</span><span class="sxs-lookup"><span data-stu-id="f3e5e-103">Users may receive a **Read-Only for Maintenance** message when attempting to use SharePoint or OneDrive for one of the following scenarios.</span></span> 

-   <span data-ttu-id="f3e5e-104">Aktivnost na planirane ili aktivnog održavanja.</span><span class="sxs-lookup"><span data-stu-id="f3e5e-104">A planned or active maintenance activity.</span></span>  <span data-ttu-id="f3e5e-105">Potraži ih navigacijom u [Centar za poruke](https://portal.office.com/adminportal/home#/messagecenter).</span><span class="sxs-lookup"><span data-stu-id="f3e5e-105">Check for them by navigating to the [Message Center](https://portal.office.com/adminportal/home#/messagecenter).</span></span>
-   <span data-ttu-id="f3e5e-106">Incident aktivne usluge visokog prioriteta, to može biti zatvorena.</span><span class="sxs-lookup"><span data-stu-id="f3e5e-106">A high-priority, active service incident that may be occurring.</span></span> <span data-ttu-id="f3e5e-107">Potraži savjete/incidenti, navigacijom do [Zdravstvenih usluga](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="f3e5e-107">Check for any advisories/incidents by navigating to [Service Health](https://portal.office.com/adminportal/home#/servicehealth).</span></span>
-   <span data-ttu-id="f3e5e-108">Manji isceljenja automatskog oporavka scenario koji moglo dogoditi zbog neočekivane događaje na serverima koji može trajati za manje od 30 min ili tako nešto.</span><span class="sxs-lookup"><span data-stu-id="f3e5e-108">A minor auto-healing recovery scenario that could be happening due to any unexpected events on the servers which might last for less than 30 min or so.</span></span> 
    
    <span data-ttu-id="f3e5e-109">Postoje nema centar za poruke ili zdravstveni servis knjiži ovih manjih oporavljaju, ali ti treba da se vrati u normalu uskoro.</span><span class="sxs-lookup"><span data-stu-id="f3e5e-109">There are no Message Center or Service Health posts for these minor recoveries but you should be back to normal very soon.</span></span>

<span data-ttu-id="f3e5e-110">U nekoliko navrata posmatrali smo da jedan od tri scenarija gore navedene bio uzrok, i usluga obnovljena, ali korisnici pregledača keš nije postala jasnija.</span><span class="sxs-lookup"><span data-stu-id="f3e5e-110">On very few occasions we observed that one of the three scenarios listed above have been the cause, and service has been restored, but the users browser cache hasn’t been cleared up.</span></span>

<span data-ttu-id="f3e5e-111">Molim te, pokušati da biste obrisali keš memoriju pregledača ranije kretanje do lokacije.</span><span class="sxs-lookup"><span data-stu-id="f3e5e-111">Please attempt to clear the browser cache before navigating to the site.</span></span>

1. <span data-ttu-id="f3e5e-112">U pregledaču Microsoft Edge, izaberite stavku **Postavke**, a zatim izaberite **privatnosti i bezbednosti**.</span><span class="sxs-lookup"><span data-stu-id="f3e5e-112">In your Microsoft Edge browser, select **Settings**, and then select **Privacy and Security**.</span></span>
2. <span data-ttu-id="f3e5e-113">Pod **jasno pregledanja**, izaberite **izaberem kako biste obrisali**.</span><span class="sxs-lookup"><span data-stu-id="f3e5e-113">Under **Clear browsing**, select **Choose what to clear**.</span></span>
3. <span data-ttu-id="f3e5e-114">Izaberite **kolačiće i podatke sačuvane Veb lokacija**i izaberite **Obriši**.</span><span class="sxs-lookup"><span data-stu-id="f3e5e-114">Select **Cookies and saved website data**, and select **Clear**.</span></span>

>[!Note] 
> <span data-ttu-id="f3e5e-115">Ovi koraci mogu da se razlikuju kada koristite drugi pregledači, kao što su Mozilla Firefox ili Google Chrome.</span><span class="sxs-lookup"><span data-stu-id="f3e5e-115">These steps may differ when using other browsers such as Mozilla Firefox or Google Chrome.</span></span>

>[!Note] 
> <span data-ttu-id="f3e5e-116">Druga opcija je da otvorite SharePoint lokacija ili OneDrive u novom prozoru InPrivate.</span><span class="sxs-lookup"><span data-stu-id="f3e5e-116">Another option would be to open your SharePoint site or OneDrive in a new InPrivate window.</span></span>