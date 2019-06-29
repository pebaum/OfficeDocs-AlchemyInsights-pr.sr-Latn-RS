---
title: Ažuriranje DNS zapisa da bi vaša Web lokacija sa svoje trenutne usluga hostinga
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
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
ms.openlocfilehash: 62f49038cf541c2185ed6a60c6cb58fe2889342d
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/28/2019
ms.locfileid: "35353191"
---
# <a name="update-dns-records-to-keep-your-website-with-your-current-hosting-provider"></a><span data-ttu-id="90ea1-102">Ažuriranje DNS zapisa da bi vaša Web lokacija sa svoje trenutne usluga hostinga</span><span class="sxs-lookup"><span data-stu-id="90ea1-102">Update DNS records to keep your website with your current hosting provider</span></span>

1. <span data-ttu-id="90ea1-103">Na stranici [domene](https://portal.office.com/adminportal/home#/Domains) , liste domena, izaberite domenu koristite za vašu Web lokaciju, a zatim izaberite **DNS postavke** u oknu za upravljanje.</span><span class="sxs-lookup"><span data-stu-id="90ea1-103">On the [Domains](https://portal.office.com/adminportal/home#/Domains) page, in the list of domains, select the domain you're using for your website, and then select **DNS settings** in the management pane.</span></span>

2. <span data-ttu-id="90ea1-104">Izaberite **+ novi prilagođeni zapis** i unesite sledeće:</span><span class="sxs-lookup"><span data-stu-id="90ea1-104">Select **+ New custom record** and enter the following:</span></span>

  - <span data-ttu-id="90ea1-105">Unesite za **DNS tip** : **(adresa)**</span><span class="sxs-lookup"><span data-stu-id="90ea1-105">For **DNS type** enter: **A (Address)**</span></span>

  - <span data-ttu-id="90ea1-106">U **ime domaćina ili pseudonim**, upišite sledeće:**@**</span><span class="sxs-lookup"><span data-stu-id="90ea1-106">For **Host name or Alias**, type the following: **@**</span></span>

  - <span data-ttu-id="90ea1-107">Za **IP adresu**, upišite statična IP adresa za vašu Web lokaciju gde se trenutno nalazi (na primer, 172.16.140.1).</span><span class="sxs-lookup"><span data-stu-id="90ea1-107">For **IP Address**, type the static IP address for your website where it's currently hosted (for example, 172.16.140.1).</span></span>

    <span data-ttu-id="90ea1-108">Ovo mora da je *statična* IP adresa za Web lokacije, ne *dinamičnu* IP adresu.</span><span class="sxs-lookup"><span data-stu-id="90ea1-108">This must be a  *static*  IP address for the website, not a  *dynamic*  IP address.</span></span> <span data-ttu-id="90ea1-109">Proverite sa lokacije gde vaša Web lokacija je bila je domaćin da proverite da li možete da dobijete statičnu IP adresu za vaše javne Web lokacije.</span><span class="sxs-lookup"><span data-stu-id="90ea1-109">Check with site where your website is hosted to make sure you can get a static IP address for your public website.</span></span>

3. <span data-ttu-id="90ea1-110">Izaberite **Sačuvaj**.</span><span class="sxs-lookup"><span data-stu-id="90ea1-110">Select **Save**.</span></span>

<span data-ttu-id="90ea1-111">Osim toga, možete da kreirate CNAME zapis da bi pomogao korisnicima pronaći vašu Web lokaciju.</span><span class="sxs-lookup"><span data-stu-id="90ea1-111">In addition, you can create a CNAME record to help customers find your website.</span></span>
  
1. <span data-ttu-id="90ea1-112">Izaberite **+ novi prilagođeni zapis** i unesite sledeće:</span><span class="sxs-lookup"><span data-stu-id="90ea1-112">Select **+ New custom record** and enter the following:</span></span>

  - <span data-ttu-id="90ea1-113">Unesite za **DNS tip** : **CNAME (Alias)**</span><span class="sxs-lookup"><span data-stu-id="90ea1-113">For **DNS type** enter: **CNAME (Alias)**</span></span>

  - <span data-ttu-id="90ea1-114">Za **ime domaćina ili pseudonim**, otkucajte sledeće: **www**</span><span class="sxs-lookup"><span data-stu-id="90ea1-114">For **Host name or Alias**, type the following: **www**</span></span>

  - <span data-ttu-id="90ea1-115">Za **tačke na adresu**, upišite je potpuno određeno ime domena (FQDN) na svojoj Web lokaciji (na primer, contoso.com).</span><span class="sxs-lookup"><span data-stu-id="90ea1-115">For **Points to address**, type the fully qualified domain name (FQDN) for your website (for example, contoso.com).</span></span>

2. <span data-ttu-id="90ea1-116">Izaberite **Sačuvaj**.</span><span class="sxs-lookup"><span data-stu-id="90ea1-116">Select **Save**.</span></span>
