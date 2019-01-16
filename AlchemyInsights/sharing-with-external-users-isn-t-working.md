---
title: Deljenje sa spoljnim korisnicima ne radi
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 5/18/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: 305b3891e6c83e27b5c55c13757640e6e9d51a81
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/15/2019
ms.locfileid: "28310046"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a>Otklanjanje problema na deljenje SharePoint sadržaj sa spoljnim korisnicima

Uverite se da spoljni je uključeno deljenje vaše organizacije:
  
1. Idite na na [usluge &amp; programske dodatke stranice u centru za administraciju sistema Office 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), i kliknite na **lokacijama**.
    
2. Uverite se da postavka je pretvorila u „Aktivna”. Ako izaberete „Jedini postojeći spoljnim korisnicima”, uverite se da spoljni korisnik je naveden u centru za administraciju sistema Office 365.
    
Uverite se eksterno dijeljenje to je uključeno za lokaciju. Za kolekciju klasične lokacija:
  
1. U klasični SharePoint admin centru, u lijevom oknu, kliknite **kolekcije**.
    
2. Izaberite lokaciju ili lokacije, a na glavnoj traci kliknite **Deljenje**.
    
Za lokaciju tima koji pripada grupi programa Office 365 ili lokaciju za komunikaciju:
  
- Ovi novi tipovi lokacije imati isti deljenja postavljanje kao postavke vašeg širom organizacije, ako se širom organizacije postavka omogućava deljenje datoteka pomoću veze koje ne zahtevaju za prijavljivanje. U ovom slučaju, na lokacijama dozvoli deljenje sa novim i postojećim spoljnim korisnicima koji se prijavite. Da biste promenili postavke za pojedine lokacije, koristite novu SharePoint admin centar (pregled) ili PowerShell. I [Saznajte više](https://go.microsoft.com/fwlink/?linkid=871863).
    
> [!NOTE]
> Spoljni deljenja postavku za bilo koju lokaciju može biti restriktivniji nego što je vaša postavka širom organizacije, ali ne više popustljivog nego postavku širom organizacije. 
  

