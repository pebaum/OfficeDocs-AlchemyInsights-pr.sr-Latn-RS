---
title: Duplirani zapis uređaja u portalu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4386"
ms.openlocfilehash: 277afc59705e6040f0f9ae0c8cad965bd7d3ef65
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2020
ms.locfileid: "43790171"
---
# <a name="duplicate-device-record-in-the-portal"></a><span data-ttu-id="49f79-102">Duplirani zapis uređaja u portalu</span><span class="sxs-lookup"><span data-stu-id="49f79-102">Duplicate device record in the portal</span></span>

<span data-ttu-id="49f79-103">Možda ćete videti 2 zapisa za uređaj na portalu ako uređaj ne prijavi tačno prijavljivanje statusa za saradnju na sajt upravljača konfigurisanja.</span><span class="sxs-lookup"><span data-stu-id="49f79-103">You may see 2 records for a device in the portal if the device does not correctly report the co-management status to the Configuration Manager site.</span></span> <span data-ttu-id="49f79-104">Da biste proverili status koordinatora uređaja, pregledajte \*\*\*\* kolonu za uređaj u alatki "Upravljač konfigurisanja" u okviru Konzola za upravljanje.</span><span class="sxs-lookup"><span data-stu-id="49f79-104">To check the co-management status of a device, review the **Co-managed** column for the device in the Configuration Manager console.</span></span> <span data-ttu-id="49f79-105">Ako kolona nije vidljiva, možete da je dodate tako što ćete kliknuti desnim tasterom miša na bilo koje zaglavlja kolona i odabrati ga sa liste.</span><span class="sxs-lookup"><span data-stu-id="49f79-105">If the column is not visible, you may add it by right-clicking any of the column headers, and selecting it from the list.</span></span>

<span data-ttu-id="49f79-106">Zajednički kontrolisana vrednost mora da bude **Da**.</span><span class="sxs-lookup"><span data-stu-id="49f79-106">The Co-managed value must be **Yes**.</span></span> <span data-ttu-id="49f79-107">Ako je vrednost **Ne**, otvorite aplet za Menadžer konfigurisanja klijenta na uređaju klijenta i potvrdite izbor u polju za potvrdu **Saradništvo** na kartici Opšte.</span><span class="sxs-lookup"><span data-stu-id="49f79-107">If the value is **No**, open the Configuration Manager client applet on the client device and check the **Co-management** property in the General tab.</span></span>

- <span data-ttu-id="49f79-108">Ako je vrednost **omogućena**, to ukazuje na probleme sa komunikacijom klijenta uz management Point.</span><span class="sxs-lookup"><span data-stu-id="49f79-108">If the value is **Enabled**, this indicates problems with client communication with the Management Point.</span></span> <span data-ttu-id="49f79-109">Pregledajte **CcmMessaging. log** na uređaju da biste istražili potencijalne probleme sa povezivanjem.</span><span class="sxs-lookup"><span data-stu-id="49f79-109">Please review the **CcmMessaging.log** on the device to investigate potential connectivity issues.</span></span>

- <span data-ttu-id="49f79-110">Ako je vrednost **onemogućena**, a uređaj je upisan u Intune, uverite se da je uređaj primio smernice za saradnju tako što će pregledati **CoManagementHandler.log** na uređaju.</span><span class="sxs-lookup"><span data-stu-id="49f79-110">If the value is **Disabled** and the device is enrolled in Intune, please ensure that the device has received the Co-management policy by reviewing the **CoManagementHandler.log** on the device.</span></span>
