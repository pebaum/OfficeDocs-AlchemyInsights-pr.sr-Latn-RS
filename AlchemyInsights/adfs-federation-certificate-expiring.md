---
title: ADFS Federacije istek certifikata
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/8/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "645"
- "1300012"
ms.assetid: 26a7eebb-1424-4ddc-a123-af1cc94bc40f
ms.openlocfilehash: b014e350d5f6f1a61feb223e3d3fd0a1f56f5872
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/28/2019
ms.locfileid: "35357979"
---
# <a name="adfs-federation-certificate-expiring"></a><span data-ttu-id="6df77-102">ADFS Federacije istek certifikata</span><span class="sxs-lookup"><span data-stu-id="6df77-102">ADFS Federation Certificate Expiring</span></span>

<span data-ttu-id="6df77-103">Da biste riješili taj problem, slijedite ove korake:</span><span class="sxs-lookup"><span data-stu-id="6df77-103">To resolve this issue, follow these steps:</span></span>
  
1. <span data-ttu-id="6df77-104">Instalirati na Microsoft Azure Active Directory modul za Windows PowerShell na računaru (ako modul nije već instaliran).</span><span class="sxs-lookup"><span data-stu-id="6df77-104">Install the Microsoft Azure Active Directory Module for Windows PowerShell on the computer (if the module isn't already installed).</span></span> <span data-ttu-id="6df77-105">Da biste ovo uradili, idite na [Upravljanje azurno AD koristeći Windows PowerShell](https://aka.ms/aadposh).</span><span class="sxs-lookup"><span data-stu-id="6df77-105">To do this, go to [Manage Azure AD using Windows PowerShell](https://aka.ms/aadposh).</span></span>

2. <span data-ttu-id="6df77-106">Sledite korake u na „Scenario 1: AD FS token potpisivanje certifikat istekao” delu [„Postoji problem sa pristupom na lokaciji” greška iz AD FS kada savezni korisnik potpiše Office 365, Azure, ili Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span><span class="sxs-lookup"><span data-stu-id="6df77-106">Follow the steps in the "Scenario 1: The AD FS token-signing certificate expired" section of ["There was a problem accessing the site" error from AD FS when a federated user signs in to Office 365, Azure, or Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span></span>

3. <span data-ttu-id="6df77-107">Sledite korake u [Kako da ažurirate ili popravite postavke savezni domena u Office 365, Azure, ili Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span><span class="sxs-lookup"><span data-stu-id="6df77-107">Follow the steps in [How to update or repair the settings of a federated domain in Office 365, Azure, or Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span></span>

    <span data-ttu-id="6df77-108">Da biste saznali više o obnavlja certifikate Federacije, vidim [obnova Federacije certifikate za Office 365 i Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span><span class="sxs-lookup"><span data-stu-id="6df77-108">To learn more about renewing Federation certificates, see [Renew federation certificates for Office 365 and Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span></span>
