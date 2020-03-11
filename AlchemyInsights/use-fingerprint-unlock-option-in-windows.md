---
title: Korišćenje opcije za otključavanje otiska prsta u operativnom sistemu Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001689"
- "3765"
ms.openlocfilehash: 8a5059c722c306ad79811140062cec7f52f31766
ms.sourcegitcommit: 00e4266575438f55bdc18db05ed54aafcb75a3c9
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/11/2020
ms.locfileid: "42588329"
---
# <a name="use-fingerprint-unlock-option-in-windows-10"></a><span data-ttu-id="4246f-102">Korišćenje opcije za otključavanje otiska prsta u operativnom sistemu Windows 10</span><span class="sxs-lookup"><span data-stu-id="4246f-102">Use fingerprint unlock option in Windows 10</span></span>

<span data-ttu-id="4246f-103">**Omogući Windows Hello otisak prsta**</span><span class="sxs-lookup"><span data-stu-id="4246f-103">**Enable Windows Hello Fingerprint**</span></span>

<span data-ttu-id="4246f-104">Da biste otključali Windows 10 pomoću otiska prsta, potrebno je da podesite Windows Hello otisak prsta tako što ćete dodati (Ako Windows nauči da prepozna) bar jedan prst.</span><span class="sxs-lookup"><span data-stu-id="4246f-104">To unlock Windows 10 using your fingerprint, you need to set up Windows Hello Fingerprint by adding (letting Windows learn to recognize) at least one finger.</span></span> 

1. <span data-ttu-id="4246f-105">Izaberite **podešavanja > nalozi > opcije za prijavljivanje** (ili kliknite [ovde](ms-settings:signinoptions?activationSource=GetHelp)).</span><span class="sxs-lookup"><span data-stu-id="4246f-105">Go to **Settings  > Accounts > Sign-in options** (or click [here](ms-settings:signinoptions?activationSource=GetHelp)).</span></span> <span data-ttu-id="4246f-106">Biće navedene raspoložive opcije za prijavljivanje.</span><span class="sxs-lookup"><span data-stu-id="4246f-106">Available sign-in options will be listed.</span></span> <span data-ttu-id="4246f-107">Na primer:</span><span class="sxs-lookup"><span data-stu-id="4246f-107">For example:</span></span>

    ![Opcije za prijavljivanje.](media/sign-in-options.png)

2. <span data-ttu-id="4246f-109">Kliknite ili dodirnite **Windows Hello otisak prsta**, a zatim kliknite na dugme **Podesi**.</span><span class="sxs-lookup"><span data-stu-id="4246f-109">Click or tap **Windows Hello Fingerprint**, then click **Set up**.</span></span> <span data-ttu-id="4246f-110">U prozoru "Windows Hello podešavanje" kliknite na dugme " **Započni**".</span><span class="sxs-lookup"><span data-stu-id="4246f-110">In the Windows Hello setup window, click **Get started**.</span></span> <span data-ttu-id="4246f-111">Senzor otisaka prstiju će se aktivirati i od vas će se zatražiti da postavite prst na senzor:</span><span class="sxs-lookup"><span data-stu-id="4246f-111">The fingerprint sensor will activate, and you'll be asked to place your finger on the sensor:</span></span>

   ![Senzor otisaka prstiju.](media/fingerprint-sensor.png)

3. <span data-ttu-id="4246f-113">Sledite uputstva koja će vam zatražiti da više puta skenirate prst.</span><span class="sxs-lookup"><span data-stu-id="4246f-113">Follow the instructions, which will ask you to repeatedly scan your finger.</span></span> <span data-ttu-id="4246f-114">Kada se ovo završi, imaćete mogućnost dodavanja ostalih prstiju koje ćete možda želeti da koristite za prijavljivanje.</span><span class="sxs-lookup"><span data-stu-id="4246f-114">When this is finished, you'll have the option of adding other fingers you may want to use for sign-in.</span></span> <span data-ttu-id="4246f-115">Sledeći put kada se prijavite u Windows 10, imaćete opciju da koristite otisak prsta da biste to uradili.</span><span class="sxs-lookup"><span data-stu-id="4246f-115">Next time you sign in to Windows 10, you will have the option of using your fingerprint to do so.</span></span>

