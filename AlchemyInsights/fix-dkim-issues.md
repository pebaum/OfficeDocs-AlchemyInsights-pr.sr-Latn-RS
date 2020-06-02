---
title: Rešavanje problema sa DKIM instalacijom
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1389
ms.assetid: ''
ms.openlocfilehash: 8195b0e3fada6da033b2d95b1fc6600e7fa3341e
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506788"
---
# <a name="fix-dkim-setup-issues"></a><span data-ttu-id="5c767-102">Rešavanje problema sa DKIM instalacijom</span><span class="sxs-lookup"><span data-stu-id="5c767-102">Fix DKIM setup issues</span></span>

<span data-ttu-id="5c767-103">Ako imate problema sa omogućavanjem DKIM za prilagođeni domen, koristite sledeće korake:</span><span class="sxs-lookup"><span data-stu-id="5c767-103">If you experience issues enabling DKIM for your custom domain, use the following steps:</span></span>

- <span data-ttu-id="5c767-104">Većina problema sa instalacijom je povezana sa netačnim DNS zapisima.</span><span class="sxs-lookup"><span data-stu-id="5c767-104">Most DKIM setup issues are related to incorrect DNS records.</span></span> <span data-ttu-id="5c767-105">Proverite da li je zapis DKIM CNAME (**nije** zapis txt) ispravno formatiran.</span><span class="sxs-lookup"><span data-stu-id="5c767-105">Verify the DKIM CNAME record (**not** a TXT record) is formatted correctly.</span></span> <span data-ttu-id="5c767-106">Za više informacija pogledajte ovu [temu](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email#steps-you-need-to-do-to-manually-set-up-dkim).</span><span class="sxs-lookup"><span data-stu-id="5c767-106">For more information, see this [topic](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email#steps-you-need-to-do-to-manually-set-up-dkim).</span></span>

- <span data-ttu-id="5c767-107">Kada kreirate ili ažurirate svoje DKIM DNS zapise u usluzi DNS hosting za vaš domen (obično, registrator domena), sačekajte da se DNS zapisi prenose.</span><span class="sxs-lookup"><span data-stu-id="5c767-107">After you create or update your DKIM DNS records at the DNS hosting service for your domain (typically, your domain registrar), wait for the DNS records to propagate.</span></span>

- <span data-ttu-id="5c767-108">Ako ne možete da kreirate DKIM DNS zapise u okviru administratorskog centra, možete da ga zamenite \<CustomDomain\> prilagođenim domenom (na primer, contoso.com) i pokrenete ovu komandu u [Exchange online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true` .</span><span class="sxs-lookup"><span data-stu-id="5c767-108">If you can't create the DKIM DNS records in the admin center, you can replace \<CustomDomain\> with your custom domain (for example, contoso.com) and run this command in [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.</span></span>
