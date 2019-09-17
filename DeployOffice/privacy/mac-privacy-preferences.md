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
# <a name="use-preferences-to-manage-privacy-controls-for-office-for-mac"></a>„Office for Mac“ privatumo valdiklių valdymas naudojant nuostatas

Nauji nuostatų parametrai, pradedant nuo „Office for Mac“ 16.28 versijos, leis valdyti parametrus, susijusius su:

- ***Diagnostikos duomenimis*** apie „Office“ kliento naudojamą programinę įrangą, kurie renkami ir siunčiami „Microsoft“.

- ***Prijungtosiomis funkcijomis***, kurios veikia debesų technologijos pagrindu ir pagerina jūsų ir jūsų vartotojų naudojamas „Office“ funkcijas.

Be to, yra naujas nuostatų parametras, susijęs su „Microsoft AutoUpdate“ (MAU) dialogo langu **Pranešimas apie privalomuosius duomenis**.

Daugiau informacijos apie diagnostikos duomenis ir prijungtąsias funkcijas žr. [Privatumo valdiklių apžvalga](overview-privacy-controls.md).

> [!NOTE]
> Informacijos apie panašius „Office“ parametrus kompiuteriuose, kuriuose veikia „Windows“, žr. [„Office 365 ProPlus“ privatumo valdiklių valdymas naudojant strategijos parametrus](manage-privacy-controls.md).

## <a name="setting-preferences"></a>Nuostatų nustatymas

Šie nauji nuostatų parametrai yra suderinami su „CFPreferences“ API ir gali būti nustatomi naudojant `defaults` komandą terminale arba priverstinai nustatomi naudojant konfigūravimo profilį ar mobiliųjų įrenginių valdymo (MDM) serverį. Pritaikius nuostatas vartotojas negali pakeisti reikšmių, o visi programos valdikliai bus rodomi kaip išjungti.

## <a name="preference-setting-for-diagnostic-data"></a>Diagnostikos duomenų nuostatos nustatymas

Diagnostikos duomenys naudojami siekiant apsaugoti ir atnaujinti „Office“, aptikti, diagnozuoti ir spręsti problemas, taip pat tobulinti produktus. Daugiau informacijos žr. [Diagnostikos duomenys, siunčiami „Microsoft“ iš „Office 365 ProPlus“](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).

|||
|:-----|:-----|
|**Nuostatų domenas**  | `com.microsoft.office` |
|**Raktas**  | `DiagnosticDataTypePreference`  |
|**Duomenų tipas**  | Eilutė |
|**Galimos reikšmės**  | `BasicDiagnosticData` *(nustatomas lygis Privalomieji)* <br/> `FullDiagnosticData` *(nustatomas lygis Pasirinktiniai)* <br/> `ZeroDiagnosticData` *(nustatomas lygis Nė vienas)* |
|**Pasiekiamumas** |16.28 ir vėlesnės versijos |

> [!NOTE]
> Jei nustatėte šią nuostatą, ji taip pat bus taikoma šiems produktams:
> - „Teams for Mac“ 1.00.217856 ir vėlesnėms versijoms
> - „Skype“ verslui, skirta „Mac“ 16.28 ir vėlesnėms versijoms

Jei nenustatysite šios nuostatos, „Microsoft“ bus siunčiami pasirinktiniai ir privalomieji diagnostikos duomenys, jei vartotojai, turintys „Office 365“ prenumeratą, yra prisijungę naudodami darbo arba mokymo įstaigos paskyrą arba jei vartotojai turi bendrojo licencijavimo „Office 2019 for Mac“ versiją. Be to, šie vartotojai negali pakeisti diagnostikos duomenų lygio, neatsižvelgiant į tai, kaip nustatėte šią nuostatą.

Kitų vartotojų, pvz., namų vartotojų, turinčių „Office 365“ prenumeratą, siunčiami tik privalomieji diagnostikos duomenys, nebent vartotojas pasirenka taip pat siųsti pasirinktinius diagnostikos duomenis eidamas į sritį **Preferences** > **Privacy** (Nuostatos > Privatumas).

## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a>Turinį analizuojančių prijungtųjų funkcijų nuostatos nustatymas

Turinį analizuojančios prijungtosios funkcijos yra funkcijos, kurios naudodamos „Office“ turinį pateikia dizaino rekomendacijų, redagavimo pasiūlymų, duomenų įžvalgų ir panašių funkcijų. Pavyzdžiui, „PowerPoint“ dizaino įrankis arba „Word“ Tyrinėtojas. Išsamesnį prijungtųjų funkcijų sąrašą žr. [„Office“ prijungtosios funkcijos](connected-experiences.md).

