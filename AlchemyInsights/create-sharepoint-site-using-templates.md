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
ms.openlocfilehash: b9009fdbdc2a5e7443151446daade1685d2f5d45
ms.sourcegitcommit: 317eeed39c7777a922442992d67733726c41d9e1
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/04/2020
ms.locfileid: "41770437"
---
# <a name="create-sharepoint-sites-using-templates"></a><span data-ttu-id="37d26-102">Kreiranje SharePoint lokacija pomoću predložaka</span><span class="sxs-lookup"><span data-stu-id="37d26-102">Create SharePoint sites using templates</span></span>

<span data-ttu-id="37d26-103">Mogućnost čuvanja lokacije kao predloška nije podržana sa modernim komunikacijama ili lokacijama timova.</span><span class="sxs-lookup"><span data-stu-id="37d26-103">The ability to save a site as a template is not supported with modern Communication or Team Sites.</span></span> <span data-ttu-id="37d26-104">Više informacija o korišćenju predložaka potražite u članku [Čuvanje, preuzimanje i otpremanje SharePoint lokacije kao predloška](https://docs.microsoft.com/sharepoint/dev/general-development/save-download-and-upload-a-sharepoint-site-as-a-template).</span><span class="sxs-lookup"><span data-stu-id="37d26-104">For more information about using templates see [Save, download and upload a SharePoint site as a template](https://docs.microsoft.com/sharepoint/dev/general-development/save-download-and-upload-a-sharepoint-site-as-a-template).</span></span>

<span data-ttu-id="37d26-105">Evo nekih uobičajenih problema/rešenja u vezi sa čuvanjem lokacije ili liste kao predloška u sistemu SharePoint online.</span><span class="sxs-lookup"><span data-stu-id="37d26-105">Here are some common issues/solutions regarding Saving a Site or List as a template in Sharepoint Online.</span></span> 

<span data-ttu-id="37d26-106">**Dugme "Sačuvaj predložak lokacije/liste" nije dostupno ili nedostaje**</span><span class="sxs-lookup"><span data-stu-id="37d26-106">**Save site/list template button is not available or missing**</span></span>

<span data-ttu-id="37d26-107">Administratori će morati da omoguće da prilagođena skripta omogući funkcije predloška.</span><span class="sxs-lookup"><span data-stu-id="37d26-107">Administrators will need to Allow Custom Script to enable the template features.</span></span> <span data-ttu-id="37d26-108">Za detaljne korake, primeri i razmatranja</span><span class="sxs-lookup"><span data-stu-id="37d26-108">For detailed steps, examples and considerations see</span></span> 

- [<span data-ttu-id="37d26-109">Dozvoljavanje ili sprečavanje prilagođene skripte</span><span class="sxs-lookup"><span data-stu-id="37d26-109">Allow or prevent custom script</span></span>](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)

- <span data-ttu-id="37d26-110">Lokacija "Sačuvaj lokaciju" kao predložak nije podržana i može da izazove probleme na lokacijama koje koriste infrastrukturu za objavljivanje SharePoint servera.</span><span class="sxs-lookup"><span data-stu-id="37d26-110">The Save site as template command is not supported and can cause problems on sites that use the SharePoint Server Publishing Infrastructure.</span></span>

<span data-ttu-id="37d26-111">**Nije moguće kreirati predložak lokacije ili on ne funkcioniše ispravno**</span><span class="sxs-lookup"><span data-stu-id="37d26-111">**The site template cannot be created or does not work correctly**</span></span>

<span data-ttu-id="37d26-112">Predlošku nedostaje [funkcija](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) i ne može da se aktivira.</span><span class="sxs-lookup"><span data-stu-id="37d26-112">The template may be missing a [feature](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) and won't activate.</span></span> <span data-ttu-id="37d26-113">Ako funkcija nije dostupna za aktivaciju u trenutnoj kolekciji lokacija, ne možete da koristite predložak lokacije da biste kreirali lokaciju.</span><span class="sxs-lookup"><span data-stu-id="37d26-113">If the feature is not available to activate in the current site collection, you cannot use the site template to create a site.</span></span>

- <span data-ttu-id="37d26-114">Proverite da li neke liste ili biblioteke premašuju [cenzus](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) od 5000 stavki, jer to može blokirati Kreiranje predloška lokacije.</span><span class="sxs-lookup"><span data-stu-id="37d26-114">Check to see if any lists or libraries exceed the [List View Limit Threshold](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) of 5000 items as this can block creation of a site template.</span></span>

- <span data-ttu-id="37d26-115">Lokacija možda koristi previše resursa i zato predložak lokacije premašuje ograničenje od 50 MB.</span><span class="sxs-lookup"><span data-stu-id="37d26-115">The site may be using too many resources and therefore the site template exceeds the 50 MB limit.</span></span>


- <span data-ttu-id="37d26-116">Postoje problemi sa prikazivanjem podataka sa liste koja koristi kolonu za pronalaženje.</span><span class="sxs-lookup"><span data-stu-id="37d26-116">There are problems displaying data from a list that uses a lookup column.</span></span> <span data-ttu-id="37d26-117">Više informacija potražite u članku [Lista generisanih predložaka ne prikazuje podatke sa ispravne liste za pronalaženje u sistemu SharePoint online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).</span><span class="sxs-lookup"><span data-stu-id="37d26-117">For more information, see [Template-generated list doesn't display data from the correct lookup list in SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).</span></span>

<span data-ttu-id="37d26-118">Detaljnije informacije o uobičajenim problemima i rešenjima potražite u okviru " [Kreiranje i korišćenje predložaka lokacije](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989)".</span><span class="sxs-lookup"><span data-stu-id="37d26-118">For more detailed information on common problems and solutions, please check [Create and use site templates](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span></span>



