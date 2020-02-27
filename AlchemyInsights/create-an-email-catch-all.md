---
title: Kreiranje e-poruke uhvati sve
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001524"
- "3732"
ms.openlocfilehash: 35f31c1662547d57c2fc9978ffb495ac29abcc01
ms.sourcegitcommit: 67015549afcbe05f3b77ea314e2ef7e0e439f9f2
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/26/2020
ms.locfileid: "42286305"
---
# <a name="create-an-email-catch-all"></a><span data-ttu-id="7c6fd-102">Kreiranje e-poruke uhvati sve</span><span class="sxs-lookup"><span data-stu-id="7c6fd-102">Create an email catch all</span></span>

<span data-ttu-id="7c6fd-103">Korišćenje hvataka sve je snažno obeshrabrilo.</span><span class="sxs-lookup"><span data-stu-id="7c6fd-103">Use of a catch all is strongly discouraged.</span></span> <span data-ttu-id="7c6fd-104">Bolje je vratiti se pošiljaocu i pustiti pošiljaoce da znaju da njihova poruka nije mogla da se isporuči kao adresirana kako bi mogla da preduzmu korake.</span><span class="sxs-lookup"><span data-stu-id="7c6fd-104">It is better to provide a bounce back to the sender letting senders know their message could not be delivered as addressed so they can take action.</span></span> <span data-ttu-id="7c6fd-105">Takođe možete ograničiti nadgledani poštansko sanduče da biste hvatali i ranije važeće e-adrese.</span><span class="sxs-lookup"><span data-stu-id="7c6fd-105">You can also limit the monitored mailbox to only catch formerly valid email addresses.</span></span> 

<span data-ttu-id="7c6fd-106">Svaki od njih može dobiti dobar posao bezvredne pošte i na kraju će popuniti ako ne bude pažljivo nadgledan.</span><span class="sxs-lookup"><span data-stu-id="7c6fd-106">Any catch all mailbox will receive a good deal of spam and may eventually fill if not closely monitored.</span></span> <span data-ttu-id="7c6fd-107">(Dobijaju se ograničenja.)</span><span class="sxs-lookup"><span data-stu-id="7c6fd-107">(There are receiving limits.)</span></span> 

<span data-ttu-id="7c6fd-108">Ako odlučite da nastavite, sledite ove korake:</span><span class="sxs-lookup"><span data-stu-id="7c6fd-108">If you decide to proceed, follow these steps:</span></span>

1. <span data-ttu-id="7c6fd-109">Kreiranje dinamičke grupe za distribuciju & sadrži "sve tipove primalaca".</span><span class="sxs-lookup"><span data-stu-id="7c6fd-109">Create a Dynamic Distribution Group & include "All Recipient Types."</span></span>

2. <span data-ttu-id="7c6fd-110">Kreirajte namensko poštansko sanduče za hvatanje e-poruka, na primer catchall@domain.com.</span><span class="sxs-lookup"><span data-stu-id="7c6fd-110">Create a dedicated Mailbox to catch emails, for example, catchall@domain.com.</span></span>

3. <span data-ttu-id="7c6fd-111">Za određeni domen podesite DomainType na "Internalreleu".</span><span class="sxs-lookup"><span data-stu-id="7c6fd-111">For the specific domain, set the DomainType to “InternalRelay”.</span></span> <span data-ttu-id="7c6fd-112">Ako kasnije uklonite "uhvati sve", uverite se da ste ponovo podesili domen na pouzdane.</span><span class="sxs-lookup"><span data-stu-id="7c6fd-112">If you later remove the catch all, be sure to set the domain back to Authoritative.</span></span>

4. <span data-ttu-id="7c6fd-113">Kreirajte pravilo transporta za tok pošte na sledeći način:</span><span class="sxs-lookup"><span data-stu-id="7c6fd-113">Create a Mailflow Transport Rule as follows:</span></span>

    - <span data-ttu-id="7c6fd-114">Ako je pošiljalac "izvan organizacije"</span><span class="sxs-lookup"><span data-stu-id="7c6fd-114">If the Sender is "Outside the Organization"</span></span>
    - <span data-ttu-id="7c6fd-115">Preusmeri poruku na Catchall@domain.com</span><span class="sxs-lookup"><span data-stu-id="7c6fd-115">Redirect the message to Catchall@domain.com</span></span>
    - <span data-ttu-id="7c6fd-116">Osim ako je primalac član allusers@domain.com (grupa za distribuciju sadrži sve članove)</span><span class="sxs-lookup"><span data-stu-id="7c6fd-116">Except if the recipient is a member of allusers@domain.com (Distribution Group contains all members)</span></span>
    - <span data-ttu-id="7c6fd-117">Uverite se da ste proverili da li su novi poštanski sandučići dodati u dinamičku grupu distribucije</span><span class="sxs-lookup"><span data-stu-id="7c6fd-117">Ensure to validate that new mailboxes are added into the Dynamic Distribution Group</span></span>
