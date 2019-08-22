---
title: Kôd greške 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Ako dobijete grešku prilikom aktivacije Office 2013 na usluge udaljene radne površine (RDS) raspoređivanje, razmislite o omogućavanju ADAL uređivanjem registra.
ms.openlocfilehash: 4ef2943e5a529368fa2c614e4431cf180924fbb8
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36527055"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a><span data-ttu-id="3f5f0-103">Greška prilikom aktiviranja Office 2013 na usluge udaljene radne površine</span><span class="sxs-lookup"><span data-stu-id="3f5f0-103">Error while activation Office 2013 on Remote Desktop Services</span></span>

<span data-ttu-id="3f5f0-104">Ako dobijete grešku prilikom aktivacije Office 2013 na usluge udaljene radne površine (RDS) raspoređivanje, razmislite o omogućavanju ADAL uređivanjem registra.</span><span class="sxs-lookup"><span data-stu-id="3f5f0-104">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span>
  
|<span data-ttu-id="3f5f0-105">**Ključ registratora**</span><span class="sxs-lookup"><span data-stu-id="3f5f0-105">**Registry key**</span></span>|<span data-ttu-id="3f5f0-106">**Tip**</span><span class="sxs-lookup"><span data-stu-id="3f5f0-106">**Type**</span></span>|<span data-ttu-id="3f5f0-107">**Vrednost**</span><span class="sxs-lookup"><span data-stu-id="3f5f0-107">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="3f5f0-108">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="3f5f0-108">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="3f5f0-109">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="3f5f0-109">REG_DWORD</span></span>  <br/> |<span data-ttu-id="3f5f0-110">1</span><span class="sxs-lookup"><span data-stu-id="3f5f0-110">1</span></span>  <br/> |

<span data-ttu-id="3f5f0-111">Za više informacija, pogledajte [Omogući moderne potvrda identiteta za Office 2013 na uređajima Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="3f5f0-111">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="3f5f0-112">ADAL je podrazumevano omogućena u Office 365 ProPlus i Office 2016.</span><span class="sxs-lookup"><span data-stu-id="3f5f0-112">ADAL is enabled by default in Office 365 ProPlus and Office 2016.</span></span> <span data-ttu-id="3f5f0-113">Usluge udaljene radne površine (RDS) prethodno proglašena je usluga terminala.</span><span class="sxs-lookup"><span data-stu-id="3f5f0-113">Remote Desktop Services (RDS) was previously named Terminal Services.</span></span>
  