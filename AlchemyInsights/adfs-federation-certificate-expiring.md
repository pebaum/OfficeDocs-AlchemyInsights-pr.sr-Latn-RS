---
title: Adr.
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "645"
- "1300012"
ms.assetid: 26a7eebb-1424-4ddc-a123-af1cc94bc40f
ms.openlocfilehash: 14e7da6220dfa96edca5d9ec5c32e003480a9eaf
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43710421"
---
# <a name="adfs-federation-certificate-expiring"></a>Adr.

Da biste riješili taj problem, slijedite ove korake:
  
1. Instalirajte Microsoft Azure Active Directory modul za Windows PowerShell na računaru (ako modul nije već instaliran). Da biste to uradili, idite da biste [upravljali AZURE oglasima pomoću Windows PowerShell](https://aka.ms/aadposh).

2. Sledite korake u odjeljku "scenario 1: istekao je certifikat potpisa" AD FS "-a za potpis" došlo [je do problema sa pristupom lokaciji "u usluzi AD FS kada se federirani korisnik prijavi u Microsoft 365, Azure ili Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).

3. Sledite korake u programu [Update ili popravite postavke federovanog domena u aplikaciji Microsoft, Azure ili Intune](https://docs.microsoft.com/office365/troubleshoot/security/update-federated-domain-office-365).

    Da biste saznali više o obnavljanju certifikata Federacije, pogledajte odeljak [obnavljanje certifikata Federacije za Microsoft 365 i Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).
