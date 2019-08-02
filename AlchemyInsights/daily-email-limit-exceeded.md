---
title: Daily Mail ograničenje je prekoračeno. Tok posla je obustavljen.
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 7/25/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1227"
ms.openlocfilehash: 802aba696da61be5f0a6c12072842cbc3cd96499
ms.sourcegitcommit: 407f6c1e82f1a0be5cf53301fbf03cd25dcbf0ee
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/02/2019
ms.locfileid: "36059652"
---
# <a name="daily-email-limit-exceeded-workflow-is-suspended"></a><span data-ttu-id="69ea8-103">Daily Mail je prekoračeno ograničenje.</span><span class="sxs-lookup"><span data-stu-id="69ea8-103">Daily email Limit Exceeded.</span></span> <span data-ttu-id="69ea8-104">Tok posla je obustavljen.</span><span class="sxs-lookup"><span data-stu-id="69ea8-104">Workflow is suspended.</span></span>

<span data-ttu-id="69ea8-105">Ova greška može biti primljen u sljedećim scenarijima:</span><span class="sxs-lookup"><span data-stu-id="69ea8-105">This error may be received in the following scenarios:</span></span>

- <span data-ttu-id="69ea8-106">Imate toka posla u SharePoint na mreži koja koristi SharePoint 2010 ili SharePoint 2013 toka posla platforma tip.</span><span class="sxs-lookup"><span data-stu-id="69ea8-106">You have a workflow in SharePoint Online that's using the SharePoint 2010 or SharePoint 2013 workflow platform type.</span></span>
- <span data-ttu-id="69ea8-107">Tok je konfigurisan da pošaljete poruku prilagođene e-pošte za više od 200 korisnika po jedan, više od 10 000 primalaca dnevno ili više od 30 poruka u minuti.</span><span class="sxs-lookup"><span data-stu-id="69ea8-107">The workflow is configured to send a custom email message to more than 200 users at a time, more than 10,000 recipients per day, or more than 30 messages per minute.</span></span>
- <span data-ttu-id="69ea8-108">Kada pokrenete tok posla, zar ne poslati poruku e-pošte i primetite na sljedeći način:</span><span class="sxs-lookup"><span data-stu-id="69ea8-108">When you run the workflow, the email message isn't sent, and you notice the following behavior:</span></span>
    - <span data-ttu-id="69ea8-109">Za tok posla pomoću SharePoint 2013 tip platforme, pregledate na stranicu " **Status toka posla** ".</span><span class="sxs-lookup"><span data-stu-id="69ea8-109">For a workflow using the SharePoint 2013 platform type, you browse to the **Workflow Status** page.</span></span> <span data-ttu-id="69ea8-110">Na stranici "Status toka posla", **Unutrašnja Status** je podešen na **pokrenuto**, a balon informacija prikazuje **nije moguće poslati primaocu**.</span><span class="sxs-lookup"><span data-stu-id="69ea8-110">On the Workflow Status page, the **Internal Status** is set to **Started**, and the information balloon displays **Unable to send to a recipient**.</span></span>

<span data-ttu-id="69ea8-111">Da biste rešili ovaj problem, konfigurišite vaš tok posla za slanje e-poruka bez prekoračenja [ograničenja za Exchange Online pošiljaoca](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits).</span><span class="sxs-lookup"><span data-stu-id="69ea8-111">To work around this issue, configure your workflow to send email messages without exceeding the [Exchange Online sender limits](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits).</span></span> <span data-ttu-id="69ea8-112">Na primer, koristite pauze u toku posla, pošaljite e-poštu grupi programa Office 365, grupi za distribuciju ili pošta omogućena bezbednost grupe ili manje od 200 primaocima istovremeno pošaljete poruku.</span><span class="sxs-lookup"><span data-stu-id="69ea8-112">For example, use a pause in the workflow, send the email to an Office 365 group, a distribution group or mail enabled security group, or send the message to fewer than 200 recipients at a time.</span></span>


<span data-ttu-id="69ea8-113">Za više informacija, pogledajte sledeći [članak](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or).</span><span class="sxs-lookup"><span data-stu-id="69ea8-113">For more information, see the following [article](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or).</span></span>

## <a name="related-topics"></a><span data-ttu-id="69ea8-114">Povezane teme</span><span class="sxs-lookup"><span data-stu-id="69ea8-114">Related topics</span></span>
- [<span data-ttu-id="69ea8-115">Kreiranje toka</span><span class="sxs-lookup"><span data-stu-id="69ea8-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="69ea8-116">SharePoint i protok</span><span class="sxs-lookup"><span data-stu-id="69ea8-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 