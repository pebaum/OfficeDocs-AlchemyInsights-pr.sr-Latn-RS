---
title: Deljenje sa spoljnim korisnicima ne radi
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 5/18/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: d4c8fc75ff8db2319b88a20bea9b3ee661f2e36e
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/18/2019
ms.locfileid: "36502245"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a>Rešavanje problema sa deljenjem SharePoint sadržaja sa spoljnim korisnicima

Proverite da li je uključeno zajedničko deljenje za vašu organizaciju:
  
1. Idite na [stranicu " &amp; programski dodaci za usluge" u Microsoft 365 admin Center](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns)i izaberite stavku **lokacije**.
    
2. Proverite da li je postavka uključena u "uključeno". Ako je izabrano "samo postojeći spoljni korisnici", uverite se da je spoljni korisnik naveden u Microsoft 365 admin Center.
    
Uverite se da je spoljna podela uključena za lokaciju. Za klasičnu kolekciju lokacija:
  
1. U novom SharePoint administratoru centra, u levom oknu izaberite stavku **lokacije**.
    
2. Izaberite lokaciju ili lokacije i na glavnoj traci kliknite na dugme **Deljenje**.
    
Za lokaciju tima koja pripada Office 365 grupi ili lokaciji za komunikaciju:
  
- Ovi novi tipovi lokacija imaju istu postavku deljenja kao i postavke za celu organizaciju, osim ako postavka za celu organizaciju ne dozvoljava deljenje datoteka pomoću veza koje ne zahtevaju prijavljivanje. U ovom slučaju, lokacije omogućavaju deljenje sa novim i postojećim spoljnim korisnicima koji se prijave. Da biste promenili postavke za određene lokacije, koristite novi SharePoint admin Center ili PowerShell. [Saznajte više](https://go.microsoft.com/fwlink/?linkid=871863).
    
> [!NOTE]
> Postavka spoljnog deljenja za svaku lokaciju može da bude restriktivnija od postavke za celu organizaciju, ali ne i veća od postavke za celu organizaciju. 
  

