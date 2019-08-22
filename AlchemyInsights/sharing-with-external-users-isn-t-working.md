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
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36502245"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a>Otklanjanje problema na deljenje SharePoint sadržaj sa spoljnim korisnicima

Uverite se da spoljni je uključeno deljenje vaše organizacije:
  
1. Idite na na [usluge &amp; programske dodatke stranice u Microsoft 365 admin centru](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), i kliknite na **lokacijama**.
    
2. Uverite se da postavka je pretvorila u „Aktivna”. Ako izaberete „Jedini postojeći spoljnim korisnicima”, uverite se da spoljni korisnik je naveden u centru za admin Microsoft 365.
    
Uverite se eksterno dijeljenje to je uključeno za lokaciju. Za kolekciju klasične lokacija:
  
1. U novu SharePoint admin centru, u lijevom oknu, kliknite na **lokacijama**.
    
2. Izaberite lokaciju ili lokacije, a na glavnoj traci kliknite **Deljenje**.
    
Za lokaciju tima koji pripada grupi programa Office 365 ili lokaciju za komunikaciju:
  
- Ovi novi tipovi lokacije imati isti deljenja postavljanje kao postavke vašeg širom organizacije, ako se širom organizacije postavka omogućava deljenje datoteka pomoću veze koje ne zahtevaju za prijavljivanje. U ovom slučaju, na lokacijama dozvoli deljenje sa novim i postojećim spoljnim korisnicima koji se prijavite. Da biste promenili postavke za pojedine lokacije, koristite novu SharePoint admin centar ili PowerShell. I [Saznajte više](https://go.microsoft.com/fwlink/?linkid=871863).
    
> [!NOTE]
> Spoljni deljenja postavku za bilo koju lokaciju može biti restriktivniji nego što je vaša postavka širom organizacije, ali ne više popustljivog nego postavku širom organizacije. 
  

