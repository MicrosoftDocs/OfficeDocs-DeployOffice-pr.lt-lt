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
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a>„Office“ privatumo valdiklių valdymas „iOS“ įrenginiuose naudojant nuostatas

Yra naujų nuostatų parametrų, skirtų „Office“ „iOS“ įrenginiuose, leidžiančių valdyti parametrus, susijusius su:

- ***Diagnostikos duomenimis*** apie „Office“ kliento naudojamą programinę įrangą, kurie renkami ir siunčiami „Microsoft“.

- ***Prisijungus naudojamų funkcijų***, kurios veikia debesų technologijos pagrindu ir pagerina jūsų ir jūsų vartotojų naudojamas „Office“ funkcijas.

Daugiau informacijos apie diagnostikos duomenis ir prisijungus naudojamas funkcijas žr. [Privatumo valdiklių apžvalga](overview-privacy-controls.md).

Šie nuostatų parametrai taikomi šioms taikomosioms programoms:
- 2.30 ir naujesnės versijos „Word“, skirtai „iOS“, „Excel“, skirtai „iOS“, ir „PowerPoint“, skirtai „iOS“.
- 16.30 ir naujesnės versijos „OneNote“, skirtai „iOS“.
- 1.17 ir naujesnės versijos „Visio“ peržiūros programai, skirtai „iOS“.

> [!NOTE]
> Informaciją apie panašius „Office“ parametrus „macOS“ kompiuteriuose žr. [„Office“ privatumo valdiklių valdymas „macOS“ įrenginiuose naudojant nuostatas](mac-privacy-preferences.md).


## <a name="setting-device-preferences"></a>Įrenginio nuostatų nustatymas
Šiuos naujus nuostatų parametrus taip pat galima nustatyti mobiliojo įrenginio valdymo (MDM) serveryje įrenginio lygiu, kai įdiegta „Office“ taikomoji programa. Daug MDM serverių leidžia IT administratoriams įtraukti pasirinktinį konfigūravimo žodyną, kai serveris siunčia `InstallApplication` MDM komandą į „iOS“ įrenginį. Jei reikia daugiau informacijos, žr. MDM serverio dokumentaciją.

Žodynas vaizduojamas kaip raktų/reikšmių porų rinkinys XML formatu. Pavyzdžiui:

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

Kai nusiųsite į įrenginį, konfigūravimo žodynas bus rodomas po `com.apple.managed.configuration` klavišu, kur jis bus perskaitytas, kai bus paleista „Office“ taikomoji programa.

## <a name="preference-setting-for-diagnostic-data"></a>Diagnostikos duomenų nuostatos nustatymas

Diagnostikos duomenys naudojami siekiant apsaugoti ir atnaujinti „Office“, aptikti, diagnozuoti ir spręsti problemas, taip pat tobulinti produktus. Daugiau informacijos žr. [Diagnostikos duomenys, siunčiami „Microsoft“ iš „Office 365 ProPlus“](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).

|||
|:-----|:-----|
|**Raktas**  | `DiagnosticDataTypePreference`  |
|**Duomenų tipas**  | Eilutė |
|**Galimos reikšmės**  | `BasicDiagnosticData` *(nustatomas lygis Privalomieji)* <br/> `FullDiagnosticData` *(nustatomas lygis Pasirinktiniai)* <br/> `ZeroDiagnosticData` *(nustatomas lygis Nė vienas)* |

Jei nenustatysite šios nuostatos, „Microsoft“ bus siunčiami tik privalomieji diagnostikos duomenys, jei vartotojai, turintys „Office 365“ prenumeratą, bus prisijungę naudodami darbo arba mokymo įstaigos paskyrą. Be to, šie vartotojai negali pakeisti diagnostikos duomenų lygio, neatsižvelgiant į tai, kaip nustatėte šią nuostatą.

Kitų vartotojų, pvz., namų vartotojų, turinčių „Office 365“ prenumeratą, siunčiami tik privalomieji diagnostikos duomenys, nebent vartotojas pasirenka taip pat siųsti pasirinktinius diagnostikos duomenis eidamas į sritį **Parametrai** > **Privatumo parametrai**.


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a>Turinį analizuojančių prisijungus naudojamų funkcijų nuostatų nustatymas

