---
title: Identifikujte eksterni mail špedicije na Poštanske sandučiće u evidencije nadgledanja
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1369
ms.assetid: ''
ms.openlocfilehash: 7fb2c161c558a7eb961f86ca2b86e33750d902fd
ms.sourcegitcommit: ffe2f489b1ac3aae62aa784c959da6a41c3261eb
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/17/2019
ms.locfileid: "31909525"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a><span data-ttu-id="ddf24-102">Određivanje kada eksterni mail špedicije je podešen na Poštanske sandučiće</span><span class="sxs-lookup"><span data-stu-id="ddf24-102">Identify when external email forwarding is configured on mailboxes</span></span>

<span data-ttu-id="ddf24-103">Kada korisnik podešava eksterni mail špedicije na poštansko sanduče, aktivnost je revizije u sklopu cmdlet na **Setu-poštansko sanduče** .</span><span class="sxs-lookup"><span data-stu-id="ddf24-103">When a user configures external email forwarding on a mailbox, the activity is audited as part of the **Set-Mailbox** cmdlet.</span></span> <span data-ttu-id="ddf24-104">Možete da vidite aktivnosti koristeći pretraživanje evidencija nadgledanja u bezbednosti & usklađenosti centar.</span><span class="sxs-lookup"><span data-stu-id="ddf24-104">You can see the activity using audit log search in the Security & Compliance Center.</span></span>

1. <span data-ttu-id="ddf24-105">Prijavite se za [Office 365 bezbednosni & usklađenosti centar](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="ddf24-105">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="ddf24-106">Izaberite **pretragu i istrage** i **Pretraživanje evidencije nadgledanja**.</span><span class="sxs-lookup"><span data-stu-id="ddf24-106">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

3. <span data-ttu-id="ddf24-107">Izaberite opseg datuma u poljima **datum početka** i **datum završetka** .</span><span class="sxs-lookup"><span data-stu-id="ddf24-107">Select the date range in the **Start date** and **End date** fields.</span></span> <span data-ttu-id="ddf24-108">Ne morate navesti korisničko ime.</span><span class="sxs-lookup"><span data-stu-id="ddf24-108">You don't need to specify a username.</span></span> <span data-ttu-id="ddf24-109">Provjerite **aktivnosti** polje postavljeno na **Prikaz rezultata za sve aktivnosti**.</span><span class="sxs-lookup"><span data-stu-id="ddf24-109">Verify the **Activities** field is set to **Show results for all activities**.</span></span>

4. <span data-ttu-id="ddf24-110">Kliknite na dugme **za pretragu**.</span><span class="sxs-lookup"><span data-stu-id="ddf24-110">Click **Search**.</span></span>

<span data-ttu-id="ddf24-111">Na listi rezultata kliknite **Rezultati filtriranja** i upišite **Setu-poštansko sanduče** u okviru aktivnosti filtera.</span><span class="sxs-lookup"><span data-stu-id="ddf24-111">In the results, click **Filter Results** and type **Set-Mailbox** in the activity filter box.</span></span> <span data-ttu-id="ddf24-112">Izaberite zapis o reviziji u rezultatima.</span><span class="sxs-lookup"><span data-stu-id="ddf24-112">Select an audit record in the results.</span></span> <span data-ttu-id="ddf24-113">U Potpaleta u **detalje** , kliknite na " **više informacija**".</span><span class="sxs-lookup"><span data-stu-id="ddf24-113">In the **Details** flyout, click **More information**.</span></span> <span data-ttu-id="ddf24-114">Morate da vidi detalje o svakom zapisu nadgledanja utvrditi ako se odnosi aktivnost u e-mail na špedicije.</span><span class="sxs-lookup"><span data-stu-id="ddf24-114">You have to look at the details of each audit record to determine if the activity is related to email forwarding.</span></span>

- <span data-ttu-id="ddf24-115">**ObjectId**: pseudonim vrednost poštanskog sandučeta izmene.</span><span class="sxs-lookup"><span data-stu-id="ddf24-115">**ObjectId**: The alias value of the mailbox that was modified.</span></span>

- <span data-ttu-id="ddf24-116">**Parametri**: _ForwardingSmtpAddress_ ukazuje na adresu e-pošte meta.</span><span class="sxs-lookup"><span data-stu-id="ddf24-116">**Parameters**: _ForwardingSmtpAddress_ indicates the target email address.</span></span>

- <span data-ttu-id="ddf24-117">**ID korisnika**: korisnika koji je podešen email špedicije na poštansko sanduče u polju **ObjectId** .</span><span class="sxs-lookup"><span data-stu-id="ddf24-117">**UserId**: The user who configured email forwarding on the mailbox in the **ObjectId** field.</span></span>

<span data-ttu-id="ddf24-118">Za više informacija, pogledajte [Determining ko podešavanje email Špedicija za poštansko sanduče](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).</span><span class="sxs-lookup"><span data-stu-id="ddf24-118">For more information, see [Determining who set up email forwarding for a mailbox](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).</span></span>
