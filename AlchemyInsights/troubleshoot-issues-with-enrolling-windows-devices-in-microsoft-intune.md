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
ms.openlocfilehash: aa2262ed487ae4160f13490e92163a145e657862
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29934790"
---
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a>Rešavanje problema sa upiљem Windows uređaja u Microsoft Intune

Pregledajte resurse dole navedene riješiti tvoj problem sada. 
  
Neke uobičajene poruke o grešci i rezolucija korake:
  
 **Ne može biti instaliran softver, 0x80cf4017:** Vaš račun certifikat je istekao. Ponovo preuzmite paket softvera za PC klijent u Intune Admin konzoli. Pregledajte ovu dokumentaciju za više informacija. 
  
 **Kôd greške 0x801c0003:** I greška se može pojaviti u sljedećim scenarijima: 
  
1. Korisnik ima više uređaja je upisano od ograničenja uređaja. Pregledajte ove dokumente da [uklonite uređaj](https://docs.microsoft.com/intune/devices-wipe) ili [promijenite ograničenja uređaja](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).
    
2. „Korisnicima možete pridružiti uređaji azurno AD” je postavljen na „nijedan”. Postavite ga na sve, ili izaberite korisnika. Pregledajte [ovu dokumentaciju](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) za više informacija. 
    
3. Uređaj je već upisan drugi korisnik. Ako je to slučaj, uklonite uređaj iz konzole za Azure Intune ili ručno unenroll uređaj pre nego što pokušate ponovo.
    
4. Uređaj je Windows 10 Home. Samo Windows 10 Pro, obrazovanje i Enterprise MJ ne može da se pridruži Azure Active Directory.
    
Dodatni resursi da biste rešili problem:
  
1. Koristite [Intune rešavanje problema Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) da utvrdite i otklonite uobičajene upisa otkazivanja. Pregledajte [ovaj dokument](https://docs.microsoft.com/intune/help-desk-operators) za više detalja. 
    
2. Pregledajte ove dokumente za listu uobičajenih grešaka koje sprečavaju upisa i rezolucijama svakom: [Vodič za rešavanje problema](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) i [otklanjanje poteškoća doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).
    
Da [biste saznali kako da se upišu Windows uređaja u Microsoft Intune](https://docs.microsoft.com/intune/windows-enroll).
  