|||
|:-----|:-----|
|**Nuostatų domenas**  | `com.microsoft.office` |
|**Raktas**  | `OfficeExperiencesAnalyzingContentPreference`  |
|**Duomenų tipas**  | Bulio logika |
|**Galimos reikšmės**  | `TRUE` *(įgalinta)* <br/> `FALSE` *(išjungta)*|
|**Pasiekiamumas** |16.28 ir vėlesnės versijos |

Jei nenustatysite šios nuostatos, vartotojams bus teikiamos turinį analizuojančios prijungtosios funkcijos. 

Jei vartotojas turi „Office 365“ prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą arba vartotojas turi „Office 2019 for Mac“ bendrojo licencijavimo versiją, vartotojas negali išjungti prijungtųjų funkcijų, kurios analizuoja turinį.

Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ prenumeratą, gali pasirinkti išjungti prijungtąsias funkcijas, kurios analizuoja turinį, nuėję į sritį **Preferences** > **Privacy** (Nuostatos > Privatumas).

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a>Internetinį turinį atsisiunčiančių prijungtųjų funkcijų nuostatos nustatymas

Prijungtosios funkcijos, kurios atsisiunčia turinį, yra funkcijos, kurias naudodami galite ieškoti internetinio turinio ir jį atsisiųsti, įskaitant šablonus, vaizdus, 3D modelius, vaizdo įrašus ir pagalbinę medžiagą, kad patobulintumėte dokumentus. Pavyzdžiui, „Office“ šablonai arba „PowerPoint“ funkcija „QuickStarter“. Išsamesnį prijungtųjų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos naudojant „Office“](connected-experiences.md).

|||
|:-----|:-----|
|**Nuostatų domenas**  | `com.microsoft.office` |
|**Raktas**  | `OfficeExperiencesDownloadingContentPreference`  |
|**Duomenų tipas**  | Bulio logika |
|**Galimos reikšmės**  | `TRUE` *(įgalinta)* <br/> `FALSE` *(išjungta)*|
|**Pasiekiamumas** |16.28 ir vėlesnės versijos |

Jei nenustatysite šios nuostatos, vartotojams bus teikiamos internetinį turinį atsisiunčiančios prijungtosios funkcijos.

Jei vartotojas turi „Office 365“ prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą arba vartotojas turi „Office 2019 for Mac“ bendrojo licencijavimo versiją, vartotojas negali išjungti prijungtųjų funkcijų, kurios atsisiunčia internetinį turinį.

Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ prenumeratą, gali pasirinkti išjungti prijungtas funkcijas, kurios atsisiunčia internetinį turinį, nuėję į sritį **Preferences** > **Privacy** (Nuostatos > Privatumas).

## <a name="preference-setting-for-optional-connected-experiences"></a>Pasirinktinių prijungtųjų funkcijų nuostatos nustatymas

Be anksčiau minėtų prijungtųjų funkcijų, yra tam tikrų pasirinktinių prijungtųjų funkcijų, kurias galite leisti pasiekti vartotojams, prisijungusiems su organizacijos paskyra, kuri kartais vadinama darbo arba mokymo įstaigos paskyra. Pavyzdžiui, „LinkedIn“ CV kūrimo pagalbinės priemonės funkcijos programoje „Word“ arba orų prognozės juosta programoje „Outlook“, kurią naudoja MSN orai. Daugiau pavyzdžių rasite [Pasirinktinių „Office“ prijungtųjų funkcijų apžvalga](optional-connected-experiences.md).

|||
|:-----|:-----|
|**Nuostatų domenas**  | `com.microsoft.office` |
|**Raktas**  | `OptionalConnectedExperiencesPreference`  |
|**Duomenų tipas**  | Bulio logika |
|**Galimos reikšmės**  | `TRUE` *(įgalinta)* <br/> `FALSE` *(išjungta)*|
|**Pasiekiamumas** |16.28 ir vėlesnės versijos |

Jei nenustatysite šios nuostatos, pasirinktinės prijungtosios funkcijos bus pasiekiamos vartotojams, turintiems „Office 365“ prenumeratą, kurie yra prisijungę naudodami darbo ar mokymo įstaigos paskyrą, arba vartotojams, kurie turi bendrojo licencijavimo „Office 2019 for Mac“ versiją. Jei nenustatėte šios nuostatos į `FALSE`, šie vartotojai galės pasirinkti išjungti pasirinktines prijungtąsias funkcijas eidami į **Preferences** > **Privacy** (Nuostatos > Privatumas).

