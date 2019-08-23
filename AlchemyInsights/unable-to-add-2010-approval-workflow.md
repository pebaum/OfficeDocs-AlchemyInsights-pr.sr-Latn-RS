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
ms.openlocfilehash: 1f564c5d1e689dcf41b22fab5a05ab1b488c2b0b
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36558631"
---
# <a name="unable-to-add-2010-approval-workflow"></a><span data-ttu-id="e83c9-102">Nije moguće dodati tok posla za odobravanje 2010</span><span class="sxs-lookup"><span data-stu-id="e83c9-102">Unable to add 2010 Approval Workflow</span></span>

<span data-ttu-id="e83c9-103">U kolekciji lokacija Microsoft SharePoint, ne možete dodati globalno koji možete ponovo koristiti toka posla (kao što su „odobrenje - SharePoint 2010”) u listu ili biblioteku.</span><span class="sxs-lookup"><span data-stu-id="e83c9-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="e83c9-104">Da biste riješili taj problem, slijedite ove korake:</span><span class="sxs-lookup"><span data-stu-id="e83c9-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="e83c9-105">Otvorite osnovnu Web lokacija u kolekciji lokacija u SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="e83c9-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="e83c9-106">U okviru **Lokacije objekata**, izaberite **tokova posla**.</span><span class="sxs-lookup"><span data-stu-id="e83c9-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="e83c9-107">U **novom** delu glavnoj **tokova posla** , izaberite **Tok posla moguće ponovo koristiti**.</span><span class="sxs-lookup"><span data-stu-id="e83c9-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="e83c9-108">**Kreiranje toka posla moguće ponovo koristiti** obrazac, unesite ime \*\* *Repair2010* \*\*.</span><span class="sxs-lookup"><span data-stu-id="e83c9-108">On the **Create Reusable Workflow** form, enter the name \*\* *Repair2010* \*\*.</span></span> <span data-ttu-id="e83c9-109">Za **Tip platforme**, kliknite **SharePoint 2010 toka posla**, a zatim kliknite na dugme **u redu**.</span><span class="sxs-lookup"><span data-stu-id="e83c9-109">For **Platform Type**, click **SharePoint 2010 Workflow**, and then click **OK**.</span></span> 
  
1. <span data-ttu-id="e83c9-110">U odeljku **spasiti** glavne trake **toka posla** , izaberite **objavljivanje**.</span><span class="sxs-lookup"><span data-stu-id="e83c9-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
2. <span data-ttu-id="e83c9-111">U odeljku za **Upravljanje** glavne trake **toka posla** , izaberite **Objavljivanje globalno**.</span><span class="sxs-lookup"><span data-stu-id="e83c9-111">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**.</span></span> <span data-ttu-id="e83c9-112">U okviru za dijalog koji se pojavljuje, izaberite **OK**.</span><span class="sxs-lookup"><span data-stu-id="e83c9-112">In the confirmation dialog box that appears, select **OK**.</span></span> 
  
3. <span data-ttu-id="e83c9-113">U web pregledaču, pronađite osnovne Web lokacija u kolekciji lokacija, a zatim pristupite **Postavke lokacije** \> **Funkcije kolekcije lokacija**.</span><span class="sxs-lookup"><span data-stu-id="e83c9-113">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**.</span></span> <span data-ttu-id="e83c9-114">Uključi/isključi funkcije za **tokove posla** :</span><span class="sxs-lookup"><span data-stu-id="e83c9-114">Toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="e83c9-115">· Ako je funkcija *aktivirano* , kliknite **Deaktiviraj,** a zatim **Aktiviraj**.</span><span class="sxs-lookup"><span data-stu-id="e83c9-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="e83c9-116">· Ako je funkcija " *Deactivated* ", kliknite na dugme **Aktiviraj**.</span><span class="sxs-lookup"><span data-stu-id="e83c9-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="e83c9-117">Za više informacija pogledajte sledeći [članak](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="e83c9-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  

