---
title: „Office 365 ProPlus“ privatumo valdiklių valdymas naudojant strategijos parametrus
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection:
- Ent_O365
- M365-modern-desktop
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Suteikia informacijos „Office“ administratoriams, kaip valdyti privatumo kontrolės mechanizmus "Office 365 ProPlus" naudojant strategijos parametrus.
hideEdit: true
ms.openlocfilehash: ee02079595157af2fea8883069a640b90ff962d2
ms.sourcegitcommit: ff396a54d8e36d71ebc4cade5014eb502952dc65
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 11/15/2019
ms.locfileid: "38639323"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-office-365-proplus"></a>„Office 365 ProPlus“ privatumo valdiklių valdymas naudojant strategijos parametrus

„Microsoft“ yra įsipareigojusi suteikti jums informaciją ir jums reikalingus valdiklius, kad galėtumėte priimti sprendimus, susijusius su jūsų duomenų rinkimu ir naudojimu, kai naudojatės „Office 365 ProPlus“.

Nauji strategijos parametrai, pradedant nuo „Office 365 ProPlus“ 1904 versijos, leis jums nustatyti parametrus, susijusius su:

- ***Diagnostikos duomenimis*** apie „Office“ kliento naudojamą programinę įrangą, kurie renkami ir siunčiami „Microsoft“.

- ***Prisijungus naudojamų funkcijų***, kurios veikia debesų technologijos pagrindu ir pagerina jūsų ir jūsų vartotojų naudojamas „Office“ funkcijas.

Toliau pateikiami penki naujos strategijos parametrai:

- Konfigūruoti kliento programinės įrangos diagnostikos duomenų lygį, kuriuos „Office“ siunčia „Microsoft“ tarnybai
- Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios analizuoja turinį
- Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios parsiunčia internetinį turinį
- Leisti „Office“ naudoti pasirinktines, papildomas prisijungus naudojamas funkcijas 
- Leisti „Office" naudoti prisijungus naudojamas funkcijas

