---
title: Popravi DKIM instaliranja sustava
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1389
ms.assetid: ''
ms.openlocfilehash: 4d6dadbcbf71fe6e9ea56d6a82a7d8ababdd38ef
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34765373"
---
# <a name="fix-dkim-setup-issues"></a><span data-ttu-id="6a2ed-102">Popravi DKIM instaliranja sustava</span><span class="sxs-lookup"><span data-stu-id="6a2ed-102">Fix DKIM setup issues</span></span>

<span data-ttu-id="6a2ed-103">Ako dođe do problema, što će omogućiti DKIM vašeg prilagođenih domena, slijedite ove korake:</span><span class="sxs-lookup"><span data-stu-id="6a2ed-103">If you experience issues enabling DKIM for your custom domain, use the following steps:</span></span>

- <span data-ttu-id="6a2ed-104">Većina DKIM instaliranja sustava se odnose na neispravan DNS zapisa.</span><span class="sxs-lookup"><span data-stu-id="6a2ed-104">Most DKIM setup issues are related to incorrect DNS records.</span></span> <span data-ttu-id="6a2ed-105">Proverite DKIM CNAME zapis (**ne** TXT zapis) ispravno formatiran.</span><span class="sxs-lookup"><span data-stu-id="6a2ed-105">Verify the DKIM CNAME record (**not** a TXT record) is formatted correctly.</span></span> <span data-ttu-id="6a2ed-106">Za više informacija, pročitajte ovu [temu](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).</span><span class="sxs-lookup"><span data-stu-id="6a2ed-106">For more information, see this [topic](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).</span></span>

- <span data-ttu-id="6a2ed-107">Nakon te kreirate ili ažurirate DKIM DNS zapise u na DNS hosting servis vašeg domena (obično tvoj domena specijalista), stani za DNS zapise da propagira.</span><span class="sxs-lookup"><span data-stu-id="6a2ed-107">After you create or update your DKIM DNS records at the DNS hosting service for your domain (typically, your domain registrar), wait for the DNS records to propagate.</span></span>

- <span data-ttu-id="6a2ed-108">Ako ne možete da kreirate na DKIM DNS zapise u admin centru, možete zameniti \<CustomDomain\> sa vašeg prilagođenih domena (na primer, contoso.com) i pokrenete ovu komandu u [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.</span><span class="sxs-lookup"><span data-stu-id="6a2ed-108">If you can't create the DKIM DNS records in the admin center, you can replace \<CustomDomain\> with your custom domain (for example, contoso.com) and run this command in [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.</span></span>
