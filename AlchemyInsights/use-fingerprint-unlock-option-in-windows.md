---
title: Korišćenje opcije za otključavanje otiska prsta u operativnom sistemu Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001689"
- "3765"
ms.openlocfilehash: 8a5059c722c306ad79811140062cec7f52f31766
ms.sourcegitcommit: 00e4266575438f55bdc18db05ed54aafcb75a3c9
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/11/2020
ms.locfileid: "42588329"
---
# <a name="use-fingerprint-unlock-option-in-windows-10"></a>Korišćenje opcije za otključavanje otiska prsta u operativnom sistemu Windows 10

**Omogući Windows Hello otisak prsta**

Da biste otključali Windows 10 pomoću otiska prsta, potrebno je da podesite Windows Hello otisak prsta tako što ćete dodati (Ako Windows nauči da prepozna) bar jedan prst. 

1. Izaberite **podešavanja > nalozi > opcije za prijavljivanje** (ili kliknite [ovde](ms-settings:signinoptions?activationSource=GetHelp)). Biće navedene raspoložive opcije za prijavljivanje. Na primer:

    ![Opcije za prijavljivanje.](media/sign-in-options.png)

2. Kliknite ili dodirnite **Windows Hello otisak prsta**, a zatim kliknite na dugme **Podesi**. U prozoru "Windows Hello podešavanje" kliknite na dugme " **Započni**". Senzor otisaka prstiju će se aktivirati i od vas će se zatražiti da postavite prst na senzor:

   ![Senzor otisaka prstiju.](media/fingerprint-sensor.png)

3. Sledite uputstva koja će vam zatražiti da više puta skenirate prst. Kada se ovo završi, imaćete mogućnost dodavanja ostalih prstiju koje ćete možda želeti da koristite za prijavljivanje. Sledeći put kada se prijavite u Windows 10, imaćete opciju da koristite otisak prsta da biste to uradili.

**Windows Hello otisak prsta nije dostupan kao opcija za prijavljivanje**

Ako Windows Hello otisak prsta nije prikazan kao opcija u **opcijama za prijavljivanje**, to znači da Windows nije upoznat sa bilo kojim čitačem otisaka prstiju/skenera koji je PRIKLJUČEN na računar ili da smernice sistema sprečavaju njeno korišćenje (ako na primer, računar upravlja vašim radnim mestom). Da biste rešili problem: 

1. Kliknite na dugme **Start** na traci zadataka i potražite **Upravljač uređajima**.

2. Kliknite ili dodirnite da biste otvorili **Upravljač uređajima**.

3. U upravljaču uređajima razvijte biometrijske uređaje tako što ćete kliknuti na njegov ševron.

   ![Biometrijske uređaje.](media/biometric-devices.png)

4. Skener otisaka prstiju bi trebalo da bude naveden kao biometrijski uređaj, kao što je Synaptics WBDI skener:

   ![Biometrijske uređaje.](media/biometric-devices-expanded.png)

5. Ako skener otisaka prstiju nije prikazan, a skener je integrisan u računar, posetite Veb lokaciju proizvođača računara. U odeljku za tehničku podršku za model računara potražite Windows 10 upravljački program za skener koji možete da instalirate.

6. Ako je skener odvojen od računara (priključen preko USB-a), posetite Veb lokaciju proizvođača skenera da biste pronašli i instalirali softver upravljačkog programa za Windows 10 za model skenera koji imate.
