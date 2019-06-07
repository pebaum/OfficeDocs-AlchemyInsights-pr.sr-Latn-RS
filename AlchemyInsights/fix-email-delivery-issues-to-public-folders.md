---
title: Rešite probleme isporuku e-pošte da rade sa e-poštom javnim fasciklama
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1956
ms.assetid: ''
ms.openlocfilehash: 900b6cc2765937ee005c7e7dce5d33bbdf582601
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34752690"
---
# <a name="fix-email-delivery-issues-to-mail-enabled-public-folders"></a><span data-ttu-id="e145f-102">Rešite probleme isporuku e-pošte da rade sa e-poštom javnim fasciklama</span><span class="sxs-lookup"><span data-stu-id="e145f-102">Fix email delivery issues to mail-enabled public folders</span></span>

<span data-ttu-id="e145f-103">Ako spoljni pošiljaoci mogu da šalju poruke za svoje javne fascikle sa omogućenom e-poštom i pošiljalaca dobiti grešku: **nije moguće pronaći (550 5.4.1)**, provjerite e-mail domena za javna fascikla je konfigurisan kao domena za interni relej umesto da je autoritativnih domena:</span><span class="sxs-lookup"><span data-stu-id="e145f-103">If external senders can't send messages to your mail-enabled public folders, and the senders receive the error: **couldn't be found (550 5.4.1)**, verify the email domain for the public folder is configured as an internal relay domain instead of an authoritative domain:</span></span>

1. <span data-ttu-id="e145f-104">Otvorite [Centar za admin Exchange (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).</span><span class="sxs-lookup"><span data-stu-id="e145f-104">Open the [Exchange admin center (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).</span></span>

2. <span data-ttu-id="e145f-105">Idite na **tok pošte** \> **prihvaćeno domeni**, izaberite prihvaćena domena, a zatim izaberite stavku **Uredi**.</span><span class="sxs-lookup"><span data-stu-id="e145f-105">Go to **Mail flow** \> **Accepted domains**, select the accepted domain, and then click **Edit**.</span></span>

3. <span data-ttu-id="e145f-106">U svojstvima stranica taj otvara, ako tip domena podešen na **autoritativno**, promenite vrednost u **unutrašnje relej** i izaberite stavku **Sačuvaj**.</span><span class="sxs-lookup"><span data-stu-id="e145f-106">In the properties page that opens, if the domain type is set to **Authoritative**, change the value to **Internal relay** and then click **Save**.</span></span>

<span data-ttu-id="e145f-107">Ako spoljni pošiljaoci dobijate greške **nemate dozvolu (550 5.7.13)**, pokrenite sledeću komandu u [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) vidjeti dozvole za anonimne korisnike u javnoj fascikli:</span><span class="sxs-lookup"><span data-stu-id="e145f-107">If external senders receive the error **you don't have permission (550 5.7.13)**, run the following command in [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) to see the permissions for anonymous users in the public folder:</span></span>

<span data-ttu-id="e145f-108">`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous`Na primer, `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.</span><span class="sxs-lookup"><span data-stu-id="e145f-108">`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous` For example, `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.</span></span>

<span data-ttu-id="e145f-109">Da biste dozvolili spoljnim korisnicima da šalju e-poruke ovoj javnoj fascikli, dodati CreateItems pristup redu anonimni korisnik.</span><span class="sxs-lookup"><span data-stu-id="e145f-109">To allow external users to send email to this public folder, add the CreateItems access right to the user Anonymous.</span></span> <span data-ttu-id="e145f-110">Na primer, `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.</span><span class="sxs-lookup"><span data-stu-id="e145f-110">For example, `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.</span></span>
