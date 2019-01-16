---
title: 1554 Winsock greška 10061
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: 96a9cfd11941158ddf13655c74974e3eb800e570
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/15/2019
ms.locfileid: "28309554"
---
# <a name="winsock-error-10061"></a>Winsock greška 10061

Ovaj kôd greške znači da Office 365 nije mogao da uspostavi TCP priključak (veza) sa meta domaćin. Najverovatniji uzrok ove greške je problem u konfiguraciji vatrozida. Da biste rešili problem, pogledajte ove postavke:
  
- Proverite konfiguraciju zaštitnog zida sa informacijama u [Office 365 URL adrese i opsega IP adresa](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)
    
- Ako greška je specifična za Exchange Online zaštitu (EOP), trebalo bi da ste prethodno obavešteni do promene na [Exchange Online zaštitu IP adrese](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).
    
- Uverite se da je tvoj dobavljač Internet usluga (ISP) ne blokira port.
    
- Provjerite pametan hosta i ciljnih postavke servera u tvoj konektori.
    
Imajte na umu da Office 365 ne blokira *dolazne* veze na ovaj način. 
  

