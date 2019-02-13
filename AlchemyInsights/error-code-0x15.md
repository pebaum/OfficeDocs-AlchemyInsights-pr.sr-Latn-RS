---
title: Kôd greške 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Ako dobijete grešku prilikom aktivacije Office 2013 na usluge udaljene radne površine (RDS) raspoređivanje, razmislite o omogućavanju ADAL uređivanjem registra.
ms.openlocfilehash: 6d4076ecb5c6ee3c3cf4c4610ad4aa29ab477d8a
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29929103"
---
<span data-ttu-id="1fd32-103">Ako dobijete grešku prilikom aktivacije Office 2013 na usluge udaljene radne površine (RDS) raspoređivanje, razmislite o omogućavanju ADAL uređivanjem registra.</span><span class="sxs-lookup"><span data-stu-id="1fd32-103">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span> 
  
|<span data-ttu-id="1fd32-104">**Ključ registratora**</span><span class="sxs-lookup"><span data-stu-id="1fd32-104">**Registry key**</span></span>|<span data-ttu-id="1fd32-105">\*\*Ukucajte \*\*</span><span class="sxs-lookup"><span data-stu-id="1fd32-105">**Type**</span></span>|<span data-ttu-id="1fd32-106">**Vrednost**</span><span class="sxs-lookup"><span data-stu-id="1fd32-106">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="1fd32-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="1fd32-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="1fd32-108">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="1fd32-108">REG_DWORD</span></span>  <br/> |<span data-ttu-id="1fd32-109">1</span><span class="sxs-lookup"><span data-stu-id="1fd32-109">1</span></span>  <br/> |
   
<span data-ttu-id="1fd32-110">Za više informacija, pogledajte [Omogući moderne potvrda identiteta za Office 2013 na uređajima Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="1fd32-110">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="1fd32-p101">ADAL je podrazumevano omogućena u Office 365 ProPlus i Office 2016. > usluge udaljene radne površine (RDS) prethodno proglašena je usluga terminala.</span><span class="sxs-lookup"><span data-stu-id="1fd32-p101">ADAL is enabled by default in Office 365 ProPlus and Office 2016. >  Remote Desktop Services (RDS) was previously named Terminal Services.</span></span> 
  

