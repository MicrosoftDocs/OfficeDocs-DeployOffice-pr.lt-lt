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
ms.openlocfilehash: 000fd2c5e13ed51abf3afba6e7a1433c9d4b912f
ms.sourcegitcommit: 9b5f18c543c286c95e546e22fc8edb60ef541030
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 05/20/2021
ms.locfileid: "52578344"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="d9b57-103">„Office“ privatumo valdiklių valdymas „iOS“ įrenginiuose naudojant nuostatas</span><span class="sxs-lookup"><span data-stu-id="d9b57-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

> [!NOTE]
> <span data-ttu-id="d9b57-104">„Office“ produktų, kuriems taikoma ši privatumo informacija, sąrašą žr. [Galimi „Office“ produktų privatumo valdikliai](products-versions-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="d9b57-104">For a list of Office products covered by this privacy information, see [Privacy controls available for Office products](products-versions-privacy-controls.md).</span></span>

<span data-ttu-id="d9b57-105">Yra naujų nuostatų parametrų, skirtų „Office“ „iOS“ įrenginiuose, leidžiančių valdyti parametrus, susijusius su:</span><span class="sxs-lookup"><span data-stu-id="d9b57-105">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="d9b57-106">***Diagnostikos duomenimis*** apie „Office“ kliento naudojamą programinę įrangą, kurie renkami ir siunčiami „Microsoft“.</span><span class="sxs-lookup"><span data-stu-id="d9b57-106">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="d9b57-107">***Prisijungus naudojamų funkcijų***, kurios veikia debesų technologijos pagrindu ir pagerina jūsų ir jūsų vartotojų naudojamas „Office“ funkcijas.</span><span class="sxs-lookup"><span data-stu-id="d9b57-107">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="d9b57-108">Daugiau informacijos apie diagnostikos duomenis ir prijungtąsias funkcijas žr. [Privatumo valdiklių apžvalga](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="d9b57-108">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

> [!NOTE]
> <span data-ttu-id="d9b57-109">Informaciją apie panašius „Office“ parametrus „macOS“ kompiuteriuose žr. [„Office“ privatumo valdiklių valdymas „macOS“ įrenginiuose naudojant nuostatas](mac-privacy-preferences.md).</span><span class="sxs-lookup"><span data-stu-id="d9b57-109">For information about similar settings for Office on computers running macOS, see [Use preferences to manage privacy controls for Office for Mac](mac-privacy-preferences.md)</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="d9b57-110">Įrenginio nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="d9b57-110">Setting device preferences</span></span>
<span data-ttu-id="d9b57-111">Šiuos naujus nuostatų parametrus taip pat galima nustatyti mobiliojo įrenginio valdymo (MDM) serveryje įrenginio lygiu, kai įdiegta „Office“ taikomoji programa.</span><span class="sxs-lookup"><span data-stu-id="d9b57-111">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="d9b57-112">Daug MDM serverių leidžia IT administratoriams įtraukti pasirinktinį konfigūravimo žodyną, kai serveris siunčia `InstallApplication` MDM komandą į „iOS“ įrenginį.</span><span class="sxs-lookup"><span data-stu-id="d9b57-112">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="d9b57-113">Jei reikia daugiau informacijos, žr. MDM serverio dokumentaciją.</span><span class="sxs-lookup"><span data-stu-id="d9b57-113">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="d9b57-p102">Žodynas vaizduojamas kaip raktų / reikšmių porų rinkinys XML formatu. Pavyzdžiui:</span><span class="sxs-lookup"><span data-stu-id="d9b57-p102">The dictionary is represented as a set of key/value pairs in XML format. For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="d9b57-116">Kai nusiųsite į įrenginį, konfigūravimo žodynas bus rodomas po `com.apple.managed.configuration` klavišu, kur jis bus perskaitytas, kai bus paleista „Office“ taikomoji programa.</span><span class="sxs-lookup"><span data-stu-id="d9b57-116">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

> [!NOTE]
> <span data-ttu-id="d9b57-117">Taip pat galite naudoti „Office“ debesies strategijos tarnybą ir šiuos 4 strategijos parametrus:</span><span class="sxs-lookup"><span data-stu-id="d9b57-117">You can also use the Office cloud policy service and these 4 policy settings:</span></span>
> - <span data-ttu-id="d9b57-118">Konfigūruoti kliento programinės įrangos diagnostikos duomenų lygį, kuriuos „Office“ siunčia „Microsoft“ tarnybai</span><span class="sxs-lookup"><span data-stu-id="d9b57-118">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>
> - <span data-ttu-id="d9b57-119">Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios analizuoja turinį</span><span class="sxs-lookup"><span data-stu-id="d9b57-119">Allow the use of connected experiences in Office that analyze content</span></span>
> - <span data-ttu-id="d9b57-120">Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios parsiunčia internetinį turinį</span><span class="sxs-lookup"><span data-stu-id="d9b57-120">Allow the use of connected experiences in Office that download online content</span></span>
> - <span data-ttu-id="d9b57-121">Leisti „Office“ naudoti pasirinktines, papildomas prisijungus naudojamas funkcijas </span><span class="sxs-lookup"><span data-stu-id="d9b57-121">Allow the use of additional optional connected experiences in Office</span></span>
>
> <span data-ttu-id="d9b57-122">„Outlook“ skirtos „iOS“ ir „OneDrive“ skirtos „iOS: privatumo parametrai gali būti konfigūruojami tik naudojant „Office“ debesies strategijos tarnybą.</span><span class="sxs-lookup"><span data-stu-id="d9b57-122">Privacy settings for Outlook for iOS and OneDrive for iOS can only be configured by using the Office cloud policy service.</span></span>
>
> <span data-ttu-id="d9b57-123">Daugiau informacijos apie „Office“ debesies strategijų tarnybos naudojimą rasite straipsnyje [„Office“ debesies strategijų tarnybos apžvalga](../overview-office-cloud-policy-service.md).</span><span class="sxs-lookup"><span data-stu-id="d9b57-123">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="d9b57-124">Diagnostikos duomenų nuostatos nustatymas</span><span class="sxs-lookup"><span data-stu-id="d9b57-124">Preference setting for diagnostic data</span></span>

<span data-ttu-id="d9b57-125">Diagnostikos duomenys naudojami siekiant apsaugoti ir naujinti „Office“, aptikti, diagnozuoti ir spręsti problemas, taip pat tobulinti produktus.</span><span class="sxs-lookup"><span data-stu-id="d9b57-125">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="d9b57-126">Daugiau informacijos žr. [Diagnostikos duomenys, siunčiami „Microsoft“ iš „Microsoft 365“ programų įmonėms](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="d9b57-126">For more information, see [Diagnostic data sent from Microsoft 365 Apps for enterprise to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span></span>

|<span data-ttu-id="d9b57-127">Kategorija</span><span class="sxs-lookup"><span data-stu-id="d9b57-127">Category</span></span>|<span data-ttu-id="d9b57-128">Išsami informacija</span><span class="sxs-lookup"><span data-stu-id="d9b57-128">Details</span></span>|
|:-----|:-----|
|<span data-ttu-id="d9b57-129">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="d9b57-129">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="d9b57-130">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="d9b57-130">**Data Type**</span></span>  | <span data-ttu-id="d9b57-131">Eilutė</span><span class="sxs-lookup"><span data-stu-id="d9b57-131">String</span></span> |
|<span data-ttu-id="d9b57-132">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="d9b57-132">**Possible values**</span></span>  | <span data-ttu-id="d9b57-133">`BasicDiagnosticData` *(ši reikšmė nustato lygį į Būtina)*</span><span class="sxs-lookup"><span data-stu-id="d9b57-133">`BasicDiagnosticData` *(this value sets the level to Required)*</span></span> <br/> <span data-ttu-id="d9b57-134">`FullDiagnosticData` *(ši reikšmė nustato lygį į Pasirinktinai)*</span><span class="sxs-lookup"><span data-stu-id="d9b57-134">`FullDiagnosticData` *(this value sets the level to Optional)*</span></span> <br/> <span data-ttu-id="d9b57-135">`ZeroDiagnosticData` *(ši reikšmė nustato lygį į Nė vienas)*</span><span class="sxs-lookup"><span data-stu-id="d9b57-135">`ZeroDiagnosticData` *(this value sets the level to Neither)*</span></span> |

<span data-ttu-id="d9b57-136">Jei nenustatysite šios nuostatos, „Microsoft“ bus siunčiami tik pasirinktiniai diagnostikos duomenys, jei vartotojai, turintys „Office 365“ (arba „Microsoft 365“) prenumeratą, bus prisijungę naudodami darbo arba mokymo įstaigos paskyrą.</span><span class="sxs-lookup"><span data-stu-id="d9b57-136">If you don't set this preference, both required and optional diagnostic data are sent to Microsoft if users with an Office 365 (or Microsoft 365) subscription are signed in with a work or school account.</span></span> <span data-ttu-id="d9b57-137">Be to, šie vartotojai negali pakeisti diagnostikos duomenų lygio, neatsižvelgiant į tai, kaip nustatėte šią nuostatą.</span><span class="sxs-lookup"><span data-stu-id="d9b57-137">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

> [!NOTE]
> <span data-ttu-id="d9b57-138">Atnaujinome ankstesnę pastraipą, kad paaiškintume, jog pasirinktiniai diagnostikos duomenys taip pat siunčiami „Microsoft“, jei nenustatėte šios nuostatos.</span><span class="sxs-lookup"><span data-stu-id="d9b57-138">We've updated the previous paragraph to clarify that optional diagnostic data is also sent to Microsoft if you don't set this preference.</span></span>

<span data-ttu-id="d9b57-139">Kitų vartotojų, pvz., namų vartotojų, turinčių „Office 365“ (arba „Microsoft 365“) prenumeratą, siunčiami tik privalomieji diagnostikos duomenys, nebent vartotojas pasirenka taip pat siųsti pasirinktinius diagnostikos duomenis eidamas į sritį **Parametrai** > **Privatumo parametrai**.</span><span class="sxs-lookup"><span data-stu-id="d9b57-139">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Settings** > **Privacy Settings**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="d9b57-140">Turinį analizuojančių prisijungus naudojamų funkcijų nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="d9b57-140">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="d9b57-141">Turinį analizuojančios prijungtosios funkcijos yra funkcijos, kurios naudodamos „Office“ turinį pateikia dizaino rekomendacijų, redagavimo pasiūlymų, duomenų įžvalgų ir panašių funkcijų.</span><span class="sxs-lookup"><span data-stu-id="d9b57-141">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="d9b57-142">Pvz., „PowerPoint“ dizaino idėjos.</span><span class="sxs-lookup"><span data-stu-id="d9b57-142">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="d9b57-143">Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos „Office“](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="d9b57-143">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|<span data-ttu-id="d9b57-144">Kategorija</span><span class="sxs-lookup"><span data-stu-id="d9b57-144">Category</span></span>|<span data-ttu-id="d9b57-145">Išsami informacija</span><span class="sxs-lookup"><span data-stu-id="d9b57-145">Details</span></span>|
|:-----|:-----|
|<span data-ttu-id="d9b57-146">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="d9b57-146">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="d9b57-147">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="d9b57-147">**Data Type**</span></span>  | <span data-ttu-id="d9b57-148">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="d9b57-148">Boolean</span></span> |
|<span data-ttu-id="d9b57-149">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="d9b57-149">**Possible values**</span></span>  | <span data-ttu-id="d9b57-150">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="d9b57-150">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="d9b57-151">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="d9b57-151">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="d9b57-152">Jei nenustatysite šios nuostatos, vartotojams bus pasiekiamos turinį analizuojančios prijungtosios funkcijos.</span><span class="sxs-lookup"><span data-stu-id="d9b57-152">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="d9b57-153">Jei vartotojas turi „Office 365“ (arba „Microsoft 365“) prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą, jis negali išjungti prijungtųjų funkcijų, kurios analizuoja turinį.</span><span class="sxs-lookup"><span data-stu-id="d9b57-153">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="d9b57-154">Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ (arba „Microsoft 365“) prenumeratą, gali pasirinkti išjungti prijungtąsias funkcijas, kurios analizuoja turinį, nuėję į sritį **Nustatymai** > **Privatumo nustatymai**.</span><span class="sxs-lookup"><span data-stu-id="d9b57-154">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that analyze content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="d9b57-155">Prijungtųjų funkcijų, kurios atsisiunčia internetinį turinį, nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="d9b57-155">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="d9b57-156">Prisijungus naudojamos funkcijos, kurios atsisiunčia internetinį turinį, yra funkcijos, kurias naudodami galite ieškoti internetinio turinio ir jį atsisiųsti, įskaitant šablonus, vaizdus, vaizdo įrašus ir pagalbinę medžiagą, kad patobulintumėte dokumentus.</span><span class="sxs-lookup"><span data-stu-id="d9b57-156">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="d9b57-157">Pvz., „Office“ šablonai ar internetinės piktogramos įterpimas.</span><span class="sxs-lookup"><span data-stu-id="d9b57-157">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="d9b57-158">Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos „Office“](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="d9b57-158">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|<span data-ttu-id="d9b57-159">Kategorija</span><span class="sxs-lookup"><span data-stu-id="d9b57-159">Category</span></span>|<span data-ttu-id="d9b57-160">Išsami informacija</span><span class="sxs-lookup"><span data-stu-id="d9b57-160">Details</span></span>|
|:-----|:-----|
|<span data-ttu-id="d9b57-161">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="d9b57-161">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="d9b57-162">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="d9b57-162">**Data Type**</span></span>  | <span data-ttu-id="d9b57-163">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="d9b57-163">Boolean</span></span> |
|<span data-ttu-id="d9b57-164">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="d9b57-164">**Possible values**</span></span>  | <span data-ttu-id="d9b57-165">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="d9b57-165">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="d9b57-166">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="d9b57-166">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="d9b57-167">Jei nenustatysite šios nuostatos, vartotojams bus pasiekiamos internetinį turinį atsisiunčiančios prijungtosios funkcijos.</span><span class="sxs-lookup"><span data-stu-id="d9b57-167">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="d9b57-168">Jei vartotojas turi „Office 365“ (arba „Microsoft 365“) prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą, jis negali išjungti prijungtųjų funkcijų, kurios atsisiunčia interneto turinį.</span><span class="sxs-lookup"><span data-stu-id="d9b57-168">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="d9b57-169">Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ (arba „Microsoft 365“) prenumeratą, gali pasirinkti išjungti prijungtas funkcijas, kurios atsisiunčia interneto turinį, nuėję į sritį **Nustatymai** > **Privatumo nustatymai**.</span><span class="sxs-lookup"><span data-stu-id="d9b57-169">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that download online content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="d9b57-170">Pasirinktinių prijungtųjų funkcijų nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="d9b57-170">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="d9b57-171">Be anksčiau minėtų prijungtųjų funkcijų, yra tam tikrų pasirinktinių prijungtųjų funkcijų, kurias galite leisti pasiekti vartotojams, prisijungusiems su organizacijos paskyra, kuri kartais vadinama darbo arba mokymo įstaigos paskyra.</span><span class="sxs-lookup"><span data-stu-id="d9b57-171">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="d9b57-172">Pvz., „Office“ papildiniai, atsisiunčiami iš „Office“ parduotuvės į jūsų įrenginį.</span><span class="sxs-lookup"><span data-stu-id="d9b57-172">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="d9b57-173">Daugiau pavyzdžių rasite [Pasirinktinių „Office“ prisijungus naudojamų funkcijų apžvalga](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="d9b57-173">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|<span data-ttu-id="d9b57-174">Kategorija</span><span class="sxs-lookup"><span data-stu-id="d9b57-174">Category</span></span>|<span data-ttu-id="d9b57-175">Išsami informacija</span><span class="sxs-lookup"><span data-stu-id="d9b57-175">Details</span></span>|
|:-----|:-----|
|<span data-ttu-id="d9b57-176">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="d9b57-176">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="d9b57-177">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="d9b57-177">**Data Type**</span></span>  | <span data-ttu-id="d9b57-178">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="d9b57-178">Boolean</span></span> |
|<span data-ttu-id="d9b57-179">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="d9b57-179">**Possible values**</span></span>  | <span data-ttu-id="d9b57-180">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="d9b57-180">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="d9b57-181">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="d9b57-181">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="d9b57-182">Jei nenustatysite šios nuostatos, pasirinktinės prijungtosios funkcijos bus pasiekiamos vartotojams, turintiems „Office 365“ (arba „Microsoft 365“) prenumeratą, kurie yra prisijungę naudodami darbo ar mokymo įstaigos paskyrą.</span><span class="sxs-lookup"><span data-stu-id="d9b57-182">If you don't set this preference, optional connected experiences are available to users with an Office 365 (or Microsoft 365) subscription that are signed in with a work or school account.</span></span> <span data-ttu-id="d9b57-183">Jei nenustatėte šios nuostatos į FALSE (klaidinga), šie vartotojai gali pasirinkti išjungti pasirinktines prijungtąsias funkcijas nuėję į **Parametrai**  >  **Privatumo parametrai**.</span><span class="sxs-lookup"><span data-stu-id="d9b57-183">Unless you have set this preference to FALSE, these users can choose to turn off optional connected experiences by going to **Settings** > **Privacy Settings**.</span></span>

<span data-ttu-id="d9b57-184">Kitiems vartotojams, pvz., namų vartotojams, turintiems „Office 365“ (arba „Microsoft 365“) prenumeratą, neteikiama galimybė išjungti pasirinktines prijungtąsias funkcijas.</span><span class="sxs-lookup"><span data-stu-id="d9b57-184">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, there isn't an option to turn off optional connected experiences.</span></span>