---
title: Identifikuj događaje brisanja poruka u evidencijama nadgledanja
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1370"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 641c0216491186aeb423a13854c6b39ee005e5df
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44509002"
---
# <a name="audit-logs-for-deleted-email-messages"></a><span data-ttu-id="38bf1-102">Evidencija nadgledanja izbrisanih e-poruka</span><span class="sxs-lookup"><span data-stu-id="38bf1-102">Audit logs for deleted email messages</span></span>

<span data-ttu-id="38bf1-103">Počevši od januara 2019, Microsoft podrazumevano postaje uključena evidencija nadgledanja poštanskog sandučeta.</span><span class="sxs-lookup"><span data-stu-id="38bf1-103">Starting in January 2019, Microsoft is turning on mailbox audit logging by default.</span></span> <span data-ttu-id="38bf1-104">U suprotnom, da biste redigovali poruke o brisanju događaja za određenog korisnika, potrebno je da ručno omogućite brisanje radnji za nadgledanje.</span><span class="sxs-lookup"><span data-stu-id="38bf1-104">Otherwise, to review delete message events for a specific user, you need to manually enable the delete actions for auditing.</span></span> <span data-ttu-id="38bf1-105">Ako je evidencija nadgledanja za poštansko sanduče već omogućena za vašu organizaciju ili za određenog korisnika, sledite dolenavedene korake.</span><span class="sxs-lookup"><span data-stu-id="38bf1-105">If mailbox audit logging is already enabled for your organization or for the specific user, follow the steps below.</span></span>

1. <span data-ttu-id="38bf1-106">Prijavite se na [Microsoft 365 Security & centar za usaglašavanje](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="38bf1-106">Log in to the [Microsoft 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="38bf1-107">Kliknite na dugme **Pretraga i istraga** i izaberite **pretragu evidencije nadgledanja**.</span><span class="sxs-lookup"><span data-stu-id="38bf1-107">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

3. <span data-ttu-id="38bf1-108">Izaberite opseg datuma u poljima **Početni datum** i **Krajnji datum** .</span><span class="sxs-lookup"><span data-stu-id="38bf1-108">Select the date range in the **Start date** and **End date** fields.</span></span> <span data-ttu-id="38bf1-109">Odredite korisničko ime za korisnika koji želite da istražite (korisnika koji je izbrisao stavke).</span><span class="sxs-lookup"><span data-stu-id="38bf1-109">Specify username for the user that you want to investigate (the user who deleted the items).</span></span> <span data-ttu-id="38bf1-110">U polju **aktivnosti** izaberite **izbrisane poruke iz fascikle "Izbrisane stavke** " i **premestite poruke u fasciklu "Izbrisane stavke**".</span><span class="sxs-lookup"><span data-stu-id="38bf1-110">In the **Activities** field, select **Deleted messages from Deleted Items folder** and **Moved messages to Deleted Items folder**.</span></span>

4. <span data-ttu-id="38bf1-111">Kliknite na dugme **Pretraži**.</span><span class="sxs-lookup"><span data-stu-id="38bf1-111">Click **Search**.</span></span>

<span data-ttu-id="38bf1-112">U rezultatima izaberite zapis nadgledanja.</span><span class="sxs-lookup"><span data-stu-id="38bf1-112">In the results, select an audit record.</span></span> <span data-ttu-id="38bf1-113">Kliknite na dugme " **više informacija**" u prozoru "Detalji".</span><span class="sxs-lookup"><span data-stu-id="38bf1-113">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="38bf1-114">Dodatne informacije o izbrisanom artiklu (na primer, red za temu i lokacija stavke kada je ona izbrisana) prikazane su u polju "zone za **stavke** ".</span><span class="sxs-lookup"><span data-stu-id="38bf1-114">Additional information about the deleted item (for example, the subject line and the location of the item when it was deleted) is displayed in the **AffectedItems** field.</span></span> <span data-ttu-id="38bf1-115">Svojstvo **Clientinfostring** će prikazati da li je brisanje bilo u programu Outlook, Outlook na vebu (ranije poznato kao Outlook Web aplikacija) ili bilo koji drugi uređaj.</span><span class="sxs-lookup"><span data-stu-id="38bf1-115">The **ClientInfoString** property will show if the deletion occurred in Outlook, Outlook on the web (formerly known as Outlook Web App), or any other device.</span></span>

<span data-ttu-id="38bf1-116">Više informacija potražite u članku [Utvrđivanje ko je podesio Prosleđivanje e-pošte za poštansko sanduče](https://docs.microsoft.com/microsoft-365/compliance/auditing-troubleshooting-scenarios#determine-if-a-user-deleted-email-items).</span><span class="sxs-lookup"><span data-stu-id="38bf1-116">For more information, see [Determining who set up email forwarding for a mailbox](https://docs.microsoft.com/microsoft-365/compliance/auditing-troubleshooting-scenarios#determine-if-a-user-deleted-email-items).</span></span>

<span data-ttu-id="38bf1-117">**Napomena**: ne možete da preuzimate izbrisane stavke pomoću funkcije "evidencija nadgledanja".</span><span class="sxs-lookup"><span data-stu-id="38bf1-117">**Note**: You can't retrieve deleted items using the audit log feature.</span></span> <span data-ttu-id="38bf1-118">Da biste preuzeli izbrisane poruke u programu Outlook na vebu, pogledajte odeljak [oporavak izbrisanih stavki u Outlook Web aplikaciji](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).</span><span class="sxs-lookup"><span data-stu-id="38bf1-118">To retrieve deleted messages in Outlook on the web, see [Recover deleted items in Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).</span></span>
