---
title: Otvoriti pomoću programa Explorer ne radi
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 12/10/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: b8f07022-69fe-4112-a2f6-d3a6cedb966c
ms.openlocfilehash: f788c3c626cdeb19970edb59563c59eea60e2992
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29906818"
---
# <a name="open-with-explorer-isnt-working"></a>Otvoriti pomoću programa Explorer ne radi

Ako **Otvori pomoću programa Explorer** ili **prikaz u datoteku Explorer** ne radi se WebClient servis je podešen da **radi** prateći korake ispod. Na primer, to može potrajati dugo vremena da biste otvorili biblioteku SharePoint ili OneDrive kada usluga nije pokrenuta. 
  
1. U polje za pretragu Windows, tip pokrenuli, izaberite pokreni aplikaciju na radnoj površini, upišite services.msc i zatim izaberite **Enter**.
    
2. Pomerite se do WebClient servis i proveri **Status** kolone. Ako WebClient status usluga nije **pokrenuta**, kliknite dvaput na uslugu, kliknite na dugme **Start**i onda kliknite na **OK**. Omogućite uslugu, ako je potrebno, tako što ćete izabrati ili **ručno** ili **automatski** u okviru **Tip pokretanja** . 
    
> [!NOTE]
> Rešavanje problema sa otvaranjem u datoteku programa Explorer, potražite [otvoren u Explorer](https://go.microsoft.com/fwlink/?linkid=871665). Istražite Prevod kao bolju alternativu: [SharePoint sinhronizacije datoteke sa novom klijentu sinhronizaciju OneDrive](https://go.microsoft.com/fwlink/?linkid=871666). 
  

