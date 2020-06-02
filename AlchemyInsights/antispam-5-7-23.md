---
title: Antispam - 5.7.23
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3156"
- "9001196"
ms.openlocfilehash: 8122b409a731a5fcc46c718aff1eeda07e26890b
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506457"
---
# <a name="fix-email-delivery-issues-for-error-code-5723"></a>Rešavanje problema sa isporukom e-pošte za kôd greške 5.7.23

Provjerite SPF DNS zapis za vaš domen na javno dostupnom SPF ili DNS kontroloru zapisa na vebu.

Uverite se da poruka nije identifikovana kao bezvredna pošta korporacije Microsoft i da se usmerava kroz [prostor za isporuku visokog rizika](https://docs.microsoft.com/microsoft-365/security/office-365-security/high-risk-delivery-pool-for-outbound-messages). Poruke u bazenu visokog rizika neće propustiti proveru PRAVOPISA i stoga neće prihvatiti odredišna organizacija e-pošte.

Ako problem potraje, možda ćete morati da se obratite administratoru glavnog računarskog sistema na koji pokušavate da pošaljete e-poruku. Zabeležite detaljnu spoljnu grešku koja je dostupna u poruci za odskok. Microsoft podrška možda neće moći da pomogne dalje.
