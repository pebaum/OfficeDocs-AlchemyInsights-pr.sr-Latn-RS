---
title: Podešavanje DKIM u sistemu Office 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1388
ms.assetid: ''
ms.openlocfilehash: 0f81fe02135f3d0901ffe5a26d7aa3dad70c3770
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34765385"
---
# <a name="setup-dkim-in-office-365"></a><span data-ttu-id="23e9e-102">Podešavanje DKIM u sistemu Office 365</span><span class="sxs-lookup"><span data-stu-id="23e9e-102">Setup DKIM in Office 365</span></span>

<span data-ttu-id="23e9e-103">Kompletna uputstva za konfigurisanje DKIM za prilagođene domene u Office 365 su [ovde](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).</span><span class="sxs-lookup"><span data-stu-id="23e9e-103">The complete instructions for configuring DKIM for custom domains in Office 365 are [here](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).</span></span>

1. <span data-ttu-id="23e9e-104">Za **svaku** prilagođenu domenu, morate da kreirate **dve** DKIM CNAME zapise kod vašeg domena DNS hosting servisa (obično u domenu prijavnicu).</span><span class="sxs-lookup"><span data-stu-id="23e9e-104">For **each** custom domain, you need to create **two** DKIM CNAME records at your domain's DNS hosting service (typically, the domain registrar).</span></span> <span data-ttu-id="23e9e-105">Na primer, contoso.com i fourthcoffee.com zahteva četiri DKIM CNAME zapisa: dva za contoso.com i dva za fourthcoffee.com.</span><span class="sxs-lookup"><span data-stu-id="23e9e-105">For example, contoso.com and fourthcoffee.com require four DKIM CNAME records: two for contoso.com and two for fourthcoffee.com.</span></span>

   <span data-ttu-id="23e9e-106">DKIM CNAME zapise za **svaku** prilagođenih domena koristite sledeće formate:</span><span class="sxs-lookup"><span data-stu-id="23e9e-106">The DKIM CNAME records for **each** custom domain use the following formats:</span></span>

   - <span data-ttu-id="23e9e-107">**Ime domaćina**:`selector1._domainkey.<CustomDomain>`</span><span class="sxs-lookup"><span data-stu-id="23e9e-107">**Host name**: `selector1._domainkey.<CustomDomain>`</span></span>

     <span data-ttu-id="23e9e-108">**Tačke na adresu ili vrednost**:`selector1-<DomainGUID>._domainkey.<InitialDomain>`</span><span class="sxs-lookup"><span data-stu-id="23e9e-108">**Points to address or value**: `selector1-<DomainGUID>._domainkey.<InitialDomain>`</span></span>

     <span data-ttu-id="23e9e-109">**TTL**: 3600</span><span class="sxs-lookup"><span data-stu-id="23e9e-109">**TTL**: 3600</span></span>

   - <span data-ttu-id="23e9e-110">**Ime domaćina**:`selector2._domainkey.<CustomDomain>`</span><span class="sxs-lookup"><span data-stu-id="23e9e-110">**Host name**: `selector2._domainkey.<CustomDomain>`</span></span>

     <span data-ttu-id="23e9e-111">**Tačke na adresu ili vrednost**:`selector2-<DomainGUID>._domainkey.<InitialDomain>`</span><span class="sxs-lookup"><span data-stu-id="23e9e-111">**Points to address or value**: `selector2-<DomainGUID>._domainkey.<InitialDomain>`</span></span>

     <span data-ttu-id="23e9e-112">**TTL**: 3600</span><span class="sxs-lookup"><span data-stu-id="23e9e-112">**TTL**: 3600</span></span>

   <span data-ttu-id="23e9e-113">\<DomainGUID\> je tekst sa leve strane `.mail.protection.outlook.com` u prilagođeni MX zapis za prilagođenih domena (na primer, `contoso-com` za u domenu contoso.com).</span><span class="sxs-lookup"><span data-stu-id="23e9e-113">\<DomainGUID\> is the text to the left of `.mail.protection.outlook.com` in the customized MX record for the custom domain (for example, `contoso-com` for the domain contoso.com).</span></span> <span data-ttu-id="23e9e-114">\<InitialDomain\> je domen koji ste koristili kada ste se prijavili za Office 365 (na primer, contoso.onmicrosoft.com).</span><span class="sxs-lookup"><span data-stu-id="23e9e-114">\<InitialDomain\> is the domain you used when you signed up for Office 365 (for example, contoso.onmicrosoft.com).</span></span>

2. <span data-ttu-id="23e9e-115">Nakon što ste kreirali CNAME zapise za tvoj prilagođenih domena, dovršite sledeće instrukcije:</span><span class="sxs-lookup"><span data-stu-id="23e9e-115">After you've created the CNAME records for your custom domains, complete the following instructions:</span></span>

   <span data-ttu-id="23e9e-116">jedan.</span><span class="sxs-lookup"><span data-stu-id="23e9e-116">a.</span></span> <span data-ttu-id="23e9e-117">[Prijavite se na Office 365](https://support.office.microsoft.com/article/e9eb7d51-5430-4929-91ab-6157c5a050b4) uz svoj radni ili skola nalog.</span><span class="sxs-lookup"><span data-stu-id="23e9e-117">[Sign in to Office 365](https://support.office.microsoft.com/article/e9eb7d51-5430-4929-91ab-6157c5a050b4) with your work or school account.</span></span>

   <span data-ttu-id="23e9e-118">b.</span><span class="sxs-lookup"><span data-stu-id="23e9e-118">b.</span></span> <span data-ttu-id="23e9e-119">Izaberite aplikaciju pokretač ikonu u gornjem levom i odaberite **Admin**.</span><span class="sxs-lookup"><span data-stu-id="23e9e-119">Select the app launcher icon in the upper-left and choose **Admin**.</span></span>

   <span data-ttu-id="23e9e-120">c.</span><span class="sxs-lookup"><span data-stu-id="23e9e-120">c.</span></span> <span data-ttu-id="23e9e-121">U donjem levom navigaciji, proširite **Admin** i odaberite **Exchange**.</span><span class="sxs-lookup"><span data-stu-id="23e9e-121">In the lower-left navigation, expand **Admin** and choose **Exchange**.</span></span>

   <span data-ttu-id="23e9e-122">d.</span><span class="sxs-lookup"><span data-stu-id="23e9e-122">d.</span></span> <span data-ttu-id="23e9e-123">Idite na **zaštitu** > **DKIM**.</span><span class="sxs-lookup"><span data-stu-id="23e9e-123">Go to **Protection** > **DKIM**.</span></span>

   <span data-ttu-id="23e9e-124">e.</span><span class="sxs-lookup"><span data-stu-id="23e9e-124">e.</span></span> <span data-ttu-id="23e9e-125">Izaberite domenu, a zatim odaberite **Omogući** za **znak poruke za ovaj domen sa DKIM potpisa**.</span><span class="sxs-lookup"><span data-stu-id="23e9e-125">Select the domain and then choose **Enable** for **Sign messages for this domain with DKIM signatures**.</span></span> <span data-ttu-id="23e9e-126">Ponovite ovaj korak za svaku prilagođenih domena.</span><span class="sxs-lookup"><span data-stu-id="23e9e-126">Repeat this step for each custom domain.</span></span>
