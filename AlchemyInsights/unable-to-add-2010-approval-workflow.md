---
title: Nije moguće dodati tok posla za odobravanje 2010
ms.author: kirks
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 0df65cf9-7eae-4de7-88e9-1914635c8d11
ms.openlocfilehash: 3741b1169ddf731725c18fbaed80bfb321e5db46
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32366849"
---
# <a name="unable-to-add-2010-approval-workflow"></a><span data-ttu-id="f11b7-102">Nije moguće dodati tok posla za odobravanje 2010</span><span class="sxs-lookup"><span data-stu-id="f11b7-102">Unable to add 2010 Approval Workflow</span></span>

<span data-ttu-id="f11b7-103">U kolekciji lokacija Microsoft SharePoint, ne možete dodati globalno koji možete ponovo koristiti toka posla (kao što su „odobrenje - SharePoint 2010”) u listu ili biblioteku.</span><span class="sxs-lookup"><span data-stu-id="f11b7-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="f11b7-104">Da biste riješili taj problem, slijedite ove korake:</span><span class="sxs-lookup"><span data-stu-id="f11b7-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="f11b7-105">Otvorite osnovnu Web lokacija u kolekciji lokacija u SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="f11b7-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="f11b7-106">U okviru **Lokacije objekata**, izaberite **tokova posla**.</span><span class="sxs-lookup"><span data-stu-id="f11b7-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="f11b7-107">U **novom** delu glavnoj **tokova posla** , izaberite **Tok posla moguće ponovo koristiti**.</span><span class="sxs-lookup"><span data-stu-id="f11b7-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="f11b7-108">**Kreiranje toka posla moguće ponovo koristiti** obrazac, unesite ime \*\* *Repair2010* \*\*.</span><span class="sxs-lookup"><span data-stu-id="f11b7-108">On the **Create Reusable Workflow** form, enter the name \*\* *Repair2010* \*\*.</span></span> <span data-ttu-id="f11b7-109">Za **Tip platforme**, kliknite **SharePoint 2010 toka posla**, a zatim kliknite na dugme **u redu**.</span><span class="sxs-lookup"><span data-stu-id="f11b7-109">For **Platform Type**, click **SharePoint 2010 Workflow**, and then click **OK**.</span></span> 
  
1. <span data-ttu-id="f11b7-110">U odeljku **spasiti** glavne trake **toka posla** , izaberite **objavljivanje**.</span><span class="sxs-lookup"><span data-stu-id="f11b7-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
2. <span data-ttu-id="f11b7-111">U odeljku za **Upravljanje** glavne trake **toka posla** , izaberite **Objavljivanje globalno**.</span><span class="sxs-lookup"><span data-stu-id="f11b7-111">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**.</span></span> <span data-ttu-id="f11b7-112">U okviru za dijalog koji se pojavljuje, izaberite **OK**.</span><span class="sxs-lookup"><span data-stu-id="f11b7-112">In the confirmation dialog box that appears, select **OK**.</span></span> 
  
3. <span data-ttu-id="f11b7-113">U web pregledaču, pronađite osnovne Web lokacija u kolekciji lokacija, a zatim pristupite **Postavke lokacije** \> **Funkcije kolekcije lokacija**.</span><span class="sxs-lookup"><span data-stu-id="f11b7-113">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**.</span></span> <span data-ttu-id="f11b7-114">Uključi/isključi funkcije za **tokove posla** :</span><span class="sxs-lookup"><span data-stu-id="f11b7-114">Toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="f11b7-115">· Ako je funkcija *aktivirano* , kliknite **Deaktiviraj,** a zatim **Aktiviraj**.</span><span class="sxs-lookup"><span data-stu-id="f11b7-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="f11b7-116">· Ako je funkcija " *Deactivated* ", kliknite na dugme **Aktiviraj**.</span><span class="sxs-lookup"><span data-stu-id="f11b7-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="f11b7-117">Za više informacija pogledajte sledeći [članak](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="f11b7-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  

