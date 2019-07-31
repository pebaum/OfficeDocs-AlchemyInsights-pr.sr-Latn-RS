---
title: Problemi prijavljivanja na Office aplikacije
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000571"
- "2556"
ms.openlocfilehash: 08bb0a94066f071f2ba0e9c54378f0d479191496
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938327"
---
# <a name="blank-sign-in-screen-in-office-apps"></a>Prazan za prijavljivanje ekran u Office aplikacije

Da biste rešili ovaj problem, pokušajte sledeće:
- Instalirajte najnovije ispravke za [Windows](https://support.microsoft.com/help/4027667/windows-10-update) i [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).
- Poništavanje opcije programa Internet Explorer: U **Alatke** > **Internet opcije** > **Više opcija** > **Vraćanje početnih postavki programa Internet Explorer** (Napomena da će izgubiti prilagođene postavke) i zatim pokušajte ponovo potpisivanje kancelariju.
- Onemogućite garde aplikacije Windows Defender (WDAG) ili bilo koji sličan zaštitni zid ili antivirusni program:
    1. Na kontrolnoj tabli, idite na **programe**, a zatim odaberite **Windows Uključivanje ili isključivanje funkcija**.
    2. Ako je omogućen Windows Defender aplikacije garde, pokušajte da ga onemogućite.<br/>
    **Napomena:** Morate ponovo pokrenuti računalo.
- Uverite se da se Microsoft.AAD.BrokerPlugin [AAD WAM dodatne komponente](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-1) ne blokira neke aplikacije ili program zaštitnog zida/anti-virus.
- [Jasna Office akreditive](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) pomoću Windows upravljač akreditivima.<br/>
    **Napomena:** Putanje registratora za Office 2016 promenili 16.0. (Ex: \Software\Microsoft\Office\16.0\Common\Identity\)

Više informacija potražite u odeljku [za povezivanje pitanja u za prijavljivanje nakon ažuriranja za Office 2016 build 16.0.7967 na Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).