---
title: Rešavanje problema sa upiљem Windows uređaja u Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 20e9bd42-2db0-4dd7-b480-966571494dd9
ms.custom:
- "784"
- "6200002"
ms.openlocfilehash: fa48b76fb49cdeef0734e77520c9bf95c150f317
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/28/2019
ms.locfileid: "35353551"
---
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a><span data-ttu-id="95960-102">Rešavanje problema sa upiљem Windows uređaja u Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="95960-102">Troubleshoot issues with enrolling Windows devices in Microsoft Intune</span></span>

<span data-ttu-id="95960-103">Pregledajte resurse dole navedene riješiti tvoj problem sada.</span><span class="sxs-lookup"><span data-stu-id="95960-103">Review the resources listed below to resolve your issue now.</span></span>
  
<span data-ttu-id="95960-104">Neke uobičajene poruke o grešci i rezolucija korake:</span><span class="sxs-lookup"><span data-stu-id="95960-104">Some common error messages and resolution steps:</span></span>
  
 <span data-ttu-id="95960-105">**Ne može biti instaliran softver, 0x80cf4017:** Vaš račun certifikat je istekao.</span><span class="sxs-lookup"><span data-stu-id="95960-105">**The software cannot be installed, 0x80cf4017:** Your account certificate has expired.</span></span> <span data-ttu-id="95960-106">Ponovo preuzmite paket softvera za PC klijent u Intune Admin konzoli.</span><span class="sxs-lookup"><span data-stu-id="95960-106">Re-download the PC Client software package in the Intune Admin Console.</span></span> <span data-ttu-id="95960-107">Pregledajte ovu dokumentaciju za više informacija.</span><span class="sxs-lookup"><span data-stu-id="95960-107">Review this documentation for more information.</span></span>
  
 <span data-ttu-id="95960-108">**Kôd greške 0x801c0003:** I greška se može pojaviti u sljedećim scenarijima:</span><span class="sxs-lookup"><span data-stu-id="95960-108">**Error code 0x801c0003:** The error can occur in the following scenarios:</span></span>
  
1. <span data-ttu-id="95960-109">Korisnik ima više uređaja je upisano od ograničenja uređaja.</span><span class="sxs-lookup"><span data-stu-id="95960-109">The user has more devices enrolled than the device limit.</span></span> <span data-ttu-id="95960-110">Pregledajte ove dokumente da [uklonite uređaj](https://docs.microsoft.com/intune/devices-wipe) ili [promijenite ograničenja uređaja](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span><span class="sxs-lookup"><span data-stu-id="95960-110">Review these documents to [remove a device](https://docs.microsoft.com/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>

2. <span data-ttu-id="95960-111">„Korisnicima možete pridružiti uređaji azurno AD” je postavljen na „nijedan”.</span><span class="sxs-lookup"><span data-stu-id="95960-111">"Users may join devices to Azure AD" is set to "none".</span></span> <span data-ttu-id="95960-112">Postavite ga na sve, ili izaberite korisnika.</span><span class="sxs-lookup"><span data-stu-id="95960-112">Set it to all or select users.</span></span> <span data-ttu-id="95960-113">Pregledajte [ovu dokumentaciju](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) za više informacija.</span><span class="sxs-lookup"><span data-stu-id="95960-113">Review [this documentation](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) for more information.</span></span>

3. <span data-ttu-id="95960-114">Uređaj je već upisan drugi korisnik.</span><span class="sxs-lookup"><span data-stu-id="95960-114">The device is already enrolled by another user.</span></span> <span data-ttu-id="95960-115">Ako je to slučaj, uklonite uređaj iz konzole za Azure Intune ili ručno unenroll uređaj pre nego što pokušate ponovo.</span><span class="sxs-lookup"><span data-stu-id="95960-115">If that's the case, remove the device from the Azure Intune console or manually unenroll the device before trying again.</span></span>

4. <span data-ttu-id="95960-116">Uređaj je Windows 10 Home.</span><span class="sxs-lookup"><span data-stu-id="95960-116">The device is Windows 10 Home.</span></span> <span data-ttu-id="95960-117">Samo Windows 10 Pro, obrazovanje i Enterprise MJ ne može da se pridruži Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="95960-117">Only Windows 10 Pro, Education and Enterprise SKUs can join Azure Active Directory.</span></span>

<span data-ttu-id="95960-118">Dodatni resursi da biste rešili problem:</span><span class="sxs-lookup"><span data-stu-id="95960-118">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="95960-119">Koristite [Intune rešavanje problema Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) da utvrdite i otklonite uobičajene upisa otkazivanja.</span><span class="sxs-lookup"><span data-stu-id="95960-119">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="95960-120">Pregledajte [ovaj dokument](https://docs.microsoft.com/intune/help-desk-operators) za više detalja.</span><span class="sxs-lookup"><span data-stu-id="95960-120">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span>

2. <span data-ttu-id="95960-121">Pregledajte ove dokumente za listu uobičajenih grešaka koje sprečavaju upisa i rezolucijama svakom: [Vodič za rešavanje problema](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) i [otklanjanje poteškoća doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="95960-121">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) and [Troubleshooting doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>

<span data-ttu-id="95960-122">Da [biste saznali kako da se upišu Windows uređaja u Microsoft Intune](https://docs.microsoft.com/intune/windows-enroll).</span><span class="sxs-lookup"><span data-stu-id="95960-122">[Learn how to enroll Windows devices in Microsoft Intune](https://docs.microsoft.com/intune/windows-enroll).</span></span>