Šie strategijos parametrai gali būti įdiegti naudojant arba grupės strategiją, arba [„Office“ debesies strategijos tarnybą](https://docs.microsoft.com/DeployOffice/overview-office-client-policy-service). Jei naudojate grupės strategiją, turite atsisiųsti naujausius administravimo šablonų failus (ADMX/ADML) iš [„Microsoft“ atsisiuntimo centro](https://www.microsoft.com/download/details.aspx?id=49030).

> [!NOTE]
> - Informaciją apie „Office for Mac“ privatumo valdiklių valdymą žr. [Nuostatų naudojimas siekiant valdyti „Office for Mac“ privatumo valdiklius](mac-privacy-preferences.md).
> - Informaciją apie panašius „Office“ parametrus „iOS“ įrenginiuose žr. [„Office“ privatumo valdiklių valdymas „iOS“ įrenginiuose naudojant nuostatas](ios-privacy-preferences.md).
> - Informaciją apie panašius „Office“ parametrus „Android“ įrenginiuose žr. [„Office“ privatumo valdiklių valdymas „Android“ įrenginiuose naudojant strategijos parametrus](android-privacy-controls.md).


Jei naudojate grupės strategijos valdymo įrankį, šie strategijos parametrai yra įrankio srityje Vartotojo konfigūracija\\Politikos\\Administravimo šablonai\\„Microsoft Office 2016“\\Privatumas\\ Patikimumo centras.

Šie nauji strategijos parametrai taip pat bus taikomi „Project“ ir „Visio“ kompiuterio versijoms, kurios įtrauktos į kai kuriuos prenumeratos planuos, pvz., planą „Project Online Professional“ arba „Visio Online“ 2 planą. Jie taip pat taikomi „Office 365 Business“.

Yra ir keletas esamų strategijos parametrų, kurie nebebus taikomi „Office 365 ProPlus“, taip pat keli vartotojo sąsajos (UI) keitimai privatumo parametruose, apie kuriuos turėtumėte žinoti, nes vartotojai gali pastebėti šiuos pakeitimus ir klausti apie juos.

Kaip ir bet kuriuos naujus strategijos parametrus, atidžiai patikrinkite juos apribotoje, kontroliuojamoje aplinkoje, kad prieš įdiegiant platesniam naudojimui savo organizacijoje užtikrintumėte, jog jie turės norimą efektą.

## <a name="policy-setting-for-diagnostic-data"></a>Diagnostikos duomenų strategijos parametrai

Diagnostikos duomenys naudojami siekiant apsaugoti ir naujinti „Office“, aptikti, diagnozuoti ir spręsti problemas, taip pat tobulinti produktus.

Norėdami pasirinkti, kokio dydžio diagnostikos duomenis siunčiami „Microsoft“, galite naudoti strategijos parametro parinktį *Konfigūruoti kliento programinės įrangos diagnostikos duomenų lygį, kuriuos „Office“ siunčia „Microsoft“ tarnybai*.

Jei įgalinsite šį strategijos parametrą, galite pasirinkti, kokio lygio diagnostikos duomenys siunčiami „Microsoft“. Galimos parinktys: būtinieji, pasirinktiniai arba nė vieni.

- ***Būtinieji.*** Minimalūs duomenys, kurie yra būtini, kad programų paketas „Office“ būtų apsaugotas, atnaujintas ir veiktų kaip numatyta įrenginyje, kuriame jis įdiegtas.

- ***Pasirinktiniai.*** Pasirinktinai duomenys, kurie padeda tobulinti produktą ir gauti papildomos informacijos, padedančios aptikti, diagnozuoti ir išspręsti kilusias problemas. Jei pasirinksite siųsti mums pasirinktinius diagnostikos duomenis, būtinieji diagnostikos duomenys taip pat bus įtraukti.

- ***Nė vieni.*** Jokie diagnostikos duomenys apie „Office“ kliento programinę įrangą, įdiegtą vartotojo įrenginyje, nerenkami ir nesiunčiami. „Microsoft“. Tačiau ši parinktis gerokai apriboja „Microsoft“ gebėjimą aptikti, diagnozuoti ir spręsti problemas, kurios gali kilti vartotojams naudojantis „Office“.

Jei išjungsite arba nekonfigūruosite šio strategijos parametro, pasirinktiniai ir būtinieji diagnostikos duomenys bus siunčiami „Microsoft“.

Daugiau informacijos apie diagnostikos duomenis, žr.:

- [„Office 365 ProPlus“ privatumo valdiklių apžvalga](overview-privacy-controls.md)
- [Būtinieji „Office“ diagnostikos duomenys](required-diagnostic-data.md)
- [Pasirinktiniai „Office“ diagnostikos duomenys](optional-diagnostic-data.md)
- [Diagnostikos duomenų peržiūros programos naudojimas su „Office“](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

## <a name="policy-settings-for-connected-experiences"></a>Strategijos parametrai, skirti prisijungus naudojamoms funkcijoms

„Office 365 ProPlus“ sudaro kliento programinės įrangos programos ir prisijungus naudojamos funkcijos, kurios sukurtos, kad galėtumėte kurti, bendrauti ir bendradarbiauti efektyviau. Prisijungus naudojamų funkcijų pavyzdžiai yra „OneDrive“ verslui saugomo dokumento redagavimas su kitais arba „Word“ dokumento turinio vertimas į kitą kalbą.

Suprantame, kad galite norėti pasirinkti, kokių tipų prisijungus naudojamos funkcijos pasiekiamos vartotojams, kai jie dirba „Office“ programose. Taigi, pateikėme jums keturis naujus strategijos parametrus:

- Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios analizuoja turinį
- Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios parsiunčia internetinį turinį
- Leisti „Office“ naudoti pasirinktines, papildomas prisijungus naudojamas funkcijas 
- Leisti „Office" naudoti prisijungus naudojamas funkcijas

Jei nekonfigūruosite šių strategijos parametrų, visos prisijungus naudojamos funkcijos bus pasiekiamos. Tai suteikia jūsų vartotojams visų funkcijų ir funkcionalumo pasiekiamumą per „Office 365 ProPlus“. Tačiau suprantame, kad gali tekti išjungti kai kurias arba visas prisijungus naudojamas funkcijas, kad jos atitiktų tam tikrus jūsų organizacijos reikalavimus.

Jei nuspręsite kai kurių tipų prisijungus naudojamas funkcijas padaryti nepasiekiamas vartotojams, šių funkcijų juostelės arba meniu komandos bus rodoma pilkos arba vartotojai gaus klaidos pranešimą, kai bandys jas naudoti. Tokiu atveju jokie[reikalingi tarnybų duomenys](required-service-data.md)apie prisijungus naudojamas funkcijas nebus siunčiami „Microsoft“.

Vartotojai negalės pasirinkti, ar šios prisijungus naudojamos funkcijos yra įjungtos, ar išjungtos „Office 365 ProPlus“, jei jie prisijungę prie „Office“ naudodami organizacijos kredencialus, kurie kartais vadinami darbo arba mokymo įstaigos paskyra.

### <a name="policy-setting-for-connected-experiences-that-analyze-your-content"></a>Prisijungus naudojamų funkcijų, kurios analizuoja turinį, strategijos parametras

Tai funkcijos, kurios naudodamos „Office“ turinį pateikia dizaino rekomendacijų, redagavimo pasiūlymų, duomenų įžvalgų ir panašių funkcijų. Pavyzdžiui, „PowerPoint“ dizaino įrankis arba „Word“ Redaktorius. Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos naudojant „Office“](connected-experiences.md).

Norėdami kontroliuoti, ar tokių tipų prisijungus naudojamos funkcijos prieinamos vartotojams, galite naudoti strategijos parametrą *Leisti „Office“ naudoti prisijungus naudojamas funkcijas, kurios analizuoja turinį*. Jei nekonfigūruosite šių strategijos parametrų, šios prisijungus naudojamos funkcijos bus pasiekiamos vartotojams.

Pastaba: jei išjungsite strategijos parametrą *Leisti „Office“ naudoti prisijungus naudojamas funkcijas*, šios funkcijos, kurios analizuoja turinį, nebus prieinamos vartotojams.

### <a name="policy-setting-for-connected-experiences-that-download-online-content"></a>Strategijos parametras prisijungus naudojamoms funkcijoms, kurios atsisiunčia internetinį turinį

Tai funkcijos, kurias naudodami galite ieškoti ir atsisiųsti internetinį turinį, įskaitant šablonus, vaizdus, 3D modelius, vaizdo įrašus ir pagalbinę medžiagą, kad patobulintumėte dokumentus. Pavyzdžiui, „Office“ šablonai arba „PowerPoint“ funkcija „QuickStarter“. Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos naudojant „Office“](connected-experiences.md).

