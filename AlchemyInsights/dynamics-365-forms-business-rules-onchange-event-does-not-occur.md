---
title: Dynamics 365 obrasci poslovni pravila-pravilo poslovanja nije otpuštanje iz obrasca
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1926"
- "6200018"
ms.openlocfilehash: cbdedd2c5fcf5517243e60e36d86479d6c3f7814
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/25/2019
ms.locfileid: "36529033"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a>Događaj OnChange se ne pojavljuje ako je polje programsko promenjeno

Događaj " *OnChange* " se ne pojavljuje ako je polje programsko promenjeno koristeći *atribut.* metod [setValue](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) . Ako želite da se Rukovaoci događajima za događaj *OnChange* pokrenu nakon što podesite vrednost morate da koristite *formkontekst. podaci. atribut entiteta.* metod [Vatonpromene](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) u vašem kodu.

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
