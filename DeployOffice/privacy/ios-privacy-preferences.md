---
title: „Office“ privatumo valdiklių valdymas „iOS“ įrenginiuose naudojant nuostatas
ms.author: danbrown
author: pbowden-msft
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
- Ent_Office_Mac
description: Suteikia informacijos „Office“ administratoriams, kaip valdyti privatumo parametrus „iOS“ įrenginiuose.
hideEdit: true
ms.openlocfilehash: 40fc1ec1f5b2abc587e1b5224dc7fe0a5a656f33
ms.sourcegitcommit: 3890a23390edd0b5fdb2cf33613ec0778566cf97
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 05/01/2020
ms.locfileid: "43992114"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="3f2de-103">„Office“ privatumo valdiklių valdymas „iOS“ įrenginiuose naudojant nuostatas</span><span class="sxs-lookup"><span data-stu-id="3f2de-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

<span data-ttu-id="3f2de-104">Yra naujų nuostatų parametrų, skirtų „Office“ „iOS“ įrenginiuose, leidžiančių valdyti parametrus, susijusius su:</span><span class="sxs-lookup"><span data-stu-id="3f2de-104">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="3f2de-105">***Diagnostikos duomenimis*** apie „Office“ kliento naudojamą programinę įrangą, kurie renkami ir siunčiami „Microsoft“.</span><span class="sxs-lookup"><span data-stu-id="3f2de-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="3f2de-106">***Prisijungus naudojamų funkcijų***, kurios veikia debesų technologijos pagrindu ir pagerina jūsų ir jūsų vartotojų naudojamas „Office“ funkcijas.</span><span class="sxs-lookup"><span data-stu-id="3f2de-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="3f2de-107">Daugiau informacijos apie diagnostikos duomenis ir prijungtąsias funkcijas žr. [Privatumo valdiklių apžvalga](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="3f2de-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="3f2de-108">Šie nuostatų parametrai taikomi šioms programoms:</span><span class="sxs-lookup"><span data-stu-id="3f2de-108">These preference settings apply to the following applications:</span></span>
- <span data-ttu-id="3f2de-109">2.30 ir naujesnės versijos „Word“, skirtai „iOS“, „Excel“, skirtai „iOS“, ir „PowerPoint“, skirtai „iOS“.</span><span class="sxs-lookup"><span data-stu-id="3f2de-109">Version 2.30 and later of Word for iOS, Excel for iOS, and PowerPoint for iOS.</span></span>
- <span data-ttu-id="3f2de-110">16.30 ir naujesnės versijos „OneNote“, skirtai „iOS“.</span><span class="sxs-lookup"><span data-stu-id="3f2de-110">Version 16.30 and later of OneNote for iOS.</span></span>
- <span data-ttu-id="3f2de-111">1.17 ir naujesnės versijos „Visio“ peržiūros programai, skirtai „iOS“.</span><span class="sxs-lookup"><span data-stu-id="3f2de-111">Version 1.17 and later of Visio Viewer for iOS.</span></span>

> [!NOTE]
> <span data-ttu-id="3f2de-112">Informaciją apie panašius „Office“ parametrus „macOS“ kompiuteriuose žr. [„Office“ privatumo valdiklių valdymas „macOS“ įrenginiuose naudojant nuostatas](mac-privacy-preferences.md).</span><span class="sxs-lookup"><span data-stu-id="3f2de-112">For information about similar settings for Office on computers running macOS, see [Use preferences to manage privacy controls for Office for Mac](mac-privacy-preferences.md)</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="3f2de-113">Įrenginio nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="3f2de-113">Setting device preferences</span></span>
<span data-ttu-id="3f2de-114">Šiuos naujus nuostatų parametrus taip pat galima nustatyti mobiliojo įrenginio valdymo (MDM) serveryje įrenginio lygiu, kai įdiegta „Office“ taikomoji programa.</span><span class="sxs-lookup"><span data-stu-id="3f2de-114">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="3f2de-115">Daug MDM serverių leidžia IT administratoriams įtraukti pasirinktinį konfigūravimo žodyną, kai serveris siunčia `InstallApplication` MDM komandą į „iOS“ įrenginį.</span><span class="sxs-lookup"><span data-stu-id="3f2de-115">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="3f2de-116">Jei reikia daugiau informacijos, žr. MDM serverio dokumentaciją.</span><span class="sxs-lookup"><span data-stu-id="3f2de-116">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="3f2de-117">Žodynas vaizduojamas kaip raktų/reikšmių porų rinkinys XML formatu.</span><span class="sxs-lookup"><span data-stu-id="3f2de-117">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="3f2de-118">Pavyzdžiui:</span><span class="sxs-lookup"><span data-stu-id="3f2de-118">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="3f2de-119">Kai nusiųsite į įrenginį, konfigūravimo žodynas bus rodomas po `com.apple.managed.configuration` klavišu, kur jis bus perskaitytas, kai bus paleista „Office“ taikomoji programa.</span><span class="sxs-lookup"><span data-stu-id="3f2de-119">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

> [!NOTE]
> <span data-ttu-id="3f2de-120">Taip pat galite naudoti „Office“ debesies strategijos tarnybą ir šiuos 4 strategijos parametrus:</span><span class="sxs-lookup"><span data-stu-id="3f2de-120">You can also use the Office cloud policy service and these 4 policy settings:</span></span>
> - <span data-ttu-id="3f2de-121">Konfigūruoti kliento programinės įrangos diagnostikos duomenų lygį, kuriuos „Office“ siunčia „Microsoft“ tarnybai</span><span class="sxs-lookup"><span data-stu-id="3f2de-121">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>
> - <span data-ttu-id="3f2de-122">Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios analizuoja turinį</span><span class="sxs-lookup"><span data-stu-id="3f2de-122">Allow the use of connected experiences in Office that analyze content</span></span>
> - <span data-ttu-id="3f2de-123">Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios parsiunčia internetinį turinį</span><span class="sxs-lookup"><span data-stu-id="3f2de-123">Allow the use of connected experiences in Office that download online content</span></span>
> - <span data-ttu-id="3f2de-124">Leisti „Office“ naudoti pasirinktines, papildomas prisijungus naudojamas funkcijas </span><span class="sxs-lookup"><span data-stu-id="3f2de-124">Allow the use of additional optional connected experiences in Office</span></span>
>
> <span data-ttu-id="3f2de-125">Daugiau informacijos apie „Office“ debesies strategijų tarnybos naudojimą rasite straipsnyje [„Office“ debesies strategijų tarnybos apžvalga](../overview-office-cloud-policy-service.md).</span><span class="sxs-lookup"><span data-stu-id="3f2de-125">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="3f2de-126">Diagnostikos duomenų nuostatos nustatymas</span><span class="sxs-lookup"><span data-stu-id="3f2de-126">Preference setting for diagnostic data</span></span>

<span data-ttu-id="3f2de-127">Diagnostikos duomenys naudojami siekiant apsaugoti ir naujinti „Office“, aptikti, diagnozuoti ir spręsti problemas, taip pat tobulinti produktus.</span><span class="sxs-lookup"><span data-stu-id="3f2de-127">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="3f2de-128">Daugiau informacijos žr. [Diagnostikos duomenys, siunčiami „Microsoft“ iš „Microsoft 365“ programų įmonėms](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="3f2de-128">For more information, see [Diagnostic data sent from Microsoft 365 Apps for enterprise to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="3f2de-129">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="3f2de-129">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="3f2de-130">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="3f2de-130">**Data Type**</span></span>  | <span data-ttu-id="3f2de-131">Eilutė</span><span class="sxs-lookup"><span data-stu-id="3f2de-131">String</span></span> |
|<span data-ttu-id="3f2de-132">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="3f2de-132">**Possible values**</span></span>  | <span data-ttu-id="3f2de-133">`BasicDiagnosticData` *(nustatomas lygis Privalomieji)*</span><span class="sxs-lookup"><span data-stu-id="3f2de-133">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="3f2de-134">`FullDiagnosticData` *(nustatomas lygis Pasirinktiniai)*</span><span class="sxs-lookup"><span data-stu-id="3f2de-134">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="3f2de-135">`ZeroDiagnosticData` *(nustatomas lygis Nė vienas)*</span><span class="sxs-lookup"><span data-stu-id="3f2de-135">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="3f2de-136">Jei nenustatysite šios nuostatos, „Microsoft“ bus siunčiami tik privalomieji diagnostikos duomenys, jei vartotojai, turintys „Office 365“ (arba „Microsoft 365“) prenumeratą, bus prisijungę naudodami darbo arba mokymo įstaigos paskyrą.</span><span class="sxs-lookup"><span data-stu-id="3f2de-136">If you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 (or Microsoft 365) subscription are signed in with a work or school account.</span></span> <span data-ttu-id="3f2de-137">Be to, šie vartotojai negali pakeisti diagnostikos duomenų lygio, neatsižvelgiant į tai, kaip nustatėte šią nuostatą.</span><span class="sxs-lookup"><span data-stu-id="3f2de-137">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="3f2de-138">Kitų vartotojų, pvz., namų vartotojų, turinčių „Office 365“ (arba „Microsoft 365“) prenumeratą, siunčiami tik privalomieji diagnostikos duomenys, nebent vartotojas pasirenka taip pat siųsti pasirinktinius diagnostikos duomenis eidamas į sritį **Parametrai** > **Privatumo parametrai**.</span><span class="sxs-lookup"><span data-stu-id="3f2de-138">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Settings** > **Privacy Settings**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="3f2de-139">Turinį analizuojančių prisijungus naudojamų funkcijų nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="3f2de-139">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="3f2de-140">Turinį analizuojančios prijungtosios funkcijos yra funkcijos, kurios naudodamos „Office“ turinį pateikia dizaino rekomendacijų, redagavimo pasiūlymų, duomenų įžvalgų ir panašių funkcijų.</span><span class="sxs-lookup"><span data-stu-id="3f2de-140">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="3f2de-141">Pvz., „PowerPoint“ dizaino idėjos.</span><span class="sxs-lookup"><span data-stu-id="3f2de-141">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="3f2de-142">Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos „Office“](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="3f2de-142">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="3f2de-143">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="3f2de-143">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="3f2de-144">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="3f2de-144">**Data Type**</span></span>  | <span data-ttu-id="3f2de-145">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="3f2de-145">Boolean</span></span> |
|<span data-ttu-id="3f2de-146">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="3f2de-146">**Possible values**</span></span>  | <span data-ttu-id="3f2de-147">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="3f2de-147">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="3f2de-148">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="3f2de-148">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="3f2de-149">Jei nenustatysite šios nuostatos, vartotojams bus pasiekiamos turinį analizuojančios prijungtosios funkcijos.</span><span class="sxs-lookup"><span data-stu-id="3f2de-149">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="3f2de-150">Jei vartotojas turi „Office 365“ (arba „Microsoft 365“) prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą, jis negali išjungti prijungtųjų funkcijų, kurios analizuoja turinį.</span><span class="sxs-lookup"><span data-stu-id="3f2de-150">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="3f2de-151">Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ (arba „Microsoft 365“) prenumeratą, gali pasirinkti išjungti prijungtąsias funkcijas, kurios analizuoja turinį, nuėję į sritį **Nustatymai** > **Privatumo nustatymai**.</span><span class="sxs-lookup"><span data-stu-id="3f2de-151">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that analyze content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="3f2de-152">Prijungtųjų funkcijų, kurios atsisiunčia internetinį turinį, nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="3f2de-152">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="3f2de-153">Prisijungus naudojamos funkcijos, kurios atsisiunčia internetinį turinį, yra funkcijos, kurias naudodami galite ieškoti internetinio turinio ir jį atsisiųsti, įskaitant šablonus, vaizdus, vaizdo įrašus ir pagalbinę medžiagą, kad patobulintumėte dokumentus.</span><span class="sxs-lookup"><span data-stu-id="3f2de-153">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="3f2de-154">Pvz., „Office“ šablonai ar internetinės piktogramos įterpimas.</span><span class="sxs-lookup"><span data-stu-id="3f2de-154">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="3f2de-155">Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos „Office“](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="3f2de-155">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="3f2de-156">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="3f2de-156">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="3f2de-157">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="3f2de-157">**Data Type**</span></span>  | <span data-ttu-id="3f2de-158">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="3f2de-158">Boolean</span></span> |
|<span data-ttu-id="3f2de-159">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="3f2de-159">**Possible values**</span></span>  | <span data-ttu-id="3f2de-160">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="3f2de-160">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="3f2de-161">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="3f2de-161">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="3f2de-162">Jei nenustatysite šios nuostatos, vartotojams bus pasiekiamos internetinį turinį atsisiunčiančios prijungtosios funkcijos.</span><span class="sxs-lookup"><span data-stu-id="3f2de-162">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="3f2de-163">Jei vartotojas turi „Office 365“ (arba „Microsoft 365“) prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą, jis negali išjungti prijungtųjų funkcijų, kurios atsisiunčia interneto turinį.</span><span class="sxs-lookup"><span data-stu-id="3f2de-163">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="3f2de-164">Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ (arba „Microsoft 365“) prenumeratą, gali pasirinkti išjungti prijungtas funkcijas, kurios atsisiunčia interneto turinį, nuėję į sritį **Nustatymai** > **Privatumo nustatymai**.</span><span class="sxs-lookup"><span data-stu-id="3f2de-164">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that download online content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="3f2de-165">Pasirinktinių prijungtųjų funkcijų nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="3f2de-165">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="3f2de-166">Be anksčiau minėtų prijungtųjų funkcijų, yra tam tikrų pasirinktinių prijungtųjų funkcijų, kurias galite leisti pasiekti vartotojams, prisijungusiems su organizacijos paskyra, kuri kartais vadinama darbo arba mokymo įstaigos paskyra.</span><span class="sxs-lookup"><span data-stu-id="3f2de-166">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="3f2de-167">Pvz., „Office“ papildiniai, atsisiunčiami iš „Office“ parduotuvės į jūsų įrenginį.</span><span class="sxs-lookup"><span data-stu-id="3f2de-167">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="3f2de-168">Daugiau pavyzdžių rasite [Pasirinktinių „Office“ prisijungus naudojamų funkcijų apžvalga](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="3f2de-168">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="3f2de-169">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="3f2de-169">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="3f2de-170">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="3f2de-170">**Data Type**</span></span>  | <span data-ttu-id="3f2de-171">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="3f2de-171">Boolean</span></span> |
|<span data-ttu-id="3f2de-172">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="3f2de-172">**Possible values**</span></span>  | <span data-ttu-id="3f2de-173">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="3f2de-173">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="3f2de-174">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="3f2de-174">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="3f2de-175">Jei nenustatysite šios nuostatos, pasirinktinės prijungtosios funkcijos bus pasiekiamos vartotojams, turintiems „Office 365“ (arba „Microsoft 365“) prenumeratą, kurie yra prisijungę naudodami darbo ar mokymo įstaigos paskyrą.</span><span class="sxs-lookup"><span data-stu-id="3f2de-175">If you don't set this preference, optional connected experiences are available to users with an Office 365 (or Microsoft 365) subscription that are signed in with a work or school account.</span></span> <span data-ttu-id="3f2de-176">Jei nenustatėte šios nuostatos į FALSE (klaidinga), šie vartotojai gali pasirinkti išjungti pasirinktines prijungtąsias funkcijas nuėję į **Parametrai**  >  \*\*Privatumo parametrai \*\*.</span><span class="sxs-lookup"><span data-stu-id="3f2de-176">Unless you have set this preference to FALSE, these users can choose to turn off optional connected experiences by going to **Settings** > **Privacy Settings**.</span></span>

<span data-ttu-id="3f2de-177">Kitiems vartotojams, pvz., namų vartotojams, turintiems „Office 365“ (arba „Microsoft 365“) prenumeratą, neteikiama galimybė išjungti pasirinktines prijungtąsias funkcijas.</span><span class="sxs-lookup"><span data-stu-id="3f2de-177">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, there isn't an option to turn off optional connected experiences.</span></span>