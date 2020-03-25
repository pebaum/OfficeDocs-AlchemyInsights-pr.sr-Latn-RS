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
ms.openlocfilehash: 890bba57bc36c034c507e6124cd6593ef4d92af8
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932672"
---
# <a name="dlp-might-need-a-custom-type"></a><span data-ttu-id="deb85-102">DLP će možda trebati prilagođeni tip</span><span class="sxs-lookup"><span data-stu-id="deb85-102">DLP might need a custom type</span></span>

<span data-ttu-id="deb85-103">**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini.</span><span class="sxs-lookup"><span data-stu-id="deb85-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="deb85-104">Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje.</span><span class="sxs-lookup"><span data-stu-id="deb85-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="deb85-105">U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.</span><span class="sxs-lookup"><span data-stu-id="deb85-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="deb85-106">U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici.</span><span class="sxs-lookup"><span data-stu-id="deb85-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="deb85-107">Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena.</span><span class="sxs-lookup"><span data-stu-id="deb85-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="deb85-108">Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.</span><span class="sxs-lookup"><span data-stu-id="deb85-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="deb85-109">**DLP može zahtijevati prilagođeni tip informacija**</span><span class="sxs-lookup"><span data-stu-id="deb85-109">**DLP may require a custom information type**</span></span>

<span data-ttu-id="deb85-110">Pomoću smernica za sprečavanje gubitka podataka (DLP) možete da identifikujete i zaštitite osetljive podatke u vašoj organizaciji.</span><span class="sxs-lookup"><span data-stu-id="deb85-110">With a data loss prevention (DLP) policy, you can identify and protect sensitive data in your organization.</span></span> <span data-ttu-id="deb85-111">U nekim slučajevima ćete možda morati da kreirate svoj **prilagođeni** tip poverljivih informacija da biste zaštitili podatke svoje organizacije.</span><span class="sxs-lookup"><span data-stu-id="deb85-111">In some scenarios, you might need to create your own **custom** sensitive information type to protect your organization's data.</span></span>

<span data-ttu-id="deb85-112">Na primer, vaša organizacija će možda morati da identifikuje i zaštiti ID-ove zaposlenih ili druge podatke u nekom formatu koji je karakterističan za vaš org. Ako je tako, pogledajte sledeće članke za više informacija.</span><span class="sxs-lookup"><span data-stu-id="deb85-112">For example, your organization might need to identify and protect employee IDs or other data in some format specific to your org. If so, see the following articles for more information.</span></span>
  
 <span data-ttu-id="deb85-113">**Prilagođavanje ugrađenog tipa poverljivih informacija**</span><span class="sxs-lookup"><span data-stu-id="deb85-113">**Customize a built-in sensitive information type**</span></span>
  
<span data-ttu-id="deb85-114">Ako je u ugrađenom tipu sa poverljivim informacijama zadovoljeno vaše potrebe sa samo nekoliko tvitova, možete da [prilagodite ugrađeni tip osetljivih informacija](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="deb85-114">If a built-in sensitive information type would meet your needs with just a few tweaks, you can [customize a built-in sensitive information type](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span></span> <span data-ttu-id="deb85-115">Na primer, možete da dodate ili uklonite ključne reči ili da dodate ili uklonite prateće dokaze kao što su datum ili adresa.</span><span class="sxs-lookup"><span data-stu-id="deb85-115">For example, you can add or remove keywords, or add or remove supporting evidence such as a date or address.</span></span>
  
 <span data-ttu-id="deb85-116">**Kreiranje prilagođenog osetljivog tipa informacija**</span><span class="sxs-lookup"><span data-stu-id="deb85-116">**Create a custom sensitive information type**</span></span>
  
<span data-ttu-id="deb85-117">Međutim, ako je potrebno da potpuno identifikujete i zaštitite različite tipove osetljivih informacija, možete da [kreirate prilagođeni tip poverljivih informacija](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) u korisničkom interfejsu bezbednosnog & centra za usaglašavanje.</span><span class="sxs-lookup"><span data-stu-id="deb85-117">But if you need to identify and protect a different type of sensitive information altogether, you can [create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) in the UI of the Security & Compliance Center.</span></span>
  
<span data-ttu-id="deb85-118">**Kreiranje prilagođenog tipa osetljivih informacija u bezbednosnom & PowerShell centra za usaglašavanje**</span><span class="sxs-lookup"><span data-stu-id="deb85-118">**Create a custom sensitive information type in Security & Compliance Center PowerShell**</span></span>

<span data-ttu-id="deb85-119">Na kraju, ako korisnički interfejs ne obezbedi sve opcije koje su vam potrebne, možete da [kreirate prilagođeni tip poverljivih informacija u bezbednosnom & PowerShell centra za usaglašavanje](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span><span class="sxs-lookup"><span data-stu-id="deb85-119">Finally, if the UI doesn't provide all the options you need, you can [create a custom sensitive information type in Security & Compliance Center PowerShell](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span></span> <span data-ttu-id="deb85-120">Ako započnete sa XML datotekom, možete da koristite svaku dostupnu opciju.</span><span class="sxs-lookup"><span data-stu-id="deb85-120">By starting with an XML file, you can use every option available.</span></span>
