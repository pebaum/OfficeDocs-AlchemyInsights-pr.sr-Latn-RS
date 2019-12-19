---
title: Rešavanje problema sa postojećim monitorom
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3454"
- "9001450"
ms.openlocfilehash: d90baddd01bdf8508bd6289509c8399b8241887a
ms.sourcegitcommit: 42463e8d8869f36225a27388d83d37629c6b149e
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/18/2019
ms.locfileid: "40738582"
---
# <a name="troubleshoot-an-existing-monitor"></a><span data-ttu-id="f168a-102">Rešavanje problema sa postojećim monitorom</span><span class="sxs-lookup"><span data-stu-id="f168a-102">Troubleshoot an existing monitor</span></span>

<span data-ttu-id="f168a-103">Isprobajte ova rešenja za rešavanje problema sa monitorom.</span><span class="sxs-lookup"><span data-stu-id="f168a-103">Try these solutions to troubleshoot a monitor.</span></span> 

<span data-ttu-id="f168a-104">**Osvežavanje prikaza monitora:**</span><span class="sxs-lookup"><span data-stu-id="f168a-104">**Refresh your monitor's display:**</span></span>

<span data-ttu-id="f168a-105">Pritisnite sljedeće ključeve u isto vreme: tipka s logotipom sustava Windows + CTRL + SHIFT + B. Ovo će osvežiti komunikaciju sa vašim grafičkim upravljačkim programom.</span><span class="sxs-lookup"><span data-stu-id="f168a-105">Press the following keys at the same time: Windows Key  + Ctrl + Shift + B. This will refresh communication with your graphics driver.</span></span> <span data-ttu-id="f168a-106">Monitori će se momentalno treći i vratiti se nakon nekoliko sekundi.</span><span class="sxs-lookup"><span data-stu-id="f168a-106">Your monitors will blink momentarily and come back after a few seconds.</span></span>

<span data-ttu-id="f168a-107">**Rešavanje problema sa hardverom za nadgledanje:**</span><span class="sxs-lookup"><span data-stu-id="f168a-107">**Troubleshoot monitor hardware:**</span></span>

1. <span data-ttu-id="f168a-108">Isključite kabl koji povezuje računar sa monitorom i priključite ga nazad.</span><span class="sxs-lookup"><span data-stu-id="f168a-108">Unplug the cable connecting your PC to your monitor, and plug it back in.</span></span>
2. <span data-ttu-id="f168a-109">Isključite sve uređaje koji nisu neophodni sa računara (kao što su adapteri ili dokovi).</span><span class="sxs-lookup"><span data-stu-id="f168a-109">Disconnect any non-essential devices from your PC (such as adapters or docks).</span></span>

<span data-ttu-id="f168a-110">**Ako ste nedavno instalirali ispravku na RAČUNARU, možete da vratite upravljački program ekrana:**</span><span class="sxs-lookup"><span data-stu-id="f168a-110">**If you recently installed an update on your PC, you can roll back your display driver:**</span></span>

1. <span data-ttu-id="f168a-111">Izaberite stavku **Start**, otkucajte **Upravljač uređajima**i izaberite **Upravljač uređajima** od rezultata.</span><span class="sxs-lookup"><span data-stu-id="f168a-111">Select **Start**, type **device manager**, and select **Device Manager** from the results.</span></span>
2. <span data-ttu-id="f168a-112">Razvijte odeljak za **Prikaz adaptera** , kliknite desnim tasterom miša na adapter za prikaz, a zatim izaberite stavku **Svojstva**.</span><span class="sxs-lookup"><span data-stu-id="f168a-112">Expand the **Display adapters** section, right-click your display adapter, ands select **Properties**.</span></span>
3. <span data-ttu-id="f168a-113">Krećite se do kartice **upravljačkog programa** i izaberite stavku " **Vrati upravljački program**".</span><span class="sxs-lookup"><span data-stu-id="f168a-113">Navigate to the **Driver** tab and select **Roll Back Driver**.</span></span> <br>
<span data-ttu-id="f168a-114">Napomena: ako ovo nije dostupno ili je nedostupno, izaberite opciju " **ne** " iz dole navedenih opcija da biste se premestili na sledeći korak.</span><span class="sxs-lookup"><span data-stu-id="f168a-114">Note: If this isn't available or is grayed out, select **No** from the options below to move to the next step.</span></span>
4. <span data-ttu-id="f168a-115">Možda ćete morati ponovo da pokrenete računar pre nego što se promene stupe na snagu.</span><span class="sxs-lookup"><span data-stu-id="f168a-115">You may need to restart your PC before these changes take effect.</span></span>

<span data-ttu-id="f168a-116">**Deinstalirajte i ponovo instalirajte upravljački program ekrana:**</span><span class="sxs-lookup"><span data-stu-id="f168a-116">**Uninstall and reinstall your display driver:**</span></span>

1. <span data-ttu-id="f168a-117">Izaberite stavku **Start**, otkucajte **Upravljač uređajima**i izaberite **Upravljač uređajima** od rezultata.</span><span class="sxs-lookup"><span data-stu-id="f168a-117">Select **Start**, type **device manager**, and select **Device Manager** from the results.</span></span>
2. <span data-ttu-id="f168a-118">Razvijte odeljak za **Prikaz adaptera** , kliknite desnim tasterom miša na adapter za prikaz, a zatim izaberite stavku **Deinstaliraj uređaj**.</span><span class="sxs-lookup"><span data-stu-id="f168a-118">Expand the **Display adapters** section, right-click your display adapter, ands select **Uninstall device**.</span></span> 
3. <span data-ttu-id="f168a-119">Izaberite polje pored da biste **izbrisali softver upravljačkog programa za ovaj uređaj** i izaberite stavku " **Deinstaliraj**".</span><span class="sxs-lookup"><span data-stu-id="f168a-119">Select the box next to **Delete the driver software for this device** and select **Uninstall**.</span></span><br>
<span data-ttu-id="f168a-120">Napomena: možda će vam biti zatraženo da ponovo pokrenete računar u ovoj fazi.</span><span class="sxs-lookup"><span data-stu-id="f168a-120">Note: You may be asked to restart your computer at this stage.</span></span> <span data-ttu-id="f168a-121">Uverite se da ste zapisali preostala uputstva pre ponovnog pokretanja.</span><span class="sxs-lookup"><span data-stu-id="f168a-121">Make sure to write down the remaining instructions before you restart.</span></span>
4. <span data-ttu-id="f168a-122">Ponovo otvorite Upravljač uređajima.</span><span class="sxs-lookup"><span data-stu-id="f168a-122">Open Device Manager again.</span></span>
5. <span data-ttu-id="f168a-123">Razvijte odeljak "adapter za **Prikaz** ", kliknite desnim tasterom miša na adapter za prikaz i izaberite stavku **Ažuriraj upravljački program**.</span><span class="sxs-lookup"><span data-stu-id="f168a-123">Expand the **Display adapters** section, right-click on your display adapter, and select **Update Driver**.</span></span>
6. <span data-ttu-id="f168a-124">Izaberite opciju " **Pretraži automatski" za ažuriranje softvera upravljačkog programa** i pratite uputstva za instalaciju.</span><span class="sxs-lookup"><span data-stu-id="f168a-124">Select **Search automatically for update driver software** and follow the installation instructions.</span></span>