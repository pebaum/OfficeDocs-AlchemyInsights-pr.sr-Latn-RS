---
title: Na radnoj površini opoziv programa Outlook "ili" zameni e-poruku
ms.author: daeite
author: daeite
manager: joallard
ms.date: 3/13/2019
ms.audience: Admin
ms.topic: article
ms.custom: 9000260
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: aced684777ef82860b969aea8825699b78b04c5a
ms.sourcegitcommit: aad9f863bc9fd7d5522c480bd1a7d15f3a80ff4f
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/15/2019
ms.locfileid: "30657057"
---
# <a name="recall-or-replace-an-email-message"></a><span data-ttu-id="291ad-102">Opozovete ili zamenite e-poruku</span><span class="sxs-lookup"><span data-stu-id="291ad-102">Recall or replace an email message</span></span>

- <span data-ttu-id="291ad-103">Kao administrator, možete **opoziv poruke u ime korisnika pomoću PowerShell**.</span><span class="sxs-lookup"><span data-stu-id="291ad-103">As the admin, you can **recall messages on behalf of users using PowerShell**.</span></span> <span data-ttu-id="291ad-104">Ne mogu da se setim poruke iz centra za administraciju.</span><span class="sxs-lookup"><span data-stu-id="291ad-104">You can't recall messages from the admin center.</span></span>
- <span data-ttu-id="291ad-105">Možete **samo opoziv poruke koje se šalju osobe u vašoj organizaciji**.</span><span class="sxs-lookup"><span data-stu-id="291ad-105">You can **only recall messages that are sent to people in your organization**.</span></span> <span data-ttu-id="291ad-106">Ako je poruka poslata na Gmail adresu, na primer, da mogu da se setim to.</span><span class="sxs-lookup"><span data-stu-id="291ad-106">If the message was sent to a Gmail address, for example, you can't recall it.</span></span>
- <span data-ttu-id="291ad-107">Možete **samo opoziv poruke poslane iz Outlook 2016 na PC**.</span><span class="sxs-lookup"><span data-stu-id="291ad-107">You can **only recall messages sent from Outlook 2016 on the PC**.</span></span> <span data-ttu-id="291ad-108">Ako korisnik pošalje poruku koristeći Outlook za Mac ili Outlook na Webu, mogu da se setim.</span><span class="sxs-lookup"><span data-stu-id="291ad-108">If a user sends a message using Outlook for Mac or Outlook on the web, you can't recall it.</span></span>

<span data-ttu-id="291ad-109">Da opozovete ili zamenite e-poruku:</span><span class="sxs-lookup"><span data-stu-id="291ad-109">To recall or replace an email message:</span></span>

1. <span data-ttu-id="291ad-110">U oknu fascikle na levoj strani prozora programa Outlook izaberite fasciklu poslate stavke.</span><span class="sxs-lookup"><span data-stu-id="291ad-110">In the folder pane on the left of the Outlook window, select the Sent Items folder.</span></span>
1. <span data-ttu-id="291ad-111">Kliknite dvaput na poruku koju želite da se setim da biste je otvorili.</span><span class="sxs-lookup"><span data-stu-id="291ad-111">Double-click the message you want to recall to open it.</span></span>
1. <span data-ttu-id="291ad-112">Izaberite karticu za **poruku** , a zatim izaberite **Radnje** > **Opozovi ovu poruku**.</span><span class="sxs-lookup"><span data-stu-id="291ad-112">Select the **Message** tab, and then select **Actions** > **Recall This Message**.</span></span>
1. <span data-ttu-id="291ad-113">Izaberite **Izbriši nepročitane kopije ove poruke** ili **Izbriši nepročitane kopije i zameni ih novom porukom**, a zatim izaberite **OK**.</span><span class="sxs-lookup"><span data-stu-id="291ad-113">Select **Delete unread copies of this message** or **Delete unread copies and replace with a new message**, and then select **OK**.</span></span>
1. <span data-ttu-id="291ad-114">Ako šaljete poruku zamenu, koristite za pisanje poruke, a zatim izaberite **Pošalji**.</span><span class="sxs-lookup"><span data-stu-id="291ad-114">If you're sending a replacement message, compose the message, and then select **Send**.</span></span>
1. <span data-ttu-id="291ad-115">Uspeh ili neuspeh opoziva poruke zavisi od primaoca postavke u programu Outlook.</span><span class="sxs-lookup"><span data-stu-id="291ad-115">The success or failure of a message recall depends on the recipient's settings in Outlook.</span></span> <span data-ttu-id="291ad-116">Korake da proveri opoziv, potražite u [ovom članku](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).</span><span class="sxs-lookup"><span data-stu-id="291ad-116">For steps to check on the recall, see [this article](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).</span></span>

<span data-ttu-id="291ad-117">Pronađite i izbrišite poruke e-pošte u vašoj organizaciji</span><span class="sxs-lookup"><span data-stu-id="291ad-117">Search for and delete email messages in your organization</span></span>

- <span data-ttu-id="291ad-118">Ako ti nisi globalne admin, vaš račun mora da se doda na eDiscovery Manager ulogu ili ulogu upravljanja usklađenosti pretragu da biste pronašli poruke.</span><span class="sxs-lookup"><span data-stu-id="291ad-118">If you're not a global admin, your account must be added to the eDiscovery Manager role or Compliance Search management role to search for messages.</span></span> <span data-ttu-id="291ad-119">Da biste izbrisali poruke, moraćete da se pridruži grupi uloga upravljanje organizacijom ili uloga za upravljanje pretraživanja i očisti.</span><span class="sxs-lookup"><span data-stu-id="291ad-119">To delete messages, you'll need to join the Organization Management role group or the Search and Purge management role.</span></span> <span data-ttu-id="291ad-120">Dozvole za ove uloge dodeljuju na [Centar za sigurnost i usklađenosti](https://go.microsoft.com/fwlink/?linkid=2083731).</span><span class="sxs-lookup"><span data-stu-id="291ad-120">Permissions for these roles are assigned in the [Security and compliance center](https://go.microsoft.com/fwlink/?linkid=2083731).</span></span>
- <span data-ttu-id="291ad-121">[Kreiraj sadržaj pretragu](https://docs.microsoft.com/office365/securitycompliance/content-search) pronaći poruku da biste je izbrisali.</span><span class="sxs-lookup"><span data-stu-id="291ad-121">[Create a content search](https://docs.microsoft.com/office365/securitycompliance/content-search) to find the message to delete.</span></span>
- <span data-ttu-id="291ad-122">[Povezivanje sa sigurnosti i usklađenosti centar PowerShell](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).</span><span class="sxs-lookup"><span data-stu-id="291ad-122">[Connect to Security and Compliance Center PowerShell](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).</span></span>

<span data-ttu-id="291ad-123">Ako koristite višestruku potvrdu identiteta, vidim da je [Povezivanje sa Office 365 sigurnosti i usklađenosti centar PowerShell koristeći višestruku potvrdu identiteta](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).</span><span class="sxs-lookup"><span data-stu-id="291ad-123">If you're using multi-factor authentication, see [Connect to Office 365 Security and Compliance Center PowerShell using multi-factor authentication](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).</span></span>