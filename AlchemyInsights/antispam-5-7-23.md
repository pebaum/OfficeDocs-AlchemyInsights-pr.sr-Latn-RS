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
ms.openlocfilehash: 307b738c40c620d057e68eff7d218c8c9b5eb665
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43676511"
---
# <a name="fix-email-delivery-issues-for-error-code-5723"></a>Rešavanje problema sa isporukom e-pošte za kôd greške 5.7.23

Provjerite SPF DNS zapis za vaš domen na javno dostupnom SPF ili DNS kontroloru zapisa na vebu.

Uverite se da poruka nije identifikovana kao bezvredna pošta korporacije Microsoft i da se usmerava kroz [prostor za isporuku visokog rizika](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages). Poruke u bazenu visokog rizika neće propustiti proveru PRAVOPISA i stoga neće prihvatiti odredišna organizacija e-pošte.

Ako problem potraje, možda ćete morati da se obratite administratoru glavnog računarskog sistema na koji pokušavate da pošaljete e-poruku. Zabeležite detaljnu spoljnu grešku koja je dostupna u poruci za odskok. Microsoft podrška možda neće moći da pomogne dalje.
