---
title: „Office for Mac“ privatumo valdiklių valdymas naudojant nuostatas
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
description: Suteikia informacijos „Office“ administratoriams, kaip valdyti „Office for Mac“ privatumo kontrolės valdiklius naudojant nuostatas.
hideEdit: true
ms.openlocfilehash: 01bb31f3b6c307ec1dc4762b54fea17185dcf27d
ms.sourcegitcommit: 0fd23324ba1364fa1f8dd1578adf25946adde90f
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 08/07/2019
ms.locfileid: "36246300"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-for-mac"></a><span data-ttu-id="41b93-103">„Office for Mac“ privatumo valdiklių valdymas naudojant nuostatas</span><span class="sxs-lookup"><span data-stu-id="41b93-103">Use preferences to manage privacy controls for Office for Mac</span></span>

<span data-ttu-id="41b93-104">Nauji nuostatų parametrai, pradedant nuo „Office for Mac“ 16.28 versijos, leis valdyti parametrus, susijusius su:</span><span class="sxs-lookup"><span data-stu-id="41b93-104">Starting with Version 1904 of Office 365 ProPlus, there are new policy settings that will allow you to control settings related to the following:</span></span>

- <span data-ttu-id="41b93-105">***Diagnostikos duomenimis*** apie „Office“ kliento naudojamą programinę įrangą, kurie renkami ir siunčiami „Microsoft“.</span><span class="sxs-lookup"><span data-stu-id="41b93-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used</span></span>

- <span data-ttu-id="41b93-106">***Prijungtosios funkcijos***, kurios veikia debesų technologijos pagrindu ir pagerina jūsų ir jūsų vartotojų naudojamas „Office“ funkcijas.</span><span class="sxs-lookup"><span data-stu-id="41b93-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="41b93-107">Be to, yra naujas nuostatų parametras, susijęs su „Microsoft AutoUpdate“ (MAU) dialogo langu **Būtinas duomenų pranešimas**.</span><span class="sxs-lookup"><span data-stu-id="41b93-107">In addition, there is a new preference setting related to a **Required Data Notice** dialog for Microsoft AutoUpdate (MAU).</span></span>

