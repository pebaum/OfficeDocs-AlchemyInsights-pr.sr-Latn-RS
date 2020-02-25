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
ms.openlocfilehash: f51fd233db5ae068e719f1cf3bc94a0dac82444f
ms.sourcegitcommit: d87a6ac6ee77375d1d750100359b4dc7b2871691
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/25/2020
ms.locfileid: "42265030"
---
# <a name="troubleshooting-audio-issues-in-windows-10"></a><span data-ttu-id="b5284-102">Rešavanje problema sa zvukom u operativnom sistemu Windows 10</span><span class="sxs-lookup"><span data-stu-id="b5284-102">Troubleshooting audio issues in Windows 10</span></span>

<span data-ttu-id="b5284-103">**Pokretanje programa za rešavanje problema sa zvukom**</span><span class="sxs-lookup"><span data-stu-id="b5284-103">**Run the audio troubleshooter**</span></span>

1.  <span data-ttu-id="b5284-104">Otvorite [Postavke rešavanja problema](ms-settings:troubleshoot).</span><span class="sxs-lookup"><span data-stu-id="b5284-104">Open the [Troubleshoot settings](ms-settings:troubleshoot).</span></span>

2.  <span data-ttu-id="b5284-105">Izaberite **reprodukovanje zvuka** > **pokretanje programa za rešavanje problema**.</span><span class="sxs-lookup"><span data-stu-id="b5284-105">Select **Playing Audio** > **Run the troubleshooter**.</span></span>

<span data-ttu-id="b5284-106">**Postavljanje podrazumevanog uređaja**</span><span class="sxs-lookup"><span data-stu-id="b5284-106">**Set the default device**</span></span>

<span data-ttu-id="b5284-107">Ako se povezujete sa audio uređajem pomoću USB-a ili HDMI-a, možda ćete morati da podesite taj uređaj kao podrazumevani:</span><span class="sxs-lookup"><span data-stu-id="b5284-107">If you're connecting to an audio device using USB or HDMI, you might need to set that device as the default:</span></span>

1. <span data-ttu-id="b5284-108">Otvorite **početni** > **zvuk**, a zatim izaberite **zvučni** ili **promenite sistemske zvukove** sa liste rezultata.</span><span class="sxs-lookup"><span data-stu-id="b5284-108">Open **Start** > **Sound**, and then select **Sound** or **Change system sounds** from the list of results.</span></span>

2.  <span data-ttu-id="b5284-109">Na kartici **Reprodukcija** izaberite uređaj, izaberite stavku Postavi kao **podrazumevani**, a zatim kliknite na **dugme u redu**.</span><span class="sxs-lookup"><span data-stu-id="b5284-109">On the **Playback** tab, select a device, select **Set Default**, and then select **OK**.</span></span>

<span data-ttu-id="b5284-110">**Provera kablova, volumena, zvučnika i slušalica**</span><span class="sxs-lookup"><span data-stu-id="b5284-110">**Check cables, volume, speakers, and headphones**</span></span>

1. <span data-ttu-id="b5284-111">Proverite veze zvučnika i slušalica za labave kablove i uverite se da su povezani sa ispravnim konektorom.</span><span class="sxs-lookup"><span data-stu-id="b5284-111">Check your speaker and headphone connections for loose cables, and make sure they're connected to the correct jack.</span></span>

2. <span data-ttu-id="b5284-112">Proverite snagu i jačinu zvuka i probajte da uključite sve kontrole jačine zvuka.</span><span class="sxs-lookup"><span data-stu-id="b5284-112">Check your power and volume levels and try turning all the volume controls up.</span></span>

3. <span data-ttu-id="b5284-113">Neki zvučnici i aplikacije imaju svoje kontrole jačine zvuka; Možda ćete morati sve da ih proverite da biste se uverili da su na pravom nivou.</span><span class="sxs-lookup"><span data-stu-id="b5284-113">Some speakers and apps have their own volume controls; you might have to check them all to make sure they're at the right levels.</span></span>

4. <span data-ttu-id="b5284-114">Pokušajte da se povežete koristeći drugi USB port.</span><span class="sxs-lookup"><span data-stu-id="b5284-114">Try connecting using a different USB port.</span></span>