Norėdami kontroliuoti, ar tokių tipų prisijungus naudojamos funkcijos prieinamos vartotojams, galite naudoti strategijos parametrą *Leisti „Office“ naudoti prisijungus naudojamas funkcijas, kurios atsisiunčia internetinį turinį*. Jei nekonfigūruosite šių strategijos parametrų, šios prisijungus naudojamos funkcijos bus pasiekiamos vartotojams.

Pastaba: jei išjungsite strategijos parametrą *Leisti „Office“ naudoti prisijungus naudojamas funkcijas*, šios funkcijos, kurios atsisiunčia internetinį turinį, nebus prieinamos vartotojams.

### <a name="policy-setting-for-optional-connected-experiences"></a>Strategijos parametrai pasirinktinėms prisijungus naudojamoms funkcijoms

Be anksčiau minėtų prisijungus naudojamų funkcijų, kurios įtrauktos į „Office 365 ProPlus“, yra pasirinktinių prisijungus naudojamų funkcijų, kurias galite padaryti pasiekiamas vartotojams besinaudojantiems organizacijos paskyra. Pavyzdžiui, „LinkedIn“ CV kūrimo pagalbinės priemonės funkcijos programoje „Word“ arba trimačių žemėlapių funkcija programoje „Excel“, kuri naudoja „Bing“. Daugiau pavyzdžių rasite [Pasirinktinių „Office“ prisijungus naudojamų funkcijų apžvalga](optional-connected-experiences.md).

