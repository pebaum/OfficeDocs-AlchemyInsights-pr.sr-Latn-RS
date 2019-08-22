---
title: Identifikujte prijemnog pravilo aktivnost u evidencije nadgledanja
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1368"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 1201a625948743cacfaa58410abeb4108ed2eb56
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36539187"
---
# <a name="identify-inbox-rule-activity-in-audit-logs"></a><span data-ttu-id="d5442-102">Identifikujte prijemnog pravilo aktivnost u evidencije nadgledanja</span><span class="sxs-lookup"><span data-stu-id="d5442-102">Identify inbox rule activity in audit logs</span></span>

<span data-ttu-id="d5442-103">Pretraživanje evidencije nadgledanja u Office 365 bezbednosti & usklađenosti centar možete koristiti da biste pregledali prijemnog pravilo događaja (kreiranje, menjanje i brisanje pravila prijemnog).</span><span class="sxs-lookup"><span data-stu-id="d5442-103">You can use audit log search in the Office 365 Security & Compliance Center to view inbox rule events (creating, modifying, and deleting inbox rules).</span></span>

1. <span data-ttu-id="d5442-104">Prijavite se za [Office 365 bezbednosni & usklađenosti centar](https://protection.office.com/).</span><span class="sxs-lookup"><span data-stu-id="d5442-104">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/).</span></span>

2. <span data-ttu-id="d5442-105">Idi na **pretragu** > stranicu**za pretraživanje evidencije nadgledanja** .</span><span class="sxs-lookup"><span data-stu-id="d5442-105">Go to the **Search** > **Audit log search** page.</span></span>

3. <span data-ttu-id="d5442-106">Izaberite opseg datuma u poljima **datum početka** i **datum završetka** .</span><span class="sxs-lookup"><span data-stu-id="d5442-106">Select the date range in the **Start date** and **End date** fields.</span></span>

4. <span data-ttu-id="d5442-107">U okviru **Aktivnosti Exchange poštansko sanduče**, provjerite **aktivnosti** polje postavljeno na **New-InboxRule Kreiraj/izmeni/omogući/onemogući pravilo za Prispjelu poštu**.</span><span class="sxs-lookup"><span data-stu-id="d5442-107">Under **Exchange Mailbox Activities**, verify the **Activities** field is set to **New-InboxRule Create/modify/enable/disable inbox rule**.</span></span>

5. <span data-ttu-id="d5442-108">Kliknite na dugme **za pretragu**.</span><span class="sxs-lookup"><span data-stu-id="d5442-108">Click **Search**.</span></span>

<span data-ttu-id="d5442-109">Na listi rezultata izaberite zapis o reviziji.</span><span class="sxs-lookup"><span data-stu-id="d5442-109">In the results, select an audit record.</span></span> <span data-ttu-id="d5442-110">U Potpaleta na detalje, kliknite **Više informacija**.</span><span class="sxs-lookup"><span data-stu-id="d5442-110">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="d5442-111">Informacije o postavkama pravila prijemnog je prikazan u polju **parametre** .</span><span class="sxs-lookup"><span data-stu-id="d5442-111">Information about the inbox rule settings is displayed in the **Parameters** field.</span></span>

<span data-ttu-id="d5442-112">Za više informacija, pogledajte [Determining ako je korisnik kreirao pravilo za Prispjelu poštu](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span><span class="sxs-lookup"><span data-stu-id="d5442-112">For more information, see [Determining if a user created an inbox rule](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span></span>
