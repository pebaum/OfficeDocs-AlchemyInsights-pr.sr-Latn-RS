---
title: E-poruka toka posla se ne šalje
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1586"
ms.openlocfilehash: 391d3a2dcc2676a405065115f375c802d2492119
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766147"
---
# <a name="workflow-email-is-not-being-sent-for-a-sharepoint-list-or-library"></a><span data-ttu-id="bf4c9-102">E-poruka toka posla se ne šalje za SharePoint listu ili biblioteku</span><span class="sxs-lookup"><span data-stu-id="bf4c9-102">Workflow email is not being sent for a SharePoint list or library</span></span>

1. <span data-ttu-id="bf4c9-103">E-pošta iz tokova posla se ne šalje svim korisnicima ili samo određenim korisnicima ili vidite grešku **nije moguće poslati e-poruku. Uverite se da e-poruka ima važećeg primaoca**.</span><span class="sxs-lookup"><span data-stu-id="bf4c9-103">Email from workflows are not sent to all users or only specific users, or you see the error **The e-mail message cannot be sent. Make sure the e-mail has a valid recipient**.</span></span>

    <span data-ttu-id="bf4c9-104">Proverite da li korisnik postoji u grupi " **sve osobe** za dozvole" (Lista korisničkih informacija) za tu kolekciju lokacija.</span><span class="sxs-lookup"><span data-stu-id="bf4c9-104">Check if the user exist in the **All People** permissions group (user information list) for that site collection.</span></span>  <span data-ttu-id="bf4c9-105">Uzorak direktne URL adrese:<tenant>https://.<sitename>SharePoint.com/sites//_layouts/15/ljudi .aspx? Grupa špeditera = 0</span><span class="sxs-lookup"><span data-stu-id="bf4c9-105">Sample direct URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx?MembershipGroupId=0</span></span>

    - <span data-ttu-id="bf4c9-106">Ako korisnik ne postoji, proverite da li je korisnik prijavljen na stranicu.</span><span class="sxs-lookup"><span data-stu-id="bf4c9-106">If the user does not exist, make sure the user is signed into the page.</span></span> 
    - <span data-ttu-id="bf4c9-107">Ako je to spoljni korisnik, uverite se da je poziv prihvaćen.</span><span class="sxs-lookup"><span data-stu-id="bf4c9-107">If it is an external user, make sure that their invitation has been accepted.</span></span>
    - <span data-ttu-id="bf4c9-108">Ako korisnik ne postoji u grupi dozvola, uverite se da je e-adresa tačna.</span><span class="sxs-lookup"><span data-stu-id="bf4c9-108">If the user does exist in the permissions group, make sure the email address is correct.</span></span>
    - <span data-ttu-id="bf4c9-109">Ako ne postavite adresu e-pošte korisnika, onda Kreirajte obaveštenje za tog korisnika koji primorava sinhronizaciju tog korisničkog naloga od korisničkih profila u ovoj kolekciji lokacija.</span><span class="sxs-lookup"><span data-stu-id="bf4c9-109">If the users email address is not set here, then create a sample alert for that user which forces the sync of that user account from User Profiles of SharePoint to this site collection.</span></span>
 
2. <span data-ttu-id="bf4c9-110">E-pošta iz tokova posla se šalje administratorima kolekcije lokacija, ali ne ostalim korisnicima i vidi grešku koju je **http zabranjen za <span>https:</span>//URL/_vti_bin/Client.XVC.SP.Utilities.Utility.sendemail**.</span><span class="sxs-lookup"><span data-stu-id="bf4c9-110">Email from workflows are sent to the site collection administrators but not to other users and see the error **HTTP Forbidden to <span>https:</span>//URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**.</span></span>
 

    <span data-ttu-id="bf4c9-111">[Za slanje e-poruke SharePoint grupi vidite zabranu pristupa](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span><span class="sxs-lookup"><span data-stu-id="bf4c9-111">See [Access Denied when you send an email to a SharePoint group](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span></span>

    <span data-ttu-id="bf4c9-112">Takođe, proverite da li je u režimu za opciju "nije aktivna **dozvola za pristup** " za korisnike lokacije "Ograničeno".</span><span class="sxs-lookup"><span data-stu-id="bf4c9-112">Also, verify that the **Limited-access user permission lockdown mode** site collection feature is not active.</span></span>


## <a name="related-topics"></a><span data-ttu-id="bf4c9-113">Povezane teme</span><span class="sxs-lookup"><span data-stu-id="bf4c9-113">Related topics</span></span>
<span data-ttu-id="bf4c9-114">Želite li da isprobate Microsoft protok na SharePoint mreži?</span><span class="sxs-lookup"><span data-stu-id="bf4c9-114">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="bf4c9-115">Kreiraj tok</span><span class="sxs-lookup"><span data-stu-id="bf4c9-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="bf4c9-116">SharePoint i protok</span><span class="sxs-lookup"><span data-stu-id="bf4c9-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