Šios prisijungus naudojamos funkcijos skiriasi, nes jos neaptariamos jūsų organizacijos komerciniame susitarime su „Microsoft“. Pasirinktinėms prisijungus naudojamoms funkcijoms, kurias „Microsoft“ siūlo tiesiogiai vartotojams, taikoma [„Microsoft“ paslaugų teikimo sutartis](https://www.microsoft.com/servicesagreement), o ne [Internetinių paslaugų teikimo sąlygos](https://www.microsoft.com/licensing/product-licensing/products). Kai kuriais atvejais, per šias pasirinktines prisijungus naudojamas funkcijas teikiamas trečiosios šalies turinys ar funkcionalumas, todėl taip pat gali būti taikomos kitos sąlygos. Daugiau informacijos rasite [Pasirinktinių „Office“ prisijungus naudojamų funkcijų apžvalga](optional-connected-experiences.md).

Norėdami kontroliuoti, ar tokių tipų prisijungus naudojamos funkcijos prieinamos vartotojams, galite naudoti strategijos parametrą *Leisti „Office“ naudoti papildomas pasirinktines prisijungus naudojamas funkcijas*. Jei nekonfigūruosite šio strategijos parametro, šios papildomos pasirinktinės prisijungus naudojamos funkcijos bus pasiekiamos vartotojams.

> [!NOTE]
> Strategijos parametras *Leisti „Office“ naudoti pasirinktines, papildomas prisijungus naudojamas funkcijas* taip pat gali būti konfigūruotas, norint pritaikyti šias internetinės „Office“ programas:
> - internetinę „Excel“;
> - internetinę „OneNote“;
> - „PowerPoint“ žiniatinkliui;
> - internetinę „Visio“;
> - internetinę „Word“.
>
> Norėdami konfigūruoti šį strategijos parametrą minėtoms internetinės „Office“ programoms, turite naudoti [„Office“ debesies strategijos tarnybą](../overview-office-cloud-policy-service.md).

Net jei šias pasirinktines prijungtąsias funkcijas padarysite pasiekiamas vartotojams, jie galės jas išjungti kaip grupę eidami į [privatumo parametrų dialogo langą](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b). Vartotojai turės šį pasirinkimą, tik jei jie bus prisijungę prie „Office“ naudodamiesi organizacijos kredencialais (kartais vadinamais darbo arba mokymo įstaigos paskyra), o ne naudodami savo asmeninį el. pašto adresą.

Be to, kai kurios iš šių pasirinktinių prisijungus naudojamų funkcijų taip pat laikomos pasirinktinai naudojamomis funkcijomis, kurios analizuoja turinį arba atsisiunčia internetinį turinį. Pvz., Internetinių paveikslėlių įterpimas yra pasirinktinė prisijungus naudojama funkcija, kurią teikia „Microsoft Bing“, tačiau ji taip pat laikoma prisijungus naudojama funkcija, kuri atsisiunčia internetinį turinį. Taigi, jei išjungsite strategijos parametrą *Leisti „Office“ naudoti prisijungus naudojamas funkcijas, kurios atsisiunčia internetinį turinį*, strategijos parametras Internetinių paveikslėlių įterpimas nebus pasiekiamas vartotojams. Jis nebus pasiekiamas net jei įjungėte strategijos parametrą *Leisti "Office" naudoti papildomas pasirinktines prisijungus naudojamas funkcijas*. Daugiau informacijos apie tai, kurios prisijungus naudojamos funkcijos analizuoja turinį arba atsisiunčia internetinį turinį, žiūrėkite [Prisijungus naudojamos funkcijos „Office“](connected-experiences.md).

Atkreipkite dėmesį, kad yra viena išimtis: Strategijos parametru *Leisti naudoti papildomas pasirinktines prisijungus naudojamas funkcijas „Office“* nevaldomos funkcijos, kurias naudojant jums reikia susieti savo „LinkedIn“ paskyrą su „Microsoft“ darbo arba mokymo įstaigos paskyra. Informacijos apie šių tipų funkcijų valdymą (pvz., „LinkedIn“ informacijos rodymą „Outlook“ [profilio kortelėje](https://support.office.com/article/365-e80f931f-5fc4-4a59-ba6e-c1e35a85b501)) žr. [„LinkedIn“ ir „Microsoft“ paskyrų susiejimas](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381) ir [Sutikimas „LinkedIn“ paskyrų prijungimui prie „Azure Active Directory“ organizacijų](https://docs.microsoft.com/azure/active-directory/users-groups-roles/linkedin-integration).

### <a name="policy-setting-for-most-connected-experiences"></a>Strategijos parametras daugumai prisijungus naudojamoms funkcijoms

Norėdami kontroliuoti, ar tokių tipų prisijungus naudojamos funkcijos prieinamos vartotojams per „Office 365 ProPlus“, galite naudoti strategijos parametrą *Leisti „Office“ naudoti prisijungus naudojamas funkcijas*. Jei išjungsite strategijos parametrą, šių tipų prisijungus naudojamos funkcijos nebus pasiekiamos vartotojams:

- Funkcijos, kurios analizuoja turinį
- Funkcijos, kurios atsisiunčia internetinį turinį
- Pasirinktinės prisijungus naudojamos funkcijos

Be to, jei išjungsite šį strategijos parametrą, dauguma kitų prisijungus naudojamų funkcijų taip pat išjungiamos, pvz., redagavimas vienu metu ir failų saugykla internete. Išsamesnį prisijungus naudojamų funkcijų sąrašą žr. [Prisijungus naudojamos funkcijos „Office“](connected-experiences.md).

Net jei išjungsite šį strategijos parametrą, kai kurios „Office“ funkcijos ir toliau veiks, pvz., bus sinchronizuojama jūsų „Outlook“ pašto dėžutė ir veiks „Teams“ bei „Skype verslui“. [Pagrindinės paslaugos](essential-services.md), pvz., licencijavimo tarnyba, kuri patvirtina, kad turite tinkamą licenciją naudoti „Office“, taip pat veiks.

## <a name="existing-policy-settings-that-are-replaced-by-new-policy-settings"></a>Esami strategijos parametrai, kurie pakeičiami naujais strategijos parametrais

Yra du esami strategijos parametrai, kurie nebebus taikomi „Office 365 ProPlus“, pradedant nuo 1904 versijos. Tai yra šie strategijos parametrai:

- **Siųsti asmeninę informaciją**, kurią galite rasti Vartotojo konfigūracija\\Strategijos\\Administravimo šablonai\\“Microsoft Office 2016“\\Privatumas\\Patikimumo centras.

- **Interneto turinio parinktys**, kurias galite rasti Vartotojo konfigūracija\\Strategijos\\Administravimo šablonai\\„Microsoft Office 2016“\\Įrankiai | Funkcijos | Bendra | Tarnybos pasirinkimai \\Internetinis turinys.

Pradedant nuo 1904 versijos, šių dviejų esamų strategijos parametrų konfigūravimas neturės poveikio „Office 365 ProPlus“. Jie nebebus taikomi, nes jų funkcijos keičiamos šiais naujais strategijos parametrais:

- Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios analizuoja turinį
- Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios parsiunčia internetinį turinį
- Leisti „Office“ naudoti pasirinktines, papildomas prisijungus naudojamas funkcijas 
- Leisti „Office" naudoti prisijungus naudojamas funkcijas

Šie nauji strategijos parametrai suteiks tikslesnį kontrolės lygį nei du jau esami strategijos parametrai. Pvz., anksčiau, jei naudojote strategijos parametrą*Siųsti asmeninę informaciją*, „PowerPoint“ funkcija „QuickStarter“ ir išmanioji ieška bus išjungta. Tačiau dabar, su naujais strategijos parametrais naudojant strategijos parametrą*Leisti „Office“ naudoti prisijungus naudojamas funkcijas, kurios analizuoja turinį*,norint išjungti šio tipo funkcijas, išjungiama tik išmanioji ieška. „PowerPoint“ funkcija „QuickStarter“ vis tiek bus pasiekiama vartotojams.

Strategijos parametrai vis tiek rodomi įrankyje Grupės strategijos valdymas, nes jie vis tiek taikomi bendrojo licencijavimo versijose „Office 2016“ ir „Office 2019“, pvz., „Office Professional Plus 2019“.

## <a name="what-about-existing-policy-settings-that-control-connected-experiences"></a>O kaip dėl esamų strategijos parametrų, kurie kontroliuoja prisijungus naudojamas funkcijas?

Kaip jūs tikriausiai jau žinote, šiuo metu kai kurie esamos strategijos parametrai leidžia jums kontroliuoti prisijungus naudojamas funkcijas. Toliau pateikiami keli esamų strategijos parametrų pavyzdžiai:

- *„PowerPoint“ dizaino įrankio parinktys*, kurias galite rasti Vartotojo konfigūracija\\Strategijos\\Administravimo šablonai\\„Microsoft Office 2016“\\Įrankiai | Funkcijos | Bendra | Tarnybos pasirinkimai... \\„PowerPoint“ dizaino įrankis.

- *Išjungti „QuickStarter“* eikite į Vartotojo konfigūracija\\Strategijos\\Administravimo šablonai\\„Microsoft“ „PowerPoint 2016“\\„PowerPoint“ parinktys\\Bendra

- *Leisti „LinkedIn“ funkciją CV kūrimo pagalbinė priemonė*, eikite į Vartotojo konfigūracija\\Strategijos\\Administravimo šablonai\\„Microsoft Word 2016“\\„Word“ parinktys\\Bendra

 Norėdami išjungti atskiras prisijungus naudojamas funkcijas, vis dar galite naudoti šiuos esamus strategijos parametrus. Tačiau atminkite, kad jei naudojate vieną iš naujos strategijos parametrų, jis gali išjungti prisijungus naudojamą funkciją, kurią įjungėte naudodami kitą strategijos parametrą. Pvz., jei įjungiate strategijos parametrą*Leisti „LinkedIn“ funkciją CV kūrimo pagalbinė priemonė*, bet išjungiate strategijos parametrą*Leisti „Office“ naudoti prisijungus naudojamas funkcijas*, „LinkedIn“ funkcija CV kūrimo pagalbinė priemonė bus nepasiekiama vartotojams.

Paprastai, kai vienas strategijos parametrų sukonfigūruotas įjungti konkrečią prisijungus naudojamą funkciją, kai tuo pačiu metu kitas strategijos parametras sukonfigūruotas išjungti šio tipo funkciją, tada ta konkreti funkcija vartotojams išjungiama.

## <a name="privacy-related-changes-to-the-office-ui"></a>Privatumo pakeitimai „Office“ vartotojo sąsajai

„Office 365 ProPlus“ vartotojo sąsaja turi keletą pakeitimų, susijusių su privatumu, kuriuos vartotojai gali pastebėti ir apie juos klausti. Šie pakeitimai yra naujų privatumo kontrolės mechanizmų ir strategijos parametrų, pradedamų taikyti nuo 1904 versijos, tiesioginis rezultatas.

### <a name="dialog-about-optional-connected-experiences"></a>Dialogo langas apie pasirinktines prisijungus naudojamas funkcijas

Jei pasirinkote teikti vartotojams [pasirinktines prisijungus naudojamas funkcijas](optional-connected-experiences.md), pirmą kartą vartotojams atidarius „Office“ programą, kuri jau bus atnaujintos 1904 ar vėlesnės versijos, pasirodys informacinis dialogo langas. Šis dialogo langas informuoja vartotojus, kad suteikėte jiems galimybę naudoti šias pasirinktines prisijungus naudojamas funkcijas, ir, kad norėdami pakeisti šį parametrą jie gali eiti į **Failas** > **Paskyra**  >  ** Paskyros privatumas**.

### <a name="privacy-settings-removed-from-the-office-ui"></a>Iš „Office“ vartotojo sąsajos pašalinti privatumo parametrai 

Šie parametrai pašalinti iš: **Failas** > **Funkcijos** > **Patikimumo centras** > **Patikimumo centro parametrai...** > **Privatumo parinktys**:

- Gaukite dizainus, informaciją, rekomendacijas ir paslaugas leisdami „Office“ pasiekti ir tobulinti produktus pagal „Office“ turinį savo įrenginyje.

- Leisti „Office“ prisijungti prie „Microsoft“ internetinių tarnybų, kad būtų galima teikti funkcijas, susijusias su jūsų naudojimu ir nuostatomis.

Be to, pašalinama galimybė įgalinti „Office“ intelektualiąsias paslaugas dalyje**Failas** > **Funkcijos** > **Bendra**.

Kaip jūsų organizacijos administratorius, dabar galite valdyti atitinkamus parametrus naudodami anksčiau minėtus naujos strategijos parametrus.

### <a name="privacy-settings-added-to-the-office-ui"></a>Privatumo parametrai priskirti prie „Office“ vartotojo sąsajos

Toliau pateikiami nauji elementai, priskirti „Office“ vartotojo sąsajai:

- Dalyje**Failas** > **Paskyra**, vartotojai matys naują parinktį **Paskyros privatumas** > **Valdyti nustatymus**. Dalyje **Valdyti nustatymus** vartotojai gali išjungti pasirinktines prisijungus naudojamas funkcijas, jei suteikėte jiems šią galimybę.

- Dalyje**Failas** > **Funkcijos** > **Patikimumo centras** > **Patikimumo centro parametrai...** > **Privatumo parinktys**, yra galimybė įgalinti [Diagnostikos duomenų ieškiklio](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855) naudojimą įrenginyje.

 
## <a name="control-privacy-settings-by-editing-the-registry"></a>Valdykite privatumo parametrus redaguodami registrą

Kai kurie administratoriai pirmenybę teikia parametrų keitimui tiesiogiai registre, pvz., naudodami scenarijų, o ne grupės strategiją arba „Office“ debesies strategijos tarnybą. Norėdami konfigūruoti privatumo parametrus tiesiogiai registre, galite naudoti toliau pateikiamą informaciją.


|**Strategijos parametras** |**Registro parametras**  |**Reikšmės**  |
|---------|---------|---------|---------|
|Kliento programinės įrangos diagnostikos duomenų lygio, „Office“ siunčiamų „Microsoft“ tarnybai, konfigūravimas  | SendTelemetry |1 = privaloma <br/> 2 = pasirenkamas <br/> 3 = nė vienas|
|Leisti „Office" naudoti prisijungus naudojamas funkcijas, analizuojančias turinį  | UserContentDisabled | 1 = įjungta <br/> 2 = išjungta|
|Leisti „Office" naudoti prisijungus naudojamas funkcijas, kurios parsiunčia internetinį turinį  | DownloadContentDisabled | 1 = įjungta <br/> 2 = išjungta|
|Leisti „Office“ naudoti pasirinktines, papildomas prisijungus naudojamas funkcijas    | ControllerConnectedServicesEnabled  |1 = įjungta <br/> 2 = išjungta|
|Leisti „Office" naudoti prisijungus naudojamas funkcijas | DisconnectedState  | 1 = įjungta <br/> 2 = išjungta|

Norėdami sukurti .reg failą privatumo parametruose, atidarykite užrašinę ir nukopijuokite toliau nurodytas eilutes. Koreguokite reikšmes, kad atitiktų jūsų poreikius, tada įrašykite failą. Įsitikinkite, kad failo vardas turi plėtinį .reg

```
Windows Registry Editor Version 5.00

[HKEY_CURRENT_USER\Software\Policies\Microsoft\office\16.0\common\privacy]
"disconnectedstate"=dword:00000001
"usercontentdisabled"=dword:00000001
"downloadcontentdisabled"=dword:00000001
"controllerconnectedservicesenabled"=dword:00000001

[HKEY_CURRENT_USER\Software\Policies\Microsoft\office\common\clienttelemetry]
"sendtelemetry"=dword:00000002
```

Pavyzdžiui, scenarijuje galite naudoti šį .reg failą su komanda regedit.exe konfigūruoti vartotojo privatumo parametrus.