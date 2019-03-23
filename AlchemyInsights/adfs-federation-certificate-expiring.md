---
title: ADFS Federacije istek certifikata
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/8/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 26a7eebb-1424-4ddc-a123-af1cc94bc40f
ms.openlocfilehash: 518261787b1b0df99ee7b3dc3e51dec70e4373bc
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/22/2019
ms.locfileid: "30755168"
---
# <a name="adfs-federation-certificate-expiring"></a>ADFS Federacije istek certifikata

Da biste riješili taj problem, slijedite ove korake:
  
1. Instalirati na Microsoft Azure Active Directory modul za Windows PowerShell na računaru (ako modul nije već instaliran). Da biste ovo uradili, idite na [Upravljanje azurno AD koristeći Windows PowerShell](https://aka.ms/aadposh).
    
2. Sledite korake u na „Scenario 1: AD FS token potpisivanje certifikat istekao” delu [„Postoji problem sa pristupom na lokaciji” greška iz AD FS kada savezni korisnik potpiše Office 365, Azure, ili Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).
    
3. Sledite korake u [Kako da ažurirate ili popravite postavke savezni domena u Office 365, Azure, ili Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).
    
    Da biste saznali više o obnavlja certifikate Federacije, vidim [obnova Federacije certifikate za Office 365 i Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).
    

