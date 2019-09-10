---
title: Premeštanje e-poruka u poštansko sanduče arhive
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1083"
- "3100008"
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: 5592bc7d4566e3498c33bbf9488db7f46ec58842
ms.sourcegitcommit: 8864b5789d9905916039081b53530c7e6d8bc529
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/10/2019
ms.locfileid: "36822176"
---
# <a name="move-email-to-the-archive-mailbox"></a><span data-ttu-id="17e27-102">Premeštanje e-poruke u poštansko sanduče arhive</span><span class="sxs-lookup"><span data-stu-id="17e27-102">Move email to the archive mailbox</span></span>

1. <span data-ttu-id="17e27-103">Potvrdite da je **poštansko sanduče arhive** omogućeno.</span><span class="sxs-lookup"><span data-stu-id="17e27-103">Confirm that an **Archive mailbox** has been enabled.</span></span> <span data-ttu-id="17e27-104">Ako ne, koristite korake iz [ovog članka](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) da biste omogućili poštansko sanduče arhive.</span><span class="sxs-lookup"><span data-stu-id="17e27-104">If not, use the steps in [this article](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) to enable the archive mailbox.</span></span>

2. <span data-ttu-id="17e27-105">Da bi se poruke automatski arhivirali u poštansko sanduče arhive, oznaka za zadržavanje sa radnjom " **Premesti u arhivu** " mora biti podešena tako da se **automatski primenjuje u celokupnu oznaku "poštansko sanduče" (podrazumevana)**.</span><span class="sxs-lookup"><span data-stu-id="17e27-105">To archive messages automatically to the archive mailbox, a retention tag with the **Move to archive** action must be set to **applied automatically to entire mailbox (default) tag**.</span></span> <span data-ttu-id="17e27-106">Koristite korake ovde da biste kreirali oznaku: [Arhiviraj podrazumevanu oznaku](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#create-a-custom-archive-default-policy-tag).</span><span class="sxs-lookup"><span data-stu-id="17e27-106">Use the steps here to create the tag: [Archive Default tag](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#create-a-custom-archive-default-policy-tag).</span></span>

3. <span data-ttu-id="17e27-107">Zatim dodajte oznaku **arhive** u smernice za zadržavanje.</span><span class="sxs-lookup"><span data-stu-id="17e27-107">Next, add the **Archive** tag to your retention policy.</span></span> <span data-ttu-id="17e27-108">U Exchange admin Center izaberite smernice za **zadržavanje** > dodajte stavku " **Premesti u** " u smernicu > " **Sačuvaj**".</span><span class="sxs-lookup"><span data-stu-id="17e27-108">In the Exchange admin center, choose **Retention Policies** > add the **Move to Archive tag** to the policy > **Save**.</span></span>

4. <span data-ttu-id="17e27-109">Sada [dodelite smernice za zadržavanje](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) u poštansko sanduče određenog korisnika.</span><span class="sxs-lookup"><span data-stu-id="17e27-109">Now [Assign the Retention Policy](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) to the specific user's mailbox.</span></span> <span data-ttu-id="17e27-110">Ista smernica će se primeniti i na **primarnu** i u poštansko sanduče **arhive** .</span><span class="sxs-lookup"><span data-stu-id="17e27-110">The same policy will be applied to both the **Primary** and the **Archive** mailbox.</span></span>

<span data-ttu-id="17e27-111">Možda će biti neophodno da naterate pomoćnika za upravljane fascikle (MFA) da pokrećete i primenite nove postavke na korisnikovo poštansko sanduče.</span><span class="sxs-lookup"><span data-stu-id="17e27-111">It may be necessary to force the Managed Folder Assistant (MFA) to run and apply the new settings to the user's mailbox.</span></span> <span data-ttu-id="17e27-112">Pokrenite sledeću komandu dok [ste povezani sa EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) da biste pokrenuli pomoćnika za kontrolisanu fasciklu za određeno poštansko sanduče:</span><span class="sxs-lookup"><span data-stu-id="17e27-112">Run the following command while [connected to EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) to start the Managed Folder Assistant for a specific mailbox:</span></span>
  
<span data-ttu-id="17e27-113">Start-ManagedFolderAssistant-identitet<name of the mailbox></span><span class="sxs-lookup"><span data-stu-id="17e27-113">Start-ManagedFolderAssistant -Identity <name of the mailbox></span></span>

<span data-ttu-id="17e27-114">Više informacija o podešavanju smernica arhive potražite [u članku Podešavanje smernica za arhiviranje i brisanje za Poštanske sandučiće](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span><span class="sxs-lookup"><span data-stu-id="17e27-114">For more information on setting up an archive policy, see [Set up an archive and deletion policy for mailboxes](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span></span>
  