<span data-ttu-id="41b93-108">Daugiau informacijos apie diagnostikos duomenis ir prijungtąsias funkcijas žr. [Privatumo valdiklių apžvalga](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="41b93-108">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

> [!NOTE]
> <span data-ttu-id="41b93-109">Informacijos apie panašius „Office“ parametrus kompiuteriuose, kuriuose veikia „Windows“, žr. [„Office 365 ProPlus“ privatumo valdiklių valdymas naudojant strategijos parametrus](manage-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="41b93-109">For information about similar settings for Office on computers running Windows, see [Use policy settings to manage privacy controls for Office 365 ProPlus](manage-privacy-controls.md)</span></span>

## <a name="setting-preferences"></a><span data-ttu-id="41b93-110">Nuostatų nustatymas</span><span class="sxs-lookup"><span data-stu-id="41b93-110">Setting preferences</span></span>

<span data-ttu-id="41b93-111">Šie nauji nuostatų parametrai yra suderinami su CFPreferences API ir gali būti nustatomi naudojant `defaults` komandą terminale arba priverstinai naudojami pasitelkus konfigūravimo profilį ar mobiliojo įrenginio valdymo (MDM) serverį.</span><span class="sxs-lookup"><span data-stu-id="41b93-111">These new preference settings are CFPreferences API compatible and can be set using the `defaults` command in Terminal, or enforced through a Configuration Profile or Mobile Device Management (MDM) server.</span></span> <span data-ttu-id="41b93-112">Pritaikius nuostatas vartotojas negali pakeisti reikšmių, o visi programos valdikliai bus rodomi kaip išjungti.</span><span class="sxs-lookup"><span data-stu-id="41b93-112">When the preferences are enforced, the user cannot change the values, and any in-app controls will appear disabled.</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="41b93-113">Diagnostikos duomenų nuostatų parametrai</span><span class="sxs-lookup"><span data-stu-id="41b93-113">Policy setting for diagnostic data</span></span>

<span data-ttu-id="41b93-114">Diagnostikos duomenys naudojami siekiant apsaugoti ir atnaujinti „Office“, aptikti, diagnozuoti ir spręsti problemas, taip pat tobulinti produktus.</span><span class="sxs-lookup"><span data-stu-id="41b93-114">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="41b93-115">Daugiau informacijos žr. [Diagnostikos duomenys, siunčiami „Microsoft“ iš „Office 365 ProPlus“](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="41b93-115">Diagnostic data sent from Office 365 ProPlus to Microsoft</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="41b93-116">**Nuostatų domenas**</span><span class="sxs-lookup"><span data-stu-id="41b93-116">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="41b93-117">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="41b93-117">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="41b93-118">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="41b93-118">**Data Type**</span></span>  | <span data-ttu-id="41b93-119">Eilutė</span><span class="sxs-lookup"><span data-stu-id="41b93-119">String</span></span> |
|<span data-ttu-id="41b93-120">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="41b93-120">**Possible values**</span></span>  | <span data-ttu-id="41b93-121">`BasicDiagnosticData` *(nustatomas lygis Būtina)*</span><span class="sxs-lookup"><span data-stu-id="41b93-121">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="41b93-122">`FullDiagnosticData` *(nustatomas lygis Pasirinktinai)*</span><span class="sxs-lookup"><span data-stu-id="41b93-122">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="41b93-123">`ZeroDiagnosticData` *(nustatomas lygis Nė vienas)*</span><span class="sxs-lookup"><span data-stu-id="41b93-123">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |
|<span data-ttu-id="41b93-124">**Pasiekiamumas**</span><span class="sxs-lookup"><span data-stu-id="41b93-124">**Availability**</span></span> |<span data-ttu-id="41b93-125">16.28 ir vėlesnės</span><span class="sxs-lookup"><span data-stu-id="41b93-125">16.28 and later</span></span> |

> [!NOTE]
> <span data-ttu-id="41b93-126">Jei nustatėte šią nuostatą, ji taip pat bus taikoma šiems produktams:</span><span class="sxs-lookup"><span data-stu-id="41b93-126">If you set this preference, it also will apply to the following products:</span></span>
> - <span data-ttu-id="41b93-127">„Teams for Mac“ 1.00.217856 ir vėlesnėms versijoms</span><span class="sxs-lookup"><span data-stu-id="41b93-127">Version 1.00.217856 and later of Teams for Mac</span></span>
> - <span data-ttu-id="41b93-128">„Skype“ verslui, skirta „Mac“ 16.28 ir vėlesnėms versijoms</span><span class="sxs-lookup"><span data-stu-id="41b93-128">Version 16.28 and later of Skype for Business for Mac</span></span>

<span data-ttu-id="41b93-129">Jei nenustatysite šios nuostatos, „Microsoft“ bus siunčiami pasirinktiniai ir būtini diagnostikos duomenys, jei vartotojai, turintys „Office 365“ prenumeratą, yra prisijungę naudodami darbo arba švietimo įstaigos paskyrą, ar jei vartotojai turi bendrojo licencijavimo „Office 2019 for Mac“ versiją.</span><span class="sxs-lookup"><span data-stu-id="41b93-129">If you don't set this preference, both optional and required diagnostic data is sent to Microsoft if users with an Office 365 subscription are signed in with a work or school account or if users have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="41b93-130">Be to, šie vartotojai negali pakeisti diagnostikos duomenų lygio, neatsižvelgiant į tai, kaip nustatėte šią nuostatą.</span><span class="sxs-lookup"><span data-stu-id="41b93-130">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="41b93-131">Kitų vartotojų, pvz., namų vartotojų, turinčių „Office 365“ prenumeratą, siunčiami tik būtini diagnostikos duomenys, nebent vartotojas pasirenka taip pat siųsti pasirinktinius diagnostikos duomenis eidamas į sritį **Nuostatos** > **Privatumas**.</span><span class="sxs-lookup"><span data-stu-id="41b93-131">For other users, such as home users with an Office 365 subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="41b93-132">Turinį analizuojančių prijungtųjų funkcijų nuostatos parametras</span><span class="sxs-lookup"><span data-stu-id="41b93-132">Policy setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="41b93-133">Turinį analizuojančios prijungtosios funkcijos yra funkcijos, kurios naudodamos „Office“ turinį pateikia dizaino rekomendacijų, redagavimo pasiūlymų, duomenų įžvalgų ir panašių funkcijų.</span><span class="sxs-lookup"><span data-stu-id="41b93-133">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="41b93-134">Pavyzdžiui, „PowerPoint“ dizaino įrankis arba „Word“ Tyrinėtojas.</span><span class="sxs-lookup"><span data-stu-id="41b93-134">For example, PowerPoint Designer or Editor in Word.</span></span> <span data-ttu-id="41b93-135">Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [„Office“ prijungtosios funkcijos](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="41b93-135">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="41b93-136">**Nuostatų domenas**</span><span class="sxs-lookup"><span data-stu-id="41b93-136">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="41b93-137">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="41b93-137">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="41b93-138">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="41b93-138">**Data Type**</span></span>  | <span data-ttu-id="41b93-139">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="41b93-139">Boolean</span></span> |
|<span data-ttu-id="41b93-140">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="41b93-140">**Possible values**</span></span>  | <span data-ttu-id="41b93-141">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="41b93-141">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="41b93-142">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="41b93-142">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="41b93-143">**Pasiekiamumas**</span><span class="sxs-lookup"><span data-stu-id="41b93-143">**Availability**</span></span> |<span data-ttu-id="41b93-144">16.28 ir vėlesnės</span><span class="sxs-lookup"><span data-stu-id="41b93-144">16.28 and later</span></span> |

<span data-ttu-id="41b93-145">Jei nenustatysite šios nuostatos, vartotojams bus teikiamos turinį analizuojančios prijungtosios funkcijos.</span><span class="sxs-lookup"><span data-stu-id="41b93-145">If you don't set this preference, connected experiences that analyze content are available to users.</span></span> 

<span data-ttu-id="41b93-146">Jei vartotojas turi „Office 365“ prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą, arba vartotojas turi Office 2019 for Mac“ bendrojo licencijavimo versiją, vartotojas negali išjungti prijungtųjų funkcijų, kurios analizuoja turinį.</span><span class="sxs-lookup"><span data-stu-id="41b93-146">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="41b93-147">Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ prenumeratą, gali pasirinkti išjungti prijungtąsias funkcijas, kurios analizuoja turinį, nuėję į sritį **Nuostatos** > **Privatumas**.</span><span class="sxs-lookup"><span data-stu-id="41b93-147">For other users, such as home users with an Office 365 subscription, the user can choose to turn off connected experiences that analyze content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="41b93-148">Internetinį turinį atsisiunčiančių prijungtųjų funkcijų nuostatos nustatymas</span><span class="sxs-lookup"><span data-stu-id="41b93-148">Policy setting for connected experiences that download online content</span></span>

<span data-ttu-id="41b93-149">Prijungtosios funkcijos, kurios atsisiunčia turinį, yra funkcijos, kurias naudodami galite ieškoti internetinio turinio ir jį atsisiųsti, įskaitant šablonus, vaizdus, 3D modelius, vaizdo įrašus ir pagalbinę medžiagą, kad patobulintumėte dokumentus.</span><span class="sxs-lookup"><span data-stu-id="41b93-149">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, 3D models, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="41b93-150">Pavyzdžiui, „Office“ šablonai arba „PowerPoint“ funkcija „QuickStarter“.</span><span class="sxs-lookup"><span data-stu-id="41b93-150">For example, Office templates or PowerPoint QuickStarter.</span></span> <span data-ttu-id="41b93-151">Išsamesnį prijungtųjų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos naudojant „Office“](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="41b93-151">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="41b93-152">**Nuostatų domenas**</span><span class="sxs-lookup"><span data-stu-id="41b93-152">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="41b93-153">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="41b93-153">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="41b93-154">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="41b93-154">**Data Type**</span></span>  | <span data-ttu-id="41b93-155">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="41b93-155">Boolean</span></span> |
|<span data-ttu-id="41b93-156">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="41b93-156">**Possible values**</span></span>  | <span data-ttu-id="41b93-157">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="41b93-157">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="41b93-158">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="41b93-158">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="41b93-159">**Pasiekiamumas**</span><span class="sxs-lookup"><span data-stu-id="41b93-159">**Availability**</span></span> |<span data-ttu-id="41b93-160">16.28 ir vėlesnės</span><span class="sxs-lookup"><span data-stu-id="41b93-160">16.28 and later</span></span> |

<span data-ttu-id="41b93-161">Jei nenustatysite šios nuostatos, vartotojams bus teikiamos turinį atsisiunčiančios prijungtosios funkcijos.</span><span class="sxs-lookup"><span data-stu-id="41b93-161">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="41b93-162">Jei vartotojas turi „Office 365“ prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą, arba vartotojas turi Office 2019 for Mac“ bendrojo licencijavimo versiją, vartotojas negali išjungti prijungtųjų funkcijų, kurios atsisiunčia turinį.</span><span class="sxs-lookup"><span data-stu-id="41b93-162">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="41b93-163">Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ prenumeratą, gali pasirinkti išjungti prijungtas funkcijas, kurios atsisiunčia interneto turinį, nuėję į sritį **Nuostatos** > **Privatumas**.</span><span class="sxs-lookup"><span data-stu-id="41b93-163">For other users, such as home users with an Office 365 subscription, a user can choose to turn off connected experiences that download online content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="41b93-164">Pasirinktinių prijungtųjų funkcijų nuostatos parametras</span><span class="sxs-lookup"><span data-stu-id="41b93-164">Policy setting for optional connected experiences</span></span>

<span data-ttu-id="41b93-165">Be anksčiau minėtų prijungtųjų funkcijų, kurios yra tam tikros pasirinktinės prijungtosios funkcijos, kurias galite leisti naudoti savo vartotojams, kad jie galėtų pasiekti savo organizacijos paskyrą, kuri kartais vadinama darbo arba mokymo įstaigos paskyra.</span><span class="sxs-lookup"><span data-stu-id="41b93-165">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="41b93-166">Pavyzdžiui, „LinkedIn“ CV kūrimo pagalbinės priemonės funkcijos programoje „Word“ arba orų prognozės juosta programoje „Outlook“, kurią naudoja MSN orai.</span><span class="sxs-lookup"><span data-stu-id="41b93-166">For example, the LinkedIn features of the Resume Assistant in Word or the 3D Maps feature in Excel, which uses Bing.</span></span> <span data-ttu-id="41b93-167">Daugiau pavyzdžių rasite [Pasirinktinių „Office“ prisijungus naudojamų funkcijų apžvalga](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="41b93-167">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="41b93-168">**Nuostatų domenas**</span><span class="sxs-lookup"><span data-stu-id="41b93-168">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="41b93-169">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="41b93-169">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="41b93-170">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="41b93-170">**Data Type**</span></span>  | <span data-ttu-id="41b93-171">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="41b93-171">Boolean</span></span> |
|<span data-ttu-id="41b93-172">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="41b93-172">**Possible values**</span></span>  | <span data-ttu-id="41b93-173">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="41b93-173">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="41b93-174">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="41b93-174">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="41b93-175">**Pasiekiamumas**</span><span class="sxs-lookup"><span data-stu-id="41b93-175">**Availability**</span></span> |<span data-ttu-id="41b93-176">16.28 ir vėlesnės</span><span class="sxs-lookup"><span data-stu-id="41b93-176">16.28 and later</span></span> |

<span data-ttu-id="41b93-177">Jei nenustatysite šios nuostatos, pasirinktinės prijungtosios funkcijos bus pasiekiamos vartotojams, turintiems „Office 365“ paskyrą, kurie yra prisijungę prie darbo ar mokymo įstaigos paskyros, arba vartotojams, kurie turi bendrojo licencijavimo „Office 2019 for Mac“ versiją.</span><span class="sxs-lookup"><span data-stu-id="41b93-177">If you don't set this preference, optional connected experiences are available to users with an Office 365 subscription that are signed in with a work or school account or users who have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="41b93-178">Jei nenustatėte šios nuostatos į `FALSE`, šie vartotojai galės pasirinkti išjungti pasirinktines prijungtąsias funkcijas eidami į **Nuostatos** > **Privatumas**.</span><span class="sxs-lookup"><span data-stu-id="41b93-178">Unless you have set this preference to `FALSE`, these users can choose to turn off optional connected experiences by going to **Preferences** > **Privacy**.</span></span>

<span data-ttu-id="41b93-179">Kitiems vartotojams, pvz., namų vartotojams, turintiems „Office 365“ prenumeratą, neteikiama galimybė išjungti pasirinktines prijungtąsias funkcijas.</span><span class="sxs-lookup"><span data-stu-id="41b93-179">For other users, such as home users with an Office 365 subscription, there isn't an option to turn off optional connected experiences.</span></span>

## <a name="preference-setting-for-most-connected-experiences"></a><span data-ttu-id="41b93-180">Daugelio prijungtųjų funkcijų nuostatos parametras</span><span class="sxs-lookup"><span data-stu-id="41b93-180">Policy setting for most connected experiences</span></span>

<span data-ttu-id="41b93-181">Šią nuostatą galite naudoti norėdami kontroliuoti, ar prijungtosios funkcijos pasiekiamos jūsų vartotojams.</span><span class="sxs-lookup"><span data-stu-id="41b93-181">You can use this preference to control whether most connected experiences are available to your users.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="41b93-182">**Nuostatų domenas**</span><span class="sxs-lookup"><span data-stu-id="41b93-182">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="41b93-183">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="41b93-183">**Key**</span></span>  | `ConnectedOfficeExperiencesPreference`  |
|<span data-ttu-id="41b93-184">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="41b93-184">**Data Type**</span></span>  | <span data-ttu-id="41b93-185">Bulio logika</span><span class="sxs-lookup"><span data-stu-id="41b93-185">Boolean</span></span> |
|<span data-ttu-id="41b93-186">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="41b93-186">**Possible values**</span></span>  | <span data-ttu-id="41b93-187">`TRUE` *(įgalinta)*</span><span class="sxs-lookup"><span data-stu-id="41b93-187">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="41b93-188">`FALSE` *(išjungta)*</span><span class="sxs-lookup"><span data-stu-id="41b93-188">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="41b93-189">**Pasiekiamumas**</span><span class="sxs-lookup"><span data-stu-id="41b93-189">**Availability**</span></span> |<span data-ttu-id="41b93-190">16.28 ir vėlesnės</span><span class="sxs-lookup"><span data-stu-id="41b93-190">16.28 and later</span></span> |

<span data-ttu-id="41b93-191">Jei ši nuostata nerodoma, vartotojams pasiekiamos visos prijungtosios funkcijos, nebent nustatėte kurią nors kitą anksčiau minėtų prijungtųjų funkcijų nuostatą, pvz., `OfficeExperiencesAnalyzingContentPreference`.</span><span class="sxs-lookup"><span data-stu-id="41b93-191">If you don't set this preference, all connected experiences are available to your users, unless you have set one of the other preferences for connected experiences previously mentioned, such as `OfficeExperiencesAnalyzingContentPreference`.</span></span>

<span data-ttu-id="41b93-192">Jei nustatysite šią nuostatą į `FALSE`, vartotojams nebus pasiekiamos toliau nurodytų tipų prijungtosios funkcijos:</span><span class="sxs-lookup"><span data-stu-id="41b93-192">For example, if you set this preference to `FALSE`, the following types of connected experiences won't be available to your users:</span></span>
- <span data-ttu-id="41b93-193">Funkcijos, kurios analizuoja turinį</span><span class="sxs-lookup"><span data-stu-id="41b93-193">Experiences that analyze your content</span></span>
- <span data-ttu-id="41b93-194">Funkcijos, kurios atsisiunčia internetinį turinį</span><span class="sxs-lookup"><span data-stu-id="41b93-194">Experiences that download online content</span></span>
- <span data-ttu-id="41b93-195">Pasirinktinės prisijungus naudojamos funkcijos</span><span class="sxs-lookup"><span data-stu-id="41b93-195">Optional connected experiences</span></span>

<span data-ttu-id="41b93-196">Be to, jei nustatysite šią nuostatą į `FALSE`, daugelis kitų prijungtųjų funkcijų taip pat bus išjungtos, pvz., redagavimas vienu metu ir failų saugykla internete.</span><span class="sxs-lookup"><span data-stu-id="41b93-196">In addition, if you disable this policy setting, most other connected experiences are also turned off, such as co-authoring and online file storage.</span></span> <span data-ttu-id="41b93-197">Išsamesnį prijungtųjų funkcijų sąrašą žr. [Prijungtosios funkcijos „Office“](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="41b93-197">For a list of these other connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

<span data-ttu-id="41b93-198">Net jei nustatysite šią nuostatą į `FALSE`, kai kurios „Office“ funkcijos ir toliau veiks, pvz., bus sinchronizuojama jūsų „Outlook“ pašto dėžutė ir veiks „Teams“ bei „Skype“ verslui.</span><span class="sxs-lookup"><span data-stu-id="41b93-198">But even if you disable this policy setting, limited Office functionality will remain available, such as synching a mailbox in Outlook, and Teams and Skype for Business will continue to work.</span></span> <span data-ttu-id="41b93-199">[Pagrindinės paslaugos](essential-services.md), pvz., licencijavimo tarnyba, kuri patvirtina, kad turite tinkamą licenciją naudoti „Office“, taip pat veiks.</span><span class="sxs-lookup"><span data-stu-id="41b93-199">[Essential services](essential-services.md), such as the licensing service that confirms that you’re properly licensed to use Office, will also remain available.</span></span>

<span data-ttu-id="41b93-200">Jei vartotojas turi „Office 365“ prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą, arba vartotojas turi „Office 2019 for Mac“ bendrojo licencijavimo versiją, vartotojas negali išjungti daugelio prijungtųjų funkcijų.</span><span class="sxs-lookup"><span data-stu-id="41b93-200">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off most connected experiences.</span></span>

<span data-ttu-id="41b93-201">Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ prenumeratą, gali pasirinkti išjungti daugelį prijungtųjų funkcijų nuėję į sritį **Nuostatos** > **Privatumas**.</span><span class="sxs-lookup"><span data-stu-id="41b93-201">For other users, such as home users with an Office 365 subscription, a user can choose to turn off most connected experiences by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-the-required-data-notice-dialog-for-microsoft-autoupdate"></a><span data-ttu-id="41b93-202">„Microsoft AutoUpdate“ būtinųjų duomenų pranešimo dialogo lango nuostatos parametras</span><span class="sxs-lookup"><span data-stu-id="41b93-202">Preference setting for the Required Data Notice dialog for Microsoft AutoUpdate</span></span>

<span data-ttu-id="41b93-203">Pirmą kartą paleidus „Microsoft AutoUpdate“ (MAU) 4.12 arba vėlesnę versiją, vartotojams bus rodomas dialogo langas **Būtinų duomenų pranešimas**, kuriame bus pateikta informacija apie tai, kokie MAU duomenys siunčiami „Microsoft“.</span><span class="sxs-lookup"><span data-stu-id="41b93-203">The first time Version 4.12 or later of Microsoft AutoUpdate (MAU) is launched, users will see a **Required Data Notice** dialog which provides them with information about what data from MAU is sent to Microsoft.</span></span>

<span data-ttu-id="41b93-204">Jei nenorite, kad vartotojai matytų „Microsoft AutoUpdate“ dialogo langą **Būtinų duomenų pranešimas**, galite nustatyti toliau pateiktą nuostatą.</span><span class="sxs-lookup"><span data-stu-id="41b93-204">If you don't want your users to see this **Required Data Notice** dialog for Microsoft AutoUpdate, you can set the following preference.</span></span> <span data-ttu-id="41b93-205">Neatsižvelgiant į tai, kurią reikšmę nustatėte, vartotojams nebus rodomas dialogo langas.</span><span class="sxs-lookup"><span data-stu-id="41b93-205">Regardless of which value you set, the dialog won't be shown to your users.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="41b93-206">**Nuostatų domenas**</span><span class="sxs-lookup"><span data-stu-id="41b93-206">**Preference Domain**</span></span>  | `com.microsoft.autoupdate2` |
|<span data-ttu-id="41b93-207">**Raktas**</span><span class="sxs-lookup"><span data-stu-id="41b93-207">**Key**</span></span>  | `AcknowledgedDataCollectionPolicy`  |
|<span data-ttu-id="41b93-208">**Duomenų tipas**</span><span class="sxs-lookup"><span data-stu-id="41b93-208">**Data Type**</span></span>  | <span data-ttu-id="41b93-209">Eilutė</span><span class="sxs-lookup"><span data-stu-id="41b93-209">String</span></span> |
|<span data-ttu-id="41b93-210">**Galimos reikšmės**</span><span class="sxs-lookup"><span data-stu-id="41b93-210">**Possible values**</span></span>  | `RequiredDataOnly` <br/> `RequiredAndOptionalData`|
|<span data-ttu-id="41b93-211">**Pasiekiamumas**</span><span class="sxs-lookup"><span data-stu-id="41b93-211">**Availability**</span></span> |<span data-ttu-id="41b93-212">4.12 ir vėlesnė</span><span class="sxs-lookup"><span data-stu-id="41b93-212">4.12 and later</span></span> |

<span data-ttu-id="41b93-213">Jei leisite vartotojams matyti šį dialogo langą, tada vartotojui pasirinkus **Gerai**, reikšmė `RequiredDataOnly` įrašoma į `AcknowledgedDataCollectionPolicy`ir vartotojui daugiau neberodomas dialogo langas.</span><span class="sxs-lookup"><span data-stu-id="41b93-213">If you let your users see this dialog, then when the user chooses **OK**, the value `RequiredDataOnly` is written to `AcknowledgedDataCollectionPolicy` and the dialog is not shown to the user again.</span></span>


## <a name="related-topics"></a><span data-ttu-id="41b93-214">Susijusios temos</span><span class="sxs-lookup"><span data-stu-id="41b93-214">Related topics</span></span>

- [<span data-ttu-id="41b93-215">Konfigūravimo profilio nuoroda („Apple“ kūrėjų dokumentacija)</span><span class="sxs-lookup"><span data-stu-id="41b93-215">Configuration Profile Reference (Apple developer documentation)</span></span>](https://go.microsoft.com/fwlink/p/?linkid=852998)
- [<span data-ttu-id="41b93-216">„Office for Mac“ diegimo nuostatos</span><span class="sxs-lookup"><span data-stu-id="41b93-216">Deploy preferences for Office for Mac</span></span>](../mac/deploy-preferences-for-office-for-mac.md)
- [<span data-ttu-id="41b93-217">Paskyros privatumo parametrai</span><span class="sxs-lookup"><span data-stu-id="41b93-217">Account Privacy Settings</span></span>](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Mac)
