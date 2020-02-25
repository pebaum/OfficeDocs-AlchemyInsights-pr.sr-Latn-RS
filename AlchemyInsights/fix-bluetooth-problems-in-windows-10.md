---
title: Otklanjanje Bluetooth problema u operativnom sistemu Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001475"
- "3506"
ms.openlocfilehash: 94dda7a42632f57ce3aef5f467b87df1033b8d49
ms.sourcegitcommit: 9a35768444824cde9e192f1d9daafc9157437244
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/25/2020
ms.locfileid: "42268707"
---
# <a name="fix-bluetooth-problems-in-windows-10"></a><span data-ttu-id="363db-102">Otklanjanje Bluetooth problema u operativnom sistemu Windows 10</span><span class="sxs-lookup"><span data-stu-id="363db-102">Fix Bluetooth problems in Windows 10</span></span>

<span data-ttu-id="363db-103">Ako Bluetooth ikona nedostaje ili se ne može uključiti ili isključiti, možda ćete želeti da pokrenete program za rešavanje problema sa Bluetooth uređajem.</span><span class="sxs-lookup"><span data-stu-id="363db-103">If the Bluetooth icon is missing or Bluetooth can't be turned on or off, you may want to run the Bluetooth troubleshooter.</span></span> <span data-ttu-id="363db-104">[Otvorite postavke rešavanja problema](ms-settings:troubleshoot), kliknite na **Bluetooth** u okviru **Pronalaženje i rešavanje drugih problema**, izaberite stavku **Pokreni alatku za rešavanje problema**.</span><span class="sxs-lookup"><span data-stu-id="363db-104">[Open the Troubleshoot settings](ms-settings:troubleshoot), click **Bluetooth** under **Find and fix other problems**, click **Run the troubleshooter**.</span></span>

<span data-ttu-id="363db-105">Ako ne vidite ikonu "Bluetooth", ali se Bluetooth pojavljuje u upravljaču uređajima:</span><span class="sxs-lookup"><span data-stu-id="363db-105">If you don't see the Bluetooth icon, but Bluetooth does appear in Device Manager:</span></span>

1. <span data-ttu-id="363db-106">U upravljaču uređajima kliknite na dugme **Bluetooth**.</span><span class="sxs-lookup"><span data-stu-id="363db-106">In Device Manager, click **Bluetooth**.</span></span> <span data-ttu-id="363db-107">Pritisnite i držite ili kliknite desnim tasterom miša na ime Bluetooth adaptera i izaberite stavku **Deinstaliraj uređaj**.</span><span class="sxs-lookup"><span data-stu-id="363db-107">Press and hold (or right-click) the Bluetooth adapter name and click **Uninstall device**.</span></span>

2. <span data-ttu-id="363db-108">Isključite Windows uređaj, sačekajte nekoliko sekundi, a zatim ga ponovo uključite.</span><span class="sxs-lookup"><span data-stu-id="363db-108">Shut down your Windows device, wait a few seconds, and then turn it back on.</span></span> <span data-ttu-id="363db-109">Windows će pokušati da ponovo instalira upravljački program.</span><span class="sxs-lookup"><span data-stu-id="363db-109">Windows will try to reinstall the driver.</span></span>

<span data-ttu-id="363db-110">Ako ste nedavno instalirali Windows 10 dopune ili obavili nadogradnju na Windows 10, možda ćete želeti da proverite da li postoje ispravke upravljačkih programa:</span><span class="sxs-lookup"><span data-stu-id="363db-110">If you recently installed Windows 10 updates or upgraded to Windows 10, you may want to check for driver updates:</span></span>

1. <span data-ttu-id="363db-111">U upravljaču uređajima izaberite stavku **Bluetooth**, a zatim kliknite na ime Bluetooth adaptera (što može da uključuje reč "radio").</span><span class="sxs-lookup"><span data-stu-id="363db-111">In Device Manager, click **Bluetooth**, and then click the Bluetooth adapter name (which may include the word "radio").</span></span>

2. <span data-ttu-id="363db-112">Pritisnite i držite (ili kliknite desnim tasterom miša) na Bluetooth adapter, a zatim izaberite stavku Ažuriraj automatski Pretraži **upravljački program** > **za ažurirani softver upravljačkog programa**.</span><span class="sxs-lookup"><span data-stu-id="363db-112">Press and hold (or right-click) the Bluetooth adapter, and then click **Update driver** > **Search automatically for updated driver software**.</span></span> <span data-ttu-id="363db-113">Sledite ove korake, a zatim kliknite na dugme **Zatvori**.</span><span class="sxs-lookup"><span data-stu-id="363db-113">Follow the steps, then click **Close**.</span></span>

      - <span data-ttu-id="363db-114">Ako Windows ne može da pronađe novi Bluetooth upravljački program, posetite Veb lokaciju proizvođača računara i preuzmite najnoviji Bluetooth upravljački program odatle.</span><span class="sxs-lookup"><span data-stu-id="363db-114">If Windows can't find a new Bluetooth driver, visit the PC manufacturer's website and download the latest Bluetooth driver from there.</span></span>

    - <span data-ttu-id="363db-115">Kada ga preuzmete, kliknite na **Ažuriraj upravljački program** > **Potraži softver** > upravljačkog programa na računaru da biste**potražili** lokaciju na kojoj su datoteke upravljačkog programa uskladištene > **u redu** > **sledeće**i pratite korake koje želite da instalirate.</span><span class="sxs-lookup"><span data-stu-id="363db-115">After you download it, click **Update driver** > **Browse my computer for driver software** > **Browse** for the location where the driver files are stored > **OK** > **Next**, and follow the steps to install.</span></span>

3. <span data-ttu-id="363db-116">Nakon instaliranja ažuriranog upravljačkog programa, ponovo pokrenite mašinu, a zatim proverite da li to rešava problem veze.</span><span class="sxs-lookup"><span data-stu-id="363db-116">After installing the updated driver, restart the machine, and then check whether that fixes the connection issue.</span></span>

<span data-ttu-id="363db-117">Za više detalja o rešavanju problema sa Bluetooth vezom pogledajte kompletan članak, [ispravite Bluetooth probleme u operativnom sistemu Windows 10](https://support.microsoft.com/help/14169/windows-10-fix-bluetooth-problems).</span><span class="sxs-lookup"><span data-stu-id="363db-117">For more details of how to troubleshoot Bluetooth problems, please see the full article, [Fix Bluetooth problems in Windows 10](https://support.microsoft.com/help/14169/windows-10-fix-bluetooth-problems).</span></span>
