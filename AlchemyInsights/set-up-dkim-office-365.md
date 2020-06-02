---
title: Podešavanje DKIM
ms.author: chrisda
author: chrisda
manager: dansimp
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1388
ms.assetid: ''
ms.openlocfilehash: 0acaed476dbd06bc933bf466f9bf6116413a44bb
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44509398"
---
# <a name="setup-dkim"></a><span data-ttu-id="28422-102">Podešavanje DKIM</span><span class="sxs-lookup"><span data-stu-id="28422-102">Setup DKIM</span></span>

<span data-ttu-id="28422-103">Sva uputstva za konfigurisanje DKIM za prilagođene domene u sistemu Microsoft 365 su [ovde](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email#steps-you-need-to-do-to-manually-set-up-dkim).</span><span class="sxs-lookup"><span data-stu-id="28422-103">The complete instructions for configuring DKIM for custom domains in Microsoft 365 are [here](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email#steps-you-need-to-do-to-manually-set-up-dkim).</span></span>

1. <span data-ttu-id="28422-104">Za **svaki** prilagođeni domen potrebno je da kreirate **dva** zapisa DKIM CNAME na DNS hosting u vašem domenu (obično je to registrator domena).</span><span class="sxs-lookup"><span data-stu-id="28422-104">For **each** custom domain, you need to create **two** DKIM CNAME records at your domain's DNS hosting service (typically, the domain registrar).</span></span> <span data-ttu-id="28422-105">Na primer, contoso.com i fourthcoffee.com zahtevaju četiri DKIM CNAME zapisa: dva za contoso.com i dva za fourthcoffee.com.</span><span class="sxs-lookup"><span data-stu-id="28422-105">For example, contoso.com and fourthcoffee.com require four DKIM CNAME records: two for contoso.com and two for fourthcoffee.com.</span></span>

   <span data-ttu-id="28422-106">Zapisi DKIM CNAME za **svaki** prilagođeni domen koriste sledeće formate:</span><span class="sxs-lookup"><span data-stu-id="28422-106">The DKIM CNAME records for **each** custom domain use the following formats:</span></span>

   - <span data-ttu-id="28422-107">**Ime domaćina**:`selector1._domainkey.<CustomDomain>`</span><span class="sxs-lookup"><span data-stu-id="28422-107">**Host name**: `selector1._domainkey.<CustomDomain>`</span></span>

     <span data-ttu-id="28422-108">**Ukazuje na adresu ili vrednost**:`selector1-<DomainGUID>._domainkey.<InitialDomain>`</span><span class="sxs-lookup"><span data-stu-id="28422-108">**Points to address or value**: `selector1-<DomainGUID>._domainkey.<InitialDomain>`</span></span>

     <span data-ttu-id="28422-109">**TTL**: 3600</span><span class="sxs-lookup"><span data-stu-id="28422-109">**TTL**: 3600</span></span>

   - <span data-ttu-id="28422-110">**Ime domaćina**:`selector2._domainkey.<CustomDomain>`</span><span class="sxs-lookup"><span data-stu-id="28422-110">**Host name**: `selector2._domainkey.<CustomDomain>`</span></span>

     <span data-ttu-id="28422-111">**Ukazuje na adresu ili vrednost**:`selector2-<DomainGUID>._domainkey.<InitialDomain>`</span><span class="sxs-lookup"><span data-stu-id="28422-111">**Points to address or value**: `selector2-<DomainGUID>._domainkey.<InitialDomain>`</span></span>

     <span data-ttu-id="28422-112">**TTL**: 3600</span><span class="sxs-lookup"><span data-stu-id="28422-112">**TTL**: 3600</span></span>

   <span data-ttu-id="28422-113">\<DomainGUID\>predstavlja tekst levo od `.mail.protection.outlook.com` PRILAGOĐENOG MX zapisa za prilagođeni domen (na primer, `contoso-com` za domen contoso.com).</span><span class="sxs-lookup"><span data-stu-id="28422-113">\<DomainGUID\> is the text to the left of `.mail.protection.outlook.com` in the customized MX record for the custom domain (for example, `contoso-com` for the domain contoso.com).</span></span> <span data-ttu-id="28422-114">\<InitialDomain\>je domen koji ste koristili kada ste se prijavili za Microsoft 365 (na primer, contoso.onmicrosoft.com).</span><span class="sxs-lookup"><span data-stu-id="28422-114">\<InitialDomain\> is the domain you used when you signed up for Microsoft 365 (for example, contoso.onmicrosoft.com).</span></span>

2. <span data-ttu-id="28422-115">Nakon što ste kreirali zapise CNAME za svoje prilagođene domene, popunite sledeća uputstva:</span><span class="sxs-lookup"><span data-stu-id="28422-115">After you've created the CNAME records for your custom domains, complete the following instructions:</span></span>

   <span data-ttu-id="28422-116">A.</span><span class="sxs-lookup"><span data-stu-id="28422-116">a.</span></span> <span data-ttu-id="28422-117">[Prijavite se u Microsoft 365](https://support.office.microsoft.com/article/e9eb7d51-5430-4929-91ab-6157c5a050b4) pomoću poslovnog ili školskog naloga.</span><span class="sxs-lookup"><span data-stu-id="28422-117">[sign in to Microsoft 365](https://support.office.microsoft.com/article/e9eb7d51-5430-4929-91ab-6157c5a050b4) with your work or school account.</span></span>

   <span data-ttu-id="28422-118">B.</span><span class="sxs-lookup"><span data-stu-id="28422-118">b.</span></span> <span data-ttu-id="28422-119">Izaberite ikonu pokretanja aplikacije u gornjem levom uglu i odaberite stavku " **admin**".</span><span class="sxs-lookup"><span data-stu-id="28422-119">Select the app launcher icon in the upper-left and choose **Admin**.</span></span>

   <span data-ttu-id="28422-120">C.</span><span class="sxs-lookup"><span data-stu-id="28422-120">c.</span></span> <span data-ttu-id="28422-121">U donjem levom navigaciji, razvijte **admin** i odaberite stavku **Exchange**.</span><span class="sxs-lookup"><span data-stu-id="28422-121">In the lower-left navigation, expand **Admin** and choose **Exchange**.</span></span>

   <span data-ttu-id="28422-122">D.</span><span class="sxs-lookup"><span data-stu-id="28422-122">d.</span></span> <span data-ttu-id="28422-123">Idite na **zaštitu**  >  **dkim**.</span><span class="sxs-lookup"><span data-stu-id="28422-123">Go to **Protection** > **DKIM**.</span></span>

   <span data-ttu-id="28422-124">E.</span><span class="sxs-lookup"><span data-stu-id="28422-124">e.</span></span> <span data-ttu-id="28422-125">Izaberite domen, a zatim odaberite opciju **Omogući** za **potpisivanje poruka za ovaj domen sa dkim potpisima**.</span><span class="sxs-lookup"><span data-stu-id="28422-125">Select the domain and then choose **Enable** for **Sign messages for this domain with DKIM signatures**.</span></span> <span data-ttu-id="28422-126">Ponovite ovaj korak za svaki prilagođeni domen.</span><span class="sxs-lookup"><span data-stu-id="28422-126">Repeat this step for each custom domain.</span></span>
