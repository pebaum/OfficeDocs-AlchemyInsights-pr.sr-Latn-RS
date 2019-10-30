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
ms.openlocfilehash: 3cdd2175083e864b3bffc57a70bb6c6220843fad
ms.sourcegitcommit: defe2c412567b596fa8c3ab52111bde712ebb314
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/29/2019
ms.locfileid: "37769353"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a><span data-ttu-id="2b6be-102">Događaj OnChange se ne pojavljuje ako je polje programsko promenjeno</span><span class="sxs-lookup"><span data-stu-id="2b6be-102">OnChange event does not occur if the field is changed programmatically</span></span>

<span data-ttu-id="2b6be-103">Događaj " *OnChange* " se ne pojavljuje ako je polje programsko promenjeno koristeći *atribut.* metod [setValue](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) .</span><span class="sxs-lookup"><span data-stu-id="2b6be-103">The *OnChange* event does not occur if the field is changed programmatically using the *attribute.*[setValue](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) method.</span></span> <span data-ttu-id="2b6be-104">Ako želite da se Rukovaoci događajima za događaj *OnChange* pokrenu nakon što podesite vrednost morate da koristite *formkontekst. podaci. atribut entiteta* [fireonpromene](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) metoda u vašem kodu.</span><span class="sxs-lookup"><span data-stu-id="2b6be-104">If you want event handlers for the *OnChange* event to run after you set the value you must use the *formContext.data.entity attribute* [fireOnchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) method in your code.</span></span>

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
