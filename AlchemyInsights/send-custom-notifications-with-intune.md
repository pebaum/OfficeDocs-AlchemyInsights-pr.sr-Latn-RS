---
title: Pošalji korisnička obaveštenja pomoću Intune
ms.author: brenduns
author: brenduns
manager: dougeby
ms.date: 07/31/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000679
ms.openlocfilehash: 1244f07fd56cf603280f1710520a04d579224e44
ms.sourcegitcommit: 16f08d051afca3c6d0de32826324f91cf63ab5ba
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/16/2019
ms.locfileid: "36992326"
---
# <a name="how-to-send-custom-notifications-to-the-users-of-managed-ios-and-android-devices"></a><span data-ttu-id="d2887-102">Kako slati prilagođena obaveštenja korisnicima kontrolisanih iOS i Android uređaja</span><span class="sxs-lookup"><span data-stu-id="d2887-102">How to send custom notifications to the users of managed iOS and Android devices</span></span>

<span data-ttu-id="d2887-103">Na korisničkom uređaju obrađuje se prilagođena obaveštenja za Intune.</span><span class="sxs-lookup"><span data-stu-id="d2887-103">Custom notifications for Intune are processed by the Company Portal app on a user’s device.</span></span> <span data-ttu-id="d2887-104">Aplikacija zatim kreira push obaveštenja na tom uređaju.</span><span class="sxs-lookup"><span data-stu-id="d2887-104">The app then creates the push notification on that device.</span></span>

<span data-ttu-id="d2887-105">Slede preduslovi za uređaje za podržavanje prijema prilagođenih obaveštenja, kao i za aplikaciju koja zatim kreira Push obaveštenje:</span><span class="sxs-lookup"><span data-stu-id="d2887-105">The following are device prerequisites to support receipt of custom notifications, and for the app to then create the push notification:</span></span>

- <span data-ttu-id="d2887-106">Uređaj mora imati instaliranu aplikaciju "portal kompanije".</span><span class="sxs-lookup"><span data-stu-id="d2887-106">The device must have the Company Portal app installed.</span></span>  

- <span data-ttu-id="d2887-107">Uređaj mora da dozvoli aplikaciji Company da šalje push obaveštenja.</span><span class="sxs-lookup"><span data-stu-id="d2887-107">The device must allow the Company Portal app to send push notifications.</span></span> <span data-ttu-id="d2887-108">Kada se aplikacija instalira ili ažurira, on će zatražiti od korisnika da dozvoli obaveštenja.</span><span class="sxs-lookup"><span data-stu-id="d2887-108">When the app is installed or updated, it will prompt the user to permit notifications.</span></span>

- <span data-ttu-id="d2887-109">Android uređaji moraju imati instalirane usluge Google Play Services.</span><span class="sxs-lookup"><span data-stu-id="d2887-109">Android devices must have Google Play Services installed.</span></span>

- <span data-ttu-id="d2887-110">Uređaj mora biti upisan uz Intune.</span><span class="sxs-lookup"><span data-stu-id="d2887-110">The device must be enrolled with Intune.</span></span>

<span data-ttu-id="d2887-111">Više informacija o tome kako da pošaljete poruku potražite u [dokumentaciji funkcije](https://docs.microsoft.com/intune/custom-notifications).</span><span class="sxs-lookup"><span data-stu-id="d2887-111">For more information including how to send a message, see the [feature documentation](https://docs.microsoft.com/intune/custom-notifications).</span></span>
