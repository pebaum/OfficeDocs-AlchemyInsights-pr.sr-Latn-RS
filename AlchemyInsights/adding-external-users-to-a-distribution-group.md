---
title: Dodavanje spoljnih korisnika u grupu distribucije
ms.author: chrisda
author: chrisda
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: caa0f310-0bb7-48e3-8ad2-cb358b53bbba
ms.openlocfilehash: 7dbc69bced9ca800d3f95081b77dda5e49662579
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/27/2020
ms.locfileid: "43910946"
---
# <a name="add-external-users-to-a-distribution-group"></a><span data-ttu-id="051a8-102">Dodavanje spoljnih korisnika u grupu distribucije</span><span class="sxs-lookup"><span data-stu-id="051a8-102">Add external users to a Distribution Group</span></span>

<span data-ttu-id="051a8-103">Dodavanje spoljnog kontakta grupi za distribuciju (DG) je proces u dva koraka:</span><span class="sxs-lookup"><span data-stu-id="051a8-103">Adding an external contact to a Distribution Group (DG) is a two-step process:</span></span>
  
1. <span data-ttu-id="051a8-104">Kreirajte kontakt za e-poštu za spoljnog korisnika:</span><span class="sxs-lookup"><span data-stu-id="051a8-104">Create a Mail Contact for the external user:</span></span>
    
    1. <span data-ttu-id="051a8-105">U okviru administratorskog centra idite na stranicu " **Korisnici** > [kontakata](https://admin.microsoft.com/adminportal/home#/Contact) ".</span><span class="sxs-lookup"><span data-stu-id="051a8-105">In the admin center, go to the **Users** > [Contacts](https://admin.microsoft.com/adminportal/home#/Contact) page.</span></span> 
    
    2. <span data-ttu-id="051a8-106">Izaberite stavku **Dodaj kontakt**.</span><span class="sxs-lookup"><span data-stu-id="051a8-106">Select **Add a contact**.</span></span>
    
    3. <span data-ttu-id="051a8-107">Upišite informacije o svom kontaktu i kliknite na dugme " **Dodaj**".</span><span class="sxs-lookup"><span data-stu-id="051a8-107">Type the information for your contact and select **Add**.</span></span>
    
2. <span data-ttu-id="051a8-108">Dodajte kontakt iz pošte svom DG:</span><span class="sxs-lookup"><span data-stu-id="051a8-108">Add the Mail Contact to your DG:</span></span>
    
    1. <span data-ttu-id="051a8-109">U okviru administratorskog centra idite na **Groups** > stranicu grupe[grupe](https://admin.microsoft.com/adminportal/home#/groups) .</span><span class="sxs-lookup"><span data-stu-id="051a8-109">In the admin center, go to the **Groups** > [Groups](https://admin.microsoft.com/adminportal/home#/groups) page.</span></span> 
    
    2. <span data-ttu-id="051a8-110">Pronađite DG kojoj želite da dodate spoljnog korisnika i izaberite ga da biste otvorili dijalog "Uređivanje".</span><span class="sxs-lookup"><span data-stu-id="051a8-110">Find the DG you want to add the external user to, and select it to open the edit dialog.</span></span>
    
    3. <span data-ttu-id="051a8-111">Na kartici " **članovi** " izaberite stavku " **Prikaz svih članova" i "Upravljanje članovima**".</span><span class="sxs-lookup"><span data-stu-id="051a8-111">On the **Members** tab, select **View all and manage members**.</span></span> 
    
    4. <span data-ttu-id="051a8-112">Izaberite stavku **Dodaj članove**.</span><span class="sxs-lookup"><span data-stu-id="051a8-112">Select **Add members**.</span></span>
    
    5. <span data-ttu-id="051a8-113">Izaberite kontakt za poštu koji ste kreirali na prethodnom koraku, a zatim kliknite na dugme **Sačuvaj**.</span><span class="sxs-lookup"><span data-stu-id="051a8-113">Select the Mail Contact you created on the previous step, and then select **Save**.</span></span>
    
<span data-ttu-id="051a8-114">Ako nakon ovih koraka spoljni korisnici ne mogu da šalju e-poruke DG ili ne primaju e-poruke od nje, moguće je da je DG označen samo da bi omogućio e-poruke od unutrašnjih korisnika.</span><span class="sxs-lookup"><span data-stu-id="051a8-114">If after following these steps your external users can't send emails to the DG or don't receive emails from it, it could be that the DG is marked to only allow emails from internal users.</span></span> <span data-ttu-id="051a8-115">Ovu konfiguraciju možete da proverite i popravite na sledeći [način.](https://docs.microsoft.com/exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/fix-error-code-5-7-133-in-exchange-online)</span><span class="sxs-lookup"><span data-stu-id="051a8-115">You can check this configuration and fix it following the directions [here](https://docs.microsoft.com/exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/fix-error-code-5-7-133-in-exchange-online).</span></span>
  
 <span data-ttu-id="051a8-116">**Napomena:** Ova uputstva se ne primenjuju ako je tip grupe "Microsoft 365 grupa" umesto "grupa za distribuciju".</span><span class="sxs-lookup"><span data-stu-id="051a8-116">**Note:** These instructions don't apply if your group's type is "Microsoft 365 group" instead of "Distribution group."</span></span> <span data-ttu-id="051a8-117">Ako je to slučaj, spoljni korisnik možete da dodate direktno u grupu iz programa Outlook.</span><span class="sxs-lookup"><span data-stu-id="051a8-117">If that is the case, you can add the external user directly to the group from Outlook.</span></span> <span data-ttu-id="051a8-118">Detaljne informacije o gostima Microsoft 365 grupa gostiju, kao i uputstva za dodavanje spoljnih gostiju možete pronaći u [ovom članku](https://support.office.com/article/Guest-access-in-Office-365-Groups-bfc7a840-868f-4fd6-a390-f347bf51aff6.aspx).</span><span class="sxs-lookup"><span data-stu-id="051a8-118">Detailed information on Microsoft 365 Groups guests as well as instructions for adding external guests can be found in [this article](https://support.office.com/article/Guest-access-in-Office-365-Groups-bfc7a840-868f-4fd6-a390-f347bf51aff6.aspx).</span></span>
  