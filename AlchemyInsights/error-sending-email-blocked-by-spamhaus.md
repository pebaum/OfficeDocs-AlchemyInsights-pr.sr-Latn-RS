---
title: Greška pri slanju e-poruke blokiranu spam Haus
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "255"
- "3100003"
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: 3ff4f7a155fe74f5b42a1bd43e67ef0a751d7fbd
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43714272"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a><span data-ttu-id="4e4e0-102">Greška pri slanju e-poruke: host klijenta je blokirana pomoću bezvredne pošte</span><span class="sxs-lookup"><span data-stu-id="4e4e0-102">Error sending email: Client host blocked using Spamhaus</span></span>

<span data-ttu-id="4e4e0-103">IP adresa koja je poslala poruku nalazi se na listi blokiranih poruka u vlasništvu [spam Haus](https://go.microsoft.com/fwlink/p/?linkid=123245).</span><span class="sxs-lookup"><span data-stu-id="4e4e0-103">The IP address that sent the message is on a block list owned by [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245).</span></span> <span data-ttu-id="4e4e0-104">Razlozi za blokiranje bezvredne pošte uključuju kompromitovana konta, ugrožene mašine koje dele javnu IP adresu i smernice dobavljača Internet usluga (ISP).</span><span class="sxs-lookup"><span data-stu-id="4e4e0-104">Reasons for being blocked by Spamhaus include compromised accounts, compromised machines sharing a public IP address, and Internet Service Provider (ISP) policies.</span></span> <span data-ttu-id="4e4e0-105">Moguća rešenja su:</span><span class="sxs-lookup"><span data-stu-id="4e4e0-105">Possible fixes are:</span></span>
  
- <span data-ttu-id="4e4e0-106">Za blokirane dolazne poruke u kojima kontrolišete izvorni server e-pošte, potrebno je da utvrdite uzrok i uklonite blok sa Web lokacije "spam Haus".</span><span class="sxs-lookup"><span data-stu-id="4e4e0-106">For blocked inbound messages where you control the source email server, you need to determine the cause and remove the block from the Spamhaus website.</span></span>

- <span data-ttu-id="4e4e0-107">Za blokirane dolazne poruke gde izvorna IP adresa pripada nekom drugom, vlasnik adrese treba da ukloni blok sa Web lokacije "spam Haus".</span><span class="sxs-lookup"><span data-stu-id="4e4e0-107">For blocked inbound messages where the source IP address belongs to someone else, the address owner needs to remove the block from the Spamhaus website.</span></span> <span data-ttu-id="4e4e0-108">Ako se IP adresa nalazi na listi blokiranih smernica (PBL), vlasnik može da dodeli drugačiju statičnu IP adresu ili da ukloni adresu iz PBL-a.</span><span class="sxs-lookup"><span data-stu-id="4e4e0-108">If the IP address is on the Policy Block List (PBL), the owner can assign a different static IP address or remove the address from the PBL.</span></span>

- <span data-ttu-id="4e4e0-109">Za blokirane odlazne poruke iz domena povezanog sa korporacijom Microsoft, ovu grešku možete dobiti ako se poruke usmeravaju preko usluge nezavisnog proizvođača.</span><span class="sxs-lookup"><span data-stu-id="4e4e0-109">For blocked outbound messages from your domain connected to Microsoft, you can receive this error if the messages are routed through a 3rd party service.</span></span> <span data-ttu-id="4e4e0-110">Da biste pronašli blokirani IP adresu, možete da koristite alatku za pronalaženje koja se može koristiti.</span><span class="sxs-lookup"><span data-stu-id="4e4e0-110">You can use a WHOIS lookup tool to find the blocked IP address owner.</span></span>
