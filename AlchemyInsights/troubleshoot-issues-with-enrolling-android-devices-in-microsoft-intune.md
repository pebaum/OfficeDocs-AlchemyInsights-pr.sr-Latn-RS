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
ms.custom:
- "787"
- "6200002"
ms.openlocfilehash: 1e1d50c31df588a3416d758d40fbd7bde3f73b21
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36500085"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a><span data-ttu-id="f5c33-102">Rešavanje problema sa upiљem Android uređaja u Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="f5c33-102">Troubleshoot issues with enrolling Android devices in Microsoft Intune</span></span>

<span data-ttu-id="f5c33-103">Pregledajte resurse dole navedene riješiti tvoj problem sada.</span><span class="sxs-lookup"><span data-stu-id="f5c33-103">Review the resources listed below to resolve your issue now.</span></span>
  
<span data-ttu-id="f5c33-104">Neke uobičajene probleme i rezolucija korake:</span><span class="sxs-lookup"><span data-stu-id="f5c33-104">Some common issues and resolution steps:</span></span>
  
 <span data-ttu-id="f5c33-105">**Uređaj nije šifrovana greške u kompaniji Portal:** Novije verzije androida, posebno, počevši od v7.0, zahteva za pokretanje љifrom da se uverite da li je vaš uređaj u potpunosti šifrovana.</span><span class="sxs-lookup"><span data-stu-id="f5c33-105">**Device not Encrypted error in Company Portal:** Newer versions of Android, particularly starting with v7.0, require a startup passcode to make sure that your device is fully encrypted.</span></span> <span data-ttu-id="f5c33-106">Da biste omogućili pin za pokretanje ili u potpunosti Šifriraj uređaj su uobičajene rešenja.</span><span class="sxs-lookup"><span data-stu-id="f5c33-106">Common solutions are to enable a startup pin or fully encrypt the device.</span></span> <span data-ttu-id="f5c33-107">Pregledajte [ovaj dokument](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) za više informacija.</span><span class="sxs-lookup"><span data-stu-id="f5c33-107">Review [this document](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) for more information.</span></span>
  
 <span data-ttu-id="f5c33-108">**Uređaji ne uspeju da provjerimo Intune servis ili prikazati kao „Unhealthy” u Intune admin konzoli:** 4.4 neki Samsung i 5.5 uređaji možda ne prijavi se u servis.</span><span class="sxs-lookup"><span data-stu-id="f5c33-108">**Devices fail to check in with the Intune service or display as "Unhealthy" in the Intune admin console:** Some Samsung 4.4 and 5.5 devices may not check into the service.</span></span> <span data-ttu-id="f5c33-109">Postoje 3 mogućih rešenja ovog problema:</span><span class="sxs-lookup"><span data-stu-id="f5c33-109">There are 3 possible solutions to this issue:</span></span>
  
1. <span data-ttu-id="f5c33-110">Ručno otvorite aplikaciju Intune kompanije Portal, koji će automatski pokrenuti sinhronizaciju uređaja.</span><span class="sxs-lookup"><span data-stu-id="f5c33-110">Manually open the Intune Company Portal app, which will automatically initiate a device sync.</span></span>

2. <span data-ttu-id="f5c33-111">Ažurirajte uređaj na Android 6.0 ili višu.</span><span class="sxs-lookup"><span data-stu-id="f5c33-111">Update the device to Android 6.0 or higher.</span></span>

3. <span data-ttu-id="f5c33-112">Onemogući pametan menadžer Samsung od upravljanja Intune kompanija Portal.</span><span class="sxs-lookup"><span data-stu-id="f5c33-112">Disable Samsung Smart Manager from managing the Intune Company Portal.</span></span> <span data-ttu-id="f5c33-113">Pregledajte [ovaj dokument](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) za dalje detalje o tim pitanjima i rezolucijama.</span><span class="sxs-lookup"><span data-stu-id="f5c33-113">Review [this document](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) for further details on these issues and resolutions.</span></span>

 <span data-ttu-id="f5c33-114">**Korisnička licenca tip nevažeći** ili **korisničko ime nije prepoznato greška:** korisniku je potrebna za dodeljivanje licence za Intune ili EMS.</span><span class="sxs-lookup"><span data-stu-id="f5c33-114">**User License Type Invalid** or **User Name Not Recognized error:** The user needs to be assigned an Intune or EMS license.</span></span> <span data-ttu-id="f5c33-115">Pregledajte ove dokumente da dodelite dozvole kroz: Office Admin centar "ili" Azure portal.</span><span class="sxs-lookup"><span data-stu-id="f5c33-115">Review these documents to assign a license through: Office Admin Center or Azure portal.</span></span>
  
<span data-ttu-id="f5c33-116">Dodatni resursi da biste rešili problem:</span><span class="sxs-lookup"><span data-stu-id="f5c33-116">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="f5c33-117">Koristite [Intune rešavanje problema Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) da utvrdite i otklonite uobičajene upisa otkazivanja.</span><span class="sxs-lookup"><span data-stu-id="f5c33-117">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="f5c33-118">Pregledajte [ovaj dokument](https://docs.microsoft.com/intune/help-desk-operators) za više detalja.</span><span class="sxs-lookup"><span data-stu-id="f5c33-118">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span>

2. <span data-ttu-id="f5c33-119">Pregledajte [ovaj dokument](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) na listu uobičajenih grešaka koje sprečavaju upisa i rezolucijama svakom.</span><span class="sxs-lookup"><span data-stu-id="f5c33-119">Review [this document](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) for a list of common errors that prevent enrollment and resolutions to each.</span></span>

3. <span data-ttu-id="f5c33-120">Da [biste saznali kako da se upišu Android uređaja u Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).</span><span class="sxs-lookup"><span data-stu-id="f5c33-120">[Learn how to enroll Android devices in Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).</span></span>
