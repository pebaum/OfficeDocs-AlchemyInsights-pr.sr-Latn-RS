---
title: Postojenciguid/ponašanje u okviru izvora
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
ms.openlocfilehash: f0ff94a8e46f1fb4e0ac8653c51f8f651e29498b
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/25/2019
ms.locfileid: "36517008"
---
# <a name="consistencyguid--sourceanchor-behavior"></a><span data-ttu-id="719a2-102">Postojenciguid/ponašanje u okviru izvora</span><span class="sxs-lookup"><span data-stu-id="719a2-102">ConsistencyGuid / sourceAnchor behavior</span></span>

<span data-ttu-id="719a2-103">Azure reklama Connect (verzija 1.1.524.0 i nakon) sada olakšava korišćenje msDS-a-Postojenciguid-a kao atributa izvora.</span><span class="sxs-lookup"><span data-stu-id="719a2-103">Azure AD Connect (version 1.1.524.0 and after) now facilitates the use of msDS-ConsistencyGuid as sourceAnchor attribute.</span></span> <span data-ttu-id="719a2-104">Kada koristite ovu funkciju, Azure funkcija Connect automatski konfiguriše pravila sinhronizacije na:</span><span class="sxs-lookup"><span data-stu-id="719a2-104">When using this feature, Azure AD Connect automatically configures the synchronization rules to:</span></span>
  
- <span data-ttu-id="719a2-105">Za korisničke objekte koristite msDS-postojan Enciguid kao atribut Loncerenja.</span><span class="sxs-lookup"><span data-stu-id="719a2-105">Use msDS-ConsistencyGuid as the sourceAnchor attribute for User objects.</span></span> <span data-ttu-id="719a2-106">ObjectGUID se koristi za druge tipove objekata.</span><span class="sxs-lookup"><span data-stu-id="719a2-106">ObjectGUID is used for other object types.</span></span>
    
- <span data-ttu-id="719a2-107">Za sve date objekte za korisnike oglasa čiji msDS-postojani Encyguid atribut nije naseljen, Azure Connect za povezivanje upisuje svoju objectGUID vrednost nazad na msDS-Postojencyguid atribut u aktivnom direktorijumu na prostoru.</span><span class="sxs-lookup"><span data-stu-id="719a2-107">For any given on-premises AD User object whose msDS-ConsistencyGuid attribute isn't populated, Azure AD Connect writes its objectGUID value back to the msDS-ConsistencyGuid attribute in on-premises Active Directory.</span></span> <span data-ttu-id="719a2-108">Nakon što datoteka msDS-a ima Encyguid atribut bude popunjena, Azure oglas Connect zatim izvozi objekat u Azure oglas.</span><span class="sxs-lookup"><span data-stu-id="719a2-108">After the msDS-ConsistencyGuid attribute is populated, Azure AD Connect then exports the object to Azure AD.</span></span>
    
 <span data-ttu-id="719a2-109">**Napomena:** Kada se objekat na objektu u programu "Uvoz" bude uvezen u "Azure" Connect (odnosno uvezen u prostor za konektore), ne možete više da promenite njegovu vrednost.</span><span class="sxs-lookup"><span data-stu-id="719a2-109">**Note:** Once an on-premises AD object is imported into Azure AD Connect (that is, imported into the AD Connector Space and projected into the Metaverse), you cannot change its sourceAnchor value anymore.</span></span> <span data-ttu-id="719a2-110">Da biste naveli vrednost polja izvora na osnovu datog objekta na objektu, konfigurišite njen msDS-Postojenciguid atribut pre nego što se uveze u "Azure" povezivanje sa više lokacija.</span><span class="sxs-lookup"><span data-stu-id="719a2-110">To specify the sourceAnchor value for a given on-premises AD object, configure its msDS-ConsistencyGuid attribute before it is imported into Azure AD Connect.</span></span> 
  
<span data-ttu-id="719a2-111">Za više informacija o polju "isusidriti" i "Postojenciguid" Pogledajte sledeće: [AZURE oglas Connect: koncepti dizajna](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span><span class="sxs-lookup"><span data-stu-id="719a2-111">For more information on SourceAnchor and ConsistencyGuid, refer to the following: [Azure AD Connect: Design concepts](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span></span>
  

