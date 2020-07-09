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
ms.openlocfilehash: 6465a5b5e2103070170bdec8cd64b8bc044d46a3
ms.sourcegitcommit: f441b1a5f8853c0941b3e23c7781c89abf0be641
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 07/09/2020
ms.locfileid: "45087855"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="541a9-103">„Office“ privatumo valdiklių valdymas „iOS“ įrenginiuose naudojant nuostatas</span><span class="sxs-lookup"><span data-stu-id="541a9-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

<span data-ttu-id="541a9-104">Yra naujų nuostatų parametrų, skirtų „Office“ „iOS“ įrenginiuose, leidžiančių valdyti parametrus, susijusius su:</span><span class="sxs-lookup"><span data-stu-id="541a9-104">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="541a9-105">***Diagnostikos duomenimis*** apie „Office“ kliento naudojamą programinę įrangą, kurie renkami ir siunčiami „Microsoft“.</span><span class="sxs-lookup"><span data-stu-id="541a9-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="541a9-106">***Prisijungus naudojamų funkcijų***, kurios veikia debesų technologijos pagrindu ir pagerina jūsų ir jūsų vartotojų naudojamas „Office“ funkcijas.</span><span class="sxs-lookup"><span data-stu-id="541a9-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="541a9-107">Daugiau informacijos apie diagnostikos duomenis ir prijungtąsias funkcijas žr. [Privatumo valdiklių apžvalga](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="541a9-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="541a9-108">Šie nuostatų parametrai taikomi šioms programoms:</span><span class="sxs-lookup"><span data-stu-id="541a9-108">These preference settings apply to the following applications:</span></span>
- <span data-ttu-id="541a9-109">2.30 ir naujesnės versijos „Word“, skirtai „iOS“, „Excel“, skirtai „iOS“, ir „PowerPoint“, skirtai „iOS“.</span><span class="sxs-lookup"><span data-stu-id="541a9-109">Version 2.30 and later of Word for iOS, Excel for iOS, and PowerPoint for iOS.</span></span>
- <span data-ttu-id="541a9-110">4.30.0 ir naujesnės „Outlook“, skirtos „iOS“, versijos.</span><span class="sxs-lookup"><span data-stu-id="541a9-110">Version 4.30.0 and later of Outlook for iOS</span></span>
- <span data-ttu-id="541a9-111">16.30 ir naujesnės „OneNote“, skirtos „iOS“, versijos.</span><span class="sxs-lookup"><span data-stu-id="541a9-111">Version 16.30 and later of OneNote for iOS.</span></span>
- <span data-ttu-id="541a9-112">11.19.11 ir naujesnės „OneDrive“, skirtos „iOS“, versijos.</span><span class="sxs-lookup"><span data-stu-id="541a9-112">Version 11.19.11 and later of OneDrive for iOS.</span></span>
- <span data-ttu-id="541a9-113">1.17 ir naujesnės versijos „Visio“ peržiūros programai, skirtai „iOS“.</span><span class="sxs-lookup"><span data-stu-id="541a9-113">Version 1.17 and later of Visio Viewer for iOS.</span></span>

> [!NOTE]
> <span data-ttu-id="541a9-114">Informaciją apie panašius „Office“ parametrus „macOS“ kompiuteriuose žr. [„Office“ privatumo valdiklių valdymas „macOS“ įrenginiuose naudojant nuostatas](mac-privacy-preferences.md).</span><span class="sxs-lookup"><span data-stu-id="541a9-114">For information about similar settings for Office on computers running macOS, see [Use preferences to manage privacy controls for Office for Mac](mac-privacy-preferences.md)</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="541a9-115">Įrenginio nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="541a9-115">Setting device preferences</span></span>
<span data-ttu-id="541a9-116">Šiuos naujus nuostatų parametrus taip pat galima nustatyti mobiliojo įrenginio valdymo (MDM) serveryje įrenginio lygiu, kai įdiegta „Office“ taikomoji programa.</span><span class="sxs-lookup"><span data-stu-id="541a9-116">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="541a9-117">Daug MDM serverių leidžia IT administratoriams įtraukti pasirinktinį konfigūravimo žodyną, kai serveris siunčia `InstallApplication` MDM komandą į „iOS“ įrenginį.</span><span class="sxs-lookup"><span data-stu-id="541a9-117">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="541a9-118">Jei reikia daugiau informacijos, žr. MDM serverio dokumentaciją.</span><span class="sxs-lookup"><span data-stu-id="541a9-118">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="541a9-119">Žodynas vaizduojamas kaip raktų/reikšmių porų rinkinys XML formatu.</span><span class="sxs-lookup"><span data-stu-id="541a9-119">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="541a9-120">Pavyzdžiui:</span><span class="sxs-lookup"><span data-stu-id="541a9-120">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="541a9-121">Kai nusiųsite į įrenginį, konfigūravimo žodynas bus rodomas po `com.apple.managed.configuration` klavišu, kur jis bus perskaitytas, kai bus paleista „Office“ taikomoji programa.</span><span class="sxs-lookup"><span data-stu-id="541a9-121">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

> [!NOTE]
> <span data-ttu-id="541a9-122">Taip pat galite naudoti „Office“ debesies strategijos tarnybą ir šiuos 4 strategijos parametrus:</span><span class="sxs-lookup"><span data-stu-id="541a9-122">You can also use the Office cloud policy service and these 4 policy settings:</span></span>
> - <span data-ttu-id="541a9-123">Konfigūruoti kliento programinės įrangos diagnostikos duomenų lygį, kuriuos „Office“ siunčia „Microsoft“ tarnybai</span><span class="sxs-lookup"><span data-stu-id="541a9-123">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>
> - <span data-ttu-id="541a9-124">Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios analizuoja turinį</span><span class="sxs-lookup"><span data-stu-id="541a9-124">Allow the use of connected experiences in Office that analyze content</span></span>
> - <span data-ttu-id="541a9-125">Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios parsiunčia internetinį turinį</span><span class="sxs-lookup"><span data-stu-id="541a9-125">Allow the use of connected experiences in Office that download online content</span></span>
> - <span data-ttu-id="541a9-126">Leisti „Office“ naudoti pasirinktines, papildomas prisijungus naudojamas funkcijas </span><span class="sxs-lookup"><span data-stu-id="541a9-126">Allow the use of additional optional connected experiences in Office</span></span>
>
> <span data-ttu-id="541a9-127">„Outlook“ skirtos „iOS“ ir „OneDrive“ skirtos „iOS: privatumo parametrai gali būti konfigūruojami tik naudojant „Office“ debesies strategijos tarnybą.</span><span class="sxs-lookup"><span data-stu-id="541a9-127">Privacy settings for Outlook for iOS and OneDrive for iOS can only be configured by using the Office cloud policy service.</span></span>
>
> <span data-ttu-id="541a9-128">Daugiau informacijos apie „Office“ debesies strategijų tarnybos naudojimą rasite straipsnyje [„Office“ debesies strategijų tarnybos apžvalga](../overview-office-cloud-policy-service.md).</span><span class="sxs-lookup"><span data-stu-id="541a9-128">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="541a9-129">Diagnostikos duomenų nuostatos nustatymas</span><span class="sxs-lookup"><span data-stu-id="541a9-129">Preference setting for diagnostic data</span></span>

<span data-ttu-id="541a9-130">Diagnostikos duomenys naudojami siekiant apsaugoti ir naujinti „Office“, aptikti, diagnozuoti ir spręsti problemas, taip pat tobulinti produktus.</span><span class="sxs-lookup"><span data-stu-id="541a9-130">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="541a9-131">Daugiau informacijos žr. [Diagnostikos duomenys, siunčiami „Microsoft“ iš „Microsoft 365“ programų įmonėms](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="541a9-131">For more information, see [Diagnostic data sent from Microsoft 365 Apps for enterprise to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="541a9-132">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="541a9-132">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="541a9-133">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="541a9-133">**Data Type**</span></span>  | <span data-ttu-id="541a9-134">Eilutė</span><span class="sxs-lookup"><span data-stu-id="541a9-134">String</span></span> |
|<span data-ttu-id="541a9-135">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="541a9-135">**Possible values**</span></span>  | <span data-ttu-id="541a9-136">`BasicDiagnosticData` *(nustatomas lygis Privalomieji)*</span><span class="sxs-lookup"><span data-stu-id="541a9-136">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="541a9-137">`FullDiagnosticData` *(nustatomas lygis Pasirinktiniai)*</span><span class="sxs-lookup"><span data-stu-id="541a9-137">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="541a9-138">`ZeroDiagnosticData` *(nustatomas lygis Nė vienas)*</span><span class="sxs-lookup"><span data-stu-id="541a9-138">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="541a9-139">Jei nenustatysite šios nuostatos, „Microsoft“ bus siunčiami tik privalomieji diagnostikos duomenys, jei vartotojai, turintys „Office 365“ (arba „Microsoft 365“) prenumeratą, bus prisijungę naudodami darbo arba mokymo įstaigos paskyrą.</span><span class="sxs-lookup"><span data-stu-id="541a9-139">If you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 (or Microsoft 365) subscription are signed in with a work or school account.</span></span> <span data-ttu-id="541a9-140">Be to, šie vartotojai negali pakeisti diagnostikos duomenų lygio, neatsižvelgiant į tai, kaip nustatėte šią nuostatą.</span><span class="sxs-lookup"><span data-stu-id="541a9-140">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="541a9-141">Kitų vartotojų, pvz., namų vartotojų, turinčių „Office 365“ (arba „Microsoft 365“) prenumeratą, siunčiami tik privalomieji diagnostikos duomenys, nebent vartotojas pasirenka taip pat siųsti pasirinktinius diagnostikos duomenis eidamas į sritį **Parametrai** > **Privatumo parametrai**.</span><span class="sxs-lookup"><span data-stu-id="541a9-141">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Settings** > **Privacy Settings**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="541a9-142">Turinį analizuojančių prisijungus naudojamų funkcijų nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="541a9-142">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="541a9-143">Turinį analizuojančios prijungtosios funkcijos yra funkcijos, kurios naudodamos „Office“ turinį pateikia dizaino rekomendacijų, redagavimo pasiūlymų, duomenų įžvalgų ir panašių funkcijų.</span><span class="sxs-lookup"><span data-stu-id="541a9-143">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="541a9-144">Pvz., „PowerPoint“ dizaino idėjos.</span><span class="sxs-lookup"><span data-stu-id="541a9-144">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="541a9-145">Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos „Office“](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="541a9-145">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="541a9-146">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="541a9-146">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="541a9-147">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="541a9-147">**Data Type**</span></span>  | <span data-ttu-id="541a9-148">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="541a9-148">Boolean</span></span> |
|<span data-ttu-id="541a9-149">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="541a9-149">**Possible values**</span></span>  | <span data-ttu-id="541a9-150">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="541a9-150">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="541a9-151">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="541a9-151">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="541a9-152">Jei nenustatysite šios nuostatos, vartotojams bus pasiekiamos turinį analizuojančios prijungtosios funkcijos.</span><span class="sxs-lookup"><span data-stu-id="541a9-152">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="541a9-153">Jei vartotojas turi „Office 365“ (arba „Microsoft 365“) prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą, jis negali išjungti prijungtųjų funkcijų, kurios analizuoja turinį.</span><span class="sxs-lookup"><span data-stu-id="541a9-153">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="541a9-154">Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ (arba „Microsoft 365“) prenumeratą, gali pasirinkti išjungti prijungtąsias funkcijas, kurios analizuoja turinį, nuėję į sritį **Nustatymai** > **Privatumo nustatymai**.</span><span class="sxs-lookup"><span data-stu-id="541a9-154">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that analyze content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="541a9-155">Prijungtųjų funkcijų, kurios atsisiunčia internetinį turinį, nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="541a9-155">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="541a9-156">Prisijungus naudojamos funkcijos, kurios atsisiunčia internetinį turinį, yra funkcijos, kurias naudodami galite ieškoti internetinio turinio ir jį atsisiųsti, įskaitant šablonus, vaizdus, vaizdo įrašus ir pagalbinę medžiagą, kad patobulintumėte dokumentus.</span><span class="sxs-lookup"><span data-stu-id="541a9-156">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="541a9-157">Pvz., „Office“ šablonai ar internetinės piktogramos įterpimas.</span><span class="sxs-lookup"><span data-stu-id="541a9-157">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="541a9-158">Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos „Office“](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="541a9-158">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="541a9-159">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="541a9-159">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="541a9-160">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="541a9-160">**Data Type**</span></span>  | <span data-ttu-id="541a9-161">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="541a9-161">Boolean</span></span> |
|<span data-ttu-id="541a9-162">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="541a9-162">**Possible values**</span></span>  | <span data-ttu-id="541a9-163">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="541a9-163">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="541a9-164">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="541a9-164">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="541a9-165">Jei nenustatysite šios nuostatos, vartotojams bus pasiekiamos internetinį turinį atsisiunčiančios prijungtosios funkcijos.</span><span class="sxs-lookup"><span data-stu-id="541a9-165">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="541a9-166">Jei vartotojas turi „Office 365“ (arba „Microsoft 365“) prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą, jis negali išjungti prijungtųjų funkcijų, kurios atsisiunčia interneto turinį.</span><span class="sxs-lookup"><span data-stu-id="541a9-166">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="541a9-167">Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ (arba „Microsoft 365“) prenumeratą, gali pasirinkti išjungti prijungtas funkcijas, kurios atsisiunčia interneto turinį, nuėję į sritį **Nustatymai** > **Privatumo nustatymai**.</span><span class="sxs-lookup"><span data-stu-id="541a9-167">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that download online content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="541a9-168">Pasirinktinių prijungtųjų funkcijų nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="541a9-168">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="541a9-169">Be anksčiau minėtų prijungtųjų funkcijų, yra tam tikrų pasirinktinių prijungtųjų funkcijų, kurias galite leisti pasiekti vartotojams, prisijungusiems su organizacijos paskyra, kuri kartais vadinama darbo arba mokymo įstaigos paskyra.</span><span class="sxs-lookup"><span data-stu-id="541a9-169">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="541a9-170">Pvz., „Office“ papildiniai, atsisiunčiami iš „Office“ parduotuvės į jūsų įrenginį.</span><span class="sxs-lookup"><span data-stu-id="541a9-170">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="541a9-171">Daugiau pavyzdžių rasite [Pasirinktinių „Office“ prisijungus naudojamų funkcijų apžvalga](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="541a9-171">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="541a9-172">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="541a9-172">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="541a9-173">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="541a9-173">**Data Type**</span></span>  | <span data-ttu-id="541a9-174">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="541a9-174">Boolean</span></span> |
|<span data-ttu-id="541a9-175">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="541a9-175">**Possible values**</span></span>  | <span data-ttu-id="541a9-176">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="541a9-176">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="541a9-177">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="541a9-177">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="541a9-178">Jei nenustatysite šios nuostatos, pasirinktinės prijungtosios funkcijos bus pasiekiamos vartotojams, turintiems „Office 365“ (arba „Microsoft 365“) prenumeratą, kurie yra prisijungę naudodami darbo ar mokymo įstaigos paskyrą.</span><span class="sxs-lookup"><span data-stu-id="541a9-178">If you don't set this preference, optional connected experiences are available to users with an Office 365 (or Microsoft 365) subscription that are signed in with a work or school account.</span></span> <span data-ttu-id="541a9-179">Jei nenustatėte šios nuostatos į FALSE (klaidinga), šie vartotojai gali pasirinkti išjungti pasirinktines prijungtąsias funkcijas nuėję į **Parametrai**  >  \*\*Privatumo parametrai \*\*.</span><span class="sxs-lookup"><span data-stu-id="541a9-179">Unless you have set this preference to FALSE, these users can choose to turn off optional connected experiences by going to **Settings** > **Privacy Settings**.</span></span>

<span data-ttu-id="541a9-180">Kitiems vartotojams, pvz., namų vartotojams, turintiems „Office 365“ (arba „Microsoft 365“) prenumeratą, neteikiama galimybė išjungti pasirinktines prijungtąsias funkcijas.</span><span class="sxs-lookup"><span data-stu-id="541a9-180">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, there isn't an option to turn off optional connected experiences.</span></span>