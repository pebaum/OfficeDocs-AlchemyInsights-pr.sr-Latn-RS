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
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a>Rešavanje problema sa počinje upis Android uređajima u usluzi Microsoft Intune

Pregledajte dole navedene resurse da biste odmah rešili problem.
  
Neka uobičajena pitanja i koraci rešenja:
  
 **Uređaj nije šifrovana greška u portalu preduzeća:** Novije verzije programa android, naročito počevši od v 7.0, zahtevaju kôd za prolaz za pokretanje da biste se uverili da je uređaj potpuno šifrovan. Uobičajena rešenja su omogućavanje PIN-a za pokretanje ili u potpunosti šifrovanje uređaja. Pregledajte [ovaj dokument](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) za više informacija.
  
 **Uređaji ne uspevaju da se provere pomoću usluge Intune ili prikazuju kao "nezdrave" u usluzi Intune admin Console:** Neki Samsung 4,4 i 5,5 uređaja možda neće proveravati uslugu. Postoji 3 moguća rešenja za ovaj problem:
  
1. Ručno otvorite aplikaciju "Intune Company portal" koja će automatski pokrenuti sinhronizaciju uređaja.

2. Ažurirajte uređaj na Android 6,0 ili noviji.

3. Onemogućite Samsung Smart Manager iz upravljanja portalom "Intune Company". Pregledajte [ovaj dokument](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) za više detalja o ovim problemima i rezolucijama.

 **Tip licence korisnika nevažeće** ili **korisničko ime nije prepoznato greška:** korisniku treba da bude dodeljena licenca za Intune ili Ems licencu. Pregledajte ove dokumente da biste dodelili licencu preko: Office admin Center ili Azure portala.
  
Dodatni resursi koji vam pomažu da rešite problem:
  
1. Koristite [Intune za rešavanje problema](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) da biste ustanovili i rešili uobičajene greške u uvrštavanju. Pregledajte [ovaj dokument](https://docs.microsoft.com/intune/help-desk-operators) za više detalja.

2. Pregledajte [ovaj dokument](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) da biste dobili listu uobičajenih grešaka koje sprečavaju upis i rešenja.

3. [Saznajte kako da prijavite Android uređaje u programu Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).
