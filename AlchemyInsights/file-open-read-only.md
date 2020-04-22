---
title: Otvaranje datoteke samo za čitanje
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 39748581-d319-403c-8501-9b785e4a0ed8
ms.custom:
- "765"
- "2200014"
ms.openlocfilehash: c045188af15fcec0f868eb0e5b399bd1fb42a09a
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43702788"
---
# <a name="file-open-read-only"></a><span data-ttu-id="76ef0-102">Otvaranje datoteke samo za čitanje</span><span class="sxs-lookup"><span data-stu-id="76ef0-102">File open read-only</span></span>

<span data-ttu-id="76ef0-103">To možete pronaći kada otvarate datoteke, one se otvaraju samo za čitanje.</span><span class="sxs-lookup"><span data-stu-id="76ef0-103">You may find that when you are opening files, they open as read-only.</span></span> <span data-ttu-id="76ef0-104">U nekim slučajevima, ovo je za dodatnu bezbednost, kao što je slučaj kada otvarate datoteke sa interneta, a ponekad se može doći zbog postavke koja se može promeniti.</span><span class="sxs-lookup"><span data-stu-id="76ef0-104">In some cases, this is for added security, such as when you are opening files from the internet, and other times, it can be due to a setting that can be changed.</span></span> <span data-ttu-id="76ef0-105">Evo nekih scenarija u kojima datoteka otvara samo za čitanje i neke korake koje možete preduzeti da biste to promenili.</span><span class="sxs-lookup"><span data-stu-id="76ef0-105">Here are some scenarios where a file opens read-only and some steps you can take to change that.</span></span>
  
 <span data-ttu-id="76ef0-106">**Antivirusni program uzrokuje da otvori samo za čitanje**</span><span class="sxs-lookup"><span data-stu-id="76ef0-106">**My antivirus is causing them to open read-only**</span></span>
  
