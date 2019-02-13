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
ms.custom: Adm_O365
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: e1ffa9cf2b59570cb6ea3517efad7a55fd9489a8
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29927688"
---
# <a name="consistencyguid--sourceanchor-behavior"></a><span data-ttu-id="5e8dd-102">ConsistencyGuid / sourceAnchor ponašanje</span><span class="sxs-lookup"><span data-stu-id="5e8dd-102">ConsistencyGuid / sourceAnchor behavior</span></span>

<span data-ttu-id="5e8dd-p101">Azurno AD povezivanje (verzija 1.1.524.0 i posle) sada olakšava upotrebu msDS-ConsistencyGuid kao atribut sourceAnchor. Kada koristite ovu funkciju, Azure AD Poveži se automatski podešava sinhronizaciju pravila da:</span><span class="sxs-lookup"><span data-stu-id="5e8dd-p101">Azure AD Connect (version 1.1.524.0 and after) now facilitates the use of msDS-ConsistencyGuid as sourceAnchor attribute. When using this feature, Azure AD Connect automatically configures the synchronization rules to:</span></span>
  
- <span data-ttu-id="5e8dd-p102">Koristite msDS-ConsistencyGuid kao atribut sourceAnchor za objekte korisnika. ObjectGUID se koristi za druge tipove objekata.</span><span class="sxs-lookup"><span data-stu-id="5e8dd-p102">Use msDS-ConsistencyGuid as the sourceAnchor attribute for User objects. ObjectGUID is used for other object types.</span></span>
    
- <span data-ttu-id="5e8dd-p103">Za bilo koga s obzirom na lokalne AD korisnik objekat čija msDS-ConsistencyGuid atribut nije naseljena, Azure AD povezivanje upisuje njenu vrednost objectGUID nazad atribut msDS-ConsistencyGuid u Aktivnom direktoriju na više lokacija. Nakon što je atribut msDS-ConsistencyGuid je naseljena, Azure AD povezivanje onda izvozi objekat azurno AD.</span><span class="sxs-lookup"><span data-stu-id="5e8dd-p103">For any given on-premises AD User object whose msDS-ConsistencyGuid attribute isn't populated, Azure AD Connect writes its objectGUID value back to the msDS-ConsistencyGuid attribute in on-premises Active Directory. After the msDS-ConsistencyGuid attribute is populated, Azure AD Connect then exports the object to Azure AD.</span></span>
    
 <span data-ttu-id="5e8dd-p104">**Napomena:** Jednom je lokalne AD objekat uvezu u Azure AD povezivanje (to jest, uvesti u reklamni prostor spajanja i predviđena u u Metaverse), više ne možete promeniti njegovu sourceAnchor vrednost. Da biste naveli vrijednost sourceAnchor za neki s obzirom na lokalne AD prigovor, podesite svoj atribut msDS-ConsistencyGuid pre nego što se ona uvozi u Azure AD povezivanje.</span><span class="sxs-lookup"><span data-stu-id="5e8dd-p104">**Note:** Once an on-premises AD object is imported into Azure AD Connect (that is, imported into the AD Connector Space and projected into the Metaverse), you cannot change its sourceAnchor value anymore. To specify the sourceAnchor value for a given on-premises AD object, configure its msDS-ConsistencyGuid attribute before it is imported into Azure AD Connect.</span></span> 
  
<span data-ttu-id="5e8dd-111">Za više informacija o SourceAnchor i ConsistencyGuid, obratite pažnju na sledeće: [Azure AD povezivanje: dizajn koncepte](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span><span class="sxs-lookup"><span data-stu-id="5e8dd-111">For more information on SourceAnchor and ConsistencyGuid, refer to the following: [Azure AD Connect: Design concepts](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span></span>
  

