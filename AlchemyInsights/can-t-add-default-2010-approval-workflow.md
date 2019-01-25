---
title: Nije moguće dodati podrazumevani tok posla za odobravanje 2010
ms.author: kirks
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 2060c9a1-e714-4d93-925e-629c82c35986
ms.openlocfilehash: 758b0339b842478f9609eb716b5b4ddab6579c80
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/24/2019
ms.locfileid: "29487171"
---
# <a name="cant-add-default-2010-approval-workflow"></a><span data-ttu-id="87c95-102">Nije moguće dodati podrazumevani tok posla za odobravanje 2010</span><span class="sxs-lookup"><span data-stu-id="87c95-102">Can't add default 2010 Approval Workflow</span></span>

<span data-ttu-id="87c95-103">U kolekciji lokacija Microsoft SharePoint, ne možete dodati globalno koji možete ponovo koristiti toka posla (kao što su „odobrenje - SharePoint 2010”) u listu ili biblioteku.</span><span class="sxs-lookup"><span data-stu-id="87c95-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="87c95-104">Da biste riješili taj problem, slijedite ove korake:</span><span class="sxs-lookup"><span data-stu-id="87c95-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="87c95-105">Otvorite osnovnu Web lokacija u kolekciji lokacija u SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="87c95-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="87c95-106">U okviru **Lokacije objekata**, izaberite **tokova posla**.</span><span class="sxs-lookup"><span data-stu-id="87c95-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="87c95-107">U **novom** delu glavnoj **tokova posla** , izaberite **Tok posla moguće ponovo koristiti**.</span><span class="sxs-lookup"><span data-stu-id="87c95-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="87c95-p101">**Kreiranje toka posla moguće ponovo koristiti** obrazac, unesite ime \* \*\*Repair2010\*\*\*. Za **Tip platforme**, izaberite **SharePoint 2010 toka posla**, a zatim izaberite **OK**.</span><span class="sxs-lookup"><span data-stu-id="87c95-p101">On the **Create Reusable Workflow** form, enter the name  \* **Repair2010**\* . For **Platform Type**, select **SharePoint 2010 Workflow**, and then select **OK**.</span></span> 
  
5. <span data-ttu-id="87c95-110">U odeljku **spasiti** glavne trake **toka posla** , izaberite **objavljivanje**.</span><span class="sxs-lookup"><span data-stu-id="87c95-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
6. <span data-ttu-id="87c95-p102">U odeljku za **Upravljanje** glavne trake **toka posla** , izaberite **Objavljivanje globalno**. U okviru za dijalog koji se pojavljuje, izaberite **OK**.</span><span class="sxs-lookup"><span data-stu-id="87c95-p102">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**. In the confirmation dialog box that appears, select **OK**.</span></span> 
  
7. <span data-ttu-id="87c95-p103">U web pregledaču, pronađite osnovne Web lokacija u kolekciji lokacija, a zatim pristupite **Postavke lokacije** \> **Funkcije kolekcije lokacija**. Onda, Uključi/isključi funkcije za **tokove posla** :</span><span class="sxs-lookup"><span data-stu-id="87c95-p103">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**. Then, toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="87c95-115">· Ako je funkcija *aktivirano* , kliknite **Deaktiviraj,** a zatim **Aktiviraj**.</span><span class="sxs-lookup"><span data-stu-id="87c95-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="87c95-116">· Ako je funkcija " *Deactivated* ", kliknite na dugme **Aktiviraj**.</span><span class="sxs-lookup"><span data-stu-id="87c95-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="87c95-117">Za više informacija pogledajte sledeći [članak](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="87c95-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  

