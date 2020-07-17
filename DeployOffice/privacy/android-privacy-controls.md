---
title: „Office“ privatumo valdiklių valdymas „Android“ įrenginiuose naudojant strategijų parametrus
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Pateikiama informacija „Office“ administratoriams, kaip valdyti „Office“ privatumo parametrus „Android“ įrenginiuose.
hideEdit: true
ms.openlocfilehash: 6086ecd1b2cd55bbf6cb4577879714f1d20a2f93
ms.sourcegitcommit: 81295dff0f2fa474f0db39fd40560e3a23fff32a
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 07/09/2020
ms.locfileid: "45092126"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-office-on-android-devices"></a><span data-ttu-id="70217-103">„Office“ privatumo valdiklių valdymas „Android“ įrenginiuose naudojant strategijų parametrus</span><span class="sxs-lookup"><span data-stu-id="70217-103">Use policy settings to manage privacy controls for Office on Android devices</span></span>

<span data-ttu-id="70217-104">Yra strategijų parametrų, skirtų „Office“ programoms „Android“ įrenginiuose, leidžiančių valdyti parametrus, susijusius su:</span><span class="sxs-lookup"><span data-stu-id="70217-104">There are policy settings for Office on Android devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="70217-105">***Diagnostikos duomenimis*** apie „Office“ kliento naudojamą programinę įrangą, kurie renkami ir siunčiami „Microsoft“.</span><span class="sxs-lookup"><span data-stu-id="70217-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="70217-106">***Prisijungus naudojamų funkcijų***, kurios veikia debesų technologijos pagrindu ir pagerina jūsų ir jūsų vartotojų naudojamas „Office“ funkcijas.</span><span class="sxs-lookup"><span data-stu-id="70217-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="70217-107">Daugiau informacijos apie diagnostikos duomenis ir prisijungus naudojamas funkcijas žr. [Privatumo valdiklių apžvalga](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="70217-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="70217-108">Šie strategijų parametrai taikomi šioms programoms:</span><span class="sxs-lookup"><span data-stu-id="70217-108">These policy settings apply to the following applications:</span></span>
- <span data-ttu-id="70217-109">16.0.12228.20260 ir naujesnės „Word“, skirtos „Android“, „Excel“, skirtos „Android“, ir „PowerPoint“, skirtos „Android“, versijos.</span><span class="sxs-lookup"><span data-stu-id="70217-109">Version 16.0.12228.20260 and later of Word for Android, Excel for Android, and PowerPoint for Android.</span></span>
- <span data-ttu-id="70217-110">4.1.71 ir naujesnės „Outlook“, skirtos „Android“, versijos.</span><span class="sxs-lookup"><span data-stu-id="70217-110">Version 4.1.71 and later of Outlook for Android.</span></span>
- <span data-ttu-id="70217-111">16.0.12228.20004 ir naujesnės „OneNote“, skirtos „Android“, versijos.</span><span class="sxs-lookup"><span data-stu-id="70217-111">Version 16.0.12228.20004 and later of OneNote for Android.</span></span>
- <span data-ttu-id="70217-112">5.47 ir naujesnės „OneDrive“, skirtos „Android“, versijos.</span><span class="sxs-lookup"><span data-stu-id="70217-112">Version 5.47 and later of OneDrive for Android.</span></span>
- <span data-ttu-id="70217-113">16.0.12430.20254 ir naujesnės programėlės „Office“, skirtos „Android“, versijos.</span><span class="sxs-lookup"><span data-stu-id="70217-113">Version 16.0.12430.20254 and later of the Office app for Android.</span></span>

## <a name="policy-settings-available-for-office-on-android-devices"></a><span data-ttu-id="70217-114">„Office“ strategijų parametrai „Android“ įrenginiuose</span><span class="sxs-lookup"><span data-stu-id="70217-114">Policy settings available for Office on Android devices</span></span>

<span data-ttu-id="70217-115">Toliau esančioje lentelėje nurodoma, kurie „Office“ strategijų parametrai galimi „Android“ įrenginiuose, ir pateikiamas saitas į papildomą informaciją apie kiekvieną strategijos parametrą.</span><span class="sxs-lookup"><span data-stu-id="70217-115">The following table lists which policy settings are available for Office on Android devices and a link to additional information about each policy setting.</span></span>

> [!NOTE]
>- <span data-ttu-id="70217-116">Pateikta papildoma informacija apima „Office“ strategijų parametrus įrenginiuose, kuriuose veikia „Windows“.</span><span class="sxs-lookup"><span data-stu-id="70217-116">The additional information provided covers the policy settings for Office on devices running Windows.</span></span> <span data-ttu-id="70217-117">Tačiau ta pati informacija taikoma ir „Office“, kuris veikia „Android“ įrenginiuose, nes tai yra tie patys strategijų parametrai.</span><span class="sxs-lookup"><span data-stu-id="70217-117">But the same information applies to Office on Android devices because they are the same policy settings.</span></span>
>- <span data-ttu-id="70217-118">Strategijos parametras *Leisti „Office“ naudoti prisijungus naudojamas funkcijas*, kuris galimas „Office“ programose įrenginiuose, kuriuose veikia „Windows“, netaikomas „Office“ programoms „Android“ įrenginiuose.</span><span class="sxs-lookup"><span data-stu-id="70217-118">The *Allow the use of connected experiences in Office* policy setting that's available for Office on devices running Windows does not apply to Office on Android devices.</span></span> 


|<span data-ttu-id="70217-119">Strategijos parametro pavadinimas</span><span class="sxs-lookup"><span data-stu-id="70217-119">Name of policy setting</span></span>  |<span data-ttu-id="70217-120">Papildoma informacija</span><span class="sxs-lookup"><span data-stu-id="70217-120">Additional information</span></span> |
|---------|---------|
|<span data-ttu-id="70217-121">Kliento programinės įrangos diagnostikos duomenų, kurį „Office“ siunčia „Microsoft“ tarnybai, lygio konfigūravimas</span><span class="sxs-lookup"><span data-stu-id="70217-121">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>|[<span data-ttu-id="70217-122">Diagnostikos duomenų strategijų parametrai</span><span class="sxs-lookup"><span data-stu-id="70217-122">Policy setting for diagnostic data</span></span>](manage-privacy-controls.md#policy-setting-for-diagnostic-data)         |
|<span data-ttu-id="70217-123">Leisti „Office" naudoti prisijungus naudojamas funkcijas, analizuojančias turinį</span><span class="sxs-lookup"><span data-stu-id="70217-123">Allow the use of connected experiences in Office that analyze content</span></span>| [<span data-ttu-id="70217-124">Prisijungus naudojamų funkcijų, kurios analizuoja turinį, strategijos parametras</span><span class="sxs-lookup"><span data-stu-id="70217-124">Policy setting for connected experiences that analyze your content</span></span>](manage-privacy-controls.md#policy-setting-for-connected-experiences-that-analyze-your-content)        |
|<span data-ttu-id="70217-125">Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios parsiunčia internetinį turinį</span><span class="sxs-lookup"><span data-stu-id="70217-125">Allow the use of connected experiences in Office that download online content</span></span> |[<span data-ttu-id="70217-126">Strategijos parametras prisijungus naudojamoms funkcijoms, kurios atsisiunčia internetinį turinį</span><span class="sxs-lookup"><span data-stu-id="70217-126">Policy setting for connected experiences that download online content</span></span>](manage-privacy-controls.md#policy-setting-for-connected-experiences-that-download-online-content)         |
|<span data-ttu-id="70217-127">Leisti „Office“ naudoti pasirinktines papildomas prisijungus naudojamas funkcijas </span><span class="sxs-lookup"><span data-stu-id="70217-127">Allow the use of additional optional connected experiences in Office</span></span> |[<span data-ttu-id="70217-128">Strategijų parametrai pasirinktinėms prisijungus naudojamoms funkcijoms</span><span class="sxs-lookup"><span data-stu-id="70217-128">Policy setting for optional connected experiences</span></span>](manage-privacy-controls.md#policy-setting-for-optional-connected-experiences)|



## <a name="use-office-cloud-policy-service-to-apply-policy-settings"></a><span data-ttu-id="70217-129">Strategijų parametrų taikymas naudojant „Office“ debesies strategijų tarnybą</span><span class="sxs-lookup"><span data-stu-id="70217-129">Use Office cloud policy service to apply policy settings</span></span>

<span data-ttu-id="70217-130">Norėdami pritaikyti bet kurį iš šių 4 strategijų parametrų „Office“, veikiančiame „Android“ įrenginiuose, turite naudoti „Office“ debesies strategijų tarnybą.</span><span class="sxs-lookup"><span data-stu-id="70217-130">To apply any of these 4 policy settings for Office on Android devices, you need to use the Office cloud policy service.</span></span> <span data-ttu-id="70217-131">Daugiau informacijos apie „Office“ debesies strategijų tarnybos naudojimą rasite straipsnyje [„Office“ debesies strategijų tarnybos apžvalga](../overview-office-cloud-policy-service.md).</span><span class="sxs-lookup"><span data-stu-id="70217-131">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

> [!NOTE]
> <span data-ttu-id="70217-132">Jei anksčiau naudojote „Office“ debesies strategijų tarnybą norėdami konfigūruoti šiuos „Office“ strategijų parametrus įrenginiuose, kuriuose veikia „Windows“, tie patys parametrai taikomi ir naudojant „Office“ „Android“ įrenginiuose.</span><span class="sxs-lookup"><span data-stu-id="70217-132">If you previously used Office cloud policy service to configure these policy settings for Office on devices running Windows, those same settings will apply to Office on Android devices.</span></span> <span data-ttu-id="70217-133">Kad taip būtų, jums tereikia prisijungti prie „Office“ debesies strategijų tarnybos ir ši tarnyba automatiškai pritaikys parametrus „Office“ programoms „Android“ įrenginiuose.</span><span class="sxs-lookup"><span data-stu-id="70217-133">For that to happen, you just need to sign in to the Office cloud policy service and the service will apply the settings automatically to Office on Android devices.</span></span>
