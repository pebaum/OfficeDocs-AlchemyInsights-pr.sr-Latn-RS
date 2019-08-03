---
title: Tok posla se ne pokreće
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 8/2/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000144"
- "1670"
ms.openlocfilehash: efd17c302ae6d857207e87e94d74d3794e94a83a
ms.sourcegitcommit: 204be4a6ae03700b75eae6b09b4e9ab283089fbf
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/03/2019
ms.locfileid: "36171809"
---
# <a name="workflow-is-not-starting"></a><span data-ttu-id="55216-102">Tok posla se ne pokreće</span><span class="sxs-lookup"><span data-stu-id="55216-102">Workflow is not starting</span></span>

- <span data-ttu-id="55216-103">SharePoint 2010 i SharePoint 2013 tokovi posla ne počinju.</span><span class="sxs-lookup"><span data-stu-id="55216-103">SharePoint 2010 and SharePoint 2013 workflows are not starting.</span></span>

    <span data-ttu-id="55216-104">Ako ne uspijete pokrenuti tok posla, postoji problem sa privremene servis gde korisnici iskusiti intervalni kašnjenja sa napredak toka posla.</span><span class="sxs-lookup"><span data-stu-id="55216-104">If your workflow is not starting, there may be a temporary service issue where users may experience intermittent delays with workflow progress.</span></span> <span data-ttu-id="55216-105">Proverite [Kontrolnu tablu zdravstvenih usluga](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) da vidim ako je uticala na vašu organizaciju.</span><span class="sxs-lookup"><span data-stu-id="55216-105">Check the [Service Health Dashboard](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) to see if your organization is impacted.</span></span>

    <span data-ttu-id="55216-106">Ako više od 24 sata je prošlo od kad ste prvi put videli ovaj problem, odjavite kartu za podršku.</span><span class="sxs-lookup"><span data-stu-id="55216-106">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="55216-107">U mnogim slučajevima, već radimo na rešenje.</span><span class="sxs-lookup"><span data-stu-id="55216-107">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="55216-108">Molim vas, dajte nam barem 24 sata da biste dovršili rešenje.</span><span class="sxs-lookup"><span data-stu-id="55216-108">Please give us at least 24 hours to complete a solution.</span></span>

- <span data-ttu-id="55216-109">Tokovi posla SharePoint 2010 odložen na start.</span><span class="sxs-lookup"><span data-stu-id="55216-109">SharePoint 2010 workflows delayed on start.</span></span>

    <span data-ttu-id="55216-110">To se događa ako se tok posla je aktivirati u velikom loncu.</span><span class="sxs-lookup"><span data-stu-id="55216-110">This occurs if the workflow is triggered in large batches.</span></span> <span data-ttu-id="55216-111">(na primer, kada nekoliko stavke dodaju u isto vreme).</span><span class="sxs-lookup"><span data-stu-id="55216-111">(for example, when several items are added at once).</span></span>

    <span data-ttu-id="55216-112">Tokovi posla nisu dizajnirani za pokretanje u realnom vremenu, tako da kašnjenja do dizajna ponašanje.</span><span class="sxs-lookup"><span data-stu-id="55216-112">Workflows are not designed to run real-time, so a delay is by-design behavior.</span></span>

    <span data-ttu-id="55216-113">Ako je tok posla kompleks Extensible objekat Markup Language (XMOL), kompilacije može biti sporo.</span><span class="sxs-lookup"><span data-stu-id="55216-113">If the Workflow is complex Extensible Object Markup Language (XMOL), compilation can be slow.</span></span> <span data-ttu-id="55216-114">Pogledajte [ovaj](https://support.microsoft.com/en-us/kb/3043697) članak.</span><span class="sxs-lookup"><span data-stu-id="55216-114">Check [this](https://support.microsoft.com/en-us/kb/3043697) article.</span></span>

    <span data-ttu-id="55216-115">Treba da pojednostavite toka posla ili redizajn i koristeći tip platforme Microsoft SharePoint 2013 toka posla.</span><span class="sxs-lookup"><span data-stu-id="55216-115">You should simplify the workflow or redesign it using the Microsoft SharePoint 2013 Workflow platform type.</span></span>

    <span data-ttu-id="55216-116">Osim toga, tok istorije je postala velika, možda ćete želeti da očisti stavke ili da kreirate novu listu istorije.</span><span class="sxs-lookup"><span data-stu-id="55216-116">Also, if your workflow history has grown large, you may want to purge the items or create a new history list.</span></span>

    <span data-ttu-id="55216-117">Više informacija: da [Očisti tok istorije](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span><span class="sxs-lookup"><span data-stu-id="55216-117">More Information : [Purge Workflow History](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span></span>


## <a name="related-topics"></a><span data-ttu-id="55216-118">Povezane teme</span><span class="sxs-lookup"><span data-stu-id="55216-118">Related topics</span></span>
<span data-ttu-id="55216-119">Da probamo Micrsoft protok u SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="55216-119">Want to try Micrsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="55216-120">Kreiranje toka</span><span class="sxs-lookup"><span data-stu-id="55216-120">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="55216-121">SharePoint i protok</span><span class="sxs-lookup"><span data-stu-id="55216-121">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


