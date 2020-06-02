---
title: Outlook radna površina se opoziva ili zamenjuje e-poruku
ms.author: daeite
author: daeite
manager: joallard
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.custom: 9000260
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: bb84363ae7d3c91750d5de789c091c7cebbbedc2
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44502333"
---
# <a name="recall-or-replace-an-outlook-email-message"></a><span data-ttu-id="24a2c-102">Opozivanje ili zamenjivanje e-poruke programa Outlook</span><span class="sxs-lookup"><span data-stu-id="24a2c-102">Recall or replace an Outlook email message</span></span>

- <span data-ttu-id="24a2c-103">Kao administrator, možete da **opozovete poruke u ime korisnika pomoću programa "PowerShell**".</span><span class="sxs-lookup"><span data-stu-id="24a2c-103">As the admin, you can **recall messages on behalf of users using PowerShell**.</span></span> <span data-ttu-id="24a2c-104">Ne možete da opozovete poruke iz administratorskog centra.</span><span class="sxs-lookup"><span data-stu-id="24a2c-104">You can't recall messages from the admin center.</span></span>
- <span data-ttu-id="24a2c-105">Možete **samo da opozovete poruke koje se šalju osobama iz vaše organizacije**.</span><span class="sxs-lookup"><span data-stu-id="24a2c-105">You can **only recall messages that are sent to people in your organization**.</span></span> <span data-ttu-id="24a2c-106">Na primer, ako je poruka poslata na gmail adresu, ne možete je opozvati.</span><span class="sxs-lookup"><span data-stu-id="24a2c-106">If the message was sent to a Gmail address, for example, you can't recall it.</span></span>
- <span data-ttu-id="24a2c-107">Možete **samo da opozovete poruke poslate iz programa Outlook 2016 na računaru**.</span><span class="sxs-lookup"><span data-stu-id="24a2c-107">You can **only recall messages sent from Outlook 2016 on the PC**.</span></span> <span data-ttu-id="24a2c-108">Ako korisnik pošalje poruku pomoću programa Outlook za Mac ili Outlook na Webu, ne možete je opozvati.</span><span class="sxs-lookup"><span data-stu-id="24a2c-108">If a user sends a message using Outlook for Mac or Outlook on the web, you can't recall it.</span></span>

<span data-ttu-id="24a2c-109">Da biste opozvali ili zamenili e-poruku:</span><span class="sxs-lookup"><span data-stu-id="24a2c-109">To recall or replace an email message:</span></span>

1. <span data-ttu-id="24a2c-110">U oknu sa leve strane prozora programa Outlook izaberite fasciklu "Poslate stavke".</span><span class="sxs-lookup"><span data-stu-id="24a2c-110">In the folder pane on the left of the Outlook window, select the Sent Items folder.</span></span>
1. <span data-ttu-id="24a2c-111">Dvaput kliknite na poruku koju želite da opozovete da biste je otvorili.</span><span class="sxs-lookup"><span data-stu-id="24a2c-111">Double-click the message you want to recall to open it.</span></span>
1. <span data-ttu-id="24a2c-112">Izaberite karticu **poruka** , a zatim izaberite **Radnje**  >  **Opozovi ovu poruku**.</span><span class="sxs-lookup"><span data-stu-id="24a2c-112">Select the **Message** tab, and then select **Actions** > **Recall This Message**.</span></span>
1. <span data-ttu-id="24a2c-113">Izaberite stavku **Izbriši nepročitane kopije ove poruke** ili **Izbrišite nepročitane kopije i zamenite ih novom porukom**, a zatim kliknite na **dugme u redu**.</span><span class="sxs-lookup"><span data-stu-id="24a2c-113">Select **Delete unread copies of this message** or **Delete unread copies and replace with a new message**, and then select **OK**.</span></span>
1. <span data-ttu-id="24a2c-114">Ako šaljete poruku za zamenu, napišite poruku, a zatim kliknite na dugme " **Pošalji**".</span><span class="sxs-lookup"><span data-stu-id="24a2c-114">If you're sending a replacement message, compose the message, and then select **Send**.</span></span>
1. <span data-ttu-id="24a2c-115">Uspeh ili neuspeh opoziva poruke zavisi od postavki primaoca u programu Outlook.</span><span class="sxs-lookup"><span data-stu-id="24a2c-115">The success or failure of a message recall depends on the recipient's settings in Outlook.</span></span> <span data-ttu-id="24a2c-116">Da biste mogli da proverite opoziv, pogledajte [Ovaj članak](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).</span><span class="sxs-lookup"><span data-stu-id="24a2c-116">For steps to check on the recall, see [this article](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).</span></span>

<span data-ttu-id="24a2c-117">Traženje i brisanje e-poruka u vašoj organizaciji</span><span class="sxs-lookup"><span data-stu-id="24a2c-117">Search for and delete email messages in your organization</span></span>

- <span data-ttu-id="24a2c-118">Ako niste globalni administrator, vaš nalog mora biti dodat u ulogu eDiscovery menadžera ili u ulogu upravljanja pretragom usaglašenosti da biste potražili poruke.</span><span class="sxs-lookup"><span data-stu-id="24a2c-118">If you're not a global admin, your account must be added to the eDiscovery Manager role or Compliance Search management role to search for messages.</span></span> <span data-ttu-id="24a2c-119">Da biste izbrisali poruke, potrebno je da se pridružite grupi uloga za upravljanje organizacijom ili u ulozi za pretraživanje i čišćenje.</span><span class="sxs-lookup"><span data-stu-id="24a2c-119">To delete messages, you'll need to join the Organization Management role group or the Search and Purge management role.</span></span> <span data-ttu-id="24a2c-120">Dozvole za ove uloge se dodeljuju u [centru za bezbednost i usaglašenost](https://go.microsoft.com/fwlink/?linkid=2083731).</span><span class="sxs-lookup"><span data-stu-id="24a2c-120">Permissions for these roles are assigned in the [Security and compliance center](https://go.microsoft.com/fwlink/?linkid=2083731).</span></span>
- <span data-ttu-id="24a2c-121">[Kreirajte pretragu sadržaja](https://docs.microsoft.com/microsoft-365/compliance/content-search) da biste pronašli poruku za brisanje.</span><span class="sxs-lookup"><span data-stu-id="24a2c-121">[Create a content search](https://docs.microsoft.com/microsoft-365/compliance/content-search) to find the message to delete.</span></span>
- <span data-ttu-id="24a2c-122">[Poveži se sa bezbednošću i PowerShell centra za usaglašavanje](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).</span><span class="sxs-lookup"><span data-stu-id="24a2c-122">[Connect to Security and Compliance Center PowerShell](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).</span></span>

<span data-ttu-id="24a2c-123">Ako koristite nepotvrdu identiteta sa više faktora, pogledajte odeljak [Povezivanje sa programom Microsoft 365 Security i centar za usaglašavanje pomoću višefaktora potvrde identiteta](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).</span><span class="sxs-lookup"><span data-stu-id="24a2c-123">If you're using multi-factor authentication, see [Connect to Microsoft 365 security and Compliance Center PowerShell using multi-factor authentication](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).</span></span>