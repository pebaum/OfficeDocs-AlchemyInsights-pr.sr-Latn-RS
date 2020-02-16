---
title: Popravljanje Office aplikacija vaš nalog je u lošem stanju
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2558"
- "9000571"
ms.openlocfilehash: e591c56dd207a5bcb3979be3f66052121100b162
ms.sourcegitcommit: 2572c4e5a981d5f3f556835061c568cfd08b78da
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/27/2019
ms.locfileid: "41969759"
---
# <a name="fixing-the-office-apps-your-account-is-in-a-bad-state-error"></a><span data-ttu-id="99fdb-102">Popravljanje Office aplikacija "vaš nalog je u lošem stanju"</span><span class="sxs-lookup"><span data-stu-id="99fdb-102">Fixing the Office apps "Your account is in a bad state" error</span></span>

<span data-ttu-id="99fdb-103">Da biste otklonili ovu grešku, Isprobajte sledeće opcije na računaru koji je na njemu:</span><span class="sxs-lookup"><span data-stu-id="99fdb-103">To fix this error, try the following options on the affected computer:</span></span>

- <span data-ttu-id="99fdb-104">Otvorite Office aplikaciju, izaberite**nalog** > za **datoteku** > **sa svih naloga**.</span><span class="sxs-lookup"><span data-stu-id="99fdb-104">Open an Office app, select **File** > **Account** > **Sign Out of all accounts**.</span></span> <span data-ttu-id="99fdb-105">Prijavite se ponovo koristeći korisnički nalog sa važećom licencom.</span><span class="sxs-lookup"><span data-stu-id="99fdb-105">Sign in again using a user account with a valid license.</span></span> <span data-ttu-id="99fdb-106">Detaljnije informacije potražite u članku [Nalozi u sistemu Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span><span class="sxs-lookup"><span data-stu-id="99fdb-106">For detailed information, see [Accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span></span>
- <span data-ttu-id="99fdb-107">[Obrišite Office akreditive](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) koristeći Windows upravljač akreditivima.</span><span class="sxs-lookup"><span data-stu-id="99fdb-107">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br>
  <span data-ttu-id="99fdb-108">**Napomena:** Putanje registratora za Office 2016 su promenjene u 16,0.</span><span class="sxs-lookup"><span data-stu-id="99fdb-108">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="99fdb-109">Na primer, \Software\microsoft\office\16.0\uobičajeno \ Identitet</span><span class="sxs-lookup"><span data-stu-id="99fdb-109">For example, \Software\Microsoft\Office\16.0\Common\Identity</span></span>\
- <span data-ttu-id="99fdb-110">Na računaru koji je uticao na računar postavite potencijalnog klijenta za praćenje = 0 koristeći sledeće korake:</span><span class="sxs-lookup"><span data-stu-id="99fdb-110">On the affected computer, set the EnableADAL = 0 using the following steps:</span></span>  
     1. <span data-ttu-id="99fdb-111">Kliknite desnim tasterom miša na dugme Windows i izaberite stavku **Pokreni**.</span><span class="sxs-lookup"><span data-stu-id="99fdb-111">Right-click the Windows button and select **Run**.</span></span> <span data-ttu-id="99fdb-112">U polju **Otvori** otkucajte **Regedit**, a zatim izaberite **"u redu"**.</span><span class="sxs-lookup"><span data-stu-id="99fdb-112">In the **Open** box, type **regedit**, and then select **OK**.</span></span>
     2. <span data-ttu-id="99fdb-113">Kliknite na **dugme "da** " kada se od vas zatraži da dozvolite Registry Editoru da promeni vaš uređaj.</span><span class="sxs-lookup"><span data-stu-id="99fdb-113">Select **Yes** when prompted to allow Registry Editor to make changes to your device.</span></span>
    3. <span data-ttu-id="99fdb-114">U programu Registry Editor dodajte DWORD vrednost Enabpotencijalnog klijenta sa postavkom 0 ispod HKEY_CURRENT_USER \Software\microsoft\office\16.0\pod\identitet.</span><span class="sxs-lookup"><span data-stu-id="99fdb-114">In the Registry Editor, add a DWORD value of EnableADAL with a setting of 0 under HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.</span></span>
- <span data-ttu-id="99fdb-115">Ako dođe do greške tokom povezivanja sa Office 365 pomoću programa Office 2013, [omogućite modernu potvrdu identiteta](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication) za Office Client.</span><span class="sxs-lookup"><span data-stu-id="99fdb-115">If the error occurs while connecting to Office 365 using Office 2013, [enable modern authentication](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication) for the Office client.</span></span>

<span data-ttu-id="99fdb-116">Više informacija potražite u članku [Rešavanje problema sa aplikacijama koje ne pripadaju pregledaču koje ne mogu da se prijave na Office 365, Azure ili Intune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).</span><span class="sxs-lookup"><span data-stu-id="99fdb-116">For more information, see [How to troubleshoot non-browser apps that can't sign in to Office 365, Azure, or Intune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).</span></span>

