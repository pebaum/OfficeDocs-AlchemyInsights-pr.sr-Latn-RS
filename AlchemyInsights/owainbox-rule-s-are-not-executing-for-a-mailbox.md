---
title: 1332 OWA - poštanskom sandučetu pravila se ne izvršava za poštansko sanduče
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1332
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: 9e782faa59bb9a16c271f7c46c79635961e88aed
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/22/2019
ms.locfileid: "30784355"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a>Pravilo za Prispjelu poštu ne radi kao što se očekivalo

Provjerite sljedeće postavke:
  
- Poruku možete preusmerena, prosleđivanja ili odgovoreno da automatski na osnovu pravila prijemnog samo jedan put. Preusmeravanje pravilo (pravilo za Prispjelu poštu ili protok pravilo za poštu, poznat i kao transportni pravilo) možete dodati najviše 10 špedicije primaoci poruke. Za više informacija, pogledajte [dnevnik, Transport, i poštanskom sandučetu pravilo ograničenja](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).
    
- Poštanskom sandučetu pravila ne funkcionišu u poštansko sanduče na alternativni ugojena. Za više informacija o poštanskom sandučetu alternativni ugojena, vidim [poštansko sanduče alternativni ugojena](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).
    
Da biste rešili ove probleme, vidim [KB 2829319](https://support.microsoft.com/kb/2829319).
  
Ako prethodna pitanja ne odnose, pokrenite dijagnostiku izveštaj prijemnog pravilo pre nego što si eskalirati problem na lokaciji Microsoft Support:
  
1. Otvoriti poštansko sanduče u programu Outlook na Webu, i kliknite na dugme **Postavke** \> **Opcije** \> **Organizuj email** \> **pravila prijemnog**.
    
2. U donjem delu stranice, izaberite opciju **Ako vaša pravila ne rade kliknite ovde da biste generisali dijagnostički izveštaj**.
    

