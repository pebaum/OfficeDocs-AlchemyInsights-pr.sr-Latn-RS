---
title: Kôd greške 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Ako dobijete grešku prilikom aktivacije Office 2013 na usluge udaljene radne površine (RDS) raspoređivanje, razmislite o omogućavanju ADAL uređivanjem registra.
ms.openlocfilehash: 89f9270169e13fd7706f7826c624ef8ae4d47b3f
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/24/2019
ms.locfileid: "29499396"
---
<span data-ttu-id="85b53-103">Ako dobijete grešku prilikom aktivacije Office 2013 na usluge udaljene radne površine (RDS) raspoređivanje, razmislite o omogućavanju ADAL uređivanjem registra.</span><span class="sxs-lookup"><span data-stu-id="85b53-103">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span> 
  
|<span data-ttu-id="85b53-104">**Ključ registratora**</span><span class="sxs-lookup"><span data-stu-id="85b53-104">**Registry key**</span></span>|<span data-ttu-id="85b53-105">Ukucajte </span><span class="sxs-lookup"><span data-stu-id="85b53-105">**Type**</span></span>|<span data-ttu-id="85b53-106">**Vrednost**</span><span class="sxs-lookup"><span data-stu-id="85b53-106">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="85b53-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="85b53-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="85b53-108">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="85b53-108">REG_DWORD</span></span>  <br/> |<span data-ttu-id="85b53-109">1</span><span class="sxs-lookup"><span data-stu-id="85b53-109">1</span></span>  <br/> |
   
<span data-ttu-id="85b53-110">Za više informacija, pogledajte [Omogući moderne potvrda identiteta za Office 2013 na uređajima Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="85b53-110">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="85b53-p101">ADAL je podrazumevano omogućena u Office 365 ProPlus i Office 2016. > usluge udaljene radne površine (RDS) prethodno proglašena je usluga terminala.</span><span class="sxs-lookup"><span data-stu-id="85b53-p101">ADAL is enabled by default in Office 365 ProPlus and Office 2016. >  Remote Desktop Services (RDS) was previously named Terminal Services.</span></span> 
  

