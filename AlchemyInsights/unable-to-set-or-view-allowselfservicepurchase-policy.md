---
title: Nije moguće podesiti ili prikazati smernicu Allowsebservicepurchase
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001212"
- "3526"
ms.openlocfilehash: 587a05cccbc71a970d4bd7723bff0df0c3b64ccc
ms.sourcegitcommit: 2a9d059262c07c33f9a740b3da4e6e3366b2f925
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/20/2020
ms.locfileid: "42158575"
---
# <a name="unable-to-set-or-view-the-allowselfservicepurchase-policy"></a><span data-ttu-id="82b1d-102">Nije moguće podesiti ili prikazati smernicu Allowsebservicepurchase</span><span class="sxs-lookup"><span data-stu-id="82b1d-102">Unable to set or view the AllowSelfServicePurchase policy</span></span>

<span data-ttu-id="82b1d-103">Kada pokušate da postavite ili prikažete smernicu Allowsebservicefurchase, dobićete sledeću poruku o grešci:</span><span class="sxs-lookup"><span data-stu-id="82b1d-103">When attempting to set or view the AllowSelfServicePurchase policy, you receive the following error message:</span></span>

<span data-ttu-id="82b1d-104">*Ručni greška: nije uspelo preuzimanje smernica proizvoda pomoću programa PolicyId ' Allowsamoservicepurchase ', greška-osnovna veza je zatvorena: došlo je do neočekivane greške prilikom slanja.*</span><span class="sxs-lookup"><span data-stu-id="82b1d-104">*HandleError : Failed to retrieve product policy with PolicyId 'AllowSelfServicePurchase', ErrorMessage - The underlying connection was closed: An unexpected error occurred on a send.*</span></span>

<span data-ttu-id="82b1d-105">Do ovoga je možda došlo zbog starije verzije bezbednosti sloja transporta (TLS).</span><span class="sxs-lookup"><span data-stu-id="82b1d-105">This may be due to an older version of Transport Layer Security (TLS).</span></span> <span data-ttu-id="82b1d-106">Da biste povezali MSCommerce uslugu, potrebno je da koristite TLS 1,2 ili noviji.</span><span class="sxs-lookup"><span data-stu-id="82b1d-106">To connect the MSCommerce service, you need to use TLS 1.2 or greater.</span></span>  

<span data-ttu-id="82b1d-107">Pokušajte sledeće korake da biste omogućili/podesili TLS protokol na 1,2, proverite i pokušajte ponovo.</span><span class="sxs-lookup"><span data-stu-id="82b1d-107">Try the following steps to enable/set the TLS protocol to 1.2, verify, and retry.</span></span>
 1. <span data-ttu-id="82b1d-108">Na komandnoj liniji PowerShell (PS C:\) unesite sledeću komandu da biste podesili TLS protokol na verziju 1,2:</span><span class="sxs-lookup"><span data-stu-id="82b1d-108">At the PowerShell command prompt (PS C:\) enter the following command to set the TLS protocol to version 1.2:</span></span>

    `[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12`

2. <span data-ttu-id="82b1d-109">Provjerite TLS Protocol (e) u upotrebi, sa sledećom komandom:</span><span class="sxs-lookup"><span data-stu-id="82b1d-109">Verify the TLS protocol(s) in use, with the following command:</span></span>

    `[Net.ServicePointManager]::SecurityProtocol` 

3. <span data-ttu-id="82b1d-110">Ponovo pokušajte da dobijete ili ažurirate komande po potrebi.</span><span class="sxs-lookup"><span data-stu-id="82b1d-110">Retry the Get or Update commands as needed.</span></span>

