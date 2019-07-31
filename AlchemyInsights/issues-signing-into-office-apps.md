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
- "2559"
ms.openlocfilehash: 5f500ecf1f779fb1be4d257fd050a3ad054087dc
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938328"
---
# <a name="fixing-the-office-apps-your-computers-trusted-platform-module-is-not-functioning-properly-message"></a>Popravljanje Office aplikacije „modul pouzdane platforme na računaru ne funkcioniše ispravno” poruka

Da biste otklonili ovu grešku, pokušajte sledeće:

- Instalirajte najnovije ispravke za [Windows](https://support.microsoft.com/help/4027667/windows-10-update) i [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).
- [Jasna Office akreditive](https://docs.microsoft.com/eoffice/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) pomoću Windows upravljač akreditivima.<br/>
    **Napomena:** Putanje registratora za Office 2016 promenili 16.0. (Ex: \Software\Microsoft\Office\16.0\Common\Identity\)
- Probaj [proces oporavka korisnika](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-2) da popravimo modul pouzdane platforme (TPM) otkazivanja.
- Postavljen je EnableADAL = 0, koristite sledeće korake:  
    1. Kliknite desnim tasterom miša na dugme Start operativnog sistema Windows, odaberite **Pokreni**, upišite **regedit**, a zatim odaberite **u redu**.
    2. Kliknite na dugme **da** da biste dozvolili Registry Editor da biste promenili vaš uređaj.
    3. U alatki "Uređivač registratora" dodati DWORD vrijednost od **EnableADAL** sa postavkom **0** pod HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.

Više informacija potražite u odeljku [za povezivanje pitanja u za prijavljivanje nakon ažuriranja za Office 2016 build 16.0.7967 na Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).