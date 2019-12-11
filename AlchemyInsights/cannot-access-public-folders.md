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
ms.openlocfilehash: a9305b175e1ca0b992c014a73705447d67e037bc
ms.sourcegitcommit: cbbd46fa9a32873c5446d9fd5a532cea0300b795
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/10/2019
ms.locfileid: "39959508"
---
# <a name="outlook-cannot-connect-to-public-folders"></a>Outlook ne može da se poveže sa javnim fasciklama

Ako pristup javnoj fascikli ne funkcioniše za nekoliko korisnika, pokušajte sledeće:

Povežite se sa EXO PowerShell i konfigurišite DefaultPublicFolderMailbox na korisničkom nalogu problema da bi se podudarali sa jednim na radnom korisničkom računu.

Primer:

Get-poštansko sanduče | FT DefaultPublicFolderMailbox, EffectivePublicFolderMailbox

Set-poštansko sanduče-problem korisnik \<-DefaultPublicFolderMailbox vrednost iz prethodne komande>

Sačekajte najmanje jedan sat da bi promena stupila na snagu.