---
title: SharePoint velike liste
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 2/12/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "407"
- "530001"
ms.assetid: ee07bf74-7aeb-4c47-8f5d-f496d6c09d79
ms.openlocfilehash: 222ad554de0d94dcfd4e34e9a2c6aa8ab4e6f81f
ms.sourcegitcommit: d7e1b097d3866782f508527c797426dc56c6ba17
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/14/2019
ms.locfileid: "37488531"
---
# <a name="work-with-large-lists-and-libraries-in-sharepoint"></a><span data-ttu-id="2fb46-102">Rad sa velikim listama i bibliotekama u sistemu SharePoint</span><span class="sxs-lookup"><span data-stu-id="2fb46-102">Work with large lists and libraries in SharePoint</span></span>

<span data-ttu-id="2fb46-103">SharePoint liste i biblioteke mogu da sadrže do 30.000.000 stavki, ali kada imaju više od 5.000 stavki, možda ćete videti grešku u prikazu liste kada pokušate da radite sa njima.</span><span class="sxs-lookup"><span data-stu-id="2fb46-103">SharePoint lists and libraries can contain up to 30 million items, but when they have more than 5,000 items, you might see a List View Threshold error when you try to work with them.</span></span> <span data-ttu-id="2fb46-104">Ovaj prag je na snazi da bi se održala efikasnost usluge.</span><span class="sxs-lookup"><span data-stu-id="2fb46-104">This threshold is in place to maintain performance of the service.</span></span> <span data-ttu-id="2fb46-105">Ne može se promeniti.</span><span class="sxs-lookup"><span data-stu-id="2fb46-105">It can't be changed.</span></span> <span data-ttu-id="2fb46-106">Da biste izbegli udaranje ove granice:</span><span class="sxs-lookup"><span data-stu-id="2fb46-106">To avoid hitting this threshold:</span></span>

<span data-ttu-id="2fb46-107">**Koristi moderne**</span><span class="sxs-lookup"><span data-stu-id="2fb46-107">**Use modern**</span></span>

<span data-ttu-id="2fb46-108">Prikazi koji prikazuju mnoge stavke najbolje rade u modernom iskustvu.</span><span class="sxs-lookup"><span data-stu-id="2fb46-108">Views showing many items work best in the modern experience.</span></span> <span data-ttu-id="2fb46-109">[Koristite moderan doživljaj](https://support.office.com/article/66dac24b-4177-4775-bf50-3d267318caa9) da biste izbegli greške koje možete da vidite u klasičnom iskustvu.</span><span class="sxs-lookup"><span data-stu-id="2fb46-109">[Use the modern experience](https://support.office.com/article/66dac24b-4177-4775-bf50-3d267318caa9) to avoid errors you might see in the classic experience.</span></span>

<span data-ttu-id="2fb46-110">**Dodavanje indeksa**</span><span class="sxs-lookup"><span data-stu-id="2fb46-110">**Add indexes**</span></span>

<span data-ttu-id="2fb46-111">Kada filtrirate ili sortirate po koloni koja nema indeks, možda ćete videti poruku o grešci.</span><span class="sxs-lookup"><span data-stu-id="2fb46-111">When you filter or sort by a column that doesn't have an index, you might see an error message.</span></span> <span data-ttu-id="2fb46-112">Ručno [Dodajte indeks](https://support.office.com/article/f3f00554-b7dc-44d1-a2ed-d477eac463b0) **iz menija sa postavkama u** meniju "Postavke", a zatim **Indeksirane kolone**.</span><span class="sxs-lookup"><span data-stu-id="2fb46-112">[Add an index](https://support.office.com/article/f3f00554-b7dc-44d1-a2ed-d477eac463b0) manually from **List Settings** in the settings menu, then **Indexed Columns**.</span></span>

<span data-ttu-id="2fb46-113">**Uređivanje prikaza liste**</span><span class="sxs-lookup"><span data-stu-id="2fb46-113">**Edit the list view**</span></span>

<span data-ttu-id="2fb46-114">Ako dođe do greške kada radite sa velikom listom, [uredite prikaz liste](https://support.office.com/article/15916903-e79a-423f-b4e2-02d37e1ff372).</span><span class="sxs-lookup"><span data-stu-id="2fb46-114">If an error occurs when working with a large list, [edit your list view](https://support.office.com/article/15916903-e79a-423f-b4e2-02d37e1ff372).</span></span>

<span data-ttu-id="2fb46-115">Sledeće četiri promene ukloniće greške u vezi sa prikazom liste.</span><span class="sxs-lookup"><span data-stu-id="2fb46-115">The following four changes will remove list view threshold errors.</span></span> <span data-ttu-id="2fb46-116">Izvršite sve četiri promene da biste uklonili sve greške.</span><span class="sxs-lookup"><span data-stu-id="2fb46-116">Make all four changes to remove all errors.</span></span> <span data-ttu-id="2fb46-117">Ako i dalje dobijate greške, proverite [Upravljanje velikim listama i bibliotekama](https://support.office.com/article/B8588DAE-9387-48C2-9248-C24122F07C59).</span><span class="sxs-lookup"><span data-stu-id="2fb46-117">If you are still getting errors, check [Manage large lists and libraries](https://support.office.com/article/B8588DAE-9387-48C2-9248-C24122F07C59).</span></span>

1. <span data-ttu-id="2fb46-118">Izaberite **ništa** od **prvog sortiranja po koloni** , a **Zatim sortirajte po koloni**.</span><span class="sxs-lookup"><span data-stu-id="2fb46-118">Select **None** from both **First sort by the column** and **Then sort by the column**.</span></span>
2. <span data-ttu-id="2fb46-119">Izaberite **nijedno** od **prve grupe po koloni** , a **zatim Grupiši po koloni**.</span><span class="sxs-lookup"><span data-stu-id="2fb46-119">Select **None** from both **First group by the column** and **Then group by the column**.</span></span>
3. <span data-ttu-id="2fb46-120">Izaberite **nijedno** za sve kolone u odeljku " **ukupne vrednosti** ".</span><span class="sxs-lookup"><span data-stu-id="2fb46-120">Select **None** for all columns in the **Totals** section.</span></span>
4. <span data-ttu-id="2fb46-121">Opozovite izbor za sve osim jedne kolone za prikaz iz odeljka " **kolone** ".</span><span class="sxs-lookup"><span data-stu-id="2fb46-121">Deselect all but one column for display from the **Columns** section.</span></span>

