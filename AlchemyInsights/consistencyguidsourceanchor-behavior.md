---
title: ConsistencyGuid / sourceAnchor ponašanje
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: cb1b50792b07a1b3b69607bf2f6824141a15922f
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32408122"
---
# <a name="consistencyguid--sourceanchor-behavior"></a><span data-ttu-id="76108-102">ConsistencyGuid / sourceAnchor ponašanje</span><span class="sxs-lookup"><span data-stu-id="76108-102">ConsistencyGuid / sourceAnchor behavior</span></span>

<span data-ttu-id="76108-103">Azurno AD povezivanje (verzija 1.1.524.0 i posle) sada olakšava upotrebu msDS-ConsistencyGuid kao atribut sourceAnchor.</span><span class="sxs-lookup"><span data-stu-id="76108-103">Azure AD Connect (version 1.1.524.0 and after) now facilitates the use of msDS-ConsistencyGuid as sourceAnchor attribute.</span></span> <span data-ttu-id="76108-104">Kada koristite ovu funkciju, Azure AD Poveži se automatski podešava sinhronizaciju pravila da:</span><span class="sxs-lookup"><span data-stu-id="76108-104">When using this feature, Azure AD Connect automatically configures the synchronization rules to:</span></span>
  
- <span data-ttu-id="76108-105">Koristite msDS-ConsistencyGuid kao atribut sourceAnchor za objekte korisnika.</span><span class="sxs-lookup"><span data-stu-id="76108-105">Use msDS-ConsistencyGuid as the sourceAnchor attribute for User objects.</span></span> <span data-ttu-id="76108-106">ObjectGUID se koristi za druge tipove objekata.</span><span class="sxs-lookup"><span data-stu-id="76108-106">ObjectGUID is used for other object types.</span></span>
    
- <span data-ttu-id="76108-107">Za bilo koga s obzirom na lokalne AD korisnik objekat čija msDS-ConsistencyGuid atribut nije naseljena, Azure AD povezivanje upisuje njenu vrednost objectGUID nazad atribut msDS-ConsistencyGuid u Aktivnom direktoriju na više lokacija.</span><span class="sxs-lookup"><span data-stu-id="76108-107">For any given on-premises AD User object whose msDS-ConsistencyGuid attribute isn't populated, Azure AD Connect writes its objectGUID value back to the msDS-ConsistencyGuid attribute in on-premises Active Directory.</span></span> <span data-ttu-id="76108-108">Nakon što je atribut msDS-ConsistencyGuid je naseljena, Azure AD povezivanje onda izvozi objekat azurno AD.</span><span class="sxs-lookup"><span data-stu-id="76108-108">After the msDS-ConsistencyGuid attribute is populated, Azure AD Connect then exports the object to Azure AD.</span></span>
    
 <span data-ttu-id="76108-109">**Napomena:** Jednom je lokalne AD objekat uvezu u Azure AD povezivanje (to jest, uvesti u reklamni prostor spajanja i predviđena u u Metaverse), više ne možete promeniti njegovu sourceAnchor vrednost.</span><span class="sxs-lookup"><span data-stu-id="76108-109">**Note:** Once an on-premises AD object is imported into Azure AD Connect (that is, imported into the AD Connector Space and projected into the Metaverse), you cannot change its sourceAnchor value anymore.</span></span> <span data-ttu-id="76108-110">Da biste naveli vrijednost sourceAnchor za neki s obzirom na lokalne AD prigovor, podesite svoj atribut msDS-ConsistencyGuid pre nego što se ona uvozi u Azure AD povezivanje.</span><span class="sxs-lookup"><span data-stu-id="76108-110">To specify the sourceAnchor value for a given on-premises AD object, configure its msDS-ConsistencyGuid attribute before it is imported into Azure AD Connect.</span></span> 
  
<span data-ttu-id="76108-111">Za više informacija o SourceAnchor i ConsistencyGuid, obratite pažnju na sledeće: [Azure AD povezivanje: dizajn koncepte](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span><span class="sxs-lookup"><span data-stu-id="76108-111">For more information on SourceAnchor and ConsistencyGuid, refer to the following: [Azure AD Connect: Design concepts](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span></span>
  

