---
title: Fix 0x8004de40 greška u usluzi OneDrive
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 5da4271f242597b195ef61d553fd4a2ffb313025
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716042"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a><span data-ttu-id="b3669-102">Fix 0x8004de40 greška u usluzi OneDrive</span><span class="sxs-lookup"><span data-stu-id="b3669-102">Fix 0x8004de40 error in OneDrive</span></span>

<span data-ttu-id="b3669-103">Ako dobijete grešku 0x8004de40 u usluzi OneDrive:</span><span class="sxs-lookup"><span data-stu-id="b3669-103">If you receive an 0x8004de40 error with OneDrive:</span></span>

- <span data-ttu-id="b3669-104">Ponovo pokrenite računar na koji je bio povezan sa domenom u vašem Akitve.</span><span class="sxs-lookup"><span data-stu-id="b3669-104">Reboot the affected computer while connected to your Acitve Directory domain.</span></span>
- <span data-ttu-id="b3669-105">Ako ponovno pokretanje ne reši problem, raspakovanje i ponovno pridruživanje uređaju iz Azure oglasa.</span><span class="sxs-lookup"><span data-stu-id="b3669-105">If a reboot doesn't fix the issue, unjoin and rejoin your device from Azure AD.</span></span> 

<span data-ttu-id="b3669-106">**Napomena**: trebalo bi da budete na korporativnoj mreži dok izvršavate ove korake.</span><span class="sxs-lookup"><span data-stu-id="b3669-106">**Note**: You should be on your corporate network while performing these steps.</span></span> <span data-ttu-id="b3669-107">Nemojte da izvršavate ove korake kada ne možete da se povežete sa korporativnom infrastrukturom (na primer, tokom putovanja).</span><span class="sxs-lookup"><span data-stu-id="b3669-107">Don't perform these steps when you aren't able to connect to your corporate infrastructure (for example, while traveling).</span></span> 

- <span data-ttu-id="b3669-108">Otvaranje pune komandne linije.</span><span class="sxs-lookup"><span data-stu-id="b3669-108">Open an elevated command prompt.</span></span> 
- <span data-ttu-id="b3669-109">Kliknite desnim tasterom miša na **komandnu liniju** **, a**zatim izaberite stavku **Pokreni kao administrator**da biste otvorili sve pune komandne linije.</span><span class="sxs-lookup"><span data-stu-id="b3669-109">To open an elevated command prompt, click - **Start**, right-click **Command Prompt**, and then click **Run as administrator**.</span></span>
- <span data-ttu-id="b3669-110">Otkucajte *dsregcmd/napuštanje* i pritisnite taster **ENTER**.</span><span class="sxs-lookup"><span data-stu-id="b3669-110">Type *dsregcmd /leave* and press **Enter**.</span></span>
- <span data-ttu-id="b3669-111">Kada dovršite, otkucajte *dsregcmd/JOIN* i pritisnite taster **ENTER**.</span><span class="sxs-lookup"><span data-stu-id="b3669-111">When complete, type *dsregcmd /join* and press **Enter**.</span></span>
- <span data-ttu-id="b3669-112">Kada dovršite, zatvorite komandnu liniju.</span><span class="sxs-lookup"><span data-stu-id="b3669-112">When complete, close the command prompt.</span></span>
- <span data-ttu-id="b3669-113">Ponovo pokrenite računar i prijavite se u OneDrive.</span><span class="sxs-lookup"><span data-stu-id="b3669-113">Reboot the computer, and log into OneDrive.</span></span>