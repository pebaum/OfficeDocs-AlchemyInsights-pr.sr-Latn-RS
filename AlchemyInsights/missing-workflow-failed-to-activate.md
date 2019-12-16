---
title: Nije uspjelo aktiviranje toka posla koji nedostaje
ms.author: pebaum
author: pebaum
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: e46ae8c5-3d81-457e-8c77-f7c1cbe267c4
ms.openlocfilehash: 3df1ddc1059c4cd6cc3f9f42dc157d20be79a63a
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40052627"
---
# <a name="missing-workflow-failed-to-activate"></a>Nije uspjelo aktiviranje toka posla koji nedostaje

U Microsoft SharePoint kolekciji lokacija ne možete dodati globalno tok posla koji je moguće ponovo koristiti (kao što je "odobrenje-SharePoint 2010") u listu ili biblioteku.
  
Da biste riješili taj problem, slijedite ove korake: 
  
1. Otvorite osnovnu Web lokaciju kolekcije lokacija u programu SharePoint Designer 2013.
  
2. U okviru **objekti lokacije**izaberite stavku **Tokovi posla**. 
  
3. U **novom** odeljku trake **tokova posla** izaberite opciju **tok posla**koji je moguće ponovo koristiti. 
  
4. U obrascu **Kreiranje toka posla** koji je moguće ponovo koristiti unesite ime * * *Repair2010* * *. Za **tip platforme**izaberite stavku **SharePoint 2010 tok posla**, a zatim kliknite na dugme **u redu**. 
  
1. U odeljku **Sačuvaj** na traci **toka posla** izaberite stavku **Objavi**. 
  
2. U odeljku " **Upravljanje** " na traci **toka posla** izaberite opciju " **Objavi globalno**". U dijalogu za potvrđivanje koji se pojavljuje izaberite **"u redu"**. 
  
3. U Web pregledaču pronađite osnovnu Veb lokaciju kolekcije lokacija, a zatim pristupite **postavkama** \> **kolekcije**lokacija. Zatim Preklapaj funkciju **tokova posla** : 
  
· Ako je funkcija *aktivirana* , kliknite na dugme **"Deaktiviraj",** a zatim kliknite na dugme " **Aktiviraj**". 
  
· Ako je funkcija *deaktivirana* , kliknite na dugme " **Aktiviraj**". 
  
Za više informacija pogledajte sledeći [članak](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).
  

