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
description: Suteikia „Office“ administratoriams informacijos apie pasirinktinius diagnostikos duomenis naudojant „Office“, įskaitant keletą įvykių pavyzdžių.
hideEdit: true
ms.openlocfilehash: bcb9a8d4a886fefde3fbb42280183bf163b315c3
ms.sourcegitcommit: 596a0a60394011aafe1119f353ac76f27e1a4d1b
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 10/29/2020
ms.locfileid: "48794809"
---
# <a name="optional-diagnostic-data-for-office"></a>Pasirinktiniai „Office“ diagnostikos duomenys

> [!NOTE]
> „Office“ produktų, kuriems taikoma ši privatumo informacija, sąrašas, žr. [Galimi „Office“ produktų privatumo valdikliai](products-versions-privacy-controls.md).

Diagnostikos duomenys naudojami siekiant apsaugoti ir naujinti „Office“, aptikti, diagnozuoti ir taisyti problemas, taip pat tobulinti produktus. Šie duomenys neapima vartotojo vardo ar el. pašto adreso, vartotojo failų turinio ar informacijos apie programas, nesusijusias su „Office“.

Šie diagnostikos duomenys renkami ir siunčiami „Microsoft“ apie „Office“ kliento programinę įrangą, veikiančią vartotojo įrenginyje. Kai kurie diagnostikos duomenys yra privalomi, o kiti – pasirinktiniai. Suteikiame jums galimybę pasirinkti, ar siųsti mums privalomuosius, ar pasirinktinius diagnostikos duomenis naudojant privatumo valdiklius, pvz., organizacijoms skirtus strategijos parametrus. Naudodami diagnostikos duomenų peržiūros programą galite matyti mums siunčiamus diagnostikos duomenis.

***Pasirinktiniai diagnostikos duomenys** _ yra papildomi duomenys, kurie padeda mums tobulinti produktą ir gauti papildomos informacijos, padedančios aptikti, diagnozuoti ir ištaisyti kilusias problemas.

Jei pasirinksite siųsti mums pasirinktinius diagnostikos duomenis, būtinieji diagnostikos duomenys taip pat bus įtraukti. Taip pat gali būti siunčiami „Office“ diagnostikos žurnalo failai, kuriuose yra informacijos, labai panašios į pasirinktinius diagnostikos duomenis. Daugiau informacijos apie šiuos žurnalo failus žr. [„Office“ diagnostinių žurnalų failų apžvalga](https://support.microsoft.com/office/fba86aac-70dc-4858-ae1f-ec2034346cdf).

Pasirinktinių diagnostikos duomenų pavyzdžiai yra duomenys, kuriuos renkame apie figūras, kurias vartotojai įterpia į „Word“ dokumentus, kad galėtume teikti geresnes parinktis, bei duomenys, kuriuos renkame apie tai, per kiek laiko „PowerPoint“ skaidrė pasirodo jūsų ekrane, kad galėtume pagerinti veikimą, jei jis lėtas.

Daugiau informacijos apie diagnostikos duomenis, žr. straipsniuose:

- [Privalomieji „Office“ diagnostikos duomenys](required-diagnostic-data.md)
- [Diagnostikos duomenų peržiūros programos naudojimas su „Office“](https://support.microsoft.com/office/cf761ce9-d805-4c60-a339-4e07f3182855)

Jei esate organizacijos administratorius, galbūt jus domina šie straipsniai:

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

| _ *Įvykio pavadinimas**   | **Įvykio aprašas**  |
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
