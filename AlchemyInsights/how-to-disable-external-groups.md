---
title: Kako onemogućiti spoljne grupe
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: 4d911c319c3e8e327f9b3af3ba67816e646bc468
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29899150"
---
# <a name="how-to-disable-external-groups"></a><span data-ttu-id="602eb-102">Kako onemogućiti spoljne grupe</span><span class="sxs-lookup"><span data-stu-id="602eb-102">How to disable External Groups</span></span>

<span data-ttu-id="602eb-p101">Za Yammer spoljni messaging primenjuje Exchange Transport pravila (ETRs), skup proaktivne kontrole da biste sprečili deljenje informacija kompanije. Kako bi se ograničavanje korisnika da kreiranje spoljne grupe, morate da konfigurišete transporta pravilo za Exchange (ETR), a zatim konfigurišite Yammer da koristite Exchange Transport pravilo da blokira spoljni messaging.</span><span class="sxs-lookup"><span data-stu-id="602eb-p101">Yammer external messaging applies Exchange Transport Rules (ETRs), a set of proactive controls to prevent company information from being shared. In order to restrict users from creating external groups, you need to configure an Exchange transport rule (ETR), and then configure Yammer to use the Exchange Transport rule to block external messaging.</span></span> 
  
<span data-ttu-id="602eb-105">Jednom kada ste kreirali pravilo u Exchange Online admin center, slijedite ove korake da biste podesili ETR da se prijavite za Yammer:</span><span class="sxs-lookup"><span data-stu-id="602eb-105">Once you have created a rule in Exchange Online admin center, follow these steps to set ETR to apply in Yammer:</span></span>
  
- <span data-ttu-id="602eb-106">Prijavite se na Yammer kao verifikovan admin, a u na **Yammer admin centar**, idi u C **ontent i bezbednosti \> bezbednosnim postavkama.**</span><span class="sxs-lookup"><span data-stu-id="602eb-106">Log on to Yammer as a verified admin, and in the **Yammer admin center**, go to C **ontent and Security \> Security Settings.**</span></span>
    
- <span data-ttu-id="602eb-107">Pod **Spoljnim Messaging**, izaberite **sprovodi Exchange Online Exchange Transport pravila (ETRs) u Yammer.**</span><span class="sxs-lookup"><span data-stu-id="602eb-107">Under **External Messaging**, select **Enforce your Exchange Online Exchange Transport Rules (ETRs) in Yammer.**</span></span>
    
- <span data-ttu-id="602eb-108">Odaberite da **sačuvate**.</span><span class="sxs-lookup"><span data-stu-id="602eb-108">Choose **Save**.</span></span> 
    
<span data-ttu-id="602eb-109">Više informacija potražite u odeljku [kontrole spoljnih messaging u mreži sa Exchange Transport pravila za Yammer](https://support.office.com/article/Control-external-messaging-in-a-Yammer-network-with-Exchange-Transport-Rules-f8fd6403-c8f3-4307-9230-65304d6000d9)</span><span class="sxs-lookup"><span data-stu-id="602eb-109">For more information, see [Control external messaging in a Yammer network with Exchange Transport rules](https://support.office.com/article/Control-external-messaging-in-a-Yammer-network-with-Exchange-Transport-Rules-f8fd6403-c8f3-4307-9230-65304d6000d9)</span></span>
  

