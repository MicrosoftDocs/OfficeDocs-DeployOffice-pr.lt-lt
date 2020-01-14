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
ms.openlocfilehash: d1a14d2e1bfe45710255467fcbce9ac4af2c9cb7
ms.sourcegitcommit: 903d6bac7d8b7d8003863ac778c0b5bbdfa7a62a
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 10/21/2019
ms.locfileid: "37604291"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="94853-103">„Office“ privatumo valdiklių valdymas „iOS“ įrenginiuose naudojant nuostatas</span><span class="sxs-lookup"><span data-stu-id="94853-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

<span data-ttu-id="94853-104">Yra naujų nuostatų parametrų, skirtų „Office“ „iOS“ įrenginiuose, leidžiančių valdyti parametrus, susijusius su:</span><span class="sxs-lookup"><span data-stu-id="94853-104">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="94853-105">***Diagnostikos duomenimis*** apie „Office“ kliento naudojamą programinę įrangą, kurie renkami ir siunčiami „Microsoft“.</span><span class="sxs-lookup"><span data-stu-id="94853-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="94853-106">***Prisijungus naudojamų funkcijų***, kurios veikia debesų technologijos pagrindu ir pagerina jūsų ir jūsų vartotojų naudojamas „Office“ funkcijas.</span><span class="sxs-lookup"><span data-stu-id="94853-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="94853-107">Daugiau informacijos apie diagnostikos duomenis ir prijungtąsias funkcijas žr. [Privatumo valdiklių apžvalga](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="94853-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="94853-108">Šie nuostatų parametrai taikomi šioms programoms:</span><span class="sxs-lookup"><span data-stu-id="94853-108">These preference settings apply to the following applications:</span></span>
- <span data-ttu-id="94853-109">2.30 ir naujesnės versijos „Word“, skirtai „iOS“, „Excel“, skirtai „iOS“, ir „PowerPoint“, skirtai „iOS“.</span><span class="sxs-lookup"><span data-stu-id="94853-109">Version 2.30 and later of Word for iOS, Excel for iOS, and PowerPoint for iOS.</span></span>
- <span data-ttu-id="94853-110">16.30 ir naujesnės versijos „OneNote“, skirtai „iOS“.</span><span class="sxs-lookup"><span data-stu-id="94853-110">Version 16.30 and later of OneNote for iOS.</span></span>
- <span data-ttu-id="94853-111">1.17 ir naujesnės versijos „Visio“ peržiūros programai, skirtai „iOS“.</span><span class="sxs-lookup"><span data-stu-id="94853-111">Version 1.17 and later of Visio Viewer for iOS.</span></span>

> [!NOTE]
> <span data-ttu-id="94853-112">Informaciją apie panašius „Office“ parametrus „macOS“ kompiuteriuose žr. [„Office“ privatumo valdiklių valdymas „macOS“ įrenginiuose naudojant nuostatas](mac-privacy-preferences.md).</span><span class="sxs-lookup"><span data-stu-id="94853-112">For information about similar settings for Office on computers running Windows, see [Use policy settings to manage privacy controls for Office 365 ProPlus](mac-privacy-preferences.md).</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="94853-113">Įrenginio nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="94853-113">Setting device preferences</span></span>
<span data-ttu-id="94853-114">Šiuos naujus nuostatų parametrus taip pat galima nustatyti mobiliojo įrenginio valdymo (MDM) serveryje įrenginio lygiu, kai įdiegta „Office“ taikomoji programa.</span><span class="sxs-lookup"><span data-stu-id="94853-114">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="94853-115">Daug MDM serverių leidžia IT administratoriams įtraukti pasirinktinį konfigūravimo žodyną, kai serveris siunčia `InstallApplication` MDM komandą į „iOS“ įrenginį.</span><span class="sxs-lookup"><span data-stu-id="94853-115">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="94853-116">Jei reikia daugiau informacijos, žr. MDM serverio dokumentaciją.</span><span class="sxs-lookup"><span data-stu-id="94853-116">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="94853-117">Žodynas vaizduojamas kaip raktų/reikšmių porų rinkinys XML formatu.</span><span class="sxs-lookup"><span data-stu-id="94853-117">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="94853-118">Pavyzdžiui:</span><span class="sxs-lookup"><span data-stu-id="94853-118">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="94853-119">Kai nusiųsite į įrenginį, konfigūravimo žodynas bus rodomas po `com.apple.managed.configuration` klavišu, kur jis bus perskaitytas, kai bus paleista „Office“ taikomoji programa.</span><span class="sxs-lookup"><span data-stu-id="94853-119">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="94853-120">Diagnostikos duomenų nuostatos nustatymas</span><span class="sxs-lookup"><span data-stu-id="94853-120">Preference setting for diagnostic data</span></span>

<span data-ttu-id="94853-121">Diagnostikos duomenys naudojami siekiant apsaugoti ir atnaujinti „Office“, aptikti, diagnozuoti ir spręsti problemas, taip pat tobulinti produktus.</span><span class="sxs-lookup"><span data-stu-id="94853-121">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="94853-122">Daugiau informacijos žr. [Diagnostikos duomenys, siunčiami „Microsoft“ iš „Office 365 ProPlus“](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="94853-122">For more information, see [Diagnostic data sent from Office 365 ProPlus to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="94853-123">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="94853-123">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="94853-124">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="94853-124">**Data Type**</span></span>  | <span data-ttu-id="94853-125">Eilutė</span><span class="sxs-lookup"><span data-stu-id="94853-125">String</span></span> |
|<span data-ttu-id="94853-126">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="94853-126">**Possible values**</span></span>  | <span data-ttu-id="94853-127">`BasicDiagnosticData` *(nustatomas lygis Privalomieji)*</span><span class="sxs-lookup"><span data-stu-id="94853-127">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="94853-128">`FullDiagnosticData` *(nustatomas lygis Pasirinktiniai)*</span><span class="sxs-lookup"><span data-stu-id="94853-128">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="94853-129">`ZeroDiagnosticData` *(nustatomas lygis Nė vienas)*</span><span class="sxs-lookup"><span data-stu-id="94853-129">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="94853-130">Jei nenustatysite šios nuostatos, „Microsoft“ bus siunčiami tik privalomieji diagnostikos duomenys, jei vartotojai, turintys „Office 365“ prenumeratą, bus prisijungę naudodami darbo arba mokymo įstaigos paskyrą.</span><span class="sxs-lookup"><span data-stu-id="94853-130">Starting with new installations of Version 16.30, if you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 subscription are signed in with a work or school account or if users have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="94853-131">Be to, šie vartotojai negali pakeisti diagnostikos duomenų lygio, neatsižvelgiant į tai, kaip nustatėte šią nuostatą.</span><span class="sxs-lookup"><span data-stu-id="94853-131">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="94853-132">Kitų vartotojų, pvz., namų vartotojų, turinčių „Office 365“ prenumeratą, siunčiami tik privalomieji diagnostikos duomenys, nebent vartotojas pasirenka taip pat siųsti pasirinktinius diagnostikos duomenis eidamas į sritį **Parametrai** > **Privatumo parametrai**.</span><span class="sxs-lookup"><span data-stu-id="94853-132">For other users, such as home users with an Office 365 subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Preferences** > **Privacy**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="94853-133">Turinį analizuojančių prisijungus naudojamų funkcijų nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="94853-133">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="94853-134">Turinį analizuojančios prijungtosios funkcijos yra funkcijos, kurios naudodamos „Office“ turinį pateikia dizaino rekomendacijų, redagavimo pasiūlymų, duomenų įžvalgų ir panašių funkcijų.</span><span class="sxs-lookup"><span data-stu-id="94853-134">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="94853-135">Pvz., „PowerPoint“ dizaino idėjos.</span><span class="sxs-lookup"><span data-stu-id="94853-135">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="94853-136">Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos „Office“](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="94853-136">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="94853-137">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="94853-137">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="94853-138">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="94853-138">**Data Type**</span></span>  | <span data-ttu-id="94853-139">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="94853-139">Boolean</span></span> |
|<span data-ttu-id="94853-140">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="94853-140">**Possible values**</span></span>  | <span data-ttu-id="94853-141">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="94853-141">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="94853-142">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="94853-142">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="94853-143">Jei nenustatysite šios nuostatos, vartotojams bus pasiekiamos turinį analizuojančios prijungtosios funkcijos.</span><span class="sxs-lookup"><span data-stu-id="94853-143">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="94853-144">Jei vartotojas turi „Office 365“ prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą, jis negali išjungti prijungtųjų funkcijų, kurios analizuoja turinį.</span><span class="sxs-lookup"><span data-stu-id="94853-144">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="94853-145">Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ prenumeratą, gali pasirinkti išjungti prijungtąsias funkcijas, kurios analizuoja turinį, nuėję į sritį **Nustatymai** > **Privatumo nustatymai**.</span><span class="sxs-lookup"><span data-stu-id="94853-145">For other users, such as home users with an Office 365 subscription, the user can choose to turn off connected experiences that analyze content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="94853-146">Prijungtųjų funkcijų, kurios atsisiunčia internetinį turinį, nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="94853-146">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="94853-147">Prisijungus naudojamos funkcijos, kurios atsisiunčia internetinį turinį, yra funkcijos, kurias naudodami galite ieškoti internetinio turinio ir jį atsisiųsti, įskaitant šablonus, vaizdus, vaizdo įrašus ir pagalbinę medžiagą, kad patobulintumėte dokumentus.</span><span class="sxs-lookup"><span data-stu-id="94853-147">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, 3D models, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="94853-148">Pvz., „Office“ šablonai ar internetinės piktogramos įterpimas.</span><span class="sxs-lookup"><span data-stu-id="94853-148">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="94853-149">Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos „Office“](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="94853-149">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="94853-150">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="94853-150">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="94853-151">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="94853-151">**Data Type**</span></span>  | <span data-ttu-id="94853-152">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="94853-152">Boolean</span></span> |
|<span data-ttu-id="94853-153">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="94853-153">**Possible values**</span></span>  | <span data-ttu-id="94853-154">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="94853-154">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="94853-155">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="94853-155">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="94853-156">Jei nenustatysite šios nuostatos, vartotojams bus pasiekiamos internetinį turinį atsisiunčiančios prijungtosios funkcijos.</span><span class="sxs-lookup"><span data-stu-id="94853-156">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="94853-157">Jei vartotojas turi „Office 365“ prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą, jis negali išjungti prijungtųjų funkcijų, kurios atsisiunčia internetinį turinį.</span><span class="sxs-lookup"><span data-stu-id="94853-157">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="94853-158">Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ prenumeratą, gali pasirinkti išjungti prijungtas funkcijas, kurios atsisiunčia internetinį turinį, nuėję į sritį **Nustatymai** > **Privatumo nustatymai**.</span><span class="sxs-lookup"><span data-stu-id="94853-158">For other users, such as home users with an Office 365 subscription, a user can choose to turn off connected experiences that download online content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="94853-159">Pasirinktinių prijungtųjų funkcijų nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="94853-159">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="94853-160">Be anksčiau minėtų prijungtųjų funkcijų, yra tam tikrų pasirinktinių prijungtųjų funkcijų, kurias galite leisti pasiekti vartotojams, prisijungusiems su organizacijos paskyra, kuri kartais vadinama darbo arba mokymo įstaigos paskyra.</span><span class="sxs-lookup"><span data-stu-id="94853-160">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="94853-161">Pvz., „Office“ papildiniai, atsisiunčiami iš „Office“ parduotuvės į jūsų įrenginį.</span><span class="sxs-lookup"><span data-stu-id="94853-161">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="94853-162">Daugiau pavyzdžių rasite [Pasirinktinių „Office“ prisijungus naudojamų funkcijų apžvalga](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="94853-162">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="94853-163">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="94853-163">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="94853-164">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="94853-164">**Data Type**</span></span>  | <span data-ttu-id="94853-165">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="94853-165">Boolean</span></span> |
|<span data-ttu-id="94853-166">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="94853-166">**Possible values**</span></span>  | <span data-ttu-id="94853-167">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="94853-167">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="94853-168">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="94853-168">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="94853-169">Jei nenustatysite šios nuostatos, pasirinktinės prijungtosios funkcijos bus pasiekiamos vartotojams, turintiems „Office 365“ prenumeratą, kurie yra prisijungę naudodami darbo ar mokymo įstaigos paskyrą.</span><span class="sxs-lookup"><span data-stu-id="94853-169">If you don't set this preference, optional connected experiences are available to users with an Office 365 subscription that are signed in with a work or school account or users who have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="94853-170">Jei nenustatėte šios nuostatos į FALSE (klaidinga), šie vartotojai gali pasirinkti išjungti pasirinktines prijungtąsias funkcijas nuėję į **Parametrai**  >  \*\*Privatumo parametrai \*\*.</span><span class="sxs-lookup"><span data-stu-id="94853-170">Unless you have set this preference to , these users can choose to turn off optional connected experiences by going to Preferences  Privacy.</span></span>

<span data-ttu-id="94853-171">Kitiems vartotojams, pvz., namų vartotojams, turintiems „Office 365“ prenumeratą, neteikiama galimybė išjungti pasirinktines prijungtąsias funkcijas.</span><span class="sxs-lookup"><span data-stu-id="94853-171">For other users, such as home users with an Office 365 subscription, there isn't an option to turn off optional connected experiences.</span></span>