---
title: Popravljanje problema sa isporukom e-pošte u javne fascikle koje su omogućene za poštu
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1956"
- "3500007"
ms.assetid: ''
ms.openlocfilehash: e261fe60843555fa45927b0a6b36e1ccf79fb028
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716366"
---
# <a name="fix-email-delivery-issues-to-mail-enabled-public-folders"></a><span data-ttu-id="b78c2-102">Popravljanje problema sa isporukom e-pošte u javne fascikle koje su omogućene za poštu</span><span class="sxs-lookup"><span data-stu-id="b78c2-102">Fix email delivery issues to mail-enabled public folders</span></span>

<span data-ttu-id="b78c2-103">Ako spoljni pošiljaoci ne mogu da šalju poruke u javne fascikle omogućene za poštu, a pošiljaoci dobijaju grešku: **nije bilo moguće pronaći (550 5.4.1)**, proverite da li je domen e-pošte za javnu fasciklu konfigurisan kao interni domen prenosa, a ne pouzdane domene:</span><span class="sxs-lookup"><span data-stu-id="b78c2-103">If external senders can't send messages to your mail-enabled public folders, and the senders receive the error: **couldn't be found (550 5.4.1)**, verify the email domain for the public folder is configured as an internal relay domain instead of an authoritative domain:</span></span>

1. <span data-ttu-id="b78c2-104">Otvorite [Exchange admin Center (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).</span><span class="sxs-lookup"><span data-stu-id="b78c2-104">Open the [Exchange admin center (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).</span></span>

2. <span data-ttu-id="b78c2-105">Idite na **tok** \> pošte **prihvaćeni domeni**, izaberite prihvaćeni domen, a zatim kliknite na dugme **Uredi**.</span><span class="sxs-lookup"><span data-stu-id="b78c2-105">Go to **Mail flow** \> **Accepted domains**, select the accepted domain, and then click **Edit**.</span></span>

3. <span data-ttu-id="b78c2-106">Na stranici sa svojstvima koja se otvara, ako je tip domena postavljen na **pouzdane**, promenite vrednost u **interni relej** i zatim kliknite na dugme **Sačuvaj**.</span><span class="sxs-lookup"><span data-stu-id="b78c2-106">In the properties page that opens, if the domain type is set to **Authoritative**, change the value to **Internal relay** and then click **Save**.</span></span>

<span data-ttu-id="b78c2-107">Ako spoljni pošiljaoci dobiju grešku nemate **dozvolu (550 5.7.13)**, pokrenite sledeću komandu u programu [Exchange online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) da biste videli dozvole za anonimne korisnike u javnoj fascikli:</span><span class="sxs-lookup"><span data-stu-id="b78c2-107">If external senders receive the error **you don't have permission (550 5.7.13)**, run the following command in [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) to see the permissions for anonymous users in the public folder:</span></span>

<span data-ttu-id="b78c2-108">`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous`Na primer, `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.</span><span class="sxs-lookup"><span data-stu-id="b78c2-108">`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous` For example, `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.</span></span>

<span data-ttu-id="b78c2-109">Da biste dozvolili spoljnim korisnicima da šalju e-poruke u ovu javnu fasciklu, dodajte pravo pristupa za Createstavke korisniku anonimnom.</span><span class="sxs-lookup"><span data-stu-id="b78c2-109">To allow external users to send email to this public folder, add the CreateItems access right to the user Anonymous.</span></span> <span data-ttu-id="b78c2-110">Na primer, `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.</span><span class="sxs-lookup"><span data-stu-id="b78c2-110">For example, `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.</span></span>
