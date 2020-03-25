---
title: Saveti za smernice za DLP ne rade
ms.author: deniseb
author: denisebmsft
manager: laurawims
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: c03d30be-474a-4a34-b3c0-240eb2a2c466
ms.custom:
- "1428"
- "3200001"
ms.openlocfilehash: 51b4472fa721443192eb542cac45965df67634df
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932600"
---
# <a name="dlp-policy-tip-issues"></a><span data-ttu-id="4cf64-102">Problemi sa savete za DLP smernice</span><span class="sxs-lookup"><span data-stu-id="4cf64-102">DLP Policy Tip issues</span></span>

<span data-ttu-id="4cf64-103">**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini.</span><span class="sxs-lookup"><span data-stu-id="4cf64-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="4cf64-104">Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje.</span><span class="sxs-lookup"><span data-stu-id="4cf64-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="4cf64-105">U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.</span><span class="sxs-lookup"><span data-stu-id="4cf64-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="4cf64-106">U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici.</span><span class="sxs-lookup"><span data-stu-id="4cf64-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="4cf64-107">Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena.</span><span class="sxs-lookup"><span data-stu-id="4cf64-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="4cf64-108">Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.</span><span class="sxs-lookup"><span data-stu-id="4cf64-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="4cf64-109">**Savete za DLP smernice**</span><span class="sxs-lookup"><span data-stu-id="4cf64-109">**DLP policy tips**</span></span>

<span data-ttu-id="4cf64-110">Kada koristite **Dlp smernice**, korisnici mogu biti obavešteni o kršenju pravila sa **savetima za smernice**.</span><span class="sxs-lookup"><span data-stu-id="4cf64-110">When using **DLP policies**, users can be notified of a policy violation with **policy tips**.</span></span> <span data-ttu-id="4cf64-111">Administratori mogu da konfigurišu savete za smernice koji će se prikazivati prilikom testiranja njihovih DLP smernica ili kada je smernica u režimu potpunog sprovođenja.</span><span class="sxs-lookup"><span data-stu-id="4cf64-111">Admins can configure policy tips to display while testing their DLP policy or when the policy is in full enforcement mode.</span></span>
  
<span data-ttu-id="4cf64-112">Postupite na sledeći način da biste podesili savete za smernice u okviru "DLP" smernica u centru za bezbednost i usaglašenost u režimu potpunog sprovođenja.</span><span class="sxs-lookup"><span data-stu-id="4cf64-112">To configure policy tips on your DLP policy in the Security and Compliance center in full enforcement mode, do the following:</span></span>
  
- <span data-ttu-id="4cf64-113">Uverite se da su saveti za smernice **omogućeni** u pravilu "dlp" koristeći korake koje [ovde](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)koristite.</span><span class="sxs-lookup"><span data-stu-id="4cf64-113">Ensure policy tips have been **enabled** on the DLP rule using the steps [here](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips).</span></span>

- <span data-ttu-id="4cf64-114">Uverite se da se **sadržaj podudara sa** onim što je **potrebno** za aktiviranje pravila iznetih u [ovom članku.](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="4cf64-114">Ensure your **content matches** what is **required** to trigger the rule outlined in this article [here](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span></span>

- <span data-ttu-id="4cf64-115">Saveti za smernice prikazuju se u OWI i Outlook.</span><span class="sxs-lookup"><span data-stu-id="4cf64-115">Policy tips display in both OWA and Outlook.</span></span> <span data-ttu-id="4cf64-116">Međutim, ako koristite **Outlook 2013 ili noviji**, saveti za smernice su prikazani samo pod određenim uslovima.</span><span class="sxs-lookup"><span data-stu-id="4cf64-116">However, when using **Outlook 2013 or later**, policy tips are only displayed under certain conditions.</span></span> <span data-ttu-id="4cf64-117">Ovi uslovi su ovde navedeni: [podržani uslovi za Outlook 2013 ili noviji za prikazivanje saveta o smernicama](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips#outlook-2013-and-later-supports-showing-policy-tips-for-only-some-conditions)</span><span class="sxs-lookup"><span data-stu-id="4cf64-117">These conditions are listed here: [Supported conditions for Outlook 2013 or later for displaying Policy Tips](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips#outlook-2013-and-later-supports-showing-policy-tips-for-only-some-conditions)</span></span>

<span data-ttu-id="4cf64-118">Za dodatne informacije o tasterskim savetima za DLP smernice pogledajte odeljak: [Prikazivanje saveta za smernice za DLP smernice](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)</span><span class="sxs-lookup"><span data-stu-id="4cf64-118">For additional information on DLP policy tips, see: [Show policy tips for DLP Policies](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)</span></span>
  