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
ms.openlocfilehash: 69a8880b03e63be391731f9882bcee17a81a51ab
ms.sourcegitcommit: e542473cc4fe07a98874c275846f6982a6863e35
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 12/05/2019
ms.locfileid: "39837722"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-office-on-android-devices"></a>„Office“ privatumo valdiklių valdymas „Android“ įrenginiuose naudojant strategijų parametrus

Yra strategijų parametrų, skirtų „Office“ programoms „Android“ įrenginiuose, leidžiančių valdyti parametrus, susijusius su:

- ***Diagnostikos duomenimis*** apie „Office“ kliento naudojamą programinę įrangą, kurie renkami ir siunčiami „Microsoft“.

- ***Prisijungus naudojamų funkcijų***, kurios veikia debesų technologijos pagrindu ir pagerina jūsų ir jūsų vartotojų naudojamas „Office“ funkcijas.

Daugiau informacijos apie diagnostikos duomenis ir prisijungus naudojamas funkcijas žr. [Privatumo valdiklių apžvalga](overview-privacy-controls.md).

Šie strategijų parametrai taikomi šioms programoms:
- 16.0.12228.20260 ir naujesnės „Word“, skirtos „Android“, „Excel“, skirtos „Android“, ir „PowerPoint“, skirtos „Android“, versijos.
- 16.0.12228.20004 ir naujesnės „OneNote“, skirtos „Android“, versijos.

> [!NOTE]
>- Šie strategijų parametrai taip pat taikomi 16.0.12130.20272 ir naujesnėms [„Office“ mobiliųjų įrenginių programos](https://techcommunity.microsoft.com/t5/Office-Apps-Blog/Introducing-Office-Your-new-go-to-mobile-app-for-getting-work/ba-p/977172), skirtos „Android“, viešosios peržiūros versijoms.
>- Naudojant „Office“ mobiliųjų įrenginių programos, skirtos „Android“, viešosios peržiūros versiją, bus renkami gedimų žurnalai, kuriuose tam tikromis aplinkybėmis gali būti turinio.
>- Jei nerimaujate dėl duomenų rinkimo, kai naudojate „Office“ mobiliųjų įrenginių programos, skirtos „Android“, viešosios peržiūros versiją, informuokite savo vartotojus neprisijungti prie programos naudojant darbo ar mokymo įstaigų paskyras.

## <a name="policy-settings-available-for-office-on-android-devices"></a>„Office“ strategijų parametrai „Android“ įrenginiuose

Toliau esančioje lentelėje nurodoma, kurie „Office“ strategijų parametrai galimi „Android“ įrenginiuose, ir pateikiamas saitas į papildomą informaciją apie kiekvieną strategijos parametrą.

> [!NOTE]
>- Pateikta papildoma informacija apima „Office“ strategijų parametrus įrenginiuose, kuriuose veikia „Windows“. Tačiau ta pati informacija taikoma ir „Office“, kuris veikia „Android“ įrenginiuose, nes tai yra tie patys strategijų parametrai.
>- Strategijos parametras *Leisti „Office“ naudoti prisijungus naudojamas funkcijas*, kuris galimas „Office“ programose įrenginiuose, kuriuose veikia „Windows“, netaikomas „Office“ programoms „Android“ įrenginiuose. 


|Strategijos parametro pavadinimas  |Papildoma informacija |
|---------|---------|
|Kliento programinės įrangos diagnostikos duomenų, kurį „Office“ siunčia „Microsoft“ tarnybai, lygio konfigūravimas|[Diagnostikos duomenų strategijų parametrai](manage-privacy-controls.md#policy-setting-for-diagnostic-data)         |
|Leisti „Office" naudoti prisijungus naudojamas funkcijas, analizuojančias turinį| [Prisijungus naudojamų funkcijų, kurios analizuoja turinį, strategijos parametras](manage-privacy-controls.md#policy-setting-for-connected-experiences-that-analyze-your-content)        |
|Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios parsiunčia internetinį turinį |[Strategijos parametras prisijungus naudojamoms funkcijoms, kurios atsisiunčia internetinį turinį](manage-privacy-controls.md#policy-setting-for-connected-experiences-that-download-online-content)         |
|Leisti „Office“ naudoti pasirinktines papildomas prisijungus naudojamas funkcijas  |[Strategijų parametrai pasirinktinėms prisijungus naudojamoms funkcijoms](manage-privacy-controls.md#policy-setting-for-optional-connected-experiences)|



## <a name="use-office-cloud-policy-service-to-apply-policy-settings"></a>Strategijų parametrų taikymas naudojant „Office“ debesies strategijų tarnybą

Norėdami pritaikyti bet kurį iš šių 4 strategijų parametrų „Office“, veikiančiame „Android“ įrenginiuose, turite naudoti „Office“ debesies strategijų tarnybą. Daugiau informacijos apie „Office“ debesies strategijų tarnybos naudojimą rasite straipsnyje [„Office“ debesies strategijų tarnybos apžvalga](../overview-office-cloud-policy-service.md).

> [!NOTE]
> Jei anksčiau naudojote „Office“ debesies strategijų tarnybą norėdami konfigūruoti šiuos „Office“ strategijų parametrus įrenginiuose, kuriuose veikia „Windows“, tie patys parametrai taikomi ir naudojant „Office“ „Android“ įrenginiuose. Kad taip būtų, jums tereikia prisijungti prie „Office“ debesies strategijų tarnybos ir ši tarnyba automatiškai pritaikys parametrus „Office“ programoms „Android“ įrenginiuose.
