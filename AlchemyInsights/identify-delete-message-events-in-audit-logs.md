---
title: Identifikujte brisanje poruka događaja u evidencije nadgledanja
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1370
ms.assetid: ''
ms.openlocfilehash: 93f8a192af6e689e2b2d04013f35b8da2b69e607
ms.sourcegitcommit: ffe2f489b1ac3aae62aa784c959da6a41c3261eb
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/17/2019
ms.locfileid: "31909521"
---
# <a name="audit-logs-for-deleted-email-messages"></a><span data-ttu-id="4c5cc-102">Evidencije nadgledanja za izbrisane e-poruka</span><span class="sxs-lookup"><span data-stu-id="4c5cc-102">Audit logs for deleted email messages</span></span>

<span data-ttu-id="4c5cc-103">Počev od januara 2019, Microsoft je uključivanje Korektura poštanskog sandučeta evidentiranje po podrazumevanoj vrednosti.</span><span class="sxs-lookup"><span data-stu-id="4c5cc-103">Starting in January 2019, Microsoft is turning on mailbox audit logging by default.</span></span> <span data-ttu-id="4c5cc-104">U suprotnom, da biste pregledali brisanje poruka događaja za određenog korisnika, potrebno je da ručno omogućite brisanje radnje za nadzor.</span><span class="sxs-lookup"><span data-stu-id="4c5cc-104">Otherwise, to review delete message events for a specific user, you need to manually enable the delete actions for auditing.</span></span> <span data-ttu-id="4c5cc-105">Ako poštansko sanduče nadgledanja vođenja evidencije je već omogućena za vašu organizaciju ili za određenog korisnika, sledite korake ispod.</span><span class="sxs-lookup"><span data-stu-id="4c5cc-105">If mailbox audit logging is already enabled for your organization or for the specific user, follow the steps below.</span></span>

1. <span data-ttu-id="4c5cc-106">Prijavite se za [Office 365 bezbednosni & usklađenosti centar](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="4c5cc-106">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="4c5cc-107">Izaberite **pretragu i istrage** i **Pretraživanje evidencije nadgledanja**.</span><span class="sxs-lookup"><span data-stu-id="4c5cc-107">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

3. <span data-ttu-id="4c5cc-108">Izaberite opseg datuma u poljima **datum početka** i **datum završetka** .</span><span class="sxs-lookup"><span data-stu-id="4c5cc-108">Select the date range in the **Start date** and **End date** fields.</span></span> <span data-ttu-id="4c5cc-109">Navedite korisničko ime za korisnika kojeg želite da istražite (korisnika koji su izbrisane stavke).</span><span class="sxs-lookup"><span data-stu-id="4c5cc-109">Specify username for the user that you want to investigate (the user who deleted the items).</span></span> <span data-ttu-id="4c5cc-110">U polju **aktivnosti** , izaberite **izbrisane poruke iz fascikle izbrisane stavke** i **Moved poruke u fasciklu izbrisane stavke**.</span><span class="sxs-lookup"><span data-stu-id="4c5cc-110">In the **Activities** field, select **Deleted messages from Deleted Items folder** and **Moved messages to Deleted Items folder**.</span></span>

4. <span data-ttu-id="4c5cc-111">Kliknite na dugme **za pretragu**.</span><span class="sxs-lookup"><span data-stu-id="4c5cc-111">Click **Search**.</span></span>

<span data-ttu-id="4c5cc-112">Na listi rezultata izaberite zapis o reviziji.</span><span class="sxs-lookup"><span data-stu-id="4c5cc-112">In the results, select an audit record.</span></span> <span data-ttu-id="4c5cc-113">U Potpaleta na detalje, kliknite **Više informacija**.</span><span class="sxs-lookup"><span data-stu-id="4c5cc-113">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="4c5cc-114">Dodatne informacije o izbrisanih stavki (na primer, temu i lokaciju stavke kada je izbrisana) je prikazan u polju **AffectedItems** .</span><span class="sxs-lookup"><span data-stu-id="4c5cc-114">Additional information about the deleted item (for example, the subject line and the location of the item when it was deleted) is displayed in the **AffectedItems** field.</span></span> <span data-ttu-id="4c5cc-115">Svojstvo **ClientInfoString** će prikazati ako brisanje je došlo u programu Outlook, Outlook na Webu (poznatog i kao Outlook Web App), ili bilo koji drugi uređaj.</span><span class="sxs-lookup"><span data-stu-id="4c5cc-115">The **ClientInfoString** property will show if the deletion occurred in Outlook, Outlook on the web (formerly known as Outlook Web App), or any other device.</span></span>

<span data-ttu-id="4c5cc-116">Za više informacija, pogledajte [Determining ko podešavanje email Špedicija za poštansko sanduče](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).</span><span class="sxs-lookup"><span data-stu-id="4c5cc-116">For more information, see [Determining who set up email forwarding for a mailbox](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).</span></span>

<span data-ttu-id="4c5cc-117">**Napomena**: te nije moguće preuzeti izbrisanih stavki pomoću funkcije evidencije nadgledanja.</span><span class="sxs-lookup"><span data-stu-id="4c5cc-117">**Note**: You can't retrieve deleted items using the audit log feature.</span></span> <span data-ttu-id="4c5cc-118">Da biste preuzeli izbrisane poruke u programu Outlook na Webu, vidim da [spasi izbrisane stavke u programu Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).</span><span class="sxs-lookup"><span data-stu-id="4c5cc-118">To retrieve deleted messages in Outlook on the web, see [Recover deleted items in Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).</span></span>
