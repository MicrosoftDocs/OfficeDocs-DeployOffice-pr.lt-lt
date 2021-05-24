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
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a>„Office“ privatumo valdiklių valdymas „iOS“ įrenginiuose naudojant nuostatas

> [!NOTE]
> „Office“ produktų, kuriems taikoma ši privatumo informacija, sąrašą žr. [Galimi „Office“ produktų privatumo valdikliai](products-versions-privacy-controls.md).

Yra naujų nuostatų parametrų, skirtų „Office“ „iOS“ įrenginiuose, leidžiančių valdyti parametrus, susijusius su:

- ***Diagnostikos duomenimis*** apie „Office“ kliento naudojamą programinę įrangą, kurie renkami ir siunčiami „Microsoft“.

- ***Prisijungus naudojamų funkcijų***, kurios veikia debesų technologijos pagrindu ir pagerina jūsų ir jūsų vartotojų naudojamas „Office“ funkcijas.

Daugiau informacijos apie diagnostikos duomenis ir prijungtąsias funkcijas žr. [Privatumo valdiklių apžvalga](overview-privacy-controls.md).

> [!NOTE]
> Informaciją apie panašius „Office“ parametrus „macOS“ kompiuteriuose žr. [„Office“ privatumo valdiklių valdymas „macOS“ įrenginiuose naudojant nuostatas](mac-privacy-preferences.md).


## <a name="setting-device-preferences"></a>Įrenginio nuostatų nustatymas
Šiuos naujus nuostatų parametrus taip pat galima nustatyti mobiliojo įrenginio valdymo (MDM) serveryje įrenginio lygiu, kai įdiegta „Office“ taikomoji programa. Daug MDM serverių leidžia IT administratoriams įtraukti pasirinktinį konfigūravimo žodyną, kai serveris siunčia `InstallApplication` MDM komandą į „iOS“ įrenginį. Jei reikia daugiau informacijos, žr. MDM serverio dokumentaciją.

Žodynas vaizduojamas kaip raktų / reikšmių porų rinkinys XML formatu. Pavyzdžiui:

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

Kai nusiųsite į įrenginį, konfigūravimo žodynas bus rodomas po `com.apple.managed.configuration` klavišu, kur jis bus perskaitytas, kai bus paleista „Office“ taikomoji programa.

> [!NOTE]
> Taip pat galite naudoti „Office“ debesies strategijos tarnybą ir šiuos 4 strategijos parametrus:
> - Konfigūruoti kliento programinės įrangos diagnostikos duomenų lygį, kuriuos „Office“ siunčia „Microsoft“ tarnybai
> - Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios analizuoja turinį
> - Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios parsiunčia internetinį turinį
> - Leisti „Office“ naudoti pasirinktines, papildomas prisijungus naudojamas funkcijas 
>
> „Outlook“ skirtos „iOS“ ir „OneDrive“ skirtos „iOS: privatumo parametrai gali būti konfigūruojami tik naudojant „Office“ debesies strategijos tarnybą.
>
> Daugiau informacijos apie „Office“ debesies strategijų tarnybos naudojimą rasite straipsnyje [„Office“ debesies strategijų tarnybos apžvalga](../overview-office-cloud-policy-service.md).

## <a name="preference-setting-for-diagnostic-data"></a>Diagnostikos duomenų nuostatos nustatymas

Diagnostikos duomenys naudojami siekiant apsaugoti ir naujinti „Office“, aptikti, diagnozuoti ir spręsti problemas, taip pat tobulinti produktus. Daugiau informacijos žr. [Diagnostikos duomenys, siunčiami „Microsoft“ iš „Microsoft 365“ programų įmonėms](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).

|Kategorija|Išsami informacija|
|:-----|:-----|
|**Raktas**  | `DiagnosticDataTypePreference`  |
|**Duomenų tipas**  | Eilutė |
|**Galimos reikšmės**  | `BasicDiagnosticData` *(ši reikšmė nustato lygį į Būtina)* <br/> `FullDiagnosticData` *(ši reikšmė nustato lygį į Pasirinktinai)* <br/> `ZeroDiagnosticData` *(ši reikšmė nustato lygį į Nė vienas)* |

Jei nenustatysite šios nuostatos, „Microsoft“ bus siunčiami tik pasirinktiniai diagnostikos duomenys, jei vartotojai, turintys „Office 365“ (arba „Microsoft 365“) prenumeratą, bus prisijungę naudodami darbo arba mokymo įstaigos paskyrą. Be to, šie vartotojai negali pakeisti diagnostikos duomenų lygio, neatsižvelgiant į tai, kaip nustatėte šią nuostatą.

> [!NOTE]
> Atnaujinome ankstesnę pastraipą, kad paaiškintume, jog pasirinktiniai diagnostikos duomenys taip pat siunčiami „Microsoft“, jei nenustatėte šios nuostatos.

