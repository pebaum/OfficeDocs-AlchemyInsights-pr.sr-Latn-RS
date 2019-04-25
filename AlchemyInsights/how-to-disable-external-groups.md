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
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32399677"
---
# <a name="how-to-disable-external-groups"></a>Kako onemogućiti spoljne grupe

Za Yammer spoljni messaging primenjuje Exchange Transport pravila (ETRs), skup proaktivne kontrole da biste sprečili deljenje informacija kompanije. Kako bi se ograničavanje korisnika da kreiranje spoljne grupe, morate da konfigurišete transporta pravilo za Exchange (ETR), a zatim konfigurišite Yammer da koristite Exchange Transport pravilo da blokira spoljni messaging. 
  
Jednom kada ste kreirali pravilo u Exchange Online admin center, slijedite ove korake da biste podesili ETR da se prijavite za Yammer:
  
- Prijavite se na Yammer kao verifikovan admin, a u na **Yammer admin centar**, idi u C **ontent i bezbednosti \> bezbednosnim postavkama.**
    
- Pod **Spoljnim Messaging**, izaberite **sprovodi Exchange Online Exchange Transport pravila (ETRs) u Yammer.**
    
- Odaberite da **sačuvate**. 
    
Više informacija potražite u odeljku [kontrole spoljnih messaging u mreži sa Exchange Transport pravila za Yammer](https://support.office.com/article/Control-external-messaging-in-a-Yammer-network-with-Exchange-Transport-Rules-f8fd6403-c8f3-4307-9230-65304d6000d9)
  