Turinį analizuojančios prijungtosios funkcijos yra funkcijos, kurios naudodamos „Office“ turinį pateikia dizaino rekomendacijų, redagavimo pasiūlymų, duomenų įžvalgų ir panašių funkcijų. Pvz., „PowerPoint“ dizaino idėjos. Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos „Office“](connected-experiences.md).

|||
|:-----|:-----|
|**Raktas**  | `OfficeExperiencesAnalyzingContentPreference`  |
|**Duomenų tipas**  | Bulio logika |
|**Galimos reikšmės**  | `TRUE` *(įgalinta)* <br/> `FALSE` *(išjungta)*|


Jei nenustatysite šios nuostatos, vartotojams bus pasiekiamos turinį analizuojančios prijungtosios funkcijos.

Jei vartotojas turi „Office 365“ prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą, jis negali išjungti prijungtųjų funkcijų, kurios analizuoja turinį.

Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ prenumeratą, gali pasirinkti išjungti prijungtąsias funkcijas, kurios analizuoja turinį, nuėję į sritį **Nustatymai** > **Privatumo nustatymai**.

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a>Prijungtųjų funkcijų, kurios atsisiunčia internetinį turinį, nuostatų nustatymas

Prisijungus naudojamos funkcijos, kurios atsisiunčia internetinį turinį, yra funkcijos, kurias naudodami galite ieškoti internetinio turinio ir jį atsisiųsti, įskaitant šablonus, vaizdus, vaizdo įrašus ir pagalbinę medžiagą, kad patobulintumėte dokumentus. Pvz., „Office“ šablonai ar internetinės piktogramos įterpimas. Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos „Office“](connected-experiences.md).

|||
|:-----|:-----|
|**Raktas**  | `OfficeExperiencesDownloadingContentPreference`  |
|**Duomenų tipas**  | Bulio logika |
|**Galimos reikšmės**  | `TRUE` *(įgalinta)* <br/> `FALSE` *(išjungta)*|


Jei nenustatysite šios nuostatos, vartotojams bus pasiekiamos internetinį turinį atsisiunčiančios prijungtosios funkcijos.

Jei vartotojas turi „Office 365“ prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą, jis negali išjungti prijungtųjų funkcijų, kurios atsisiunčia internetinį turinį.

Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ prenumeratą, gali pasirinkti išjungti prijungtas funkcijas, kurios atsisiunčia internetinį turinį, nuėję į sritį **Nustatymai** > **Privatumo nustatymai**.

## <a name="preference-setting-for-optional-connected-experiences"></a>Pasirinktinių prijungtųjų funkcijų nuostatų nustatymas

Be anksčiau minėtų prijungtųjų funkcijų, yra tam tikrų pasirinktinių prijungtųjų funkcijų, kurias galite leisti pasiekti vartotojams, prisijungusiems su organizacijos paskyra, kuri kartais vadinama darbo arba mokymo įstaigos paskyra. Pvz., „Office“ papildiniai, atsisiunčiami iš „Office“ parduotuvės į jūsų įrenginį. Daugiau pavyzdžių rasite [Pasirinktinių „Office“ prisijungus naudojamų funkcijų apžvalga](optional-connected-experiences.md).

|||
|:-----|:-----|
|**Raktas**  | `OptionalConnectedExperiencesPreference`  |
|**Duomenų tipas**  | Bulio logika |
|**Galimos reikšmės**  | `TRUE` *(įgalinta)* <br/> `FALSE` *(išjungta)*|


Jei nenustatysite šios nuostatos, pasirinktinės prijungtosios funkcijos bus pasiekiamos vartotojams, turintiems „Office 365“ prenumeratą, kurie yra prisijungę naudodami darbo ar mokymo įstaigos paskyrą. Jei nenustatėte šios nuostatos į FALSE (klaidinga), šie vartotojai gali pasirinkti išjungti pasirinktines prijungtąsias funkcijas nuėję į **Parametrai**  >  **Privatumo parametrai **.

Kitiems vartotojams, pvz., namų vartotojams, turintiems „Office 365“ prenumeratą, neteikiama galimybė išjungti pasirinktines prijungtąsias funkcijas.