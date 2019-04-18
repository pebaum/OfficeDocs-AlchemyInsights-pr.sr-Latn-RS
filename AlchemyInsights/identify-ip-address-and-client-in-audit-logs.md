---
title: Identifikovati IP adresu i klijent u evidencije nadgledanja
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1367
ms.assetid: ''
ms.openlocfilehash: 7e30a638de5926aa11b8ae637613a48076d7bdc9
ms.sourcegitcommit: ffe2f489b1ac3aae62aa784c959da6a41c3261eb
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/17/2019
ms.locfileid: "31909523"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a><span data-ttu-id="c2983-102">Identifikovati IP adresu i klijent u evidencije nadgledanja</span><span class="sxs-lookup"><span data-stu-id="c2983-102">Identify IP address and client in audit logs</span></span>

<span data-ttu-id="c2983-103">IP adresu koja odgovara aktivnost korisnik ili administrator je prikazan u evidencije nadgledanja.</span><span class="sxs-lookup"><span data-stu-id="c2983-103">The IP address that corresponds to an activity by a user or administrator is shown in the Audit Logs.</span></span> <span data-ttu-id="c2983-104">Informacije o klijentu se takođe evidentira.</span><span class="sxs-lookup"><span data-stu-id="c2983-104">The client information is also logged.</span></span> <span data-ttu-id="c2983-105">Evo ti korake za identifikaciju takve informacije</span><span class="sxs-lookup"><span data-stu-id="c2983-105">Here are the steps to identifying such information</span></span>

1. <span data-ttu-id="c2983-106">Prijavite se za [Office 365 bezbednosni & usklađenosti centar](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="c2983-106">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="c2983-107">Izaberite **pretragu i istrage** i **Pretraživanje evidencije nadgledanja**.</span><span class="sxs-lookup"><span data-stu-id="c2983-107">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

   <span data-ttu-id="c2983-108">Ako ste zainteresovani za određene aktivnosti, izaberite je sa liste **aktivnosti** .</span><span class="sxs-lookup"><span data-stu-id="c2983-108">If you're interested in a specific activity, select it from **Activities** list.</span></span> <span data-ttu-id="c2983-109">U suprotnom, sve aktivnosti će biti vraćen za izabranog korisnika (podrazumevana postavka).</span><span class="sxs-lookup"><span data-stu-id="c2983-109">If not, all activities will be returned for the selected user (default setting).</span></span>

   <span data-ttu-id="c2983-110">**Napomena**: određene aktivnosti možda neće biti dostupna u meniju **aktivnosti** ; Međutim, one revizije stavki će biti vraćena ako je **Pokazati rezultate za sve aktivnosti** je izabranu (podrazumevana postavka).</span><span class="sxs-lookup"><span data-stu-id="c2983-110">**Note**: Certain activities may not be available in the **Activities** menu; however, those audit items will be returned if **Show Results for all activities** is selected (default setting).</span></span>

3. <span data-ttu-id="c2983-111">Navedite korisničko ime u polju **korisnicima** , izaberite odgovarajući opseg aktivnosti i zatim kliknite na dugme **za pretragu**.</span><span class="sxs-lookup"><span data-stu-id="c2983-111">Specify the username in the **Users** field, select the appropriate date range for the activity, and then click **Search**.</span></span>

<span data-ttu-id="c2983-112">U rezultatima, možete videti IP adresu za tu aktivnost u oknu rezultata.</span><span class="sxs-lookup"><span data-stu-id="c2983-112">In the results, you can see the IP address for that activity in the results pane.</span></span> <span data-ttu-id="c2983-113">Izaberite nadgledanja za detaljne informacije u **detalje** Potpaleta (na primer, klijent, korisnik koji izvršava radnju, itd.).</span><span class="sxs-lookup"><span data-stu-id="c2983-113">Select the audit record to see detailed information in the **Details** flyout (for example, Client, User that performed action, etc.).</span></span>

<span data-ttu-id="c2983-114">Više informacija potražite u odeljku [Pronalaženje IP adresu računara koristi za pristup kompromitovane nalog](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span><span class="sxs-lookup"><span data-stu-id="c2983-114">For more information, see [Finding the IP address of the computer used to access a compromised account](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span></span>
