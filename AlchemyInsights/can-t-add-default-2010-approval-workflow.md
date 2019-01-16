---
title: Nije moguće dodati podrazumevani tok posla za odobravanje 2010
ms.author: kirks
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 2060c9a1-e714-4d93-925e-629c82c35986
ms.openlocfilehash: 758b0339b842478f9609eb716b5b4ddab6579c80
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/15/2019
ms.locfileid: "28309256"
---
# <a name="cant-add-default-2010-approval-workflow"></a>Nije moguće dodati podrazumevani tok posla za odobravanje 2010

U kolekciji lokacija Microsoft SharePoint, ne možete dodati globalno koji možete ponovo koristiti toka posla (kao što su „odobrenje - SharePoint 2010”) u listu ili biblioteku.
  
Da biste riješili taj problem, slijedite ove korake: 
  
1. Otvorite osnovnu Web lokacija u kolekciji lokacija u SharePoint Designer 2013.
  
2. U okviru **Lokacije objekata**, izaberite **tokova posla**. 
  
3. U **novom** delu glavnoj **tokova posla** , izaberite **Tok posla moguće ponovo koristiti**. 
  
4. **Kreiranje toka posla moguće ponovo koristiti** obrazac, unesite ime * **Repair2010***. Za **Tip platforme**, izaberite **SharePoint 2010 toka posla**, a zatim izaberite **OK**. 
  
5. U odeljku **spasiti** glavne trake **toka posla** , izaberite **objavljivanje**. 
  
6. U odeljku za **Upravljanje** glavne trake **toka posla** , izaberite **Objavljivanje globalno**. U okviru za dijalog koji se pojavljuje, izaberite **OK**. 
  
7. U web pregledaču, pronađite osnovne Web lokacija u kolekciji lokacija, a zatim pristupite **Postavke lokacije** \> **Funkcije kolekcije lokacija**. Onda, Uključi/isključi funkcije za **tokove posla** : 
  
· Ako je funkcija *aktivirano* , kliknite **Deaktiviraj,** a zatim **Aktiviraj**. 
  
· Ako je funkcija " *Deactivated* ", kliknite na dugme **Aktiviraj**. 
  
Za više informacija pogledajte sledeći [članak](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).
  

