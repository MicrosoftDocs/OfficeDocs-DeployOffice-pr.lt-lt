---
title: Pasirinktiniai „Office“ diagnostikos duomenys
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Suteikia „Office“ administratoriams informacijos apie pasirinktinius duomenis naudojant „Office“, įskaitant keletą įvykių pavyzdžių.
hideEdit: true
ms.openlocfilehash: 0190c29a017b35d945e6a1d540e1560dfab47a4c
ms.sourcegitcommit: 3890a23390edd0b5fdb2cf33613ec0778566cf97
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 05/01/2020
ms.locfileid: "43993135"
---
# <a name="optional-diagnostic-data-for-office"></a>Pasirinktiniai „Office“ diagnostikos duomenys

> [!IMPORTANT]
> Šiame straipsnyje pateikta informacija taikoma 1904 arba naujesnės versijos „Office“ kliento programinei įrangai, įdiegtai „Windows“ kompiuteryje:
> - „Microsoft 365“ programos įmonėms (anksčiau vadintos „Office 365 ProPlus“)
> - „Microsoft 365“ programos verslui (anksčiau vadintos „Office 365 Business“)
> - „Microsoft 365 Personal“, „Microsoft 365 Family“ ar kitoms „Office“ versijoms, kurios yra „Microsoft 365“ prenumeratos dalis.
> - „Project“ ir „Visio“ kompiuterio taikomosioms programoms, pateikiamoms su kai kuriais prenumeratų planais, pvz., „Project“ 5 planas arba „Visio“ 2 planas.
>
> Ši informacija taip pat taikoma „Office“, skirto „Mac“ (16,28 arba vėlesnės versijos) programoms: „Excel“, „Outlook“, „OneNote“, „PowerPoint“ ir „Word“.

Diagnostikos duomenys naudojami siekiant apsaugoti ir naujinti „Office“, aptikti, diagnozuoti ir taisyti problemas, taip pat tobulinti produktus. Šie duomenys neapima vartotojo vardo ar el. pašto adreso, vartotojo failų turinio ar informacijos apie programas, nesusijusias su „Office“.

Šie diagnostikos duomenys, susiję su „Office“ kliento programine įranga, naudojama kompiuteriuose, kuriuose įdiegta operacinė sistema „Windows“, renkami ir siunčiami „Microsoft“. Kai kurie diagnostikos duomenys yra privalomi, o kiti – pasirinktiniai. Suteikiame jums galimybę pasirinkti, ar siųsti mums privalomuosius, ar pasirinktinius diagnostikos duomenis naudojant privatumo valdiklius, pvz., organizacijoms skirtus strategijos parametrus. Naudodami diagnostikos duomenų peržiūros programą galite matyti mums siunčiamus diagnostikos duomenis.

***Pasirinktiniai diagnostikos duomenys*** yra papildomi duomenys, kurie padeda mums tobulinti produktą ir gauti papildomos informacijos, padedančios aptikti, diagnozuoti ir ištaisyti kilusias problemas.

Jei pasirinksite siųsti mums pasirinktinius diagnostikos duomenis, būtinieji diagnostikos duomenys taip pat bus įtraukti.

Pasirinktinių diagnostikos duomenų pavyzdžiai yra duomenys, kuriuos renkame apie figūras, kurias vartotojai įterpia į „Word“ dokumentus, kad galėtume teikti geresnes parinktis, bei duomenys, kuriuos renkame apie tai, per kiek laiko „PowerPoint“ skaidrė pasirodo jūsų ekrane, kad galėtume pagerinti veikimą, jei jis lėtas.

Daugiau informacijos apie diagnostikos duomenis, žr.:

