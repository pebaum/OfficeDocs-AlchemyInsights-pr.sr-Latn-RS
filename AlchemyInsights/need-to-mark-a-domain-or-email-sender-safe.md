---
title: Potrebno je da označite domen ili pošiljaoca e-pošte bezbedno?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002921"
- "5673"
ms.openlocfilehash: 7dc1576fd61e87b319c7486c59ed125943b4d959
ms.sourcegitcommit: 43acdecef129bfffc8bbe8ebb08fdd581b238a03
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/18/2020
ms.locfileid: "44281185"
---
# <a name="need-to-mark-a-domain-or-email-sender-safe"></a><span data-ttu-id="70721-102">Potrebno je da označite domen ili pošiljaoca e-pošte bezbedno?</span><span class="sxs-lookup"><span data-stu-id="70721-102">Need to mark a domain or email sender safe?</span></span>

- <span data-ttu-id="70721-103">Korišćenje **pouzdanih lista pošiljalaca se ne preporučuje** jer se u vašoj organizaciji otvara bezvredna pošta, Phish i lažno predstavljanje napada.</span><span class="sxs-lookup"><span data-stu-id="70721-103">Use of **safe sender lists is not recommended** since it opens up your organization to spam, phish, and spoofing attacks.</span></span>
- <span data-ttu-id="70721-104">Međutim, ako postoji poslovni uslov, **preporučujemo** da koristite pravila za **[tok pošte](https://docs.microsoft.com/microsoft-365/security/office-365-security/create-safe-sender-lists-in-office-365?view=o365-worldwide#recommended-use-mail-flow-rules)** .</span><span class="sxs-lookup"><span data-stu-id="70721-104">However, if there is a business requirement, we **recommend** using **[Mail Flow Rules](https://docs.microsoft.com/microsoft-365/security/office-365-security/create-safe-sender-lists-in-office-365?view=o365-worldwide#recommended-use-mail-flow-rules)** for this.</span></span> <span data-ttu-id="70721-105">Naše smernice osigurava potvrdu identiteta pošiljaoca (verifikuje se da slanje domena nije lažno).</span><span class="sxs-lookup"><span data-stu-id="70721-105">Our guidance ensures sender authentication (verifies sending domain is not being spoofed).</span></span> <span data-ttu-id="70721-106">**Napomena**: ne preporučujemo upravljanje lažnim imali greške pomoću liste pouzdanih pošiljalaca, zato što izuzeci od filtriranja bezvredne pošte mogu da otvore vašu organizaciju na bezbednosne napade.</span><span class="sxs-lookup"><span data-stu-id="70721-106">**Note**: We don't recommend managing false positives by using safe sender lists, because exceptions to spam filtering can open your organization to security attacks.</span></span> <span data-ttu-id="70721-107">Ako vaši korisnici (e) primaju poruke koje su nepravilno označene kao bezvredne ili neželjene e-pošte, **[Prijavite poruke i datoteke korporaciji Microsoft](https://protection.office.com/reportsubmission)**.</span><span class="sxs-lookup"><span data-stu-id="70721-107">If your user(s) receive messages incorrectly marked as spam or junk email, please **[Report messages and files to Microsoft](https://protection.office.com/reportsubmission)**.</span></span>
- <span data-ttu-id="70721-108">Pouzdani pošiljaoci u programu Outlook, dozvoljenih lista pošiljalaca ili dozvoljena lista domena u smernicama za borbu protiv bezvredne pošte **treba izbegavati** zato što pošiljaoci zaobilaze sve bezvredne pošte, spore i Phish zaštite i potvrdu identiteta pošiljaoca (SPF, dkim, dmark).</span><span class="sxs-lookup"><span data-stu-id="70721-108">Safe Senders in Outlook, Allowed sender list, or allowed domain list in anti-spam policies **should be avoided** because senders bypass all spam, spoof, and phish protection, and sender authentication (SPF, DKIM, DMARC).</span></span> <span data-ttu-id="70721-109">Ovaj metod je najbolje koristiti samo za privremeno testiranje.</span><span class="sxs-lookup"><span data-stu-id="70721-109">This method is best used for temporary testing only.</span></span>
