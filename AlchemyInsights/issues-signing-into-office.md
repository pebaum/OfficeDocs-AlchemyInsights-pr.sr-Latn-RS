---
title: Problemi sa prijavljivanjem u Office aplikacije
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
- "2574"
ms.openlocfilehash: 695d449a876c22ff441da2367ef67aaea470eb66
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43763015"
---
# <a name="issues-signing-in-to-office-apps"></a>Problemi sa prijavljivanjem u Office aplikacije

Da biste ispravili probleme sa prijavljivanjem pomoću Office aplikacija, Isprobajte sledeće:

- Uklonite sve poslovne naloge, izuzev sa pogođenim nalogom, koristeći Windows postavke > **pristup poslu ili školi**.
- [Obrišite Office akreditive](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) koristeći Windows upravljač akreditivima.<br/>
    **Napomena:** Putanje registratora za Office 2016 su promenjene u 16,0. (Ex: \Software\microsoft\office\16.0\zajed\identitet\)
- Otvorite Office aplikaciju, odaberite stavku "**nalog** > za **datoteku** > **".** Zatim se prijavite koristeći korisnički nalog sa važećom licencom. Detaljne informacije potražite u članku [Nalozi u sistemu Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).
- Za Mac računar pročitajte članak [Nije moguće prijaviti se u Office 2016 za Mac aplikaciju](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).
- Ako dođe do grešaka prilikom povezivanja sa Microsoft 365 pomoću programa Office 2013, omogućite modernu potvrdu identiteta za Office Client.

Za više informacija pogledajte:
- [Ne možete da se prijavite u Microsoft 365, Azure ili Intune](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-365-azure-intune)
- [Problemi sa vezom u prijavljivanju nakon ažuriranja na Office 2016 Build 16.0.7967 na Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016)
- ["Nažalost, drugi nalog iz vaše organizacije je već prijavljen na ovaj računar" u sistemu Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in)
- [Rešavanje problema pri prijavljivanju sa Office modernom potvrdom identiteta kada koristite ADFS](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-issue-with-modern-auth)