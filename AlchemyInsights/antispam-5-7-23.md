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
ms.openlocfilehash: 9c9bc2d04fb8efaa5e75194b4ca09316d24e018e
ms.sourcegitcommit: 07b47d7f3ca191363e6bc84140e8e01524d6f08e
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/24/2019
ms.locfileid: "37682276"
---
# <a name="fix-email-delivery-issues-for-error-code-5723"></a>Rešavanje problema sa isporukom e-pošte za kôd greške 5.7.23

Provjerite SPF DNS zapis za vaš domen na javno dostupnom SPF ili DNS kontroloru zapisa na vebu.

Proverite da li je odlazna poruka identifikovana kao bezvredna u sistemu Office 365 i usmerila se kroz [prostor za isporuku visokog rizika](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages). Poruke u bazenu visokog rizika neće propustiti proveru PRAVOPISA i stoga neće prihvatiti odredišna organizacija e-pošte.

Ako problem potraje, možda ćete morati da se obratite administratoru glavnog računarskog sistema na koji pokušavate da pošaljete e-poruku. Zabeležite detaljnu spoljnu grešku koja je dostupna u poruci za odskok.  Office 365 možda neće moći da pomogne dalje.