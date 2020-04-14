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
ms.openlocfilehash: 4f69de167dc51961fa7cf71b4d73ca7ee3ed4d55
ms.sourcegitcommit: 57fb994ddd3854d06faa67680c971b003b06bf83
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/13/2020
ms.locfileid: "43241266"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a><span data-ttu-id="17a8b-102">Popravljanje poruka koje su zaglavljena u otpremnom poštanskom sandučetu</span><span class="sxs-lookup"><span data-stu-id="17a8b-102">Fix messages that are stuck in the Outbox</span></span>

<span data-ttu-id="17a8b-103">Preporučujemo da počnete pokretanjem scenarija "Imam problema sa [slanjem, prijemom ili pronalaženjem e-poruka"](https://aka.ms/SaRA-OutlookSendReceive) iz alatke [Microsoft pomoćnik za podršku i oporavak](https://diagnostics.office.com/#/) .</span><span class="sxs-lookup"><span data-stu-id="17a8b-103">We recommend that you start by running the scenario ["I'm having problems sending, receiving, or finding email messages"](https://aka.ms/SaRA-OutlookSendReceive) from the [Microsoft Support and Recovery Assistant](https://diagnostics.office.com/#/) tool.</span></span>

<span data-ttu-id="17a8b-104">Kada se poruka zaglavi u vašem otpremnom poštanskom sandučetu, Najverovatniji uzrok je veliki prilog ili opcija "Pošalji odmah kada veza" nije omogućena.</span><span class="sxs-lookup"><span data-stu-id="17a8b-104">When a message gets stuck in your Outbox, the most likely cause is a large attachment or the option "Send immediately when connected" is not enabled.</span></span>

<span data-ttu-id="17a8b-105">**Uklanjanje velikog priloga**</span><span class="sxs-lookup"><span data-stu-id="17a8b-105">**Remove the large attachment**</span></span>

1. <span data-ttu-id="17a8b-106">U programu Outlook izaberite opciju **Pošalji/primi** > **van mreže**.</span><span class="sxs-lookup"><span data-stu-id="17a8b-106">In Outlook, select **Send / Receive** > **Work Offline**.</span></span> 
2. <span data-ttu-id="17a8b-107">U oknu za navigaciju izaberite stavku **Otpremno poštansko sanduče**.</span><span class="sxs-lookup"><span data-stu-id="17a8b-107">In the navigation pane, select **Outbox**.</span></span> <span data-ttu-id="17a8b-108">Odavde možete da:</span><span class="sxs-lookup"><span data-stu-id="17a8b-108">From here, you can:</span></span> 
    - <span data-ttu-id="17a8b-109">Izbrišite poruku (izaberite je, a zatim izaberite **Izbriši**).</span><span class="sxs-lookup"><span data-stu-id="17a8b-109">Delete the message (select it and then select **Delete**).</span></span>
    - <span data-ttu-id="17a8b-110">Prevucite poruku u fasciklu "radne verzije", dvaput kliknite da biste je otvorili, a zatim uklonite prilog izaberite ga, a zatim kliknite na dugme " **Izbriši**".</span><span class="sxs-lookup"><span data-stu-id="17a8b-110">Drag the message to your Drafts folder, double-click to open it, and remove the attachment select it and then select **Delete**).</span></span>
