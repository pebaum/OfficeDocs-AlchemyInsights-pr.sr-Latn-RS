---
title: Greška prilikom slanja e-pošte blokiran od strane SpamHaus
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 2/23/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "255"
- "3100003"
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: 52a5c20d59a2eac4c4bf465edaa888952d47f39f
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/28/2019
ms.locfileid: "35387863"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a><span data-ttu-id="5d8c3-102">Greška prilikom slanja e-pošte: klijent domaćina blokirane pomoću Spamhaus</span><span class="sxs-lookup"><span data-stu-id="5d8c3-102">Error sending email: Client host blocked using Spamhaus</span></span>

<span data-ttu-id="5d8c3-103">IP adresu koja je poslala poruku je na listu bloka koja je u vlasništvu [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245).</span><span class="sxs-lookup"><span data-stu-id="5d8c3-103">The IP address that sent the message is on a block list owned by [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245).</span></span> <span data-ttu-id="5d8c3-104">Razlozi za blokirana od strane Spamhaus uključuju kompromitovane račune, kompromitovan mašine Deljenje javne IP adrese, a dobavljač Internet usluga (ISP) politike.</span><span class="sxs-lookup"><span data-stu-id="5d8c3-104">Reasons for being blocked by Spamhaus include compromised accounts, compromised machines sharing a public IP address, and Internet Service Provider (ISP) policies.</span></span> <span data-ttu-id="5d8c3-105">Moguće ispravke su:</span><span class="sxs-lookup"><span data-stu-id="5d8c3-105">Possible fixes are:</span></span>
  
- <span data-ttu-id="5d8c3-106">Za ulazni blokirane poruke Office 365 gde ti kontrolisati izvornom serveru e-pošte, morate utvrditi uzrok i ukloniti iz bloka sa Spamhaus Internet.</span><span class="sxs-lookup"><span data-stu-id="5d8c3-106">For blocked inbound messages to Office 365 where you control the source email server, you need to determine the cause and remove the block from the Spamhaus website.</span></span>

- <span data-ttu-id="5d8c3-107">Za blokirane dolazne poruke Office 365 gde IP adresu izvora pripada nekom drugom, vlasnik adresa mora ukloniti blok sa Spamhaus Internet.</span><span class="sxs-lookup"><span data-stu-id="5d8c3-107">For blocked inbound messages to Office 365 where the source IP address belongs to someone else, the address owner needs to remove the block from the Spamhaus website.</span></span> <span data-ttu-id="5d8c3-108">Ako IP adresa je na blok listi politike (PBL), vlasnik možete da dodelite različite statičnu IP adresu ili adresu uklanjanje u PBL.</span><span class="sxs-lookup"><span data-stu-id="5d8c3-108">If the IP address is on the Policy Block List (PBL), the owner can assign a different static IP address or remove the address from the PBL.</span></span>

- <span data-ttu-id="5d8c3-109">Za izlazni blokirane poruke iz domena svoje Office 365, da primate ovu grešku ako poruke usmeravaju kroz uslugu 3 partije.</span><span class="sxs-lookup"><span data-stu-id="5d8c3-109">For blocked outbound messages from your Office 365 domain, you can receive this error if the messages are routed through a 3rd party service.</span></span> <span data-ttu-id="5d8c3-110">Možete koristiti alat za pronalaženje ko je pronaci vlasnika blokiranih IP adresa.</span><span class="sxs-lookup"><span data-stu-id="5d8c3-110">You can use a WHOIS lookup tool to find the blocked IP address owner.</span></span>
