---
title: Sačuvaj lokaciju ili listu kao predložak
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 368ff1fa-82cf-4a07-986e-140b212ffc5c
ms.openlocfilehash: 7930551c0938501d006f791491594f9d6d9ba260
ms.sourcegitcommit: 56c52c73e752414d66785f175c3a0e2925ad41c1
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/02/2019
ms.locfileid: "31044018"
---
# <a name="save-site-or-list-as-a-template"></a><span data-ttu-id="244c4-102">Sačuvaj lokaciju ili listu kao predložak</span><span class="sxs-lookup"><span data-stu-id="244c4-102">Save site or list as a template</span></span>

<span data-ttu-id="244c4-103">Predlošci lokacija SharePoint su izgrađenom definicije dizajniran oko specifičnim poslovnim potrebama.</span><span class="sxs-lookup"><span data-stu-id="244c4-103">SharePoint site templates are prebuilt definitions designed around a particular business need.</span></span> <span data-ttu-id="244c4-104">Za više informacija, pogledajte [koristeći predloške da biste kreirali različite vrste SharePoint lokacije](https://support.office.com/en-us/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span><span class="sxs-lookup"><span data-stu-id="244c4-104">For more information, see [Using templates to create different kinds of SharePoint sites](https://support.office.com/en-us/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span></span>

<span data-ttu-id="244c4-105">Evo nekih uobičajenih pitanja/rešenja u pogledu čuvanja na lokaciju ili listu kao predložak u SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="244c4-105">Here are some common issues/solutions regarding Saving a Site or List as a template in SharePoint Online.</span></span>

<span data-ttu-id="244c4-106">**Lista lokacija/predložak dugme je spasi nije dostupan ili nedostaje**.</span><span class="sxs-lookup"><span data-stu-id="244c4-106">**Save site/list template button is not available or missing**.</span></span> 

- <span data-ttu-id="244c4-107">Administratori morat ćete omogućiti skripte Prilagođeno da biste omogućili funkcije predloška.</span><span class="sxs-lookup"><span data-stu-id="244c4-107">Administrators will need to Allow Custom Script to enable the template features.</span></span> <span data-ttu-id="244c4-108">Detaljni koraci, primeri i razmatranja potražite u [Dozvoli ili sprečavaju adaptirani scenario](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script).</span><span class="sxs-lookup"><span data-stu-id="244c4-108">For detailed steps, examples and considerations see [Allow or prevent custom script](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script).</span></span>


- <span data-ttu-id="244c4-109">Sačuvaj lokaciju kao predložak komanda nije podržano i može da izazove probleme na lokacijama koje koriste SharePoint Server Publishing infrastrukturu.</span><span class="sxs-lookup"><span data-stu-id="244c4-109">The Save site as template command is not supported and can cause problems on sites that use the SharePoint Server Publishing Infrastructure.</span></span>


**<span data-ttu-id="244c4-110">Predložak lokacije nije moguće kreirati ili ne radi ispravno</span><span class="sxs-lookup"><span data-stu-id="244c4-110">The site template cannot be created or does not work correctly</span></span>**

- <span data-ttu-id="244c4-111">Obrazac može biti nedostaje [funkcija](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) i neće aktivirati.</span><span class="sxs-lookup"><span data-stu-id="244c4-111">The template may be missing a [feature](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) and won’t activate.</span></span> <span data-ttu-id="244c4-112">Ako funkcija nije dostupna za aktivaciju u trenutnoj kolekciji, predložak lokacije ne možete da kreirate lokaciju.</span><span class="sxs-lookup"><span data-stu-id="244c4-112">If the feature is not available to activate in the current site collection, you cannot use the site template to create a site.</span></span>


- <span data-ttu-id="244c4-113">Proverite da li ako liste ili biblioteke da premaši [Prag ograničenje prikaza liste](https://support.office.com/en-us/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) od 5000 artikala kao što to možete blokirati stvaranje predložak.</span><span class="sxs-lookup"><span data-stu-id="244c4-113">Check to see if any lists or libraries exceed the [List View Limit Threshold](https://support.office.com/en-us/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) of 5000 items as this can block creation of a site template.</span></span>


- <span data-ttu-id="244c4-114">Lokacija možda koristi previše resursa i stoga je predložak lokacije premašuje ograničenje od 50 megabajta (MB).</span><span class="sxs-lookup"><span data-stu-id="244c4-114">The site may be using too many resources and therefore the site template exceeds the 50 megabyte (MB) limit.</span></span>


- <span data-ttu-id="244c4-115">Postoje problemi u prikazivanju podataka iz liste u kojoj se koristi kolone za pronalaženje.</span><span class="sxs-lookup"><span data-stu-id="244c4-115">There are problems displaying data from a list that uses a lookup column.</span></span> <span data-ttu-id="244c4-116">Više informacija potražite u odeljku [generiše predložak liste ne prikaže podatke iz liste ispravne za pronalaženje u SharePoint Online](https://support.office.com/en-us/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a).</span><span class="sxs-lookup"><span data-stu-id="244c4-116">For more information, see [Template-generated list doesn’t display data from the correct lookup list in SharePoint Online](https://support.office.com/en-us/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a).</span></span>


<span data-ttu-id="244c4-117">Za detaljnije informacije o uobičajenim problemima i rešenjima molim referencu, [Kreiranje i upotreba predložaka lokacije](https://support.office.com/en-us/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span><span class="sxs-lookup"><span data-stu-id="244c4-117">For more detailed information on common problems and solutions please reference, [Create and use site templates](https://support.office.com/en-us/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span></span>

