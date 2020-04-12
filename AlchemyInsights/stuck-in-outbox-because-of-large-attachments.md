---
title: Zaglavljena u otpremnom poštanskom sandučetu zbog velikih priloga
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2713"
- "9000768"
- "9002385"
- "4645"
ms.openlocfilehash: 35fe9ae76ca77faa43796b288af09be8525cb6df
ms.sourcegitcommit: 929f8accdca2b8e5be170e0fc8edd527581453d4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/12/2020
ms.locfileid: "43232644"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a><span data-ttu-id="b8af0-102">Popravljanje poruka koje su zaglavljena u otpremnom poštanskom sandučetu</span><span class="sxs-lookup"><span data-stu-id="b8af0-102">Fix messages that are stuck in the Outbox</span></span>

<span data-ttu-id="b8af0-103">Preporučujemo da počnete pokretanjem scenarija "Imam problema sa [slanjem, prijemom ili pronalaženjem e-poruka"](https://aka.ms/SaRA-OutlookSendReceive) sa Microsoft alatke " [Pomoćnik za podršku i oporavak](https://diagnostics.office.com/#/) " na računaru sa pogođenim računarom.</span><span class="sxs-lookup"><span data-stu-id="b8af0-103">We recommend that you start by running the scenario ["I'm having problems sending, receiving, or finding email messages"](https://aka.ms/SaRA-OutlookSendReceive) from the [Microsoft Support and Recovery Assistant](https://diagnostics.office.com/#/) tool on the affected machine.</span></span>

<span data-ttu-id="b8af0-104">Kada se poruka zaglavi u vašem otpremnom poštanskom sandučetu, Najverovatniji uzrok je veliki prilog ili opcija "Pošalji odmah kada veza" nije omogućena.</span><span class="sxs-lookup"><span data-stu-id="b8af0-104">When a message gets stuck in your Outbox, the most likely cause is a large attachment or the option "Send immediately when connected" is not enabled.</span></span>

<span data-ttu-id="b8af0-105">**Uklanjanje velikog priloga**</span><span class="sxs-lookup"><span data-stu-id="b8af0-105">**Remove the large attachment**</span></span>

1. <span data-ttu-id="b8af0-106">Kliknite na dugme **Pošalji/primi** > **van mreže**.</span><span class="sxs-lookup"><span data-stu-id="b8af0-106">Click **Send / Receive** > **Work Offline**.</span></span> 
2. <span data-ttu-id="b8af0-107">U oknu za navigaciju izaberite stavku **Otpremno poštansko sanduče**.</span><span class="sxs-lookup"><span data-stu-id="b8af0-107">In the navigation pane, click **Outbox**.</span></span> <span data-ttu-id="b8af0-108">Odavde možete da:</span><span class="sxs-lookup"><span data-stu-id="b8af0-108">From here, you can:</span></span> 
    - <span data-ttu-id="b8af0-109">Izbrišite poruku.</span><span class="sxs-lookup"><span data-stu-id="b8af0-109">Delete the message.</span></span> <span data-ttu-id="b8af0-110">Samo ga izaberite i kliknite na dugme **Izbriši**.</span><span class="sxs-lookup"><span data-stu-id="b8af0-110">Just select it and click **Delete**.</span></span>
    - <span data-ttu-id="b8af0-111">Prevucite poruku u **fasciklu "radne verzije**", dvaput kliknite da biste otvorili poruku i izbrišite prilog (kliknite na nju i kliknite na dugme " **Izbriši**").</span><span class="sxs-lookup"><span data-stu-id="b8af0-111">Drag the message to your **drafts folder**, double-click to open the message, and delete the attachment (click it and click **Delete**).</span></span>
3. <span data-ttu-id="b8af0-112">Ako vam greška saopštava da Outlook pokušava da prenese poruku, zatvorite Outlook.</span><span class="sxs-lookup"><span data-stu-id="b8af0-112">If an error tells you Outlook is trying to transmit the message, close Outlook.</span></span> <span data-ttu-id="b8af0-113">Za izlazak može potrajati nekoliko trenutaka.</span><span class="sxs-lookup"><span data-stu-id="b8af0-113">It may take a few moments to exit.</span></span> <span data-ttu-id="b8af0-114">Ako se Outlook ne zatvori, pritisnite **tastere CTRL + ALT + DELETE** i kliknite na dugme " **Pokreni Menadžer zadataka**".</span><span class="sxs-lookup"><span data-stu-id="b8af0-114">If Outlook doesn't close, press **Ctrl+Alt+Delete** and click **Start Task Manager**.</span></span> <span data-ttu-id="b8af0-115">U upravljaču zadacima izaberite karticu **procesi** , pomerite se nadole do stavke Outlook. exe, a zatim izaberite stavku **završi proces**.</span><span class="sxs-lookup"><span data-stu-id="b8af0-115">In Task Manager, select the **Processes** tab, scroll down to outlook.exe, and click **End Process**.</span></span>
4. <span data-ttu-id="b8af0-116">Nakon što se Outlook zatvori, ponovo pokrenite Outlook i ponovite korake 2-3.</span><span class="sxs-lookup"><span data-stu-id="b8af0-116">After Outlook closes, restart Outlook and repeat steps 2-3.</span></span> 
5. <span data-ttu-id="b8af0-117">Kada uklonite prilog, kliknite na dugme " **Pošalji/primi** > **rad van mreže** " da biste poništili izbor dugmeta i nastavili sa radom na mreži.</span><span class="sxs-lookup"><span data-stu-id="b8af0-117">After you remove the attachment, click **Send / Receive** > **Work Offline** to deselect the button and to resume working online.</span></span> 

<span data-ttu-id="b8af0-118">Poruke se takođe zaglave u otpremnom poštanskom sandučetu kada kliknete na dugme " **Pošalji**", ali niste povezani.</span><span class="sxs-lookup"><span data-stu-id="b8af0-118">Messages also get stuck in the Outbox when you click **Send**, but you are not connected.</span></span> <span data-ttu-id="b8af0-119">Kliknite na dugme " **Pošalji/primi** " i pogledajte dugme " **radi van mreže** ".</span><span class="sxs-lookup"><span data-stu-id="b8af0-119">Click **Send / Receive** and look at the **Work Offline** button.</span></span> <span data-ttu-id="b8af0-120">Ako je plava, veza je prekinuta.</span><span class="sxs-lookup"><span data-stu-id="b8af0-120">If it's blue, you're disconnected.</span></span> <span data-ttu-id="b8af0-121">Kliknite na nju da biste se povezali (dugme postaje belo) i kliknite na dugme " **Pošalji sve**".</span><span class="sxs-lookup"><span data-stu-id="b8af0-121">Click it to connect (the button turns white) and click **Send All**.</span></span>
 
<span data-ttu-id="b8af0-122">**Omogući slanje odmah nakon povezivanja**</span><span class="sxs-lookup"><span data-stu-id="b8af0-122">**Enable Send immediately when connected**</span></span>
 
1. <span data-ttu-id="b8af0-123">Na kartici datoteka izaberite stavku **Opcije**.</span><span class="sxs-lookup"><span data-stu-id="b8af0-123">On the File tab, click **Options**.</span></span>

2. <span data-ttu-id="b8af0-124">U dijalogu "Opcije programa Outlook" kliknite na dugme " **Više opcija**".</span><span class="sxs-lookup"><span data-stu-id="b8af0-124">In the Outlook Options dialog box, click **Advanced**.</span></span>

3. <span data-ttu-id="b8af0-125">U odeljku slanje i prijem kliknite da biste omogućili **Slanje odmah nakon povezivanja**.</span><span class="sxs-lookup"><span data-stu-id="b8af0-125">In the Send and receive section, click to enable **Send immediately when connected**.</span></span> <span data-ttu-id="b8af0-126">Kliknite na dugme **U redu**.</span><span class="sxs-lookup"><span data-stu-id="b8af0-126">Click **OK**.</span></span>
 
<span data-ttu-id="b8af0-127">Za sve detalje pogledajte:</span><span class="sxs-lookup"><span data-stu-id="b8af0-127">For full details, see:</span></span>
- [<span data-ttu-id="b8af0-128">Video zapis: slanje ili brisanje zaglavljena e-poruke</span><span class="sxs-lookup"><span data-stu-id="b8af0-128">Video: Send or delete a stuck email</span></span>](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [<span data-ttu-id="b8af0-129">E-poruka ostaje u fascikli "Otpremno poštansko sanduče" dok ručno ne pokrenete operaciju slanja/prijema u programu Outlook</span><span class="sxs-lookup"><span data-stu-id="b8af0-129">Email stays in the Outbox folder until you manually initiate a send/receive operation in Outlook</span></span>](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
