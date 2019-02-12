---
title: 1554 Winsock greška 10061
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: 9331a6c2b6e92a66fb97daf7dc5655ec320cba0f
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29903124"
---
# <a name="winsock-error-10061"></a><span data-ttu-id="c6cf8-102">Winsock greška 10061</span><span class="sxs-lookup"><span data-stu-id="c6cf8-102">Winsock error 10061</span></span>

<span data-ttu-id="c6cf8-p101">Ovaj kôd greške znači da Office 365 nije mogao da uspostavi TCP priključak (veza) sa meta domaćin. Najverovatniji uzrok ove greške je problem u konfiguraciji vatrozida. Da biste rešili problem, pogledajte ove postavke:</span><span class="sxs-lookup"><span data-stu-id="c6cf8-p101">This error code means that Office 365 couldn't establish a TCP socket (connection) with the target host. The most likely cause of this error is a problem with your firewall configuration. To fix the problem, check these settings:</span></span>
  
- <span data-ttu-id="c6cf8-106">Proverite konfiguraciju zaštitnog zida sa informacijama u [Office 365 URL adrese i opsega IP adresa](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span><span class="sxs-lookup"><span data-stu-id="c6cf8-106">Verify your firewall configuration with the information in [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span></span>
    
- <span data-ttu-id="c6cf8-107">Ako greška je specifična za Exchange Online zaštitu (EOP), trebalo bi da ste prethodno obavešteni do promene na [Exchange Online zaštitu IP adrese](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="c6cf8-107">If the error is specific to Exchange Online Protection (EOP), you should have been previously notified to a change to the [Exchange Online Protection IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
    
- <span data-ttu-id="c6cf8-108">Uverite se da je tvoj dobavljač Internet usluga (ISP) ne blokira port.</span><span class="sxs-lookup"><span data-stu-id="c6cf8-108">Verify that your Internet Service Provider (ISP) isn't blocking the port.</span></span>
    
- <span data-ttu-id="c6cf8-109">Provjerite pametan hosta i ciljnih postavke servera u tvoj konektori.</span><span class="sxs-lookup"><span data-stu-id="c6cf8-109">Verify the smart host and target server settings in your connectors.</span></span>
    
<span data-ttu-id="c6cf8-110">Imajte na umu da Office 365 ne blokira *dolazne* veze na ovaj način.</span><span class="sxs-lookup"><span data-stu-id="c6cf8-110">Note that Office 365 doesn't block  *incoming*  connections in this manner.</span></span> 
  

