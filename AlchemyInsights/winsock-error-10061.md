---
title: 1554 Winsock greška 10061
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1554"
- "9000079"
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: e8f62d97efc937518ef766b45e1747e83b7f99c3
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766183"
---
# <a name="winsock-error-10061"></a>Winsock greška 10061

Ovaj kôd greške znači da Microsoft nije mogao da uspostavi TCP priključak (vezu) sa ciljnim domaćinom. Najverovatniji uzrok ove greške je problem sa konfiguracijom zaštitnog zida. Da biste rešili problem, proverite sledeće postavke:

- Proverite konfiguraciju zaštitnog zida informacijama iz [Microsoft 365 URL adresa i OPSEGA IP adresa](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)

- Ako je greška specifična za razmenu zaštite na mreži (EOP), trebalo je prethodno da budete obavešteni o promeni [IP adresa za zaštitu na mreži Exchange servera](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).

- Proverite da li vaš dobavljač Internet usluga (ISP) ne blokira priključak.

- Proverite pametni host i postavke ciljnog servera u konektorima.

Imajte na umu da Microsoft 365 ne blokira *dolazne* veze na ovaj način.