3. <span data-ttu-id="17a8b-111">Ako dobijete grešku u kojoj piše da Outlook pokušava da prenese poruku, zatvorite Outlook.</span><span class="sxs-lookup"><span data-stu-id="17a8b-111">If you receive an error that says Outlook is trying to transmit the message, close Outlook.</span></span> <span data-ttu-id="17a8b-112">Za izlazak može potrajati nekoliko trenutaka.</span><span class="sxs-lookup"><span data-stu-id="17a8b-112">It may take a few moments to exit.</span></span> <span data-ttu-id="17a8b-113">Ako se Outlook ne zatvori, pritisnite tastere CTRL + ALT + DELETE i izaberite stavku **Pokretanje upravljača zadacima**.</span><span class="sxs-lookup"><span data-stu-id="17a8b-113">If Outlook doesn't close, press Ctrl+Alt+Delete and select **Start Task Manager**.</span></span> <span data-ttu-id="17a8b-114">U upravljaču zadacima izaberite karticu **procesi** , pomerite se nadole do stavke Outlook. exe i izaberite stavku **kraj procesa**.</span><span class="sxs-lookup"><span data-stu-id="17a8b-114">In Task Manager, select the **Processes** tab, scroll down to outlook.exe, and select **End Process**.</span></span>
4. <span data-ttu-id="17a8b-115">Nakon što se Outlook zatvori, ponovo ga pokrenite i ponovite korake 2 i 3.</span><span class="sxs-lookup"><span data-stu-id="17a8b-115">After Outlook closes, restart it and repeat steps 2 and 3.</span></span> 
5. <span data-ttu-id="17a8b-116">Kada uklonite prilog, kliknite na dugme " **Pošalji/primi** > **rad van mreže** " da biste nastavili sa radom na mreži.</span><span class="sxs-lookup"><span data-stu-id="17a8b-116">After you remove the attachment, click **Send / Receive** > **Work Offline** to resume working online.</span></span> 

<span data-ttu-id="17a8b-117">Poruke se takođe zaglave u otpremnom poštanskom sandučetu kada kliknete na dugme " **Pošalji**", ali niste povezani.</span><span class="sxs-lookup"><span data-stu-id="17a8b-117">Messages also get stuck in the Outbox when you click **Send**, but you are not connected.</span></span> <span data-ttu-id="17a8b-118">Kliknite na dugme " **Pošalji/primi** " i pogledajte dugme " **radi van mreže** ".</span><span class="sxs-lookup"><span data-stu-id="17a8b-118">Click **Send / Receive** and look at the **Work Offline** button.</span></span> <span data-ttu-id="17a8b-119">Ako je plava, veza je prekinuta.</span><span class="sxs-lookup"><span data-stu-id="17a8b-119">If it's blue, you're disconnected.</span></span> <span data-ttu-id="17a8b-120">Kliknite na nju da biste se povezali (dugme postaje belo) i kliknite na dugme " **Pošalji sve**".</span><span class="sxs-lookup"><span data-stu-id="17a8b-120">Click it to connect (the button turns white) and click **Send All**.</span></span>
 
<span data-ttu-id="17a8b-121">**Omogući slanje odmah nakon povezivanja**</span><span class="sxs-lookup"><span data-stu-id="17a8b-121">**Enable Send immediately when connected**</span></span>
 
1. <span data-ttu-id="17a8b-122">Na kartici datoteka izaberite stavku **Opcije**.</span><span class="sxs-lookup"><span data-stu-id="17a8b-122">On the File tab, click **Options**.</span></span>

2. <span data-ttu-id="17a8b-123">U dijalogu "Opcije programa Outlook" kliknite na dugme " **Više opcija**".</span><span class="sxs-lookup"><span data-stu-id="17a8b-123">In the Outlook Options dialog box, click **Advanced**.</span></span>

3. <span data-ttu-id="17a8b-124">U odeljku slanje i prijem kliknite da biste omogućili **Slanje odmah nakon povezivanja**.</span><span class="sxs-lookup"><span data-stu-id="17a8b-124">In the Send and receive section, click to enable **Send immediately when connected**.</span></span> <span data-ttu-id="17a8b-125">Kliknite na dugme **U redu**.</span><span class="sxs-lookup"><span data-stu-id="17a8b-125">Click **OK**.</span></span>
 
<span data-ttu-id="17a8b-126">Za sve detalje pogledajte:</span><span class="sxs-lookup"><span data-stu-id="17a8b-126">For full details, see:</span></span>
- [<span data-ttu-id="17a8b-127">Video zapis: slanje ili brisanje zaglavljena e-poruke</span><span class="sxs-lookup"><span data-stu-id="17a8b-127">Video: Send or delete a stuck email</span></span>](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [<span data-ttu-id="17a8b-128">E-poruka ostaje u fascikli "Otpremno poštansko sanduče" dok ručno ne pokrenete operaciju slanja/prijema u programu Outlook</span><span class="sxs-lookup"><span data-stu-id="17a8b-128">Email stays in the Outbox folder until you manually initiate a send/receive operation in Outlook</span></span>](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
