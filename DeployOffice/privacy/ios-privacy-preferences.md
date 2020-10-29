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
ms.openlocfilehash: ed24ac934625bba61eac25e764a892d48365c005
ms.sourcegitcommit: 596a0a60394011aafe1119f353ac76f27e1a4d1b
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 10/29/2020
ms.locfileid: "48794665"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="2bc98-103">„Office“ privatumo valdiklių valdymas „iOS“ įrenginiuose naudojant nuostatas</span><span class="sxs-lookup"><span data-stu-id="2bc98-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

> [!NOTE]
> <span data-ttu-id="2bc98-104">„Office“ produktų, kuriems taikoma ši privatumo informacija, sąrašą žr. [Galimi „Office“ produktų privatumo valdikliai](products-versions-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="2bc98-104">For a list of Office products covered by this privacy information, see [Privacy controls available for Office products](products-versions-privacy-controls.md).</span></span>

<span data-ttu-id="2bc98-105">Yra naujų nuostatų parametrų, skirtų „Office“ „iOS“ įrenginiuose, leidžiančių valdyti parametrus, susijusius su:</span><span class="sxs-lookup"><span data-stu-id="2bc98-105">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="2bc98-106">\***Diagnostikos duomenimis** , kurie renkami ir siunčiami „Microsoft“, apie naudojamą „Office“ kliento programinę įrangą.</span><span class="sxs-lookup"><span data-stu-id="2bc98-106">\***Diagnostic data** _ that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="2bc98-107">_*_Prijungtosiomis funkcijomis_*_ , kurios veikia debesų technologijos pagrindu ir pagerina jūsų ir jūsų vartotojų naudojamas „Office“ funkcijas.</span><span class="sxs-lookup"><span data-stu-id="2bc98-107">_*_Connected experiences_*_ that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="2bc98-108">Daugiau informacijos apie diagnostikos duomenis ir prijungtąsias funkcijas žr. [Privatumo valdiklių apžvalga](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="2bc98-108">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

> [!NOTE]
> <span data-ttu-id="2bc98-109">Informaciją apie panašius „Office“ parametrus „macOS“ kompiuteriuose žr. [„Office“ privatumo valdiklių valdymas „macOS“ įrenginiuose naudojant nuostatas](mac-privacy-preferences.md).</span><span class="sxs-lookup"><span data-stu-id="2bc98-109">For information about similar settings for Office on computers running macOS, see [Use preferences to manage privacy controls for Office for Mac](mac-privacy-preferences.md)</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="2bc98-110">Įrenginio nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="2bc98-110">Setting device preferences</span></span>
<span data-ttu-id="2bc98-111">Šiuos naujus nuostatų parametrus taip pat galima nustatyti mobiliojo įrenginio valdymo (MDM) serveryje įrenginio lygiu, kai įdiegta „Office“ taikomoji programa.</span><span class="sxs-lookup"><span data-stu-id="2bc98-111">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="2bc98-112">Daug MDM serverių leidžia IT administratoriams įtraukti pasirinktinį konfigūravimo žodyną, kai serveris siunčia `InstallApplication` MDM komandą į „iOS“ įrenginį.</span><span class="sxs-lookup"><span data-stu-id="2bc98-112">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="2bc98-113">Jei reikia daugiau informacijos, žr. MDM serverio dokumentaciją.</span><span class="sxs-lookup"><span data-stu-id="2bc98-113">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="2bc98-114">Žodynas vaizduojamas kaip raktų/reikšmių porų rinkinys XML formatu.</span><span class="sxs-lookup"><span data-stu-id="2bc98-114">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="2bc98-115">Pavyzdžiui:</span><span class="sxs-lookup"><span data-stu-id="2bc98-115">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="2bc98-116">Kai nusiųsite į įrenginį, konfigūravimo žodynas bus rodomas po `com.apple.managed.configuration` klavišu, kur jis bus perskaitytas, kai bus paleista „Office“ taikomoji programa.</span><span class="sxs-lookup"><span data-stu-id="2bc98-116">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

> [!NOTE]
> <span data-ttu-id="2bc98-117">Taip pat galite naudoti „Office“ debesies strategijos tarnybą ir šiuos 4 strategijos parametrus:</span><span class="sxs-lookup"><span data-stu-id="2bc98-117">You can also use the Office cloud policy service and these 4 policy settings:</span></span>
> - <span data-ttu-id="2bc98-118">Konfigūruoti kliento programinės įrangos diagnostikos duomenų lygį, kuriuos „Office“ siunčia „Microsoft“ tarnybai</span><span class="sxs-lookup"><span data-stu-id="2bc98-118">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>
> - <span data-ttu-id="2bc98-119">Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios analizuoja turinį</span><span class="sxs-lookup"><span data-stu-id="2bc98-119">Allow the use of connected experiences in Office that analyze content</span></span>
> - <span data-ttu-id="2bc98-120">Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios parsiunčia internetinį turinį</span><span class="sxs-lookup"><span data-stu-id="2bc98-120">Allow the use of connected experiences in Office that download online content</span></span>
> - <span data-ttu-id="2bc98-121">Leisti „Office“ naudoti pasirinktines, papildomas prisijungus naudojamas funkcijas </span><span class="sxs-lookup"><span data-stu-id="2bc98-121">Allow the use of additional optional connected experiences in Office</span></span>
>
> <span data-ttu-id="2bc98-122">„Outlook“ skirtos „iOS“ ir „OneDrive“ skirtos „iOS: privatumo parametrai gali būti konfigūruojami tik naudojant „Office“ debesies strategijos tarnybą.</span><span class="sxs-lookup"><span data-stu-id="2bc98-122">Privacy settings for Outlook for iOS and OneDrive for iOS can only be configured by using the Office cloud policy service.</span></span>
>
> <span data-ttu-id="2bc98-123">Daugiau informacijos apie „Office“ debesies strategijų tarnybos naudojimą rasite straipsnyje [„Office“ debesies strategijų tarnybos apžvalga](../overview-office-cloud-policy-service.md).</span><span class="sxs-lookup"><span data-stu-id="2bc98-123">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="2bc98-124">Diagnostikos duomenų nuostatos nustatymas</span><span class="sxs-lookup"><span data-stu-id="2bc98-124">Preference setting for diagnostic data</span></span>

<span data-ttu-id="2bc98-125">Diagnostikos duomenys naudojami siekiant apsaugoti ir naujinti „Office“, aptikti, diagnozuoti ir spręsti problemas, taip pat tobulinti produktus.</span><span class="sxs-lookup"><span data-stu-id="2bc98-125">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="2bc98-126">Daugiau informacijos žr. [Diagnostikos duomenys, siunčiami „Microsoft“ iš „Microsoft 365“ programų įmonėms](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="2bc98-126">For more information, see [Diagnostic data sent from Microsoft 365 Apps for enterprise to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="2bc98-127">_ *Raktas*\*</span><span class="sxs-lookup"><span data-stu-id="2bc98-127">_ *Key*\*</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="2bc98-128">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="2bc98-128">**Data Type**</span></span>  | <span data-ttu-id="2bc98-129">Eilutė</span><span class="sxs-lookup"><span data-stu-id="2bc98-129">String</span></span> |
|<span data-ttu-id="2bc98-130">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="2bc98-130">**Possible values**</span></span>  | <span data-ttu-id="2bc98-131">`BasicDiagnosticData` *(nustatomas lygis Privalomieji)*</span><span class="sxs-lookup"><span data-stu-id="2bc98-131">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="2bc98-132">`FullDiagnosticData` *(nustatomas lygis Pasirinktiniai)*</span><span class="sxs-lookup"><span data-stu-id="2bc98-132">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="2bc98-133">`ZeroDiagnosticData` *(nustatomas lygis Nė vienas)*</span><span class="sxs-lookup"><span data-stu-id="2bc98-133">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="2bc98-134">Jei nenustatysite šios nuostatos, „Microsoft“ bus siunčiami tik privalomieji diagnostikos duomenys, jei vartotojai, turintys „Office 365“ (arba „Microsoft 365“) prenumeratą, bus prisijungę naudodami darbo arba mokymo įstaigos paskyrą.</span><span class="sxs-lookup"><span data-stu-id="2bc98-134">If you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 (or Microsoft 365) subscription are signed in with a work or school account.</span></span> <span data-ttu-id="2bc98-135">Be to, šie vartotojai negali pakeisti diagnostikos duomenų lygio, neatsižvelgiant į tai, kaip nustatėte šią nuostatą.</span><span class="sxs-lookup"><span data-stu-id="2bc98-135">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="2bc98-136">Kitų vartotojų, pvz., namų vartotojų, turinčių „Office 365“ (arba „Microsoft 365“) prenumeratą, siunčiami tik privalomieji diagnostikos duomenys, nebent vartotojas pasirenka taip pat siųsti pasirinktinius diagnostikos duomenis eidamas į sritį **Parametrai** > **Privatumo parametrai** .</span><span class="sxs-lookup"><span data-stu-id="2bc98-136">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Settings** > **Privacy Settings** .</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="2bc98-137">Turinį analizuojančių prisijungus naudojamų funkcijų nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="2bc98-137">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="2bc98-138">Turinį analizuojančios prijungtosios funkcijos yra funkcijos, kurios naudodamos „Office“ turinį pateikia dizaino rekomendacijų, redagavimo pasiūlymų, duomenų įžvalgų ir panašių funkcijų.</span><span class="sxs-lookup"><span data-stu-id="2bc98-138">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="2bc98-139">Pvz., „PowerPoint“ dizaino idėjos.</span><span class="sxs-lookup"><span data-stu-id="2bc98-139">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="2bc98-140">Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos „Office“](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="2bc98-140">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="2bc98-141">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="2bc98-141">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="2bc98-142">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="2bc98-142">**Data Type**</span></span>  | <span data-ttu-id="2bc98-143">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="2bc98-143">Boolean</span></span> |
|<span data-ttu-id="2bc98-144">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="2bc98-144">**Possible values**</span></span>  | <span data-ttu-id="2bc98-145">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="2bc98-145">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="2bc98-146">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="2bc98-146">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="2bc98-147">Jei nenustatysite šios nuostatos, vartotojams bus pasiekiamos turinį analizuojančios prijungtosios funkcijos.</span><span class="sxs-lookup"><span data-stu-id="2bc98-147">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="2bc98-148">Jei vartotojas turi „Office 365“ (arba „Microsoft 365“) prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą, jis negali išjungti prijungtųjų funkcijų, kurios analizuoja turinį.</span><span class="sxs-lookup"><span data-stu-id="2bc98-148">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="2bc98-149">Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ (arba „Microsoft 365“) prenumeratą, gali pasirinkti išjungti prijungtąsias funkcijas, kurios analizuoja turinį, nuėję į sritį **Nustatymai** > **Privatumo nustatymai** .</span><span class="sxs-lookup"><span data-stu-id="2bc98-149">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that analyze content by going to **Settings** > **Privacy Settings** .</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="2bc98-150">Prijungtųjų funkcijų, kurios atsisiunčia internetinį turinį, nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="2bc98-150">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="2bc98-151">Prisijungus naudojamos funkcijos, kurios atsisiunčia internetinį turinį, yra funkcijos, kurias naudodami galite ieškoti internetinio turinio ir jį atsisiųsti, įskaitant šablonus, vaizdus, vaizdo įrašus ir pagalbinę medžiagą, kad patobulintumėte dokumentus.</span><span class="sxs-lookup"><span data-stu-id="2bc98-151">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="2bc98-152">Pvz., „Office“ šablonai ar internetinės piktogramos įterpimas.</span><span class="sxs-lookup"><span data-stu-id="2bc98-152">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="2bc98-153">Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos „Office“](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="2bc98-153">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="2bc98-154">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="2bc98-154">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="2bc98-155">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="2bc98-155">**Data Type**</span></span>  | <span data-ttu-id="2bc98-156">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="2bc98-156">Boolean</span></span> |
|<span data-ttu-id="2bc98-157">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="2bc98-157">**Possible values**</span></span>  | <span data-ttu-id="2bc98-158">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="2bc98-158">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="2bc98-159">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="2bc98-159">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="2bc98-160">Jei nenustatysite šios nuostatos, vartotojams bus pasiekiamos internetinį turinį atsisiunčiančios prijungtosios funkcijos.</span><span class="sxs-lookup"><span data-stu-id="2bc98-160">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="2bc98-161">Jei vartotojas turi „Office 365“ (arba „Microsoft 365“) prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą, jis negali išjungti prijungtųjų funkcijų, kurios atsisiunčia interneto turinį.</span><span class="sxs-lookup"><span data-stu-id="2bc98-161">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="2bc98-162">Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ (arba „Microsoft 365“) prenumeratą, gali pasirinkti išjungti prijungtas funkcijas, kurios atsisiunčia interneto turinį, nuėję į sritį **Nustatymai** > **Privatumo nustatymai** .</span><span class="sxs-lookup"><span data-stu-id="2bc98-162">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that download online content by going to **Settings** > **Privacy Settings** .</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="2bc98-163">Pasirinktinių prijungtųjų funkcijų nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="2bc98-163">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="2bc98-164">Be anksčiau minėtų prijungtųjų funkcijų, yra tam tikrų pasirinktinių prijungtųjų funkcijų, kurias galite leisti pasiekti vartotojams, prisijungusiems su organizacijos paskyra, kuri kartais vadinama darbo arba mokymo įstaigos paskyra.</span><span class="sxs-lookup"><span data-stu-id="2bc98-164">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="2bc98-165">Pvz., „Office“ papildiniai, atsisiunčiami iš „Office“ parduotuvės į jūsų įrenginį.</span><span class="sxs-lookup"><span data-stu-id="2bc98-165">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="2bc98-166">Daugiau pavyzdžių rasite [Pasirinktinių „Office“ prisijungus naudojamų funkcijų apžvalga](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="2bc98-166">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="2bc98-167">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="2bc98-167">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="2bc98-168">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="2bc98-168">**Data Type**</span></span>  | <span data-ttu-id="2bc98-169">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="2bc98-169">Boolean</span></span> |
|<span data-ttu-id="2bc98-170">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="2bc98-170">**Possible values**</span></span>  | <span data-ttu-id="2bc98-171">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="2bc98-171">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="2bc98-172">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="2bc98-172">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="2bc98-173">Jei nenustatysite šios nuostatos, pasirinktinės prijungtosios funkcijos bus pasiekiamos vartotojams, turintiems „Office 365“ (arba „Microsoft 365“) prenumeratą, kurie yra prisijungę naudodami darbo ar mokymo įstaigos paskyrą.</span><span class="sxs-lookup"><span data-stu-id="2bc98-173">If you don't set this preference, optional connected experiences are available to users with an Office 365 (or Microsoft 365) subscription that are signed in with a work or school account.</span></span> <span data-ttu-id="2bc98-174">Jei nenustatėte šios nuostatos į FALSE (klaidinga), šie vartotojai gali pasirinkti išjungti pasirinktines prijungtąsias funkcijas nuėję į **Parametrai**  >  **Privatumo parametrai** .</span><span class="sxs-lookup"><span data-stu-id="2bc98-174">Unless you have set this preference to FALSE, these users can choose to turn off optional connected experiences by going to **Settings** > **Privacy Settings** .</span></span>

<span data-ttu-id="2bc98-175">Kitiems vartotojams, pvz., namų vartotojams, turintiems „Office 365“ (arba „Microsoft 365“) prenumeratą, neteikiama galimybė išjungti pasirinktines prijungtąsias funkcijas.</span><span class="sxs-lookup"><span data-stu-id="2bc98-175">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, there isn't an option to turn off optional connected experiences.</span></span>