Kitiems vartotojams, pvz., namų vartotojams, turintiems „Office 365“ prenumeratą, neteikiama galimybė išjungti pasirinktines prijungtąsias funkcijas.

## <a name="preference-setting-for-most-connected-experiences"></a>Daugelio prijungtųjų funkcijų nuostatos nustatymas

Šią nuostatą galite naudoti norėdami kontroliuoti, ar prijungtosios funkcijos pasiekiamos jūsų vartotojams.

|||
|:-----|:-----|
|**Nuostatų domenas**  | `com.microsoft.office` |
|**Raktas**  | `ConnectedOfficeExperiencesPreference`  |
|**Duomenų tipas**  | Bulio logika |
|**Galimos reikšmės**  | `TRUE` *(įgalinta)* <br/> `FALSE` *(išjungta)*|
|**Pasiekiamumas** |16.28 ir vėlesnės versijos |

Jei ši nuostata nerodoma, vartotojams pasiekiamos visos prijungtosios funkcijos, nebent nustatėte kurią nors kitą anksčiau minėtų prijungtųjų funkcijų nuostatą, pvz., `OfficeExperiencesAnalyzingContentPreference`.

Jei nustatysite šią nuostatą į `FALSE`, vartotojams nebus pasiekiamos toliau nurodytų tipų prijungtosios funkcijos:
- Funkcijos, kurios analizuoja turinį
- Funkcijos, kurios atsisiunčia internetinį turinį
- Pasirinktinės prisijungus naudojamos funkcijos

Be to, jei nustatysite šią nuostatą kaip `FALSE`, daugelis kitų prijungtųjų funkcijų taip pat bus išjungtos, pvz., redagavimas vienu metu ir failų saugykla internete. Išsamesnį prijungtųjų funkcijų sąrašą žr. [Prijungtosios funkcijos „Office“](connected-experiences.md).

Net jei nustatysite šią nuostatą kaip `FALSE`, kai kurios „Office“ funkcijos ir toliau veiks, pvz., bus sinchronizuojama jūsų „Outlook“ pašto dėžutė ir veiks „Teams“ bei „Skype“ verslui. [Pagrindinės paslaugos](essential-services.md), pvz., licencijavimo tarnyba, kuri patvirtina, kad turite tinkamą licenciją naudoti „Office“, taip pat veiks.

Jei vartotojas turi „Office 365“ prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą arba vartotojas turi „Office 2019 for Mac“ bendrojo licencijavimo versiją, vartotojas negali išjungti daugelio prijungtųjų funkcijų.

Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ prenumeratą, gali pasirinkti išjungti daugelį prijungtųjų funkcijų nuėję į sritį **Preferences** > **Privacy** (Nuostatos > Privatumas).

## <a name="preference-setting-for-the-required-data-notice-dialog-for-microsoft-autoupdate"></a>„Microsoft AutoUpdate“ pranešimo apie privalomuosius duomenis dialogo lango nuostatos nustatymas

Pirmą kartą paleidus „Microsoft AutoUpdate“ (MAU) 4.12 arba vėlesnę versiją, vartotojams bus rodomas dialogo langas **Pranešimas apie privalomuosius duomenis**, kuriame bus pateikta informacija apie tai, kokie MAU duomenys siunčiami „Microsoft“.

Jei nenorite, kad vartotojai matytų „Microsoft AutoUpdate“ dialogo langą **Pranešimas apie privalomuosius duomenis**, galite nustatyti toliau pateiktą nuostatą. Neatsižvelgiant į tai, kurią reikšmę nustatėte, vartotojams nebus rodomas dialogo langas.

|||
|:-----|:-----|
|**Nuostatų domenas**  | `com.microsoft.autoupdate2` |
|**Raktas**  | `AcknowledgedDataCollectionPolicy`  |
|**Duomenų tipas**  | Eilutė |
|**Galimos reikšmės**  | `RequiredDataOnly` <br/> `RequiredAndOptionalData`|
|**Pasiekiamumas** |4.12 ir vėlesnės versijos |

Jei leisite vartotojams matyti šį dialogo langą, tada vartotojui pasirinkus **Gerai**, reikšmė `RequiredDataOnly` įrašoma į `AcknowledgedDataCollectionPolicy`ir vartotojui daugiau neberodomas dialogo langas.


## <a name="related-topics"></a>Susijusios temos

- [Konfigūravimo profilio nuoroda („Apple“ kūrėjų dokumentacija)](https://go.microsoft.com/fwlink/p/?linkid=852998)
- [„Office for Mac“ diegimo nuostatos](../mac/deploy-preferences-for-office-for-mac.md)
- [Paskyros privatumo parametrai](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Mac)
