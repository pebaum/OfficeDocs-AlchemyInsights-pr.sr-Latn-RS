---
title: Kreiranje lokacije u sistemu SharePoint online
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 84f2b70e-2b23-4039-8305-85783798feed
ms.openlocfilehash: 458990889d3c074820527982cbfa6e2d198d3e66
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40052483"
---
# <a name="create-sharepoint-sites-using-templates"></a><span data-ttu-id="b08be-102">Kreiranje SharePoint lokacija pomoću predložaka</span><span class="sxs-lookup"><span data-stu-id="b08be-102">Create SharePoint sites using templates</span></span>

<span data-ttu-id="b08be-103">Predlošci SharePoint lokacija su unapred ugrađene definicije dizajnirane oko određenog poslovnog potreba.</span><span class="sxs-lookup"><span data-stu-id="b08be-103">SharePoint site templates are prebuilt definitions designed around a particular business need.</span></span> <span data-ttu-id="b08be-104">Više informacija potražite u članku [Korišćenje predložaka za kreiranje različitih vrsta SharePoint lokacija](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span><span class="sxs-lookup"><span data-stu-id="b08be-104">For more information, see [Using templates to create different kinds of SharePoint sites](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span></span>

<span data-ttu-id="b08be-105">Evo nekih uobičajenih problema/rešenja u vezi sa čuvanjem lokacije ili liste kao predloška u sistemu SharePoint online.</span><span class="sxs-lookup"><span data-stu-id="b08be-105">Here are some common issues/solutions regarding Saving a Site or List as a template in Sharepoint Online.</span></span> 

<span data-ttu-id="b08be-106">**Dugme "Sačuvaj predložak lokacije/liste" nije dostupno ili nedostaje**</span><span class="sxs-lookup"><span data-stu-id="b08be-106">**Save site/list template button is not available or missing**</span></span>

<span data-ttu-id="b08be-107">Administratori će morati da omoguće da prilagođena skripta omogući funkcije predloška.</span><span class="sxs-lookup"><span data-stu-id="b08be-107">Administrators will need to Allow Custom Script to enable the template features.</span></span> <span data-ttu-id="b08be-108">Za detaljne korake, primeri i razmatranja</span><span class="sxs-lookup"><span data-stu-id="b08be-108">For detailed steps, examples and considerations see</span></span> 

- [<span data-ttu-id="b08be-109">Dozvoljavanje ili sprečavanje prilagođene skripte</span><span class="sxs-lookup"><span data-stu-id="b08be-109">Allow or prevent custom script</span></span>](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)

- <span data-ttu-id="b08be-110">Lokacija "Sačuvaj lokaciju" kao predložak nije podržana i može da izazove probleme na lokacijama koje koriste infrastrukturu za objavljivanje SharePoint servera.</span><span class="sxs-lookup"><span data-stu-id="b08be-110">The Save site as template command is not supported and can cause problems on sites that use the SharePoint Server Publishing Infrastructure.</span></span>

<span data-ttu-id="b08be-111">**Nije moguće kreirati predložak lokacije ili on ne funkcioniše ispravno**</span><span class="sxs-lookup"><span data-stu-id="b08be-111">**The site template cannot be created or does not work correctly**</span></span>

<span data-ttu-id="b08be-112">Predlošku nedostaje [funkcija](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) i ne može da se aktivira.</span><span class="sxs-lookup"><span data-stu-id="b08be-112">The template may be missing a [feature](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) and won't activate.</span></span> <span data-ttu-id="b08be-113">Ako funkcija nije dostupna za aktivaciju u trenutnoj kolekciji lokacija, ne možete da koristite predložak lokacije da biste kreirali lokaciju.</span><span class="sxs-lookup"><span data-stu-id="b08be-113">If the feature is not available to activate in the current site collection, you cannot use the site template to create a site.</span></span>

- <span data-ttu-id="b08be-114">Proverite da li neke liste ili biblioteke premašuju [cenzus](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) od 5000 stavki, jer to može blokirati Kreiranje predloška lokacije.</span><span class="sxs-lookup"><span data-stu-id="b08be-114">Check to see if any lists or libraries exceed the [List View Limit Threshold](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) of 5000 items as this can block creation of a site template.</span></span>

- <span data-ttu-id="b08be-115">Lokacija možda koristi previše resursa i zato predložak lokacije premašuje ograničenje od 50 MB.</span><span class="sxs-lookup"><span data-stu-id="b08be-115">The site may be using too many resources and therefore the site template exceeds the 50 MB limit.</span></span>


- <span data-ttu-id="b08be-116">Postoje problemi sa prikazivanjem podataka sa liste koja koristi kolonu za pronalaženje.</span><span class="sxs-lookup"><span data-stu-id="b08be-116">There are problems displaying data from a list that uses a lookup column.</span></span> <span data-ttu-id="b08be-117">Više informacija potražite u članku [Lista generisanih predložaka ne prikazuje podatke sa ispravne liste za pronalaženje u sistemu SharePoint online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).</span><span class="sxs-lookup"><span data-stu-id="b08be-117">For more information, see [Template-generated list doesn't display data from the correct lookup list in SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).</span></span>

<span data-ttu-id="b08be-118">Detaljnije informacije o uobičajenim problemima i rešenjima potražite u okviru " [Kreiranje i korišćenje predložaka lokacije](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989)".</span><span class="sxs-lookup"><span data-stu-id="b08be-118">For more detailed information on common problems and solutions, please check [Create and use site templates](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span></span>



