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
ms.custom: Adm_O365
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: 20b538846997c021b6e88596a1e8aff401ea935b
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29900900"
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
  

