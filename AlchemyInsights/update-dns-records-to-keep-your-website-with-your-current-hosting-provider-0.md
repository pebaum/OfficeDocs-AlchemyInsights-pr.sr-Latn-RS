---
title: Ažuriranje DNS zapisa da bi vaša Web lokacija sa svoje trenutne usluga hostinga
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "42"
- "43"
- "100002"
ms.assetid: 48251355-7383-4fdc-a1e1-9dc2c85a8d29
ms.openlocfilehash: 7bd36c3954d12d3ee4ac624a2f827d8e5cd88082
ms.sourcegitcommit: b3e55405af384e868fcd32ea794eb15d1356c3fc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/29/2019
ms.locfileid: "36665774"
---
# <a name="update-dns-records-to-keep-your-website-with-your-current-hosting-provider"></a><span data-ttu-id="aeecf-102">Ažuriranje DNS zapisa da bi vaša Web lokacija sa svoje trenutne usluga hostinga</span><span class="sxs-lookup"><span data-stu-id="aeecf-102">Update DNS records to keep your website with your current hosting provider</span></span>

1. <span data-ttu-id="aeecf-103">U centru za admin Microsoft 365, idite na **Podešavanje** > [domeni](https://portal.office.com/adminportal/home#/Domains) stranica i domena, izaberite liste domena koji koristite za vašu Web lokaciju.</span><span class="sxs-lookup"><span data-stu-id="aeecf-103">In the Microsoft 365 admin center, go to the **Setup** > [Domains](https://portal.office.com/adminportal/home#/Domains) page, and in the list of domains, select the domain you're using for your website.</span></span>

2. <span data-ttu-id="aeecf-104">Izaberite **+ novi prilagođeni zapis** i unesite sledeće:</span><span class="sxs-lookup"><span data-stu-id="aeecf-104">Select **+ New custom record** and enter the following:</span></span>

  - <span data-ttu-id="aeecf-105">Unesite za **DNS tip** : **(adresa)**</span><span class="sxs-lookup"><span data-stu-id="aeecf-105">For **DNS type** enter: **A (Address)**</span></span>

  - <span data-ttu-id="aeecf-106">U **ime domaćina ili pseudonim**, upišite sledeće:**@**</span><span class="sxs-lookup"><span data-stu-id="aeecf-106">For **Host name or Alias**, type the following: **@**</span></span>

  - <span data-ttu-id="aeecf-107">Za **IP adresu**, upišite statična IP adresa za vašu Web lokaciju gde se trenutno nalazi (na primer, 172.16.140.1).</span><span class="sxs-lookup"><span data-stu-id="aeecf-107">For **IP Address**, type the static IP address for your website where it's currently hosted (for example, 172.16.140.1).</span></span>

    <span data-ttu-id="aeecf-108">Ovo mora da je *statična* IP adresa za Web lokacije, ne *dinamičnu* IP adresu.</span><span class="sxs-lookup"><span data-stu-id="aeecf-108">This must be a  *static*  IP address for the website, not a  *dynamic*  IP address.</span></span> <span data-ttu-id="aeecf-109">Proverite sa lokacije gde vaša Web lokacija je bila je domaćin da proverite da li možete da dobijete statičnu IP adresu za vaše javne Web lokacije.</span><span class="sxs-lookup"><span data-stu-id="aeecf-109">Check with site where your website is hosted to make sure you can get a static IP address for your public website.</span></span>

3. <span data-ttu-id="aeecf-110">Izaberite **Sačuvaj**.</span><span class="sxs-lookup"><span data-stu-id="aeecf-110">Select **Save**.</span></span>

<span data-ttu-id="aeecf-111">Osim toga, možete da kreirate CNAME zapis da bi pomogao korisnicima pronaći vašu Web lokaciju.</span><span class="sxs-lookup"><span data-stu-id="aeecf-111">In addition, you can create a CNAME record to help customers find your website.</span></span>
  
1. <span data-ttu-id="aeecf-112">Izaberite **+ novi prilagođeni zapis** i unesite sledeće:</span><span class="sxs-lookup"><span data-stu-id="aeecf-112">Select **+ New custom record** and enter the following:</span></span>

  - <span data-ttu-id="aeecf-113">Unesite za **DNS tip** : **CNAME (Alias)**</span><span class="sxs-lookup"><span data-stu-id="aeecf-113">For **DNS type** enter: **CNAME (Alias)**</span></span>

  - <span data-ttu-id="aeecf-114">Za **ime domaćina ili pseudonim**, otkucajte sledeće: **www**</span><span class="sxs-lookup"><span data-stu-id="aeecf-114">For **Host name or Alias**, type the following: **www**</span></span>

  - <span data-ttu-id="aeecf-115">Za **tačke na adresu**, upišite je potpuno određeno ime domena (FQDN) na svojoj Web lokaciji (na primer, contoso.com).</span><span class="sxs-lookup"><span data-stu-id="aeecf-115">For **Points to address**, type the fully qualified domain name (FQDN) for your website (for example, contoso.com).</span></span>

2. <span data-ttu-id="aeecf-116">Izaberite **Sačuvaj**.</span><span class="sxs-lookup"><span data-stu-id="aeecf-116">Select **Save**.</span></span>
