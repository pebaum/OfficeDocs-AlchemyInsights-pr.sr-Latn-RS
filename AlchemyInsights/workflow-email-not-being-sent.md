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
ms.openlocfilehash: 783bf0a5721aa5db7088432c71e06cac6dc90513
ms.sourcegitcommit: 407f6c1e82f1a0be5cf53301fbf03cd25dcbf0ee
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/02/2019
ms.locfileid: "36059617"
---
# <a name="workflow-email-is-not-being-sent"></a><span data-ttu-id="06b4c-102">Tok posla e-mail ne šalje</span><span class="sxs-lookup"><span data-stu-id="06b4c-102">Workflow email is not being sent</span></span>

1. <span data-ttu-id="06b4c-103">Mejl od tokova posla ne šalju se svim korisnicima ili samo određenim korisnicima, ili vidite da je greška u **poruci e-pošte nije moguće poslati. Uverite se da e-poruka nema važećeg primaoca**.</span><span class="sxs-lookup"><span data-stu-id="06b4c-103">Email from workflows are not sent to all users or only specific users, or you see the error **The e-mail message cannot be sent. Make sure the e-mail has a valid recipient**.</span></span>

<span data-ttu-id="06b4c-104">Proveri da li korisnik postoje u **Svim ljudima** dozvole grupi (korisničke informacije lista) za tu kolekciju.</span><span class="sxs-lookup"><span data-stu-id="06b4c-104">Check if the user exist in the **All People** permissions group (user information list) for that site collection.</span></span>  <span data-ttu-id="06b4c-105">Uzorak direktni URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx? MembershipGroupId = 0</span><span class="sxs-lookup"><span data-stu-id="06b4c-105">Sample direct URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx?MembershipGroupId=0</span></span>

- <span data-ttu-id="06b4c-106">Ako korisnik ne postoji, uverite se da korisnik bude potpisan u stranicu.</span><span class="sxs-lookup"><span data-stu-id="06b4c-106">If the user does not exist, make sure the user is signed into the page.</span></span> 
- <span data-ttu-id="06b4c-107">Ako je spoljnog korisnika, uverite se da je njihov poziv je prihvaćen.</span><span class="sxs-lookup"><span data-stu-id="06b4c-107">If it is an external user, make sure that their invitation has been accepted.</span></span>
- <span data-ttu-id="06b4c-108">Ako je korisnik postoji u grupi dozvole, uverite se da je e-adresa tačna.</span><span class="sxs-lookup"><span data-stu-id="06b4c-108">If the user does exist in the permissions group, make sure the email address is correct.</span></span>
- <span data-ttu-id="06b4c-109">Ako e-adresa korisnika podešen ovde, zatim kreirajte primer obaveštenja za tog korisnika koje obavezuje sinhronizacije za taj korisnički nalog iz SharePoint profila korisnika u ovoj kolekciji lokacija.</span><span class="sxs-lookup"><span data-stu-id="06b4c-109">If the users email address is not set here, then create a sample alert for that user which forces the sync of that user account from User Profiles of SharePoint to this site collection.</span></span>
 
2. <span data-ttu-id="06b4c-110">E-mail iz tokovi posla se šalju administratorima kolekcije lokacija, ali ne i ostalim korisnicima, i vidim grešku \*\*HTTP zabranjeno da <spam> <spam> \*\* <spam> <spam>.</span><span class="sxs-lookup"><span data-stu-id="06b4c-110">Email from Workflows are sent to the site collection administrators but not to other users and see the error **HTTP Forbidden to <spam><spam>https://URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**<spam><spam>.</span></span>
 

<span data-ttu-id="06b4c-111">Vidim [Zabranjen pristup kada poslate e-poruke za grupe](https://docs.microsoft.com/sharepoint/support/server-admin/access-denied-when-send-an-email-to-groups).</span><span class="sxs-lookup"><span data-stu-id="06b4c-111">See [Access Denied when sent email to groups](https://docs.microsoft.com/sharepoint/support/server-admin/access-denied-when-send-an-email-to-groups).</span></span>

<span data-ttu-id="06b4c-112">Takođe, proverite da li funkciju kolekcije lokacija je **ograničen pristup korisnika dozvola pritajili** nije aktivan.</span><span class="sxs-lookup"><span data-stu-id="06b4c-112">Also, verify that the **Limited-access user permission lockdown mode** site collection feature is not active.</span></span>

## <a name="related-topics"></a><span data-ttu-id="06b4c-113">Povezane teme</span><span class="sxs-lookup"><span data-stu-id="06b4c-113">Related topics</span></span>
- [<span data-ttu-id="06b4c-114">Kreiranje toka</span><span class="sxs-lookup"><span data-stu-id="06b4c-114">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="06b4c-115">SharePoint i protok</span><span class="sxs-lookup"><span data-stu-id="06b4c-115">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


