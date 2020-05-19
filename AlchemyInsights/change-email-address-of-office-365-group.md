---
title: Promena e-adrese Microsoft 365 grupe
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "4704"
ms.openlocfilehash: 0a07e6279f533a4c26a4e90c10651421a5df8860
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/27/2020
ms.locfileid: "44283259"
---
# <a name="change-email-address-of-an-microsoft-365-group"></a>Promena e-adrese Microsoft 365 grupe

E-adresu Microsoft 365 grupe možete da promenite pomoću administratorskog centra. Samo izaberite grupu i izaberite @edit e-adresu.

Takođe možete koristiti sledeću komandu "EXO PowerShell" da biste promenili primarnu SMTP adresu Microsoft 365 grupe:

Set-UnifiedGroup <Group Name> -PrimarySmtpAddress<new SMTP Address>

Primer:

```
    Set-UnifiedGroup Marketing -PrimarySmtpAddress marketing@contoso.com
```
