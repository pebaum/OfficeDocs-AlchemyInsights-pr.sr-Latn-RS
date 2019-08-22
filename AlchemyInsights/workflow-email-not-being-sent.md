---
title: Tok posla e-mail ne šalje
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 7/25/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1586"
ms.openlocfilehash: 261fe1b1bc815dd4ad568051cfefad1e214b957e
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36530902"
---
# <a name="workflow-email-is-not-being-sent-for-a-sharepoint-list-or-library"></a><span data-ttu-id="f7570-102">Tok posla e-mail ne šalje za SharePoint liste ili biblioteke</span><span class="sxs-lookup"><span data-stu-id="f7570-102">Workflow email is not being sent for a SharePoint list or library</span></span>

1. <span data-ttu-id="f7570-103">Mejl od tokova posla ne šalju se svim korisnicima ili samo određenim korisnicima, ili vidite da je greška u **poruci e-pošte nije moguće poslati. Uverite se da e-poruka nema važećeg primaoca**.</span><span class="sxs-lookup"><span data-stu-id="f7570-103">Email from workflows are not sent to all users or only specific users, or you see the error **The e-mail message cannot be sent. Make sure the e-mail has a valid recipient**.</span></span>

    <span data-ttu-id="f7570-104">Proveri da li korisnik postoje u **Svim ljudima** dozvole grupi (korisničke informacije lista) za tu kolekciju.</span><span class="sxs-lookup"><span data-stu-id="f7570-104">Check if the user exist in the **All People** permissions group (user information list) for that site collection.</span></span>  <span data-ttu-id="f7570-105">Uzorak direktni URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx? MembershipGroupId = 0</span><span class="sxs-lookup"><span data-stu-id="f7570-105">Sample direct URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx?MembershipGroupId=0</span></span>

    - <span data-ttu-id="f7570-106">Ako korisnik ne postoji, uverite se da korisnik bude potpisan u stranicu.</span><span class="sxs-lookup"><span data-stu-id="f7570-106">If the user does not exist, make sure the user is signed into the page.</span></span> 
    - <span data-ttu-id="f7570-107">Ako je spoljnog korisnika, uverite se da je njihov poziv je prihvaćen.</span><span class="sxs-lookup"><span data-stu-id="f7570-107">If it is an external user, make sure that their invitation has been accepted.</span></span>
    - <span data-ttu-id="f7570-108">Ako je korisnik postoji u grupi dozvole, uverite se da je e-adresa tačna.</span><span class="sxs-lookup"><span data-stu-id="f7570-108">If the user does exist in the permissions group, make sure the email address is correct.</span></span>
    - <span data-ttu-id="f7570-109">Ako e-adresa korisnika podešen ovde, zatim kreirajte primer obaveštenja za tog korisnika koje obavezuje sinhronizacije za taj korisnički nalog iz SharePoint profila korisnika u ovoj kolekciji lokacija.</span><span class="sxs-lookup"><span data-stu-id="f7570-109">If the users email address is not set here, then create a sample alert for that user which forces the sync of that user account from User Profiles of SharePoint to this site collection.</span></span>
 
2. <span data-ttu-id="f7570-110">E-mail iz tokovi posla se šalju administratorima kolekcije lokacija, ali ne i ostalim korisnicima, i vidim grešku **HTTP zabranjeno da <span>https:</span>//URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**.</span><span class="sxs-lookup"><span data-stu-id="f7570-110">Email from workflows are sent to the site collection administrators but not to other users and see the error **HTTP Forbidden to <span>https:</span>//URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**.</span></span>
 

    <span data-ttu-id="f7570-111">Vidim [Zabranjen pristup kada šaljete e-mail na SharePoint grupa](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span><span class="sxs-lookup"><span data-stu-id="f7570-111">See [Access Denied when you send an email to a SharePoint group](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span></span>

    <span data-ttu-id="f7570-112">Takođe, proverite da li funkciju kolekcije lokacija je **ograničen pristup korisnika dozvola pritajili** nije aktivan.</span><span class="sxs-lookup"><span data-stu-id="f7570-112">Also, verify that the **Limited-access user permission lockdown mode** site collection feature is not active.</span></span>


## <a name="related-topics"></a><span data-ttu-id="f7570-113">Povezane teme</span><span class="sxs-lookup"><span data-stu-id="f7570-113">Related topics</span></span>
<span data-ttu-id="f7570-114">Da probamo Microsoft Flow u SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="f7570-114">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="f7570-115">Kreiranje toka</span><span class="sxs-lookup"><span data-stu-id="f7570-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="f7570-116">SharePoint i protok</span><span class="sxs-lookup"><span data-stu-id="f7570-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


