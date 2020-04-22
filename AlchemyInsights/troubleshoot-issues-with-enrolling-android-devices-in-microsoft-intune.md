---
title: Rešavanje problema sa počinje upis Android uređajima u usluzi Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d0269461-20a8-4c9e-83b2-8fcf608dc0a5
ms.custom:
- "787"
- "6200002"
ms.openlocfilehash: bd6d278ebf6cca7fb6e4ac1049deae600b516707
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43759634"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a><span data-ttu-id="9b725-102">Rešavanje problema sa počinje upis Android uređajima u usluzi Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="9b725-102">Troubleshoot issues with enrolling Android devices in Microsoft Intune</span></span>

<span data-ttu-id="9b725-103">Pregledajte dole navedene resurse da biste odmah rešili problem.</span><span class="sxs-lookup"><span data-stu-id="9b725-103">Review the resources listed below to resolve your issue now.</span></span>
  
<span data-ttu-id="9b725-104">Neka uobičajena pitanja i koraci rešenja:</span><span class="sxs-lookup"><span data-stu-id="9b725-104">Some common issues and resolution steps:</span></span>
  
 <span data-ttu-id="9b725-105">**Uređaj nije šifrovana greška u portalu preduzeća:** Novije verzije programa android, naročito počevši od v 7.0, zahtevaju kôd za prolaz za pokretanje da biste se uverili da je uređaj potpuno šifrovan.</span><span class="sxs-lookup"><span data-stu-id="9b725-105">**Device not Encrypted error in Company Portal:** Newer versions of Android, particularly starting with v7.0, require a startup passcode to make sure that your device is fully encrypted.</span></span> <span data-ttu-id="9b725-106">Uobičajena rešenja su omogućavanje PIN-a za pokretanje ili u potpunosti šifrovanje uređaja.</span><span class="sxs-lookup"><span data-stu-id="9b725-106">Common solutions are to enable a startup pin or fully encrypt the device.</span></span> <span data-ttu-id="9b725-107">Pregledajte [ovaj dokument](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) za više informacija.</span><span class="sxs-lookup"><span data-stu-id="9b725-107">Review [this document](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) for more information.</span></span>
  
 <span data-ttu-id="9b725-108">**Uređaji ne uspevaju da se provere pomoću usluge Intune ili prikazuju kao "nezdrave" u usluzi Intune admin Console:** Neki Samsung 4,4 i 5,5 uređaja možda neće proveravati uslugu.</span><span class="sxs-lookup"><span data-stu-id="9b725-108">**Devices fail to check in with the Intune service or display as "Unhealthy" in the Intune admin console:** Some Samsung 4.4 and 5.5 devices may not check into the service.</span></span> <span data-ttu-id="9b725-109">Postoji 3 moguća rešenja za ovaj problem:</span><span class="sxs-lookup"><span data-stu-id="9b725-109">There are 3 possible solutions to this issue:</span></span>
  
1. <span data-ttu-id="9b725-110">Ručno otvorite aplikaciju "Intune Company portal" koja će automatski pokrenuti sinhronizaciju uređaja.</span><span class="sxs-lookup"><span data-stu-id="9b725-110">Manually open the Intune Company Portal app, which will automatically initiate a device sync.</span></span>

2. <span data-ttu-id="9b725-111">Ažurirajte uređaj na Android 6,0 ili noviji.</span><span class="sxs-lookup"><span data-stu-id="9b725-111">Update the device to Android 6.0 or higher.</span></span>

3. <span data-ttu-id="9b725-112">Onemogućite Samsung Smart Manager iz upravljanja portalom "Intune Company".</span><span class="sxs-lookup"><span data-stu-id="9b725-112">Disable Samsung Smart Manager from managing the Intune Company Portal.</span></span> <span data-ttu-id="9b725-113">Pregledajte [ovaj dokument](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) za više detalja o ovim problemima i rezolucijama.</span><span class="sxs-lookup"><span data-stu-id="9b725-113">Review [this document](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) for further details on these issues and resolutions.</span></span>

 <span data-ttu-id="9b725-114">**Tip licence korisnika nevažeće** ili **korisničko ime nije prepoznato greška:** korisniku treba da bude dodeljena licenca za Intune ili Ems licencu.</span><span class="sxs-lookup"><span data-stu-id="9b725-114">**User License Type Invalid** or **User Name Not Recognized error:** The user needs to be assigned an Intune or EMS license.</span></span> <span data-ttu-id="9b725-115">Pregledajte ove dokumente da biste dodelili licencu preko: Office admin Center ili Azure portala.</span><span class="sxs-lookup"><span data-stu-id="9b725-115">Review these documents to assign a license through: Office Admin Center or Azure portal.</span></span>
  
<span data-ttu-id="9b725-116">Dodatni resursi koji vam pomažu da rešite problem:</span><span class="sxs-lookup"><span data-stu-id="9b725-116">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="9b725-117">Koristite [Intune za rešavanje problema](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) da biste ustanovili i rešili uobičajene greške u uvrštavanju.</span><span class="sxs-lookup"><span data-stu-id="9b725-117">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="9b725-118">Pregledajte [ovaj dokument](https://docs.microsoft.com/intune/help-desk-operators) za više detalja.</span><span class="sxs-lookup"><span data-stu-id="9b725-118">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span>

2. <span data-ttu-id="9b725-119">Pregledajte [ovaj dokument](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) da biste dobili listu uobičajenih grešaka koje sprečavaju upis i rešenja.</span><span class="sxs-lookup"><span data-stu-id="9b725-119">Review [this document](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) for a list of common errors that prevent enrollment and resolutions to each.</span></span>

3. <span data-ttu-id="9b725-120">[Saznajte kako da prijavite Android uređaje u programu Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).</span><span class="sxs-lookup"><span data-stu-id="9b725-120">[Learn how to enroll Android devices in Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).</span></span>
