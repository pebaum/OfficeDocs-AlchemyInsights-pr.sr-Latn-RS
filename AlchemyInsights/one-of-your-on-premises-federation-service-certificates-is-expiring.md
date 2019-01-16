---
title: Jedan od vaše lokalne Federacije servis certifikate ističe
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 172084b7-68a1-42a5-944d-2e871eaa2972
ms.openlocfilehash: 89a4dd910d43d70e849be19d5f88e281f6d19834
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/15/2019
ms.locfileid: "28309424"
---
# <a name="one-of-your-on-premises-federation-service-certificates-is-expiring"></a>Jedan od vaše lokalne Federacije servis certifikate ističe

Da biste riješili taj problem, slijedite ove korake:
  
- Instalirati na Microsoft Azure Active Directory modul za Windows PowerShell na računaru (ako modul nije već instaliran). Da biste ovo uradili, idite na [Azure Active Directory PowerShell za grafikon](https://docs.microsoft.com/en-us/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)
    
- Sledite korake u na „Scenario 1: AD FS token potpisivanje certifikat istekao” delu [„Postoji problem sa pristupom na lokaciji” greška iz AD FS kada savezni korisnik potpiše Office 365, Azure, ili Intune](https://support.microsoft.com/en-us/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).
    
- Sledite korake u t[Kako da ažurirate ili popravite postavke savezni domena u Office 365, Azure, ili Intune](https://support.microsoft.com/en-us/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).
    
Za više informacija o obnavlja certifikate Federacije, pogledajte [obnove certifikata za O365 i azurno AD](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-o365-certs).
  

