---
title: Uslovni pristup sa Intune
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: e147e7460ee6a786e577a43c0b8355fc27ee367b
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/18/2019
ms.locfileid: "36505008"
---
# <a name="conditional-access-with-intune"></a><span data-ttu-id="bc8a5-102">Uslovni pristup sa Intune</span><span class="sxs-lookup"><span data-stu-id="bc8a5-102">Conditional Access with Intune</span></span>

<span data-ttu-id="bc8a5-103">Korišćenje **uslovnog pristupa** sa Intune zahteva 3 koraka:</span><span class="sxs-lookup"><span data-stu-id="bc8a5-103">Using **Conditional Access** with Intune requires 3 steps:</span></span> 
  
- <span data-ttu-id="bc8a5-104">Kreirajte **smernice za uslovno pristup** koje određuju koji resursi se štite i koji uslovi treba da budu ispunjeni da bi pristupili tim resursima.</span><span class="sxs-lookup"><span data-stu-id="bc8a5-104">Create a **Conditional Access Policy** that defines what resources are being protected, and what conditions need to be met to access those resources.</span></span> <span data-ttu-id="bc8a5-105">Na primer, uređaj mora biti usaglašen sa pristupom korporativnoj e-pošti.</span><span class="sxs-lookup"><span data-stu-id="bc8a5-105">For example, a device must be compliant before accessing corporate email.</span></span> 
    
- <span data-ttu-id="bc8a5-106">Kreirajte **smernice usaglašenosti** da biste definisali postavke koje moraju da se ispune pre nego što se taj uređaj smatra usaglašen.</span><span class="sxs-lookup"><span data-stu-id="bc8a5-106">Create a **Compliance Policy** to define settings that must be met before the device is considered compliant.</span></span> <span data-ttu-id="bc8a5-107">Na primer, uređaj mora da ima PIN kôd od najmanje 6 cifara pre nego što se smatra usaglašen.</span><span class="sxs-lookup"><span data-stu-id="bc8a5-107">For example, a device must have a pin of at least 6 digits before it is considered compliant.</span></span> 
    
- <span data-ttu-id="bc8a5-108">Obezbeđivanje **smernica usaglašenosti** i **smernica uslovnog pristupa** usmerena su na željene grupe korisnika.</span><span class="sxs-lookup"><span data-stu-id="bc8a5-108">Ensuring both **Compliance Policies** and **Conditional Access Policies** are targeted to the desired groups of users.</span></span> <span data-ttu-id="bc8a5-109">Ovo može zahtevati Kreiranje određenih grupa korisnika u Azure aktivnom direktorijumu.</span><span class="sxs-lookup"><span data-stu-id="bc8a5-109">This may require creating specific groups of users in Azure Active Directory.</span></span> 
    
<span data-ttu-id="bc8a5-110">Opširnije:</span><span class="sxs-lookup"><span data-stu-id="bc8a5-110">Read more:</span></span>
  
- [<span data-ttu-id="bc8a5-111">Najbolje prakse uslovnog pristupa</span><span class="sxs-lookup"><span data-stu-id="bc8a5-111">Conditional Access best practices</span></span>](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [<span data-ttu-id="bc8a5-112">Prvi koraci sa uslovnim pristupom</span><span class="sxs-lookup"><span data-stu-id="bc8a5-112">Getting started with Conditional Access </span></span>](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

