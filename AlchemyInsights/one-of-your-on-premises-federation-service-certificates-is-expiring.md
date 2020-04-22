---
title: Jedan od tvojih potvrda o službi Federacije
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 172084b7-68a1-42a5-944d-2e871eaa2972
ms.openlocfilehash: 24c369c61ad7cf7a9fe101ac29271c32e5159c1f
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43761397"
---
# <a name="one-of-your-on-premises-federation-service-certificates-is-expiring"></a>Jedan od tvojih potvrda o službi Federacije

Da biste riješili taj problem, slijedite ove korake:
  
- Instalirajte Microsoft Azure Active Directory modul za Windows PowerShell na računaru (ako modul nije već instaliran). Da biste to uradili, idite na [Azure PowerShell aktivnog direktorijuma za grafik](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)
    
- Sledite korake u odjeljku "scenario 1: istekao je certifikat potpisa" AD FS "-za potpisivanje" [postoji problem "Došlo je do problema sa pristupom lokaciji" iz AD FS-a kada se federirani korisnik prijavi na Office 365, Azure ili Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).
    
- Sledite korake u t[Kako da ažurirate ili popravite postavke federovanog domena u sistemu Office 365, Azure ili Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).
    
Za više informacija o obnavljanju certifikata u Federaciji pogledajte odeljak [obnova certifikata za O365 i AZURE oglas](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).
  

