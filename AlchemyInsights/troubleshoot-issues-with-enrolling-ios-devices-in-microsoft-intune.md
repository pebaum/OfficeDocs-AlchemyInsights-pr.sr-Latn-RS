---
title: Rešavanje problema sa počinje upis iOS uređajima u usluzi Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d717bcc9-1cc1-44f6-b5e6-c1bc059c1973
ms.openlocfilehash: 664c18daca5d8e0ad4a88f41db3ff0dbced606e5
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43736172"
---
# <a name="troubleshoot-issues-with-enrolling-ios-devices-in-microsoft-intune"></a>Rešavanje problema sa počinje upis iOS uređajima u usluzi Microsoft Intune

Pregledajte dole navedene resurse da biste odmah rešili problem. 
  
Neke uobičajene poruke o grešci i koraci rešenja:
  
- **Dostignut je poklopac uređaja** Korisnik je više uređaja upisalo od ograničenja uređaja. Pregledajte ove dokumente da biste [uklonili uređaj](https://docs.microsoft.com/intune/devices-wipe) ili [promenili ograničenje uređaja](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).
    
- **Ova usluga nije podržana. Bez smernica za upis:** Apple push obaveštenja (APNS) treba konfigurisati ili obnoviti. Pregledajte [ovaj dokument](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) za uputstva kako da to uradite. 
    
- **Tip licence korisnika nevažeće ili korisničko ime nije prepoznato:** Korisniku se mora dodeliti licenca za Intune ili EMS. Pregledajte ove dokumente da biste dodelili licencu preko: [Office admin Center](https://docs.microsoft.com/intune/licenses-assign) ili [Azure portala](https://docs.microsoft.com/azure/active-directory/license-users-groups).
    
Dodatni resursi koji vam pomažu da rešite problem:
  
1. Koristite [Intune za rešavanje problema](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) da biste ustanovili i rešili uobičajene greške u uvrštavanju. Pregledajte [ovaj dokument](https://docs.microsoft.com/intune/help-desk-operators) za više detalja. 
    
2. Pregledajte ove dokumente da biste dobili listu uobičajenih grešaka koje sprečavaju upis i rešenja za svaki: [Vodič za rešavanje problema](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) i [Rešavanje problema sa programom Doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).
    
3. [Saznajte kako da prijavite iOS uređaje u programu Microsoft Intune](https://docs.microsoft.com/intune/ios-enroll).
    

