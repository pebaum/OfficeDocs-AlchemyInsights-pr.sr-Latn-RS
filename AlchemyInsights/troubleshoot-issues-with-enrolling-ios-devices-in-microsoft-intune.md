---
title: Rešavanje problema sa upiљem iOS uređaja u Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d717bcc9-1cc1-44f6-b5e6-c1bc059c1973
ms.openlocfilehash: bdbfe7bae00a4c5cfa0edbe9a37522cc98e52401
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36507017"
---
# <a name="troubleshoot-issues-with-enrolling-ios-devices-in-microsoft-intune"></a><span data-ttu-id="d2ad7-102">Rešavanje problema sa upiљem iOS uređaja u Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="d2ad7-102">Troubleshoot issues with enrolling iOS devices in Microsoft Intune</span></span>

<span data-ttu-id="d2ad7-103">Pregledajte resurse dole navedene riješiti tvoj problem sada.</span><span class="sxs-lookup"><span data-stu-id="d2ad7-103">Review the resources listed below to resolve your issue now.</span></span> 
  
<span data-ttu-id="d2ad7-104">Neke uobičajene poruke o grešci i rezolucija korake:</span><span class="sxs-lookup"><span data-stu-id="d2ad7-104">Some common error messages and resolution steps:</span></span>
  
- <span data-ttu-id="d2ad7-105">**Uređaj Cap postignut** Korisnik ima više uređaja je upisano od ograničenja uređaja.</span><span class="sxs-lookup"><span data-stu-id="d2ad7-105">**Device Cap Reached** The user has more devices enrolled than the device limit.</span></span> <span data-ttu-id="d2ad7-106">Pregledajte ove dokumente da [uklonite uređaj](https://docs.microsoft.com/intune/devices-wipe) ili [promijenite ograničenja uređaja](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span><span class="sxs-lookup"><span data-stu-id="d2ad7-106">Review these documents to [remove a device](https://docs.microsoft.com/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>
    
- <span data-ttu-id="d2ad7-107">**Ova usluga ne podržava. Nema upisa politika:** jabuka gurati obaveštenje usluge (odredi poseban APN za) potrebno konfigurisan ili obnovljena.</span><span class="sxs-lookup"><span data-stu-id="d2ad7-107">**This Service is not supported. No Enrollment Policy:** Apple Push Notification Service (APNS) needs to be configured or renewed.</span></span> <span data-ttu-id="d2ad7-108">Pregledajte [ovaj dokument](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) za uputstva o tome kako se to radi.</span><span class="sxs-lookup"><span data-stu-id="d2ad7-108">Review [this document](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) for instructions on how to do that.</span></span> 
    
- <span data-ttu-id="d2ad7-109">**Je nevažeći tip licence korisnika ili korisničko ime nije prepoznat:** Korisniku je potrebna za dodeljivanje licence za Intune ili EMS.</span><span class="sxs-lookup"><span data-stu-id="d2ad7-109">**User License Type Invalid or User Name Not Recognized:** The user needs to be assigned an Intune or EMS license.</span></span> <span data-ttu-id="d2ad7-110">Pregledajte ove dokumente da dodelite dozvole kroz: [Office Admin Center](https://docs.microsoft.com/intune/licenses-assign) ili [azurno portal](https://docs.microsoft.com/azure/active-directory/license-users-groups).</span><span class="sxs-lookup"><span data-stu-id="d2ad7-110">Review these documents to assign a license through: [Office Admin Center](https://docs.microsoft.com/intune/licenses-assign) or [Azure portal](https://docs.microsoft.com/azure/active-directory/license-users-groups).</span></span>
    
<span data-ttu-id="d2ad7-111">Dodatni resursi da biste rešili problem:</span><span class="sxs-lookup"><span data-stu-id="d2ad7-111">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="d2ad7-112">Koristite [Intune rešavanje problema Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) da utvrdite i otklonite uobičajene upisa otkazivanja.</span><span class="sxs-lookup"><span data-stu-id="d2ad7-112">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="d2ad7-113">Pregledajte [ovaj dokument](https://docs.microsoft.com/intune/help-desk-operators) za više detalja.</span><span class="sxs-lookup"><span data-stu-id="d2ad7-113">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="d2ad7-114">Pregledajte ove dokumente za listu uobičajenih grešaka koje sprečavaju upisa i rezolucijama svakom: [Vodič za rešavanje problema](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) i [otklanjanje poteškoća doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="d2ad7-114">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) and [Troubleshooting doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>
    
3. <span data-ttu-id="d2ad7-115">Da [biste saznali kako da se upišu iOS uređaja u Microsoft Intune](https://docs.microsoft.com/intune/ios-enroll).</span><span class="sxs-lookup"><span data-stu-id="d2ad7-115">[Learn how to enroll iOS devices in Microsoft Intune](https://docs.microsoft.com/intune/ios-enroll).</span></span>
    