<span data-ttu-id="76ef0-107">Neki antivirusni programi mogu da vas zaštite od potencijalno nebezbednih datoteka tako što će ih otvoriti samo za čitanje.</span><span class="sxs-lookup"><span data-stu-id="76ef0-107">Some antivirus programs may protect you from potentially unsafe files by opening them read-only.</span></span> <span data-ttu-id="76ef0-108">Možda ćete morati da proverite kod dobavljača antivirusnog programa da biste saznali kako da podesite ove postavke.</span><span class="sxs-lookup"><span data-stu-id="76ef0-108">You may need to check with your antivirus provider to learn how to adjust these settings.</span></span> <span data-ttu-id="76ef0-109">BitDefender, na primer, ima sadržaj o dodavanju isključenih aplikacija ovde: [Kako da dodate isključivosti aplikacija ili procesa u kontrolnoj centru BitDefender](https://aka.ms/AA6098i).</span><span class="sxs-lookup"><span data-stu-id="76ef0-109">BitDefender, for example, has content on adding application exclusions here: [How to add application or process exclusions in Bitdefender Control Center](https://aka.ms/AA6098i).</span></span>
  
 <span data-ttu-id="76ef0-110">**Da li su svojstva datoteke podešena samo za čitanje?**</span><span class="sxs-lookup"><span data-stu-id="76ef0-110">**Are the file properties set to read-only?**</span></span>
  
<span data-ttu-id="76ef0-111">Svojstva datoteke možete da proverite tako što ćete kliknuti desnim tasterom miša na datoteku i odabrati stavku "Svojstva".</span><span class="sxs-lookup"><span data-stu-id="76ef0-111">You can check the file properties by right-clicking on the file and choosing Properties.</span></span> <span data-ttu-id="76ef0-112">Ako je atribut samo za čitanje proveren, možete da ga opozovete i kliknete na dugme "u redu".</span><span class="sxs-lookup"><span data-stu-id="76ef0-112">If the Read-only attribute is checked, you can uncheck it and click OK.</span></span>
  
 <span data-ttu-id="76ef0-113">**Sadržaj je u zaštićenom prikazu**</span><span class="sxs-lookup"><span data-stu-id="76ef0-113">**The content is in protected view**</span></span>
  
<span data-ttu-id="76ef0-114">Datoteke sa interneta i drugih potencijalno nebezbednih lokacija mogu da sadrže viruse, crve ili druge vrste malvera koji mogu da oštete računar.</span><span class="sxs-lookup"><span data-stu-id="76ef0-114">Files from the Internet and from other potentially unsafe locations can contain viruses, worms, or other kinds of malware that can harm your computer.</span></span> <span data-ttu-id="76ef0-115">Ovo je obično i slučaj sa prilozima e-pošte ili datotekama koje ste preuzeli.</span><span class="sxs-lookup"><span data-stu-id="76ef0-115">This is also commonly the case with email attachments or files you've downloaded.</span></span> <span data-ttu-id="76ef0-116">Da bi se vaš računar zaštitio, datoteke sa ovih potencijalno nebezbednih lokacija se otvaraju u zaštićenom prikazu.</span><span class="sxs-lookup"><span data-stu-id="76ef0-116">To help protect your computer, files from these potentially unsafe locations are opened in Protected View.</span></span> <span data-ttu-id="76ef0-117">Korišćenjem zaštićenog prikaza možete čitati datoteku i videti njen sadržaj dok umanjuje rizike.</span><span class="sxs-lookup"><span data-stu-id="76ef0-117">By using Protected View, you can read a file and see its contents while reducing the risks.</span></span> <span data-ttu-id="76ef0-118">Više informacija o zaštićenom prikazu i o tome kako da promenite postavke potražite u ovom članku: [Šta je zaštićeni prikaz?](https://support.office.com/article/d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)</span><span class="sxs-lookup"><span data-stu-id="76ef0-118">For more information on Protected view and how to change settings, see this article: [What is Protected View?](https://support.office.com/article/d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)</span></span>
  
 <span data-ttu-id="76ef0-119">**Da li je OneDrive puna?**</span><span class="sxs-lookup"><span data-stu-id="76ef0-119">**Is OneDrive full?**</span></span>
  
<span data-ttu-id="76ef0-120">Ako je datoteka uskladištena u usluzi OneDrive, a vaš prostor za skladištenje u usluzi OneDrive je pun, nećete moći da sačuvate dokument dok ne budete pod dodeljenim prostorom.</span><span class="sxs-lookup"><span data-stu-id="76ef0-120">If the file is stored on OneDrive and your OneDrive storage space is full, you will be unable to save the document until you are under your allotted space.</span></span> <span data-ttu-id="76ef0-121">Slobodno mesto u usluzi OneDrive možete da proverite tako što ćete kliknuti na ikonu OneDrive u okviru centra za obaveštenja i odabrati stavku "Upravljanje skladištem" [https://onedrive.live.com](https://onedrive.live.com)ili možete da odete na nju, da se prijavite i zabeležite količinu upotrebljenog prostora u donjem levom uglu ekrana.</span><span class="sxs-lookup"><span data-stu-id="76ef0-121">You can check your free space on OneDrive by clicking the OneDrive icon in the notification center and choosing Manage storage, or you can go to [https://onedrive.live.com](https://onedrive.live.com), sign in, and note the amount of used space in the lower left of the screen.</span></span>
  
 <span data-ttu-id="76ef0-122">**Da li je Office aktiviran?**</span><span class="sxs-lookup"><span data-stu-id="76ef0-122">**Is Office activated?**</span></span>
  
<span data-ttu-id="76ef0-123">Ako Office nije aktiviran ili ako je vaša pretplata istekla, možete da budete u režimu smanjene funkcionalnosti samo za čitanje.</span><span class="sxs-lookup"><span data-stu-id="76ef0-123">If Office is not activated, or if your subscription has expired, you could be in read-only Reduced Functionality Mode.</span></span> <span data-ttu-id="76ef0-124">Više informacija o aktiviranju sistema Office potražite u članku: [Nelicencirana greška proizvoda i aktivacije u sistemu Office](https://support.office.com/article/0d23d3c0-c19c-4b2f-9845-5344fedc4380).</span><span class="sxs-lookup"><span data-stu-id="76ef0-124">For information on how to Activate Office, see: [Unlicensed Product and activation errors in Office](https://support.office.com/article/0d23d3c0-c19c-4b2f-9845-5344fedc4380).</span></span>
  
 <span data-ttu-id="76ef0-125">**Ako ništa drugo ne uspe...**</span><span class="sxs-lookup"><span data-stu-id="76ef0-125">**If all else fails...**</span></span>
  
- <span data-ttu-id="76ef0-126">Pokušajte da ponovo pokrenete računar</span><span class="sxs-lookup"><span data-stu-id="76ef0-126">Try restarting the computer</span></span>
    
- <span data-ttu-id="76ef0-127">Instaliranje dopuna sistema Office</span><span class="sxs-lookup"><span data-stu-id="76ef0-127">Install Office updates</span></span>
    
- <span data-ttu-id="76ef0-128">Izvršite popravku na mreži za Office</span><span class="sxs-lookup"><span data-stu-id="76ef0-128">Perform an Online repair of Office</span></span>
    

