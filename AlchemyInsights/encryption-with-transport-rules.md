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
# <a name="encryption-with-transport-rules"></a><span data-ttu-id="9b003-102">Šifriranje pomoću pravila za prenos</span><span class="sxs-lookup"><span data-stu-id="9b003-102">Encryption with transport rules</span></span>

<span data-ttu-id="9b003-103">U [Exchange Centru administracije](https://go.microsoft.com/fwlink/p/?linkid=834822) (EAC) možete da koristite Office Message Encryption (OME) mogućnosti u pravilima protoka pošte da biste aktivirali šifrovanje poruke.</span><span class="sxs-lookup"><span data-stu-id="9b003-103">In the [Exchange Admin Center](https://go.microsoft.com/fwlink/p/?linkid=834822) (EAC), you can use Office Message Encryption(OME) capabilities in your mail flow rules to trigger message encryption.</span></span> <span data-ttu-id="9b003-104">U uslovu pravila za prenos izaberite opciju **Primena Office 365 zaštita šifrovanja poruka i prava**.</span><span class="sxs-lookup"><span data-stu-id="9b003-104">Choose the **Apply Office 365 Message Encryption and rights protection** option on the Transport Rule condition.</span></span>

- <span data-ttu-id="9b003-105">Za više informacija pogledajte članak [Definisanje pravila protoka pošte da šifruju](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).</span><span class="sxs-lookup"><span data-stu-id="9b003-105">For more information, see [Define Mail flow rule to encrypt](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).</span></span>

- <span data-ttu-id="9b003-106">U programu PowerShell koristite [Novo pravilo za prenos ](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email?view=o365-worldwide#use-exchange-online-powershell-to-create-a-mail-flow-rule-for-encrypting-email-messages-without-the-new-ome-capabilities) cmdlet i podesite parametar *Primena OME* na $true.</span><span class="sxs-lookup"><span data-stu-id="9b003-106">In Powershell, use the [New-TransportRule](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email?view=o365-worldwide#use-exchange-online-powershell-to-create-a-mail-flow-rule-for-encrypting-email-messages-without-the-new-ome-capabilities) cmdlet and set the *ApplyOME* parameter to $true.</span></span>
