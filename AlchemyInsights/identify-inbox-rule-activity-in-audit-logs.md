---
title: Identifikovanje aktivnosti pravila prijemnog poštanskog sandučeta u evidencijama nadgledanja
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1368"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: f946510539b3d28f2ceeec1546cbffce8bd352fd
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716438"
---
# <a name="identify-inbox-rule-activity-in-audit-logs"></a><span data-ttu-id="b4fe6-102">Identifikovanje aktivnosti pravila prijemnog poštanskog sandučeta u evidencijama nadgledanja</span><span class="sxs-lookup"><span data-stu-id="b4fe6-102">Identify inbox rule activity in audit logs</span></span>

<span data-ttu-id="b4fe6-103">Pretragu za evidenciju nadgledanja možete koristiti u Microsoft 365 bezbednosnom & centru za usaglašavanje da biste prikazali događaje za pravila prijemnog poštanskog sandučeta (kreiranje, izmenu i brisanje pravila prijemnog poštanskog sandučeta).</span><span class="sxs-lookup"><span data-stu-id="b4fe6-103">You can use audit log search in the Microsoft 365 Security & Compliance Center to view inbox rule events (creating, modifying, and deleting inbox rules).</span></span>

1. <span data-ttu-id="b4fe6-104">Prijavite se na [Microsoft 365 Security & centar za usaglašavanje](https://protection.office.com/).</span><span class="sxs-lookup"><span data-stu-id="b4fe6-104">Log in to the [Microsoft 365 Security & Compliance Center](https://protection.office.com/).</span></span>

2. <span data-ttu-id="b4fe6-105">Idite na stranicu za**pretraživanje evidencije nadgledanja** **pretraživanja** > .</span><span class="sxs-lookup"><span data-stu-id="b4fe6-105">Go to the **Search** > **Audit log search** page.</span></span>

3. <span data-ttu-id="b4fe6-106">Izaberite opseg datuma u poljima **Početni datum** i **Krajnji datum** .</span><span class="sxs-lookup"><span data-stu-id="b4fe6-106">Select the date range in the **Start date** and **End date** fields.</span></span>

4. <span data-ttu-id="b4fe6-107">U odeljku **Exchange poštanskog sandučeta**, proverite da li je polje **aktivnosti** postavljeno na **novo-inboxpravilo kreiranje/menjanje/omogućavanje/onemogućavanje pravila prijemnog poštanskog sandučeta**.</span><span class="sxs-lookup"><span data-stu-id="b4fe6-107">Under **Exchange Mailbox Activities**, verify the **Activities** field is set to **New-InboxRule Create/modify/enable/disable inbox rule**.</span></span>

5. <span data-ttu-id="b4fe6-108">Kliknite na dugme **Pretraži**.</span><span class="sxs-lookup"><span data-stu-id="b4fe6-108">Click **Search**.</span></span>

<span data-ttu-id="b4fe6-109">U rezultatima izaberite zapis nadgledanja.</span><span class="sxs-lookup"><span data-stu-id="b4fe6-109">In the results, select an audit record.</span></span> <span data-ttu-id="b4fe6-110">Kliknite na dugme " **više informacija**" u prozoru "Detalji".</span><span class="sxs-lookup"><span data-stu-id="b4fe6-110">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="b4fe6-111">Informacije o postavkama pravila prijemnog poštanskog sandučeta prikazane su u polju " **Parametri** ".</span><span class="sxs-lookup"><span data-stu-id="b4fe6-111">Information about the inbox rule settings is displayed in the **Parameters** field.</span></span>

<span data-ttu-id="b4fe6-112">Više informacija potražite u članku [Utvrđivanje da li je korisnik kreirao pravilo prijemnog poštanskog sandučeta](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span><span class="sxs-lookup"><span data-stu-id="b4fe6-112">For more information, see [Determining if a user created an inbox rule](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span></span>
