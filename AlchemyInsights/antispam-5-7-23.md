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
# <a name="fix-email-delivery-issues-for-error-code-5723"></a><span data-ttu-id="5a65d-102">Rešavanje problema sa isporukom e-pošte za kôd greške 5.7.23</span><span class="sxs-lookup"><span data-stu-id="5a65d-102">Fix email delivery issues for error code 5.7.23</span></span>

<span data-ttu-id="5a65d-103">Provjerite SPF DNS zapis za vaš domen na javno dostupnom SPF ili DNS kontroloru zapisa na vebu.</span><span class="sxs-lookup"><span data-stu-id="5a65d-103">Verify the SPF DNS record for your domain at a publicly available SPF or DNS record checker on the web.</span></span>

<span data-ttu-id="5a65d-104">Uverite se da poruka nije identifikovana kao bezvredna pošta korporacije Microsoft i da se usmerava kroz [prostor za isporuku visokog rizika](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages).</span><span class="sxs-lookup"><span data-stu-id="5a65d-104">Verify that the outbound message wasn't identified as spam by Microsoft and routed through the [High Risk Delivery Pool](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages).</span></span> <span data-ttu-id="5a65d-105">Poruke u bazenu visokog rizika neće propustiti proveru PRAVOPISA i stoga neće prihvatiti odredišna organizacija e-pošte.</span><span class="sxs-lookup"><span data-stu-id="5a65d-105">Messages in the High Risk Delivery Pool won't pass SPF checks, and therefore won't be accepted by the destination email organization.</span></span>

<span data-ttu-id="5a65d-106">Ako problem potraje, možda ćete morati da se obratite administratoru glavnog računarskog sistema na koji pokušavate da pošaljete e-poruku.</span><span class="sxs-lookup"><span data-stu-id="5a65d-106">If the problem persists, you may need to contact the admin of the mail host to which you are attempting to send email.</span></span> <span data-ttu-id="5a65d-107">Zabeležite detaljnu spoljnu grešku koja je dostupna u poruci za odskok.</span><span class="sxs-lookup"><span data-stu-id="5a65d-107">Make note of the detailed external error available in the bounce message.</span></span> <span data-ttu-id="5a65d-108">Microsoft podrška možda neće moći da pomogne dalje.</span><span class="sxs-lookup"><span data-stu-id="5a65d-108">Microsoft support may not be able to assist further.</span></span>
