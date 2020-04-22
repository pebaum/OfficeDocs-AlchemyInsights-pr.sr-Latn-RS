---
title: Tok posla ne počinje
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000144"
- "1670"
ms.openlocfilehash: 941e6349c98278a1a8cdac77457ec1cc72cdef8b
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766111"
---
# <a name="workflow-is-not-starting"></a><span data-ttu-id="2492b-102">Tok posla ne počinje</span><span class="sxs-lookup"><span data-stu-id="2492b-102">Workflow is not starting</span></span>

- <span data-ttu-id="2492b-103">SharePoint 2010 i SharePoint 2013 tokovi posla se ne pokreću.</span><span class="sxs-lookup"><span data-stu-id="2492b-103">SharePoint 2010 and SharePoint 2013 workflows are not starting.</span></span>

    - <span data-ttu-id="2492b-104">Ako tok posla nije počeo, možda postoji problem sa privremenim servisom u kome korisnici mogu iskusiti povremene kašnjenja sa napretkom toka posla.</span><span class="sxs-lookup"><span data-stu-id="2492b-104">If your workflow is not starting, there may be a temporary service issue where users may experience intermittent delays with workflow progress.</span></span> <span data-ttu-id="2492b-105">Proverite da li je vaša organizacija uticala na [instrument za zdravstvo](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) .</span><span class="sxs-lookup"><span data-stu-id="2492b-105">Check the [Service Health Dashboard](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) to see if your organization is impacted.</span></span>

    - <span data-ttu-id="2492b-106">Ako je prošlo više od 24 časa od kada ste prvi put videli ovaj problem, molimo vas da prijavite tiket za podršku.</span><span class="sxs-lookup"><span data-stu-id="2492b-106">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="2492b-107">U mnogim slučajevima već radimo na rešenju.</span><span class="sxs-lookup"><span data-stu-id="2492b-107">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="2492b-108">Molimo vas da nam date najmanje 24 sata da završimo rešenje.</span><span class="sxs-lookup"><span data-stu-id="2492b-108">Please give us at least 24 hours to complete a solution.</span></span>

- <span data-ttu-id="2492b-109">SharePoint 2010 tokovi posla su odloženi na početnom ekranu.</span><span class="sxs-lookup"><span data-stu-id="2492b-109">SharePoint 2010 workflows delayed on start.</span></span>

    - <span data-ttu-id="2492b-110">Ovo se dešava ako se tok posla aktivira u velikim grupama.</span><span class="sxs-lookup"><span data-stu-id="2492b-110">This occurs if the workflow is triggered in large batches.</span></span> <span data-ttu-id="2492b-111">(na primer, kada je nekoliko stavki dodato odjednom).</span><span class="sxs-lookup"><span data-stu-id="2492b-111">(for example, when several items are added at once).</span></span>

    - <span data-ttu-id="2492b-112">Tokovi posla nisu dizajnirani da rade u realnom vremenu, tako da je odlaganje ponašanje po dizajnu.</span><span class="sxs-lookup"><span data-stu-id="2492b-112">Workflows are not designed to run real-time, so a delay is by-design behavior.</span></span>

   -  <span data-ttu-id="2492b-113">Ako je tok posla složen, Extensible Markup Language (XMOL), kompilacije mogu biti spore.</span><span class="sxs-lookup"><span data-stu-id="2492b-113">If the Workflow is complex Extensible Object Markup Language (XMOL), compilation can be slow.</span></span> <span data-ttu-id="2492b-114">Proverite [ovaj](https://support.microsoft.com//kb/3043697) članak.</span><span class="sxs-lookup"><span data-stu-id="2492b-114">Check [this](https://support.microsoft.com//kb/3043697) article.</span></span>

    - <span data-ttu-id="2492b-115">Trebalo bi da pojednostavite tok posla ili da ga redizajnite pomoću tipa platforme Microsoft SharePoint 2013 toka posla.</span><span class="sxs-lookup"><span data-stu-id="2492b-115">You should simplify the workflow or redesign it using the Microsoft SharePoint 2013 Workflow platform type.</span></span>

    - <span data-ttu-id="2492b-116">Ako je istorija toka posla odrasla, možda ćete želeti da ih počistite ili da kreirate novu listu istorije.</span><span class="sxs-lookup"><span data-stu-id="2492b-116">If your workflow history has grown large, you may want to purge the items or create a new history list.</span></span>

        <span data-ttu-id="2492b-117">Više informacija: [Očisti istoriju toka posla](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span><span class="sxs-lookup"><span data-stu-id="2492b-117">More Information : [Purge Workflow History](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span></span>


## <a name="related-topics"></a><span data-ttu-id="2492b-118">Povezane teme</span><span class="sxs-lookup"><span data-stu-id="2492b-118">Related topics</span></span>
<span data-ttu-id="2492b-119">Želite li da isprobate Microsoft protok na SharePoint mreži?</span><span class="sxs-lookup"><span data-stu-id="2492b-119">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="2492b-120">Kreiraj tok</span><span class="sxs-lookup"><span data-stu-id="2492b-120">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="2492b-121">SharePoint i protok</span><span class="sxs-lookup"><span data-stu-id="2492b-121">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


