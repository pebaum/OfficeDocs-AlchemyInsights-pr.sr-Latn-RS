---
title: Rešavanje problema sa zvukom u operativnom sistemu Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3476"
- "9001463"
ms.openlocfilehash: 46b23f97c2e682258224dc95e7a76b1201991828
ms.sourcegitcommit: 802537a54ef8bde1bdd758ee9a60b6c19d37d6e1
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/19/2019
ms.locfileid: "40796347"
---
# <a name="troubleshooting-audio-problems-in-windows-10"></a><span data-ttu-id="2cc0e-102">Rešavanje problema sa zvukom u operativnom sistemu Windows 10</span><span class="sxs-lookup"><span data-stu-id="2cc0e-102">Troubleshooting audio problems in Windows 10</span></span>

<span data-ttu-id="2cc0e-103">**Pokretanje programa za rešavanje problema sa zvukom**</span><span class="sxs-lookup"><span data-stu-id="2cc0e-103">**Run the audio troubleshooter**</span></span>

<span data-ttu-id="2cc0e-104">Program za rešavanje problema sa zvukom će možda moći automatski da otkloni probleme sa zvukom:</span><span class="sxs-lookup"><span data-stu-id="2cc0e-104">The audio troubleshooter might be able to fix the audio problems automatically:</span></span> 

1. <span data-ttu-id="2cc0e-105">Kliknite na dugme **Start**, otkucajte **Rešavanje problema**, a zatim izaberite stavku **Rešavanje problema** sa liste rezultata.</span><span class="sxs-lookup"><span data-stu-id="2cc0e-105">Select **Start**, type **troubleshoot**, and then select **Troubleshoot** from the list of results.</span></span> 
2. <span data-ttu-id="2cc0e-106">Izaberite **reprodukovanje zvuka** > **pokretanje programa za rešavanje problema**.</span><span class="sxs-lookup"><span data-stu-id="2cc0e-106">Select **Playing Audio** > **Run the troubleshooter**.</span></span>

<span data-ttu-id="2cc0e-107">**Provera kablova, volumena, zvučnika i slušalica**</span><span class="sxs-lookup"><span data-stu-id="2cc0e-107">**Check cables, volume, speakers, and headphones**</span></span>

- <span data-ttu-id="2cc0e-108">Proverite veze zvučnika i slušalica za labave kablove i uverite se da su povezani sa ispravnim konektorom.</span><span class="sxs-lookup"><span data-stu-id="2cc0e-108">Check your speaker and headphone connections for loose cables, and make sure they're connected to the correct jack.</span></span>
- <span data-ttu-id="2cc0e-109">Proverite snagu i jačinu zvuka i probajte da uključite sve kontrole jačine zvuka.</span><span class="sxs-lookup"><span data-stu-id="2cc0e-109">Check your power and volume levels, and try turning all the volume controls up.</span></span>
- <span data-ttu-id="2cc0e-110">Neki zvučnici i aplikacije imaju svoje kontrole jačine zvuka i možda ćete morati da ih proverite da biste se uverili da su na pravom nivou.</span><span class="sxs-lookup"><span data-stu-id="2cc0e-110">Some speakers and apps have their own volume controls, and you might have to check them all to make sure they're at the right levels.</span></span>
- <span data-ttu-id="2cc0e-111">Pokušajte da se povežete koristeći drugi USB port.</span><span class="sxs-lookup"><span data-stu-id="2cc0e-111">Try connecting using a different USB port.</span></span>
- <span data-ttu-id="2cc0e-112">**Napomena:** Imajte u vidu da zvučnici možda neće raditi kada su slušalice priključene.</span><span class="sxs-lookup"><span data-stu-id="2cc0e-112">**Note:** Remember that your speakers may not work when headphones are plugged in.</span></span>

<span data-ttu-id="2cc0e-113">**Provera upravljača uređajima**</span><span class="sxs-lookup"><span data-stu-id="2cc0e-113">**Check Device Manager**</span></span>

<span data-ttu-id="2cc0e-114">Da biste se uverili da su upravljački programi ažurni:</span><span class="sxs-lookup"><span data-stu-id="2cc0e-114">To make sure the drivers are up to date:</span></span>

- <span data-ttu-id="2cc0e-115">Izaberite stavku **Start**, otkucajte **Upravljač uređajima**, a zatim izaberite stavku **Upravljač uređajima** sa liste rezultata.</span><span class="sxs-lookup"><span data-stu-id="2cc0e-115">Select **Start**, type **Device Manager**, and then select **Device Manager** from the list of results.</span></span>

