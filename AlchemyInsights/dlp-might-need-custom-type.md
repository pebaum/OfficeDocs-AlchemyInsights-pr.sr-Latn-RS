---
title: DLP će možda trebati prilagođeni tip
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: ''
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1647"
- "3200001"
ms.assetid: ''
ms.openlocfilehash: 87fcb5c3cc9ccd525265097b66d9d9b3a85c5feb
ms.sourcegitcommit: d108a2da2f5dab05246e30b5108cca5173e09051
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/26/2020
ms.locfileid: "42977284"
---
# <a name="dlp-might-need-a-custom-type"></a><span data-ttu-id="668fa-102">DLP će možda trebati prilagođeni tip</span><span class="sxs-lookup"><span data-stu-id="668fa-102">DLP might need a custom type</span></span>

<span data-ttu-id="668fa-103">**Važno**: u ovakvim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive ostanu veoma dostupne – posetite [SharePoint online prilagođavanja](https://aka.ms/ODSPAdjustments) za više informacija.</span><span class="sxs-lookup"><span data-stu-id="668fa-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="668fa-104">**DLP može zahtijevati prilagođeni tip informacija**</span><span class="sxs-lookup"><span data-stu-id="668fa-104">**DLP may require a custom information type**</span></span>

<span data-ttu-id="668fa-105">Pomoću smernica za sprečavanje gubitka podataka (DLP) možete da identifikujete i zaštitite osetljive podatke u vašoj organizaciji.</span><span class="sxs-lookup"><span data-stu-id="668fa-105">With a data loss prevention (DLP) policy, you can identify and protect sensitive data in your organization.</span></span> <span data-ttu-id="668fa-106">U nekim slučajevima ćete možda morati da kreirate svoj **prilagođeni** tip poverljivih informacija da biste zaštitili podatke svoje organizacije.</span><span class="sxs-lookup"><span data-stu-id="668fa-106">In some scenarios, you might need to create your own **custom** sensitive information type to protect your organization's data.</span></span>

<span data-ttu-id="668fa-107">Na primer, vaša organizacija će možda morati da identifikuje i zaštiti ID-ove zaposlenih ili druge podatke u nekom formatu koji je karakterističan za vaš org. Ako je tako, pogledajte sledeće članke za više informacija.</span><span class="sxs-lookup"><span data-stu-id="668fa-107">For example, your organization might need to identify and protect employee IDs or other data in some format specific to your org. If so, see the following articles for more information.</span></span>
  
 <span data-ttu-id="668fa-108">**Prilagođavanje ugrađenog tipa poverljivih informacija**</span><span class="sxs-lookup"><span data-stu-id="668fa-108">**Customize a built-in sensitive information type**</span></span>
  
<span data-ttu-id="668fa-109">Ako je u ugrađenom tipu sa poverljivim informacijama zadovoljeno vaše potrebe sa samo nekoliko tvitova, možete da [prilagodite ugrađeni tip osetljivih informacija](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="668fa-109">If a built-in sensitive information type would meet your needs with just a few tweaks, you can [customize a built-in sensitive information type](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span></span> <span data-ttu-id="668fa-110">Na primer, možete da dodate ili uklonite ključne reči ili da dodate ili uklonite prateće dokaze kao što su datum ili adresa.</span><span class="sxs-lookup"><span data-stu-id="668fa-110">For example, you can add or remove keywords, or add or remove supporting evidence such as a date or address.</span></span>
  
 <span data-ttu-id="668fa-111">**Kreiranje prilagođenog osetljivog tipa informacija**</span><span class="sxs-lookup"><span data-stu-id="668fa-111">**Create a custom sensitive information type**</span></span>
  
<span data-ttu-id="668fa-112">Međutim, ako je potrebno da potpuno identifikujete i zaštitite različite tipove osetljivih informacija, možete da [kreirate prilagođeni tip poverljivih informacija](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) u korisničkom interfejsu bezbednosnog & centra za usaglašavanje.</span><span class="sxs-lookup"><span data-stu-id="668fa-112">But if you need to identify and protect a different type of sensitive information altogether, you can [create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) in the UI of the Security & Compliance Center.</span></span>
  
<span data-ttu-id="668fa-113">**Kreiranje prilagođenog tipa osetljivih informacija u bezbednosnom & PowerShell centra za usaglašavanje**</span><span class="sxs-lookup"><span data-stu-id="668fa-113">**Create a custom sensitive information type in Security & Compliance Center PowerShell**</span></span>

<span data-ttu-id="668fa-114">Na kraju, ako korisnički interfejs ne obezbedi sve opcije koje su vam potrebne, možete da [kreirate prilagođeni tip poverljivih informacija u bezbednosnom & PowerShell centra za usaglašavanje](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span><span class="sxs-lookup"><span data-stu-id="668fa-114">Finally, if the UI doesn't provide all the options you need, you can [create a custom sensitive information type in Security & Compliance Center PowerShell](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span></span> <span data-ttu-id="668fa-115">Ako započnete sa XML datotekom, možete da koristite svaku dostupnu opciju.</span><span class="sxs-lookup"><span data-stu-id="668fa-115">By starting with an XML file, you can use every option available.</span></span>
