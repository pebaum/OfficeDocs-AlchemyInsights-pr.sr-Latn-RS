---
title: Identifikuj IP adresu i klijenta u evidencijama nadgledanja
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1367"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: d1a0d412fc0c6d79e50b101ca759127522f45dcd
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716402"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a><span data-ttu-id="50b5f-102">Identifikuj IP adresu i klijenta u evidencijama nadgledanja</span><span class="sxs-lookup"><span data-stu-id="50b5f-102">Identify IP address and client in audit logs</span></span>

<span data-ttu-id="50b5f-103">IP adresa koja odgovara aktivnosti Microsoft 365 korisnika ili administratora prikazana je u evidencijama nadgledanja.</span><span class="sxs-lookup"><span data-stu-id="50b5f-103">The IP address that corresponds to an activity by a Microsoft 365 user or administrator is shown in the Audit Logs.</span></span> <span data-ttu-id="50b5f-104">Informacije o klijentu se takođe evidentiraju.</span><span class="sxs-lookup"><span data-stu-id="50b5f-104">The client information is also logged.</span></span> <span data-ttu-id="50b5f-105">Evo koraka za identifikovanje takvih informacija</span><span class="sxs-lookup"><span data-stu-id="50b5f-105">Here are the steps to identifying such information</span></span>

1. <span data-ttu-id="50b5f-106">Prijavite se na [Microsoft 365 Security & centar za usaglašavanje](https://protection.office.com/).</span><span class="sxs-lookup"><span data-stu-id="50b5f-106">Log in to the [Microsoft 365 Security & Compliance Center](https://protection.office.com/).</span></span>

2. <span data-ttu-id="50b5f-107">Idite na stranicu za**pretraživanje evidencije nadgledanja** **pretraživanja** > .</span><span class="sxs-lookup"><span data-stu-id="50b5f-107">Go to the **Search** > **Audit log search** page.</span></span>

   <span data-ttu-id="50b5f-108">Ako ste zainteresovani za određenu aktivnost, izaberite je sa liste **aktivnosti** .</span><span class="sxs-lookup"><span data-stu-id="50b5f-108">If you're interested in a specific activity, select it from **Activities** list.</span></span> <span data-ttu-id="50b5f-109">Ako ne, sve aktivnosti će biti vraćene za izabranog korisnika (podrazumevana postavka).</span><span class="sxs-lookup"><span data-stu-id="50b5f-109">If not, all activities will be returned for the selected user (default setting).</span></span>

   <span data-ttu-id="50b5f-110">**Napomena**: određene aktivnosti možda neće biti dostupne u meniju " **aktivnosti** "; Međutim, te stavke nadgledanja će biti vraćene ako je izabrano **Prikaz rezultata za sve aktivnosti** (podrazumevana postavka).</span><span class="sxs-lookup"><span data-stu-id="50b5f-110">**Note**: Certain activities may not be available in the **Activities** menu; however, those audit items will be returned if **Show Results for all activities** is selected (default setting).</span></span>

3. <span data-ttu-id="50b5f-111">Navedite korisničko ime u polju " **Korisnici** " izaberite odgovarajući opseg datuma za aktivnost, a zatim kliknite na dugme " **Pretraži**".</span><span class="sxs-lookup"><span data-stu-id="50b5f-111">Specify the username in the **Users** field, select the appropriate date range for the activity, and then click **Search**.</span></span>

<span data-ttu-id="50b5f-112">U rezultatima možete videti IP adresu za tu aktivnost u oknu sa rezultatima.</span><span class="sxs-lookup"><span data-stu-id="50b5f-112">In the results, you can see the IP address for that activity in the results pane.</span></span> <span data-ttu-id="50b5f-113">Izaberite zapis nadgledanja da biste videli detaljne informacije o **detaljima sa detalja** (npr. klijent, korisnik koji je izvršio radnju itd.)</span><span class="sxs-lookup"><span data-stu-id="50b5f-113">Select the audit record to see detailed information in the **Details** flyout (for example, Client, User that performed action, etc.).</span></span>

<span data-ttu-id="50b5f-114">Više informacija potražite u članku [PRONALAŽENJE IP adrese računara koji se koristi za pristup ugroženog naloga](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span><span class="sxs-lookup"><span data-stu-id="50b5f-114">For more information, see [Finding the IP address of the computer used to access a compromised account](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span></span>