<span data-ttu-id="b5284-115">**Napomena**: Imajte u vidu da zvučnici možda neće raditi kada su slušalice priključene.</span><span class="sxs-lookup"><span data-stu-id="b5284-115">**Note**: Remember that your speakers may not work when headphones are plugged in.</span></span>

<span data-ttu-id="b5284-116">**Provera upravljača uređajima**</span><span class="sxs-lookup"><span data-stu-id="b5284-116">**Check Device Manager**</span></span>

<span data-ttu-id="b5284-117">Da biste se uverili da su upravljački programi ažurni:</span><span class="sxs-lookup"><span data-stu-id="b5284-117">To make sure the drivers are up to date:</span></span>

1. <span data-ttu-id="b5284-118">Izaberite stavku **Start**, otkucajte **Upravljač uređajima**, a zatim izaberite stavku **Upravljač uređajima** sa liste rezultata.</span><span class="sxs-lookup"><span data-stu-id="b5284-118">Select **Start**, type **Device Manager**, and then select **Device Manager** from the list of results.</span></span>

2. <span data-ttu-id="b5284-119">U okviru **Upravljači za zvuk, video i igre**izaberite zvučnu karticu, otvorite je, izaberite karticu **upravljački program** , a zatim izaberite stavku **Ažuriraj upravljački program**.</span><span class="sxs-lookup"><span data-stu-id="b5284-119">Under **Sound, video, and game controllers**, select your sound card, open it, select the **Driver** tab, and select **Update Driver**.</span></span>

<span data-ttu-id="b5284-120">**Napomena**: Ako Windows ne pronađe novi upravljački program, potražite ga na Veb lokaciji proizvođača uređaja i sledite uputstva.</span><span class="sxs-lookup"><span data-stu-id="b5284-120">**Note**: If Windows doesn't find a new driver, look for one on the device manufacturer's website and follow their instructions.</span></span>

<span data-ttu-id="b5284-121">**Ponovo instalirajte upravljački program**</span><span class="sxs-lookup"><span data-stu-id="b5284-121">**Reinstall the driver**</span></span>

<span data-ttu-id="b5284-122">Ako ne možete da ažurirate pomoću upravljača uređajima ili da pronađete novi upravljački program na Veb lokaciji proizvođača, isprobajte ove korake:</span><span class="sxs-lookup"><span data-stu-id="b5284-122">If you can't update via Device Manager or find a new driver on the manufacturer's website, try these steps:</span></span>

1. <span data-ttu-id="b5284-123">U upravljaču uređajima kliknite desnim tasterom miša na ikonu (ili pritisnite i držite) audio upravljački program i izaberite stavku **Deinstaliraj**.</span><span class="sxs-lookup"><span data-stu-id="b5284-123">In Device Manager, right-click (or press and hold) the audio driver, and select **Uninstall**.</span></span> <span data-ttu-id="b5284-124">Ponovo pokrenite uređaj i Windows će pokušati da ponovo instalira upravljački program.</span><span class="sxs-lookup"><span data-stu-id="b5284-124">Restart your device and Windows will attempt to reinstall the driver.</span></span>

2. <span data-ttu-id="b5284-125">Ako ponovno instaliranje upravljačkog programa ne funkcioniše, pokušajte da koristite opšti audio upravljački program koji dobijate uz Windows.</span><span class="sxs-lookup"><span data-stu-id="b5284-125">If reinstalling the driver doesn't work, try using the generic audio driver that comes with Windows.</span></span> <span data-ttu-id="b5284-126">U upravljaču uređajima kliknite desnim tasterom miša (ili pritisnite i držite) audio upravljački program > > **Ažuriraj softver upravljačkog programa** > **Pregledaj moj računar za softver upravljačkog programa\*\*\*\*Dozvoli mi da izaberem sa liste upravljačkih programa uređaja na računaru**, izaberite **zvučni uređaj visoke definicije**, kliknite na dugme **dalje**i sledite uputstva da biste ga instalirali.</span><span class="sxs-lookup"><span data-stu-id="b5284-126">In Device Manager, right-click (or press and hold) your audio driver > **Update driver software** > **Browse my computer for driver software** > **Let me pick from a list of device drivers on my computer**, select **High Definition Audio Device**, select **Next**, and follow the instructions to install it.</span></span>