Kitų vartotojų, pvz., namų vartotojų, turinčių „Office 365“ (arba „Microsoft 365“) prenumeratą, siunčiami tik privalomieji diagnostikos duomenys, nebent vartotojas pasirenka taip pat siųsti pasirinktinius diagnostikos duomenis eidamas į sritį **Parametrai** > **Privatumo parametrai**.


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a>Turinį analizuojančių prisijungus naudojamų funkcijų nuostatų nustatymas

Turinį analizuojančios prijungtosios funkcijos yra funkcijos, kurios naudodamos „Office“ turinį pateikia dizaino rekomendacijų, redagavimo pasiūlymų, duomenų įžvalgų ir panašių funkcijų. Pvz., „PowerPoint“ dizaino idėjos. Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos „Office“](connected-experiences.md).

|Kategorija|Išsami informacija|
|:-----|:-----|
|**Raktas**  | `OfficeExperiencesAnalyzingContentPreference`  |
|**Duomenų tipas**  | Bulio logika |
|**Galimos reikšmės**  | `TRUE` *(įgalinta)* <br/> `FALSE` *(išjungta)*|


Jei nenustatysite šios nuostatos, vartotojams bus pasiekiamos turinį analizuojančios prijungtosios funkcijos.

Jei vartotojas turi „Office 365“ (arba „Microsoft 365“) prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą, jis negali išjungti prijungtųjų funkcijų, kurios analizuoja turinį.

Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ (arba „Microsoft 365“) prenumeratą, gali pasirinkti išjungti prijungtąsias funkcijas, kurios analizuoja turinį, nuėję į sritį **Nustatymai** > **Privatumo nustatymai**.

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a>Prijungtųjų funkcijų, kurios atsisiunčia internetinį turinį, nuostatų nustatymas

Prisijungus naudojamos funkcijos, kurios atsisiunčia internetinį turinį, yra funkcijos, kurias naudodami galite ieškoti internetinio turinio ir jį atsisiųsti, įskaitant šablonus, vaizdus, vaizdo įrašus ir pagalbinę medžiagą, kad patobulintumėte dokumentus. Pvz., „Office“ šablonai ar internetinės piktogramos įterpimas. Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos „Office“](connected-experiences.md).

|Kategorija|Išsami informacija|
|:-----|:-----|
|**Raktas**  | `OfficeExperiencesDownloadingContentPreference`  |
|**Duomenų tipas**  | Bulio logika |
|**Galimos reikšmės**  | `TRUE` *(įgalinta)* <br/> `FALSE` *(išjungta)*|


Jei nenustatysite šios nuostatos, vartotojams bus pasiekiamos internetinį turinį atsisiunčiančios prijungtosios funkcijos.

Jei vartotojas turi „Office 365“ (arba „Microsoft 365“) prenumeratą ir yra prisijungęs naudodamas darbo arba mokymo įstaigos paskyrą, jis negali išjungti prijungtųjų funkcijų, kurios atsisiunčia interneto turinį.

Kiti vartotojai, pvz., namų vartotojai, turintys „Office 365“ (arba „Microsoft 365“) prenumeratą, gali pasirinkti išjungti prijungtas funkcijas, kurios atsisiunčia interneto turinį, nuėję į sritį **Nustatymai** > **Privatumo nustatymai**.

## <a name="preference-setting-for-optional-connected-experiences"></a>Pasirinktinių prijungtųjų funkcijų nuostatų nustatymas

Be anksčiau minėtų prijungtųjų funkcijų, yra tam tikrų pasirinktinių prijungtųjų funkcijų, kurias galite leisti pasiekti vartotojams, prisijungusiems su organizacijos paskyra, kuri kartais vadinama darbo arba mokymo įstaigos paskyra. Pvz., „Office“ papildiniai, atsisiunčiami iš „Office“ parduotuvės į jūsų įrenginį. Daugiau pavyzdžių rasite [Pasirinktinių „Office“ prisijungus naudojamų funkcijų apžvalga](optional-connected-experiences.md).

|Kategorija|Išsami informacija|
|:-----|:-----|
|**Raktas**  | `OptionalConnectedExperiencesPreference`  |
|**Duomenų tipas**  | Bulio logika |
|**Galimos reikšmės**  | `TRUE` *(įgalinta)* <br/> `FALSE` *(išjungta)*|


Jei nenustatysite šios nuostatos, pasirinktinės prijungtosios funkcijos bus pasiekiamos vartotojams, turintiems „Office 365“ (arba „Microsoft 365“) prenumeratą, kurie yra prisijungę naudodami darbo ar mokymo įstaigos paskyrą. Jei nenustatėte šios nuostatos į FALSE (klaidinga), šie vartotojai gali pasirinkti išjungti pasirinktines prijungtąsias funkcijas nuėję į **Parametrai**  >  **Privatumo parametrai**.

Kitiems vartotojams, pvz., namų vartotojams, turintiems „Office 365“ (arba „Microsoft 365“) prenumeratą, neteikiama galimybė išjungti pasirinktines prijungtąsias funkcijas.