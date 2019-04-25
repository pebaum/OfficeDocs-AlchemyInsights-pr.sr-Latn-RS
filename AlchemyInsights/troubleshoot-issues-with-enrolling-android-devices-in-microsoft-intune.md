---
title: Rešavanje problema sa upiљem Android uređaja u Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d0269461-20a8-4c9e-83b2-8fcf608dc0a5
ms.openlocfilehash: 0e727bd47a7d549a439e4666fa9dbb8a02e39778
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32420606"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a><span data-ttu-id="fa7ee-102">Rešavanje problema sa upiљem Android uređaja u Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="fa7ee-102">Troubleshoot issues with enrolling Android devices in Microsoft Intune</span></span>

<span data-ttu-id="fa7ee-103">Pregledajte resurse dole navedene riješiti tvoj problem sada.</span><span class="sxs-lookup"><span data-stu-id="fa7ee-103">Review the resources listed below to resolve your issue now.</span></span>
  
<span data-ttu-id="fa7ee-104">Neke uobičajene probleme i rezolucija korake:</span><span class="sxs-lookup"><span data-stu-id="fa7ee-104">Some common issues and resolution steps:</span></span>
  
 <span data-ttu-id="fa7ee-105">**Uređaj nije šifrovana greške u kompaniji Portal:** Novije verzije androida, posebno, počevši od v7.0, zahteva za pokretanje љifrom da se uverite da li je vaš uređaj u potpunosti šifrovana.</span><span class="sxs-lookup"><span data-stu-id="fa7ee-105">**Device not Encrypted error in Company Portal:** Newer versions of Android, particularly starting with v7.0, require a startup passcode to make sure that your device is fully encrypted.</span></span> <span data-ttu-id="fa7ee-106">Da biste omogućili pin za pokretanje ili u potpunosti Šifriraj uređaj su uobičajene rešenja.</span><span class="sxs-lookup"><span data-stu-id="fa7ee-106">Common solutions are to enable a startup pin or fully encrypt the device.</span></span> <span data-ttu-id="fa7ee-107">Pregledajte [ovaj dokument](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) za više informacija.</span><span class="sxs-lookup"><span data-stu-id="fa7ee-107">Review [this document](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) for more information.</span></span> 
  
 <span data-ttu-id="fa7ee-108">**Uređaji ne uspeju da provjerimo Intune servis ili prikazati kao „Unhealthy” u Intune admin konzoli:** 4.4 neki Samsung i 5.5 uređaji možda ne prijavi se u servis.</span><span class="sxs-lookup"><span data-stu-id="fa7ee-108">**Devices fail to check in with the Intune service or display as "Unhealthy" in the Intune admin console:** Some Samsung 4.4 and 5.5 devices may not check into the service.</span></span> <span data-ttu-id="fa7ee-109">Postoje 3 mogućih rešenja ovog problema:</span><span class="sxs-lookup"><span data-stu-id="fa7ee-109">There are 3 possible solutions to this issue:</span></span> 
  
1. <span data-ttu-id="fa7ee-110">Ručno otvorite aplikaciju Intune kompanije Portal, koji će automatski pokrenuti sinhronizaciju uređaja.</span><span class="sxs-lookup"><span data-stu-id="fa7ee-110">Manually open the Intune Company Portal app, which will automatically initiate a device sync.</span></span>
    
2. <span data-ttu-id="fa7ee-111">Ažurirajte uređaj na Android 6.0 ili višu.</span><span class="sxs-lookup"><span data-stu-id="fa7ee-111">Update the device to Android 6.0 or higher.</span></span>
    
3. <span data-ttu-id="fa7ee-112">Onemogući pametan menadžer Samsung od upravljanja Intune kompanija Portal.</span><span class="sxs-lookup"><span data-stu-id="fa7ee-112">Disable Samsung Smart Manager from managing the Intune Company Portal.</span></span> <span data-ttu-id="fa7ee-113">Pregledajte [ovaj dokument](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) za dalje detalje o tim pitanjima i rezolucijama.</span><span class="sxs-lookup"><span data-stu-id="fa7ee-113">Review [this document](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) for further details on these issues and resolutions.</span></span> 
    
 <span data-ttu-id="fa7ee-114">**Korisnička licenca tip nevažeći** ili **korisničko ime nije prepoznato greška:** korisniku je potrebna za dodeljivanje licence za Intune ili EMS.</span><span class="sxs-lookup"><span data-stu-id="fa7ee-114">**User License Type Invalid** or **User Name Not Recognized error:** The user needs to be assigned an Intune or EMS license.</span></span> <span data-ttu-id="fa7ee-115">Pregledajte ove dokumente da dodelite dozvole kroz: Office Admin centar "ili" Azure portal.</span><span class="sxs-lookup"><span data-stu-id="fa7ee-115">Review these documents to assign a license through: Office Admin Center or Azure portal.</span></span> 
  
<span data-ttu-id="fa7ee-116">Dodatni resursi da biste rešili problem:</span><span class="sxs-lookup"><span data-stu-id="fa7ee-116">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="fa7ee-117">Koristite [Intune rešavanje problema Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) da utvrdite i otklonite uobičajene upisa otkazivanja.</span><span class="sxs-lookup"><span data-stu-id="fa7ee-117">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="fa7ee-118">Pregledajte [ovaj dokument](https://docs.microsoft.com/intune/help-desk-operators) za više detalja.</span><span class="sxs-lookup"><span data-stu-id="fa7ee-118">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="fa7ee-119">Pregledajte [ovaj dokument](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) na listu uobičajenih grešaka koje sprečavaju upisa i rezolucijama svakom.</span><span class="sxs-lookup"><span data-stu-id="fa7ee-119">Review [this document](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) for a list of common errors that prevent enrollment and resolutions to each.</span></span> 
    
3. <span data-ttu-id="fa7ee-120">Da [biste saznali kako da se upišu Android uređaja u Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).</span><span class="sxs-lookup"><span data-stu-id="fa7ee-120">[Learn how to enroll Android devices in Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).</span></span>
    

