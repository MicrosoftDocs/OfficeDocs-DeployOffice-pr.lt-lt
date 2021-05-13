---
title: Būtinieji „Office“ diagnostikos duomenys
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
description: „Office“ administratoriams suteikia informaciją apie būtinuosius „Office“ diagnostikos duomenis ir pateikia įvykių ir duomenų laukų sąrašą.
hideEdit: true
ms.openlocfilehash: c61c3072c4c0f61926b51c0fab5e46a1b5151e00
ms.sourcegitcommit: 2796ba69444926d686e7ed587a89d8ee9e313d84
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 05/11/2021
ms.locfileid: "52328431"
---
# <a name="required-diagnostic-data-for-office"></a>Būtinieji „Office“ diagnostikos duomenys

> [!NOTE]
> „Office“ produktų, kuriems taikoma ši privatumo informacija, sąrašas, žr. [Galimi „Office“ produktų privatumo valdikliai](products-versions-privacy-controls.md).

Diagnostikos duomenys naudojami siekiant apsaugoti ir naujinti „Office“, aptikti, diagnozuoti ir taisyti problemas, taip pat tobulinti produktus. Šie duomenys neapima vartotojo vardo ar el. pašto adreso, vartotojo failų turinio ar informacijos apie programas, nesusijusias su „Office“.

Šie diagnostikos duomenys renkami ir siunčiami „Microsoft“ apie „Office“ kliento programinę įrangą, veikiančią vartotojo įrenginyje. Kai kurie diagnostikos duomenys yra privalomi, o kiti – pasirinktiniai. Suteikiame jums galimybę pasirinkti, ar siųsti mums privalomuosius, ar pasirinktinius diagnostikos duomenis naudojant privatumo valdiklius, pvz., organizacijoms skirtus strategijos parametrus. Naudodami diagnostikos duomenų peržiūros programą galite matyti mums siunčiamus diagnostikos duomenis.

***Būtinieji diagnostikos duomenys*** yra minimalūs duomenys, kurie yra būtini, kad programų paketas „Office“ būtų apsaugotas, atnaujintas ir veiktų kaip numatyta įrenginyje, kuriame jis įdiegtas.

Būtinieji diagnostikos duomenys padeda nustatyti „Office“ problemas, kurios gali būti susiję su įrenginiu arba programinės įrangos konfigūracija. Pavyzdžiui, jie gali padėti nustatyti, ar programos „Office“ funkcija sugenda dažniau konkrečioje operacinės sistemos versijos su naujai įdiegtomis funkcijomis, ar išjungus tam tikras „Office“ funkcijas. Būtini diagnostikos duomenys padeda aptikti, nustatyti ir išspręsti šias problemas greičiau, kad būtų sumažintas poveikis vartotojams arba organizacijoms.

Daugiau informacijos apie diagnostikos duomenis, žr. straipsniuose:

- [Pasirinktiniai „Office“ diagnostikos duomenys](optional-diagnostic-data.md)
- [Diagnostikos duomenų peržiūros programos naudojimas su „Office“](https://support.microsoft.com/office/cf761ce9-d805-4c60-a339-4e07f3182855)

Jei esate organizacijos administratorius, galbūt jus domina šie straipsniai:

- [„Microsoft 365“ programų įmonėms privatumo kontrolės apžvalga](overview-privacy-controls.md)
- [„Microsoft 365“ programos įmonėms privatumo valdiklių valdymas naudojant strategijos parametrus](manage-privacy-controls.md)
- [„Office“, skirto „Mac“, privatumo valdiklių valdymas, naudojant nuostatas](mac-privacy-preferences.md)
- [„Office“ privatumo valdiklių valdymas „iOS“ įrenginiuose naudojant nuostatas](ios-privacy-preferences.md)
- [„Office“ privatumo valdiklių valdymas „Android“ įrenginiuose naudojant strategijos parametrus](android-privacy-controls.md)

## <a name="categories-data-subtypes-events-and-data-fields-for-required-diagnostic-data"></a>Būtinų diagnostikos duomenų kategorijos, duomenų porūšiai, įvykiai ir duomenų laukai

Būtini diagnostikos duomenys suskirstyti į kategorijas ir duomenų potipius. Su kiekvienu duomenų potipiu yra įvykiai, turintys duomenų laukus, konkrečius tam įvykiui.

Šioje lentelėje pateikiamas būtinų diagnostikos duomenų kategorijų sąrašas. Kiekvienoje kategorijoje pateikiami duomenų potipiai, kartu su tų duomenų potipio tikslo aprašymu. Yra nuorodos į kiekvieną duomenų potipio skyrių, kuriame rasite šią informaciją:

- To duomenų potipio įvykių sąrašas
- Kiekvieno įvykio aprašas
- Kiekvieno įvykio duomenų laukų sąrašas
- Kiekvieno duomenų lauko aprašas

| **Kategorija**       | **Duomenų potipis**| **Aprašas**    |
| ---------- | ------------- | ---- |
| **Programinės įrangos sąranka ir inventorius** | [„Office“ sąranka ir inventorius](#office-setup-and-inventory-subtype)   | Įdiegtas produktas ir versija, bei diegimo būsena.  |
| | [„Office“ papildinio konfigūracija](#office-add-in-configuration-subtype)  | Programinės įrangos papildiniai ir jų parametrai.     |
| | [Sauga](#security-subtype)  | Dokumento, funkcijos ir papildinio sąlygos, kurios gali pažeisti saugą, įskaitant produkto parengimą naujinti.  |
| **Produktų ir tarnybų naudojimas**    | [Taikomosios programos funkcijų sėkmingas atlikimas](#application-feature-success-subtype)   | Sėkmingos taikomosios programos funkcijos. Tik taikomosios programos ir dokumentų atidarymas ir uždarymas, failų redagavimas ir failų bendrinimas (bendradarbiavimas). |
| | [Taikomosios programos būsena ir įkrova](#application-status-and-boot-subtype)    | Nustatymas, ar įvyko specifiniai funkcijų įvykiai, pvz., paleidimas ar sustabdymas, ir ar funkcija veikia.   |
| | [„Office“ pritaikymo neįgaliesiems konfigūracija](#office-accessibility-configuration-subtype)  | „Office“ pritaikymo neįgaliesiems funkcijos       |
| | [Privatumas](#privacy-subtype)| „Office“ privatumo parametrai|
| **Produktų ir tarnybų veikimas**       | [Netikėtas taikomosios programos uždarymas (gedimas)](#unexpected-application-exit-crash-subtype)  | Nenumatytas programų uždarymas ir programos būsena, kai taip nutinka.    |
|  | [Taikomosios programos funkcijų veikimas](#application-feature-performance-subtype)  | Prastas scenarijų, pvz., programos paleidimo ar failo atidarymo, atsako laikas ar veikimas. |
|  | [Taikomosios programos veiklos klaida](#application-activity-error-subtype)   | Funkcijos ar vartotojo patirties veikimo klaidos.  |
| **Įrenginių jungiamumas ir konfigūracija** | [Įrenginių jungiamumas ir konfigūracija](#device-connectivity-and-configuration-subtype) | Tinklo ryšio būsena ir įrenginio parametrai, tokie kaip atmintis. |


> [!NOTE]
> - Kategorijos pateikiamos Diagnostikos duomenų peržiūros programoje, tačiau duomenų porūšiai nerodomi.
> - Duomenų lauke, pažymėtame *Nebenaudojami*, buvo arba netrukus bus pašalinti iš būtinų diagnostikos duomenų. Kai kurie iš šių duomenų laukų dubliuojasi. Tai įvyko dėl diagnostikos duomenų modernizavimo ir naudojimo siekiant užtikrinti, kad nebūtų nutraukta tiesioginių diagnostikos stebėjimo ataskaitų teikimo paslauga.

## <a name="categories-and-data-fields-that-are-common-for-all-events"></a>Kategorijos ir duomenų laukai, įprasti visiems įvykiams

Pateikiama tam tikra informacija apie įvykius, bendrus visiems įvykiams, neatsižvelgiant į kategoriją arba duomenų potipį. Ši bendra informacija, kuri yra kartais vadinama *duomenų sutartimis*, yra suskirstyti į kategorijas. Kiekvienoje kategorijoje yra laukai, ir šie laukai yra atskiro įvykio metaduomenys ir ypatybės. Šią informaciją galite matyti naudodami Diagnostikos duomenų peržiūros programą.

Apie įvykį surinktas informacijos kategorijas galima suskirstyti į dvi grupes:

  - [Visiems įvykiams bendra informacija](#information-common-to-all-events)
  - [Specialiai diagnostikos duomenų rinkimą palaikanti diagnostikos informacija](#information-that-specifically-supports-diagnostic-data-collection)

### <a name="information-common-to-all-events"></a>*Visiems įvykiams bendra informacija*

Visiems atvejams bendra informacija renkama į toliau nurodytas kategorijas.

#### <a name="app"></a>Taikomoji programa 

Informacija apie taikomąją programą. Visi laukai pastovūs visiems konkrečios taikomosios programos versijos seansams.

Šioje kategorijoje yra šie laukai:

  - **Branch** – filialas, pateikęs konkrečią komponavimo versiją. Leidžia mums nustatyti iš kokio filialo buvo gauta komponavimo versija, kad galėtume tinkamai pateikti pataisas.
  - **InstallType** – surašytuvas, nurodantis kaip vartotojas įdiegė taikomąją programą. Leidžia mums nustatyti, ar konkretūs diegimo mechanizmai kuria problemas, nematomas kituose diegimo mechanizmuose.
  - **Name** – duomenis pateikiančios taikomosios programos pavadinimas. Leidžia mums nustatyti, kuri taikomoji programa nurodo problemą, todėl žinome, kaip ją šalinti.
  - **Platform** – plati platformos, kurioje taikomoji programa veikia, klasifikacija. Leidžia mums nustatyti kurioje platformose problema gali kilti, kad galėtume tinkamai nustatyti problemos prioritetą.
  - **Version** – taikomosios programos versiją. Leidžia mums nustatyti kurios produkto versijos rodo problemą, kad galėtume tinkamai nustatyti jos prioritetą.

#### <a name="client"></a>Klientas 

Identifikatorius, susijęs su įrenginyje įdiegtu „Office“ egzemplioriumi. Pateiktos diegimo versijos, skirtos keliems taikomųjų programų paketams, visų taikomųjų programų seansų arba pateiktos taikomosios programos versijos seansų metu išlieka tokie patys.

Šioje kategorijoje yra šie laukai:

  - **Id** – unikalus identifikatorius, priskirtas klientui „Office“ diegimo metu. Leidžia mums nustatyti, ar problema daro poveikį pasirinktam diegimų rinkiniui ir keliems vartotojams yra daroma įtaka.

#### <a name="consent"></a>Sutikimas

Informacija apie vartotojų sutikimą dėl diagnostikos duomenų ir prisijungus naudojamų funkcijų.

Šioje kategorijoje yra šie laukai:

  - **ControllerConnectedServicesSourceLocation** – nurodo, kaip vartotojas pasirinko pasirinktines prisijungus naudojamas funkcijas

  - **ControllerConnectedServicesState** – nurodo, ar vartotojas turi prieigą prie pasirinktinių prisijungus naudojamų funkcijų

  - **ControllerConnectedServicesStateConsentTime** – nurodo, kada vartotojas pasirinko pasirinktinių prisijungus naudojamų funkcijų būseną. Data bus rodoma kaip žmonėms skirta data arba mašininio šifravimo data, kuri atrodo kaip didelis skaičius.

  - **DiagnosticConsentConsentTime** – nurodo, kada vartotojas pateikė sutikimą dėl diagnostikos duomenų. Data bus rodoma kaip žmonėms skirta data arba mašininio šifravimo data, kuri atrodo kaip didelis skaičius.

  - **DiagnosticConsentLevel** – nurodo, kokiam diagnostikos duomenų lygiui vartotojas davė sutikimą

  - **DiagnosticConsentLevelSourceLocation** – nurodo, kaip vartotojas pateikė sutikimą dėl diagnostikos duomenų

  - **DownloadContentSourceLocation** – nurodo, kaip vartotojas pasirinko prijungus naudojamų funkcijų, atsisiunčiančių internetinį turinį, įjungimą arba išjungimą

  - **DownloadContentState** – nurodo, ar vartotojas pasirinko įjungti prijungus naudojamas funkcijas, atsisiunčiančias internetinį turinį

  - **DownloadContentStateConsentTime** – nurodo, kada vartotojas pasirinko prijungus naudojamų funkcijų, atsisiunčiančių internetinį turinį, įjungimą arba išjungimą. Data bus rodoma kaip žmonėms skirta data arba mašininio šifravimo data, kuri atrodo kaip didelis skaičius.

  - **ServiceConnectionState** – nurodo, ar vartotojas pasirinko naudoti visas prisijungus naudojamas funkcijas

  - **ServiceConnectionStateConsentTime** – nurodo, kada vartotojas pasirinko, ar naudoti visas prisijungus naudojamas funkcijas. Data bus rodoma kaip žmonėms skirta data arba mašininio šifravimo data, kuri atrodo kaip didelis skaičius.

  - **ServiceConnectionStateSourceLocation** – nurodo, kaip vartotojas pasirinko, ar naudoti visas prisijungus naudojamas funkcijas

  - **UserCategoryValue –** nustatė sutikimą pateikusio vartotojo tipą. Vienas iš MSAUser, AADUser arba LocalDeviceUser

  - **UserContentDependentSourceLocation** – nurodo, kaip vartotojas pasirinko prisijungus naudojamų funkcijų, analizuojančių turinį, įjungimą arba išjungimą

  - **UserContentDependentState** – nurodo, ar vartotojas pasirinko įjungti prijungus naudojamas funkcijas, analizuojančias turinį

  - **UserContentDependentStateConsentTime** – nurodo, kada vartotojas pasirinko prijungus naudojamų funkcijų, analizuojančių turinį, įjungimą arba išjungimą. Data bus rodoma kaip žmonėms skirta data arba mašininio šifravimo data, kuri atrodo kaip didelis skaičius.

#### <a name="device"></a>Įrenginys 

Informacija apie operacinę sistemą ir komponavimo versiją.

Šioje kategorijoje yra šie laukai:

  - **OsBuild** – įrenginyje įdiegtos operacinės sistemos komponavimo versijos numeris. Leidžia mums nustatyti, ar problema skirtingai nuo kitų veikia atskirus pakeitimų paketus arba pateiktos operacinės sistemos versijas, kad galėtume nustatyti problemų prioritetus.

  - **OsVersion** – įrenginyje įdiegtos operacinės sistemos pagrindinė versija. Leidžia mums nustatyti, ar problemos labiau nei kitas veikia konkrečią operacinės sistemos versiją, kad galėtume nustatyti problemų prioritetus.

#### <a name="legacy"></a>Ankstesnės versijos 

Pateikia taikomosios programos ID ir OS versiją, suderinamą su dabartinėmis ankstesnės versijos rinkimo praktikomis.

Šioje kategorijoje yra šie laukai:

  - **AppId** – surašytuvo reikšmė, nurodanti kuri taikomoji programa siunčia duomenis. Leidžia mums nustatyti, kuri taikomoji programa nurodo problemą, todėl žinome, kaip ją šalinti.

  - **OsEnv** – surašytuvas, nurodantis veikiančios operacinės sistemos seansą. Leidžia mums nustatyti, kokiai operacinei sistemai veikiant kyla problema, kad galėtume nustatyti problemų prioritetus.

#### <a name="release"></a>Pateikimas 

Su pateikimo kanalu susijusi Informacija. Visi pateiktos diegimo versijos laukai pastovūs visiems konkretiems taikomųjų programų seansams. Nurodo produkto išleidimo ciklo vienos fazės įrenginių grupę.

Šioje kategorijoje yra šie laukai:

  - **Audience** – nurodo pateiktos auditorijos grupės papildomą auditoriją. Leidžia mums sekti auditorijos grupių poaibius, kad įvertinti problemų paplitimą ir nustatyti prioritetus.

  - **AudienceGroup** – nurodo žiedą, iš kurio gaunami duomenys. Leidžia mums parengti funkcijų apibendrinimą ir nustatyti galimas problemas prieš joms pasiekiant daugelį vartotojų.

  - **Channel** – kanalas, per kurį produktas buvo išleistas. Leidžia mums nustatyti, ar problema veikia vieną iš mūsų išvesties kanalų skirtingai nuo kitų.

  - **Fork** – nurodo produkto šaką. Leidžia mechanizmui duomenis sujungti visame komponavimo versijos numerių rinkinyje, kad nustatyti su pateiktu leidimu susijusias problemas.

#### <a name="session"></a>Seansas 

Informacija apie proceso seansą. Šiam seansui visi laukų reikšmės nesikeičia.

Šioje kategorijoje yra šie laukai:

  - **ABConfigs** – nurodo testuojamų variantų, veikiančių nurodytame seanse, rinkinį. Leidžia mums aptikti, kurie atskiri testuojami variantai veikia seanso metu, kad galėtume nustatyti, ar testuojamas variantas yra problemos šaltinis, veikiantis vartotojus.

  - **EcsETag** – testuojamos sistemos indikatorius, nurodantis testavimo variantus, siųstus į kompiuterį. Leidžia mums nustatyti, kokie testavimo variantai gali veikti nurodytą seansą.

  - **Flags** – žymių sekimo šablonas, taikomas visam seansui, dabartiniu metu orientuotam į pavyzdžių rinkimą ir diagnostikos duomenų parinktis. Leidžia kontroliuoti kaip nurodytas seansas elgiasi seanso generuojamų diagnostikos duomenų atžvilgiu.

  - **HostAppName** – identifikuoja pagrindinės programos, kuri paleidžia antrinę programą, pavadinimą. Programos, pvz., „Office Mobile“ („Android“), gali paleisti „Word“, „Excel“ ir „PowerPoint“ antrines programas. Tokioms antrinėms programoms pagrindinė programa yra „OfficeMobile“

  - **HostSessionId** – unikaliai identifikuoja antrinės programos pagrindinės programos seansą

  - **Id** – unikaliai identifikuoja nurodyto seanso duomenis. Leidžia mums nustatyti problemų poveikį vertinant veikiamų seansų skaičių ir ar yra bendrų šių seansų funkcijų.

  - **ImpressionId** – nurodo testuojamų variantų rinkinį, kurie veikia nurodytame seanse. Leidžia mums aptikti, kurie atskiri testuojami variantai veikia seanso metu, kad galėtume nustatyti, ar testuojamas variantas yra problemos šaltinis, veikiantis vartotojus.

  - **MeasuresEnabled** – žymė, nurodanti, ar vykdoma dabartinio seanso duomenų atranka. Leidžia mums nustatyti, kaip statistiškai įvertinti duomenis, surinktus iš nurodyto seanso.

  - **SamplingClientIdValue** – kliento, naudojamo nustatyti, ar jis yra pavyzdžių atrankos dalis, ID. Leidžia mums nustatyti, kodėl į pavyzdžių rinkimą buvo arba nebuvo įtrauktas atskiras seansas.
  
 - **SubAppName** – skirta „Office Mobile“ programėlei, šis laukas atstovauja fone esančią programą, naudojamą atidaryti dokumentui. Pavyzdžiui, jeigu atidarote „Word“ dokumentą „Office“ programoje, šio lauko reikšmė bus „Word“.

 - **VirtualizationType** – virtualizacijos tipas, jeigu viename iš jų paleista „Office“. Galimos reikšmės: 
    - 0 = Nėra
    - 1 = „Windows“ virtualusis darbalaukis.
    - 2 = „Microsoft“ sargybos „Application Guard“
    - 3 = „Windows Core“ operacinė sistema

#### <a name="user"></a>Vartotojas

Nuomotojui pateikia informaciją apie komercinės programinės įrangos SKU.

Šioje kategorijoje yra šie laukai:

  - **PrimaryIdentityHash** – pseudonimo identifikatorius, nurodantis dabartinį vartotoją.

  - **PrimaryIdentitySpace** – tapatybės, nurodytos PrimaryIdentityHash, tipas. Vienas iš MASCID, OrgIdCID arba UserObjectId.

  - **TenantGroup** – nuomotojo, kuriam priklauso prenumerata, tipas. Leidžia mums klasifikuoti problemas ir nustatyti, ar problema yra plačiai paplitusi, ar izoliuota atskirų vartotojų grupėje.

  - **TenantId** – nuomotojas, su kuriuo yra susieta vartotojo prenumerata. Leidžia mums klasifikuoti problemas ir nustatyti, ar problema yra plačiai paplitusi, ar izoliuota atskirų nuomotojų grupėje.

### <a name="information-that-specifically-supports-diagnostic-data-collection"></a>*Specialiai diagnostikos duomenų rinkimą palaikanti diagnostikos informacija*

Diagnostikos duomenų rinkimą specialiai palaikanti informacija yra renkama šiose kategorijose.

#### <a name="activity"></a>Veikla

Informacija, padėsianti suprasti sėkmingus veiksmus su įvykių rinkiniu.

Šioje kategorijoje yra šie laukai:

  - **AggMode** – nurodo sistemai kaip agreguoti veiklos rezultatus. Leidžia mums sumažinti iš vartotojo kompiuterio įkeliamos informacijos kiekį, agreguojant veiklos rezultatus į vieną periodiškai siunčiamą įvykį.

  - **Count** – veiklos įvykimo kartų skaičius, jeigu skaičiuojami agreguoti įvykiai. Leidžia mums nustatyti kaip dažnai veikla pavyko ar nepavyko, remiantis veiklos agregavimo režimu.

  - **CV** – reikšmė, nurodanti ryšį tarp veiklų ir antrinių veiklų. Leidžia mums atkurti ryšį tarp įdėtųjų veiklų.

  - **Duration** – laikas, reikalingas vykdyti veiklai. Leidžia mums nustatyti veikimo problemas, neigiamai veikiančias vartotojo funkcijas.

  - **Result.Code** – programos nustatytas kodas, skirtas identifikuoti pateiktą rezultatą. Leidžia mums nustatyti konkretesnę pateikto sutrikimo informaciją, pvz., trikties kodą, naudojamą problemoms klasifikuoti ir šalinti.

  - **Result.Tag** – sveikųjų skaičių žymė, nurodanti kode vietą, kurioje buvo sugeneruotas rezultatas. Leidžia mums aiškiai nustatyti kodo vietą, kurioje buvo sugeneruotas rezultatas, įgalinantis klasifikuoti triktis.

  - **Result.Type** – rezultato kodo tipas. Nurodo, kokio tipo rezultato kodas buvo išsiųstas, kad būtų galima teisingai interpretuoti reikšmę.

  - **Success** – žymė, nurodanti, ar veikla atlikta sėkmingai. Leidžia mums nustatyti, ar pavyko vartotojo produkte atlikti veiksmai. Tai leidžia mums nustatyti problemas, kurios daro įtaką vartotojui.

#### <a name="application"></a>Taikomoji programa 

Informacijos apie įdiegtą taikomąją programą, iš kurios buvo renkami įvykiai.

Šioje kategorijoje yra šie laukai:

  - **Architecture** – taikomosios programos architektūra. Leidžia mums klasifikuoti klaidas, kurios gali būti susijusios su taikomosios programos architektūra.

  - **Click2RunPackageVersion** – paketo spustelėkite ir naudokitės, įdiegusio taikomąją programą, versijos numeris. Leidžia mums nustatyti, kokia diegimo programos versija buvo naudojama diegti „Office“, kad galėtume identifikuoti susijusias problemas.

  - **DistributionChannel** – kanalas, kuriame taikomoji programa buvo įdiegta. Leidžia mums išskaidyti gaunamus duomenis, kad galėtume nustatyti, ar problemos daro poveikį auditorijai.

  - **InstallMethod** – ar dabartinė „Office“ komponavimo versija buvo naujovinta iš ankstesnės komponavimo versijos, atšaukus ankstesnę komponavimo versiją arba, ar tai buvo naujas diegimas.

  - **IsClickToRunInstall** – žyma, nurodanti, ar diegimui buvo naudojama spustelėkite ir diekite technologija. Leidžia mums nustatyti problemas, kurios gali būti susijusios su spustelėkite ir naudokite diegimo mechanizmu.

  - **IsDebug** – žyma, rodanti, ar „Office“ komponavimo versija yra derinta komponavimo versija. Leidžia mums nustatyti, ar problemos kyla iš derintų komponavimo versijų, kurios gali veikti kitaip.

  - **IsInstalledOnExternalStorage** – žyma, nurodanti, ar „Office“ buvo įdiegta išorinėje saugykloje. Leidžia mums nustatyti, ar problemos gali būti atsektos iki išorinės saugyklos vietos.

  - **IsOEMInstalled** – žyma, nurodanti, ar „Office“ buvo įdiegta originalios įrangos gamintojo (OĮG). Leidžia mums nustatyti, ar programa buvo įdiegta OĮG. Tai gali padėti mums klasifikuoti ir identifikuoti problemas.

  - **PreviousVersion** – „Office“ versija, kuri buvo anksčiau įdiegta kompiuteryje. Leidžia mums atkurti ankstesnę versiją, jei dabartinė turi problemą.

  - **ProcessFileName** – taikomosios programos failo pavadinimas. Leidžia mums nustatyti pavadinimą vykdomosios programos, generuojančios duomenis, nes gali būti keli skirtingi proceso failų pavadinimai, nurodomi kaip tos pačios programos pavadinimas.

#### <a name="client"></a>Klientas

Informacija apie „Office“ klientą.

Šioje kategorijoje yra šie laukai:

  - **FirstRunTime** – kliento pirmojo veikimo trukmė. Leidžia mums suprasti, kiek laiko klientas yra įdiegęs „Office“.

#### <a name="device"></a>Įrenginys

Informacija apie įrenginio konfigūraciją ir funkcines galimybes.

Šioje kategorijoje yra šie laukai:

  - **DigitizerInfo** – informacija apie kompiuterio naudojamą skaitmeninį keitiklį. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **FormFactor** – nustato koks yra informaciją siunčiančio įrenginio formos koeficientas. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **FormFactorFamily** – nustato koks yra informaciją siunčiančio įrenginio formos koeficientas. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **HorizontalResolution** – įrenginio ekrano horizontali skiriamoji geba. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **Id** – unikalus įrenginio identifikatorius. Leidžia mums nustatyti problemų paskirstymą įrenginių rinkinyje.

  - **IsEDPPolicyEnabled** – žyma, nurodanti, ar kompiuteryje yra įjungta patobulinta duomenų apsauga. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **IsTerminalServer** – žyma, nustatanti, ar kompiuteris yra terminalo serveris. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **Manufacturer** – įrenginio gamintojas. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **Model** – įrenginio modelis. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **MotherboardUUIDHash** – unikalaus pagrindinės plokštės identifikatoriaus maiša. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **Name** – įrenginio pavadinimas. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.
  
  - **NetworkCost** – nurodo tinklo kainą arba tipą, pvz., apskaičiuotas, apskaičiuotas virš savikainos.
  
  - **NetworkCountry** – siuntėjo šalies kodas, pagrįstas netvarkytu kliento IP adresu.

  - **NumProcPhysCores** – procesoriaus fizinių branduolių skaičius. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **OsLocale** – veikiančios operacinės sistemos lokalė. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **ProcessorArchitecture** – procesoriaus architektūra. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **ProcessorCount** – kompiuterio procesorių skaičių. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **ProcSpeedMHz** – procesoriaus greitis. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **RamMB** – įrenginio turimos atminties kiekis. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **ScreenDepth** – leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **ScreenDPI** – ekrano DPI reikšmė. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **SusClientId** – įrenginio, kuriame veikia „Office“, „Windows Update“.

  - **SystemVolumeFreeSpaceMB** – laisvos vietos dydis sistemos laikmenoje. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **SystemVolumeSizeMB** – kompiuterio sistemos laikmenos dydis. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **VerticalResolution** – įrenginių ekranų vertikali skiriamoji geba. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **WindowErrorReportingMachineId** – unikalus kompiuterio identifikatorius, pateikiamas „Windows“ klaidų ataskaitoje. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

  - **WindowSqmMachineId** – unikalus kompiuterio identifikatorius, pateikiamas „Windows“ SQM. Leidžia mums priskirti duomenis remiantis įrenginio suvestine.

#### <a name="event"></a>Įvykis 

Konkretaus įvykio informacija, įskaitant jo unikalų identifikatorių seanse.

Šioje kategorijoje yra šie laukai:

  - **Contract** – bet kokių sutarčių, kurias įvykis vykdo, sąrašas. Leidžia mums įvertinti kokie duomenys priklauso atskiram įvykiui, kad galėtume juos efektyviai apdoroti.

  - **CV** – vertė, leidžianti mums nustatyti tarpusavyje susijusius įvykius. Naudojamas diagnostikai, kad galėtume identifikuoti susijusio veikimo būdo modelį arba susijusius įvykius.

  - **Flags** – informacija, naudojama keisti pateikiamo įvykio reagavimą. Naudojama valdyti pateikiamo įvykio traktavimą duomenų įkėlimo į „Microsoft“ tikslų atžvilgiu.

  - **Id** – unikalus įvykio identifikatorius. Leidžia mums unikaliai identifikuoti gautus įvykius.

  - **Level** – nurodo įvykio tipą.

  - **Name** – įvykio pavadinimas. Leidžia identifikuoti įvykį, kuris buvo siunčiamas iš kliento.

  - **Rule** – duomenis generavusios taisyklės identifikatorius, jeigu jie buvo sugeneruoti taisyklės. Leidžia mums nustatyti dalies duomenų šaltinį, kad galėtume patvirtinti ir tvarkyti įvykių parametrus

  - **RuleId** – duomenis generavusios taisyklės identifikatorius, jeigu jie buvo sugeneruoti taisyklės. Leidžia mums nustatyti dalies duomenų šaltinį, kad galėtume patvirtinti ir tvarkyti įvykių parametrus.

  - **RuleInterfaces** – visos sąsajos, įgyvendintos naudojant konkrečią taisyklę. Leidžia mums klasifikuoti ir importuoti duomenis pagal jų struktūrą, kuri supaprastina duomenų apdorojimą.

  - **RuleVersion** – duomenis generavusios taisyklės identifikatorius, jeigu jie buvo sugeneruoti taisyklės. Leidžia mums nustatyti dalies duomenų šaltinį, kad galėtume patvirtinti ir tvarkyti įvykių parametrus.

  - **SampleRate** – indikatorius, nurodantis koks vartotojų procentas siunčia šią informacijos dalį. Tai leidžia mums atlikti statistinę duomenų analizę ir nereikia, kad dažniausius naudojamus duomenų elementus siųstų visi vartotojai.

  - **SchemaVersion** – schemos versija, naudojama generuoti diagnostikos duomenis. Būtina valdyti iš kliento siunčiamus duomenis. Taip užtikrina kiekvieno kliento siunčiamų duomenų pokyčius per tam tikrą laiką.

  - **Sequence** – skaitiklis, nurodantis įvykio, sugeneruoto kliento, eiliškumą. Leidžia užsakyti gautus duomenis, kad galėtume nustatyti kokie veiksmai galėjo sukelti problemą, darančią įtaką klientams.

  - **Source** – šaltinio srautas, naudotas duomenims įkelti. Būtinas stebėti visus mūsų nusiuntimo srautus bendrai sveikatai ir padėti identifikuoti įkėlimo srauto problemas. Tai leidžia stebėti atskirus nusiuntimo srautus, siekiant užtikrinti, kad jie ir toliau atitinka reikalavimus.

  - **Time** – įvykio sugeneravimo kliente laikas. Leidžia mums sinchronizuoti ir patikrinti kliente sugeneruotų įvykių eiliškumą ir nustatyti veikimo metriką vartotojo instrukcijoms. 

#### <a name="host"></a>Pagrindinis kompiuteris

Informacija apie taikomąją programą, kurią pagrindinis kompiuteris naudoja kaip įdėtąją taikomąją programą

Šioje kategorijoje yra šie laukai:

  - **Id** – unikalus identifikatorius, kurį įdėtoji taikomoji programa priskyrė pagrindinio kompiuterio taikomajai programai.

  - **SessionId** – pagrindinio kompiuterio seanso visuotinis unikalusis identifikatorius.

  - **Versija** – pagrindinio kompiuterio pirminės vykdomosios programos versijos identifikatorius.

#### <a name="legacy"></a>Ankstesnės versijos

Ankstesnės versijos sistemos suderinamumui reikalinga informacija.

Šioje kategorijoje yra šie laukai:

  - **OsBuild** – konkretus operacinės sistemos komponavimo versijos numeris. Leidžia mums nustatyti iš kurios operacinės sistemos versijos gaunami diagnostiniai duomenys, kad nustatyti problemų prioritetus.

  - **OsBuildRevision** – operacinės sistemos komponavimo versijos peržiūros numeris. Leidžia mums nustatyti iš kurios operacinės sistemos versijos gaunami diagnostiniai duomenys, kad nustatyti problemų prioritetus.

  - **OsMinorVersion** – operacinės sistemos papildoma versija. Leidžia mums nustatyti iš kurios operacinės sistemos versijos gaunami diagnostiniai duomenys, kad nustatyti problemų prioritetus.

  - **OsVersionString** – bendra eilutė, pateikianti operacinės sistemos komponavimo versijos numerį. Leidžia mums nustatyti iš kurios operacinės sistemos versijos gaunami diagnostiniai duomenys, kad nustatyti problemų prioritetus.

#### <a name="session"></a>Seansas

Informacija apie proceso seansą.

Šioje kategorijoje yra šie laukai:

  - **ABConfigsDelta** – seka skirtumą tarp dabartinių ABConfigs duomenų ir ankstesnės reikšmės. Leidžia mums sekti naujus testuojamus variantus kompiuteryje, kad nustatyti, ar naujas testuojamas variantas yra problemos priežastis.

  - **CollectibleClassification** – informacijos, kurią galima surinkti seanso metu, klasės. Leidžia filtruoti seansus remiantis turimais duomenimis.

  - **DisableTelemetry** – žyma, nurodanti, ar nustatytas raktas DisableTelemetry. Leidžia mums žinoti, ar seanso metu nebuvo pateikti kiti, nei EssentialServiceMetadata, diagnostikos duomenys.

  - **SamplingClientIdValue** – rakto, naudojamo pavyzdžių rinkimo nustatymui, reikšmė. Leidžia mums nustatyti, kodėl seanso metu buvo arba nebuvo vykdomas pavyzdžių rinkimas.

  - **SamplingDeviceIdValue** – rakto, naudojamo pavyzdžio ėmimo nustatymui, reikšmė. Leidžia mums nustatyti, kodėl seanso metu buvo arba nebuvo vykdomas pavyzdžių rinkimas.

  - **SamplingKey** – raktas, naudojamas nustatyti, ar seanso metu vykdomas duomenų rinkimas. Leidžia mums suprasti, kaip atskiri seansai pasirenka, ar jų metu yra vykdoma duomenų atranka.

  - **SamplingMethod** – būdas, naudojamas nustatyti pavyzdžių rinkimo strategijai. Leidžia mums suprasti, kokie duomenys gaunami iš seanso.

  - **SamplingSessionKValue** – išplėstinio pavyzdžių rinkimo metaduomenys. Naudojami, kad būtų galima įvertinti gautų statistikos duomenų reikšmes.

  - **SamplingSessionNValue** – išplėstinio pavyzdžių rinkimo metaduomenys. Naudojami, kad būtų galima įvertinti gautų statistikos duomenų reikšmes.

  - **Sequence** – unikalus skaitinis seanso identifikatorius. Leidžia analizuoti seansų eiliškumą, kad nustatyti, kokiu atveju galėjo įvykti problema.

  - **Start** – procesas seanso įkrovos trukmė. Leidžia mums nustatyti seanso pradžios laiką.

  - **TelemetryPermissionLevel** – reikšmė, nurodanti vartotojo pasirinktą diagnostikos duomenų lygį. Leidžia mums suprasti, kokio lygio diagnostikos duomenų galime tikėtis iš seanso.

  - **TimeZoneBiasInMinutes** – UTC ir vietinio laiko skirtumas minutėmis. Leidžia normalizuoti UTC laiką atgal į vietinį laiką.

## <a name="data-fields-that-are-common-for-onenote-events"></a>„OneNote“ įvykiams dažnai naudojami duomenų laukai

Šie duomenų laukai dažniausiai naudojami visiems „OneNote“, skirtos „Mac“, „iOS“ ir „Android“, įvykiams.

> [!NOTE]
> Naudojant diagnostikos duomenų peržiūros programą, „OneNote“, skirtos „Mac“, „iOS“ ir „Android“ įvykiai bus parodyti su pavadinimais Activity, ReportData arba Unexpected. Norėdami rasti tikrąjį įvykio pavadinimą, pasirinkite įvykį, tada pažiūrėkite į lauką EventName.

- **Activity_ActivityType** – nurodo šio veiklos įvykio tipą. Veikla gali būti normali veikla arba svarbi veikla.

- **Activity_AggMode** – nurodo sistemai kaip agreguoti veiklos rezultatus. Leidžia mums sumažinti iš vartotojo kompiuterio įkeliamos informacijos kiekį, agreguojant veiklos rezultatus į vieną periodiškai siunčiamą įvykį.

- **Activity_Count** – veiklos įvykimo kartų skaičius, jeigu skaičiuojami agreguoti įvykiai. Leidžia mums nustatyti kaip dažnai veikla pavyko ar nepavyko, remiantis veiklos agregavimo režimu.

- **Activity_CV** – reikšmė, nurodanti ryšį tarp veiklų ir antrinių veiklų. Leidžia atkurti ryšį tarp įdėtųjų veiklų.

- **Activity_DetachedDurationInMicroseconds** – laikas, kai veikla yra laukimo būsenoje ir neatliekama jokio realaus darbo, bet laikas vis tiek įskaitomas į bendrą veiklos laiką.

- **Activity_DurationInMicroseconds** – laikas, kai veikla buvo vykdoma. Leidžia mums nustatyti veikimo problemas, neigiamai veikiančias vartotojo funkcijas.

- **Activity_Expiration** – skaitinio formato data, nurodanti, kada šis įvykis nebebus siunčiama iš klientų

- **Activity_FailCount** – nurodo, kiek kartų ši veikla nepavyko

- **Activity_Name** – trumpas įvykio pavadinimas. Leidžia identifikuoti įvykį, kuris buvo siunčiamas iš kliento.

- **Activity_Namespace** – įvykio vardų sritis. Leidžia mums suskirstyti įvykį į grupes.

- **Activity_Reason** – eilutė, nurodanti priežastį, dėl kurios veikla baigiasi su konkrečiu rezultatu.

- **Activity_Result** – žymė, nurodanti, ar veikla pavyko, nepavyko arba netikėtai nepavyko. Leidžia mums nustatyti, ar pavyko vartotojo produkte atlikti veiksmai. Tai leidžia mums nustatyti problemas, kurios daro įtaką vartotojui.

- **Activity_State** – žymė nurodanti, ar įvykis yra naudotojo veiklos pradžioje ar pabaigoje.

- **Activity_SucceedCount** – skaičius, kiek kartų pavyko ši veikla.

- **ErrorCode** – nurodo klaidos kodą, jei jis yra.

- **ErrorCode2** – nurodo antrą klaidos kodą, jei jis yra.

- **ErrorCode3** – nurodo trečią klaidos kodą, jei jis yra.

- **ErrorTag** – nurodo su klaidos kodu susietą žymę, jei ji yra.

- **ErrorType** – nurodo klaidos tipą, jei jis yra.

- **EventName** – unikalus „OneNote“ įvykio pavadinimas. „OneNote“ įvykiai naudoja šį pasirinktinį lauką, kad nurodytų unikalų pavadinimą dėl praeities inžinerinių apribojimų.

- **ExpFeatures** – nurodo, ar vartotojas programoje „OneNote“ turi įjungti eksperimentinių funkcijų jungiklį, ar ne.

- **ExpirationDate** – skaitinio formato data, nurodanti, kada šis įvykis nebebus siunčiama iš klientų

- **IsConsumer** – nurodo, ar programos vartotojas yra vartotojas, ar ne

- **IsEdu** – nurodo, ar vartotojas yra švietimo įstaigos nuomotojo vartotojas, ar ne

- **IsIW** – nurodo, ar vartotojas yra įmonės vartotojas, ar ne

- **IsMsftInternal** – nurodo, ar vartotojas yra „Microsoft“ darbuotojas, ar ne

- **IsPremiumUser** – nurodo, ar vartotojas turi „Premium“ licenciją, ar ne

- **Namespace** – įvykio vardų sritis. Leidžia mums suskirstyti įvykį į grupes.

- **Release_AppStore** – žymė, nurodanti, ar komponavimo versija gaunama iš programėlių parduotuvės, ar ne.

- **Release_Audience** – nurodo pateiktos auditorijos grupės papildomą auditoriją. Leidžia mums sekti auditorijos grupių poaibius, ir taip įvertinti problemų paplitimą bei nustatyti prioritetus.

- **Release_AudienceGroup** – nurodo žiedą, iš kurio gaunami duomenys. Leidžia mums parengti funkcijų apibendrinimą ir nustatyti galimas problemas, prieš joms pasiekiant daugelį vartotojų.

- **Release_Channel** – kanalas, per kurį produktas buvo išleistas. Leidžia mums nustatyti, ar problema veikia vieną iš mūsų išvesties kanalų skirtingai nuo kitų.

- **RunningMode** – nurodo, kaip programą paleidžia vartotojas arba sistemos procesas.

- **SchemaVersion** – nurodo dabartinę telemetrijos schemos versiją „OneNote“ telemetrijos sraute.

- **Session_EcsETag** – testuojamos sistemos indikatorius, nurodantis testavimo variantus, siųstus į kompiuterį. Leidžia mums nustatyti, kokie testavimo variantai gali veikti nurodytą seansą.

- **Session_ImpressionId** – nurodo testuojamų variantų, kurie veikia per nurodytą seansą, rinkinį. Leidžia mums aptikti, kurie atskiri testuojami variantai veikia seanso metu, kad galėtume nustatyti, ar testuojamas variantas yra problemos šaltinis, veikiantis vartotojus.

- **SessionCorrelationId** – pagrindinio kompiuterio seanso visuotinis unikalusis identifikatorius.

- **SH_ErrorCode** – nurodo klaidos kodą, jei jis yra, kai veikla nepavyksta.

- **Tag** – sveikųjų skaičių žymė, nurodanti kode vietą, kurioje buvo sugeneruotas telemetrijos įvykis.

- **UserInfo_IdType** – vartotojo paskyros tipą nurodanti eilutė

- **UserInfo.OMSTenantId** – nuomotojas, su kuriuo yra susieta vartotojo prenumerata. Leidžia mums klasifikuoti problemas ir nustatyti, ar problema yra plačiai paplitusi, ar izoliuota atskirų nuomotojų grupėje.

- **UserInfo_OtherId** – nepirminių pseudoniminių identifikatorių, atitinkančių vartotojo paskyras, sąrašas.

- **UserInfo_OtherIdType** – nepagrindinių paskyrų tipų sąrašas.

## <a name="data-fields-that-are-common-for-outlook-mobile-events"></a>„Outlook Mobile“ įvykiams dažnai naudojami duomenų laukai

„Outlook Mobile“ surenka įprastus kiekvieno iš mūsų įvykių laukus, kad galėtume užtikrinti, jog programa būtų atnaujinta, saugi ir funkcionuojanti. 

Šie duomenų laukai dažniausiai naudojami visiems „Outlook“, skirtos „iOS“ ir „Android“, įvykiams.

- **aad_tenant_id** – kliento nuomotojo ID, jei jis pasiekiamas

- **account_cid** – pseudonimo identifikatorius, nurodantis dabartinį vartotoją

- **account_domain** – paskyros domeno vardas

- **account_puid** – vartotojo „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius.

- **account_type** – seka paskyros tipą, pvz., „Office 365“, „Google Cloud Cache“, Outlook.com ir t.t.

- **action** – įvykio veiksmo pavadinimas (pvz., archyvuoti,naikinti ir t.t.), kad galėtume aptikti specifinių veiksmų, kurių imtasi, problemą

- **ad_id** – unikalus reklamavimo identifikatorius

- **app_version** – naujausia taikomosios programos versija, kuri padės mums aptikti tam tikros taikomosios programos versijos triktis

- **AppInfo.ETag** – unikalus jūsų funkcijų išleidimo valdymo identifikatorius, padedantis nustatyti, kurios triktys veikia tam tikras paleistas funkcijas

- **AppInfo.Language** – šiuo metu nustatyti įrenginio kalbos parametrai, kurie padės mums aptikti tam tikromis kalbomis kylančias triktis

- **AppInfo. version** – naujausia taikomosios programos versija, kuri padės mums aptikti triktis, kurios veikia tam tikras taikomųjų programų versijas

- **ci** – pseudoniminis konkrečios programos įrenginio unikalus identifikatorius

- **cid_type** – nurodo, kokio tipo yra paskyra, pvz., komercinė paskyra arba „Outlook.com“ paskyra.

- **cloud** – kai pašto dėžutė yra šio įrenginio paskyroje ir padeda aptikti konkretaus pašto dėžutės debesies, pvz., „Office 365“ ar GCC, debesies problemą.

- **customer_type** – nurodo kliento tipą (vartotoją, komercinę, trečiąją šalį ir t. t.), padedantį nustatyti tam tikrų klientų tipų triktis.

- **device_category** – nurodo, kokio tipo įrenginys (telefonas, planšetinis kompiuteris ir t. t.), kad būtų lengviau aptikti įrenginio kategorijos tam tikras triktis

- **DeviceInfo.Id** – unikalus įrenginio identifikatorius, kuris padės mums aptikti įrenginio specifines triktis

- **DeviceInfo.Make** – įrenginio, pvz., „Apple“, „Samsung“ ir t.t., markė, kuri padės aptikti specifines įrenginio triktis

- **DeviceInfo.Model** – įrenginio modelis (t. y. „iPhone 6s“), kuris padės mums aptikti įrenginio modelio tam tikras triktis

- **DeviceInfo.NetworkType** – naudojamas esamas įrenginių tinklas (WiFi, mobilusis ir t.t.), kuris padės mums aptikti įrenginio tinklo tam tikras triktis

- **DeviceInfo.OsBuild** – dabartinės OS komponavimo versija, padedanti mums aptikti konkrečias OS komponavimo versijas veikiančias triktis

- **DeviceInfo.OsName** – OS pavadinimas (pvz., „iOS“), kurie padės mums aptikti tam tikroms platformoms būdingas triktis

- **DeviceInfo.OsBuild** – dabartinės OS komponavimo versija, padedanti mums aptikti konkrečias OS komponavimo versijas veikiančias triktis

- **DeviceInfo.SDKUid** – įrenginio unikalusis identifikatorius (panašus į DeviceInfo.Id)

- **EventInfo.InitId** – ID, naudojamas kaip sekos, skirtos įvykių užsakymui mūsų telemetrijos sraute, nustatymas, kad būtų galima nustatyti pagrindinės srauto problemos priežastį

- **EventInfo.SdkVersion** – SDK versija, kurią naudojame siųsti telemetriją, padedanti nustatyti pagrindinės vamzdyno problemos priežastį

- **EventInfo. Sequence** – seka yra skirta įvykių užsakymams per mūsų telemetrijos srautą, kad galėtume nustatyti pagrindinės srauto problemos priežastį

- **EventInfo.Source** – parodo, kokią kodo dalį atsiuntė įvykis, kad galėtume nustatyti priežastį, dėl kurios kyla problemų

- **EventInfo.Time** – laikas ir data, kada renginys buvo išmetamas iš įrenginio, kad mūsų sistemos galėtų sėkmingai valdyti ateinančius įvykius

- **eventpriority** – telemetrijos įvykių prioritetas, lyginant su kitais įvykiais, kad mūsų sistemos galėtų sėkmingai valdyti ateinančius įvykius

- **first_launch_date** – pirmą kartą paleidus programą, tai padės mums suprasti, kada pirmą kartą atsirado problema

- **hashed_email** – pseudonimo identifikatorius, nurodantis dabartinio vartotojo el. paštą

- **is_first_session** – seka, ar tai yra pirmasis taikomosios programos seansas

- **origin** – veiksmo inicijacija. Pvz., pranešimo žymėjimas kaip perskaityto gali būti gaunamas iš pranešimų sąrašo arba pranešimo apie naują el. laišką, todėl tai padeda mums aptikti triktis, pagrįstas veiksmų inicijavimu

- **PipelineInfo.AccountId** – pseudonimo identifikatorius, nurodantis dabartinį vartotoją.

- **PipelineInfo.ClientCountry** – dabartinė įrenginio šalis, kad būtų aptiktos šaliai ar regionui specifinės triktys ar nepasiekiamumas

- **PipelineInfo.ClientIp** – IP adresas, kuriuo įrenginys yra prijungtas prie ryšio trikčių derinimo

- **PipelineInfo.IngestionTime** – laiko žyma, kai vyksta mūsų telemetrijos failų įdėjimas šiam renginiui

- **sample_rate** – įvykio egzempliorius renkančių įrenginių procentinė dalis. Padeda apskaičiuoti pradinį įvykio egzempliorių skaičių.

- **Session.Id** – unikalus taikomosios programos seanso identifikatorius, padedantis nustatyti su seansu susijusias triktis

- **Seansas. ImpressionId** – unikalus funkcijų išleidimo valdymo identifikatorius, siekiant užtikrinti, kad funkcijos būtų sėkmingai išleistos visiems vartotojams ir įrenginiams

- **ui_mode** – ar vartotojas apšvietimo, ar tamsos režimu, padeda mums klasifikuoti UX klaidas, naudojant tamsų režimą

- **UserInfo.Language** – vartotojo kalba, padedanti derinti teksto vertimo triktis

- **UserInfo.TimeZone** – vartotojo laiko juosta, padedanti šalinti kalendoriaus triktis


Be to, šie laukai dažniausiai naudojami visiems „Outlook“, skirtos „iOS“, įvykiams.

- **DeviceInfo.NetworkProvider** – įrenginio tinklo teikėjas (pvz., „Verizon“)

- **gcc_restrictions_enabled** – parodo, jei GCC apribojimai buvo taikomi programėlei, kad galėtume užtikrinti, kad mūsų GCC klientai saugiai naudoja mūsų programą
 
- **multi_pane_mode** – parodo, ar vartotojas, naudojantis „iPad“, naudoja aplanką Gauta su keliomis įjungtomis sritimis, kuriose klasifikuodamas el. laiškus gali matyti aplankų sąrašą. To reikia, kad galėtume aptikti problemas, būdingas naudojant aplanką Gauta su keliomis atidarytomis sritimis.

- **multi_window_mode** – parodo, ar vartotojas, naudojantis „iPad“ naudoja kelis langus, kad galėtume nustatyti problemas, susijusias su kelių langų naudojimu.

- **office_session_id** – unikalus ID, kuriuo sekama prijungtų „Office“ tarnybų seansas, kad būtų lengviau aptikti „Office“ paslaugų integravimą programoje „Outlook“, pvz., „Word“

- **state** – ar taikomoji programa buvo aktyvi, kai šis įvykis buvo nusiųstas, kad būtų lengviau aptikti aktyvios arba neaktyvios taikomųjų programų triktis


Be to, šie laukai dažniausiai naudojami visiems „Outlook“, skirtos „Android“, įvykiams.

- **aad_id** – pseudoniminis „Azure Active Directory“ identifikatorius

- **DeviceInfo.NetworkCost** – įrenginių, kurių būsena atitinka WiFi/Cellular/roaming būseną, kad būtų lengviau aptikti įrenginių tinklo triktis, nurodymas

- **is_app_in_duo_split_view_mode** – tai praneš mums, kad taikomoji programa buvo rodoma Duo ekrano režimu.  Ši ypatybė nustatyta tik Duo (tik „Android“) įrenginiams.

- **is_dex_mode_enabled** – ar „Samsung DeX Mode“ įgalinta „Samsung“ įrenginiuose, norint aptikti DeX režimu būdingas triktis

- **is_preload_install** – nurodo mums, ar jūsų programa įrenginyje buvo iš anksto įkelta (įrenginiuose su „Android 11“ ar vėlesne versija)

- **is_sliding_drawer_enabled** – ar slankiojo stalčiaus sąsajos įgalintos, padeda aptikti slankiojo stalčiaus sąsajos triktis

- **oem_preinstall** – nurodo, ar programa buvo iš anksto įdiegta įrenginyje

- **oem_preload_property** – nurodo, ar jūsų programa buvo iš anksto įkelta, kaip konkrečios sutarties su OĮG dalis

- **orientation** – fizinė ekrano padėtis (stačias/gulsčias), padedanti aptikti įrenginio padėties būdingus dalykus

- **os_arch** – įrenginio operacinė sistema, kuri padeda aptikti įrenginio veikimo sistemoms būdingus dalykus

- **process_bitness** proceso bitų skaičius (32 arba 64 bit), kad galėtų aptikti problemas, kurios būdingos įrenginio bitų skaičiui

- **webview_kernel_version**: įrenginio „Chromium“ branduolio „WebView“ versija, kuri padės mums aptikti suderinamumo su „WebView“ versija susijusias problemas.

- **webview_package_name**: įrenginio paketo pavadinimas, kuris padės mums aptikti suderinamumo su „WebView“ versija susijusias problemas.

- **webview_package_version**: įrenginio paketo versija, kuri padės mums aptikti suderinamumo su „WebView“ versija susijusias problemas.


## <a name="software-setup-and-inventory-data-events"></a>Programinės įrangos sąrankos ir inventoriaus duomenų įvykiai

Toliau pateikiami šios kategorijos duomenų potipiai:
- [„Office“ sąranka ir inventorius](#office-setup-and-inventory-subtype)
- [„Office“ papildinio konfigūracija](#office-add-in-configuration-subtype)
- [Sauga](#security-subtype)  

### <a name="office-setup-and-inventory-subtype"></a>*„Office“ sąranka ir inventoriaus potipis*

Įdiegtas produktas ir versija bei diegimo būsena.

#### <a name="addssoaccount"></a>add.sso.account

Tai praneš „Microsoft“ apie sėkmingą arba nesėkmingą vartotojo paskyros įtraukimą naudojant bendrąją autentifikaciją (SSO).

Renkami šių laukų duomenys: 

- **account_type** – paskyros, pridėtos naudojant SSO, tipas.

- **action_origin** – iš kur buvo sukurtas šis įvykis. (pvz., reikšmės: sso_drawer, sso_add_account, sso_add_account_prompt, sso_settings, sso_oobe).

- **provider** – tiekėjo programinės įrangos paketo, skirto SSO, identifikatorius.

- **state** – dabartinė paskyros būsena (reikšmės pavyzdys: FAILED (nepavyko), PENDING (laukiama), ADDED (įtraukta) ir t. t.)


#### <a name="installreferral"></a>install.referral

Šis įvykis paleidžiamas pradiniame programos įdiegime ir įrašo, iš kur buvo nurodytas vartotojas (jei yra).

Renkami šių laukų duomenys:

- **install_referrer** – produktas arba patirtis, kai vartotojas nurodytas

 
#### <a name="officeclicktorunupdatestatus"></a>Office.ClickToRun.UpdateStatus

Taikoma visoms „win32“ programoms. Padeda suprasti „Office“ paketo naujinimo proceso būseną (sėkmingai ar nesėkmingai atliktas, bei pateikiama klaidų informacija)

Renkami šių laukų duomenys:

- **build** – šiuo metu įdiegta „Office“ versija

- **channel** – kanalas, kuriuo platintas „Office“

- **errorCode** – triktį nurodantis klaidos kodas

- **errorMessage** – papildoma klaidos informacija

- **status** – dabartinė naujinimo būsena

- **targetBuild** – „Office“ versija, į kurią naujinama

#### <a name="officecompliancefileformatballotdisplayedonfirstboot"></a>Office.Compliance.FileFormatBallotDisplayedOnFirstBoot

Nurodo, ar „Office“ failų formato pasirinkimo dialogo langas buvo rodomas vartotojui pirmą arba antrą kartą paleidžiant „Word“, „Excel“, „PowerPoint“ sąsajoje „Win32“.  Stebi, ar rodomas dialogo langas „FileFormat Ballot“ – įvykis siunčiamas pirmą arba antrą kartą paleidžiant „Word“, „Excel“ arba PPT sąsajoje „Win32“.

Renkami toliau apibūdintų laukų duomenys.

- **CountryRegion** – vartotojų šalies regiono parametrai sistemoje „Windows“

- **FileFormatBallotBoxAppIDBootedOnce** – nurodo, kurioje programoje („Word“, „Excel“, PPT) buvo tvarkoma failo formato balsavimo rodymo logika.

- **FileFormatBallotBoxDisplayedOnFirstBoot** – nurodo, koks yra failo formato balsavimo rodymo rezultatas (rodomas, nerodomas kaip netikėtas, nerodomas dėl licencijos, nerodomas dėl vietos).

#### <a name="officecompliancefileformatballotoption"></a>Office.Compliance.FileFormatBallotOption

Stebi, ar rodomas dialogo langas „FileFormat Ballot“ – įvykis siunčiamas pirmą arba antrą kartą paleidžiant „Word“, „Excel“ arba PPT sąsajoje „Win32“.  Nurodo, ar „Office“ failų formato pasirinkimo dialogo langas buvo rodomas pirmą arba antrą kartą paleidžiant „Word“, „Excel“, „PowerPoint“ sąsajoje „Win32“.

Renkami šių laukų duomenys:

- **FileFormatBallotSelectedOption** – identifikuoja failo formato parinktį (OOXML/ODF), kurią vartotojas pasirinko per failo formato balsavimo dialogo langą.


#### <a name="officecorrelationmetadatautccorrelationmetadata"></a>Office.CorrelationMetadata.UTCCorrelationMetadata

Renka „Office“ metaduomenis per UTC, kad palyginti atitinkamus duomenis, surinktus naudojant „Office“ telemetrijos srautą, bei patikrinti duomenų tikslumą ir užbaigtumą.

Renkami šių laukų duomenys:

- **abConfigs** – funkcijų ID sąrašas, skirtas identifikuoti pas klientą įjungtas funkcijas arba jis gali būti tuščias, kai duomenys nėra renkami.

- **abFlights** – „NoNL:NoFlights“, kai funkcijų testavimo variantai nenustatyti. Kitu atveju „holdoutinfo=unknown“.

- **AppSessionGuid** – konkrečios taikomosios programos seanso pradžios identifikatorius, naudojamas nuo proceso kūrimo pradžios ir iki proceso pabaigos. Jis yra suformuotas kaip standartinis 128 bitų GUID, tik sudarytas iš keturių dalių. Šios keturios dalys eilės tvarka yra (1) 32 bitų proceso ID (2) 16 bitų seanso ID (3) 16 bitų įkrovos ID (4) 64 bitų proceso sukūrimo laikas, išreikštas UTC 100 nsek.

- **appVersionBuild** – taikomosios programos komponavimo versijos numeris.

- **appVersionMajor** – taikomosios programos pagrindinės versijos numeris.

- **appVersionMajor** – taikomosios programos papildomos versijos numeris.

- **appVersionRevision** – taikomosios programos peržiūros versijos numeris.

- **audienceGroup** – leidimo auditorijos grupės pavadinimas

- **audienceId** – leidimo auditorijos pavadinimas

- **channel** – kanalas, kuriuo platintas „Office“

- **deviceClass** – įrenginio formos koeficientas iš OS

- **ecsETag** – proceso eksperimento identifikatorius

- **impressionId** – GUID rodo dabartinį funkcijų rinkinį.

- **languageTag** - dabartinė „Office“ UI IETF kalbos žymė

- **officeUserID** – atsitiktinai sugeneruotas GUID, skirtas šiam „Office“ diegimui

- **osArchitecture** – operacinės sistemos architektūra

- **osEnvironment** – sveikasis skaičius, nurodantis operacinę sistemą („Windows“, „Android“, „iOS“, „Mac“ ir kt).

- **osVersionString –** operacinės sistemos versija

- **sessionID** – atsitiktinai sugeneruotas GUID, skirtas nustatyti taikomosios programos seansą

- **UTCReplace_AppSessionGuid** – nuolatinė Bulio logikos vertė. Visuomet „True“.

#### <a name="officeonenoteandroidapponenotelaunchednonactivated"></a>Office.OneNote.Android.App.OneNoteLaunchedNonActivated

*[Šis įvykis anksčiau buvo pavadintas OneNote.App.OneNoteLaunchedNonActivated.]*

Įrašo taikomosios programos aktyvinimo būsenos informaciją.  Duomenys stebimi, kad galėtume nustatyti aktyvinimo problemų šuolius. Taip pat analizuojame duomenis, kad rastume tobulintinas sritis.

Renkami šių laukų duomenys: 

- **INSTALL_LOCATION** – nurodo, ar taikomoji programa yra iš anksto įdiegta, ar atsisiųsta iš parduotuvės

#### <a name="officeonenoteandroidresetstatus"></a>Office.OneNote.Android.ResetStatus

*[Šis įvykis anksčiau buvo vadinamas OneNote.ResetStatus.]*

Signalas, naudojamas įrašyti visas problemas, iškilusias naudotojui bandant nustatyti iš naujo taikomąją programą.  Telemetrija naudojama stebėti, aptikti ir išspręsti problemas, susijusias su paleidimu iš naujo. 

Renkami šių laukų duomenys: 

- **Accounts** – nurodo tipus, jei paskyros naudojamos prisijungti prie taikomosios programos

- **GenericStringType** – pateikia informaciją, jei tai yra visiškas notes_light_data atkūrimas

- **LaunchPoint** – nustatymo iš naujo inicijavimo vieta. Galimos reikšmės: Sign Out Button, Sign out failure, Intune Triggered

- **Pass** – nurodo, ar nustatymas iš naujo pavyko

#### <a name="officeonenoteandroidsigninsignincompleted"></a>Office.OneNote.Android.SignIn.SignInCompleted

*[Šis įvykis anksčiau buvo vadinamas OneNote.SignIn.SignInCompleted.]*

Kritinis signalas, naudojamas norint įsitikrinti, ar prisijungimas buvo sėkmingas. Telemetrija renkama siekiant užtikrinti kritinės regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai

Renkami šių laukų duomenys: 

- **CompletionState** – galutinė prisijungimo būsena: ar pavyko. Ir trikčių atvejai

- **EntryPoint** – nurodo, iš kur buvo pradėtas prisijungimas

- **Hresult** – klaidos kodas

- **Provider Package ID** – automatinio prisijungimo atveju

- **Rezultatas** – Pavyko, Nepavyko, Nežinoma, Atšaukta

- **ServerType** – pateikia serverio, siūlančio tarnybą, tipą 

- **SignInMode** – prisijungimas, prisiregistravimas, automatinis prisijungimas arba pagreitintas prisijungimas.

#### <a name="officeonenoteandroidsigninsigninstarted"></a>Office.OneNote.Android.SignIn.SignInStarted

*[Šis įvykis anksčiau buvo vadinamas OneNote.SignIn.SignInStarted.]*

Signalas, naudojamas rodyti visas problemas, iškilusias naudojant pranešimų juostą.  Telemetrija naudojama stebėti, aptikti ir išspręsti problemas, atsiradusias naudojant pranešimų juostą.

Renkami šių laukų duomenys: 

- **EntryPoint** – nurodo, iš kur buvo pradėtas prisijungimas

- **Result** – prisijungimo srauto rezultatas

- **ServerType** – pateikia serverio, siūlančio tarnybą, tipą 

- **SignInMode** – prisijungimas, prisiregistravimas, automatinis prisijungimas arba pagreitintas prisijungimas.


#### <a name="officeonenotefirstrunfirstrun"></a>Office.OneNote.FirstRun.FirstRun

Kritinis signalas, naudojamas siekiant užtikrinti, kad nauji vartotojai galėtų sėkmingai paleisti ir paleisti „OneNote“ pirmą kartą.  Telemetrija renkama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Jei vartotojai negali paleisti programos pirmą kartą, suaktyvinamas didelės svarbos incidentas.

- **AfterOneDriveFrozenAccountError** – nurodo klaidą iš „OneDrive“, kai paskyra yra pristabdyta.

- **Attempt** – kiek kartų turi būti bandoma paleisti pirmą kartą.

- **IsDefaultNotebookCreated** – nurodo, ar „OneNote“ sukūrė vartotojo numatytąjį bloknotą, ar ne.

- **Isdelayesignin** – nurodo, ar pirmasis paleidimas veikia uždelsto prisijungimo režimu, kai vartotojui nereikia prisijungti.

- **IsMSA** – nurodo, ar paskyra yra „Microsoft“ paskyra.

#### <a name="officeonenotefirstrunfirstrunformsa"></a>Office.OneNote.FirstRun.FirstRunForMSA

Kritinis signalas, naudojamas siekiant užtikrinti, kad nauji vartotojai („Microsoft“ paskyra) gali sėkmingai paleisti ir naudoti „OneNote“ pirmą kartą.

Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Jei vartotojai negali paleisti programos pirmą kartą, suaktyvinamas didelės svarbos incidentas.

Renkami šių laukų duomenys:

- **Attempt** – kiek kartų turi būti bandoma paleisti pirmą kartą.

- **Error A** – „OneNote“ klaidos objektas, nurodantis klaidą pirmojo paleidimo metu, jei tokių yra.

- **FAllowAddingGuide** – nurodo, ar „OneNote“ leis sukurti vadovo bloknotą.

- **FrozenOneDriveAccount** – nurodo, ar „OneDrive“ paskyra yra sustabdyta.

- **IsDefaultNotebookCreated** – nurodo, ar „OneNote“ sukūrė vartotojo numatytąjį bloknotą, ar ne.

- **NoInternetConnection** – nurodo, ar įrenginys turi interneto ryšį.

- **ProvisioningFailure** – „OneNote“ klaidos objektas, nurodantis pateikiamą klaidą, jei tokių yra.

- **ProvisioningFinishedTime** – nurodo „OneNote“ bloknoto pateikimo pabaigos laiką pirmojo paleidimo metu.

- **ProvisioningStartedTime** – nurodo „OneNote“ bloknoto pateikimo pradžios laiką pirmojo paleidimo metu.

- **ShowSuggestedNotebooks** – nurodo, ar „OneNote“ parodys siūlomo bloknoto funkciją.

#### <a name="officeonenotefirstrunfirstrunfororgid"></a>Office.OneNote.FirstRun.FirstRunForOrgId

Kritinis signalas, naudojamas siekiant užtikrinti, kad nauji įmonės vartotojai (AAD/ORGID) galėtų sėkmingai paleisti ir vykdyti „OneNote“ pirmą kartą.  Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Jei vartotojai negali paleisti programos pirmą kartą, suaktyvinamas didelės svarbos incidentas.

- **Attempt** – kiek kartų turi būti bandoma paleisti pirmą kartą.

- **Error** – „OneNote“ klaidos objektas, nurodantis klaidą pirmojo paleidimo metu, jei tokių yra.

- **FAllowAddingGuide** – nurodo, ar „OneNote“ leis sukurti vadovo bloknotą.

- **IsDefaultNotebookCreated** – nurodo, ar „OneNote“ sukūrė vartotojo numatytąjį bloknotą, ar ne.

- **ProvisioningFailure** – „OneNote“ klaidos objektas, nurodantis pateikiamo klaidą, jei tokių yra.

- **ProvisioningFinishedTime** – nurodo „OneNote“ bloknoto pateikimo pabaigos laiką pirmojo paleidimo metu.

- **ProvisioningStartedTime** – nurodo „OneNote“ bloknoto pateikimo pradžios laiką pirmojo paleidimo metu.

#### <a name="officeonenotefirstrunmrureadernotebookentries"></a>Office.OneNote.FirstRun.MruReaderNoteBookEntries 

Signalas, naudojamas įrašyti visas problemas, iškilusias įkeliant Bloknotus pirmojo paleidimo metu.  Telemetrija naudojama stebėti, aptikti ir išspręsti problemas, susijusias su pirmuoju paleidimu.

Renkami šių laukų duomenys: 

- **OnPremNBCount** – bloknotų skaičius „Prem“ serveryje

- **TotalNBCount** – bendras su vartotojo paskyra susietų bloknotų skaičius

#### <a name="officeonenotesystemapplifecycleuseraccountinfo"></a>Office.OneNote.System.AppLifeCycle.UserAccountInfo

Šis įvykis suaktyvinamas bendrinamam kodui ir įrašo reikšmes to tipo paskyroms, prie kurių prisijungta per „isEdu“, „isMsftInternal“, „isIW“, „isMSA“. Duomenys renkami, kai po paleisties eilė pirmą kartą tampa laukimo būsenos. Šis žymeklis naudojamas paskyrų, prie kurių įrenginyje buvo prisijungta, tipams sekti. Tai padės mums identifikuoti EDU vartotojus programoje „OneNote“. 

Renkami šių laukų duomenys: 

- **IsEdu** – galimos reikšmės – teisinga / klaidinga

- **IsMSA** – galimos reikšmės – teisinga / klaidinga

- **IsIW** – galimos reikšmės – teisinga / klaidinga

- **IsMsftInternal** – galimos reikšmės – teisinga / klaidinga


#### <a name="officetargetedmessagingensurecached"></a>Office.TargetedMessaging.EnsureCached 

Seka, ar buvo atsisiųstas paketas dinaminei matomosios tinklalapio srities daliai. Laikoma taikomosios programinės įrangos konfigūracija, nes paketas turi būti sėkmingai atsisiųstas, kad įgalinti klientą generuoti tinkamą patirtį. Yra ypač kritinės vartotojo prenumeratoms, kur matomąją tinklalapio sritį naudojame informuoti vartotoją, kad licencija nebegalioja. Naudojamas sekti metaduomenis dinaminio turinio paketo, kurį atsisiuntė ir į talpyklą įkėlė produktas, ir operacijų, atliktų su paketu, rezultatus: nesėkmingus atsisiuntimus, negalimą išsipakavimą, nuolatines patikros triktis, sėkmingą kreipimąsi į talpyklą, paketo naudojimus ir atsisiuntimo šaltinius.

Renkami šių laukų duomenys:

  - **Data\_CacheFolderNotCreated –** Bulio logikos žyma nurodo, ar pavyko sukurti talpyklos aplanką

  - **Data\_CdnPath – paketo šaltinio adresas –**

  - **Data\_EnsureCached –** Bulio logikos žyma, nurodanti, ar turinio paketas buvo įtrauktas į talpyklą

  - **Data\_ExistsAlready –** Bulio logikos žyma, nurodanti, kad paketas jau buvo atsisiųstas anksčiau ir buvo dar vienas bandymas

  - **Data\_GetFileStreamFailed –** šaltinio paketo nėra šaltinyje

  - **Data\_GetFileStreamFailedToCreateLocalFolder –** vietinio disko problemos, dėl kurių nepavyksta sukurti katalogo

  - **Data\_GetFileStreamFromPackageFailed –** žyma, nurodanti, ar paketas buvo atsisiųstas, bet klientas negali jo perskaityti

  - **Data\_GetFileStreamFromPackageSuccess –** sėkmingi paketo perskaitymo bandymai

  - **Data\_GetFileStreamSuccess –** nėra disko arba konfigūravimo problemų, neleidžiančių skaityti failų srauto

  - **Data\_GetRelativePathsFailed –** santykinis kelias nenurodo pasiekiamos vietos

  - **Data\_HashActualValue –** maišos vertė paimta iš failo pavadinimo paketo naudojimo metu

  - **Data\_HashCalculationFailed –** maišos skaičiavimo klaida

  - **Data\_HashMatchFailed –** maišos neatitikimas tarp paketo pavadinimo ir registro vertės, įtrauktos į talpyklą

  - **Data\_HashMatchSuccess –** sėkminga maišos nuoseklumo patikra

  - **Data\_PackageDownloadRequestFailed –** negalima atsisiųsti paketo

  - **Data\_PackageDownloadRequestNoData –** atsisiųstame pakete nėra duomenų

  - **Data\_PackageDownloadRequestSuccess –** sėkmingas paketo atsisiuntimas

  - **Data\_PackageExplodedSuccess –** bandymo išpakuoti būsenos

  - **Data\_PackageOpenFailed –** nepavykę bandymai atidaryti paketo failą

  - **Data\_PackageOpenSuccess –** pavykę bandymai atidaryti paketo failą

  - **Data\_SuccessHashValue –** maišos vertė paimta iš failo pavadinimo, kai buvo atsisiųstas paketas

  - **Data\_SuccessSource –** paviršius, kuriam buvo atsisiųstas paketas

#### <a name="officevisiovisiosku"></a>Office.Visio.VisioSKU

Nustato, ar „Visio“ SKU yra standartinė ar profesionali. Būtina problemas skirstyti į kategorijas pagal SKU.

Renkami šių laukų duomenys:

  - **Data\_VisioSKU**:**integer** – „0“ – standartinis SKU, o „1“ profesionalus SKU

### <a name="office-add-in-configuration-subtype"></a>*„Office“ papildinio konfigūracijos potipis*

Programinės įrangos papildiniai ir jų parametrai.

#### <a name="exceladdindefinedfunctioncustomfunctionsallinone"></a>Excel.AddinDefinedFunction.CustomFunctionsAllInOne

Renka informaciją apie pasirinktinių papildinių funkcijų vykdymo veikimą. Palaiko vykdymo bandymų, sėkmingos pabaigos, infrastruktūros klaidų ir vartotojo kodų klaidų skaitiklius. Ši funkcija naudojama produkto patikimumo problemoms nustatyti ir vartotoją veikiančioms problemoms spręsti.
 
Renkami šių laukų duomenys:

- **AsyncBegin** – asinchroninių funkcijų skaičius, kurios prasideda

- **AsyncEndAddinError** – asinchroninių funkcijų, kurios baigiasi klaida, skaičius

- **AsyncEndInfraFailure** – asinchroninių funkcijų, kurios baigiasi infraraudonųjų spindulių gedimu, skaičius

- **AsyncEndSuccess** – asinchroninių funkcijų, kurios baigiasi sėkmingai, skaičius

- **AsyncRemoveCancel** – atšauktų asinchroninių funkcijų skaičius 

- **AsyncRemoveRecycle** – asinchroninių funkcijų, kurios buvo pašalintos dėl perdirbimo, skaičius 

- **StreamingCycles1** – srautinio perdavimo ciklo skaitiklis

#### <a name="officeextensibilityappcommandsappcmdprojectionstatus"></a>Office.Extensibility.AppCommands.AppCmdProjectionStatus

Renka informaciją, skirtą stebėti kurie „Office“ papildiniai diegimai sėkmingai atnaujino juostelę ir jų palyginimas su nepavykusiais naujinimais.

Skirtas šalintis standartines registracijos problemas, kai papildiniai nėra tinkamai įdiegiami ir niekada nerodo, kad jie netinka naudoti.

Renkami šių laukų duomenys:

  - Nėra

#### <a name="officeextensibilityappcommandsaddsolution"></a>Office.Extensibility.AppCommands.AddSolution

Kaupia „Office“ papildinių, kurie tinkina juostelę, diegimo informaciją.  Naudojama aptikti problemas, atsirandančias tinkintiems papildiniams keičiant „Office“ juostelę.
 
Renkami šių laukų duomenys:

- **AppVersion** – taikomosios programos versija

- **SolutionId** – sprendimo ID

- **StoreType** – nurodo taikomosios programos kilmę


#### <a name="officeextensibilitycatalogexchangegetentitlements"></a>Office.Extensibility.Catalog.ExchangeGetEntitlements

Informacija apie sėkmingą arba nesėkmingą „Office 365“ nuomotojo administratoriui priskirtų papildinių teisių suteikimo duomenų atgavimo. Naudota sveikatos metrikoms, diagramoms ir kliento problemų analizei.

Renkami šių laukų duomenys:

  - **CachingResult –** rezultatas bandymo įrašyti tarnybos kvietimo grąžinamą vertę

  - **ClientParameter –** tarnybos kvietimo metu kliento siųstas identifikatorius

  - **EntitlementsCount –** numatomų atsako į kvietimą teisių suteikimų skaičius

  - **EntitlementsParsed –** iš atsakymų išanalizuotų teisių suteikimų skaičius

  - **IsAllEntitlementsParsed –** ar numatomų teisių suteikimų skaičius atitinka išanalizuotų teisių suteikimų skaičių

  - **ServiceCallHResult –** tarnybos kvietimo API grąžintas rezultatas

  - **TelemetryId –** GUID, nurodantis unikalų vartotoją

  - **UsedCache –** ar vietoj tarnybos kvietimo buvo naudojamas į talpyklą perkeltas atsakas

  - **VersionParameter –** „Office“ versijos numeris, išsiųstas tarnybos kvietimo metu

#### <a name="officeextensibilitycatalogexchangegetlastupdate"></a>Office.Extensibility.Catalog.ExchangeGetLastUpdate

Informacija apie sėkmingą arba nesėkmingą „Office 365“ nuomotojo administratoriui priskirtų papildinių poreikį atnaujintiems duomenims. Naudota sveikatos metrikoms, diagramoms ir kliento problemų analizei. ExchangeGetLastUpdate visada bus paleista įkrovos metu kaip dalis pagrindinio kompiuterio kodo ir nustatys, ar buvo vartotojui pakeistos papildinio užduotys.  Jei taip, tuomet osf.DLL bus įkeltas, kad galėtume iškviesti ExchangeGetEntitlements ir gauti konkrečius priskyrimus (ir ExchangeGetManifests bus iškviestas, kad būtų gautos visos naujos reikalingos deklaracijos).   ExchangeGetEntitlements (ir ExchangeGetManifests) gali taip pat būti iškviestos pagal poreikį, kai jau veikia pagrindinio kompiuterio taikomoji programa.  Norima, kad nebūtų įkeltas didelis DLL, jei mums jis nereikalingas.  Jeigu nepavyksta pirmasis tarnybos kvietimas, be šio įvykio nurodyto lauke Privaloma, negalėtume pasakyti, ar vartotojai negali gauti jiems priskirtų papildinių.  Tai taip pat yra pagrindinis įspėjimas dėl galimų bet kokių autentifikavimo problemų, su kuriomis galime susidurti kreipdamiesi į savo paslaugą.

Renkami šių laukų duomenys:

  - **Abort –** ar pagrindinis kompiuteris buvo išjungtas tarnybos kvietimo metu

  - **AllowPrompt –** ar buvo leistas autentifikavimo raginimas

  - **AuthScheme –** mainų prašoma autentifikavimo schema

  - **BackEndHttpStatus –** pateiktas http kodas, kai kreipiamasi dėl vidinių mainų

  - **BackupUrl –** antrinis mainų URL, skirtas iškvietimui

  - **BEServer –** vidinio mainų serverio vardas

  - **CalculatedBETarget –** visas mainų vidinio kompiuterio pavadinimas

  - **Call(n)\_TokenAuthError –** n-tojo tarnybos kvietimo bandymo autentifikavimo klaida

  - **Call(n)\_TokenIsValid –** ar buvo galiojantis autentifikavimo atpažinimo ženklo n-jame paslaugos iškvietimo bandyme

  - **CallMethod –** eilutė, nurodanti kodo naudotą kelią

  - **ConfigSvcReady –** ar jau buvo inicijuota konfigūravimo tarnyba

  - **Data –** „Exchange Server“ grąžinta keitimosi reikšmė

  - **DiagInfo –** „Exchange Server“ grąžinta informacija

  - **End\_TicketAuthError –** bet kokia klaida, įvykusi gaunant autentifikavimo bilietą po tarnybos kvietimo

  - **End\_TokenIsValid –** ar autentifikavimo bilietas galioja po tarnybos kvietimo

  - **EndingIdentityState –** nustato objektų pateiktą būseną, atlikus tarnybos kvietimus

  - **EwsHandler –** mainų metu grąžinta reikšmė

  - **FEServer –** mainų sąsaja, naudojama užklausai

  - **HResult –** rezultato kodas

  - **HttpStatus –** mainų grąžintas http būsenos kodas

  - **IsSupportedAuthResponse –** ar galime naudoti autentifikavimo tipą

  - **LastUpdateValueRegistry –** iš registro gauta maišos reikšmė

  - **LastUpdateValueRetrieved –** tarnybos kvietimo grąžinta maišos reikšmė

  - **MSDiagnostics –** mainų metu grąžinta reikšmė

  - **MsoHttpResult –** http API grąžinta surašytuvo vertė

  - **NeedRefresh –-** tai yra „true“ arba „false“ laukai, nurodantys, ar papildinio duomenys paseno ir mums reikia jį atnaujinti.

  - **PrimaryUrl –** pagrindinis URL, skirtas atlikti tarnybos kvietimą į

  - **RequestId –** mainų grąžinta reikšmė

  - **RequestTryCount –** mūsų atliktų tarnybos kvietimo bandymų skaičius

  - **RequestTryCount –** bandymo kreiptis dėl mainų kartai

  - **ResultChain –** rezultato kodo serijos iš kiekvieno tarnybos kvietimo bandymo

  - **EndingIdentityState –** nustato objektų pateiktą būseną prieš tarnybos kvietimą

  - **TelemetryId –** GUID, nurodantis unikalų vartotoją, informuoja, ar reikia atlikti kitus tarnybų kvietimus

#### <a name="officeextensibilitycatalogexchangegetmanifests"></a>Office.Extensibility.Catalog.ExchangeGetManifests

Duomenys apie sėkmingą papildinio deklaravimo duomenų atgavimo „Office 365“ nuomotojo administratoriui priskirtų papildinių problemos šalinimą. Naudota sveikatos metrikoms, diagramoms ir kliento problemų analizei.

Renkami šių laukų duomenys:

  - **CachedManifestsParsed** – talpykloje rastų deklaracijų skaičius

  - **IsAllReturnedManifestsParsed** – ar buvo galima analizuoti visas gautas deklaracijas

  - **ManifestsRequested** – reikiamų deklaracijų skaičius

  - **ManifestsReturned** – serverio grąžintų deklaracijų skaičius

  - **ManifestsToRetrieve** – planuojamų gauti iš serverio deklaracijų skaičius

  - **ReturnedManifestsParsed** – iš serverio grąžintų deklaracijų, kurios buvo sėkmingai išanalizuotos, skaičius

  - **TelemetryId** – GUID, nurodantis unikalų vartotoją

#### <a name="officeextensibilityuxfensureloadosfdll"></a>Office.Extensibility.UX.FEnsureLoadOsfDLL 

Seka Osf.DLL įkėlimo triktį. Aptinka DLL įkėlimo triktį, neleidžiančią veikti funkcijai.

Renkami šių laukų duomenys:

  - Nėra

#### <a name="officeextensibilityuxfensureloadosfuidll"></a>Office.Extensibility.UX.FEnsureLoadOsfUIDLL 

Seka OsfUI.DLL įkėlimo triktį. Aptinka DLL įkėlimo triktį, neleidžiančią veikti funkcijai.

Renkami šių laukų duomenys:

  - Nėra

#### <a name="officeextensibilityuxfensureosfshareddllload"></a>Office.Extensibility.UX.FEnsureOsfSharedDLLLoad 

Seka OsfShared.DLL įkėlimo triktį. Aptinka DLL įkėlimo triktį, neleidžiančią veikti funkcijai.

Renkami šių laukų duomenys:

  - Nėra

#### <a name="officeextensibilityvbatelemetrycomobjectinstantiated"></a>Office.Extensibility.VBATelemetryComObjectInstantiated

Renka informaciją apie automatizavimo serverio iškvietimą arba klientą VBA sprendimuose. Naudota suprasti VBA ir COM objektų sąveiką.

Renkami šių laukų duomenys:

  - **ComObjectInstantiatedCount** – COM objekto diegimų skaičius

  - **HashComObjectInstantiatedClsid** – COM objekto klasės identifikatoriaus maiša

  - **HashProjectName** – VBA projekto pavadinimo maiša

  - **TagId** – unikali žymė

#### <a name="officeextensibilityvbatelemetrydeclare"></a>Office.Extensibility.VBATelemetryDeclare 

Renka informaciją apie „Win32“ API iškvietimą VBA sprendimuose. Naudojamas suprasti VBA ir naudojimo sąveiką, bei papildyti saugos tyrimus.

Renkami šių laukų duomenys:

  - **DeclareCount** – aprašų skaičius

  - **HashDeclare** – DLL failo vardo maiša

  - **HashEntryPoint** – API pavadinimo maiša

  - **HashProjectName** – VBA projekto pavadinimo maiša

  - **IsPtrSafe** – ar aprašo pareiškimas suderinamas su skirtinga architektūra

  - **TagId** – unikali žymė

#### <a name="officeoutlookdesktopadd-insadd-inloaded"></a>Office.Outlook.Desktop.Add-ins.Add-inLoaded

Renka informaciją apie sėkmingą ir nesėkmingą „Outlook“ papildinio įkėlimą. Šie duomenys yra aktyviai stebimi, siekiant užtikrinti, kad „Outlook“ su kliento papildiniais veikia tinkamai. Šie duomenys naudojami problemoms aptikti ir tirti.

Renkami šių laukų duomenys:

  - **Standartinė HVA veikla**, kai nėra pasirinktinės apkrovos

#### <a name="officeoutlookmacaddinapiusage"></a>Office.Outlook.Mac.AddinAPIUsage

Surenka informaciją apie sėkmingą ir nesėkmingą papildinio vykdymą programoje „Outlook“. Šie duomenys yra aktyviai stebimi, siekiant užtikrinti, kad „Outlook“ su papildiniais veikia tinkamai. Šie duomenys naudojami problemoms aptikti ir tirti.

Renkami šių laukų duomenys:

- **AccountType** – su papildiniu susietos paskyros tipas 

- **Cookie** – papildinio naudojamas slapukas

- **DispId** – išsiuntimo identifikatorius 

- **EndTime** – laikas, kai papildinys baigėsi 

- **ExecutionTime** – papildinio vykdymo laikas 

- **Result** – papildinio naudojimo programoje „Outlook“ rezultatas 

- **StartTime** – laikas, kai papildinys buvo paleistas


#### <a name="officeoutlookmacaddineventapisusage"></a>Office.Outlook.Mac.AddinEventAPIsUsage

Surenka informaciją apie sėkmingą arba nesėkmingą papildinio vykdymą programoje „Outlook“. Šie duomenys yra aktyviai stebimi, siekiant užtikrinti, kad „Outlook“ su papildiniais veikia tinkamai. Šie duomenys naudojami problemoms aptikti ir tirti.

Renkami šių laukų duomenys:

- **AddinType** – papildinio tipas 

- **EventAction** – papildinio atliekamas veiksmas 

- **EventDispid** – išsiuntimo identifikatorius

- **EventResult**– veiksmo, kurį atliko papildinys, rezultatas 

#### <a name="officeoutlookmacaddininstallationfrominclientstore"></a>Office.Outlook.Mac.AddInInstallationFromInClientStore

Renka informaciją apie sėkmingą ar nesėkmingą „Outlook“ papildinio įdiegimą. Šie duomenys yra aktyviai stebimi, siekiant užtikrinti, kad „Outlook“ su papildiniais veikia tinkamai. Šie duomenys naudojami problemoms aptikti ir tirti.

Renkami šių laukų duomenys:

- **AccountType** – su papildiniu susietos paskyros 

- **FailureReason** – priežastis, kodėl papildinio nepavyko įdiegti 

- **MarketplaceAssetId** – parduotuvės papildinio identifikatorius 

- **Status** – papildinio diegimo būsena


#### <a name="officeprogrammabilityaddinsinternalsetconnectenterprise"></a>Office.Programmability.Addins.InternalSetConnectEnterprise

Įvykis generuojamas, kai COM papildinys yra įkeltas į įmonės įrenginį. Naudojama „Office“ papildinių pritaikymo, veikimo ir patikimumo problemoms nustatyti. 

Renkami šių laukų duomenys:

  - **Activity Result** – ryšio sėkmingumo būsena *[Šis laukas buvo pašalintas iš dabartinių „Office“ komponavimo versijų, bet gali būti rodomas senesnėse komponavimo versijose.]*

  - **AddinconnectFlag** – nurodo įkėlimo veikseną 

  - **AddinDescriptionV2** – papildinio aprašas

  - **AddinFileNameV2** – papildinio failo vardas, be failo kelio

  - **AddinFriendlyNameV2** – papildinio draugiškas vardas

  - **Add-inId** – papildinio klasės ID *[Šis laukas buvo pašalintas iš dabartinių „Office“ versijų, bet gali būti rodomas senesnėse versijose.]*

  - **AddinIdV2** – papildinio klasės ID

  - **AddinProgIdV2** – papildinio programos ID

 - **AddinProviderV2** – papildinio teikėjas

  - **Add-inTimeDateStamp** – papildinio laiko žyma iš DLL metaduomenų *[Šis laukas buvo pašalintas iš dabartinių „Office“ komponavimo versijų, bet gali būti rodomas senesnėse komponavimo versijose.]*

  - **AddinTimeDateStampV2** – papildinio laiko žyma iš DLL metaduomenų

  - **AddinVersionV2** – papildinio versija

  - **IsBootInProgress** – ar „Office“ taikomoji programa šiuo metu perkraunama
 
  - **LoadDuration** – papildinio įkėlimo trukmė
  
  - **LoadResult** – įkėlimo sėkmės būsena

  - **"OfficeArchitecture** " – „Office“ kliento architektūra

#### <a name="officevisiovisioaddonload"></a>Office.Visio.Visio.AddonLoad

Fiksuoja klaidas, kai nepavyksta įkelti sprendimo. Būtinas derinti priedų įkėlimo klaidas programoje „Visio“.

Renkami šių laukų duomenys:

  - **Data\_Load1Error:integer** – „Visio“ priedų įkėlimo metu įvykusios klaidos vertė

#### <a name="officevisiovisioaddonusage"></a>Office.Visio.Visio.AddonUsage

Fiksuoja klaidas, kai sprendimo funkcijoje yra klaida. Būtinas derinti priedų klaidas prieduose.

Renkami šių laukų duomenys:

  - **Data\_DocumentSessionLogID:string** – dokumento seanso identifikatorius

  - **Data\_IsEnabled**:**bool** – „true“, jeigu sprendimas yra įgalintas

  - **Data\_TemplateID:string** - šablono GUID, kuriame buvo įkeltas sprendimas. Pasirinktiniam sprendimui prisijungę kaip „0“

  - **Data\_AddOnID**:**string** – GUID įkeltam priedui identifikuoti

  - **Data\_Error**:**integer** – klaidos ID

### <a name="security-subtype"></a>*Saugos potipis*

Dokumento, funkcijos ir papildinio sąlygos, kurios gali pažeisti saugą, įskaitant produkto parengimą naujinti.

#### <a name="officeappguardcreatecontainer"></a>Office.AppGuard.CreateContainer

Renkame klaidų kodus ir informaciją, ar konteineris jau egzistavo, ar ne. Taip pat renkame nustatymo iš naujo įvykio klaidų kodus tam atvejui, jeigu nepavyktų sukurti konteinerio pirmuoju bandymu. Duomenys bus naudojami nustatyti procentą kartų, kai sėkmingai sukūrėme konteinerį „Office Application Guard“ programų paleidimui. Duomenys taip pat leis „Microsoft“ nustatyti ir iš sukurto konteinerio pašalinti klaidų kodus.

Renkami šių laukų duomenys:

- **ErrorCode1** – konteinerio nustatymo klaidos kodo tipas.  

- **ErrorCode2** – klaidos kodas iš kūrimo vykdymo. 

- **ErrorCode3** – papildomas klaidos kodas. 

- **Id** – konteinerio kūrimo unikalus identifikatorius (GUID).

- **ResetError** – Klaidos kodas, rodomas bandant nustatyti konteinerį iš naujo po nepavykusio bandymo.

- **ResetErrorCode1** – konteinerio nustatymo klaidos kodo tipas po nustatymo iš naujo komandos. 

- **ResetErrorCode2** – klaidos kodas iš kūrimo vykdymo po nustatymo iš naujo komandos.

- **ResetErrorCode3** – papildomas klaidos kodas po nustatymo iš naujo komandos.

- **ResetErrorType** – klaidos, paleidimo iš naujo metu, tipas: Creation (kūrimas), Preparing File (failo ruošimas) arba Launch (paleidimas).

- **WarmBoot** – nustato, ar konteineris jau sukurtas, ar ne.

#### <a name="officeappguardlaunchfile"></a>Office.AppGuard.LaunchFile

Šis įvykis nurodo „Application Guard“ paleisties failo vykdymą. Mes galėsime nustatyti, kiek procentų seansų sėkmingai paleidome „Word“, „Excel“ arba „PowerPoint“ failus ir nepavykusių bandymų klaidų kodus.

Renkami šių laukų duomenys:

- **AppId** – identifikuoja, kuri programa pradedama.

- **DetachedDuration** – identifikuoja bendrą sulietų veiksmų laiką. 

- **ErrorCode1** – konteinerio nustatymo klaidos kodo tipas.  

- **ErrorCode2** – klaidos kodas iš kūrimo vykdymo. 

- **ErrorCode3** – papildomas klaidos kodas. 

- **FileId**" – unikalus identifikatorius (GUID), kuris buvo grąžintas iš „Window“ API paleidus failą.

- **ID** – unikalusis identifikatorius (GUID), skirtas paleisti ir sukurti failą. Šis ID naudojamas susieti įvykius iš „Office“ ir „Windows“.

- **ResetError** – Klaidos kodas, rodomas bandant nustatyti konteinerį iš naujo po nepavykusio bandymo.

- **ResetErrorCode1** – konteinerio nustatymo klaidos kodo tipas po nustatymo iš naujo komandos. 

- **ResetErrorCode2** – klaidos kodas iš kūrimo vykdymo po nustatymo iš naujo komandos.

- **ResetErrorCode3** – papildomas klaidos kodas po nustatymo iš naujo komandos.  

- **ResetErrorType** – klaidos tipas: kūrimas, failo paruošimas arba paleidimas.



#### <a name="officesecurityactivationfilterclsidactivated"></a>Office.Security.ActivationFilter.CLSIDActivated

Seka kai konkretus klasės identifikatorius („Flash“, „Silverlight“ ir kt.) aktyvuojamas programoje „Office“. Naudojamas sekti „Flash“, „Silverlight“ ir „Shockwave“ valdiklių blokavimą galutiniams vartotojams.

Renkami šių laukų duomenys:

  - **ActivationType** – valdiklio aktyvavimo tipas

  - **Blocked** – „Office“ užblokuotas valdiklis

  - **CLSID** – valdiklio klasės identifikatorius

  - **Count** – kiek kartų valdiklis buvo aktyvuotas

#### <a name="officesecurityactivationfilterfailedtoregister"></a>Office.Security.ActivationFilter.FailedToRegister

Seka klaidos sąlygą, blokuojančią pavojingų valdiklių aktyvavimą programoje „Office“, bei skirtą saugos rizikai mažinti.

Naudojamas norint diagnozuoti klaidos būsenas, galinčias įtakoti galutinių vartotojų saugą, kad sumažinti saugos riziką.

Renkami šių laukų duomenys:

  - Nėra

#### <a name="officesecuritycomsecurityfileextensionlistfromservice"></a>Office.Security.ComSecurity.FileExtensionListFromService

Seka, ar pakavimo programos bloko plėtiniai buvo nuskaitomi iš konfigūravimo tarnybos arba ar naudojome kliento numatytąjį sąrašą. Naudota užtikrinti saugos rizikos mažinimo efektyvumą, saugantį programos „Office“ galutinius vartotojus.

Renkami šių laukų duomenys:

  - **RetrievedFromServiceStatus** – ar galėjome gauti failų plėtinių sąrašą blokavimui, jeigu ne, tuomet kokia buvo klaidos priežastis

#### <a name="officesecuritycomsecurityload"></a>Office.Security.ComSecurity.Load

Seka kada OLE objektas įkeltas į dokumentą. Naudota užtikrinti saugos rizikos mažinimo efektyvumą, saugantį programos „Office“ galutinius vartotojus.

Renkami šių laukų duomenys:

  - **Clsid** – OLE valdiklio klasės identifikatorius

  - **Count** – kiek kartų buvo įkeltas OLE valdiklis

  - **DocUrlHash** – unikali dokumentą nurodanti maiša. (Atkreipkite dėmesį – iš šio parametro neįmanoma sužinoti faktinės dokumento informacijos. Tai tiesiog unikalus dokumento pateikimas).

  - **IsCategorized** – ar buvo OLE valdiklis klasifikuotas įkelti į „Office“

  - **IsInsertable** – ar galima įterpti OLE valdiklį

#### <a name="officesecuritycomsecurityobjdetected"></a>Office.Security.ComSecurity.ObjDetected

Seka kada OLE objektas aptiktas dokumente. Naudota užtikrinti saugos rizikos mažinimo efektyvumą, saugantį programos „Office“ galutinius vartotojus.

Renkami šių laukų duomenys:

  - **Clsid** – OLE valdiklio klasės identifikatorius

  - **Count** – kiek kartų šis OLE objektas buvo aptiktas

  - **DocUrlHash** – unikali dokumentą nurodanti maiša. (Atkreipkite dėmesį – iš šio parametro neįmanoma sužinoti faktinės dokumento informacijos. Tai tiesiog unikalus dokumento pateikimas).

  - **IsCategorized** – ar OLE valdiklis klasifikuotas įkelti į „Office“

  - **IsInsertable** – ar galima įterpti OLE valdiklį

#### <a name="officesecuritycomsecuritypackageractivation"></a>Office.Security.ComSecurity.PackagerActivation

Seka saugos rizikos mažinimo rezultatą, blokuojantį pavojingus plėtinius, įdėtus „Office“ dokumentuose. Naudota užtikrinti saugos rizikos mažinimo efektyvumą, saugantį programos „Office“ galutinius vartotojus.

Renkami šių laukų duomenys:

  - **FromInternet** – ar dokumentas buvo iš interneto

  - **PackagerSetting** – koks buvo dabartinis pakavimo programos parametras

  - **TrustedDocument** – ar dokumentas buvo patikimas dokumentas

#### <a name="officesecuritycomsecuritypackageractivationerrors"></a>Office.Security.ComSecurity.PackagerActivationErrors

Seka saugos rizikos mažinimo, blokuojančio pavojingus plėtinius, įdėtus „Office“ dokumentuose, klaidos sąlygas. Naudota užtikrinti saugos rizikos mažinimo efektyvumą, saugantį programos „Office“ galutinius vartotojus.

Renkami šių laukų duomenys:

  - **Error** – klaidos kodas

  - **Plėtinys** – koks buvo failo plėtinys

  - **FromInternet** – ar dokumentas buvo iš interneto

  - **LinkedDocument** – ar tai buvo susietas dokumentas

  - **PackagerSetting** – koks buvo dabartinis pakavimo programos parametras

  - **TrustedDocument** – ar dokumentas buvo patikimas


#### <a name="officesecuritymacrointernetvbablockenabled"></a>Office.Security.Macro.InternetVBABlockEnabled

Seka, ar pas klientą yra įgalintas interneto parametro makro komandos blokas. Įvertina saugos rizikos mažinimą, saugantį nuo kenkėjiškų makrokomandų.

Renkami šių laukų duomenys:

  - Nėra

#### <a name="officesecuritymacropolicydigsigtrustedpublishers"></a>Office.Security.Macro.PolicyDigSigTrustedPublishers

Seka, ar makrokomanda buvo patvirtinta kaip esanti iš patikimo leidėjo. Naudota užtikrinti saugos rizikos mažinimo efektyvumą, saugantį programos „Office“ galutinius vartotojus.

Renkami šių laukų duomenys:

  - **Policy** – ar strategija nustatyta, nenustatyta arba negalima

#### <a name="officesecuritymacroprompted"></a>Office.Security.Macro.Prompted

Seka, kai vartotojas yra raginamas įgalinti VBA makrokomandas. Naudojama, atsižvelgiant į saugos incidentus, įvertinti VBA makrokomandų ir disko būsimų saugos mažinimo priemonių paplitimą, ribojantį makrokomandos vykdymą.

Renkami šių laukų duomenys:

  - **PromptType** – kokio tipo buvo rodomas raginimas

  - **VBAMacroAntiVirusHash** – makrokomandos antivirusinė maiša

  - **VBAMacroAntiVirusHRESULT** – antivirusinio vertinimo rezultatas

#### <a name="officesecuritymacrovbasecureruntimesessionenablestate"></a>Office.Security.Macro.VBASecureRuntimeSessionEnableState

Seka kiekvieną AMSI apdorojimo laiko tikrinimą, atliekamą vykdant makrokomandą. Seka makrokomandos vykdymo AMSI apdorojimo laiko efektyvumą ir nustatyto klaidas, kurios gali turėti įtakos galutinių vartotojų saugumui.

Renkami šių laukų duomenys:

  - **IsRegistry** – ar administratorius registre atliko pakeitimus

  - **State** – kokia yra saugaus vykdymo laiko būsena

#### <a name="officesecuritymacroxl4prompted"></a>Office.Security.Macro.XL4Prompted

Seka, kada vartotojas raginamas įgalinti XL4 makrokomandas. Naudojamas siekiant įvertinti XL4 makrokomandų paplitimą programoje „Excel“, kad būtų galima užtikrinti būsimas riziką mažinančias saugos priemones, blokuojančias XL4 pagal numatytuosius parametrus, bei atsižvelgti į saugos incidentus, atsirandančius netinkamai naudojant XL4 makrokomandas.

Renkami šių laukų duomenys:

  - **PromptType** – kokio tipo buvo rodomas raginimas


#### <a name="officesecurityocxufiprompt"></a>Office.Security.OCX.UFIPrompt

Seka, kada saugos raginimas rodomas vartotojui, kai įkeliamas „ActiveX“ valdiklis, pažymėtas kaip nesaugus inicijavimui. Skirtas sekti UFI „ActiveX“ valdiklių paplitimas „Office“ dokumentuose, kad atsižvelgiant į saugos incidentus, užtikrinti rizikos mažinimą (pvz. užrakinant valdiklius).

Renkami šių laukų duomenys:

  - **IsFromInternet** – ar dokumentas atidaromas internete

  - **IsSecureReaderMode** – ar dokumentas atidaroma saugiame skaitytuve

  - **OcxTrustCenterSettings** – koks yra dabartinis „ActiveX“ parametras


#### <a name="officesecuritysecurereaderhostopeninosr"></a>Office.Security.SecureReaderHost.OpenInOSR

Seka atidaryto apsaugoto rodinio užbaigimą. Skirtas nustatyti sąlygoms, dėk kurių įvyko triktis atidarant failus apsaugotame rodinyje, bei kurios daro įtaką vartotojų saugumui ir produktyvumui.

Renkami šių laukų duomenys:

  - Nėra

## <a name="product-and-service-usage-data-events"></a>Produktų ir tarnybų duomenų naudojimo įvykiai

Toliau pateikiami šios kategorijos duomenų potipiai:

- [Taikomosios programos funkcijų sėkmingas atlikimas](#application-feature-success-subtype)
- [Taikomosios programos būsena ir įkrova](#application-status-and-boot-subtype)
- [„Office“ pritaikymo neįgaliesiems konfigūracija](#office-accessibility-configuration-subtype)
- [Privatumas](#privacy-subtype)


### <a name="application-feature-success-subtype"></a>*Taikomosios programos funkcijos sėkmingo atlikimo potipis*

Sėkmingos taikomosios programos funkcijos. Tik taikomosios programos ir dokumentų atidarymas ir uždarymas, failų redagavimas ir failų bendrinimas (bendradarbiavimas).

#### <a name="accountaction"></a>account.action

Būtina siekiant užtikrinti tinkamą paskyros konfigūracijos veikimą ir naudojimą, kad būtų galima stebėti paskyros kūrimo sveikatą, galimybes įtraukti naujų el. pašto paskyrų ir stebėti paskyros dalinius atkūrimus. 

Renkami šių laukų duomenys: 

- **account_calendar_count** – kiek kalendorių turi paskyra
 
- **action** – atliekamo veiksmo tipas, pvz., create_account, delete_account.
 
- **duration_seconds** – veiksmo trukmė
 
- **entry_point** – veiksmo įvesties vieta, kaip vartotojas pradėjo veiksmą
 
- **has_hx** – ar įrenginyje yra paskyra, kuri naudoja mūsų naują pašto sinchronizavimo paslaugą. Nebūtinai paskyra, su kuria buvo atliktas veiksmas
 
- **is_hx** – paskyra, naudojanti mūsų naują pašto sinchronizavimo tarnybą
 
- **is_shared_mailbox** – ar veiksmas susijęs su bendrinama pašto dėžute
 
- **number_of_accounts** – bendras paskyrų, kuriose atliekamas veiksmas, skaičius
 
- **result** – veiksmo rezultatas, pvz., sėkmingas, nepavyko.
   
- **server_type** – paskyros serverio tipas, panašus į account_type
 
- **shared_type** – bendrinamos paskyros tipas (jei paskyra bendrinama)
 
- **scope** – veiksmo aprėptis, jei norite panaikinti paskyrą, this_device arba all_devices
 
- **total_calendar_accounts** – kalendoriaus paskyrų skaičius veiksmo atlikimo metu
 
- **total_email_accounts** – el. pašto paskyrų skaičius veiksmo atlikimo metu
 
- **total_file_accounts** – failų paskyrų skaičius veiksmo atlikimo metu

#### <a name="accountlifecycle"></a>account.lifecycle

Šis įvykis renkamas siekiant užtikrinti tinkamą paskyros konfigūracijos veikimą ir naudojamas, kad būtų galima stebėti paskyros kūrimo sveikatą, galimybes įtraukti naujų el. pašto paskyrų ir stebėti paskyros dalinius atkūrimus.

Renkami šių laukų duomenys: 

- **account_creation_source** – pasirinktinė ypatybė, kuri naudojama norint rasti ir diagnozuoti bet kokias triktis, kylančias kuriant paskyrą, kai veiksmo tipas yra „įtraukti“.  Galimos reikšmės, tokios kaip vienkartinis prisijungimas (SSO), create_new_account, rankinis ir t. t.

- **action** – veiksmo, kuris buvo atliktas su paskyra, tipas, pvz., įtraukimas, pašalinimas arba nustatymas iš naujo

#### <a name="addnewaccountstep"></a>add.new.account.step

Šis įvykis leidžia mums nustatyti vartotojo progresą naujos paskyros kūrimo formoje.  Jis nurodo, ar vartotojas perėjo prie kito veiksmo, ar išėjo.  Mums reikia šios informacijos, kad galėtume nustatyti, ar yra veiksmų, kuriuos atlikdami vartotojai išeina, ir užtikrinti, kad jie sėkmingai sukurtų paskyrą. 

Renkami šio lauko duomenys: 

- **OTAddAccountCurrentStep** – gali turėti tokias reikšmes: profile_form, redirect_mobile_check, mobile_check_success

#### <a name="apperror"></a>app.error

Stebi kritinių programų klaidas, kad galėtume išvengti problemų, dėl kurių programa gali užstrigti arba neleisti skaityti el. laiškų.

Renkami šių laukų duomenys: 

- **clientName** – debesies failo, kuriame įvyko klaida, kliento vardas, jei taikoma.

- **cloudfile_error_type** – įvykusios debesies failo klaidos tipas, jei taikoma.

- **cloudfile_response_type** – įvykusios debesies failo klaidos atsako pavadinimas, jei taikoma.

- **component_name** – programos, kurioje įvyko klaida, komponento pavadinimas, pvz., paštas ar kalendorius.

- **debug_info** – informacija apie klaidą, kuri įvyko dėl debesies failo, kad būtų galima nustatyti, kodėl įvyko klaida.

- **error_origin_identifier** – klaidos, kurį įvyko su juodraščiu, kilmė, jei taikoma.

- **error_type** – įvykusios klaidos tipas. Kai kurie pavyzdžiai apima juodraščio įrašymą, juodraščio siuntimą ir debesies failo klaidas.

- **exdate** -išplėstinės taisyklės data (taikoma tik paskyros pasikartojimo klaidoms) *[Šis laukas buvo pašalintas iš dabartinės „Office“ komponavimo versijos, bet vis tiek gali būti rodomas senesnėse komponavimo versijose.]*

- **exrule** – išplėstinės taisyklės reikšmė (taikoma tik paskyros pasikartojimo klaidoms) *[Šis laukas buvo pašalintas iš dabartinės „Office“ komponavimo versijos, bet vis tiek gali būti rodomas senesnėse komponavimo versijose.]*

- **has_attachments** – nurodo, ar juodraštis, kuriame įvyko klaida, turi priedų, jei taikoma.

- **is_IRM_protected** – nurodo, ar juodraštis, kuriame įvyko klaida, yra apsaugotas taikant informacijos teisių valdymą, jei taikoma.

- **is_legitimate** – nurodo, jei klaida gaunama iš programavimo klaidos. Programavimo klaidos laikomos neteisėtomis.

- **is_local** – nurodo, ar juodraštis, kuriame įvyko klaida, buvo sinchronizuotas su serveriu, jei taikoma.

- **is_recoverable** – nurodo, ar klaida gali būti ištaisyta, ar tai yra neištaisoma klaida.

- **rdate** – pasikartojančios taisyklės data (taikoma tik paskyros pasikartojimo klaidoms) *[Šis laukas buvo pašalintas iš dabartinės „Office“ komponavimo versijos, bet vis tiek gali būti rodomas senesnėse komponavimo versijose.]*

- **rrule** – pati pasikartojanti taisyklė (taikoma tik paskyros pasikartojimo klaidoms) *[Šis laukas buvo pašalintas iš dabartinės „Office“ komponavimo versijos, bet vis tiek gali būti rodomas senesnėse komponavimo versijose.]*

- **rrule_error_message** – pasikartojančios taisyklės analizės klaidos pranešimas (taikoma tik paskyros pasikartojimo klaidoms) *[Šis laukas buvo pašalintas iš dabartinės „Office“ komponavimo versijos, bet vis tiek gali būti rodomas senesnėse komponavimo versijose.]*

- **rrule_error_type** – pasikartojančios taisyklės analizės klaidos tipas (taikoma tik paskyros pasikartojimo klaidoms) *[Šis laukas buvo pašalintas iš dabartinės „Office“ komponavimo versijos, bet vis tiek gali būti rodomas senesnėse komponavimo versijose.]*

- **status_code** – įvykusios klaidos būsenos kodas. Padeda mums suprasti klaidos priežastį.

Visi simboliai taip pat gali būti ypatybės. Padeda mums suprasti laiško juodraščio tekste esančius simbolius, kai įvyko klaida. Pavyzdžiui, galimos ypatybės yra „a“, „b“, „c“.

#### <a name="applaunchreport"></a>app.launch.report

Šis įvykis leidžia mums aptikti ir išspręsti problemas, kai „Outlook“ paleidžiama lėtai arba nevisiškai, todėl vartotojams tampa sudėtinga naudoti mūsų programą. Apima informaciją apie tam tikras įgalintas funkcijas ir kiek laiko buvo truko dalių paleistis.

Renkami šių laukų duomenys: 

- **is_agenda_widget_active** – nurodo mums, ar aktyvus darbotvarkės valdiklis.

- **is_alert_available** – nurodo mums, ar programa sukonfigūruota taip, kad pranešimuose būtų leidžiami įspėjimai.

- **is_background_refresh_available** – nurodo, ar programa sukonfigūruota taip, kad būtų galima atnaujinti fone.

- **is_badge_available** – nurodo mums, ar programa sukonfigūruota taip, kad pranešimuose būtų leidžiami ženkleliai.

- **is_intune_managed** – nurodoma, ar programą valdo „Intune“.

- **is_registered_for_remote_notifications** – nurodo, ar programa užregistruota nuotoliniams pranešimams.

- **is_sound_available** – nurodo mums, ar programa sukonfigūruota taip, kad pranešimuose būtų leidžiami garsai.

- **is_watch_app_installed** – nurodo, ar buvo įdiegta „Outlook“ stebėjimo programa.

- **is_watch_paired** – nurodo, ar „Outlook“ stebėjimo programa susieta su pagrindine „Outlook“ programa.

- **launch_to_db_ready_ms** – nurodo, kiek laiko „Outlook“ programa praleido nuo paleidimo iki duomenų bazės paruošimo.

- **num_calendar_accounts** – nurodo kalendoriaus paskyrų programoje skaičių.

- **num_cloud_accounts** – nurodo saugyklos paskyrų programoje skaičių.

- **num_hx_calendar_accounts** – nurodo, kalendoriaus paskyrų skaičių programoje, kuri jungiasi prie mūsų naujosios pašto sinchronizavimo tarnybos.

- **num_hx_mail_accounts** – nurodo, el. pašto paskyrų skaičių programoje, kuri jungiasi prie mūsų naujosios pašto sinchronizavimo tarnybos.

- **num_cloud_accounts** – nurodo el. pašto paskyrų programoje skaičių.

#### <a name="calendaraction"></a>calendar.action

Naudojama stebėti bet kokį galimą neigiamą poveikį jūsų gebėjimui atlikti pagrindinius kalendoriaus veiksmus, pvz., kurti ar redaguoti įvykius.  Įvykis taip pat gali apimti ypatybių pavadinimų seką ir nurodyta, ar jie buvo pakeisti. Pvz., „title_changed“, „online_meeting_changed“ ir „description_changed“ yra ypatybių pavadinimai, kurie įtraukti, kad padėtų mums suprasti, ar yra kokių nors su tam tikromis ypatybėmis susijusių problemų.

Renkami šių laukų duomenys: 

- **account_sfb_enabled** – padeda užtikrinti tinkamą „Skype“ verslui konfigūraciją. 

- **action** – veiksmo, kuris buvo atliktas su kalendoriumi, tipas. Apima tokius veiksmus, kaip atidarymą, redagavimą, sparčiųjų klavišų įtraukimą, atidėjimą ir t. t. Padeda užtikrinti, kad kalendoriaus patirtis veiktų taip, kaip numatyta, ir niekas nesugedo 

- **action_result** – veiksmo, kuris buvo atliktas naudojant kalendoriaus komponentus, rezultatas. Tai gali būti tokios reikšmės kaip sėkminga, nepavyko, nežinoma ir baigėsi skirtasis laikas. Naudojama stebėti sėkmės koeficientą veiksmams ir nustatyti, ar yra plačiai paplitusi problema dėl kalendoriaus veiksmų. 

- **attendee_busy_status** – dalyvio, su kuriuo susijęs veiksmas, užimtumo būsena. Ši reikšmė gali būti laisvas, užimtas arba neapsisprendęs. Padeda suprasti, ar kilo problemų dėl veiksmų, susijusių su tam tikra užimtumo būsena. 

- **availability** – pasiekiamumo reikšmė, jei užimtumo reikšmė susitikimo metu pakeista į laisvas / užsiėmęs. Padeda suprasti, ar kilo problemų su tam tikros prieinamumo reikšmės nustatymu. 

- **calendar_onlinemeeting_default_provider** – apima numatytąjį internetinių susitikimų teikėją, skirtą naudoti su serverio palaikomų internetinių susitikimų kūrimu. Apima „Skype“, „Skype“ verslui, „Hangout“ ir „Teams“ verslui tipus. Padeda nustatyti potencialias problemas kuriant internetinius susitikimus tam tikruose teikėjuose. 

- **calendar_onlinemeeting_enabled** – teisinga, jei kalendorius palaiko serverio palaikomą internetinių susitikimų kūrimą, pagrįstą numatytuoju internetinių susitikimų teikėju. Padeda suprasti, ar yra kokių nors problemų dėl kalendorių, kuriuose įgalinti internetiniai susitikimai. 

- **calendar_type** – kalendoriaus, kurio įvykis įjungtas po to, kai vartotojas suredagavo šį susitikimą, tipas. Galimos reikšmės yra pirminis, antrinis, bendrinamas ir grupės. Padeda suprasti, ar kilo problemų su tam tikro tipo kalendoriais. 

- **delete_action_origin** – atlikto naikinimo veiksmo kilmė. Apima reikšmes, pvz., naršymo juostos įrankių juostą ir kapsulės įrankių juostą.  Padeda suprasti, ar kyla problemų dėl susitikimų panaikinimo iš tam tikros vietos. 

- **distribution_list_count** – dalyvių, kurie yra platinimo sąrašuose, skaičius. Padeda sekti, ar yra problemų, susijusių su dalyviais, kurie yra įtraukti platinimo sąrašus. 

- **guest_count** – susitikime esančių svečių skaičius.  Padeda užtikrinti tinkamą svečių įtraukimą. 

- **is_all_day** – naudojama kartu su „meeting_duration“ siekiant nurodyti, ar susitikimas vyksta visą dieną. Padeda suprasti, ar yra kokių nors problemų, susijusių su veiksmais, atliekamais visą dieną vykstančių susitikimų metu. 

- **is_location_permission_granted** – ar vartotojas suteikė taikomosios programos sistemos vietos teises. Jei suteikiamas vietos leidimas, taikomoji programa gali pateikti papildomą naudingumo informaciją vartotojo sąsajoje. Žinodami, ar suteikiamas leidimas naudoti vietą, turėsime galimybę sužinoti, kaip dažnai vartotojams rodoma papildoma naudingumo informacija.

- **is_organizer** – padeda suprasti, ar organizatorius gali tinkamai redaguoti ir kurti susitikimus. 

- **is_recurring** – padeda suprasti, ar kyla problemų, konkrečiai paveikiančių pasikartojančius susitikimus. 

- **launch_point** – veiksmo pradžios taškas. Gali turi reikšmes, pvz., valdiklio antraštė, valdiklių poraštė, visos dienos valdiklis ir kalendoriaus nuoroda. Padeda suprasti, nuo ko buvo pradėtas veiksmas. 

- **location_count** – vietų, kurios nustatytos sukūrus arba redagavus įvykį, skaičius. Padeda suprasti, ar kilo kokių nors problemų kuriant ar redaguojant įvykius kai naudojamas tam tikras vietų skaičius. 

- **location_selection_source_type** – vietos pasirinkimo šaltinio tipas. Gali būti tokios reikšmės kaip vietos pasiūlymai, pasirinktinė vieta ar esama vieta. Padeda diagnozuoti problemas dėl vietos pasirinkimo iš tam tikrų šaltinių. 

- **location_session_id** – susitikimo vietos parinkiklio seanso ID. Padeda diagnozuoti problemas dėl vietos pasirinkimo siekiant ją įtraukti į susitikimą. 

- **location_type** – pasirinktos vietos tipas.  Apima tipus, pvz., pasirinktinė vieta, konferencijų salė ir „Bing“. Padeda suprasti problemas dėl atitinkamų susitikimo vietų tipų. 

- **meeting_duration** – susitikimo trukmė.  Padeda užtikrinti, kad susitikimai konfigūruojami naudojant teisingus laikus. 

- **meeting_insights_type** – įvykio informacijos susitikimo įžvalgų tipas.  Apima failą ir pranešimą. Padeda suprasti rodomų susitikimo įžvalgų skaičių. 

- **meeting_type** – su veiksmu susieto internetinio susitikimo tipas.  Apima „Skype“, „Skype“ verslui, „Hangout“ ir „Teams“ verslui tipus. Padeda suprasti, ar susitikimai internete tinkamai sukonfigūruoti. 

- **online_meeting_provider_switch_type** – perjungimo, kurį vartotojas atlieka tarp susitikimų internetu paslaugų teikėjų, tipas. Padeda mums suprasti vartotojo pasirinkimą naudoti funkciją.

- **origin** – kalendoriaus veiksmo kilmė. Apima tokius tipus kaip darbotvarkė, kalendorius, valdiklio darbotvarkė ir t. t. Padeda mums užtikrinti geresnę sąveiką tarp kalendoriaus komponentų 

- **recurrence_scope** – susitikimo pasikartojimo įvykis – pasikartojimas ar seka.  Padeda suprasti, ar kyla problemų redaguojant skirtingų pasikartojimo tipų susitikimus. 

- **reminder_time** – susitikimo priminimo laikas, jei buvo pakeistas.  Naudojamas užtikrinti, susitikimo priminimo laikas įrašytas tinkamai. 

- **reminders_count** – įvykio priminimų skaičius, jei buvo pakeisti priminimai. Padeda nustatyti problemas dėl kelių įvykio priminimų. 

- **sensitivity** – susitikimo konfidencialumas. Apima tokius tipus kaip: įprastas, asmeninis, privatu ir konfidencialus. Padeda suprasti, ar tinkamai konfigūruojamas susitikimo konfidencialumas. 

- **session_duration** – seanso trukmė milisekundėmis. Padeda suprasti, ar kyla problemų, dėl kurių padidėja laiko trukmė, būtina kalendoriaus veiksmui atlikti. 

- **shared_calendar_result** – veiksmo, atlikto su bendrinamu kalendoriumi, rezultatas. Galimos reikšmės yra gerai, nėra teisių, nežinoma, savininkas vietinis ir savininkas yra grupė. Padeda suprasti su bendrinamais kalendoriais atliekamų veiksmų patikimumą. 

- **time_picker_origin** – laiko parinkiklio, skirto įrašyti veiksmą, kilmė. Apima reikšmes, pvz., daugiau parinkčių ir mažiau parinkčių. Padeda suprasti, kaip vartotojas naršė srautą, kad galėtų įrašyti susitikimą ir užtikrinti tinkamą jo funkcionavimą. 

- **title** – automatiškai pasiūlytas pavadinimas iš programos apibrėžtų reikšmių. Apima tokias reikšmes kaip „Skambutis“, „Pietūs“ ir „Skype“. Padeda suprasti, ar tinkamai sukonfigūruotas automatiškai pasiūlytas pavadinimas. 

- **txp** – įvykio užsakymo ar rezervacijos tipas, jei toks yra. Apima tipus, pvz., įvykio rezervavimas, skrydžio rezervavimas, automobilių nuomos rezervavimas ir t. t. Padeda suprasti, ar užsakymo / rezervavimo kortelės veikia tinkamai. 

- **upcoming_event_count** – artėjančių įvykių, rodomų artėjančių įvykių rodinyje, skaičius. Padeda suprasti, ar kilo problemų su artėjančių įvykių rodiniu. 

- **upcoming_event_seconds_until_event** – sekundžių, likusių iki kito artėjančio įvykio pradžios, skaičius. Padeda suprasti įprastus įvykius, kurie rodomi artėjančių įvykių rodinyje. 

- **value** – konkretaus veiksmo reikšmė, pvz., įspėjimo delsos trukmė ar kartojimas iki kategorijos. Padeda suprasti veiksmo atlikimo kontekstą. 

#### <a name="combinedsearchuse"></a>combined.search.use

Naudojama stebėti galimą neigiamą poveikį jūsų gebėjimui atlikti pagrindines ieškos funkcijas, pvz., ieškoti el. laiškų, kontaktų ar įvykių.

Toliau nurodyti laukai renkami „Android“ ir „Android“: 

- **account_switcher_action_type** – šis veiksmų tipas seka, ar vartotojas naudojo paskyros perjungiklį paprastam aptikimui, ar nusprendė perjungti paskyrą

- **action_type** – veiksmo, kuris buvo atliktas ieškai, tipas. Nurodo, ar ieška buvo pradėta, pasikartojanti, ar užbaigta, ir kokių veiksmų buvo imtasi atliekant iešką, t. y. ar buvo naudotas mikrofonas. Padeda užtikrinti tikslias ir naudingas paieškas. 

- **conversation_id** – unikalus kiekvieno ieškos seanso ID (pvz., kiekvieną kartą, kai vartotojas įveda ieškos lauką)

- **entrance_type** – nustato, kaip vartotojas pradėjo ieškos užklausą: ieškos skirtuke, naudodamas nulinę užklausą, ieškos antraštę ar ieškos rezultatą. 

- **has_contact_results** – nurodo, ar kontakto rezultatai rodomi ieškos užklausoje

- **include_deleted** – ar ieškos rezultatuose rodomos panaikintos parinktys 

- **is_best_match_suggestion** – ar pasirinktas ieškos patarimas yra tiksliausias atitikmuo.

- **is_ics_external_data** – fiksuoja, ar įtrauktas įvykis yra vidinis (pvz.,  įtraukta į „Outlook“ į „Outlook“ kalendorių) ar išorinis (t. y. įtraukta iš kitos el. pašto programos, pvz., iš „Gmail“ į „Outlook“ kalendorių).

- **is_network_fully_connected** – užuominai apie neprisijungus atliktos paieškos priežastį gauti. Jei tinklas yra prijungtas ir ieška neprijungta, priežastis greičiausiai bus serverio skirtojo laiko pabaiga

- **is_offline_search** – ar ieškos seanse yra autonominė ieška, pagrįsta HX grąžintais ieškos rezultatais

- **re_enter_search_tab** – Bulio funkcija, skirta nurodyti, ar vartotojas perjungė skirtukus prieš pasirinkdamas ieškos rezultatą

- **result_selected_type** – su kokio tipo duomenimis, kurie buvo rodomi, sąveikavo vartotojas, pvz., peržiūrėjo visus kontaktus, pokalbius, įvykius ir t. t. 

- **search_conversation_result_data** – apima duomenis apie pokalbį, pasirinktą iš ieškos rezultatų, įskaitant paskyros tipą (HX, AC ir t. t.), nesvarbu, ar pranešimas yra debesies tarnyboje, ir ar rodomas puslapio poslinkis yra tas pats puslapis kaip pirmasis laiškas. 

- **search_origin** – kaip buvo pradėta ieška, pvz., naudojant balso asistentą, „Cortana“, klaviatūros įvestį ir pan. 

- **search_scope** – eilutė, nurodanti, kokio tipo paskyroje vartotojas atliko iešką (t. y. „Exchange“, „Gmail“ ir t. t.), ar ji buvo atliekama visose paskyrose. 

- **search_suggestion_type** – nurodo, kas slypi už ieškos pasiūlymo, t. y. yra rašybos korekcija? Atsižvelgiant į retrospektyvą? Automatinis užbaigimas?

- **search_request_reason** – nurodo priežastį, kodėl iš programos buvo išsiųsta ieškos užklausa, taip nurodant komponento ar vartotojo veiksmą, kuris sukėlė iešką.

- **search_result_filter_type** – nurodo, kokio tipo filtras buvo pritaikytas paieškai: rodyti visus ar tik priedus

Toliau nurodyti laukai renkami „Outlook Mobile“ „iOS“ programose. 

- **action** – veiksmo, kuris buvo atliktas ieškai, tipas. Nurodo, ar ieška buvo pradėta, pasikartojanti, ar užbaigta, ir kokių veiksmų buvo imtasi atliekant iešką, t. y. ar buvo naudotas mikrofonas. Padeda užtikrinti tikslias ir naudingas paieškas.

- **answer_result_selected_count** – seka, kiek kartų ieška buvo „sėkminga“, t. y. ar vartotojas rado pageidaujamą žmogų? Sukūrė el. laišką? Pažymėjo laišką? 

- **contact_result_in_full_list_selected_count** – seka, kiek kartų vartotojas paprašė „peržiūrėti visus kontaktus“ visame sąraše ir jis buvo pasirinktas bendro paieškos seanso metu

- **contact_result_selected_count** – seka, kiek kontakto rezultatų buvo pasirinkta bendro paieškos seanso metu

- **conversation_result_selected_count** – seka, kiek pokalbių buvo pasirinkta bendro paieškos seanso metu

- **mail_paging_gesture_count** – seka, kiek pašto ieškos pranešimų gestų buvo atlikta bendro ieškos seanso metu

- **mail_requests_count** – seka, kiek pašto ieškos užklausų buvo išsiųstos kombinuotos ieškos seanse

- **people_filter_selected_contacts_count** – seka, kiek kontaktų buvo pasirinkta žmonių filtruose

- **search_session_ended_type** – nurodo, kur buvo baigta ieška, nes ji buvo atšaukta arba atnaujinta užklausa

- **search_suggestion_type** – nurodo, kas slypi už ieškos pasiūlymo, t. y. yra rašybos korekcija? Atsižvelgiant į retrospektyvą? Automatinis užbaigimas?

- **see_all_contacts_selected_count** – seka, kiek kartų buvo pasirinkta „peržiūrėti visus kontaktus“ bendro paieškos seanso metu

- **subtab_type** – seka, kur vartotojas pasirinkto rezultatą ir iš kurio rezultatų skirtuko

- **top_mail_result_selected_count** – seka, kiek kartų vartotojas pasirenka jam pateiktus populiariausius rezultatus.

- **ui_reload_result_count** – fiksuoja vartotojo sąsajos perkrovimo laiką, dėl rezultatų rinkinio naujinimo (atitinkamos užklausos metu)

- **ui_reload_result_time** – fiksuoja visą laiką, paleistą vartotojo sąsajos perkrovimui, dėl rezultatų rinkinio naujinimo (atitinkamos užklausos metu)

- **ui_reload_status_count** – fiksuoja vartotojo sąsajos perkrovimo laiką, dėl būsenos naujinimo (atitinkamos užklausos metu)

- **ui_reload_status_time** – fiksuoja visą laiką, paleistą vartotojo sąsajos perkrovimui, dėl būsenos naujinimo (atitinkamos užklausos metu)

#### <a name="composemailaccessory"></a>compose.mail.accessory

Šis įvykis leidžia nustatyti ir išspręsti problemas, susijusias su pagrindiniais laiškų kūrimo veiksmais, kad nekiltų problemų, susijusių su failo pridėjimu, fotografavimu kaip priedo ar jūsų prieinamumo siuntimu.

Renkami šių laukų duomenys: 

- **action** – nurodo veiksmą, kurį buvo bandyta atlikti registruojant veiksmą. Kai kurie pavyzdžiai apima failo pridėjimą ir didesnio parinkčių kiekio pateikimą.

- **icon_name** - nurodo piktogramos, kuri buvo rodoma registruojant veiksmą, pavadinimą.
 
- **Origin** – mums nurodo veiksmo kilmę. Galimos reikšmės yra quick_reply ir full_screen.

- **toolbar_type** – Praneškite mums apie įrankių juostos tipą, kuris pateikiamas puslapyje kurti. Galimos reikšmės yra compose_actions ir formatavimas.


#### <a name="conversationviewaction"></a>conversation.view.action

Naudojama stebėti galimą neigiamą poveikį jūsų gebėjimui peržiūrėti ir atsakyti į el. laiškus

Renkami šių laukų duomenys:

- **contains_mention** – nurodo, ar pokalbyje buvo naudojamas @ paminėjimas, kad galėtume nustatyti problemas su paminėjimais laiškuose

- **conversation_type** – nurodo, kokio tipo el. laiško rodinys buvo generuotas, pvz., vieno laiško rodinys ar kelių laiškų rodinys. Padeda nustatyti problemas, susijusias su konkrečiu laiško tipu jūsų el. pašto pokalbių rodinyje.

- **hx_error_type** – praneša mums, kokia klaida įvyko, kai tarnyba uždraudė pašalinti, atnaujinti arba įtraukti atsakymą į laišką.

- **hx_string_tag** – praneš mums klaidos žymę tarnybos kode

- **reaction_origin** – nurodo mums kilmę įvykio, kur vartotojas reagavo 

- **reaction_type** – nurodo mums vartotojo reakcijos tipą

- **suggested_reply_char_count** – nurodo, kiek simbolių siūloma pateiktame atsakyme (jei galima), kad galėtume nustatyti su pasiūlymais susijusius nesklandumus

- **suggested_reply_click_pos** – nurodo, kurioje padėtyje buvo sugeneruotas pateiktas atsakymas (jei galima), kad galėtume nustatyti konkretaus pasiūlymo nesklandumus

- **suggested_reply_type** – nurodo šio veiksmo siūlomo atsakymo tipą. Galimos reikšmės yra text, send_avail ir create_meeting.

- **use_default_quick_reply_mode** – nurodo, ar buvo naudojamas numatytasis spartaus atsakymo režimas, kad galėtume nustatyti problemas, susijusias su el. pašto spartaus atsakymo patirtimi

#### <a name="draftaction"></a>draft.action

Naudojama stebėti galimą neigiamą poveikį jūsų gebėjimui kurti ir įrašyti el. pašto priedus.

Renkami šių laukų duomenys: 

- **action** – veiksmo tipas, pvz., įrašyti, atmesti.
 
- **draft_message_id** juodraščio laiško ID

- **is_groups** – ar juodraštis siunčiamas į / iš grupės aplanko
 
- **origin** – kur juodraštis buvo inicijuotas, pvz., laiško informacija, kurti.

- **smart_compose_model_version** – seka, kuri išmaniojo komponavimo modelio versija yra naudojama

- **suggestions_requested** – nurodo, kiek išmaniojo rašymo pasiūlymų prašoma

- **suggestions_results** – išmaniojo rašymo pasiūlymų rezultatas, t. y. priimtas, atmestas

- **suggestions_returned** – nurodo, kiek išmaniojo rašymo pasiūlymų pateikta iš serverio

- **suggestions_returned** – nurodo, kiek išmaniojo rašymo pasiūlymų pateikta vartotojui
 
- **thread_id** – pokalbio juodraščio, su kuriuo jis yra susietas, gijos ID

#### <a name="draganddrop"></a>drag.and.drop

Šis įvykis leidžia mums nustatyti, ar nuvilkimo veiksmas buvo sėkmingas, ar ne.  Jis naudojamas siekiant užtikrinti, kad nuvilkimo funkcija veiktų tinkamai tarp programų tiek paliekant įvykį „Outlook“, tiek nuvelkat įvykį iš „Outlook“.  Turėdami šiuos duomenis galime užtikrinti, kad veiksmai su kitomis programomis būtų atliekami, kaip numatyta.

Renkami šių laukų duomenys: 

- **action** – nuvilkimo arba palikimo veiksmas

- **location** – nuvilkimo veiksmo atveju galėsime žinoti, iš kurios vietos vartotojas pradėjo vilkti elementą.  Palikimo veiksmo atveju galėsime žinoti, kur vartotojas paliko nuvilktą failą. 

- **source** – perkėlimo veiksmo atveju galėsime žinoti, iš kurios vietos vartotojas pradėjo vilkti elementą. Tai padeda mums geriau suprasti konkretaus šaltinio, pvz., „OneDrive“ arba failų, problemas, kylančias konkrečioje perkėlimo vietoje, pvz., naujame el. laiške.

#### <a name="drawerevent"></a>drawer.event

Naudojama stebėti galimą neigiamą poveikį jūsų gebėjimui pasiekti gautų laiškų pašto dėžutės aplankus.

Renkami šių laukų duomenys:

- **add_calendar_option** – nurodo kalendoriaus, kuris įtraukiamas iš stalčiaus, tipą, t. y. įdomus kalendorius, pašto kalendorius, bendrinamas kalendorius, kad būtų lengviau nustatyti su tam tikrais kalendoriaus tipais susijusias problemas

- **calendar_accounts_count** – nurodo kalendoriaus paskyrų skaičių, kad būtų galima nustatyti su paskyrų skaičiumi susijusias problemas

- **calendar_apps_count** – nurodo vartotojo įrenginyje esančių kalendoriaus programų skaičių, kad būtų lengviau nustatyti su kalendoriaus programomis susijusias problemas

- **drawer_type** – nurodo stalčiaus tipą: kalendorius, paštas ar nulinė užklausa, kad galėtume nustatyti su stalčiaus tipu susijusias problemas

- **from_favorites** – nurodo, ar veiksmas buvo paimtas iš parankinių, kad galėtume aptikti su parankiniais susijusias problemas

- **group_calendar_count** – nurodo paskyros kalendorių skaičių, kuris padės aptikti problemas, susijusias su grupės kalendoriais

- **inbox_unread_count** – nurodo neperskaitytų laiškų skaičių aplanke Gauta, kad būtų lengviau nustatyti aplanko Gauta neskaitytų laiškų skaičių.

- **interesting_calendar_accounts_count** – nurodo paskyrų, kurios gali būti priskirtos įdomiems kalendoriams įrenginyje, skaičių, kad galėtume nustatyti su įdomiausiais kalendoriais susijusias problemas

- **is_group_calendar** – nurodo, ar kalendorius yra grupės kalendorius, kad būtų lengviau nustatyti problemas, susijusias su grupės kalendoriais

- **mail_folder_type** – nurodo pašto aplanko tipą, t. y. Gauta, Juodraščiai ir t. t., kad galėtume aptikti su aplankų tipais susijusias problemas.

- **mail_accounts_count** – nurodo pašto paskyrų skaičių, kad būtų galima nustatyti su pašto paskyrų skaičiumi susijusias problemas.

- **selected_group_calendar_count** – nurodo grupės kalendorių, kurie buvo pasirinkti ir aktyvūs vartotojo sąsajoje, skaičių

- **visibility_toggle** – nurodo, ar vartotojas įjungė arba išjungia nurodytą kalendorių, kad galėtume nustatyti kalendorius rodymo ar slėpimo problemas

#### <a name="ipccreaterepublishinglicense"></a>IpcCreateRepublishingLicense

Gaunamas, kai vartotojas bando atidaryti IRM apsaugotą dokumentą arba taikyti IRM apsaugą. Jame yra informacija, būtina norint tinkamai ištirti ir nustatyti problemas, kurios įvyksta atliekant IpcpSerializeLicense API iškvietimą.

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.Duration** – bendras API iškvietimo baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia API iškvietimas, jei tokių yra

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.Result** – API iškvietimo sėkmė arba nesėkmė

- **RMS.ScenarioId** – API apibrėžtas scenarijaus ID

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.StatusCode** – pateikto rezultato būsenos kodas

#### <a name="ipcgetlicenseproperty"></a>IpcGetLicenseProperty

Gaunamas, kai vartotojas bando atidaryti IRM apsaugotą dokumentą arba taikyti IRM apsaugą. Jame yra informacija, būtina norint tinkamai ištirti ir nustatyti problemas, kurios įvyksta atliekant IpcGetLicenseProperty API iškvietimą.

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas.

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.Duration** – bendras API iškvietimo baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia API iškvietimas, jei tokių yra

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.LicensePropertyType** – licencijos ypatybės tipas

- **RMS.Result** – API iškvietimo sėkmė arba nesėkmė

- **RMS.ScenarioId** – API apibrėžtas scenarijaus ID

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.StatusCode** – pateikto rezultato būsenos kodas

#### <a name="ipcgetserializedlicenseproperty"></a>IpcGetSerializedLicenseProperty

Gaunamas, kai vartotojas bando atidaryti IRM apsaugotą dokumentą arba taikyti IRM apsaugą. Jame yra informacija, būtina norint tinkamai ištirti ir nustatyti problemas, kurios įvyksta atliekant IpcGetSerializedLicenseProperty API iškvietimą.

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas.

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.Duration** – bendras API iškvietimo baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia API iškvietimas, jei tokių yra

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.LicensePropertyType** – licencijos ypatybės tipas

- **RMS.Result** – API iškvietimo sėkmė arba nesėkmė

- **RMS.ScenarioId** – API apibrėžtas scenarijaus ID

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.StatusCode** – pateikto rezultato būsenos kodas

#### <a name="ipcgettemplateissuerlist"></a>IpcGetTemplateIssuerList

Gaunamas, kai vartotojas bando atidaryti IRM apsaugotą dokumentą arba taikyti IRM apsaugą. Jame yra informacija, būtina norint tinkamai ištirti ir nustatyti problemas, kurios įvyksta atliekant IpcGetTemplateIssuerList API iškvietimą.

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas.

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.AuthCallbackProvided** – nurodo, ar pateikiamas autentifikavimo iškvietimas kaip API iškvietimo įvestis

- **RMS.ConnectionInfo.ExtranetUrl** – ryšio informacijos ekstraneto URL

- **RMS.ConnectionInfo.IntranetUrl** – ryšio informacijos intraneto URL

- **RMS.ConnectionMode** – ryšio režimas tarp teisių valdymo tarnybos kliento ir serverio: prisijungęs ar neprisijungęs

- **RMS.Duration** – bendras API iškvietimo baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia API iškvietimas, jei tokių yra

- **RMS.GuestTenant** – vartotojo svečio nuomotojo ID

- **RMS.GuestTenant** – vartotojo namų nuomotojo ID

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.Identity.ExtranetUrl** – vartotojo teisių valdymo tarnybos ekstraneto URL, gautas gaunant naują teisių paskyros sertifikatą iš serverio
 
- **RMS.Identity.IntranetUrl** – vartotojo teisių valdymo tarnybos intraneto URL, gautas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.Identity.Status** – pirmas kartas, kai buvo gautas teisių paskyros sertifikatas iš serverio arba buvo atnaujintas teisių paskyros sertifikatas 

- **RMS.Identity.Type** – vartotojo paskyros tipas, pvz., „Windows“ paskyra arba tiesioginė paskyra

- **RMS.Identity.UserProvided** – nurodo, ar pateiktas vartotojo el. pašto adresas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.IssuerId** – teisių valdymo tarnybos serverio, kuris išduoda teisių paskyros sertifikatą, ID 

- **RMS.LicenseFormat** – licencijos formatas: Xrml arba Json

- **RMS.RACType** –teisių paskyros sertifikato tipas

- **RMS.Result** – API iškvietimo sėkmė arba nesėkmė

- **RMS.ScenarioId** – API apibrėžtas scenarijaus ID

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.ServerType** – teisių valdymo tarnybos tipas

- **RMS.StatusCode** – pateikto rezultato būsenos kodas

- **UserInfo.UserObjectId** – vartotojo objekto ID

#### <a name="ipcgettemplatelist"></a>IpcGetTemplateList

Gaunamas, kai vartotojas bando atidaryti IRM apsaugotą dokumentą arba taikyti IRM apsaugą. Jame yra informacija, būtina norint tinkamai ištirti ir nustatyti problemas, kurios įvyksta atliekant IpcGetTemplateList API iškvietimą.

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas.

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.AuthCallbackProvided** – nurodo, ar pateikiamas autentifikavimo iškvietimas kaip API iškvietimo įvestis

- **RMS.ConnectionInfo.ExtranetUrl** – ryšio informacijos ekstraneto URL

- **RMS.ConnectionInfo.IntranetUrl** – ryšio informacijos intraneto URL

- **RMS.ConnectionMode** – ryšio režimas tarp teisių valdymo tarnybos kliento ir serverio: prisijungęs ar neprisijungęs

- **RMS.Duration** – bendras API iškvietimo baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia API iškvietimas, jei tokių yra

- **RMS.GuestTenant** – vartotojo svečio nuomotojo ID

- **RMS.GuestTenant** – vartotojo namų nuomotojo ID

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.Identity.ExtranetUrl** – vartotojo teisių valdymo tarnybos ekstraneto URL, gautas gaunant naują teisių paskyros sertifikatą iš serverio
 
- **RMS.Identity.IntranetUrl** – vartotojo teisių valdymo tarnybos intraneto URL, gautas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.Identity.Status** – pirmas kartas, kai buvo gautas teisių paskyros sertifikatas iš serverio arba buvo atnaujintas teisių paskyros sertifikatas 

- **RMS.Identity.Type** – vartotojo paskyros tipas, pvz., „Windows“ paskyra arba tiesioginė paskyra

- **RMS.Identity.UserProvided** – nurodo, ar pateiktas vartotojo el. pašto adresas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.IssuerId** – teisių valdymo tarnybos serverio, kuris išduoda teisių paskyros sertifikatą, ID 

- **RMS.LicenseFormat** – licencijos formatas: Xrml arba Json

- **RMS.RACType** –teisių paskyros sertifikato tipas

- **RMS.Result** – API iškvietimo sėkmė arba nesėkmė

- **RMS.ScenarioId** – API apibrėžtas scenarijaus ID

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.ServerType** – teisių valdymo tarnybos tipas

- **RMS.StatusCode** – pateikto rezultato būsenos kodas

- **RMS.TemplatesCount** – šablonų skaičius

- **UserInfo.UserObjectId** – vartotojo objekto ID

#### <a name="ipcpcreatelicensefromscratch"></a>IpcpCreateLicenseFromScratch

Gaunamas, kai vartotojas bando atidaryti IRM apsaugotą dokumentą arba taikyti IRM apsaugą. Jame yra informacija, būtina norint tinkamai ištirti ir nustatyti problemas, kurios įvyksta atliekant IpcpCreateLicenseFromScratch API iškvietimą.

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas.

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.Duration** – bendras API iškvietimo baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia API iškvietimas, jei tokių yra

- **RMS.GuestTenant** – vartotojo svečio nuomotojo ID

- **RMS.GuestTenant** – vartotojo namų nuomotojo ID

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.Identity.ExtranetUrl** – vartotojo teisių valdymo tarnybos ekstraneto URL, gautas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.Identity.IntranetUrl** – vartotojo teisių valdymo tarnybos intraneto URL, gautas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.Identity.UserProvided** – nurodo, ar pateiktas vartotojo el. pašto adresas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.IssuerId** – teisių valdymo tarnybos serverio, kuris išduoda teisių paskyros sertifikatą, ID 

- **RMS.LicenseFormat** – licencijos formatas: Xrml arba Json

- **RMS.RACType** –teisių paskyros sertifikato tipas

- **RMS.Result** – API iškvietimo sėkmė arba nesėkmė

- **RMS.ScenarioId** – API apibrėžtas scenarijaus ID

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.ServerType** – teisių valdymo tarnybos tipas

- **RMS.StatusCode** – pateikto rezultato būsenos kodas

- **RMS.TokenProvided** – nurodo, ar pateikiama žymė kaip API iškvietimo įvestis 

- **RMS.UserProvided** – nurodo, ar pateikiamas vartotojas kaip API iškvietimo įvestis 

- **UserInfo.UserObjectId** – vartotojo objekto ID 

#### <a name="ipcpcreatelicensefromtemplate"></a>IpcpCreateLicenseFromTemplate

Gaunamas, kai vartotojas bando atidaryti IRM apsaugotą dokumentą arba taikyti IRM apsaugą. Jame yra informacija, būtina norint tinkamai ištirti ir nustatyti problemas, kurios įvyksta atliekant IpcpCreateLicenseFromTemplate API iškvietimą. 

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas.

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.AuthCallbackProvided** – nurodo, ar pateikiamas autentifikavimo iškvietimas kaip API iškvietimo įvestis

- **RMS.ConnectionMode** – ryšio režimas tarp teisių valdymo tarnybos kliento ir serverio: prisijungęs ar neprisijungęs

- **RMS.Duration** – bendras API iškvietimo baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia API iškvietimas, jei tokių yra

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.Result** – API iškvietimo sėkmė arba nesėkmė

- **RMS.ScenarioId** – API apibrėžtas scenarijaus ID

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.StatusCode** – pateikto rezultato būsenos kodas

- **RMS.TokenProvided** – nurodo, ar pateikiama žymė kaip API iškvietimo įvestis 

- **RMS.UserProvided** – nurodo, ar pateikiamas vartotojas kaip API iškvietimo įvestis 

#### <a name="ipcpgettemplatelistforuser"></a>IpcpGetTemplateListForUser

Gaunamas, kai vartotojas bando atidaryti IRM apsaugotą dokumentą arba taikyti IRM apsaugą. Jame yra informacija, būtina norint tinkamai ištirti ir nustatyti problemas, kurios įvyksta atliekant IpcpGetTemplateListForUser API iškvietimą. 

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas.

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.ApplicationScenarioId** – programos pateiktas scenarijaus ID

- **RMS.AuthCallbackProvided** – nurodo, ar pateikiamas autentifikavimo iškvietimas kaip API iškvietimo įvestis

- **RMS.ConnectionInfo.ExtranetUrl** – ryšio informacijos ekstraneto URL

- **RMS.ConnectionInfo.IntranetUrl** – ryšio informacijos intraneto URL

- **RMS.ConnectionMode** – ryšio režimas tarp teisių valdymo tarnybos kliento ir serverio: prisijungęs ar neprisijungęs

- **RMS.Duration** – bendras API iškvietimo baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia API iškvietimas, jei tokių yra

- **RMS.GuestTenant** – vartotojo svečio nuomotojo ID

- **RMS.GuestTenant** – vartotojo namų nuomotojo ID

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.Identity.ExtranetUrl** – vartotojo teisių valdymo tarnybos ekstraneto URL, gautas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.Identity.IntranetUrl** – vartotojo teisių valdymo tarnybos intraneto URL, gautas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.Identity.Status** – pirmas kartas, kai buvo gautas teisių paskyros sertifikatas iš serverio arba buvo atnaujintas teisių paskyros sertifikatas 

- **RMS.Identity.Type** – vartotojo paskyros tipas, pvz., „Windows“ paskyra arba tiesioginė paskyra

- **RMS.Identity.UserProvided** – nurodo, ar pateiktas vartotojo el. pašto adresas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.IssuerId** – teisių valdymo tarnybos serverio, kuris išduoda teisių paskyros sertifikatą, ID 

- **RMS.LicenseFormat** – licencijos formatas: Xrml arba Json

- **RMS.RACType** –teisių paskyros sertifikato tipas

- **RMS.Result** – API iškvietimo sėkmė arba nesėkmė

- **RMS.ScenarioId** – API apibrėžtas scenarijaus ID

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.ServerType** – teisių valdymo tarnybos tipas

- **RMS.StatusCode** – pateikto rezultato būsenos kodas

- **RMS.TemplatesCount** – šablonų skaičius

- **RMS.TokenProvided** – nurodo, ar pateikiama žymė kaip API iškvietimo įvestis 
    
- **RMS.UserProvided** – nurodo, ar pateikiamas vartotojas kaip API iškvietimo įvestis 

- **UserInfo.UserObjectId** – vartotojo objekto ID 

#### <a name="ipcpserializelicense"></a>IpcpSerializeLicense

Gaunamas, kai vartotojas bando taikyti IRM apsaugas dokumentui. jame yra informacija, būtina siekiant tinkamai ištirti ir nustatyti problemas, kurios įvyko atliekant IpcpSerializeLicense API iškvietimą.

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas.

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.ApplicationScenarioId** – programos pateiktas scenarijaus ID

- **RMS.AuthCallbackProvided** – nurodo, ar pateikiamas autentifikavimo iškvietimas kaip API iškvietimo įvestis

- **RMS.ConnectionMode** – ryšio režimas tarp teisių valdymo tarnybos kliento ir serverio: prisijungęs ar neprisijungęs

- **RMS.ContentId** dokumento turinio ID

- **RMS.Duration** – bendras API iškvietimo baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia API iškvietimas, jei tokių yra

- **RMS.GuestTenant** – vartotojo svečio nuomotojo ID

- **RMS.GuestTenant** – vartotojo namų nuomotojo ID

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.Identity.ExtranetUrl** – vartotojo teisių valdymo tarnybos ekstraneto URL, gautas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.Identity.IntranetUrl** – vartotojo teisių valdymo tarnybos intraneto URL, gautas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.Identity.Status** – pirmas kartas, kai buvo gautas teisių paskyros sertifikatas iš serverio arba buvo atnaujintas teisių paskyros sertifikatas 

- **RMS.Identity.Type** – vartotojo paskyros tipas, pvz., „Windows“ paskyra arba tiesioginė paskyra

- **RMS.Identity.UserProvided** – nurodo, ar pateiktas vartotojo el. pašto adresas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.IssuerId** – teisių valdymo tarnybos serverio, kuris išduoda teisių paskyros sertifikatą, ID 

- **RMS.KeyHandle** – rakto valdymo programos atminties adresas

- **RMS.LicenseFormat** – licencijos formatas: Xrml arba Json

- **RMS.PL.KeyType** – reikšmė „Single“ arba „Double“. Nurodo, ar PL apsaugoti buvo naudota vieno, ar dviejų raktų apsauga.

- **RMS.RACType** –teisių paskyros sertifikato tipas

- **RMS.Result** – API iškvietimo sėkmė arba nesėkmė

- **RMS.ScenarioId** – API apibrėžtas scenarijaus ID

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.ServerType** – teisių valdymo tarnybos tipas

- **RMS.StatusCode** – pateikto rezultato būsenos kodas

- **RMS.TokenProvided** – nurodo, ar pateikiama žymė kaip API iškvietimo įvestis 

- **RMS.UserProvided** – nurodo, ar pateikiamas vartotojas kaip API iškvietimo įvestis 

- **UserInfo.UserObjectId** – vartotojo objekto ID 

#### <a name="ipcsetlicenseproperty"></a>IpcSetLicenseProperty

Gaunamas, kai vartotojas bando atidaryti IRM apsaugotą dokumentą arba taikyti IRM apsaugą. Jame yra informacija, būtina norint tinkamai ištirti ir nustatyti problemas, kurios įvyksta atliekant IpcSetLicenseProperty API iškvietimą. 

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas.

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.Duration** – bendras API iškvietimo baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia API iškvietimas, jei tokių yra 

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.LicensePropertyType** – licencijos ypatybės tipas

- **RMS.Result** – API iškvietimo sėkmė arba nesėkmė

- **RMS.ScenarioId** – API apibrėžtas scenarijaus ID

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.StatusCode** – API apibrėžtas scenarijaus ID


#### <a name="linkclickedaction"></a>link.clicked.action

Įvykis naudojamas sekti, kaip vartotojams sekasi peržiūrėti URL „Edge“ žiniatinklio rodinyje ir be klaidų naudojant žiniatinklio rodinio standartinius žiniatinklio scenarijus

Renkami šių laukų duomenys:

- **account_type** – jei „Edge“ žiniatinklio rodinys buvo paleistas iš el. laiško ar įvykio programoje „Outlook“, paskyros, iš kurios buvo gautas URL, tipas

- **action** – vartotojo veiksmai, atliekami „Outlook“ nuo to momento, kai jie bakstelėja URL, kai jie išeina iš šio srauto (atidaro saitą „Edge“ žiniatinklio rodinyje, puslapio nepavykta įkelti žiniatinklio rodinyje, atliko iešką žiniatinklyje, išėjo iš „Edge“ žiniatinklio rodinio, kad atidarytų žiniatinklio naršyklės programą ir t. t.)

- **SessionDuration** – vartotojo seanso trukmė

- **launch_type** – jei buvo paleistas „Edge“ internetinis rodinys, ar jis paleistas naudojant „Outlook“, valdiklį ar OS komponentą

- **origin** – jei vartotojas atliko veiksmą „Edge“ žiniatinklio rodinyje, to veiksmo kilmė

- **referrer** – URL, kurį naudotojas spustelėjo, vieta (el. paštas, kalendoriaus įvykis, TXP kortelė ir kt.)

- **search_scope** – jei vartotojas atliko iešką „Edge“ žiniatinklio rodinyje, šios ieškos aprėptis (viskas, vaizdai, vaizdo įrašai ir t. t.)

- **search_subtype** – jei vartotojas atliko iešką „Edge“ rodinyje, ar ji buvo pradinė ieška, ar patobulinta ieška

- **session_summary_page_loaded_count** – puslapių, kuriuos vartotojas įkelia per savo sesiją „Edge“ žiniatinklio rodinyje, skaičius

- **session_summary_page_loaded_count** – „Bing“ ieškų skaičius, kuriuos vartotojas atliko savo sesijos „Edge“ žiniatinklio rodinyje metu

- **session_summary_session_id** – dabartinio vartotojo seanso identifikatorius „Edge“ žiniatinklio rodinyje

- **"txp**, jei „Edge“ žiniatinklio rodinys buvo paleistas iš TXP kortelės, tos kortelės įvykio tipas (maitinimas, skrydis ir t. t.)

- **txp_component** – jei „Edge“ žiniatinklio rodinys buvo paleistas TXP kortelės, tos kortelės UI komponento tipas


#### <a name="mailaction"></a>mail.action

Naudojama stebėti galimą neigiamą poveikį jūsų gebėjimui atlikti kritinius el. pašto veiksmus (pvz., naudoti pašto gijų režimą, užtikrinti tinkamą laiškų klasifikavimo veiksmų atlikimą), kad galėtume užtikrinti tinkamą el. pašto programos veikimą.

Renkami šių laukų duomenys:

- **account** – paskyra, kurią naudojant atliktas veiksmas *[Šis laukas buvo pašalintas iš dabartinių „Office“ komponavimo versijų, bet gali būti rodomas senesnėse komponavimo versijose.]*

- **action** seka, kokio tipo veiksmas buvo atliekamas, t. y. archyvavimas, naikinimas, žymėjimas kaip perskaityto ir t. t. 

- **attachment_content_type** – atsisiųsto priedo turinio tipas 

- **attachment_content_type_with_count** – seka el. pašto priedų skaičių

- **attachment_download_result** – priedo atsisiuntimo veiksmo rezultatas (t. y. sėkmingas / nepavyko)

- **attachment_download_time** – priedo atsisiuntimo veiksmo laiko trukmė

- **attachment_extn** – atsisiųsto priedo failo plėtinys *[Šis laukas buvo pašalintas iš dabartinių „Office“ komponavimo versijų, bet gali būti rodomas senesnėse komponavimo versijose.]*

- **attachment_id** – atsisiųsto priedo sistemos identifikatorius 

- **attachment_size** – atsisiųsto priedo dydis

- **domain** – atidaromo dokumento domenas

- **duration** – stebi, kiek laiko truko veiksmas kaip žmonių nuskaitoma anglų k. eilutė (pvz., 1 s, 4 val.)

- **error** – su veiksmu susietas klaidos pranešimas 

- **event_mode** – kokio tipo įvykio režimu jis veikė, grupių ar kitu. 

- **Extension** – su šiuo veiksmu susijusio saito ar priedo failo plėtinio keturi simboliai *[Šis laukas buvo pašalintas iš dabartinių „Office“ komponavimo versijų, bet gali būti rodomas senesnėse komponavimo versijose.]*

- **internet_message_id** – sekimo pranešimo ID

- **is_group_escalation** – nurodo, ar pranešimas, pagal kurį buvo atliktas veiksmas, buvo nusiųstas į vartotojo pašto dėžutę dėl eskalavimo (prenumeruota grupei)

- **is_rule** – nurodo, ar atliktas pašto veiksmas iš naujo nustato reikšmingiausių / kitą klasifikaciją.

- **is_threaded_mode** – nurodo, ar pranešimas buvo gijos režimu, t. y. kaip grupuojami pranešimai

- **is_unread** – nurodo, ar pranešimas yra neskaitytas apie atliktą veiksmą

- **left_swipe_setting** – nurodo, kuris veiksmas buvo nustatytas kaip braukimas į kairę

- **message_id** – serverio pranešimo ID, skirtas veiksmui, arba kableliais atskirtas sąrašas, jei buvo atliktas daugiau nei vienas elementas.

- **message_type** – nurodo, su kokio tipo pranešimu buvo atliktas veiksmas – grupė ar kitas

- **number_selected** – elementų, kuriuos vartotojas pasirinko pranešimų sąraše ir kuriuos naudodamas ėmėsi veiksmų kelių elementų pasirinkimo režimu, skaičius.

- **origin** – veiksmo šaltinis, t. y. langelių perbraukimas, nulinė užklausa, gilus saitas, el. pašto rodinys, el. laiškų sąrašas ir t. t.

- **origin_view** – veiksmo rodinio, pvz., pokalbio, laiško ir t. t., šaltinis.

- **reported_to_msft** – nusiuntus el. laišką į nepageidaujamą el. paštą (pašto šiukšles) arba šiukšliadėžę (sukčiavimas), galima pasirinkti pranešti apie savo veiksmus „Microsoft“.

- **retry** – ar veiksmas buvo kartojamas

- **right_swipe_setting** – nurodo, kuris veiksmas buvo nustatytas kaip braukimas į dešinę 

- **shortcut** – nurodo, ar nuoroda buvo naudota, ir kokia nuoroda buvo naudota planavimo pranešimui, t. y. vėliau, rytoj, pasirinkti laiką ir t. t.

- **size** – saito arba priedo, susieto su šiuo veiksmu, dydis

- **source_folder** – seka šaltinio aplanko tipą, kai veiksmas nurodo pereiti iš vieno aplanko į kitą, t. y. į aplanką Gauta, šiukšlinę ir t. t. 

- **source_inbox** – nurodo, kuriame aplanke Gauta atliekamas pašto veiksmas (t. y. reikšmingiausi, kiti ir t. t.), state – veiksmo būsena, sėkminga arba gedimo vieta

- **state** – veiksmo būsena, t.y. sėkminga arba gedimo vieta

- **target_folder** – nurodo paskirties aplanko tipą perkeliant el. laiškus iš vieno aplanko į kitą

- **thread_id** – pokalbio, nukreipti veiksmui, gijos ID arba kableliais atskirtas sąrašas, jei buvo skirta daugiau nei vienam elementui.

- **time_taken_to_fetch_access_token** – laikas, kurį truko sistemos prieigos ženklo gavimo naudojimas saito atidarymui

- **time_taken_to_fetch_drive_item** – laikas, kurį truko „OneDrive“ išteklių gavimas spustelėjus

- **time_taken_to_fetch_embed_viewer_resource** – laikas, kurį truko įtaisytosios peržiūros programos inicijavimas atidarant saitus

- **time_taken_to_load_embed_viewer** – laikas, kurį truko įtaisytosios peržiūros programos inicijavimas atidarant saitus

- **time_taken_to_load_link** – laikas, per kurį baigiamas saito įkėlimo veiksmas

- **time_taken_to_tap_attachment** – laikas tarp pranešimo atidarymo ir priedo spustelėjimo

- **time_taken_to_tap_link** – laikas, kurį vartotojas užtruko peržiūrėdamas pranešimą ir spustelėdamas saitą

- **txp** – nurodo, ar „txp“ elemento tipas susietas su el. laišku, su kuriuo buvo atliktas veiksmas, t. y. įvykio rezervavimas, skrydžio rezervavimas ir t. t. 

- **type** – dokumento tipas, atidaromas naudojant saitą

#### <a name="mailcompose"></a>mail.compose

Naudojama stebėti galimą neigiamą poveikį jūsų gebėjimui kurti ir atsakyti į el. laiškus, pvz., susiduriama su problemomis atsakant visiems, formatuojant el. laišką ar siunčiant el. laiškus.

Renkami šių laukų duomenys: 

- **draft_message_id** – kuriamo pokalbio juodraščio ID, kad būtų galima nustatyti su el. pašto juodraščiais susijusias problemas

- **from_context_menu** – nurodo, ar kūrimas pradėtas atliekant kontekstinio meniu veiksmus.

- **message_id** – atsakomo ar persiunčiamo pokalbio pranešimo ID, kad būtų galima nustatyti problemas, susijusias su konkrečiu laišku

- **origin** – nurodo, iš ko kurti kilmę, pvz., iš atsakymo visiems, naujo sukūrimo ar sparčiojo atsakymo. Padeda aptikti problemas, susijusias su tam tikru atsakymo kilmės tipu.

- **is_group_escalation** – ar laiškas yra eskaluotas grupės pranešimas, kad būtų galima aptikti su grupėmis susijusias kūrimo problemas.

- **is_link** – nurodo, ar sukurtas naujas projektas buvo sukurtas naudojant saitą. Padeda aptikti su juodraščiais, kurie buvo sukurti naudojant saitus, susijusias problemas.

- **is_force_touch** – nurodo, ar naujai sukurtas juodraštis kurtas naudojant priverstinio lietimo veiksmą. Padeda aptikti su juodraščiais, kurie buvo sukurti atliekant šį konkretų veiksmą, susijusias problemas.

- **is_groups** – ar įvykis buvo pradėtas iš grupių srities, kad galėtume aptikti su grupėmis susijusias kūrimo problemas.

- **source_inbox** – nurodo šaltinio aplanką Gauta, pvz., ar jis buvo sutelktas, ar tai buvo kitas aplankas Gauta

- **thread_id** – atsakomo ar persiunčiamo pokalbio gijos ID, kad būtų galima nustatyti problemas, susijusias su konkrečia gija

#### <a name="meetingcalltoaction"></a>meeting.call.to.action

Naudojama stebėti galimą neigiamą poveikį jūsų gebėjimui atlikti pagrindinius susitikimų veiksmus, pvz., kurti, redaguoti ar atsakyti į įvykius.

Renkami šių laukų duomenys:

- **event_mode** – nurodo, ar šis įvykis buvo iš grupės, kad būtų galima aptikti grupės įvykių problemas

- **meeting_id** – susitikimo ID, kuris padeda mums sekti problemas per visą susitikimo laiką, kad galėtume nustatyti konkretaus susitikimo problemas

- **meeting_provider** – nurodo internetinių susirinkimų teikėją, pvz., „Teams“, „Skype“ verslui, kad galėtume nustatyti problemas, susijusias su konkrečiais internetinių susitikimų teikėjais

- **notify_type** – nurodo kitų paskyrų tipų atsakymo tipą, kad būtų galima nustatyti skirtingų paskyrų tipų problemas

- **recurrence** – nurodo, kaip dažnai įvyksta šis susitikimas, t. y. pasikartojimas ar seka, kad galėtume nustatyti pasikartojančių susitikimų sekų problemas

- **response** – nurodo atsakymo tipą, pvz., priimti arba atmesti tam tikrus paskyros tipus, kad būtų lengviau nustatyti problemas, susijusias su reagavimu į įvykius

- **response_message_length** – nurodo, kokio ilgio buvo pranešimas, kad būtų galima aptikti atsakymų į susitikimus problemas

- **review_time_proposal_action_type** – nurodo vartotojo atsakymo naujo laiko pasiūlymą, kad būtų galima nustatyti problemas, kylančias, kai siūlomas naujas laikas

- **send_response** – nurodo, ar buvo išsiųstas atsakymas, kad galėtume nustatyti kvietimų į susitikimus atsakymų siuntimo problemas

- **txp** – nurodo, kokio tipo susitikimas buvo sukurtas iš skrydžio užsakymų ir pristatymų, kad būtų galima aptikti problemas, susijusias su šio tipo susitikimais

- **with_message_enabled** – nurodo, ar vartotojas gali atsakyti naudodamas pranešimą, kad būtų galima nustatyti problemas, susijusias su atsakymu į susitikimų kvietimus


#### <a name="multiwindowlaunch"></a>multi.window.launch

Šis įvykis užfiksuoja, kada vartotojas imasi veiksmo, kuriame yra kelių langų paleidimas suskleidžiamuose įrenginiuose, pvz., kuria el. laišką, įvykį, atidaro kalendoriaus langą.  Jis naudoja veiksmą, kad atsimintų tokį veiksmą, pvz., ir toliau gauti raginimą arba visada paleisti naujame lange.  Šio įvykio surinkti duomenys bus naudojami įvertinti aptinkamumą, efektyvumą, o taip pat ir bendras vartotojo nuostatas, kad būtų galima valdyti dabartinę ir ateities kelių langų funkcijų plėtrą.

Renkami šių laukų duomenys: 

- **is_remembered** – ar nuostata paleisti naujame lange iš praneštos vietos buvo įrašyta vartotojo.

- **multi_window_origin** – vieta programoje, kurioje vyksta sąveika paleisti kitą programos ekraną naujame lange.


#### <a name="officeandroiddocsuifileoperationsopendocumentmeasurements"></a>Office.Android.DocsUI.FileOperations.OpenDocumentMeasurements

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Android“ platformoje, ir įrašams, kai atliekama failo atidarymo operacija. Įvykis padeda apsaugoti, atnaujinti ir tinkamai atlikti failo atidarymo procedūrą. Šių duomenų rinkimo tikslas – nuolatos didinti failų atidarymo efektyvumą. 

Renkami šių laukų duomenys:

- **Data_AppDocsOperationDuration** – antriniame sluoksnyje praleista trukmė atliekant failo atidarymo operaciją.

- **Data_AppDuration** – taikomosios programos apdorojimo trukmė atliekant failo atidarymo operaciją. 

- **Data_AppWarmUpGain** – įgyta programos paleidimo trukmė dėl dalinio programos paleidimo iš anksto.

- **Data_BootDuration** – programos paleidimo trukmė atliekant failo atidarymo procesą.

- **Data_BootMarkers** – eilutės reikšmė, fiksuojanti laiką tarp tam tikrų funkcijų iškvietimų programos paleidimo metu, pateikiama formatu su funkcijos ID ir trukme.

- **Data_ClosePreviouslyOpenedMarkers** – kai kuriuose failų atidarymo scenarijuose, prieš pradedant dabartinį dokumentą, uždaromas anksčiau atidarytas dokumentas. Šis laikotarpis tarp kai kurių operacijų, vykstančių šiuo atveju, užfiksuotas eilutės reikšmė, kurioje yra formatas \<functionId>\<functionValue>\<functionId>\<functionValue>

- **Data_Doc_AccessMode** – išvardijimas, rodantis failo prieigos režimą, pvz., tik skaityti, skaityti / rašyti.

- **Data_Doc_AsyncOpenKind** – išvardijimas, rodantis, kokio tipo asinchroninis srautas naudojamas failui atidaryti.

- **Data_Doc_ChunkingType** – išvardijimas, rodantis failo segmentavimo algoritmą.

- **Data_Doc_EdpState** – išvardijimas, rodantis įmonės duomenų failo apsaugos būseną.

- **Data_Doc_Ext** – failo plėtinys.

- **Data_Doc_Fqdn** – failo serverio pagrindinio kompiuterio pavadinimas.

- **Data_Doc_FqdnHash** – globaliai unikalus identifikatorius (GUID), kuris unikaliai identifikuoja serverio pagrindinio kompiuterio pavadinimą.

- **Data_Doc_IdentityTelemetryId** – GUID, kuris unikaliai identifikuoja tapatybę, naudojamą failui atidaryti. 

- **Data_Doc_InitializationScenario** – išvardijimas, rodantis išsamius failo atidarymo operacijos scenarijaus tipus.

- **Data_Doc_IOFlags** – išvardijimas, rodantis failo atidarymo operacijos įvesties ir išvesties žymes, pvz., ar failas yra talpykloje.

- **Data_Doc_IsCloudCollabEnabled** – ar šiam failui įgalintas bendradarbiavimas debesyje.

- **Data_Doc_IsIncrementalOpen** – ar failas buvo atidarytas naudojant papildantįjį atidarymą.

- **Data_Doc_IsOcsSupported** – ar failas palaiko „Office“ bendradarbiavimo tarnybą.

- **Data_Doc_IsOpeningOfflineCopy** – ar failas atidaromas iš autonominėje talpykloje laikomos kopijos.

- **Data_Doc_IsPrefetched** – ar failas buvo paimtas iš anksto prieš atidarymo operacijos atlikimą.

- **Data_Doc_IsSyncBacked** – ar debesies failas yra lokaliai ir ar sinchronizuojamas su serveriu.

- **Data_Doc_Location** – išvardijimas, rodantis failo vietą, pvz., lokalus arba debesyje.

- **Data_Doc_ReadOnlyReasons** – išvardijimas, rodantis failo priežastį tik skaityti.

- **Data_Doc_ResourceIdHash** – GUID, unikaliai identifikuojantis failo serverio išteklių ID.

- **Data_Doc_RtcType** – išvardijimas, rodantis failo naudojamą realaus laiko kanalo (RTC) tipą.

- **Data_Doc_FqdnHash** – GUID, kuris unikaliai identifikuoja serverio dokumento ID.

- **Data_Doc_ServerProtocol** – išvardijimas, rodantis debesies failo serverio protokolą.

- **Data_Doc_ServerType** – išvardijimas, rodantis debesies failo serverio tipą.

- **Data_Doc_ServerVersion** – išvardijimas, rodantis debesies failo serverio versiją.

- **Data_Doc_SessionId** – sveikasis skaičius, padidėjantis 1 kiekvieną kartą, kai seanso metu atliekama failo atidarymo operacija.

- **Data_Doc_SharePointServiceContext** – eilutė, naudojama susieti kliento ir serverio žurnalus, paprastai tai yra ID tipas.

- **Data_Doc_SizeInBytes** – dokumento dydis baitais.

- **Data_Doc_SpecialChars** – išvardijimas, rodantis URL failo specialųjį simbolį.

- **Data_Doc_UrlHash** – GUID, kuris unikaliai identifikuoja failo URL.

- **Data_Doc_UsedWrsDataOnOpen** – ar failas buvo atidarytas palaipsniui naudojant iš anksto talpykloje saugomus WRS duomenis.

- **Data_Doc_WopiServiceId** – eilutė, rodanti iš kurios tarnybos yra žiniatinklio programos atviro platformos sąsajos protokolo (WOPI) failas.

- **Data_ErrorId_Code** – klaidos kodas, nurodantis duomenų rinkimo operacijos klaidą

- **Data_ErrorId_Tag** – kodo žymė, padedanti rasti klaidos vietą

- **Data_FileOpenFlowMarkers** – prieš pradedant procesą, reikia atlikti tam tikrą išankstinį apdorojimą. Šį laiką, kada buvo atliktas šis paruošiamasis apdorojimas, fiksuojama eilutės reikšmė, kurios formatas \<functionId>\<functionValue>\<functionId>\<functionValue>...

- **Data_FirstPartyProviderApp** – jei failas atidarytas naudojant „Word“, „Excel“, „PowerPoint“ arba „Office“ taikomąsias programas iš kitos „Microsoft“ taikomosios programos, čia fiksuojamas teikėjo taikomosios programos pavadinimas.

- **Data_InclusiveMeasurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, kuri apima papildomų funkcijų iškvietimų trukmę. 

- **Data_InitializationReason** – išvardijimas, rodantis kaip failas atidaromas, pvz., iš kurio vartotojo sąsajos elemento, paleistas kitos programos ir t. t.

- **Data_Measurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, neapimančia papildomų funkcijų iškvietimų trukmės.

- **Data_OfficeMobileInitReason** – išvardijimas, nurodantis atidaryto failo įvesties vietą. 

- **Data_RenderToInSpaceDuration** – trukmė tarp atvaizdavimo pabaigos ir silueto / drobės animacijos.

- **Data_SilhouetteDuration** – failo atidarymo generavimo trukmė.

- **Data_TimeSplitMeasurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme, pradžios laiko žyma ir trukme. 

#### <a name="officeandroiddocsuipaywallcontrolpresigninfre"></a>Office.Android.DocsUI.PaywallControl.PreSignInFRE

*[Šis įvykis anksčiau vadinosi Office.DocsUI.PaywallControl.PreSignInFRE.]*
 
Tai yra papildomo pardavimo kritinė naudojimo telemetrija pirmajame veikimo skyriuje neprijungtiems vartotojams. Šis įvykis užfiksuoja pirmą kartą vykdytą prisijungimo metriką. Duomenys bus naudojami norint pateikti įžvalgų apie išankstinį prisijungimą ir suprasti, ar vartotojas toliau eis į kitą vartotojo srauto etapą.
 
Renkami šių laukų duomenys: 

- **EventDate** – įvykio įvykimo laiko žyma  

- **FunnelPoint** – Surašytuvas, nurodantis, kur vartotojas yra šiame eksperimento piltuve. Surašytuvas pasakys, ar vartotojas mato apdorojimą ir, ar išeina, ar ne.

- **SessionID** – globaliai unikalus identifikatorius (GUID), kad galima būtų sujungti įvykius pagal seansą


#### <a name="officeandroiddocsuipaywallcontrolskuchoosertoggled"></a>Office.Android.DocsUI.PaywallControl.SkuChooserToggled

Telemetrijos naudojimas, kad būtų galima peržiūrėti, kiek kartų vartotojas pereina per skirtingus SKU prieš bandydamas įsigyti. Naudojamas suprasti SKU parinkiklio naudojimą ir optimizuoti pirkimo programoje funkcijas būsimose versijose.

Renkami šių laukų duomenys:

- **EventDate** – įvykio įvykimo laiko žyma 

- **SessionID** – GUID, skirtas sujungti įvykius pagal sesiją


#### <a name="officeandroiddocsuipaywallcontroluserimageclicked"></a>Office.Android.DocsUI.PaywallControl.UserImageClicked 

*[Šis įvykis anksčiau vadinosi Office.DocsUI.PaywallControl.UserImageClicked.]*
 
Šis įvykis matuoja telemetrijos veiksmus, kad sužinotumėte, ar vartotojai bando atlikti veiksmą spustelėję vartotojo avatarą. Šie duomenys bus naudojami norint įvertinti, kiek vartotojų naudoja avataro piktogramą, kad įvertintų, ar reikia tolesnės pagalbos, kai bakstelėsite.
 
Renkami šių laukų duomenys: 

- **EventDate** – įvykio įvykimo laiko žyma  

- **SessionID** – globaliai unikalus identifikatorius (GUID), kad galima būtų sujungti įvykius pagal seansą 


#### <a name="officeandroidearlytelemetryexpansionfilesavailability"></a>Office.Android.EarlyTelemetry.ExpansionFilesAvailability

Įgaliname papildomus „Android Package Kit“ (APK) failus, skirtus „Office“ mobiliųjų įrenginių programai. Papildomi APK failai yra pridėtiniai išteklių failai, kuriuos „Android“ programų kūrėjai gali paskelbti kartu su programa. Siekdami suprasti papildomų failų patikimumą, užregistruojame reikšmę, nurodančią, ar papildomi failai pasiekiami, ar ne, per kiekvieną paleidimą.

Renkami šių laukų duomenys:

- **Data_ExpansionFilesAvailable** – Bulio logikos reikšmė, kuri nurodo, ar papildomi APK failai pasiekiami įrenginyje paleidžiant programą.

#### <a name="officeandroidearlytelemetryexpansionfilesdownloader"></a>Office.Android.EarlyTelemetry.ExpansionFilesDownloader

Įgaliname papildomus „Android Package Kit“ (APK) failus, skirtus „Office“ mobiliųjų įrenginių programai. Papildomi APK failai yra pridėtiniai išteklių failai, kuriuos „Android“ programų kūrėjai gali paskelbti kartu su programa.  Siekdami suprasti papildomų failų atsisiuntimo mechanizmo patikimumą, užregistruojame reikšmę, nurodančią, ar galime sėkmingai atsisiųsti papildomus failus.

Renkami šių laukų duomenys: 

- **Data_DownloadSuccess** – Bulio logikos reikšmė, nurodanti, ar papildomi APK failai atsisiųsti sėkmingai, kai bandome juos atsisiųsti per programos paleidimą.

#### <a name="officeandroidearlytelemetrynotecreated"></a>Office.Android.EarlyTelemetry.NoteCreated

Kritinis signalas, naudojamas stebėti priklijuojamų lapelių galimybę kurti pastabas programoje. Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Jei vartotojai negali sukurti pastabos, tai gali lemti didelės svarbos incidentą.

Renkami šių laukų duomenys:

- **IsExportable** – žymė, nurodanti, ar šis įvykis tapo vartotojo veiksmo rezultatu. Turėtų būti nustatyta į True, nes NoteCreated yra vartotojo suaktyvinamas veiksmas.

- **NoteLocalId** – atskiriamas unikalusis identifikatorius, priskirtas pastabai tuo metu, kai vartotojas sukuria pastabą programoje.

- **StickyNotes-SDKVersion** – versijos numeris, nurodantis priklijuojamų lapelių programos, kurią naudoja vartotojas, versiją. Leidžia mums nustatyti kurios produkto versijos rodo problemą, kad galėtume tinkamai nustatyti jos prioritetą.


#### <a name="officeandroidearlytelemetrynoteviewed"></a>Office.Android.EarlyTelemetry.NoteViewed 

Kritinis signalas, naudojamas stebėti priklijuojamų lapelių galimybę peržiūrėti pastabas programoje. Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Jei vartotojai negali peržiūrėti savo pastabų, suaktyvinamas didelės svarbos incidentas.

Renkami šių laukų duomenys:

- **HasImages** – žymė, nurodanti, ar peržiūrėta pastaba turi joje išsaugotų vaizdų.

- **IsExportable** – žymė, nurodanti, ar šis įvykis tapo vartotojo veiksmo rezultatu. Turėtų būti nustatyta į True, nes NoteViewed yra vartotojo suaktyvinamas veiksmas.

- **NoteLocalId** – atskiriamas unikalusis identifikatorius, priskirtas pastabai tuo metu, kai vartotojas sukuria pastabą programoje.

- **StickyNotes-SDKVersion** – versijos numeris, nurodantis priklijuojamų lapelių programos, kurią naudoja vartotojas, versiją. Leidžia mums nustatyti kurios produkto versijos rodo problemą, kad galėtume tinkamai nustatyti jos prioritetą.


#### <a name="officeandroidintuneintunecompliancerequest"></a>Office.Android.Intune.IntuneComplianceRequest

Šis įvykis renkamas „Office“ programoms, kuriose veikia „Android“, įskaitant „Office Mobile“, „Word“, „Excel“, „PowerPoint“ ir „OneNote“. Įvykis nurodo mėginimą prisijungti prie „Intune“ licencijuotos organizacijos paskyros, kur organizacijos administratorius sukonfigūravo strategiją, kad būtų galima taikyti sąlyginę prieigą prie programų. Jis naudojamas norint sužinoti skaičių galutinių vartotojų, kurie bando naudoti programas pagal šią strategijos konfigūraciją, ir yra suderintas su kitu įvykiu Office.Android.Intune.IntuneComplianceStatus, siekiant užtikrinti sukonfigūruotos strategijos vykdymą. 

Nepasirinkti jokie duomenų laukai.

#### <a name="officeandroidintuneintunecompliancestatus"></a>Office.Android.Intune.IntuneComplianceStatus

Šis įvykis renkamas „Office“ programoms, kuriose veikia „Android“, įskaitant „Office Mobile“, „Word“, „Excel“, „PowerPoint“ ir „OneNote“. Įvykis nurodo mėginimą prisijungti prie „Intune“ licencijuotos organizacijos paskyros, kur organizacijos administratorius sukonfigūravo strategiją, kad būtų galima taikyti sąlyginę prieigą prie programų. Šis įvykis nurodo būseną programos, prie kurios vartotojas yra prisijungęs ir kuri naudojama klaidoms tirti. Jis susietas su kitu įvykiu, Office.Android.Intune.IntuneComplianceRequest, siekiant užtikrinti sukonfigūruotos strategijos vykdymą.
  
Renkami šių laukų duomenys:

- **Data_ComplianceStatus** – nurodo programos suderinamumo būseną prisijungiant su sėkmingo prisijungimo arba klaidos kodu.
  - -1 – Nežinoma klaida
  -    0 – Programa suderinama su organizacijos strategijomis
  - 1 – Programa nesuderinama su organizacijos strategijomis
  - 2 – Su tarnyba susijusios klaidos
  - 3 – Su tinklu susijusios klaidos
  - 4 – Programai nepavyko gauti autentifikavimo ženklelio 
  - 5 – Dar negautas atsakas iš tarnybos
  - 6 – Būtina įdiegti įmonės portalo programą

#### <a name="officeandroidodwxpssotelemetry"></a>Office.Android.ODWXPSSO.Telemetry

Šis įvykis padeda suprasti su kuria kita „Microsoft“ taikomąja programa įrenginyje mūsų taikomoji programa gavo automatinę bendrąją autentifikaciją, iš kurio įėjimo taško ir t. t. Taip pat padeda suprasti trikties priežastį, dėl kurios negauta automatinė bendroji autentifikacija.  Gauname geresnių įžvalgų, pvz., iš kurios „Microsoft“ taikomosios programos įrenginyje, galime gauti bendrosios autentifikacijos patirtį. Veikia įvykus triktims, kai bendroji autentifikacija veikia netinkamai.

Renkami šių laukų duomenys:

- **AccountType** – nurodo paskyros tipą, kurį naudojant vyksta bendroji autentifikacija, pvz., asmeninė „Microsoft“ paskyra arba darbo paskyra.

- **EntryPoint** – nurodo taikomosios programos įvesties vietą, iš kur pradėtas bendrosios autentifikacijos bandymas.

- **ErrorCode** – nurodo bendrosios autentifikacijos klaidos kodą.

- **ErrorDescription** – nurodo bendrosios autentifikacijos bandymo klaidos kodą.

- **ErrorCode** – nurodo bendrosios autentifikacijos bandymo rezultato būsenos kodą.

- **ProviderPackageId** – kita „Microsoft“ taikomoji programa įrenginyje, iš kurio vyksta bendroji autentifikacija.

#### <a name="officeandroidphonenumbersignins"></a>Office.Android.PhoneNumberSignIns

Šis įvykis padeda suprasti, ar vartotojas prisijungė arba prisiregistravo naudodamas telefono numeriu paremta paskyra, ar el. paštu pagrįsta asmenine „Microsoft“ paskyra.  Šis įvykis padeda žinoti skaičių vartotojų, prisijungusių arba prisiregistravusių naudojant asmeninę „Microsoft“ paskyrą, kurioje nurodytas telefono numeris.

Renkami šių laukų duomenys:

- **EntryPoint** – nurodo taikomosios programos įvesties vietą, iš kur pradėtas prisijungimo bandymas.

- **IsEmailMissing** – ar paskyros profilio informacijoje nėra el. pašto adreso?

- **IsPhoneNumberMissing** – ar paskyros profilio informacijoje nėra telefono numerio?

- **UserDecision** – nurodo vartotojo pasirinkimą, pvz., prisijungimas, užsiregistravimas arba prisijungti vėliau.

#### <a name="officeandroidusersignindecision"></a>Office.Android.UserSignInDecision

Šis įvykis padeda suprasti kuriame etape vartotojas atsisako prisijungimo srauto, kodėl prisijungti nepavyksta, kiek vartotojų sėkmingai prisijungė, iš kurio taikomosios programos įėjimo taško ir t. t.  Šis įvykis padeda su prisijungimų nuoseklių išimčių duomenimis, kurie padeda suprasti kuriame etape vartotojai buvo atmesti ir t. t.

Renkami šių laukų duomenys:

- **AccountType** – nurodo paskyros tipą, kurį naudojant buvo atliktas prisijungimo bandymas, pvz., asmeninė paskyra arba darbo paskyra.

- **AfterLicensingState** – nurodo taikomosios programos licencijavimo būseną po prisijungimo baigimo.

- **AllowedEditsWithoutSignIn** – nurodo, kiek nemokamų redagavimų buvo atlikta prieš prisijungimo bandymą.

- **BeforeLicensingState** – nurodo taikomosios programos licencijavimo būseną prieš prisijungimo bandymą.

- **CompletionState** – nurodo prisijungimo užbaigimo etapą.

- **EntryPoint** – nurodo taikomosios programos įvesties vietą, iš kur pradėtas prisijungimo bandymas.

- **HRDAutoAcceleratedSignUpAttemptCount** – nurodo pagreitinto užsiregistravimo bandymų skaičių.

- **HRDAutoAcceleratedSignUpQuitCount** – nurodo pagreitinto užsiregistravimo atšaukimų skaičių.

- **HResult** – nurodo prisijungimo operacijos rezultato būsenos kodą.

- **IsPhoneOnlyAuthFeatureEnabled** – ar leidžiamas telefono numeriu paremtas prisijungimas?

- **LicenseActivationHResult** – nurodo licencijos aktyvinimo bandymo būsenos numerį.

- **LicenseActivationMessageCode** – nurodo licencijavimo tarnybos pranešimo kodą.

- **NoFreeEditsTreatmentValue** – ar leidžiami nemokami redagavimai?

- **SignUpAttemptCount** – nurodo bandymų užsiregistruoti skaičių.

- **StartMode** – nurodo režimą, kuriame buvo pradėtas bandymas prisijungti.

- **UserDecision** – nurodo vartotojo pasirinkimą, pvz., prisijungimas, užsiregistravimas arba prisijungti vėliau.


#### <a name="officeappcompatappcompatagentscanandupload"></a>Office.AppCompat.AppCompat.AgentScanAndUpload

Renkama tik kai galutinis vartotojas įgalina „Office“ telemetrijos ataskaitų sritį. Renka informaciją apie tai, kada paleidžiamas „Office“ telemetrijos agentas.  Informacija renkama tik tuo atveju, kai „Office“ telemetrijos ataskaitų sritis yra įjungta ir naudojama nustatyti „Office“ telemetrijos agento sveikatą.

Renkami šių laukų duomenys:

  - **Data.AgentExit** – telemetrijos agento sėkmingo uždarymo laiko žyma

  - **Data.AgentExit** – telemetrijos agento sėkmingo nuskaitymo atlikimo laiko žyma

  - **Data.AgentUpload** – telemetrijos agento sėkmingo įkėlimo atlikimo laiko žyma

#### <a name="officeappcompatappcompatagentupload"></a>Office.AppCompat.AppCompat.AgentUpload

Generuojama paleidžiant klientą, kai galutinis vartotojas įgalina „Office“ telemetrijos ataskaitų sritį.  Tenka informaciją, kai „Office“ telemetrijos agentas įkelia duomenis į bendrinimo aplanką. Šis įvykis visų pirma naudojamas norint stebėti „Office“ telemetrijos agento sveikatą. Antrinė paskirtis yra įvertinti „Office“ telemetrijos ataskaitų srities naudojimą.

Renkami šių laukų duomenys:

- **UploadTime** – paskutinio sėkmingo nusiuntimo, atlikti telemetrijos agento, laiko žyma.


#### <a name="officeappcompatappcompattelemetrydashboardresiliencycrashlog"></a>Office.AppCompat.AppCompat.TelemetryDashboardResiliencyCrashLog

Renkama tik kai „Office“ telemetrijos ataskaitų sritis yra įgalinta galutinio vartotojo (greičiausiai administratoriaus). Renka „Office“ papildinių ir dokumentų gedimų įvykius.  Duomenys renkami tik tuo atveju, kai vartotojas įgalino „Office“ telemetrijos ataskaitų sritį ir naudoja nustatyti, ar yra padidėjo papildinių arba dokumentų gedimų įvykių.

Renkami šių laukų duomenys:

  - **Data.CollectionTime** – laiko žyma, kai buvo užregistruotas gedimo įvykis

#### <a name="officeappdocsappdocsdocumentoperation"></a>Office.AppDocs.AppDocs.DocumentOperation

Šis įvykis renkamas „Office“ programoms, kurios veikia „Android“, „iOS“, „Universal“ arba „Windows“ platformose. Įvykių įrašai, kai vykdoma failo operacija (kurti / atidaryti / įrašyti / eksportuoti / kt.), naudojami suprasti ir nustatyti prioritetus, pagrįstus vartotojo patirtimi pagal failo atidarymo operacijos informaciją.

Renkami šių laukų duomenys:

- **Data_AppIdForReportEndBeforeAppKnown** – programos ID, kai ji nėra žinoma prieš operacijos pabaigą.

- **Data_CanContinueFromOnBeforeOperationBegins** – „CanContinue“ būsena prieš iškviečiant pradžios apdorojimo programą.

- **Data_DetachedDuration** – įvykio atsiejimo proceso trukmė. 

- **Data_Doc_AccessMode** – išvardijimas, rodantis failo prieigos režimą, pvz., tik skaityti, skaityti / rašyti.

- **Data_Doc_AsyncOpenKind** – išvardijimas, rodantis, kokio tipo asinchroninis srautas naudojamas failui atidaryti.

- **Data_Doc_ChunkingType** – Išvardijimas, rodantis failo segmentavimo algoritmą.

- **Data_Doc_EdpState** – išvardijimas, rodantis įmonės duomenų failo apsaugos būseną.

- **Data_Doc_Ext** – pirmieji keturi failo plėtinio simboliai.

- **Data_Doc_Fqdn** – failo serverio pagrindinio kompiuterio pavadinimas.

- **Data_Doc_FqdnHash** – GUID, kuris unikaliai identifikuoja serverio pagrindinio kompiuterio pavadinimą.

- **Data_Doc_IdentityTelemetryId** – vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša.

- **Data_Doc_InitializationScenario** – išvardijimas, rodantis išsamius failo atidarymo operacijos scenarijaus tipus.

- **Data_Doc_IOFlags** – išvardijimas, rodantis failo atidarymo operacijos įvesties ir išvesties žymes, pvz., ar failas yra talpykloje.

- **Data_Doc_IsCloudCollabEnabled** – ar šiam failui įgalintas bendradarbiavimas debesyje.

- **Data_Doc_IsIncrementalOpen** – ar failas buvo atidarytas naudojant papildantįjį atidarymą.

- **Data_Doc_IsOcsSupported** – ar failas palaiko „Office“ bendradarbiavimo tarnybą.

- **Data_Doc_IsOpeningOfflineCopy** – ar failas atidaromas iš autonominėje talpykloje laikomos kopijos.

- **Data_Doc_IsPrefetched** – ar failas buvo paimtas iš anksto prieš atidarymo operacijos atlikimą.

- **Data_Doc_IsSyncBacked** – ar debesies failas yra lokaliai ir ar sinchronizuojamas su serveriu.

- **Data_Doc_Location** – išvardijimas, rodantis failo vietą, pvz., lokaliai arba debesyje.

- **Data_Doc_ReadOnlyReasons** – išvardijimas, rodantis failo priežastį tik skaityti.

- **Data_Doc_ResourceIdHash** – GUID, unikaliai identifikuojantis failo serverio išteklių ID.

- **Data_Doc_RtcType** – išvardijimas, rodantis failo naudojamą realaus laiko kanalo (RTC) tipą.

- **Data_Doc_FqdnHash** – GUID, kuris unikaliai identifikuoja serverio dokumento ID.

- **Data_Doc_ServerProtocol** – išvardijimas, rodantis debesies failo serverio protokolą.

- **Data_Doc_ServerType** – išvardijimas, rodantis debesies failo serverio tipą.

- **Data_Doc_ServerVersion** – išvardijimas, rodantis debesies failo serverio versiją.

- **Data_Doc_SessionId** – sveikasis skaičius, padidėjantis 1 kiekvieną kartą, kai seanso metu atliekama failo atidarymo operacija.

- **Data_Doc_SharePointServiceContext** – eilutė, naudojama susieti kliento ir serverio žurnalus, paprastai tai yra ID tipas.

- **Data_Doc_SizeInBytes** – dokumento dydis baitais.

- **Data_Doc_SpecialChars** – išvardijimas, rodantis URL failo specialųjį simbolį.

- **Data_Doc_UrlHash** – GUID, kuris unikaliai identifikuoja failo URL.

- **Data_Doc_UsedWrsDataOnOpen** – ar failas buvo atidarytas palaipsniui naudojant iš anksto talpykloje saugomus WRS duomenis.

- **Data_Doc_WopiServiceId** – eilutė, rodanti iš kurios tarnybos yra WOPI (žiniatinklio taikomosios programos atviro platformos sąsajos protokolas) failas.

- **Data_DocumentInputCurrency** – operacijos naudojamas dokumento įvesties tipas.

- **Data_DocumentOperation_AppId** – išvardijimo reikšmė, vaizduojanti programos ID.

- **Data_DocumentOperation_EndEventId** – žymė, nurodanti, kur operacija buvo baigta.

- **Data_DocumentOperation_EndReason** – išvardijimo reikšmė, vaizduojanti galutinę priežastį.

- **Data_DocumentOperation_IsReinitialized** – iš naujo inicijuojamas jau atidarytas dokumentas.

- **Data_DocumentOperation_isTargetECBeginEC** – tai paskirties vykdymo kontekstas, toks pats kaip ir atidarymo šaltinio kontekstas.

- **Data_DocumentOperation_ParamsFlags** – išvardijimo vėliavėlės, naudojamos operacijai vykdyti.

- **Data_DocumentOperation_TelemetryReason** – atidaryto įvykio įeities taško išvardijimo reprezentacija. Pvz., atidaryti iš MRU arba naršyti, aktyvinti failą ir t.t.

- **Data_InclusiveMeasurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, kuri apima papildomų funkcijų iškvietimų trukmę.

- **Data_Measurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, neapimančia papildomų funkcijų iškvietimų trukmės.

- **Data_InitializationReason** – tam tikros operacijos priežasties išvardijimas. Pvz., atidaryti iš URL arba vietinio failo kelio, sukurti naudojant failų parinkiklį, kopijuoti į failo maršrutą, eksportuoti į URL ir t. t.

- **Data_IsDisambiguateCsiNetworkConnectivityErrorEnabled**.

- **Data_IsNameMissingInUrl** – nurodo, ar pavadinimas nebuvo išanalizuotas iš URL.

- **Data_IsPathMissingForLocalFile** – nurodo, ar tai vietinis failas be maršruto.

- **Data_IsUnpackedLinkSupportedForOpen** – nurodo, ar atidarymui palaikomas nepakuojamas saitas.

- **Data_LinksOpenRightScenario** – išvardijimo reikšmė, kuri nurodo, kaip atidaryti tinkamą scenarijų.

- **Data_OpEndEventId** – žymė, nurodanti, kur iš tikrųjų baigėsi operacija.

- **Data_OperationType** – skaičiuojamas bendrojo tipo operacijos vaizdas. Pvz., kurti, atidaryti, kopijuoti, įrašyti ir kt.

- **Data_RelatedPrevOpTelemetryReason** – operacija, susijusi su ankstesne operacija.

- **Data_StopwatchDuration** – bendras įvykio laikas.

- **Data_UnpackLinkHint** – išvardijimas, atspindintis galimą vartotojo veiksmą pagal išpakuojamą saitą.

- **Data_UnpackLinkPromptResult** – išvardijimas, žymintis saito išpakavimo raginimą.

#### <a name="officeappleactivateperpetual"></a>Office.Apple.ActivatePerpetual

Šis įvykis renkamas „Office“ taikomosioms programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas nuolatinio aktyvinimo srauto sveikatai stebėti bei tirti trikčių priežastims, peržiūrint parametro „FailedAt“ reikšmes.

Renkami šių laukų duomenys:

- **Data_FailedAt** – renkame duomenis eilutės, nurodančios aktyvaus nuolatinio licencijos srauto klaidą.

#### <a name="officeappleactivatesubscription"></a>Office.Apple.ActivateSubscription

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Mes renkame informaciją, susijusią su perkėlimu iš senstelėjusių licencijavimo kodų rinkinio į „vNext“ licencijavimo kodo rinkinį. Tai naudojama prenumeratos aktyvinimo srauto sveikatai stebėti, taip pat sekti, ar tai yra perkėlimas į „vNext“ licencijavimą ir ar buvo naudojamas pagrindinė tapatybė.

Renkami šių laukų duomenys:

- **Data_ActivatingPrimaryIdentity** – teisinga/klaidinga reikšmė, jei buvo naudojamas pagrindinį tapatybė. 

- **Data_NULSubscriptionLicensed** – teisinga/klaidinga reikšmė, žyminti prenumeratos būseną

#### <a name="officeapplecisauthticketwithidentity"></a>Office.Apple.CISAuthTicketWithIdentity

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas fiksuoti autorizavimo žymos generavimo klaidas atliekant InAppPurchase „Mac“ (įvykių žurnalai, gautas klaidos kodas).  Šis įvykis naudojamas nustatant ir sprendžiant autorizavimo žymos generavimo klaidas

Renkami šių laukų duomenys:

- **Data_EmptyAuthToken** – renkame eilutę, nurodančią aktyvaus nuolatinio licencijos srauto klaidą.

- **Data_TicketAuthError** – klaidos kodas, kuris nurodo klaidos priežastį

- **Data_ValidIdentity** – ar klientas turi tinkamą tapatybę

#### <a name="officeappleinappassociationactivity"></a>Office.Apple.InAppAssociationActivity

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Mes renkame informaciją, susijusią su produkto sąsaja pirkimo programėlėje. Užregistruojame, kurį prenumeratos SKU susiejame.  Tai naudojama pirkimo programėlėje produktų susiejimų sveikatai stebėti.

Renkami šių laukų duomenys:

- **Data_ProductID** – prenumeratos SKU, kuriam bandome susieti produktą.

#### <a name="officeappleinapppurchaseactivity"></a>Office.Apple.InAppPurchaseActivity

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. 

Renkame informaciją, susijusią su produktų pirkimu „AppStore“. Stebime pirkimo rezultatą (nepavyko, pavyko, mokėjimo problema ir t. t.), pirkimo užklausos tipą (atkūrimas, įsigijimas) ir įsigytą SKU/produktą („Microsoft 365 Family“ ir t. t.).  Šie duomenys naudojami pirkimo programėlėje srautų sveikatai stebėti.

Renkami šių laukų duomenys:

- **Data_ Data_PurchaseResult** – pirkimo operacijos rezultatas

- **Data_ProductID** – perkamas produktas

- **Data_PurchaseRequestType** – pirkimo užklausos tipas

#### <a name="officeappleintune"></a>Office.Apple.InTune

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Renkame, ar dabartinis seansas yra „Intune“ valdomas. Tai naudojama „Intune“ valdomuose seansuose greitai rikiuoti / filtruoti, bei suteikia mums galimybę ištirti galimas programos „Office, kuri vykdoma kaip „Intune“ valdoma taikomoji programa, triktis.

Renkami šių laukų duomenys:

- **Data_EventID** – renkame eilutę, nurodančią kodą, pateikiantį, ar seansas yra „Intune“ valdomas.

#### <a name="officeapplelicensingmaclicensingstate"></a>Office.Apple.Licensing.Mac.LicensingState

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis fiksuoja dabartinę seanso licencijos būseną kompiuteryje (OLS licencijos ID, naudojamą SKU, ar lengvatinis laikotarpis, RFM ir t. t.). Surinkti duomenys naudojami klaidoms aptikti ir nustatyti trikčių priežastis. 

Renkami šių laukų duomenys:

- **Data_DidRunPreview** – eilutė, nurodanti, ar seansas paleidžiamas dalyje Peržiūra

- **Data_LicensingACID** – eilutė, nurodanti licencijavimo sistemos vidinį identifikatorių

- **Data_LicensingType** – eilutė, nurodanti licencijos tipą

- **Data_OLSLicenseId** – eilutė, nurodanti licencijos identifikatorių

- **Data_State** – eilutė, nurodanti dabartinę licencijos būseną

#### <a name="officeconnectdeviceactivitystart"></a>Office.ConnectDevice.Activity.Start

Leidžia mums žinoti, ar buvo sėkmingai prisijungta prie įrenginio arba taikomosios programos.  Naudojama funkcijos sveikatai užtikrinti ir stebėti. Šis įvykis generuojamas „Microsoft“ srautinio duomenų siųstuvo, skirto „Excel“ papildiniui.

Renkami šių laukų duomenys:

- **Datasource_Type** – nuosekliojo įrenginio arba taikomosios programos tarnybos informacija

- **DataSource_Name** – prijungto duomenų šaltinio pavadinimas

- **Activity_Name** – „ConnectDevice“ veiklos pavadinimas

- **Activity_CV** = ID, skirtas nustatyti įvykius ryšio seanso metu

- **Activity_StartStopType** = paleidimas

- **Activity_DateTimeTicks** = veiklos data ir laikas
 
#### <a name="officeconnectdeviceactivitystop"></a>Office.ConnectDevice.Activity.Stop

Leidžia mums žinoti, ar buvo sėkmingai prisijungta prie įrenginio arba taikomosios programos. Naudojama funkcijos sveikatai užtikrinti ir stebėti. Šis įvykis generuojamas „Microsoft“ srautinio duomenų siųstuvo, skirto „Excel“ papildiniui.

Renkami šių laukų duomenys:

- **Datasource_Type** – nuosekliojo įrenginio arba taikomosios programos tarnybos informacija

- **DataSource_Name** – prijungto duomenų šaltinio pavadinimas

- **Activity_Name** – „ConnectDevice“ veiklos pavadinimas

- **Activity_CV** – ID, skirtas nustatyti įvykius ryšio seanso metu

- **Activity_StartStopType** – stabdymas

- **Activity_DateTimeTicks** – veiklos data ir laikas

#### <a name="officedocsappdocsoperationopenfrommrubypath"></a>Office.Docs.AppDocs.OperationOpenFromMruByPath

Šis įvykis renkamas „Office“ taikomosioms programoms, veikiančioms „Android“, „iOS“, „Universal“ arba „Windows“ platformose. Įvykis įrašomas, kai vykdoma failo atidarymo operacija iš kelio, pateikto vėliausiai naudotųjų sąraše, ir yra naudojamas siekiant suprasti bei pagal svarbą suskirstyti vartotojo patirties klaidas pagal failo atidarymo operacijos informaciją.

Renkami šių laukų duomenys:

- **Data_AppIdForReportEndBeforeAppKnown** – programos ID, kai ji nėra žinoma prieš operacijos pabaigą.

- **Data_CanContinueFromOnBeforeOperationBegins** – „CanContinue“ būsena prieš iškviečiant pradžios apdorojimo programą.

- **Data_DetachedDuration** – įvykio atsiejimo proceso trukmė. 

- **Data_Doc_AccessMode** – išvardijimas, rodantis failo prieigos režimą, pvz., tik skaityti, skaityti / rašyti.

- **Data_Doc_AsyncOpenKind** – išvardijimas, rodantis, kokio tipo asinchroninis srautas naudojamas failui atidaryti.

- **Data_Doc_ChunkingType** – Išvardijimas, rodantis failo segmentavimo algoritmą.

- **Data_Doc_EdpState** – išvardijimas, rodantis įmonės duomenų failo apsaugos būseną.

- **Data_Doc_Ext** – pirmieji 4 failo plėtinio simboliai.

- **Data_Doc_Fqdn** – failo serverio pagrindinio kompiuterio pavadinimas.

- **Data_Doc_FqdnHash** – GUID, kuris unikaliai identifikuoja serverio pagrindinio kompiuterio pavadinimą.

- **Data_Doc_IdentityTelemetryId** – vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša.

- **Data_Doc_InitializationScenario** – išvardijimas, rodantis išsamius failo atidarymo operacijos scenarijaus tipus.

- **Data_Doc_IOFlags** – išvardijimas, rodantis failo atidarymo operacijos įvesties ir išvesties žymes, pvz., ar failas yra talpykloje.

- **Data_Doc_IsCloudCollabEnabled** – ar šiam failui įgalintas bendradarbiavimas debesyje.

- **Data_Doc_IsIncrementalOpen** – ar failas buvo atidarytas naudojant papildantįjį atidarymą.

- **Data_Doc_IsOcsSupported** – ar failas palaiko „Office“ bendradarbiavimo tarnybą.

- **Data_Doc_IsOpeningOfflineCopy** – ar failas atidaromas iš autonominėje talpykloje laikomos kopijos.

- **Data_Doc_IsPrefetched** – ar failas buvo paimtas iš anksto prieš atidarymo operacijos atlikimą.

- **Data_Doc_IsSyncBacked** – ar debesies failas yra lokaliai ir ar sinchronizuojamas su serveriu.

- **Data_Doc_Location** – išvardijimas, rodantis failo vietą, pvz., lokaliai arba debesyje.

- **Data_Doc_ReadOnlyReasons** – išvardijimas, rodantis failo priežastį tik skaityti.

- **Data_Doc_ResourceIdHash** – GUID, unikaliai identifikuojantis failo serverio išteklių ID.

- **Data_Doc_RtcType** – išvardijimas, rodantis failo naudojamą realaus laiko kanalo (RTC) tipą.

- **Data_Doc_FqdnHash** – GUID, kuris unikaliai identifikuoja serverio dokumento ID.

- **Data_Doc_ServerProtocol** – išvardijimas, rodantis debesies failo serverio protokolą.

- **Data_Doc_ServerType** – išvardijimas, rodantis debesies failo serverio tipą.

- **Data_Doc_ServerVersion** – išvardijimas, rodantis debesies failo serverio versiją.

- **Data_Doc_SessionId** – sveikasis skaičius, padidėjantis 1 kiekvieną kartą, kai seanso metu atliekama failo atidarymo operacija.

- **Data_Doc_SharePointServiceContext** – eilutė, naudojama susieti kliento ir serverio žurnalus, paprastai tai yra ID tipas.

- **Data_Doc_SizeInBytes** – dokumento dydis baitais.

- **Data_Doc_SpecialChars** – išvardijimas, rodantis URL failo specialųjį simbolį.

- **Data_Doc_UrlHash** – GUID, kuris unikaliai identifikuoja failo URL.

- **Data_Doc_UsedWrsDataOnOpen** – ar failas buvo atidarytas palaipsniui naudojant iš anksto talpykloje saugomus WRS duomenis.

- **Data_Doc_WopiServiceId** – eilutė, rodanti iš kurios tarnybos yra WOPI (žiniatinklio taikomosios programos atviro platformos sąsajos protokolas) failas.

- **Data_DocumentInputCurrency** – operacijos naudojamas dokumento įvesties tipas.

- **Data_DocumentOperation_AppId** – išvardijimo reikšmė, vaizduojanti programos ID.

- **Data_DocumentOperation_EndEventId** – žymė, nurodanti, kur operacija buvo baigta.

- **Data_DocumentOperation_EndReason** – išvardijimo reikšmė, vaizduojanti galutinę priežastį.

- **Data_DocumentOperation_IsReinitialized** – iš naujo inicijuojamas jau atidarytas dokumentas.

- **Data_DocumentOperation_ParamsFlags** – išvardijimo vėliavėlės, naudojamos operacijai vykdyti.

- **Data_DocumentOperation_TelemetryReason** – atidaryto įvykio įeities taško išvardijimo reprezentacija. Pvz., atidaryti iš MRU arba naršyti, aktyvinti failą ir t.t.

- **Data_DocumentOperation_isTargetECBeginEC** – tai paskirties vykdymo kontekstas, toks pats kaip ir iš atidaryto konteksto.

- **Data_InclusiveMeasurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, kuri apima papildomų funkcijų iškvietimų trukmę.

- **Data_Measurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, neapimančia papildomų funkcijų iškvietimų trukmės.

- **Data_IsNameMissingInUrl** – nurodo, ar pavadinimas nebuvo išanalizuotas iš URL.

- **Data_IsPathMissingForLocalFile** – nurodo, ar tai vietinis failas be maršruto.

- **Data_IsUnpackedLinkSupportedForOpen** – nurodo, ar atidarymui palaikomas nepakuojamas saitas.

- **Data_LinksOpenRightScenario** – išvardijimo reikšmė, kuri nurodo, kaip atidaryti tinkamą scenarijų.

- **Data_OpEndEventId** – žymė, nurodanti, kur iš tikrųjų baigėsi operacija.

- **Data_RelatedPrevOpTelemetryReason** – operacija, susijusi su ankstesne operacija.

- **Data_StopwatchDuration** – bendras įvykio laikas.

- **Data_UnpackLinkHint** – išvardijimas, atspindintis galimą vartotojo veiksmą pagal išpakuojamą saitą.

- **Data_UnpackLinkPromptResult** – išvardijimas, žymintis saito išpakavimo raginimą.

#### <a name="officedocsappdocsoperationopenfrommrubyurl"></a>Office.Docs.AppDocs.OperationOpenFromMruByUrl

Šis įvykis renkamas „Office“ taikomosioms programoms, veikiančioms „Android“, „iOS“, „Universal“ arba „Windows“ platformose. Įvykis įrašomas, kai vykdoma failo atidarymo operacija iš URL, pateikto vėliausiai naudotųjų sąraše, ir yra naudojamas siekiant suprasti bei pagal svarbą suskirstyti vartotojo patirčiai pagal failo atidarymo operacijos informaciją. 

Renkami šių laukų duomenys:

- **Data_AppIdForReportEndBeforeAppKnown** – programos ID, kai ji nėra žinoma prieš operacijos pabaigą.

- **Data_CanContinueFromOnBeforeOperationBegins** – „CanContinue“ būsena prieš iškviečiant pradžios apdorojimo programą.

- **Data_DetachedDuration** – įvykio atsiejimo proceso trukmė. 

- **Data_Doc_AccessMode** – išvardijimas, rodantis failo prieigos režimą, pvz., tik skaityti, skaityti / rašyti.

- **Data_Doc_AsyncOpenKind** – išvardijimas, rodantis, kokio tipo asinchroninis srautas naudojamas failui atidaryti.

- **Data_Doc_ChunkingType** – Išvardijimas, rodantis failo segmentavimo algoritmą.

- **Data_Doc_EdpState** – išvardijimas, rodantis įmonės duomenų failo apsaugos būseną.

- **Data_Doc_Ext** – pirmieji 4 failo plėtinio simboliai.

- **Data_Doc_Fqdn** – failo serverio pagrindinio kompiuterio pavadinimas.

- **Data_Doc_FqdnHash** – GUID, kuris unikaliai identifikuoja serverio pagrindinio kompiuterio pavadinimą.

- **Data_Doc_IdentityTelemetryId** – vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša.

- **Data_Doc_InitializationScenario** – išvardijimas, rodantis išsamius failo atidarymo operacijos scenarijaus tipus.

- **Data_Doc_IOFlags** – išvardijimas, rodantis failo atidarymo operacijos įvesties ir išvesties žymes, pvz., ar failas yra talpykloje.

- **Data_Doc_IsCloudCollabEnabled** – ar šiam failui įgalintas bendradarbiavimas debesyje.

- **Data_Doc_IsIncrementalOpen** – ar failas buvo atidarytas naudojant papildantįjį atidarymą.

- **Data_Doc_IsOcsSupported** – ar failas palaiko „Office“ bendradarbiavimo tarnybą.

- **Data_Doc_IsOpeningOfflineCopy** – ar failas atidaromas iš autonominėje talpykloje laikomos kopijos.

- **Data_Doc_IsPrefetched** – ar failas buvo paimtas iš anksto prieš atidarymo operacijos atlikimą.

- **Data_Doc_IsSyncBacked** – ar debesies failas yra lokaliai ir ar sinchronizuojamas su serveriu.

- **Data_Doc_Location** – išvardijimas, rodantis failo vietą, pvz., lokaliai arba debesyje.

- **Data_Doc_ReadOnlyReasons** – išvardijimas, rodantis failo priežastį tik skaityti.

- **Data_Doc_ResourceIdHash** – GUID, unikaliai identifikuojantis failo serverio išteklių ID.

- **Data_Doc_RtcType** – išvardijimas, rodantis failo naudojamą realaus laiko kanalo (RTC) tipą.

- **Data_Doc_FqdnHash** – GUID, kuris unikaliai identifikuoja serverio dokumento ID.

- **Data_Doc_ServerProtocol** – išvardijimas, rodantis debesies failo serverio protokolą.

- **Data_Doc_ServerType** – išvardijimas, rodantis debesies failo serverio tipą.

- **Data_Doc_ServerVersion** – išvardijimas, rodantis debesies failo serverio versiją.

- **Data_Doc_SessionId** – sveikasis skaičius, padidėjantis 1 kiekvieną kartą, kai seanso metu atliekama failo atidarymo operacija.

- **Data_Doc_SharePointServiceContext** – eilutė, naudojama susieti kliento ir serverio žurnalus, paprastai tai yra ID tipas.

- **Data_Doc_SizeInBytes** – dokumento dydis baitais.

- **Data_Doc_SpecialChars** – išvardijimas, rodantis URL failo specialųjį simbolį.

- **Data_Doc_UrlHash** – GUID, kuris unikaliai identifikuoja failo URL.

- **Data_Doc_UsedWrsDataOnOpen** – ar failas buvo atidarytas palaipsniui naudojant iš anksto talpykloje saugomus WRS duomenis.

- **Data_Doc_WopiServiceId** – eilutė, rodanti iš kurios tarnybos yra WOPI (žiniatinklio taikomosios programos atviro platformos sąsajos protokolas) failas.

- **Data_DocumentInputCurrency** – operacijos naudojamas dokumento įvesties tipas.

- **Data_DocumentOperation_AppId** – išvardijimo reikšmė, vaizduojanti programos ID.

- **Data_DocumentOperation_EndEventId** – žymė, nurodanti, kur operacija buvo baigta.

- **Data_DocumentOperation_EndReason** – išvardijimo reikšmė, vaizduojanti galutinę priežastį.

- **Data_DocumentOperation_IsReinitialized** – iš naujo inicijuojamas jau atidarytas dokumentas.

- **Data_DocumentOperation_ParamsFlags** – išvardijimo vėliavėlės, naudojamos operacijai vykdyti.

- **Data_DocumentOperation_TelemetryReason** – atidaryto įvykio įeities taško išvardijimo reprezentacija. Pvz., atidaryti iš MRU arba naršyti, aktyvinti failą ir t.t.

- **Data_DocumentOperation_isTargetECBeginEC** – tai paskirties vykdymo kontekstas, toks pats kaip ir iš atidaryto konteksto.

- **Data_InclusiveMeasurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, kuri apima papildomų funkcijų iškvietimų trukmę.

- **Data_Measurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, neapimančia papildomų funkcijų iškvietimų trukmės.

- **Data_IsNameMissingInUrl** – nurodo, ar pavadinimas nebuvo išanalizuotas iš URL.

- **Data_IsPathMissingForLocalFile** – nurodo, ar tai vietinis failas be maršruto.

- **Data_IsUnpackedLinkSupportedForOpen** – nurodo, ar atidarymui palaikomas nepakuojamas saitas.

- **Data_LinksOpenRightScenario** – išvardijimo reikšmė, kuri nurodo, kaip atidaryti tinkamą scenarijų.

- **Data_OpEndEventId** – žymė, nurodanti, kur iš tikrųjų baigėsi operacija.

- **Data_RelatedPrevOpTelemetryReason** – operacija, susijusi su ankstesne operacija.

- **Data_StopwatchDuration** – bendras įvykio laikas.

- **Data_UnpackLinkHint** – išvardijimas, atspindintis galimą vartotojo veiksmą pagal išpakuojamą saitą.

- **Data_UnpackLinkPromptResult** – išvardijimas, žymintis saito išpakavimo raginimą.


#### <a name="officedocsappdocsoperationopenfrompath"></a>Office.Docs.AppDocs.OperationOpenFromPath

Šis įvykis renkamas „Office“ programoms, kurios veikia „Android“, „iOS“, „Universal“ arba „Windows“ platformose. Įvykių įrašai, kai vykdoma failo atidarymo operacija, naudojami suprasti ir nustatyti prioritetus vartotojo patirčiai pagal failo atidarymo operacijos informaciją.

Renkami šių laukų duomenys:

- **Data_AppIdForReportEndBeforeAppKnown** – programos ID, kai ji nėra žinoma prieš operacijos pabaigą.

- **Data_CanContinueFromOnBeforeOperationBegins** – „CanContinue“ būsena prieš iškviečiant pradžios apdorojimo programą.

- **Data_DetachedDuration** – įvykio atsiejimo proceso trukmė. 

- **Data_Doc_AccessMode** – išvardijimas, rodantis failo prieigos režimą, pvz., tik skaityti, skaityti / rašyti.

- **Data_Doc_AsyncOpenKind** – išvardijimas, rodantis, kokio tipo asinchroninis srautas naudojamas failui atidaryti.

- **Data_Doc_ChunkingType** – Išvardijimas, rodantis failo segmentavimo algoritmą.

- **Data_Doc_EdpState** – išvardijimas, rodantis įmonės duomenų failo apsaugos būseną.

- **Data_Doc_Ext** – pirmieji 4 failo plėtinio simboliai.

- **Data_Doc_Fqdn** – failo serverio pagrindinio kompiuterio pavadinimas.

- **Data_Doc_FqdnHash** – GUID, kuris unikaliai identifikuoja serverio pagrindinio kompiuterio pavadinimą.

- **Data_Doc_IdentityTelemetryId** – vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša.

- **Data_Doc_InitializationScenario** – išvardijimas, rodantis išsamius failo atidarymo operacijos scenarijaus tipus.

- **Data_Doc_IOFlags** – išvardijimas, rodantis failo atidarymo operacijos įvesties ir išvesties žymes, pvz., ar failas yra talpykloje.

- **Data_Doc_IsCloudCollabEnabled** – ar šiam failui įgalintas bendradarbiavimas debesyje.

- **Data_Doc_IsIncrementalOpen** – ar failas buvo atidarytas naudojant papildantįjį atidarymą.

- **Data_Doc_IsOcsSupported** – ar failas palaiko „Office“ bendradarbiavimo tarnybą.

- **Data_Doc_IsOpeningOfflineCopy** – ar failas atidaromas iš autonominėje talpykloje laikomos kopijos.

- **Data_Doc_IsPrefetched** – ar failas buvo paimtas iš anksto prieš atidarymo operacijos atlikimą.

- **Data_Doc_IsSyncBacked** – ar debesies failas yra lokaliai ir ar sinchronizuojamas su serveriu.

- **Data_Doc_Location** – išvardijimas, rodantis failo vietą, pvz., lokaliai arba debesyje.

- **Data_Doc_ReadOnlyReasons** – išvardijimas, rodantis failo priežastį tik skaityti.

- **Data_Doc_ResourceIdHash** – GUID, unikaliai identifikuojantis failo serverio išteklių ID.

- **Data_Doc_RtcType** – išvardijimas, rodantis failo naudojamą realaus laiko kanalo (RTC) tipą.

- **Data_Doc_FqdnHash** – GUID, kuris unikaliai identifikuoja serverio dokumento ID.

- **Data_Doc_ServerProtocol** – išvardijimas, rodantis debesies failo serverio protokolą.

- **Data_Doc_ServerType** – išvardijimas, rodantis debesies failo serverio tipą.

- **Data_Doc_ServerVersion** – išvardijimas, rodantis debesies failo serverio versiją.

- **Data_Doc_SessionId** – sveikasis skaičius, padidėjantis 1 kiekvieną kartą, kai seanso metu atliekama failo atidarymo operacija.

- **Data_Doc_SharePointServiceContext** – eilutė, naudojama susieti kliento ir serverio žurnalus, paprastai tai yra ID tipas.

- **Data_Doc_SizeInBytes** – dokumento dydis baitais.

- **Data_Doc_SpecialChars** – išvardijimas, rodantis URL failo specialųjį simbolį.

- **Data_Doc_UrlHash** – GUID, kuris unikaliai identifikuoja failo URL.

- **Data_Doc_UsedWrsDataOnOpen** – ar failas buvo atidarytas palaipsniui naudojant iš anksto talpykloje saugomus WRS duomenis.

- **Data_Doc_WopiServiceId** – eilutė, rodanti iš kurios tarnybos yra WOPI (žiniatinklio taikomosios programos atviro platformos sąsajos protokolas) failas.

- **Data_DocumentInputCurrency** – operacijos naudojamas dokumento įvesties tipas.

- **Data_DocumentOperation_AppId** – išvardijimo reikšmė, vaizduojanti programos ID.

- **Data_DocumentOperation_EndEventId** – žymė, nurodanti, kur operacija buvo baigta.

- **Data_DocumentOperation_EndReason** – išvardijimo reikšmė, vaizduojanti galutinę priežastį.

- **Data_DocumentOperation_IsReinitialized** – iš naujo inicijuojamas jau atidarytas dokumentas.

- **Data_DocumentOperation_ParamsFlags** – išvardijimo vėliavėlės, naudojamos operacijai vykdyti.

- **Data_DocumentOperation_TelemetryReason** – atidaryto įvykio įeities taško išvardijimo reprezentacija. Pvz., atidaryti iš MRU arba naršyti, aktyvinti failą ir t.t.

- **Data_DocumentOperation_isTargetECBeginEC** – tai paskirties vykdymo kontekstas, toks pats kaip ir iš atidaryto konteksto.

- **Data_InclusiveMeasurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, kuri apima papildomų funkcijų iškvietimų trukmę.

- **Data_Measurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, neapimančia papildomų funkcijų iškvietimų trukmės.

- **Data_IsNameMissingInUrl** – nurodo, ar pavadinimas nebuvo išanalizuotas iš URL.

- **Data_IsPathMissingForLocalFile** – nurodo, ar tai vietinis failas be maršruto.

- **Data_IsUnpackedLinkSupportedForOpen** – nurodo, ar atidarymui palaikomas nepakuojamas saitas.

- **Data_LinksOpenRightScenario** – išvardijimo reikšmė, kuri nurodo, kaip atidaryti tinkamą scenarijų.

- **Data_OpEndEventId** – žymė, nurodanti, kur iš tikrųjų baigėsi operacija.

- **Data_RelatedPrevOpTelemetryReason** – operacija, susijusi su ankstesne operacija.

- **Data_StopwatchDuration** – bendras įvykio laikas.

- **Data_UnpackLinkHint** – išvardijimas, atspindintis galimą vartotojo veiksmą pagal išpakuojamą saitą.

- **Data_UnpackLinkPromptResult** – išvardijimas, žymintis saito išpakavimo raginimą.

#### <a name="officedocsappdocsoperationopenfromprotocolhandler"></a>Office.Docs.AppDocs.OperationOpenFromProtocolHandler

Šis įvykis renkamas „Office“ programoms, kurios veikia „Android“, „iOS“, „Universal“ arba „Windows“ platformose. Įvykių įrašai, kai vykdoma failo atidarymo operacija iš kitos programos naudojant protokolų apdorojimo sąsają, naudojama suprasti ir nustatyti prioritetus vartotojo patirčiai pagal failo atidarymo operacijos informaciją.

Renkami šių laukų duomenys:

- **Data_AppIdForReportEndBeforeAppKnown** – programos ID, kai ji nėra žinoma prieš operacijos pabaigą.

- **Data_CanContinueFromOnBeforeOperationBegins** – „CanContinue“ būsena prieš iškviečiant pradžios apdorojimo programą.

- **Data_DetachedDuration** – įvykio atsiejimo proceso trukmė. 

- **Data_Doc_AccessMode** – išvardijimas, rodantis failo prieigos režimą, pvz., tik skaityti, skaityti / rašyti.

- **Data_Doc_AsyncOpenKind** – išvardijimas, rodantis, kokio tipo asinchroninis srautas naudojamas failui atidaryti.

- **Data_Doc_ChunkingType** – Išvardijimas, rodantis failo segmentavimo algoritmą.

- **Data_Doc_EdpState** – išvardijimas, rodantis įmonės duomenų failo apsaugos būseną.

- **Data_Doc_Ext** – pirmieji 4 failo plėtinio simboliai.

- **Data_Doc_Fqdn** – failo serverio pagrindinio kompiuterio pavadinimas.

- **Data_Doc_FqdnHash** – GUID, kuris unikaliai identifikuoja serverio pagrindinio kompiuterio pavadinimą.

- **Data_Doc_IdentityTelemetryId** – vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša.

- **Data_Doc_InitializationScenario** – išvardijimas, rodantis išsamius failo atidarymo operacijos scenarijaus tipus.

- **Data_Doc_IOFlags** – išvardijimas, rodantis failo atidarymo operacijos įvesties ir išvesties žymes, pvz., ar failas yra talpykloje.

- **Data_Doc_IsCloudCollabEnabled** – ar šiam failui įgalintas bendradarbiavimas debesyje.

- **Data_Doc_IsIncrementalOpen** – ar failas buvo atidarytas naudojant papildantįjį atidarymą.

- **Data_Doc_IsOcsSupported** – ar failas palaiko „Office“ bendradarbiavimo tarnybą.

- **Data_Doc_IsOpeningOfflineCopy** – ar failas atidaromas iš autonominėje talpykloje laikomos kopijos.

- **Data_Doc_IsPrefetched** – ar failas buvo paimtas iš anksto prieš atidarymo operacijos atlikimą.

- **Data_Doc_IsSyncBacked** – ar debesies failas yra lokaliai ir ar sinchronizuojamas su serveriu.

- **Data_Doc_Location** – išvardijimas, rodantis failo vietą, pvz., lokaliai arba debesyje.

- **Data_Doc_ReadOnlyReasons** – išvardijimas, rodantis failo priežastį tik skaityti.

- **Data_Doc_ResourceIdHash** – GUID, unikaliai identifikuojantis failo serverio išteklių ID.

- **Data_Doc_RtcType** – išvardijimas, rodantis failo naudojamą realaus laiko kanalo (RTC) tipą.

- **Data_Doc_FqdnHash** – GUID, kuris unikaliai identifikuoja serverio dokumento ID.

- **Data_Doc_ServerProtocol** – išvardijimas, rodantis debesies failo serverio protokolą.

- **Data_Doc_ServerType** – išvardijimas, rodantis debesies failo serverio tipą.

- **Data_Doc_ServerVersion** – išvardijimas, rodantis debesies failo serverio versiją.

- **Data_Doc_SessionId** – sveikasis skaičius, padidėjantis 1 kiekvieną kartą, kai seanso metu atliekama failo atidarymo operacija.

- **Data_Doc_SharePointServiceContext** – eilutė, naudojama susieti kliento ir serverio žurnalus, paprastai tai yra ID tipas.

- **Data_Doc_SizeInBytes** – dokumento dydis baitais.

- **Data_Doc_SpecialChars** – išvardijimas, rodantis URL failo specialųjį simbolį.

- **Data_Doc_UrlHash** – GUID, kuris unikaliai identifikuoja failo URL.

- **Data_Doc_UsedWrsDataOnOpen** – ar failas buvo atidarytas palaipsniui naudojant iš anksto talpykloje saugomus WRS duomenis.

- **Data_Doc_WopiServiceId** – eilutė, rodanti iš kurios tarnybos yra WOPI (žiniatinklio taikomosios programos atviro platformos sąsajos protokolas) failas.

- **Data_DocumentInputCurrency** – operacijos naudojamas dokumento įvesties tipas.

- **Data_DocumentOperation_AppId** – išvardijimo reikšmė, vaizduojanti programos ID.

- **Data_DocumentOperation_EndEventId** – žymė, nurodanti, kur operacija buvo baigta.

- **Data_DocumentOperation_EndReason** – išvardijimo reikšmė, vaizduojanti galutinę priežastį.

- **Data_DocumentOperation_IsReinitialized** – iš naujo inicijuojamas jau atidarytas dokumentas.

- **Data_DocumentOperation_ParamsFlags** – išvardijimo vėliavėlės, naudojamos operacijai vykdyti.

- **Data_DocumentOperation_TelemetryReason** – atidaryto įvykio įeities taško išvardijimo reprezentacija. Pvz., atidaryti iš MRU arba naršyti, aktyvinti failą ir t.t.

- **Data_DocumentOperation_isTargetECBeginEC** – tai paskirties vykdymo kontekstas, toks pats kaip ir iš atidaryto konteksto.

- **Data_InclusiveMeasurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, kuri apima papildomų funkcijų iškvietimų trukmę.

- **Data_Measurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, neapimančia papildomų funkcijų iškvietimų trukmės.

- **Data_IsNameMissingInUrl** – nurodo, ar pavadinimas nebuvo išanalizuotas iš URL.

- **Data_IsPathMissingForLocalFile** – nurodo, ar tai vietinis failas be maršruto.

- **Data_IsUnpackedLinkSupportedForOpen** – nurodo, ar atidarymui palaikomas nepakuojamas saitas.

- **Data_LinksOpenRightScenario** – išvardijimo reikšmė, kuri nurodo, kaip atidaryti tinkamą scenarijų.

- **Data_OpEndEventId** – žymė, nurodanti, kur iš tikrųjų baigėsi operacija.

- **Data_RelatedPrevOpTelemetryReason** – operacija, susijusi su ankstesne operacija.

- **Data_StopwatchDuration** – bendras įvykio laikas.

- **Data_UnpackLinkHint** – išvardijimas, atspindintis galimą vartotojo veiksmą pagal išpakuojamą saitą.

- **Data_UnpackLinkPromptResult** – išvardijimas, žymintis saito išpakavimo raginimą.

#### <a name="officedocsappdocsoperationopenfromshell"></a>Office.Docs.AppDocs.OperationOpenFromShell

Šis įvykis renkamas „Office“ programoms, kurios veikia „Android“, „iOS“, „Universal“ arba „Windows“ platformose. Įvykių įrašai, kai vykdoma failo atidarymo operacija iš apvalkalo, naudojami suprasti ir nustatyti prioritetus vartotojo patirčiai pagal failo atidarymo operacijos informaciją.

Renkami šių laukų duomenys:

- **Data_AppIdForReportEndBeforeAppKnown** – programos ID, kai ji nėra žinoma prieš operacijos pabaigą.

- **Data_CanContinueFromOnBeforeOperationBegins** – „CanContinue“ būsena prieš iškviečiant pradžios apdorojimo programą.

- **Data_DetachedDuration** – įvykio atsiejimo proceso trukmė. 

- **Data_Doc_AccessMode** – išvardijimas, rodantis failo prieigos režimą, pvz., tik skaityti, skaityti / rašyti.

- **Data_Doc_AsyncOpenKind** – išvardijimas, rodantis, kokio tipo asinchroninis srautas naudojamas failui atidaryti.

- **Data_Doc_ChunkingType** – Išvardijimas, rodantis failo segmentavimo algoritmą.

- **Data_Doc_EdpState** – išvardijimas, rodantis įmonės duomenų failo apsaugos būseną.

- **Data_Doc_Ext** – pirmieji 4 failo plėtinio simboliai.

- **Data_Doc_Fqdn** – failo serverio pagrindinio kompiuterio pavadinimas.

- **Data_Doc_FqdnHash** – GUID, kuris unikaliai identifikuoja serverio pagrindinio kompiuterio pavadinimą.

- **Data_Doc_IdentityTelemetryId** – vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša.

- **Data_Doc_InitializationScenario** – išvardijimas, rodantis išsamius failo atidarymo operacijos scenarijaus tipus.

- **Data_Doc_IOFlags** – išvardijimas, rodantis failo atidarymo operacijos įvesties ir išvesties žymes, pvz., ar failas yra talpykloje.

- **Data_Doc_IsCloudCollabEnabled** – ar šiam failui įgalintas bendradarbiavimas debesyje.

- **Data_Doc_IsIncrementalOpen** – ar failas buvo atidarytas naudojant papildantįjį atidarymą.

- **Data_Doc_IsOcsSupported** – ar failas palaiko „Office“ bendradarbiavimo tarnybą.

- **Data_Doc_IsOpeningOfflineCopy** – ar failas atidaromas iš autonominėje talpykloje laikomos kopijos.

- **Data_Doc_IsPrefetched** – ar failas buvo paimtas iš anksto prieš atidarymo operacijos atlikimą.

- **Data_Doc_IsSyncBacked** – ar debesies failas yra lokaliai ir ar sinchronizuojamas su serveriu.

- **Data_Doc_Location** – išvardijimas, rodantis failo vietą, pvz., lokaliai arba debesyje.

- **Data_Doc_ReadOnlyReasons** – išvardijimas, rodantis failo priežastį tik skaityti.

- **Data_Doc_ResourceIdHash** – GUID, unikaliai identifikuojantis failo serverio išteklių ID.

- **Data_Doc_RtcType** – išvardijimas, rodantis failo naudojamą realaus laiko kanalo (RTC) tipą.

- **Data_Doc_FqdnHash** – GUID, kuris unikaliai identifikuoja serverio dokumento ID.

- **Data_Doc_ServerProtocol** – išvardijimas, rodantis debesies failo serverio protokolą.

- **Data_Doc_ServerType** – išvardijimas, rodantis debesies failo serverio tipą.

- **Data_Doc_ServerVersion** – išvardijimas, rodantis debesies failo serverio versiją.

- **Data_Doc_SessionId** – sveikasis skaičius, padidėjantis 1 kiekvieną kartą, kai seanso metu atliekama failo atidarymo operacija.

- **Data_Doc_SharePointServiceContext** – eilutė, naudojama susieti kliento ir serverio žurnalus, paprastai tai yra ID tipas.

- **Data_Doc_SizeInBytes** – dokumento dydis baitais.

- **Data_Doc_SpecialChars** – išvardijimas, rodantis URL failo specialųjį simbolį.

- **Data_Doc_UrlHash** – GUID, kuris unikaliai identifikuoja failo URL.

- **Data_Doc_UsedWrsDataOnOpen** – ar failas buvo atidarytas palaipsniui naudojant iš anksto talpykloje saugomus WRS duomenis.

- **Data_Doc_WopiServiceId** – eilutė, rodanti iš kurios tarnybos yra WOPI (žiniatinklio taikomosios programos atviro platformos sąsajos protokolas) failas.

- **Data_DocumentInputCurrency** – operacijos naudojamas dokumento įvesties tipas.

- **Data_DocumentOperation_AppId** – išvardijimo reikšmė, vaizduojanti programos ID.

- **Data_DocumentOperation_EndEventId** – žymė, nurodanti, kur operacija buvo baigta.

- **Data_DocumentOperation_EndReason** – išvardijimo reikšmė, vaizduojanti galutinę priežastį.

- **Data_DocumentOperation_IsReinitialized** – iš naujo inicijuojamas jau atidarytas dokumentas.

- **Data_DocumentOperation_ParamsFlags** – išvardijimo vėliavėlės, naudojamos operacijai vykdyti.

- **Data_DocumentOperation_TelemetryReason** – atidaryto įvykio įeities taško išvardijimo reprezentacija. Pvz., atidaryti iš MRU arba naršyti, aktyvinti failą ir t.t.

- **Data_DocumentOperation_isTargetECBeginEC** – tai paskirties vykdymo kontekstas, toks pats kaip ir iš atidaryto konteksto.

- **Data_InclusiveMeasurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, kuri apima papildomų funkcijų iškvietimų trukmę.

- **Data_Measurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, neapimančia papildomų funkcijų iškvietimų trukmės.

- **Data_IsNameMissingInUrl** – nurodo, ar pavadinimas nebuvo išanalizuotas iš URL.

- **Data_IsPathMissingForLocalFile** – nurodo, ar tai vietinis failas be maršruto.

- **Data_IsUnpackedLinkSupportedForOpen** – nurodo, ar atidarymui palaikomas nepakuojamas saitas.

- **Data_LinksOpenRightScenario** – išvardijimo reikšmė, kuri nurodo, kaip atidaryti tinkamą scenarijų.

- **Data_OpEndEventId** – žymė, nurodanti, kur iš tikrųjų baigėsi operacija.

- **Data_RelatedPrevOpTelemetryReason** – operacija, susijusi su ankstesne operacija.

- **Data_StopwatchDuration** – bendras įvykio laikas.

- **Data_UnpackLinkHint** – išvardijimas, atspindintis galimą vartotojo veiksmą pagal išpakuojamą saitą.

- **Data_UnpackLinkPromptResult** – išvardijimas, žymintis saito išpakavimo raginimą.


#### <a name="officedocsappdocsoperationopenfromurl"></a>Office.Docs.AppDocs.OperationOpenFromUrl

Šis įvykis renkamas „Office“ programoms, kurios veikia „Android“, „iOS“, „Universal“ arba „Windows“ platformose. Įvykių įrašai, kai vykdoma failo atidarymo operacija iš URL, naudojami suprasti ir nustatyti prioritetus vartotojo patirčiai pagal failo atidarymo operacijos informaciją.

Renkami šių laukų duomenys:

- **Data_AppIdForReportEndBeforeAppKnown** – programos ID, kai ji nėra žinoma prieš operacijos pabaigą.

- **Data_CanContinueFromOnBeforeOperationBegins** – „CanContinue“ būsena prieš iškviečiant pradžios apdorojimo programą.

- **Data_DetachedDuration** – įvykio atsiejimo proceso trukmė. 

- **Data_Doc_AccessMode** – išvardijimas, rodantis failo prieigos režimą, pvz., tik skaityti, skaityti / rašyti.

- **Data_Doc_AsyncOpenKind** – išvardijimas, rodantis, kokio tipo asinchroninis srautas naudojamas failui atidaryti.

- **Data_Doc_ChunkingType** – Išvardijimas, rodantis failo segmentavimo algoritmą.

- **Data_Doc_EdpState** – išvardijimas, rodantis įmonės duomenų failo apsaugos būseną.

- **Data_Doc_Ext** – pirmieji 4 failo plėtinio simboliai.

- **Data_Doc_Fqdn** – failo serverio pagrindinio kompiuterio pavadinimas.

- **Data_Doc_FqdnHash** – GUID, kuris unikaliai identifikuoja serverio pagrindinio kompiuterio pavadinimą.

- **Data_Doc_IdentityTelemetryId** – vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša.

- **Data_Doc_InitializationScenario** – išvardijimas, rodantis išsamius failo atidarymo operacijos scenarijaus tipus.

- **Data_Doc_IOFlags** – išvardijimas, rodantis failo atidarymo operacijos įvesties ir išvesties žymes, pvz., ar failas yra talpykloje.

- **Data_Doc_IsCloudCollabEnabled** – ar šiam failui įgalintas bendradarbiavimas debesyje.

- **Data_Doc_IsIncrementalOpen** – ar failas buvo atidarytas naudojant papildantįjį atidarymą.

- **Data_Doc_IsOcsSupported** – ar failas palaiko „Office“ bendradarbiavimo tarnybą.

- **Data_Doc_IsOpeningOfflineCopy** – ar failas atidaromas iš autonominėje talpykloje laikomos kopijos.

- **Data_Doc_IsPrefetched** – ar failas buvo paimtas iš anksto prieš atidarymo operacijos atlikimą.

- **Data_Doc_IsSyncBacked** – ar debesies failas yra lokaliai ir ar sinchronizuojamas su serveriu.

- **Data_Doc_Location** – išvardijimas, rodantis failo vietą, pvz., lokaliai arba debesyje.

- **Data_Doc_ReadOnlyReasons** – išvardijimas, rodantis failo priežastį tik skaityti.

- **Data_Doc_ResourceIdHash** – GUID, unikaliai identifikuojantis failo serverio išteklių ID.

- **Data_Doc_RtcType** – išvardijimas, rodantis failo naudojamą realaus laiko kanalo (RTC) tipą.

- **Data_Doc_FqdnHash** – GUID, kuris unikaliai identifikuoja serverio dokumento ID.

- **Data_Doc_ServerProtocol** – išvardijimas, rodantis debesies failo serverio protokolą.

- **Data_Doc_ServerType** – išvardijimas, rodantis debesies failo serverio tipą.

- **Data_Doc_ServerVersion** – išvardijimas, rodantis debesies failo serverio versiją.

- **Data_Doc_SessionId** – sveikasis skaičius, padidėjantis 1 kiekvieną kartą, kai seanso metu atliekama failo atidarymo operacija.

- **Data_Doc_SharePointServiceContext** – eilutė, naudojama susieti kliento ir serverio žurnalus, paprastai tai yra ID tipas.

- **Data_Doc_SizeInBytes** – dokumento dydis baitais.

- **Data_Doc_SpecialChars** – išvardijimas, rodantis URL failo specialųjį simbolį.

- **Data_Doc_UrlHash** – GUID, kuris unikaliai identifikuoja failo URL.

- **Data_Doc_UsedWrsDataOnOpen** – ar failas buvo atidarytas palaipsniui naudojant iš anksto talpykloje saugomus WRS duomenis.

- **Data_Doc_WopiServiceId** – eilutė, rodanti iš kurios tarnybos yra WOPI (žiniatinklio taikomosios programos atviro platformos sąsajos protokolas) failas.

- **Data_DocumentInputCurrency** – operacijos naudojamas dokumento įvesties tipas.

- **Data_DocumentOperation_AppId** – išvardijimo reikšmė, vaizduojanti programos ID.

- **Data_DocumentOperation_EndEventId** – žymė, nurodanti, kur operacija buvo baigta.

- **Data_DocumentOperation_EndReason** – išvardijimo reikšmė, vaizduojanti galutinę priežastį.

- **Data_DocumentOperation_IsReinitialized** – iš naujo inicijuojamas jau atidarytas dokumentas.

- **Data_DocumentOperation_ParamsFlags** – išvardijimo vėliavėlės, naudojamos operacijai vykdyti.

- **Data_DocumentOperation_TelemetryReason** – atidaryto įvykio įeities taško išvardijimo reprezentacija. Pvz., atidaryti iš MRU arba naršyti, aktyvinti failą ir t.t.

- **Data_DocumentOperation_isTargetECBeginEC** – tai paskirties vykdymo kontekstas, toks pats kaip ir iš atidaryto konteksto.

- **Data_InclusiveMeasurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, kuri apima papildomų funkcijų iškvietimų trukmę.

- **Data_Measurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, neapimančia papildomų funkcijų iškvietimų trukmės.

- **Data_IsNameMissingInUrl** – nurodo, ar pavadinimas nebuvo išanalizuotas iš URL.

- **Data_IsPathMissingForLocalFile** – nurodo, ar tai vietinis failas be maršruto.

- **Data_IsUnpackedLinkSupportedForOpen** – nurodo, ar atidarymui palaikomas nepakuojamas saitas.

- **Data_LinksOpenRightScenario** – išvardijimo reikšmė, kuri nurodo, kaip atidaryti tinkamą scenarijų.

- **Data_OpEndEventId** – žymė, nurodanti, kur iš tikrųjų baigėsi operacija.

- **Data_RelatedPrevOpTelemetryReason** – operacija, susijusi su ankstesne operacija.

- **Data_StopwatchDuration** – bendras įvykio laikas.

- **Data_UnpackLinkHint** – išvardijimas, atspindintis galimą vartotojo veiksmą pagal išpakuojamą saitą.

- **Data_UnpackLinkPromptResult** – išvardijimas, žymintis saito išpakavimo raginimą.



#### <a name="officedocsappledocsuxiossaveasthroughfilemenu"></a>Office.Docs.Apple.DocsUXiOSSaveAsThroughFileMenu 

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis įrašomas, kai vykdoma operacija Įrašyti kaip, ir naudojamas siekiant suprasti ir nustatyti prioritetus vartotojo patirčiai pagal failo operacijos informaciją, pvz., vietų kategorijas.  Operacija „įrašyti kaip“ vykdoma, kai vartotojas sukuria naują failą ir įrašo jį pirmą kartą arba išsaugo esamo failo kopiją naujoje vietoje.

Renkami šių laukų duomenys:

- **Data_OriginServiceType** – pradinės failo vietos, pvz., „SharePoint“, „OneDrive“, „Local“, „WOPI“ ir t. t., abstraktus kategorizavimas, ir aiškus nurodymas, kad tai nėra faktinė failo vieta.

- **Data_ServiceType** – naujos failo vietos, pvz., „SharePoint“, „OneDrive“, „Local“, „WOPI“ ir t. t., abstraktus kategorizavimas kai įrašymas yra baigtas ir aiškus nurodymas, kad tai nėra faktinė failo vieta.

#### <a name="officedocsappledocsuxmacatmentioninsertedatmention"></a>Office.Docs.Apple.DocsUXMacAtMentionInsertedAtMention 

Šis įvykis renkamas „Office“ taikomosioms programoms, veikiančioms „Apple“ platformose. Šis įvykis įrašo, kada vartotojas „@“ pamini kitą vartotoją ir yra naudojamas norint suprasti ir nustatyti vartotojo patirčių prioritetus, atsižvelgiant į tai, kaip vartotojai bendradarbiauja su kitais vartotojais.

Renkami šių laukų duomenys:

- **Data_CharactersTyped** – skaitinė reikšmė, nurodanti bendrą simbolių skaičių, įvestą tekste, kuriame minimas vartotojas „@“.

#### <a name="officedocsappledocsuxmacodspsharingwebviewsharingcompleted"></a>Office.Docs.Apple.DocsUXMacODSPSharingWebViewSharingCompleted 

Šis įvykis renkamas „Office“ taikomosioms programoms, veikiančioms „Apple“ platformose. Šis įvykis įrašo, kada vartotojas pasirenka bendrinti debesies dokumentą naudodamas „OneDrive“ bendrinimo patirtį ir yra naudojamas norint geriau suprasti ir nustatyti vartotojo patirties prioritetus, atsižvelgiant į dokumentų bendrinimą.

Renkami šių laukų duomenys:

- **Data_ShareType** – užprogramuota eilutė, kurioje nurodoma, kokio tipo operacija buvo baigta, įskaitant (bet tuo neapsiribojant) operacijas „kopijuoti saitą“, „daugiau programų“, „Teams“.

- **Data_ShareWebViewMode** – užprogramuota eilutė, nurodanti, kokio tipo bendrinimo režimas buvo aktyvus, kai bendrinamas buvo baigtas, įskaitant (bet tuo neapsiribojant) „ManageAccess“, „AtMentions“, Bendrinti.

#### <a name="officedocsuicollaborationcoauthorgalleryrowtapped"></a>Office.DocsUI.Collaboration.CoauthorGalleryRowTapped 

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Šis įvykis fiksuoja, kada vartotojas pasirenka dabartinio bendraautorių sąrašo peržiūrą.  Šie duomenys naudojami siekiant geriau suprasti ir nustatyti vartotojo patirčių prioritetus, susijusius su dokumento redagavimu vienu metu.

Renkami šių laukų duomenys:

- **Data_CoauthorCount** – skaitinė reikšmė, nurodanti bendrą skaičių žmonių, kurie vienu metu redaguoja tą patį dokumentą.

#### <a name="officedocsuicollaborationcollabcornerpeoplegallerycoauthorsupdated"></a>Office.DocsUI.Collaboration.CollabCornerPeopleGalleryCoauthorsUpdated 

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykių įrašai, kai pasikeičia aktyvių bendraautorių skaičius debesies dokumente.  Šie duomenys naudojami siekiant geriau suprasti ir nustatyti vartotojo patirčių prioritetus, susijusius su dokumento redagavimu vienu metu.

Renkami šių laukų duomenys:

- **Data_CoauthorsJoined** – bendraautorių, prisijungusių prie dokumento, skaičius.

- **Data_CoauthorsLeft** – bendraautorių, kurie atsijungė nuo dokumento, skaičius.

- **Data_NewCoauthorCount** – naujas aktyvių dokumento bendraautorių skaičius. 

- **Data_OldCoauthorCount** – ankstesnis prieš naujinimą nustatytas aktyvių bendraautorių skaičius.

- **Data_ServiceType** – failo vietos, pvz., „SharePoint“, „OneDrive“, „Local“, „WOPI“ ir t. t., abstraktus kategorizavimas ir aiškus nurodymas, kad tai nėra faktinė failo vieta.

#### <a name="officedocsuidocstagedocstagecreatenewfromtemplate"></a>Office.DocsUI.DocStage.DocStageCreateNewFromTemplate 

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis įrašomas, kai sukuriamas naujas failas naudojant funkciją Naujas iš šablono, ir naudojamas siekiant geriau suprasti ir nustatyti vartotojo patirties prioritetus, atsižvelgiant į dokumentų kūrimo informaciją.

Renkami šių laukų duomenys:

- **Data_InHomeTab** – Bulio logikos reikšmė, nurodanti, ar naujas failas iš šablono buvo sukurtas failo naujų funkcijų skirtuke Pagrindinis.

- **Data_InSearch** – Bulio logika, nurodanti, ar failas buvo sukurtas, kai vartotojas ieškojo šablono.

- **Data_IsHomeTabEnabled** – Bulio logikos reikšmė, nurodanti, ar skirtukas Pagrindinis šiuo metu pasiekiamas vartotojui.

- **Data_IsRecommendedEnabled** – Bulio logikos reikšmė, nurodanti, ar patirtis Rekomenduojama šiuo metu pasiekiamas vartotojui.

- **Data_TemplateIndex** – vartotojui vizualiai rodomas šablono failo skaitinis indeksas.

- **Data_TemplateType** – klasifikacija, padedanti atskirti šablono tipą, įskaitant (bet tuo neapsiribojant) šablonus „Online“, „Online search“ ar „Local“.

#### <a name="officedocsuidocstagerecommendedopen"></a>Office.DocsUI.DocStage.RecommendedOpen

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis įrašo, kada vykdoma failo atidarymo operacija iš rekomenduojamo dokumentų galerijos failų skyriaus, ir yra naudojamas siekiant suprasti ir nustatyti prioritetus vartotojo patirčiai remiantis failo atidarymo operacijos informacija.

Renkami šių laukų duomenys:

- **Data_Success** – Bulio logikos reikšmė, nurodanti, ar pavyko atlikti operaciją.

#### <a name="officedocsuifileoperationsdocsuifileopenmacrequired"></a>Office.DocsUI.FileOperations.DocsUIFileOpenMacRequired

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis įrašomas, kai vykdoma failo atidarymo operacija, ir naudojamas siekiant suprasti ir nustatyti prioritetus vartotojo patirčiai remiantis failo atidarymo operacijos informacija, pvz., vietinėmis kategorijomis „ServiceType“ ir pirmaisiais keturiais plėtinio simboliais.

Renkami šių laukų duomenys:

- **Data_Ext** – failo plėtinys, apribotas iki pirmų keturių ar mažiau plėtinio simbolių.

- **Data_ServiceType** – failo vietos, pvz., „SharePoint“, „OneDrive“, „Local“, „WOPI“ ir t. t., abstraktus kategorizavimas.

#### <a name="officedocsuifileoperationsopendocumentmeasurements"></a>Office.DocsUI.FileOperations.OpenDocumentMeasurements

Šis įvykis gaunamas „Office“ programoms, veikiančioms „iOS“ platformoje. Įvykis įrašo, kada vykdoma failo atidarymo operacija, ir yra naudojamas siekiant suprasti ir nustatyti prioritetus vartotojo patirčiai remiantis failo atidarymo operacijos informacija, o ypač – veikimo informacija.

Renkami šių laukų duomenys:

- **Data_AppDuration** – taikomosios programos apdorojimo trukmė atliekant failo atidarymo operaciją.

- **Data_BootDuration** – failo atidarymo paleidimo proceso trukmė.

- **Data_ClickOrigin** – eilutė, rodanti, saito dalį, kurią vartotojas spustelėjo „iOS Outlook“, kad atidaryti failą „Office“ programoje.

- **Data_ClickTime** – „Unix“ laikotarpis, kai vartotojas spustelėjo saitą „iOS Outlook“, kad atidaryti failą programoje „Office“.

- **Data_ClosePreviouslyOpenedMarkers** – eilutės reikšmė, fiksuojanti laiką tarp tam tikrų funkcijų iškvietimų, pateikiama formatu su funkcijos ID ir trukme.

- **Data_DetachedDuration** – įvykio atsiejimo proceso trukmė. 

- **Data_Doc_AccessMode** – išvardijimas, rodantis failo prieigos režimą, pvz., tik skaityti, skaityti / rašyti.

- **Data_Doc_AsyncOpenKind** – išvardijimas, rodantis, kokio tipo asinchroninis srautas naudojamas failui atidaryti.

- **Data_Doc_ChunkingType** – išvardijimas, rodantis failo segmentavimo algoritmą.

- **Data_Doc_EdpState** – išvardijimas, rodantis įmonės duomenų failo apsaugos būseną.

- **Data_Doc_Ext** – failo plėtinys.

- **Data_Doc_Fqdn** – failo serverio pagrindinio kompiuterio pavadinimas.

- **Data_Doc_FqdnHash** – GUID, kuris unikaliai identifikuoja serverio pagrindinio kompiuterio pavadinimą.

- **Data_Doc_IdentityTelemetryId** – GUID, kuris unikaliai identifikuoja tapatybę, naudojamą failui atidaryti.

- **Data_Doc_InitializationScenario** – išvardijimas, rodantis išsamius failo atidarymo operacijos scenarijaus tipus.

- **Data_Doc_IOFlags** – išvardijimas, rodantis failo atidarymo operacijos įvesties ir išvesties žymes, pvz., ar failas yra talpykloje.

- **Data_Doc_IsCloudCollabEnabled** – ar šiam failui įgalintas bendradarbiavimas debesyje.

- **Data_Doc_IsIncrementalOpen** – ar failas buvo atidarytas naudojant papildantįjį atidarymą.

- **Data_Doc_IsOcsSupported** – ar failas palaiko „Office“ bendradarbiavimo tarnybą.

- **Data_Doc_IsOpeningOfflineCopy** – ar failas atidaromas iš autonominėje talpykloje laikomos kopijos.

- **Data_Doc_IsPrefetched** – ar failas buvo paimtas iš anksto prieš atidarymo operacijos atlikimą.

- **Data_Doc_IsSyncBacked** – ar debesies failas yra lokaliai ir ar sinchronizuojamas su serveriu.

- **Data_Doc_Location** – išvardijimas, rodantis failo vietą, pvz., lokalus arba debesyje.

- **Data_Doc_ReadOnlyReasons** – išvardijimas, rodantis failo priežastį tik skaityti.

- **Data_Doc_ResourceIdHash** – GUID, unikaliai identifikuojantis failo serverio išteklių ID.

- **Data_Doc_RtcType** – išvardijimas, rodantis failo naudojamą realaus laiko kanalo (RTC) tipą.

- **Data_Doc_FqdnHash** – GUID, kuris unikaliai identifikuoja serverio dokumento ID.

- **Data_Doc_ServerProtocol** – išvardijimas, rodantis debesies failo serverio protokolą.

- **Data_Doc_ServerType** – išvardijimas, rodantis debesies failo serverio tipą.

- **Data_Doc_ServerVersion** – išvardijimas, rodantis debesies failo serverio versiją.

- **Data_Doc_SessionId** – sveikasis skaičius, padidėjantis 1 kiekvieną kartą, kai seanso metu atliekama failo atidarymo operacija.

- **Data_Doc_SharePointServiceContext** – eilutė, naudojama susieti kliento ir serverio žurnalus, paprastai tai yra ID tipas.

- **Data_Doc_SizeInBytes** – dokumento dydis baitais.

- **Data_Doc_SpecialChars** – išvardijimas, rodantis URL failo specialųjį simbolį.

- **Data_Doc_UrlHash** – GUID, kuris unikaliai identifikuoja failo URL.

- **Data_Doc_UsedWrsDataOnOpen** – ar failas buvo atidarytas palaipsniui naudojant iš anksto talpykloje saugomus WRS duomenis.

- **Data_Doc_WopiServiceId** – eilutė, rodanti iš kurios tarnybos yra WOPI (žiniatinklio taikomosios programos atviro platformos sąsajos protokolas) failas.

- **Data_HWModel** – eilutės reikšmė, kuri registruoja „iPad“ arba „iPhone“ įrenginio modelį.

- **Data_InclusiveMeasurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, kuri apima papildomų funkcijų iškvietimų trukmę.

- **Data_InitializationReason** – išvardijimas, rodantis kaip failas atidaromas, pvz., iš kurio vartotojo sąsajos elemento arba paleistas kitos taikomosios programos.

- **Data_IsDocumentAlreadyOpen** – ar failas jau atidarytas.

- **Data_IsInterrupted** – ar failo atidarymo operacija buvo nutraukta, kai programa perėjo prie fono.

- **Data_Measurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme ir trukme, neapimančia papildomų funkcijų iškvietimų trukmės.

- **Data_OpenInPlace** – ar failas turi būti kopijuojamas į „Office“ smėlio dėžės talpyklą, kad vartotojas galėtų jį atidaryti.

- **Data_OpenStartTime** – „Unix“ laikotarpis, kai prasidėjo failo atidarymas.

- **Data_PrefetchSourceOptions** – išvardijimas, nurodantis, kaip debesies dokumentų failas padarytas pasiekiamas neprisijungus, pvz., iš vėliausiai naudotų ir rekomenduojamų failų. 

- **Data_SilhouetteDuration** – failo atidarymo generavimo trukmė.

- **Data_SourceApplication** – eilutė, nurodanti šaltinio taikomosios programos grupavimo ID, kai failas atidaromas naudojant kitą taikomąją programą.

- **Data_StopwatchDuration** – trukmė nuo įvykio pradžios iki pabaigos.

- **Data_TimeSplitMeasurements** – eilutės reikšmė, fiksuojanti laiką, sugaištą atliekant tam tikrus funkcijų iškvietimus. Pateikiama formatu: su funkcijos žyme, pradžios laiko žyma ir trukme.

#### <a name="officedocsuifileoperationsopenfilewithreason"></a>Office.DocsUI.FileOperations.OpenFileWithReason 

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis įrašomas, kai vykdoma failo atidarymo operacija, ir naudojamas siekiant suprasti ir nustatyti prioritetus vartotojo patirčiai remiantis failo atidarymo operacijos informacija, pvz., vietinėmis kategorijomis „ServiceType“, bei iš kurios programos vietos vartotojas pateikė failo atidarymo užklausą.

Renkami šių laukų duomenys:

- **Data_IsCandidateDropboxFile** – tai yra Bulio logikos reikšmė, kuri registruojama, jei tikrinant failo kelią, manome, kad jis gali būti iš aplanko, kuris sinchronizuotas saugyklos „DropBox“.

- **Data_IsSignedIn** – ar failo įrašymo metu vartotojas yra prisijungęs.

- **Data_OpenReason** – atviroji priežastis yra skaitinė reikšmė, nurodanti vietą, iš kurios taikomojoje programoje vartotojas atidarė failą.

- **Data_ServiceType** – failo vietos, pvz., „SharePoint“, „OneDrive“, „Local“, „WOPI“ ir t. t., abstraktus skaitinis kategorizavimas, ir aiškus nurodymas, kad tai nėra faktinė failo vieta.

#### <a name="officedocsuifileoperationssavetourl"></a>Office.DocsUI.FileOperations.SaveToURL

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis įrašomas, kai vykdoma operacija „įrašyti kaip“, ir naudojamas siekiant suprasti ir nustatyti prioritetus vartotojo patirčiai remiantis failo operacijos informacija, pvz., vietinėmis kategorijomis ir pirmaisiais keturiais plėtinio simboliais.  Operacija „įrašyti kaip“ vykdoma, kai vartotojas sukuria naują failą ir įrašo jį pirmą kartą arba išsaugo esamo failo kopiją naujoje vietoje.

Renkami šių laukų duomenys:

- **Data_FileExtension** – pirmi keturi naujo failo plėtinio simboliai.

- **Data_IsNewFileCreation** – nurodo, ar įrašymo operacija skirta naujam failui, ar esamo failo kopijai.

- **Data_IsSignedIn** – ar failo įrašymo metu vartotojas yra prisijungęs.

- **Data_SaveErrorCode** – skaitinė reikšmė, nustatoma įvykus klaidai, kad padėtų nustatyti klaidos tipą.

- **Data_SaveErrorDomain** – nurodo SaveErrorCode domeną, kaip apibrėžta „Apple“ SaveErrorDomains – „yra pasirenkamos eilutės, skirtos kodų grupėms atskirti“.

- **Data_SaveLocation** – failo vietos, pvz., „SharePoint“, „OneDrive“, „Local“, „WOPI“ ir t. t., abstraktus kategorizavimas, ir aiškus nurodymas, kad tai nėra faktinė failo vieta.

- **Data_SaveOperationType** – skaitinė reikšmė, apibrėžta „Apple“ NSSaveOperationType reikšmių grupėje.


#### <a name="officedocsuisharinguicloudupsellshown"></a>Office.DocsUI.SharingUI.CloudUpsellShown 

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Šis įvykis įrašo, kada vartotojas peržvelgia papildomo debesies srauto pardavimo dokumentą.  Šie duomenys naudojami siekiant geriau suprasti ir nustatyti vartotojo patirčių prioritetus, susijusius su dokumentų perkėlimu į debesį.

Renkami šių laukų duomenys:

- **Data_FileStyle** – skaitinė reikšmė, nurodanti, koks scenarijus buvo naudojamas papildomo pardavimo patirties rodymui, pvz., automatinio įrašymo jungiklio ar bendrinimo mygtuko.

- **Data_FileType** – pirmi keturi esamo failo plėtinio simboliai.

- **Data_InDocStage** – Bulio logika, nurodanti, ar papildomo pardavimo patirtis rodoma iš dokumentų galerijos ar dokumento lango.

- **Data_IsDocumentOpened** – Bulio logika, nurodanti, ar taip pat atidarytas esamas dokumentas, kuriame rodoma papildomo pardavimo patirtis.

- **Data_IsDraft** – Bulio logika, nurodanti, ar esamas failas kada nors buvo įrašytas.

- **Data_IsSheetModal** – Bulio logika, nurodanti, ar papildomo pardavimo patirtis buvo pateikta modališkai.

#### <a name="officedocsuisharinguicloudupsellupload"></a>Office.DocsUI.SharingUI.CloudUpsellUpload 

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Šis įvykis fiksuoja kada vartotojas pasirenka nusiųsti naują ar vietinį failą į debesį ir šios operacijos rezultatą.  Šie duomenys naudojami siekiant geriau suprasti ir nustatyti vartotojo patirčių prioritetus, susijusius su dokumentų perkėlimu į debesį.

Renkami šių laukų duomenys:

- **Data_FileStyle** – skaitinė reikšmė, nurodanti, koks scenarijus buvo naudojamas papildomo pardavimo patirties rodymui, pavyzdžiui, automatinio įrašymo jungiklio ar bendrinimo mygtuko.

- **Data_FileType** – pirmi keturi esamo failo plėtinio simboliai.

- **Data_InDocStage** – Bulio logika, nurodanti, ar papildomo pardavimo patirtis rodoma iš dokumentų galerijos ar dokumento lango.

- **Data_IsDefaultServiceLocation** – Bulio logikos reikšmė, nurodanti, ar pasirinkta dokumento įkėlimo vieta yra numatytoji vieta.

- **Data_IsDocumentOpened** – Bulio logika, nurodanti, ar taip pat atidarytas esamas dokumentas, kuriame rodoma papildomo pardavimo patirtis.

- **Data_IsDraft** – Bulio logika, nurodanti, ar esamas failas kada nors buvo įrašytas.

- **Data_IsSheetModal** – Bulio logika, nurodanti, ar papildomo pardavimo patirtis buvo pateikta modališkai.

- **Data_LocationServiceType** – failo vietos, pvz., „SharePoint“, „OneDrive“, „Local“, „WOPI“ ir t. t., abstraktus kategorizavimas ir aiškus nurodymas, kad tai nėra faktinė failo vieta.

- **Data_UploadAction** – užprogramuota eilutė, nurodanti, ar nusiuntimas buvo perkėlimo, ar kopijavimo operacija.

- **Data_UploadResult** – užprogramuota eilutė, nurodanti mėginimo nusiųsti rezultatą, įskaitant (bet tuo neapsiribojant) parametrus „Success“, „UserCancelledUpload“ ir „PreAuthFailed“.

#### <a name="officedocsuisharinguicopylinkoperation"></a>Office.DocsUI.SharingUI.CopyLinkOperation

Šis įvykis renkamas „Office“ programoms, veikiančioms „Apple“ platformose. Šis įvykis įrašo, kada vartotojas pasirenka bendrinti dokumentą sugeneruodamas saitą su debesies dokumentu, ir yra naudojamas norint geriau suprasti ir nustatyti vartotojo patirties prioritetus, atsižvelgiant į dokumentų bendrinimą.

Renkami šių laukų duomenys:

- **Data_ServiceType** – failo vietos, pvz., „SharePoint“, „OneDrive“, „Local“, „WOPI“ ir t. t., abstraktus kategorizavimas ir aiškus nurodymas, kad tai nėra faktinė failo vieta.

- **Data_LinkType** – užprogramuota eilutė, aprašanti kvietimo operacijos rūšį, pvz., „ViewOnly“ ir „ViewAndEdit“.

- **Data_ShareScenario** – užprogramuota eilutė, aprašanti, ar failas buvo bendrintas iš programos vartotojo sąsajos, įskaitant (bet tuo neapsiribojant) „FileMenu“, „OpenTabShareActionMenu“, „RecentTabShareActionMenu“.

#### <a name="officedocsuisharinguidocsuionedriveshare"></a>Office.DocsUI.SharingUI.DocsUIOneDriveShare 

Šis įvykis renkamas „Office“ taikomosioms programoms, veikiančioms „Apple“ platformose. Šis įvykis įrašo, kada vartotojas pasirenka bendrinti debesies dokumentą naudodamas „OneDrive“ bendrinimo patirtį ir yra naudojamas norint geriau suprasti ir nustatyti vartotojo patirties prioritetus, atsižvelgiant į dokumentų bendrinimą.

Renkami šių laukų duomenys:

- **Data_ODSPShareWebviewShareError** – jei bendrinimo patirties metu įvyksta klaida, tai yra skaitinė reikšmė, padedanti nustatyti trikties priežastį.

- **Data_ODSPShareWebviewShareGrantAccessResult** – Bulio logikos reikšmė. Kai yra teisinga, nurodo, kad sėkmingai įvykdyta paprasta bendrinimo operacija.

- **Data_ODSPShareWebviewShareSuccessType** – sėkmingai užbaigus bendrinimo operaciją, tai yra skaitinė reikšmė, naudojama nustatyti atliktos bendrinimo operacijos tipą.

- **Data_WebViewInfoResult** – jei nepavyko įkelti vartotojo sąsajos, tai yra skaitinė reikšmė, padedanti nustatyti trikties priežastį. 

- **Data_WebViewLoadTimeInMs** – skaitinė reikšmė, kuri registruoja laiką, reikalingą įkelti žiniatinklio vartotojo sąsają.

#### <a name="officedocsuisharinguiinvitepeople"></a>Office.DocsUI.SharingUI.InvitePeople 

Šis įvykis renkamas „Office“ programoms, veikiančioms „Apple“ platformose. Šis įvykis įrašo, kada vartotojas pasirenka pakviesti žmones naudotis debesies dokumentu, ir yra naudojamas norint geriau suprasti ir nustatyti vartotojo patirties prioritetus, atsižvelgiant į dokumentų bendrinimą.

Renkami šių laukų duomenys:

- **Data_ServiceType** – failo vietos, pvz., „SharePoint“, „OneDrive“, „Local“, „WOPI“ ir t. t., abstraktus kategorizavimas ir aiškus nurodymas, kad tai nėra faktinė failo vieta.

- **Data_InviteeCount** – bendras kontaktų, pakviestų prisijungti prie dokumento atliekant vieną kvietimo veiksmą, skaičius.

- **Data_LinkType** – užprogramuota eilutė, aprašanti kvietimo operacijos rūšį, pvz., „ViewOnly“ ir „ViewAndEdit“.

- **Data_MessageLength** – bendras išsiųsto kvietimo pranešimo simbolių skaičius.

- **Data_ShareScenario** – užprogramuota eilutė, aprašanti, ar failas buvo bendrintas iš programos vartotojo sąsajos, įskaitant (bet tuo neapsiribojant) „FileMenu“, „OpenTabShareActionMenu“, „RecentTabShareActionMenu“.

#### <a name="officedocsuisharinguisendacopyoperation"></a>Office.DocsUI.SharingUI.SendACopyOperation

Šis įvykis renkamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis įrašo, kada vartotojas pasirenka siųsti dokumento kopiją, ir yra naudojamas norint geriau suprasti ir nustatyti vartotojo patirties prioritetus, atsižvelgiant į dokumentų bendrinimą.

Renkami šių laukų duomenys:

- **Data_IsHomeTabEnabled** – Bulio logikos reikšmė, nurodanti, ar skirtukas Pagrindinis šiuo metu pasiekiamas vartotojui.

- **Data_IsRecommendedEnabled** – Bulio logikos reikšmė, nurodanti, ar patirtis Rekomenduojama šiuo metu pasiekiamas vartotojui.

- **Data_OperationType** – skaitinė reikšmė, nurodanti vykdomos kopijos siuntimo operacijos tipą, pvz., siųsti kopiją el. paštu arba nusiųsti kopiją naudojantis „Apple“ bendrinimo valdymo funkcija.

- **Data_ServiceType** – failo vietos, pvz., „SharePoint“, „OneDrive“, „Local“, „WOPI“ ir t. t., abstraktus kategorizavimas ir aiškus nurodymas, kad tai nėra faktinė failo vieta.

- **Data_ShareFileType** – užprogramuotas eilutės aprašas, nurodantis bendrinamo objekto tipą, įskaitant (bet tuo neapsiribojant) „Dokumentas“, „PDF“, „Paveikslėlis“.

- **Data_ShareScenario** – užprogramuota eilutė, aprašanti, ar failas buvo bendrintas iš programos vartotojo sąsajos, įskaitant (bet tuo neapsiribojant) „FileMenu“, „OpenTabShareActionMenu“, „RecentTabShareActionMenu“.

- **Data_SharingService** – Bulio logika, nurodanti, ar failas buvo sukurtas, kai vartotojas ieškojo šablono.

#### <a name="officedocsuisharinguiupsellshare"></a>Office.DocsUI.SharingUI.UpsellShare 

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Šis įvykis įrašo, kai vartotojas peržvelgia papildomo debesies srauto pardavimo dokumentą, kai bando bendrinti dokumentą.  Šie duomenys naudojami, kad geriau suprasti ir nustatyti vartotojo patirčių prioritetus, susijusius su dokumentų perkėlimu į debesį.

Renkami šių laukų duomenys:

- **Data_FileOperationResult** – skaitinė reikšmė, nurodanti, ar pavyko atlikti operaciją.

- **Data_HostedFromDocStage** – Bulio logika, nurodanti, ar vartotojas peržiūri debesies srauto reklamą naudodami DocStage funkcijas arba iš atidaryto dokumento.

- **Data_isLocalCopyOn** – Bulio logika, nurodanti, ar naudoti pasirinko saugoti dokumento vietinę kopiją, kuri buvo nusiųsta į debesį arba perkelti esamą dokumentą į debesį.

- **Data_NewFileType** – naujos failo vietos, pvz., „SharePoint“, „OneDrive“, „Local“, „WOPI“ ir t. t., abstraktus kategorizavimas ir aiškus nurodymas, kad tai nėra faktinė failo vieta.

- **Data_OriginalFileType** – failo vietos, pvz., „SharePoint“, „OneDrive“, „Local“, „WOPI“ ir t. t., abstraktus kategorizavimas ir aiškus nurodymas, kad tai nėra faktinė failo vieta.

- **Data_UploadButtonPressed** – Bulio logika, nurodanti, ar vartotojas pasirinko įkelti dabartinį dokumentą į vietą debesyje.

- **Data_UploadError** – skaitinė reikšmė, nurodanti klaidos tipą, jei įkėlimo operacijos atlikti nepavyksta.

- **Data_UpsellAppearsFromDelegate** – Bulio logikos reikšmė, nurodanti, ar rodinys buvo rodomas bendrinamame meniu.

#### <a name="officeextensibilitycatalogexchangeprocessentitlement"></a>Office.Extensibility.Catalog.ExchangeProcessEntitlement

Atskirų teisių suteikimo apdorojimo ir „Office 365“ nuomotojo administratoriaus priskirto papildinio duomenys.

Naudoti kliento sėkmingų veiksmų diagramos sudaryme (prašomų komandos vadovų) ir klientų problemų analizėje.

Renkami šių laukų duomenys:

  - **AppVersion** – valdančiosios programos papildinio versija

  - **SolutionId –** GUID, nurodantis unikalų papildinį

  - **TelemetryId** – GUID, nurodantis unikalų vartotoją

#### <a name="officeextensibilitycatalogexchangeprocessmanifest"></a>Office.Extensibility.Catalog.ExchangeProcessManifest

Duomenys apie „Office 365“ nuomotojo administratoriaus priskirto papildinio atskiros deklaracijos tvarkymą. Naudojamas klientų problemoms analizuoti ir klientų sėkmės diagramoms kurti.
 
Renkami šių laukų duomenys:

- **AppVersion** – taikomosios programos versija

- **IsAllReturnedManifestsParsed** – Bulio logika, nurodanti, kad mes išanalizavome visas grąžintas deklaracijas

- **IsAppCommand** – Bulio logika, nurodanti, ar tai taikomosios programos komandų programa 

- **ReturnedManifestsParsed** – išanalizuotų deklaracijų skaičius

- **SolutionId** – sprendimo ID

- **TelemetryId** – telemetrijos ID pagal pasirašytą tapatybę

#### <a name="officeextensibilityodpappcommandsribbonclick"></a>Office.Extensibility.ODPAppCommandsRibbonClick

Renka, ar tinkinto papildinio valdiklio spustelėjimas buvo sėkmingas, ar ne. Naudojamas norint aptikti vartotojo sąveikos su papildinių valdikliais problemas.
 
Renkami šių laukų duomenys:

- **CommandActionType** – papildinio komandos tipas

- **CommandLabel** – spustelėta komandos žymė

- **SolutionId** – sprendimo ID

#### <a name="officefeedeventsinitializing"></a>Office.Feed.Events.Initializing

Šio įvykio duomenys renkami, kai pradedamas informacijos santraukos inicijavimas. Šis įvykis naudojamas norint nurodyti, kad informacijos santrauka pradedama, ir diagnozuoti patikimumo triktis paleidžiant informacijos santrauką.

- **AppInfo.Language** – programos kalba IETF kalbos žymės formatu.

- **AppInfo.Name** – naudojamo komponento pavadinimas („Office“ informacijos santrauka).

- **AppInfo.Version** – programos versija.

- **clientCorrelationId** – programos seanso visuotinis unikalusis identifikatorius.

- **clientType** – programa, kurioje veikia komponentas.

- **DeviceInfo.Make** – įrenginio gamintojas arba įrenginio OĮG pavadinimas.

- **DeviceInfo.NetworkProvider** – tinklas ar mobiliojo ryšio operatorius, pvz., „AT&T“.

- **DeviceInfo.NetworkType** – naudojamo įrenginio tinklo ryšio tipas, pvz., laidinis, „WiFi“ arba „WWAN“ (duomenys / mobilusis tinklas).

- **DeviceInfo.OsName** – įrenginio OS pavadinimas.

- **DeviceInfo.SDKUid** – unikaliai identifikuoja įrenginį iš telemetrijos SDK perspektyvos.

- **eventId** – įvykio pavadinimo identifikatorius. 

- **EventInfo.SdkVersion** – telemetrijos SDK, kurį klientas naudoja įvykiui generuoti, versija.

- **eventpriority** – įvykio siuntimo prioriteto išvardijimo reikšmė.

- **feature** – naudojama grupuoti įvairius tos pačios funkcijos įvykius.

- **hostAppRing** – vartotojų, kuriems buvo paskirstyta programa, ratas.

- **properties** – pateikiami kiekvieno įvykio surinkti papildomi metaduomenys.
        
    - **ClientTimeStamp** – laiko žyma, kada įvykis buvo užregistruotas kliente.

- **publicEventName** – viešasis įvykio pavadinimas.  

- **region** – informacijos santraukų tarnybos, prie kurios yra prisijungęs vartotojas, geografinis regionas. 

- **tenantAadObjectId** – visuotinis unikalusis vartotojo įmonės nuomotojo identifikatorius.

- **type** – užregistruoto įvykio tipas, pvz., sekimas, klaida, įvykis, QoS.

- **userAadObjectId** – įmonės „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius.

- **UserInfo.Id** – įmonės „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius.

- **UserInfo.IdType** – nurodo vartotojo ID tipą. 

- **UserInfo.Language** – vartotojo kalba IETF kalbos žymės formatu.

- **UserInfo.MsaId** – vartotojo „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius.

- **UserInfo.OMSTenantId** – nuomotojas, su kuriuo yra susieta vartotojo prenumerata. Leidžia mums klasifikuoti problemas ir nustatyti, ar problema yra plačiai paplitusi, ar izoliuota atskirų nuomotojų grupėje.

- **UserInfo.TimeZone** – vartotojo laiko juosta pagal UTC.

- **userPuid** – vartotojo „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius.

- **version** – informacijos santraukos kliento versija.

#### <a name="officefeedeventsofficefeeddidappear"></a>Office.Feed.Events.OfficeFeedDidAppear

Šio įvykio duomenys renkami, kai informacijos santrauka rodoma vartotojui. Įvykis naudojamas norint patvirtinti, kad informacijos santraukos inicijavimo veiksmas buvo atliktas, ir diagnozuoti patikimumo triktis paleidžiant informacijos santrauką.

- **AppInfo.Language** – programos kalba IETF kalbos žymės formatu.

- **AppInfo.Name** – naudojamo komponento pavadinimas („Office“ informacijos santrauka).

- **AppInfo.Version** – programos versija.

- **bridgeWaitingTime** – metrika, naudojama diagnozuoti informacijos santraukos generavimo našumui.

- **clientCorrelationId** – programos seanso visuotinis unikalusis identifikatorius.

- **clientScenario** – skirtingų sklaidos kanalų variantų scenarijus.

- **ClientTimeStamp** – laiko žyma, kada įvykis buvo užregistruotas kliente.

- **clientType** – programa, kurioje veikia komponentas.

- **DeviceInfo.Make** – įrenginio gamintojas arba įrenginio OĮG pavadinimas.

- **DeviceInfo.NetworkProvider** – tinklas ar mobiliojo ryšio operatorius, pvz., „AT&T“.

- **DeviceInfo.NetworkType** – naudojamo įrenginio tinklo ryšio tipas, pvz., laidinis, „WiFi“ arba „WWAN“ (duomenys / mobilusis tinklas).

- **DeviceInfo.OsName** – įrenginio OS pavadinimas.

- **DeviceInfo.SDKUid** – unikaliai identifikuoja įrenginį iš telemetrijos SDK perspektyvos.

- **eventId** – įvykio pavadinimo identifikatorius.

- **EventInfo.SdkVersion** – telemetrijos SDK, kurį klientas naudoja įvykiui generuoti, versija.

- **eventpriority** – įvykio siuntimo prioriteto išvardijimo reikšmė.

- **feature** – naudojama grupuoti įvairius tos pačios funkcijos įvykius.

- **hostAppRing** – vartotojų, kuriems buvo paskirstyta programa, ratas.

- **properties** – pateikiami kiekvieno įvykio surinkti papildomi metaduomenys. *[Šis laukas buvo pašalintas iš dabartinių „Office“ versijų, bet gali būti rodomas senesnėse versijose.]*

- **publicEventName** – viešasis įvykio pavadinimas.  

- **region** – informacijos santraukų tarnybos, prie kurios yra prisijungęs vartotojas, geografinis regionas. 

- **renderTime** – metrika, naudojama diagnozuoti informacijos santraukos generavimo našumui.

- **tenantAadObjectId** – visuotinis unikalusis vartotojo įmonės nuomotojo identifikatorius.

- **type** – užregistruoto įvykio tipas, pvz., sekimas, klaida, įvykis, QoS.

- **userAadObjectId** – įmonės „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius.

- **UserInfo.Id** – įmonės „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius.

- **UserInfo.IdType** – nurodo vartotojo ID tipą. 

- **UserInfo.Language** – vartotojo kalba IETF kalbos žymės formatu.

- **UserInfo.MsaId** – vartotojo „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius.

- **UserInfo.OMSTenantId** – nuomotojas, su kuriuo yra susieta vartotojo prenumerata. Leidžia mums klasifikuoti problemas ir nustatyti, ar problema yra plačiai paplitusi, ar izoliuota atskirų nuomotojų grupėje.

- **UserInfo.TimeZone** – vartotojo laiko juosta pagal UTC.

- **userPuid** – vartotojo „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius.

- **version** – informacijos santraukos kliento versija.


#### <a name="officefeedbacksurveyfloodgateclientsurveytracked"></a>Office.Feedback.Survey.FloodgateClient.SurveyTracked

Seka, kada įrenginys, atitinkantis reikalavimus apklausai, paleidžia programą. Naudojama įvertinti apklausos vartotojo pasirinkimo proceso būklę bei užtikrinti, kad signalas, naudojamas analizuoti klientų problemas ir būklę, veikia tinkamai.

Renkami šių laukų duomenys:

- **ExpirationTimeUTC** – data / laikas, kad pasibaigs apklausos galiojimas

- **SurveyName** – rodomos apklausos pavadinimas

- **SurveyId** – unikalus kampanijos egzempliorius

- **UniqueId** – ID, nustatyti atskirai telemtrijos daliai

#### <a name="officefeedbacksurveyfloodgateclienttriggermet"></a>Office.Feedback.Survey.FloodgateClient.TriggerMet

Seka, kada įrenginys atitiko reikalavimus, kad jam būtų rodoma apklausa. Naudojama įvertinti apklausos suaktyvinimo proceso būklę bei užtikrinti, kad signalas, naudojamas analizuoti klientų problemas ir būklę, veikia tinkamai.

Renkami šių laukų duomenys:

- **ExpirationTimeUTC** – data / laikas, kad pasibaigs apklausos galiojimas

- **SurveyName** – rodomos apklausos pavadinimas

- **SurveyId** – unikalus kampanijos egzempliorius

- **UniqueId** – ID, nustatyti atskirai telemtrijos daliai

#### <a name="officefeedbacksurveyfloodgateclientuserselected"></a>Office.Feedback.Survey.FloodgateClient.UserSelected

Seka, kada įrenginys pasirenkamas apklausai. Naudojama įvertinti apklausos vartotojo pasirinkimo proceso būklei bei užtikrinti, kad signalas, naudojamas analizuoti klientų problemoms ir būklei, veikia tinkamai.

Renkami šių laukų duomenys:

- **ExpirationTimeUTC** – data / laikas, kad pasibaigs apklausos galiojimas

- **SurveyName** – rodomos apklausos pavadinimas

- **SurveyId** – unikalus kampanijos egzempliorius

- **UniqueId** – ID, nustatyti atskirai telemtrijos daliai

#### <a name="officefeedbacksurveyuiandroid"></a>Office.Feedback.Survey.UI.Android

„Android“ įrenginyje seka, kada vartotojas įrenginyje sąveikauja su apklausos paraginimu ir apklausos vartotojo sąsaja. Naudojama įvertinti visapusę apklausos funkcijos būklę bei užtikrinti, kad signalas, naudojamas analizuoti klientų problemas ir būklę, veikia tinkamai.

Renkami šių laukų duomenys:

- **ExpirationTimeUTC** – data / laikas, kad pasibaigs apklausos galiojimas

- **SurveyName** – rodomos apklausos pavadinimas

- **SurveyId** – unikalus kampanijos egzempliorius

- **UniqueId** – ID, nustatyti atskirai telemtrijos daliai

#### <a name="officefeedbacksurveyuiios"></a>Office.Feedback.Survey.UI.IOS

„iOS“ įrenginyje seka, kada vartotojas įrenginyje sąveikauja su apklausos paraginimu ir apklausos vartotojo sąsaja. Naudojama įvertinti visapusę apklausos funkcijos būklę bei užtikrinti, kad signalas, naudojamas analizuoti klientų problemas ir būklę, veikia tinkamai.

Renkami šių laukų duomenys:

- **ExpirationTimeUTC** – data / laikas, kad pasibaigs apklausos galiojimas

- **SurveyName** – rodomos apklausos pavadinimas

- **SurveyId** – unikalus kampanijos egzempliorius

- **UniqueId** – ID, nustatyti atskirai telemtrijos daliai

#### <a name="officefeedbacksurveyuimac"></a>Office.Feedback.Survey.UI.Mac

„Mac“ įrenginyje seka, kada vartotojas įrenginyje sąveikauja su apklausos paraginimu ir apklausos vartotojo sąsaja. Naudojama įvertinti visapusę apklausos funkcijos būklę bei užtikrinti, kad signalas, naudojamas analizuoti klientų problemas ir būklę, veikia tinkamai.

Renkami šių laukų duomenys:

- **ExpirationTimeUTC** – data / laikas, kad pasibaigs apklausos galiojimas

- **SurveyName** – rodomos apklausos pavadinimas

- **SurveyId** – unikalus kampanijos egzempliorius

- **UniqueId** – ID, nustatyti atskirai telemtrijos daliai

#### <a name="officefeedbacksurveyuiwin32"></a>Office.Feedback.Survey.UI.Win32

„Win32“ įrenginyje seka, kada vartotojas įrenginyje sąveikauja su apklausos paraginimu ir apklausos vartotojo sąsaja. Naudojama įvertinti visapusę apklausos funkcijos būklę bei užtikrinti, kad signalas, naudojamas analizuoti klientų problemas ir būklę, veikia tinkamai.

Renkami šių laukų duomenys:

- **ExpirationTimeUTC** – data / laikas, kad pasibaigs apklausos galiojimas

- **SurveyName** – rodomos apklausos pavadinimas

- **SurveyId** – unikalus kampanijos egzempliorius

- **UniqueId** – ID, nustatyti atskirai telemtrijos daliai

#### <a name="officefeedbacksurveyuiwin32toast"></a>Office.Feedback.Survey.UI.Win32.Toast

Seka, kada rodomas apklausos raginimas. Naudojama norint įvertinti apklausos paraginimo proceso būklę bei užtikrinti, kad signalas, naudojamas analizuoti klientų problemoms ir būklei, veikia tinkamai.

Renkami šių laukų duomenys:

- **ExpirationTimeUTC** – data / laikas, kad pasibaigs apklausos galiojimas

- **SurveyName** – rodomos apklausos pavadinimas

- **SurveyId** – unikalus kampanijos egzempliorius

- **UniqueId** – ID, nustatyti atskirai telemtrijos daliai

#### <a name="officefileiocsiccachedfilecsiloadfilebasic"></a>Office.FileIO.CSI.CCachedFileCsiLoadFileBasic

Leidžia mums žinoti, ar failas iš FIO sluoksnio atidarytas sėkmingai. Naudojama funkcijos sveikatai ir stebėjimui.

Renkami šių laukų duomenys:

  - **Activity.Group –** žymė, leidžianti nustatyti stebimų įvykių rinkinį, grupuojamą sėkmingam atlikimui valdyti

  - **Activity.IsHVA –** žyma, nurodanti, kad įvykis yra kritinis vartotojų sėkmingiems veiksmams užtikrinti

  - **Data.AsyncOpen –** žyma, nurodanti, kad atidarymo metu buvo turinys, gautas po pagrindinės dalies atidarymo

  - **Data.CacheFileId –** prisijungia prie „Office“ dokumentų talpyklos telemetrijos, kad atliktų vartotojo patiriamų talpyklos problemų analizę
 
  - **Data.CFREnabled** – nurodo, kad seansui įgalinta funkcija CacheFileRuntime.

  - **Data.CFRFailure** – nurodo, kad įvyko funkcijos CacheFileRuntime klaida.
  
  - **Data.CoauthStatus –** informuoja apie dokumento bendradarbiavimo būseną atidarymo metu

  - **Data.CountOfMultiRoundTripsDownload –** kelionių į serverį ir atgal skaičius, naudotas veikimo triktims ir tinklo problemoms šalinti

  - **Data.CountOfMultiRoundTripsUpload –** kelionių į serverį ir atgal skaičius, naudotas našumo triktims ir tinklo problemoms šalinti

  - **Data.DialogId –** nustato, ar vartotojo sąsajos dialogo langas buvo rodomas atidarymo metu, nurodantis, kad įspėjimo pranešimas buvo rodomas vartotojui

  - **Data.DidFallbackToDAV –** nustato, ar dokumentas buvo atidarytas naudojant senesnį failų perdavimo protokolą

  - **Data.Doc.AccessMode –** dokumentas yra skirtas tik skaityti / redaguoti

  - **Data.Doc.AssistedReadingReasons –** nustato, ar dokumentas turi elektroninių duomenų apsaugą

  - **Data.Doc.AsyncOpenKind** – nurodo, ar debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

  - **Data.Doc.ChunkingType –** vienetai, naudojami nuosekliam dokumento atidarymui

  - **Data.Doc.EdpState –** dokumentui taikomas elektroninių duomenų apsaugos parametras

  - **Data.Doc.Ext –** dokumento plėtinys (docx / xlsb / pptx ir kt.)

  - **Data.Doc.Extension –** nebenaudojamas

  - **Data.Doc.FileFormat –** failo formato protokolo versija

  - **Data.Doc.Fqdn –** „OneDrive“ arba „SharePoint“ interneto domeno vardas

  - **Data.Doc.FqdnHash –** kliento identifikuojamo domeno vardo vienpusė maiša

  - **Data.Doc.IdentityTelemetryId –** vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša

  - **Data.Doc.IdentityUniqueId –** nebenaudojamas

  - **Data.Doc.InitializationScenario –** įrašo kaip dokumentas buvo atidarytas

  - **Data.Doc.IOFlags –** informuoja apie į talpyklą įtrauktas žymes, naudotas nustatyti užklausos parinktis

  - **Data.Doc.IrmRights –** veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kurie buvo taikyti dokumentui / vartotojui

  - **Data.Doc.IsCloudCollabEnabled –** žymė, nurodanti, kad tarnyba bendradarbiavimą debesyje palaiko

  - **Data.Doc.IsIncrementalOpen –** žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

  - **Data.Doc.IsOcsSupported –** žymė nurodo, jog dokumentą bendradarbiavimo tarnyba palaiko

  - **Data.Doc.IsOpeningOfflineCopy –** žymė, nurodanti, kad autonominė dokumento kopija atidaryta

  - **Data.Doc.IsSyncBacked –** žymė, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

  - **Data.Doc.Location –** nurodo tarnybą, pateikusią dokumentą („OneDrive“, „File Server“, „SharePoint“ ir kt.)

  - **Data.Doc.LocationDetails –** nurodo vietoje saugomo dokumento žinomą aplanką

  - **Data.Doc.NumberCoAuthors –** skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

  - **Data.Doc.PasswordFlags –** nurodo, ar nustatytas skaitymo arba skaitymo / rašymo slaptažodžio žymių rinkinys

  - **Data.Doc.ReadOnlyReasons –** dokumento atidarymo tik kaip skaitomo priežastys

  - **Data.Doc.ResourceIdHash –** anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data.Doc.ServerDocId –** nekintamų anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data.Doc.ServerProtocol –** protokolo versija, naudojama norint susisiekti su tarnyba

  - **Data.Doc.ServerType –** tarnybą siūlančio serverio tipas („SharePoint“, „OneDrive“, WOPI ir kt.)

  - **Data.Doc.ServerVersion –** serverio versija, siūlanti tarnybą

  - **Data.Doc.SessionId –** nustato konkretų viso seanso dokumentų redagavimo seansą

  - **Data.Doc.SharePointServiceContext –** „SharePoint Online“ užklausų diagnostinė informacija

  - **Data.Doc.SizeInBytes –** dokumento dydžio indikatorius

  - **Data.Doc.SpecialChars –** dokumento URL arba kelio specialiųjų simbolių indikatorius

  - **Data.Doc.StorageProviderId –** nebenaudojamas

  - **Data.Doc.StreamAvailability –** indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas arba išjungtas

  - **Data.Doc.SyncBackedType –** dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba)

  - **Data.Doc.UrlHash –** vienpusė maiša, skirta „naïve“ dokumento identifikatoriui

  - **Data.Doc.UsedWrsDataOnOpen –** diagnostikos indikatorius, skirtas nuosekliam dokumento atidarymui

  - **Data.Doc.WopiServiceId –** apima unikalų WOPI tarnybos teikėjo identifikatorių

  - **Data.DocumentLoadEndpoint –** nebenaudojamas / nereikalingas dublikatas (Data.Doc.Location ir Data.Doc.IsSyncbacked)

  - **Data.DocumentSizeInBytes –** nebenaudojamas / nereikalingas, pakeistas į Data.Doc.SizeInBytes

  - **Data.DocumentSizeOnDisk –** nebenaudojamas

  - **Data.DoesBaseHaveContentOnOpen –** pakeitimų sekimo diagnostika, užtikrinanti, kad turėtume naujausią bendrinamo failo versiją

  - **Data.DoesWorkingBranchHaveExcludedDataOnOpen –** pakeitimų sekimo diagnostika, užtikrinanti, kad turėtume naujausią bendrinamo failo versiją

  - **Data.DownloadFragmentSize –** duomenų, siųstų papildomoje užklausoje tinklo problemų nustatymui, dydis

  - **Data.DsmcStartedTooEarly –** nurodo klaidą, atsirandančią paleidžiant bendradarbiavimo redaguojant seansą

  - **Data.EditorsCount –** kitų dokumentą redaguojančių bendradarbių skaičius

  - **Data.ExcludedDataThresholdInBytes –** failo dydis, reikalingas asinchroniniam atidarymui

  - **Data.FileIOResult.Code –** protokolo sluoksnio paskutinio atidarymo grąžinto kodo talpykla

  - **Data.FileIOResult.Success –** protokolo sluoksnio paskutinio atidarymo sėkmingo atlikimo indikatoriaus talpykla

  - **Data.FileIOResult.Tag –** protokolo sluoksnio paskutinio atidarymo klaidos žymos talpykla

  - **Data.FileIOResult.Type –** protokolo sluoksnio paskutinio atidarymo klaidos tipo talpykla

  - **Data.FqdnHash –** nebenaudojamas, pakeistas į Data\_Doc\_FqdnHash

  - **Data.FullIError –** protokolo sluoksnio visų atidarymo klaidų kodų talpykla

  - **Data.FullyQualifiedDomainName –** nebenaudojamas, pakeistas į Data\_Doc\_Fqdn

  - **Data.Input.FileOpenState –** taikomosios programos (skaityti / skaityti ir rašyti, ir kt.) užklausta būsena

  - **Data.Input.OpenAsync –** taikomosios programos užklaustas asinchroninis atidarymas

  - **Data.Input.OpenOfflineCopy –** taikomosios programos užklaustas atidarymas iš autonominės kopijos

  - **Data.IOFlags –** nebenaudojamas

  - **Data.IsBaseBranchEmptyOnOpen –** pakeitimų sekimo diagnostika, užtikrinanti, kad turėtume naujausią bendrinamo failo versiją

  - **Data.IsCachedHistoricalVersion –** talpykloje yra senesnė dokumento versija

  - **Data.IsDocEnterpriseProtected –** dokumentas buvo apsaugotas naudojant šifravimą (elektroninę dokumento apsaugą / EDP)

  - **Data.IsDocInODC –** dokumentas buvo atidarytas anksčiau ir jau yra talpykloje

  - **Data.IsMapUnMapCase –** dalis talpyklos failo būsenos

  - **Data.IsMapUnMapCase.End –** dalis talpyklos failo būsenos

  - **Data.IsOfficeHydrationInProgress –** „Windows“ atkūrė dokumentą iš autonominės saugyklos 

  - **Data.isOfficeHydrationRequired –** dokumento šiuo metu yra autonominėje talpykloje

  - **Data.isOpenFromCollab –** naujausia dokumento kopija buvo gauta iš bendrinamos bendradarbiavimo tarnybos

  - **Data.isPendingNameExist –** vykdomas dokumento pervardijimas

  - **Data.IsStubFile –** dokumentas dar neįrašytas į debesies paslaugą

  - **Data.IsSyncBackedStateDifferentThanOnLastOpen –** pasikeitė dokumento būsena, pakeitimai galėjo būti gauti, kai dokumentas nebuvo atidarytas

  - **Data.isTaskCanceledAfterOpenComplete –** nebenaudojamas

  - **Data.IsWorkingBranchAvailableOnOpen –** pakeitimų sekimo diagnostika, užtikrinanti, kad turėtume naujausią bendrinamo failo versiją

  - **Data.LicenseStatus** – diagnostikos produkto licencijos būsena, naudojama patvirtinti, kad vartotojo licencijos tipui yra įgalintos atitinkamos produkto funkcijos 

  - **Data.LicenseType –** nurodo licencijos būseną (nemokama / mokama / bandomoji ir kt.)

  - **Data.Location –** nurodo medijos saugyklos tipą / vietą (USB, debesis ir kt.)

  - **Data.LockRequestDocMode –** nurodo, ar dokumentas yra pasiekiamas kitiems vartotojams

  - **Data.MyDeferredValue –** nebenaudojamas

  - **Data.Network.BytesReceived –** nebenaudojamas

  - **Data.Network.BytesSent –** nebenaudojamas

  - **Data.Network.ConnectionsCreated –** nebenaudojamas

  - **Data.Network.ConnectionsEnded –** nebenaudojamas

  - **Data.OcsDisableReasons –** priežastis, dėl kurios bendrinama bendradarbiavimo tarnyba buvo nepasiekiama dokumentui

  - **Data.OcsHostOnOpen –** žyma nurodo, jog valdiklis persijungs į bendrinamą bendradarbiavimo tarnybą atidarymo metu

  - **Data.OpeningOfflineCopy –** žymė, nurodanti, kad vietinė dokumento kopija bus atidaryta

  - **Data.Partition –** nebenaudojamas

  - **Data.RequestTime –** nebenaudojamas

  - **Data.ResourceIdHash –** nebenaudojamas

  - **Data.ResumedIncrementalOpen –** nebenaudojamas

  - **Data.RTCEnabled –** greitų pakeitimų paskirstymo protokolas paleistas

  - **Data.SaveOnOpen –** neįrašyti pakeitimai vietiniame dokumente buvo įrašyti į tarnybą atidarymo metu

  - **Data.ServerProtocol –** nebenaudojamas, pakeistas į Data\_Doc\_ServerProtocol

  - **Data.ServerType –** nebenaudojamas, pakeistas į Data\_Doc\_ServerType

  - **Data.ServerVersion –** nebenaudojamas, pakeistas į Data\_Doc\_ServerVersion

  - **Data.ServiceId –** nebenaudojamas, pakeistas į Data\_Doc\_WopiServiceId

  - **Data.SessionId –** nebenaudojamas

  - **Data.ShouldSwitchToServerOnly –** vietinė dokumento kopija negali būti naudojama; turi būti naudojama serverio versija

  - **Data.SpecialChars –** nebenaudojamas

  - **Data.StopwatchDuration –** nebenaudojamas

  - **Data.SyncBackedFileTelemetrySessionId –** nebenaudojamas

  - **Data.SyncElapsedTime –** nebenaudojamas

  - **Data.SyncRequestId –** nebenaudojamas

  - **Data.TestProperty –** nebenaudojamas

  - **Data.TransitionToHostOnOpen –** žymė, nurodanti, kad seanso metu prisijungs prie tarnybos išteklių nuomos dokumento

  - **Data.TransitionToHostOnOpenResult –** perėjimo prie pagrindinio kompiuterio tarnybos būsena

  - **Data.UseCachedNetworkConnection –** žymė, nurodanti, ar ryšys buvo naudojamas pakartotinai, ar buvo sukurtas naujas ryšys

  - **Data.UseClientIdAsSchemaLockId –** žymė, kontroliuojanti kaip dokumentai yra užrakinti tarnyboje

  - **Data.VersionType** – nurodo dabartinės operacinės sistemos versijos tipą.

  - **Data.WopiServiceId –** nebenaudojamas, pakeistas į Data\_Doc\_WopiServiceId

#### <a name="officefileiocsiccachedfilecsisavefilebasic"></a>Office.FileIO.CSI.CCachedFileCsiSaveFileBasic

Šis įvykis leidžia mums žinoti, ar failas iš FIO sluoksnio įrašytas sėkmingai. Naudojama funkcijos sveikatai užtikrinti ir stebėti.

Renkami šių laukų duomenys:

  - **Activity.Group –** žymė, leidžianti nustatyti stebimų įvykių rinkinį, grupuojamą sėkmingam atlikimui valdyti

  - **Activity.IsHVA –** žyma, nurodanti, kad įvykis yra kritinis vartotojų sėkmingiems veiksmams užtikrinti

  - **Data.AsyncOpen –** žyma, nurodanti, kad dokumentas buvo atidarytas su turiniu, gautu po pagrindinės dalies atidarymo

  - **Data.BaseDownloadTriggered –** keičia sekimo diagnostiką, nurodančią, kad buvo užklausta pagrindinė dokumento versija

  - **Data.BlockAutoUploadReasons –** užblokuotos nusiuntimo būsenos priežasčių kodai (pvz. automatinis įrašymas išjungtas, dokumentas perkeliamas)

  - **Data.BlockUploadDueToFailedSaveAsOverExisting –** nusiuntimas užblokuotas, nes kartojant jis nepavyks

  - **Data.CacheFileId –** prisijungia prie „Office“ dokumentų talpyklos telemetrijos, kad atliktų vartotojo patiriamų talpyklos problemų analizę

  - **Data.ChartType –** nebenaudojamas

  - **Data.CoAuthStatus –** informuoja apie dokumento bendradarbiavimo būseną įrašant

  - **Data.CoauthUpdatesContext –** pranešamas kontekstas (suliejimas / laipsniškas atidarymas)

  - **Data.CountOfMultiRoundTripsDownload –** kelionių į serverį ir atgal skaičius, naudotas veikimo triktims ir tinklo problemoms šalinti

  - **Data.CountOfMultiRoundTripsUpload –** kelionių į serverį ir atgal skaičius, naudotas našumo triktims ir tinklo problemoms šalinti
  
  - **Data.CFREnabled** – nurodo, kad seansui įgalinta funkcija CacheFileRuntime.

  - **Data.CFRFailure** – nurodo, kad įvyko funkcijos CacheFileRuntime klaida.

  - **Data.DialogChoice –** įrašo pasirinkimą bet kuriuose klaidų dialogų languose

  - **Data.DialogId –** įrašo visus klaidų dialogų DialogId, rodomus įrašymo metu

  - **Data.Dmc.IsOcsSupported –** nebenaudojamas

  - **Data.Doc.AccessMode –** dokumentas yra skirtas tik skaityti

  - **Data.Doc.AssistedReadingReasons –** nustato, ar dokumentas turi elektroninių duomenų apsaugą

  - **Data.Doc.AsyncOpenKind** – nurodo, ar debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

  - **Data.Doc.ChunkingType –** vienetai, naudojami nuosekliam dokumento atidarymui

  - **Data.Doc.EdpState –** dokumentui taikomas elektroninių duomenų apsaugos parametras

  - **Data.Doc.Ext –** dokumento plėtinys (docx / xlsm / pptx ir kt.)

  - **Data.Doc.Extension –** nebenaudojamas

  - **Data.Doc.FileFormat –** failo formato protokolo versija

  - **Data.Doc.Fqdn –** „OneDrive“ arba „SharePoint“ interneto domeno vardas

  - **Data.Doc.FqdnHash –** kliento identifikuojamo domeno vardo vienpusė maiša

  - **Data.Doc.FqdnHasi –** nebenaudojamas

  - **Data.Doc.IdentityTelemetryId –** vartotojo tapatybės, naudojamos įrašymui, vienpusė maiša

  - **Data.Doc.IdentityUniqueId –** nebenaudojamas

  - **Data.Doc.IKFlags –** nebenaudojamas

  - **Data.Doc.InitializationScenario –** įrašo kaip dokumentas buvo atidarytas

  - **Data.Doc.IOFlags –** informuoja apie į talpyklą įtrauktas žymes, naudotas nustatyti užklausos parinktis

  - **Data.Doc.IrmRights –** veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kurie buvo taikyti dokumentui / vartotojui

  - **Data.Doc.IsCloudCollabEnabled –** žymė, nurodanti, kad taikomoji programa bendradarbiavimą debesyje palaiko

  - **Data.Doc.IsIncrementalOpen –** žymė, nurodanti, kad dokumentas buvo atidarytas palaipsniui

  - **Data.Doc.IsOcsSupported –** žymė, nurodanti, kad dokumentas bendradarbiavimą debesyje palaiko

  - **Data.Doc.IsOpeningOfflineCopy –** žymė, nurodanti, kad autonominė dokumento kopija atidaryta

  - **Data.Doc.IsSyncBacked –** žymė, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

  - **Data.Doc.Location –** nurodo tarnybą, pateikusią dokumentą („OneDrive“, „File Server“, „SharePoint“ ir kt.)

  - **Data.Doc.LocationDetails –** nurodo vietoje saugomo dokumento žinomą aplanką

  - **Data.Doc.NumberCoAuthors –** skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

  - **Data.Doc.PasswordFlags –** nurodo, ar nustatytas skaitymo arba skaitymo / rašymo slaptažodžio žymių rinkinys

  - **Data.Doc.ReadOnlyReasons –** dokumento atidarymo tik kaip skaitomo priežastys

  - **Data.Doc.ResourceIdHash –** anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data.Doc.ServerDocId –** nekintamų anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data.Doc.ServerProtocol –** protokolo versija, naudojama norint susisiekti su tarnyba

  - **Data.Doc.ServerType –** tarnybą siūlančio serverio tipas („SharePoint“, „OneDrive“, WOPI ir kt.)

  - **Data.Doc.ServerVersion –** serverio versija, siūlanti tarnybą

  - **Data.Doc.SessionId –** nustato konkretų viso seanso dokumentų redagavimo seansą

  - **Data.Doc.SharePointServiceContext –** „SharePoint Online“ užklausų diagnostinė informacija

  - **Data.Doc.SizeInBytes –** dokumento dydžio indikatorius

  - **Data.Doc.SpecialChars –** dokumento URL arba kelio specialiųjų simbolių indikatorius

  - **Data.Doc.StorageProviderId –** nebenaudojamas

  - **Data.Doc.StreamAvailability –** indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas arba išjungtas

  - **Data.Doc.SussionId –** nebenaudojamas

  - **Data.Doc.SyncBackedType –** dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba)

  - **Data.Doc.UrlHash –** vienpusė maiša, skirta „naïve“ dokumento identifikatoriui

  - **Data.Doc.UsedWrsDataOnOpen –** diagnostikos indikatorius, skirtas nuosekliam dokumento atidarymui

  - **Data.Doc.WopiServiceId –** apima unikalų WOPI tarnybos teikėjo identifikatorių

  - **Data.DocnReadOnlyReasons –** nebenaudojamas

  - **Data.DocumentSaveEndpoint –** nebenaudojamas, keičiamas į Data\_Doc\_Location

  - **Data.DocumentSaveType –** įrašymo tipas (įprastas, sukurti, įrašyti kaip)

  - **Data.DocumentSizeOnDisk –** nebenaudojamas, keičiamas į Data\_Doc\_SizeInBytes

  - **Data.DoesBaseHaveContentOnOpen –** pakeitimų sekimo diagnostika, užtikrinanti, kad turėtume naujausią bendrinamo failo versiją

  - **Data.DoesWorkingBranchHaveExcludedDataOnOpen –** pakeitimų sekimo diagnostika, užtikrinanti, kad turėtume naujausią bendrinamo failo versiją

  - **Data.DstDoc.AccessMode –** naujas dokumentas yra skirtas tik skaityti / redaguoti

  - **Data.DstDoc.EdpState –** naujam dokumentui taikomas elektroninių duomenų apsaugos parametras

  - **Data.DstDoc.Extension –** naujo dokumento plėtinys (docx / xlsm / pptx ir kt.)

  - **Data.DstDoc.FileFormat –** naujo dokumento failų formato protokolas

  - **Data.DstDoc.Fqdn –** naujo dokumento „OneDrive“ arba „SharePoint“ interneto domeno vardas

  - **Data.DstDoc.FqdnHash –** naujo dokumento kliento identifikuojamo domeno vardo vienpusė maiša

  - **Data.DstDoc.IdentityUniqueId –** nebenaudojamas

  - **Data.DstDoc.IOFlags –** atidarant naujo dokumento į talpyklą įkeltos naudojamos parinkčių žymės

  - **Data.DstDoc.IsOpeningOfflineCopy –** žymė, nurodanti, kad autonominė naujo dokumento kopija atidaryta

  - **Data.DstDoc.IsSyncBacked –** žyma, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

  - **Data.DstDoc.Location –** nurodo, kuri tarnyba teikė naują dokumentą („OneDrive“, failų serveris, „SharePoint“, kt.)

  - **Data.DstDoc.NumberCoAuthors –** skaičiuoja naujo dokumento bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

  - **Data.DstDoc.ReadOnlyReasons –** priežastys, kodėl naujas dokumentas buvo atidarytas tik kaip skaitomas

  - **Data.DstDoc.ResourceIdHash –** anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms su nauju dokumentu diagnozuoti

  - **Data.DstDoc.ResourceIdHash –** nekeičiamas anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms su nauju dokumentu diagnozuoti

  - **Data.DstDoc.ServerProtocol –** protokolo versija, naudojama norint susisiekti su tarnyba, kai kuriamas naujas dokumentas

  - **Data.DstDoc.ServerType –** serverio tipas, siūlantis tarnybą („SharePoint“, „OneDrive“, WOPI ir kt.) naujam dokumentui

  - **Data.DstDoc.ServerVersion –** serverio versija, siūlanti tarnybą naujam dokumentui

  - **Data.DstDoc.SessionId –** nustato konkretų dokumento redagavimo seansą, naudojamą naujo dokumento seanse

  - **Data.DstDoc.SharePointServiceContext –** „SharePoint Online“ užklausų diagnostinė informacija

  - **Data.DstDoc.SizeInBytes –** dokumento dydžio indikatorius naujam dokumentui

  - **Data.DstDoc.UrlHash –** vienpusė maiša, skirta naujo dokumento „naïve“ dokumento identifikatoriui sukurti

  - **Data.EditorsCount –** kitų dokumentą redaguojančių bendradarbių skaičius

  - **Data.FullIError –** talpykla visų klaidų kodams iš protokolo sluoksnio

  - **Data.HasFilteredCategories –** nebenaudojamas

  - **Data.HasFilteredCategoryNames –** nebenaudojamas

  - **Data.HasFilteredSeries –** nebenaudojamas

  - **Data.HasFilteredSeriesNames –** nebenaudojamas

  - **Data.HasPendingSaveAs –** nurodo, kad užklausa įrašyti kaip / įrašyti kopiją vykdoma

  - **Data.Input.FileOpenState –** taikomosios programos (skaityti / skaityti ir rašyti, ir kt.) užklausta būsena

  - **Data.Input.FileSaveState –** taikomosios programos užklausta būsena (įrašyti atidarant, įrašyti kaip ir kt.)

  - **Data.Input.NetworkCost –** nurodo tinklo kainą / tipą (apskaičiuotas, apskaičiuotas virš savikainos ir kt.)

  - **Data.Input.OpenAsync –** žymė nurodo taikomosios programos užklaustą asinchroninį atidarymą

  - **Data.Input.OpenOfflineCopy –** žymė nurodo taikomosios programos užklaustą atidarymą neprisijungus

  - **Data.IsCachedHistoricalVersion –** nurodo, kad šis talpyklos failas nėra naujausios versijos

  - **Data.IsHtml –** nurodo, kad HTML formato tekstas įklijuotas

  - **Data.IsLegacyCode –** nurodo, kad ankstesnės versijos kodo formato tekstas įterptas

  - **Data.IsLocalOnlyFile –** nurodo, kad failas buvo atidarytas tik iš vietinės saugyklos

  - **Data.IsLocalOrSyncBackedFile –** nurodo, kad failas atliktas vietinis failo atidarymas ir susietas su tarnyba

  - **Data.IsMapUnMapCase –** dalis talpyklos failo būsenos

  - **Data.isOpenFromCollab –** nurodo, kad failą atidarė iš bendrinamos bendradarbiavimo tarnybos

  - **Data.IsStubFile –** dokumentas dar nebendrintas į debesies paslaugą

  - **Data.IsSyncBackedFile –** dokumentas yra aplanke, kuris atnaujinamas atliekant automatinį sinchronizavimą

  - **Data.IsSyncBackedStateDifferentThanOnLastOpen –** pasikeitė dokumento būsena, pakeitimai galėjo būti gauti, kai dokumentas nebuvo atidarytas

  - **Data.IsWorkingBranchAvailableOnOpen –** pakeitimų sekimo diagnostika, užtikrinanti, kad turėtume naujausią bendrinamo failo versiją

  - **Data.Location –** nurodo medijos saugyklos tipą / vietą (USB, debesis ir kt.)

  - **Data.LockRequestDocMode –** nurodo, ar dokumentas yra pasiekiamas kitiems vartotojams

  - **Data.MruRequestResult –** nebenaudojamas

  - **Data.NewDataNotAvailableReason –** nebenaudojamas

  - **Data.OcsDisableReasons –** komanda įrašyti nenaudoja

  - **Data.OcsHostOnOpen –** komanda įrašyti nebenaudoja

  - **Data.Output.FileSaveState –** įrašymo užbaigimo būsena

  - **Data.PivotChart –** nebenaudojamas

  - **Data.resolveConflictState –** užklausų, skirtų išspręsti suliejimo konfliktus, priežasčių kodai

  - **Data.RTCEnabled –** greitų pakeitimų paskirstymo protokolas paleistas

  - **Data.SaveAsToCurrent –** nurodo, kad aktyvaus dokumento perrašys saugomą failą

  - **Data.ServiceId –** nebenaudojamas, pakeistas į Data\_Doc\_WopiServiceId

  - **Data.SessionId –** nebenaudojamas

  - **Data.SizeInBytes –** nebenaudojamas, keičiamas į Data\_Doc\_SizeInBytes

  - **Data.StopwatchDuration –** nebenaudojamas

  - **Data.SyncBackedFileRequiresOnlineTransition –** žymė, nurodanti, kad įrašymo veiksmą laikinai blokuoja perėjimas internete

  - **Data.SyncBackedFileSaveOnOpen –** žymė, nurodanti, kad automatinio sinchronizavimo atliktiems pakeitimams būtina įrašyti, kai failas atidarytas

  - **Data.TelemetryId –** nebenaudojamas

  - **Data.TriggerSaveAfterBaseDownload –** pakeitimų sekimo diagnostika, užtikrinanti, kad turėtume naujausią bendrinamo failo versiją

  - **Data.UploadBlockedDueToCoherencyFailure –** įrašymas į tarnybą užblokuotas dėl laukiančio vartotojo sprendimo dėl konfliktą sukeliančių pakeitimų

  - **Data.UploadBlockedDueToFailedSaveAsOverExisting –** įrašymas į tarnybą užblokuotas dėl nepavykusio bandymo perrašyti esamą failą

  - **Data.UploadPreemptedForCoherency –** atsisakyta įrašymo į tarnybą, nes vartotojas atliko daugiau pakeitimų

  - **Data.UploadPreemptedForSaveAsOverExistingFailure –** atsisakyta įrašymo į tarnybą dėl ankstesnės SaveAsOverExisting klaidos

  - **Data.UploadScheduled –** failas yra paruoštas asinchroniškai nusiųstas į tarnybą

  - **Data.UseClientIdAsSchemaLockId –** žymė, kontroliuojanti kaip dokumentai yra užrakinti tarnyboje

  - **Data.WorkingCopySaved –** pakeitimų sekimo diagnostika, užtikrinanti, kad turėtume naujausią bendrinamo failo versiją

  - **Data.ZrtSaveAsforSyncBackedBusinessEnabled –** žymė, nurodanti įgalintą greitą įrašymą internetinėje „SharePoint“

  - **Data.ZrtSaveAsforSyncBackedConsumerEnabled –** žymė, nurodanti įgalintą greitą įrašymą „OneDrive“ vartotojui

  - **Data.ZrtSaveAsforSyncBackedCTBusinessEnabled –** žymė, nurodanti įgalintą greitą turinio tipų įrašymą internetinėje „SharePoint“

  - **Data.ZrtSaveAsforSyncBackedCTConsumerEnabled –** žymė, nurodanti įgalintą greitą turinio tipų įrašymą „OneDrive“ vartotojui

  - **Data.ZrtSaveAsforSyncBackedMetaDataBusinessEnabled –** žymė, nurodanti įgalintą greitą failo metaduomenų įrašymą internetinėje „SharePoint“

  - **Data.ZrtSaveAsforSyncBackedMetaDataConsumerEnabled –** žymė, nurodanti įgalintą greitą failo metaduomenų įrašymą „OneDrive“ vartotojui

#### <a name="officefindtimeappfailedtostart"></a>Office.FindTime.AppFailedToStart

Surinkta, kai taikomoji programa nepasileidžia dėl netikėtos klaidos paleidimo metu. Naudojama sekti išimtis ir gedimus. Padeda stebėti ir derinti taikomosios programos sveikatą.

Renkami šių laukų duomenys:
- **DateTime** – laiko žyma, kada įvykis užregistruotas

- **EventName** – užregistruoto įvykio pavadinimas

#### <a name="officefirstrunappleactivationresult"></a>Office.FirstRun.Apple.ActivationResult

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas mūsų taikomosios programos aktyvinimo srauto sveikatai stebėti. Renkame duomenis, kad išsiaiškintume „Office 365“ prenumeratos aktyvinimo rezultatus kartu su aktyvinimui naudojamu srautu (pirmojo sistemos paleidimo programa (FRE), srautas taikomojoje programoje, pirkimas ir t. t.).

Renkami šių laukų duomenys:

- **Data_ActivationStatusCollectionTime** – laiko žyma

- **Data_ActivationStatusError** – aktyvinimo klaidos kodas.

- **Data_ActivationStatusFlowType** – skaitinė reikšmė, nurodanti aktyvinimo srauto tipą

#### <a name="officefirstrunappleactivationstatus"></a>Office.FirstRun.Apple.ActivationStatus

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas išsiaiškinti „Office 365“ prenumeratos aktyvinimo rezultatus kartu su aktyvinimui naudojamu srautu (pirmojo sistemos paleidimo programa, srautas taikomojoje programoje, pirkimas ir t. t.). Renkame duomenis, kuriuose yra aktyvinimo tipas, srauto tipas (FRE/DocStage/pirkimas) ir „Office“ licencijavimo tarnybos ID.

Renkami šių laukų duomenys:

- **Data_ActivationTypeCollectionTime** – laiko žyma

- **Data_ActivationTypeFlowType** – skaitinė reikšmė, nurodanti aktyvinimo srauto tipą

- **Data_ActivationTypeOLSLicense** – licencijos identifikatorius

- **Data_ActivationTypeStatus** – aktyvinimo būsenos kodas.

#### <a name="officefirstrunapplefirstruncomplete"></a>Office.FirstRun.Apple.FirstRunComplete

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis leidžia mums žinoti, ar vartotojas naudoja prenumeratą „Freemium“, vykdomo srauto tipą (FRE/DocStage/pirkimas) ir tapatybės tipą (MSA/OrgID). Šį įvykį naudojame norėdami išsiaiškinti, ar įvykdyta pirmojo sistemos paleidimo programa (FRE) ir prisijungimui naudotą tapatybės tipą (MSA/OrgID).

Renkami šių laukų duomenys:

- **Data_FirstRunCompletedCollectionTime** – laiko žyma, skirta srauto užbaigimo laikui registruoti

- **Data_FirstRunCompletedFlowType** – kodas, žymintis vartotojo užbaigto srauto tipą 

- **Data_FirstRunCompletedFreemiumStatus** – kodas, nurodantis prenumeratos „Freemium“ vartotojo srauto užbaigimo būseną

- **Data_FirstRunCompletedIdentityType** – vartotojo, užbaigusio srautą, tapatybės tipas

#### <a name="officefirstrunapplefirstrunstart"></a>Office.FirstRun.Apple.FirstRunStart

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis leidžia mums žinoti, kad vartotojas įvedė pirmojo sistemos paleidimo programą ir vykdomo srauto tipą (FRE/DocStage/pirkimas). Šį įvykį naudojame išsiaiškinti, ar pirmojo sistemos paleidimo programa (FRE) buvo sėkmingai paleista.

Renkami šių laukų duomenys:

- **Data_FirstRunStartedCollectionTime** – laiko žyma, skirta srauto užbaigimo laikui registruoti

- **Data_FirstRunStartedFlowType** – kodas, žymintis vartotojo užbaigto srauto tipą 

#### <a name="officefirstrunapplefirstrunstartedandcompleted"></a>Office.FirstRun.Apple.FirstRunStartedAndCompleted

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis leidžia mums žinoti, ar vartotojas naudoja prenumeratą „Freemium“, vykdomo srauto tipą (FRE/DocStage/pirkimas) ir tapatybės tipą (MSA/OrgID). Naudojame šį įvykį mūsų pirmojo sistemos paleidimo programos (FRE) sveikatai ir efektyvumui išsiaiškinti.

Renkami šių laukų duomenys:

- **Data_FirstRunCompletedCollectionTime** – laiko žyma, skirta srauto užbaigimo laikui registruoti

- **Data_FirstRunCompletedFlowType** – kodas, žymintis vartotojo užbaigto srauto tipą  

- **Data_FirstRunCompletedFreemiumStatus** – kodas, nurodantis prenumeratos „Freemium“ vartotojo srauto užbaigimo būseną

- **Data_FirstRunCompletedIdentityType** – vartotojo, užbaigusio srautą, tapatybės tipas

- **Data_FirstRunStartedCollectionTime** – laiko žyma, skirta srauto pradėjimo laikui registruoti

- **Data_FirstRunStartedFlowType** – kodas, žymintis pradėto vartotojo srauto tipą

#### <a name="officefirstrunappleinapppurchaseactivationfail"></a>Office.FirstRun.Apple.InAppPurchaseActivationFail

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas mūsų taikomosios programos aktyvinimo srauto sveikatai stebėti. Renkame duomenis, kad išsiaiškintume pirkimo programėlėje aktyvinimo rezultatus kartu su aktyvinimui naudojamu srautu (pirmojo sistemos paleidimo programa, srautas programėlėje, pirkimas ir t. t.). 

Renkami šių laukų duomenys:

- **Data_ActivationFailCollectionTime** – laiko žyma, registruojant aktyvinimo klaidos įvykimo laiką 

- **Data_ActivationFailFlowType** – kodas, žymintis vykdyto vartotojo srauto tipą

- **Data_AssoicatedSuccessfullyCollectionTime** – laiko žyma, registruojant laiką, kada įvyko susiejimas 

- **Data_AssoicatedSuccessfullyFlowType** – kodas, žymintis vykdyto vartotojo srauto tipą

#### <a name="officefirstrunappleinapppurchaseactivationsuccess"></a>Office.FirstRun.Apple.InAppPurchaseActivationSuccess

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas mūsų taikomosios programos aktyvinimo srauto sveikatai stebėti. Renkame duomenis, kad išsiaiškintume pirkimo programėlėje aktyvinimo rezultatus kartu su aktyvinimui naudojamu srautu (pirmojo sistemos paleidimo programa, srautas programėlėje, pirkimas ir t. t.). 

Renkami šių laukų duomenys:

- **Data_ActivatedSuccessfullyCollectionTime** – laiko žyma, registruojant laiką, kada įvyko veikla 

- **Data_ActivatedSuccessfullyFlowType** – kodas, žymintis vykdyto vartotojo srauto tipą

- **Data_AssoicatedSuccessfullyCollectionTime** – laiko žyma, registruojant laiką, kada įvyko susiejimas 

- **Data_AssoicatedSuccessfullyFlowType** – kodas, žymintis vykdyto vartotojo srauto tipą

#### <a name="officefirstrunappleinapppurchaseassociationfailed"></a>Office.FirstRun.Apple.InAppPurchaseAssociationFailed

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas mūsų taikomosios programos aktyvinimo srauto sveikatai stebėti. Renkame duomenis, kad išsiaiškintume pirkimo programėlėje aktyvinimo rezultatus kartu su aktyvinimui naudojamu srautu (pirmojo sistemos paleidimo programa, srautas programėlėje, pirkimas ir t. t.). 

Renkami šių laukų duomenys:

- **Data_AppChargedSuccessfullyCollectionTime** – laiko žyma, registruojant laiką, kada buvo įvykdytas pirkimas

- **Data_AppChargedSuccessfullyFlowType** – kodas, žymintis vykdyto vartotojo srauto tipą

- **Data_AssoicationFailedCollectionTime** – laiko žyma, registruojant laiką, kada taikomųjų programų susiejimas nepavyko

- **Data_AssoicationFailedFlowType** – kodas, žymintis vykdyto vartotojo srauto tipą

- **Data_AssoicationFailedResult** – kodas, nurodantis pastebėtos trikties tipą

#### <a name="officefirstrunappleinapppurchaseassociationsuccess"></a>Office.FirstRun.Apple.InAppPurchaseAssociationSuccess

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas mūsų taikomosios programos aktyvinimo srauto sveikatai stebėti. Renkame duomenis, kad išsiaiškintume pirkimo programėlėje aktyvinimo rezultatus kartu su aktyvinimui naudojamu srautu (pirmojo sistemos paleidimo programa, srautas programėlėje, pirkimas ir t. t.). 

Renkami šių laukų duomenys:

- **Data_AppChargedSuccessfullyCollectionTime** – laiko žyma, registruojant laiką, kada buvo įvykdytas pirkimas

- **Data_AppChargedSuccessfullyFlowType** – kodas, žymintis vykdyto vartotojo srauto tipą

- **Data_AssoicatedSuccessfullyCollectionTime** – laiko žyma, registruojant laiką, kada taikomųjų programų susiejimas nepavyko

- **Data_AssoicatedSuccessfullyFlowType** – kodas, žymintis vykdyto vartotojo srauto tipą

#### <a name="officefirstrunappleinapppurchasefailures"></a>Office.FirstRun.Apple.InAppPurchaseFailures

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas mūsų taikomosios programos aktyvinimo srauto sveikatai stebėti. Renkame duomenis apie pirkimo programėlėje srauto rezultatus.

Renkami šių laukų duomenys:

- **Data_AppStoreFailureFlowType** – kodas, nurodantis vykdyto vartotojo srauto tipą

- **Data_AppStoreFailureResult** – pastebėtas nesėkmingas rezultatas

- **Data_CancelRequestFlowType** – kodas, nurodantis vykdyto vartotojo srauto tipą

- **Data_EventId** – kodas, nurodantis pastebėto gedimo tipą

#### <a name="officefirstrunappleinapppurchasesattempted"></a>Office.FirstRun.Apple.InAppPurchasesAttempted

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas mūsų taikomosios programos pirkimo programėlėje srauto sveikatai stebėti. Renkame duomenis, kad galėtume stebėti pirkimą programėlėje ir įsigyjamo SKU tipą (mėnesinis/kasmetinis/namams/asmeninis).

Renkami šių laukų duomenys:

- **Data_EventId** – kodas, nurodantis stebimo rezultato tipą

- **Data_PurchasedClickedOfferType** – SKU, kurį buvo bandoma įsigyti, tipas

- **Data_PurchaseSuccessfulFlowType** – kodas, žymintis vykdyto vartotojo srauto tipą

#### <a name="officefirstrunappleinapprestoreattempted"></a>Office.FirstRun.Apple.InAppRestoreAttempted

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas mūsų taikomosios programos pirkimo programėlėje srauto sveikatai stebėti. Renkame duomenis, kad galėtume stebėti kortelėje atliekamą atkūrimą.

Renkami šių laukų duomenys:

- **Data_EventId** – kodas, nurodantis bandymo rezultato tipą

- **Data_RestoreAttemptFlowType** – kodas, nurodantis vykdyto vartotojo srauto tipą

#### <a name="officefirstrunappleinapprestoreattemptfailed"></a>Office.FirstRun.Apple.InAppRestoreAttemptFailed

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas mūsų taikomosios programos pirkimo programėlėje srauto sveikatai stebėti. Renkame duomenis, kad galėtume stebėti kortelėje atliekamą atkūrimą ir susieti srautą bei klaidas.

Renkami šių laukų duomenys:

- **Data_RestoreButtonFlowType** – kodas, nurodantis vykdyto vartotojo srauto tipą

- **Data_RestoredFailedPaymentCancelledFlowType** – kodas, nurodantis vykdyto mokėjimo atšaukimo srauto tipą

- **Data_RestoredFailedUnKnownFlowType** – ar bandymas nepavyko dėl netikėto vartotojo srauto vykdymo

- **Data_RestoredFailedUnKnownResult** – ar bandymas nepavyko dėl nežinomų priežasčių

#### <a name="officefirstrunapplemacfirstruncompleted"></a>Office.FirstRun.Apple.MacFirstRunCompleted

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis leidžia mums žinoti, kad vartotojas atliko iki galo pirmojo sistemos paleidimo programą. Šį įvykį naudojame norėdami išsiaiškinti, ar pirmojo sistemos paleidimo programa (FRE) sėkmingai užbaigta.

Renkami šių laukų duomenys:

- **Data_FirstRunCollectionTime** – laiko žyma, skirta srauto užbaigimo laikui registruoti.

#### <a name="officefirstrunapplemacwxpfirstrunstarted"></a>Office.FirstRun.Apple.MacWXPFirstRunStarted

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis leidžia mums žinoti, kad vartotojas paleido pirmojo sistemos paleidimo programą. Šį įvykį naudojame išsiaiškinti, ar pirmojo sistemos paleidimo programa (FRE) buvo sėkmingai paleista.

Renkami šių laukų duomenys:

- **Data_FirstRunPanelName** – skydo, iš kurio buvo paleista programa, pavadinimas


#### <a name="officefloodgateuserfactappusage"></a>Office.Floodgate.UserFact.AppUsage

Tai parodo, ar vartotojas naudojo didelės vertės produkto funkcijas. Gali rodyti, kad vartotojas aptiko funkciją arba ja naudojosi. Signalas pateiks įžvalgų apie produkto funkcijos naudojimą, padedančių geriau naudotis produktu.

Renkami šių laukų duomenys: 

- **FeatureAction** – žyma, nurodanti didelės vertės funkciją ir vartotojo atliktą veiksmą, pvz., ContentPickerTried, TemplatesSeen.


#### <a name="officelenslenssdkcloudconnectorlaunch"></a>Office.Lens.LensSdk.CloudConnectorLaunch

Kai vartotojas apkarpo vaizdą ir bakstelėjimu patvirtina galutinį vaizdo pasirinkimą, kad būtų galima naudoti OCR, pasirenkamas šis įvykis.     
Tai yra tarnybos vartotojo-su-užklausa įrašas, nes tarnyboje nėra vartotojo-su-tarnybos-užduotimi susiejimo. Vartotojo ID turi atitikti BDAR reikalavimus, nes tarnyba nėra tiesiogiai pasiekiama vartotojams, o per klientus, ir identifikuoja bendrą žmonių, naudojančių tarnybą, skaičių, padedantį sekti vartotojų, naudojančių produktą, kiekį, taip pat nustatyti tendencijų pokyčius, padėti rasti ir pataisyti produkto problemas.

Renkami šių laukų duomenys:

- **CallType** – eilutė, skirta nustatyti, ar API skambutis buvo sinchroninis arba asinchroninis.

- **CloudConnectorRequestId** – eilutė, kuri identifikuoja tarnybos užklausą, kuri buvo sukurta norint konvertuoti vaizdus naudojant tarnybą. 

- **CloudConnectorTarget** – eilutė, kuri patvirtina, kokio tipo konvertavimą tarnyba atliks su vaizdais, pvz., konvertavimas į PDF, docx, tekstą ir t. t.

- **CustomerId** – eilutė, identifikuojanti vartotoją, kuriam priklauso apdorojami vaizdai.

- **CustomerType** – eilutė, kuri identifikuoja klientą kaip įmonę arba individualų vartotoją. Šis skirtumas turi įtakos atvaizdų, kurias klientas gali konvertuoti vienu metu, skaičiui (kvotai). 

- **RelationId** – eilutė, kuri identifikuoja ryšį tarp „Lens“ ir tarnybos, kuri naudojama apdorojant failus.


#### <a name="officelenslenssdkcloudconnectoruploaderror"></a>Office.Lens.LensSdk.CloudConnectorUploadError

Naudojant Vaizdas į lentelę, kai vartotojas bakstelėja Bendrinti, Kopijuoti ar Atidaryti, vartotojo pateiktos lentelės pataisos bendrinamos su tarnyba, kad būtų patobulintas OCR. Šis įvykis surenkamas atsakius į tos tarnybos klaidą ir apima atitinkamus identifikatorius, skirtus spręsti įvairias tarnybos problemas. 

Renkami šių laukų duomenys:

- **CloudConnectorRequestId** – eilutės identifikatorius, skirtas susieti tarnybos užduotį su dabartine tarnybos užklausa, kurios tobulinimo duomenys buvo bendrinami.

- **CorrelationId** – eilutė, kurioje yra dabartinio tarnybos užduoties egzemplioriaus identifikatorius.

- **Reason** – eilutė, kurioje yra klaidos kodas ir klaidos aprašas.

- **TargetType** – eilutė, identifikuojant tarnybos galinį punktą.

- **TaskType** – eilutė, identifikuojant tarnybos skambučio ketinimą.


#### <a name="officelenslenssdkcloudconnectoruploadsuccess"></a>Office.Lens.LensSdk.CloudConnectorUploadSuccess

Naudojant Vaizdas į lentelę, kai vartotojas bakstelėja Bendrinti, Kopijuoti ar Atidaryti, vartotojo pateiktos lentelės pataisos bendrinamos su tarnyba, kad būtų patobulintas OCR. Šis įvykis surenkamas gavus sėkmingą tarnybos atsaką ir apima atitinkamus identifikatorius, skirtus šalinti proceso problemas. Jis taip pat padeda analizuoti paslaugų tobulinimo galimybių naudojimą.

Renkami šių laukų duomenys:

- **CloudConnectorRequestId** – eilutės identifikatorius, skirtas susieti tarnybos užduotį su dabartine tarnybos užklausa, kurios tobulinimo duomenys buvo bendrinami.

- **CorrelationId** – eilutė, kurioje yra dabartinio tarnybos užduoties egzemplioriaus identifikatorius.

- **TargetType** – eilutė, identifikuojant tarnybos galinį punktą.

- **TaskType** – eilutė, identifikuojant tarnybos skambučio ketinimą.


#### <a name="officelenslenssdksavemedia"></a>Office.Lens.LensSdk.SaveMedia

Šis įvykis iškviečiamas, kai vartotojas spustelėja mygtuką Atlikta ir įrašo vaizdus „Android“ ir „iOS“. Tai padeda išmatuoti vartotojo dalyvavimo lygį kiekybiškai įvertinant vartotojus, kurie įrašo vaizdus naudodami mūsų programą.

Toliau nurodyti laukai renkami „Android“:

- **Data_FileSizeAfterCleanUp** – failo dydis po to, kai jis išvalomas naudojant programą, kad suprastume, koks glaudinimas buvo pasiektas po valymo.

- **Data_FileSizeAfterSave** – failo dydis po to, kai jį įrašo vartotojas, kad suprastume, koks glaudinimas buvo pasiektas po įrašymo.

- **Data_FileSizeBeforeCleanUp** – failo dydį prieš jį išvalant programai, kad suprastume, kokio dydžio jis buvo užfiksuotas

- **Data_Filter** – vaizdui pritaikytas filtras.

- **Data_ImageHeightAfterCleanUp** – vaizdo aukštis po to, kai jį išvalė programa.

- **Data_ImageHeightBeforeCleanUp** – vaizdo aukštis prieš tai, kai jį išvalė programa.

- **Data_ImageWidthAfterCleanUp** – vaizdo plotis po to, kai jį išvalė programa.

- **Data_ImageWidthBeforeCleanUp** – vaizdo plotis prieš tai, kai jį išvalė programa.

- **Data_MediaId** – atvaizdų identifikatorius, skirtas stebėti operacijos sėkmę.

- **Data_ProcessMode** – vartotojo režimas, kai jis įrašė vaizdą.

- **Data_Source** – apibrėžia, iš kur gautas vaizdas, pvz., kamera, importuota iš galerijos ir t. t. 

Toliau nurodyti laukai renkami tik „iOS“:

- **Data_filter** – vaizdui pritaikytas filtras. 

- **Data_imageDPI** – vaizdo sumažinimas, pritaikytas įrašytam vaizdo failui

- **Data_imageSize** – vaizdo dydis vartotojui įrašius vaizdą

- **Data_mediaId** – vaizdų identifikatorius, skirtas stebėti operacijos sėkmę.

- **Data_mode** – vartotojo režimas, kai jis įrašė vaizdą.

- **Data_sizeinPixel** – vaizdo dydis pikselių formatu

- **Data_source** – apibrėžia, iš kur gautas vaizdas, pvz., kamera, importuota iš galerijos ir t. t. 


#### <a name="officelenslenssdkserviceidmapping"></a>Office.Lens.LensSdk.ServiceIDMapping

Duomenys apie šį įvykį renkami, kai „Lens SDK“ sąveikauja su „Microsoft“ vaizdo konvertavimo į dokumentą (arba „I2D“) tarnyba. Tai reiškia, kad įvykis iškviečiamas toliau nurodytais atvejais.

- Nusiuntus vaizdą į „I2D“ tarnybą, siekiant konvertuoti ir išskleisti (OCR) failą.
- Kai vartotojui reikia taisyti tarnybos išvestį, siunčiame atsiliepimą dėl kokybės tobulinimo.

Šie duomenys naudojami siekiant analizuoti tarnybos naudojimą ir diagnozuoti bei šalinti gedimus.  

Renkami šių laukų duomenys:

- **CloudConnectorRequestId** – eilutė, identifikuojanti tarnybos užklausas dėl konvertavimo ir atsiliepimų scenarijų kliento programoje.

- **CustomerId** – ši eilutė padeda susieti vartotojus su tarnybos užklausomis ir leidžia stebėti naudojimą. UserId turi atitikti BDAR reikalavimus, nes tarnyba yra ne tiesiogiai pasiekiama vartotojams, o per klientus, ir identifikuoja bendrą tarnyba besinaudojančių žmonių, skaičių, tokiu būdu padeda tarnybai sekti produktą naudojančių vartotojų kiekį. 

- **I2DFeedbackAPICorrelationId** – eilutė, identifikuojanti atsiliepimų užklausą „I2D“ tarnyboje, kai vartotojas taiso tarnybos išvestį.

- **I2DServiceProcessID** – eilutė, identifikuojanti tarnybos užklausą „I2D“ tarnyboje, kai vartotojas nusiunčia vaizdus konvertuoti.


#### <a name="officelivepersonacardconfigurationsetaction"></a>Office. LivePersonaCard. ConfigurationSetAction

Registruojame, kada vartotojas yra programoje, kuri įkelia asmens kortelę, tikintis, kad vartotojas atidarys „Live“ asmens kortelę. Duomenys naudojami siekiant nustatyti, ar kortelė įkeliama tinkamai. 

Renkami šių laukų duomenys: 

- **Data.accountType** – ar vartotojas priklauso organizacijai ar vartotojui

- **Data.appContextId** – atsitiktine tvarka generuojamas ID, naudojamas identifikuoti skirtingas tos pačios programos paskyras

- **Data.AppInfo.Name** – naudojamos tarnybos pavadinimas (profilio kortelė)

- **Data.AppInfo_Id** – valdančiosios programos pavadinimas

- **Data.AppInfo_Version** – valdančiosios programos versija

- **Data.cardCorrelationId** – asmeninės kortelės visuotinis unikalusis identifikatorius

- **Data.cardPersonaCorrelationId** – kortelėje rodomo konkretaus asmens visuotinis unikalusis identifikatorius

- **Data.clientCorrelationId** – programos seanso visuotinis unikalusis identifikatorius

- **Data.clientType** – įrenginio, kuriame veikia programa, tipas

- **Data.contextType** – iš kokio konteksto (programos) buvo paleista kortelė

- **Data.ecsConfigIds** – kortelėje įgalintų funkcijų versijų identifikatoriai

- **Data.ecsTagId** – funkcijų žymės ID

- **Data.eventId** – įvykio pavadinimo identifikatorius, pvz., „LivePersonaCardRenderedAction“

- **Data.eventpriority** – įvykio siuntimo prioriteto išvardijimo reikšmė.

- **Data.feature** – naudojama grupuoti įvairius tos pačios funkcijos įvykius (profilio kortelė)

- **Data.flights** – kortelėje įgalintos funkcijos

- **Data.fromCache** – ar duomenys buvo surinkti iš atminties

- **Data.hasFinePointer** – ar įrenginys turi pelės žymiklio galimybę

- **Data.hasHoverEvents** – ar įrenginys turi pelės laikymo galimybę

- **Data.immersiveProfileCorrelationId** – išplėstinio profilio peržiūros seanso visuotinis unikalusis identifikatorius

- **Data.offlineResolved** – ar duomenys buvo surinkti neprisijungus

- **Data.OTelJS.Version** – OTel registravimo priemonės versija

- **Data.personaCorrelationId** – seanso unikalių asmenų visuotinis unikalusis identifikatorius

- **Data.properties** – papildomi kiekvieno įvykio duomenys renkami taip: *[Šis laukas buvo pašalintas iš dabartinės „Office“ komponavimo versijos, bet vis tiek gali būti rodomas senesnėse komponavimo versijose.]*

  - **cardCorrelationId** pirmiau esančio Data.appContextId dublikatas
  - **cardPersonaCorrelationId** pirmiau esančio Data.cardCorrelationId dublikatas
  - **ClientTimeStamp** – laikas programoje, kada buvo užregistruotas įvykis
  - **consumerCorrelationId** pirmiau esančio Data.clientCorrelationId dublikatas

  - **externalAppSessionCorrelationId** – programos visuotinis unikalusis identifikatorius, skirtas identifikuoti visas asmenines korteles, atidarytas to paties antrinio seanso metu

- **Data.region** – profilio kortelės vidinės tarnybos, prie kurios vartotojas yra prisijungęs, geografinis regionas

- **Data.tenantAadObjectId** – nuomotojas, su kuriuo susieta vartotojo prenumerata. Leidžia mums klasifikuoti problemas ir nustatyti, ar problema yra plačiai paplitusi, ar izoliuota atskirų nuomotojų grupėje

- **Data.type** – užregistruoto įvykio tipas, pvz., sekimas, klaida, įvykis

- **Data.userAadObjectId** – įmonės „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius (Data.UserInfo.Id dublikatas)

- **Data.UserInfo.Id** – įmonės „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius

- **Data.UserInfo.MsaId** – vartotojo „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius

- **Data.UserInfo.OMSTenantId** – nuomotojas, su kuriuo yra susieta vartotojo prenumerata. Leidžia mums klasifikuoti problemas ir nustatyti, ar problema yra plačiai paplitusi, ar izoliuota atskirų nuomotojų grupėje

- **Data.userPuid** – vartotojo „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius (Data.UserInfo.MsaId dublikatas)

- **Data.version** – tarnybos versija (profilio kortelė)

- **Data.workloadCulture** – valdančiojoje programoje nustatyta kultūra

- **DeviceInfo_Id** – įrenginio visuotinis unikalusis identifikatorius

- **DeviceInfo_Make** – operacinės sistemos prekės ženklas

- **DeviceInfo_Model** – įrenginio modelis

- **DeviceInfo_OsName** – įrenginio OS pavadinimas

- **DeviceInfo_OsVersion** – operacinės sistemos versija

- **DeviceInfo.SDKUid** – unikaliai identifikuoja įrenginį iš telemetrijos SDK perspektyvos

#### <a name="officelivepersonacarduseractionsclosedexpandedpersonacard"></a>Office.LivePersonaCard.UserActions.ClosedExpandedPersonaCard

Registruojama, kai vartotojas uždaro išplėstą asmeninę kortelę. Naudojama stebėti kritines tiesioginių asmeninių kortelių uždarymo klaidų dažnumo anomalijas.

Renkami šių laukų duomenys:

- **AppInfo_Id** – valdančiosios programos pavadinimas

- **AppInfo_Version** – valdančiosios programos versija

- **Data.appContextId** – atsitiktine tvarka generuojamas ID, naudojamas identifikuoti skirtingas tos pačios programos paskyras

- **Data.AppInfo.Name** naudojamos tarnybos pavadinimas (profilio kortelė)

- **Data.cardCorrelationId** – asmeninės kortelės visuotinis unikalusis identifikatorius

- **Data.cardPersonaCorrelationId** – kortelėje rodomo konkretaus asmens visuotinis unikalusis identifikatorius

- **Data.clientCorrelationId** – programos seanso visuotinis unikalusis identifikatorius

- **Data.clientType** – įrenginio, kuriame veikia programa, tipas, pvz., „Outlook_Win32“

- **Data.eventId** – įvykio pavadinimo identifikatorius, pvz., „LivePersonaCardRenderedAction“

- **Data.exportName** vartotojo veiksmo įvykio žmonėms perskaitomas pavadinimas, pvz., „ClosedExpandedPersonaCard“

- **Data.exportType** – BDAR eksportavimo užklausos įvykio kategorija

- **Data.externalAppSessionCorrelationId** – programos visuotinis unikalusis identifikatorius, skirtas identifikuoti visas asmenines korteles, atidarytas to paties antrinio seanso metu

- **Data.feature** – naudojama grupuoti įvairius tos pačios funkcijos įvykius (profilio kortelė)

- **Data.immersiveProfileCorrelationId** – išplėstinio profilio peržiūros seanso visuotinis unikalusis identifikatorius

- **Data.OTelJS.Version** – OTel registravimo priemonės versija

- **Data.personaCorrelationId** – seanso unikalių asmenų visuotinis unikalusis identifikatorius

- **Data.properties** – papildomi kiekvieno įvykio duomenys renkami taip: *[Šis laukas buvo pašalintas iš dabartinės „Office“ komponavimo versijos, bet vis tiek gali būti rodomas senesnėse komponavimo versijose.]*

   - **cardCorrelationId** pirmiau esančio Data.appContextId dublikatas 
   - **cardPersonaCorrelationId** pirmiau esančio Data.cardCorrelationId dublikatas
   - **ClientTimeStamp** – laikas, kada įvyko įvykis „Unix“ epochos metu
   - **consumerCorrelationId** pirmiau esančio Data.clientCorrelationId dublikatas 

- **Data.region** – profilio kortelės vidinės tarnybos, prie kurios vartotojas yra prisijungęs, geografinis regionas

- **Data.tenantAadObjectId** – nuomotojas, su kuriuo susieta vartotojo prenumerata. Leidžia mums klasifikuoti problemas ir nustatyti, ar problema yra plačiai paplitusi, ar izoliuota atskirų nuomotojų grupėje

- **Data.type** – užregistruoto įvykio tipas, pvz., sekimas, klaida, įvykis

- **Data.userAadObjectId** – įmonės „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius (Data.UserInfo.Id dublikatas)

- **Data.UserInfo.Id** – įmonės „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius 

- **Data.UserInfo.MsaId** – vartotojo „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius

- **Data.UserInfo.OMSTenantId** – nuomotojas, su kuriuo yra susieta vartotojo prenumerata. Leidžia mums klasifikuoti problemas ir nustatyti, ar problema yra plačiai paplitusi, ar izoliuota atskirų nuomotojų grupėje.

- **Data.userPuid** – vartotojo „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius(Data.UserInfo.MsaId dublikatas)

- **Data.version** – tarnybos versija (profilio kortelė)

- **DeviceInfo_Id** – įrenginio visuotinis unikalusis identifikatorius

- **DeviceInfo_Make** – operacinės sistemos prekės ženklas

- **DeviceInfo_Model** – įrenginio modelis

- **DeviceInfo.NetworkCost** – nurodo tinklo kainą / tipą (apskaičiuotas, apskaičiuotas virš savikainos ir kt.)

- **DeviceInfo_OsName** – įrenginio OS pavadinimas

- **DeviceInfo_OsVersion** – operacinės sistemos versija

- **PipelineInfo.ClientCountry** – siuntėjo šalies kodas, pagrįstas netvarkytu kliento IP adresu.


#### <a name="officelivepersonacarduseractionsclosedpersonacard"></a>Office.LivePersonaCard.UserActions.ClosedPersonaCard

Registruojame, kai vartotojas uždaro asmens kortelę.  Duomenys naudojami nustatyti, ar kortelė tinkamai uždaryta. 

Renkami šių laukų duomenys: 

- **BatchId** – visuotinis unikalus identifikatorius, jei buvo pateiktas užklausų rinkinys

- **Data.appContextId** – atsitiktine tvarka generuojamas ID, naudojamas identifikuoti skirtingas tos pačios programos paskyras

- **Data.AppInfo.Name** – naudojamos tarnybos pavadinimas (profilio kortelė)

- **Data.AppInfo_Id** – valdančiosios programos pavadinimas

- **Data.AppInfo_Version** – valdančiosios programos versija

- **Data.cardCorrelationId** – asmeninės kortelės visuotinis unikalusis identifikatorius

- **Data.cardPersonaCorrelationId** – kortelėje rodomo konkretaus asmens visuotinis unikalusis identifikatorius

- **Data.clientCorrelationId** – programos seanso visuotinis unikalusis identifikatorius

- **Data.clientType** – įrenginio, kuriame veikia programa, tipas

- **Data.eventId** – įvykio pavadinimo identifikatorius, pvz., „LivePersonaCardRenderedAction“

- **Data.externalAppSessionCorrelationId** – programos visuotinis unikalusis identifikatorius, skirtas identifikuoti visas asmenines korteles, atidarytas to paties antrinio seanso metu.

- **Data.feature** – naudojama grupuoti įvairius tos pačios funkcijos įvykius (profilio kortelė)

- **Data.immersiveProfileCorrelationId** – išplėstinio profilio peržiūros seanso visuotinis unikalusis identifikatorius

- **Data.OTelJS.Version** – OTel registravimo priemonės versija

- **Data.personaCorrelationId** – seanso unikalių asmenų visuotinis unikalusis identifikatorius

- **Data.properties** – papildomi kiekvieno įvykio duomenys renkami taip: *[Šis laukas buvo pašalintas iš dabartinės „Office“ komponavimo versijos, bet vis tiek gali būti rodomas senesnėse komponavimo versijose.]*

  - **ClientTimeStamp** – laikas programoje, kada buvo užregistruotas įvykis
  - **cardCorrelationId** pirmiau esančio Data.appContextId dublikatas
  - **cardPersonaCorrelationId** pirmiau esančio Data.cardCorrelationId dublikatas
  - **consumerCorrelationId** pirmiau esančio Data.clientCorrelationId dublikatas

- **Data.region** – profilio kortelės vidinės tarnybos, prie kurios vartotojas yra prisijungęs, geografinis regionas

- **Data.tenantAadObjectId** – nuomotojas, su kuriuo susieta vartotojo prenumerata. Leidžia mums klasifikuoti problemas ir nustatyti, ar problema yra plačiai paplitusi, ar izoliuota atskirų nuomotojų grupėje

- **Data.type** – užregistruoto įvykio tipas, pvz., sekimas, klaida, įvykis

- **Data.userAadObjectId** – įmonės „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius (Data.UserInfo.Id dublikatas)

- **Data.UserInfo.Id** – įmonės „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius

- **Data.UserInfo.MsaId** – vartotojo „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius

- **Data.UserInfo.OMSTenantId** – nuomotojas, su kuriuo yra susieta vartotojo prenumerata. Leidžia mums klasifikuoti problemas ir nustatyti, ar problema yra plačiai paplitusi, ar izoliuota atskirų nuomotojų grupėje

- **Data.userPuid** – vartotojo „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius(Data.UserInfo.MsaId dublikatas)

- **Data.version** – tarnybos versija (profilio kortelė)

- **Data_hostAppRing** – asmens kortelės pateikimo žiedas

- **Event_ReceivedTime** – renginio registravimo tarnyboje laikas

#### <a name="officelivepersonacarduseractionsopenedexpandedpersonacard"></a>Office.LivePersonaCard.UserActions.OpenedExpandedPersonaCard

Registruojama, kai vartotojas atidaro išplėstą asmeninę kortelę. Naudojama stebėti kritines tiesioginių asmeninių kortelių klaidų dažnumo anomalijas.

Renkami šių laukų duomenys:

- **AppInfo_Id** – valdančiosios programos pavadinimas

- **AppInfo_Version** – valdančiosios programos versija

- **Data.appContextId** – atsitiktine tvarka generuojamas ID, naudojamas identifikuoti skirtingas tos pačios programos paskyras

- **Data.AppInfo.Name** naudojamos tarnybos pavadinimas (profilio kortelė)

- **Data.cardCorrelationId** – asmeninės kortelės visuotinis unikalusis identifikatorius

- **Data.cardPersonaCorrelationId** – kortelėje rodomo konkretaus asmens visuotinis unikalusis identifikatorius

- **Data.clientCorrelationId** – programos seanso visuotinis unikalusis identifikatorius

- **Data.clientScenario** – nustatyti programos funkciją, iš kurios buvo atidaryta asmens kortelė

- **Data.clientType** – įrenginio, kuriame veikia programa, tipas

- **Data.eventId** – įvykio pavadinimo identifikatorius, pvz., „LivePersonaCardRenderedAction“

- **Data.externalAppSessionCorrelationId** – programos visuotinis unikalusis identifikatorius, skirtas identifikuoti visas asmenines korteles, atidarytas to paties antrinio seanso metu.

- **Data.exportName** vartotojo veiksmo įvykio žmonėms perskaitomas pavadinimas, pvz., OpenedPersonaCard

- **Data.exportType** – BDAR eksportavimo užklausos įvykio kategorija

- **Data.feature** – naudojama grupuoti įvairius tos pačios funkcijos įvykius (profilio kortelė)

- **Data.hasPersonalInsightRing** – „Office“ arba „LinkedIn“ įžvalgos gali būti prieinamos vartotojui

- **Data.hostAppRing** – žiedas, kuriuo buvo išplatinta programa

- **Data.immersiveProfileCorrelationId** – išplėstinio profilio peržiūros seanso visuotinis unikalusis identifikatorius

- **Data.OTelJS.Version** – OTel registravimo priemonės versija

- **Data.personaCorrelationId** – seanso unikalių asmenų visuotinis unikalusis identifikatorius

- **Data.properties** – papildomi kiekvieno įvykio duomenys renkami taip: *[Šis laukas buvo pašalintas iš dabartinės „Office“ komponavimo versijos, bet vis tiek gali būti rodomas senesnėse komponavimo versijose.]*

  - **cardCorrelationId** pirmiau esančio Data.appContextId dublikatas 
  - **cardPersonaCorrelationId** pirmiau esančio Data.cardCorrelationId dublikatas
  - **consumerCorrelationId** pirmiau esančio Data.clientCorrelationId dublikatas 

- **Data.region** – profilio kortelės vidinės tarnybos, prie kurios vartotojas yra prisijungęs, geografinis regionas

- **Data.section** – aktyvi išplėstos kortelės sekcija

- **Data.tenantAadObjectId** – nuomotojas, su kuriuo susieta vartotojo prenumerata. Leidžia mums klasifikuoti problemas ir nustatyti, ar problema yra plačiai paplitusi, ar izoliuota atskirų nuomotojų grupėje

- **Data.type** – užregistruoto įvykio tipas, pvz., sekimas, klaida, įvykis

- **Data.userAadObjectId** – įmonės „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius (Data.UserInfo.Id dublikatas)

- **Data.UserInfo.Id** – įmonės „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius 

- **Data.UserInfo.MsaId** – vartotojo „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius

- **Data.UserInfo.OMSTenantId** – nuomotojas, su kuriuo yra susieta vartotojo prenumerata. Leidžia mums klasifikuoti problemas ir nustatyti, ar problema yra plačiai paplitusi, ar izoliuota atskirų nuomotojų grupėje

- **Data.userPuid** – vartotojo „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius(Data.UserInfo.MsaId dublikatas)

- **Data.version** – tarnybos versija (profilio kortelė)

- **DeviceInfo_Id** – įrenginio visuotinis unikalusis identifikatorius

- **DeviceInfo_Make** – operacinės sistemos prekės ženklas

- **DeviceInfo_Model** – įrenginio modelis

- **DeviceInfo_OsName** – įrenginio OS pavadinimas

- **DeviceInfo_OsVersion** – operacinės sistemos versija

- **DeviceInfo_SDKUid** – unikaliai identifikuoja įrenginį iš telemetrijos SDK perspektyvos

- **NetworkCost** – nurodo tinklo kainą / tipą (apskaičiuotas, apskaičiuotas virš savikainos ir kt.)

- **NetworkCountry** – siuntėjo šalies kodas, pagrįstas netvarkytu kliento IP adresu


#### <a name="officelivepersonacarduseractionsopenedpersonacard"></a>Office.LivePersonaCard.UserActions.OpenedPersonaCard

Registruojama, kai vartotojas atidaro asmeninę kortelę. Naudojama stebėti kritines tiesioginių asmeninių kortelių klaidų dažnumo anomalijas.

Renkami šių laukų duomenys:

- **Data.appContextId** – atsitiktine tvarka generuojamas ID, naudojamas identifikuoti skirtingas tos pačios programos paskyras

- **Data.AppInfo.Name** naudojamos tarnybos pavadinimas (profilio kortelė)

- **Data.bandwidthEstimateMbps** – efektyvios dažnių juostos apskaičiavimas Mbps

- **Data.cardCorrelationId** – asmeninės kortelės visuotinis unikalusis identifikatorius

- **Data.cardPersonaCorrelationId** – kortelėje rodomo konkretaus asmens visuotinis unikalusis identifikatorius

- **Data.clientCorrelationId** – programos seanso visuotinis unikalusis identifikatorius

- **Data.clientType** – įrenginio, kuriame veikia programa, tipas.

- **Data.eventId** – įvykio pavadinimo identifikatorius, pvz., „LivePersonaCardRenderedAction“

- **Data.exportName** vartotojo veiksmo įvykio žmonėms perskaitomas pavadinimas, pvz., OpenedPersonaCard

- **Data.exportType** – BDAR eksportavimo užklausos įvykio kategorija

- **Data.externalAppSessionCorrelationId** – programos visuotinis unikalusis identifikatorius, skirtas identifikuoti visas asmenines korteles, atidarytas to paties antrinio seanso metu

- **Data.feature** – naudojama grupuoti įvairius tos pačios funkcijos įvykius (profilio kortelė)

- **Data.hasPersonalInsightRing** – „Office“ arba „LinkedIn“ įžvalgos gali būti prieinamos vartotojui

- **Data.hostAppRing** – žiedas, kuriuo buvo išplatinta programa

- **Data.immersiveProfileCorrelationId** – išplėstinio profilio peržiūros seanso visuotinis unikalusis identifikatorius

- **Data.OTelJS.Version** – OTel registravimo priemonės versija

- **Data.personaCorrelationId** – seanso unikalių asmenų visuotinis unikalusis identifikatorius

- **Data.properties** – papildomi kiekvieno įvykio metaduomenys renkami taip: *[Šis laukas buvo pašalintas iš dabartinės „Office“ komponavimo versijos, bet vis tiek gali būti rodomas senesnėse komponavimo versijose.]*

    - **cardCorrelationId** pirmiau esančio Data.appContextId dublikatas 
    - **cardPersonaCorrelationId** pirmiau esančio Data.cardCorrelationId dublikatas
    - **consumerCorrelationId** pirmiau esančio Data.clientCorrelationId dublikatas 
    - **networkEffectiveType** – tinklo ryšio efektyvus tipas, pvz., slow-2g Online, skirtas identifikuoti, ar vartotojas yra prisijungęs prie interneto asmeninės kortelės rodymo metu
    - **networkType** – naudojamo įrenginio tinklo ryšio tipas
    - **roundTripEstimateMs** – dabartinio ryšio pirmyn ir atgal numatomas efektyvus laikas milisekundėmis

- **Data.region** – profilio kortelės vidinės tarnybos, prie kurios vartotojas yra prisijungęs, geografinis regionas

- **Data.tenantAadObjectId** – nuomotojas, su kuriuo susieta vartotojo prenumerata. Leidžia mums klasifikuoti problemas ir nustatyti, ar problema yra plačiai paplitusi, ar izoliuota atskirų nuomotojų grupėje

- **Data.type** – užregistruoto įvykio tipas, pvz., sekimas, klaida, įvykis

- **Data.userAadObjectId** – įmonės „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius (Data.UserInfo.Id dublikatas)

- **Data.UserInfo.Id** – įmonės „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius 

- **Data.UserInfo.MsaId** – vartotojo „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius

- **Data.UserInfo.OMSTenantId** – nuomotojas, su kuriuo yra susieta vartotojo prenumerata. Leidžia mums klasifikuoti problemas ir nustatyti, ar problema yra plačiai paplitusi, ar izoliuota atskirų nuomotojų grupėje

- **Data.userPuid** – vartotojo „Microsoft“ paskyros visuotinis unikalusis vartotojo identifikatorius(Data.UserInfo.MsaId dublikatas)

- **Data.version** – tarnybos versija (profilio kortelė)

- **Data.viewType** – apibrėžia rodomos profilio kortelės tipą

- **Data.wasOpenedAsCompactCard** – naudojama identifikuoti, jeigu kortelė iš pradžių buvo atidaryta kompaktiniame rodinyje

- **NetworkCost** – nurodo tinklo kainą / tipą (apskaičiuotas, apskaičiuotas virš savikainos ir kt.)

- **NetworkCountry** – siuntėjo šalies kodas, pagrįstas netvarkytu kliento IP adresu.

#### <a name="officemanageabilityclient-fetchpolicyprechecks"></a>Office.Manageability.Client Fetch.PolicyPreChecks

Svarbu, kad telemetrija sektų sėkmingą\\nesėkmingą debesies strategijos iškvietimą pirminiam tikrinimui patvirtinti. ExitReason turi surašytuvo žemėlapį, iš anksto tikrinantį nepavykusią sąlygą.

Renkami šių laukų duomenys:

  - **Data.ExitReason** – surašytuvo reikšmė, nurodanti išjungimo priežastį, jeigu pirminis tikrinimas nepavyko

  - **Data.Log** – pasirinktinis žurnalo pranešimas nurodo, ar pirminis tikrinimas pavyko

#### <a name="officemanageabilityclientfetchandapplypolicy"></a>Office.Manageability.Client.Fetch.AndApplyPolicy

Svarbu, kad telemetrija sektų sėkmingą\\nesėkmingą debesies strategijos iškvietimo inicijavimą iš taikomosios programos. Išjungimo priežastyje pateikiamas surašytuvo žemėlapis į trikties priežastį.

Renkami šių laukų duomenys:

  - **Data.ExitReason** – surašytuvo reikšmė, nurodanti išjungimo priežastį, jeigu pirminis tikrinimas nepavyko

  - **Data.Log** – pasirinktinis žurnalo pranešimas nurodo, ar pirminis tikrinimas pavyko


#### <a name="officeofficemobilepdfviewerpdffileoperations-on-android"></a>Office.OfficeMobile.PdfViewer.PdfFileOperations („Android“)

Įvykis renkamas naudojantis „Office“ programa, skirta „Android“. Jis įrašomas, kai vykdoma .pdf failo atidarymo, uždarymo arba įrašymo operacija, ir naudojamas siekiant suprasti ir nustatyti prioritetus vartotojo patirčiai pagal .pdf failo operacijos informaciją. Įvykis mums leidžia užtikrinti, kad .pdf failų atidarymo, uždarymo ir įrašymo operacijos būtų vykdomos, kaip numatyta, ir pagerinti .pdf failų operacijų veikimą.

Renkami šių laukų duomenys:

- **Data_Doc_FileOpSessionID** – dokumento seanso unikalusis ID

- **Data_ErrorCode** – klaida, rodoma failo atidarymo trikčių / atsisiuntimo trikčių / atsisiuntimo atšaukimo atveju

- **Data_ErrorMessage** – pranešimas, susijęs su klaidos kodu

- **Data_FailureReason** – esant atidarymo trikčiai, nurodoma trikties priežastis.

- **Data_FetchReason** – nurodo, kaip buvo gautas failas (rankiniu būdu, įrašytas į talpyklą, neįrašytas į talpyklą) 

- **Data_FileGUID** – bendrasis failo, kuris yra atsitiktinai sugeneruotas, identifikatorius

- **Data_FileLocation** – failo vieta, pvz., „Local“, „ODSP“, „iCloud“ ir pan.

- **Data_FileOpenEntryPoint** – failo atidarymo įvesties taškas

- **Data_FileSize** – failo, su kuriuo vykdoma operacija, dydis

- **Data_NetworkRequestErrorResponse** – tinklo klaidų atsakas atitinka klaidos kodą.

- **Data_NetworkRequestStage** – klaidų lygis atsisiunčiant debesies PDF failus.

- **Data_OpenMode** – kokiu režimu buvo atidarytas PDF failas, pvz., 0: peržiūros režimas, 2: pasirašymo režimas

- **Data_PageCount** – puslapių skaičius PDF faile.

- **Data_PasswordProtected** – žyma, kuri nurodo, ar failas apsaugotas slaptažodžiu, ar ne.

- **Data_ProviderApp** – dabartinė teikėjo programa tik failo aktyvinimo atveju  

- **Data_ReadOnly** – žyma, kuri nurodo, ar failas yra tik skaitomas, ar ne.

- **Data_Result** – vykdomos operacijos būsena, pvz., teisinga: pavyko, neteisinga: triktis

- **Data_Type** – failo operacijos tipas (atidarymas, uždarymas arba įrašymas) 

#### <a name="officeofficemobilepdfviewerpdffileoperations-on-ios"></a>Office.OfficeMobile.PdfViewer.PdfFileOperations („iOS“)

Įvykis renkamas naudojantis „Office“ programa, skirta „ iOS“. Jis įrašomas, kai vykdoma .pdf failo atidarymo, uždarymo arba įrašymo operacija, ir naudojamas siekiant suprasti ir nustatyti prioritetus vartotojo patirčiai pagal .pdf failo operacijos informaciją. Įvykis mums leidžia užtikrinti, kad .pdf failų atidarymo, uždarymo ir įrašymo operacijos būtų vykdomos, kaip numatyta, ir pagerinti .pdf failų operacijų veikimą. 

- **Data_Doc_FileOpSessionID** – dokumento seanso unikalusis ID 

- **Data_ErrorCode** – klaida, rodoma failo atidarymo trikčių / atsisiuntimo trikčių / atsisiuntimo atšaukimo atveju 

- **Data_ErrorMessage** – pranešimas, susijęs su klaidos kodu 

- **Data_FailureReason** – esant atidarymo trikčiai, nurodoma trikties priežastis. 

- **Data_FetchReason** – nurodo, kaip buvo gautas failas (rankiniu būdu, įrašytas į talpyklą, neįrašytas į talpyklą)

- **Data_FileGUID** – bendrasis failo, kuris yra atsitiktinai sugeneruotas, identifikatorius

- **Data_FileLocation** – failo vieta („Local“, „ODSP“, „iCloud“ ir pan.) 

- **Data_FileOpenEntryPoint** – failo atidarymo įvesties taškas 

- **Data_FileSize** – failo, su kuriuo vykdoma operacija, dydis 

- **Data_OpenMode** – kokiu režimu buvo atidarytas PDF failas (0: peržiūros režimas, 2: pasirašymo režimas) 

- **Data_PageCount** – puslapių skaičius PDF faile.

- **Data_PasswordProtected** – žyma, kuri nurodo, ar failas apsaugotas slaptažodžiu, ar ne. 

- **Data_ProviderApp** – dabartinė teikėjo programa tik failo aktyvinimo atveju  

- **Data_ReadOnly** – žyma, kuri nurodo, ar failas yra tik skaitomas, ar ne.

- **Data_Result** – vykdomos operacijos būsena (teisinga: pavyko, neteisinga: triktis) 

- **Data_Type** – failo operacijos tipas (atidarymas, uždarymas arba įrašymas)


#### <a name="officeonenoteandroidappnavigationnavigationuistatechanged"></a>Office.OneNote.Android.App.Navigation.NavigationUIStateChanged

*[Šis įvykis anksčiau buvo pavadintas OneNote.App.Navigation.NavigationUIStateChanged.]*

Šis įvykis renka kritinį signalą, naudojamą užtikrinti, kad „OneNote“ vartotojai galėtų sėkmingai naršyti programoje.  Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. 

Renkami šių laukų duomenys: 

- **IS_SPANNED** – nurodo, ar programa veikia segmentuotu režimu. Registruojama konkrečiai sulenkiamų įrenginių atveju.

- **NEW_STATE** – nurodo programų būseną iškart po naršymo veiksmo

- **OLD_STATE** – nurodo programų būseną iškart prieš naršymo veiksmą

#### <a name="officeonenoteandroidcanvaspageopened"></a>Office.OneNote.Android.Canvas.PageOpened

*[Šis įvykis anksčiau buvo vadinamas OneNote.Canvas.PageOpened.]*

Signalas, naudojamas įrašyti kai puslapis yra atidarytas.  Telemetrija naudojama stebėti, aptikti ir išspręsti problemas, susijusias su puslapio atidarymu programoje „OneNote“.

Renkami šių laukų duomenys: 

- **JOT_ID** – atidaryto puslapio objektas

- **TIME_TAKEN_IN_MS** – laikas, skirtas puslapiui atidaryti

#### <a name="officeonenoteandroidcapturenewnotenewnotetaken"></a>Office.OneNote.Android.Capture.NewNote.NewNoteTaken

*[Šis įvykis anksčiau buvo vadinamas OneNote.Capture.NewNote.NewNoteTaken.]*

Šis signalas naudojamas siekiant užtikrinti, kad vartotojui prisijungus prie „OneNote“ „Android“ programos, bloknotai būtų tinkamai parengti ir vartotojas sėkmingai sukurtų naują pastabą.  Tai naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai.

Renkami šių laukų duomenys:

- Nėra

#### <a name="officeonenoteandroidlenssdkofficelenslaunched"></a>Office.OneNote.Android.LensSDK.OfficeLensLaunched

*[Šis įvykis anksčiau buvo vadinamas OneNote.LensSDK.OfficeLensLaunched.]*

Šis įvykis renka kritinį signalą, naudojamą siekiant užtikrinti sėkmingą „OfficeLens“ paleidimą.  Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. 

Renkami šių laukų duomenys: 

- **CAPTURE_MODE** – nurodo, kokiu režimu buvo paleista „OfficeLens“.  Jis gali būti numatytasis, redagavimo, greitojo įterpimo arba vaizdo įrašo importavimo.

- **ERROR_CODE** – nurodo paleidimo klaidos kodą, jei paleidžiant įvyko klaida.

- **IMAGE_COUNT** – nurodo padarytų nuotraukų skaičių

- **LAUNCH_REASON** – nurodo „OfficeLens“ paleidimo procesą. Tai gali būti atlikta užrakto ekrane arba per fotoaparato ar galerijos parinktis, priklijuojamuose lapeliuose arba „OneNote“ drobėje ir pan.

#### <a name="officeonenoteandroidmessagebarmessagebarclicked"></a>Office.OneNote.Android.MessageBar.MessageBarClicked

*[Šis įvykis anksčiau buvo vadinamas OneNote. OneNote.MessageBar.MessageBarClicked.]*

Signalas, naudojamas rodyti visas problemas, iškilusias naudojant pranešimų juostą.  Telemetrija naudojama stebėti, aptikti ir išspręsti problemas, atsiradusias naudojant pranešimų juostą.

Renkami šių laukų duomenys: 

- **Message_Bar_Type** – pateikia informaciją, jei vartotojas naudoja seną arba naują pranešimų juostą

- **Message_Type** – pateikia klaidos pranešimo ID

#### <a name="officeonenoteandroidstickynotesnotecreated"></a>Office.OneNote.Android.StickyNotes.NoteCreated
 
Kritinis signalas, naudojamas stebėti priklijuojamų lapelių galimybę kurti pastabas programoje.   Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Jei vartotojai negali sukurti pastabos, tai gali lemti didelės svarbos incidentą.

Renkami šių laukų duomenys:

- **IsExportable** – žymė, nurodanti, ar šis įvykis tapo vartotojo veiksmo rezultatu. Turėtų būti nustatyta į True, nes NoteCreated yra vartotojo suaktyvinamas veiksmas.

- **NoteLocalId** – atskiriamas unikalusis identifikatorius, priskirtas pastabai tuo metu, kai vartotojas sukuria pastabą programoje.

- **StickyNotes-SDKVersion** – versijos numeris, nurodantis priklijuojamų lapelių programos, kurią naudoja vartotojas, versiją. Leidžia mums nustatyti kurios produkto versijos rodo problemą, kad galėtume tinkamai nustatyti jos prioritetą.


#### <a name="officeonenoteandroidstickynotesnoteviewed"></a>Office.OneNote.Android.StickyNotes.NoteViewed

Kritinis signalas, naudojamas stebėti priklijuojamų lapelių galimybę peržiūrėti pastabas programoje.  Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Jei vartotojai negali peržiūrėti savo pastabų, suaktyvinamas didelės svarbos incidentas.

Renkami šių laukų duomenys:

- **HasImages** – žymė, nurodanti, ar peržiūrėta pastaba turi joje išsaugotų vaizdų.

- **IsExportable** – žymė, nurodanti, ar šis įvykis tapo vartotojo veiksmo rezultatu. Turėtų būti nustatyta į True, nes NoteViewed yra vartotojo suaktyvinamas veiksmas.

- **NoteLocalId** – atskiriamas unikalusis identifikatorius, priskirtas pastabai tuo metu, kai vartotojas sukuria pastabą programoje.

- **StickyNotes-SDKVersion** – versijos numeris, nurodantis priklijuojamų lapelių programos, kurią naudoja vartotojas, versiją. Leidžia mums nustatyti kurios produkto versijos rodo problemą, kad galėtume tinkamai nustatyti jos prioritetą.


#### <a name="officeonenotecanvasinkinkstrokelogger"></a>Office.OneNote.Canvas.Ink.InkStrokeLogger 

Šis įvykis naudojamas aptikti ir diagnozuoti aukšto dažnio klaidą, su kuria vartotojas susiduria naudodamas rankraščio funkciją.  Tai bus panaudota norint nustatyti tinkamiausią šios problemos nustatymo būdą. 

Renkami šių laukų duomenys:

- **CurrentCanvasZoomFactor** – dabartinis drobės padidinimo koeficientas.

- **CurrentNotebook** – dabartinio aktyvaus bloknoto identifikatorius.

- **CurrentPage** – dabartinio aktyvaus puslapio identifikatorius.

- **CurrentSection** – dabartinio aktyvaus skyriaus identifikatorius.

- **DefaultCanvasZoomFactor** – drobės padidinimo koeficiento numatytoji reikšmė.

- **InkStrokeCount** – bendras rankraščio brūkštelėjimų skaičius nuo paskutinio įrašo.

- **InkStrokeWithLayerInkEffect** – rankraščio brūkštelėjimų su sluoksnio rankraščio efektu skaičius nuo paskutinio įrašo.

- **InkStrokeWithoutPressureCount** – nespaudžiamų rankraščio brūkštelėjimų skaičius nuo paskutinio įrašo.

- **InkStrokeWithPencilInkEffect** – rankraščio brūkštelėjimų su pieštuku skaičius nuo paskutinio įrašo.

- **InkStrokeWithTilt** – rankraščio brūkštelėjimų su pakreipimu skaičius nuo paskutinio įrašo.

#### <a name="officeonenotenavigationcreatepage"></a>Office.OneNote.Navigation.CreatePage

Kritinis signalas, naudojamas stebėti „OneNote“ vartotojų gebėjimą kurti puslapius programoje „OneNote“.  Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Jei vartotojai negali sukurti puslapio, suaktyvinimas didelės svarbos incidentas.

Renkami šių laukų duomenys:

- **IsAtSectionEnd** – nurodo, ar naujas puslapis sukuriamas skyriaus pabaigoje, ar ne.

- **IsBlank** – nurodo, ar naujas puslapis yra tuščias, ar sukurtas naudojant šabloną.

- **IsRecentsView** – nurodo, ar puslapis sukuriamas iš Naujausių, ar ne.

- **NavView** – nurodo, ar puslapis sukuriamas iš naršymo rodinio, ar ne.

- **NoteType** – nurodo puslapio tipą (sparčioji pastaba, sąrašas arba nuotrauka).

- **QuickNoteType** – nurodo puslapio tipą (sparčioji pastaba, sąrašas arba nuotrauka).

- **RailState** – nurodo „OneNote“ naršymo kreiptuvo būseną kuriant puslapį.

- **Trigger** – nurodo įvesties tašką, kuriame pradedamas puslapio kūrimo veiksmas.

- **TriggerInfo** – nurodo papildomą informaciją, susijusią su paleidikliu.


#### <a name="officeonenotenavigationcreatesection"></a>Office.OneNote.Navigation.CreateSection

Kritinis signalas, naudojamas stebėti „OneNote“ vartotojų gebėjimą kurti sekcijas programoje „OneNote“.  Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Jei vartotojai negali sukurti puslapio, suaktyvinimas didelės svarbos incidentas.

Renkami toliau apibūdintų laukų duomenys

- **NotebookID** – unikalusis bloknoto identifikatorius.

- **SectionID** – unikalusis sukurtos sekcijos identifikatorius.

- **Trigger** – nurodo įvesties tašką, kuriame pradedamas sekcijos kūrimo veiksmas.

- **TriggerInfo** – nurodo papildomą informaciją, susijusią su paleidikliu.


#### <a name="officeonenotenavigationnavigate"></a>Office.OneNote.Navigation.Navigate

Kritinis signalas, naudojamas stebėti „OneNote“ vartotojų gebėjimą naršyti tarp puslapių programoje „OneNote“.  Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Jei vartotojai negali naršyti, suaktyvinamas didelės svarbos incidentas.

Renkami šių laukų duomenys:

- **FromNotebook** – unikalusis bloknoto identifikatorius.

- **FromPage** – unikalusis puslapio identifikatorius.

- **FromSection** – unikalusis sekcijos identifikatorius.

- **FromSectionGroup** – unikalusis sekcijų grupės identifikatorius.

- **IsCurrentUserEduStudent** – nurodo, ar dabartiniam vartotojui švietimo įstaigos bloknote priskirtas mokinio arba studento vaidmuo, ar ne.

- **IsEduNotebook** – nurodo, ar dabartinis puslapis yra švietimo įstaigos bloknotas, ar ne.

- **IsEduNotebookReadOnlyPage** – nurodo, ar dabartinis puslapis yra švietimo įstaigos bloknote tik skaitomas, ar ne.

- **ToNotebook** – unikalusis bloknoto identifikatorius.

- **ToPage** – unikalusis puslapio identifikatorius.

- **ToSection** – unikalusis sekcijos identifikatorius.

- **ToSectionGroup** – unikalusis sekcijų grupės identifikatorius.


#### <a name="officeonenotenotebookmanagementcreatenotebook"></a>Office.OneNote.NotebookManagement.CreateNotebook

Kritinis signalas, naudojamas stebėti „OneNote“ vartotojų gebėjimą kurti bloknotus programoje „OneNote“.  Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Jei vartotojai negali sukurti bloknotų, suaktyvinamas didelės svarbos incidentas.

Renkami šių laukų duomenys:
    
- **NotebookID** – unikalusis bloknoto identifikatorius.


#### <a name="officeonenotenotebookmanagementopennotebook"></a>Office.OneNote.NotebookManagement.OpenNotebook

Kritinis signalas, naudojamas stebėti „OneNote“ vartotojų gebėjimą atidaryti bloknotus programoje „OneNote“.  Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Jei vartotojai negali atidaryti bloknotų, suaktyvinamas didelės svarbos incidentas.

Renkami šių laukų duomenys:

-  **NotebookID** – unikalusis bloknoto identifikatorius.

    
#### <a name="officeonenotesearchsearch"></a>Office.OneNote.Search.Search

Kritinio signalo ID, naudojamas stebėti „OneNote“ vartotojų gebėjimą rasti informaciją tūkstančiuose puslapių ir bloknotų.   Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Jei vartotojai negali rasti informacijos įvairiuose bloknotuose, suaktyvinamas didelės svarbos incidentas.

Renkami šių laukų duomenys:

- **PageSearchResultCount** – nurodo ieškos rezultatų, rastų puslapio ieškos režimu, skaičių.

-  **PageTimeToFirstResultInMs** – nurodo, per kiek laiko puslapio ieškos režimu veikianti „OneNote“ randa pirmą atitikmenį.
    
-  **PageTimeToLastResultInMs** – nurodo, per kiek laiko puslapio ieškos režimu veikianti „OneNote“ randa paskutinį atitikmenį.

-  **PageTimeToMedianResultInMs** – nurodo, laiko, per kurį puslapio ieškos režimu veikianti „OneNote“ randa visus atitikmenis, medianą.

-  **SearchResultCount** – nurodo ieškos rezultatų skaičių.

-  **TagSearchResultCount** – nurodo ieškos rezultatų, rastų žymių ieškos režimu, skaičių.

-  **TagTimeToFirstResultInMs** – nurodo, per kiek laiko žymių ieškos režimu veikianti „OneNote“ randa pirmą atitikmenį.

-  **TagTimeToLastResultInMs** – nurodo, per kiek laiko žymių ieškos režimu veikianti „OneNote“ randa paskutinįjį atitikmenį.

-  **TagTimeToMedianResultInMs** – nurodo, laiko, per kurį žymių ieškos režimu veikianti „OneNote“ randa visus atitikmenis, medianą.

-  **TimeToFirstResultInMs** – nurodo, per kiek laiko „OneNote“ randa pirmą atitikmenį.

-  **TimeToLastResultInMs** – nurodo, per kiek laiko „OneNote“ randa paskutinį atitikmenį.

-  **TimeToMedianResultInMs** – nurodo, laiko, per kurį „OneNote“ randa visus atitikmenis, medianą.

### <a name="officeonenotesigscriticalerrorencountered"></a>Office.OneNote.SIGS.CriticalErrorEncountered

Šis įvykis fiksuoja kritinį signalą, kuris naudojamas stebėti signalų įtraukimo tarnybos (SIGS) sveikatą registruojant, kiekvieną kartą, kai susiduriama su kritine klaida. Kritinės klaidos gali užblokuoti visas SIGS, o tai mums padės pastebėti tokias ir panašias problemas, kai tik su jomis susiduria vartotojai. 

Be šios funkcijos, mes būsime priklausomi nuo vartotojų pranešimų apie problemas, su kuriomis jie susiduria. Be tokios telemetrijos, tokių problemų sprendimo laikas užtruktų daug ilgiau.

Renkami šių laukų duomenys: 

- **ErrorCode** – problemos, su kuria susidūrė vartotojas, kodas.


#### <a name="officeonenotestickynotesnotecreated-on-ios-onenotestickynotesnotecreated-on-android"></a>Office.OneNote.StickyNotes.NoteCreated („iOS“), OneNote.StickyNotes.NoteCreated („Android“)

Tai kritinis signalas, naudojamas stebėti priklijuojamų lapelių galimybę kurti pastabas programoje.  Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Jei vartotojai negali sukurti pastabos, suaktyvinamas didelės svarbos incidentas.

Renkami šių laukų duomenys:

- **NoteLocalId** – atskiriamas unikalusis identifikatorius, priskirtas pastabai tuo metu, kai vartotojas sukuria pastabą programoje.

- **IsExportable** – žymė, nurodanti, ar šis įvykis tapo vartotojo veiksmo rezultatu. Turėtų būti nustatyta į True, nes NoteCreated yra vartotojo suaktyvinamas veiksmas.

- **StickyNotes-SDKVersion** – versijos numeris, nurodantis priklijuojamų lapelių programos, kurią naudoja vartotojas, versiją. Leidžia mums nustatyti kurios produkto versijos rodo problemą, kad galėtume tinkamai nustatyti jos prioritetą.


#### <a name="officeonenotestickynotesnoteviewed-on-ios-onenotestickynotesnoteviewed-on-android"></a>Office.OneNote.StickyNotes.NoteViewed („iOS“), OneNote.StickyNotes.NoteViewed („Android“)

Tai kritinis signalas, naudojamas stebėti priklijuojamų lapelių galimybę kurti pastabas programoje.  Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Jei vartotojai negali sukurti pastabos, suaktyvinamas didelės svarbos incidentas.

Renkami šių laukų duomenys:

- **HasImages** – žymė, nurodanti, ar peržiūrėta pastaba turi joje išsaugotų vaizdų.

- **IsExportable** – žymė, nurodanti, ar šis įvykis tapo vartotojo veiksmo rezultatu. Turėtų būti nustatyta į True, nes NoteViewed yra vartotojo suaktyvinamas veiksmas.

- **NoteLocalId** – atskiriamas unikalusis identifikatorius, priskirtas pastabai tuo metu, kai vartotojas sukuria pastabą programoje.

- **StickyNotes-SDKVersion** – versijos numeris, nurodantis priklijuojamų lapelių programos, kurią naudoja vartotojas, versiją. Leidžia mums nustatyti kurios produkto versijos rodo problemą, kad galėtume tinkamai nustatyti jos prioritetą.


#### <a name="officeonenotestoragenotebooksyncresult"></a>Office.OneNote.Storage.NotebookSyncResult
 
Šis įvykis registruoja bloknoto sinchronizavimo rezultatą. Jis naudojamas norint suprasti, kiek reikia unikalių sinchronizavimo tikslų, apskaičiuojant „OneNote“ sinchronizavimo balą.
 
Renkami toliau apibūdintų laukų duomenys

- **CachedError_Code** – skaitinis arba raidinis kodas, naudojamas nustatyti talpyklinės klaidos pobūdį ir (arba) kodėl ji įvyko
    
- **CachedError_Description** – talpyklinės klaidos aprašas

- **CachedError_Tag** – nurodo, kur kode įvyksta talpyklinė klaida

- **CachedError_Type** – talpyklinės klaidos tipas, pvz., „Win32Error“ ir t. t.

- **ExecutionTime** – laikas milisekundėmis, reikalingas bloknotui dubliuoti

- **Gosid** – visuotinio objekto srities ID

- **IdentityType** – tapatybės tipas, pavyzdžiui, „Windows Live“, organizacijos ID ir t. t.

- **InitialReplicationInSession** – nurodo, ar dubliuojamas pirmasis bloknoto dubliavimas atidarius, ar ne

- **IsBackgroundSync** – nurodo, ar tai fono sinchronizavimas ar ne

- **IsCachedErrorSuppressed** – nurodo, ar talpyklinė klaida suglaudinta, ar ne

- **IsCachedErrorUnexpected** – nurodo, ar talpyklinė klaida netikėta, ar ne

- **IsNotebookErrorSuppressed** – nurodo, ar bloknoto lygio sinchronizavimo klaida suglaudinta, ar ne

- **IsNotebookErrorUnexpected** – nurodo, ar bloknoto lygio sinchronizavimo klaida netikėta, ar ne

- **IsSectionErrorSuppressed** – nurodo, ar sekcijos sinchronizavimo klaida suglaudinta, ar ne

- **IsSectionErrorUnexpected** – nurodo, ar sekcijos sinchronizavimo klaida suglaudinta, ar ne

- **IsUsingRealtimeSync** – nurodo, ar bloknotas sinchronizuotas naudojant šiuolaikinį puslapio turinio sinchronizavimą, ar ne

- **LastAttemptedSync** – laiko žyma, nurodanti, kada bloknotas buvo bandytas sinchronizuoti paskutinį kartą

- **LastBackgroundSync** – laiko žyma, nurodanti, kada paskutinį kartą buvo bandyta sinchronizuoti foną

- **LastNotebookViewedDate** – vėliausios bloknoto peržiūros data

- **LastSuccessfulSync** – laiko žyma, nurodanti, kada bloknotas buvo sėkmingai sinchronizuotas prieš tai

- **NeedToRestartBecauseOfInconsistencies** – nurodo, ar sinchronizavimą reikia paleisti iš naujo dėl nesuderinamumų, ar ne

- **NotebookErrorCode** – nurodo, kad bloknoto lygio sinchronizavimo klaidos kodas įrašytas bloknoto diagramos srityje

- **NotebookId** – bloknoto ID

- **NotebookType** – bloknoto tipas

- **ReplicatingAgainBecauseOfInconsistencies** – nurodo, ar sinchronizavimas paleidžiamas iš naujo dėl nesuderinamumų, ar ne

- **SectionError_Code** – skaitinis arba raidinis kodas, naudojamas nustatyti sekcijos sinchronizavimo klaidos pobūdį ir (arba) kodėl ji įvyko

- **SectionError_Description** – sekcijos sinchronizavimo klaidos aprašas

- **SectionError_Tag** – nurodo, kur kode įvyksta sekcijos sinchronizavimo klaida

- **SectionError_Type** – sekcijos sinchronizavimo klaidos tipas, pvz., „Win32Error“ ir t. t.

- **Success** – nurodo, ar bloknotą pavyko sėkmingai sinchronizuoti, ar ne

- **SyncDestinationType** – nurodo sinchronizacijos paskirties tipą, pvz., „OneDrive“ arba „SharePoint Online“

- **SyncId** – unikalus kiekvieno bloknoto sinchronizavimo numeris

- **SyncWasFirstInSession** – nurodo, ar šis sinchronizavimas yra pirmasis sinchronizavimas per dabartinį seansą

- **SyncWasUserInitiated** – nurodo, ar šį sinchronizavimą inicijavo vartotojas, ar ne

- **TenantId** – „SharePoint“ nuomotojo ID

- **TimeSinceLastAttemptedSync** – laikas, praėjęs nuo vėliausio bandymo sinchronizuoti bloknotą

- **TimeSinceLastSuccessfulSync** – laikas, praėjęs nuo vėliausio sėkmingo bloknoto sinchronizavimo


#### <a name="officeonenotesystemapplifecycleapplaunch"></a>Office.OneNote.System.AppLifeCycle.AppLaunch

Kritinis signalas, naudojamas užtikrinti, kad „OneNote“ vartotojai gali sėkmingai paleisti taikomąją programą. Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Jei vartotojai negali paleisti programos mūsų efektyvumo lange, suaktyvinamas didelės svarbos incidentas.

Renkami šių laukų duomenys: jokių

#### <a name="officeoutlookdesktopaccountconfigurationcreateaccountresult"></a>Office.Outlook.Desktop.AccountConfiguration.CreateAccountResult

Rezultatas yra paskyros įtraukimas į naują profilį „Outlook“ iš „Office Backstage“ arba iš paskyros nustatymų dialogo lango. Duomenys yra aktyviai stebimi siekiant užtikrinti, kad triktyse nebūtų matomi realizavimo keliai. Taip pat analizuojame duomenis, kad rastume tobulintinas sritis. Siekiame pagerinti šį sėkmingo atlikimo procentą su kiekviena versija.

Renkami šių laukų duomenys:

  - **AccountCreationResult** – paskyros įtraukimo į „Outlook“ rezultatas (pavyko, nepavyko, nutrauktas ir kt.).

  - **AccountCreationTime** – laikas, naudotas bandant sukurti paskyrą

  - **AccountInfoSource** – paskyros parametrų šaltinis (pvz., AutoDiscover, GuessSmart, AutoDetect ir kt.)

  - **AccountType** – konfigūruojamos paskyros tipas.

  - **HashedEmailAddress** – el. pašto adreso maiša

  - **ShowPasswordPageFlightEnabled** – indikatorius, jei testavimo variantas ShowPopImapPasswordPage yra įgalintas

#### <a name="officeoutlookdesktopaccountconfigurationrepairaccountresult"></a>Office.Outlook.Desktop.AccountConfiguration.RepairAccountResult

Įvyko dėl paskyros taisymo arba išplėstinių paskyros parametrų keitimo. Duomenys yra aktyviai stebimi siekiant užtikrinti, kad triktyse nebūtų matomi realizavimo keliai. Taip pat analizuojame duomenis, kad rastume tobulintinas sritis. Kadangi tai yra naujos (pertvarkyta) patirtys, norime užtikrinti, kad jas tinkamai atlikome.

Renkami šių laukų duomenys:

  - **AccountInfoSource** – paskyros, naudotos bandymui taisyti, informacijos šaltinis

  - **AccountType** – paskyros, kurią buvo bandoma taisyti, tipas

  - **HashedEmailAddress** – el. pašto adreso maiša

  - **ManualRepairRequested** – indikatorius, nurodantis, ar buvo užklaustas rankinis taisymas

  - **Result** – bandymo taisyti paskyrą rezultatas. Pvz.: „Success“ arba „Fail\_SaveChangesToAccount“

#### <a name="officeoutlookdesktopaccountconfigurationupdatepasswordresult"></a>Office.Outlook.Desktop.AccountConfiguration.UpdatePasswordResult

Paskyros slaptažodžio iš paskyros parametrų išplečiamojo meniu naujinimo rezultatas. Duomenys yra aktyviai stebimi siekiant užtikrinti, kad triktyse nebūtų matomi realizavimo keliai. Taip pat analizuojame duomenis, kad rastume tobulintinas sritis. Kadangi tai yra naujos (pertvarkyta) patirtys, norime užtikrinti, kad jas tinkamai atlikome.

Renkami šių laukų duomenys:

  - **AccountType** – paskyros, kurios buvo bandoma atnaujinti slaptažodį, tipas

  - **HashedEmailAddress** – el. pašto adreso maiša

  - **Result** – bandymo naujinti slaptažodį rezultatas. Pvz.: „Success“ ar „Fail\_AllowLessSecureAppsDisabled“


#### <a name="officeoutlookdesktopstorescreatenewstore"></a>Office.Outlook.Desktop.Stores.CreateNewStore

Renka naujos parduotuvės (tipo ir versijos) sukūrimo rezultatą, bei rezultato kodą. Aktyviai stebime šį įvykį, sekdami vartotojo galimybės sinchronizuoti ir saugoti el. paštą kompiuteryje, archyvuoti el. laiškus (PST) ar naudoti „Groups“ sveikatą.

Renkami šių laukų duomenys:

  - **Standartinė HVA veikla** su pasirinktine apkrova

  - **StoreType** – parduotuvės, sukūrusios OST/PST/NST, tipas

  - **StoreVersion** – sukurtos mažos / didelės / „Tardis“ parduotuvės versija

#### <a name="officeoutlookmacaccountaddworkflow"></a>Office.Outlook.Mac.AccountAddWorkflow

Paskyros įtraukimo į programą „Outlook“ rezultatas. Duomenys yra stebimi siekiant užtikrinti, kad nebūtų didelio trikčių skaičiaus padidėjimo. Taip pat analizuojame duomenis, kad rastume tobulintinas sritis. Siekiame pagerinti šį sėkmingo atlikimo procentą su kiekviena versija. 

Renkami šių laukų duomenys:

- **AccountConfigMethod** – paskyros konfigūravimo metodas

- **AccountType** – konfigūruojamos paskyros tipas

- **AccountWorkflowSession** – seansas, per kurį bandoma paskyros darbo eiga

- **SessionDuration** – seanso trukmė 

- **ThreadId** – gijos identifikatorius


#### <a name="officeoutlookmacaccountonboardingflow"></a>Office.Outlook.Mac.AccountOnboardingFlow

Paskyros įtraukimo į programą „Outlook“, naudojant naujas paskyros konfigūravimo funkcijas, rezultatas. Duomenys yra stebimi siekiant užtikrinti, kad nebūtų didelio trikčių skaičiaus padidėjimo. Taip pat analizuojame duomenis, kad rastume tobulintinas sritis. Siekiame pagerinti šį sėkmingo atlikimo procentą su kiekviena versija. 

Renkami šių laukų duomenys:

- **AccountConfigAutoSignIn** – administratoriaus nustatytas automatinis paskyros konfigūravimas

- **AccountConfigDomain** – domenas, nurodytas konfigūruojant paskyrą 

- **AccountConfigEntryPoint** – įvesties taškas, kuriame vartotojas įvedė paskyros konfigūraciją 

- **AccountConfigErrorCode** – konfigūruojant paskyrą aptiktas klaidos kodas 

- **AccountConfigErrorString** – konfigūruojant paskyrą aptikta klaida

- **AccountConfigMethod** – paskyros konfigūravimo metodas

- **AccountConfigPhase** – dabartinis paskyros konfigūravimo darbo eigos veiksmas

- **AccountConfigPhaseFrom** – pradinis paskyros konfigūravimo darbo eigos veiksmas 

- **AccountConfigPhaseTo** – paskutinis paskyros konfigūravimo darbo eigos veiksmas 

- **AccountType** – konfigūruojamos paskyros tipas

- **AccountWorkflowSession** – seansas, per kurį bandoma paskyros darbo eiga

- **SessionDuration** – seanso trukmė


#### <a name="officeoutlookmacdeleteaccountusage"></a>Office.Outlook.Mac.DeleteAccountUsage

Paskyros naikinimo programoje „Outlook“ rezultatas. Duomenys yra stebimi siekiant užtikrinti, kad nebūtų didelio trikčių skaičiaus padidėjimo. Taip pat analizuojame duomenis, kad rastume tobulintinas sritis. Siekiame pagerinti šį sėkmingo atlikimo procentą su kiekviena versija. 

Renkami šių laukų duomenys:

- **AccountType** – konfigūruojamos paskyros tipas

- **AccountID** – paskyros identifikatorius

- **DeprovisionAccount** – nurodo, ar paskyra pašalinama iš serverio

- **IsFastDelete** – nurodo, ar paskyra panaikinta iš fono gijos

#### <a name="officepowerpointdocoperationclose"></a>Office.PowerPoint.DocOperation.Close

Surinkta uždarius „PowerPoint“ pateiktis. Joje yra informacija, reikalinga tinkamai nustatyti ir diagnozuoti problemas, įvykusias uždarymo proceso metu, ir kurios yra vartotojo duomenų išlaikymo ir sinchronizavimo ribojimo priežastimi. „Microsoft“ naudoja šiuos duomenis, kad užtikrintų, jog uždarymas veikia kaip priklauso ir vartotojo turinys yra sėkmingai išlaikomas.

Renkami šių laukų duomenys:

  - **Data\_AddDocTelemetryResult:long –** ar šis žurnalo įrašas turi visą reikiamą dokumento telemetriją (Data\_Doc\_\* laukus)? Jei ne, kodėl?

  - **Data\_AutoSaveDisabledReasons:string –** iš anksto nustatytų reikšmių, nurodančių kodėl šiame dokumente buvo išjungtas automatinis įrašymas, rinkinys (Suliejomo klaida, įrašymo klaida, grupės strategija ir kt.)

  - **Data\_CloseReason:long –** kaip buvo vykdomas uždarymas? Uždarant dokumentą? Uždarant programą?

  - **Data\_CppUncaughtExceptionCount:long –** neapdorojamų išimčių skaičius

  - **Data\_DetachedDuration:long –** veiklos atskyrimo / neveikimo trukmė

  - **Data\_Doc\_AccessMode:long –** kaip šis dokumentas buvo atidarytas (tik skaityti | skaityti ir rašyti)

  - **Data\_Doc\_AssistedReadingReasons:long –** iš anksto apibrėžtų reikšmių, nurodančių dokumento atidarymo pagalbiniu skaitymo režimu priežastis, rinkinys

  - **Data_Doc_AsyncOpenKind:long** – nurodo, ar debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

  - **Data\_Doc\_ChunkingType:long –** kaip dokumentas saugomas programoje „SharePoint“

  - **Data\_Doc\_EdpState:long –** dokumento įmonės duomenų apsaugos būsena

  - **Data\_Doc\_Ext:string –** dokumento plėtinys

  - **Data\_Doc\_Extension:string –** dokumento plėtinys

  - **Data\_Doc\_FileFormat:long –** iš anksto nustatytų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

  - **Data\_Doc\_Fqdn:string –** vieta, kurioje saugomas dokumentas (SharePoint.com, live.net) galima tik „Office 365“ domenams

  - **Data\_Doc\_FqdnHash:string –** dokumento saugojimo vietos maiša

  - **Data\_Doc\_IdentityTelemetryId:string –** unikalus vartotojo GUID

  - **Data\_Doc\_IdentityUniqueId:string –** unikalus tapatybės identifikatorius, kuris buvo naudojamas veiksmui su bendrinamais dokumentais

  - **Data\_Doc\_IOFlags:long –** šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

  - **Data\_Doc\_IrmRights:long –** iš anksto nustatytų reikšmių, nurodančių kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool –** „true“, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

  - **Data\_Doc\_IsIncrementalOpen:bool –** ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

  - **Data\_Doc\_IsOcsSupported:bool –** ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

  - **Data\_Doc\_IsOpeningOfflineCopy:bool –** tikrina, ar dokumentas atidarytas iš vietinės talpyklos

  - **Data\_Doc\_IsSyncBacked:bool –** tikrina, ar dokumentas atidarytas iš aplanko, naudojamo „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai

  - **Data\_Doc\_Location:long –** iš anksto apibrėžtų dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

  - **Data\_Doc\_LocationDetails:long –** iš anksto apibrėžtų išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

  - **Data\_Doc\_NumberCoAuthors:long –** bendraautorių skaičius dokumento atidarymo metu

  - **Data\_Doc\_PasswordFlags:long –** iš anksto apibrėžtų dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit) –

  - **Data\_Doc\_ReadOnlyReasons:long –** iš anksto apibrėžtų dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

  - **Data\_Doc\_ResourceIdHash:string –** debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data_Doc_RtcType** – nurodo, kaip buvo nustatytas realaus laiko kanalas (RTC) dabartiniam failui (išjungtas, nepalaikomas, pagal pageidavimą, visada įjungta, ir t. t.).

  - **Data\_Doc\_ResourceIdHash:string -** Debesyje saugomų dokumentų maišos išteklių identifikatorius

  - **Data\_Doc\_ServerProtocol:long –** iš anksto apibrėžtų protokolo naudojimas kreiptis į serverį reikšmių rinkinys (Http, „Cobalt“, WOPI ir kt.)

  - **Data\_Doc\_ServerType:long –** iš anksto apibrėžtų serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI)

  - **Data\_Doc\_ServerVersion:long –** tikrina, ar serveryje naudojama „Office14“, „Office15“ arba „Office 16“

  - **Data\_Doc\_SessionId:long -** Generuotas GUID, kuris identifikuoja dokumento egzempliorių to paties seanso metu

  - **Data\_Doc\_SharePointServiceContext:string –** nepermatoma eilutė, paprastai GridManagerID.FarmID. Tinkanti kliento ir serverio įvykių žurnalo koreliacijai

  - **Data\_Doc\_SizeInBytes:long –** dokumento dydis baitais

  - **Data\_Doc\_SpecialChars:long –** šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

  - **Data\_Doc\_StorageProviderId:string –** eilutė, nurodanti dokumento saugyklos teikėją, pvz., „DropBox“

  - **Data\_Doc\_StreamAvailability:long –** iš anksto apibrėžtų dokumentų srauto būsenos reikšmių rinkinys (available, permanently disabled, not available)

  - **Data\_Doc\_UrlHash:string –** debesyje saugomų dokumentų visų URL maiša

  - **Data\_Doc\_UsedWrsDataOnOpen:bool –** „true“, jei failas buvo atidarytas palaipsniui naudojant iš anksto pagrindinio kompiuterio talpykloje saugomus WRS duomenis

  - **Data\_Doc\_WopiServiceId:string –** WOPI tarnybos identifikatorius, pvz., „Dropbox“

  - **Data\_DocHasStorage:bool –** ar šis dokumentas turi vietinę saugyklą?

  - **Data\_fLifeguarded:bool –** ar kada dokumentui buvo naudojama apsauginė funkcija (funkcija, automatiškai taisanti dokumento klaidas nepranešant vartotojui)?

  - **Data\_IsDocAutoSaveable:bool -** Ar pateiktis įrašoma automatiškai?

  - **Data\_IsDocDirty:bool –** ar pristatyme yra dar neįrašytų pakeitimų?

  - **Data\_IsNewDoc:bool –** ar tai naujas arba esamas dokumentas

  - **Data\_IsRecoveredDoc:bool –** ar dokumentą galima atkurti? (Jei prieš seansą sugedo, rodome dokumento atkūrimo sritį kitoje sesijoje)

  - **Data\_NewDocDiscarded:bool –** ar naujas pristatymas šalinamas neįrašytas

  - **Data\_OCSClosingDlgCanceled:bool –** jei nusiuntimo laukiama OCS, kai vartotojas uždaro dokumentą, atsidariusiame laikinajame dialogo lange vartotojo prašoma palaukti. Kurią parinktį renkasi vartotojas?

  - **Data\_OCSClosingDlgExpired:bool –** ar dialogo langas užsidarė pasibaigus jam skirtam laikui (po 1 minutės)?

  - **Data\_OCSClosingStatus:long –** kokia galutinė OCS būsena (In CSI, Closable, In OCS Transition, In CSI transition ir kt.)

  - **Data\_OCSClosingWaitDurationMS:long –** kiek laiko vartotojas turėjo laukti, kad nusiųstų OCS

  - **Data\_OCSHandleTransitionResult:long –** iš anksto nustatytų perėjimo uždarymo metu rezultatų verčių rinkinys (Already tried, continue to close ir kt.)

  - **Data\_ServerDocId:string –** unikalaus dokumento identifikavimo GUID

  - **Data\_StopwatchDuration:long –** visas veiklos laikas

  - **Data\_UserContinuedZRTClose:bool –** kai uždarymo metu rodomas dialogo langas, ar vartotojas pasirinkto Tęsti norėdami uždaryti?

#### <a name="officepowerpointdocoperationnewdocument"></a>Office.PowerPoint.DocOperation.NewDocument

Surinkta, „PowerPoint“ naujos pateikties sukūrimo metu.  Apima sėkmingą klaidos šalinimą ir našumo metrikas.

Ši informacija naudojama užtikrinti, kad galėsime sukurti failus sėkmingai, nesumažėjant našumui.

Renkami šių laukų duomenys:

  - **NewDocumentType** – ar naujas dokumentas sukurtas naudojant šabloną, ar sukurtas tik tuščias dokumentas?

  - **FLifeguarded** – dokumento apsauga (funkcija, atkurianti sugadintos būsenos dokumentą nepateikdami raginimo vartotojui)

#### <a name="officepowerpointdocoperationopencompleteprotocol"></a>Office.PowerPoint.DocOperation.OpenCompleteProtocol

Renkama, kai „PowerPoint“ atidaro pateiktis. Jame yra informacija, reikalinga norint tinkamai nustatyti ir diagnozuoti problemas, įvykstančias atidarymo proceso baigiamosiose stadijose.

„Microsoft“ naudoja šiuos duomenis užtikrinti, jog funkcija veikia kaip numatyta ir pateikčių atidarymas nesuprastėjo.

Renkami šių laukų duomenys:

  - **Data\_AntiVirusScanMethod:long –** iš anksto apibrėžtas antivirusinės programos nuskaitymo tipo reikšmių rinkinys (IOAV, AMSI, None ir kt.)

  - **Data\_AntiVirusScanStatus:long –** iš anksto apibrėžtas antivirusinės programos nuskaitymo, atliekamo atidarant kiekvieną dokumentą, reikšmių rinkinys (NoThreatsDetected, Failed, MalwareDetected ir kt.)

  - **Data\_CloseAndReopen:bool –** ar šis dokumentas buvo uždarytas, ar pakartotinai atidarytas?

  - **Data_ClpDocHasDrmDoc:bool** – ar dokumentas turi DRM dokumentą

  - **Data_ClpDocHasIdentity:bool** – ar dokumentas turi tapatybės informaciją (naudojamą gauti ir nustatyti slaptumo žymas)

  - **Data_ClpDocHasSessionMetadata:bool** – ar dokumente yra veikiantys seanso slaptumo žymos metaduomenys

  - **Data_ClpDocHasSpoMetadata:bool** – ar dokumente yra slaptumo žymos metaduomenys iš SPO per IMetadataCache

  - **Data_ClpDocHasSpoPackage:bool** – ar dokumente yra slaptumo žymos metaduomenys iš SPO per IPackage

  - **Data_ClpDocIsProtected:bool** – ar dokumentas yra apsaugotas IRM, ar ne

  - **Data_ClpDocMetadataSource:int** – išvardijimas, nurodantis, iš kur gaunami slaptumo žymos metaduomenys (IRM, OPC dalies, „SharePoint“ ir t. t.)

  - **Data_ClpDocNeedsUpconversion:bool** – ar dokumentai reikia konvertuoti slaptumo žymos duomenis iš custom.xml dalies

  - **Data_ClpDocNumFailedSetLabels:int** – slaptumo žymų, kurių nepavyko nustatyti dokumente, skaičius

  - **Data_ClpDocSessionMetadataDirty:bool** – ar dokumente yra veikiantys slaptumo žymos duomenys, kurie buvo suteršti

  - **Data_ClpDocWasInTrustBoundary:bool** – ar dokumentas buvo patikimo ribose (o tai leidžia bendraautoriaus dirbti dokumentuose, apsaugotuose slaptumo žymų)

  - **Data\_DetachedDuration:long –** veiklos atskyrimo / neveikimo trukmė

  - **Data\_Doc\_AccessMode:long –** kaip šis dokumentas buvo atidarytas (tik skaityti | skaityti ir rašyti)

  - **Data\_Doc\_AssistedReadingReasons:long –** iš anksto apibrėžtų reikšmių, nurodančių dokumento atidarymo pagalbiniu skaitymo režimu priežastis, rinkinys

  - **Data_Doc_AsyncOpenKind:long** – nurodo, ar debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

  - **Data\_Doc\_ChunkingType:long –** kaip dokumentas saugomas programoje „SharePoint“

  - **Data\_Doc\_EdpState:long –** dokumento įmonės duomenų apsaugos būsena

  - **Data\_Doc\_Ext:string –** dokumento plėtinys

  - **Data\_Doc\_Extension:string –** dokumento plėtinys

  - **Data\_Doc\_FileFormat:long –** iš anksto nustatytų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

  - **Data\_Doc\_Fqdn:string –** vieta, kurioje saugomas dokumentas (SharePoint.com, live.net) galima tik „Office 365“ domenams

  - **Data\_Doc\_FqdnHash:string –** dokumento saugojimo vietos maiša

  - **Data\_Doc\_IdentityTelemetryId:string –** unikalus vartotojo GUID

  - **Data\_Doc\_IdentityUniqueId:string –** unikalus tapatybės identifikatorius, kuris buvo naudojamas veiksmui su bendrinamais dokumentais

  - **Data\_Doc\_IOFlags:long –** šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

  - **Data\_Doc\_IrmRights:long –** iš anksto nustatytų reikšmių, nurodančių kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool –** „true“, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

  - **Data\_Doc\_IsIncrementalOpen:bool –** ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

  - **Data\_Doc\_IsOcsSupported:bool –** ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

  - **Data\_Doc\_IsOpeningOfflineCopy:bool –** ar dokumentas atidarytas iš vietinės talpyklos?

  - **Data\_Doc\_IsSyncBacked:bool –** ar dokumentas atidarytas iš aplanko, naudojančio „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai

  - **Data\_Doc\_Location:long –** iš anksto apibrėžtų dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

  - **Data\_Doc\_LocationDetails:long –** iš anksto apibrėžtų išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

  - **Data\_Doc\_NumberCoAuthors:long –** bendraautorių skaičius dokumento atidarymo metu

  - **Data\_Doc\_PasswordFlags:long –** iš anksto apibrėžtų dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit) –

  - **Data\_Doc\_ReadOnlyReasons:long –** iš anksto apibrėžtų dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

  - **Data\_Doc\_ResourceIdHash:string –** debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data_Doc_RtcType** – nurodo, kaip buvo nustatytas realaus laiko kanalas (RTC) dabartiniam failui (išjungtas, nepalaikomas, pagal pageidavimą, visada įjungta, ir t. t.).

  - **Data\_Doc\_ResourceIdHash:string -** Debesyje saugomų dokumentų maišos išteklių identifikatorius

  - **Data\_Doc\_ServerProtocol:long –** iš anksto apibrėžtų protokolo naudojimas kreiptis į serverį reikšmių rinkinys (Http, „Cobalt“, WOPI ir kt.)

  - **Data\_Doc\_ServerType:long –** iš anksto apibrėžtų serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI)

  - **Data\_Doc\_ServerVersion:long –** tikrina, ar serveryje naudojama „Office14“, „Office15“ arba „Office 16“

  - **Data\_Doc\_SessionId:long -** Generuotas GUID, kuris identifikuoja dokumento egzempliorių to paties seanso metu

  - **Data\_Doc\_SharePointServiceContext:string –** nepermatoma eilutė, paprastai GridManagerID.FarmID. Tinkanti kliento ir serverio įvykių žurnalų koreliacijai

  - **Data\_Doc\_SizeInBytes:long –** dokumento dydis baitais

  - **Data\_Doc\_SpecialChars:long –** šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

  - **Data\_Doc\_StorageProviderId:string –** eilutė, nurodanti dokumento saugyklos teikėją, pvz., „DropBox“

  - **Data\_Doc\_StreamAvailability:long –** iš anksto apibrėžtų dokumentų srauto būsenos reikšmių rinkinys (available, permanently disabled, not available)

  - **Data\_Doc\_UrlHash:string –** debesyje saugomų dokumentų visų URL maiša

  - **Data\_Doc\_UsedWrsDataOnOpen:bool –** „true“, jei failas buvo atidarytas palaipsniui naudojant iš anksto pagrindinio kompiuterio talpykloje saugomus WRS duomenis

  - **Data\_Doc\_WopiServiceId:string –** WOPI tarnybos identifikatorius, pvz., „Dropbox“

  - **Data\_ExecutionCount:long –** kiek kartų vykdėme IncOpen protokolą, prieš šio protokolo (OpenComplete) vykdymą

  - **Data\_FailureComponent:long –** iš anksto nustatytų verčių, dėl kurių komponentų įvyko šio protokolo triktis, rinkinys (Conflict, CSI, Internal ir kt.)

  - **Data\_FailureReason:long –** iš anksto nustatytų reikšmių, nurodančių trikties priežastis, rinkinys (FileIsCorrupt, BlockedByAntivirus ir kt.)

  - **Data_FullDownloadRoundTripCount:long –** kelionių į serverį ir atgal, skirtų atsisiųsti visą dokumentą, skaičius.
  
  - **Data_IsProtocolRunInIncOpenMode:bool –** ar protokolas vykdytas papildančiajam atsisiuntimui, kuris yra dokumento dalių, prieš tai jas parodžius vartotojui, atsisiuntimas.

  - **Data\_MethodId:long –** nurodo vidinę informaciją kodo eilutės, kuri turėjo būti vykdoma paskutinė

  - **Data\_StopwatchDuration:long –** visas veiklos laikas

  - **Data\_TimeToEdit:long –** dokumento tapimo redaguotinu trukmė

  - **Data\_TimeToView:long –** pirmosios dokumento skaidrės tapimo generuotina trukmė

  - **Data\_UnhandledException:bool –** visos vietinės neapdorotos išimtys?

#### <a name="officepowerpointdocoperationsave"></a>Office.PowerPoint.DocOperation.Save

Surinkti kiekvieną kartą, kai „PowerPoint“ įrašo naudodama modernų kodo kelią. Apima sėkmingai arba nesėkmingai atlikto našumo metrikų ir susijusio dokumento metaduomenų įrašymo rezultato tipą.  Nepavykus įrašymui, duomenys gali būti prarasti. „Microsoft“ naudoja šiuos duomenis, kad užtikrintų, jog funkcija veikia kaip priklauso ir vartotojo turinys yra sėkmingai išlaikomas.

Renkami šių laukų duomenys:

  - **Data\_AddDocTelemetryResult:long –** ar šis žurnalo įrašas turi visą reikiamą dokumento telemetriją (Data\_Doc\_\* laukus)? Jei ne, kodėl?

  - **Data\_BeforeSaveEvent:long –** laikas, skirtas pakelti dokumentą prieš įrašymo įvykį

  - **Data\_CheckDownRevSaveTimeMS:long –** laikas, skirtas peržiūrai tikrinti

  - **Data\_CheckMacroSaveTimeMS:long –** laikas, skirtas makrokomandoms įrašyti

  - **Data\_ClearAutoSaveTimeMS:long –** laikas, skirtas automatinio įrašymo žymei valyti

  - **Data\_ClearDirtyFlagTimeMS:long –** laikas, skirtas dokumento neatnaujintai žymei valyti

  - **Data\_CloneDocumentTimeMS:long –** laikas, skirtas dokumentą prieš įrašymą klonuoti

  - **Data_ClpDocHasDrmDoc:bool** – ar dokumentas turi DRM dokumentą

  - **Data_ClpDocHasIdentity:bool** – ar dokumentas turi tapatybės informaciją (naudojamą gauti ir nustatyti slaptumo žymas)

  - **Data_ClpDocHasSessionMetadata:bool** – ar dokumente yra veikiantys seanso slaptumo žymos metaduomenys

  - **Data_ClpDocHasSpoMetadata:bool** – ar dokumente yra slaptumo žymos metaduomenys iš SPO per IMetadataCache

  - **Data_ClpDocHasSpoPackage:bool** – ar dokumente yra slaptumo žymos metaduomenys iš SPO per IPackage

  - **Data_ClpDocIsProtected:bool** – ar dokumentas yra apsaugotas IRM, ar ne

  - **Data_ClpDocMetadataSource:int** – išvardijimas, nurodantis, iš kur gaunami slaptumo žymos metaduomenys (IRM, OPC dalies, „SharePoint“ ir t. t.)

  - **Data_ClpDocNeedsUpconversion:bool** – ar dokumentai reikia konvertuoti slaptumo žymos duomenis iš custom.xml dalies

  - **Data_ClpDocNumFailedSetLabels:int** – slaptumo žymų, kurių nepavyko nustatyti dokumente, skaičius

  - **Data_ClpDocSessionMetadataDirty:bool** – ar dokumente yra veikiantys slaptumo žymos duomenys, kurie buvo suteršti

  - **Data_ClpDocWasInTrustBoundary:bool** – ar dokumentas buvo patikimo ribose (o tai leidžia bendraautoriaus dirbti dokumentuose, apsaugotuose slaptumo žymų)

  - **Data\_CommitTransactionTimeMS:long –** laikas, skirtas įrašymo operacijai atlikti

  - **Data\_CppUncaughtExceptionCount:long –** veiklos veikimo metu neaptiktos vietinės išimtys

  - **Data\_DetachedDuration:long –** veiklos atskyrimo / neveikimo trukmė

  - **Data\_Doc\_AccessMode:long –** kaip šis dokumentas buvo atidarytas (tik skaityti | skaityti ir rašyti)

  - **Data\_Doc\_AssistedReadingReasons:long –** iš anksto apibrėžtų reikšmių, nurodančių dokumento atidarymo pagalbiniu skaitymo režimu priežastis, rinkinys

  - **Data_Doc_AsyncOpenKind:long** – nurodo, ar debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

  - **Data\_Doc\_ChunkingType:long –** kaip dokumentas saugomas programoje „SharePoint“

  - **Data\_Doc\_EdpState:long –** dokumento įmonės duomenų apsaugos būsena

  - **Data\_Doc\_Ext:string –** dokumento plėtinys

  - **Data\_Doc\_Extension:string –** dokumento plėtinys

  - **Data\_Doc\_FileFormat:long –** iš anksto nustatytų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

  - **Data\_Doc\_Fqdn:string –** vieta, kurioje saugomas dokumentas (SharePoint.com, live.net) galima tik „Office 365“ domenams

  - **Data\_Doc\_FqdnHash:string –** dokumento saugojimo vietos maiša

  - **Data\_Doc\_IdentityTelemetryId:string –** unikalus vartotojo GUID

  - **Data\_Doc\_IdentityUniqueId:string –** unikalus tapatybės identifikatorius, kuris buvo naudojamas veiksmui su bendrinamais dokumentais

  - **Data\_Doc\_IOFlags:long –** šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

  - **Data\_Doc\_IrmRights:long –** iš anksto nustatytų reikšmių, nurodančių kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool –** „true“, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

  - **Data\_Doc\_IsIncrementalOpen:bool –** ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

  - **Data\_Doc\_IsOcsSupported:bool –** ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

  - **Data\_Doc\_IsOpeningOfflineCopy:bool –** tikrina, ar dokumentas atidarytas iš vietinės talpyklos

  - **Data\_Doc\_IsSyncBacked:bool –** ar dokumentas atidarytas iš aplanko, naudojančio „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai

  - **Data\_Doc\_Location:long –** iš anksto apibrėžtų dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

  - **Data\_Doc\_LocationDetails:long –** iš anksto apibrėžtų išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

  - **Data\_Doc\_NumberCoAuthors:long –** bendraautorių skaičius dokumento atidarymo metu

  - **Data\_Doc\_PasswordFlags:long –** iš anksto apibrėžtų dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit)

  - **Data\_Doc\_ReadOnlyReasons:long –** iš anksto apibrėžtų dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

  - **Data\_Doc\_ResourceIdHash:string –** debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data_Doc_RtcType** – nurodo, kaip buvo nustatytas realaus laiko kanalas (RTC) dabartiniam failui (išjungtas, nepalaikomas, pagal pageidavimą, visada įjungta, ir t. t.).

  - **Data\_Doc\_ResourceIdHash:string -** Debesyje saugomų dokumentų maišos išteklių identifikatorius

  - **Data\_Doc\_ServerProtocol:long –** iš anksto apibrėžtų protokolo naudojimas kreiptis į serverį reikšmių rinkinys (Http, „Cobalt“, WOPI ir kt.)

  - **Data\_Doc\_ServerType:long –** iš anksto apibrėžtų serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI)

  - **Data\_Doc\_ServerVersion:long –** tikrina, ar serveryje naudojama „Office14“, „Office15“ arba „Office 16“

  - **Data\_Doc\_SessionId:long -** Generuotas GUID, kuris identifikuoja dokumento egzempliorių to paties seanso metu

  - **Data\_Doc\_SharePointServiceContext:string –** nepermatoma eilutė, paprastai GridManagerID.FarmID. Tinkanti kliento ir serverio įvykių žurnalų koreliacijai

  - **Data\_Doc\_SizeInBytes:long –** dokumento dydis baitais

  - **Data\_Doc\_SpecialChars:long –** šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

  - **Data\_Doc\_StorageProviderId:string –** eilutė, nurodanti dokumento saugyklos teikėją, pvz., „DropBox“

  - **Data\_Doc\_StreamAvailability:long –** iš anksto apibrėžtų dokumentų srauto būsenos reikšmių rinkinys (available, permanently disabled, not available)

  - **Data\_Doc\_UrlHash:string –** debesyje saugomų dokumentų visų URL maiša

  - **Data\_Doc\_UsedWrsDataOnOpen:bool –** „true“, jei failas buvo atidarytas palaipsniui naudojant iš anksto pagrindinio kompiuterio talpykloje saugomus WRS duomenis

  - **Data\_Doc\_WopiServiceId:string –** WOPI tarnybos identifikatorius, pvz., „Dropbox“

  - **Data\_DurationUAEOnSaveStartedMs:long –** laikas, skirtas nežinomai taikomajai programai išjungti įrašymo metu

  - **Data\_EnsureSaveTransactionTimeMS:long –** laikas, skirtas įrašymo operacijos sukūrimui užtikrinti, jei jos nėra

  - **Data\_FailureComponent:long –** iš anksto nustatytų verčių, dėl kurių komponentų įvyko šio protokolo triktis, rinkinys (Conflict, CSI, Internal ir kt.)

  - **Data\_FailureReason:long –** iš anksto nustatytų reikšmių, nurodančių trikties priežastis, rinkinys (FileIsCorrupt, BlockedByAntivirus ir kt.)

  - **Data\_fLifeguarded:bool –** ar kada dokumentui buvo naudojama apsauginė funkcija (funkcija, automatiškai taisanti dokumento klaidas nepranešant vartotojui)?

  - **Data\_HandleEnsureContentType:long –** laikas,skirtas visų turinio tipų teisingumui užtikrinti

  - **Data\_HandleEnsureContentTypeTimeMS:long –** laikas,skirtas visų turinio tipų teisingumui užtikrinti

  - **Data\_HasEmbeddedFont:bool –** ar šiame dokumente yra įdėtieji šriftai?

  - **Data\_InitializeSaveTimeMS:long –** laikas inicijuoti dokumento turinio pradėti įrašyti

  - **Data\_InOCSTransition:bool –** ar šis įrašymas skirtas pereiti į OCS

  - **Data\_IsSavingWithEmbeddedFont:bool –** ar šiame dokumente yra įdėtieji šriftai?

  - **Data\_MethodId:long –** nurodo vidinę informaciją kodo eilutės, kuri turėjo būti vykdoma paskutinė

  - **Data\_PerformEmbedFontsTimeMS:long –** laikas, skirtas išdėstyti nuosekliai įdėtuosius šriftus

  - **Data\_PerformModernSaveTimeMS:long –** laikas, skirtas moderniam įrašymui atlikti (naujas kodas)

  - **Data\_PerformPostSaveTimeMS:long –** laikas, skirtas funkcijoms po įrašymo atlikti (pranešimai, įrašų anuliavimas)

  - **Data\_PrepareForSaveTimeMS:long –** laikas, skirtas įrašymui pradėti

  - **Data\_RaiseDocumentBeforeSaveEventTimeMS:long –** laikas, skirtas BeforeSave įvykiui pakelti

  - **Data\_ReflectDocumentChangeTimeMS:long –** laikas, skirtas, kad įrašyti į UI pakeitimai būtų matomi (miniatiūrų publikavimas iš naujo ir kt.)

  - **Data\_ReportStartTimeMS:long –** laikas, skirtas baigti įrašymo telemetrijos inicijavimą

  - **Data\_ReportSuccessTimeMS:long –** laikas, skirtas sėkmingai įrašymo ataskaitai baigti

  - **Data\_ResetDirtyFlagOnErrorTimeMS:long –** laikas, skirtas dokumento klaidos neatnaujintai žymei nustatyti iš naujo

  - **Data\_SaveReason:long –** iš anksto apibrėžtas reikšmių, nurodančių įrašymo atlikimo priežastis, rinkinys (AutoSave, ToOCSTransitionSave, ToCSITransitionSave ir kt.)

  - **Data\_SaveType:long –** iš anksto nustatytų įrašymo tipo reikšmių rinkinys (SaveAs, Publish, Manual, OMSave ir kt.)

  - **Data\_SavingWithFont:bool –** ar įrašome dokumentą su naujais įdėtaisiais šriftais?

  - **Data\_ScrubClonedDocumentTimeMS:long –** laikas, skirtas asmeninio pobūdžio informacijai apie klonuotą dokumento kopiją šalinti

  - **Data\_StopwatchDuration:long –** visas veiklos laikas

  - **Data\_TransactionType:long –** ar tai Save, ar MergeAndSave operacija?

#### <a name="officepowerpointdocoperationsaveas"></a>Office.PowerPoint.DocOperation.SaveAs

Surinkti kiekvieną kartą, kai „PowerPoint“ atlieka operaciją įrašyti kaip. Apima sėkmingai arba nesėkmingai atlikto našumo metrikų ir susijusio dokumento metaduomenų įrašymo rezultato tipą. Nepavykus įrašymui, duomenys gali būti prarasti.  „Microsoft“ naudoja šiuos duomenis, kad užtikrintų, jog funkcija veikia kaip priklauso ir vartotojo turinys yra sėkmingai išlaikomas.

Renkami šių laukų duomenys:

- **Data_AddDocTelemetryResult:long** – ar šis žurnalo įrašas turi visą reikiamą dokumento telemetriją (Data_Doc_* fields)? Jei ne, kodėl?

- **Data_ClpDocHasDrmDoc:bool** – ar dokumentas turi DRM dokumentą

- **Data_ClpDocHasIdentity:bool** – ar dokumentas turi tapatybės informaciją (naudojamą gauti ir nustatyti slaptumo žymas)

- **Data_ClpDocHasSessionMetadata:bool** – ar dokumente yra veikiantys seanso slaptumo žymos metaduomenys

- **Data_ClpDocHasSpoMetadata:bool** – ar dokumente yra slaptumo žymos metaduomenys iš SPO per IMetadataCache

- **Data_ClpDocHasSpoPackage:bool** – ar dokumente yra slaptumo žymos metaduomenys iš SPO per IPackage

- **Data_ClpDocIsProtected:bool** – ar dokumentas yra apsaugotas IRM, ar ne

- **Data_ClpDocMetadataSource:int** – išvardijimas, nurodantis, iš kur gaunami slaptumo žymos metaduomenys (IRM, OPC dalies, „SharePoint“ ir t. t.)

- **Data_ClpDocNeedsUpconversion:bool** – ar dokumentai reikia konvertuoti slaptumo žymos duomenis iš custom.xml dalies

- **Data_ClpDocNumFailedSetLabels:int** – slaptumo žymų, kurių nepavyko nustatyti dokumente, skaičius

- **Data_ClpDocSessionMetadataDirty:bool** – ar dokumente yra veikiantys slaptumo žymos duomenys, kurie buvo suteršti

- **Data_ClpDocWasInTrustBoundary:bool** – ar dokumentas buvo patikimo ribose (o tai leidžia bendraautoriaus dirbti dokumentuose, apsaugotuose slaptumo žymų)

- **Data_CppUncaughtExceptionCount:long** – veiklos veikimo metu neaptiktos vietinės išimtys

- **Data_DetachedDuration:long** – veiklos atskyrimo / neveikimo trukmė

- **Data_DstDoc_AccessMode:long** – nurodo, kaip šis dokumentas buvo atidarytas (tik skaityti | skaityti ir rašyti)

- **Data_DstDoc_AssistedReadingReasons:long** – iš anksto apibrėžtas reikšmių, nurodančių dokumento atidarymo pagalbiniu skaitymo režimu priežastis, rinkinys

- **Data_DstDoc_AsyncOpenKind:long** – nurodo, ar naujo debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

- **Data_DstDoc_ChunkingType:long** – nurodo, kaip dokumentas saugomas programoje „SharePoint“

- **Data_DstDoc_EdpState:long** – dokumento įmonės duomenų apsaugos būsena

- **Data_DstDoc_Ext:string** – dokumento plėtinys

- **Data_DstDoc_Extension:string** – dokumento plėtinys

- **Data_DstDoc_FileFormat:long** – iš anksto nustatytų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

- **Data_DstDoc_Fqdn:string** – vieta, kurioje saugomas dokumentas (SharePoint.com, live.net), galima tik „Office 365“ domenams
    
- **Data_DstDoc_FqdnHash:string** – dokumento saugojimo vietos maiša

- **Data_DstDoc_IdentityTelemetryId:string** – unikalusis vartotojo GUID

- **Data_DstDoc_IdentityUniqueId:string** – unikalusis tapatybės identifikatorius, naudojamas veiksmui su bendrinamais dokumentais

- **Data_DstDoc_IOFlags:long** – šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

- **Data_DstDoc_IrmRights:long** – iš anksto nustatytų reikšmių, nurodančių, kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)
    
- **Data_DstDoc_IsCloudCollabEnabled:bool** – „teisinga“, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

- **Data_DstDoc_IsIncrementalOpen:bool** – nurodo, ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

- **Data_DstDoc_IsOcsSupported:bool** – nurodo, ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

- **Data_DstDoc_IsOpeningOfflineCopy:bool** – tikrina, ar dokumentas atidarytas iš vietinės talpyklos

- **Data_DstDoc_IsSyncBacked:bool** – nurodo, ar dokumentas atidarytas iš aplanko, naudojančio „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai
    
- **Data_DstDoc_Location:long** – iš anksto apibrėžtas dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

- **Data_DstDoc_LocationDetails:long** – iš anksto apibrėžtas išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

- **Data_DstDoc_NumberCoAuthors:long** – bendraautorių skaičius dokumento atidarymo metu

- **Data_DstDoc_PasswordFlags:long** – iš anksto apibrėžtas dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit)

- **Data_DstDoc_ReadOnlyReasons:long** – iš anksto apibrėžtas dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

- **Data_DstDoc_ResourceIdHash:string** – debesyje saugomų dokumentų išteklių identifikatoriaus maiša

- **Data_DstDoc_ServerDocId:string** – debesyje saugomų dokumentų išteklių identifikatoriaus maiša

- **Data_DstDoc_ServerProtocol:long** – iš anksto apibrėžtas reikšmių, nurodančių, kuris protokolas naudojamas kreiptis į serverį, rinkinys (Http, „Cobalt“, WOPI ir kt.)

- **Data_DstDoc_ServerType:long** – iš anksto apibrėžtas serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI)

- **Data_DstDoc_ServerVersion:long** – tikrina, ar serveryje naudojama „Office14“, „Office15“ arba „Office 16“

- **Data_DstDoc_SessionId:long** – generuotas GUID, identifikuojantis dokumento egzempliorių to paties proceso seanso metu

- **Data_DstDoc_SharePointServiceContext:string** – nepermatoma eilutė, paprastai GridManagerID.FarmID. Tinkama kliento ir serverio įvykių žurnalų koreliacijai

- **Data_DstDoc_SizeInBytes:long** – dokumento dydis baitais

- **Data_DstDoc_SpecialChars:long** – šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

- **Data_DstDoc_StorageProviderId:string** – eilutė, nurodanti dokumento saugyklos teikėją, pvz., „DropBox“

- **Data_DstDoc_StreamAvailability:long** – iš anksto apibrėžtas dokumentų srauto būsenos reikšmių rinkinys (available, permanently disabled, not available)

- **Data_DstDoc_UrlHash:string** – debesyje saugomų dokumentų visų URL maiša

- **Data_DstDoc_UsedWrsDataOnOpen:bool** – „teisinga“, jei failas buvo atidarytas palaipsniui naudojant iš anksto pagrindinio kompiuterio talpykloje saugomus WRS duomenis

- **Data_DstDoc_WopiServiceId:string** – WOPI tarnybos identifikatorius, pvz., „Dropbox“

- **Data_FileType:long** – iš anksto apibrėžtas failo vidinio tipo reikšmių rinkinys

- **Data_fLifeguarded:bool** – nurodo, ar kada dokumentui buvo naudojama apsauginė funkcija (funkcija, automatiškai taisanti dokumento klaidas nepranešant vartotojui)?

- **Data_FWebCreated:bool** – nurodo, ar šiame dokumente yra WebCreator žymė?

- **Data_SaveReason:long** – iš anksto apibrėžtas reikšmių, nurodančių įrašymo atlikimo priežastis, rinkinys (AutoSave, ToOCSTransitionSave, ToCSITransitionSave ir kt.)

- **Data_SaveType:long** – iš anksto apibrėžtas įrašymo tipo reikšmių rinkinys (SaveAs, Publish, Manual, OMSave ir kt.) 

- **Data_SrcDoc_AccessMode:long** – nurodo, kaip šis dokumentas buvo atidarytas (tik skaityti | skaityti ir rašyti)

- **Data_SrcDoc_AssistedReadingReasons:long** – iš anksto apibrėžtas reikšmių, nurodančių dokumento atidarymo pagalbiniu skaitymo režimu priežastis, rinkinys

- **Data_SrcDoc_AsyncOpenKind:long** – nurodo, ar pradinio debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

- **Data_SrcDoc_ChunkingType:long** – nurodo, kaip dokumentas saugomas programoje „SharePoint“ 

- **Data_SrcDoc_EdpState:long** – dokumento įmonės duomenų apsaugos būsena

- **Data_SrcDoc_Ext:string** – dokumento plėtinys

- **Data_SrcDoc_Extension:string** – dokumento plėtinys

- **Data_SrcDoc_FileFormat:long** – iš anksto nustatytų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

- **Data_SrcDoc_Fqdn:string** – vieta, kurioje saugomas dokumentas (SharePoint.com, live.net), galima tik „Office 365“ domenams

- **Data_SrcDoc_FqdnHash:string** – dokumento saugojimo vietos maiša

- **Data_SrcDoc_IdentityTelemetryId:string** – unikalusis vartotojo GUID

- **Data_SrcDoc_IdentityUniqueId:string** – unikalusis tapatybės identifikatorius, naudojamas veiksmui su bendrinamais dokumentais

- **Data_SrcDoc_IOFlags:long** – šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

- **Data_SrcDoc_IrmRights:long** – iš anksto nustatytų reikšmių, nurodančių, kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)

- **Data_SrcDoc_IsCloudCollabEnabled:bool** – „teisinga“, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

- **Data_SrcDoc_IsIncrementalOpen:bool** – nurodo, ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

- **Data_SrcDoc_IsOcsSupported:bool** – nurodo, ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

- **Data_SrcDoc_IsOpeningOfflineCopy:bool** – tikrina, ar dokumentas atidarytas iš vietinės talpyklos

- **Data_SrcDoc_IsSyncBacked:bool** – nurodo, ar dokumentas atidarytas iš aplanko, naudojančio „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai

- **Data_SrcDoc_Location:long** – iš anksto apibrėžtas dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

- **Data_SrcDoc_LocationDetails:long** – iš anksto apibrėžtas išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

- **Data_SrcDoc_NumberCoAuthors:long** – bendraautorių skaičius dokumento atidarymo metu

- **Data_SrcDoc_PasswordFlags:long** – iš anksto apibrėžtas dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit)

- **Data_SrcDoc_ReadOnlyReasons:long** – iš anksto apibrėžtas dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

- **Data_SrcDoc_ResourceIdHash:string** – debesyje saugomų dokumentų išteklių identifikatoriaus maiša

- **Data_SrcDoc_ServerDocId:string** – debesyje saugomų dokumentų išteklių identifikatoriaus maiša

- **Data_SrcDoc_ServerProtocol:long** – iš anksto apibrėžtas reikšmių, nurodančių, kuris protokolas naudojamas kreiptis į serverį, rinkinys (Http, „Cobalt“, WOPI ir kt.)

- **Data_SrcDoc_ServerType:long** – iš anksto apibrėžtas serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI)

- **Data_SrcDoc_ServerVersion:long** – tikrina, ar serveryje naudojama „Office14“, „Office15“ arba „Office 16“

- **Data_SrcDoc_SessionId:long** – generuotas GUID, identifikuojantis dokumento egzempliorių to paties proceso seanso metu

- **Data_SrcDoc_SharePointServiceContext:string** – nepermatoma eilutė, paprastai GridManagerID.FarmID. Tinkama kliento ir serverio įvykių žurnalų koreliacijai

- **Data_SrcDoc_SizeInBytes:long** – dokumento dydis baitais

- **Data_SrcDoc_SpecialChars:long** – šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

- **Data_SrcDoc_StorageProviderId:string** – eilutė, nurodanti dokumento saugyklos teikėją, pvz., „DropBox“

- **Data_SrcDoc_StreamAvailability:long** – iš anksto apibrėžtas dokumentų srauto būsenos reikšmių rinkinys (available, permanently disabled, not available)

- **Data_SrcDoc_UrlHash:string** – debesyje saugomų dokumentų visų URL maiša

- **Data_SrcDoc_UsedWrsDataOnOpen:bool** – „teisinga“, jei failas buvo atidarytas palaipsniui naudojant iš anksto pagrindinio kompiuterio talpykloje saugomus WRS duomenis

- **Data_SrcDoc_WopiServiceId:string** – WOPI tarnybos identifikatorius, pvz., „Dropbox“

- **Data_StopwatchDuration:long** – visas veiklos laikas

- **Data_TypeOfSaveDialog:long** – iš anksto apibrėžtas dialogo reikšmių rinkinys (RUN_SAVEAS_DLG, RUN_SAVEMEDIA_DLG, RUN_SAVEAS_VIDEO_DLG ir t. t.)

- **Data_WaitForSaveOrMergeSuccess:bool** – Įrašyti kaip pavyko, laukiama fono įrašymo arba suliejimo.
 
- **Data_WaitForSaveOrMergeTimeout:long** – Įrašyti kaip laikas baigėsi, laukiama fono įrašymo arba suliejimo.

- **DstDoc** – nauja dokumento vieta 

- **SrcDoc** – pradinė dokumento vieta


#### <a name="officepowerpointdocoperationsavelegacy"></a>Office.PowerPoint.DocOperation.SaveLegacy

Surinkti kiekvieną kartą, kai „PowerPoint“ įrašo naudodama senesnį kodo kelią. Apima sėkmingai arba nesėkmingai atlikto našumo metrikų ir susijusio dokumento metaduomenų įrašymo rezultato tipą.  Nepavykus įrašymui, duomenys gali būti prarasti.  „Microsoft“ naudoja šiuos duomenis, kad užtikrintų, jog funkcija veikia kaip priklauso ir vartotojo turinys yra sėkmingai išlaikomas.

Renkami šių laukų duomenys:

- **Data_AddDocTelemetryResult:long** – ar šis žurnalo įrašas turi visą reikiamą dokumento telemetriją (Data_Doc_* fields)? Jei ne, kodėl?

- **Data_ClpDocHasDrmDoc:bool** – ar dokumentas turi DRM dokumentą

- **Data_ClpDocHasIdentity:bool** – ar dokumentas turi tapatybės informaciją (naudojamą gauti ir nustatyti slaptumo žymas)

- **Data_ClpDocHasSessionMetadata:bool** – ar dokumente yra veikiantys seanso slaptumo žymos metaduomenys

- **Data_ClpDocHasSpoMetadata:bool** – ar dokumente yra slaptumo žymos metaduomenys iš SPO per IMetadataCache

- **Data_ClpDocHasSpoPackage:bool** – ar dokumente yra slaptumo žymos metaduomenys iš SPO per IPackage

- **Data_ClpDocIsProtected:bool** – ar dokumentas yra apsaugotas IRM, ar ne

- **Data_ClpDocMetadataSource:int** – išvardijimas, nurodantis, iš kur gaunami slaptumo žymos metaduomenys (IRM, OPC dalies, „SharePoint“ ir t. t.)

- **Data_ClpDocNeedsUpconversion:bool** – ar dokumentai reikia konvertuoti slaptumo žymos duomenis iš custom.xml dalies

- **Data_ClpDocNumFailedSetLabels:int** – slaptumo žymų, kurių nepavyko nustatyti dokumente, skaičius

- **Data_ClpDocSessionMetadataDirty:bool** – ar dokumente yra veikiantys slaptumo žymos duomenys, kurie buvo suteršti

- **Data_ClpDocWasInTrustBoundary:bool** – ar dokumentas buvo patikimo ribose (o tai leidžia bendraautoriaus dirbti dokumentuose, apsaugotuose slaptumo žymų)

- **Data_CppUncaughtExceptionCount:long** – veiklos veikimo metu neaptiktos vietinės išimtys

- **Data_DetachedDuration:long** – veiklos atskyrimo / neveikimo trukmė

- **Data_Doc_AccessMode:long** – nurodo, kaip šis dokumentas buvo atidarytas (tik skaityti | skaityti ir rašyti)

- **Data_Doc_AssistedReadingReasons:long** – iš anksto apibrėžtas reikšmių, nurodančių dokumento atidarymo pagalbiniu skaitymo režimu priežastis, rinkinys

- **Data_Doc_AsyncOpenKind:long** – nurodo, ar debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

- **Data_Doc_ChunkingType:long** – nurodo, kaip dokumentas saugomas programoje „SharePoint“

- **Data_Doc_EdpState:long** – dokumento įmonės duomenų apsaugos būsena

- **Data_Doc_Ext:string** – dokumento plėtinys

- **Data_Doc_Extension:string** – dokumento plėtinys

- **Data_Doc_FileFormat:long** – iš anksto nustatytų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

- **Data_Doc_Fqdn:string** – vieta, kurioje saugomas dokumentas (SharePoint.com, live.net), galima tik „Office 365“ domenams

- **Data_Doc_FqdnHash:string** – dokumento saugojimo vietos maiša

- **Data_Doc_IdentityTelemetryId:string** – unikalusis vartotojo GUID

- **Data_Doc_IdentityUniqueId:string** – unikalusis tapatybės identifikatorius, naudojamas veiksmui su bendrinamais dokumentais

- **Data_Doc_IOFlags:long** – šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

- **Data_Doc_IrmRights:long** – iš anksto nustatytų reikšmių, nurodančių, kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)

- **Data_Doc_IsCloudCollabEnabled:bool** – „teisinga“, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

- **Data_Doc_IsIncrementalOpen:bool** – nurodo, ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

- **Data_Doc_IsOcsSupported:bool** – nurodo, ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

- **Data_Doc_IsOpeningOfflineCopy:bool** – tikrina, ar dokumentas atidarytas iš vietinės talpyklos

- **Data_Doc_IsSyncBacked:bool** – nurodo, ar dokumentas atidarytas iš aplanko, naudojančio „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai

- **Data_Doc_Location:long** – iš anksto apibrėžtas dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

- **Data_Doc_LocationDetails:long** – iš anksto apibrėžtas išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

- **Data_Doc_NumberCoAuthors:long** – bendraautorių skaičius dokumento atidarymo metu

- **Data_Doc_PasswordFlags:long** – iš anksto apibrėžtas dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit)

- **Data_Doc_ReadOnlyReasons:long** – iš anksto apibrėžtas dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

- **Data_Doc_ResourceIdHash:string** – debesyje saugomų dokumentų išteklių identifikatoriaus maiša

- **Data_Doc_RtcType** – nurodo, kaip buvo nustatytas realaus laiko kanalas (RTC) dabartiniam failui (išjungtas, nepalaikomas, pagal pageidavimą, visada įjungta, ir t. t.).

- **Data_Doc_ServerDocId:string** – debesyje saugomų dokumentų išteklių identifikatoriaus maiša

- **Data_Doc_ServerProtocol:long** – iš anksto apibrėžtas reikšmių, nurodančių, kuris protokolas naudojamas kreiptis į serverį, rinkinys (Http, „Cobalt“, WOPI ir kt.)

- **Data_Doc_ServerType:long** – iš anksto apibrėžtas serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI) 

- **Data_Doc_ServerVersion:long** – tikrina, ar serveryje naudojama „Office14“, „Office15“ arba „Office 16“

- **Data_Doc_SessionId:long** – generuotas GUID, identifikuojantis dokumento egzempliorių to paties proceso seanso metu

- **Data_Doc_SharePointServiceContext:string** – nepermatoma eilutė, paprastai GridManagerID.FarmID. Tinkama kliento ir serverio įvykių žurnalų koreliacijai

- **Data_Doc_SizeInBytes:long** – dokumento dydis baitais

- **Data_Doc_SpecialChars:long** – šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

- **Data_Doc_StorageProviderId:string** – eilutė, nurodanti dokumento saugyklos teikėją, pvz., „DropBox“

- **Data_Doc_StreamAvailability:long** – iš anksto apibrėžtas dokumentų srauto būsenos reikšmių rinkinys (available, permanently disabled, not available)

- **Data_Doc_UrlHash:string** – debesyje saugomų dokumentų visų URL maiša

- **Data_Doc_UsedWrsDataOnOpen:bool** – „teisinga“, jei failas buvo atidarytas palaipsniui naudojant iš anksto pagrindinio kompiuterio talpykloje saugomus WRS duomenis

- **Data_Doc_WopiServiceId:string** – WOPI tarnybos identifikatorius, pvz., „Dropbox“

- **Data_DstDoc_AccessMode:long** – nurodo, kaip šis dokumentas buvo atidarytas (tik skaityti | skaityti ir rašyti)

- **Data_DstDoc_AssistedReadingReasons:long** – iš anksto apibrėžtas reikšmių, nurodančių dokumento atidarymo pagalbiniu skaitymo režimu priežastis, rinkinys

- **Data_DstDoc_AsyncOpenKind:long** – nurodo, ar naujo debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

- **Data_DstDoc_ChunkingType:long** – nurodo, kaip dokumentas saugomas programoje „SharePoint“

- **Data_DstDoc_EdpState:long** – dokumento įmonės duomenų apsaugos būsena

- **Data_DstDoc_Ext:string** – dokumento plėtinys

- **Data_DstDoc_Extension:string** – dokumento plėtinys

- **Data_DstDoc_FileFormat:long** – iš anksto nustatytų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

- **Data_DstDoc_Fqdn:string** – vieta, kurioje saugomas dokumentas (SharePoint.com, live.net), galima tik „Office 365“ domenams
    
- **Data_DstDoc_FqdnHash:string** – dokumento saugojimo vietos maiša

- **Data_DstDoc_IdentityTelemetryId:string** – unikalusis vartotojo GUID

- **Data_DstDoc_IdentityUniqueId:string** – unikalusis tapatybės identifikatorius, naudojamas veiksmui su bendrinamais dokumentais

- **Data_DstDoc_IOFlags:long** – šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

- **Data_DstDoc_IrmRights:long** – iš anksto nustatytų reikšmių, nurodančių, kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)

- **Data_DstDoc_IsCloudCollabEnabled:bool** – „teisinga“, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

- **Data_DstDoc_IsIncrementalOpen:bool** – nurodo, ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

- **Data_DstDoc_IsOcsSupported:bool** – nurodo, ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

- **Data_DstDoc_IsOpeningOfflineCopy:bool** – tikrina, ar dokumentas atidarytas iš vietinės talpyklos

- **Data_DstDoc_IsSyncBacked:bool** – nurodo, ar dokumentas atidarytas iš aplanko, naudojančio „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai

- **Data_DstDoc_Location:long** – iš anksto apibrėžtas dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

- **Data_DstDoc_LocationDetails:long** – iš anksto apibrėžtas išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

- **Data_DstDoc_NumberCoAuthors:long** – bendraautorių skaičius dokumento atidarymo metu

- **Data_DstDoc_PasswordFlags:long** – iš anksto apibrėžtas dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit)

- **Data_Doc_ReadOnlyReasons:long** – iš anksto apibrėžtas dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

- **Data_DstDoc_ResourceIdHash:string** – debesyje saugomų dokumentų išteklių identifikatoriaus maiša

- **Data_DstDoc_ServerDocId:string** – debesyje saugomų dokumentų išteklių identifikatoriaus maiša

- **Data_DstDoc_ServerProtocol:long** – iš anksto apibrėžtas reikšmių, nurodančių, kuris protokolas naudojamas kreiptis į serverį, rinkinys (Http, „Cobalt“, WOPI ir kt.)

- **Data_DstDoc_ServerType:long** – iš anksto apibrėžtas serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI)

- **Data_DstDoc_ServerVersion:long** – tikrina, ar serveryje naudojama „Office14“, „Office15“ arba „Office 16“

- **Data_DstDoc_SessionId:long** – generuotas GUID, identifikuojantis dokumento egzempliorių to paties proceso seanso metu

- **Data_DstDoc_SharePointServiceContext:string** – nepermatoma eilutė, paprastai GridManagerID.FarmID. Tinkama kliento ir serverio įvykių žurnalų koreliacijai

- **Data_DstDoc_SizeInBytes:long** – dokumento dydis baitais

- **Data_DstDoc_SpecialChars:long** – šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

- **Data_DstDoc_StorageProviderId:string** – eilutė, nurodanti dokumento saugyklos teikėją, pvz., „DropBox“

- **Data_DstDoc_StreamAvailability:long** – iš anksto apibrėžtas dokumentų srauto būsenos reikšmių rinkinys (available, permanently disabled, not available)

- **Data_DstDoc_UrlHash:string** – debesyje saugomų dokumentų visų URL maiša

- **Data_DstDoc_UsedWrsDataOnOpen:bool** – „teisinga“, jei failas buvo atidarytas palaipsniui naudojant iš anksto pagrindinio kompiuterio talpykloje saugomus WRS duomenis

- **Data_DstDoc_WopiServiceId:string** – WOPI tarnybos identifikatorius, pvz., „Dropbox“

- **Data_FileType:long** – iš anksto apibrėžtas failo vidinio tipo reikšmių rinkinys

- **Data_fLifeguarded:bool** – nurodo, ar kada dokumentui buvo naudojama apsauginė funkcija (funkcija, automatiškai taisanti dokumento klaidas nepranešant vartotojui)?

- **Data_SaveReason:long** – iš anksto apibrėžtas reikšmių, nurodančių įrašymo atlikimo priežastis, rinkinys (AutoSave, ToOCSTransitionSave, ToCSITransitionSave ir kt.)

- **Data_SaveType:long** – iš anksto apibrėžtas įrašymo tipo reikšmių rinkinys (SaveAs, Publish, Manual, OMSave ir kt.)

- **Data_SrcDoc_AccessMode:long** – nurodo, kaip šis dokumentas buvo atidarytas (tik skaityti | skaityti ir rašyti)

- **Data_SrcDoc_AssistedReadingReasons:long** – iš anksto apibrėžtas reikšmių, nurodančių dokumento atidarymo pagalbiniu skaitymo režimu priežastis, rinkinys

- **Data_SrcDoc_AsyncOpenKind:long** – nurodo, ar pradinio debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

- **Data_SrcDoc_ChunkingType:long** – nurodo, kaip dokumentas saugomas programoje „SharePoint“

- **Data_SrcDoc_EdpState:long** – dokumento įmonės duomenų apsaugos būsena

- **Data_SrcDoc_Ext:string** – dokumento plėtinys

- **Data_SrcDoc_Extension:string** – dokumento plėtinys

- **Data_SrcDoc_FileFormat:long** – iš anksto nustatytų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

- **Data_SrcDoc_Fqdn:string** – vieta, kurioje saugomas dokumentas (SharePoint.com, live.net), galima tik „Office 365“ domenams

- **Data_SrcDoc_FqdnHash:string** – dokumento saugojimo vietos maiša 

- **Data_SrcDoc_IdentityTelemetryId:string** – unikalusis vartotojo GUID

- **Data_SrcDoc_IdentityUniqueId:string** – unikalusis tapatybės identifikatorius, naudojamas veiksmui su bendrinamais dokumentais

- **Data_SrcDoc_IOFlags:long** – šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

- **Data_SrcDoc_IrmRights:long** – iš anksto nustatytų reikšmių, nurodančių, kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)
    
- **Data_SrcDoc_IsCloudCollabEnabled:bool** – „teisinga“, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

- **Data_SrcDoc_IsIncrementalOpen:bool** – nurodo, ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

- **Data_SrcDoc_IsOcsSupported:bool** – nurodo, ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

- **Data_SrcDoc_IsOpeningOfflineCopy:bool** – tikrina, ar dokumentas atidarytas iš vietinės talpyklos

- **Data_SrcDoc_IsSyncBacked:bool** – nurodo, ar dokumentas atidarytas iš aplanko, naudojančio „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai

- **Data_SrcDoc_Location:long** – iš anksto apibrėžtas dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

- **Data_SrcDoc_LocationDetails:long** – iš anksto apibrėžtas išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

- **Data_SrcDoc_NumberCoAuthors:long** – bendraautorių skaičius dokumento atidarymo metu

- **Data_SrcDoc_PasswordFlags:long** – iš anksto apibrėžtas dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit)

- **Data_SrcDoc_ReadOnlyReasons:long** – iš anksto apibrėžtas dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

- **Data_SrcDoc_ResourceIdHash:string** – debesyje saugomų dokumentų išteklių identifikatoriaus maiša

- **Data_SrcDoc_ServerDocId:string** – debesyje saugomų dokumentų išteklių identifikatoriaus maiša

- **Data_SrcDoc_ServerProtocol:long** – iš anksto apibrėžtas reikšmių, nurodančių, kuris protokolas naudojamas kreiptis į serverį, rinkinys (Http, „Cobalt“, WOPI ir kt.)

- **Data_SrcDoc_ServerType:long** – iš anksto apibrėžtas serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI)

- **Data_SrcDoc_ServerVersion:long** – tikrina, ar serveryje naudojama „Office14“, „Office15“ arba „Office 16“

- **Data_SrcDoc_SessionId:long** – generuotas GUID, identifikuojantis dokumento egzempliorių to paties proceso seanso metu

- **Data_SrcDoc_SharePointServiceContext:string** – nepermatoma eilutė, paprastai GridManagerID.FarmID. Tinkama kliento ir serverio įvykių žurnalų koreliacijai

- **Data_SrcDoc_SizeInBytes:long** – dokumento dydis baitais

- **Data_SrcDoc_SpecialChars:long** – šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

- **Data_SrcDoc_StorageProviderId:string** – eilutė, nurodanti dokumento saugyklos teikėją, pvz., „DropBox“

- **Data_SrcDoc_StreamAvailability:long** – iš anksto apibrėžtas dokumentų srauto būsenos reikšmių rinkinys (available, permanently disabled, not available)

- **Data_SrcDoc_UrlHash:string** – debesyje saugomų dokumentų visų URL maiša

- **Data_SrcDoc_UsedWrsDataOnOpen:bool** – „teisinga“, jei failas buvo atidarytas palaipsniui naudojant iš anksto pagrindinio kompiuterio talpykloje saugomus WRS duomenis

- **Data_SrcDoc_WopiServiceId:string** – WOPI tarnybos identifikatorius, pvz., „Dropbox“

- **Data_StopwatchDuration:long** – visas veiklos laikas

- **Data_TypeOfSaveDialog:long** – iš anksto apibrėžtas dialogo reikšmių rinkinys (RUN_SAVEAS_DLG, RUN_SAVEMEDIA_DLG, RUN_SAVEAS_VIDEO_DLG ir t. t.)

- **Doc** – dabartinis dokumentas įrašymui

- **DstDoc** – nauja dokumento vieta (kai naudojama funkcija SaveAs)

- **SrcDoc** – pradinė dokumento vieta (kai naudojama funkcija SaveAs)


#### <a name="officepowerpointpptiosrehearseview"></a>Office.PowerPoint.PPT.IOS.RehearseView 

Šis įvykis nurodo, kad vartotojas sustabdė repeticijos seansą. Duomenys naudojami kartu su Office.PowerPoint.IOS.Android.RehearseView.StartSession, kaip pirmasis bet kokių gedimų arba klaidų, su kuriomis susiduria vartotojas, indikatorius.  
 
Renkami šių laukų duomenys:

- **ConnectionCreationTime** – tarnybų ryšiams kurti reikalingas laikas.

- **CountDownAlertTime** – laikas, kuriuo buvo rodomas atgalinės atskaitos įspėjimas.

- **CountdownInitTime–** – laikas tarp skaidrių demonstravimo užbaigimo ir atgalinės atskaitos pradėjimo.

- **CritiqueSummary** – santrauka, kokius skaičius pamatė visi kritikos vartotojai.

- **ExitEventCode** – kodas, skirtas nustatyti, pagal kurį scenarijų vartotojas išeina iš repeticijos seanso, nesvarbu, ar tai buvo klaidos scenarijus, ar sėkmingas išėjimas.

- **FRETime** – laikas nuo FRE ekrano pradėjimo rodyti iki atmetimo, inicijuoto vartotojo.

- **MicrophonePermissionTime** – laikas, kurį buvo rodomas mikrofono įspėjimas iki vartotojas pasirinko vieną iš parinkčių.

- **PauseRehearsingCount** – skaičius, kiek kartų vartotojas spustelėjo pristabdyti repeticijas.

- **RehearsalInitTime** repeticijos inicijavimo trukmė.

- **ResumeRehearsingCount** – skaičius, kiek kartų vartotojas spustelėjo tęsti repeticijas.

- **Sessionid** – tai kalbos pagrindinių durų seanso ID.  Tai naudojama derinti paslaugų žurnalus.

- **SlideshowViewLoadTime** – skaidrių demonstracijos įkėlimo laikas.


#### <a name="officepowerpointpptiosrehearseviewrehearsalsummarypage"></a>Office.PowerPoint.PPT.IOS.RehearseView.RehearsalSummaryPage

Įvykis paleidžiamas, kai santraukos puslapis baigtas įkelti. Šis įvykis padeda mums užfiksuoti suvestinės puslapio rezultatus. Jis nurodo, kiek laiko užtrunka, kol reikia įkelti puslapį, kad būtų galima įkelti į klientą. Būtina išlaikyti funkcijų efektyvumą.  

Renkami šių laukų duomenys: 

- **PayloadCreationTime** – tai laikas, užfiksuotas milisekundėmis, kurio reikėjo, kad būtų sukurtas paketo turinys.  

- **PostUrlCallTime** – tai laikas, užfiksuotas milisekundėmis, kurio reikėjo, kad būtų nusiųstas Url skelbimo iškvietimas. 

- **RehearseSessionId** – tai kalbos pagrindinių durų seanso ID. Galime jį naudoti, kad galėtumėte derinti paslaugų žurnalus.  

- **SummaryPageErrorReceived** – tai Bulio logikos reikšmė, kuri nurodo, ar suvestinės puslapis buvo gautas, ar įvyko klaida.

- **SummaryPageHtmlLoadTime** – tai laikas, užfiksuotas sekundėmis, kurio prireikė įkelti summarypageHtml. 

- **SummaryPageLoadStartTime** – tai laikas užfiksuotas sekundėmis, kurio prireikė gauti pirmą atsakymą iš serverio. 

- **SummaryPageLoadTime** – tai laikas, kurio prireikė norint įkelti suvestinės puslapį. Tai apima naudingosios apkrovos kūrimo laiką. 

- **ThumbnailsCount** – tai bendras miniatiūrų, kurios bus suvestinės puslapio dalimi, skaičius. 


#### <a name="officepowerpointpptiosrehearseviewstartsession"></a>Office.PowerPoint.PPT.IOS.RehearseView.StartSession 
 
Įvykis paleidžiamas, kai vartotojas spustelėja pradėti seansą. Šis įvykis padeda mums užfiksuoti, kiek vartotojų naudoja pranešėjo pagalbinę priemonę „iOS“. Kartu su „Office.PowerPoint.PPT.Android.RehearseView“ praneš mums, kiek vartotojų sėkmingai baigė repeticijos seansą ir kiek negalėjo. Tai mūsų pirmasis funkcijos gedimų arba klaidų indikatorius.

Renkami šių laukų duomenys:

- Nėra

#### <a name="officepowerpointpptmacshellprintinfo"></a>Office.PowerPoint.PPT.Mac.Shell.PrintInfo

Renkama, kai PDF eksportavimo operacija baigta, ir joje yra informacijos apie operacijos sėkmę. Ši informacija yra labai svarbi norint nustatyti, ar PDF eksportavimo operacijos sėkmingai vykdomos mūsų programoje.

Renkami šių laukų duomenys:

- **Data_ExportAsPDFSucceed** – Bulio logika, nurodanti, ar PDF eksportavimas buvo sėkmingas.

#### <a name="officepowerpointpptsharedrehearseviewrehearseclicked"></a>Office.PowerPoint.PPT.Shared.RehearseView.RehearseClicked

Šis įvykis fiksuoja, kai spustelimas RehearseWithCoach.  Šis įvykis naudojamas analizuojant pastebėtą funkcijos piltuvėlį. Šis įvykis kartu su išbandytu ir išsaugotu įvykiu padeda mums išsiaiškinti, ar vartotojai nukrenta iš piltuvėlio. Tai padeda mums išlaikyti funkcijos sveikatą.

Renkami šių laukų duomenys:

- Nėra


#### <a name="officepowerpointpptsharedslideshowfailure"></a>Office.PowerPoint.PPT.Shared.SlideShow.Failure

Informacijos apie trikti per skaidrių demonstravimą, kuris yra svarbiausia „PowerPoint“ funkcija, rinkimas. „Microsoft“ skaidrių demonstravimo metu renka informaciją apie klaidos įvykimą, kad padėtų tobulinti naudotojo patirtį. „Microsoft“ šiuos duomenis naudoja gauti diagnostinę informaciją apie tai, kur klaida įvyksta, kai vartotojas naudoja skaidrių demonstravimą.

Renkami šių laukų duomenys:

- **CountOArtErrors** – bendras OArt klaidų skaičius

- **CountOtherErrors** – bendras kitų klaidų skaičius

- **CountPPTErrors** – bendras PPT klaidų skaičius

- **CountSlideShowErrors** – bendras skaidrių demonstravimo klaidų skaičius

- **FirstOArtError** – pirma klaida, įvykusi OArt

- **FirstOtherError** – pirma klaida, įvykusi kitoje srityje

- **FirstPPTError** – pirma klaida, įvykusi PPT

- **FirstSlideShowError** – pirma klaida, įvykusi skaidrių demonstravimo metu

    
#### <a name="officepowerpointrunprintoperation"></a>Office.PowerPoint.RunPrintOperation

Renkama, kai PDF spausdinimo operacija baigta, ir joje yra informacijos apie maketo tipą, skaidrių numerių naudojimą bei apie operacijos sėkmę. Ši informacija yra labai svarbi norint nustatyti, kaip ar PDF spausdinimo operacijos sėkmingai vykdomos mūsų programoje.

Renkami šių laukų duomenys:

- **Data_PrintWithSlideNumbers** – Bulio logika, nurodanti, ar vartotojas spausdindamas naudoja skaidrių numerius.

- **Data_SavePrintLayoutType** – spausdinimo maketo tipas tuo metu, kai pradedama spausdinti arba eksportuoti.

- **Data_Success** – Bulio logika, nurodanti, ar spausdinimas buvo sėkmingas.


#### <a name="officeprojectprojectfilesave"></a>Office.Project.ProjectFileSave

Projektas įrašo failą. Šis įvykis nurodo projekto įrašymą. Tai leidžia „Microsoft“ vertinti sėkmingą projekto failo įrašymo atlikimą, būtiną dokumento duomenų praradimui išvengti.

Renkami šių laukų duomenys:

  - **Data\_TriggerTime** – įrašymo laikas

  - **Data\_FileType** – failo tipas, kuriuo projektas buvo įrašytas kaip
 
#### <a name="officesessionactivitystart"></a>Office.Session.Activity.Start

Leidžia mums žinoti, kada buvo paleistas srautinio duomenų siųstuvo seansas.  Naudojama funkcijos sveikatai užtikrinti ir stebėti. Šis įvykis generuojamas „Microsoft“ srautinio duomenų siųstuvo, skirto „Excel“ papildiniui.

Renkami šių laukų duomenys:

- **Activity_Name** – „Session“ veiklos pavadinimas

- **Activity_CV** – ID, skirtas nustatyti įvykius ryšio seanso metu

- **Activity_StartStopType** – paleidimas

- **Activity_DateTimeTicks** – veiklos data ir laikas

#### <a name="officesessionactivitystop"></a>Office.Session.Activity.Stop

Leidžia mums žinoti, kada srautinis duomenų siųstuvas seansas sustojo. Naudojama funkcijos sveikatai užtikrinti ir stebėti. Šis įvykis generuojamas „Microsoft“ srautinio duomenų siųstuvo, skirto „Excel“ papildiniui.

Renkami šių laukų duomenys:

- **Activity_Name** – „Session“ veiklos pavadinimas

- **Activity_CV** – ID, skirtas nustatyti įvykius ryšio seanso metu

- **Activity_StartStopType** – stabdymas

- **Activity_DateTimeTicks** – veiklos data ir laikas

#### <a name="officestreamdeviceactivitystart"></a>Office.StreamDevice.Activity.Start

Leidžia mums žinoti, ar duomenų srauto šaltinio paleidimas buvo sėkmingas.   Naudojama funkcijos sveikatai užtikrinti ir stebėti. Šis įvykis generuojamas „Microsoft“ srautinio duomenų siųstuvo, skirto „Excel“ papildiniui.

Renkami šių laukų duomenys:

- **Datasource_Type** – nuosekliojo įrenginio arba taikomosios programos tarnybos informacija

- **DataSource_Name** – prijungto duomenų šaltinio pavadinimas

- **Activity_Name** – veiklos „StreamDeviceData“ arba „StreamFileData“ pavadinimas

- **Activity_CV** – ID, skirtas nustatyti įvykius ryšio seanso metu

- **Activity_StartStopType** – paleidimas

- **Activity_DateTimeTicks** – veiklos data ir laikas

#### <a name="officestreamdeviceactivitystop"></a>Office.StreamDevice.Activity.Stop

Leidžia mums žinoti, ar duomenų srauto šaltinio stabdymas buvo sėkmingas.   Naudojama funkcijos sveikatai užtikrinti ir stebėti. Šis įvykis generuojamas „Microsoft“ srautinio duomenų siųstuvo, skirto „Excel“ papildiniui.

Renkami šių laukų duomenys:

- **Datasource_Type** – nuosekliojo įrenginio arba taikomosios programos tarnybos informacija

- **DataSource_Name** – prijungto duomenų šaltinio pavadinimas

- **Activity_Name** – veiklos „StreamDeviceData“ arba „StreamFileData“ pavadinimas

- **Activity_CV** – ID, skirtas nustatyti įvykius ryšio seanso metu

- **Activity_StartStopType** – stabdymas

- **Activity_DateTimeTicks** – veiklos data ir laikas

#### <a name="officetargetedmessagingabexperimentmessagetrigger"></a>Office.TargetedMessaging.ABExperimentMessageTrigger

Seka, kiek vartotojų gavo BizBar ir dinaminės matomosios tinklalapio srities pranešimus iš TargetedMessagingService (TMS). Šie duomenys yra labai svarbūs suprasti, kokius gauna laiškus vartotojai ir kokioje darbinėje srityje, kad galėtume užtikrinti, jog jiems netrūksta jokių pranešimų, kurie gali būti labai svarbūs tolimesniam produkto naudojimui. Taip pat jie reikalingi tiksliai išmatuoti savo bandymų per TMS vykdomų kampanijų atlikimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_Surface** – darbinės srities, kuriai skirtas šios tarnybos pristatytas pranešimas, pavadinimas

  - **Data\_Flight** – ECS/CT testuojamo varianto identifikatorius, naudojamas pranešimui siųsti

  - **Data\_CampaignId** – kampanijos, kurios dalis yra šis pranešimas, identifikatorius

  - **Data\_MessageId** – šios tarnybos, pristačiusios pranešimą, identifikatorius

  - **Data\_TransactionId** – šios operacijos su tarnyba identifikatorius

  - **Data\_TriggerPoint** – veiksmas, kuriame šis įvykis buvo užfiksuotas (gauto pranešimo palyginimas su rodomu)

#### <a name="officetextfontpickerfontselectedwin32"></a>Office.Text.FontPickerFontSelected.Win32

Šis įvykis nurodo, ar atsisiųstas šriftas buvo teisingai sugeneruotas. Naudojama nurodyti, ar šrifto atsisiuntimas atliktas teisingai.

Renkami šių laukų duomenys:

  - **Font name (Data\_Font)** – šrifto parinkiklyje pasirinkto šrifto pavadinimas

  - **User click (Data\_FClick)** – ar vartotojas naudoja pelę elementui pasirinkti

#### <a name="officetextresourceclientrequestresourceinternal"></a>Office.Text.ResourceClient.RequestResourceInternal

Šis įvykis nurodo, ar šriftas buvo teisingai atsisiųstas. Naudojama nurodyti, ar atsisiųsto šrifto generavimas atliktas sėkmingai.

Renkami šių laukų duomenys:

  - **Data\_FontToken** – ištekliaus failo vardas bus įrašytas kaip

  - **Data\_HTTPResult** – HTTP užklausos rezultatas

  - **Data\_HTTPStatusCode** – HTTP kodas, grąžintas iš HTTP užklausos

  - **Data\_isInternetOn** – ar turėjome ryšį, kai bandėme nuskaityti išteklių

  - **Data\_RequestUrl** – CDN ištekliaus URL, kurį bandome gauti



#### <a name="officetranslatordocumenttranslated"></a>Office.Translator.DocumentTranslated

Renka informaciją, ar viso dokumento vertimas, kurį vartotojas įjungė Translator SDX, atliktas sėkmingai. Labai svarbu įvertinti vertimo funkcijos sveikatą ir reaguoti į bet kokius sutrikimus, kurie gali atsirasti. Stebi „verčiamo dokumento“ scenarijaus sveikatą programoje „Word“.

Renkami šių laukų duomenys:

- **Data.actionSource** – nurodo, kaip buvo paleistas vertimo pasirinkimas

- **Data.bodyBackgroundColor** – „Office“ temos konteinerio fono spalva

- **Data.bodyForegroundColor** – „Office“ temos konteinerio priekinio plano spalva

- **Data.browserLang** – dabartinė naršyklės rodoma kalba

- **Data.browserOnline** – nebenaudojamas

- **Data.browserPlatform** – naršyklės platforma

- **Data.browserUserAgent** – naršyklės vartotojo agentas

- **Data.colorDepth** – sistemos spalvos gylis

- **Data.contentLanguage** – aptikta verstino turinio kalba

- **Data.controlBackgroundColor** – „Office“ temos valdiklio fono spalva

- **Data.controlBackgroundColor** – „Office“ temos valdiklio priekinio plano spalva

- **Data.correlationId** – tarnybai siųstos užklausos unikalusis identifikatorius

- **Data.crossSessionId** – unikalusis vartotojo identifikatorius

- **Data.crossSessionStartTime** – vertimo seanso pradžios UTC laiko žyma

- **Data.currentTime** – šio telemetrijos pranešimo išsiuntimo UTC laiko žyma

- **Data.displayLanguage** – rodoma „Office“ kalba

- **Data.documentSourceLang** – dokumento turinio kalba

- **Data.documentTargetLang** – kalba, į kurią bus išverstas dokumentas

- **Data.Environment** – tarnybos aplinka, kuriai išsiųsta užklausa

- **Data.errorMessage** – tarnybos pateiktas klaidos pranešimas

- **Data.eventActionType** – telemetrijos įvykio tipas

- **Data.eventTagId** – kodo eilutės, sukūrusios šį telemetrijos pranešimą, unikalusis identifikatorius.

- **Data.flights** – įgalinti testuojami variantai

- **Data.fileSize** – „Word“ failo, skirto versti, dydis

- **Data.fileSource** – „Word“ failo laikymo vieta (neprisijungus, internete)

- **Data.fileType** – „Word“ failo plėtinys

- **Data.innerHeight“** – šoninės srities konteinerio aukštis

- **Data.innerWidth“** – šoninės srities konteinerio plotis

- **Data.lookupSourceLang** – nenaudojama dokumentui versti

- **Data.lookupTargetLang** – nenaudojama dokumentui versti

- **Data.officeHost** – „Office“ taikomoji programa, esanti šoninėje srityje

- **Data.officeLocale** – „Office“ vartotojo kalba

- **Data.officeMachineId** – unikalusis įrenginio identifikatorius

- **Data.officePlatform** – įrenginio platforma

- **Data.officeSessionId** – „Office“ seanso identifikatorius

- **Data.officeUserId** – „Office“ vartotojo unikalusis identifikatorius

- **Data.officeVersion** – „Office“ versija

- **Data.pageXOffset** – kairėje šoninėje srityje esančios šoninės srities horizontalios slinkties padėtis

- **Data.pageYOffset** – viršutinėje šoninėje srityje esančios šoninės srities vertikalios slinkties padėtis

- **Data.pixelDepth** – ekrano spalvų skiriamoji geba

- **Data.responseCode** – iš tarnybos gautas atsakymo į užklausą kodas

- **Data.responseTime** – praėjęs užklausos laikas 

- **Data.resultType** – užklausos rezultatas

- **Data.screenHeight** – ekrano aukštis pikseliais

- **Data.screenLeft** – lango horizontalioji koordinatė ekrano atžvilgiu

- **Data.screenTop** – lango vertikalioji koordinatė ekrano atžvilgiu

- **Data.screenWidth** – ekrano plotis pikseliais

- **Data.selectedTab** – pasirinktas skirtukas: Pasirinkimas arba Dokumentas

- **Data.serverUrl** – vertimo tarnybos URL

- **Data.sessionId** – šoninės srities seanso identifikatorius

- **Data.sessionStartTime** – vertimo seanso pradžios UTC laiko žyma

- **Data.sourceTextHash** – verstino teksto maiša

- **Data.sourceTextLength** – verstino teksto ilgis

- **Data.sourceTextWords** – žodžių skaičius verstiname tekste

- **Data.warningMessage** – tarnybos pateiktas įspėjimo pranešimas


#### <a name="officetranslatortexttranslated"></a>Office.Translator.TextTranslated

Renka informaciją apie tai, ar pasirinktos dalies vertimas, kurį vartotojas įjungė Translator SDX, atliktas sėkmingai. Labai svarbu įvertinti vertimo funkcijos sveikatą ir reaguoti į bet kokius sutrikimus, kurie gali atsirasti. Naudojama stebėti „Excel“, „PowerPoint“ ir „Word“ scenarijaus „Vertimo pasirinkimas“ sveikatą.

Renkami šių laukų duomenys:

- **Data.actionSource** – nurodo, kaip buvo paleistas vertimo pasirinkimas

- **Data.bodyBackgroundColor** – „Office“ temos konteinerio fono spalva

- **Data.bodyForegroundColor** – „Office“ temos konteinerio priekinio plano spalva

- **Data.browserLang** – dabartinė naršyklės rodoma kalba

- **Data.browserOnline** – nebenaudojamas

- **Data.browserPlatform** – naršyklės platforma

- **Data.browserUserAgent** – naršyklės vartotojo agentas

- **Data.colorDepth** – sistemos spalvos gylis

- **Data.contentLanguage** – aptikta verstino turinio kalba

- **Data.controlBackgroundColor** – „Office“ temos valdiklio fono spalva

- **Data.controlBackgroundColor** – „Office“ temos valdiklio priekinio plano spalva

- **Data.correlationId** – tarnybai siųstos užklausos unikalusis identifikatorius

- **Data.crossSessionId** – unikalusis vartotojo identifikatorius

- **Data.crossSessionStartTime** – vertimo seanso pradžios UTC laiko žyma

- **Data.currentTime** – šio telemetrijos pranešimo išsiuntimo UTC laiko žyma

- **Data.displayLanguage** – rodoma „Office“ kalba

- **Data.documentSourceLang** – nenaudojama pasirinkimui

- **Data.documentTargetLang** – nenaudojama vertimo pasirinkimui

- **Data.Environment** – tarnybos aplinka, kuriai išsiųsta užklausa

- **Data.errorMessage** – tarnybos pateiktas klaidos pranešimas

- **Data.eventActionType** – telemetrijos įvykio tipas

- **Data.eventTagId“** – kodo eilutės, sukūrusios šį telemetrijos pranešimą, unikalusis identifikatorius

- **Data.flights** – įgalinti testuojami variantai

- **Data.innerHeight** – šoninės srities konteinerio aukštis

- **Data.innerWidth** – šoninės srities konteinerio plotis

- **Data.lookupSourceLang** – dabartinio pažymėto teksto kalba

- **Data.lookupTargetLang** – kalba, į kurią bus verčiamas pažymėtas tekstas

- **Data.officeHost** – „Office“ taikomoji programa, esanti šoninėje srityje

- **Data.officeLocale** – „Office“ vartotojo kalba

- **Data.officeMachineId** – unikalusis įrenginio identifikatorius

- **Data.officePlatform** – įrenginio platforma

- **Data.officeSessionId** – „Office“ seanso identifikatorius

- **Data.officeUserId** – „Office“ vartotojo unikalusis identifikatorius

- **Data.officeVersion** – „Office“ versija

- **Data.pageXOffset** – kairėje šoninėje srityje esančios šoninės srities horizontalios slinkties padėtis

- **Data.pageYOffset** – viršutinėje šoninėje srityje esančios šoninės srities vertikalios slinkties padėtis

- **Data.pixelDepth** – ekrano spalvų skiriamoji geba

- **Data.responseCode** – iš tarnybos gautas atsakymo į užklausą kodas

- **Data.responseTime** – praėjęs užklausos laikas

- **Data.resultType** – užklausos rezultatas

- **Data.screenHeight** – ekrano aukštis pikseliais

- **Data.screenLeft** – lango horizontalioji koordinatė ekrano atžvilgiu

- **Data.screenTop** – lango vertikalioji koordinatė ekrano atžvilgiu

- **Data.screenWidth** – ekrano plotis pikseliais

- **Data.selectedTab** – pasirinktas skirtukas: Pasirinkimas arba Dokumentas

- **Data.serverUrl** – vertimo tarnybos URL

- **Data.sessionId** – šoninės srities seanso identifikatorius

- **Data.sessionStartTime** – vertimo seanso pradžios UTC laiko žyma

- **Data.sourceTextHash** – verstino teksto maiša

- **Data.sourceTextLength** – verstino teksto ilgis

- **Data.sourceTextWords** – žodžių skaičius verstiname tekste

- **Data.warningMessage** – tarnybos pateiktas įspėjimo pranešimas


#### <a name="officeuxacccheckeracccheckerfinalviolationcountperrule"></a>Office.UX.AccChecker.AccCheckerFinalViolationCountPerRule

Šis įvykis paleidžiamas, kai pranešama apie šiuo metu atidaryto dokumento pritaikymo neįgaliesiems triktis. Šis įvykis, pagal taisyklę, pateikia pritaikymo neįgaliesiems pažeidimus (klaidas, įspėjimus ir patarimus) atidaryto dokumento seanso pradžioje ir pabaigoje.  Šis įvykis, pagal taisyklę, naudojamas fiksuoti pritaikymo neįgaliesiems pažeidimų skaičių (klaidas, įspėjimus ir patarimus) atidaryto dokumento seanso pradžioje ir pabaigoje.

Informacija apie pažeidimų skaičių pagal taisyklę padeda „Microsoft“ nustatyti, kurios pritaikymo neįgaliesiems problemos dažniausiai pasitaiko „Office“ dokumentuose. Tai padeda sutvarkyti problemas ir skatina kurti integruotą aplinką žmonėms su negalia darbo vietose ir klasėse.

Renkami šių laukų duomenys:

- **Data_FinalCount_RuleID_0** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_FinalCount_RuleID_1** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_FinalCount_RuleID_2** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_FinalCount_RuleID_3** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_FinalCount_RuleID_4** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_FinalCount_RuleID_5** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_FinalCount_RuleID_6** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_FinalCount_RuleID_7** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_FinalCount_RuleID_8** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_FinalCount_RuleID_9** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_FinalCount_RuleID_10** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_FinalCount_RuleID_11** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_FinalCount_RuleID_12** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_FinalCount_RuleID_13** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_FinalCount_RuleID_14** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_FinalCount_RuleID_15** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_FinalCount_RuleID_16** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_FinalCount_RuleID_17** – taisyklės ID pažeidimų skaičius = n kuris išlieka, kai paskutinį kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_0** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_1** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_2** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_3** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_4** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_5** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_6** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_7** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_8** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_9** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_10** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_11** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_12** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_13** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_14** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_15** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_16** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **Data_InitialCount_RuleID_17** - taisyklės ID pažeidimų skaičius = n rastas, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **FinalDocID** - nuskaityto dokumento galutinis DokumentoID

- **FinalDocUrlHash** - nuskaityto dokumento galutinis DokumentoURLGrotelės
    
- **FinalDocID** - nuskaityto dokumento pradinis DokumentoID

- **FinalDocUrlHash** - nuskaityto dokumento pradinis DokumentoURLGrotelės

- **PaneOpened** - Bulio reikšmė, kuri seka, ar buvo atidaryta sritis Paskyros Tikrintuvas

- **ServerDocID** - pritaikymo neįgaliesiems tikrintuvu nuskaityto dokumento serverio DokumentoID


#### <a name="officeuxacccheckeracccheckerviolationinformation"></a>Office.UX.AccChecker.AccCheckerViolationInformation

Šis įvykis paleidžiamas, kai pranešama apie šiuo metu atidaryto dokumento pritaikymo neįgaliesiems triktis. Tai parodo apibendrintą pažeidimų skaičių (klaidos, įspėjimai ir patarimai) atidaryto dokumento seanso pradžioje ir pabaigoje. Šis įvykis yra naudojamas fiksuoti apibendrintą pritaikymo neįgaliesiems pažeidimų skaičių (klaidos, įspėjimai ir patarimai) atidaryto dokumento seanso pradžioje ir pabaigoje. Pritaikymo neįgaliesiems tikrintuvo naudojimo žinios leidžia „Microsoft“ patobulinti programų patirtį, kad žmonėms su negalia būtų labiau pritaikyti „Office“ naudojimo scenarijai darbo vietose ir klasėse.

Renkami šių laukų duomenys:
    
- **FinalDocID** - nuskaityto dokumento galutinis DokumentoID

- **FinalDocUrlHash** - nuskaityto dokumento galutinis DokumentoURLGrotelės

- **FinalErrorCount** – galutinis klaidų, kurias pateikė pritaikymo neįgaliesiems tikrintuvas, skaičius dokumente

- **FinalIntelligentServiceCount** - galutinis intelektualiųjų tarnybų problemų, kurias pateikė pritaikymo neįgaliesiems tikrintuvas, skaičius dokumente

- **FinalTipCount** – galutinis patarimų, kuriuos pateikė pritaikymo neįgaliesiems tikrintuvas, skaičius dokumente

- **FinalViolationCount** – galutinis pažeidimų, kuriuos pateikė pritaikymo neįgaliesiems tikrintuvas, skaičius dokumente

- **FinalWarningCount** – galutinis įspėjimų, kuriuos pateikė pritaikymo neįgaliesiems tikrintuvas, skaičius dokumente

- **FinalDocID** - nuskaityto dokumento pradinis DokumentoID

- **FinalDocUrlHash** - nuskaityto dokumento pradinis DokumentoURLGrotelės

- **InitialErrorCount** - visų rastų klaidos tipo pažeidimų skaičius, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **InitialIntelligentServicesCount** - visų rastų intelektualiosios tarnybos tipo pažeidimų skaičius, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **InitialTipCount** - rastas visų patarimo tipo pažeidimų skaičius, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **InitialUrlHash** - visų rastų klaidos tipo pažeidimų skaičius, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **InitialViolationCount** - visų rastų pažeidimų skaičius, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **InitialWarningCount** - visų rastų įspėjimo tipo pažeidimų skaičius, kai pirmą kartą seanse buvo paleistas paskyros tikrintuvas.

- **PaneOpened** - Bulio reikšmė, kuri seka, ar buvo atidaryta sritis Pritaikymo neįgaliesiems Tikrintuvas

- **ServerDocID** - pritaikymo neįgaliesiems tikrintuvu nuskaityto dokumento serverio DokumentoID


#### <a name="officeuxacccheckerbackgroundacccheckerenabledstate"></a>Office.UX.AccChecker.BackgroundAccCheckerEnabledState

Šis įvykis paleidžiamas, kai vartotojas arba IT administratorius aktyvina foninį Pritaikymo neįgaliesiems tikrintuvą „Office“ vartotojui. Šis įvykis naudojamas, norint suprasti atvejus, kai „Office“ vartotojams aktyvinamas foninis Pritaikymo neįgaliesiems tikrintuvas. Įjungta foninio Pritaikymo neįgaliesiems tikrintuvo būsena leidžia „Microsoft“ suprasti, ar dokumentai gali būti automatiškai nuskaityti fone. Tai padeda sukurti labiau integruotą darbo vietą ir klasės aplinką žmonėms su negalia.

Renkami šių laukų duomenys:

- **BackgroundAccCheckerEnabled** - Bulio logika stebėti foninio Pritaikymo neįgaliesiems tikrintuvo Įjungta/Išjungta būsenas


#### <a name="officeuxacccheckerbackgroundscanningcheckboxclicked"></a>Office.UX.AccChecker.BackgroundScanningCheckboxClicked

Šis įvykis paleidžiamas, kai vartotojas aktyvina foninį Pritaikymo neįgaliesiems tikrintuvą, naudojant Pritaikymo neįgaliesiems tikrintuvo užduočių sritį.  Šis įvykis naudojamas, norint suprasti atvejus, kai „Office“ dokumentams aktyvinamas foninis Pritaikymo neįgaliesiems tikrintuvas. Įjungta foninio Pritaikymo neįgaliesiems tikrintuvo būsena leidžia „Microsoft“ suprasti, ar dokumentai gali būti automatiškai nuskaityti fone. Tai padeda sukurti labiau integruotą darbo vietą ir klasės aplinką žmonėms su negalia.

Renkami šių laukų duomenys:
    
- **FinalBackgroundScanningState** - pradinė žymės langelio, kuris įgalina foninį nuskaitymą, būsena

- **InitialBackgroundScanningState** - pradinė žymės langelio, kuris įgalina foninį nuskaitymą, būsena


#### <a name="officeuxacccheckerdisabledresults"></a>Office.UX.AccChecker.DisabledResults

Šis įvykis paleidžiamas, kai Pritaikymo neįgaliesiems tikrintuvas išjungiamas atidarytame dokumente. Šis įvykis naudojamas norint suprasti atvejus, kai „Office“ Pritaikymo neįgaliesiems tikrintuvas išjungiamas, dėl pasenusio ar nepalaikomo „Office“ dokumento. Išjungta Pritaikymo neįgaliesiems tikrintuvo būsena leidžia „Microsoft“ suprasti, kaip dažnai nepavyksta nuskaityti dokumento, ir padėti vartotojams, kad jie galėtų nuskaityti tokius dokumentus, konvertuojant dokumentą į modernų failo formatą. Tai padeda sukurti labiau integruotą darbo vietą ir klasės aplinką žmonėms su negalia.

Renkami šių laukų duomenys:
    
- **Data_Disabled_ID** - Išjungimo klaidos ID

- **Data_Disabled_Reason** – Pritaikymo neįgaliesiems tikrintuvo išjungimo priežastis

- **Data_IsUpConvertEnabled** - stebi ar galima konvertuoti dokumentą į modernų failo formatą


#### <a name="officeuxacccheckershowtaskpane"></a>Office.UX.AccChecker.ShowTaskPane

Šis įvykis paleidžiamas, kai Pritaikymo neįgaliesiems tikrintuvo užduočių sritis paleidžiama atidarytam dokumentui.  Šis įvykis naudojamas norint suprasti „Office“ pritaikymo neįgaliesiems tikrintuvo naudojimą. Pritaikymo neįgaliesiems tikrintuvas naudojamas nustatyti ir išspręsti Pritaikymo neįgaliesiems problemas „Office“ dokumentuose. Pritaikymo neįgaliesiems tikrintuvo naudojimo žinios leidžia „Microsoft“ patobulinti programų patirtį, kad žmonėms su negalia būtų labiau pritaikyti „Office“ naudojimo scenarijai darbo vietose ir klasėse.

Renkami šių laukų duomenys:

- **BackgroundScanCheckboxEnabled** – stebi ar įjungtas foninis Pritaikymo neįgaliesiems tikrintuvas
    
- **Column** - Paskirtis

- **DocUrlHash** – nuskaityto dokumento unikali dokumento ID maiša

- **HasAccessibilityViolations** - stebi ar dokumente yra pritaikymo neįgaliesiems pažeidimų, kai sritis atidaroma

- **IsPaneDisabled** - stebi ar Pritaikymo neįgaliesiems tikrintuvo sritis yra atverta išjungimo būsenoje (pasenęs ar nepalaikomas dokumentas)

- **PaneOpenedBefore** - stebi ar anksčiau buvo atidaryta Pritaikymo neįgaliesiems tikrintuvo sritis.

- **WAC_ServerDocId** - nuskaityto dokumento Serverio Dokumento ID


#### <a name="officevisiosharedfeatureexperimentation"></a>Office.Visio.Shared.FeatureExperimentation

Stebi funkcijos testavimą vartotojams. Šis įvykis padeda mums nustatyti, ar funkcija testuojama sėkmingai.

Renkami šių laukų duomenys:

  - **Data\_Enable:bool**- „True“ nurodo, ar funkcija įjungta esamam vartotojui

  - **Data\_Feature:string** - Funkcijos pavadinimas

  - **Data\_Flighted:bool** - „True“ nurodo, ar funkcija yra įjungta

  - **Data\_Licensed:bool** - „True“ nurodo, ar tikrinama funkcijos licencija

  - **Data\_Subscriber:bool** - „True“ nurodo, ar vartotojas turi prenumeratos licenciją

#### <a name="officevisiosharedrefreshsmartdiagram"></a>Office.Visio.Shared.RefreshSmartDiagram

Fiksuoja diagramos atnaujinimo gedimus, kai failas sukuriamas per DV. Tai padeda mums derinti gedimus ir problemas atnaujinant duomenis DV diagramoje.

Renkami šių laukų duomenys:

  - **Data\_ConnectorsBasedOnSequence:bool**– „True“ nurodo, jei atnaujinta diagrama iš pradžių buvo sukurta naudojant jungtį, pagrįstą sekos parinktimi

  - **Data\_DialogError**:**string** - klaida atnaujinant išmaniąją diagramą

  - **Data\_FileError:string** - klaidos eilutė, kai prijungtas „Excel“ failas yra netinkamas

  - **Data\_OverwriteSelected**:**bool** - „True“ nurodo, ar vartotojas atnaujinant diagramą pasirinko diagramos perrašymo parinktį

  - **Data\_WarningShown**:**bool** - „True“ nurodo, ar nebuvo jokių įspėjimų vartotojui atliekant duomenų atnaujinimą

#### <a name="officevisiosharedwritebacktoexcel"></a>Office.Visio.Shared.WritebackToExcel

Fiksuoja „Excel“ rašymo triktis, kai failas sukurtas naudojant DV. Tai padeda mums derinti gedimus ir problemas įrašant duomenis į „Excel“ DV diagramoje.

Renkami šių laukų duomenys:

  - **Data\_ConnectorsBasedOnSequence:bool** - „True“ nurodo jungtis, kurios sukurtos pagrindžiant sekos parametrais

  - **Data\_DataSourceType:string** - šiame lauke nurodoma, ar diagrama sukurta naudojant „Table“, ar „CustomRange“

  - **Data\_DialogError:string** - Pasirinktinis klaidos tipas kuriant išmaniąją diagramą „Excel“

  - **Data\_NoOfShapesAdded:int** - Figūrų, kurios pridėtos įrašant „Excel“ funkcijos kopiją skaičius

  - **Data\_NoOfShapesDeleted:int** - Figūrų, kurios panakintos įrašant „Excel“ funkcijos kopiją skaičius

  - **Data\_OverwriteSelected:bool** - „True“ nurodo, ar vartotojas pasirinko duomenų perrašymo parinktį

  - **Data\_SourceDataModified:bool** - „True“ nurodo, kad pakeisti šaltinio duomenys

  - **Data\_WarningShown:bool** - „True“ reiškia, kad vartotojui rodomas duomenų naujinimo įspėjimas

  - **Data\_WarningShownBecauseOfPresenceOfFormula:bool** - „True“ nurodo vartotojui rodomą įspėjimą dėl formulės programoje „Excel“

  - **Data\_WarningShownToAddNextStepID:bool** - „True“ nurodo vartotojui rodomą įspėjimą dėl kitų identifikavimo priemonės programoje „Excel“ praleistų veiksmų

  - **Data\_WarningShownToConvertToTable:bool** - „True“ nurodo vartotojui rodomą įspėjimą konvertuoti „Excel“ duomenis į lentelės formatą


#### <a name="officewordfilenewcreatenewfile"></a>Office.Word.FileNew.CreateNewFile

Šis įvykis nurodo, kad sukurtas naujas dokumentas „Office Word“ ir sekamas sėkmingas arba nesėkmingas operacijų atlikimas. Įvykis naudojamas stebėti, ar naujų dokumentų kūrimas veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti.

Renkami šių laukų duomenys:

  - **Data\_DirtyState** – ar dokumentas buvo sukurtas neatnaujintoje būsenoje (su pakeitimais, kurie turi būti įrašyti)

  - **Data\_ErrorID** – klaidų identifikatorius operacijos gedimo atveju

  - **Data\_MainPdod –** dokumento identifikatorius šio proceso seanso metu

  - **Data\_UsesCustomTemplate** – nurodo, ar dokumentas buvo sukurtas naudojant pasirinktinį šabloną

#### <a name="officewordfileopenuserinitiatedopen"></a>Office.Word.FileOpen.UserInitiatedOpen 

Šis įvykis nurodo, kad „Office Word“ atidaro dokumentą vartotojo inicijavimu, o ne programiškai iš „Office Word“. Jame taip pat yra svarbių failo atidarymo našumo duomenų ir yra programėlės pradžios įvykis vertinant iš vartotojo perspektyvos.  Įvykis stebi ar file-open veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti. 
 
Renkami šių laukų duomenys:

- **Data_AddDocTelemRes** – nurodo, ar įvykyje galima tinkamai užpildyti kitų dokumentų telemetrijos susijusias reikšmes. Naudojama duomenų kokybės diagnostikai. 

- **Data_BytesAsynchronous** – baitų (suglaudintų), kurie, kaip manoma, gali atidaryti failą, skaičius, nepaisant, ar mes juos gausime iki tol, kol vartotojas nori pradėti redaguoti arba galbūt įrašyti. 

- **Data_BytesAsynchronousWithWork** – baitų (suglaudintų), kuriuos naudodami galėtume atidaryti failą, skaičius, tačiau norint, kad tai įvyktų, reikės daug investuoti į kodą 

- **Data_BytesSynchronous** – baitų (suglaudintų) skaičius, kuriuos privalome turėti prieš pradėdami atidaryti failą 

- **Data_BytesUnknown** – baitų skaičius dokumento dalyse, kurių nesitikėjome rasti. 

- **Data_Doc_AccessMode** – nurodo, ar dokumentas yra skirtas tik skaityti, ar redaguojamas 

- **Data_Doc_AssistedReadingReasons** – iš anksto nustatytų dokumento atidarymo pagalbiniu skaitymo režimu priežasčių reikšmių rinkinys 

- **Data_Doc_ChunkingType** – elementai, naudojami nuosekliam dokumento atidarymui 

- **Data_Doc_EdpState** – dokumentui taikomas elektroninių duomenų apsaugos parametras 

- **Data_Doc_Ext** – dokumento plėtinys (docx, xlsb, pptx ir kt.) 

- **Data_Doc_FileFormat** – failo formato protokolo versija 

- **Data_Doc_Fqdn** – „OneDrive“ arba „SharePoint“ interneto domeno vardas 

- **Data_Doc_FqdnHash** – kliento identifikuojamo domeno vardo vienpusė maiša 

- **Data_Doc_IdentityTelemetryId** – vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša 

- **Data_Doc_InitializationScenario** – įrašo, kaip dokumentas buvo atidarytas 

- **Data_Doc_IOFlags** – informuoja apie į talpyklą įtrauktas žymes, naudotas nustatyti užklausos parinktis 

- **Data_Doc_IrmRights** – veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kuri buvo taikyta dokumentui arba vartotojui 

- **Data_Doc_IsIncrementalOpen** – žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas 

- **Data_Doc_IsOcsSupported** – žymė nurodanti, kad dokumentą palaiko bendradarbiavimo tarnyba 

- **Data_Doc_IsOpeningOfflineCopy** – žymė, nurodanti, kad atidaryta autonominė dokumento kopija 

- **Data_Doc_IsSyncBacked** – žymė, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje 

- **Data_Doc_Location** – nurodo tarnybą, pateikusią dokumentą („OneDrive“, „File Server“, „SharePoint“) 

- **Data_Doc_LocationDetails** – nurodo įrenginyje saugomo dokumento žinomą aplanką 

- **Data_Doc_NumberCoAuthors** – skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių 

- **Data_Doc_PasswordFlags** – nurodo, ar nustatytas skaitymo arba skaitymo / rašymo slaptažodžio žymių rinkinys 

- **Data_Doc_ReadOnlyReasons** – dokumento atidarymo tik kaip skaitomo priežastys 

- **Data.Doc.ResourceIdHash** – anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti 

- **Data.Doc.ServerDocId** – nekintamų anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti 

- **Data_Doc_ServerProtocol** – protokolo versija, naudojama norint susisiekti su tarnyba 

- **Data_Doc_ServerType** – tarnybą siūlančio serverio tipas („SharePoint“, „OneDrive“, WOPI ir kt.) 

- **Data_Doc_ServerVersion** – serverio versija, siūlanti tarnybą 

- **Data_Doc_SessionId** – serverio versija, siūlanti tarnybą 

- **Data_Doc_SharePointServiceContext** – „SharePoint Online“ užklausų diagnostinė informacija 

- **Data_Doc_SizeInBytes** – dokumento dydžio indikatorius 

- **Data_Doc_SpecialChars** – dokumento URL arba kelio specialiųjų simbolių indikatorius 

- **Data_Doc_StreamAvailability** – indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas arba išjungtas 

- **Data_Doc_SyncBackedType** – dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba) 

- **Data_Doc_UrlHash** – vienpusė maiša, skirta „naïve“ dokumento identifikatoriui 

- **Data_Doc_WopiServiceId** – apima unikalų WOPI tarnybos teikėjo identifikatorių 

- **Data_EditorDisablingRename** – pirmojo redaktoriaus, dėl kurio buvo išjungtas pervardijimas, identifikatorius 

- **Data_EditorsCount** – dokumento redaktorių skaičius 

- **Data_ForceReadWriteReason** – sveikasis skaičius, nurodantis priežastį, kodėl failas buvo priverstinai atidarytas skaitymo / rašymo režimu 

- **Data_FSucceededAfterRecoverableFailure** – nurodo, kad atidaryti pavyko pašalinus triktį, įvykusią atidarant dokumentą 

- **Data_LastLoggedTag** – unikali kodo iškvietimo žymės vieta, naudojama nustatyti, kada dukart nepavyksta bandymas atidaryti (naudojama duomenų kokybės diagnostikai) 

- **Data_LinkStyles** – nurodo, ar mes susieti su šablono stiliais 

- **Data_MainPdod** – dokumento identifikatorius vykstant „Office Word“ procesui. 

- **Data_Measurements** – užkoduota eilutė, kurioje pateiktas skirtingų dalių atidarymo laiko suskirstymas. Skirtas diagnozuoti atvirai veiklai. 

- **Data_MoveDisabledReason** – klaida, kuri yra išjungia dokumento perkėlimą 

- **Data_MoveFlightEnabled** – nurodo, ar įjungta perkėlimo testavimo funkcija 

- **Data_OpenInitiateKind** – scenarijaus tipas, kai vartotojas pradėjo šią file-open operaciją. 

- **Data_PartsUnknown** – dokumento dalių, iš kurių nepavyko gauti duomenų, skaičius 

- **Data_RecoverableFailureInitiationLocationTag** – unikali kodo iškvietimo vietos žymė, naudojama vietai kode, kurioje stengiamės sutvarkyti failą prieš jį atidarant, identifikuoti 

- **Data_RenameDisabledReason** – klaida, dėl kurios šiam dokumentui išjungiamas pervardijimas 

- **Data_RenameFlightEnabled** – nurodo, ar įjungta pervardijimo testavimo funkcija 

- **Data_SecondaryTag** – unikali kodo iškvietimo vietos žymė, naudojama papildomiems trikties duomenims atidaryti. 

- **Data_TemplateFormat** – šablono failo, kuriuo pagrįstas dokumentas, formatas. 

- **Data_UsesNormal** – nurodo, ar atidarytas dokumentas pagrįstas įprastu šablonu. 

- **Data_VerboseMeasurements** – užkoduota eilutė, kurioje pateiktas skirtingų dalių atidarymo išsamus laiko suskirstymas.  Naudojama matuoti efektyvumą, įgalinta tik vidiniams žiedams. 



#### <a name="officewordfilesaveactcmdgosubsaveas"></a>Office.Word.FileSave.ActCmdGosubSaveAs

Šis įvykis nurodo, kad vartotojas įrašo savo pakeitimus į naują dokumentą. Įvykis stebi, ar įrašymas į naują dokumentą veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti.

Renkami šių laukų duomenys:

- **Data_AddDocTelemRes** – nurodo, ar įvykyje galima tinkamai užpildyti kitų dokumentų telemetrijos susijusias reikšmes. Naudojama duomenų kokybės diagnostikai.

- **Data_DetachedDuration** – nurodo, kiek laiko gijoje nebuvo veiklos

- **Data_Doc_AccessMode** – nurodo, ar dokumentas yra skirtas tik skaityti, ar redaguojamas

- **Data_Doc_AssistedReadingReasons** – iš anksto nustatytų dokumento atidarymo pagalbiniu skaitymo režimu priežasčių reikšmių rinkinys

- **Data_Doc_AsyncOpenKind** – nurodo, ar debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

- **Data_Doc_ChunkingType** – elementai, naudojami nuosekliam dokumento atidarymui

- **Data_Doc_EdpState** – dokumentui taikomas elektroninių duomenų apsaugos parametras

- **Data_Doc_Ext** – dokumento plėtinys (docx, xlsb, pptx ir kt.)

- **Data_Doc_FileFormat** – failo formato protokolo versija

- **Data_Doc_Fqdn** – „OneDrive“ arba „SharePoint“ interneto domeno vardas

- **Data_Doc_FqdnHash** – kliento identifikuojamo domeno vardo vienpusė maiša

- **Data_Doc_IdentityTelemetryId** – vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša

- **Data_Doc_InitializationScenario** – įrašo, kaip dokumentas buvo atidarytas

- **Data_Doc_IOFlags** – informuoja apie į talpyklą įtrauktas žymes, naudotas nustatyti užklausos parinktis

- **Data_Doc_IrmRights** – veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kuri buvo taikyta dokumentui arba vartotojui
    
- **Data_Doc_IsIncrementalOpen** – žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

- **Data_Doc_IsOcsSupported** – žymė nurodanti, kad dokumentą palaiko bendradarbiavimo tarnyba
    
- **Data_Doc_IsOpeningOfflineCopy** – žymė, nurodanti, kad atidaryta autonominė dokumento kopija

- **Data_Doc_IsSyncBacked** – žymė, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

- **Data_Doc_Location** – nurodo tarnybą, pateikusią dokumentą („OneDrive“, „File Server“, „SharePoint“ ir kt.)

- **Data_Doc_LocationDetails** – nurodo įrenginyje saugomo dokumento žinomą aplanką

- **Data_Doc_NumberCoAuthors** – skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

- **Data_Doc_PasswordFlags** – nurodo, ar nustatytas skaitymo arba skaitymo / rašymo slaptažodžio žymių rinkinys

- **Data_Doc_ReadOnlyReasons** – dokumento atidarymo tik kaip skaitomo priežastys

- **Data_Doc_ResourceIdHash** – anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

- **Data_Doc_RtcType** – nurodo, kaip buvo nustatytas realaus laiko kanalas (RTC) dabartiniam failui (išjungtas, nepalaikomas, pagal pageidavimą, visada įjungta, ir t. t.).

- **Data_Doc_ServerDocId** – nekintamų anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

- **Data_Doc_ServerProtocol** – protokolo versija, naudojama norint susisiekti su tarnyba

- **Data_Doc_ServerType** – tarnybą siūlančio serverio tipas („SharePoint“, „OneDrive“, WOPI ir kt.)

- **Data_Doc_ServerVersion** – serverio versija, siūlanti tarnybą

- **Data_Doc_SessionId** – nustato konkretų dokumentų redagavimo seansą visame seanse

- **Data_Doc_SharePointServiceContext** – „SharePoint Online“ užklausų diagnostinė informacija

- **Data_Doc_SizeInBytes** – dokumento dydžio indikatorius

- **Data_Doc_SpecialChars** – dokumento URL arba kelio specialiųjų simbolių indikatorius

- **Data_Doc_StreamAvailability** – indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas arba išjungtas

- **Data_Doc_SyncBackedType** – dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba)

- **Data_Doc_UrlHash** – vienpusė maiša, skirta „naïve“ dokumento identifikatoriui

- **Data_EditorDisablingRename** – pirmojo redaktoriaus, dėl kurio buvo išjungtas pervardijimas, identifikatorius

- **Data_EditorsCount** – dokumento redaktorių skaičius

- **Data_LastLoggedTag** – unikali kodo iškvietimo žymės vieta, naudojama nustatyti, kada dukart nepavyksta bandymas įrašyti (naudojama duomenų kokybės diagnostikai)

- **Data_MoveDisabledReason** – klaida, kuri yra išjungia dokumento perkėlimą

- **Data_MoveFlightEnabled** – nurodo, ar įjungta perkėlimo testavimo funkcija

- **Data_RenameDisabledReason** – klaida, dėl kurios išjungiamas dokumento pervardijimas

- **Data_RenameFlightEnabled** – nurodo, ar įjungta pervardijimo testavimo funkcija

    

#### <a name="officewordfilesaveactfconfirmsavedoccorequerysave"></a>Office.Word.FileSave.ActFConfirmSaveDocCoreQuerySave

Šis įvykis nurodo, kad „Office Word“ ragina vartotoją įrašyti keitimus, kai programa bando uždaryti dokumentą. Tai leidžia „Microsoft“ stebėti, ar įrašymas išėjimo metu veikia tinkamai, kad neprarasti dokumento duomenų. Įvykis stebi, ar funkcija įrašyti išėjimo metu veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti.

Renkami šių laukų duomenys:

- **Data_AddDocTelemRes** – nurodo, ar įvykyje galima tinkamai užpildyti kitų dokumentų telemetrijos susijusias reikšmes. Naudojama duomenų kokybės diagnostikai.

- **Data_DetachedDuration** – nurodo, kiek laiko gijoje nebuvo veiklos

- **Data_Doc_AccessMode** – nurodo, ar dokumentas yra skirtas tik skaityti, ar redaguojamas

- **Data_Doc_AssistedReadingReasons** – iš anksto nustatytų dokumento atidarymo pagalbiniu skaitymo režimu priežasčių reikšmių rinkinys

- **Data_Doc_AsyncOpenKind** – nurodo, ar debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

- **Data_Doc_ChunkingType** – elementai, naudojami nuosekliam dokumento atidarymui

- **Data_Doc_EdpState** – dokumentui taikomas elektroninių duomenų apsaugos parametras

- **Data_Doc_Ext** – dokumento plėtinys (docx, xlsb, pptx ir kt.)

- **Data_Doc_FileFormat** – failo formato protokolo versija

- **Data_Doc_Fqdn** – „OneDrive“ arba „SharePoint“ interneto domeno vardas

- **Data_Doc_FqdnHash** – kliento identifikuojamo domeno vardo vienpusė maiša

- **Data_Doc_IdentityTelemetryId** – vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša

- **Data_Doc_InitializationScenario** – įrašo, kaip dokumentas buvo atidarytas

- **Data_Doc_IOFlags** – informuoja apie į talpyklą įtrauktas žymes, naudotas nustatyti užklausos parinktis

- **Data_Doc_IrmRights** – veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kuri buvo taikyta dokumentui arba vartotojui

- **Data_Doc_IsIncrementalOpen** – žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

- **Data_Doc_IsOcsSupported** – žymė nurodanti, kad dokumentą palaiko bendradarbiavimo tarnyba
    
- **Data_Doc_IsOpeningOfflineCopy** – žymė, nurodanti, kad atidaryta autonominė dokumento kopija

- **Data_Doc_IsSyncBacked** – žymė, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

- **Data_Doc_Location** – nurodo tarnybą, pateikusią dokumentą („OneDrive“, „File Server“, „SharePoint“ ir kt.)

- **Data_Doc_LocationDetails** – nurodo įrenginyje saugomo dokumento žinomą aplanką

- **Data_Doc_NumberCoAuthors** – skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

- **Data_Doc_PasswordFlags** – nurodo, ar nustatytas skaitymo arba skaitymo / rašymo slaptažodžio žymių rinkinys

- **Data_Doc_ReadOnlyReasons** – dokumento atidarymo tik kaip skaitomo priežastys

- **Data_Doc_ResourceIdHash** – anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

- **Data_Doc_RtcType** – nurodo, kaip buvo nustatytas realaus laiko kanalas (RTC) dabartiniam failui (išjungtas, nepalaikomas, pagal pageidavimą, visada įjungta, ir t. t.).

- **Data_Doc_ServerDocId** – nekintamų anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

- **Data_Doc_ServerProtocol** – protokolo versija, naudojama norint susisiekti su tarnyba

- **Data_Doc_ServerType** – tarnybą siūlančio serverio tipas („SharePoint“, „OneDrive“, WOPI ir kt.)

- **Data_Doc_ServerVersion** – serverio versija, siūlanti tarnybą

- **Data_Doc_SessionId** – nustato konkretų dokumentų redagavimo seansą visame seanse

- **Data_Doc_SharePointServiceContext** – „SharePoint Online“ užklausų diagnostinė informacija

- **Data_Doc_SizeInBytes** – dokumento dydžio indikatorius

- **Data_Doc_SpecialChars** – dokumento URL arba kelio specialiųjų simbolių indikatorius

- **Data_Doc_StreamAvailability** – indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas arba išjungtas

- **Data_Doc_SyncBackedType** – dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba)

- **Data_Doc_UrlHash** – vienpusė maiša, skirta „naïve“ dokumento identifikatoriui

- **Data_Doc_WopiServiceId** – apima unikalų WOPI tarnybos teikėjo identifikatorių

- **Data_DstDoc_AccessMode** – paskirties dokumentas skirtas tik skaityti / redaguoti

- **Data_DstDoc_EdpState** – elektroninių duomenų apsaugos parametras, skirtas paskirties dokumentui

- **Data_DstDoc_Ext** – paskirties dokumento plėtinys (docx, xlsb, pptx ir kt.)

- **Data_DstDoc_FileFormat** – paskirties dokumento failo formato protokolo versija

- **Data_DstDoc_Location** – nurodo, kuri tarnyba teikia paskirties dokumento saugyklą („OneDrive“, failų serveris, „SharePoint“, kt.)

- **Data_DstDoc_LocationDetails** – nurodo, kuriuose žinomuose aplankuose yra paskirties dokumentas

- **Data_DstDoc_SessionId** – nustato konkretų dokumentų redagavimo seansą visame seanse

- **Data_DstDoc_UrlHash** – vienpusė maiša, skirta paskirties dokumento „naïve“ dokumento identifikatoriui sukurti

- **Data_FailureClass** – sveikasis skaičius, nurodantis OCS perėjimo trikčių trikties klasę

- **Data_LocationPickerSaveStatus** – sveikojo skaičiaus reikšmė, kuri nurodo veiksmą, suaktyvinantį įrašymą naudojant įrašymo arba išėjimo dialogo langą

- **Data_MainPdod** – dokumento identifikatorius vykstant „Office Word“ procesui.

- **Data_MoveFlightEnabled** – nurodo, ar įjungta perkėlimo testavimo funkcija

- **Data_OCSSyncbackSaveStarted** – žymė, nurodanti, kad šis įrašymas susijęs su sinchronizuotu atsarginės kopijos įrašymu 

- **Data_RenameDisabledReason** – klaida, dėl kurios šiam dokumentui išjungiamas pervardijimas

- **Data_RenameFlightEnabled** – nurodo, ar įjungta pervardijimo testavimo funkcija

- **Data_SaveInitiateKind** – sveikasis skaičius, nurodantis, kaip buvo inicijuotas įrašymas

- **Data_SrcDocIsUnnamedOrNew** – nurodo, ar įrašomas dokumentas yra naujas


#### <a name="officewordfilesavesaveassavefile"></a>Office.Word.FileSave.SaveAsSaveFile

Šis įvykis nurodo, kad „Office Word“ įrašo dokumentą į naują dokumentą. Tai leidžia „Microsoft“ aptikti funkcijos Įrašyti kaip klaidas, o tai svarbu norint išvengti dokumento duomenų praradimo. Įvykis stebi, ar funkcija Įrašyti kaip veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti.

Renkami šių laukų duomenys:

- **Data_AddDocTelemRes** – nurodo, ar įvykyje galima tinkamai užpildyti kitų dokumentų telemetrijos susijusias reikšmes. Naudojama duomenų kokybės diagnostikai.

- **Data_AddDocTelemResDst** – nurodo, ar paskirties dokumento įvykyje galima tinkamai užpildyti susijusias kitų dokumentų telemetrijos reikšmes. Naudojama duomenų kokybės diagnostikai.

- **Data_AddDocTelemResSrc** – nurodo, ar šaltinio dokumento įvykyje galima tinkamai užpildyti susijusias kitų dokumentų telemetrijos reikšmes. Naudojama duomenų kokybės diagnostikai.

- **Data_DetachedDuration** – nurodo, kiek laiko gijoje nebuvo veiklos

- **Data_Doc_AccessMode** – nurodo, ar dokumentas yra skirtas tik skaityti, ar redaguojamas

- **Data_Doc_AssistedReadingReasons** – iš anksto nustatytų dokumento atidarymo pagalbiniu skaitymo režimu priežasčių reikšmių rinkinys

- **Data_Doc_AsyncOpenKind** – nurodo, ar debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

- **Data_Doc_ChunkingType** – elementai, naudojami nuosekliam dokumento atidarymui

- **Data_Doc_EdpState** – dokumentui taikomas elektroninių duomenų apsaugos parametras

- **Data_Doc_Ext** – dokumento plėtinys (docx, xlsb, pptx ir kt.)

- **Data_Doc_FileFormat** – failo formato protokolo versija

- **Data_Doc_Fqdn** – „OneDrive“ arba „SharePoint“ interneto domeno vardas

- **Data_Doc_FqdnHash** – kliento identifikuojamo domeno vardo vienpusė maiša

- **Data_Doc_IdentityTelemetryId** – vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša

- **Data_Doc_IOFlags** – informuoja apie į talpyklą įtrauktas žymes, naudotas nustatyti užklausos parinktis

- **Data_Doc_IrmRights** – veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kuri buvo taikyta dokumentui arba vartotojui

- **Data_Doc_IsIncrementalOpen** – žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

- **Data_Doc_IsOcsSupported** – žymė nurodanti, kad dokumentą palaiko bendradarbiavimo tarnyba

- **Data_Doc_IsOpeningOfflineCopy** – žymė, nurodanti, kad atidaryta autonominė dokumento kopija

- **Data_Doc_IsSyncBacked** – žymė, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

- **Data_Doc_Location** – nurodo tarnybą, pateikusią dokumentą („OneDrive“, „File Server“, „SharePoint“ ir kt.)

- **Data_Doc_LocationDetails** – nurodo įrenginyje saugomo dokumento žinomą aplanką

- **Data_Doc_NumberCoAuthors** – skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

- **Data_Doc_ReadOnlyReasons** – dokumento atidarymo tik kaip skaitomo priežastys

- **Data_Doc_ResourceIdHash** – anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

- **Data_Doc_RtcType** – nurodo, kaip buvo nustatytas realaus laiko kanalas (RTC) dabartiniam failui (išjungtas, nepalaikomas, pagal pageidavimą, visada įjungta, ir t. t.).

- **Data_Doc_ServerDocId** – nekintamų anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

- **Data_Doc_ServerProtocol** – protokolo versija, naudojama norint susisiekti su tarnyba

- **Data_Doc_ServerType** – tarnybą siūlančio serverio tipas („SharePoint“, „OneDrive“, WOPI ir kt.)

- **Data_Doc_ServerVersion** – serverio versija, siūlanti tarnybą

- **Data_Doc_SessionId** – nustato konkretų dokumentų redagavimo seansą visame seanse

- **Data_Doc_SharePointServiceContext** – „SharePoint Online“ užklausų diagnostinė informacija

- **Data_Doc_SizeInBytes** – dokumento dydžio indikatorius

- **Data_Doc_SpecialChars** – dokumento URL arba kelio specialiųjų simbolių indikatorius

- **Data_Doc_StreamAvailability** – indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas arba išjungtas

- **Data_Doc_UrlHash** – vienpusė maiša, skirta „naïve“ dokumento identifikatoriui

- **Data_DstDoc_AccessMode** – paskirties dokumentas skirtas tik skaityti / redaguoti

- **Data_DstDoc_AssistedReadingReasons** – iš anksto apibrėžtas reikšmių rinkinys, kodėl dokumentas buvo atidarytas pagalbiniu skaitymo režimu

- **Data_DstDoc_AsyncOpenKind** – nurodo, ar naujo debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.
    
- **Data_DstDoc_ChunkingType** – elementai, naudojami nuosekliam dokumento atidarymui

- **Data_DstDoc_EdpState** – paskirties dokumentui skirtas elektroninių duomenų apsaugos parametras

- **Data_DstDoc_Ext** – dokumento plėtinys (docx, xlsb, pptx ir kt.)

- **Data_DstDoc_FileFormat** – failo formato protokolo versija

- **Data_DstDoc_Fqdn** – „OneDrive“ arba „SharePoint Online“ paskirties dokumento domeno vardas

- **Data_DstDoc_FqdnHash** – vienpusė kliento identifikuojamo paskirties dokumento domeno vardo maiša

- **Data_DstDoc_IdentityTelemetryId** – vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša

- **Data_DstDoc_InitializationScenario** – įrašo, kaip paskirties dokumentas buvo atidarytas

- **Data_DstDoc_IOFlags** – informuoja apie į talpyklą įtrauktas žymas, naudotas paskirties dokumento užklausos parinktims nustatyti
    
- **Data_DstDoc_IrmRights** – elektroninių duomenų apsaugos strategijos leidžiami veiksmai, kurie buvo taikyti paskirties dokumentui arba vartotojui

- **Data_DstDoc_IsIncrementalOpen** – žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

- **Data_DstDoc_IsOcsSupported** – žymė nurodanti, kad dokumentą palaiko bendradarbiavimo tarnyba

- **Data_DstDoc_IsOpeningOfflineCopy** – žymė, nurodanti, kad atidaryta autonominė dokumento kopija

- **Data_DstDoc_IsSyncBacked** – žymė, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

- **Data_DstDoc_Location** – nurodo, kuri tarnyba teikia paskirties dokumento saugyklą („OneDrive“, failų serveris, „SharePoint“, kt.)

- **Data_DstDoc_LocationDetails** – nurodo įrenginyje saugomo dokumento žinomą aplanką

- **Data_DstDoc_NumberCoAuthors** – skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

- **Data_DstDoc_PasswordFlags** – nurodo, ar nustatytas paskirties dokumento skaitymo arba skaitymo / rašymo slaptažodžio žymių rinkinys

- **Data_DstDoc_ReadOnlyReasons** – nurodo priežastis, kodėl paskirties dokumentas buvo atidarytas tik kaip skaitomas 

- **Data_DstDoc_ResourceIdHash** – anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

- **Data_DstDoc_ServerDocId** – nekintamų anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

- **Data_DstDoc_ServerProtocol** – protokolo versija, naudojama norint susisiekti su tarnyba

- **Data_DstDoc_ServerType** – tarnybą siūlančio serverio tipas („SharePoint“, „OneDrive“, WOPI ir kt.)
    
- **Data_DstDoc_ServerVersion** – serverio versija, siūlanti tarnybą

- **Data_DstDoc_SessionId** – nustato konkretų dokumentų redagavimo seansą visame seanse

- **Data_DstDoc_SharePointServiceContext** – „SharePoint Online“ užklausų diagnostinė informacija

- **Data_DstDoc_SizeInBytes** – dokumento dydžio indikatorius

- **Data_DstDoc_SpecialChars** – dokumento URL arba kelio specialiųjų simbolių indikatorius

- **Data_DstDoc_StreamAvailability** – indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas arba išjungtas

- **Data_DstDoc_SyncBackedType** – dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba)

- **Data_DstDoc_UrlHash** – vienpusė maiša, skirta paskirties dokumento „naïve“ dokumento identifikatoriui sukurti
    
- **Data_DstDoc_WopiServiceId** – apima unikalų WOPI tarnybos teikėjo identifikatorių

- **Data_FailureClass** – sveikasis skaičius, nurodantis OCS perėjimo trikčių trikties klasę

- **Data_LocationPickerPropagateToSaveTime,spLapsedMsec** – matuoja laiką milisekundėmis, kiek trunka įrašymo sužadinimas gavus vietos duomenų rinkiklio rezultatus

- **Data_LocationPickerSaveStatus** – vietos parinkiklio pateikta būsena

- **Data_MainPdod** – dokumento identifikatorius vykstant „Office Word“ procesui.

- **Data_MoveDisabledReason** – klaida, kuri yra išjungia dokumento perkėlimą

- **Data_MoveFlightEnabled** – nurodo, ar įjungta perkėlimo testavimo funkcija

- **Data_RenameDisabledReason** – klaida, dėl kurios šiam dokumentui išjungiamas pervardijimas

- **Data_RenameFlightEnabled** – nurodo, ar įjungta pervardijimo testavimo funkcija

- **Data_SaveInitiateKind** – sveikasis skaičius, nurodantis, kaip buvo inicijuotas įrašymas

- **Data_SrcDoc_AccessMode** – nurodo, ar šaltinio dokumentas yra skirtas tik skaityti, ar redaguojamas

- **Data_SrcDoc_AssistedReadingReasons** – iš anksto apibrėžtas dokumento atidarymo pagalbiniu skaitymo režimu priežasčių reikšmių rinkinys

- **Data_SrcDoc_AsyncOpenKind** – nurodo, ar pradinio debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

- **Data_SrcDoc_ChunkingType** – elementai, naudojami nuosekliam dokumento atidarymui

- **Data_SrcDoc_EdpState** – šaltinio dokumentui taikomas elektroninių duomenų apsaugos parametras

- **Data_SrcDoc_Ext** – šaltinio dokumento plėtinys (docx, xlsb, pptx ir kt.)

- **Data_SrcDoc_FileFormat** – šaltinio dokumento failo formato protokolo versija

- **Data_SrcDoc_Fqdn** – „OneDrive“ arba „SharePoint Online“ šaltinio dokumento domeno vardas

- **Data_SrcDoc_FqdnHash** – vienpusė kliento identifikuojamo šaltinio dokumento domeno vardo maiša

- **Data_SrcDoc_IdentityTelemetryId** – vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša

- **Data_SrcDoc_InitializationScenario** – įrašo, kaip dokumentas buvo atidarytas

- **Data_SrcDoc_IOFlags** – informuoja apie į talpyklą įtrauktas žymes, naudotas nustatyti užklausos parinktis

- **Data_SrcDoc_IrmRights** – veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kuri buvo taikyta dokumentui arba vartotojui

- **Data_SrcDoc_IsIncrementalOpen** – žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

- **Data_SrcDoc_IsOcsSupported** – žymė nurodanti, kad dokumentą palaiko bendradarbiavimo tarnyba

- **Data_SrcDoc_IsOpeningOfflineCopy** – žymė, nurodanti, kad atidaryta autonominė dokumento kopija

- **Data_SrcDoc_IsSyncBacked** – žymė, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje
    
- **Data_SrcDoc_Location** – nurodo, kuri tarnyba teikia šaltinio dokumentą („OneDrive“, failų serveris, „SharePoint“, kt.)

- **Data_SrcDoc_LocationDetails** – nurodo įrenginyje saugomo dokumento žinomą aplanką

- **Data_SrcDoc_NumberCoAuthors** – skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

- **Data_SrcDoc_PasswordFlags** – nurodo, ar nustatytas skaitymo, ar skaitymo / rašymo slaptažodžio žymių rinkinys

- **Data_SrcDoc_ReadOnlyReasons** – dokumento atidarymo tik kaip skaitomo priežastys

- **Data_SrcDoc_ResourceIdHash** – anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

- **Data_SrcDoc_ServerDocId** – nekintamų anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

- **Data_SrcDoc_ServerProtocol** – protokolo versija, naudojama norint susisiekti su tarnyba

- **Data_SrcDoc_ServerType** – tarnybą siūlančio serverio tipas („SharePoint“, „OneDrive“, WOPI ir kt.)

- **Data_SrcDoc_ServerVersion** – serverio versija, siūlanti tarnybą

- **Data_SrcDoc_SessionId** – nustato konkretų dokumentų redagavimo seansą visame seanse

- **Data_SrcDoc_SharePointServiceContext** – „SharePoint Online“ užklausų diagnostinė informacija

- **Data_SrcDoc_SizeInBytes** – dokumento dydžio indikatorius

- **Data_SrcDoc_SpecialChars** – dokumento URL arba kelio specialiųjų simbolių indikatorius

- **Data_SrcDoc_StreamAvailability** – indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas, ar išjungtas

- **Data_SrcDoc_SyncBackedType** – dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba)

- **Data_SrcDoc_UrlHash** – vienpusė maiša, skirta „naïve“ dokumento identifikatoriui

- **Data_SrcDoc_WopiServiceId** – apima unikalų WOPI tarnybos teikėjo identifikatorių

- **Data_SrcDocIsUnnamedOrNew** – nurodo, ar įrašomas dokumentas yra naujas


#### <a name="officewordworddocumentdirtyflagchanged"></a>Office.Word.Word.DocumentDirtyFlagChanged

Šis įvykis nurodo, ar „Office Word“ redaguoja dokumentą, kurio keitimų vidinė būsena nustatyta kaip „juodraštis“ Tai leidžia „Microsoft“ įvertinti dokumento redagavimo sveikatos funkciją. Šis įvykis yra vartotojo redagavimų svarbiausias įvykis. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams apskaičiuoti.

Renkami šių laukų duomenys:

  - **Data\_CollectionTime-** Įvykio laiko žyma

  - **Data\_DocumentLocation-** Dokumento vietos tipas

  - **Data\_DocumentLocationDetails-** Dokumento vietos potipis

  - **Data\_FAlwaysSaveEnabled-** Nurodo, ar buvo įjungta funkcija Visada įrašyti

  - **Data\_FirstEditTime-** Pirmo redagavimo laiko žyma

  - **Data\_NumberCoAuthors-** Bendraautorių, redagavusių dokumentą seanso metu, skaičius

  - **Data\_NumberOfTimesDocumentDirtied-** Keitimų, atliktų redaguojant, skaičius

  - **Data\_Pdod-** Dokumento identifikatorius vykstant „Office Word“ procesui

  - **Data\_UrlHash-** Dokumento kelio maiša

  - **Data\_ViewKind-** „Word“ rodinio tipas



#### <a name="onenoteappnavigationratingreminderdialogshown"></a>OneNote.App.Navigation.RatingReminderDialogShown

Kritinis signalas, naudojamas pamatuoti vertinimo priminimo paleidimo logikos veiksmingumą. Šis dialogo langas rodomas, kai vartotojas atitiko visas sąlygas, kad matytų vertinimo priminimą ( aktyvių dienų skaičių, ar anksčiau vertinta, ar ne ir t. t.) Naudojama užtikrinti vertinimo priminimo paleidimo logiką. Jei vartotojai mato šį dialogo langą, mes gausime galimybę gauti atsiliepimus iš klientų tinkamu metu ir pagerinti programos būklę.

Renkami šių laukų duomenys:

- Nėra

#### <a name="parselicenseop"></a>ParseLicenseOp

Gaunamas, kai vartotojas bando atidaryti IRM apsaugotą dokumentą arba taikyti IRM apsaugą. Jame yra informacija, būtina norint tinkamai ištirti ir nustatyti problemas, kurios įvyksta atliekant licencijų analizės operaciją. 

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas

- **AppInfo.Version** – programos versija

- **iKey** – registravimo serverio ID

- **RMS.ApplicationScenarioId** – programos pateiktas scenarijaus ID

- **RMS.Duration** – bendras operacijos baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia operacija, jei tokia yra

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.LicenseFormat** – licencijos formatas: Xrml arba Json

- **RMS.Result** – operacijos sėkmė arba nesėkmė

- **RMS.ScenarioId** – scenarijaus ID, kurį apibrėžia teisių valdymo tarnybos klientas

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.ServerType** – teisių valdymo tarnybos tipas 

- **RMS.StatusCode** – operacijos rezultato būsenos kodas

- **RMS.VerifyCertChainDuration** – sertifikato grandinės patvirtinimo trukmė

- **RMS.VerifySignatureDuration** – parašo patvirtinimo trukmė

#### <a name="readconversation"></a>read.conversation

Naudojama stebėti galimą neigiamą įtaką el. laiško generavimo sveikatai ir veikimo efektyvumui

Renkami šių laukų duomenys: 

- **above_40fps** – kadrų skaičius virš 40 fps
 
- **above_50fps** – kadrų skaičius virš 50 fps
 
- **above_55fps** – kadrų skaičius virš 55 fps

- **adal_id** – paskyros „Active Directory“ autentifikavimo ID, unikalusis „Microsoft“ autentifikavimo sistemos identifikatorius 

- **component_name** – filtruojant aktyvaus komponento/rodinio pavadinimas

- **event_mode** – vieta, kurioje vartotojas prisijungė prie pokalbio (grupės arba kita)

- **internet_message_id** – naujausio pokalbio pranešimo sekimo ID
      
- **orientation** – ekrano padėtis įvykio metu (stačias arba gulsčias)

- **recent_message_id** – naujausio pokalbio pranešimo ID

- **suggested_reply_state** – šio pokalbio siūlomų atsakymų būsena (nepasiekiama, pasiekiama, rodoma, naudojama arba atmesta)

- **suggested_reply_types** – nurodo siūlomo atsakymo tipą ir skaičių. Tai žodynas. Pvz., {tekstas: 2, send_avail: 1}.
  
- **total_count** – bendras rodomų kadrų skaičius pagal komponentą
 
- **view_duration** – kiek laiko vartotojas peržiūrėjo komponentą

#### <a name="saveattempt"></a>save.attempt

Leidžia mums nustatyti problemų, kurios kilo vartotojams bandant įrašyti failą, poveikį vertinant veikiamų seansų skaičių ir ar yra bendrų šių seansų funkcijų.

Renkami šių laukų duomenys: 

- **file_type** – vartotojo bandyto įrašyti failo tipas (pvz.,. doc)

- **origin** – iš kur buvo bandoma įrašyti failą (pvz., iš el. laiško), kad galėtume aptikti problemą, susijusią su failo įrašymu iš tam tikros programos vietos

- **token_type** – atpažinimo ženklo tipas, naudojamas autentifikuoti paskyrą, kad būtų galima įrašyti failą, kad galėtume nustatyti autentifikavimo problemas, susijusias su failo įrašymais

#### <a name="searchsubtabselected"></a>search.subtab.selected

Įvykis renka kilmės taškus ieškos sub_tab pasirinkimo priežasčiai. Antriniai skirtukai yra pirminės programos ieškos juostoje, skirtoje filtruoti duomenis. Šis įvykis mums leidžia stebėti objekto tipo elementus (visus, paštą, kontaktus ir kalendorių), kuriuos vartotojai naudoja, kai ieško, kad galėtume užtikrinti tinkamą ieškos filtrų mechanizmų veikimą.

Renkami šių laukų duomenys:

- **properties_general** – bendrosios ypatybės, kurias renka visi „Aria“ įvykiai

- **selected_reason** – pasirenkamo tipo elemento priežastis, kuri gali būti viena iš šių reikšmių (glifas yra piktograma): tap_on_header, tap_on_see_all, enter_search_mode, mail_glyph, calendar_glyph.

- **subtab_type** – pasirinktas tipo elementas, kuris gali būti vienas iš šių keturių reikšmių: visi, paštas, kontaktas, įvykis.

#### <a name="sendmessage"></a>send.message

Naudojama stebėti galimą neigiamą įtaką el. laiško siuntimo sveikatai ir veikimo efektyvumui.

Renkami šių laukų duomenys:
  
- **account** – seka veiksmą atlikusią paskyrą

- **compose_duration** – seka bendrą laiką, kurį vartotoją kūrė laišką, įskaitant kelis juodraščių seansus

- **draft_message_id** – seka siunčiamo laiško ID

- **event_mode** – seka įvykio režimą, jei jis taikomas pranešimui („grupės“ arba „kita“).

- **has_attachment** – nurodo, ar pranešimas turi priedų

- **has_mip_label** – nurodo, ar pranešime buvo pažymėtas MIK žyme

- **image_attachment_count** – nurodo, kiek vaizdų siunčiama pranešimo prieduose

- **image_body_count** – nurodo, kiek vaizdų siunčiama pranešimo tekste

- **image_movement_count** – nurodo, kiek pranešimo vaizdų buvo perkelta į pranešimo tekstą arba atgal.

- **is_group_escalation** – ar tai grupės eskaluotas pranešimas, „eskaluotas pranešimas“ – tai pranešimas, išsiųstas į vartotojo pašto dėžutę dėl eskalavimo (prenumeruota grupei)

- **is_groups** – seka, ar siunčiamas pranešimas yra grupės pranešimas

- **key_stroke_count** – seka siunčiamo pranešimo klavišų paspaudimų skaičių

- **message_id** – seka atsakomo / persiunčiamo pranešimo ID

- **origin** – nurodo, kur buvo pradėtas kūrimas, t. y. naujas, atsakymas, greitasis atsakymas ir t. t.

- **send_draft_origin** – nurodo, kur buvo inicijuotas siuntimas, t. y. sukurtas arba greitas atsakymas

- **smart_compose_model_version** – seka, kuri išmaniojo komponavimo modelio versija yra naudojama

- **source_inbox** – nurodo šaltinio aplanko Gauta tipą nuorodos pranešimui, 

- **suggested_reply_state** – fiksuoja šiam laiškui siūlomo atsakymo būseną, t. y. nepasiekiama, pasiekiama, rodoma, naudojama arba atmesta

- **suggested_reply_types**: nurodo tipą ir siūlomo atsakymo kiekį, kuris rodomas/naudojamas šiam išsiųstiems el. laiškams. Tai žodynas. Pvz., {tekstas: 2, send_avail: 1}.

- **suggestions_requested** – nurodo, kiek išmaniojo rašymo pasiūlymų prašoma

- **suggestions_results** – išmaniojo rašymo pasiūlymų rezultatas, t. y. priimtas, atmestas

- **suggestions_returned** – nurodo, kiek išmaniojo rašymo pasiūlymų pateikta iš serverio

- **suggestions_returned** – nurodo, kiek išmaniojo rašymo pasiūlymų pateikta vartotojui

- **thread_id** – nurodo pokalbio į kurį atsakoma / kuris persiunčiamas gijos ID

#### <a name="session"></a>session

Leidžia nustatyti ir pataisyti situacijas, kai naudojame per daug įrenginio akumuliatoriaus energijos, taip pat padeda mums nustatyti galimą priežastį.

Renkami šių laukų duomenys: 

- **battery_level** – nurodo įrenginio akumuliatoriaus lygį, kad galėtume nustatyti, kada mūsų programa neigiamai veikia įrenginio akumuliatoriaus lygį

- **has_hx** – nurodo, kad paskyra naudoja mūsų naują sinchronizavimo tarnybą, kad būtų galima aptikti sinchronizavimo tarnybos sukeltas problemas

- **Session.Duration** – seanso ilgis sekundėmis

- **Session.DurationBucket** – seanso ilgio talpykla *[Šis laukas buvo pašalintas iš dabartinių „Office“ versijų, bet gali būti rodomas senesnėse versijose.]*

- **Session.FirstLaunchTime** – Pirma įrašyta programos įkėlimo trukmė *[Šis laukas buvo pašalintas iš dabartinių „Office“ versijų, bet gali būti rodomas senesnėse versijose.]*

- **Seansas.State** – indikatorius, ar tai yra seanso pradžios arba pabaigos pabaiga

#### <a name="settingsaction"></a>settings.action

Šis įvykis renka konfigūracijos informaciją parametruose. Duomenys leidžia aptikti situacijas, kai gali būti neigiamas poveikis vartotojo gebėjimui konfigūruoti programos parametrus, pvz., pranešimų parametrus, pagrindinę el. pašto paskyrą ir konfigūruoti el. pašto parašą.

Renkami šių laukų duomenys: 

- **account_order_changed** – kad būtų galima tikrinti, ar pakeitėte paskyrų tvarką siekiant įsitikinti, jog ši konfigūracija tinkamai veikia 

- **action** – galimi veiksmai, kurių buvo imtasi parametruose, pvz., panaikinta paskyra, kad būtų galima diagnozuoti problemas ir užtikrinti neigiamo poveikio buvimą

- **auth_type** – paskyros naudojamas autentifikavimo tipas, kad suprastume, kurį vidinės sistemos sinchronizavimo sluoksnį naudojame ir būtų galima diagnozuoti problemas 

- **changed_folder** – fiksuoja, ar buvo pakeistas aplankas, kad galėtume diagnozuoti problemas. 

- **delete_scope** – paskyros naikinimo metu, ar panaikinote paskyrą iš šio įrenginio, ar iš visų įrenginių su „Outlook“.  

- **enabled_state** – ar tinkamai sukonfigūruotas automatinis atsakymas, kontaktų įrašymas ir išorinių vaizdų blokavimo parametrai  

- **notification_action** – skirta tikrinti, ar konfigūravote kokius nors pranešimų veiksmus el. laiškų klasifikavimui, kad galėtumėte įsitikinti, jog šis nustatymas veikia tinkamai 

- **notification_action_number** – kad būtų galima patikrinti, ar jūsų pranešimų veiksmai (pirmas veiksmas arba antras veiksmas) yra tinkamai sukonfigūruoti

- **server_type** – panašiai kaip auth_type, nurodo, kokio tipo paskyrą turite, kad galėtume geriau diagnozuoti problemas.  Pavyzdžiai: „Office365“, „Gmail“, „Outlook“

- **setting_properties** – seka ypatybių sąsają su parametro veiksmu, aprašytu toliau: 
   - **alternate_app_icon_setting** – pasirinkta alternatyvi taikomosios programos piktograma (šviesi, tamsi)
   - **auth_type** – nurodo vidinio autentifikavimo tipą, kuris leidžia žinoti, ar kilo konkretaus paskyros tipo problemų
   - **badge_count_state** – nurodo, kokio tipo ženklelių skaičiaus pageidavo vartotojas, t. y. nėra ženklelių, tik reikšmingiausi gautieji ir t. t. 
   - **changed_folder** – nustato, ar šis veiksmas buvo archyvuotas, suplanuotas, ar kitas veiksmas.
   - **delete_scope** – seka, ar šis veiksmas buvo susijęs su asmens panaikinimu tik šiame įrenginyje, ar visuose įrenginiuose, jei taikoma. 
  - **enabled_state** – ar įgalinta su veiksmu susijusi būsena
  - **in_app_language** – pasirinkta programos kalba, eilutės tipas (numatytoji, EN-US, FA, RU ir t. t.)
  - **notification_action_setting** – nurodo, jei taikoma, pranešimo veiksmo parametrų, susijusių su šiuo veiksmu, informaciją.
    - **notification_action** – nurodo, ką vartotojas bandė daryti, t. y. pažymėti vėliavėle, naikinti, archyvuoti, kad galėtume nustatyti, kokio el. laiško veiksmo vartotojas norėjo pranešime ir ar veiksmas pavyko. 
    - **notification_action_number** – nurodo, kuris veiksmo numeris (du iš trijų veiksmų yra tinkinami) buvo priskirtas pranešimų veiksmui, t. y. pirmas veiksmas, antras veiksmas. Tai leidžia nustatyti, ar kilo problemų dėl konkretaus veiksmo.
   - **notification_state** – nurodo, kokio tipo ženklelių skaičiaus pageidavo vartotojas, t. y. nėra ženklelių, tik reikšmingiausi gautieji ir t. t.
   - **server_type** – nurodo vidinio serverio tipą, kuris leidžia žinoti, ar kilo konkretaus serverio tipo problemų
   - **source** – nurodo, kas yra pranešimų šaltinis, jei taikoma, iš parametrų arba nustatymo netrukdyti
   - **swipe_setting** – nurodo, jei taikoma, braukimo parametrų, susijusių su šiuo veiksmu, informaciją.
     - **swipe_action** – nurodo, ką vartotojas bandė daryti, t. y. pažymėti vėliavėle, naikinti, archyvuoti, kad galėtume nustatyti, kokio veiksmo vartotojas norėjo ir ar veiksmas pavyko. 
     - **swipe_direction** – nurodo, kokiu būdu vartotojas nustatė braukimo naudojimą, t. y. iš kairės į dešinę arba iš dešinės į kairę. Tai leidžia nustatyti, ar kilo problemų dėl konkrečios braukimo krypties.
   - **temperature_unit_setting** - pasirinktos temperatūros matavimo vienetas, naudojamas orui 
   - **theme_color_setting** – vartotojo pasirinkta programos temos spalva 
   - **ui_mode_setting** – pasirinktas vartotojo sąsajos režimas (tamsus, šviesus, sistemos numatytasis, mažai akumuliatoriaus energijos naudojantis ir t. t.)
   - **signature_setting** – nurodo, ar parametras buvo taikomas visoms paskyroms, ar atskirai paskyrai

- **state_changed_to** – skirta tikrinti, ar tinkamai sukonfigūruotas aplanko reikšmingiausi Gautieji įjungta / išjungta parametras 

- **swipe_action** – skirta tikrinti, ar konfigūravote kokius nors braukimo veiksmus el. laiškų klasifikavimui, kad galėtumėte įsitikinti, jog šis nustatymas veikia tinkamai 

- **swipe_direction** – skirta tikrinti, ar braukimo kryptys (kairė arba dešinė) sukonfigūruotos tinkamai


#### <a name="sidebaraction"></a>sidebar.action

Leidžia aptikti situacijas, kai gali būti neigiamas poveikis jūsų gebėjimui konfigūruoti programos parametrus, pvz., pranešimų parametrus, pagrindinę el. pašto paskyrą ir konfigūruoti el. pašto parašą.

Bendri „Outlook Mobile“ duomenų laukai, skirti šiam įvykiui „iOS“ ir „Android“ įrenginyje:

- **Account** – seka paskyrą ir jos duomenis, susijusius su įvykiu, šiuose duomenyse stebimos vertės yra bendrojoje „om“ lauko dokumentacijoje *[Šis laukas buvo pašalintas iš dabartinių „Office“ versijų, tačiau vis tiek gali būti rodomas senesnėse versijose.]*

- **action** – seka, kokio tipo juostos veiksmas įvyko, t. y. atmestas, pasirinktas žinyno mygtukas, el. pašto šoninė juosta ir t. t., 

- **from_favorites** – seka, ar veiksmas ateina iš parankinių elemento 

- **mail_folder_type** – kokio tipo aplankas buvo pasirinktas atliekant šoninės juostos veiksmą, jei toks buvo.

- **sidebar_type** – seka tipą šoninės juostos, susietos su šiuo įvykiu, t.y. el. pašto arba kalendoriaus, kad galėtume užtikrinti, kad naršymas iš parankinių parametrų veikia tinkamai

Renkami šių laukų duomenys: 

- **account_type** – nurodo, kokio autentifikavimo tipo yra paskyra, t. y. „Gmail“, „Outlook“ ir t. t. 

- **account_has_groups** – padeda užtikrinti, kad jei paskyroje yra grupių, jos yra sukonfigūruotos tinkamai

- **calendar_accounts_count** – turimų kalendoriaus paskyrų skaičius, kad būtų galima užtikrinti tinkamą kalendoriaus paskyrų konfigūraciją 

- **calendar_apps_count** – turimų kalendoriaus programų skaičius, kad būtų galima užtikrinti tinkamą kalendoriaus programų konfigūraciją 

- **calendar_type** – turimo kalendoriaus tipas (Pagrindinis kalendorius, grupės kalendorius ir t. t.) 

- **has_favorite_folders** – padeda užtikrinti tinkamą parankinių aplankų konfigūraciją 

- **has_favorite_people** – padeda užtikrinti tinkamą parankinių žmonių / kontaktų konfigūraciją 

- **has_group_calendar** – padeda užtikrinti tinkamą grupės kalendorių, jei tokių turite, konfigūraciją. 

- **has_group_calendar_account** – padeda užtikrinti tinkamą grupės kalendorių, jei tokių turite, konfigūraciją. 

- **has_group_toggled** – padeda užtikrinti tinkamą perjungiamų grupės kalendorių, jei tokių turite, konfigūraciją. 

- **interesting_calendars_accounts_count** – turimų dominančių kalendoriaus paskyrų skaičius, kad būtų galima užtikrinti tinkamą dominančių kalendoriaus paskyrų konfigūraciją 

- **mail_accounts_count** – bendras skaičius pašto paskyrų šoninėje juostoje, kad būtų galima užtikrinti tinkamą konfigūraciją 

- **mail_folder_type** – aplanko, kurį bakstelėjo vartotojas, tipas, kad būtų galima užtikrinti tinkamą konfigūraciją. Tai gali būti aplankas Panaikinta, Pašto šiukšlės ar aplankas Išsiųsti. 

- **mail_inbox_unread_count** – padeda užtikrinti, kad neskaitytų laiškų skaičius būtų rodomas ir sukonfigūruotas tinkamai 

- **mail_subfolder_depth** – padeda užtikrinti, kad galime sėkmingai rodyti vartotojo pašto poaplankių konfigūracijas

#### <a name="storeop"></a>StoreOp

Renkama, kai vartotojas bando atidaryti IRM apsaugotą dokumentą ar taikyti IRM apsaugas.  Joje yra informacija, reikalinga tinkamai nustatyti ir diagnozuoti problemas, įvykusias teisių valdymo tarnybos licencijos operacijos problemas. 

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas.

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.ApplicationScenarioId** – programos pateiktas scenarijaus ID

- **RMS.ContentId** – galutinio vartotojo licencijos turinio ID

- **RMS.Duration** – bendras API iškvietimo baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia operacija, jei tokia yra

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.LicenseFormat** – licencijos formatas: Xrml arba Json

- **RMS.OperationName** – operacijos pavadinimas

- **RMS.Result** – operacijos sėkmė arba nesėkmė

- **RMS.ScenarioId** – scenarijaus ID, kurį apibrėžia teisių valdymo tarnybos klientas

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.ServerType** – teisių valdymo tarnybos tipas 

- **RMS.StatusCode** – operacijos rezultato būsenos kodas

- **RMS.Url** – teisių valdymo tarnybos serverio URL


#### <a name="surveyfloodgatetriggermet"></a>Survey.Floodgate.TriggerMet

Seka, kada įrenginys atitiko kriterijus rodyti apklausai. Naudojama įvertinti apklausos suaktyvinimo proceso būklei bei užtikrinti, kad signalas, naudojamas analizuoti klientų problemoms ir būklei, veikia tinkamai.

Renkami šių laukų duomenys: 

- **CampaignId** – tarnyboje pristatomos kampanijos identifikatorius

- **SurveyId** – unikalus kampanijos egzempliorius

- **SurveyType** – identifikuoja apklausos tipą


#### <a name="surveyuiformsubmit"></a>Survey.UI.Form.Submit

Seka, kada pateikiama apklausa. Naudojama siekiant įvertinti apklausų pateikimo proceso sveikatos būseną bei užtikrinti, kad signalas, naudojamas analizuojant klientų problemas ir būklę, veiktų tinkamai.

Renkami šių laukų duomenys: 

- **CampaignId** – tarnyboje pristatomos kampanijos identifikatorius

- **SurveyId** – unikalus kampanijos egzempliorius

- **SurveyType** – identifikuoja apklausos tipą


#### <a name="watchappv2"></a>watchAppV2

Šis įvykis leidžia aptikti ir išspręsti galimas „Apple Watch“ galimybių problemas, pvz., pranešimų gavimą ir atsakymą į el. laiškus.

Renkami šių laukų duomenys: 

- **app_action** – nurodo veiksmo, kurį vartotojas atliko su „Apple Watch“, pvz., archive_message, tipus, kad būtų galima nustatyti su tam tikru veiksmu susijusias problemas, pvz., nepavyko sėkmingai archyvuoti el. laiškų naudojant „Apple Watch“

- **is_watch_app_installed** – nurodo, ar vartotojas įdiegė mūsų „Apple Watch“ programą savo įrenginyje

- **is_complication_enabled** – nurodo, ar vartotojas įtraukė „Outlook“ į savo „Apple Watch“ ekraną, kad būtų galima aptikti su „Apple Watch“ ekranais susijusias problemas

- **watch_os** – nurodo „Apple Watch“ operacinės sistemos versiją, kuri buvo įdiegta, kad būtų galima aptikti su konkrečiomis „Apple Watch“ operacinės sistemos versijomis susijusias problemas


### <a name="application-status-and-boot-subtype"></a>*Taikomosios programos būsena ir įkrovos potipis*

Nustatymas, ar įvyko specifiniai funkcijų įvykiai, pvz., paleidimas ar sustabdymas, ir ar funkcija veikia.

#### <a name="appstartup"></a>app.startup

Šis įvykis leidžia mums aptikti ir išspręsti problemas, kai „Outlook“ paleidžiama lėtai arba nevisiškai, todėl vartotojams tampa sudėtinga naudoti mūsų programą.  Apima informaciją apie tam tikras įgalintas funkcijas ir kiek laiko buvo truko dalių paleistis.

Renkami šių laukų duomenys: 

- **attach_base_context_millis** – laikas tarp bazinio Context paleidimo ir onCreate() paleidimo

- **device_ram_in_mb** – įrenginyje pasiekiamas RAM kiekis

- **has_company_portal** – ar įdiegta įmonės portalo programa

- **hx_okhttp_mode** – ar naujas el. pašto sinchronizavimo tarnybos komponentas naudoja „OKHttp“ HTTP pagrįstų tinklo užklausų siuntimui ir gavimui

- **initial_activity_name** – „Android“ veikla, kuri paleido programą

- **manufacturer** – įrenginio gamintojas

- **model** – įrenginio modelis

- **on_create_millis** – sugaištas laikas naudojant onCreate() metodą

- **on_create_millis** – sugaištas laikas naudojant onResume() metodą

- **time_until_attach** – laikas tarp klasės įkėlimo ir bazinio Context paleidimo

- **total_millis** – bendras laikas nuo klasės įkėlimo pradžios iki „Android“ veiklos atnaujinimo užbaigimo

#### <a name="boottime"></a>boot.time 

Šis įvykis leidžia nustatyti, kada įvyko kritinių programų klaidų, dėl kurių programa galėjo sugesti arba kilti rimtų problemų, pvz., aplanke Gauta rodomos tuščios eilutės. Šis įvykis renka informaciją, kuri leidžia skirstyti ir klasifikuoti problemas, kad būtų lengviau prioretizuoti problemų įtaką klientams.

Renkami šių laukų duomenys:

- **black_list_reason** – nurodo, ar yra priežasčių, kodėl turėtume nepaisyti šių duomenų. Keli pavyzdžiai: paleidimas dėl nuotolinio pranešimo ir paleidimas dėl foninio iškvietimo.

- **step_premain** – mums nurodo, kiek laiko trunka „Outlook“, kad pereitumėte iš vartotojo bakstelėję piktogramą step0_main, kuris yra šiame dokumente apibrėžtas pagrindinis veiksmas.

- **step0_main** – nurodo, kiek laiko „Outlook“ užtruko pasiekti „pagrindinį“ veiksmą, kuris yra „Apple“ apibrėžtas veiksmas.

- **step1_appWillFinishLaunching** – nurodo, kiek laiko trunka „Outlook“ pereiti iš „pagrindinio“ veiksmo į „appWillFinishLaunching“ veiksmą, kuris yra „Apple“ apibrėžtas veiksmas.

- **step2_appDidFinishLaunching** – nurodo, kiek laiko trunka „Outlook“ pereiti iš „appWillFinishLaunching“ veiksmo į „appDidFinishLaunching“ veiksmą, kuris yra „Apple“ apibrėžtas veiksmas.

- **step3_engineStarted** – nurodo, kiek laiko trunka „Outlook“ pereiti iš veiksmo „appDidFinishLaunching“ prie programos modulio paleidimo, kuris tvarko duomenų saugojimą ir sinchronizavimą.

- **step4_runLoopFirstIdle** – nurodo, kiek laiko trunka „Outlook“ pereiti nuo veiksmo „engineStarted“ prie būsenos, kai nebėra papildomų darbų, kuriuos reikėtų baigti.

- **total_time** – nurodo, kiek laiko trunka „Outlook“ baigti paleisties procesą.

#### <a name="dnslookupop"></a>DnsLookupOp

Renkama, kai vartotojas bando atidaryti IRM apsaugotą dokumentą ar taikyti IRM apsaugas.  Joje yra informacija, reikalinga tinkamai nustatyti ir diagnozuoti problemas, įvykusias atliekant DNS informacijos peržvalgos operaciją. 

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas.

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.ApplicationScenarioId** – programos pateiktas scenarijaus ID

- **RMS.Duration** – bendras operacijos baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia operacija, jei tokia yra

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.LicenseFormat** – licencijos formatas: Xrml arba Json

- **RMS.NoOfDomainsSearched** – ieškotų domenų skaičius    

- **RMS.NoOfDomainsSkipped** – praleistų domenų skaičius 

- **RMS.Result** – operacijos sėkmė arba nesėkmė

- **RMS.ScenarioId** – scenarijaus ID, kurį apibrėžia teisių valdymo tarnybos klientas

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.ServerType** – teisių valdymo tarnybos tipas 

- **RMS.StatusCode** – operacijos rezultato būsenos kodas

#### <a name="firstvisible"></a>first.visible

Šis įvykis leidžia mums nustatyti, kada vartotojas pirmą kartą tikslingai paleido programą. Šis įvykis reikalingas siekiant užtikrinti sėkmingą programos darbą originaliosios įrangos gamintojo (OĮG) versijose.

Renkami šių laukų duomenys:

- **is_oem** – lauko sekimas, kuris nurodo, ar programa paleista OĮG variante

- **is_system_install** – laukas, sekantis iš anksto įdiegto ypatybių failo, kuris nurodo, kad tai OĮG įdiegtis, buvimą 

- **manufacturer** – įrenginio gamintojas

- **model** – įrenginio modelis

- **systemFlagSet** – „Android“ sistemos žymė (ApplicationInfo.FLAG_SYSTEM), kuri nurodo, ar programa buvo įdiegta kaip įrenginio sistemos atvaizdo dalis

#### <a name="getuserop"></a>GetUserOp

Renkama, kai vartotojas bando atidaryti IRM apsaugotą dokumentą ar taikyti IRM apsaugas.  Joje yra informacija, reikalinga tinkamai nustatyti ir diagnozuoti problemas, įvykusias atliekant vartotojo sertifikatų gavimo operaciją. 

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.ApplicationScenarioId** – programos pateiktas scenarijaus ID

- **RMS.ContentId** – turinio ID

- **RMS.Duration** – bendras operacijos baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia operacija

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.LicenseFormat** – licencijos formatas: Xrml arba Json

- **RMS.Result** – operacijos sėkmė arba nesėkmė

- **RMS.ScenarioId** – scenarijaus ID, kurį apibrėžia teisių valdymo tarnybos klientas

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.ServerType** – teisių valdymo tarnybos tipas 

- **RMS.StatusCode** – operacijos rezultato būsenos kodas

- **RMS.Type** - vartotojo informacijos tipas

#### <a name="httpop"></a>HttpOp

Gaunamas, kai vartotojas bando atidaryti IRM apsaugotą dokumentą arba taikyti IRM apsaugą. Jame yra informacija, būtina norint tinkamai ištirti ir nustatyti problemas, kurios įvyksta atliekant http užklausos operaciją.

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje
    
- **AppInfo.Name** – programos pavadinimas

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.ApplicationScenarioId** – programos pateiktas scenarijaus ID

- **RMS.CallBackStatus** – autentifikavimo atskambinimo pateikto rezultato būsena

- **RMS.CallbackTime** – laikas, sunaudotas autentifikavimo atskambinimui 

- **RMS.CorrelationId** – HTTP užklausos sąsajos ID

- **RMS.DataSize** – HTTP užklausos duomenų dydis

- **RMS.Duration** – bendras operacijos baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia operacija, jei tokia yra

- **RMS.HttpCall** – nurodo, ar yra įdėtoji HTTP operacija 

- **RMS.LicenseFormat** – licencijos formatas: Xrml arba Json

- **RMS.OperationName** – operacijos pavadinimas

- **RMS.Result** – operacijos sėkmė arba nesėkmė

- **RMS.ScenarioId** – scenarijaus ID, kurį apibrėžia teisių valdymo tarnybos klientas

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.ServerType** – teisių valdymo tarnybos tipas 

- **RMS.StatusCode** – operacijos rezultato būsenos kodas

- **RMS.Url** – teisių valdymo tarnybos serverio URL

- **RMS.WinhttpCallbackStatus** – winhttp atskambinimo rezultato būsena

#### <a name="initialized"></a>Initialized

Leidžia analizuoti sąsajos, kuri leidžia mobiliosioms programėlėms gauti vartotojo ir privatumo parametrus iš „Office“ tarnybų, sveikatą, ir diagnozuoti ryšio ir privatumo parametrų tarnybos problemas.

Renkami šių laukų duomenys:

- **roamingSettingType** – identifikuoja vietą, iš kurios bandyta skaityti parametrus

#### <a name="ipccreateoauth2token"></a>IpcCreateOauth2Token

Gaunamas, kai vartotojas bando atidaryti IRM apsaugotą dokumentą arba taikyti IRM apsaugą. Jame yra informacija, būtina norint tinkamai ištirti ir nustatyti problemas, kurios įvyksta atliekant IpcCreateOauth2Token API iškvietimą.

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje
    
- **AppInfo.Name** – programos pavadinimas.

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.Duration** – bendras API iškvietimo baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia API iškvietimas, jei tokių yra

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.Result** – API iškvietimo sėkmė arba nesėkmė

- **RMS.ScenarioId** – API apibrėžtas scenarijaus ID

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.StatusCode** – pateikto rezultato būsenos kodas


#### <a name="officeandroidaccountstorageinfo"></a>Office.Android.AccountStorageInfo

Šis įvykis nustato MSA ir ADAL paskyrų skaičių registre ir bendrinamose nuostatose. Tai suteikia galimybę analizuoti duomenų saugyklos neatitikimus ir padeda mums stabilizuoti programų veiksmingumą.

Renkami šių laukų duomenys:

- **RegistryADALCount**– nurodo ADAL paskyrų skaičių registre.

- **RegistryADALCount**– nurodo MSA paskyrų skaičių registre.

- **Shareprefadalcount**– nurodo ADAL paskyrų skaičių bendrinamuose nuostatose.

- **Shareprefadalcount**– nurodo MSA paskyrų skaičių bendrinamuose nuostatose.


#### <a name="officeandroidandroidoffice16bootlatency"></a>Office.Android.AndroidOffice16BootLatency

Svarbu užfiksuoti programos veikimo metriką, atsižvelgiant į taikomosios programos atsakymo laiką nuo paleidimo.  „Microsoft“ šią funkciją naudoja fiksuoti laiką, skirtą taikomajai programai reaguoti ir aptikti scenarijus, kurie gali veikti paleidimo laiką programose „Word“, „Excel“ ar „PowerPoint“.

Renkami šių laukų duomenys:

- **AppLaunchResponsiveTimeInMilliSec** – taikomųjų programų paleidimo reagavimo laikas

- **AppSuspendedDuringBoot** – Bulio logika, rodanti, ar taikomoji programa buvo laikinai sustabdyta paleidimo metu

- **CollectionTime** – įvykio laikas

- **FileActivationAttempted** – Bulio logika, rodanti, ar buvo bandyta aktyvinti failą

- **FirstIdleOnAppThreadTimeInMilliSec** – taikomosios programos gijos laukimo trukmė

- **IsThisFirstLaunch** – Bulio logika, rodanti, ar taikomoji programa paleidžiama pirmą kartą

- **UserDialogInterruptionDuringBoot** – Bulio logika, rodanti, ar paleidimo metu buvo blokuojama vartotojo sąsaja

#### <a name="officeextensibilityofficejsappactivated"></a>Office.Extensibility.OfficeJS.Appactivated

Įrašo informaciją apie netikėtus „Office“ uždarymus. Tai leidžia mums nustatyti produkto gedimus ir pakibimus programoje, kad juos būtų galima pašalinti.

Renkami šių laukų duomenys:

  - **Data\_AirspaceInitTime:integer** – laikas, skirtas „Airspace Office“ komponentui inicijuoti

  - **Data\_AllShapes:integer -** Figūrų skaičius dokumente

  - **Data\_APIInitTime:integer -** Laikas, skirtas inicijuoti „Visio API“ moduliui

  - **Data\_AppSizeHeight –** prideda **-** lango dydžio aukštį

  - **Data\_AppSizeWidth –** prideda **-** lango dydžio plotį

  - **Data\_AppURL -** Papildinio URL; Registruoja parduotuvėje esančio papildinio visą URL ir ne parduotuvėje esančio papildinio URL domeną

  - **Data_Doc_AsyncOpenKind:long** – nurodo, ar debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

  - **Data\_AuthorsCount:integer -** Autorių, redagavusių dokumentą šio seanso metu, skaičius

  - **Data\_BackgroundPages:integer -** Foninių puslapių skaičius diagramoje

  - **Data\_BootTime:integer -** Laikas, kurio reikia „Visio“ įkelti

  - **Data\_Browser -** Naršyklės eilutė su informacija apie naršyklę, pvz., tipą, versiją

  - **Data\_ChildWindowMixedModeTime:integer -** Laikas, skirtas mišriam režimui „Visio“ (antrinis langas gali turėti skirtingas „DpiAwareness“ iš pirminio lango)

  - **Data\_CommentsCount:integer -** Dokumento komentarų skaičius

  - **Data\_ConnectionCount:integer -** Duomenų ryšio diagramoje skaičius

  - **Data\_ContentMgrInitTim:integer -** Laikas, skirtas turinio tvarkytuvui inicijuoti

  - **Data\_CreateMainFrameTime:integer -** Kuria pagrindinio rėmelio laiką 

  - **Data\_CreatePaletteTime:integer -** Laikas, skirtas pasaulio spalvų paletei sukurti

  - **Data\_DispFormatCount:integer -** Duomenų grafinių elementų diagramoje skaičius

  - **Data\_Doc\_Ext:string -** Dokumento plėtinys

  - **Data\_Doc\_Fqdn:string -** Vieta, kurioje saugomas dokumentas (SharePoint.com, live.net) galima tik „Office 365“ domenams

  - **Duomenų\_ad\_FqdnHash:string -** maišos, kur saugomas dokumentas

  - **Data\_Doc\_IsIncrementalOpen:bool-** : Ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

  - **Data\_Doc\_IsOpeningOfflineCopy:bool -** Ar dokumentas atidarytas iš vietinės talpyklos?

  - **Data\_Doc\_IsSyncBacked:bool-** „True“, kai tai yra serverio dokumentas, kuris yra vietoje, ir yra sinchronizuotas su serveriu (pvz., per „OneDrive“ arba ODB kliento programas)

  - **Data\_Doc\_Location:long-** : Iš anksto nustatytų reikšmių, kur saugomas dokumentas (vietoje, „SharePoint“, WOPI, tinkle ir kt.) rinkinys

  - **Data\_Doc\_LocationDetails:long -** Iš anksto nustatytų išsamesnės informacijos apie vietą (laikinas aplankas, atsisiuntimų aplankas, „One Drive“ dokumentai, „One Drive“ paveikslėliai) rinkinys

  - **Data\_Doc\_ResourceIdHash:string -** Debesyje saugomų dokumentų maišos išteklių identifikatorius

  - **Data_Doc_RtcType** – nurodo, kaip buvo nustatytas realaus laiko kanalas (RTC) dabartiniam failui (išjungtas, nepalaikomas, pagal pageidavimą, visada įjungta, ir t. t.).

  - **Data\_Doc\_ResourceIdHash:string -** Debesyje saugomų dokumentų maišos išteklių identifikatorius

  - **Data\_Doc\_SessionId:long -** Generuotas GUID, kuris identifikuoja dokumento egzempliorių to paties seanso metu

  - **Data\_Doc\_SizeInBytes:long -** Dokumento dydis baitais

  - **Data\_Doc\_SpecialChars:long -** Ilgasis šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

  - **Data\_Doc\_SyncBackedType –** dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba) 

  - **Data\_Doc\_UrlHash:string -** Debesyje saugomų dokumentų viso URL maiša

  - **Data\_DpiAwarenessTime:integer -** Laikas, kurio reikia įgalinti monitoriaus DPI informacijos surinkimo tarnybą 

  - **Data\_DurationToCompleteInMilliseconds:double-** Trukmė milisekundėmis, kol atliekamas įrašymas

  - **Data\_ErrorCode:int -** 0, jei sėkminga, sveikasis skaičius – gedimo atveju

  - **Data\_FailureReason:integer -** Asinchroninio įrašymo trikties priežastis

  - **Data\_FileExtension -** failo Atidarytos diagramos failo plėtinys

  - **Data\_FileHasDGMaster:bool -** „True“, kai faile yra duomenų grafinių elementų

  - **Data\_FileHasImportedData:bool -** „True“, kai faile yra importuotų duomenų

  - **Data\_FileHasShapesLinked:bool -** „True“, kai faile yra susietų figūrų su duomenimis

  - **Data\_FileIOBytesRead:int -** Perskaitytų baitų skaičius įrašant

  - **Data\_FileIOBytesReadSquared:int -** kvadratu pakelta duomenų reikšmė\_FileIOBytesRead

  - **Data\_FileIOBytesWritten:int -** bendras baitų kiekis išsaugant

  - **Data\_FileIOBytesWrittenSquared:int-** kvadratu pakelta duomenų reikšmė\_FileIOBytesWritten

  - **Data\_FilePathHash:binary** -dvejetainė failo kelio maiša

  - **Data\_FilePathHash: binary** - failo kelio GUID 

  - **Data\_FileSize -** Dokumento dydis baitais

  - **Data\_ForegroundPages:integer -** Foninių puslapių skaičius diagramoje

  - **Data\_ForegroundShapes:integer -** Sveikasis foninių puslapių figūrų skaičius

  - **Data\_GdiInitTime:integer -** Laikas, skirtas GDI moduliui inicijuoti

  - **Data\_HasCoauthUserEdit:bool -** „True“, jei dokumentas buvo redaguojamas bendro dokumentų kūrimo seanso metu

  - **Data\_HasCustomPages:bool -** „True“, jei dokumente yra pasirinktinių puslapių

  - **Data\_HasCustPatterns:bool -** „True“, jei faile yra pasirinktinių šablonų

  - **Data\_HasDynConn:bool -** „True“, jei dokumente yra dinaminis ryšys

  - **Data\_HasCustomPages:bool -** „True“, jei dokumente yra pakeisto mastelio puslapių

  - **Data\_HasUserWaitTime:bool -** „True“, jei failų dialogo langas rodomas įrašant

  - **Data\_InitAddinsTime:integer -** Laikas, kurio reikia COM priedui inicijuoti ir įkelti

  - **Data\_InitBrandTime:integer –** laikas, kurio reikia inicijuoti ekrano užsklandai ir prekės ženklo „Office“ komponentams

  - **Data\_InitGimmeTime:integer –** laikas, skirtas „Office“ komponentui inicijuoti

  - **Data\_InitLicensingTime:integer –** laikas, skirtas „Office“ komponento licencijai inicijuoti

  - **Data\_InitMsoUtilsTime:integer –** „MSOUTILS Office“ komponento inicijavimo laikas

  - **Data\_InitPerfTime:integer –** „Office“ komponento veikimo inicijavimo laikas

  - **Data\_InitTCOTime:integer –** laikas, reikalingas „Office“ komponento tvarkymo priemonei inicijuoti

  - **Data\_InitTrustCenterTime:integer –** laikas, skirtas „Office“ komponento patikimumo centrui inicijuoti

  - **Data\_InitVSSubSystemsTime:integer -** Laikas, reikalingas „Visio“ komponentams inicijuoti

  - **Data\_InternalFile:bool -** „True“, jei failas yra vidinis failas. pvz., šablonų rinkinys

  - **Data\_IsAsyncSave:bool -** „True“, jei įrašymas buvo asinchroninis

  - **Data\_IsAutoRecoveredFile:bool -** „True“, jei failas buvo automatiškai atkurtas

  - **Data\_IsEmbedded:bool -** „True“, jei „Visio“ failas buvo įdėtas į kitą programą

  - **Data\_IsInfinitePageDisabledForAllPages:bool -** jei neribotas puslapis išjungtas visiems dokumento, kurio vertė „True“, puslapiams

  - **Data\_IsIRMProtected:bool -** „True“, jei failas turi informacijos teisių apsaugą

  - **Data\_IsLocal:bool -** „True“, jei failas yra vietinis

  - **Data\_IsRecoverySave:bool -** „True“, jei sauga buvo inicijuota dėl atkūrimo

  - **Data\_IsShapeSearchPaneHiddenState:bool -** „True“, jei formos ieškos sritis dokumente buvo paslėpta

  - **Data\_IsSmartDiagramPresentInActivePageOfFile:bool -** bulio vertė „True“, jei vizualiosios diagramos išmanieji duomenys yra aktyviame puslapyje

  - **Data\_IsSmartDiagramPresentInActivePageOfFile:bool -** bulio vertė „True“, jei vizualiosios diagramos išmanieji duomenys yra aktyviame puslapyje.

  - **Data\_IsUNC:bool -** „True“, jei dokumento kelias atitinka universaliųjų vardų suteikimo sutartį

  - **Data\_LandscapePgCount:integer -** gulsčios padėties puslapių skaičius diagramoje 

  - **Data\_Layers:integer -** Sluoksnių diagramoje skaičius

  - **Data\_LoadProfileTime:integer –** laikas, kurio reikia, kad įkeltų „Office“ analizės įrankį

  - **Duomenų\_LoadRichEditTim:integer-** daug redaguoti komponentas įkėlimo laiką

  - **Data\_LoadVisIntlTime:integer -** Laikas, kurio reikia „Visio“ tarptautiniam DLL įkelti

  - **Data\_Location:integer -** Vietą failo, iš kurio buvo atidaryta 0 vietos, 1, tinklo, 2, „SharePoint“, 3 – žiniatinklio

  - **Data\_MasterCount:integer -** Ruošinių skaičius diagramoje

  - **Data\_MaxCoauthUsers:integer -** Maksimalus vartotojų skaičius, bendradarbiavusių bet kuriuo seansų Filesystem, Registry, First Party, SDX metu

  - **Data\_MaxTilesAutoSizeOn:integer -** Puslapio, kuriame įjungtas automatinis dydžio nustatymas, maksimalus plytelių skaičius

  - **Data\_MsoBeginBootTime:integer -** MSO paleidimo laikas

  - **Data\_MsoDllLoadTime:integer -** Laikas, kurio reikia MSO DLL įkelti

  - **Data\_MsoEndBootTime:integer -** Laikas, kurio reikia MSO įkelti

  - **Data\_MsoInitCoreTime:integer –** laikas, kurio reikia „MSO Office“ komponentui inicijuoti

  - **Data\_MsoInitUITime:integer –** laikas, skirtas „MSO Office“ komponento vartotojo sąsajai inicijuoti

  - **Data\_MsoMigrateTime:integer -** Laikas, kurio reikia vartotojo parametrams perkelti pirmo paleidimo metu, jei vartotojas atnaujino iš ankstesnės versijos

  - **Data\_NetworkIOBytesRead:int -** Perskaitytų tinklo baitų skaičius įrašant

  - **Data\_NetworkIOBytesReadSquared:int -** kvadratu pakelta duomenų reikšmė\_NetworkIOBytesRead

  - **Data\_NetworkIOBytesWritten:int -** Bendrasis tinklo baitų kiekis išsaugant

  - **Data\_NetworkIOBytesWrittenSquared :int-** kvadratu pakelta duomenų reikšmė NetworkIOBytesWritten

  - **Data\_OartStartupTime:integer –** laikas, skirtas „OART Office“ komponentui inicijuoti

  - **Data\_OleInitTime:integer –**„OLE Office“ komponento inicijavimo laikas

  - **Data\_OpenDurationTimeInMs:integer -** Trukmė milisekundėmis, kiek trunka atidaryti failą

  - **Data\_OriginatedFromTemplateID:integer -** Šablono, iš kurio sukurta diagrama, identifikatorius. Neapibrėžta (null) trečiosios šalies šablonų vertė

  - **Data\_Pages:integer -** Dokumento puslapių skaičius

  - **Data\_PositionToolbarsTime:integer -** Laikas, kurio reikia įrankių juostai patekti į vietą

  - **Data\_ReadOnly:bool -** „True“, jei failas yra tik skaitomas

  - **Data\_RecordSetCount:integer -** Diagramos įrašų rinkinio numeris

  - **Data\_RecoveryTime:integer -** Laikas, kurio reikia atkurtiems failams atidaryti

  - **Data\_ReviewerPages:integer -** Tikrintojų puslapių skaičius diagramoje

  - **Data\_RibbonTime:integer -** Laikas, kurio reikia būsenos juostai parodyti

  - **Data\_RoamingSettingsStartupTime:integer -** Laikas, kurio reikia sukurti ir įkelti visiems šiuo metu nustatytiems tarptinklinio ryšio „Visio“ parametrams

  - **Data\_SchemeMgrStartupTime:integer -** Laikas, kurio reikia schemos tvarkytuvui inicijuoti 

  - **Data\_SDX\_AssetId -** TIK parduotuvės papildiniams. OMEX suteikia papildiniams AssetId, kai jie siunčiami į parduotuvę

  - **Data\_SDX\_BrowserToken -** Identifikatorius, kuris yra naršyklės talpykloje

  - **Data\_SDX\_HostJsVersion -** Tai konkreti platformos versija Office.js (pvz., „Outlook“ web16.01.js) Jame yra „API Surface“ papildinių

  - **Data\_SDX\_Id -** Papildinio GUID, kuris išskirtinai jį identifikuoja

  - **Data\_SDX\_InstanceId -** Nurodo papildinį dokumentų poroje

  - **Duomenų\_SDX\_MarketplaceType -** Nurodo, iš kur papildinys įdiegtas

  - **Data\_SDX\_OfficeJsVersion -** Tai Office.js versija, kuri nukreips į konkrečią platformos versiją.

  - **Data\_SDX\_Version -** Papildinio versija

  - **Data\_ShellCmdLineTime:integer -** Laikas, kurio reikia norint apdoroti ir vykdyti bet kurias komandų eilutės komandas

  - **Data\_Size:long** - Failo dydis baitais

  - **Data\_StartEndTransactionTime:integer -** Laikas, reikalingas „Visio“ komponentams inicijuoti

  - **Data\_STNInitTime:integer -** Laikas, skirtas šablonų rinkinio langui inicijuoti

  - **Data\_Tag:string -** Unikalus identifikatorius nustatyti įvykio funkcijai Įrašyti kaip

  - **Data\_ThemeCount:integer -** Temų diagramoje skaičius

  - **Data\_TimeStamp -** Laiko žyma, kada dokumentas buvo uždarytas

  - **Data\_UIInitTime:integer -** UI inicijavimo laikas

  - **Data\_WasSuccessful:bool -** „True“, jei įrašymas pavyko

  - **Data\_WinLaunchTime:integer -** Laikas, per kurį paleista „Visio“ įkrovos užduočių sritis ir kt.

  
#### <a name="officeextensibilitysandboxodpactivationhanging"></a>Office.Extensibility.Sandbox.ODPActivationHanging

Renka, kai paleisti „Office“ papildinį užtrunka netikėtai ilgai (> 5 sek.). Naudojama „Office“ papildinių paleidimo triktims aptikti ir pašalinti.
 
Renkami šių laukų duomenys:

- **AppId** – taikomosios programos ID

- **AppInfo** – duomenys, susiję su papildinio tipu (užduočių sritis arba be sąsajos, arba turinys ir t. t.) ir teikėjo tipu (domenas, „SharePoint“, failų sistema ir t. t.)

- **AppInstanceId** – taikomosios programos egzemplioriaus ID 

- **AssetId** – taikomosios programos ištekliaus ID

- **"IsPreload**" – nurodo, ar papildinys yra iš anksto įkeltas, kad būtų pagerintas aktyvinimas

- **NumberOfAddinsActivated** – suaktyvintas papildinių skaitiklis

- **RemoterType** – nurodo nuotolinio elemento, kuris naudojamas norint suaktyvinti papildinį, tipą (patikimas, nepatikimas, „Win32webView“, patikimas UDF ir t. t.)

- **StoreType** – taikomosios programos kilmė

- **TimeForAuth** – autentifikacijai sugaištas laikas 

- **TimeForSandbox** – smėlio dėžėje praleistas laikas

- **TimeForServerCall** – laikas, praleistas skambinant į serverį 

- **TotalTime** – bendras praleistas laikas

- **UsesSharedRuntime** – nurodo, ar taikomoji programa naudoja „sharedRuntime“.

#### <a name="officelenslenssdklaunchlens"></a>Office.Lens.LensSdk.LaunchLens

Vartotojui paleidus „Lens“ vaizdams fiksuoti ar importuoti į kurią programą, paleidžiama „Lens“ SDK ir fiksuojamas šis įvykis. Paleidimo duomenys padeda nustatyti, kiek vartotojų / įrenginių paleidžia programą ir geriau suprasti funkcijų naudojimą. Tai padeda stebėti produkto vartotojų kiekius ir nustatyti tendencijų pokyčius, ieškoti ir taisyti produkto problemas.

Renkami šių laukų duomenys:

- **Data_isResumeSession** – ar programa paleista tęsiant, ar vartotojas paleido iš naujo. (Bulio logikos laukas) 

- **Data_launchPerf** – skaičius, nurodantis laiką, kurį truko programos paleidimas („Android“)

- **Data_LaunchWorkFlowItem** – laukas nurodo, ar programa paleista kameros ekrane ar redagavimo ekrane. 

- **Data_mediaCompressionFactor** – koeficientas, pagal kurį vaizdai suglaudinti naudojant programą.

- **Data_RecoveryMode** – Bulio logikos laukas, nurodantis, ar šis seansas buvo atkurtas po to, kai programa buvo nutraukta („Android“)

- **IsDexModeEnabled** – Bulio logika, nurodanti, ar įrenginys palaiko „Samsung Dex“ funkcijas.

- **IsEmbeddedLaunch** – Bulio logikos laukas, nurodantis, ar vartotojas paleido valdiklį vaizdo vaizde režimu.

- **IsInterimCropEnabled** – Bulio logikos laukas, nurodantis, ar vartotojas pasirinko rankiniu būdu apkarpyti kiekvieną vaizdą.

- **IsMultiWindowEnabled** – Bulio logikos laukas, nurodantis, ar galima paleisti programą padalintame ekrane.

- **LaunchPerf** – skaičius, nurodantis laiką, kurį truko programos paleidimas („iOS“)

- **RecoveryMode** – Bulio logikos laukas, nurodantis, ar šis seansas buvo atkurtas po to, kai programa buvo nutraukta („iOS“)

- **SDKMode** – režimas, kuriuo buvo užfiksuoti vaizdai.


#### <a name="officeofficemobileappactivationlaunch"></a>Office.OfficeMobile.AppActivation.Launch

Šis įvykis nustato pirmą kartą ir tolesnius aktyvinimus per išorinius paleidiklius, kurie aktyvina programą. Programos aktyvinimas įkelia tam tikras priklausomybes, kurios yra atsakingos už sklandų programos veikimą, o šis įvykis įrašys, jeigu buvo įkelta sėkmingai. Jis taip pat įrašys aktyvinimo šaltinį ir programos tikslą, kuris buvo atsakingas už programos aktyvinimą

Renkami šių laukų duomenys:

- **ActionName** – sveikųjų skaičių reikšmės susiejimas su veiksmo / funkcijos pavadinimu, kuris iškviečiamas iš aktyvinio taško.
 
- **ActivationType** – sveikųjų skaičių reikšmės susiejimas su aktyvinimo šaltiniu
  
- **IsActionTriggered** – Bulio logikos reikšmė, nustatanti, ar veiksmas buvo paleistas sėkmingai aktyvinus programą.

- **IsFirstRun** – Bulio logikos reikšmė, nustatanti, ar tai buvo pirmas programos paleidimas ar vėlesnis.
 

#### <a name="officeofficemobilefrefirstrunsetup"></a>Office.OfficeMobile.FRE.FirstRunSetup

Pirmasis programos paleidimas po įdiegimo suaktyvins šį kontrolinio signalo įvykį. Tai padės nustatyti diegimus ir automatinius versijos naujinimus iš senesnių programos versijų ir leis nustatyti automatinių versijos naujinimų klaidas, įskaitant bibliotekos įkėlimus ir išplėtimo / kalbos paketo atsisiuntimo triktis.

Renkami šių laukų duomenys:

- **IsFlightAssigned** – Boolean reikšmė nustatanti, ar vartotojas buvo iš bet kurios iš dalies paskirtos skrydžio grupės, kuri gali suaktyvinti tam tikras funkcijas.

- **IsFRELoadSuccessful** – sveikasis skaičius, nurodantis rezultatų būseną

#### <a name="officeonenoteandroidappappbootcomplete-officeandroidearlytelemetryappbootcomplete"></a>Office.OneNote.Android.App.AppBootComplete, Office.Android.EarlyTelemetry.AppBootComplete

*[Šis įvykis anksčiau buvo vadinamas OneNote.App.AppBootComplete.]*

Kritinis signalas, naudojamas siekiant užtikrinti, kad nauji vartotojai („Microsoft“ paskyra) gali sėkmingai paleisti ir naudoti „OneNote“ pirmą kartą.  Tai naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai.  Jei vartotojai negali paleisti programos pirmą kartą, suaktyvinamas didelės svarbos incidentas.

Renkami šių laukų duomenys: 

- **ACTIVITY_BOOT_TIME_IN_MS** – laikas, skirtas veiklos kūrimui baigti

- **ACTIVITY_NAME** – paleidimo metu atidarytos veiklos pavadinimas 

- **ANY_DIALOG_SHOWN** – nurodo, ar paleidimo metu rodomas koks nors dialogo langas

- **APP_SUSPEND_DURING_EVENT** – nurodo, ar paleidimas buvo iš anksto ištuštintas

- **APP_THREAD_CREATION_WAIT_TIME_TIME_FOR_APP_THREAD_CREATION** – laikas, skirtas taikomųjų programų gijoms kurti

- **AVAILABLE_MEMORY_IN_MB** – bendras įrenginyje pasiekiamos atminties kiekis 

- **AVG_SNAPSHOT_POPULATION_TIME** – vid. laikas, skirtas bloknoto struktūroms, kai naudojama taikomoji programa, iškviesti

- **BOOT_END_AT_VIEW** – veiklos subkategorijos pavadinimas (rodinio pavadinimas)

- **BOOT_SNAPSHOTS** – bloknoto struktūros, išrinktos taikomojoje programoje naudojamos paskyros (-ų) išrinkimui, duomenys

- **COREAPP_STARTUP_ACCOUNT_SETUP_STARTUP_ACCOUNT_SETUP** – laikas, skirtas SSO patirčiai patikrinti ir inicijuoti

- **CRASH_INTERACTION_DURING_BOOT > 0** – nurodo, ar taikomoji programa sugedo paskutinio seanso metu

- **DALVIK_HEAP_LIMIT_IN_MB** – nenaudojama

- **DELAY_LOAD_STICKY_NOTES** – nurodo, ar Priklijuojami lapeliai yra uždelsiami

- **FISHBOWL_SHOWN_DURING_EVENT** – nurodo atvejus, kai turinys nesinchronizuotas

- **HAS_LOGCAT_LOGGING_IMPACT_ON_BOOT** – nurodo, ar žurnalų turi įtakos paleidimo laikui

- **INIT_SNAPSHOT_DURATION** – laikas, skirtas bloknoto struktūros vartotojo paskyrai (-oms) gauti

- **IS_COLD_BOOT** – nurodo, ar taikomoji programa paleidžiama, kai taikomoji programa neveikė fone

- **IS_FIRST_LAUNCH** – nurodo, ar įrenginyje taikomoji programa buvo paleista pirmą kartą

- **IS_FOLDABLE_TYPE** – nurodo, ar įrenginys yra sulenkiamas

- **IS_PHONE** – nurodo, ar įrenginys yra telefonas arba planšetinis kompiuteris

- **IS_RECENT_PAGES_AVAILABLE_ON_FRAGMENT_CREATION** – nurodo, ar vartotojo sąsaja paruošta ir laukia, kol turinys bus pasiekiamas 

- **IS_REHYDRATE_LAUNCH** – nurodo, ar taikomoji programa buvo nutraukta sistemos

- **IS_UPGRADE** – nurodo, ar taikomoji programa paleidžiama atnaujinus versiją

- **JOT_MAIN_APP_CREATE_TIME_MAIN_APP_CREATE_TIME** – laikas, reikalingas sukurti JOT komponentą (bendrinto kodo komponentas) 

- **JOT_MAIN_APP_INIT_TIME_MAIN_APP_INIT_TIME** – laikas, skirtas JOT komponentui inicijuoti

- **LAUNCH_POINT** – nurodo, ar taikomoji programa atidaryta naudojant valdiklį, taikomosios programos piktogramą, hipersaitas, ar įjungtas bendrinimas ir t. t.

- **MSO_ACTIVATION_TIME_ACTIVATION_TIME** – laikas, skirtas MSO inicijuoti

- **NATIVE_LIBRARIES_LOAD_TIME** – laikas, skirtas bibliotekoms įkelti

- **NAVIGATION_CREATE_TO_NAVIGATION_RESUME_CREATE_TO_NAVIGATION_RESUME** – laikas, skirtas naršymui baigti

- **NAVIGATION_RESUME_TO_BOOT_END_RESUME_TO_BOOT_END**– laikas, skirtas puslapio įkėlimo delsai po paleidimo išmatuoti

- **NAVIGATION_SET_CONTENT_VIEW_TIME_SET_CONTENT_VIEW_TIME** – laikas, skirtas turiniui pateikti

- **NUMBER_Of_RUNNING_PROCESSES** – nurodo veikiančių aktyvių procesų skaičių

- **NUMBER_OF_SNAPSHOTS** – bloknoto struktūros gavimo paleidimo metu skaičius

- **OFFICEASSETMANAGER_INITIALIZATION_TIME** – laikas, skirtas „ Asset Manager“ išskleisti ir inicijuoti

- **PROCESS_BOOT_TIME_IN_MS** – laikas, skirtas proceso kūrimui užbaigti

- **ROOT_ACTIVITY_CREATE_ACTIVITY_CREATE** – laikas, skirtas pereiti iš šakninio sluoksnio 

- **ROOT_ACTIVITY_DISK_CHECK_ACTIVITY_DISK_CHECK** – nenaudojama

- **ROOT_ACTIVITY_LAUNCH_NEXTACTIVITY_ACTIVITY_LAUNCH_NEXTACTIVITY** – nenaudojama

- **ROOT_ACTIVITY_PROCESS_INTENT_ACTIVITY_PROCESS_INTENT** – nenaudojama 

- **ROOT_ACTIVITY_SESSION_ACTIVITY_SESSION** – laikas, skirtas pereiti iš šakninio sluoksnio 

- **ROOT_TO_NAVIGATION_TRANSITION_TO_NAVIGATION_TRANSITION** – laikas, skirtas perėjimui iš šakninio sluoksnio tvarkyti

- **SNAPSHOT_PUBLISH_TO_RENDERING_END_PUBLISH_TO_RENDERING_END** – laikas turinio generavimui užbaigti

- **SPLASH_ACTIVITY_SESSION_ACTIVITY_SESSION** – laikas, skirtas krovimosi ekranui rodyti

- **SPLASH_TO_ROOT_TRANSITION_TO_ROOT_TRANSITION** – laikas, skirtas pereiti iš šakninio sluoksnio 

- **TIME_BETWEEN_PROCESS_BOOT_AND_ACTIVITY_BEGIN_IN_MS** – laikas tarp proceso ir veiklos sukūrimo 

- **TIME_TAKEN_IN_MS** – laikas, skirtas paleidimui užbaigti
 
- **TOTAL_MEMORY_IN_MB** – bendra įrenginio atmintis
 
- **USER_INTERACTED_DURING_EVENT** – nurodo, ar vartotojas sąveikavo paleidimo metu

#### <a name="officeonenoteandroidapponenoteappforeground-officeandroidearlytelemetryonenoteappforeground"></a>Office.OneNote.Android.App.OneNoteAppForeground, Office.Android.EarlyTelemetry.OneNoteAppForeground

*[Šis įvykis anksčiau buvo pavadintas OneNote.App.OneNoteAppForeground.]*

Signalas, naudojamas nurodyti, kad taikomoji programa „OneNote“ veikia fone.  Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. 

Renkami šių laukų duomenys: 

- Nėra

#### <a name="officeonenoteandroidapplaunch-officeandroidearlytelemetryapplaunch"></a>Office.OneNote.Android.AppLaunch, Office.Android.EarlyTelemetry.AppLaunch

*[Šis įvykis anksčiau buvo vadinamas OneNote.AppLaunch.]*

Kritinis signalas, naudojamas užtikrinti, kad „OneNote“ vartotojai gali sėkmingai paleisti taikomąją programą.  Telemetrija naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. 

Renkami šių laukų duomenys: 

- **ANDROID_SDK_VERSION** – užfiksuoja „Android“ SDK versiją

- **FirstLaunchTime** – įrašo laiką, kai taikomoji programa buvo pirmą kartą paleista

- **InstallLocation** – nurodo, ar taikomoji programa yra iš anksto įdiegta, ar atsisiųsta iš parduotuvės

- **is_boot_completed_ever** – nurodo, ar programa anksčiau buvo sėkmingai paleista įrenginyje

- **IS_DARK_MODE_ENABLED** – Bulio logikos reikšmė, kuri nurodo, ar įjungtas tamsusis programos režimas, ar ne

- **NewOneNoteUser** – nustatyto, ar vartotojas yra naujas vartotojas

#### <a name="officeoutlookdesktopexchangepuidandtenantcorrelation"></a>Office.Outlook.Desktop.ExchangePuidAndTenantCorrelation

Kartą per seansą renka vartotojo PUID ir nuomotojo identifikatorių. PUID ir nuomininko ryšys yra būtinas norint suprasti ir diagnozuoti „Outlook“ problemas, atsižvelgiant į nuomotoją.

Renkami šių laukų duomenys:

  - **CollectionTime** - Įvykio laiko žyma

  - **ConnId** - Ryšio identifikatorius: ryšio, analizuojančio PUID ir OMS nuomininko identifikatorių, identifikatorius

  - **OMSTenantId** – „Microsoft“ sugeneruotas unikalusis nuomotojo identifikatorius

  - **PUID** – „Exchange“ PUID, skirtas unikaliai identifikuoti vartotojus


#### <a name="officeoutlookmacmacolkactivationstate"></a>Office.Outlook.Mac.MacOLKActivationState

Renka informaciją apie taip, kaip „Outlook“ aktyvinama, tokią kaip prenumeratos arba bendrosios licencijos. Duomenys yra stebimi siekiant užtikrinti, kad nebūtų didelio trikčių skaičiaus padidėjimo. Taip pat analizuojame duomenis, kad rastume tobulintinas sritis. 

Renkami šių laukų duomenys:

- **SetupUIActivationMethod** – „Outlook“ aktyvinimo metodas, pavyzdžiui, prenumeratos arba bendrosios licencijos.

#### <a name="officepowerpointdocoperationopen"></a>Office.PowerPoint.DocOperation.Open 

Renkama, kai „PowerPoint“ atidaro failą. Pateikiama sėkmingo veikimo informacija, išsami gedimo informacija, našumo metrika ir pagrindinė informacija apie failą, įskaitant failo formato tipą ir dokumento metaduomenis. Ši informacija būtina norint užtikrinti, kad „PowerPoint“ gali sėkmingai atidaryti failus nemažinant našumo. Tai leidžia mums diagnozuoti bet kokias aptiktas problemas.

Renkami šių laukų duomenys:

  - **Data\_AddDocTelemetryResult -** Ar šis žurnalo įrašas turi visą reikiamą dokumento telemetriją (Data\_Doc\_\* laukus)

  - **Data\_AddDocumentToMruList -** Metodo AddDocumentToMruList vykdymo trukmė

  - **Data\_AlreadyOpened -** Ar šis dokumentas anksčiau buvo atidarytas (to paties proceso seanso kontekste)

  - **Data\_AntiVirusScanMethod -** Išankstinis nuskaitytų antivirusinių tipų reikšmių rinkinys (IOAV, AMSI, None ir kt.)

  - **Data\_AntiVirusScanStatus -** iš anksto nustatytų antivirusinės programos nuskaitymo, atliekamo atidarant kiekvieną dokumentą, reikšmių rinkinys (NoThreatsDetected, Failed, MalwareDetected ir kt.)

  - **Data\_AsyncOpenKind -** Iš anksto nustatytų asinchroninių parinkčių (Collab, ServerOnly, SyncBacked, NotAsync) rinkinys

  - **Data\_CancelBackgroundDownloadHr -** Ar dokumento atsisiuntimas buvo nutrauktas? Jei taip, koks buvo nutraukimo rezultatas?

  - **Data\_CheckForAssistedReadingReasons -** Metodo CheckForAssistedReadingReasons vykdymo trukmė milisekundėmis

  - **Data\_CheckForDisabledDocument -** Metodo CheckForDisabledDocument vykdymo trukmė milisekundėmis

  - **Data\_CheckForExistingDocument -** Metodo CheckForExistingDocument vykdymo trukmė milisekundėmis

  - **Data\_CheckIncOpenResult -** Metodo CheckIncOpenResult vykdymo trukmė milisekundėmis

  - **Data\_CheckLambdaResult -** Metodo CheckIncOpenResult vykdymo trukmė milisekundėmis

  - **Data\_CheckPackageForRequiredParts -** Metodo CheckPackageForRequiredParts vykdymo trukmė milisekundėmis

  - **Data\_CheckPackageForSpecialCases -** Metodo CheckPackageForSpecialCases vykdymo trukmė milisekundėmis

  - **Data\_CheckRequiredPartsLoaded -** Metodo CheckRequiredPartsLoaded vykdymo trukmė milisekundėmis

  - **Data\_CheckWebSharingViolationForIncOpen -** Metodo CheckWebSharingViolationForIncOpen vykdymo trukmė milisekundėmis
   
  - **Data_CloseAndReopenWithoutDiscard –** Ar dokumentas buvo uždarytas ir iš naujo atidarytas atidarymo proceso metu neatmetant.

  - **Data_ClpDocHasDrmDoc:bool** – ar dokumentas turi DRM dokumentą

  - **Data_ClpDocHasIdentity:bool** – ar dokumentas turi tapatybės informaciją (naudojamą gauti ir nustatyti slaptumo žymas)

  - **Data_ClpDocHasSessionMetadata:bool** – ar dokumente yra veikiantys seanso slaptumo žymos metaduomenys

  - **Data_ClpDocHasSpoMetadata:bool** – ar dokumente yra slaptumo žymos metaduomenys iš SPO per IMetadataCache

  - **Data_ClpDocHasSpoPackage:bool** – ar dokumente yra slaptumo žymos metaduomenys iš SPO per IPackage

  - **Data_ClpDocIsProtected:bool** – ar dokumentas yra apsaugotas IRM, ar ne

  - **Data_ClpDocMetadataSource:int** – išvardijimas, nurodantis, iš kur gaunami slaptumo žymos metaduomenys (IRM, OPC dalies, „SharePoint“ ir t. t.)

  - **Data_ClpDocNeedsUpconversion:bool** – ar dokumentai reikia konvertuoti slaptumo žymos duomenis iš custom.xml dalies

  - **Data_ClpDocNumFailedSetLabels:int** – slaptumo žymų, kurių nepavyko nustatyti dokumente, skaičius

  - **Data_ClpDocSessionMetadataDirty:bool** – ar dokumente yra veikiantys slaptumo žymos duomenys, kurie buvo suteršti

  - **Data_ClpDocWasInTrustBoundary:bool** – ar dokumentas buvo patikimo ribose (o tai leidžia bendraautoriaus dirbti dokumentuose, apsaugotuose slaptumo žymų)

  - **Data\_ContentTransaction -** Iš anksto nustatytų reikšmių rinkiniai, kai galima sukurti transakciją (AllowedOnLoadDocument, AllowedOnOpenComplete ir kt.)

  - **Data_CorrelationId -** GUID, kurį ProtocolHandler perdavė programai „PowerPoint“ telemetrijai susieti. ProtocolHandler yra atskiras procesas, kuris tvarko „Office“ saitus, skirtus OS.

  - **Data\_CppUncaughtExceptionCount:long –** veiklos veikimo metu neaptiktos vietinės išimtys

  - **Data\_CreateDocumentTimeMS -** Metodo CreateDocumentTimeMS vykdymo trukmė milisekundėmis

  - **Data\_CreateDocumentToken -** Metodo CreateDocumentTimeMS vykdymo trukmė milisekundėmis

  - **Data\_CreateDocumentToW -** Metodo CreateDocumentTimeMS vykdymo trukmė milisekundėmis

  - **Data\_CreateDocWindow -** Metodo CreateDocumentTimeMS vykdymo trukmė milisekundėmis

  - **Data\_CreateLocalTempFile -** Metodo CreateDocumentTimeMS vykdymo trukmė milisekundėmis

  - **Data\_DetachedDuration:long -** veiklos atskyrimo / neveikimo trukmė

  - **Data\_DetermineFileType -** Metodo DetermineFileType vykdymo trukmė milisekundėmis

  - **Data\_Doc\_AccessMode:long –** kaip buvo atidarytas šis dokumentas (tik skaityti / skaityti ir rašyti)

  - **Data\_Doc\_AssistedReadingReasons:long –** iš anksto apibrėžtų reikšmių, nurodančių dokumento atidarymo pagalbiniu skaitymo režimu priežastis, rinkinys

  - **Data_Doc_AsyncOpenKind:long** – nurodo, ar debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

  - **Data\_Doc\_ChunkingType:long –** kaip dokumentas saugomas programoje „SharePoint“

  - **Data\_Doc\_EdpState:long –** dokumento įmonės duomenų apsaugos būsena

  - **Data\_Doc\_Ext:string –** dokumento plėtinys

  - **Data\_Doc\_Extension:string –** dokumento plėtinys

  - **Data\_Doc\_FileFormat:long –** iš anksto nustatytų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

  - **Data\_Doc\_Fqdn:string –** vieta, kurioje saugomas dokumentas (SharePoint.com, live.net), galima tik „Office 365“ domenams

  - **Data\_Doc\_FqdnHash:string –** dokumento saugojimo vietos maiša

  - **Data\_Doc\_IdentityTelemetryId:string –** unikalusis vartotojo GUID

  - **Data\_Doc\_IdentityUniqueId:string –** unikalus tapatybės identifikatorius, kuris buvo naudojamas veiksmui su bendrinamais dokumentais

  - **Data\_Doc\_IOFlags:long –** šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

  - **Data\_Doc\_IrmRights:long –** iš anksto nustatytų reikšmių, nurodančių kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool –** teisinga, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

  - **Data\_Doc\_IsIncrementalOpen:bool –** ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

  - **Data\_Doc\_IsOcsSupported:bool –** ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

  - **Data\_Doc\_IsOpeningOfflineCopy:bool –** ar dokumentas atidarytas iš vietinės talpyklos?

  - **Data\_Doc\_IsSyncBacked:bool –** ar dokumentas atidarytas iš aplanko, naudojančio „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai

  - **Data\_Doc\_Location:long –** iš anksto apibrėžtų dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

  - **Data\_Doc\_LocationDetails:long –** iš anksto apibrėžtų išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

  - **Data\_Doc\_NumberCoAuthors:long –** bendraautorių skaičius dokumento atidarymo metu

  - **Data\_Doc\_PasswordFlags:long –** iš anksto apibrėžtų dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit)

  - **Data\_Doc\_ReadOnlyReasons:long –** iš anksto apibrėžtų dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

  - **Data\_Doc\_ResourceIdHash:string –** debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data_Doc_RtcType** – nurodo, kaip buvo nustatytas realaus laiko kanalas (RTC) dabartiniam failui (išjungtas, nepalaikomas, pagal pageidavimą, visada įjungta, ir t. t.).

  - **Data\_Doc\_ResourceIdHash:string -** Debesyje saugomų dokumentų maišos išteklių identifikatorius

  - **Data\_Doc\_ServerProtocol:long –** iš anksto apibrėžtų protokolo naudojimas kreiptis į serverį reikšmių rinkinys (Http, „Cobalt“, WOPI ir kt.)
 
  - **Data\_Doc\_ServerType:long –** iš anksto apibrėžtų serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI)

  - **Data\_Doc\_ServerVersion:long –** ar serveris pagrįstas „Office14“, „Office15“ arba „Office 16“?

  - **Data\_Doc\_SessionId:long -** Generuotas GUID, kuris identifikuoja dokumento egzempliorių to paties seanso metu

  - **Data\_Doc\_SharePointServiceContext:string –** nepermatoma eilutė, paprastai GridManagerID.FarmID. Tinkanti kliento ir serverio įvykių žurnalų koreliacijai

  - **Data\_Doc\_SizeInBytes:long –** dokumento dydis baitais

  - **Data\_Doc\_SpecialChars:long –** šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

  - **Data\_Doc\_StorageProviderId:string –** eilutė, nurodanti dokumento saugyklos teikėją, pvz., „DropBox“

  - **Data\_Doc\_StreamAvailability:long –** iš anksto apibrėžtų dokumentų srauto būsenos reikšmių rinkinys (available, permanently disabled, not available)

  - **Data\_Doc\_UrlHash:string –** debesyje saugomų dokumentų viso URL maiša

  - **Data\_Doc\_UsedWrsDataOnOpen:bool –** „True“, jei failas buvo atidarytas palaipsniui naudojant iš anksto pagrindinio kompiuterio talpykloje saugomus WRS duomenis

  - **Data\_Doc\_WopiServiceId:string –** WOPI tarnybos identifikatorius, pvz., „Dropbox“

  - **Data\_DownloadExcludedData -** Metodo DownloadExcludedData vykdymo trukmė milisekundėmis

  - **Data\_DownloadExcludedDataTelemetry -** Iš anksto nustatytų sinchroniškai laukiančių atsisiuntimo reikšmių būsena (SynchronousLogicHit, UserCancelled RunModalTaskUnexpectedHResult ir kt.)

  - **Data\_DownloadFileInBGThread -** Metodo DownloadFileInBGThread vykdymo trukmė milisekundėmis

  - **Data\_DownloadFragmentSize -** Fragmento dydis (atsisiųsta failo dalis), paprastai 3,5 MB

  - **Data\_ExcludedEmbeddedItems -** Suglaudintų dalių, kurios neįtrauktos į pirmą atvaizdavimą, skaičius

  - **Data\_ExcludedEmbeddedItems -** Suglaudintų dalių, kurios neįtrauktos į pirmą atvaizdavimą, bendrasis skaičius

  - **Data\_ExcludedRequiredItems -** Suglaudintų dalių, kurios neįtrauktos į pirmą atvaizdavimą, tačiau yra būtinos, skaičius

  - **Data\_ExcludedRequiredItemsSize -** Suglaudintų dalių, kurios neįtrauktos į pirmą atvaizdavimą, tačiau yra būtinos, bendrasis dydis

  - **Data\_ExecutionCount -** Kiek kartų buvo įvykdytas IncOpen protokolas

  - **Data\_FailureComponent:long –** iš anksto nustatytų verčių, dėl kurių komponentų įvyko šio protokolo triktis, rinkinys (Conflict, CSI, Internal ir kt.)

  - **Data\_FailureReason:long –** iš anksto nustatytų reikšmių, nurodančių trikties priežastis, rinkinys (FileIsCorrupt, BlockedByAntivirus ir kt.)

  - **Data\_FCreateNew -** Ar tai naujas tuščias dokumentas

  - **Data\_FCreateNewFromTemplate -** Ar tai naujas dokumentas, sukurtas naudojant šablonus

  - **Data_FErrorAfterDocWinCreation:boolean –** ar įvyko bet kokia klaida arba išimtis po dokumento lango sukūrimo.

  - **Data_FileIOClpState:int** – Bitset su reikšmėmis, susijusiomis su slaptumo žymų būsena. Pavyzdžiui, tai apima informaciją apie tai, ar bendradarbiavimas naudojant apsaugotas žymas yra įgalintas, ar dokumentas turi pritaikytą žymą iš dabartinio nuomotojo ir ar dokumentas yra apsaugotas IRM.

  - **Data\_FileUrlLocation -** Iš anksto nustatytų reikšmių, kur saugomas dokumentas (NetworkShare, LocalDrive, ServerOther ir kt.) rinkinys

  - **Data\_FirstSlideCompressedSize -** Suglaudintas pirmos skaidrės dalies (paprastai Slide1.xml) dydis

  - **Data_FIsAutoBackupFile-** ar šis failas yra automatinis atsarginės kopijos failas?

  - **Data\_FIsDownloadFileInBgThreadEnabled -** Ar įgalintas gijos atsisiuntimas fone?

  - **Data\_fLifeguarded:bool –** ar kada dokumentui buvo naudojama apsauginė funkcija (funkcija, automatiškai taisanti dokumento klaidas nepranešant vartotojui)?

  - **Data\_ForceReopenOnIncOpenMergeFailure -** Žyma, nurodanti, ar mes buvome priversti iš naujo atidaryti, kad sulietume triktį „Inc Open“

  - **Data\_ForegroundThreadPass0TimeMS -** (tik „Mac“) Bendras laikas, kurio reikia gijai paleisti fone pirmą kartą

  - **Data\_ForegroundThreadPass1TimeMS -** (tik „Mac“) Bendras laikas, kurio reikia gijai paleisti fone antrą kartą

  - **Data\_FWebCreatorDoc -** Ar dokumentas sukurtus naudojant šabloną arba funkciją Sparčioji pradžia

  - **Data\_HasDocToken -** Ar šiame dokumente yra CSI dokumento atpažinimo ženklas (vidaus kodas)

  - **Data\_HasDocument -** Ar šiame dokumente yra CSI dokumentas (vidaus kodas)

  - **Data\_InclusiveMeasurements -** Ar metodo įvertinimo trukmė įskaičiuota į antrinio metodo iškvietimo trukmę

  - **Data\_IncompleteDocReasons -** Iš anksto nustatytų reikšmių, kodėl atidarymas nebuvo baigtas (nežinoma, DiscardFailure ir kt.) rinkinys

  - **Data\_IncOpenDisabledReasons -** Iš anksto nustatytų priežasčių reikšmių, kodėl buvo išjungtas nuoseklus atidarymas, rinkinys

  - **Data\_IncOpenFailureHr -** Rezultatas, kodėl nepavyko nuoseklus atidarymas

  - **Data\_IncOpenFailureTag -** Žyma (kodo vietos žymiklis), kur nuoseklus atidarymas nepavyko

  - **Data\_IncOpenFallbackReason -** Kodėl nevykdomas IncOpen

  - **Data\_IncOpenRequiredTypes -** Iš anksto nustatytų turinio tipų reikšmių, reikalingų pirmam vaizdui generuoti (RequiredXmlZipItem, RequiredNotesMaster ir kt.), rinkinys

  - **Duomenų\_IncOpenStatus -** Iš anksto nustatytų nuoseklaus atidarymo būsenos reikšmių (bandyta, FoundExcludedItems, DocIncOpenInfoCreated ir kt.), rinkinys

  - **Data\_InitFileContents -** Metodo InitFileContents vykdymo trukmė milisekundėmis

  - **Data\_InitialExcludedItems -** Suglaudintų dalių, kurios tyčia neįtrauktos, skaičius

  - **Data\_InitialExcludedItemsSize -** Suglaudintų dalių, kurios tyčia neįtrauktos, skaičius

  - **Data\_InitializationTimeMS -** (tik „Mac“) Laikas, reikalingas inicijuoti

  - **Data\_InitialRoundtripCount -** Serverio atsakų, reikalingų pradiniam suglaudintam archyvui sukurti, skaičius

  - **Data\_InitLoadProcess -** Metodo InitLoadProcess vykdymo trukmė milisekundėmis

  - **Data\_InitPackage -** Metodo InitLoadProcess vykdymo trukmė milisekundėmis

  - **Data\_InitSecureReaderReasons -** Metodo InitLoadProcess vykdymo trukmė milisekundėmis

  - **Data\_IsIncOpenInProgressWhileOpen -** Tuo atveju, jei tas pats dokumentas yra atidarytas, yra protokolas „Inc open“, kuris veikia kartu su atviru protokolu?

  - **Data\_IsMultiOpen -** Ar mes palaikome kelių dokumentų atidarymus?

  - **Data\_IsOCS –** ar dokumentas OCS režimu yra paskutinės žinomos būsenos

  - **Data\_IsODPFile -** Ar dokumentas yra „Open Document“ formato, kurį naudoja „OpenOffice.org“

  - **Data\_IsPPTMetroFile -** Ar dokumentas yra metro (pptx) failo formato

  - **Duomenų\_LoadDocument –** Metodo LoadDocument vykdymo trukmė milisekundėmis

  - **Data\_MeasurementBreakdown -** Koduotas matavimo suskirstymas (sutrumpintas išsamus metodas)

  - **Data\_Measurements -** Užkoduoti matavimai

  - **Data\_MethodId -** Paskutinis metodas, kuris buvo vykdomas

  - **Data\_NotRequiredExcludedItems -** „PowerPoint“ paketo elementų, kurie nėra reikalingi pirmo vaizdo generavimo ir išskyrimo metu, bendras skaičius

  - **Data\_NotRequiredExcludedItemsSize -** „PowerPoint“ paketo elementų, kurie nėra reikalingi pirmo vaizdo generavimo ir išskyrimo metu, bendras dydis

  - **Data\_NotRequiredExcludedParts -** Suglaudintų dalių, kurios nėra reikalingos pirmo vaizdo generavimo ir išskyrimo metu, bendras skaičius

  - **Data\_NotRequiredExcludedPartsSize -** Suglaudintų dalių, kurios nėra reikalingos pirmo vaizdo generavimo ir išskyrimo metu, bendras skaičius

  - **Data_OngoingBlockingOpenCount –** tai šiuo metu veikiančių blokuojamų atvirųjų protokolų skaičius.
  
  - **Data_OngoingOpenCount –** tai šiuo metu veikiančių atvirųjų protokolų skaičius.

  - **Duomenų\_OpenCompleteFailureHR -** Rezultatas, kodėl nepavyko OpenComplete protokolas

  - **Data\_OpenCompleteFailureTag -** Žyma (kodo vietos žymiklis), kur OpenComplete protokolas nepavyko

  - **Data\_OpenLifeguardOption -** Iš anksto nustatytų gelbėjimo operacijos reikšmių (nėra, TryAgain, OpenInWebApp ir kt.) rinkinys

  - **Data\_OpenReason -** Iš anksto nustatytų reikšmių, kaip šis dokumentas buvo atidarytas (FilePicker, OpenFromMru, FileDrop ir kt.), rinkinys

  - **Data\_OSRPolicy -** SecureReader strategija

  - **Data\_OSRReason -** Priežastys, kodėl šis dokumentas atidarytas saugaus skaitytuvo režimu

  - **Data\_OtherContentTypesWithRequiredParts -** Nestandartiniai turinio tipai, kurie buvo neįtraukti, bet reikalingi pirmajam vaizdo generavimui

  - **Data\_PrepCacheAsync -** OcsiOpenPerfPrepCacheAsync žyma

  - **Data\_PreviousDiscardFailed -** Nurodo, kad ankstesnis atidarymo / uždarymo bandymas dokumente tinkamai nepaleido visų atminčių

  - **Data\_PreviousFailureHr -** Iš naujo atidarius tą patį dokumentą, koks buvo paskutinis nesėkmės rezultatas

  - **Data\_PreviousFailureTag -** Iš naujo atidarius tą patį dokumentą, kokia buvo paskutinės nesėkmės žyma (kodo vietos žymiklis)

  - **Data\_RemoteDocToken -** Ar nuotolinis atidarymas įgalintas (prototipo funkcija, leidžianti atidaryti failą iš tarnybos, o ne iš pagrindinio kompiuterio)?

  - **Data\_Repair -** Ar mes veikiame dokumentų taisymo režimu (sugadintiems dokumentams, kurie yra pataisomi)

  - **Data\_RequestPauseStats -** Kiek kartų reikalingas kodas, kad būtų pristabdytas įrašymas

  - **Data\_RequiredPartsComressedSize -** Bendras reikalingų „PowerPoint“ dalių dydis, kurio reikia pirmam vaizdui generuoti

  - **Data\_RequiredPartsDownload -** Bendras atsisiunčiamų „PowerPoint“ dalių dydis

  - **Data\_RequiredPartsRoundtripCount -** Bendras kelionės pirmyn ir atgal (iškvietimų į pagrindinį kompiuterį) skaičius, reikalingas norint gauti visas „PowerPoint“ dalis pirmam vaizdui generuoti

  - **Data\_RequiredZipItemsDownload -** Bendras suglaudintų elementų, reikalingų pirmam vaizdui generuoti, dydis

  - **Data\_RequiredZipItemsRoundtripCount -** Bendras kelionės pirmyn ir atgal (iškvietimų į pagrindinį kompiuterį) skaičius, reikalingas norint gauti visus reikalingus suglaudintus elementus pirmam vaizdui generuoti

  - **Data\_RoundtripsAfterMissingRequiredParts -** Bendras kelionės pirmyn ir atgal (iškvietimų į pagrindinį kompiuterį) skaičius, reikalingas aptikus, kad trūksta „PowerPoint“ dalių

  - **Data\_RoundtripsAfterMissingRequiredZipItems -** Bendras kelionės pirmyn ir atgal (iškvietimų į pagrindinį kompiuterį) skaičius, reikalingas aptikus, kad trūksta suglaudintų elementų

  - **Data\_RoundtripsAfterRequiredPackage -** Bendras kelionės pirmyn ir atgal (iškvietimų į pagrindinį kompiuterį) skaičius, reikalingas po paketo sukūrimo, skaičius

  - **Data\_RoundtripsAfterRequiredParts -** Bendras kelionės pirmyn ir atgal (iškvietimų į pagrindinį kompiuterį) skaičius, reikalingas atsisiuntus visas reikalingas dalis

  - **Data\_SetDocCoAuthAutoSaveable -** Metodo SetDocCoAuthAutoSaveable vykdymo trukmė milisekundėmis

  - **Data\_SniffedFileType -** Sugadinto dokumento siūlomo failo tipo pagrindimas

  - **Duomenų\_pradžios laikas –** Našumo skaitiklis pradėjus atidarymą

  - **Data\_StopwatchDuration:long –** visas veiklos laikas

  - **Data\_SyncSlides -** MetodoSyncSlides vykdymo trukmė milisekundėmis

  - **Data\_TimerStartReason -** Iš anksto nustatytų reikšmių, kaip paleidžiamas laikmatis (CatchMissedSyncStateNotification, WaitingForFirstDownload ir kt.), rinkinys

  - **Data\_TimeSplitMeasurements -** Koduotas matavimo suskirstymas (sutrumpintas išsamus metodas)

  - **Data\_TimeToInitialPackage -** Laikas, kurio reikia pradiniam paketui sukurti

  - **Data\_TimeToRequiredPackage -** Laikas, kurio reikia paketui sukurti

  - **Data\_TimeToRequiredParts -** Laikas, kurio reikia paketui sukurti su visomis reikalingomis dalimis

  - **Data\_TotalRequiredParts -** Bendras „PowerPoint“ dalių skaičius, reikalingų pirmo vaizdo generavimo metu

  - **Data\_UnknownRequiredParts -** Bendras „PowerPoint“ nestandartinių dalių skaičius, reikalingų pirmo vaizdo generavimo metu

  - **Data\_UnpackLinkWatsonId -** Watsono klaidos identifikatorius, kai dokumentas atidaromas per „Share OneDrive“ URL

  - **Data\_UnpackResultHint -** Iš anksto nustatytų reikšmių išpakavima, kad būtų galima bendrinti URL rezultatus (NavigateToWebWithoutError, UrlUnsupported, AttemptOpen ir kt.)

  - **Data\_UnpackUrl -** Metodo UnpackUrl vykdymo trukmė milisekundėmis

  - **Data\_UpdateAppstateTimeMS -** Metodo UpdateAppstate vykdymo trukmė milisekundėmis

  - **Data\_UpdateCoauthoringState -** Metodo UpdateAppstate vykdymo trukmė milisekundėmis

  - **Data\_UpdateReadOnlyState -** Metodo UpdateAppstate vykdymo trukmė milisekundėmis

  - **Data\_WACCorrelationId -** Atidarant failą naršyklėje, gaunami WebApp sąsajos žurnalai

  - **Data\_WasCachedOnInitialize -** Ar šis dokumentas inicijavimo metu buvo talpykloje 

  - **Data\_WBDirtyBeforeDiscard -** Ar prieš vėl atidarant dokumentą, darbo šaka tapo neatnaujinta

  - **Data\_ZRTOpenDisabledReasons -** Kodėl mums nepavyko atidaryti dokumento iš talpyklos (nulinė kelionė pirmyn ir atgal)

#### <a name="officepowerpointpptdesktopbootime"></a>Office.PowerPoint.PPT.Desktop.Bootime

Renka, kaip paleista „PowerPoint“. Jis apima „PowerPoint“ paleistį apsaugotame rodinyje, pagalbiniu skaitymo režimu nuo makro režimo, spausdinimo, naujo ir tuščio dokumento atkūrimo iki automatizavimo ir ar jis yra paleistas paspaudžiant. Taip pat renka kiek laiko užtrunka paleisti „PowerPoint“. Šie duomenys yra labai svarbūs norint užtikrinti, kad „PowerPoint“ veiktų tinkamai, kai įkeliama iš skirtingų režimų. „Microsoft“ naudoja šiuos duomenis, kad fiksuotų ilgą paleidimo laiką, kai atidaroma „PowerPoint“ iš skirtingų režimų.

Renkami šių laukų duomenys:

  - **AssistedReading -** pagalbimiu skaitymo režimu

  - **Automation -** automatizavimo režimu

  - **Benchmark -** paleidžiamas vykdymo kontrolinis etalonas

  - **Blank -** Tuščias dokumentas

  - **BootTime -** seanso paleidimo laikas

  - **Embedding -** Dokumento įdėjimas

  - **IsC2R -** Technologija „Spustelėkite ir naudokitės“

  - **IsNew -** Naujas dokumentas 

  - **IsOpen -** Atidaryta

  - **Macro1 -** Vykdoma makrokomanda

  - **Macro2 -** Vykdoma makrokomanda

  - **NonStandardSpaceInCmdLine** – Komandinėje eilutėje yra nestandartinė erdvė

  - **Print -** Spausdinamas dokumentas

  - **PrintDialog -** Spausdinamas dokumentas dialogo lange

  - **PrintDialog -** Spausdinamas dokumentas spausdintuve

  - **ProtectedView -** Apsaugotame rodinyje

  - **Regserver -** „PowerPoint“ registravimas kaip COM serverio

  - **Atkurti -** Atkurti dokumentą

  - **Rodyti -** Rodyti dokumentą

  - **Laikas -** Sesijos laikas

  - **UnprotectedView -** Neapsaugotame rodinyje

#### <a name="officepowerpointppthasuserediteddocument"></a>Office.PowerPoint.PPT.HasUserEditedDocument

Renkama, kai vartotojas pradeda redaguoti dokumentą. „Microsoft“ naudoja šiuos duomenis, kad apskaičiuotų aktyvius vartotojus, kurie redagavo dokumentą „PowerPoint“

Renkami šių laukų duomenys:

  - **CorrelationId** – Dokumento koreliacijos identifikatorius

#### <a name="officeprojectbootandopenproject"></a>Office.Project.BootAndOpenProject

„Project“ paleidžiamas atidarant failą. Šis įvykis rodo, kad vartotojas atidarė „Office Project“ su susijusiu failu. Jame yra svarbūs sėkmės duomenys, užtikrinantys, kad „Project“ gali būti paleista ir įkelti failą.

Renkami šių laukų duomenys:

  - **Data\_AlertTime -** Laikas, kai aktyvus įkėlimo dialogo langas.

  - **Data\_BootTime -** Laikas, kurio reikia „Project“ įkelti

  - **Data\_CacheFileSize -** Jei failas laikomas saugykloje, failo dydis

  - **Data\_EntDocType -** Failo, kuris buvo atidarytas, tipas

  - **Data\_IsInCache -** Ar šis atidarytas failas įrašytas į talpyklą

  - **Data\_LoadSRAs -** Ar vartotojas nori įkelti SRA

  - **Data\_Outcome -** viso Bendras paleidimo ir failo atidarymo laikas.

  - **Data\_OpenFromDocLib -** Ar „Project“ failas atidarytas iš dokumentų bibliotekos

  - **Data\_ProjectServerVersion -** Versija ir komponavimo versija, kurią šiuo metu naudoja „Project“

#### <a name="officeprojectbootproject"></a>Office.Project.BootProject

„Project“ paleidžiamas neatidarant failo. Šis įvykis rodo, kad vartotojas atidarė „Office Project“ be susijusio failo. Jame yra svarbūs duomenys, užtikrinantys, kad „Project“ bus sėkmingai paleistas.

Renkami šių laukų duomenys:

  - **Data\_BootTime -** Laikas, kurio reikia „Project“ įkelti

  - **Data\_FileLoaded -** „False“, jei atidaroma ne vietoje arba naujas tuščias projektas

  - **Data\_IsEntOfflineWithProfile -** Jei vartotojai priklauso profesionaliam SKU ir prisijungę prie serverio

  - **Data\_IsEntOnline -** Jeigu „Project“ seansas prijungtas prie „Project“ serverio su įmonės funkcijomis

  - **Data\_IsEntOnline -** Jeigu „Project“ seansas prijungtas prie „Project“ serverio su įmonės funkcijomis

  - **Data\_ProjectServerVersion -** Versija ir komponavimo versija, kurią šiuo metu naudoja „Project“


#### <a name="officeprojectopenproject"></a>Office.Project.OpenProject

„Project“ atidaro failą. Šis įvykis nurodo vartotojui, kad jis tiesiogiai atidaro „Project“ failą. Jame yra svarbūs duomenys, užtikrinantys, kad „Project“ bus sėkmingai atidaromi failai.

Renkami šių laukų duomenys:

  - **Data\_AgileMode -** Nustatoma, ar projektas atidarytas kaip kaskadinė diagrama, ar kaip lankstus projektas

  - **Data\_AlertTime -** Laikas, kai aktyvus įkėlimo dialogo langas.

  - **Data\_CacheFileSize -** Jei failas laikomas saugykloje, failo dydis

  - **Data\_EntDocType -** Failo, kuris buvo atidarytas, tipas

  - **Data\_IsInCache -** Ar šis atidarytas failas įrašytas į talpyklą

  - **Data\_LoadSRAs -** Ar vartotojas nori įkelti SRA

  - **Data\_OpenFromDocLib -** Ar „Project“ failas atidarytas iš dokumentų bibliotekos

  - **Data\_Outcome -** viso Bendras paleidimo ir failo atidarymo laikas.

  - **Data\_Outcome -** viso Bendras paleidimo ir failo atidarymo laikas.

  - **Data\_ProjectServerVersion -** Versija ir komponavimo versija, kurią šiuo metu naudoja „Project“

#### <a name="officesessionidproviderofficeprocesssessionstart"></a>Office.SessionIdProvider.OfficeProcessSessionStart

Taikoma visoms „Office“ „Windows“ pagrįstomis programomis: win32 ir UWP

Renkami šių laukų duomenys:

- **OfficeProcessSessionStart** Siunčia pagrindinę informaciją į naują „Office“ seanso pradžią. Naudojamas norint suskaičiuoti unikalius seansus, matomus šiais įrenginiais. Jis naudojamas kaip pasikartojantis įvykis, kad užtikrintų, jog taikomoji programa paleista įrenginyje. Be to, tai yra svarbus visos programos patikimumo signalas

- **ProgramosSeansoVedikl** – konkrečios taikomosios programos seanso pradžios identifikatorius, naudojamas nuo proceso kūrimo pradžios ir iki proceso pabaigos. Jis yra suformuotas kaip standartinis 128 bitų GUID, tik sudarytas iš keturių dalių. Šios keturios dalys eilės tvarka yra (1) 32 bitų proceso ID (2) 16 bitų seanso ID (3) 16 bitų įkrovos ID (4) 64 bitų proceso sukūrimo laikas, išreikštas UTC 100 nsek.

- **processSessionId** - Atsitiktinai sugeneruotas žinynas, skirtas programos seansui identifikuoti 

- **UTCReplace_AppSessionGuid** - Pastovi Bulio logikos vertė. Visuomet „True“.

#### <a name="officesystemsessionhandoff"></a>Office.System.SessionHandoff

Nurodo, kad dabartinis „Office“ seansas yra perdavimo seansas. Tai reiškia, kad vartotojo prašymo atidaryti dokumentą tvarkymas perduodamas į tos pačios programos jau veikiantį egzempliorių.

Renkami toliau apibūdintų laukų duomenys.

- **ParentSessionId** – seanso, kuris perims vartotojų užklausos tvarkymą, ID.

#### <a name="officetelemetryengineisprelaunch"></a>Office.TelemetryEngine.IsPreLaunch

Tinka Office UWP taikomosioms programoms.  Šis įvykis sužadinamas, kai „Office“ programa paleidžiama pirmą kartą po atnaujinimo ar įdiegimo iš parduotuvės. Tai yra pagrindinės diagnostikos duomenų dalis, naudojama seansui stebėti, ar jis pradėtas.

Renkami šių laukų duomenys:

- **appVersionBuild** – taikomosios programos komponavimo versijos numeris.

- **appVersionMajor** – taikomosios programos pagrindinės versijos numeris.

- **appVersionMajor** – taikomosios programos papildomos versijos numeris.

- **appVersionRev** – taikomosios programos peržiūros versijos numeris.

- **sessionID** – atsitiktinai sugeneruotas GUID, skirtas nustatyti taikomosios programos seansą

#### <a name="officetelemetryenginesessionhandoff"></a>Office.TelemetryEngine.SessionHandOff

Taikoma „Win32“ „Office“ taikomosioms programoms.  Šis įvykis padeda suprasti, ar buvo sukurtas naujas seansas, kuris tvarkys vartotojų inicijuotą failo atidarymo įvykį. Tai svarbi diagnostinė informacija, naudojama patikimumo signalui gauti ir užtikrinti, kad programa veiktų taip, kaip tikėtasi.

Renkami šių laukų duomenys:

- **appVersionBuild** – taikomosios programos komponavimo versijos numeris.

- **appVersionMajor** – taikomosios programos pagrindinės versijos numeris.

- **appVersionMajor** – taikomosios programos papildomos versijos numeris.

- **appVersionRev** – taikomosios programos peržiūros versijos numeris.

- **sessionID** – atsitiktinai sugeneruotas GUID, skirtas nustatyti taikomosios programos seansą

- **parentSessionId** – atsitiktinai sugeneruotas GUID, skirtas nustatyti taikomosios programos seansą

#### <a name="officevisiovisioiosappboottime"></a>Office.Visio.VisioIosAppBootTime

Jis suaktyvinamas kiekvieną kartą, kai paleidžiama „Visio iOS“. Labai svarbu suprasti taikomosios programos „Visio iOS“ paleidimo rezultatus. Naudojama prasto veikimo trikčių diagnostikai. 

Renkami šių laukų duomenys:

- **Data_AppBootTime** – taikomosios programos paleidimo trukmė, išreikšta milisekundėmis.

#### <a name="officevisiovisioiosappresumetime"></a>Office.Visio.VisioIosAppResumeTime 

Šis įvykis paleidžiamas kiekvieną kartą, kai taikomoji programa „Visio iOS“ tęsia fokusavimą. Būtina išmatuoti taikomosios programos tęsimo našumą ir taikomosios programos „Visio iOS“ trikčių diagnostikos našumo problemas.

Renkami šių laukų duomenys:

- **Data_AppResumeTime** – programos trukmė iki tęsimo, išreikšta milisekundėmis.

#### <a name="officewordfileopenopencmdfilemrupriv"></a>Office.Word.FileOpen.OpenCmdFileMruPriv

Šis įvykis nurodo „Office Word“ atidaryti dokumentą iš vėliausiai naudoto (MRU) sąrašo. Jame taip pat yra svarbių failo atidarymo našumo duomenų ir yra programėlės pradžios įvykis vertinant iš vartotojo perspektyvos. Įvykis stebi, ar file-open-from-MRU veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti.

Renkami šių laukų duomenys:

- **Data_AddDocTelemRes** – nurodo, ar įvykyje galima tinkamai užpildyti kitų dokumentų telemetrijos susijusias reikšmes. Naudojama duomenų kokybės diagnostikai.

- **Data_BytesAsynchronous** – baitų (suglaudintų), kurie, kaip manoma, gali atidaryti failą, skaičius, nepaisant, ar mes juos gausime iki tol, kol vartotojas nori pradėti redaguoti arba galbūt įrašyti

- **Data_BytesAsynchronousWithWork** – baitų (suglaudintų), kuriuos naudodami galėtume atidaryti failą, skaičius, tačiau norint, kad tai įvyktų, reikės daug investuoti į kodą

- **Data_BytesSynchronous** – baitų (suglaudintų) skaičius, kuriuos privalome turėti prieš pradėdami atidaryti failą

- **Data_BytesUnknown** – baitų skaičius dokumento dalyse, kurių nesitikėjome rasti 

- **Data_DetachedDuration** – nurodo, kiek laiko gijoje nebuvo veiklos

- **Data_Doc_AccessMode** – nurodo, ar dokumentas yra skirtas tik skaityti, ar redaguojamas

- **Data_Doc_AssistedReadingReasons** – iš anksto nustatytų dokumento atidarymo pagalbiniu skaitymo režimu priežasčių reikšmių rinkinys

- **Data_Doc_AsyncOpenKind** – nurodo, ar debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

- **Data_Doc_ChunkingType** – elementai, naudojami nuosekliam dokumento atidarymui

- **Data_Doc_EdpState** – dokumentui taikomas elektroninių duomenų apsaugos parametras

- **Data_Doc_Ext** – dokumento plėtinys (docx, xlsb, pptx ir kt.)

- **Data_Doc_FileFormat** – failo formato protokolo versija

- **Data_Doc_Fqdn** – „OneDrive“ arba „SharePoint“ interneto domeno vardas

- **Data_Doc_FqdnHash** – kliento identifikuojamo domeno vardo vienpusė maiša

- **Data_Doc_IdentityTelemetryId** – vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša

- **Data_Doc_InitializationScenario** – įrašo, kaip dokumentas buvo atidarytas

- **Data_Doc_IOFlags** – informuoja apie į talpyklą įtrauktas žymes, naudotas nustatyti užklausos parinktis

- **Data_Doc_IrmRights** – veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kuri buvo taikyta dokumentui arba vartotojui

- **Data_Doc_IsIncrementalOpen** – žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

- **Data_Doc_IsOcsSupported** – žymė nurodanti, kad dokumentą palaiko bendradarbiavimo tarnyba

- **Data_Doc_IsOpeningOfflineCopy** – žymė, nurodanti, kad atidaryta autonominė dokumento kopija

- **Data.Doc.IsSyncBacked –** žymė, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

- **Data_Doc_Location** – nurodo tarnybą, pateikusią dokumentą („OneDrive“, „File Server“, „SharePoint“ ir kt.)

- **Data_Doc_LocationDetails** – nurodo įrenginyje saugomo dokumento žinomą aplanką

- **Data_Doc_NumberCoAuthors** – skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

- **Data_Doc_PasswordFlags** – nurodo, ar nustatytas skaitymo arba skaitymo / rašymo slaptažodžio žymių rinkinys

- **Data_Doc_ReadOnlyReasons** – dokumento atidarymo tik kaip skaitomo priežastys

- **Data.Doc.ResourceIdHash** – anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

- **Data_Doc_RtcType** – nurodo, kaip buvo nustatytas realaus laiko kanalas (RTC) dabartiniam failui (išjungtas, nepalaikomas, pagal pageidavimą, visada įjungta, ir t. t.).

- **Data.Doc.ServerDocId** – nekintamų anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti 

- **Data_Doc_ServerProtocol** – protokolo versija, naudojama norint susisiekti su tarnyba

- **Data.Doc.ServerType** – tarnybą siūlančio serverio tipas („SharePoint“, „OneDrive“, WOPI ir kt.)

- **Data_Doc_ServerVersion** – serverio versija, siūlanti tarnybą

- **Data_Doc_SessionId** – nustato konkretų dokumentų redagavimo seansą visame seanse

- **Data_Doc_SharePointServiceContext** – „SharePoint Online“ užklausų diagnostinė informacija

- **Data_Doc_SizeInBytes** – dokumento dydžio indikatorius

- **Data.Doc.SpecialChars** – dokumento URL specialiųjų simbolių indikatorius 

- **Data_Doc_SyncBackedType** – dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba)

- **Data_Doc_UrlHash** – vienpusė maiša, skirta „naïve“ dokumento identifikatoriui

- **Data_Doc_WopiServiceId** – apima unikalų WOPI tarnybos teikėjo identifikatorių

- **Data_EditorDisablingRename** – pirmojo redaktoriaus, dėl kurio buvo išjungtas pervardijimas, identifikatorius

- **Data_EditorsCount** – dokumento redaktorių skaičius

- **Data_ForceReadWriteReason** – sveikasis skaičius, nurodantis priežastį, kodėl failas buvo priverstinai atidarytas skaitymo / rašymo režimu

- **Data_FSucceededAfterRecoverableFailure** – nurodo, kad atidaryti pavyko pašalinus triktį, įvykusią atidarant dokumentą

- **Data_LastLoggedTag** – unikali kodo iškvietimo žymės vieta, naudojama nustatyti, kada dukart nepavyksta bandymas atidaryti (naudojama duomenų kokybės diagnostikai)

- **Data_LinkStyles** – nurodo, ar mes susieti su šablono stiliais

- **Data_MainPdod** – dokumento identifikatorius vykstant „Office Word“ procesui.

- **Data_Measurements** – užkoduota eilutė, kurioje pateiktas skirtingų dalių atidarymo laiko suskirstymas. Skirta našumui vertinti.

- **Data_MoveDisabledReason** – klaida, kuri yra išjungia dokumento perkėlimą

- **Data_MoveFlightEnabled** – nurodo, ar įjungta perkėlimo testavimo funkcija

- **Data_PartsUnknown** – dokumento dalių, iš kurių nepavyko gauti duomenų, skaičius

- **Data_RecoverableFailureInitiationLocationTag** – unikali kodo iškvietimo vietos žymė, naudojama vietai kode, kurioje stengiamės sutvarkyti failą prieš jį atidarant, identifikuoti

- **Data_RenameDisabledReason** – klaida, dėl kurios šiam dokumentui išjungiamas pervardijimas

- **Data_RenameFlightEnabled** – nurodo, ar įjungta pervardijimo testavimo funkcija

- **Data_SecondaryTag** – unikali kodo iškvietimo vietos žymė, naudojama papildomiems trikties duomenims atidaryti 

- **Data_TemplateFormat** – šablono failo, kuriuo pagrįstas dokumentas, formatas.

- **Data_UsesNormal** – nurodo, ar atidarytas dokumentas pagrįstas įprastu šablonu

- **PathData_Doc_StreamAvailability** – indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas arba išjungtas


#### <a name="officewordfileopenopenffileopenxstzcore"></a>Office.Word.FileOpen.OpenFFileOpenXstzCore

Šis įvykis nurodo, kad „Office Word“ atidaro dokumentą, kurį vartotojas dukart spustelėjo. Jame taip pat yra svarbių failo atidarymo našumo duomenų ir yra programėlės pradžios įvykis vertinant iš vartotojo perspektyvos. Įvykis stebi, ar funkcija file-open-from-file-double-click veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti.

Renkami šių laukų duomenys:

- **Data_AddDocTelemRes** – nurodo, ar įvykyje galima tinkamai užpildyti kitų dokumentų telemetrijos susijusias reikšmes. Naudojama duomenų kokybės diagnostikai
    
- **Data_BytesAsynchronous** – baitų (suglaudintų), kurie, kaip manoma, gali atidaryti failą, skaičius, nepaisant, ar mes juos gausime iki tol, kol vartotojas nori pradėti redaguoti arba galbūt įrašyti
    
- **Data_BytesAsynchronousWithWork** – baitų (suglaudintų), kuriuos naudodami galėtume atidaryti failą, skaičius, tačiau norint, kad tai įvyktų, reikės daug investuoti į kodą

- **Data_BytesSynchronous** – baitų (suglaudintų) skaičius, kuriuos privalome turėti prieš pradėdami atidaryti failą
    
- **Data_BytesUnknown** – baitų skaičius dokumento dalyse, kurių nesitikėjome rasti

- **Data_DetachedDuration** – nurodo, kiek laiko gijoje nebuvo veiklos

- **Data_Doc_AccessMode** – nurodo, ar dokumentas yra skirtas tik skaityti, ar redaguojamas

- **Data_Doc_AssistedReadingReasons** – iš anksto nustatytų dokumento atidarymo pagalbiniu skaitymo režimu priežasčių reikšmių rinkinys

- **Data_Doc_AsyncOpenKind** – nurodo, ar debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

- **Data_Doc_ChunkingType** – elementai, naudojami nuosekliam dokumento atidarymui

- **Data_Doc_EdpState** – dokumentui taikomas elektroninių duomenų apsaugos parametras

- **Data_Doc_Ext** – dokumento plėtinys (docx, xlsb, pptx ir kt.)

- **Data_Doc_FileFormat** – failo formato protokolo versija

- **Data_Doc_Fqdn** – „OneDrive“ arba „SharePoint“ interneto domeno vardas

- **Data_Doc_FqdnHash** – kliento identifikuojamo domeno vardo vienpusė maiša

- **Data_Doc_IOFlags** – informuoja apie į talpyklą įtrauktas žymes, naudotas nustatyti užklausos parinktis

- **Data_Doc_IdentityTelemetryId** – vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša

- **Data_Doc_InitializationScenario** – įrašo, kaip dokumentas buvo atidarytas

- **Data_Doc_IrmRights** – veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kuri buvo taikyta dokumentui arba vartotojui

- **Data_Doc_IsIncrementalOpen** – žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

- **Data_Doc_IsOcsSupported** – žymė nurodanti, kad dokumentą palaiko bendradarbiavimo tarnyba
    
- **Data_Doc_IsOpeningOfflineCopy** – žymė, nurodanti, kad atidaryta autonominė dokumento kopija

- **Data_Doc_IsSyncBacked** – žymė, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

- **Data_Doc_Location** – nurodo tarnybą, pateikusią dokumentą („OneDrive“, „File Server“, „SharePoint“ ir kt.)
    
- **Data_Doc_LocationDetails** – nurodo įrenginyje saugomo dokumento žinomą aplanką

- **Data_Doc_NumberCoAuthors** – skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

- **Data_Doc_PasswordFlags** – nurodo, ar nustatytas skaitymo arba skaitymo / rašymo slaptažodžio žymių rinkinys

- **Data_Doc_ReadOnlyReasons** – dokumento atidarymo tik kaip skaitomo priežastys

- **Data.Doc.ResourceIdHash** – anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

- **Data_Doc_RtcType** – nurodo, kaip buvo nustatytas realaus laiko kanalas (RTC) dabartiniam failui (išjungtas, nepalaikomas, pagal pageidavimą, visada įjungta, ir t. t.).

- **Data.Doc.ServerDocId** – nekintamų anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

- **Data_Doc_ServerProtocol** – protokolo versija, naudojama norint susisiekti su tarnyba

- **Data_Doc_ServerType** – tarnybą siūlančio serverio tipas („SharePoint“, „OneDrive“, WOPI ir kt.)
    
- **Data_Doc_ServerVersion** – serverio versija, siūlanti tarnybą 

- **Data_Doc_SessionId** – nustato konkretų dokumentų redagavimo seansą visame seanse

- **Data_Doc_SharePointServiceContext** – „SharePoint Online“ užklausų diagnostinė informacija

- **Data_Doc_SizeInBytes** – dokumento dydžio indikatorius

- **Data_Doc_SpecialChars** – dokumento URL arba kelio specialiųjų simbolių indikatorius

- **Data_Doc_StreamAvailability** – indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas arba išjungtas

- **Data_Doc_SyncBackedType** – dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba)

- **Data_Doc_UrlHash** – vienpusė maiša, skirta „naïve“ dokumento identifikatoriui

- **Data_Doc_WopiServiceId** – apima unikalų WOPI tarnybos teikėjo identifikatorių

- **Data_EditorDisablingRename** – pirmojo redaktoriaus, dėl kurio buvo išjungtas pervardijimas, identifikatorius

- **Data_EditorsCount** – dokumento redaktorių skaičius

- **Data_FSucceededAfterRecoverableFailure** – nurodo, kad atidaryti pavyko pašalinus triktį, įvykusią atidarant dokumentą

- **Data_ForceReadWriteReason** – sveikasis skaičius, nurodantis priežastį, kodėl failas buvo priverstinai atidarytas skaitymo / rašymo režimu
    
- **Data_LastLoggedTag** – unikali kodo iškvietimo žymės vieta, naudojama nustatyti, kada dukart nepavyksta bandymas atidaryti (naudojama duomenų kokybės diagnostikai)

- **Data_LinkStyles** – nurodo, ar mes susieti su šablono stiliais

- **Data_MainPdod** – dokumento identifikatorius vykstant „Office Word“ procesui.

- **Data_Measurements** – užkoduota eilutė, kurioje pateiktas skirtingų dalių atidarymo laiko suskirstymas. Skirta našumui vertinti.
    
- **Data_MoveDisabledReason** – klaida, kuri yra išjungia dokumento perkėlimą

- **Data_MoveFlightEnabled** – nurodo, ar įjungta perkėlimo testavimo funkcija

- **Data_PartsUnknown** – dokumento dalių, iš kurių nepavyko gauti duomenų, skaičius

- **Data_RecoverableFailureInitiationLocationTag** – unikali kodo iškvietimo vietos žymė, naudojama vietai kode, kurioje stengiamės sutvarkyti failą prieš jį atidarant, identifikuoti.

- **Data_RenameDisabledReason** – klaida, dėl kurios šiam dokumentui išjungiamas pervardijimas

- **Data_RenameFlightEnabled** – nurodo, ar įjungta pervardijimo testavimo funkcija

- **Data_SecondaryTag** – unikali kodo iškvietimo vietos žymė, naudojama papildomiems trikties duomenims atidaryti.

- **Data_TemplateFormat** – šablono failo, kuriuo pagrįstas dokumentas, formatas.

- **Data_UsesNormal** – nurodo, ar atidarytas dokumentas pagrįstas įprastu šablonu.


#### <a name="officewordfileopenopenifrinitargs"></a>Office.Word.FileOpen.OpenIfrInitArgs

Šis įvykis nurodo, kad „Office Word“ atidaro dokumentą naudojant COM aktyvinimą arba komandinę eilutę. Jame taip pat yra svarbūs failo atidarymo našumo duomenys ir yra programėlės pradžios įvykis vertinant iš vartotojo perspektyvos. Įvykis stebi, ar file-open-from-command-line veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti.

Renkami šių laukų duomenys:

  - **Data\_AddDocTelemRes –** nurodo, ar įvykyje galima tinkamai užpildyti kitų dokumentų telemetrijos susijusias reikšmes. Naudojama duomenų kokybės diagnostikai.

  - **Data\_BytesAsynchronous -** Baitų (suglaudintų), kurie, kaip manoma, gali atidaryti failą, skaičius, nepaisant, ar mes juos gausime, kol vartotojas nori pradėti redaguoti arba galbūt įrašyti.

  - **Data\_BytesAsynchronousWithWork -** Baitų (suglaudintų), kuriuos naudodami galėtume atidaryti failą, skaičius, tačiau norint, kad tai įvyktų, reikės daug investuoti į kodą

  - **Data\_BytesSynchronous -** Baitų (suglaudintų) skaičius, kuriuos privalome turėti prieš pradėdami atidaryti failą

  - **Data\_BytesUnknown –** baitų skaičius dokumentų dalyse, kurių nesitikėjome rasti.

  - **Data\_Doc\_AccessMode -** Dokumentas yra skirtas tik skaityti / redaguoti

  - **Data\_Doc\_AssistedReadingReasons –** iš anksto nustatytų dokumento atidarymo pagalbiniu skaitymo režimu priežasčių reikšmių rinkinys

  - **Data_Doc_AsyncOpenKind** – nurodo, ar debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

  - **Data\_Doc\_ChunkingType –** vienetai, naudojami nuosekliam dokumento atidarymui

  - **Data\_Doc\_EdpState -** Dokumentui taikomas elektroninių duomenų apsaugos parametras

  - **Data\_Doc\_Ext -** Dokumento plėtinys (docx / xlsb / pptx ir kt.)

  - **Data\_Doc\_FileFormat -** Failo formato protokolo versija

  - **Data\_Doc\_Fqdn –** „OneDrive“ arba „SharePoint“ interneto domeno vardas

  - **Data\_Doc\_FqdnHash –** kliento identifikuojamo domeno vardo vienpusė maiša

  - **Data\_Doc\_IOFlags -** Informuoja apie į talpyklą įtrauktas žymes, naudotas užklausos parinktims nustatyti 

  - **Data\_Doc\_IdentityTelemetryId -** Vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša

  - **Data\_Doc\_InitializationScenario -** Įrašo, kaip dokumentas buvo atidarytas

  - **Data\_Doc\_IrmRights –** veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kurie buvo taikyti dokumentui / vartotojui

  - **Data\_Doc\_IsIncrementalOpen -** Žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

  - **Data\_Doc\_IsOcsSupported -** Žyma, nurodanti, kad dokumentas palaikomas bendradarbiavimo tarnybos

  - **Data\_Doc\_IsOpeningOfflineCopy -** Žyma, nurodanti, kad autonominė dokumento kopija atidaryta

  - **Duomenų\_ad\_IsSyncBacked -** žyma, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

  - **Data\_Doc\_Location -** Nurodo, kuri tarnyba teikia dokumentą („OneDrive“, failų serveris, „SharePoint“)

  - **Data\_Doc\_LocationDetails -** Nurodo, kuriuose žinomuose aplankuose yra vietoje saugomų dokumentų

  - **Data\_Doc\_NumberCoAuthors -** Skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

  - **Data\_Doc\_PasswordFlags –** nurodo, ar nustatytas skaitymo arba skaitymo / rašymo slaptažodžio žymų rinkinys

  - **Data\_Doc\_ReadOnlyReasons -** Priežastys, kodėl dokumentas buvo atidarytas tik kaip skaitomas

  - **Data\_Doc\_ResourceIdHash -** Anonimizuotų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data_Doc_RtcType** – nurodo, kaip buvo nustatytas realaus laiko kanalas (RTC) dabartiniam failui (išjungtas, nepalaikomas, pagal pageidavimą, visada įjungta, ir t. t.).

  - **Data\_Doc\_ServerDocId -** Nekintamų anonimizuotų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_Doc\_ServerProtocol -** Protokolo versija, naudojama norint susisiekti su tarnyba

  - **Data\_Doc\_ServerType –** tarnybą siūlančio serverio tipas („SharePoint“, „OneDrive“, WOPI ir kt.)

  - **Data\_Doc\_ServerVersion -** Serverio versija, siūlanti tarnybą

  - **Data\_Doc\_SessionId -** Serverio versija, siūlanti tarnybą

  - **Data\_Doc\_SharePointServiceContext -** Diagnostinė informacija iš „SharePoint Online“ užklausų

  - **Data\_Doc\_SizeInBytes –** dokumento dydžio indikatorius

  - **Data\_Doc\_SpecialChars –** dokumento URL arba kelio specialiųjų simbolių indikatorius

  - **Data\_Doc\_StreamAvailability –** indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas arba išjungtas

  - **Data\_Doc\_SyncBackedType –** dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba)

  - **Data\_Doc\_UrlHash –** vienpusė maiša, skirta „naïve“ dokumento identifikatoriui

  - **Data\_Doc\_WopiServiceId -** Apima unikalų WOPI tarnybos teikėjo identifikatorių

  - **Data\_EditorDisablingRename -** Pirmojo redaktoriaus, dėl kurio buvo išjungtas pervardijimas, identifikatorius

  - **Data\_EditorsCount -** Dokumento redaktorių skaičius

  - **Data\_FSucceededAfterRecoverableFailure -** Nurodo, kad atidaryti pavyko pašalinus triktį, įvykusią atidarant dokumentą

  - **Data\_ForceReadWriteReason -** Sveikojo skaičiaus vertė, nurodanti priežastį, kodėl failas buvo priverstinai atidarytas skaitymo / rašymo režimu

  - **Data\_LastLoggedTag -** Unikali kodo iškvietimo žymės vieta, naudojama nustatyti, kada dukart nepavyksta bandymas atidaryti (naudojama duomenų kokybės diagnostikai)

  - **Data\_LinkStyles -** Nurodo, ar mes susieti su šablono stiliais

  - **Data\_MainPdod -** Dokumento identifikatorius vykstant „Office Word“ procesui.

  - **Data\_Measurements -** Užkoduota eilutė, kurioje yra skirtingų dalių atidarymo laiko suskirstymas. Skirtas diagnozuoti atvirai veiklai.

  - **Data\_MoveDisabledReason -** Klaida, kuri yra išjungia dokumento perkėlimą

  - **Data\_MoveFlightEnabled -** Ar įjungta perkėlimo testavimo funkcija

  - **Data\_PartsUnknown –** dokumentų dalių, iš kurių nepavyko gauti duomenų, skaičius

  - **Data\_RecoverableFailureInitiationLocationTag -** Unikali kodo iškvietimo vietos žymė, naudojama vietai kode, kurioje stengiamės sutvarkyti failą prieš jį atidarant, identifikuoti

  - **Data\_RenameDisabledReason -** Klaida, atsirandanti, kai pervardijimas šiam dokumentui išjungtas

  - **Data\_RenameFlightEnabled -** Ar įjungta pervardijimo testavimo funkcija

  - **Data\_SecondaryTag -** Unikali kodo iškvietimo vietos žymė, naudojama papildomiems trikties duomenims atidaryti.

  - **Data\_TemplateFormat -** Šablono failo formatas, kuriuo pagrįstas dokumentas.

  - **Data\_UsesNormal -** Nurodo, ar atidarytas dokumentas pagrįstas įprastu šablonu.


#### <a name="officewordfileopenopenloadfile"></a>Office.Word.FileOpen.OpenLoadFile

Šis įvykis nurodo, kad „Office Word“ atidaro dokumentą naudojant dialogo langą Atidaryti. Jame taip pat yra svarbių failo atidarymo našumo duomenų ir yra programėlės pradžios įvykis vertinant iš vartotojo perspektyvos. Įvykis stebi, ar file-open-from-the-open-file-dialogas veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti.

Renkami šių laukų duomenys:

- **Data_AddDocTelemRes** – nurodo, ar įvykyje galima tinkamai užpildyti kitų dokumentų telemetrijos susijusias reikšmes. Naudojama duomenų kokybės diagnostikai.

- **Data_BytesAsynchronous** – baitų (suglaudintų), kurie, kaip manoma, gali atidaryti failą, skaičius, nepaisant, ar mes juos gausime iki tol, kol vartotojas nori pradėti redaguoti arba galbūt įrašyti

- **Data_BytesAsynchronousWithWork** – baitų (suglaudintų), kuriuos naudodami galėtume atidaryti failą, skaičius, tačiau norint, kad tai įvyktų, reikės daug investuoti į kodą
    
- **Data_BytesSynchronous** – baitų (suglaudintų) skaičius, kuriuos privalome turėti prieš pradėdami atidaryti failą

- **Data_BytesUnknown** – baitų skaičius dokumento dalyse, kurių nesitikėjome rasti

- **Data_DetachedDuration** – nurodo, kiek laiko gijoje nebuvo veiklos

- **Data_Doc_AccessMode** – nurodo, ar dokumentas yra skirtas tik skaityti, ar redaguojamas

- **Data_Doc_AssistedReadingReasons** – iš anksto nustatytų dokumento atidarymo pagalbiniu skaitymo režimu priežasčių reikšmių rinkinys

- **Data_Doc_AsyncOpenKind** – nurodo, ar debesies dokumento talpykloje esanti versija buvo atidaryta, ir kuri asinchroninio atnaujinimo logika buvo naudojama.

- **Data_Doc_ChunkingType** – elementai, naudojami nuosekliam dokumento atidarymui

- **Data_Doc_EdpState** – dokumentui taikomas elektroninių duomenų apsaugos parametras

- **Data_Doc_Ext** – dokumento plėtinys (docx, xlsb, pptx ir kt.)

- **Data_Doc_FileFormat** – failo formato protokolo versija

- **Data_Doc_Fqdn** – „OneDrive“ arba „SharePoint“ interneto domeno vardas

- **Data_Doc_FqdnHash** – kliento identifikuojamo domeno vardo vienpusė maiša

- **Data_Doc_IdentityTelemetryId** – vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša

- **Data_Doc_InitializationScenario** – įrašo, kaip dokumentas buvo atidarytas

- **Data_Doc_IOFlags** – informuoja apie į talpyklą įtrauktas žymes, naudotas nustatyti užklausos parinktis

- **Data_Doc_IrmRights** – veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kuri buvo taikyta dokumentui arba vartotojui
    
- **Data_Doc_IsIncrementalOpen** – žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

- **Data_Doc_IsOcsSupported** – žymė nurodanti, kad dokumentą palaiko bendradarbiavimo tarnyba

- **Data_Doc_IsOpeningOfflineCopy** – žymė, nurodanti, kad atidaryta autonominė dokumento kopija

- **Data_Doc_IsSyncBacked** – žymė, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

- **Data_Doc_Location** – nurodo tarnybą, pateikusią dokumentą („OneDrive“, „File Server“, „SharePoint“ ir kt.)

- **Data_Doc_LocationDetails** – nurodo įrenginyje saugomo dokumento žinomą aplanką

- **Data_Doc_NumberCoAuthors** – skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

- **Data_Doc_PasswordFlags** – nurodo, ar nustatytas skaitymo arba skaitymo / rašymo slaptažodžio žymių rinkinys

- **Data_Doc_ReadOnlyReasons** – dokumento atidarymo tik kaip skaitomo priežastys

- **Data.Doc.ResourceIdHash** – anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

- **Data_Doc_RtcType** – nurodo, kaip buvo nustatytas realaus laiko kanalas (RTC) dabartiniam failui (išjungtas, nepalaikomas, pagal pageidavimą, visada įjungta, ir t. t.).

- **Data.Doc.ServerDocId** – nekintamų anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti 

- **Data_Doc_ServerProtocol** – protokolo versija, naudojama norint susisiekti su tarnyba

- **Data.Doc.ServerType** – tarnybą siūlančio serverio tipas („SharePoint“, „OneDrive“, WOPI ir kt.)

- **Data_Doc_ServerVersion** – serverio versija, siūlanti tarnybą

- **Data_Doc_SessionId** – nustato konkretų dokumentų redagavimo seansą visame seanse

- **Data_Doc_SharePointServiceContext** – „SharePoint Online“ užklausų diagnostinė informacija

- **Data_Doc_SizeInBytes** – dokumento dydžio indikatorius

- **Data_Doc_SpecialChars** – dokumento URL arba kelio specialiųjų simbolių indikatorius

- **Data_Doc_StreamAvailability** – indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas arba išjungtas

- **Data_Doc_SyncBackedType** – dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba)

- **Data_Doc_UrlHash** – vienpusė maiša, skirta „naïve“ dokumento identifikatoriui

- **Data_EditorDisablingRename** – pirmojo redaktoriaus, dėl kurio buvo išjungtas pervardijimas, identifikatorius

- **Data_EditorsCount** – dokumento redaktorių skaičius

- **Data_ForceReadWriteReason** – sveikasis skaičius, nurodantis priežastį, kodėl failas buvo priverstinai atidarytas skaitymo / rašymo režimu
    
- **Data_FSucceededAfterRecoverableFailure** – nurodo, kad atidaryti pavyko pašalinus triktį, įvykusią atidarant dokumentą

- **Data_LastLoggedTag** – unikali kodo iškvietimo žymės vieta, naudojama nustatyti, kada dukart nepavyksta bandymas įrašyti (naudojama duomenų kokybės diagnostikai)

- **Data_LinkStyles** – nurodo, ar mes susieti su šablono stiliais

- **Data_MainPdod** – dokumento identifikatorius vykstant „Office Word“ procesui.

- **Data_Measurements** – užkoduota eilutė, kurioje pateiktas skirtingų dalių atidarymo laiko suskirstymas. Skirta našumui vertinti.

- **Data_MoveDisabledReason** – klaida, kuri yra išjungia dokumento perkėlimą

- **Data_MoveFlightEnabled** – nurodo, ar įjungta perkėlimo testavimo funkcija

- **Data_PartsUnknown** – dokumento dalių, iš kurių nepavyko gauti duomenų, skaičius

- **Data_RecoverableFailureInitiationLocationTag** – unikali kodo iškvietimo vietos žymė, naudojama vietai kode, kurioje stengiamės sutvarkyti failą prieš jį atidarant, identifikuoti

- **Data_RenameDisabledReason** – klaida, dėl kurios šiam dokumentui išjungiamas pervardijimas

- **Data_RenameFlightEnabled** – nurodo, ar įjungta pervardijimo testavimo funkcija

- **Data_SecondaryTag** – unikali kodo iškvietimo vietos žymė, naudojama papildomiems trikties duomenims atidaryti

- **Data_TemplateFormat** – šablono failo, kuriuo pagrįstas dokumentas, formatas

- **Data_UsesNormal** – nurodo, ar atidarytas dokumentas pagrįstas įprastu šablonu


#### <a name="renewuserop"></a>RenewUserOp

Renkama, kai vartotojas bando atidaryti IRM apsaugotą dokumentą ar taikyti IRM apsaugas.  Joje yra informacija, reikalinga tinkamai nustatyti ir diagnozuoti problemas, įvykusias atliekant vartotojo sertifikatų atnaujinimo operaciją. 

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas.

- **AppInfo.Version** – programos versija

- **iKey** – registravimo serverio ID

- **RMS.ApplicationScenarioId** – programos pateiktas scenarijaus ID

- **RMS.Duration** – bendras operacijos baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia operacija, jei tokia yra

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.LicenseFormat** – licencijos formatas: Xrml arba Json

- **RMS.Result** – operacijos sėkmė arba nesėkmė

- **RMS.ScenarioId** – scenarijaus ID, kurį apibrėžia teisių valdymo tarnybos klientas

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.ServerType** – teisių valdymo tarnybos tipas 

- **RMS.StatusCode** – operacijos rezultato būsenos kodas

- **RMS.Type** - vartotojo informacijos tipas

#### <a name="servicediscoveryop"></a>ServiceDiscoveryOp

Gaunamas, kai vartotojas bando taikyti IRM apsaugas dokumentui. Jame yra informacija, būtina norint tinkamai ištirti ir nustatyti problemas, kurios įvyksta atliekant tarnybos aptikimo operaciją. 

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas.

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.ApplicationScenarioId** – programos pateiktas scenarijaus ID

- **RMS.Duration** – bendras operacijos baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia operacija, jei tokia yra

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.LicenseFormat** – licencijos formatas: Xrml arba Json

- **RMS.OperationName** – operacijos pavadinimas

- **RMS.Result** – operacijos sėkmė arba nesėkmė

- **RMS.ScenarioId** – scenarijaus ID, kurį apibrėžia teisių valdymo tarnybos klientas

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.ServerType** – teisių valdymo tarnybos tipas 

- **RMS.StatusCode** – operacijos rezultato būsenos kodas


### <a name="office-accessibility-configuration-subtype"></a>*„Office“ pritaikymo neįgaliesiems konfigūracijos potipis*

„Office“ pritaikymo neįgaliesiems funkcijos

#### <a name="officeaccessibilityaccessibilitytoolsessionpresencewin32"></a>Office.Accessibility.AccessibilityToolSessionPresenceWin32

Leidžia mums nustatyti, ar vartotojas turi pagalbinių technologijų įrankį ir jo pavadinimą. Tai leidžia mums suprasti, ar „Office“ vartotojui kyla konkrečių pagalbinių technologijų įrankio problemų.

Renkami šių laukų duomenys:

  - **Data\_Data\_Jaws -** Nurodo, ar „Jaws“ veikė seanso metu **Data\_Data\_Magic -** Nurodo, ar „Magic“ veikė seanso metu

  - **Data\_Data\_Magnify -** Nurodo, ar Didinimas veikė seanso metu

  - **Data\_Data\_Narrator -** Nurodo, ar Diktorius veikė seanso metu

  - **Data\_Data\_Narrator -** Nurodo, ar Diktorius veikė seanso metu

  - **Data\_Data\_SA -** Nurodo, ar SA veikė seanso metu

  - **Data\_Data\_Supernova -** Nurodo, ar „Supernova“ veikė seanso metu

  - **Data\_Data\_SuperNovaessSuite -** Nurodo, ar „SuperNovaAccessSuite“ veikė seanso metu

  - **Data\_Data\_WinEyes -** Nurodo, ar „WinEyes“ veikė seanso metu

  - **Data\_Data\_ZoomText -** Nurodo, ar Teksto mastelis veikė seanso metu

#### <a name="officeappledarkmode"></a>Office.Apple.DarkMode

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis praneša mums, ar vartotojas naudoja sistemą režime „DarkMode“ ir ar vartotojas perrašė programos „Office“ sistemos „DarkMode“ parametrus.  Naudojame šį įvykį, kad užtikrintume pritaikymą neįgaliesiems ir nustatytume prioritetu vartotojų patirties optimizavimą.

Renkami šių laukų duomenys:

- **Data_DarkModeIsEnabled** – nurodo, ar sistemoje įgalintas „DarkMode“.

- **Data_RequiresAquaSystemAppearanceEnabled** – ar programoje „Office“ perrašytas „DarkMode“.

#### <a name="officeapplehardwarekeyboardinuseapple"></a>Office.Apple.HardwareKeyboardInUse.Apple

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis praneša mums, kad vartotojas prijungia klaviatūrą prie savo mobiliojo įrenginio. Įvykis padeda patobulinti pritaikymą neįgaliesiems ir optimizuoti mūsų vartotojų patirtį.

Renkami šių laukų duomenys:

- **Data_CollectionTime** – laiko žyma, rodanti įvykio rinkimo laiką.

#### <a name="officeapplembuinstrumentdeviceaccessibilitysettings"></a>Office.Apple.MbuInstrument.DeviceAccessibilitySettings

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis renka skirtingų pritaikymų neįgaliesiems parinkčių būsenas, pasiekiamas seanso metu. Naudojame šį įvykį, kad užtikrintume pritaikymą neįgaliesiems ir nustatytume prioritetu vartotojų patirties optimizavimą.

Renkami šių laukų duomenys:

- **Data_AccessibilityContentSize** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_AssistiveTouchRunning** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_BoldTextEnabled** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_CollectionTime** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_DarkerSystemColorsEnabled** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_DifferentiateWithoutColor** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_GrayscaleEnabled** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_GuidedAccessEnabled** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_IncreaseContrast** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_InvertColorsEnabled** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_PreferredContentSizeCategory** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_ReduceMotionEnabled** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_ReduceTransparency** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_ReduceTransparencyEnabled** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_ShakeToUndeEnabled** – vėliavėlė, rodanti, ar šis parametras įgalintas. (Netinkama – naudojama tik senoms komponavimo versijoms.)

- **Data_ShakeToUndoEnabled** – vėliavėlė, rodanti, ar šis parametras įgalintas.

- **Data_SpeakScreenEnabled** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_SpeakSelectionEnabled** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_SwitchControlRunning** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_UAZoomEnabled** – vėliavėlė, rodanti, ar šis parametras įgalintas

- **Data_VoiceOverRunning** – vėliavėlė, rodanti, ar šis parametras įgalintas

#### <a name="officewordaccessibilitylearningtoolsreadaloudplayreadaloud"></a>Office.Word.Accessibility.LearningTools.ReadAloud.PlayReadAloud

Šis įvykis nurodo, ar „Office Word“ garsiai perskaito tekstą dokumente. Šis įvykis yra pasikartojantis naudojant pritaikymo neįgaliesiems funkciją, kuri leidžia „Microsoft“ įvertinti skaitymo garsiai būseną.

Renkami šių laukų duomenys:

  - **Data\_ParagraphCount -** Dokumento pastraipų skaičius

  - **Data\_Play -** Ar tai pirmas kartas, kai „Word“ perskaito garsiai

  - **Data\_ViewKind -** Dokumento peržiūros tipas

#### <a name="officewordaccessibilitylearningtoolsreadaloudstopreadaloud"></a>Office.Word.Accessibility.LearningTools.ReadAloud.StopReadAloud

Šis įvykis nurodo, ar „Office Word“ nustoja garsiai skaityti tekstą dokumente. Įvykis leidžia „Microsoft“ įvertinti garsaus skaitymo funkcijos būseną išmatuodamas darbo trukmę.

Renkami šių laukų duomenys:

  - Nėra

### <a name="privacy-subtype"></a>*Privatumo potipis*

„Office“ privatumo parametrai 

#### <a name="officeintelligentserviceprivacyconsentprivacyevent"></a>Office.IntelligentService.PrivacyConsent.PrivacyEvent

Šis įvykis nurodo vartotojo arba sistemos inicijuotą veiksmą, kuris yra „Office“ vartotojo privatumo funkcijų dalis. Jis suaktyvinamas privatumo pirmojo paleidimo dialogo languose, paskyros privatumo dialogo lange ir privatumo pranešimuose. Šis įvykis naudojamas norint suprasti: vartotojus, sutinkančius su „Office“ privatumo parametrais, vartotojus, keičiančius „Office“ privatumo parametrus, ir „Office“ privatumo parametrus, kurie atnaujinami vartotojo seansuose.

Renkami šių laukų duomenys:

  - **Data_ActionId –** vartotojo veiksmas privatumo dialogo lange

  - **Data_ControllerConnectedServicesState –** papildomų pasirinktinių prijungtųjų funkcijų vartotojo strategijos parametras

  - **Data_DownloadedContentServiceGroupState –** atsisiųsto turinio vartotojo parametras 
 
  - **Data_ForwardLinkId –** saitas į vartotojo scenarijaus privatumo dokumentaciją

  - **Data_HRESULT –** klaidų, įvykusių sąveikos su privatumo dialogo langu metu, įrašas

  - **Data_IsEnterpriseUser –** vartotojo licencijos kategorija

  - **Data_OfficeServiceConnectionState –** prijungtų tarnybų vartotojo parametras

  - **Data_RecordRegistry –** įmonės privatumo dialogo lango rodymo įrašas

  - **Data_Scenario –** pirmojo paleidimo scenarijus pagal vartotojo licenciją ir kategoriją

  - **Data_SeenInsidersDialog –** „Insider“ privatumo dialogo lango rodymo įrašas

  - **Data_SendTelemetryOption –** telemetrijai skirtas vartotojo parametras

  - **Data_SendTelemetryOptionPolicy –** telemetrijai skirtas vartotojo strategijos parametras

  - **Data_UserCategory –** vartotojo paskyros tipas  

  - **Data_UserCCSDisabled –** papildomų pasirinktinių prisijungtųjų funkcijų vartotojo nepaisymas

   - **Data_UserContentServiceGroupState –** vartotojo parametrai, skirti turiniui analizuoti

  - **Data_WillShowDialogs –** vartotojo, kuriam reikia matyti privatumo pirmojo paleidimo dialogo langus, įrašas



## <a name="product-and-service-performance-data-events"></a>Produktų ir tarnybų našumo duomenų įvykiai

Toliau pateikiami šios kategorijos duomenų potipiai:
- [Netikėtas taikomosios programos uždarymas (gedimas)](#unexpected-application-exit-crash-subtype)
- [Taikomosios programos funkcijų našumas](#application-feature-performance-subtype)
- [Taikomosios programos veiklos klaida](#application-activity-error-subtype)

### <a name="unexpected-application-exit-crash-subtype"></a>*Netikėtas taikomosios programos uždarymo (gedimas) potipis*

Nenumatytas programų uždarymas ir programos būsena, kai taip nutinka.

#### <a name="appstartupreason"></a>app.startup.reason

Šis įvykis leidžia aptikti ir išspręsti problemas, kai „Outlook“ užstrigo paleidžiant programą.  Šis įvykis apima informaciją apie tai, kodėl įvyko gedimas, kad galėtume greitai išspręsti problemą.

Renkami šių laukų duomenys: 

- **app_background_time** – trukmė, kaip ilgai programa buvo fone praeito seanso metu

- **startup_reason_type** – nurodo, kodėl programa paleidžiama, tai nurodys, ar ji buvo priverstinai išjungta, ar buvo kitų priežasčių. 

- **watch_status_info** – jei taikoma, seka toliau nurodytą informaciją. 

  - **is_watch_app_installed** – nustato, ar vartotojas turi įdiegtą „Watch“ programą

  - **is_watch_paired** – nustato, ar „iOS“ įrenginys susietas su laikrodžiu

  - **is_watch_supported_and_active** – nurodo, ar seanso metu palaikomas „Watch“ ir yra aktyvus

Šie laukai renkami tik „Outlook Mobile“, skirtoje „iOS“:

- **clean_exit_reason** – žodžių eilutė, nurodanti, kodėl sustabdyta programa, jei taip įvyko

- **is_agenda_user** – nurodo, ar vartotojas neseniai atidarė dienotvarkę, kas nurodo, ar mes rašote į diską paleisties metu

- **is_watch_supported_and_active** – nurodo, ar seanso metu palaikomas „Watch“ ir yra aktyvus


#### <a name="applicationcrash"></a>application.crash

Naudojama kritiniams programų gedimams ir padeda rinkti informaciją apie tai, kodėl programa sugedo ir kaip išvengti gedimo.

Renkami šių laukų duomenys: 

- **android.hardware.** – (pvz., android.hardware.bluetooth) aparatinės įrangos konfigūravimo reikšmės, kurias teikia „Android“ platforma

- **android.software.** – (pvz., android.software.device_admin) programinės įrangos konfigūravimo reikšmės, kurias teikia „Android“ platforma

- **android_version** – įrenginio „Android“ versijos pavadinimas, kurį nurodo android.os.Build.VERSION#RELEASE

- **application_package_name** – programos paketo pavadinimas, kurį nurodo android.content.Context#getPackageName()

- **application_stack_trace** – gedimų dėklo sekimas

- **application_version_code** – programos versijos kodas, kurį apibrėžė „Outlook“ programa

- **application_version_name** – programos versijos pavadinimas, kurį apibrėžė „Outlook“ programa 

- **com.** (pvz., com.google.android.feature.FASTPASS_BUILD, com.amazon.feature.PRELOAD, com.samsung.android.bio.face) gamintojo konfigūracijos reikšmės, kuras pateikė „Android“ platforma

- **crash_report_sdk** – SDK, jei norite siųsti gedimų žurnalus. Ledo ritulys arba „AppCenter“

- **crash_type**-crash_type yra „Java“, vietiniai, neesminiai tipai.

     - „java“ – jei gedimas įrašytas taikomųjų programų sluoksnyje.

     - „native “ – jei gedimas buvo įrašytas į taikomosios programos virtinį sluoksnį. 

     - neesminis – jei gedimas buvo įrašytas į bet kokios funkcijos derinimą. Taikomoji programa nesugenda, bet nusiųs neesminius gedimų žurnalus, kurie padės atlikti funkcijos derinimą.

- **device_brand** – įrenginio prekės ženklas (gamintojas ar operatorius), kurį nurodo android.os.Build#BRAND

- **device_ID** – įrenginio unikalusis identifikatorius (IMEI)

- **device_manufacturer** – įrenginio gamintojas, kurį nurodo android.os.Build#MANUFACTURER

- **device_model** – įrenginio modelis, kurį nurodo android.os.Build#MODEL

- **device_name** – įrenginio pavadinimas, kurį nurodo android.os.Build#DEVICE

- **device_total_memory** – numatytos bendrosios įrenginio atminties dydis, atsižvelgiant į failų sistemos statistiką.

- **glEsVersion** – „OpenGL“ įdėtosios sistemos versijos raktas


#### <a name="crashevent"></a>crash.event

Leidžia aptikti ir ištaisyti situacijas, kai įvyksta kritiniai programų gedimai, ir padeda rinkti informaciją apie tai, kodėl programa sugedo ir kaip išvengti gedimo.

Renkami šių laukų duomenys: 

- **crashTime** – gedimo data ir laikas, padedantis atlikti tyrimą

- **crash_time_from_start** – laikas, praėjęs nuo programos pradžios iki įvykusio gedimo, kad būtų lengviau atlikti tyrimą

- **exceptionName** – išimties, kuri paskatino gedimą, pavadinimas, kad būtų galima atlikti tyrimą

- **exception_reason** – išimties, kuri paskatino gedimą, priežastis, kad būtų galima atlikti tyrimą

- **hasHx** – nurodo, kad paskyra naudoja mūsų naują sinchronizavimo tarnybą, kad būtų galima aptikti sinchronizavimo tarnybos sukeltas problemas

- **incidentIdentifier** – unikalus gedimo ataskaitos ID, kad galėtume rasti atitinkamą problemą

- **isAppKill** – padeda suprasti, ar programa buvo nutraukta arba uždaryta įrenginyje

- **is_crashloop** – padeda mums suprasti, ar gedimas gali būti gedimų ciklas.

- **reportKey** – unikalusis programos diegimo ID, kad būtų galima atlikti tyrimą

- **signal** – signalas, sukėlęs gedimą, kad galėtume išsamiau ištirti šį gedimą


#### <a name="error"></a>Error

Leidžia suprasti, kaip kyla mobiliųjų įrenginių programų gedimai bandant gauti privatumo parametrus iš serverio.

Renkami šių laukų duomenys:

- **correlationId** – unikalusis tarnybos ryšio identifikatorius, dėl kurios įvyko klaida, kad galėtume nustatyti galimas problemas

- **errorCode** – identifikuoja susijusį klaidos kodą, gautą iš tarnybos, kuris gali būti naudojamas problemai diagnozuoti

- **exceptionType** – klaidos, su kuria susidūrė biblioteka gaudama parametrą, tipas

- **message** – identifikuoja iš tarnybos gautą klaidos pranešimą

- **roamingSettingType** – identifikuoja vietą, iš kurios bandyta skaityti parametrus

- **settingId** – parametras, kurį buvo bandoma gauti

#### <a name="officeappdomainunhandledexceptionhandlerfailed"></a>Office.AppDomain.UnhandledExceptionHandlerFailed

Renka bet kokių neapdorojamų išimčių informaciją naudodama duomenų srautinio duomenų siųstuvo programą. Šie duomenys naudojami programos sveikatai stebėti. Šis įvykis sugeneruojamas iš „Microsoft“ srautinio duomenų siųstuvo, skirto „Excel“ papildiniui.

Renkami šių laukų duomenys:

- **Exception** – Išimties iškvietimų rietuvė

- **Event Name** – Įvykio pavadinimas yra įvykio kategorija ir įvykio etiketė.

#### <a name="officeappleidentitydomainname"></a>Office.Apple.IdentityDomainName

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Šis įvykis naudojamas mūsų sistemos sveikatai stebėti, taip pat tiriant tam tikrų domenų vartotojų trikčių priežastis. Renkame domeną, kurį naudoja mūsų vartotojai autentifikavimo metu.  Naudojame šiuos duomenis, kad padėtų nustatyti ir išspręsti šias problemas, kurios gali atrodyti pernelyg darančios poveikį platesniame lygmenyje, bet kurios paaiškėja, kad daro poveikį tam tikram vartotojų domenui.

Renkami šių laukų duomenys:

- **Data_Domain** – autentifikavimui naudojamas domenas

- **Data_IdentityProvider** – autentifikavimo tapatybės teikėjo pavadinimas. (t. y. LiveId arba ADAL)

- **Data_IdentityProviderEnum** – autentifikavimo tapatybės teikėjo kodas. (Skaičius)

#### <a name="officeapplesystemhealthappexitmacandios"></a>Office.Apple.SystemHealthAppExitMacAndiOS

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Šis įvykis naudojamas „Office“ taikomųjų programų sveikatai stebėti, taip pat tirti trikčių priežastis. Mes renkame duomenis apie kiekvieną išėjimą iš programos, kad nustatyti, ar taikomoji programa išėjo sklandžiai.

Renkami šių laukų duomenys:

- **Data_AffectedProcessSessionID** – seanso, dėl kurio buvo išeita iš programos, identifikatorius.

- **Data_AffectedSessionBuildNumber** – papildoma taikomosios programos versija, kurioje buvo pastebėtas išėjimas iš programos.

- **Data_AffectedSessionDuration** – seanso trukmė nuo pradžios iki išėjimo

- **Data_AffectedSessionIDSMatch** – indikatorius, nurodantis telemetrijos sveikatą.

- **Data_AffectedSessionMERPSessionID** – telemetrijos sveikatos indikatorius.

- **Data_AffectedSessionOSLocale** – OS lokalė, po kurios buvo stebėtas išėjimas iš programos.

- **Data_AffectedSessionOSVersion** – OS versija, po kurios buvo stebėtas išėjimas iš programos.

- **Data_AffectedSessionResidentMemoryOnCrash** – nuolatinės atminties kiekis, kuris buvo sunaudotas įvykus išėjimui iš programos

- **Data_AffectedSessionStackHash** – identifikatorius, žymintis tam tikras įvykusias klaidas.

- **Data_AffectedSessionStartTime** – seanso pradžios laikas.

- **Data_AffectedSessionUAEType** – pastebėto išėjimo iš programos tipas (jei išėjimas nebuvo sklandus, šis kodas nurodo pastebėtą klaidos tipą)

- **Data_AffectedSessionVersion** – pagrindinė taikomosios programos versija, kurioje buvo pastebėtas išėjimas iš programos.

- **Data_AffectedSessionVirtualMemoryOnCrash** – virtualiosios atminties kiekis, kuris buvo sunaudotas įvykus išėjimui iš programos.

- **Data_ExitWasGraceful** – ar išėjimas iš programos buvo sklandus.

#### <a name="officeextensibilitycomaddinunhandledexception"></a>Office.Extensibility.COMAddinUnhandledException

Įvykis generuojamas, kai vartotojo „Office“ taikomųjų programų versijoje sugenda COM papildinys. 

Naudojama apskaičiuoti visuotiniam, su įmone nesusijusiam „Microsoft 365“ programų įmonėms „pritaikymui“; po to papildinys naudojamas kituose įrankiuose, pvz., „Readiness Toolkit“. Tai leidžia įmonės klientams patikrinti, ar jų organizacijose įdiegti papildiniai suderinami su naujausiomis „Microsoft 365“ programų įmonėms versijomis, ir atitinkamai suplanuoti jų plėtotes. 

Renkami šių laukų duomenys:

- **ScopeId** – taikoma dabartinės gijos apimtis

- **Method** – „Office“ metodas, kur įvyko išimtis

- **Interface** – „Office“ sąsaja, kur įvyko išimtis

- **AddinId** – papildinio klasės ID

- **AddinProgId** – nebenaudojama

- **AddinFriendlyName** – nebenaudojama

- **AddinTimeDateStamp** – papildinio laiko žyma iš DLL metaduomenų

- **AddinVersion** – nebenaudojama

- **AddinFileName** – nebenaudojama

- **VSTOAddIn** – ar papildinys yra VSTO

- **Add-inconnectFlag** – dabartinio įkėlimo veiksena

- **LoadAttempts** – bandymų įkelti papildinį skaičius

#### <a name="officeextensibilitycomaddinunhandledexceptionenterprise"></a>Office.Extensibility.COMAddinUnhandledExceptionEnterprise

Įvykis generuojamas, kai COM papildinys sugenda įmonės „Office“ taikomųjų programų versijoje.

Naudojama apskaičiuoti visuotiniam, su įmone nesusijusiam „Microsoft 365“ programų įmonėms „pritaikymui“; po to papildinys naudojamas kituose įrankiuose, pvz., „Readiness Toolkit“. Tai leidžia įmonės klientams patikrinti, ar jų organizacijose įdiegti papildiniai suderinami su naujausiomis „Microsoft 365“ programų įmonėms versijomis, ir atitinkamai suplanuoti jų plėtotes. 

- **ScopeId** – taikoma dabartinės gijos apimtis

- **Method** – „Office“ metodas, kur įvyko išimtis

- **Interface** – „Office“ sąsaja, kur įvyko išimtis

- **AddinId** – papildinio klasės ID

- **AddinProgId** – nebenaudojama

- **AddinFriendlyName** – nebenaudojama

- **AddinTimeDateStamp** – papildinio laiko žyma iš DLL metaduomenų

- **AddinVersion** – nebenaudojama

- **AddinFileName** – nebenaudojama

- **VSTOAddIn** – ar papildinys yra VSTO

- **Add-inconnectFlag** – dabartinio įkėlimo veiksena

- **LoadAttempts** – bandymų įkelti papildinį skaičius

#### <a name="officeextensibilitysandboxodpactivationheartbeat"></a>Office.Extensibility.Sandbox.ODPActivationHeartbeat

„Office“ papildiniai veikia smėlio dėžėje. Šis įvykis surenka kontrolinių signalų informaciją apie aktyvinimus. Kai papildinys sugenda, šis įvykis surenka informaciją, kodėl jis sugedo, jeigu su susijusi su mūsų smėlio dėžėje. Naudojama tiriant tai atvejais, kai problemas nurodo klientai.
 
Renkami šių laukų duomenys:

- **AppId** – taikomosios programos ID

- **AppInfo** – duomenys, susiję su papildinio tipu (užduočių sritis arba be sąsajos, arba turinys ir t. t.) ir teikėjo tipu (domenas, „SharePoint“, failų sistema ir t. t.)

- **AppInstanceId** – taikomosios programos egzemplioriaus ID 

- **AssetId** – taikomosios programos ištekliaus ID

- **ErrorCode** – bendras praleistas laikas

- **IsArm64** – nurodo, ar papildinio aktyvinimas vyksta programoje, imituojamoje ARM64 įrenginyje

- **IsAugmentationScenario** – nurodo, ar praplėtimo ciklas yra atsakingas už „Office“ sprendimų sistemos valdiklio inicijavimą

- **IsDebug** – nurodo, ar seansas yra derinimo seansas

- **"IsPreload**" – nurodo, ar papildinys yra iš anksto įkeltas, kad būtų pagerintas aktyvinimas.

- **IsWdagContainer** – nurodo, ar „Windows“ sargybos konteineryje vykdomas papildinys.

- **NumberOfAddinsActivated** – suaktyvintas papildinių skaitiklis

- **RemoterType** – nurodo nuotolinio elemento, kuris naudojamas norint suaktyvinti papildinį, tipą (patikimas, nepatikimas, „Win32webView“, patikimas UDF ir t. t.)

- **StoreType** – taikomosios programos kilmė

- **Tag** – nurodo, kur tiksliai kodas nepavyko, naudojant su juo susietą unikalią žymę.

- **UsesSharedRuntime** – nurodo, ar taikomoji programa naudoja „sharedRuntime“.


#### <a name="officeextensibilityvbatelemetrybreak"></a>Office.Extensibility.VbaTelemetryBreak

Įvykis, generuojamas, kai makrokomandas palaikantis failas susiduria su kompiliavimo arba vykdymo klaida

Kompiuterio „Analytics“: naudojama kaip skaitiklis apskaičiuojant konkrečių įmonių sveikatos būklę makrokomandų tipams (pvz., „Word“, „Excel“ makrokomandoms ir pan.), kurios naudojamos bandomajam rezultatui, jei papildinys „parengtas atnaujinti“ gamybos metu.

Renkami šių laukų duomenys:

- **TagId** – telemetrijos žymės ID

- **BreakReason** – nurodyta trikties priežastis (vykdymo, kompiliavimo, kita klaida)

- **SolutionType** – sprendimo tipas (dokumentas, šablonas, programos papildinys, COM papildinys)

- **Data.ErrorCode** – klaidos kodas, kurį nurodė VBA modulis


#### <a name="officefindtimeappfailedtostart"></a>Office.FindTime.AppFailedToStart

Surinkta, kai taikomoji programa nepasileidžia dėl netikėtos klaidos paleidimo metu. Naudojama sekti išimtis ir gedimus.  Padeda stebėti ir derinti taikomosios programos sveikatą.

Renkami šių laukų duomenys: 

- **DateTime** – laiko žyma, kada įvykis užregistruotas.

- **EventName** – registruojamo įvykio pavadinimas.

#### <a name="officeoutlookdesktophangbucketmetrics"></a>Office.Outlook.Desktop.HangBucketMetrics

Surenka „Outlook“ „pakibimo“ – unikalus „pakibimo“, praėjusio laiko iškvietimų rietuvės identifikatorius. Duomenys naudojami programėlės gedimams aptikti ir identifikuoti, siekiant nustatyti, ką reikia pataisyti būsimuose naujinimuose.

Renkami šių laukų duomenys:

  - **BucketId** - iškvietimų rietuvės maiša

  - **ElapsedTotal** – bendras iškvietimo laikas

  - **ElapsedHanging** – „pakibimo“ laikas iškviečiant

#### <a name="officeoutlookdesktophangreportingscopeperfmetrics"></a>Office.Outlook.Desktop.HangReportingScopePerfMetrics

Renka „Outlook“ pagrindiniams scenarijams – switchmodule, sendmailoutbox, openitemclassic, sendmailtransport – reikalingą laiką. Duomenys aktyviai stebimi, kad būtų pastebėtos neįprasto veikimo problemos. Jis naudojamas aptikti ir diagnozuoti veikimo problemas, taip pat su kiekvienu atnaujinimu pagerinti našumą.

Renkami šių laukų duomenys:

  - **ElapsedTotal** - Bendras šio iškvietimo laikas

  - **ScopeId** - funkcijos, kurioje yra deklaracija arba pasirinktinis pavadinimas, suteiktas pagal taikymo srities apibrėžimą, pavadinimas

#### <a name="officeoutlookdesktopwatsonbuckets"></a>Office.Outlook.Desktop.WatsonBuckets

Ši taisyklė kaupia gedimo informaciją iš įvykių žurnalų, kai „Outlook“ sugenda ankstesniame seanse.

Duomenys aktyviai stebimi, kad būtų pastebėtas neįprastas „pakibimas“. Ar jis naudojamas „pakibimams“ aptikti ir identifikuoti, siekiant nustatyti, ką reikia pataisyti būsimuose naujinimuose.

Renkami šių laukų duomenys:

  - **BucketId** - Iškvietimų rietuvės maiša

  - **ElapsedTotal** – bendras iškvietimo laikas

  - **ElapsedHanging** – „pakibimo“ laikas iškviečiant

#### <a name="officepowerpointsession"></a>Office.PowerPoint.Session

Renka kiekvieno „PowerPoint“ seanso funkcijos naudojimą. Šie duomenys naudojami apskaičiuoti „PowerPoint“ netikėto uždarymo santykį naudojant funkciją. „PowerPoint“ netikėto uždarymo santykis yra pagrindinis signalas, užtikrinantis, kad „PowerPoint“ veikia taip, kaip tikėtasi.

Renkami šių laukų duomenys:

  - **Flag** – seanso žymės

  - **Naudojimas** – funkcijų naudojimas

#### <a name="officepowerpointuaedialog"></a>Office.PowerPoint.UAE.Dialog

Surinkta kiekvieną kartą, kai „PowerPoint“ netikėtai uždaryta, kai „PowerPoint“ pagrindinio lango viršuje buvo atidarytas dialogo langas. Ši informacija yra labai svarbi norint pastebėti, kada „PowerPoint“ netikėtai uždaroma, nes aktyvus dialogo langas blokuoja „PowerPoint“ pagrindinį langą. „Microsoft“ naudoja šiuos duomenis, kad diagnozuotų problemą, siekiant užtikrinti kad „PowerPoint“ veikia tinkamai.

Renkami šių laukų duomenys:

  - **DlgCnt** – bendras atidarytų dialogo langų skaičius, kai seansas buvo pertrauktas

  - **DlgId** – atidarytų dialogo langų identifikatorius

  - **DlgId** – atidarytų dialogo langų identifikatoriaus tipas

  - **InitTime** – pertrauktų seansų inicijavimo laikas

  - **SessionId** – pertraukto seanso identifikatorius

  - **DlgId** – atidarytų dialogo langų identifikatorius

  - **Version** – pertraukto seanso versija

#### <a name="officepowerpointuaedocument"></a>Office.PowerPoint.UAE.Document

Renkama, kokia funkcija buvo naudota dokumente, kai „PowerPoint“ netikėtai uždaryta. Šios funkcijos apima skaidrių demonstraciją, dokumento atidarymą, įrašymą, redagavimą, bendraatorystę, išjungimą. Ši informacija yra labai svarbi norint pastebėti, kada „PowerPoint“ netikėtai uždaroma naudojimosi funkcija metu. „Microsoft“ naudoja šiuos duomenis, kad diagnozuotų problemą, siekiant užtikrinti kad „PowerPoint“ veikia tinkamai.

Renkami šių laukų duomenys:

  - **CoauthFlag** – bendraautorių žymių naudojimas

  - **CommandFlag** – dokumento pakeitimo žymės

  - **FileIOFlag** – failo IO naudojimi žymės

  - **InitTime** – pertrauktų seansų inicijavimo laikas

  - **Location** – dokumento vieta

  - **ServerDocId** – serverio dokumento identifikatorius

  - **SessionId** – pertraukto seanso identifikatorius

  - **UrlHash** – dokumento URL maiša

  - **Naudojimas** – funkcijų naudojimas

  - **Version** – pertraukto seanso versija

#### <a name="officepowerpointuaeopen"></a>Office.PowerPoint.UAE.Open

Renkama kiekvieną kartą, kai „PowerPoint“ netikėtai uždaroma atidarant dokumentą. Ši informacija yra labai svarbi norint pastebėti, kada „PowerPoint“ netikėtai uždaroma atidarant dokumentą. „Microsoft“ naudoja šiuos duomenis, kad diagnozuotų problemą, siekiant užtikrinti kad „PowerPoint“ veikia tinkamai.

Renkami šių laukų duomenys:

  - **FileUrlLocation** – dokumento URL vieta

  - **Flag** – atidaro žymes

  - **InitTime** – pertrauktų seansų inicijavimo laikas

  - **Location** – dokumento vieta

  - **OpenReason** – atidarymo priežastis

  - **ServerDocId** – serverio dokumento identifikatorius

  - **SessionId** – pertraukto seanso identifikatorius

  - **UrlHash** – dokumento URL maiša

  - **Version** – pertraukto seanso versija

#### <a name="officepowerpointuaesession"></a>Office.PowerPoint.UAE.Session

Renkama, kokią funkciją naudojote, kai „PowerPoint“ seansas buvo netikėtai uždarytas.  Ši informacija yra labai svarbi norint pastebėti, kada „PowerPoint“ netikėtai uždaroma. „Microsoft“ naudoja šiuos duomenis, kad diagnozuotų problemą, siekiant užtikrinti kad „PowerPoint“ veikia tinkamai.

Renkami šių laukų duomenys:

  - **Flag** – seanso žymės

  - **InitTime** – pertrauktų seansų inicijavimo laikas

  - **PreviousSessionId** – pertraukto seanso identifikatorius

  - **Naudojimas** – funkcijų naudojimas

  - **Version** – pertraukto seanso versija

#### <a name="officepowerpointuaeshutdown"></a>Office.PowerPoint.UAE.Shutdown

Renkama, kada „PowerPoint“ netikėtai uždaroma išjungiant. Ši informacija yra labai svarbi norint pastebėti, kada „PowerPoint“ netikėtai uždaroma išjungiant. „Microsoft“ naudoja šiuos duomenis, kad diagnozuotų problemą, siekiant užtikrinti kad „PowerPoint“ veikia tinkamai.

Renkami šių laukų duomenys:

  - **InitTime** – pertrauktų seansų inicijavimo laikas

  - **SessionId** – pertraukto seanso identifikatorius

  - **Stage** – išjungimo etapas

  - **Version** – pertraukto seanso versija

#### <a name="officepowerpointuaeslideshow"></a>Office.PowerPoint.UAE.SlideShow

Renkama, kada „PowerPoint“ netikėtai uždaroma išjungiant. Ši informacija yra labai svarbi norint pastebėti, kada „PowerPoint“ netikėtai uždaroma išjungiant. „Microsoft“ naudoja šiuos duomenis, kad diagnozuotų problemą, siekiant užtikrinti kad „PowerPoint“ veikia tinkamai.

Renkami šių laukų duomenys:

  - **InitTime** – pertrauktų seansų inicijavimo laikas

  - **Mode** – skaidrių demonstravimo režimas

  - **SessionId** – pertraukto seanso identifikatorius

  - **State** – skaidrių demonstravimo būsena

  - **Version** – pertraukto seanso versija


#### <a name="officeprogrammabilityaddinscomaddincrash"></a>Office.Programmability.Addins.COMAddInCrash 

Įvykis generuojamas, kai sugenda COM papildinys. Naudojama „Office“ papildinių pritaikymo ir patikimumo problemoms nustatyti. 

Renkami šių laukų duomenys:

- **AddinConnectFlag** – nurodo įkėlimo veikseną  

- **AddinDescriptionV2** – papildinio aprašas 

- **AddinFileNameV2** – faktinio papildinio DLL pavadinimas. Neapima failo vietos.

- **AddinFriendlyNameV2** – papildinio draugiškas vardas

- **AddinIdV2** – papildinio klasės ID (CLSID)

- **AddinProgIdV2** – papildinio programos ID 

- **AddinProviderV2** – papildinio teikėjas 

- **AddinTimeDateStampV2** – kompiliatoriaus laiko žyma

- **AddinVersionV2** – papildinio versija 

- **Interface** – gedimą sukėlusio papildinio COM sąsaja 

- **LoadAttempts** – kiek kartų buvo bandoma įkelti prieš gedimą 

- **Method** – papildinio, dėl kurio įvyko gedimas, COM metodas 

- **"OfficeArchitecture** " – „Office“ kliento architektūra

#### <a name="officeprogrammabilitytelemetryaddincrash"></a>Office.Programmability.Telemetry.AddInCrash

Įvykis generuojamas, kai įkeltas COM papildinys Ši informacija yra labai svarbi norint nustatyti, ar papildinys sukelia „Office“ programos gedimą. Jis naudojamas įvertinti visuotinio papildinio suderinamumą su „Office“ programomis.

Renkami šių laukų duomenys:

  - **CLSID** – papildinio klasės identifikatorius

  - **ConnectFlag** – dabartinio papildinio įkėlimo veiksena

  - **FileName** – papildinio failo vardas, be failo kelio

  - **FriendlyName** – papildinio draugiškas vardas

  - **Interface** – „Office“ sąsaja, kur įvyko išimtis

  - **LoadAttempts** – bandymų įkelti papildinį skaičius

  - **Method** – „Office“ metodas, kur įvyko išimtis

  - **OfficeApplication** – „Office“ programa, kur įvyko išimtis

  - **OfficeVersion** – „Office“ versija

  - **AddinProgId** – papildinio programos identifikatorius

#### <a name="officeprogrammabilitytelemetrymacrofileopened"></a>Office.Programmability.Telemetry.MacroFileOpened 

Suaktyvinama atidarant makrokomandą (VBA) turintį failą įrenginyje, kuriame IT administratorius naudojo „Office“ programas kaip tarnybą (OAAS), ir kai „Microsoft 365“ programos įmonėms buvo suaktyvintos su įmonės licencija. Įvykis naudojamas suprasti makrokomandą (VBA) turinčių failų sveiktą pas nuomotoją ir palyginti su Office.Programmability.Telemetry.VbaTelemetryBreak, kuris seka klaidas VBA turinčiuose failuose. 

Nepasirinkti jokie laukai.

#### <a name="officesystemsystemhealthungracefulappexitmacandios"></a>Office.System.SystemHealthUngracefulAppExitMacAndiOS

Taikoma sistemos įkrovos įvykiui, kuris fiksuoja nesklandų išėjimą iš programos, kad būtų galima tirti toliau.

Renkami šių laukų duomenys:

- **AffectedProcessAppBuild** – komponavimo versijos numeris

- **AffectedProcessAppBuildRevision** – komponavimo versijos tikslinimo numeris

- **AffectedProcessAppMajorVer** – pagrindinės taikomosios programos versijos numeris

- **AffectedProcessAppMinorVer** – papildomos taikomosios programos versijos numeris

- **AffectedProcessAppName** – taikomosios programos pavadinimas

- **AffectedProcessResidentMemoryOnCrash** – nuolatinė sugedusios programos atmintis

- **AffectedProcessUnsymbolicatedChecksum** – taikoma su dėklo maiša, siekiant užtikrinti simbolizaciją

- **AffectedProcessVirtualMemoryOnCrash** – sugedusios programos virtualioji atmintis

- **AffectedSessionDuration** – seanso trukmė iki gedimo, sekundėmis

- **AffectedSessionLongBuildNumber** – ilgasis komponavimo versijos numeris

- **CrashedProcessSessionID** – taikomosios programos gedimo proceso seanso ID

- **DetectionTime** – taikomosios programos gedimo data ir laikas
    
- **DeviceModel** – aparatūros modelis

- **MERPSessionID** – MERP seanso ID

- **ReportingOsLocaleTag** – operacinės sistemos lokalė

- **ReportingOSVerStr** – operacinės sistemos versija

- **SessionBuildNumber** – sugedusios programos versija

- **SessionIDSMatch** – Bulio logika, skirta patvirtinti, ar ataskaitos seanso ID yra toks pat, kaip ir paimtas MERP

- **SessionVersion** – sugedusios programos versija – **StackHash** – sugedusios programos dėklo pėdsako maiša

- **UAEType** – išvardijimas, suteikiantis mums informacijos apie įvykusios gedimo tipą

#### <a name="officethisaddinstartupfailed"></a>Office.ThisAddIn.StartupFailed

Renka išimties informaciją, kuri įvyko paleidžiant Srautinio duomenų siųstuvo programą. Šie duomenys naudojami programos sveikatai stebėti. Šis įvykis sugeneruojamas iš „Microsoft“ srautinio duomenų siųstuvo, skirto „Excel“ papildiniui.

Renkami šių laukų duomenys:

- **Exception** – Išimties iškvietimų rietuvė

- **Event Name** – Įvykio pavadinimas yra įvykio kategorija ir įvykio etiketė.

#### <a name="onenotesafebootresetcrashcounteronappsuspend-officeonenoteandroidsafebootresetcrashcounteronappsuspend-officeandroidearlytelemetrysafebootresetcrashcounteronappsuspend"></a>OneNote.SafeBootResetCrashCounterOnAppSuspend, Office.OneNote.Android.SafeBootResetCrashCounterOnAppSuspend, Office.Android.EarlyTelemetry.SafeBootResetCrashCounterOnAppSuspend

Kritinis signalas siunčiamas naujo atkūrus gedimų skaitiklį, prieš paleidžiant saugos įkrovos dialogo langą. Šis žymiklis būtinas norint stebėti ir diagnozuoti programos sveikatą. Saugos įkrovos dialogo langas rodomas, kai programa sugenda keletą kartų nepertraukiamai. Jis suteikia vartotojui galimybę iš naujo nustatyti programą. Šis žymiklis padės išsiaiškinti, ar „Safe Boot“ dialogo langas nebuvo rodomas vartotojui nepaisant paleidiklio kriterijų. 

Renkami šių laukų duomenys:

- Nėra


#### <a name="telemetryerror"></a>telemetry.error

Šis įvykis leidžia diagnozuoti ir išspręsti problemas, neleidžiančias generuoti ar išsiųsti būtinų diagnostinių duomenų. Šie įvykiai leidžia suprasti, ar trūksta svarbių duomenų, būtinų nustatyti saugos ar pagrindines programos veikimo problemas.

Renkami šių laukų duomenys: 

- **timer_name** – nurodo, kur vyksta telemetrijos problema, pvz., pašto dėžutės komponente arba kalendoriuje. Padeda aptikti ir išspręsti telemetrijos problemas, kylančias iš tam tikros programos dalies

- **type** – nurodo laikmačio klaidos tipą, kad galėtume nustatyti, kada programa turi problemų, susijusių su diagnostinių telemetrijos duomenų siuntimu


#### <a name="watchdoganr"></a>watchdog.anr

Būtina programų veiksmingumo klaidoms stebėti, kad būtų išvengta atvejų, kai programa nebeatsako, o ekranas tampa įšaldytas programoje (vadinama ANR, kai programa nereaguoja).

Renkami šių laukų duomenys: 

- **callstack** – kodo iškvietimo dėklas, kur įvyko ANR
 
- **caused_restart** – ar programa turėjo būti paleista iš naujo dėl ANR
 
- **duration** – kiek laiko įrenginys buvo užšaldytas
 
- **id** – unikalusis ANR identifikatorius
 
- **interval** – sukonfigūruota ANR suaktyvinimo ribinė vertė
 
- **is_application_object_initialized** – ar ANR įvyko po to, kai programa buvo visiškai inicijuota
 
- **last_known_is_in_foreground** -– ar programa vėliausiai buvo priekiniame plane, ar fone


### <a name="application-feature-performance-subtype"></a>*Taikomosios programos funkcijų našumo potipis*

Prastas scenarijų, pvz., taikomosios programos paleidimas ar failo atidarymas, atsakymo laikas ar veikimas.

#### <a name="androidframemetrics"></a>android.frame.metrics

Leidžia nustatyti ir pataisyti situacijas, kai mūsų „Android“ programos komponentai kelia veikimo problemų, pvz., jei netinkamai slenkamas aplankas Gauta.

Renkami šių laukų duomenys: 

- **animation_duration** – animacijos generavimo trukmė milisekundėmis

- **command_issue_duration** – komandų pateikimo platformai trukmė milisekundėmis 

- **draw_duration** – vartotojo sąsajos pateikimo trukmė milisekundėmis 

- **input_handling_duration** – įvesties tvarkymo trukmė milisekundėmis 

- **layout_measure_duration** – išdėstymo matavimo trukmė milisekundėmis

- **origin** – programos komponentas, kuris matuojamas, pvz., kalendorius arba paštas

- **sync_duration** – kadro sinchronizavimo trukmė milisekundėmis

- **swap_buffers_duration** – buferių sukeitimo trukmė milisekundėmis

- **total_duration** – bendra kadrų generavimo trukmė milisekundėmis

- **unknown_delay** – delsos dėl nežinomų šaltinių trukmė, išskyrus aiškiai susektas trukmes

#### <a name="calcomponent"></a>cal.component

Šis įvykis leidžia aptikti ir išspręsti problemas, kai yra įtariamas veikimo poveikis mūsų kalendoriaus vartotojo sąsajos komponentams, dėl kurio gali kilti kalendoriaus linkimo problemų.

Renkami šių laukų duomenys: 

- **above_40fps** – kadrų skaičius virš 40 fps

- **above_40rate** – kadrų sparta virš 40 fps

- **above_50fps** – kadrų skaičius virš 50 fps

- **above_50rate** – kadrų sparta virš 50 fps

- **above_55fps** – kadrų skaičius virš 55 fps

- **above_55rate** – kadrų sparta virš 55 fps

- **account_counter** – seka skaičių paskyrų, susietų su kiekvienu kalendoriaus tipu, pvz., 2 skirta „Gmail“ kalendoriui, ir ar ši paskyra naudoja mūsų naują sinchronizavimo tarnybą

- **app_instance** – „Outlook“ yra du „Duo“ įvesties taškai, vienas – kalendoriui, o kitas – paštui. Abu gali būti paleisti greta kelių egzempliorių aplinkoje. Tai praneš mums, kuris egzempliorius pateiks šį pranešimą: pašto arba kalendoriaus

- **component_name** – nurodo kalendoriaus komponento pavadinimą, pvz., Dienotvarkės rodinį arba Dienos rodinį, kad galėtume aptikti tam tikras problemas, darančias įtaką konkrečiam kalendoriaus komponentui.

- **display_frame_data** – seka laiką, sugaištą rodant kiekvieną 60 kadrų, kad būtų galima nustatyti, ar yra veikimo problemų. 

- **orientation** – nurodo, ar įrenginys buvo stačias, ar gulsčias, kad galėtume aptikti veikimo problemas, kurios daro įtaką tam tikrai įrenginio padėčiai.

- **taskId** – „TaskId“ pateiks mums dabartinio egzemplioriaus „taskId“. Tai bus reikalinga kelių egzempliorių aplinkoje, jei vartotojas nori paleisti tuos pačius egzempliorius (kalendorius, kalendorius arba paštas, paštas) greta

- **view_duration** – nurodo kaip ilgai užtruko generuoti įvairius vartotojo sąsajos kalendoriaus komponentus, kad būtų galima aptikti veikimo problemas, darančias įtaką kalendoriaus patirčiai

#### <a name="contactaction"></a>contact.action

Šis įvykis paleidžiamas atliekant skirtingus veiksmus su kontaktais – peržiūrint, naujinant ir naikinant kontaktus, taip pat peržiūrint kontaktų sąrašą. Jis naudojamas nustatyti, ar yra kokių nors efektyvumo regresijų, susijusių su kontaktais.

Renkami šių laukų duomenys: 

- **accounts_with_filters** – paskyrų, kurių filtrai taikomi kontaktų sąrašui, skaičius

- **action** – veiksmas, kuris buvo atliktas, pvz., kontakto peržiūra
 
- **duration_initial_view_load** – trukmė nuo rodinio atidarymo iki pirminio kontaktų sąrašo įkėlimo

- **duration_show_contacts** – trukmė nuo rodinio atidarymo, kad kontaktų sąraše būtų rodomi kontaktai
 
- **total_contacts** – kontaktų, kuriems netaikomi filtrai, skaičius
 
- **total_filtered_contacts** – kontaktų, kuriems taikomi filtrai, skaičius

#### <a name="conversationloadtime"></a>conversation.load.time

Šis įvykis leidžia nustatyti ir išspręsti problemas, kylančias dėl el. pašto pokalbių įkėlimo, kad būtų galima užtikrinti numatytą el. laiškų įkėlimą.

Renkami šių laukų duomenys: 

- **time** – nurodo, kiek laiko užtrunka el. pašto pokalbio įkėlimas.

#### <a name="conversationreloaded"></a>conversation.reloaded

Šis įvykis leidžia nustatyti, kaip dažnai iš naujo įkelsime pokalbį pagal tarnybos pranešimus. Turime sekti, ar naujinimo pranešimai yra per garsūs ir reikia juos apkarpyti, nes jie mažina praktiškumą.

Renkami šių laukų duomenys: 

- **average** – perkrovų kiekis, padalintas iš dydžio 

- **client-request-ID** – kliento užklausos, dėl kurios įvyko klaida, identifikatorius

- **date** – užklausos, dėl kurios įvyko klaida, datos žymė

- **duration** – pokalbio atidarymo laikas 


#### <a name="coredatamigration"></a>core.data.migration

Leidžia nustatyti ir pataisyti situacijas, kai įvyksta įrenginio el. pašto duomenų naujinimo į naujesnę versiją klaida.

Renkami šių laukų duomenys:

- **db_size_megabytes** – seka pagrindinės duomenų bazės dydį, suapvalintą iki artimiausių 25 megabaitų, ir daugiausia 500 megabaitų

- **db_wal_size_megabytes** – seka pagrindinės duomenų bazės dydį, kai pagrindinės saugyklos failas yra suapvalintas iki artimiausio 1 MB, ir daugiausia iki 10 MB

- **free_space_megabytes** – seka pasiekiamos laisvos vietos kiekį talpyklomis po 10, 100, 1000, 10 000 ir 100 000. 

- **migration_duration_seconds** – seka perkėlimo trukmę, suapvalintą iki vieno iš šių laiko tarpsnių – 0, 10, 20, 30, 40, 50, 60, 70, 80, 90, 100, 110, 120, 130, 140, 150, 160, 170, 180 (180 ir daugiau rodoma kaip 180)

#### <a name="coredataperformance"></a>core.data.performance

Leidžia nustatyti ir pataisyti situacijas, kai įrenginyje saugomi el. pašto duomenys kelia problemų.

Renkami šių laukų duomenys:

- **Caller** – seka objekto pavadinimą, kuris iškviečia įrašymo operaciją

- **db_size_megabytes** – seka pagrindinės duomenų bazės dydį, suapvalintą iki artimiausių 25 megabaitų, ir daugiausia 500 megabaitų

- **duration** – seka, kiek laiko užtrunka operacijai baigti

- **entity** – seka objekto pavadinimą, kuris iškvietė įrašymo operaciją

- **operation** – neapdorota operacijos vertė: įrašyti, iškviesti arba „užblokuota skaitymo ir rašymo eilė“

#### <a name="inboxcomponent"></a>inbox.component

Šis įvykis renka dviejų tipų vartotojų informaciją: „Microsoft 365“ prenumeratos būseną ir tai, ar vartotojas mato reklamą. Tai leidžia aptikti ir išspręsti problemas, kurios gali trikdyti gautų laiškų vartotojo sąsajos komponentų veikimą ir gali būti neįkeliami ar netinkamai veikti el. pašto pranešimai, pseudoportretas, skaityta / neskaityta būsenos.

Renkami šių laukų duomenys: 

- **above_40fps** – kadrų skaičius virš 40 fps

- **above_40rate** – kadrų sparta virš 40 fps

- **above_50fps** – kadrų skaičius virš 50 fps

- **above_50rate** – kadrų sparta virš 50 fps

- **above_55fps** – kadrų skaičius virš 55 fps

- **above_55rate** – kadrų sparta virš 55 fps

- **account_counter** – kiekvieno įrenginyje esančio paskyros tipo skaičius, pvz., „Office 365“ paskyra = 1 paskyra, „Outlook.com“ paskyra = 1 paskyra.

- **ad_not_shown_reason** – priežastis, kodėl nerodomi skelbimai

- **ad_shown** – ar skelbimas buvo rodomas (jei įjungti skelbimai)

- **ad_shown_for_premium** – netikėtai rodoma reklama „Premium“ vartotojams

- **age** – asmens amžius (naudojamas patvirtinti reklamos amžiaus apribojimų atitikimą) *[Šis laukas pašalintas iš dabartinės „Office“ komponavimo versijos, bet vis dar gali būti senesnėse komponavimo versijose.]*

- **app_instance** – „Outlook“ yra du „Duo“ įvesties taškai, vienas – kalendoriui, o kitas – paštui. Abu gali būti paleisti greta kelių egzempliorių aplinkoje. Tai praneš mums, kuris egzempliorius pateiks šį pranešimą: pašto arba kalendoriaus

- **component_name** – filtruojant aktyvaus komponento/rodinio pavadinimas

- **has_hx** – ar įrenginys turi bent vieną HX (mūsų nauja el. pašto sinchronizavimo tarnyba) paskyrą

- **has_subscription** – ar įrenginys turi skelbimų prenumeratą

- **is_all_accounts_inbox** – ar dabartinis aplankas Gauta yra aplankas „visos paskyros“

- **is_current_account** – ar dabartinė aktyvi paskyra yra skelbimų paskyra

- **load_error_code** – klaidos kodas įkeliant skelbimus

- **network_error_code** – tinklo klaidos kodas, kai prašoma skelbimų

- **orientation** – ekrano padėtis įvykio metu (stačias arba gulsčias)

- **provider** – dabar rodomo skelbimo teikėjas („Xandr“ arba „Facebook“)

- **sub_error_type** – išsamus klaidos tipas

- **taskId** – „TaskId“ pateiks mums dabartinio egzemplioriaus „taskId“. Tai bus reikalinga kelių egzempliorių aplinkoje, jei vartotojas nori paleisti tuos pačius egzempliorius (kalendorius, kalendorius arba paštas, paštas) greta

- **total_count** – bendras rodomų kadrų skaičius pagal komponentą

- **view_duration** – kiek laiko vartotojas peržiūrėjo komponentą

#### <a name="initialpagelanding"></a>Initial.page.landing 
 
Šis įvykis padeda sekti vartotojo matomą patirties tipą, kai vartotojai bus perkeliami į mūsų taikomosios programos puslapį.  Šie duomenys naudojami norint nustatyti vartotojų srautą, nukreiptą į kiekvieną mūsų taikomosios programos patirtį ir taip pat padeda lengvai konsoliduoti eksperimentų rezultatus.
 
Renkami šių laukų duomenys: 

- **Page** – ši funkcija naudojama patirties tipą, kurią vartotojai pirmiausia mato, kai pereina į mūsų puslapį. Galimos reikšmės yra „bandomoji versija“, „praleisti“, „iš karto“, „iš anksto sugrupuota“, „prenumerata“ ir t. t.

- **storeExperience** – naudojama nustatyti, ar vartotojas turi teisę matyti saugyklos SDK patirtį.

- **stringVariant** – ši funkcija naudojama norint nustatyti vartotojų matomų eilučių tipą, kai jie pereina į mūsų puslapį. Atminkite, kad bet kuriame puslapyje, pvz., „bandomoji versija“, vartotojas gali matyti kitas eilutes. Tai priklauso nuo to, ar jie yra įsidiegę senesnę „Office“ versiją, arba jei anksčiau suaktyvino programą „Office“. Galimi šios ypatybės išvardijimai yra „LegacyUpsell“, „OfficeOpened“, „Default“, „YesIntent“, „NoIntent“ ir t. t.

- **windowsBuildType** – tai naudojama norint stebėti naudotojo naudojamo „WindowsBuildType“ tipą. T. y. „RS4“, „RS5“, „RS19H1“, „Vibranium“ ir t. t. Kadangi mūsų patirtys dažniausiai taikomos pagal skirtingus „WindowsBuildTypes“ tipus, ši ypatybė yra gyvybiškai svarbi norint atskirti išleidimus. 

#### <a name="ipcpbootstrapuser"></a>IpcpBootstrapUser

Gaunamas, kai vartotojas bando atidaryti IRM apsaugotą dokumentą arba taikyti IRM apsaugą. Jame yra informacija, būtina norint tinkamai ištirti ir nustatyti problemas, kurios įvyksta atliekant IpcpBootstrapUser API iškvietimą.

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas.

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.ApplicationScenarioId** – programos pateiktas scenarijaus ID

- **RMS.AuthCallbackProvided** – nurodo, ar pateikiamas autentifikavimo iškvietimas kaip API iškvietimo įvestis

- **RMS.ConnectionInfo.ExtranetUrl** – ryšio informacijos ekstraneto URL

- **RMS.ConnectionInfo.IntranetUrl** – ryšio informacijos intraneto URL

- **RMS.ConnectionMode** – ryšio režimas tarp teisių valdymo tarnybos kliento ir serverio: prisijungęs ar neprisijungęs

- **RMS.Duration** – bendras API iškvietimo baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia API iškvietimas, jei tokių yra

- **RMS.GuestTenant** – vartotojo svečio nuomotojo ID

- **RMS.GuestTenant** – vartotojo namų nuomotojo ID

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.Identity.ExtranetUrl** – vartotojo teisių valdymo tarnybos ekstraneto URL, gautas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.Identity.IntranetUrl** – vartotojo teisių valdymo tarnybos intraneto URL, gautas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.Identity.Status** – pirmas kartas, kai buvo gautas teisių paskyros sertifikatas iš serverio arba buvo atnaujintas teisių paskyros sertifikatas 

- **RMS.Identity.Type** – vartotojo paskyros tipas, pvz., „Windows“ paskyra arba tiesioginė paskyra

- **RMS.Identity.UserProvided** – nurodo, ar pateiktas vartotojo el. pašto adresas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.IssuerId** – teisių valdymo tarnybos serverio, kuris išduoda teisių paskyros sertifikatą, ID  

- **RMS.LicenseFormat** – licencijos formatas: Xrml arba Json

- **RMS.RACType** –teisių paskyros sertifikato tipas

- **RMS.Result** – API iškvietimo sėkmė arba nesėkmė

- **RMS.ScenarioId** – API apibrėžtas scenarijaus ID

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.ServerType** – teisių valdymo tarnybos tipas 

- **RMS.StatusCode** – pateikto rezultato būsenos kodas

- **RMS.TemplatesCount** – šablonų skaičius

- **RMS.TokenProvided** – nurodo, ar pateikiama žymė kaip API iškvietimo įvestis 

- **RMS.UserProvided** – nurodo, ar pateikiamas vartotojas kaip API iškvietimo įvestis 

- **UserInfo.UserObjectId** – vartotojo objekto ID

#### <a name="ipcpgetkey"></a>IpcpGetKey

Gaunamas, kai vartotojas bando atidaryti IRM apsaugotą dokumentą arba taikyti IRM apsaugą. Jame yra informacija, būtina norint tinkamai ištirti ir nustatyti problemas, kurios įvyksta atliekant IpcpGetKey API iškvietimą.

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas.

- **AppInfo.Version** – programos versija

- **iKey** – registravimo tarnybos serverio ID

- **RMS.ApplicationScenarioId** – programos pateiktas scenarijaus ID

- **RMS.AuthCallbackProvided** – nurodo, ar pateikiamas autentifikavimo iškvietimas kaip API iškvietimo įvestis

- **RMS.ConnectionMode** – ryšio režimas tarp teisių valdymo tarnybos kliento ir serverio: prisijungęs ar neprisijungęs

- **RMS.ContentId** dokumento turinio ID

- **RMS.Duration** – bendras API iškvietimo baigimo laikas

- **RMS.DurationWithoutExternalOps** – bendrasis laikas atėmus išorinių operacijų laiką, pvz., tinklo delsą.

- **RMS.ErrorCode** – klaidos kodas, kurį pateikia API iškvietimas, jei tokių yra

- **RMS.EulId** – galutinio vartotojo licencijos ID

- **RMS.EulProvided** – nurodo, ar pateikiama galutinio vartotojo licencija kaip API iškvietimo įvestis

- **RMS.GuestTenant** – vartotojo svečio nuomotojo ID 

- **RMS.GuestTenant** – vartotojo namų nuomotojo ID

- **RMS.HttpCall** – nurodo, ar yra HTTP operacija

- **RMS.Identity.ExtranetUrl** – vartotojo teisių valdymo tarnybos ekstraneto URL, gautas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.Identity.IntranetUrl** – vartotojo teisių valdymo tarnybos intraneto URL, gautas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.Identity.Status** – pirmas kartas, kai buvo gautas teisių paskyros sertifikatas iš serverio arba buvo atnaujintas teisių paskyros sertifikatas 

- **RMS.Identity.Type** – vartotojo paskyros tipas, pvz., „Windows“ paskyra arba tiesioginė paskyra

- **RMS.Identity.UserProvided** – nurodo, ar pateiktas vartotojo el. pašto adresas gaunant naują teisių paskyros sertifikatą iš serverio

- **RMS.IssuerId** – teisių valdymo tarnybos serverio, kuris išduoda teisių paskyros sertifikatą, ID 

- **RMS.KeyHandle** – rakto valdymo programos atminties adresas

- **RMS.LicenseFormat** – licencijos formatas: Xrml arba Json

- **RMS.PL.ExtranetUrl** – ekstraneto URL publikavimo licencijoje

- **RMS.PL.IntranetUrl** – intraneto URL publikavimo licencijoje

- **RMS.PL.KeyType** – reikšmė „Single“ arba „Double“ nurodo, ar PL apsaugoti buvo naudota vieno, ar dviejų raktų apsauga

- **RMS.RACType** –teisių paskyros sertifikato tipas

- **RMS.Result** – API iškvietimo sėkmė arba nesėkmė

- **RMS.ScenarioId** – API apibrėžtas scenarijaus ID

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

- **RMS.ServerType** – teisių valdymo tarnybos tipas

- **RMS.StatusCode** – pateikto rezultato būsenos kodas

- **RMS.TemplatesCount** – šablonų skaičius

- **RMS.TokenProvided** – nurodo, ar pateikiama žymė kaip API iškvietimo įvestis 

- **RMS.UserProvided** – nurodo, ar pateikiamas vartotojas kaip API iškvietimo įvestis 

- **UserInfo.UserObjectId** – vartotojo objekto ID

#### <a name="jsonparseerror"></a>json.parse.error 
 
Šis įvykis nurodo, kad klaidą pateikė json formato analizatorius.  Galėsime derinti nuskaitytą registro eilutę, kuri buvo išsiųsta json formato analizatoriui, kad būtų galima užtikrinti sklandžią mūsų vartotojų patirtį.
 
Renkami šių laukų duomenys: 

- **Error** – šis parametras susideda iš klaidos pranešimo, grąžinto klaidos objekto.

#### <a name="mailfiltercomponent"></a>mail.filter.component

Šis įvykis leidžia aptikti ir išspręsti problemas, kurios gali trikdyti laiškų filtravimo patirtį ir gali būti neįkeliami ar netinkamai rodomi filtrai.

Renkami šių laukų duomenys: 

- **above_40fps** – kadrų skaičius virš 40 fps

- **above_40rate** – kadrų sparta virš 40 fps
 
- **above_50fps** – kadrų skaičius virš 50 fps

- **above_50rate** – kadrų sparta virš 50 fps
 
- **above_55fps** – kadrų skaičius virš 55 fps

- **above_55rate** – kadrų sparta virš 55 fps
 
- **account_counter** – kiekvieno įrenginyje esančio paskyros tipo skaičius, pvz., „Office 365“ paskyra = 1 paskyra, „Outlook.com“ paskyra = 1 paskyra.
 
- **ad_not_shown_reason** – priežastis, kodėl nerodomi skelbimai
 
- **ad_shown** – ar skelbimas buvo rodomas (jei įjungti skelbimai)
 
- **age** – asmens amžius (naudojamas patvirtinti skelbimų amžiaus apribojimų atitiktį)

- **app_instance** – „Outlook“ yra du „Duo“ įvesties taškai, vienas – kalendoriui, o kitas – paštui. Abu gali būti paleisti greta kelių egzempliorių aplinkoje. Tai praneš mums, kuris egzempliorius pateiks šį pranešimą: pašto arba kalendoriaus
 
- **component_name** – filtruojant aktyvaus komponento/rodinio pavadinimas
 
- **folder_type** – filtruojamo aplanko tipas (pvz., Gauta, Šiukšliadėžė, ne sistemos)
 
- **has_hx** – ar įrenginys turi bent vieną HX (nauja el. pašto sinchronizavimo tarnyba) paskyrą
 
- **has_subscription** – ar įrenginys turi skelbimų prenumeratą
 
- **is_all_accounts_inbox** – ar dabartinis aplankas Gauta yra aplankas „visos paskyros“
 
- **is_current_account** – ar dabartinė aktyvi paskyra yra skelbimų paskyra
 
- **load_error_code** – klaidos kodas įkeliant skelbimus
 
- **network_error_code** – tinklo klaidos kodas, kai prašoma skelbimų
 
- **orientation** – ekrano padėtis įvykio metu (stačias arba gulsčias)
 
- **sub_error_type** – išsamus klaidos tipas

- **taskId** – „TaskId“ pateiks mums dabartinio egzemplioriaus „taskId“. Tai bus reikalinga kelių egzempliorių aplinkoje, jei vartotojas nori paleisti tuos pačius egzempliorius (kalendorius, kalendorius arba paštas, paštas) greta
 
- **total_count** – bendras rodomų kadrų skaičius pagal komponentą
 
- **view_duration** – kiek laiko vartotojas peržiūrėjo komponentą

#### <a name="messagerenderingintercepted"></a>message.rendering.intercepted

Šis įvykis leidžia sekti, kaip dažnai vartotojai įsiterpia į generavimo procesą, kol jis baigiamas. Šiuos duomenis naudojame veikimo problemoms aptikti.

Renkami šių laukų duomenys: 

- **is_cache** – ar laiško tekstas yra įkeltas iš talpyklos

- **is_on_screen** – ar atvaizdavimo procesas matomas vartotojams (normalus atvaizdavimas)

- **is_rendering_complete** – ar atvaizdavimo procesas baigtas 

- **is_trimmed_body** – ar laiško tekstas yra apkarpytas tekstas 

- **rendering_method** - atvaizdavimo pranešimo būdas

- **rendering_time** – pranešimo pateikimo trukmė, kol vartotojas palieka puslapį

#### <a name="messagerenderingperformance"></a>message.rendering.performance

Šis įvykis leidžia mums stebėti pranešimų atvaizdavimo proceso rezultatus, kad galėtume išanalizuoti skirtingų atvaizdavimo procesų rezultatus ir aptikti produktyvumo triktis. 

Renkami šių laukų duomenys: 

- **bundle_prepare_time** – laikas paruošti pluoštą generavimą

- **full_rendering_time** – visiško utilizavimo proceso laikas

- **is_cache** – ar laiško tekstas yra įkeltas iš talpyklos

- **is_on_screen** – ar atvaizdavimo procesas matomas vartotojams (normalus atvaizdavimas)

- **is_trimmed_body** – ar laiško tekstas yra apkarpytas tekstas 

- **load_message_time** – laikas įkelti pranešimą iš vidinės sistemos (gali būti 0, jei laiškas įrašytas talpykloje)

- **native_preprocess_time** – laikas iš anksto apdoroti laiško tekstą gimtąja puse 

- **prepare_body_time** – laikas parengti pranešimo tekstą (įskaitant pranešimą įkėlimas ir išankstinis procesas)

- **rendering_method** - atvaizdavimo pranešimo būdas

- **rendering_time** – laikas, kurio reikia atvaizduoti pranešimą pagal paketą  

- **wait_time** – laikas, reikalingas sukurti pranešimo URL


#### <a name="officeandroidandroidofficelaunchtolandingpagelatency"></a>Office.Android.AndroidOfficeLaunchToLandingPageLatency

Svarbu užfiksuoti programos veikimo metriką, atsižvelgiant į taikomosios programos atsakymo laiką nuo paleidimo.  „Microsoft“ šią funkciją naudoja fiksuoti laiką, skirtą taikomajai programai reaguoti ir aptikti scenarijus, kurie gali veikti paleidimo laiką programose „Word“, „Excel“ ar „PowerPoint“.

Renkami šių laukų duomenys:
 
- **AnyCrashInteractionDuringBoot** – Bulio logika bet kokiam gedimui, kuris įvyko paleidimo metu

- **AppActivationTimeInMs** – taikomosios programos etapo laikas

- **AppSuspendedDuringBoot** – Bulio logika taikomosios programos sustabdymui paleidimo metu

- **AvailableMemoryInMB** – pasiekiama atmintis

- **CollectionTime** – įvykio laikas

- **DalvikHeapLimitInMB** – netvarkiojo masyvo informacija

- **DocumentRecoveryInvoked** – Bulio logika, nurodanti, ar buvo atkurtas koks nors dokumentas

- **ExtractionDone** – vietinės bibliotekos išskleidimo laikas

- **FastBootGainTimeInMs** – greito paleidimo užbaigimui skirtas laikas

- **FileActivationAttempted** – Bulio logika, rodanti, ar aktyvinus failą taikomoji programa buvo paleista

- **HasLogcatLoggingImpactOnBoot** – Bulio logika, rodanti, ar „logcat“ paveikė paleidimo laiką

- **IsThisFirstLaunch** – Bulio logika, rodanti, ar tai yra pirmasis taikomosios programos paleidimas

- **LatencyTimeInMilliSec** – gaištis milisekundėmis

- **LibrarySharingTimeInMs** – bibliotekų bendrinimui skirtas laikas

- **LoadMinLibsTimeInMs** – minimalus bibliotekų rinkinio įkėlimo laikas

- **MruListingTimeInMs** - MRU įkėlimo laikas

- **NativeLibrariesLoadTime** – CPP bibliotekos įkėlimo laikas

- **NumberOfRunningProcesses** – vykdomų procesų skaičius

- **NumberOfRunningProcesses** – vykdomų procesų skaičius

- **NumberOfRunningServices** – veikiančių tarnybų skaičius

- **OfficeActivityTimeInMs** – OfficeActivity inicijavimo laikas

- **PostAppInitTimeInMs** – taikomosios programos etapo laikas

- **PreAppInitializationTime** – taikomosios programos etapo inicijavimo laikas

- **PreAppInitTimeInMs** – taikomosios programos etapo laikas

- **TotalMemoryInMB** – bendra atmintis

- **UIRaaSDownloadLanguagePackageBoot** – informacija, susijusi su kalbos paketo atsisiuntimu

- **UserDialogInterruptionDuringBoot** – Bulio logika bet kokiam blokavimo dialogo langui, rodomam paleidimo metu


#### <a name="officeandroiddocsuiviewsdimepurchaseflowstate"></a>Office.Android.DocsUI.Views.DimePurchaseFlowState

Šis sveikatos įvykis bando užfiksuoti kiekvieną būseną, kurią pereina vartotojas, bandydamas atlikti pirkimą, vykdydamas pirkimo programoje veiksmus, kuriuos valdo „Dime“. Duomenys naudojami siekiant stebėti ir įspėti apie pirkimo eigos sveikatą; šiuos veiksmus suaktyvina „Office Mobile“ programėlė, kai vartotojas pasirenka pirkti „Microsoft 365“ prenumeratą.

Renkami šių laukų duomenys:

- **EntryPoint** – vartotojo bandyto atlikti pirkimo įėjimo taškas

- **OEMPreInstalled** – identifikuoja, ar programa yra įdiegta iš anksto, ar natūraliai įdiegta vartotojo

- **PurchaseState** – vartotojo būsena, bandant atlikti pirkimą
    - 0 – nežinoma klaida
    - 1 – vartotojas bandė atidaryti „Dime“
    - 2 – tinklo klaida
    - 3 – „Dime“ rodoma vartotojui
    - 4 - „Dime“ atšaukė vartotojas
    - 5 –  reikia atnaujinti, nes pirkimas sėkmingas
    - 6 – pirkimas sėkmingas
    - 7 – bendroji „Dime“ klaida
    - 8 – „Dime“ telemetrijos negalima nusiųsti dėl ryšio trikties
    - 9 – du veikiantys „Dime“ egzemplioriai sukelia pertraukimo klaidą
    - 10 – bazinis WebURL, įkeltas „officemobile“ programėlėje, neleistinas
    - 11 – „officemobile“ programėlės su „Dime“ ryšys nesėkmingas 
    - 12 – nepavyko užmegzti ryšio su ryšio kanalais
    - 13 – nepavyko išsiųsti ryšio ID į „Dime“
    - 14 – „officemobile“ programėlė užmezga ryšį su klaidingu galiniu punktu
    - 15 – šiai MSA paskyrai negautas „AuthToken“
    - 16 – „AuthToken“ neišsiųsta į „Dime“

- **WebViewShownDuration** – „Dime“ pirkimo puslapio rodymo vartotojui trukmė 


#### <a name="officeappleappleappbootmac"></a>Office.Apple.Apple.AppBoot.Mac

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas skaičiuoti taikomosios programos paleidimo laikui, taip pat gauti tam tikrą informaciją apie įkrovos tipą. Šis įvykis padeda mums stebėti savo našumą ir teikti produktyvumo patobulinimų.

Renkami šių laukų duomenys:

- **Data_ Data_EvtBootTimerDocStageReady** – laikas reikalingas pasiekti tam tikrą kodo vietą.

- **Data_DocumentRecoveryInvoked** – nurodo, ar dokumento atkūrimas buvo iškviestas paleidimo metu.

- **Data_EvtBootTimerBootIdle** – laikas reikalingas pasiekti tam tikrą kodo vietą.

- **Data_EvtBootTimerFinishLaunchEnd** – laikas reikalingas pasiekti tam tikrą kodo vietą.

- **Data_EvtBootTimerLaunchDidFinish** – laikas reikalingas pasiekti tam tikrą kodo vietą.

- **Data_EvtBootTimerLaunchStart** – laikas reikalingas pasiekti tam tikrą kodo vietą.

- **Data_EvtBootTimerMainStart** – laikas reikalingas pasiekti tam tikrą kodo vietą.

- **Data_EvtBootTimerStaticInit** – laikas reikalingas pasiekti tam tikrą kodo vietą.

- **Data_EvtDockStageReady** – laikas reikalingas pasiekti tam tikrą kodo vietą.

- **Data_IsFileOpenAttempted** – nurodo, ar buvo bandoma atidaryti failą paleidimo metu.

- **Data_IsFirstRunAttempted** – nurodo, ar taikomosios programos paleidimo metu buvo naudojama pirmojo sistemos paleidimo programa.

- **Data_SentToBackground** – nurodo, ar taikomoji programa buvo nusiųsta į foną įkėlimo metu.

#### <a name="officeapplediskruleresultserializererroronstreamop"></a>Office.Apple.DiskRuleResultSerializerErrorOnStreamOp

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas savo telemetrijos infrastruktūros sveikatai stebėti. Šis įvykis nurodo įvykusią klaidą.

Renkami šių laukų duomenys:

- **Data_ActualBytesModified** – modifikuotų baitų skaičius.

- **Data_BytesRequested** – apdorotų baitų skaičius.

- **Data_IsWriteOp** – nurodo, ar ruošiamės atlikti rašymo operaciją

#### <a name="officeapplemacbootresourceusage"></a>Office.Apple.MacBootResourceUsage

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Šis įvykis naudojamas surinkti keletą indikatorių apie išteklius, naudojamus „Office“ taikomųjų programų paleidimo metu. Šis įvykis padeda mums stebėti savo našumą ir teikti produktyvumo patobulinimų.

Renkami šių laukų duomenys:

- **Data_BlockInputOperations** – blokų įvesties operacijų skaičius

- **Data_BlockOutputOperations** – blokų įvesties operacijų skaičius

- **Data_InvoluntaryContextSwitches** – priverstinio konteksto perjungiklių skaičius

- **Data_MainThreadCPUTime** – praėjusio laiko matavimas

- **Data_MaxResidentSize** – atminties dydžio matavimas

- **Data_MessagesReceived** – gautų pranešimų skaičius

- **Data_MessagesSent** – išsiųstų pranešimų skaičius

- **Data_PageFaults** – puslapio atkūrimų skaičius

- **Data_PageReclaims** – puslapio atkūrimų skaičius

- **Data_ProcessCPUTime** – praėjusio laiko matavimas

- **Data_SharedTextMemorySize** – atminties dydžio matavimas

- **Data_SignalsReceived** – gautų signalų skaičius

- **Data_Swaps** – apsikeitimo duomenimis skaičius

- **Data_SystemCPUTime** – praėjusio laiko matavimas

- **Data_SystemUpTime** – praėjusio laiko matavimas

- **Data_UnsharedDataSize** – duomenų dydžio matavimas

- **Data_UnsharedStackSize** – bloko dydžio matavimas

- **Data_UserCPUTime** – praėjusio laiko matavimas

- **Data_VoluntaryContextSwitchesNvcsw** – neverstinio konteksto perjungiklių skaičius

#### <a name="officeapplemauvalidation"></a>Office.Apple.MAU.Validation

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas stebėti sveikatą „Microsoft AutoUpdate“ komponento, kuris naudojamas platinti ir diegti taikomųjų programų naujinimus. Surinkti duomenys naudojami klaidoms aptikti ir nustatyti trikčių priežastis.

Renkami šių laukų duomenys:

- **Data_EventID** – renkame duomenis eilutės, atvaizduojančios klaidos kodą

- **Data_Message** – renkame duomenis eilutės, kurioje pateikiamas klaidos aprašymas

#### <a name="officeapplembuinstrumenthangdetectionspincontrol"></a>Office.Apple.MbuInstrument.Hang.Detection.Spin.Control

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis užregistruojamas, kai taikomoji programa neatsako. Šis įvykis padeda mums stebėti savo našumą ir teikti produktyvumo patobulinimų.

Renkami šių laukų duomenys:

- **Data_CountSpinControlStart** – žymiklis, nurodantis, kad programa nebeatsako (arba atsako lėtai)

#### <a name="officeapplembuinstrumentvmondocumentclose"></a>Office.Apple.MbuInstrument.VMOnDocumentClose

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas rinkti atminties būsenos momentinę kopiją dokumento uždarymo metu. Šis įvykis padeda mums stebėti savo našumą ir teikti produktyvumo patobulinimų.

Renkami šių laukų duomenys:

- **Data_CollectionTime** – laiko žyma nuo momento, kai duomenys buvo surinkti

- **Data_ResidentMemory** – stebima nuolatinės atminties reikšmė

- **Data_VirtualMemory** – stebima virtualiosios atminties reikšmė

#### <a name="officeapplembuinstrumentvmonshutdown"></a>Office.Apple.MbuInstrument.VMOnShutdown

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas rinkti atminties būsenos momentinę kopiją taikomosios programos išjungimo metu. Šis įvykis padeda mums stebėti savo našumą ir teikti produktyvumo patobulinimų.

Renkami šių laukų duomenys:

- **Data_CollectionTime** – laiko žyma nuo momento, kai duomenys buvo surinkti

- **Data_ResidentMemory** – stebima nuolatinės atminties reikšmė

- **Data_VirtualMemory** – stebima virtualiosios atminties reikšmė

#### <a name="officeapplembuinstrumentvmonstart"></a>Office.Apple.MbuInstrument.VMOnStart

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas rinkti atminties būsenos momentinę kopiją taikomosios programos paleidimo metu. Šis įvykis padeda mums stebėti savo našumą ir teikti produktyvumo patobulinimų.

Renkami šių laukų duomenys:

- **Data_CollectionTime** – laiko žyma nuo momento, kai duomenys buvo surinkti

- **Data_ResidentMemory** – stebima nuolatinės atminties reikšmė

- **Data_VirtualMemory** – stebima virtualiosios atminties reikšmė

#### <a name="officeapplemsoappdelegatebootperf"></a>Office.Apple.MsoAppDelegate.BootPerf

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas rinkti informaciją apie laiką ir atmintį, sunaudotą „Office“ programų paleidimo metu, taip pat kai kurią informaciją apie paleidimo tipą. Šis įvykis padeda mums stebėti savo našumą ir teikti produktyvumo patobulinimų.

Renkami šių laukų duomenys:

- **Data_AppLaunchDurationMicroSec** – paleidimo proceso trukmė

- **Data_AppLaunchFinishSystemTime** – laiko žyma ties konkrečia paleidimo kodo žyma

- **Data_AppLaunchStartSystemTime** – laiko žyma ties konkrečia paleidimo kodo žyma

- **Data_ResidentMemory** – prieinamos nuolatinės atminties momentinė kopija

- **Data_VirtualMemory** – prieinamos virtualios atminties momentinė kopija

#### <a name="officeappleungracefulappexithangsinprevioussession"></a>Office.Apple.UngracefulAppExitHangsInPreviousSession

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Šis įvykis naudojamas „Office“ taikomųjų programų sveikatai stebėti, taip pat tirti trikčių priežastis. Renkame informaciją, kiek kartų taikomoji programa neatsakė iki buvo pasirinktas nesklandusis programos išėjimas.

Renkami šių laukų duomenys:

- **Data_HangsDetected** – kiek kartų taikomoji programa neatsakė iki buvo pastebėtas nesklandusis programos išėjimas.

- **Data_LastSessionId** – seanso, kurio metu buvo stebėtas nesklandusis programos išėjimas, identifikatorius.

- **Data_SessionBuildNumber** – papildoma taikomosios programos versija, kurioje buvo pastebėtas nesklandusis išėjimas iš programos.

- **Data_SessionVersion** – pagrindinė taikomosios programos versija, kurioje buvo pastebėtas nesklandusis išėjimas iš programos.

#### <a name="officeapplewhatsnewerrorandwarning"></a>Office.Apple.WhatsNewErrorAndWarning

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas funkcijos Kas nauja sveikatai stebėti. Šis įvykis nurodo, kad funkcijos Kas nauja turinio analizavimo įvyko klaida/įspėjimas, nurodanti galimas turinio kūrimo triktis.

Renkami šių laukų duomenys:

- **Data_ContentKey** – žymiklis, nurodantis turinio dalį, kuri galėjo sukelti klaidą.

- **Data_ErrorCode** – pastebėtos klaidos kodas (jei yra)

- **Data_ErrorDescription** – klaidos aprašas (jei yra)

- **Data_EventID** – renkame duomenis eilutės, nurodančios pastebėtos klaidos tipą.

- **Data_IncludesHTMLTag** – ar turinyje yra raiškiojo html

- **Data_IncludesItemsTag** – ar turinyje yra elementų hierarchija

- **Data_LengthOfRawData** – turinio dydis

- **Data_RequestURL** – URL, iš kurio atsisiųstas turinys

- **Data_ServerLanguageTag** – kalba, kuria buvo sukurtas turinys.

- **Data_StatusCode** – klaidos būsena (jei yra)

#### <a name="officeextensibilityrichapimethodinvocation"></a>Office.Extensibility.RichApiMethodInvocation

Šis įvykis suaktyvinamas, kai klientas naudoja „Office“ papildinį ir paslaugai teikti iškviečia raiškųjį API. Naudojamas norint įvertinti paslaugos patikimumą, veikimą ir raiškiojo API metodo naudojimą.
 
Renkami šių laukų duomenys:

- **Api** – visas API pavadinimas

- **DispFlag** – bitų žymė, aprašanti metodo iškvietimo tipą (pavyzdžiui, 0 x 1 = METHOD, 0 x 2 = PROPERTYGET, 0 x 4 = PROPERTYPUT, 0 x 8 = PROPERTYPUTREF)

- **DispId** – iškviečiamo metodo išsiuntimo ID

- **HResult** – metodo iškvietimo „HResult“

- **Latency** – iškvietimo gaištis mikrosekundėmis

- **ReqId** – GUID, skirtas paketo užklausai, kuriai šis metodas priklauso

- **TypeId** – GUID, skirtas sąsajai, kuriai šis metodas iškviečiamas


#### <a name="officemanageabilityserviceapplypolicy"></a>Office.Manageability.Service.ApplyPolicy

Svarbi telemetrija, skirta gedimams stebėti\\Sėkmingas debesijos strategijos nustatymų registravimas. „LastError“ nurodo, kodėl ir kur nepavyko taikyti registro strategijos.

Renkami šių laukų duomenys:

  - **Data.ApplyLogMsg** – išimties pranešimas, jei strategija buvo taikoma

  - **Data.Cid** – dinamiškai sukurtas sąsajos identifikatorius, siunčiamas į tarnybą, kai buvo atliktas tarnybos iškvietimas, kad gautų debesijos strategiją. Naudojamas nustatyti, kuris iškvietimas sukėlė problemą taikant strategiją debesyje.

  - **Data.Last Error** – Viena iš penkių eilučių reikšmių (surašytuvai), norint užregistruoti, kuris strategijos taikymo etapas buvo įvykdytas, kai įvyko išimtis


#### <a name="officeofficemobilepdfviewerpdffileopenmeasurements-on-android"></a>Office.OfficeMobile.PdfViewer.PdfFileOpenMeasurements („Android“)

Įvykis renkamas „Office“ programai, skirtai „Android“. Jis įrašomas, kai atliekama failo atidarymo operacija. Mes renkame šiuos duomenis, kad būtų užtikrintas tinkamas visų failų, esančių programoje, atidarymas. 

Renkami šių laukų duomenys:

- **"Data_Doc_ActivationFQDN** – teikėjo taikomosios programos, skirtos failo suaktyvinimo scenarijui, domeno vardas (registruojama tik pirmosios šalies taikomosios programos informacija).

- **Data_Doc_DownloadDurationms** – laikas, per kurį atsisiunčiamas PDF debesies failas.

- **Data_Doc_Location** – vieta, kurioje yra failas (vietinis, ODSP, „iCloud“, trečiosios šalies failų programa, „wopi“).

- **Data_Doc_OpenDurationms** – laikas milisekundėmis, per kurį atidaromas PDF failas.

- **Data_FetchReason** – nurodo, kaip buvo gautas failas (rankiniu būdu, įrašytas į talpyklą, neįrašytas į talpyklą)

- **Doc_RenderDurationms** – laikas, per kurį sugeneruojamas PDF failas

#### <a name="officeofficemobilepdfviewerpdffileopenmeasurements-on-ios"></a>Office.OfficeMobile.PdfViewer.PdfFileOperations („iOS“)

Šis įvykis renkamas „Office“ programai, skirtai „iOS“. Jis įrašomas, kai atliekama failo atidarymo operacija. Mes renkame šiuos duomenis, kad būtų užtikrintas tinkamas visų failų, esančių programoje, atidarymas. 

Renkami šių laukų duomenys:

- **"Data_Doc_ActivationFQDN** – teikėjo taikomosios programos, skirtos failo suaktyvinimo scenarijui, domeno vardas (registruojama tik pirmosios šalies taikomosios programos informacija).

- **Data_Doc_CreateTelemetryReason** – telemetrijos priežastys kurti PDF. (pvz., Kurti iš nuskaitymo, naudojant veiksmą „paveikslėlis į PDF“, „dokumentas į PDF“ ir t. t.)

- **Data_Doc_DownloadDurationms** – laikas, per kurį atsisiunčiamas PDF debesies failas.

- **Data_Doc_DownloadEndTime** – debesies failo atsisiuntimo pabaigos laiko žyma.

- **Data_Doc_DownloadEndTime** – debesies failo atsisiuntimo pradžios laiko žyma.

- **Data_Doc_FileOpSessionID** – dokumento seanso unikalusis ID.

- **Data_Doc_Location** – vieta, kurioje yra failas (vietinis, ODSP, „iCloud“, trečiosios šalies failų programa, „wopi“).

- **Data_Doc_OpenCompletionTime** – PDF failo atidarymo operacijos pabaigos laiko žyma.

- **Data_Doc_OpenDurationms** – laikas milisekundėmis, per kurį atidaromas PDF failas.

- **Data_Doc_OpenStartTime** – PDF failo atidarymo operacijos pradžios laiko žyma.

- **Data_Doc_TelemetryReason** – telemetrijos priežastys įvykiui atidaryti (pvz., atidarymas iš MRU arba naršymas, failo suaktyvinimas, protokolo suaktyvinimas ir t. t.).

- **Data_FetchReason** – nurodo, kaip buvo gautas failas (rankiniu būdu, įrašytas į talpyklą, neįrašytas į talpyklą)

- **Doc_RenderDurationms** – laikas, per kurį sugeneruojamas PDF failas


#### <a name="officeonenoteandroidsyncprovisioningcompleted"></a>Office.OneNote.Android.Sync.ProvisioningCompleted

*[Šis įvykis anksčiau buvo vadinamas OneNote.Sync.ProvisioningCompleted.]*

Šis kritinis signalas naudojamas siekiant užtikrinti, kad vartotojui prisijungus prie „OneNote“ „Android“ programos, bloknotai būtų tinkamai parengti ir juos būtų galima sėkmingai pasiekti. Tai naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai

Renkami šių laukų duomenys: 

- **AppSuspendedDuringEvent** – pateikia Bulio logiką, kad būtų galima nurodyti, ar programa buvo laikinai sustabdyta pateikimo metu

- **NetworkConnection** – naudojamo įrenginio tinklo ryšio tipas

- **NetworkDataExchange** – įrašo baitų skaičių, kuriais buvo apsikeista pateikiant.

- **ServerType** – pateikia serverio, siūlančio tarnybą, tipą

- **TimeTakenInMilliSeconds** – pateikia laiką, kiek truko visas pateikimas milisekundėmis

#### <a name="officeonenoteandroidsyncprovisioningerror"></a>Office.OneNote.Android.Sync.ProvisioningError

Šis kritinis signalas naudojamas siekiant užtikrinti, kad vartotojui prisijungus prie „OneNote“ „Android“ programos, bloknotai būtų tinkamai parengti ir juos būtų galima sėkmingai pasiekti. Tai naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai.

Renkami šių laukų duomenys:

- **AppSuspendedDuringEvent** – pateikia Bulio logiką, kad būtų galima nurodyti, ar programa buvo laikinai sustabdyta pateikimo metu

- **Klaidos kodas** – pateikia klaidos kodą, atsakingą už parengimo triktis 

- **NetworkConnection** – naudojamo įrenginio tinklo ryšio tipas

- **NetworkDataExchange** – įrašo baitų skaičių, kuriais buvo apsikeista pateikiant.

- **ServerType** – pateikia serverio, siūlančio tarnybą, tipą

- **TimeTakenInMilliSeconds** – pateikia laiką, kiek truko visas pateikimas milisekundėmis


#### <a name="officeonenoteandroidsyncprovisioningstarted"></a>Office.OneNote.Android.Sync.ProvisioningStarted

*[Šis įvykis anksčiau buvo vadinamas OneNote.Sync.ProvisioningStarted.]*

Šis kritinis signalas naudojamas siekiant užtikrinti, kad vartotojui prisijungus prie „OneNote“ „Android“ programos, bloknotai būtų tinkamai parengti ir juos būtų galima sėkmingai pasiekti.  Tai naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai

Renkami šių laukų duomenys: 

- **NetworkConnection** – naudojamo įrenginio tinklo ryšio tipas

- **ServerType** – pateikia serverio, siūlančio tarnybą, tipą

#### <a name="officeonenotesystembootdialogssafebootdialogpending"></a>Office.OneNote.System.BootDialogs.SafeBootDialogPending 

Kritiniai signalai, naudojami sekti, kai mes nusprendžiame rodyti vartotojo saugaus paleidimo dialogo langą kitoje paleidimo programoje, nes paleidimas nuolat užstringa. Tai naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Jei vartotojai mato saugaus paleidimo dialogo langą, tada turėsime kritinę paleidimo gedimo klaidą ir ši informacija padės mums sužinoti, kiek vartotojų susidūrė su šia problema ir kiek vartotojų iš naujo paleidžia programą, kad iš tikrųjų matytų saugos įkrovos dialogo langą, ir kiek negrįžta.

Renkami šių laukų duomenys:

 - Nėra

#### <a name="officeoutlookdesktopbootperfmetrics"></a>Office.Outlook.Desktop.BootPerfMetrics

Renkamas laikas, kurio reikia paleisti „Outlook“. „Outlook“ paleidimo laikas aktyviai stebimas, kad aptiktų ir diagnozuotų regresiją. Jis taip pat naudojamas klientų sudėtingesniems atvejams nustatyti ir laikui bėgant pagerinti įkrovos veikimą.

Renkami šių laukų duomenys:

  - **AddinElapsedTotal** – Bendras laikas, skirtas papildiniams įkelti

  - **CredPromptCount** – skaičių Raginimų pateikti kredencialus skaičius

  - **ElapsedTotal** – Bendras įkrovos laikas

  - **IsLoggingEnabled** – Ar įgalintas registravimas

  - **ShowChooseProfileDlg** – Ar buvo rodomas dialogo langas Pasirinkti profilį

  - **ShowFirstRunDlg** – Ar „Outlook“ paleidžiamas pirmą kartą

  - **ShowIMAPSrchfldWarningDlg** – Įspėjimai, jei yra IMAP paskyra su ANSI PST

  - **ShowNeedSupportDlg** – Įkrovos trikties sužadintas palaikymo dialogo lango

  - **ShowSafeModeDlg** – Ar seansas atidarytas saugiuoju režimu

  - **ShowScanPstDlg** – Parduotuvės taisymo patikrinimo metu rodomas klaidos pranešimas


#### <a name="officeoutlookmacbootperf"></a>Office.Outlook.Mac.BootPerf

Renkamas laikas, kurio reikia paleisti „Outlook“. „Outlook“ paleidimo laikas aktyviai stebimas, kad aptiktų ir diagnozuotų regresiją. Jis taip pat naudojamas klientų sudėtingesniems atvejams nustatyti ir laikui bėgant pagerinti įkrovos veikimą.

Renkami šių laukų duomenys:

- **MacOLKBootPerfDuration** – bendras sistemos įkrovos laikas

- **MacOLKBootPerfID** – įkrovai skirto laiko identifikatorius


#### <a name="officeoutlookmacperformanceunresponsive"></a>Office.Outlook.Mac.PerformanceUnresponsive

Naudojamas identifikuoti vartotojams įtakos turinčias „Outlook“ problemas, galinčias pasireikšti pablogėjusiu veikimu. 

Renkami šių laukų duomenys:

- **Duration** – prabėgęs pablogėjusio veikimo laikas

- **EventType** – įvykio, per kurį pablogėjo veikimas, tipas


#### <a name="officeperformanceboot"></a>Office.Performance.Boot

Surinkta taikomosios programos „Office“ paleidimo metu. Nurodoma, ar paleidimas buvo pradėtas atidarant failą, ar paleidžiant per meniu Pradžia, ar tai buvo pirmasis taikomosios programos paleidimas, kiek atminties naudoja taikomoji programa, ir ar vartotojui buvo parodyta blokuojama vartotojo sąsaja. Naudojama išmatuoti, kaip greitai veikia taikomosios programos „Office“ paleidimas ir kiek atminties naudojama paleidimo metu, kad užtikrinti priimtiną vartotojo patirtį.

Renkami šių laukų duomenys:

- **ActivationKind** – ar taikomoji programa buvo pradėta naudojant Pradžios meniu, atidarant failą arba naudojant OLE automatizavimą.
  
- **BootToStart** – ar paleidžiant šią taikomąją programą vartotojas pasirinko rodyti pradžios ekraną.

- **Child ProcessesCount** – programos paleistų antrinių procesų skaičius. (tik „Windows“)

- **ColdBoot** – ar „Office“ taikomoji programa buvo paleista pirmą kartą paleidus sistemą iš naujo, ar reikėjo programos dvejetainį įkelti iš disko. (tik „macOS“/ „iOS“)

- **DeviceModel** – įrenginio modelis. (tik „macOS“/ „iOS“)

-  – atidarant dokumentą nurodo dokumentą pateikusią tarnybą („OneDrive“, „File Server“, „SharePoint“ ir kt.)

- **DurationUntilMso20Initialization** – trukmė mikrosekundėmis nuo „Office“ proceso pradžios iki mso20win32client.dll įkėlimo.

- **Embedding** – nesvarbu, ar programa buvo atidaryta OLE įdėjimui.

- **FirstBoot** – ar tai buvo pirmas taikomosios programos įkrovimas.

- **FreeMemoryPercentage** – kiek procentų atminties įrenginyje laisva. (tik „Windows“)

- **HandleCount** – proceso atidarytų operacinės sistemos sisteminių nuorodų skaičius. (tik „Windows“)

- **PageFaultCount** – aparatūrinių proceso puslapių klaidų skaičius. (tik „Windows“)

- **Initializationduration** – pirmojo „Office“ inicijavimo proceso trukmė mikrosekundėmis.

- **InterruptionMessageId** – ar paleidimas buvo pertrauktas dialogo lango, prašančio naudotojo atlikti įvestį, dialogo lango ID.

- **LegacyDuration** – veiklos vykdymo trukmė, matuojama naudojant skirtingus pradžios ir pabaigos taškus nei Activity.Duration.

- **OpenAsNew** – ar programa buvo paleista atidarius esamą dokumentą kaip šabloną naujam.

- **OtherOperationCount** – atliktų įvesties / išvesties operacijų, išskyrus skaitymo ir rašymo operacijas, skaičius. (tik „Windows“)

- **OtherTransferCount** – baitų, perduotų vykdant ne skaitymo ir rašymo operacijas, skaičius. (tik „Windows“)

- **PageFaultCount** – proceso puslapių klaidų skaičius. (tik „Windows“)

- **PrimaryDiskType** – ar pirminis saugyklos įrenginys yra netrinusis loginis diskas ar pasukamasis diskas bei jo pasukimo greitis (jei taikoma). (tik „macOS“/ „iOS“)

- **PrivateCommitUsageMB** – „Commit Charge“ (t. y. atminties, kurią atminties valdytojas paskyrė šiam procesui, kiekis) procesui megabaitais. (tik „Windows“)

- **TotalWorkingSetMB** – proceso darbinio rinkinio atminties kiekis, nebendrinamas su kitais procesais, nurodytas megabaitais. (tik „Windows“)

- **ProcessorCount** – procesorių skaičius įrenginyje. (tik „macOS“/ „iOS“)

- **ReadOperationCount** – atliktų skaitymo operacijų skaičius. (tik „Windows“)

- **ReadTransferCount** – perskaitytų baitų skaičius.

- **TotalPhysicalMemory** – bendras įrenginio fizinės atminties kiekis. (tik „macOS“/ „iOS“)

- **TotalWorkingSetMB** – proceso darbinio rinkinio atminties kiekis megabaitais.

- **VirtualSetMB** – proceso virtualiojo rinkinio atminties kiekis megabaitais. (tik „macOS“/ „iOS“)

- **WorkingSetPeakMB** – didžiausias atminties kiekis megabaitais, kuris iki šiol yra buvęs proceso darbiniame rinkinyje.

- **ReadOperationCount** – atliktų rašymo operacijų skaičius. (tik „Windows“)

- **ReadTransferCount** – parašytų baitų skaičius. (tik „Windows“)


#### <a name="officepowerpointpptandroidrehearseview"></a>Office.PowerPoint.PPT.Android.RehearseView

Šis įvykis reiškia, kad vartotojas sustabdė kartojimo seansą. Kartu su „Office.PowerPoint.PPT.Android.RehearseView.StartSession“ tai bus pirmasis bet kokių gedimų arba klaidų, su kuriomis susiduria vartotojas, indikatorius.

Renkami šių laukų duomenys:

- **ConnectionCreationTime** – tarnybų ryšiams kurti reikalingas laikas.

- **CountDownAlertTime** – laikas, kuriam buvo rodomas atgalinės atskaitos įspėjimas.

- **CountdownInitTime–** – laikas tarp skaidrių demonstravimo užbaigimo ir atgalinės atskaitos pradėjimo.

- **CritiqueSummary** – santrauka, kokius skaičius pamatė visi kritikos vartotojai.

- **ExitEventCode** – kodas, skirtas nustatyti, pagal kurį scenarijų vartotojas išeina iš repeticijos seanso, nesvarbu, ar tai buvo klaidos scenarijus, ar sėkmingas išėjimas. 

- **FRETime** – laikas nuo FRE ekrano pradėjimo rodyti iki atmetimo, inicijuoto vartotojo. 

- **MicrophonePermissionTime** – laikas, kurį buvo rodomas mikrofono įspėjimas iki vartotojas pasirinko vieną iš parinkčių.

- **PauseRehearsingCount** – skaičius, kiek kartų vartotojas spustelėjo pristabdyti repeticijas.

- **RehearsalInitTime** repeticijos inicijavimo trukmė.

- **ResumeRehearsingCount** – skaičius, kiek kartų vartotojas spustelėjo tęsti repeticijas.

- **Sessionid** – tai kalbos pagrindinių durų seanso ID. Tai naudojama derinti paslaugų žurnalus.

- **SlideshowViewLoadTime** – skaidrių demonstracijos įkėlimo laikas.


#### <a name="officepowerpointpptandroidrehearseviewrehearsalsummarypage"></a>Office.PowerPoint.PPT.Android.RehearseView.RehearsalSummaryPage 

Įvykis paleidžiamas, kai įkeltas suvestinės puslapis. Šis įvykis padeda mums užfiksuoti suvestinės puslapio rezultatus. Jis nurodo, kiek laiko užtrunka, kol reikia įkelti puslapį, kad būtų galima įkelti į klientą. Būtina išlaikyti funkcijų efektyvumą. 

Renkami šių laukų duomenys:

- **PayloadCreationTime** – tai laikas, užfiksuotas milisekundėmis, kad būtų sukurtas paketo turinys. 

- **PostUrlCallTime** – tai laikas, užfiksuotas milisekundėmis, kurio reikėjo, kad būtų nusiųstas Url skelbimo iškvietimas. 

- **RehearseSessionid** – tai kalbos pagrindinių durų seanso ID. Galime jį naudoti, kad galėtumėte derinti paslaugų žurnalus.

- **RequestPayloadSize** – tai užklauso paketo turinio dydis. 

- **ResourcesLoadTime** – tai laikas, užfiksuotas sekundėmis, kurio prireikė išteklių įkėlimui (js, css). 

- **SummaryPageErrorReceived** – tai Bulio logikos reikšmė, kuri nurodo, ar suvestinės puslapis buvo gautas, ar įvyko klaida.

- **SummaryPageHtmlLoadTime** – tai laikas, užfiksuotas sekundėmis, kurio prireikė įkelti summarypageHtml. 

- **SummaryPageLoadStartTime** – tai laikas užfiksuotas sekundėmis, kurio prireikė gauti pirmą atsakymą iš serverio. 

- **SummaryPageLoadTime** – laikas (milisekundėmis), kurio prireikė norint įkelti suvestinės puslapį. Tai apima naudingosios apkrovos kūrimo laiką 

- **ThumbnailsCount** – tai bendras miniatiūrų, kurios bus suvestinės puslapio dalimi, skaičius. 

#### <a name="officepowerpointpptandroidrehearseviewstartsession"></a>Office.PowerPoint.PPT.Android.RehearseView.StartSession

Įvykis paleidžiamas, kai vartotojas spustelėja pradėti seansą. Šis įvykis padeda mums užfiksuoti, kiek vartotojų naudoja pranešėjo pagalbinę priemonę „Android“. Kartu su „Office.PowerPoint.PPT.Android.RehearseView“ praneš mums, kiek vartotojų sėkmingai baigė repeticijos seansą ir kiek negalėjo. Tai mūsų pirmasis funkcijos gedimų arba klaidų indikatorius.
 
Renkami šių laukų duomenys:

 - Nėra


#### <a name="officepowerpointpptsharedrehearseviewerrors"></a>Office.PowerPoint.PPT.Shared.RehearseView.Errors

*[Šis įvykis anksčiau buvo vadinamas Office.PowerPoint.PPT.Android.RehearseView.Errors]*

Įvykis suaktyvinamas, kai įvyksta bet kokia klaida. Šis įvykis padės mums žinoti klaidas, su kuriomis susidūrė vartotojas, ir padės išlaikyti pranešėjo pagalbinės priemonės našumą mobiliuosiuose įrenginiuose.

Renkami šių laukų duomenys:

- **Session ID** – repeticijų seanso ID

- **RehearsalEventCode** – repeticijos klaidos kodas


#### <a name="officepowerpointrehearsalsessionmetrics"></a>Office.PowerPoint.Rehearsal.SessionMetrics 

Įvykis paleidžiamas, kai kalbėjimo seansas sustabdomas pranešėjo pagalbinei priemonei. Šis įvykis padeda mums užfiksuoti kai kurią metriką repeticijos seanse pranešėjo pagalbinėje priemonėje. Tai padės išlaikyti aukštą paslaugos kokybę šiai funkcijai.

Renkami šių laukų duomenys:

- **ActualRehearseBootTimeInMs** – tai tikrasis laikas, kurio prireikė, kad jungtys būtų sukurtos.

- **AdaptationTextSize** – tai teksto, kuris siunčiamas tarnybai, dydis.

- **AuthDurationInMs** – tai yra laikas milisekundėmis, kai naudojamas autentifikavimas (atnaujinti autentifikavimo atpažinimo ženklą).

- **AuthError** – tai aprašo įvyko autentifikavimo klaidą (jei įvyko).

- **AvgFragmentLatencyInMs** – tai vidutinis tinklo kalbos pranešimų kelionės pirmyn ir atgal laikas.

- **ConnectDurationInMs** – tai laikas, kai seansas baigs jungimąsi per milisekundes. 

- **FirstAudioDelayInMs** – tai laikas, per kurį turi būti gaunami pirmieji garsiniai duomenys.

- **FRetriedOnOpenConnection** – tai Bulio logika, kuri nurodo, ar bandymas iš naujo vykdomas atvirai jungčiai ar ne.

- **InitMediaCaptureLayerDurationInMs** – tai laikas, per kurį turi būti inicijuotas medijos / garso fiksavimo sluoksnis.

- **LocallyDroppedMessageCount** – tai bendras pranešimų, kurie buvo išmesti vietoje, skaičius.

- **NumReconnectAttemptsDuringSession** – tai nurodo, kiek kartų bandyta iš naujo prisijungti prie kalbos tarnybos.

- **NumTriesDuringEachReconnectAttempt** – tai yra klaidos kodas, kuris nurodo, kiek bandymų buvo atlikta kiekvieno bandymo prisijungti iš naujo metu.

- **OpenFrontDoorConnectionDurationInMs** – tai laikas milisekundėmis, kuris buvo paimtas norint atidaryti ryšį su „FrontDoor“ tarnyba.

- **SendAdaptationTextDurationInMs** – tai laikas, kai į tarnybą siunčiamas adaptacijos tekstas.

- **ServiceDroppedMessageCount** – tai bendras tarnybos išmestų pranešimų skaičius.

- **SessionDurationInMs** – tai viso seanso trukmė, skaičiuojama nuo tada, kai vartotojas paspaudė pradėti, iki tada, kai vartotojas paspaudė baigti.

- **SessionId** – tai kalbos pagrindinių durų seanso ID. Galime jį naudoti, kad galėtumėte derinti paslaugų žurnalus.

- **SpeechClientResultEventsWithTimestamps** – tai klaidų kodų, gautų kartu su laiko ženklais, kurie gali padėti taisyti, masyvas.

- **SpeechHResultsWithTimestamps** – tai klaidų kodų, gautų kartu su laiko ženklais, kurie gali padėti atlikti derinimą, masyvas.

- **StartSpeechCaptureDurationInMs** – tai laikas milisekundėmis, kol pradedama kalbėjimo fiksavimo funkcija.

- **NumTriesDuringEachReconnectAttempt** – tai laiko masyvas, užfiksuotas pradedant kalbos seansą kiekvieną kartą, kai buvo bandyta prisijungti iš naujo, įskaitant ir pirmo kalbos seanso pradžios trukmę. 

- **TotalMessageCount** – tai bendras į tarnybą siunčiamų garsinių pranešimų skaičius.

- **WebSocketConnectDurationInMs** – tai laikas, kai reikia baigti naudoti interneto lizdą.


#### <a name="officeuxofficeinsidercanshowofficeinsiderslab"></a>Office.UX.OfficeInsider.CanShowOfficeInsiderSlab

Veiklos stebėjimas nustatyti, ar „Office Insider“ informacijos dalis gali būti rodoma vartotojui „Office Backstage UI“ skirtuke Paskyra.

Renkami šių laukų duomenys:

  - **Data_CanShow** – nurodo, ar „Office Insider“ informacijos dalis gali būti rodoma vartotojui „Office Backstage UI“ skirtuke Paskyra.
  
  - **Data_Event** – nenaudojamas

  - **Data_EventInfo** – nenaudojamas

  - **Data_Reason** – nenaudojamas
 

#### <a name="officeuxofficeinsiderregistercurrentinsider"></a>Office.UX.OfficeInsider.RegisterCurrentInsider

Kritinis signalas, skirtas stebėti sėkmingą arba nesėkmingą vartotojų, kurie anksčiau nebuvo užregistruoti kaip „Office Insider“ programos dalyviai, registravimą naudojant „Office Insider“ komponavimo versijas. Jis visų pirma taikomas dabartiniams „Office Insider“ programos dalyviams, kurie prie „Office Insider“ programos prisijungė prieš įtraukiant „Office Insider“ programos dalyvių registraciją.

Renkami šių laukų duomenys:

- **Data_RegisterInsider** – „Office Insider“ registracijos būsena

- **Data_RegisterInsiderHr** – „Office Insider“ registracijos rezultatų kodas

- **Data_RegistrationStateCurrent** – dabartinė registracijos būsena

- **Data_RegistrationStateDesired** – prašoma registracijos būsena


#### <a name="officeuxofficeinsidershowofficeinsiderdlg"></a>Office.UX.OfficeInsider.ShowOfficeInsiderDlg

Kritinis signalas, naudojamas vartotojo sąveikai su dialogu „Prisijunkite prie „Office Insider“ stebėti. Jis naudojamas nustatyti bet kokioms problemoms, kurios kyla vykdant vartotojo inicijuotus pakeitimus, tokius kaip prisijungimas prie „Office Insider“ programos, pasitraukimas iš jos arba „Office Insider“ programos dalyvio lygio pakeitimas.

Renkami šių laukų duomenys:

- **Data_AcceptedContactMeNew** – nurodo, ar vartotojas sutiko, kad prisijungus prie „Office Insider“ programos, „Microsoft“ su juo susisiektų

- **Data_InsiderLevel** – „Insider“ lygis atidarant dialogo langą „Prisijunkite prie „Office Insider“

- **Data_InsiderLevelNew** – „Insider“ lygis uždarant dialogo langą „Prisijunkite prie „Office Insider“

- **Data_IsInternalUser** – nurodo, ar taikomoji programa vykdoma naudojant „Microsoft“ įmonės paskyros kredencialus.

- **Data_IsInternalUser** – nurodo, ar kodas gali nustatyti, ar taikomoji programa vykdoma naudojant „Microsoft“ įmonės paskyros kredencialus.

- **Data_OpenNewsletterWebpage** – nurodo, ar „Office Insider“ informacinio biuletenio prenumeratos saitas buvo paspaustas su sąlyga, kad vartotojas prisijungė prie „„Office Insider“ programos, naujienlaiškio prenumeratos funkcija įjungta ir vartotojas neatšaukė „Office Insider“ naujienlaiškio prenumeratos svetainės atidarymo.
    
- **Data_RegisterInsider** – „Office Insider“ registracijos būsena

- **Data_RegisterInsiderHr** – „Office Insider“ registracijos rezultatų kodas

- **Data_RegistrationStateCurrent** – dabartinė registracijos būsena

- **Data_RegistrationStateDesired** – prašoma registracijos būsena


#### <a name="officevisiosharedvisiofilerender"></a>Office.Visio.Shared.VisioFileRender

Šis įvykis užfiksuoja failo generavimo laiką. Šis įvykis padeda išlaikyti failo generavimo veikimo patikrą.

Renkami šių laukų duomenys:

  - **Data\_AvgTime: integer** – Vidutinis laikas, per kurį seanse buvo generuotas „Visio“ piešimo vaizdas

  - **Data\_CompositeSurfEnabled: bool** – „ True“, jei įgalintas sudėtinis vaizdo generavimo režimas

  - **Data\_Count: integer** – Laikas, kada „Visio“ generuoja piešimo seanso vaizdą

  - **Data\_FirstRenderTime: long** – Trukmė, skirta pirmą kartą generuoti failą, milisekundėmis

  - **Data\_AvgTime: integer** – Vidutinis laikas, per kurį seanse buvo generuotas „Visio“ piešimo vaizdas


#### <a name="officevisiovisiofileopenreliability"></a>Office.Visio.VisioFileOpenReliability

Šis įvykis renka failo atidarymo našumo duomenis, skirtus „Visio“ Dev16. Šis įvykis naudojamas failo atidarymo našumui stebėti ir susieti jį su failo ypatybėmis, pvz., failo dydžiu, skirtu „Visio“ Dev16. Failo ypatybės leidžia greičiau pašalinti ir šalinti problemas.

Renkami šių laukų duomenys:

  - **Data\_CorrelationId: string -** Dokumento sąsajos identifikatorius

  - **Data\_DocIsEnterpriseProtected: bool -** „True“, jei dokumentas yra apsaugotas naudojant „Windows“ informacijos apsaugą

  - **Data\_DocumentId: string -** GUID failo kelias

  - **Data\_DurationToCompleteInMilliseconds: double -** Trukmė, kol atliekamas veiksmas Įrašyti kaip, milisekundėmis

  - **Data\_DurationToCompleteInMillisecondsSquared: double -** kvadratu pakelta reikšmė DurationToCompleteInMilliseconds

  - **Data\_ErrorCode: integer -** Failo atidarymo trikties vidinio kodo klaida

  - **Data\_Extension\_Docs: string -** Atidarytos diagramos failo plėtinys

  - **Data\_FileIOBytesRead: int -** Perskaitytų baitų skaičius įrašant

  - **Data\_FileIOBytesReadSquared:int -** kvadratu pakelta duomenų reikšmė\_FileIOBytesRead

  - **Data\_FileIOBytesWritten: int -** Bendras baitų kiekis įrašant

  - **Data\_FileIOBytesWrittenSquared: int -** kvadratu pakelta duomenų reikšmė\_FileIOBytesWritten

  - **Data\_FileName: binary -** Dvejetainė failo vardo maiša

  - **Data\_FileOpenDownloadDurationInMs: long -** Failo atsisiuntimo trukmė milisekundėmis

  - **Data\_FileOpenEndDurationInMs: long: -** Failo atidarymo trukmė milisekundėmis

  - **Data\_FileOpenTimeStamp: time: -** Laiko žyma, kai pradėtas failo atidarymas

  - **Data\_FilePathHash: binary -** Failo kelio GUID 

  - **Data\_FileSize: long -** Dokumento dydis baitais

  - **Data\_FileType: string -** Atidarytos diagramos failo plėtinys

  - **Data\_IsInternalFile: bool -** „True“, jei failas yra vidinis failas. pvz., šablonų rinkinys

  - **Data\_IsIRM: bool -** „True“, jei failas turi informacijos teisių apsaugą

  - **Data\_IsReadOnly: bool -** „True“, jei failas yra tik skaitomas

  - **Data\_IsSuccess: bool -** „True“, kai failo atidarymas pavyko

  - **Data\_Location: string -** Failo vieta, pvz., vietinis, „SharePoint“, „OneDrive“, „WopiConsumer“, „WopiBusiness“, „GenericThirdPartyConsumer“

  - **Data\_NetworkIOBytesRead: int -** Perskaitytų tinklo baitų skaičius įrašant

  - **Data\_NetworkIOBytesReadSquared: int -** kvadratu pakelta duomenų reikšmė\_NetworkIOBytesRead

  - **Data\_NetworkIOBytesWritten: int -** Bendrasis tinklo baitų kiekis išsaugant

  - **Data\_NetworkIOBytesWrittenSquared: int -** kvadratu pakelta duomenų reikšmė NetworkIOBytesWritten

  - **Data\_OpenLocation: integer -** Failo vieta, iš kurio buvo atidaryta 0, vietinis, 1, tinklas, 2, „SharePoint“, 3 – žiniatinklis

  - **Data\_Size\_Docs: integer -** Dokumento dydis baitais

  - **Data\_Tag: string -** Unikalus identifikatorius nustatyti įvykio funkcijai Įrašyti kaip

  - **Data\_WasSuccessful: bool -** „True“, jei atidaryti pavyko


#### <a name="onenoteappsafebootdialogactiontaken-officeonenoteandroidsafebootdialogactiontaken-officeandroidearlytelemetrysafebootdialogactiontaken"></a>OneNote.App.SafeBootDialogActionTaken, Office.OneNote.Android.SafeBootDialogActionTaken, Office.Android.EarlyTelemetry.SafeBootDialogActionTaken

Kritinis signalas, naudojamas vartotojo atsakui sekti, kai vartotojas mato saugos įkrovos dialogo langą. Saugaus paleidimo dialogo langas rodomas, kai nepavyksta paleisti pakartotinai. Vartotojas renkasi saugią paleistį, kad būtų galima sėkmingai paleisti programos duomenis. Tai naudojama siekiant užtikrinti regresijos aptikimą, kuris ypač svarbus programai „OneNote“ ir tarnybos sveikatai. Vartotojas mato, kai susiduria su kritine įkrovos gedimo klaida. Ši informacija padės sekti, jei buvo išspręsta gedimo triktis ir ar vartotojas gali sėkmingai įjungti programą.

Renkami šių laukų duomenys: 

- **DIALOG_ACTION** – kurį dialogo langą vartotojas spustelėjo – mygtukas teigiamas arba neigiamas


#### <a name="perfevent"></a>perf.event

Naudojama stebėti galimą neigiamą poveikį dėl skirtingų programos dalių įkėlimo, pvz., siekiant užtikrinti kuo spartesnį gautų laiškų aplanko įkėlimą pirmą kartą atidarant programą.

Renkami šių laukų duomenys: 

- **app_start_show_message_list** – tai reiškia, kad kilo programos paleisties problemų, dėl kurių ilgiau užtruko aplanko Gauta pranešimų sąrašo įkėlimas

- **average** – surenka pokalbio įkėlimų iš naujo skaičių, padalytą iš to pokalbio pranešimų skaičiaus.  

- **event_type** – nurodo tipą veikimo įvykio, dėl kurio kilo problema, kad galėtume nustatyti su tam tikru tipu susijusias problemas.   

- **extra_params** – čia kūrėjas gali įtraukti papildomų parametrų, kad galėtume pateikti daugiau informacijos apie tai, kas galėjo sukelti šią veikimo problemą, t. y. kada šis veiksmas buvo pradėtas, baigtas ir t. t. 

-   **has_work_profile** – nurodo, ar programa veikia „Android“ darbo profilyje ar panašioje konfigūracijoje, kad būtų galima susieti veikimo analizę su tomis aplinkomis.

- **profiling_summary** – teikia informaciją apie užduočių grupes, užduočių skaičių ir vidutinę jų laiką, kad būtų lengviau suprasti galimas tam tikrose srityse, kai programa įkeliama, regresijos sritis

- **runtime_performance_monitoring_data** – teikia produktyvumo duomenis (pakrovimo laiką, įrašų skaičių), kai duomenys įkeliami į skirtingas programos dalis.
  - **average_cost_time_ns** – vidutinį išlaidų laiką, įvertintą nanosekundėmis.
  - **cost_type** – praneša mums, ar šis įvykis skirtas saugyklos lygio arba bendros trukmės matavimui.
  - **hx_object_type** – pateikia matavimų duomenų planavimo objekto tipą.
  - **is_main_thread** – praneša mums, ar šis įvykis nurodo tik pagrindinio gijos įvykdymo laiką.
  - **record_count** – įrašų, kuriuos pateikia esamos saugyklos sluoksnio, skaičius.
  - **scope_name** – nurodo vartotojo sąsajos puslapį/komponentus, kuriems šis įvykis priklauso.
  - **average_cost_time_ns** – nurodo vidutinį išlaidų laiką, įvertintą nanosekundėmis. 

- **total_time_elapsed** – nurodo, kiek laiko truko įvykis, kad galėtume įvertinti problemos rimtumą

#### <a name="performancerecord"></a>performance.record

Šis įvykis renka programos produktyvumo metriką. Tai leidžia nustatyti ir ištaisyti situacijas, kai programos atminties ir CPU naudojimas tampa kritiškai didelis arba atsiranda kitų veiklos problemų, dėl ko gali sulėtėti įrenginys.

Renkami šių laukų duomenys: 

- **app_exit_metric** – pateikia mums metriką apie skirtingų priekinio plano ir fono programų išėjimų veiklos tipų skaičių ir taip padeda mums suprasti programos netikėtus išėjimus su neigiamomis veiklos priežastimis.

- **average_suspended_memory** – praneša mums apie vidutinį programos naudojamos atminties jai sustojus kiekį, kad turėtume su kuo palyginti ir suprasti neigiamą įtaką veikimui.

- **category** – nurodo, ar programa tuo metu buvo priekiniame plane, ar fone. Galimos reikšmės yra priekinis planas ir fonas.

- **cpu_usage** – nurodo, kiek CPU naudojo programa, kad turėtume su kuo palyginti ir suprasti neigiamą įtaką veikimui

- **cumulative_CPU_time** – pateikia mums bendrą CPU laika, kurį sunaudojo programa, kartu su laiko trukme, kad turėtume su kuo palyginti ir suprasti neigiamą įtaką veikimui.

- **cumulative_GPU_time** – pateikia mums bendrą GPU laiką naudojamą programos, kad mes galėtume palyginti, o tai padeda mums suprasti neigiamą akumuliatoriaus veikimo laiko įtaką.

- **is_watch_app_installed** – nurodo, ar vartotojas šiuo metu naudoja „Apple Watch“ ir ar ji įdiegta, kad būtų galima suprasti neigiamą įtaką dėl „Watch“.

- **is_watch_paired** – nurodo, ar vartotojas šiuo metu naudoja „Apple Watch“ ir ar ji susieta su įrenginiu, kad būtų galima suprasti neigiamą įtaką dėl „Watch“

- **is_watch_supported_and_active** – nurodo, ar vartotojas šiuo metu naudoja „Apple Watch“ ir ar ji aktyvi, kad būtų galima suprasti neigiamą įtaką dėl „Watch“.

- **memoAry_used_percentage** – nurodo, kiek procentų atminties naudojo programa, kad turėtume su kuo palyginti ir suprasti neigiamą įtaką veikimui

- **memory_used** – nurodo, kiek atminties naudojo programa, kad turėtume su kuo palyginti ir suprasti neigiamą įtaką veikimui

- **peak_memory_usage** – nurodo didžiausią programos naudojamos atminties kiekį, kad turėtume su kuo palyginti ir suprasti neigiamą įtaką veikimui.

- **scroll_hitch_time_ratio** – nurodo laiko, praleisto prikabinti slenkant vartotojo sąsaja, koeficientą, kad galėtume suprasti neigiamą įtaką vartotojo sąsajos veikimui.


### <a name="application-activity-error-subtype"></a>*Taikomosios programos veiklos klaidos potipis*

Funkcijos ar vartotojo patirties veikimo klaidos.

#### <a name="assertion"></a>assertion

Šis įvykis leidžia nustatyti, kada įvyko kritinių programų klaidų, dėl kurių programa galėjo sugesti arba kilti rimtų problemų, pvz., aplanke Gauta rodomos tuščios eilutės.

Renkami šių laukų duomenys:

- **count** – bendras su klaida susijusių elementų skaičius; pvz., kalendorių, kuriuose yra klaidų, skaičius

- **has_hx** – nurodo, kad paskyra naudoja mūsų naują sinchronizavimo tarnybą, kad būtų galima aptikti sinchronizavimo tarnybos sukeltas problemas

- **host_name** – tarnybinio serverio pavadinimas, kuris buvo susijęs su klaida, kad būtų galima aptikti su tam tikru serveriu susijusias problemas

- **host_type** – serverio, kuris buvo susijęs su klaida, tipas, kad būtų galima aptikti su tam tikru serverio tipu susijusias problemas

- **message** – pasirinktinis pranešimas apie teiginį, kuris naudojamas problemai diagnozuoti 

- **origin** – klaidos kodo kilmė, kuri padeda nustatyti su tam tikra kodo dalimi susijusias problemas

- **stacktrace** – rietuvės pėdsakas, kur įvyko teiginys, padedantis mums aptikti su tam tikra kodo dalimi susijusias problemas

- **type** – įvykusios teiginio klaidos tipas, pvz., null_folder_name, compose_selected_null_account, kuris padeda nustatyti su tam tikra kodo dalimi susijusias problemas

#### <a name="editcontacterror"></a>edit.contact.error

Leidžia nustatyti ir pataisyti situacijas, kai klaidos įvyksta bandant peržiūrėti arba redaguoti kontaktus naudojant programą.

Renkami šių laukų duomenys: 

- **errorType** – įvykusios klaidos tipas, kad galėtume diagnozuoti problemą

- **field** – kontakto laukas, kurį vartotojas bandė redaguoti, kad būtų galima diagnozuoti problemą

- **version** – mūsų naudojamos kontaktinės kortelės tarnybos versija, kad būtų galima diagnozuoti problemą

#### <a name="errorreport"></a>error.report

Šis įvykis leidžia aptikti kritines programos klaidas, kad galėtume išvengti problemų, dėl kurių programa gali užstrigti arba neleisti skaityti el. laiškų. 

Renkami šių laukų duomenys: 

- **client-request-id** – kliento užklausos, dėl kurios įvyko klaida, identifikatorius
 
- **date** – užklausos, dėl kurios įvyko klaida, datos žymė

- **error** – klaidos tipas, pvz., get_mailbox_location_failed
 
- **error_body** – klaidos pranešimo tekstas
 
- **is_x_mailbox_anchor_set** – ar užklausai buvo nustatyta ypatybė X-AnchorMailbox
 
- **reason** – klaidos priežastis, t. y. klaidos pranešimas
 
- **request-ID** – serverio užklausos, dėl kurios įvyko klaida, identifikatorius
 
- **source** – klaidos šaltinis OM infrastruktūroje, paprastai vienas iš BE arba FE


#### <a name="officeairspacebackendwin32graphicsdriversofthang"></a>Office.AirSpace.Backend.Win32.GraphicsDriverSoftHang 

Padeda „Microsoft“ atskirti ilgą vaizdo plokštės tvarkyklės „pakibimą“ nuo trumpo, o tai savo ruožtu padeda priimti sprendimus apie tai, kurios vaizdo plokštės tvarkyklės gali turėti problemų. Dėl vartotojo vaizdo plokštės tvarkyklės„pakibo“„Office“, bet „pakibimo“ poveikis dar nežinomas

Renkami šių laukų duomenys:

  - **Data\_InDeviceCall** – Vaizdo plokštės metodas, dėl kurio įvyko „pakibimas“

  - **Data\_Timeout** – kiek laiko truko „pakibimas“

  #### <a name="officeandroidadalsigninuiprompts"></a>Office.Android.ADALSignInUIPrompts

Šis įvykis nurodo, kad prisijungimo raginimas buvo pateiktas vartotojui, mokyklos arba darbo paskyrai.  Šis įvykis padeda suprasti prisijungimo prie mūsų taikomųjų programų būsenos sveikatą ir imtis reikiamų veiksmų, kai pastebime netikėtus prisijungimo raginimus. 

Renkami šių laukų duomenys:

- **LastLoginDelta** – laiko pokytis nuo paskutinio sėkmingo prisijungimo.

- **PreviousIdentityCredProviderState** – nurodo paskyros būseną.

- **PreviousIdentityState** – nurodo paskyros būseną, pvz., baigėsi seansas. 

- **SignInResultCode** – nurodo raginimo prisijungti baigimo rezultato kodą.

- **UseCache** – nurodo, ar mes primygtinai raginome vartotoją dar kartą pateikti slaptažodį.

- **UserType** – nurodo, ar tai yra egzistuojanti paskyra, ar nauja paskyra

#### <a name="officeandroidandroidappdocsfileoperationends"></a>Office.Android.AndroidAppDocsFileOperationEnds

Tik „Android“ skirtų svarbių dokumentų („AppDocs“) telemetrijos duomenys, skirti baigiamosioms operacijoms naujas failas / atidaryti / įrašyti kaip. Ši funkcija fiksuoja šių „AppDocs“ operacijų klaidų kodus.  „Microsoft“ šią funkciją naudoja klaidoms įvairiose failų operacijose ir tiksliam sluoksniui, kuriame įvyko „W/X/P“ taikomųjų programų triktis, nustatyti.

Renkami šių laukų duomenys:

- **AccessMode** – išvardijimo vertė, skirta failo prieigos režimui. Reikšmės – None (nėra), ReadOnly (tik skaityti), ReadOnlyUpgradable (tik skaityti / atnaujinamas), ReadWrite (skaityti / rašyti)

- **BlockingUIShown** – Bulio logika, rodanti, ar vartotojo sąsajos blokavimas buvo rodomas sraute.

- **ContentUriAuthority** – turinio URL prieiga iš SAF

- **Correlation** – GUID, skirtas su operacija susietos ID koreliacijai

- **DocId** – dokumento ID, sugeneruotas „AppDocs“

- **DocInstanceId** – DocInstanceId yra dokumento egzemplioriaus ID, sugeneruotas „AppDocs“, aprėpto operacijos egzemplioriaus dokumente

- **DocIsEnterpriseProtected** – Bulio logika, rodanti, ar dokumentas yra apsaugotas.

- **DocUserId** – vartotojo ID iš MS autentifikavimo sluoksnio

- **DocUserIdProvider** – išvardijimas, nurodantis vartotojo ID teikėją, 0 = nežinomas, 1 = „Live ID“, 2 = OrgId, 3 = SSPI; 4 = ADAL

- **DurationInMs** – failo operacijos užbaigimui skirtas laikas milisekundėmis

- **EndReason** – išvardijimo reikšmė, nurodanti užbaigimo priežastį.  Reikšmės – None, Success, Failure, Cancel

- **ErrorCode** – failo operacijos klaidos kodas

- **Extension** – atidaryto failo plėtinys.

- **FileSourceLocation** – failo vietos išvardijimo reikšmė. Galimos reikšmės: None, Local, UncOrMappedNetworkDrive, SkyDrive, App, SharePoint, UnknownServer

- **FILETIME** – įvykio trukmė

- **FirstBCSClientError_Info** – klaidos kodo informacija, susijusi su failų konvertavimais

- **HttpStatusCode** – žiniatinklio tarnybos užklausos http atsako kodas

- **InitalizationReason** – failo atidarymo įvesties vieta

- **K2FileIOHresult** – failo atidarymo operacijos užbaigimo Hresult kodas

- **LastBCSClientError_TagId** – paskutinė BCS (dvejetainė konvertavimo tarnyba) kliento klaida

- **OfficeWebServiceApiStatusFlag** – žiniatinklio tarnybos užklausos būsenos vėliavėlė

- **OpEndEventId** – žymė, nurodanti, kur iš tikrųjų baigėsi operacija

- **OpFlags** – dokumentų operacijos parametrų vėliavėlės, naudojamos „AppDocs“ sluoksnio.

- **OpSeqNum** – skaičius, nurodantis su failo operacija susijusių kvietimų seką „AppDocs“ sluoksnyje

- **OpType** – operacijos tipo išvardijimas. Reikšmės: „None“ (nėra), „CreateDocument“ (sukurti dokumentą), „OpenDocument“ (atidaryti dokumentą), „CopyDocument“ (kopijuoti dokumentą), „CloseDocument“ (uždaryti dokumentą), „SaveDocument“ (įrašyti dokumentą), „OpenVersion“ (atidaryti versiją), „CloseVersion“ (uždaryti versiją)

- **PreFetchState** – naujo failo sukūrimo operacijų išankstinio šablonų paėmimo būsenos išvardijimas.

- **ProviderApp** – taikomosios programos, kurioje atidarytas failas, paketo pavadinimas

- **ScopeInstanceId** – aprėpties egzemplioriaus ID, naudojamas prijungti duomenų kontekstą prie veiklų

- **Size** – failo dydis

- **State** – failo būsenos išvardijimo vertė. Reikšmės: None (nėra), Creating (kuriama), Created (sukurta), CreateFailed (sukurti nepavyko), Opening (atidaroma), Opened (atidarytas), OpenFailed (atidaryti nepavyko), Copying (kopijuojama), Copied (nukopijuota), CopyFailed (nukopijuoti nepavyko), Closing (uždaroma), Closed (uždaryta), CloseFail (uždarymas nepavyko)

- **TemplateName** – dokumento šablono dvejetainis šablono pavadinimas iš šablono tarnybos, pvz., TF10002009.dotx

- **UriScheme** – URL schema

#### <a name="officeandroidandroidautherror"></a>Office.Android.AndroidAuthError

Šis įvykis žymi pagrindines autentifikavimo triktis automatinio atpažinimo ženklo atnaujinimo metu, prisijungimo puslapio iš tarnybos įkėlimo metu ir t. t.  Šis įvykis padeda suprasti prisijungimo prie mūsų taikomųjų programų būklės sveikatą, atliktus prisijungimo bandymus ir imtis reikiamų veiksmų, kai pastebime netikėtas triktis. 

Renkami šių laukų duomenys:

- **ADALErrorCode** – nurodo klaidos kodą, kai rodomas prisijungimo raginimas arba tylaus atpažinimo ženklo iškvietimo bandymas darbo paskyrai.

- **ADALRawErrorCode** – nurodo pirminį klaidos kodą, kai rodomas prisijungimo raginimas arba tylaus atpažinimo ženklo iškvietimo bandymas darbo paskyrai.

- **ErrorGroup** – nurodo paskyros tipą, pvz., asmeninė paskyra, darbo paskyra arba vietinė darbo paskyra.

- **IDCRLErrorCode** – nurodo klaidos kodą, kai rodomas prisijungimo raginimas asmeninei paskyrai.

- **IDCRLRawErrorCode** – nurodo pradinį klaidos kodą, kai rodomas prisijungimo raginimas asmeninei paskyrai.

- **LiveOAuthErrorCode** – nurodo klaidos kodą automatinio atpažinimo ženklo asmeninei paskyrai atnaujinimo bandymo metu.

- **LiveOAuthRawErrorCode** – nurodo pradinį klaidos kodą automatinio atpažinimo ženklo asmeninei paskyrai atnaujinimo bandymo metu.

- **NTLMErrorCode** – nurodo klaidos kodą, kai rodomas prisijungimo raginimas vietinei darbo paskyrai.

#### <a name="officeandroidandroidfileasyncsavestatus"></a>Office.Android.AndroidFileAsyncSaveStatus

Fiksuoja failo asinchroninio įrašymo būsenos duomenis ir įvairius skirtingų komponentų klaidų kodus.  „Microsoft“ naudoja šiuos duomenis, kad galėtų išanalizuoti, ar nėra vartotojo duomenų praradimo taikomojoje programoje įrašant failus „Word“, „Excel“ ar „PowerPoint“ programose.

Renkami šių laukų duomenys:

- **FileExtension** – failo plėtinys

- **FileIOSaveHResult** – failo įrašymo operacijos HResult

- **FileIOSaveIsCopy** – Bulio logika, rodanti, ar operacija yra kopijos įrašymas.

- **FileSize** – failo dydis

- **FileSourceLocation** – failo šaltinio vietos išvardijimas. Reikšmės: None, Local, UncOrMappedNetworkDrive, SkyDrive, App, SharePoint, UnknownServer

#### <a name="officeandroidandroidfileopenreliability"></a>Office.Android.AndroidFileOpenReliability

Tai fiksuoja failo atidarymo būsenos duomenis ir įvairius klaidų kodus, kad nustatyti tikėtinas failo atidarymo triktis ir palyginti su triktimis, kurių nesitikima, bei nurodyti pranešančio kodo dalį.  „Microsoft“ naudoja šiuos duomenis, kad išanalizuotų failų atidarymo trikčių priežastis ir apskaičiuotų kritinę metriką, pvz., failų atidarymo sėkmės rodiklį programose „Word“, „Excel: arba „PowerPoint“.

Renkami šių laukų duomenys:

- **AccessMode** – prieigos režimo išvardijimas

- **AppDocsFileOpenErrorCode** – „AppDocs“ failo atidarymo klaidos kodas

- **ContentUriAuthority** – turinio URL prieiga iš SAF

- **DownloadCsiError** – atsisiuntimo klaidos pranešimas iš CSI

- **FileExtension** – failo plėtinys

- **FileOpenEndErrorCode** – failo atidarymo klaidos kodas

- **FileOpenStatus** – failo atidarymo būsenos išvardijimas

- **FileSize** – failo dydis

- **FileSourceLocation** – failo vietos išvardijimas

- **FirstBCSClientError_Info** – paskutinė BCS (dvejetainė konvertavimo tarnyba) kliento klaida

- **IfWordFileOpenCancelled** – jei failo atidarymas buvo atšauktas vartotojo programoje „Word“

- **InitializationReason** – failo atidarymo įvesties vietos išvardijimas

- **IsAutoSaveDisabled** – ar automatinis įrašymas išjungtas failo atidarymo metu

- **IsFileEmpty** – Bulio logika rodanti, ar failas yra tuščias

- **K2FileIOHresult** – failo operacijos užbaigimo Hresult

- **OpenCsiError** – failo atidarymo klaidos pranešimas, esantis CSI sluoksnyje

- **OpEndEventId** – Operacijos faktinės užbaigimo vietos žymė

- **PPTHresult** – PPT Hresult

- **PPTIsExpectedError** – failo atidarymo tikėtinos / netikėtos trikties PPT klaidos klasifikavimas 

- **PPTTag** – klaidų žymė PPT

- **ProviderApp** – taikomosios programos, kurioje atidarytas failas, paketo pavadinimas

- **ProviderFileSize** – užfiksuotas failo dydis atidarant failą per failo aktyvinimą

- **State** – failo atidarymo būsenos išvardijimas.

- **UriScheme** – URL schema

- **WordErrortag** – klaidos žymė programoje „Word“

- **WordFileCorruptionReason** – gedimo priežastis, dėl kurio „Word“ failo gali nepavykti atidaryti

- **WordFileOpenErrorCode** – specifinis „Word“ failo atidarymo klaidos kodas.

- **WordFileTypeFromDod** – „Word“ failo tipo nustatymas, paremtas faktiniu failo formatu

- **WordFileTypeFromExtension** – „Word“ failo tipo nustatymas, paremtas faktiniu failo plėtiniu

#### <a name="officeandroidandroidfilesavestatus"></a>Office.Android.AndroidFileSaveStatus

Svarbu užfiksuoti failo asinchroninio įrašymo būsenos duomenis ir įvairius skirtingų komponentų klaidų kodus.  „Microsoft“ naudoja šiuos duomenis, kad galėtų išanalizuoti, ar nėra vartotojo duomenų praradimo taikomojoje programoje įrašant failus „Word“, „Excel“ ar „PowerPoint“ programose.

Renkami šių laukų duomenys:

- **AccessMode** – reikšmės**: None, ReadOnly, ReadOnlyUpgradable, ReadWrite.

- **AppDocsEndReason** – failo įrašymo AppDoc EndReason išvardijimas.  Reikšmės: None, Success, Failure, Cancel.

- **AppDocsErrorCode** – failo įrašymo trikties galutinės klaidos kodas

- **AppDocsTriggeringSaveDetails** – laukas, rodantis, ar AppDocs suaktyvina įrašymą

- **DocInstanceId** – DocInstanceId yra dokumento egzemplioriaus ID, sugeneruotas „AppDocs“, aprėpto operacijos egzemplioriaus dokumente

- **ExcelFileSaveResult** – specifinis „Excel“ HResult

- **FileExtension** – failo plėtinys.

- **FileIOSaveErrorCode** – klaidos kodas, esantis FileIO

- **FileIOSaveHResult** – HRESULT, esantis FileIO

- **FileIOSaveIsCopy** – Bulio logika, rodanti, ar tai yra kopijavimo operacija

- **FileSize** – failo dydis

- **FileSourceLocation** – failo vietos išvardijimas.  Reikšmės: None, Local, UncOrMappedNetworkDrive, SkyDrive, App, SharePoint, UnknownServer

- **OpFlags** – įrašymui skirtos operacijų vėliavėlės

- **PPTFileSaveFailHresult** – nepavykusio įrašymo PPT Hresult

- **PPTFileSaveFailTag** – PPT žymė nepavykusiam įrašymui

- **State** – failo atidarymo būsenos išvardijimas. 

- **Reikšmės** – None, Creating, Created, CreateFailed, Opening, Opened, OpenFailed, Copying, Copied, CopyFailed, Closing, Closed, CloseFail

- **WordFileCopyErrorTrackbackTag** – atsekamumo žymė trikčiai yra CopyDocument etapas „Word“

- **WordFileSaveCancelReason** – atsekamumo žymė, atšaukimams programoje „Word“

- **WordFileSaveEid** – „Word“ specifinis klaidos kodas

- **WordFileSaveErrorTrackbackTag** – atsekamumo žymė įrašymo triktims

- **WordFileSaveOpResult** – rezultato būsenos išvardijimas: 0 – pavyko, 1 – nepavyko, 2 – atšaukta

- **WordFileSaveSuccess** – specifinės „Word“ sėkmingo failo įrašymo operacijos informacijos išvardijimas.

#### <a name="officeandroidandroidofficeactivationlatency"></a>Office.Android.AndroidOfficeActivationLatency

Kritiniai duomenys, renkantys visų failų, atidaromų taikomosiose programose „Windows“, „Excel“, „PowerPoint“, tiesioginio failo atidarymo laiką.  Tai naudojama „Microsoft“, kad sužinoti mūsų taikomųjų programų failo atidarymo efektyvumo metriką

Renkami šių laukų duomenys:

- **AppBootingOccured** – Bulio logika, skirta patikrinti, ar baigtas taikomosios programos paleidimas

- **ApplicationBootTime** – specifinei taikomosios programos paleidimo fazei reikalingas laikas

- **AppSuspendedDuringBoot** – Bulio logika, skirta patikrinti, ar taikomoji programa buvo laikinai sustabdyta paleidimo metu

- **BlockingUIShownDuringFileOpen** – Bulio logika, rodanti, ar failo atidarymo operacijos metu buvo rodomas blokavimo dialogo langas

- **CachedInfoAvailable** – Bulio logika, ieškanti talpykloje saugomo informacijos apie failo atidarymo operaciją

- **DocumentRecoveryInvoked** – Bulio logika, rodanti, ar buvo atkūrimo laukiantis dokumentas

- **EndToEndActivationTime** – laikas, skirtas failui, atidarytam ne taikomojoje programoje, generuoti

- **EndToEndFileOpenTime** – laikas, skirtas failui, atidarytam taikomojoje programoje, generuoti

- **FileOpenPhaseDurationInMs** – failo atidarymo operacijos laikas, sunaudotas tam tikro etapo metu

- **FileSourceLocation** – failo vietos išvardijimo reikšmė, pvz., None, Local, UncOrMappedNetworkDrive, SkyDrive, App, SharePoint, UnknownServer

- **InitalizationReason** – failo atidarymo įvesties vieta

- **InitialBootPhaseTime** – specifinei taikomosios programos paleidimo fazei reikalingas laikas

- **IsThisFirstLaunch** – Bulio logika, rodanti, ar tai yra pirmasis taikomosios programos paleidimas

- **MinimumLibraryLoadPhaseTime** – specifinei taikomosios programos paleidimo fazei reikalingas laikas

- **MinimumLibraryLoadPhaseTime** – specifinei taikomosios programos paleidimo fazei reikalingas laikas

- **MinimumLibraryLoadPhaseTime** – specifinei taikomosios programos paleidimo fazei reikalingas laikas

- **PostAppInitTimeInMs** – specifinei taikomosios programos paleidimo fazei reikalingas laikas

- **PPTRenderPhase** – laikas susijęs su tam tikru PPT generavimo etapu

- **PreAppInitTimeInMs** – specifinei taikomosios programos paleidimo fazei reikalingas laikas

- **ProviderApp** – taikomosios programos, kurioje atidarytas failas, paketo pavadinimas

- **TelemetryReason** – panaši į InitialisationReason, bet išsamesnė išvardijimo reikšmė, susijusi su atidaromo failo įvedimo vieta.

- **UserDialogInterruptionDuringBoot** – Bulio logika, rodanti, ar paleidimo metu buvo rodomas blokavimo dialogo langas

- **XLRenderPhase** – laikas susijęs su tam tikru „Excel“ generavimo etapu

#### <a name="officeandroidappdocsfileoperationends"></a>Office.Android.AppDocsFileOperationEnds

Tik „Android“ skirtų svarbių dokumentų („AppDocs“) telemetrijos duomenys, skirti baigiamosioms operacijoms naujas failas / atidaryti / įrašyti kaip. Ši funkcija fiksuoja šių „AppDocs“ operacijų klaidų kodus.  „Microsoft“ šią funkciją naudoja klaidoms įvairiose failų operacijose ir tiksliam sluoksniui, kuriame įvyko „W/X/P“ taikomųjų programų triktis, nustatyti.

Renkami šių laukų duomenys:

- **AccessMode** – išvardijimo vertė, skirta failo prieigos režimui.  Reikšmės: None (nėra), ReadOnly (tik skaityti), ReadOnlyUpgradable (tik skaityti / atnaujinamas), ReadWrite (skaityti / rašyti)

- **BlockingUIShown** – Bulio logika, rodanti, ar vartotojo sąsajos blokavimas buvo rodomas sraute.

- **ContentUriAuthority** – turinio URL prieiga iš SAF

- **Correlation** – GUID, skirtas su operacija susietos ID koreliacijai

- **DocId** – dokumento ID, sugeneruotas „AppDocs“

- **DocInstanceId** – DocInstanceId yra dokumento egzemplioriaus ID, sugeneruotas „AppDocs“, aprėpto operacijos egzemplioriaus dokumente

- **DocIsEnterpriseProtected** – Bulio logika, rodanti, ar dokumentas yra apsaugotas.

- **DocUserId** – vartotojo ID iš MS autentifikavimo sluoksnio

- **DocUserIdProvider** – išvardijimas, nurodantis vartotojo ID teikėją, 0 = nežinomas, 1 = „Live ID“, 2 = OrgId, 3 = SSPI; 4 = ADAL

- **DurationInMs** – failo operacijos užbaigimui skirtas laikas milisekundėmis

- **EndReason** – išvardijimo reikšmė, nurodanti užbaigimo priežastį.  Reikšmės: None, Success, Failure, Cancel

- **ErrorCode** – failo operacijos klaidos kodas

- **Extension** – atidaryto failo plėtinio pirmieji keturi simboliai.

- **FileSourceLocation** – failo vietos išvardijimo reikšmė. Galimos reikšmės: None, Local, UncOrMappedNetworkDrive, SkyDrive, App, SharePoint, UnknownServer

- **FILETIME** – įvykio trukmė

- **FirstBCSClientError_Info** – klaidos kodo informacija, susijusi su failų konvertavimais

- **HttpStatusCode** – žiniatinklio tarnybos užklausos HTTP atsako kodas

- **InitalizationReason** – failo atidarymo įvesties vieta

- **K2FileIOHresult** – failo atidarymo operacijos užbaigimo Hresult kodas

- **LastBCSClientError_TagId** – paskutinė BCS (dvejetainė konvertavimo tarnyba) kliento klaida

- **OfficeWebServiceApiStatusFlag** – žiniatinklio tarnybos užklausos būsenos vėliavėlė

- **OpEndEventId** – žymė, nurodanti, kur iš tikrųjų baigėsi operacija

- **OpFlags** – dokumentų operacijos parametrų vėliavėlės, naudojamos „AppDocs“ sluoksnio.

- **OpSeqNum** – skaičius, nurodantis su failo operacija susijusių kvietimų seką „AppDocs“ sluoksnyje

- **OpType** – operacijos tipo išvardijimas. Reikšmės: „None“ (nėra), „CreateDocument“ (sukurti dokumentą), „OpenDocument“ (atidaryti dokumentą), „CopyDocument“ (kopijuoti dokumentą), „CloseDocument“ (uždaryti dokumentą), „SaveDocument“ (įrašyti dokumentą), „OpenVersion“ (atidaryti versiją), „CloseVersion“ (uždaryti versiją)

- **PreFetchState** – naujo failo sukūrimo operacijų išankstinio šablonų paėmimo būsenos išvardijimas.

- **ProviderApp** – taikomosios programos, kurioje atidarytas failas, paketo pavadinimas

- **ScopeInstanceId** – aprėpties egzemplioriaus ID, naudojamas prijungti duomenų kontekstą prie veiklų

- **Size** – failo dydis

- **State** – failo būsenos išvardijimo vertė. Reikšmės: None (nėra), Creating (kuriama), Created (sukurta), CreateFailed (sukurti nepavyko), Opening (atidaroma), Opened (atidarytas), OpenFailed (atidaryti nepavyko), Copying (kopijuojama), Copied (nukopijuota), CopyFailed (nukopijuoti nepavyko), Closing (uždaroma), Closed (uždaryta), CloseFail (uždarymas nepavyko)

- **TemplateName** – dokumento šablono dvejetainis šablono pavadinimas iš šablono tarnybos, pvz., TF10002009.dotx

- **UriScheme** – URL schema

#### <a name="officeandroidauthaceerrors"></a>Office.Android.AuthACEErrors

Šis įvykis naudoja „Microsoft“ paskyrą (MSA), kad nustatytų, kuris vartotojas bando prisijungti prie taikomosios programos, ir kuri tuo metu iš minimų telemetrijų įjungiama kaip nepavykusio bandymo dalis.  

Šis įvykis padeda atlikti MSA prisijungimo klaidų platinimo analizę, kuri padeda suprasti, kodėl MSA prisijungimo srauto užbaigimas yra nesėkmingas.

Renkami šių laukų duomenys:

- **ExceptionsName** – nurodo išimčių klases pagal išimčių žymas, kurios pateikiamos prisijungimo prie „Microsoft“ paskyros srauto metu.

- **ExceptionsTag** – nurodo, kurios srauto išimtys kartu įvyksta MSA prisijungimo sraute.

- **IDCRLACEErrorCode** – pateikia klaidos kodą, atsirandantį MSA prisijungimo srauto metu. Skirtingi klaidų kodai, paminėti %SRCROOT%\identity\coreapi\public\IdentityData.h

- **IDCRLAuthenticationStatusErrorCode** – nurodo „Microsoft“ paskyros (MSA) neteisingos autentifikavimo būsenos klaidų kodus.

- **IDCRLUserInteractionMissingError** – nurodo, ar prisijungimo prie „Microsoft“ paskyros (MSA) srautas buvo iškviestas su showUI žyme kaip klaidingas rezultatas.


#### <a name="officeandroidbcserrors"></a>Office.Android.BCS.Errors

Dvejetainės konvertavimo klaidos telemetrija, skirta funkcijai Spausdinti ir bendrinti kaip PDF.  „Microsoft“ šią funkciją naudoja, BCS konvertavimo „Word“, „Excel“ ar „PowerPoint“ programose trikčių vietoms nustatyti.

Renkami šių laukų duomenys:

- **DocumentFileSize** – failo dydis.

- **FileExtension** – failo plėtinio pirmieji keturi simboliai.

- **IsFileDirty** – Bulio logika, rodanti, ar faile buvo neįrašytų pakeitimų.

- **Location** – failo vietos išvardijimas.  Vertės: „OneDrive“, „SharePoint“, „Dropbox“ ir pan.

- **PDFConversionError** – žymė, ties kuria įvyksta PDF konvertavimo klaida

- **PdfConversionErrorCode** – PDF konvertavimo klaidos kodas

- **PdfConversionHRStatus** – PDF konvertavimo būsenos kodas

- **PdfConversionResult** – PDF konvertavimo rezultatų išvardijimas.  Reikšmės: Success (pavyko), Failed (nepavyko) ir Cancelled (atšaukta)

- **PdfFileSize** – PDF dydis

#### <a name="officeandroidclientsideiap"></a>Office.Android.ClientSideIAP

Duomenų bazės trikties kritinės klaidos telemetrija, kai naršomi failai ir įtraukiamos vietos.„Microsoft“ šią funkciją naudoja DB sugadinimo trikčiai programose, kurios gali trukdyti vartotojams įtraukti vietas arba peržiūrėti juos programose „Word“, „Excel“ ar „PowerPoint“, nustatyti.

Renkami šių laukų duomenys:

- **ClientTransactionId** – GUID perduotas DSC tam tikrai atsiskaitymo užklausai.

- **CollectionTime** – prenumeratos pirkimo užbaigimo laikas

- **CountryCode** – kliento šalies kodas, nusiųstas į DSC kliento atsiskaitymo užklausai

- **GoPremiumEntryPoint** – įvedimo vieta, skirta pirkimui suaktyvinti 

- **IsActivateExistingSubscription** – Bulio logika, rodanti, ar buvo esama prenumerata, kuri buvo aktyvinta

- **IsErrorRetriable** – Bulio logika, rodanti, ar padengimas gali būti kartojamas

- **IsPreviousPurchase** – Bulio logika, rodanti, ar aktyvinimas įvyko ankstesnio prenumeratos įsigijimo metu

- **IsProvisioningTriggeredByRetry** – Bulio logika, rodanti, ar buvo bandoma kartoti

- **LanguageCode** – kliento kalbos kodas, nusiųstas į DSC kliento atsiskaitymo užklausai

- **ProductIdentifier** – bandomo kliento įsigyti SKU pavadinimas

- **ProvisioningHttpStatusCode** – parengimo http būsenos kodas

- **ProvisioningStatusCode** – parengimo būsenos kodas

- **PurchaseOrderId** – pirkimo užsakymo identifikatorius iš „Google“ / „Samsung“ parduotuvės

- **RedemptionTaskHR** – prenumeratos padengimo užduoties HResult

- **SubscriptionProvisioningSucceeded** – Bulio logika, rodanti prenumeratos parengimo pavykimo rezultatą

- **SubscriptionPurchaseHR** – prenumeratos įsigijimo užduoties Hresult

- **SubscriptionType** – prenumeratos tipo arba SKU išvardijimas.

- **TCID** – piktogramos spustelėjimas, suaktyvinantis prenumeratos srautą

#### <a name="officeandroiddbfailurecause"></a>Office.Android.DBFailureCause

Duomenų bazės trikties kritinės klaidos telemetrija, kai naršomi failai ir įtraukiamos vietos.„Microsoft“ šią funkciją naudoja DB sugadinimo trikčiai programose, kurios gali trukdyti vartotojams įtraukti vietas arba peržiūrėti juos programose „Word“, „Excel“ ar „PowerPoint“, nustatyti.

Renkami šių laukų duomenys:

- **ErrorAt** – žymės vertė: informacija apie vietą, kur įvyko klaida

- **ExceptionErrorMessage** – daugiažodis klaidos pranešimas

#### <a name="officeandroidearlytelemetryexpansionfileserrors"></a>Office.Android.EarlyTelemetry.ExpansionFilesErrors

Papildomi „Android Package Kit“ (APK) failai, skirti „Office“ mobiliųjų įrenginių programai, yra pridėtiniai išteklių failai, kuriuos „Android“ programų kūrėjai gali paskelbti kartu su programa. Siekdami padaryti papildomų failų atsisiuntimo mechanizmą patikimesnį, registruojame klaidų, įvykusių atsisiunčiant arba skaitant atsisiųstus papildomus failus, priežastis.

Renkami šių laukų duomenys:

- **Data_ClassName** – tekstas, nurodantis išeitinio kodo failo pavadinimą.

- **Data_ErrorMessage** – tekstas, nurodantis operaciją, kurią vykdant įvyko triktis.

- **Data_ExceptionMessage** – pasirinktinis teksto laukas, nurodantis išimties priežastį.

- **Data_ExceptionType** – pasirinktinis teksto laukas, nurodantis išimties, gautos iš išeitinio kodo, pavadinimą.

- **Data_MethodName** – tekstas, nurodantis išeitinio kodo metodo, kuriame įvyko klaida, pavadinimą.

#### <a name="officeandroidearlytelemetryextractionerror"></a>Office.Android.EarlyTelemetry.ExtractionError

Kad sumažintumėte „Android“ skirtų „Office“ programėlių dydį, glaudiname galutinio paketo resursus. Vykdymo metu pirmiausia išskleidžiame šiuos išteklius ir tik tada naudojame. Kartais išskleidimo metu įvyksta nenumatytų klaidų, dėl kurių programėlė sugenda. 

Šio įvykio metu renkame tam tikrą diagnostinę informaciją, susijusią su išskleidimu, pvz., išskleidžiamo ištekliaus pavadinimą, kelią iki išskleidimo vietos ir t. t., laisvą vietą diske ir pan. Šie duomenys renkami tik tada, kai yra išskleidimo klaidų.

Mes naudojame šiuos duomenis norėdami suprasti išskleidimo triktis ir pagerinti mūsų programėlių naudojimo patirtį.

Renkami šių laukų duomenys:

- **Data_ArchiveName** – išskleidžiamo ištekliaus pavadinimas.

- **Data_ArchivePath** – kelias iki vietos, kurioje laikinai talpinamas išteklius.

- **Data_ArchiveSizeKB** – išskleidžiamo ištekliaus dydis.
 
- **Data_ClassName** – failo pavadinimas ištekliaus kode, kuriame įvyko klaida.

- **Data_ErrorDetail** – tekstas, pateikiantis išsamesnę informaciją apie klaidos priežastį, pvz., klaidos kodą ir t. t.

- **Data_ErrorMessage** – tekstas, aprašantis išskleidimo metu aptiktos klaidos tipą.

- **Data_ExtractionDestinationPath** – kelias iki vietos, kurioje išteklius turi būti įrašytas po išskleidimo.

- **Data_FreeDiskSpaceMB** – diske esančio laisvos disko vietos kiekis, išmatuotas megabaitais. 

- **Data_ItemToExtract** – išskleidžiamo ištekliaus pavadinimas.

- **Data_MethodName** – metodo pavadinimas ištekliaus kode, kuriame įvyko klaida.


#### <a name="officeandroidearlytelemetryregistryerrors"></a>Office.Android.EarlyTelemetry.RegistryErrors

Šis įvykis fiksuoja visas klaidas, kylančias „Android“ registro prieigos metu. Šie įvykio duomenys padeda mums suprasti vartotojo klaidas ir padaryti registro funkciją patikimesnę.

Renkami šių laukų duomenys:

- **App** – programos siuntimo procesas.

- **AppVersionLong** – programos versija.

- **Data_StackTrace** – klaidos rietuvės pėdsakas.

#### <a name="officeandroidearlytelemetrysharedlibraryloadersearchandloadlibraryerror"></a>Office.Android.EarlyTelemetry.SharedLibraryLoadersearchAndloadLibraryError 

Šį įvykį užregistruojame tuo atveju, jei yra klaidų įkeliant bendrinamas bibliotekas. Gali būti bibliotekos įkėlimo klaidų dėl dviejų priežasčių 1) įdiegtas APK nesuderinamas su įrenginiu. 2) biblioteka, kurią bandome įkelti, gali būti sugadinta dėl išskleidimo klaidų, atsiradusių trūkstant vietos arba nepakankant atminties.

Renkami šių laukų duomenys:

- **Data_ExceptionMessage** – išimties pranešimas pateiktas „Android“ API System.loadLibrary

- **Data_FreeSpaceInMB** – laisva vieta įrenginyje

- **Data_nickName** – bibliotekos, kurios nepavyko įkelti, pavadinimas.

#### <a name="officeandroidintuneintunejavacopyfailedattempts"></a>Office.Android.Intune.IntuneJavaCopyFailedAttempts

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms įrašant vietinę „Intune“ apsaugotų debesies dokumentų kopiją.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą

Renkami šių laukų duomenys:

- **Data_FileCreationFailedErrorCode** – klaidos kodas, susietas su srautu

#### <a name="officeandroidintuneintunejavaexceptionadaltokenformam"></a>Office.Android.Intune.IntuneJavaExceptionADALTokenForMAM

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms ADAL atpažinimo ženklo gavimo „Intune“ resursams metu.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu, po prisijungimo prie programos naudojant darbo paskyrą

Renkami šių laukų duomenys:

- **Data_ErrorCode** – klaidos kodas, susietas su srautu

#### <a name="officeandroidintuneintunejavaexceptionapppolicy"></a>Office.Android.Intune.IntuneJavaExceptionAppPolicy

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms iškviečiant „Intune“ API, susietas su gaunamomis strategijomis, identifikuojančiomis esamą procesą.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą

Renkami šių laukų duomenys:
 
- Nėra

#### <a name="officeandroidintuneintunejavaexceptionapppolicyforcontext"></a>Office.Android.Intune.IntuneJavaExceptionAppPolicyForContext

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms iškviečiant „Intune“ API, susietas su gaunamomis strategijomis, identifikuojančiomis esamą veiklą.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą

Renkami šių laukų duomenys:
 
- Nėra

#### <a name="officeandroidintuneintunejavaexceptionauthenticationcallback"></a>Office.Android.Intune.IntuneJavaExceptionAuthenticationCallback

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms iškviečiant „Intune“ API, susietas su autentifikavimo atgalinių iškvietimų registravimu valdomoms paskyroms.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą

Renkami šių laukų duomenys:

- Nėra

#### <a name="officeandroidintuneintunejavaexceptiongetaccountstatesync"></a>Office.Android.Intune.IntuneJavaExceptionGetAccountStateSync

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms iškviečiant „Intune“ API, susietas su valdomomis paskyromis.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą

Renkami šių laukų duomenys:
 
- Nėra

#### <a name="officeandroidintuneintunejavaexceptiongetissavetolocationallowed"></a>Office.Android.Intune.IntuneJavaExceptionGetIsSaveToLocationAllowed

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms iškviečiant strategiją, susietą su įrašymu į vietinę vietą.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą

Renkami šių laukų duomenys:

- Nėra

#### <a name="officeandroidintuneintunejavaexceptiongetpolicyforidentity"></a>Office.Android.Intune.IntuneJavaExceptionGetPolicyForIdentity

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms iškviečiant „Intune“ API, susietas su gaunamomis tapatybės strategijomis.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą

Renkami šių laukų duomenys:

- Nėra

#### <a name="officeandroidintuneintunejavaexceptiongetprotectioninfofromdescriptor"></a>Office.Android.Intune.IntuneJavaExceptionGetProtectionInfoFromDescriptor

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms iškviečiant „Intune“ API, susietas su apsaugos informacija.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą

Renkami šių laukų duomenys:
  
- Nėra

#### <a name="officeandroidintuneintunejavaexceptiongetprotectioninfofrompath"></a>Office.Android.Intune.IntuneJavaExceptionGetProtectionInfoFromPath

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms iškviečiant „Intune“ API, susietas su apsaugos informacija.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą

Renkami šių laukų duomenys:

- Nėra

#### <a name="officeandroidintuneintunejavaexceptiongetuipolicyidentity"></a>Office.Android.Intune.IntuneJavaExceptionGetUIPolicyIdentity

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms iškviečiant „Intune“ API, susietas su gaunamomis naudotojo sąsajos strategijomis, skirtomis valdomai paskyrai.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą

Renkami šių laukų duomenys:

- Nėra

#### <a name="officeandroidintuneintunejavaexceptionisidentitymanaged"></a>Office.Android.Intune.IntuneJavaExceptionIsIdentityManaged

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms iškviečiant „Intune“ API, susietas su identifikavimu, jei paskyra yra valdoma.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą.

Renkami šių laukų duomenys:

- Nėra

#### <a name="officeandroidintuneintunejavaexceptionnullenrollmentmanager"></a>Office.Android.Intune.IntuneJavaExceptionNullEnrollmentManager

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms iškviečiant „Intune“ API, susietas su komponentų registravimu atgaliniam iškvietimui.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą

Renkami šių laukų duomenys:

- Nėra

#### <a name="officeandroidintuneintunejavaexceptionprotect"></a>Office.Android.Intune.IntuneJavaExceptionProtect

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms iškviečiant „Intune“ API, susietas su valdomo dokumento apsauga.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą.

Renkami šių laukų duomenys:

- Nėra

#### <a name="officeandroidintuneintunejavaexceptionprotectfromdescriptorifrequired"></a>Office.Android.Intune.IntuneJavaExceptionProtectFromDescriptorIfRequired

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms iškviečiant „Intune“ API, susietas su valdomo dokumento apsauga.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą

Renkami šių laukų duomenys:

- Nėra

#### <a name="officeandroidintuneintunejavaexceptionregisteraccountsync"></a>Office.Android.Intune.IntuneJavaExceptionRegisterAccountSync

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms iškviečiant „Intune“ API, susietas su „Intune“ valdymo paskyros registravimu.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą

Renkami šių laukų duomenys:

- Nėra

#### <a name="officeandroidintuneintunejavaexceptionsetuipolicyidentitysync"></a>Office.Android.Intune.IntuneJavaExceptionSetUIPolicyIdentitySync

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms iškviečiant „Intune“ API, susietas su strategijų valdomai paskyrai nustatymu.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą

Renkami šių laukų duomenys:

- Nėra

#### <a name="officeandroidintuneintunejavaexceptionunregisteraccountsync"></a>Office.Android.Intune.IntuneJavaExceptionUnregisterAccountSync

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms iškviečiant „Intune“ API, susietas su „Intune“ valdymo nuotolinio ištrynimo scenarijais.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą

Renkami šių laukų duomenys:

- Nėra

#### <a name="officeandroidintuneintunejavaexceptionupdatetoken"></a>Office.Android.Intune.IntuneJavaExceptionUpdateToken

Kritinės klaidos telemetrija, skirta atskiroms „Intune“ API triktims stebėti; ši telemetrija užregistruojama įvykus klaidoms iškviečiant „Intune“ API, susietas su valdomos paskyros autorizavimo atpažinimo ženklo naujinimu.  „Microsoft“ naudoja šiuos duomenis, kad nustatytų klaidas „Intune“ taikomojoje programoje registracijos metu ir ją baigus, po prisijungimo prie programos naudojant darbo paskyrą

Renkami šių laukų duomenys:

- Nėra

#### <a name="officeandroidlicenseactivationfailure"></a>Office.Android.LicenseActivationFailure

Kritinės klaidos telemetrija, skirta sekti triktis aktyvinant „Office 365“ paskyrų licencijas „W/X/P“ programose.  „Microsoft“ šią funkciją naudoja įsigytos „Office 365“ licencijos aktyvinimo trikčiai išanalizuoti.

Renkami šių laukų duomenys:

- **EntryPoint** – įėjimo taško, įjungiančio licencijos aktyvinimo srautą, išvardijimas

- **HResult** – trikties klaidos kodas

- **IsGallatin** – Bulio logika, tikrinanti, ar tai yra „Gallatin“ paskyra

- **MessageCode** – išvardijimas, nurodantis aktyvinimo trikties vietą

- **PreviousEntryPoint** – įėjimo taško, įjungiančio licencijos aktyvinimo srautą, išvardijimas

- **StateAfterActivation** – išvardijimas, nurodantis taikomosios programos licencijavimo būseną prieš pradedant aktyvinimo srautą

- **StateBeforeActivation** – išvardijimas, nurodantis taikomosios programos licencijavimo būseną prieš pradedant aktyvinimo srautą

- **UserAccountType** – išvardijimas, nurodantis, ar tai asmeninė paskyra, ar įmonės paskyra.

#### <a name="officeandroidmsasigninuiprompts"></a>Office.Android.MSASignInUIPrompts

Šis įvykis nurodo, kad prisijungimo raginimas buvo pateiktas vartotojui, asmeninei paskyrai.  Šis įvykis padeda suprasti prisijungimo prie mūsų taikomųjų programų būsenos sveikatą ir imtis reikiamų veiksmų, kai pastebime netikėtus prisijungimo raginimus. 

Renkami šių laukų duomenys:

- **ExternalCacheRefreshError** – atpažinimo ženklo atnaujinimo bandymo klaidos kodas prieš parodant prisijungimo raginimą.

- **LastLoginDelta** – laiko pokytis nuo paskutinio sėkmingo prisijungimo.

- **MSAserverUAID** – koreliacijos ID su tarnybos telemetrijos duomenimis.

- **PreviousIdentityState** – nurodo paskyros būseną, pvz., baigėsi seansas. 

- **SignInResultCode** – nurodo raginimo prisijungti baigimo rezultato kodą.

- **UseCache** – nurodo, ar mes primygtinai raginome vartotoją dar kartą pateikti slaptažodį.

- **UserType** – nurodo, ar tai yra egzistuojanti paskyra, ar nauja paskyra

- **WasIdentitySignedOut** – nurodo, ar paskyra buvo atsijungimo būsenoje.


#### <a name="officeapplelicensingmacdractivationfailures"></a>Office.Apple.Licensing.Mac.DRActivationFailures

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis naudojamas užfiksuoti „Digital River“ aktyvinimo nesėkmes (įvykis registruoja raktą ir produktą, kuris buvo naudojamas aktyvinimui, taip pat gautą klaidos kodą).  Šis įvykis naudojamas nustatant ir padedant šalinti aktyvinimo triktis („Digital River“ problemos).

Renkami šių laukų duomenys:

- **Data_DigitalRiverID** – „Digital River“ produkto ID, siejantis su šia „Office“ produkto partnerių programa SKY

- **Data_Error** – eilutė, nurodanti aktyvinimo klaidos kodą.

- **Data_ProductKey** – produkto kodas, kurį buvo bandoma suaktyvinti

- **Data_ProductKeyHash** – aktyvintas užkoduotas produkto kodas

#### <a name="officeapplelicensingmacgetmachinestatuserrors"></a>Office.Apple.Licensing.Mac.GetMachineStatusErrors

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis surenka pateiktą klaidos kodą, bei periodiškai tikrina prenumeratos licencijos galiojimą. Klaidos kodas gali reikšti serverio nepasiekiamumą, bet taip pat licencijos galiojimo laiko pasibaigimą, kompiuterių skaičiaus limitą, neteisingą aparatūros ID ir t. t. Šis įvykis naudojamas stebėti „Office“ licencijavimo tarnybos sveikatą, bei tirti įvykius, susijusius su kompiuterio prenumeratos valdymu.

Renkami šių laukų duomenys:

- **Data_Error** – renkame duomenis eilutės, atvaizduojančios klaidos kodą.

#### <a name="officeextensibilitysandboxodperrornotification"></a>Office.Extensibility.Sandbox.ODPErrorNotification

Seka įvairius iš smėlio dėžės gautus klaidų pranešimus. Naudojamas siekiant aptikti klaidų scenarijus smėlio dėžėje ir juos ištaisyti, taip siekiant pagerinti vartotojo produktyvumą
 
Renkami šių laukų duomenys:

- **AppId** – taikomosios programos ID

- **AppUrl** – perkeltos taikomosios programos URL 

- **Result** – rezultatų klaidos kodas

#### <a name="officefirstrunapplemaconiolkfirstrunstarted"></a>Office.FirstRun.Apple.MacONIOLKFirstRunStarted

Šis įvykis gaunamas „Office“ programoms, veikiančioms „Apple“ platformose. Įvykis leidžia mums žinoti, kad vartotojas paleido pirmojo sistemos paleidimo programą. Šį įvykį naudojame norėdami išsiaiškinti, ar pirmojo sistemos paleidimo programa (FRE) sėkmingai paleista.

Renkami šių laukų duomenys:

- **Data_FirstRunCollectionTime** – laiko žyma, skirta srauto pradėjimo laikui registruoti.

#### <a name="officegraphicsarcexceptions"></a>Office.Graphics.ARCExceptions 

Ši išimties ataskaitų teikimo informacija yra svarbi vertinant bendrą grafikos rietuvės sveikatą, taip pat nustatant kodo dalis, kuriose dažniai pasitaiko gedimų, siekiant nustatyti tyrimo prioritetą. Ši išimties ataskaitų teikimo informacija yra svarbi vertinant bendrą grafikos rietuvės sveikatą, taip pat nustatant kodo dalis, kuriose dažniai pasitaiko gedimų. Tai padeda inžinieriui nustatyti, kurios generavimo problemos turi įtakos daugeliui vartotojų, leidžia mums nustatyti mūsų prioritetą sprendžiant problemas, kurios aktualios didžiausiam vartotojų skaičiui.

Renkami šių laukų duomenys:

  - **Data\_HResult** – Trikties pateiktas klaidos kodas

  - **Data\_TagCount** – Visų įvykusių klaidų skaičius

  - **Data\_TagID** – Įvykusios klaidos identifikatorius


#### <a name="officeofficemobilepersonalizedcampaigningerrors"></a>Office.OfficeMobile.PersonalizedCampaigning.Errors

Norint geriau informuoti vartotojus apie jų dar neištyrinėtas „Office Mobile“ funkcijas, „Office Mobile“ integruojama su IRIS, siekiant palaikyti pranešimus programoje bei „push“ pranešimus. Pranešimų programoje atveju fiksuojamos klaidos, kurios įvyksta gaunant arba rodant pranešimą ir vartotojui sąveikaujant su pranešimu bei teikiant atsiliepimus į IRIS serverį. „Push“ pranešimų atveju fiksuojamos klaidos, kurios įvyksta rodant pranešimą ir kai vartotojas sąveikauja su pranešimu.

Renkami šių laukų duomenys:

- **Dalykas** – dalyko, kurio metu įvyko klaida, pavadinimas

- **CreativeId** – pranešimo ID, unikaliai identifikuojantis pranešimą ir jo turinį.

- **ErrorDetails** – išsami informacija apie klaidą

- **ErrorMessage** – klaidos pranešimas.

- **ErrorReason** – esama klaidos priežastis

- **Metodas** – funkcijos, kurioje įvyko klaida, pavadinimas.

- **RequestParams** – užklausos parametrai, naudoti jungiantis prie IRIS serverio, siekiant gauti pranešimą.

- **SurfaceId** – srities, kurioje bus rodomas pranešimas, ID.


#### <a name="officeoutlookdesktopcalendaracceptcalsharenavigatetosharedfoldererror"></a>Office.Outlook.Desktop.Calendar.AcceptCalShareNavigateToSharedFolder.Error

Renka informaciją, kada įvyksta klaida, kai pereinama prie bendrinamo kalendoriaus. Šie duomenys naudojami stebint kalendoriaus bendrinimo API ir „Outlook“ sąveikos su bendrinamais kalendoriais būklę.

Renkami šių laukų duomenys:

  - **FailedCaseHResult** – Trikties pateiktas klaidos kodas

#### <a name="officeoutlookdesktopedpedpopenstorefailure"></a>Office.Outlook.Desktop.EDP.EDPOpenStoreFailure

Sėkmingas ar nesėkmingas bandymas atidaryti pašto saugyklą, apsaugotą naudojant įmonės duomenų apsaugą, pagrįstą „Windows API“ iškvietimo rezultatu, kad gautų saugyklos iššifravimo kodą. Mes naudojame tai norėdami diagnozuoti vieną iš dažniausiai pasitaikančių įmonės duomenų apsaugos problemų, kurios gali užkirsti kelią „Outlook“ paleidimui. Pagrindinė trikties priežastis yra „Outlook“ sąveika su „Windows API“, naudojamomis saugyklos kodui iššifruoti.

Renkami šių laukų duomenys:

  - **HVA Activity** **-** su pasirinktiniais duomenų laukais

  - **IsFlightOn** – Nurodo, ar įjungtas EDPDecryption testuojamas variantas

#### <a name="officeoutlookdesktopndbcorruptionresult"></a>Office.Outlook.Desktop.NdbCorruptionResult

Office.Outlook.Desktop.NdbCorruptionResult ir Office.Outlook.Desktop.NDBCorruptStore.Warning renkami, kai aptinkame pažeidimą vartotojo PST/OST. Kai aptinkame pažeidimą, „Microsoft“ renka duomenų bazės formatą, vietą, kurioje pažeidimas aptikta, ir nedidelį kontekstą apie korupciją. OST/PST pažeidimas neleidžia vartotojams pasiekti savo el. laiškų. Mes aktyviai stebime šiuos neįprastos veiklos duomenis. Mes siekiame nustatyti ir apriboti klientų duomenų praradimo problemas.

Renkami šių laukų duomenys:

  - **0 -** Proceso pavadinimas, kuriame yra pažeidimas

  - **1 -** Bulio logika nurodo, ar vartotojas pasirinko naują failą

  - **2 -** Kitų procesų, kuriems vykstant duomenų bazė atidaryta, skaičius

#### <a name="officeoutlookdesktopndbcorruptstorewarning"></a>Office.Outlook.Desktop.NDBCorruptStore.Warning

Office.Outlook.Desktop.NdbCorruptionResult ir Office.Outlook.Desktop.NDBCorruptStore.Warning renkami, kai aptinkame pažeidimą vartotojo PST/OST. Kai aptinkame pažeidimą, „Microsoft“ renka duomenų bazės formatą, vietą, kurioje pažeidimas aptikta, ir nedidelį kontekstą apie korupciją. OST/PST pažeidimas neleidžia vartotojams pasiekti savo el. laiškų. Mes aktyviai stebime šiuos neįprastos veiklos duomenis. Mes siekiame nustatyti ir apriboti klientų duomenų praradimo problemas.

Renkami šių laukų duomenys:

  - **CollectionTime** – Rinkimo laikas

  - **Context** – Pažeistos saugyklos kontekstas, kuriame aptiktas pažeidimas

  - **CreatedWithVersion** – (pasirinktinis) laukas su saugyklos versija

  - **Details** – Išsami informacija apie gedimą

  - **NdbType** – Parduotuvės tipas, gali būti 0 = NdbUndefined, 1 = NdbSmall, 2 = NdbLarge, 3 = NdbTardis

  - **ProcessName** – proceso pavadinimas, dėl kurio parduotuvė gali būti pažeista

  - **PstVersion** – MSPST32.DLL versija

  - **Version** – Parduotuvės failo formato versija

#### <a name="officeoutlookdesktopoutlookcalendarusageerrmeetrcptforwardactionsruleo16"></a>Office.Outlook.Desktop.OutlookCalendarUsageErr.MeetRcpt.ForwardActions.Rule.O16

Renka sėkmingus ir nesėkmingus funkcijų Persiųsti, Persiųsti kaip priedą ir Persiųsti kaip „iCalendar“ veiksmus, skirtus vienam, pasikartojančiam ir išskirtinio susitikimo atsakymui pašte, kalendoriuje ir „Inspector Outlook“ rodinyje. Funkcijų Persiųsti, Persiųsti kaip priedą ir Persiųsti kaip „iCalendar“ veiksmus nepavykusių atvejų rodiklis aktyviai stebimas, ar nėra sutrikimų. Neįprasti statistikos duomenys rodo, kad „Outlook“ nesugeba atlikti pagrindinių kalendoriaus operacijų. Šie duomenys taip pat naudojami kitoms su kalendoriumi susijusioms problemoms nustatyti.

Renkami šių laukų duomenys:

  - **CountExceptionForward** – persiųstų susitikimų išimčių skaičius

  - **CountExceptionForwardAsiCal** – kaip „iCal“ persiųstų susitikimų išimčių skaičius

  - **CountExceptionForwardInSplit** – iš išskaidyto juostelės meniu persiųstų susitikimų išimčių skaičius

  - **CountExceptionForwardWithAttach** – kaip priedas persiųstų susitikimų išimčių skaičius

  - **CountRecurringForward** – persiųstų pasikartojančių susitikimų skaičius

  - **CountRecurringForwardAsiCal** – kaip „iCal“ persiųstų pasikartojančių susitikimų skaičius

  - **CountRecurringForwardInSplit** – iš išskaidyto juostelės meniu persiųstų pasikartojančių susitikimų skaičius

  - **CountRecurringForwardWithAttach** – kaip priedas persiųstų pasikartojančių susitikimų skaičius

  - **CountSingleForward** – persiųstų atskirų susitikimų skaičius

  - **CountSingleForwardAsiCal** – kaip „iCal“ persiųstų atskirų susitikimų skaičius

  - **CountSingleForwardInSplit** – iš išskaidyto juostelės meniu persiųstų atskirų susitikimų skaičius

  - **CountSingleForwardWithAttach** – kaip priedas persiųstų atskirų susitikimų skaičius

  - **HResult** – klaidos kodas

  - **OlkViewName** – nurodo pašto, kalendoriaus ar inspektorius rodinį

#### <a name="officeoutlookdesktopoutlookcalendarusageerrmeetrcptreplyactionsruleo16"></a>Office.Outlook.Desktop.OutlookCalendarUsageErr.MeetRcpt.ReplyActions.Rule.O16

Renka sėkmingus ir nesėkmingus funkcijų Atsakyti, Atsakyti visiems, Atsakyti IM ir Atsakyti visiems IM atvejus, skirtus vienam, pasikartojančiam ir išskirtinio susitikimo atsakymui pašte, kalendoriuje ir „Inspector Outlook“ rodinyje. Funkcijų Atsakyti, Atsakyti visiems, Atsakyti IM ir Atsakyti visiems IM nepavykusių atvejų rodiklis aktyviai stebimas, ar nėra sutrikimų. Neįprasti statistikos duomenys rodo, kad „Outlook“ nesugeba atlikti pagrindinių kalendoriaus operacijų. Šie duomenys taip pat naudojami kitoms su kalendoriumi susijusioms problemoms nustatyti.

Renkami šių laukų duomenys:

  - **CountExceptionReply** – susitikimų atsakymų dėl išimčių skaičius

  - **CountExceptionReplyAll** – susitikimų atsakymų Atsakyti visiems dėl išimčių skaičius

  - **CountExceptionReplyAllWithIM** – susitikimų atsakymų Atsakyti visiems IM skaičius

  - **CountExceptionReplyWithIM** – susitikimų atsakymų Atsakyti IM skaičius

  - **CountRecurringReply** – pasikartojančių susitikimų atsakymų skaičius

  - **CountRecurringReplyAll** – pasikartojančių susitikimų atsakymų Atsakyti visiems skaičius

  - **CountRecurringReplyAllWithIM** – pasikartojančių susitikimų atsakymų Atsakyti visiems IM skaičius

  - **CountRecurringReplyWithIM** – pasikartojančių susitikimų atsakymų Atsakyti IM skaičius

  - **CountSingleReply** – atskirų susitikimų atsakymų skaičius

  - **CountSingleReplyAll** – atskirų susitikimų atsakymų Atsakyti visiems skaičius

  - **CountSingleReplyAllWithIM** – atskirų susitikimų atsakymų Atsakyti visiems IM skaičius

  - **CountSingleReplyWithIM** – atskirų susitikimų atsakymų Atsakyti IM skaičius

  - **HResult** – klaidos kodas

  - **OlkViewName** – nurodo pašto, kalendoriaus ar inspektorius rodinį

#### <a name="officeoutlookdesktopoutlookprivsdlgsingleuserloadfail"></a>Office.Outlook.Desktop.OutlookPrivsDlgSingleUser.LoadFail

Ši taisyklė renka kalendoriaus bendrinimo klaidas įtraukiant naują vartotoją (EX arba SMTP tipo) iš adresų knygelės. Šie duomenys naudojami diagnozuoti ir išspręsti problemas, aptiktas dialogo lange Kalendoriaus bendrinimas

Renkami šių laukų duomenys:

  - **CountAccountWizardEnd** – Kiek kartų baigėsi pasenęs vediklio dialogo langas

  - **CountCreatePIMAccount** – Kiek kartų vartotojas sukūrė PIM profilį

#### <a name="officeoutlookmacmacolkasserts"></a>Office.Outlook.Mac.MacOLKAsserts

Naudojamas identifikuoti vartotojams įtakos turinčias „Outlook“ problemas, galinčias pasireikšti gedimais ar pablogėjusiu veikimu. 

Renkami šių laukų duomenys:

- **Category** – pasireiškimo tipas

- **CollectionTime** – pasireiškimo gavimo laikas


#### <a name="officeoutlookmacmacolkerrors"></a>Office.Outlook.Mac.MacOLKErrors

Naudojamas identifikuoti vartotojams įtakos turinčias „Outlook“ problemas, galinčias pasireikšti gedimais ar pablogėjusiu veikimu. 

Renkami šių laukų duomenys:

- **Category** – klaidos tipas

- **CollectionTime** – klaidos gavimo laikas

- **ThreadId** – gijos identifikatorius


#### <a name="officesystemsystemhealthasserts"></a>Office.System.SystemHealthAsserts

Šio įvykio nurodytos klaidos padeda suprasti, kada blogėja klientų patirtis. Daugelis šių „ShipAsserts“ veda yra gedimų priežastis ir ši informacija leidžia daugelį jų išspręsti. Renka produkto, kuris padeda nustatyti klaidas, „ShipAsserts“.

Renkami šių laukų duomenys:

 - **Count** – kiekvieno pasireiškimo, apie kurį pranešta, skaičius

  - **EndTime** – Laikas, kai užfiksuotas paskutinis pasireiškimas, apie kurį pranešta

  - **ErrorGroup** – Kiekvieno pasireiškimo identifikatoriaus spragos

  - **FirstTimeStamp** – Pirmas kartas, kai įvyko pasireiškimas

  - **Trackback** – Konkretaus pasireiškimo unikalus identifikatorius

#### <a name="officesystemsystemhealtherrorsetwshim"></a>Office.System.SystemHealthErrorsEtwShim

Naudojamas nustatyti klientams, kurie daro įtaką problemų atsiradimui, kai veikia programa, kuri gali pasireikšti kaip gedimai ar blogėjančios funkcijos. Įrašo klaidas, įvykstančias proceso vykdymo metu.

Renkami šių laukų duomenys:

  - **EndTime** – Laikas, kai užfiksuotas paskutinis pasieiškimas, apie kurį pranešta

  - **Trackback** – Konkrečios klaidos unikalus identifikatorius

  - **ErrorGroup** – Kiekvienos klaidos spragų identifikatorius

  - **Count** – Visų klaidų skaičius

  - **FirstTimeStamp** – Pirmas kartas, kai įvyko klaida

#### <a name="officesystemsystemhealtherrorsulsandasserts"></a>Office.System.SystemHealthErrorsUlsAndAsserts

Naudojamas nustatyti klientams, kurie daro įtaką problemų atsiradimui, kai veikia programa, kuri gali pasireikšti kaip gedimai ar blogėjančios funkcijos. Įrašo klaidas, įvykstančias proceso vykdymo metu.

Renkami šių laukų duomenys:

  - **EndTime** – Laikas, kai užfiksuotas paskutinis pasieiškimas, apie kurį pranešta

  - **Trackback** – Konkrečios klaidos unikalus identifikatorius

  - **ErrorGroup** – Kiekvienos klaidos spragų identifikatorius

  - **Count** – Visų klaidų skaičius

  - **FirstTimeStamp** – Pirmas kartas, kai įvyko klaida

#### <a name="officesystemsystemhealtherrorsulsworkaround"></a>Office.System.SystemHealthErrorsUlsWorkaround

Naudojamas nustatyti klientams, kurie daro įtaką problemų atsiradimui, kai veikia programa, kuri gali pasireikšti kaip gedimai ar blogėjančios funkcijos. Įrašo klaidas, įvykstančias proceso vykdymo metu.

Renkami šių laukų duomenys:

  - **EndTime** – Laikas, kai užfiksuotas paskutinis pasieiškimas, apie kurį pranešta

  - **Trackback** – Konkrečios klaidos unikalus identifikatorius

  - **ErrorGroup** – Kiekvienos klaidos spragų identifikatorius

  - **Count** – Visų klaidų skaičius

#### <a name="officesystemsystemhealtherrorswithouttag"></a>Office.System.SystemHealthErrorsWithoutTag

Naudojamas nustatyti klientams, kurie daro įtaką problemų atsiradimui, kai veikia programa, kuri gali pasireikšti kaip gedimai ar blogėjančios funkcijos. Įrašo klaidas, įvykstančias proceso vykdymo metu.

Renkami šių laukų duomenys:

Skaičiavimas – kiekvienos klaidos skaičius

  - **EndTime** – Laikas, kai užfiksuotas paskutinis pasireiškimas, apie kurį pranešta

  - **ErrorCode** – Klaidos identifikatorius

  - **ErrorGroup** – Kiekvienos klaidos spragų identifikatorius

  - **ErrorId** – Klaidos identifikatorius

  - **FirstTimeStamp** – Pirmas kartas, kai įvyko klaida

  - **Trackback** – Konkrečios klaidos unikalus identifikatorius

#### <a name="officesystemsystemhealtherrorswithtag"></a>Office.System.SystemHealthErrorsWithTag

Naudojamas nustatyti klientams, kurie daro įtaką problemų atsiradimui, kai veikia programa, kuri gali pasireikšti kaip gedimai ar blogėjančios funkcijos. Įrašo klaidas, įvykstančias proceso vykdymo metu.

Renkami šių laukų duomenys:

  - **Count** – Visų klaidų skaičius

  - **EndTime** – Laikas, kai užfiksuotas paskutinis pasireiškimas, apie kurį pranešta

  - **ErrorCode** – Klaidos identifikatorius

  - **ErrorGroup** – Kiekvienos klaidos spragų identifikatorius

  - **ErrorId** – Klaidos identifikatorius

  - **FirstTimeStamp** – Pirmas kartas, kai įvyko klaida

  - **Trackback** – Konkrečios klaidos unikalus identifikatorius

#### <a name="renewidentityfailure"></a>RenewIdentityFailure

Renkama, kai vartotojas bando atidaryti IRM apsaugotą dokumentą ar taikyti IRM apsaugas. Joje yra informacija, reikalinga tinkamai nustatyti ir diagnozuoti problemas, įvykusias kai nepavyko atnaujinti vartotojo sertifikatų.

Renkami šių laukų duomenys:

- **AppInfo.ClientHierarchy** – kliento hierarchija, kuri nurodo programos paleidimus gamybos aplinkoje arba kūrėjo aplinkoje

- **AppInfo.Name** – programos pavadinimas.

- **AppInfo.Version** – programos versija

- **Failure.Category** – klaidos UnhandledError kategorija

- **Failure.Detail** – klaidos išsami informacija

- **Failure.Id** – klaidos ID

- **Failure.Signature** klaidos parašas, kuris yra toks pats, kaip įvykio pavadinimas

- **iKey** – registravimo tarnybos serverio ID

- **RMS.HRESULT** – vartotojo sertifikato atnaujinimo rezultatas

- **RMS.ScenarioId** – scenarijaus ID, kurį apibrėžia teisių valdymo tarnybos klientas

- **RMS.SDKVersion** – teisių valdymo tarnybos kliento versija

#### <a name="saveerror"></a>save.error

Leidžia nustatyti ir pataisyti situacijas, kai mėginant įrašyti failą įvyko klaida.  Seka klaidas, įvykstančias dėl gedimų įrašant failą, įskaitant aprašomąjį klaidos pranešimą, kuris padės išspręsti problemą.

Renkami šių laukų duomenys: 

- **error** – klaidos, kuri įvyko siekiant aptikti ir išspręsti su tam tikru klaidos tipu susijusias problemas, tipas

- **file_type** – vartotojo bandyto įrašyti failo tipas (pvz.,. doc)

- **origin** – iš kur buvo bandoma įrašyti failą (pvz., iš el. laiško), kad galėtume aptikti problemą, susijusią su failo įrašymu iš tam tikros programos vietos

- **token_type** – atpažinimo ženklo tipas, naudojamas autentifikuoti paskyrą, kad būtų galima įrašyti failą, kad galėtume nustatyti autentifikavimo problemas, susijusias su failo įrašymais

#### <a name="wkwebviewerror"></a>wkwebview.error

Šis įvykis leidžia mums aptikti, kada rašant ar skaitant el. laiškus atsiranda žiniatinklio rodinio klaidų, kad galėtume išvengti problemų, dėl kurių programa negalėtų rašyti arba skaityti el. laiškus. 

Renkami šių laukų duomenys: 

- **description** - klaidos aprašymas

- **error_code** – „WKError“ klaidos kodas

- **function_name** – „JavaScript“ funkcijos pavadinimas, kai klaida

- **js_exception_column_number** – stulpelio numeris, kur įvyko „JavaScript“ išimtis 

- **js_exception_line_number** – eilutės numeris, kur įvyko „JavaScript“ išimtis

- **js_exception_message** – išimties pranešimas, kai įvyko „JavaScript“ išimtis

- **js_exception_source_url** – šaltinio URL, kur įvyko „JavaScript“ išimtis  

- **scenario** - kur įvyko klaida. Tai yra išvardijimas. Galimos reikšmės yra old_renderer, react_renderer ir komponavimas.

#### <a name="wkwebviewterminate"></a>wkwebview.terminate

Šis įvykis leidžia nustatyti, kada sistema nutraukia žiniatinklio rodinį. Šie duomenys leidžia mums stebėti vartotojo klaidą, su kuria susidūrė rašant ar skaitant el. laišką. 

Renkami šių laukų duomenys: 

- **is_foreground** – ar programa yra priekiniame plane, kai įvyksta šis įvykis.

- **Scenario** – kur įvyko klaida atvaizdavimo arba komponavimo metu.


## <a name="device-connectivity-and-configuration-data-events"></a>Įrenginių jungiamumo ir konfigūracijos duomenų įvykiai

Toliau pateikiami šios kategorijos duomenų potipiai:

- [Įrenginių jungiamumas ir konfigūracija](#device-connectivity-and-configuration-subtype)


### <a name="device-connectivity-and-configuration-subtype"></a>*Įrenginių jungiamumo ir konfigūracijos potipis*

Tinklo ryšio būsena ir įrenginio parametrai, tokie kaip atmintis.

#### <a name="applicationdidreceivememorywarning"></a>application.did.receive.memory.warning

Šis įvykis siunčiamas, kai „Apple“ nurodo mums, kad programai trūksta atminties. Nurodo, kad kilo problemų su įrenginio atminties valdymu.

Renkami šių laukų duomenys: 

- **current_memory_used** – nurodo, kiek atminties naudoja programa tada, kai jai pritrūko atminties.

- **current_memory_used_percentage** – nurodo, kokią atminties procentinę dalį naudoja programa iš visos atminties tuo metu, kai programai pritrūko atminties.

- **currentVC** – nurodo rodinį, kuris naudojamas tuo metu, kai programai pritrūko atminties.

- **has_hx** – nurodo, kad paskyra naudoja mūsų naują sinchronizavimo tarnybą, kad būtų galima aptikti sinchronizavimo tarnybos sukeltas problemas

- **is_watch_app_installed** – nurodo, ar vartotojas šiuo metu naudoja „Apple Watch“ ir ar ji įdiegta, kad būtų galima suprasti neigiamą įtaką dėl „Watch“.

- **is_watch_paired** – nurodo, ar vartotojas šiuo metu naudoja „Apple Watch“ ir ar ji susieta su įrenginiu, kad būtų galima suprasti neigiamą įtaką dėl „Watch“

- **is_watch_supported_and_active** – nurodo, ar vartotojas šiuo metu naudoja „Apple Watch“ ir ar ji aktyvi, kad būtų galima suprasti neigiamą įtaką dėl „Watch“.

- **rn_initialized** – nurodo, ar tuo metu, kai programai pritrūko atminties, buvo inicijuota „React Native“.

- **running_time** – nurodo laiką, kurį programa praleido veikdama, kai jai pritrūko atminties.

#### <a name="conversationmemoryleak"></a>conversation.memory.leak

Leidžia aptikti situacijas, kai mūsų el. pašto pokalbių rodinys verčia naudoti daugiau atminties jūsų įrenginyje, negu numatyta.

Renkami šių laukų duomenys:

- Nerenkami jokie laukai ar įtraukti duomenys. Renkami tik žurnalai, jei yra atminties nutekėjimas, susijęs su pokalbio gija.

#### <a name="coredatacorruption"></a>core.data.corruption

Leidžia aptikti situacijas, kai negalime rodyti el. pašto ar kalendoriaus, nes sugadinta vieta, kurioje saugome jūsų el. paštą jūsų įrenginyje.

Renkami šių laukų duomenys:

- **errorSource** – nurodo, ar gauta iš įrašymo ar sukūrimo veiksmo

- **sqlError** – skaitinis klaidos kodas, nurodytas https://www.sqlite.org/c3ref/c_abort.html

#### <a name="coredatacorruptionuserreset"></a>core.data.corruption.user.reset

Leidžia mums aptikti situacijas, kai panaikinote arba iš naujo nustatėte savo paskyrą mūsų programoje ir tai sukėlė įrenginyje saugomų el. pašto duomenų gedimą.

Renkami šių laukų duomenys:

- **errorSource** – nurodo, kur įvyko gedimas įrašant ar kuriant

#### <a name="coredatadiagnostics"></a>core.data.diagnostics 

Leidžia nustatyti ir pataisyti situacijas, kai el. pašto saugykla naudoja per daug įrenginio saugyklos vietos.

Renkami šių laukų duomenys:

- **db_size_megabytes** – seka pagrindinės duomenų bazės dydį, suapvalintą iki artimiausių 25 megabaitų, ir daugiausia 500 megabaitų

#### <a name="generalpropertieslog"></a>general.properties.log

Šis įvykis renka informaciją, kuri leidžia skirstyti ir klasifikuoti „Outlook“ programos problemas, susijusias su pritaikymo neįgaliesiems ir įrenginio parametrais.  Šis skirstymas į kategorijas būtinas tam, kad būtų galima nustatyti problemų poveikį klientams.

Toliau nurodyti laukai renkami tik „iOS“:

- **alternate_app_icon** – nurodo alternatyvią programos piktogramą, kurią vartotojas šiuo metu pasirinko programai

- **bold_text** – nurodo, ar įrenginyje įjungtas paryškintasis tekstas, kad būtų galima nustatyti su paryškintu tekstu susijusias problemas

- **closed_captioning** – nurodo, ar vartotojas įjungė paslėptuosius titrus savo įrenginyje, kad padėtų mums aptikti su paslėptaisiais titrais susijusias problemas

- **darker_system_colors** – nurodo, ar vartotojas įjungė sistemos spalvų patamsėjimą, kad padėtų mums nustatyti su šiuo parametru susijusias problemas

- **gray_scale** – nurodo, ar vartotojas įrenginyje įjungė pustonius, kad padėtų mums nustatyti su šiuo parametru susijusias problemas

- **guided_access** – nurodo, ar vartotojas įrenginyje įjungė vadovaujamą prieigą, kad padėtų mums nustatyti su šiuo parametru susijusias problemas

- **invert_colors** – nurodo, ar vartotojas įrenginyje įjungė spalvų pakeitimo parametrą, kad padėtų mums nustatyti su šiuo parametru susijusias problemas

- **mono_audio** – nurodo, ar vartotojas įrenginyje įjungė monofoninį garsą, kad padėtų mums nustatyti su šiuo parametru susijusias problemas

- **reduce_motion** – nurodo, ar vartotojas įrenginyje įjungė sumažintą judėjimą, kad padėtų mums nustatyti su šiuo parametru susijusias problemas

- **reduce_transparency** – nurodo, ar vartotojas įrenginyje įjungė skaidrumo sumažinimo parametrą, kad padėtų mums nustatyti su šiuo parametru susijusias problemas

- **speak_screen** – nurodo, ar vartotojas įrenginyje įjungė monofoninį garsą, kad padėtų mums nustatyti su šiuo parametru susijusias problemas

- **speak_selection** – nurodo, ar vartotojas įrenginyje įjungė kalbėjimo pasirinkimą, kad padėtų mums nustatyti su šiuo parametru susijusias problemas

- **switch_control** – nurodo, ar vartotojas įrenginyje įjungė jungiklio valdymą, kad padėtų mums nustatyti su šiuo parametru susijusias problemas

- **voice_over** – nurodo, ar vartotojas įrenginyje įjungė „VoiceOver“, kad padėtų mums nustatyti su šiuo parametru susijusias problemas

Toliau nurodyti laukai renkami tik „Android“:

- **braille** – nurodo, ar vartotojas įrenginyje įjungė spalvų pakeitimo parametrą, kad padėtų mums nustatyti su šiuo parametru susijusias problemas

- **caption** – nurodo, ar vartotojas įjungė paslėptuosius titrus savo įrenginyje, kad padėtų mums aptikti su paslėptaisiais titrais susijusias problemas

- **color_inversion** – nurodo, ar vartotojas įrenginyje įjungė spalvų pakeitimo parametrą, kad padėtų mums nustatyti su šiuo parametru susijusias problemas

- **high_contrast** – nurodo, ar vartotojas įrenginyje įjungė didelio kontrasto parametrą, kad padėtų mums nustatyti su šiuo parametru susijusias problemas

- **large_text** – nurodo, ar įrenginyje įjungtas didelio teksto parametras, kad būtų galima nustatyti su dideliu tekstu susijusias problemas

- **supported_abis** – nurodo, kokio tipo programos dvejetaines sąsajas (ABIs) palaiko įrenginio platforma, kad būtų galima nustatyti su šiuo parametru susijusias problemas

- **switch_access** – nurodo, ar vartotojas įrenginyje įjungė prieigos valdymą, kad padėtų mums nustatyti su šiuo parametru susijusias problemas

- **talkback** – nurodo, ar vartotojas įrenginyje įjungė „TalkBack“, kad padėtų mums nustatyti su šiuo parametru susijusias problemas

- **theme_color** – pasirinktinė (pasirinkta vartotojo) temos spalva, kurią šiuo metu naudoja programa

- **webview_kernel_version**: įrenginio „Chromium“ branduolio „WebView“ versija, kuri padės mums aptikti suderinamumo su „WebView“ versija susijusias problemas.

- **webview_package_name**: įrenginio paketo pavadinimas, kuris padės mums aptikti suderinamumo su „WebView“ versija susijusias problemas.

- **webview_package_version**: įrenginio paketo versija, kuri padės mums aptikti suderinamumo su „WebView“ versija susijusias problemas.

#### <a name="lowstoragewarning"></a>low.storage.warning

Parametras būtinas siekiant stebėti, ar programa staiga užima didžiąją dalį jūsų įrenginio saugyklos dėl didelio atminties naudojimo nurodant, kad įrenginyje liko nedaug saugyklos vietos

Renkami šių laukų duomenys: 

- **free_bytes** – įrenginyje likusios laisvos saugyklos vietos kiekis

#### <a name="officeairspaceairspacelocalblocklistdriverupdated"></a>Office.AirSpace.AirSpaceLocalBlocklistDriverUpdated

Vartotojas atnaujino vaizdo plokštės tvarkyklę, kuri anksčiau sukėlė „Office“ gedimus ir todėl nebenaudojama. Informuoja „Microsoft“, kad vartotojai, kurie vieną kartą buvo netinkamoje vaizdo generavimo būsenoje, vėl yra rekomenduojamoje vaizdo generavimo būsenoje.

Renkami šių laukų duomenys:

  - **Data\_BlockedDriverVersion** – Tvarkyklės versija, kuri buvo blokuota.

  - **Duomenų\_DeviceId** – Vaizdo plokštės įrenginio, kuris buvo blokuotas, identifikatorius.

  - **Data\_UpdatedDriverVersion** – Atnaujintos tvarkyklės versija

#### <a name="officeairspaceairspacelocalblocklistinfo"></a>Office.AirSpace.AirSpaceLocalBlocklistInfo

Išsami informacija apie vartotojo vaizdo plokštės tvarkyklę, kuri sukėlė kelis pastaruosius „Office“ programų gedimus. „Office“ nepanaudos šios vaizdo plokštės šiame „Office“ seanse (naudojant programinės įrangos vaizdo generavimą) tol, kol bus atnaujinta tvarkyklė. Informuoja „Microsoft“ apie vaizdo plokštės tvarkykles, kurios sukelia problemų „Office“, todėl galima nustatyti tendencijas ir analizuoti tokių tvarkyklių poveikį. Pranešti „Microsoft“, kiek vartotojų yra naudojant šią antrinę optimalią būseną.

Renkami šių laukų duomenys:

  - **Data\_AllAppsBlocked** – Ar visos „Office“ programos blokuotos

  - **Data\_BlockedDeviceId** – Vaizdo plokštės įrenginio, kuris buvo blokuotas, identifikatorius

  - **Data\_BlockedDriverVersion** - Tvarkyklės versija, kuri buvo blokuota.

  - **Duomenų\_CrashHistory** – Struktūra, vaizduojanti vaizdo plokštės tvarkyklės, dėl kurios kilo gedimas, istoriją

  - **Data\_SecsBetweenCrashes** - Kaip dažnai pasitaiko tvarkyklės kortelės gedimų

#### <a name="officeairspaceairspacewincompisenabled"></a>Office.AirSpace.AirSpaceWinCompIsEnabled

Ar naudojama naujausia „Office“ žemo lygio vaizdo generavimo platforma, pagrįsta „Windows Composition“.

Kadangi naujausia „Office“ žemo lygio vaizdo generavimo platforma sukurta ir pradedama leisti klientams, tai leidžia „Microsoft“ pamatyti, kiek vartotojų yra kiekvienoje versijoje, kad užtikrintų, jog platformoje neliko klaidų.

Renkami šių laukų duomenys:

  - **Data\_WinCompEnabled** - Ar naudojama „Windows Composition“ pagrįsta vidinė versija

#### <a name="officeairspacebackendwin32graphicsdriverhangdetectorblocklistapp"></a>Office.AirSpace.Backend.Win32.GraphicsDriverHangDetectorBlocklistApp

Pastebėta, kad dėl vartotojo vaizdo plokštės kyla ilgų arba nepataisomų „pakibimų“. „Office“ nepanaudos šios vaizdo plokštės šiame „Office“ seanse (naudojant programinės įrangos vaizdo generavimą) tol, kol bus atnaujinta tvarkyklė. Informuoja „Microsoft“ apie vaizdo plokštės tvarkykles, kurios sukelia problemų „Office“, todėl galima nustatyti tendencijas ir analizuoti tokių tvarkyklių poveikį. Taip pat informuoja, kiek vartotojų yra naudojant šią antrinę optimalią būseną.

Renkami šių laukų duomenys:

  - **Data\_AppName** - Dėl kokios programos „pakimba“ vaizdo plokštės tvarkyklė

#### <a name="officeairspacebackendwin32graphicsdriverhangdetectorregistrywrite"></a>Office.AirSpace.Backend.Win32.GraphicsDriverHangDetectorRegistryWrite

„Office“ nustatė, kad dėl naudotojo vaizdo plokštės „pakibo“ programa, kuri turėtų būti analizuojama kitoje „Office“ programos įkrovoje. Naudojamos norint nustatyti, ar naudojant kitą vaizdo plokštės tvarkyklę arba adapterį vartotojui būtų suteikta geresnė patirtis. Kaip matyti, „Microsoft“ gali atlikti koregavimus, kad „Office“ patirtis būtų kuo sklandesnė.

Renkami šių laukų duomenys:

  - **Data\_HangDetected** – Ar aptiktas „pakibimas“

  - **Data\_InDeviceCall** - Kuris vaizdo plokštės vaizdo generavimo iškvietimas buvo „Office“, kai įvyko „pakibimas“.

  - **Data\_Timeout** – kiek laiko praėjo nuo „pakibimo“, jei programa atkurta

  - **Duomenų\_UnrecoverableCommand** - Ar paprastai šios vaizdo plokštės vaizdo generavimo komandos „pakibimas“ yra atkuriamas.

#### <a name="officeairspacebackendwin32localblocklistactivity"></a>Office.AirSpace.Backend.Win32.LocalBlocklistActivity

Išsami informacija apie vartotojo vaizdo plokštės tvarkyklę, kuri sukėlė kelis pastaruosius „Office“ programų gedimus. „Office“ nepanaudos šios vaizdo plokštės šiame „Office“ seanse (naudojant programinės įrangos vaizdo generavimą) tol, kol bus atnaujinta tvarkyklė. Informuoja „Microsoft“ apie vaizdo plokštės tvarkykles, kurios sukelia problemų „Office“, todėl galima nustatyti tendencijas ir analizuoti tokių tvarkyklių poveikį. Pranešti „Microsoft“, kiek vartotojų yra naudojant šią antrinę optimalią būseną.

Renkami šių laukų duomenys:

  - **Data.AllAppsBlocked** - Ar visos „Office“ programos blokuotos

  - **Data.BlockedDeviceId** - Vaizdo plokštės įrenginio, kuris buvo blokuotas, identifikatorius

  - **Data.BlockedDriverVersion** - Tvarkyklės versija, kuri buvo blokuota

  - **Data.CrashHistory System.String** - Struktūra, vaizduojanti vaizdo plokštės tvarkyklės, dėl kurios kilo gedimas, istoriją

  - **Data.SecsBetweenCrashes** - Kaip dažnai pasitaiko tvarkyklės kortelės gedimų

#### <a name="officeairspacebackendwin32localblocklistdriverupdatedactivity"></a>Office.AirSpace.Backend.Win32.LocalBlocklistDriverUpdatedActivity

Vartotojas atnaujino vaizdo plokštės tvarkyklę, kuri anksčiau sukėlė „Office“ gedimus ir todėl nebenaudojama. Informuoja „Microsoft“, kad vartotojai, kurie vieną kartą buvo netinkamoje vaizdo generavimo būsenoje, vėl yra rekomenduojamoje vaizdo generavimo būsenoje.

Renkami šių laukų duomenys:

  - **Data\_BlockedDeviceId** – Vaizdo plokštės įrenginio, kuris buvo blokuotas, identifikatorius

  - **Data\_BlockedDriverVersion** - Tvarkyklės versija, kuri buvo blokuota.

  - **Data\_UpdatedDriverVersion** – Atnaujintos tvarkyklės versija

#### <a name="officegraphicsspritememcorrupt"></a>Office.Graphics.SpriteMemCorrupt

Praneša apie aptiktas „sprite“ atminties apskaitos telemetrijos klaidas. Svarbu vertinant grafinės atminties naudojimo telemetrijos būseną. Ši informacija reikalinga norint patikrinti mūsų „SpriteMem“ telemetrijos tikslumą.

Renkami šių laukų duomenys:

  - **Duomenų\_CurrentSpriteMem** - Bendras atminties kiekis, aktyviai paskirstytas išlaikyti „sprites“ (vaizdus), dėl kurių atsiranda ekrano turinys.

  - **Data\_Function** - Funkcijos, kuri bando paleisti „sprite“ atmintį, pavadinimas.

  - **Data\_SpriteMemToRemove** – Atminties kiekis, kuris turi būti pašalintas iš priskyrimo.

#### <a name="officepowerpointpptsharednointernetconnectivity"></a>Office.PowerPoint.PPT.Shared.NoInternetConnectivity

Renkama kaskart, kai „PowerPoint“ aptinka, kad nėra interneto ryšio. „Microsoft“ naudoja šiuos duomenis, kad gautų diagnostinę informaciją apie vartotojo interneto ryšį, kad galėtų suprasti, kokią tai daro įtaką ryšiui su „Office“ paslaugomis.

Renkami šių laukų duomenys:

- **Data\_IsNexusDetected:bool** - Rodo, ar turime interneto ryšio būseną skambinant „Nexus“ tarnybai (reikšmė TRUE (teisinga) arba iškviečiant bendrosios žiniatinklio tarnybos API iškvietimą (reikšmė FALSE (klaidinga)

#### <a name="officeserviceabilitymanagerofficesvcmgrprofile"></a>Office.ServiceabilityManager.OfficeSvcMgrProfile

Šis įvykis paleidžiamas, kai įjungiama „Office“ aptarnavimo valdymo tvarkymo priemonė. Šis įvykis yra labai svarbus teikiant tikslias įžvalgas apie diegimo būseną ir taikomąją programą, bei kliento nuomojamų elementų papildinių gedimus, suteikiant mums galimybę sugeneruoti įžvalgas IT administratoriui, kad galėtų užtikrintai įdiegti naujinimus savo įmonės įrenginiams.  

Renkami šių laukų duomenys:

- **DeviceIdJoinToken** – naudojama telemetrijos duomenų iš sveikatos ir diegimo būsenos sujungimui su kitais funkciniais duomenimis, surenkamais naudojant tarnybų srautus.

- **TenantAssociationKeyStamped** – Bulio logikos reikšmės vėliavėlė, naudojama nustatyti valdomų įrenginių skaičių „Office“ ekosistemoje.
