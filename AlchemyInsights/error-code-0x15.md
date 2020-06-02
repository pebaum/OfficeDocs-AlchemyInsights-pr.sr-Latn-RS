---
title: Kôd greške 0x15
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Ako dobijate grešku prilikom aktiviranja sistema Office 2013 u vezi sa raspoređivanje usluga udaljene radne površine (RDS), razmislite o omogućavanju ADAL uređivanjem registratora.
ms.openlocfilehash: 468d13e59602cf173ed2e17af44c66babfc28703
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506860"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a><span data-ttu-id="d3876-103">Greška tokom aktivacije sistema Office 2013 u uslugama udaljene radne površine</span><span class="sxs-lookup"><span data-stu-id="d3876-103">Error while activation Office 2013 on Remote Desktop Services</span></span>

<span data-ttu-id="d3876-104">Ako dobijate grešku prilikom aktiviranja sistema Office 2013 u vezi sa raspoređivanje usluga udaljene radne površine (RDS), razmislite o omogućavanju ADAL uređivanjem registratora.</span><span class="sxs-lookup"><span data-stu-id="d3876-104">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span>
  
|<span data-ttu-id="d3876-105">**Ključ registratora**</span><span class="sxs-lookup"><span data-stu-id="d3876-105">**Registry key**</span></span>|<span data-ttu-id="d3876-106">**Tip**</span><span class="sxs-lookup"><span data-stu-id="d3876-106">**Type**</span></span>|<span data-ttu-id="d3876-107">**Vrednost**</span><span class="sxs-lookup"><span data-stu-id="d3876-107">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="d3876-108">HKEY_CURRENT_USER \Software\microsoft\office\15.0\česta \Identity\enabpotencijalnog Al</span><span class="sxs-lookup"><span data-stu-id="d3876-108">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="d3876-109">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="d3876-109">REG_DWORD</span></span>  <br/> |<span data-ttu-id="d3876-110">1</span><span class="sxs-lookup"><span data-stu-id="d3876-110">1</span></span>  <br/> |

<span data-ttu-id="d3876-111">Više informacija potražite u članku [Omogućavanje moderne potvrde identiteta za Office 2013 na Windows uređajima](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="d3876-111">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="d3876-112">ADAL je po podrazumevanoj vrednosti omogućen u Microsoft 365 aplikacijama za Enterprise i Office 2016.</span><span class="sxs-lookup"><span data-stu-id="d3876-112">ADAL is enabled by default in Microsoft 365 Apps for enterprise and Office 2016.</span></span> <span data-ttu-id="d3876-113">Usluge udaljene radne površine (RDS) prethodno su imenovane usluge terminala.</span><span class="sxs-lookup"><span data-stu-id="d3876-113">Remote Desktop Services (RDS) was previously named Terminal Services.</span></span>
  