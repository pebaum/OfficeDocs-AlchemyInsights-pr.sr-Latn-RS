---
title: DLP će možda trebati prilagođeni tip
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1647"
- "3200001"
ms.assetid: ''
ms.openlocfilehash: 1ec8959a479f1a8f7bfcffb55f440e8c4ab435fb
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507528"
---
# <a name="dlp-might-need-a-custom-type"></a><span data-ttu-id="6af33-102">DLP će možda trebati prilagođeni tip</span><span class="sxs-lookup"><span data-stu-id="6af33-102">DLP might need a custom type</span></span>

<span data-ttu-id="6af33-103">**Važno**: Tokom ovih jedinstvenih vremena, preduzimamo sve korake da bismo se uverili da će usluge SharePoint Online i OneDrive ostati dostupne u najvećoj meri – više informacija potražite u članku [Privremena prilagođavanja funkcija u usluzi SharePoint Online](https://aka.ms/ODSPAdjustments).</span><span class="sxs-lookup"><span data-stu-id="6af33-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="6af33-104">**DLP može zahtijevati prilagođeni tip informacija**</span><span class="sxs-lookup"><span data-stu-id="6af33-104">**DLP may require a custom information type**</span></span>

<span data-ttu-id="6af33-105">Pomoću smernica za sprečavanje gubitka podataka (DLP) možete da identifikujete i zaštitite osetljive podatke u vašoj organizaciji.</span><span class="sxs-lookup"><span data-stu-id="6af33-105">With a data loss prevention (DLP) policy, you can identify and protect sensitive data in your organization.</span></span> <span data-ttu-id="6af33-106">U nekim slučajevima ćete možda morati da kreirate svoj **prilagođeni** tip poverljivih informacija da biste zaštitili podatke svoje organizacije.</span><span class="sxs-lookup"><span data-stu-id="6af33-106">In some scenarios, you might need to create your own **custom** sensitive information type to protect your organization's data.</span></span>

<span data-ttu-id="6af33-107">Na primer, vaša organizacija će možda morati da identifikuje i zaštiti ID-ove zaposlenih ili druge podatke u nekom formatu koji je karakterističan za vaš org. Ako je tako, pogledajte sledeće članke za više informacija.</span><span class="sxs-lookup"><span data-stu-id="6af33-107">For example, your organization might need to identify and protect employee IDs or other data in some format specific to your org. If so, see the following articles for more information.</span></span>
  
 <span data-ttu-id="6af33-108">**Prilagođavanje ugrađenog tipa poverljivih informacija**</span><span class="sxs-lookup"><span data-stu-id="6af33-108">**Customize a built-in sensitive information type**</span></span>
  
<span data-ttu-id="6af33-109">Ako je u ugrađenom tipu sa poverljivim informacijama zadovoljeno vaše potrebe sa samo nekoliko tvitova, možete da [prilagodite ugrađeni tip osetljivih informacija](https://docs.microsoft.com/microsoft-365/compliance/customize-a-built-in-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="6af33-109">If a built-in sensitive information type would meet your needs with just a few tweaks, you can [customize a built-in sensitive information type](https://docs.microsoft.com/microsoft-365/compliance/customize-a-built-in-sensitive-information-type).</span></span> <span data-ttu-id="6af33-110">Na primer, možete da dodate ili uklonite ključne reči ili da dodate ili uklonite prateće dokaze kao što su datum ili adresa.</span><span class="sxs-lookup"><span data-stu-id="6af33-110">For example, you can add or remove keywords, or add or remove supporting evidence such as a date or address.</span></span>
  
 <span data-ttu-id="6af33-111">**Kreiranje prilagođenog osetljivog tipa informacija**</span><span class="sxs-lookup"><span data-stu-id="6af33-111">**Create a custom sensitive information type**</span></span>
  
<span data-ttu-id="6af33-112">Međutim, ako je potrebno da potpuno identifikujete i zaštitite različite tipove osetljivih informacija, možete da [kreirate prilagođeni tip poverljivih informacija](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type) u korisničkom interfejsu bezbednosnog & centra za usaglašavanje.</span><span class="sxs-lookup"><span data-stu-id="6af33-112">But if you need to identify and protect a different type of sensitive information altogether, you can [create a custom sensitive information type](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type) in the UI of the Security & Compliance Center.</span></span>
  
<span data-ttu-id="6af33-113">**Kreiranje prilagođenog tipa osetljivih informacija u bezbednosnom & PowerShell centra za usaglašavanje**</span><span class="sxs-lookup"><span data-stu-id="6af33-113">**Create a custom sensitive information type in Security & Compliance Center PowerShell**</span></span>

<span data-ttu-id="6af33-114">Na kraju, ako korisnički interfejs ne obezbedi sve opcije koje su vam potrebne, možete da [kreirate prilagođeni tip poverljivih informacija u bezbednosnom & PowerShell centra za usaglašavanje](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span><span class="sxs-lookup"><span data-stu-id="6af33-114">Finally, if the UI doesn't provide all the options you need, you can [create a custom sensitive information type in Security & Compliance Center PowerShell](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span></span> <span data-ttu-id="6af33-115">Ako započnete sa XML datotekom, možete da koristite svaku dostupnu opciju.</span><span class="sxs-lookup"><span data-stu-id="6af33-115">By starting with an XML file, you can use every option available.</span></span>
