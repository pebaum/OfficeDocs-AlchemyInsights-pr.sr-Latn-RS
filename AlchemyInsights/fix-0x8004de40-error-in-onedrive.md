---
title: Fix 0x8004de40 greška u usluzi OneDrive
ms.author: pebaum
author: pebaum
ms.date: 6/20/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 48b29f57763ca22a71a23b2afddcac0e8e8a95db
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40052051"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a><span data-ttu-id="d8d3b-102">Fix 0x8004de40 greška u usluzi OneDrive</span><span class="sxs-lookup"><span data-stu-id="d8d3b-102">Fix 0x8004de40 error in OneDrive</span></span>

<span data-ttu-id="d8d3b-103">Ako dobijete grešku 0x8004de40 u usluzi OneDrive:</span><span class="sxs-lookup"><span data-stu-id="d8d3b-103">If you receive an 0x8004de40 error with OneDrive:</span></span>

- <span data-ttu-id="d8d3b-104">Ponovo pokrenite računar na koji je bio povezan sa domenom u vašem Akitve.</span><span class="sxs-lookup"><span data-stu-id="d8d3b-104">Reboot the affected computer while connected to your Acitve Directory domain.</span></span>
- <span data-ttu-id="d8d3b-105">Ako ponovno pokretanje ne reši problem, raspakovanje i ponovno pridruživanje uređaju iz Azure oglasa.</span><span class="sxs-lookup"><span data-stu-id="d8d3b-105">If a reboot doesn't fix the issue, unjoin and rejoin your device from Azure AD.</span></span> 

<span data-ttu-id="d8d3b-106">**Napomena**: trebalo bi da budete na korporativnoj mreži dok izvršavate ove korake.</span><span class="sxs-lookup"><span data-stu-id="d8d3b-106">**Note**: You should be on your corporate network while performing these steps.</span></span> <span data-ttu-id="d8d3b-107">Nemojte da izvršavate ove korake kada ne možete da se povežete sa korporativnom infrastrukturom (na primer, tokom putovanja).</span><span class="sxs-lookup"><span data-stu-id="d8d3b-107">Don't perform these steps when you aren't able to connect to your corporate infrastructure (for example, while traveling).</span></span> 

- <span data-ttu-id="d8d3b-108">Otvaranje pune komandne linije.</span><span class="sxs-lookup"><span data-stu-id="d8d3b-108">Open an elevated command prompt.</span></span> 
- <span data-ttu-id="d8d3b-109">Kliknite desnim tasterom miša na **komandnu liniju** **, a**zatim izaberite stavku **Pokreni kao administrator**da biste otvorili sve pune komandne linije.</span><span class="sxs-lookup"><span data-stu-id="d8d3b-109">To open an elevated command prompt, click - **Start**, right-click **Command Prompt**, and then click **Run as administrator**.</span></span>
- <span data-ttu-id="d8d3b-110">Otkucajte *dsregcmd/napuštanje* i pritisnite taster **ENTER**.</span><span class="sxs-lookup"><span data-stu-id="d8d3b-110">Type *dsregcmd /leave* and press **Enter**.</span></span>
- <span data-ttu-id="d8d3b-111">Kada dovršite, otkucajte *dsregcmd/JOIN* i pritisnite taster **ENTER**.</span><span class="sxs-lookup"><span data-stu-id="d8d3b-111">When complete, type *dsregcmd /join* and press **Enter**.</span></span>
- <span data-ttu-id="d8d3b-112">Kada dovršite, zatvorite komandnu liniju.</span><span class="sxs-lookup"><span data-stu-id="d8d3b-112">When complete, close the command prompt.</span></span>
- <span data-ttu-id="d8d3b-113">Ponovo pokrenite računar i prijavite se u OneDrive.</span><span class="sxs-lookup"><span data-stu-id="d8d3b-113">Reboot the computer, and log into OneDrive.</span></span>