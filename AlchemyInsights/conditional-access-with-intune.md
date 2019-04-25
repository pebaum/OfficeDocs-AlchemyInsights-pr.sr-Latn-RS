---
title: Conditional Access sa Intune
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: 2e778bf4fbdb766700fb24b3405b4ddce89253f7
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32393555"
---
# <a name="conditional-access-with-intune"></a><span data-ttu-id="391d2-102">Conditional Access sa Intune</span><span class="sxs-lookup"><span data-stu-id="391d2-102">Conditional Access with Intune</span></span>

<span data-ttu-id="391d2-103">Koristeći **Conditional Access** sa Intune zahteva 3 koraka:</span><span class="sxs-lookup"><span data-stu-id="391d2-103">Using **Conditional Access** with Intune requires 3 steps:</span></span> 
  
- <span data-ttu-id="391d2-104">Kreiranje **Smernica za uslovno pristup** koji definiše koji resursi su zaštićena, a koji uslovi treba da se ispune da pristupite tih resursa.</span><span class="sxs-lookup"><span data-stu-id="391d2-104">Create a **Conditional Access Policy** that defines what resources are being protected, and what conditions need to be met to access those resources.</span></span> <span data-ttu-id="391d2-105">Na primer, uređaj mora biti usaglašen pre pristupanja korporativni email.</span><span class="sxs-lookup"><span data-stu-id="391d2-105">For example, a device must be compliant before accessing corporate email.</span></span> 
    
- <span data-ttu-id="391d2-106">Kreiranje **Politika usklađenosti** da definišete postavke koje moraju da se ispune da bi uređaj se smatra usaglašeni.</span><span class="sxs-lookup"><span data-stu-id="391d2-106">Create a **Compliance Policy** to define settings that must be met before the device is considered compliant.</span></span> <span data-ttu-id="391d2-107">Na primer, uređaj mora da ima pin najmanje 6 cifara smatra se usaglašen.</span><span class="sxs-lookup"><span data-stu-id="391d2-107">For example, a device must have a pin of at least 6 digits before it is considered compliant.</span></span> 
    
- <span data-ttu-id="391d2-108">Osiguravanje **Usklađenosti politike** i **Uslovnog pristupa politike** su namenjene željene grupe korisnika.</span><span class="sxs-lookup"><span data-stu-id="391d2-108">Ensuring both **Compliance Policies** and **Conditional Access Policies** are targeted to the desired groups of users.</span></span> <span data-ttu-id="391d2-109">Ovo može da zahteva kreiranje određene grupe korisnika u sistemu Active Directory Azure.</span><span class="sxs-lookup"><span data-stu-id="391d2-109">This may require creating specific groups of users in Azure Active Directory.</span></span> 
    
<span data-ttu-id="391d2-110">Opširnije:</span><span class="sxs-lookup"><span data-stu-id="391d2-110">Read more:</span></span>
  
- [<span data-ttu-id="391d2-111">Uslovnog pristupa najbolje prakse</span><span class="sxs-lookup"><span data-stu-id="391d2-111">Conditional Access best practices</span></span>](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [<span data-ttu-id="391d2-112">Prvi koraci sa Conditional Access</span><span class="sxs-lookup"><span data-stu-id="391d2-112">Getting started with Conditional Access </span></span>](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