<span data-ttu-id="4246f-116">**Windows Hello otisak prsta nije dostupan kao opcija za prijavljivanje**</span><span class="sxs-lookup"><span data-stu-id="4246f-116">**Windows Hello Fingerprint not available as a sign-in option**</span></span>

<span data-ttu-id="4246f-117">Ako Windows Hello otisak prsta nije prikazan kao opcija u **opcijama za prijavljivanje**, to znači da Windows nije upoznat sa bilo kojim čitačem otisaka prstiju/skenera koji je PRIKLJUČEN na računar ili da smernice sistema sprečavaju njeno korišćenje (ako na primer, računar upravlja vašim radnim mestom).</span><span class="sxs-lookup"><span data-stu-id="4246f-117">If Windows Hello Fingerprint is not shown as an option in **Sign-in options**, it means Windows is not aware of any fingerprint reader/scanner attached to your PC, or that a system policy prevents its use (if for example your PC is managed by your workplace).</span></span> <span data-ttu-id="4246f-118">Da biste rešili problem:</span><span class="sxs-lookup"><span data-stu-id="4246f-118">To troubleshoot:</span></span> 

1. <span data-ttu-id="4246f-119">Kliknite na dugme **Start** na traci zadataka i potražite **Upravljač uređajima**.</span><span class="sxs-lookup"><span data-stu-id="4246f-119">Select the **Start** button in the Taskbar and search for **Device Manager**.</span></span>

2. <span data-ttu-id="4246f-120">Kliknite ili dodirnite da biste otvorili **Upravljač uređajima**.</span><span class="sxs-lookup"><span data-stu-id="4246f-120">Click or tap to open **Device Manager**.</span></span>

3. <span data-ttu-id="4246f-121">U upravljaču uređajima razvijte biometrijske uređaje tako što ćete kliknuti na njegov ševron.</span><span class="sxs-lookup"><span data-stu-id="4246f-121">In Device Manager, expand Biometric devices by clicking its chevron.</span></span>

   ![Biometrijske uređaje.](media/biometric-devices.png)

4. <span data-ttu-id="4246f-123">Skener otisaka prstiju bi trebalo da bude naveden kao biometrijski uređaj, kao što je Synaptics WBDI skener:</span><span class="sxs-lookup"><span data-stu-id="4246f-123">Your fingerprint scanner should be listed as a biometric device, such as the Synaptics WBDI scanner:</span></span>

   ![Biometrijske uređaje.](media/biometric-devices-expanded.png)

5. <span data-ttu-id="4246f-125">Ako skener otisaka prstiju nije prikazan, a skener je integrisan u računar, posetite Veb lokaciju proizvođača računara.</span><span class="sxs-lookup"><span data-stu-id="4246f-125">If your fingerprint scanner is not shown, and the scanner is integrated into your PC, go to the PC manufacturer's website.</span></span> <span data-ttu-id="4246f-126">U odeljku za tehničku podršku za model računara potražite Windows 10 upravljački program za skener koji možete da instalirate.</span><span class="sxs-lookup"><span data-stu-id="4246f-126">In the technical support section for your PC model, search for a Windows 10 driver for a scanner that you can install.</span></span>

6. <span data-ttu-id="4246f-127">Ako je skener odvojen od računara (priključen preko USB-a), posetite Veb lokaciju proizvođača skenera da biste pronašli i instalirali softver upravljačkog programa za Windows 10 za model skenera koji imate.</span><span class="sxs-lookup"><span data-stu-id="4246f-127">If the scanner is separate from the PC (attached via USB), go to the scanner manufacturer's website to find and install Windows 10 device driver software for the scanner model you have.</span></span>
