---
title: Šifriranje pomoću pravila za prenos
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002635"
- "5154"
ms.openlocfilehash: 3f16c7e7be99a50cd57f47ea2801b3022c4aec95
ms.sourcegitcommit: 07725fcaf073f0ac145f98653b989afdb34c5ad0
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/28/2020
ms.locfileid: "43915291"
---
# <a name="encryption-with-transport-rules"></a>Šifriranje pomoću pravila za prenos

U [Exchange Centru administracije](https://go.microsoft.com/fwlink/p/?linkid=834822) (EAC) možete da koristite Office Message Encryption (OME) mogućnosti u pravilima protoka pošte da biste aktivirali šifrovanje poruke. U uslovu pravila za prenos izaberite opciju **Primena Office 365 zaštita šifrovanja poruka i prava**.

- Za više informacija pogledajte članak [Definisanje pravila protoka pošte da šifruju](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).

- U programu PowerShell koristite [Novo pravilo za prenos ](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email?view=o365-worldwide#use-exchange-online-powershell-to-create-a-mail-flow-rule-for-encrypting-email-messages-without-the-new-ome-capabilities) cmdlet i podesite parametar *Primena OME* na $true.
