---
title: Rešavanje problema sa počinje upis iOS uređajima u usluzi Microsoft Intune
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
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/18/2019
ms.locfileid: "36507017"
---
# <a name="troubleshoot-issues-with-enrolling-ios-devices-in-microsoft-intune"></a><span data-ttu-id="2c98b-102">Rešavanje problema sa počinje upis iOS uređajima u usluzi Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="2c98b-102">Troubleshoot issues with enrolling iOS devices in Microsoft Intune</span></span>

<span data-ttu-id="2c98b-103">Pregledajte dole navedene resurse da biste odmah rešili problem.</span><span class="sxs-lookup"><span data-stu-id="2c98b-103">Review the resources listed below to resolve your issue now.</span></span> 
  
<span data-ttu-id="2c98b-104">Neke uobičajene poruke o grešci i koraci rešenja:</span><span class="sxs-lookup"><span data-stu-id="2c98b-104">Some common error messages and resolution steps:</span></span>
  
- <span data-ttu-id="2c98b-105">**Dostignut je poklopac uređaja** Korisnik je više uređaja upisalo od ograničenja uređaja.</span><span class="sxs-lookup"><span data-stu-id="2c98b-105">**Device Cap Reached** The user has more devices enrolled than the device limit.</span></span> <span data-ttu-id="2c98b-106">Pregledajte ove dokumente da biste [uklonili uređaj](https://docs.microsoft.com/intune/devices-wipe) ili [promenili ograničenje uređaja](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span><span class="sxs-lookup"><span data-stu-id="2c98b-106">Review these documents to [remove a device](https://docs.microsoft.com/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>
    
- <span data-ttu-id="2c98b-107">**Ova usluga nije podržana. Bez smernica za upis:** Apple push obaveštenja (APNS) treba konfigurisati ili obnoviti.</span><span class="sxs-lookup"><span data-stu-id="2c98b-107">**This Service is not supported. No Enrollment Policy:** Apple Push Notification Service (APNS) needs to be configured or renewed.</span></span> <span data-ttu-id="2c98b-108">Pregledajte [ovaj dokument](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) za uputstva kako da to uradite.</span><span class="sxs-lookup"><span data-stu-id="2c98b-108">Review [this document](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) for instructions on how to do that.</span></span> 
    
- <span data-ttu-id="2c98b-109">**Tip licence korisnika nevažeće ili korisničko ime nije prepoznato:** Korisniku se mora dodeliti licenca za Intune ili EMS.</span><span class="sxs-lookup"><span data-stu-id="2c98b-109">**User License Type Invalid or User Name Not Recognized:** The user needs to be assigned an Intune or EMS license.</span></span> <span data-ttu-id="2c98b-110">Pregledajte ove dokumente da biste dodelili licencu preko: [Office admin Center](https://docs.microsoft.com/intune/licenses-assign) ili [Azure portala](https://docs.microsoft.com/azure/active-directory/license-users-groups).</span><span class="sxs-lookup"><span data-stu-id="2c98b-110">Review these documents to assign a license through: [Office Admin Center](https://docs.microsoft.com/intune/licenses-assign) or [Azure portal](https://docs.microsoft.com/azure/active-directory/license-users-groups).</span></span>
    
<span data-ttu-id="2c98b-111">Dodatni resursi koji vam pomažu da rešite problem:</span><span class="sxs-lookup"><span data-stu-id="2c98b-111">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="2c98b-112">Koristite [Intune za rešavanje problema](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) da biste ustanovili i rešili uobičajene greške u uvrštavanju.</span><span class="sxs-lookup"><span data-stu-id="2c98b-112">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="2c98b-113">Pregledajte [ovaj dokument](https://docs.microsoft.com/intune/help-desk-operators) za više detalja.</span><span class="sxs-lookup"><span data-stu-id="2c98b-113">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="2c98b-114">Pregledajte ove dokumente da biste dobili listu uobičajenih grešaka koje sprečavaju upis i rešenja za svaki: [Vodič za rešavanje problema](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) i [Rešavanje problema sa programom Doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="2c98b-114">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) and [Troubleshooting doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>
    
3. <span data-ttu-id="2c98b-115">[Saznajte kako da prijavite iOS uređaje u programu Microsoft Intune](https://docs.microsoft.com/intune/ios-enroll).</span><span class="sxs-lookup"><span data-stu-id="2c98b-115">[Learn how to enroll iOS devices in Microsoft Intune](https://docs.microsoft.com/intune/ios-enroll).</span></span>
    

