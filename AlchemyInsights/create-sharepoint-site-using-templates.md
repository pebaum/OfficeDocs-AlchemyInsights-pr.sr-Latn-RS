---
title: Kreiranje lokacije u SharePoint Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 84f2b70e-2b23-4039-8305-85783798feed
ms.openlocfilehash: 9ab06cbd1648da31d8a04e61c237a2326b4bbe93
ms.sourcegitcommit: f856d46a325c517fc29d935c27f21b77c4219e66
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/24/2019
ms.locfileid: "35199287"
---
# <a name="create-sharepoint-sites-using-templates"></a><span data-ttu-id="cb386-102">Kreirati SharePoint lokacije pomoću predložaka</span><span class="sxs-lookup"><span data-stu-id="cb386-102">Create SharePoint sites using templates</span></span>

<span data-ttu-id="cb386-103">Predlošci lokacija SharePoint su izgrađenom definicije dizajniran oko specifičnim poslovnim potrebama.</span><span class="sxs-lookup"><span data-stu-id="cb386-103">SharePoint site templates are prebuilt definitions designed around a particular business need.</span></span> <span data-ttu-id="cb386-104">Za više informacija, pogledajte [koristeći predloške da biste kreirali različite vrste SharePoint lokacije](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span><span class="sxs-lookup"><span data-stu-id="cb386-104">For more information, see [Using templates to create different kinds of SharePoint sites](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span></span>

<span data-ttu-id="cb386-105">Evo nekih uobičajenih pitanja/rešenja u pogledu čuvanja na lokaciju ili listu kao predložak u Sharepoint Online.</span><span class="sxs-lookup"><span data-stu-id="cb386-105">Here are some common issues/solutions regarding Saving a Site or List as a template in Sharepoint Online.</span></span> 

<span data-ttu-id="cb386-106">**Čuvanje lokacije/lista predložak dugme nije dostupna ili nedostaju**</span><span class="sxs-lookup"><span data-stu-id="cb386-106">**Save site/list template button is not available or missing**</span></span>

<span data-ttu-id="cb386-107">Administratori morat ćete omogućiti skripte Prilagođeno da biste omogućili funkcije predloška.</span><span class="sxs-lookup"><span data-stu-id="cb386-107">Administrators will need to Allow Custom Script to enable the template features.</span></span> <span data-ttu-id="cb386-108">Detaljne korake, primeri i razmatranja potražite</span><span class="sxs-lookup"><span data-stu-id="cb386-108">For detailed steps, examples and considerations see</span></span> 

- [<span data-ttu-id="cb386-109">Omogućite ili sprečite adaptirani scenario</span><span class="sxs-lookup"><span data-stu-id="cb386-109">Allow or prevent custom script</span></span>](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)

- <span data-ttu-id="cb386-110">Sačuvaj lokaciju kao predložak komanda nije podržano i može da izazove probleme na lokacijama koje koriste SharePoint Server Publishing infrastrukturu.</span><span class="sxs-lookup"><span data-stu-id="cb386-110">The Save site as template command is not supported and can cause problems on sites that use the SharePoint Server Publishing Infrastructure.</span></span>

<span data-ttu-id="cb386-111">**Predložak lokacije nije moguće kreirati ili ne radi ispravno**</span><span class="sxs-lookup"><span data-stu-id="cb386-111">**The site template cannot be created or does not work correctly**</span></span>

<span data-ttu-id="cb386-112">Obrazac može biti nedostaje [funkcija](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) i neće aktivirati.</span><span class="sxs-lookup"><span data-stu-id="cb386-112">The template may be missing a [feature](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) and won't activate.</span></span> <span data-ttu-id="cb386-113">Ako funkcija nije dostupna za aktivaciju u trenutnoj kolekciji, predložak lokacije ne možete da kreirate lokaciju.</span><span class="sxs-lookup"><span data-stu-id="cb386-113">If the feature is not available to activate in the current site collection, you cannot use the site template to create a site.</span></span>

- <span data-ttu-id="cb386-114">Proverite da li ako liste ili biblioteke da premaši [Prag ograničenje prikaza liste](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) od 5000 artikala kao što to možete blokirati stvaranje predložak.</span><span class="sxs-lookup"><span data-stu-id="cb386-114">Check to see if any lists or libraries exceed the [List View Limit Threshold](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) of 5000 items as this can block creation of a site template.</span></span>

- <span data-ttu-id="cb386-115">Lokacija možda koristi previše resursa i stoga je predložak lokacije premašuje ograničenje 50 MB.</span><span class="sxs-lookup"><span data-stu-id="cb386-115">The site may be using too many resources and therefore the site template exceeds the 50 MB limit.</span></span>


- <span data-ttu-id="cb386-116">Postoje problemi u prikazivanju podataka iz liste u kojoj se koristi kolone za pronalaženje.</span><span class="sxs-lookup"><span data-stu-id="cb386-116">There are problems displaying data from a list that uses a lookup column.</span></span> <span data-ttu-id="cb386-117">Više informacija potražite u odeljku [generiše predložak liste ne prikaže podatke iz liste ispravne za pronalaženje u SharePoint Online](https://support.office.com/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a).</span><span class="sxs-lookup"><span data-stu-id="cb386-117">For more information, see [Template-generated list doesn't display data from the correct lookup list in SharePoint Online](https://support.office.com/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a).</span></span>

<span data-ttu-id="cb386-118">Za detaljnije informacije o zajedničkim problemima i rešenja, provjerite [predloške lokacija za kreiranje i upotrebu](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span><span class="sxs-lookup"><span data-stu-id="cb386-118">For more detailed information on common problems and solutions, please check [Create and use site templates](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span></span>



