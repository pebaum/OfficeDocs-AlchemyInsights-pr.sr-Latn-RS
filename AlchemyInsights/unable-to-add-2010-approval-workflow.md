---
title: Nije moguće dodati 2010 tok posla za odobravanje
ms.author: pebaum
author: pebaum
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 0df65cf9-7eae-4de7-88e9-1914635c8d11
ms.openlocfilehash: 11ba9bf04f826b0d7465a9a81a36c327e79f4d13
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40049567"
---
# <a name="unable-to-add-2010-approval-workflow"></a><span data-ttu-id="60efa-102">Nije moguće dodati 2010 tok posla za odobravanje</span><span class="sxs-lookup"><span data-stu-id="60efa-102">Unable to add 2010 Approval Workflow</span></span>

<span data-ttu-id="60efa-103">U Microsoft SharePoint kolekciji lokacija ne možete dodati globalno tok posla koji je moguće ponovo koristiti (kao što je "odobrenje-SharePoint 2010") u listu ili biblioteku.</span><span class="sxs-lookup"><span data-stu-id="60efa-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="60efa-104">Da biste riješili taj problem, slijedite ove korake:</span><span class="sxs-lookup"><span data-stu-id="60efa-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="60efa-105">Otvorite osnovnu Web lokaciju kolekcije lokacija u programu SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="60efa-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="60efa-106">U okviru **objekti lokacije**izaberite stavku **Tokovi posla**.</span><span class="sxs-lookup"><span data-stu-id="60efa-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="60efa-107">U **novom** odeljku trake **tokova posla** izaberite opciju **tok posla**koji je moguće ponovo koristiti.</span><span class="sxs-lookup"><span data-stu-id="60efa-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="60efa-108">U obrascu **Kreiranje toka posla** koji je moguće ponovo koristiti unesite ime \* \* *Repair2010* \* \*.</span><span class="sxs-lookup"><span data-stu-id="60efa-108">On the **Create Reusable Workflow** form, enter the name \*\* *Repair2010* \*\*.</span></span> <span data-ttu-id="60efa-109">Za **tip platforme**izaberite stavku **SharePoint 2010 tok posla**, a zatim kliknite na dugme **u redu**.</span><span class="sxs-lookup"><span data-stu-id="60efa-109">For **Platform Type**, click **SharePoint 2010 Workflow**, and then click **OK**.</span></span> 
  
1. <span data-ttu-id="60efa-110">U odeljku **Sačuvaj** na traci **toka posla** izaberite stavku **Objavi**.</span><span class="sxs-lookup"><span data-stu-id="60efa-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
2. <span data-ttu-id="60efa-111">U odeljku " **Upravljanje** " na traci **toka posla** izaberite opciju " **Objavi globalno**".</span><span class="sxs-lookup"><span data-stu-id="60efa-111">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**.</span></span> <span data-ttu-id="60efa-112">U dijalogu za potvrđivanje koji se pojavljuje izaberite **"u redu"**.</span><span class="sxs-lookup"><span data-stu-id="60efa-112">In the confirmation dialog box that appears, select **OK**.</span></span> 
  
3. <span data-ttu-id="60efa-113">U Web pregledaču pronađite osnovnu Veb lokaciju kolekcije lokacija, a zatim pristupite **postavkama** \> **kolekcije**lokacija.</span><span class="sxs-lookup"><span data-stu-id="60efa-113">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**.</span></span> <span data-ttu-id="60efa-114">Uključi/isključi funkciju **tokova posla** :</span><span class="sxs-lookup"><span data-stu-id="60efa-114">Toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="60efa-115">· Ako je funkcija *aktivirana* , kliknite na dugme **"Deaktiviraj",** a zatim kliknite na dugme " **Aktiviraj**".</span><span class="sxs-lookup"><span data-stu-id="60efa-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="60efa-116">· Ako je funkcija *deaktivirana* , kliknite na dugme " **Aktiviraj**".</span><span class="sxs-lookup"><span data-stu-id="60efa-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="60efa-117">Za više informacija pogledajte sledeći [članak](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="60efa-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  

