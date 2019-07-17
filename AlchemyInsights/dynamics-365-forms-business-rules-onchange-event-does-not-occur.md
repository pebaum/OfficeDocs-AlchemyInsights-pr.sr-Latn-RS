---
title: Dynamics 365 formira pravila poslovanja - poslovno pravilo ne pucati za obrazac
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1926"
- "6200018"
ms.openlocfilehash: 4ade8d2f68b465298e2d6efff3eef4f04f25c3bf
ms.sourcegitcommit: a413a0e27ef4ab8c484fa9fccff8bbef381c8b96
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 07/16/2019
ms.locfileid: "35748623"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a>Događaj OnChange ne dolazi ako polje je promenjeno programsko

Događaj *OnChange* ne dolazi ako je promeniti polje programsko koristeći se *atributa.* [setValue](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) metod. Ako želite događajem za događaj *OnChange* da pokrenete nakon što ste postavili vrednost morate koristiti u *atribut formContext.data.entity.* [fireOnchange](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) metod u kodu.

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
