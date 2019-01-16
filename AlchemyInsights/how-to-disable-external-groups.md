---
title: Kako onemogućiti spoljne grupe
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: 4807dbfbabcea1f13785bd39bb48e4bbaa8d0f0f
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/15/2019
ms.locfileid: "28309484"
---
# <a name="how-to-disable-external-groups"></a>Kako onemogućiti spoljne grupe

Za Yammer spoljni messaging primenjuje Exchange Transport pravila (ETRs), skup proaktivne kontrole da biste sprečili deljenje informacija kompanije. Kako bi se ograničavanje korisnika da kreiranje spoljne grupe, morate da konfigurišete transporta pravilo za Exchange (ETR), a zatim konfigurišite Yammer da koristite Exchange Transport pravilo da blokira spoljni messaging. 
  
Jednom kada ste kreirali pravilo u Exchange Online admin center, slijedite ove korake da biste podesili ETR da se prijavite za Yammer:
  
- Prijavite se na Yammer kao verifikovan admin, a u na **Yammer admin centar**, idi u C **ontent i bezbednosti \> bezbednosnim postavkama.**
    
- Pod **Spoljnim Messaging**, izaberite **sprovodi Exchange Online Exchange Transport pravila (ETRs) u Yammer.**
    
- Odaberite da **sačuvate**. 
    
Više informacija potražite u odeljku [kontrole spoljnih messaging u mreži sa Exchange Transport pravila za Yammer](https://support.office.com/en-us/article/Control-external-messaging-in-a-Yammer-network-with-Exchange-Transport-Rules-f8fd6403-c8f3-4307-9230-65304d6000d9)
  

