---
title: Nije moguće pristupiti javnim fasciklama
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3462"
ms.openlocfilehash: a579b89b68bfb8432adfe64b155803eda2c3b086
ms.sourcegitcommit: a3b42ee05224846327d353b48a8c67dab724f6eb
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/21/2020
ms.locfileid: "42891763"
---
# <a name="outlook-cannot-connect-to-public-folders"></a>Outlook ne može da se poveže sa javnim fasciklama

Ako pristup javnoj fascikli ne funkcioniše za neke korisnike, pokušajte sledeće:

Povežite se sa EXO PowerShell i konfigurišite parametar DefaultPublicFolderMailbox na korisničkom računu za ovaj problem da bi se podudarali sa parametrom na radnom korisničkom računu.

Primer:

Get-poštansko sanduče | FT DefaultPublicFolderMailbox, EffectivePublicFolderMailbox

Set-poštansko sanduče-problem korisnik \<-DefaultPublicFolderMailbox vrednost iz prethodne komande>

Sačekajte najmanje jedan sat da bi promena stupila na snagu.

Ako problem i dalje postoji, sledite [ovaj postupak](https://aka.ms/pfcte) da biste rešili probleme sa pristupom javne fascikle pomoću programa Outlook.