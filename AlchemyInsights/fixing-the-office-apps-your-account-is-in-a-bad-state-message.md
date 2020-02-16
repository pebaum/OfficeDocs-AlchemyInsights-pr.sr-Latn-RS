---
title: Popravljanje Office aplikacija vaš nalog je u lošem stanju
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2558"
- "9000571"
ms.openlocfilehash: e591c56dd207a5bcb3979be3f66052121100b162
ms.sourcegitcommit: 2572c4e5a981d5f3f556835061c568cfd08b78da
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/27/2019
ms.locfileid: "41969759"
---
# <a name="fixing-the-office-apps-your-account-is-in-a-bad-state-error"></a>Popravljanje Office aplikacija "vaš nalog je u lošem stanju"

Da biste otklonili ovu grešku, Isprobajte sledeće opcije na računaru koji je na njemu:

- Otvorite Office aplikaciju, izaberite**nalog** > za **datoteku** > **sa svih naloga**. Prijavite se ponovo koristeći korisnički nalog sa važećom licencom. Detaljnije informacije potražite u članku [Nalozi u sistemu Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).
- [Obrišite Office akreditive](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) koristeći Windows upravljač akreditivima.<br>
  **Napomena:** Putanje registratora za Office 2016 su promenjene u 16,0. Na primer, \Software\microsoft\office\16.0\uobičajeno \ Identitet\
- Na računaru koji je uticao na računar postavite potencijalnog klijenta za praćenje = 0 koristeći sledeće korake:  
     1. Kliknite desnim tasterom miša na dugme Windows i izaberite stavku **Pokreni**. U polju **Otvori** otkucajte **Regedit**, a zatim izaberite **"u redu"**.
     2. Kliknite na **dugme "da** " kada se od vas zatraži da dozvolite Registry Editoru da promeni vaš uređaj.
    3. U programu Registry Editor dodajte DWORD vrednost Enabpotencijalnog klijenta sa postavkom 0 ispod HKEY_CURRENT_USER \Software\microsoft\office\16.0\pod\identitet.
- Ako dođe do greške tokom povezivanja sa Office 365 pomoću programa Office 2013, [omogućite modernu potvrdu identiteta](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication) za Office Client.

Više informacija potražite u članku [Rešavanje problema sa aplikacijama koje ne pripadaju pregledaču koje ne mogu da se prijave na Office 365, Azure ili Intune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).