- [Privalomieji „Office“ diagnostikos duomenys](required-diagnostic-data.md)
- [Diagnostikos duomenų peržiūros programos naudojimas su „Office“](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

Jei esate organizacijos administratorius, galbūt jus domina šios temos:

- [„Microsoft 365“ programų įmonėms privatumo kontrolės apžvalga](overview-privacy-controls.md)
- [„Microsoft 365“ programos įmonėms privatumo valdiklių valdymas naudojant strategijos parametrus](manage-privacy-controls.md)
- [„Office“, skirto „Mac“, privatumo valdiklių valdymas, naudojant nuostatas](mac-privacy-preferences.md)
- [„Office“ privatumo valdiklių valdymas „iOS“ įrenginiuose naudojant nuostatas](ios-privacy-preferences.md)
- [„Office“ privatumo valdiklių valdymas „Android“ įrenginiuose naudojant strategijos parametrus](android-privacy-controls.md)

## <a name="categories-of-optional-diagnostic-data"></a>Pasirinktinių diagnostikos duomenų kategorijos

Pasirinktinai diagnostikos duomenys skirstomi į šias kategorijas:

- turima programinė įranga ir jos sąranka
- produktų ir tarnybų naudojimas
- produktų ir tarnybų našumas
- įrenginio ryšiai ir konfigūracija

Šios kategorijos rodomos diagnostikos duomenų peržiūros programoje ir yra tokios pačios, kaip kategorijos, taikomomis privalomiesiems diagnostikos duomenims.

Toliau esančiose sekcijose pateikiamas kiekvienos kategorijos aprašas ir kiekvienos kategorijos įvykių pavyzdžiai.

## <a name="software-setup-and-inventory-events"></a>Su turima programine įranga ir jos sąranka susiję įvykiai

Į šią kategoriją gali būti įtraukti šių sričių įvykiai:

- Įdiegtas produktas ir versija bei diegimo būsena
- Programinės įrangos papildiniai ir jų parametrai.
- Dokumento, funkcijos ir papildinio sąlygos, kurios gali pažeisti saugą, įskaitant produkto parengimą naujinti.

Šioje lentelėje pateikiami šios kategorijos įvykių pavyzdžiai ir šių įvykių aprašymas.

| **Įvykio pavadinimas**   | **Įvykio aprašas**  |
| ---- | ---- |
| Office.Extensibility.AppCommands.GetRibbonUpdatesForUserId | Šis įvykis nurodo, ar „Word“ sėkmingai atnaujina juostelę „Word“ vartotojo sąsajoje, kai vartotojas pakeičia savo tapatybę. Šį įvykį naudojame siekdami aptikti neteisingą sąranką ir kitas problemas, kurios gali turėti įtakos „Office“ vartotojo sąsajai. |
| Office.Extensibility.AppCommands.AppCmdInstall   | Šis įvykis suteikia informacijos apie vartotojo įdiegtą „Office“ papildinį, įskaitant programos ID, operacinės sistemos versiją ir komponavimo versiją, informaciją, ar diegimas pavyko, ir diegimo trukmę.  |

## <a name="product-and-service-usage-events"></a>Su produktų ir tarnybų naudojimu susiję įvykiai

Į šią kategoriją gali būti įtraukti šių sričių įvykiai:

- Informacija apie tai, ar sėkmingai veikia programos funkcijos. Tik programos ir dokumentų atidarymas ir uždarymas, failų redagavimas ir failų bendrinimas (bendradarbiavimas).
- Nustatymas, ar įvyko specifiniai funkcijų įvykiai, pvz., paleidimas ar sustabdymas, ir ar funkcija veikia.
- „Office“ pritaikymo neįgaliesiems funkcijos

Šioje lentelėje pateikiami šios kategorijos įvykių pavyzdžiai ir šių įvykių aprašymas.

| **Įvykio pavadinimas**   | **Įvykio aprašas**  |
| ------ | ------- |
| Office.Word.Commanding.Highlight  | Šis įvykis nurodo, kad „Word“ įvykdė teksto paryškinimo komandą. Naudojame šį įvykį, kad aptiktume klaidas teksto paryškinimo komandoje.  |
| Office.Translator.AddInLoaded   | Kontrolinis signalas, nurodantis, kad vertyklės funkcija įkelta ir sėkmingai pateikta.  |
| Office.Graphics.GVizInsertShape |Seka, ar figūros įterpimo funkcija pavyko programoje „Word“, bei praneša informaciją apie įterptų figūrų tipus ir šaltinį.| 
| Office.PowerPoint.PPT.Desktop.SummaryZoomInsertionRule   | Šis įvykis nustato, ar dokumente yra sekcijų, kai vartotojas įterpia interaktyviąją suvestinės peržiūrą, ir ar vartotojas pasirenka panaikinti esamas sekcijas. |
| Office.Security.SecureReaderHost.ProtectedViewValidation | Seka, kada ir kodėl failas atidaromas apsaugotame rodinyje. Naudojama tam, kad būtų galima diagnozuoti sąlygas, kai apsaugotas rodinys gali būti netinkamai suaktyvintas, siekiant užtikrinti, kad funkcija veiktų tinkamai. |

## <a name="product-and-service-performance-events"></a>Su produktų ir tarnybų našumu susiję įvykiai

Į šią kategoriją gali būti įtraukti šių sričių įvykiai:

- Nenumatytas programų uždarymas (užstrigimas) ir programos būsena, kai taip nutinka.
- Prastas atsakymo laikas ar našumas vykdant scenarijus, tokius kaip programos paleidimas ar failo atidarymas.
- Funkcijos ar vartotojo patirties veikimo klaidos.

Šioje lentelėje pateikiami šios kategorijos įvykių pavyzdžiai ir šių įvykių aprašymas.

| **Įvykio pavadinimas**    | **Įvykio aprašas**   |
| --------------- | -------------- |
| Office.Word.Word.CoreSaveTime100ns     | Šis įvykis užfiksuoja „Word“ dokumento įrašymo veiksmo našumą. Šį įvykį naudojame siekdami aptikti „Word“ dokumento įrašymo veiksmų klaidas ir našumo problemas.|
| Office.Identity.SignInForWamAccountAad  | Šis įvykis siunčiamas, kai vartotojas yra prisijungęs prie „Azure Active Directory“ paskyros naudodamas žiniatinklio paskyrų tvarkytuvo (WAM) biblioteką. Jei šis įvykis nepavyko, jis siunčia metaduomenis, tokius kaip AppName, AppVersion ir ErrorCode. |
| Office.PowerPoint.PPT.Desktop.FileOpen.FirstSlideMasterThumbnailRenderTime | Šis įvykis fiksuoja, kiek laiko trunka atvaizduoti pirmąją „PowerPoint“ skaidrių ruošinio miniatiūrą.  |
| Office.Extensibility.Diagnostics   | Šis įvykis suteikia bendrą „Office“ papildinių diagnostikos informaciją, tokią kaip derinimui skirtos gedimų ataskaitos.|

## <a name="device-connectivity-and-configuration-events"></a>Su įrenginio ryšiais ir konfigūracija susiję duomenys

Į šią kategoriją gali būti įtraukti šių sričių įvykiai:

- Tinklo ryšio būsena ir įrenginio parametrai, tokie kaip atmintis.

Šioje lentelėje pateikiami šios kategorijos įvykių pavyzdžiai ir šių įvykių aprašymas.

| **Įvykio pavadinimas**                    | **Įvykio aprašas**                                                                                                                                                     |
| ------ | ----- |
| Office.Graphics.ArtViewValidate | Šis įvykis fiksuoja grafinių elementų rodinio, kuris palaiko grafinę sąsają, rezultatų tikrinimą. Įvykį naudojame, kad galėtume rinkti naudojimo ir klaidų duomenis apie grafinių elementų atvaizdavimą. |
| Office.Graphics.ARCExceptionScope | Šis įvykis seka atvaizdavimo triktis, vykstančias atvaizdavimo modulyje. |
| Office.Extensibility.ODPLatency   | Šis įvykis suteikia informacijos apie vartotojo tinklo ryšį ir greitį.     |
