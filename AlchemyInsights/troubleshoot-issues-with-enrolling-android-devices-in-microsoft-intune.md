---
title: Rešavanje problema sa upiљem Android uređaja u Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: d0269461-20a8-4c9e-83b2-8fcf608dc0a5
ms.openlocfilehash: 6b26b2d77bceb063090986ff4e20bc4a56bb1242
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/30/2019
ms.locfileid: "29655897"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a>Rešavanje problema sa upiљem Android uređaja u Microsoft Intune

Pregledajte resurse dole navedene riješiti tvoj problem sada.
  
Neke uobičajene probleme i rezolucija korake:
  
 **Uređaj nije šifrovana greške u kompaniji Portal:** Novije verzije androida, posebno, počevši od v7.0, zahteva za pokretanje љifrom da se uverite da li je vaš uređaj u potpunosti šifrovana. Da biste omogućili pin za pokretanje ili u potpunosti Šifriraj uređaj su uobičajene rešenja. Pregledajte [ovaj dokument](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) za više informacija. 
  
 **Uređaji ne uspeju da provjerimo Intune servis ili prikazati kao „Unhealthy” u Intune admin konzoli:** 4.4 neki Samsung i 5.5 uređaji možda ne prijavi se u servis. Postoje 3 mogućih rešenja ovog problema: 
  
1. Ručno otvorite aplikaciju Intune kompanije Portal, koji će automatski pokrenuti sinhronizaciju uređaja.
    
2. Ažurirajte uređaj na Android 6.0 ili višu.
    
3. Onemogući pametan menadžer Samsung od upravljanja Intune kompanija Portal. Pregledajte [ovaj dokument](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) za dalje detalje o tim pitanjima i rezolucijama. 
    
 **Korisnička licenca tip nevažeći** ili **korisničko ime nije prepoznato greška:** korisniku je potrebna za dodeljivanje licence za Intune ili EMS. Pregledajte ove dokumente da dodelite dozvole kroz: Office Admin centar "ili" Azure portal. 
  
Dodatni resursi da biste rešili problem:
  
1. Koristite [Intune rešavanje problema Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) da utvrdite i otklonite uobičajene upisa otkazivanja. Pregledajte [ovaj dokument](https://docs.microsoft.com/intune/help-desk-operators) za više detalja. 
    
2. Pregledajte [ovaj dokument](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) na listu uobičajenih grešaka koje sprečavaju upisa i rezolucijama svakom. 
    
3. Da [biste saznali kako da se upišu Android uređaja u Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).
    

