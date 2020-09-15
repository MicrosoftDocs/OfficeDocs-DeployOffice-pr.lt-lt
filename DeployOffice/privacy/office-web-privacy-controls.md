---
title: Norėdami valdyti „Microsoft Office“, skirto internetinėms programėlėms, privatumo parametrus, naudokite strategijos parametrus
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
description: Pateikiama informacija „Office“ administratoriams, kaip valdyti „Office“, skirto internetinėms programėlėms, privatumo parametrus.
hideEdit: true
ms.openlocfilehash: b5131d5ffc09b28a3b5731a417fcd6d383fb7d01
ms.sourcegitcommit: da41d41b443c8392c96e64a4d2fc674957abddf5
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 09/11/2020
ms.locfileid: "47431957"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-office-for-the-web-applications"></a>Norėdami valdyti „Microsoft Office“, skirto internetinėms programėlėms, privatumo parametrus, naudokite strategijos parametrus

> [!NOTE]
> „Office“ produktų, kuriems taikoma ši privatumo informacija, sąrašas, žr. [„Office“ produktų privatumo valdiklius](products-versions-privacy-controls.md).

Jei esate organizacijos administratorius, galite kontroliuoti, ar jūsų vartotojai gali pasirinkti naudoti pasirinktines prisijungus naudojamas funkcijas, kai jie naudoja „Office“ internetinėms programėlėms, pvz., internetinei „Microsoft Word“ arba internetinei „Microsoft PowerPoint“. Šis pasirinkimas pasiekiamas jūsų vartotojams tik tuo atveju, jei jie yra prisijungę naudodami savo darbo arba mokymo įstaigos paskyrą, kai naudoja „Office“ internetinėms programėlėms. Norėdami kontroliuoti, ar jūsų vartotojai turi pasirinkimą naudoti pasirinktines prisijungus naudojamas funkcijas, galite naudoti strategijos parametrą *Leisti „Office“ naudoti papildomas pasirinktines prisijungus naudojamas funkcijas*.

## <a name="overview-of-optional-connected-experiences"></a>Pasirinktinių prisijungus naudojamų funkcijų apžvalga

Pasirinktinės prisijungus naudojamos funkcijos – tai debesų technologijos pagrindu veikiančios paslaugos, kurios pasiekiamos vartotojams, kai jie naudoja „Office“. Pasirinktinių prisijungus naudojamų funkcijų pavyzdžiai: žemėlapio diagramų kūrimas „Excel“ arba interneto paveikslėlio įterpimas į „Word“ dokumentą, kurie priklauso nuo „Microsoft Bing“ teikiamų paslaugų. Šių debesų technologijų pagrindu veikiančių paslaugų naudojimas yra pasirinktinis. 