2. <span data-ttu-id="2cc0e-116">U okviru **Upravljači za zvuk, video i igre**izaberite zvučnu karticu, otvorite je, izaberite karticu **upravljački program** , a zatim izaberite stavku **Ažuriraj upravljački program**.</span><span class="sxs-lookup"><span data-stu-id="2cc0e-116">Under **Sound, video, and game controllers**, select your sound card, open it, select the **Driver** tab, and select **Update Driver**.</span></span> 

<span data-ttu-id="2cc0e-117">**Napomena:** Ako Windows ne pronađe novi upravljački program, potražite ga na Veb lokaciji proizvođača uređaja i sledite uputstva.</span><span class="sxs-lookup"><span data-stu-id="2cc0e-117">**Note:** If Windows doesn't find a new driver, look for one on the device manufacturer's website and follow their instructions.</span></span>

<span data-ttu-id="2cc0e-118">**Ponovo instalirajte upravljački program**</span><span class="sxs-lookup"><span data-stu-id="2cc0e-118">**Reinstall the driver**</span></span>

<span data-ttu-id="2cc0e-119">Ako ne možete da ažurirate pomoću upravljača uređajima ili da pronađete novi upravljački program na Veb lokaciji proizvođača, isprobajte ove korake:</span><span class="sxs-lookup"><span data-stu-id="2cc0e-119">If you can't update via Device Manager or find a new driver on the manufacturer's website, try these steps:</span></span> 

1. <span data-ttu-id="2cc0e-120">U upravljaču uređajima kliknite desnim tasterom miša na ikonu (ili pritisnite i držite) audio upravljački program i izaberite stavku **Deinstaliraj**.</span><span class="sxs-lookup"><span data-stu-id="2cc0e-120">In Device Manager, right-click (or press and hold) the audio driver, and select **Uninstall**.</span></span> <span data-ttu-id="2cc0e-121">Ponovo pokrenite uređaj i Windows će pokušati da ponovo instalira upravljački program.</span><span class="sxs-lookup"><span data-stu-id="2cc0e-121">Restart your device and Windows will attempt to reinstall the driver.</span></span>

2. <span data-ttu-id="2cc0e-122">Ako ponovno instaliranje upravljačkog programa ne funkcioniše, pokušajte da koristite opšti audio upravljački program koji dobijate uz Windows.</span><span class="sxs-lookup"><span data-stu-id="2cc0e-122">If reinstalling the driver doesn't work, try using the generic audio driver that comes with Windows.</span></span> <span data-ttu-id="2cc0e-123">U upravljaču uređajima kliknite desnim tasterom miša (ili pritisnite i držite) audio upravljački program > > **Ažuriraj softver upravljačkog programa** > **Pregledaj moj računar za softver upravljačkog programa\*\*\*\*Dozvoli mi da izaberem sa liste upravljačkih programa uređaja na računaru**, izaberite **zvučni uređaj visoke definicije**, kliknite na dugme **dalje**i sledite uputstva da biste ga instalirali.</span><span class="sxs-lookup"><span data-stu-id="2cc0e-123">In Device Manager, right-click (or press and hold) your audio driver > **Update driver software** > **Browse my computer for driver software** > **Let me pick from a list of device drivers on my computer**, select **High Definition Audio Device**, select **Next**, and follow the instructions to install it.</span></span>

<span data-ttu-id="2cc0e-124">**Postavljanje podrazumevanog uređaja**</span><span class="sxs-lookup"><span data-stu-id="2cc0e-124">**Set the default device**</span></span>

<span data-ttu-id="2cc0e-125">Ako se povezujete sa audio uređajem pomoću USB-a ili HDMI-a, možda ćete morati da podesite taj uređaj kao podrazumevani:</span><span class="sxs-lookup"><span data-stu-id="2cc0e-125">If you're connecting to an audio device using USB or HDMI, you might need to set that device as the default:</span></span> 

1. <span data-ttu-id="2cc0e-126">Kliknite na dugme **Start**, otkucajte **zvuk**, a zatim izaberite **zvučni** ili **promenite sistemske zvukove** sa liste rezultata.</span><span class="sxs-lookup"><span data-stu-id="2cc0e-126">Select **Start**, type **Sound**, and then select **Sound** or **Change system sounds** from the list of results.</span></span>

2. <span data-ttu-id="2cc0e-127">Na kartici **Reprodukcija** izaberite uređaj, izaberite stavku Postavi kao **podrazumevani**, a zatim kliknite na **dugme u redu**.</span><span class="sxs-lookup"><span data-stu-id="2cc0e-127">On the **Playback** tab, select a device, select **Set Default**, and then select **OK**.</span></span>

