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
ms.openlocfilehash: e147e7460ee6a786e577a43c0b8355fc27ee367b
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36505008"
---
# <a name="conditional-access-with-intune"></a><span data-ttu-id="65eb5-102">Conditional Access sa Intune</span><span class="sxs-lookup"><span data-stu-id="65eb5-102">Conditional Access with Intune</span></span>

<span data-ttu-id="65eb5-103">Koristeći **Conditional Access** sa Intune zahteva 3 koraka:</span><span class="sxs-lookup"><span data-stu-id="65eb5-103">Using **Conditional Access** with Intune requires 3 steps:</span></span> 
  
- <span data-ttu-id="65eb5-104">Kreiranje **Smernica za uslovno pristup** koji definiše koji resursi su zaštićena, a koji uslovi treba da se ispune da pristupite tih resursa.</span><span class="sxs-lookup"><span data-stu-id="65eb5-104">Create a **Conditional Access Policy** that defines what resources are being protected, and what conditions need to be met to access those resources.</span></span> <span data-ttu-id="65eb5-105">Na primer, uređaj mora biti usaglašen pre pristupanja korporativni email.</span><span class="sxs-lookup"><span data-stu-id="65eb5-105">For example, a device must be compliant before accessing corporate email.</span></span> 
    
- <span data-ttu-id="65eb5-106">Kreiranje **Politika usklađenosti** da definišete postavke koje moraju da se ispune da bi uređaj se smatra usaglašeni.</span><span class="sxs-lookup"><span data-stu-id="65eb5-106">Create a **Compliance Policy** to define settings that must be met before the device is considered compliant.</span></span> <span data-ttu-id="65eb5-107">Na primer, uređaj mora da ima pin najmanje 6 cifara smatra se usaglašen.</span><span class="sxs-lookup"><span data-stu-id="65eb5-107">For example, a device must have a pin of at least 6 digits before it is considered compliant.</span></span> 
    
- <span data-ttu-id="65eb5-108">Osiguravanje **Usklađenosti politike** i **Uslovnog pristupa politike** su namenjene željene grupe korisnika.</span><span class="sxs-lookup"><span data-stu-id="65eb5-108">Ensuring both **Compliance Policies** and **Conditional Access Policies** are targeted to the desired groups of users.</span></span> <span data-ttu-id="65eb5-109">Ovo može da zahteva kreiranje određene grupe korisnika u sistemu Active Directory Azure.</span><span class="sxs-lookup"><span data-stu-id="65eb5-109">This may require creating specific groups of users in Azure Active Directory.</span></span> 
    
<span data-ttu-id="65eb5-110">Opširnije:</span><span class="sxs-lookup"><span data-stu-id="65eb5-110">Read more:</span></span>
  
- [<span data-ttu-id="65eb5-111">Uslovnog pristupa najbolje prakse</span><span class="sxs-lookup"><span data-stu-id="65eb5-111">Conditional Access best practices</span></span>](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [<span data-ttu-id="65eb5-112">Prvi koraci sa Conditional Access</span><span class="sxs-lookup"><span data-stu-id="65eb5-112">Getting started with Conditional Access </span></span>](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

