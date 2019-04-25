---
title: Nedostaje tok posla nije uspeo da aktivira
ms.author: kirks
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: e46ae8c5-3d81-457e-8c77-f7c1cbe267c4
ms.openlocfilehash: ce088227a3206fa05b99331fdb022fbe4886203f
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32418447"
---
# <a name="missing-workflow-failed-to-activate"></a><span data-ttu-id="eb11d-102">Nedostaje tok posla nije uspeo da aktivira</span><span class="sxs-lookup"><span data-stu-id="eb11d-102">Missing Workflow Failed to Activate</span></span>

<span data-ttu-id="eb11d-103">U kolekciji lokacija Microsoft SharePoint, ne možete dodati globalno koji možete ponovo koristiti toka posla (kao što su „odobrenje - SharePoint 2010”) u listu ili biblioteku.</span><span class="sxs-lookup"><span data-stu-id="eb11d-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="eb11d-104">Da biste riješili taj problem, slijedite ove korake:</span><span class="sxs-lookup"><span data-stu-id="eb11d-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="eb11d-105">Otvorite osnovnu Web lokacija u kolekciji lokacija u SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="eb11d-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="eb11d-106">U okviru **Lokacije objekata**, izaberite **tokova posla**.</span><span class="sxs-lookup"><span data-stu-id="eb11d-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="eb11d-107">U **novom** delu glavnoj **tokova posla** , izaberite **Tok posla moguće ponovo koristiti**.</span><span class="sxs-lookup"><span data-stu-id="eb11d-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="eb11d-108">**Kreiranje toka posla moguće ponovo koristiti** obrazac, unesite ime \*\* *Repair2010* \*\*.</span><span class="sxs-lookup"><span data-stu-id="eb11d-108">On the **Create Reusable Workflow** form, enter the name \*\* *Repair2010* \*\*.</span></span> <span data-ttu-id="eb11d-109">Za **Tip platforme**, kliknite **SharePoint 2010 toka posla**, a zatim kliknite na dugme **u redu**.</span><span class="sxs-lookup"><span data-stu-id="eb11d-109">For **Platform Type**, click **SharePoint 2010 Workflow**, and then click **OK**.</span></span> 
  
1. <span data-ttu-id="eb11d-110">U odeljku **spasiti** glavne trake **toka posla** , izaberite **objavljivanje**.</span><span class="sxs-lookup"><span data-stu-id="eb11d-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
2. <span data-ttu-id="eb11d-111">U odeljku za **Upravljanje** glavne trake **toka posla** , izaberite **Objavljivanje globalno**.</span><span class="sxs-lookup"><span data-stu-id="eb11d-111">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**.</span></span> <span data-ttu-id="eb11d-112">U okviru za dijalog koji se pojavljuje, izaberite **OK**.</span><span class="sxs-lookup"><span data-stu-id="eb11d-112">In the confirmation dialog box that appears, select **OK**.</span></span> 
  
3. <span data-ttu-id="eb11d-113">U web pregledaču, pronađite osnovne Web lokacija u kolekciji lokacija, a zatim pristupite **Postavke lokacije** \> **Funkcije kolekcije lokacija**.</span><span class="sxs-lookup"><span data-stu-id="eb11d-113">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**.</span></span> <span data-ttu-id="eb11d-114">Onda, Uključi/isključi funkcije za **tokove posla** :</span><span class="sxs-lookup"><span data-stu-id="eb11d-114">Then, toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="eb11d-115">· Ako je funkcija *aktivirano* , kliknite **Deaktiviraj,** a zatim **Aktiviraj**.</span><span class="sxs-lookup"><span data-stu-id="eb11d-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="eb11d-116">· Ako je funkcija " *Deactivated* ", kliknite na dugme **Aktiviraj**.</span><span class="sxs-lookup"><span data-stu-id="eb11d-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="eb11d-117">Za više informacija pogledajte sledeći [članak](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="eb11d-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  

