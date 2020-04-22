---
title: Identifikovanje spoljnog prosleđivanja e-pošte na poštanskim sandučićima u evidencijama nadgledanja
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1369"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 156fd0044cdc42230ace0a5db16f49af572bb6fa
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716474"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a><span data-ttu-id="34605-102">Prepoznavanje kada je spoljna Prosleđivanje e-pošte konfigurisana u poštanskim sandučićima</span><span class="sxs-lookup"><span data-stu-id="34605-102">Identify when external email forwarding is configured on mailboxes</span></span>

<span data-ttu-id="34605-103">Kada Microsoft 365 korisnik konfiguriše spoljnu Prosleđivanje e-pošte u poštanskom sandučetu, aktivnost se nadgleda kao deo " **Set-poštansko sanduče** " cmd.</span><span class="sxs-lookup"><span data-stu-id="34605-103">When a Microsoft 365 user configures external email forwarding on a mailbox, the activity is audited as part of the **Set-Mailbox** cmdlet.</span></span> <span data-ttu-id="34605-104">Aktivnost možete da vidite koristeći pretragu za evidenciju nadzora u centru za bezbednost &.</span><span class="sxs-lookup"><span data-stu-id="34605-104">You can see the activity using audit log search in the Security & Compliance Center.</span></span>

1. <span data-ttu-id="34605-105">Prijavite se na [Microsoft 365 Security & centar za usaglašavanje](https://protection.office.com/).</span><span class="sxs-lookup"><span data-stu-id="34605-105">Log in to the [Microsoft 365 Security & Compliance Center](https://protection.office.com/).</span></span>

2. <span data-ttu-id="34605-106">Idite na stranicu za**pretraživanje evidencije nadgledanja** **pretraživanja** > .</span><span class="sxs-lookup"><span data-stu-id="34605-106">Go to the **Search** > **Audit log search** page.</span></span>

3. <span data-ttu-id="34605-107">Izaberite opseg datuma u poljima **Početni datum** i **Krajnji datum** .</span><span class="sxs-lookup"><span data-stu-id="34605-107">Select the date range in the **Start date** and **End date** fields.</span></span> <span data-ttu-id="34605-108">Nije potrebno da navedete korisničko ime.</span><span class="sxs-lookup"><span data-stu-id="34605-108">You don't need to specify a username.</span></span> <span data-ttu-id="34605-109">Proverite da li je polje **aktivnosti** podešeno da **prikazuje rezultate za sve aktivnosti**.</span><span class="sxs-lookup"><span data-stu-id="34605-109">Verify the **Activities** field is set to **Show results for all activities**.</span></span>

4. <span data-ttu-id="34605-110">Kliknite na dugme **Pretraži**.</span><span class="sxs-lookup"><span data-stu-id="34605-110">Click **Search**.</span></span>

<span data-ttu-id="34605-111">U rezultatima, u okviru za filter aktivnosti kliknite na dugme **Filtriraj rezultate** i otkucajte **Set-poštansko sanduče** .</span><span class="sxs-lookup"><span data-stu-id="34605-111">In the results, click **Filter Results** and type **Set-Mailbox** in the activity filter box.</span></span> <span data-ttu-id="34605-112">Izaberite zapis nadgledanja u rezultatima.</span><span class="sxs-lookup"><span data-stu-id="34605-112">Select an audit record in the results.</span></span> <span data-ttu-id="34605-113">Kliknite na dugme " **više informacija**" u prozoru " **Detalji** ".</span><span class="sxs-lookup"><span data-stu-id="34605-113">In the **Details** flyout, click **More information**.</span></span> <span data-ttu-id="34605-114">Morate da pogledate detalje svakog zapisa nadgledanja da biste utvrdili da li je aktivnost povezana sa prosleđivanjem e-pošte.</span><span class="sxs-lookup"><span data-stu-id="34605-114">You have to look at the details of each audit record to determine if the activity is related to email forwarding.</span></span>

- <span data-ttu-id="34605-115">**ID objekta**: vrednost pseudonima koja je izmenjena.</span><span class="sxs-lookup"><span data-stu-id="34605-115">**ObjectId**: The alias value of the mailbox that was modified.</span></span>

- <span data-ttu-id="34605-116">**Parametri**: da bi se na njemu naznačila ciljna e _-Adresa._</span><span class="sxs-lookup"><span data-stu-id="34605-116">**Parameters**: _ForwardingSmtpAddress_ indicates the target email address.</span></span>

- <span data-ttu-id="34605-117">**ID korisnika**: korisnik koji je podesio Prosleđivanje e-pošte na poštansko sanduče u polju **ID objekta** .</span><span class="sxs-lookup"><span data-stu-id="34605-117">**UserId**: The user who configured email forwarding on the mailbox in the **ObjectId** field.</span></span>

<span data-ttu-id="34605-118">Više informacija potražite u članku [Utvrđivanje ko je podesio Prosleđivanje e-pošte za poštansko sanduče](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).</span><span class="sxs-lookup"><span data-stu-id="34605-118">For more information, see [Determining who set up email forwarding for a mailbox](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).</span></span>