Prisijungus naudojamos funkcijos neaptariamos jūsų organizacijos komerciniame susitarime su „Microsoft“. Vietoj to, pasirinktinėms prisijungus naudojamoms funkcijoms, kurias „Microsoft“ siūlo tiesiogiai vartotojams, taikoma [„Microsoft“ paslaugų teikimo sutartis](https://www.microsoft.com/servicesagreement). Kai kuriais atvejais, per šias pasirinktines prisijungus naudojamas funkcijas teikiamas trečiosios šalies turinys ar funkcionalumas, todėl taip pat gali būti taikomos kitos sąlygos.

Kai kurios pasirinktinės prijungtos funkcijos gali būti nepasiekiamos „Office“, skirtame internetinėms programėlėms, bet pasiekiamos naudojant kitas „Office“ versijas, pvz., kompiuterio versiją įrenginyje, kuriame veikia „Windows“.

Daugiau informacijos rasite [Pasirinktinių „Office“ prisijungus naudojamų funkcijų apžvalga](optional-connected-experiences.md).

## <a name="configure-the-policy-setting-by-using-the-office-cloud-policy-service"></a>Strategijos parametrų konfigūravimas naudojant „Office“ debesies strategijos tarnybą

Norėdami kontroliuoti, ar pasirinktinės prisijungus naudojamos funkcijos prieinamos vartotojams, galite naudoti strategijos parametrą *Leisti „Office“ naudoti papildomas pasirinktines prisijungus naudojamas funkcijas*. Norėdami konfigūruoti šį strategijos parametrą minėtoms internetinėms „Office“ programėlėms, turite naudoti [„Office“ debesies strategijos tarnybą](../overview-office-cloud-policy-service.md).  

Jei nekonfigūruosite šio strategijos parametro, pasirinkimas naudoti šias papildomas pasirinktines prisijungus naudojamas funkcijas bus pasiekiamas vartotojams. Jei išjungsite šį strategijos parametrą, jūsų vartotojai negalės naudoti jokių pasirenkamų prisijungus naudojamų funkcijų.

„Office“ internetinėse programėlėse strategijos parametrai taikomi, kai jūsų vartotojai dirba su „Office“ dokumentais, įrašytais į žiniatinkliu pagrįstą saugyklą iš „Microsoft“, pvz., „OneDrive“ verslui arba „SharePoint Online“.

Jei naudojate „Office“ debesies strategijos tarnybą, šis strategijos nustatymas taip pat taikomas, kai jūsų vartotojai naudoja „Office“ „Windows“, „Mac“, „iOS“ arba „Android“ įrenginiuose. Negalite konfigūruoti šio strategijos nustatymo tik tada, kai jūsų vartotojai naudoja „Office“ internetinėms programėlėms. Tačiau galite sukurti strategijos konfigūraciją, kuri apima šios strategijos parametrus ir šios strategijos konfigūracija taikoma tik vartotojams, kurie turi pasiekia dokumentus anonimiškai naudodami „Office“ internetinėms programėlėms.

Jei pasirinksite pasirinktines prisijungus naudojamas funkcijas padaryti pasiekiamas vartotojams, jūsų vartotojams pirmą kartą naudojantis internetinio „Office“ programėle bus rodomas pranešimas apie privatumą. Šiame pranešime vartotojai gali sužinos, kad jiems suteikėte galimybę naudoti šias pasirinktines prisijungus naudojamas funkcijas. Pranešime vartotojai taip pat informuojami, kad pagal „Microsoft“ paslaugų teikimo sutartį teikiamos pasirinktinės prisijungus naudojamos funkcijos. Šis pranešimas svarbus jūsų vartotojams, todėl jis turi būti rodomas ir jo negalima išjungti, paslėpti arba priimti jūsų vartotojų vardu.

## <a name="users-can-choose-to-turn-off-optional-connected-experiences"></a>Vartotojai gali pasirinkti išjungti pasirinktines prisijungus naudojamas funkcijas

Jei pasirinksite padaryti pasirinktines prisijungus naudojamas funkcijas pasiekiamas vartotojams, jūsų vartotojai galės eiti į savo [paskyros privatumo parametrus](https://support.microsoft.com/office/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Online) ir pasirinkti išjungti prieigą prie pasirenkamų prisijungus naudojamų funkcijų. Šis pasirinkimas yra pasiekiamas paskyros privatumo parametruose tik tuo atveju, jei jūsų vartotojai yra prisijungę naudodami savo darbo arba mokymo įstaigos paskyrą. Nėra būdo, kuriuo jūs, kaip administratorius, galite neleisti atskiriems jūsų organizacijos vartotojams išjungti jų prieigos prie pasirenkamų prisijungus naudojamų funkcijų, jų paskyros privatumo parametruose, jei suteikėte vartotojams galimybę naudoti pasirinktines prisijungus naudojamas funkcijas.

## <a name="related-articles"></a>Susiję straipsniai

- [„Microsoft 365“ programų įmonėms privatumo kontrolės apžvalga](overview-privacy-controls.md)
- [„Microsoft 365“ programos įmonėms privatumo valdiklių valdymas naudojant strategijos parametrus](manage-privacy-controls.md)
- [„Office“, skirto „Mac“, privatumo valdiklių valdymas, naudojant nuostatas](mac-privacy-preferences.md)
- [„Office“ privatumo valdiklių valdymas „iOS“ įrenginiuose naudojant nuostatas](ios-privacy-preferences.md)
- [„Office“ privatumo valdiklių valdymas „Android“ įrenginiuose naudojant strategijos parametrus](android-privacy-controls.md)