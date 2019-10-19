---
title: Outlook radna površina se opoziva ili zamenjuje e-poruku
ms.author: daeite
author: daeite
manager: joallard
ms.date: 3/13/2019
ms.audience: Admin
ms.topic: article
ms.custom: 9000260
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: 3d3a6c253317137b7069a978b907c97d61bf7313
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/18/2019
ms.locfileid: "36496125"
---
# <a name="recall-or-replace-an-outlook-email-message"></a><span data-ttu-id="acd74-102">Opozivanje ili zamenjivanje e-poruke programa Outlook</span><span class="sxs-lookup"><span data-stu-id="acd74-102">Recall or replace an Outlook email message</span></span>

- <span data-ttu-id="acd74-103">Kao administrator, možete da **opozovete poruke u ime korisnika pomoću programa "PowerShell**".</span><span class="sxs-lookup"><span data-stu-id="acd74-103">As the admin, you can **recall messages on behalf of users using PowerShell**.</span></span> <span data-ttu-id="acd74-104">Ne možete da opozovete poruke iz administratorskog centra.</span><span class="sxs-lookup"><span data-stu-id="acd74-104">You can't recall messages from the admin center.</span></span>
- <span data-ttu-id="acd74-105">Možete **samo da opozovete poruke koje se šalju osobama iz vaše organizacije**.</span><span class="sxs-lookup"><span data-stu-id="acd74-105">You can **only recall messages that are sent to people in your organization**.</span></span> <span data-ttu-id="acd74-106">Na primer, ako je poruka poslata na gmail adresu, ne možete je opozvati.</span><span class="sxs-lookup"><span data-stu-id="acd74-106">If the message was sent to a Gmail address, for example, you can't recall it.</span></span>
- <span data-ttu-id="acd74-107">Možete **samo da opozovete poruke poslate iz programa Outlook 2016 na računaru**.</span><span class="sxs-lookup"><span data-stu-id="acd74-107">You can **only recall messages sent from Outlook 2016 on the PC**.</span></span> <span data-ttu-id="acd74-108">Ako korisnik pošalje poruku pomoću programa Outlook za Mac ili Outlook na Webu, ne možete je opozvati.</span><span class="sxs-lookup"><span data-stu-id="acd74-108">If a user sends a message using Outlook for Mac or Outlook on the web, you can't recall it.</span></span>

<span data-ttu-id="acd74-109">Da biste opozvali ili zamenili e-poruku:</span><span class="sxs-lookup"><span data-stu-id="acd74-109">To recall or replace an email message:</span></span>

1. <span data-ttu-id="acd74-110">U oknu sa leve strane prozora programa Outlook izaberite fasciklu "Poslate stavke".</span><span class="sxs-lookup"><span data-stu-id="acd74-110">In the folder pane on the left of the Outlook window, select the Sent Items folder.</span></span>
1. <span data-ttu-id="acd74-111">Dvaput kliknite na poruku koju želite da opozovete da biste je otvorili.</span><span class="sxs-lookup"><span data-stu-id="acd74-111">Double-click the message you want to recall to open it.</span></span>
1. <span data-ttu-id="acd74-112">Izaberite karticu **poruka** , a zatim izaberite **Radnje** > **Opozovi ovu poruku**.</span><span class="sxs-lookup"><span data-stu-id="acd74-112">Select the **Message** tab, and then select **Actions** > **Recall This Message**.</span></span>
1. <span data-ttu-id="acd74-113">Izaberite stavku **Izbriši nepročitane kopije ove poruke** ili **Izbrišite nepročitane kopije i zamenite ih novom porukom**, a zatim kliknite na **dugme u redu**.</span><span class="sxs-lookup"><span data-stu-id="acd74-113">Select **Delete unread copies of this message** or **Delete unread copies and replace with a new message**, and then select **OK**.</span></span>
1. <span data-ttu-id="acd74-114">Ako šaljete poruku za zamenu, napišite poruku, a zatim kliknite na dugme " **Pošalji**".</span><span class="sxs-lookup"><span data-stu-id="acd74-114">If you're sending a replacement message, compose the message, and then select **Send**.</span></span>
1. <span data-ttu-id="acd74-115">Uspeh ili neuspeh opoziva poruke zavisi od postavki primaoca u programu Outlook.</span><span class="sxs-lookup"><span data-stu-id="acd74-115">The success or failure of a message recall depends on the recipient's settings in Outlook.</span></span> <span data-ttu-id="acd74-116">Da biste mogli da proverite opoziv, pogledajte [Ovaj članak](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).</span><span class="sxs-lookup"><span data-stu-id="acd74-116">For steps to check on the recall, see [this article](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).</span></span>

<span data-ttu-id="acd74-117">Traženje i brisanje e-poruka u vašoj organizaciji</span><span class="sxs-lookup"><span data-stu-id="acd74-117">Search for and delete email messages in your organization</span></span>

- <span data-ttu-id="acd74-118">Ako niste globalni administrator, vaš nalog mora biti dodat u ulogu eDiscovery menadžera ili u ulogu upravljanja pretragom usaglašenosti da biste potražili poruke.</span><span class="sxs-lookup"><span data-stu-id="acd74-118">If you're not a global admin, your account must be added to the eDiscovery Manager role or Compliance Search management role to search for messages.</span></span> <span data-ttu-id="acd74-119">Da biste izbrisali poruke, potrebno je da se pridružite grupi uloga za upravljanje organizacijom ili u ulozi za pretraživanje i čišćenje.</span><span class="sxs-lookup"><span data-stu-id="acd74-119">To delete messages, you'll need to join the Organization Management role group or the Search and Purge management role.</span></span> <span data-ttu-id="acd74-120">Dozvole za ove uloge se dodeljuju u [centru za bezbednost i usaglašenost](https://go.microsoft.com/fwlink/?linkid=2083731).</span><span class="sxs-lookup"><span data-stu-id="acd74-120">Permissions for these roles are assigned in the [Security and compliance center](https://go.microsoft.com/fwlink/?linkid=2083731).</span></span>
- <span data-ttu-id="acd74-121">[Kreirajte pretragu sadržaja](https://docs.microsoft.com/office365/securitycompliance/content-search) da biste pronašli poruku za brisanje.</span><span class="sxs-lookup"><span data-stu-id="acd74-121">[Create a content search](https://docs.microsoft.com/office365/securitycompliance/content-search) to find the message to delete.</span></span>
- <span data-ttu-id="acd74-122">[Poveži se sa bezbednošću i PowerShell centra za usaglašavanje](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).</span><span class="sxs-lookup"><span data-stu-id="acd74-122">[Connect to Security and Compliance Center PowerShell](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).</span></span>

<span data-ttu-id="acd74-123">Ako koristite nepotvrdu identiteta sa više faktora, pogledajte odeljak [Povezivanje sa lokacijom Office 365 Security i centar za usaglašavanje pomoću višefaktora potvrde identiteta](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).</span><span class="sxs-lookup"><span data-stu-id="acd74-123">If you're using multi-factor authentication, see [Connect to Office 365 Security and Compliance Center PowerShell using multi-factor authentication](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).</span></span>