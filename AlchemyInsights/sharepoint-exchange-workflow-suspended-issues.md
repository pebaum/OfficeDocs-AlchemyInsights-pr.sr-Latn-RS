---
title: Početak rada na lokaciji SharePoint online
ms.author: pebaum
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 7ae05f21-eb16-4d71-9e19-4f097eb100d2
ms.openlocfilehash: 5e61491b626bfe75fd26a15ee54be82d9efa19a7
ms.sourcegitcommit: defe2c412567b596fa8c3ab52111bde712ebb314
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/29/2019
ms.locfileid: "37766905"
---
# <a name="workflows-in-sharepoint"></a><span data-ttu-id="84dcb-102">Tokova posla u sistemu SharePoint</span><span class="sxs-lookup"><span data-stu-id="84dcb-102">Workflows in SharePoint</span></span>

<span data-ttu-id="84dcb-103">Ako SharePoint tokovi posla ne šalju e-poruke, vaša organizacija je možda naišla na ograničenja pošiljaoca na mreži.</span><span class="sxs-lookup"><span data-stu-id="84dcb-103">If SharePoint workflows are not sending emails, your organization may have encountered the Exchange Online sender limits.</span></span>

<span data-ttu-id="84dcb-104">Poruka o grešci "tok posla je obustavljena" može doći ako imate jednu od sledećih stavki:</span><span class="sxs-lookup"><span data-stu-id="84dcb-104">The 'Workflow is Suspended' error message may occur if you have one of the following items:</span></span>

- <span data-ttu-id="84dcb-105">Imate tok posla na SharePoint mreži koji koristi tip platforme SharePoint 2010 ili SharePoint 2013 Workflow.</span><span class="sxs-lookup"><span data-stu-id="84dcb-105">You have a workflow in SharePoint Online that's using the SharePoint 2010 or SharePoint 2013 workflow platform type.</span></span>

- <span data-ttu-id="84dcb-106">Tok posla je konfigurisan da šalje prilagođenu e-poruku u više od 200 korisnika u isto vreme, više od 10.000 primalaca dnevno ili više od 30 poruka u minuti.</span><span class="sxs-lookup"><span data-stu-id="84dcb-106">The workflow is configured to send a custom email message to more than 200 users at a time, more than 10,000 recipients per day, or more than 30 messages per minute.</span></span>

<span data-ttu-id="84dcb-107">Kada pokrenete tok posla, e-poruka se ne šalje, a vi primetite poruku o grešci, unutrašnji status je postavljen na suspendovano ili nije moguće poslati primaocu.</span><span class="sxs-lookup"><span data-stu-id="84dcb-107">When you run the workflow, the email message isn't sent, and you notice the error message, Internal Status is set to Suspended or Unable to send to a recipient is displayed.</span></span>

<span data-ttu-id="84dcb-108">Za više informacija pogledajte sledeći [članak](https://docs.microsoft.com/sharepoint/support/workflows/configured-workflow-fails-running).</span><span class="sxs-lookup"><span data-stu-id="84dcb-108">For more information, please refer to the following [article](https://docs.microsoft.com/sharepoint/support/workflows/configured-workflow-fails-running).</span></span>

