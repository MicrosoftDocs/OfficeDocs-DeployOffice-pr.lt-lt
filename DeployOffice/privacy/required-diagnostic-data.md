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
ms.openlocfilehash: d42f2bd20e3e2169e58d6f5c0a563f1b117ea847
ms.sourcegitcommit: 186aae0571f8ef5f62882b4edb10378ee8e42b6e
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 06/10/2019
ms.locfileid: "34813310"
---
# <a name="required-diagnostic-data-for-office"></a>Būtinieji „Office“ diagnostikos duomenys

> [!IMPORTANT]
> Šiame straipsnyje pateikta informacija taikoma 1904 arba naujesnės versijos „Office“ kliento programinei įrangai, įdiegtai „Windows“ kompiuteryje:
> - „Office 365 ProPlus“ ir „Office 365 Business“
> - „Office 365 Personal“, „Office 365 Home“ arba kitos „Office“ versijos, kurios yra „Office 365“ prenumeratos dalis.
> - „Project“ ir „Visio“, kurios įtrauktos į kai kuriuos prenumeratos planus, pvz., planą „Project Online Professional“ arba „Visio Online“ 2 planą.

Diagnostikos duomenys naudojami siekiant apsaugoti ir naujinti „Office“, aptikti, diagnozuoti ir taisyti problemas, taip pat tobulinti produktus. Šie duomenys neapima vartotojo vardo ar el. pašto adreso, vartotojo failų turinio ar informacijos apie programas, nesusijusias su „Office“.

Šie diagnostikos duomenys, susiję su „Office“ kliento programine įranga, naudojama kompiuteriuose, kuriuose įdiegta operacinė sistema „Windows“, renkami ir siunčiami „Microsoft“. Kai kurie diagnostikos duomenys yra privalomi, o kiti – pasirinktiniai. Suteikiame jums galimybę pasirinkti, ar siųsti mums privalomuosius, ar pasirinktinius diagnostikos duomenis naudojant privatumo valdiklius, pvz., organizacijoms skirtus strategijos parametrus. Naudodami diagnostikos duomenų peržiūros programą galite matyti mums siunčiamus diagnostikos duomenis.

***Būtinieji diagnostiniai duomenys*** yra minimalūs duomenys, kurie yra būtini, kad programų paketas „Office“ būtų apsaugotas, atnaujintas ir veiktų kaip numatyta įrenginyje, kuriame jis įdiegtas.

Būtinieji diagnostikos duomenys padeda nustatyti „Office“ problemas, kurios gali būti susiję su įrenginiu arba programinės įrangos konfigūracija. Pavyzdžiui, jie gali padėti nustatyti, ar programos „Office“ funkcija sugenda dažniau konkrečioje operacinės sistemos versijos su naujai įdiegtomis funkcijomis, ar išjungus tam tikras „Office“ funkcijas. Būtini diagnostikos duomenys padeda aptikti, nustatyti ir išspręsti šias problemas greičiau, kad būtų sumažintas poveikis vartotojams arba organizacijoms.

Daugiau informacijos apie diagnostikos duomenis, žr.:

- [Pasirinktiniai „Office“ diagnostikos duomenys](optional-diagnostic-data.md)
- [Diagnostikos duomenų peržiūros programos naudojimas su „Office“](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

Jei esate organizacijos administratorius, galbūt jus domina šios temos:

- [„Office 365 ProPlus“ privatumo valdiklių apžvalga](overview-privacy-controls.md)
- [„Office 365 ProPlus“ privatumo valdiklių valdymas naudojant strategijos parametrus](manage-privacy-controls.md)

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
| **Produktų ir tarnybų naudojimas**    | [Taikomosios programos funkcijų sėkmingas atlikimas](#application-feature-success-subtype)   | Informacija apie tai, ar sėkmingai veikia programos funkcijos. Tik taikomosios programos ir dokumentų atidarymas ir uždarymas, failų redagavimas ir failų bendrinimas (bendradarbiavimas). |
| | [Taikomosios programos būsena ir įkrova](#application-status-and-boot-subtype)    | Nustatymas, ar įvyko specifiniai funkcijų įvykiai, pvz., paleidimas ar sustabdymas, ir ar funkcija veikia.   |
| | [„Office“ pritaikymo neįgaliesiems konfigūracija](#office-accessibility-configuration-subtype)  | „Office“ pritaikymo neįgaliesiems funkcijos       |
| | [Privatumas](#privacy-subtype)| „Office“ privatumo parametrai|
| **Produktų ir tarnybų veikimas**       | [Netikėtas taikomosios programos uždarymas (gedimas)](#unexpected-application-exit-crash-subtype)  | Nenumatytas programų uždarymas ir programos būsena, kai taip nutinka.    |
|  | [Taikomosios programos funkcijų veikimas](#application-feature-performance-subtype)  | Prastas scenarijų, pvz., taikomosios programos paleidimas ar failo atidarymas, atsakymo laikas ar veikimas. |
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

Informacija apie taikomąją programą. Visi laukai pastovūs visiems konkretiems taikomosios programos versijos seansams.

Šioje kategorijoje yra šie laukai:

  - **Branch** – filialas, pateikęs konkrečią komponavimo versiją. Leidžia mums nustatyti iš kokio filialo buvo gauta komponavimo versija, kad galėtume tinkamai pateikti pataisas.
  - **InstallType** – surašytuvas, nurodantis kaip vartotojas įdiegė taikomąją programą. Leidžia mums nustatyti, ar konkretūs diegimo mechanizmai kuria problemas, nematomas kituose diegimo mechanizmuose.
  - **Name** – duomenis pateikiančios taikomosios programos pavadinimas. Leidžia mums nustatyti, kuri taikomoji programa nurodo problemą, todėl žinome, kaip ją šalinti.
  - **Platform** – plati platformos, kurioje taikomoji programa veikia, klasifikacija. Leidžia mums nustatyti kurioje platformose problema gali kilti, kad galėtume tinkamai nustatyti problemos prioritetą.
  - **Version** – taikomosios programos versiją. Leidžia mums nustatyti kurios produkto versijos rodo problemą, kad galėtume tinkamai nustatyti jos prioritetą.

#### <a name="client"></a>Klientas 

Identifikatorius, susijęs su įrenginio „Office“ egzemplioriumi. Pateiktos diegimo versijos, skirtos keliems taikomųjų programų paketams, visų taikomųjų programų seansų arba pateiktos taikomosios programos versijos seansų metu išlieka tokie patys.

Šioje kategorijoje yra šie laukai:

  - **Id** – unikalus identifikatorius, priskirtas klientui „Office“ diegimo metu. Leidžia mums nustatyti, ar problema daro poveikį pasirinktam diegimų rinkiniui ir keliems vartotojams yra daroma įtaka.

#### <a name="consent"></a>Sutikimas

Informacija apie vartotojų sutikimą dėl diagnostikos duomenų ir prisijungus naudojamų funkcijų.

Šioje kategorijoje yra šie laukai:

  - **UserCategory –** nustatytas sutikimą pateikusio vartotojo tipas. Vienas iš MSAUser, AADUser arba LocalDeviceUser

  - **DiagnosticConsentLevel** – nurodo, kokiam diagnostikos duomenų lygiui vartotojas davė sutikimą

  - **DiagnosticConsentSourceLocation** – nurodo, kaip vartotojas pateikė sutikimą dėl diagnostikos duomenų

  - **DiagnosticConsentConsentTime** – nurodo, kada vartotojas pateikė sutikimą dėl diagnostikos duomenų

  - **ServiceConnectionState** – nurodo, ar vartotojas pasirinko naudoti visas prisijungus naudojamas funkcijas

  - **ServiceConnectionStateSourceLocation** – nurodo, kaip vartotojas pasirinko, ar naudoti visas prisijungus naudojamas funkcijas

  - **ServiceConnectionStateConsentTime** – nurodo, kada vartotojas pasirinko, ar naudoti visas prisijungus naudojamas funkcijas

  - **ControllerConnectedServicesState** – nurodo, ar vartotojas turi prieigą prie pasirinktinių prisijungus naudojamų funkcijų

  - **ControllerConnectedServicesStateSourceLocation** – nurodo, kaip vartotojas pasirinko pasirinktines prisijungus naudojamas funkcijas

  - **ControllerConnectedServicesStateConsentTime** – nurodo, kada vartotojas pasirinko pasirinktinių prisijungus naudojamų funkcijų būseną

  - **UserContentDependentState** – nurodo, ar vartotojas pasirinko įjungti prijungus naudojamas funkcijas, analizuojančias turinį

  - **UserContentDependentStateSourceLocation** – nurodo, kaip vartotojas pasirinko prijungus naudojamų funkcijų, analizuojančių turinį, įjungimą arba išjungimą

  - **UserContentDependentStateConsentTime** – nurodo, kada vartotojas pasirinko prijungus naudojamų funkcijų, analizuojančių turinį, įjungimą arba išjungimą

  - **DownloadContentState** – nurodo, ar vartotojas pasirinko įjungti prijungus naudojamas funkcijas, atsisiunčiančias internetinį turinį

  - **DownloadContentStateSourceLocation** – nurodo, kaip vartotojas pasirinko prijungus naudojamų funkcijų, atsisiunčiančių internetinį turinį, įjungimą arba išjungimą

  - **DownloadContentStateConsentTime** – nurodo, kada vartotojas pasirinko prijungus naudojamų funkcijų, atsisiunčiančių internetinį turinį, įjungimą arba išjungimą.

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

  - **Id** – unikaliai identifikuoja nurodyto seanso duomenis. Leidžia mums nustatyti problemų poveikį vertinant veikiamų seansų skaičių ir ar yra bendrų šių seansų funkcijų.

  - **ImpressionId** – nurodo testuojamų variantų rinkinį, kurie veikia nurodytame seanse. Leidžia mums aptikti, kurie atskiri testuojami variantai veikia seanso metu, kad galėtume nustatyti, ar testuojamas variantas yra problemos šaltinis, veikiantis vartotojus.

  - **MeasuresEnabled** – žymė, nurodanti, ar vykdoma dabartinio seanso duomenų atranka. Leidžia mums nustatyti, kaip statistiškai įvertinti duomenis, surinktus iš nurodyto seanso.

  - **SamplingClientId** – kliento, naudoto nustatyti, ar jis yra pavyzdžių rinkimo dalis, ID. Leidžia mums nustatyti, kodėl į pavyzdžių rinkimą buvo arba nebuvo įtrauktas atskiras seansas.

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

  - **Duration** – laikas, reikalingas vykdyti veiklai. Leidžia mums nustatyti veikimo problemas, neigiamai veikiančias vartotojo patirtį.

  - **Result**.**Code** – taikomosios programos nustatytas kodas, skirtas identifikuoti pateiktus rezultatus. Leidžia mums nustatyti konkretesnę pateikto sutrikimo informaciją, pvz., trikties kodą, naudojamą problemoms klasifikuoti ir šalinti.

  - **Result.Tag** – sveikųjų skaičių žymė, nurodanti kode vietą, kurioje buvo sugeneruotas rezultatas. Leidžia mums aiškiai nustatyti kodo vietą, kurioje buvo sugeneruotas rezultatas, įgalinantis klasifikuoti triktis.

  - **Result**.**Type** – rezultato kodo tipas. Nurodo, kokio tipo rezultato kodas buvo išsiųstas, kad būtų galima teisingai interpretuoti reikšmę.

  - **Success** – žymė, nurodanti, ar veikla atlikta sėkmingai. Leidžia mums nustatyti, ar pavyko vartotojo produkte atlikti veiksmai. Tai leidžia mums nustatyti problemas, kurios daro įtaką vartotojui.

#### <a name="application"></a>Taikomoji programa 

Informacijos apie įdiegtą taikomąją programą, iš kurios buvo renkami įvykiai.

Šioje kategorijoje yra šie laukai:

  - **Architecture** – taikomosios programos architektūra. Leiskite mums klasifikuoti klaidas, kurios gali būti susijusios su taikomosios programos architektūra.

  - **Click2RunPackageVersion** – paketo spustelėkite ir naudokitės, įdiegusio taikomąją programą, versijos numeris. Leidžia mums nustatyti, kokia diegimo programos versija buvo naudojama diegti „Office“, kad galėtume identifikuoti susijusias problemas.

  - **DistributionChannel** – kanalas, kuriame taikomoji programa buvo įdiegta. Leidžia mums išskaidyti gaunamus duomenis, kad galėtume nustatyti, ar problemos daro poveikį auditorijai.

  - **InstallMethod** – ar dabartinė „Office“ komponavimo versija buvo naujovinta iš ankstesnės komponavimo versijos, atšaukus ankstesnę komponavimo versiją arba, ar tai buvo naujas diegimas.

  - **IsClickToRunInstall** – žyma, nurodanti, ar diegimui buvo naudojama spustelėkite ir diekite technologija. Leidžia mums nustatyti problemas, kurios gali būti susijusios su spustelėkite ir naudokite diegimo mechanizmu.

  - **IsDebug** – žyma, nurodanti, ar „Office“ komponavimo versija yra derinta komponavimo versija. Leidžia mums nustatyti, ar problemos kyla iš derintų komponavimo versijų, kurios gali veikti kitaip.

  - **IsInstalledOnExternalStorage** – žyma, nurodanti, ar „Office“ buvo įdiegta išorinėje saugykloje. Leidžia mums nustatyti, ar problemos gali būti atsektos iki išorinės saugyklos vietos.

  - **IsOEMInstalled** – žyma, nurodanti, ar „Office“ buvo įdiegta originalios įrangos gamintojo (OĮG). Leidžia mums nustatyti, ar taikomoji programa buvo įdiegta OĮG. Tai gali padėti mums klasifikuoti ir identifikuoti problemas.

  - **PreviousVersion** – „Office“ versija, kuri buvo anksčiau įdiegta kompiuteryje. Leidžia mums atkurti ankstesnę versiją, jei dabartinė turi problemą.

  - **ProcessFileName** – taikomosios programos failo pavadinimas. Leidžia mums nustatyti pavadinimą vykdomosios programos, generuojančios duomenis, nes gali būti keli skirtingi proceso failų pavadinimai, nurodomi kaip tos pačios taikomosios programos pavadinimas.

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

  - **Name** – įvykio pavadinimas. Leidžia nustatyti iš kliento išsiųstą įvykį.

  - **Rule** – duomenis generavusios taisyklės identifikatorius, jeigu jie buvo sugeneruoti taisyklės. Leidžia mums nustatyti dalies duomenų šaltinį, kad galėtume patvirtinti ir tvarkyti įvykių parametrus

  - **RuleId** – duomenis generavusios taisyklės identifikatorius, jeigu jie buvo sugeneruoti taisyklės. Leidžia mums nustatyti dalies duomenų šaltinį, kad galėtume patvirtinti ir tvarkyti įvykių parametrus.

  - **RuleInterfaces** – visos sąsajos, įgyvendintos naudojant konkrečią taisyklę. Leidžia mums klasifikuoti ir importuoti duomenis pagal jų struktūrą, kuri supaprastina duomenų apdorojimą.

  - **RuleVersion** – duomenis generavusios taisyklės identifikatorius, jeigu jie buvo sugeneruoti taisyklės. Leidžia mums nustatyti dalies duomenų šaltinį, kad galėtume patvirtinti ir tvarkyti įvykių parametrus.

  - **SampleRate** – indikatorius, nurodantis koks vartotojų procentas siunčia šią informacijos dalį. Tai leidžia mums atlikti statistinę duomenų analizę ir nereikia, kad dažniausius naudojamus duomenų elementus siųstų visi vartotojai.

  - **SchemaVersion** – schemos versija, naudojama generuoti diagnostikos duomenis. Būtina valdyti iš kliento siunčiamus duomenis. Taip užtikrina kiekvieno kliento siunčiamų duomenų pokyčius per tam tikrą laiką.

  - **Sequence** – skaitiklis, nurodantis įvykio, sugeneruoto kliento, eiliškumą. Leidžia užsakyti gautus duomenis, kad galėtume nustatyti kokie veiksmai galėjo sukelti problemą, darančią įtaką klientams.

  - **Source** – šaltinio srautas, naudotas duomenims įkelti. Būtinas stebėti visus mūsų nusiuntimo srautus bendrai sveikatai ir padėti identifikuoti įkėlimo srauto problemas. Tai leidžia stebėti atskirus nusiuntimo srautus, siekiant užtikrinti, kad jie ir toliau atitinka reikalavimus.

  - **Time** – įvykio sugeneravimo kliente laikas. Leidžia mums sinchronizuoti ir patikrinti kliento sugeneruotų įvykių eiliškumą, bei nustatyti veikimo rodiklius vartotojo instrukcijoms. 

#### <a name="host"></a>Pagrindinis kompiuteris

Informacija apie taikomąją programą, kurią pagrindinis kompiuteris naudoja kaip įdėtąją taikomąją programą

Šioje kategorijoje yra šie laukai:

  - **Id** – unikalus identifikatorius, kurį įdėtoji taikomoji programa priskyrė pagrindinio kompiuterio taikomajai programai.

  - **SessionId** – pagrindinio kompiuterio seanso visuotinis unikalus identifikatorius.

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

  - **SamplingKey** – raktas, naudojamas nustatyti, ar seanso metu vykdomas duomenų rinkimas. Leidžia mums suprasti, kaip atskiri seansai pasirenka, ar jų metu yra vykdoma duomenų atranka.

  - **SamplingMethod** – būdas, naudojamas nustatyti pavyzdžių rinkimo strategijai. Leidžia mums suprasti, kokie duomenys gaunami iš seanso.

  - **Sequence** – unikalus skaitinis seanso identifikatorius. Leidžia analizuoti seansų eiliškumą nustatyti, kokiu atveju galėjo įvykti problema.

  - **Start** – procesas seanso įkrovos trukmė. Leidžia mums nustatyti seanso pradžios laiką.

  - **TimeZoneBiasInMinutes** – UTC ir vietinio laiko skirtumas minutėmis. Leidžia normalizuoti UTC laiką atgal į vietinį laiką.

  - **SamplingClientIdValue** – rakto, naudojamo pavyzdžių rinkimo nustatymui, reikšmė. Leidžia mums nustatyti, kodėl seanso metu buvo arba nebuvo vykdomas pavyzdžių rinkimas.

  - **SamplingDeviceIdValue** – rakto, naudojamo pavyzdžio ėmimo nustatymui, reikšmė. Leidžia mums nustatyti, kodėl seanso metu buvo arba nebuvo vykdomas pavyzdžių rinkimas.

  - **SamplingSessionKValue** – išplėstinio pavyzdžių rinkimo metaduomenys. Naudojami, kad būtų galima įvertinti gautų statistikos duomenų reikšmes.

  - **SamplingSessionNValue** – išplėstinio pavyzdžių rinkimo metaduomenys. Naudojami, kad būtų galima įvertinti gautų statistikos duomenų reikšmes.

  - **TelemetryPermissionLevel** – reikšmė, nurodanti vartotojo pasirinktą diagnostikos duomenų lygį. Leidžia mums suprasti, kokio lygio diagnostikos duomenų galime tikėtis iš seanso.

## <a name="software-setup-and-inventory-data-events"></a>Programinės įrangos sąrankos ir inventoriaus duomenų įvykiai

Toliau pateikiami šios kategorijos duomenų potipiai:
- [„Office“ sąranka ir inventorius](#office-setup-and-inventory-subtype)
- [„Office“ papildinio konfigūracija](#office-add-in-configuration-subtype)
- [Sauga](#security-subtype)  

### <a name="office-setup-and-inventory-subtype"></a>*„Office“ sąranka ir inventoriaus potipis*

Įdiegtas produktas ir versija, bei diegimo būsena.

#### <a name="officeclicktorunupdatestatus"></a>Office.ClickToRun.UpdateStatus

Taikoma visoms „win32“ taikomosioms programoms. Padeda suprasti „Office“ paketo naujinimo proceso būseną (ar sėkmingai atliktas, su klaidų informacija)

Renkami šių laukų duomenys:

- **build** – šiuo metu įdiegta „Office“ versija

- **channel** – kanalas, kuriuo platintas „Office“

- **errorCode** – triktį nurodantis klaidos kodas

- **errorMessage** – papildoma klaidos informacija

- **status** – dabartinė naujinimo būsena

- **targetBuild** – „Office“ versija, į kurią naujinama

#### <a name="officecorrelationmetadatautccorrelationmetadata"></a>Office.CorrelationMetadata.UTCCorrelationMetadata

Renka „Office“ metaduomenis per UTC, kad palyginti atitinkamus duomenis, surinktus naudojant „Office“ telemetrijos srautą, bei patikrinti duomenų tikslumą ir užbaigtumą.

Renkami šių laukų duomenys:

- **abConfigs** – funkcijų ID sąrašas, skirtas identifikuoti pas klientą įjungtas funkcijas arba jis gali būti tuščias, kai duomenys nėra renkami.

- **abFlights** – „NoNL:NoFlights“, kai funkcijų testavimo variantai nenustatyti. Kitu atveju „holdoutinfo=unknown“.

- **AppSessionGuid** – konkrečios taikomosios programos seanso pradžios identifikatorius, naudojamas nuo proceso kūrimo pradžios ir iki proceso pabaigos. Jis yra suformuotas kaip standartinis 128 bitų GUID, tik sudarytas iš 4 dalių. Šios keturios dalys eilės tvarka yra (1) 32 bitų proceso ID (2) 16 bitų seanso ID (3) 16 bitų įkrovos ID (4) 64 bitų proceso sukūrimo laikas, išreikštas UTC 100 nsek.

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

- **UTCReplace_AppSessionGuid** – nuolatinė Bulio logikos vertė. Visuomet „true“.

#### <a name="officetargetedmessagingensurecached"></a>Office.TargetedMessaging.EnsureCached 

Seka, ar buvo atsisiųstas paketas dinaminei matomosios tinklalapio srities daliai. Laikoma taikomosios programinės įrangos konfigūracija, nes paketas turi būti sėkmingai atsisiųstas, kad įgalinti klientą generuoti tinkamą patirtį. Yra ypač kritinės vartotojo prenumeratoms, kur matomąją tinklalapio sritį naudojame informuoti vartotoją, kad licencija nebegalioja. Naudojamas sekti metaduomenis dinaminio turinio paketo, kurį atsisiuntė ir į talpyklą įkėlė produktas, taip pat operacijų, atliktų su paketu, rezultatus: nesėkmingus atsisiuntimus, negalimą išsipakavimą, nuolatines patikros triktis, sėkmingą kreipimąsi į talpyklą, paketo naudojimus ir atsisiuntimo šaltinius.

Renkami šių laukų duomenys:

  - **Data\_CacheFolderNotCreated –** Bulio logikos žyma nurodo, ar pavyko sukurti talpyklos aplanką

  - **Data\_CdnPath – paketo šaltinio adresas –**

  - **Data\_EnsureCached –** Bulio logikos žyma, nurodanti, ar turinio paketas buvo įtrauktas į talpyklą

  - **Data\_ExistsAlready –** Bulio logikos žyma, nurodanti, kad paketas jau buvo atsisiųstas anksčiau ir buvo dar vienas bandymas

  - **Data\_GetFileStreamFailed –** šaltinio paketo nėra šaltinyje

  - **Data\_GetFileStreamFailedToCreateLocalFolder –** vietinio disko problemos, dėl kurių nepavyksta sukurti katalogo

  - **Data\_GetFileStreamFromPackageFailed –** žyma, nurodanti, ar paketas buvo atsisiųstas, bet klientas negali jo perskaityti

  - **Data\_GetFileStreamFromPackageSuccess –** sėkmingi paketo perskaitymo bandymai

  - **Data\_GetFileStreamSuccess -** nėra disko arba konfigūravimo problemų, neleidžiančių skaityti failų srautą

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

#### <a name="officeextensibilityappcommandsappcmdprojectionstatus"></a>Office.Extensibility.AppCommands.AppCmdProjectionStatus

Renka informaciją, skirtą stebėti kurie „Office“ papildiniai diegimai sėkmingai atnaujino juostelę ir jų palyginimas su nepavykusiais naujinimais.

Skirtas šalintis standartines registracijos problemas, kai papildiniai nėra tinkamai įdiegiami ir niekada nerodo, kad jie netinka naudoti.

Renkami šių laukų duomenys:

  - Nėra

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

Informacija apie sėkmingą arba nesėkmingą „Office 365“ nuomotojo administratoriui priskirtų papildinių poreikį atnaujintiems duomenims. Naudota sveikatos metrikoms, diagramoms ir kliento problemų analizei. ExchangeGetLastUpdate visada bus paleista įkrovos metu kaip dalis pagrindinio kompiuterio kodo ir nustatys, ar buvo vartotojui pakeistos papildinio užduotys. Jei taip, tuomet osf.DLL bus įkeltas, kad galėtume iškviesti ExchangeGetEntitlements gauti konkrečius priskyrimus (ir ExchangeGetManifests bus iškviestas, kad būtų gauti visos naujos reikalingos deklaracijos).  ExchangeGetEntitlements (ir ExchangeGetManifests) gali taip pat būti iškviestos pagal poreikį, kai jau veikia pagrindinio kompiuterio taikomoji programa. Norima, kad nebūtų įkeltas didelis DLL, jei mums jis nereikalingas. Jeigu nepavyksta pirmasis tarnybos kvietimas, be šio įvykio nurodyto lauke Privaloma, negalėtume pasakyti, ar vartotojai negali gauti jiems priskirtų papildinių. Tai taip pat yra pagrindinis įspėjimas dėl galimų bet kokių autentifikavimo problemų, su kuriomis galime susidurti kreipdamiesi į savo paslaugą.

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

Renka informaciją apie automatizavimo serverio iškvietimą arba klientą VBA sprendimuose. Naudota suprasti VBA ir Com objektų sąveiką.

Renkami šių laukų duomenys:

  - **ComObjectInstantiatedCount** – COM objekto diegimų skaičius

  - **HashComObjectInstantiatedClsid** – COM objekto klasės identifikatoriaus maiša

  - **HashProjectName** – VBA projekto pavadinimo maiša

  - **TagId** – unikali žymė

#### <a name="officeextensibilityvbatelemetrydeclare"></a>Office.Extensibility.VBATelemetryDeclare 

Renka informaciją apie Win32 API iškvietimą VBA sprendimuose. Naudojamas suprasti VBA ir naudojimo sąveiką, bei papildyti saugos tyrimus.

Renkami šių laukų duomenys:

  - **DeclareCount** – aprašų skaičius

  - **HashDeclare** – DLL failo vardo maiša

  - **HashEntryPoint** – API pavadinimo maiša

  - **HashProjectName** – VBA projekto pavadinimo maiša

  - **IsPtrSafe** – ar aprašo pareiškimas suderinamas su skirtinga architektūra

  - **TagId** – unikali žymė

#### <a name="officeoutlookdesktopadd-insadd-inloaded"></a>Office.Outlook.Desktop.Add-ins.Add-inLoaded

Renka informaciją apie sėkmingą arba nesėkmingą „Outlook“ papildinio paleidimą. Šie duomenys yra aktyviai stebimi, siekiant užtikrinti, kad „Outlook“ su kliento papildiniais veikia tinkamai. Šie duomenys naudojami problemoms aptikti ir tirti.

Renkami šių laukų duomenys:

  - **Standartinė HVA veiklą, kai nėra pasirinktinės apkrovos**

#### <a name="officeprogrammabilityadd-insinternalsetconnectenterprise"></a>Office.Programmability.Add-ins.InternalSetConnectEnterprise

Įvykis sugeneruotas, kai COM papildinys yra įkeltas „Enterprise“ įrenginyje. Kompiuterio analizė: \# įkėlimai naudojami kaip vardiklis sveikatai apskaičiuoti (\# gedimas / \# įkėlimai), kai skaičiuojami sveikatos metrikai bandomajam sprendimui ir gamybos žiediniams tinklams „Enterprise“ scenarijuose. Tai reikalauja, kad duomenys būtų tikslūs, ne atrinkti, nes įrenginių skaičius yra mažesnis (100–1000).

Renkami šių laukų duomenys:

  - **Add-inconnectFlag** – dabartinio įkėlimo veikimas

  - **Add-inDescription** – papildinio aprašas

  - **Add-inFileName** – papildinio failo vardas, be failo kelio

  - **Įtraukti inFriendlyName** – papildinio aiškus pavadinimas

  - **Add-inFriendlyName** – papildinio klasės ID

  - **Add-inProgId** – papildinio programos ID

  - **Add-inProvider** – papildinio teikėjas

  - **Add-inTimeDateStamp** – papildinio laiko žyma iš DLL metaduomenų

  - **Add-inVersion** – papildinio versija

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

Seka, ar makrokomanda buvo patvirtinta, kad yra iš patikimo leidėjo. Naudota užtikrinti saugos rizikos mažinimo efektyvumą, saugantį programos „Office“ galutinius vartotojus.

Renkami šių laukų duomenys:

  - **Policy** – ar strategija nustatyta, nenustatytas arba negalima

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

Seka, kada vartotojas yra raginamas įgalinti XL4 makrokomandas. Naudojamas įvertinti XL4 makrokomandų paplitimą programoje „Excel“, kad užtikrinti būsimas riziką mažinančias saugos priemones, blokuojančias XL4 pagal numatytuosius parametrus, bei atsižvelgti į saugos incidentus, atsirandančius netinkamai naudojant XL4 makrokomandas.

Renkami šių laukų duomenys:

  - **PromptType** – kokio tipo buvo rodomas raginimas


#### <a name="officesecurityocxufiprompt"></a>Office.Security.OCX.UFIPrompt

Seka, kada saugos raginimas rodomas vartotojui, kai įkeliamas „ActiveX“ valdiklis, pažymėtas kaip nesaugus inicijavimui. Skirtas sekti UFI „ActiveX“ valdiklių paplitimas „Office“ dokumentuose, kad atsižvelgiant į saugos incidentus, užtikrinti rizikos mažinimą (pvz. užrakinant valdiklius).

Renkami šių laukų duomenys:

  - **IsFromInternet** – ar dokumentas atidaromas internete

  - **IsSecureReaderMode** – ar dokumentas atidaroma saugiame skaitytuve

  - **OcxTrustCenterSettings** – koks yra dabartinis „ActiveX“ parametras


#### <a name="officesecuritysecurereaderhostopeninosr"></a>Office.Security.SecureReaderHost.OpenInOSR

Seka atidarymo įvykdymą apsaugotame rodinyje. Skirtas nustatyti sąlygas, dėk kurių įvyko triktis atidarant failus apsaugotame rodinyje, bei kurios daro įtaką vartotojų saugumui ir produktyvumui.

Renkami šių laukų duomenys:

  - Nėra

## <a name="product-and-service-usage-data-events"></a>Produktų ir tarnybų duomenų naudojimo įvykiai

Toliau pateikiami šios kategorijos duomenų potipiai:

- [Taikomosios programos funkcijų sėkmingas atlikimas](#application-feature-success-subtype)
- [Taikomosios programos būsena ir įkrova](#application-status-and-boot-subtype)
- [„Office“ pritaikymo neįgaliesiems konfigūracija](#office-accessibility-configuration-subtype)
- [Privatumas](#privacy-subtype)


### <a name="application-feature-success-subtype"></a>*Taikomosios programos funkcijos sėkmingo atlikimo potipis*

Informacija apie tai, ar sėkmingai veikia programos funkcijos. Tik taikomosios programos ir dokumentų atidarymas ir uždarymas, failų redagavimas ir failų bendrinimas (bendradarbiavimas).

#### <a name="officeappcompatappcompatagentscanandupload"></a>Office.AppCompat.AppCompat.AgentScanAndUpload

Renkama tik kai galutinis vartotojas įgalina „Office“ telemetrijos ataskaitų sritį.Ji renka informaciją, kai „Office“ telemetrijos agentas yra įvykdytas.Informacija renkama tik tuo atveju, kai „Office“ telemetrijos ataskaitų sritis yra įjungta ir naudojama nustatyti „Office“ telemetrijos agento sveikatą.

Renkami šių laukų duomenys:

  - **Data.AgentExit** – telemetrijos agento sėkmingo uždarymo laiko žyma

  - **Data.AgentExit** – telemetrijos agento sėkmingo nuskaitymo atlikimo laiko žyma

  - **Data.AgentUpload** – telemetrijos agento sėkmingo įkėlimo atlikimo laiko žyma

#### <a name="officeappcompatappcompattelemetrydashboardresiliencycrashlog"></a>Office.AppCompat.AppCompat.TelemetryDashboardResiliencyCrashLog

Renkama tik kai „Office“ telemetrijos ataskaitų sritis yra įgalinta galutinio vartotojo (greičiausiai administratoriaus). Renka „Office“ papildinių ir dokumentų gedimų įvykius. Duomenys renkami tik tuo atveju, kai vartotojas įgalino „Office“ telemetrijos ataskaitų sritį ir naudoja nustatyti, ar yra padidėjo papildinių arba dokumentų gedimų įvykių.

Renkami šių laukų duomenys:

  - **Data.CollectionTime** – laiko žyma, kai buvo užregistruotas gedimo įvykis

#### <a name="officeconnectdeviceactivitystart"></a>Office.ConnectDevice.Activity.Start

Leidžia mums žinoti, ar buvo sėkmingai prisijungta prie įrenginio arba taikomosios programos.  Naudojama funkcijos sveikatai užtikrinti ir stebėti. Šis įvykis generuojamas „Microsoft“ srautinio duomenų siųstuvo, skirto „Excel“ papildiniui.

Renkami šių laukų duomenys:

- **Datasource_Type** – nuosekliojo įrenginio arba taikomosios programos tarnybos informacija

- **DataSource_Name** – prijungto duomenų šaltinio pavadinimas

- **Activity_Name** = „ConnectDevice“ veiklos pavadinimas

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

#### <a name="officeextensibilitycatalogexchangeprocessentitlement"></a>Office.Extensibility.Catalog.ExchangeProcessEntitlement

Atskirų teisių suteikimo apdorojimo ir „Office 365“ nuomotojo administratoriaus priskirto papildinio duomenys.

Naudoti kliento sėkmingų veiksmų diagramos sudaryme (prašomų komandos vadovų) ir klientų problemų analizėje.

Renkami šių laukų duomenys:

  - **AppVersion** – valdančiosios programos papildinio versija

  - **SolutionId –** GUID, nurodantis unikalų papildinį

  - **TelemetryId** – GUID, nurodantis unikalų vartotoją

#### <a name="officefileiocsiccachedfilecsiloadfilebasic"></a>Office.FileIO.CSI.CCachedFileCsiLoadFileBasic

Leidžia mums žinoti, ar failas iš FIO sluoksnio atidarytas sėkmingai. Naudojama funkcijos sveikatai užtikrinti ir stebėti.

Renkami šių laukų duomenys:

  - **Activity.Group –** žymė, leidžianti nustatyti stebimų įvykių rinkinį, grupuojamą sėkmingam atlikimui valdyti

  - **Activity.IsHVA –** žyma, nurodanti, kad įvykis yra kritinis vartotojų sėkmingiems veiksmams užtikrinti

  - **Data.AsyncOpen –** žyma, nurodanti, kad atidarymo metu buvo turinys, gautas po pagrindinės dalies atidarymo

  - **Data.CacheFileId –** prisijungia prie „Office“ dokumentų talpyklos telemetrijos, kad atliktų vartotojo patiriamų talpyklos problemų analizę

  - **Data.CoauthStatus –** informuoja apie dokumento bendradarbiavimo būseną atidarymo metu

  - **Data.CountOfMultiRoundTripsDownload –** kelionių į serverį ir atgal skaičius, naudotas veikimo triktims ir tinklo problemoms šalinti

  - **Data.CountOfMultiRoundTripsUpload –** kelionių į serverį ir atgal skaičius, naudotas našumo triktims ir tinklo problemoms šalinti

  - **Data.DialogId –** nustato, ar UI dialogo langas buvo rodomas atidarymo metu, nurodantis, kad įspėjimo pranešimas buvo rodomas vartotojui

  - **Data.DidFallbackToDAV –** nustato, ar dokumentas buvo atidarytas naudojant senesnį failų perdavimo protokolą

  - **Data.Doc.AccessMode –** dokumentas yra skirtas tik skaityti / redaguoti

  - **Data.Doc.AssistedReadingReasons –** nustato, ar dokumentas turi elektroninių duomenų apsaugą

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

  - **Data.Input.FileOpenState –** taikomosios programos (skaityti / skaityti ir rašyti, ir kt.) užklausta būsena **-**

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

  - **Data.IsSyncBackedStateDifferentThanOnLastOpen –** pasikeitė dokumento būsena, pakeitimai galėjo būti gauti kai dokumentas nebuvo atidarytas

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

  - **Data.WopiServiceId –** nebenaudojamas, pakeistas į Data\_Doc\_WopiServiceId

#### <a name="officefileiocsiccachedfilecsisavefilebasic"></a>Office.FileIO.CSI.CCachedFileCsiSaveFileBasic

Leidžia mums žinoti, ar failas iš FIO sluoksnio įrašytas sėkmingai. Naudojama funkcijos sveikatai užtikrinti ir stebėti.

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

  - **Data.DialogChoice –** įrašo pasirinkimą bet kuriuose klaidų dialogų languose

  - **Data.DialogId –** įrašo visus klaidų dialogų DialogId, rodomus įrašymo metu

  - **Data.Dmc.IsOcsSupported –** nebenaudojamas

  - **Data.Doc.AccessMode –** dokumentas yra skirtas tik skaityti

  - **Data.Doc.AssistedReadingReasons –** nustato, ar dokumentas turi elektroninių duomenų apsaugą

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

  - **Data.IsSyncBackedStateDifferentThanOnLastOpen –** pasikeitė dokumento būsena, pakeitimai galėjo būti gauti kai dokumentas nebuvo atidarytas

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

#### <a name="officeoutlookdesktopprovidersloadproviderlibrary"></a>Office.Outlook.Desktop.Providers.LoadProviderLibrary

Šis įvykis seka ar pavyko MAPI bandymas įkelti teikėjo DLL (pvz., contab32.dll, emsmdb32.dll, DLL naudojamą papildinio). MAPI operacija, atsakinga už tai, kad įkėlimo teikėjo DLL yra labai svarbūs „Outlook“ privalomiems veiksmams, bei išplėtimui (naudojant papildinius arba pasirinktinius parduotuvės / transportavimo / adresų knygos paslaugų teikėjus). Aktyviai stebime, ar pavyko ši operacija, kad užtikrinti, jog ši pagrindinė MAPI funkcija veikia kaip numatyta.

Renkami šių laukų duomenys:

  - **Standartinė HVA veikla**, kai nėra pasirinktinės apkrovos

#### <a name="officeoutlookdesktopstorescreatenewstore"></a>Office.Outlook.Desktop.Stores.CreateNewStore

Renka naujos parduotuvės (tipo ir versijos) sukūrimo rezultatą, bei rezultato kodą. Aktyviai stebime šį įvykį, kad sekti sveikatą vartotojo galimybės sinchronizuoti ir saugoti el. paštą kompiuteryje, archyvuoti el. laiškus (PST) ar naudoti „Groups“.

Renkami šių laukų duomenys:

  - **Standartinė HVA veikla** su pasirinktine apkrova

  - **StoreType** – parduotuvės, sukūrusios OST/PST/NST, tipas

  - **StoreVersion** – sukurtos mažos / didelės / „Tardis“ parduotuvės versija

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

  - **Data\_Doc\_ChunkingType:long –** kaip dokumentas saugomas programoje „SharePoint“

  - **Data\_Doc\_EdpState:long –** dokumento įmonės duomenų apsaugos būsena

  - **Data\_Doc\_Ext:string –** dokumento plėtinys

  - **Data\_Doc\_Extension:string –** dokumento plėtinys

  - **Data\_Doc\_FileFormat:long –** iš anksto nustatytų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

  - **Data\_Doc\_Fqdn:string –** vieta, kurioje saugomas dokumentas (SharePoint.com, live.net) galima tik „Office 365“ domenams

  - **Data\_Doc\_FqdnHash:string –** dokumento saugojimo vietos maiša

  - **Data\_Doc\_IdentityTelemetryId:string –** unikalus vartotojo GUID

  - **Data\_Doc\_IdentityUniqueId:string –** unikalus tapatybės identifikatorius, naudojamas veiksmui su bendrinamais dokumentais

  - **Data\_Doc\_IOFlags:long –** šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

  - **Data\_Doc\_IrmRights:long –** iš anksto nustatytų reikšmių, nurodančių kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool –** „true“, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

  - **Data\_Doc\_IsIncrementalOpen:bool –** ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

  - **Data\_Doc\_IsOcsSupported:bool –** ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

  - **Data\_Doc\_IsOpeningOfflineCopy:bool –** tikrina, ar dokumentas atidarytas iš vietinės talpyklos

  - **Data_Doc_IsRtcAlwaysOn –** „true“, jei šiam failui visada yra įjungtas realiojo laiko kanalas (RTC).

  - **Data\_Doc\_IsSyncBacked:bool –** tikrina, ar dokumentas atidarytas iš aplanko, naudojamo „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai

  - **Data\_Doc\_Location:long –** iš anksto apibrėžtų dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

  - **Data\_Doc\_LocationDetails:long –** iš anksto apibrėžtų išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

  - **Data\_Doc\_NumberCoAuthors:long –** bendraautorių skaičius dokumento atidarymo metu

  - **Data\_Doc\_PasswordFlags:long –** iš anksto apibrėžtų dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit) –

  - **Data\_Doc\_ReadOnlyReasons:long –** iš anksto apibrėžtų dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

  - **Data\_Doc\_ResourceIdHash:string –** debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data\_Doc\_ServerDocId:string –** debesyje saugomų dokumentų nekeičiamas identifikatorius

  - **Data\_Doc\_ServerProtocol:long –** iš anksto apibrėžtų protokolo naudojimas kreiptis į serverį reikšmių rinkinys (Http, „Cobalt“, WOPI ir kt.)

  - **Data\_Doc\_ServerType:long –** iš anksto apibrėžtų serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI)

  - **Data\_Doc\_ServerVersion:long –** tikrina, ar serveryje naudojama „Office14“, „Office15“ arba „Office 16“

  - **Data\_Doc\_SessionId:long –** generuotas GUID, identifikuojantis dokumento egzempliorių to paties proceso seanso metu

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

  - **Data\_IsDocAutoSaveable:bool –** ar pateiktis gali būti automatiškai įrašoma?

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

Surinkta, „PowerPoint“ naujos pateikties sukūrimo metu. Apima sėkmingą klaidos šalinimą ir našumo metrikas.

Ši informacija naudojama užtikrinti, kad galime sukurti failus sėkmingai, nemažinant našumo.

Renkami šių laukų duomenys:

  - **NewDocumentType** – ar naujas dokumentas sukurtas naudojant šabloną, ar sukurtas tik tuščias dokumentas?

  - **FLifeguarded** – dokumento apsauga (funkcija, atkurianti sugadintos būsenos dokumentą nepateikdami raginimo vartotojui)

#### <a name="officepowerpointdocoperationopencompleteprotocol"></a>Office.PowerPoint.DocOperation.OpenCompleteProtocol

Surinkta „PowerPoint“ atidarius pateiktis. Joje yra informacija, reikalinga tinkamai nustatyti ir diagnozuoti problemas, įvykusias atidarymo proceso baigiamosiose stadijose.

„Microsoft“ naudoja šiuos duomenis užtikrinti, jog funkcija veikia kaip numatyta ir pateikčių atidarymas nesuprastėjo.

Renkami šių laukų duomenys:

  - **Data\_AntiVirusScanMethod:long –** iš anksto apibrėžtas antivirusinės programos nuskaitymo tipo reikšmių rinkinys (IOAV, AMSI, None ir kt.)

  - **Data\_AntiVirusScanStatus:long –** iš anksto apibrėžtas antivirusinės programos nuskaitymo, atliekamo atidarant kiekvieną dokumentą, reikšmių rinkinys (NoThreatsDetected, Failed, MalwareDetected ir kt.)

  - **Data\_CloseAndReopen:bool –** ar šis dokumentas buvo uždarytas, ar pakartotinai atidarytas?

  - **Data\_DetachedDuration:long –** veiklos atskyrimo / neveikimo trukmė

  - **Data\_Doc\_AccessMode:long –** kaip šis dokumentas buvo atidarytas (tik skaityti | skaityti ir rašyti)

  - **Data\_Doc\_AssistedReadingReasons:long –** iš anksto apibrėžtų reikšmių, nurodančių dokumento atidarymo pagalbiniu skaitymo režimu priežastis, rinkinys

  - **Data\_Doc\_ChunkingType:long –** kaip dokumentas saugomas programoje „SharePoint“

  - **Data\_Doc\_EdpState:long –** dokumento įmonės duomenų apsaugos būsena

  - **Data\_Doc\_Ext:string –** dokumento plėtinys

  - **Data\_Doc\_Extension:string –** dokumento plėtinys

  - **Data\_Doc\_FileFormat:long –** iš anksto nustatytų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

  - **Data\_Doc\_Fqdn:string –** vieta, kurioje saugomas dokumentas (SharePoint.com, live.net) galima tik „Office 365“ domenams

  - **Data\_Doc\_FqdnHash:string –** dokumento saugojimo vietos maiša

  - **Data\_Doc\_IdentityTelemetryId:string –** unikalus vartotojo GUID

  - **Data\_Doc\_IdentityUniqueId:string –** unikalus tapatybės identifikatorius, naudojamas veiksmui su bendrinamais dokumentais

  - **Data\_Doc\_IOFlags:long –** šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

  - **Data\_Doc\_IrmRights:long –** iš anksto nustatytų reikšmių, nurodančių kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool –** „true“, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

  - **Data\_Doc\_IsIncrementalOpen:bool –** ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

  - **Data\_Doc\_IsOcsSupported:bool –** ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

  - **Data\_Doc\_IsOpeningOfflineCopy:bool -** Ar dokumentas atidarytas iš vietinės talpyklos?

  - **Data_Doc_IsRtcAlwaysOn –** „true“, jei šiam failui visada yra įjungtas realiojo laiko kanalas (RTC).

  - **Data\_Doc\_IsSyncBacked:bool –** ar dokumentas atidarytas iš aplanko, naudojančio „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai

  - **Data\_Doc\_Location:long –** iš anksto apibrėžtų dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

  - **Data\_Doc\_LocationDetails:long –** iš anksto apibrėžtų išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

  - **Data\_Doc\_NumberCoAuthors:long –** bendraautorių skaičius dokumento atidarymo metu

  - **Data\_Doc\_PasswordFlags:long –** iš anksto apibrėžtų dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit) –

  - **Data\_Doc\_ReadOnlyReasons:long –** iš anksto apibrėžtų dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

  - **Data\_Doc\_ResourceIdHash:string –** debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data\_Doc\_ServerDocId:string –** debesyje saugomų dokumentų nekeičiamas identifikatorius

  - **Data\_Doc\_ServerProtocol:long –** iš anksto apibrėžtų protokolo naudojimas kreiptis į serverį reikšmių rinkinys (Http, „Cobalt“, WOPI ir kt.)

  - **Data\_Doc\_ServerType:long –** iš anksto apibrėžtų serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI)

  - **Data\_Doc\_ServerVersion:long –** tikrina, ar serveryje naudojama „Office14“, „Office15“ arba „Office 16“

  - **Data\_Doc\_SessionId:long –** generuotas GUID, identifikuojantis dokumento egzempliorių to paties proceso seanso metu

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

  - **Data\_CommitTransactionTimeMS:long –** laikas, skirtas įrašymo operacijai atlikti

  - **Data\_CppUncaughtExceptionCount:long –** veiklos veikimo metu neaptiktos vietinės išimtys

  - **Data\_DetachedDuration:long –** veiklos atskyrimo / neveikimo trukmė

  - **Data\_Doc\_AccessMode:long –** kaip šis dokumentas buvo atidarytas (tik skaityti | skaityti ir rašyti)

  - **Data\_Doc\_AssistedReadingReasons:long –** iš anksto apibrėžtų reikšmių, nurodančių dokumento atidarymo pagalbiniu skaitymo režimu priežastis, rinkinys

  - **Data\_Doc\_ChunkingType:long –** kaip dokumentas saugomas programoje „SharePoint“

  - **Data\_Doc\_EdpState:long –** dokumento įmonės duomenų apsaugos būsena

  - **Data\_Doc\_Ext:string –** dokumento plėtinys

  - **Data\_Doc\_Extension:string –** dokumento plėtinys

  - **Data\_Doc\_FileFormat:long –** iš anksto nustatytų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

  - **Data\_Doc\_Fqdn:string –** vieta, kurioje saugomas dokumentas (SharePoint.com, live.net) galima tik „Office 365“ domenams

  - **Data\_Doc\_FqdnHash:string –** dokumento saugojimo vietos maiša

  - **Data\_Doc\_IdentityTelemetryId:string –** unikalus vartotojo GUID

  - **Data\_Doc\_IdentityUniqueId:string –** unikalus tapatybės identifikatorius, naudojamas veiksmui su bendrinamais dokumentais

  - **Data\_Doc\_IOFlags:long –** šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

  - **Data\_Doc\_IrmRights:long –** iš anksto nustatytų reikšmių, nurodančių kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool –** „true“, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

  - **Data\_Doc\_IsIncrementalOpen:bool –** ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

  - **Data\_Doc\_IsOcsSupported:bool –** ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

  - **Data\_Doc\_IsOpeningOfflineCopy:bool –** tikrina, ar dokumentas atidarytas iš vietinės talpyklos

  - **Data_Doc_IsRtcAlwaysOn –** „true“, jei šiam failui visada yra įjungtas realiojo laiko kanalas (RTC).

  - **Data\_Doc\_IsSyncBacked:bool –** ar dokumentas atidarytas iš aplanko, naudojančio „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai

  - **Data\_Doc\_Location:long –** iš anksto apibrėžtų dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

  - **Data\_Doc\_LocationDetails:long –** iš anksto apibrėžtų išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

  - **Data\_Doc\_NumberCoAuthors:long –** bendraautorių skaičius dokumento atidarymo metu

  - **Data\_Doc\_PasswordFlags:long –** iš anksto apibrėžtų dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit)

  - **Data\_Doc\_ReadOnlyReasons:long –** iš anksto apibrėžtų dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

  - **Data\_Doc\_ResourceIdHash:string –** debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data\_Doc\_ServerDocId:string –** debesyje saugomų dokumentų nekeičiamas identifikatorius

  - **Data\_Doc\_ServerProtocol:long –** iš anksto apibrėžtų protokolo naudojimas kreiptis į serverį reikšmių rinkinys (Http, „Cobalt“, WOPI ir kt.)

  - **Data\_Doc\_ServerType:long –** iš anksto apibrėžtų serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI)

  - **Data\_Doc\_ServerVersion:long –** tikrina, ar serveryje naudojama „Office14“, „Office15“ arba „Office 16“

  - **Data\_Doc\_SessionId:long –** generuotas GUID, identifikuojantis dokumento egzempliorių to paties proceso seanso metu

  - **Data\_Doc\_SharePointServiceContext:string –** nepermatoma eilutė, paprastai GridManagerID.FarmID. Tinkanti kliento ir serverio įvykių žurnalų koreliacijai

  - **Data\_Doc\_SizeInBytes:long –** dokumento dydis baitais

  - **Data\_Doc\_SpecialChars:long –** šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

  - **Data\_Doc\_StorageProviderId:string –** eilutė, nurodanti dokumento saugyklos teikėją, pvz., „DropBox“

  - **Data\_Doc\_StreamAvailability:long –** iš anksto apibrėžtų dokumentų srauto būsenos reikšmių rinkinys (available, permanently disabled, not available)

  - **Data\_Doc\_UrlHash:string –** debesyje saugomų dokumentų visų URL maiša

  - **Data\_Doc\_UsedWrsDataOnOpen:bool –** „true“, jei failas buvo atidarytas palaipsniui naudojant iš anksto pagrindinio kompiuterio talpykloje saugomus WRS duomenis

  - **Data\_Doc\_WopiServiceId:string –** WOPI tarnybos identifikatorius, pvz., „Dropbox“

  - **Data\_DurationUAEOnSaveStartedMs:long –** laikas, skirtas nežinomai taikomajai programai išjungti įrašymo metu

  - **Data\_EnsureSaveTransactionTimeMS:long –** laikas, skirtas įrašymo operacijos sukūrimui užtikrinti, jeigu jos nėra

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

Surinkti kiekvieną kartą, kai „PowerPoint“ atlieka operaciją įrašyti kaip. Apima sėkmingai arba nesėkmingai atlikto našumo metrikų ir susijusio dokumento metaduomenų įrašymo rezultato tipą. Nepavykus įrašymui, duomenys gali būti prarasti.

„Microsoft“ naudoja šiuos duomenis, kad užtikrintų, jog funkcija veikia kaip priklauso ir vartotojo turinys yra sėkmingai išlaikomas.

Renkami šių laukų duomenys:

  - **Data\_AddDocTelemetryResult:long –** ar šis žurnalo įrašas turi visą reikiamą dokumento telemetriją (Data\_Doc\_\* laukus)? Jei ne, kodėl?

  - **Data\_CppUncaughtExceptionCount:long –** veiklos veikimo metu neaptiktos vietinės išimtys

  - **Data\_DetachedDuration:long –** veiklos atskyrimo / neveikimo trukmė

  - **Data\_DstDoc\_AccessMode:long –** kaip šis dokumentas buvo atidarytas (tik skaityti | skaityti ir rašyti)

  - **Data\_DstDoc\_AccessMode:long –** iš anksto apibrėžtų reikšmių, nurodančių dokumento atidarymo pagalbiniu skaitymo režimu priežastis, rinkinys

  - **Data\_DstDoc\_ChunkingType:long –** kaip dokumentas saugomas programoje „SharePoint“

  - **Data\_DstDoc\_EdpState:long –** dokumento įmonės duomenų apsaugos būsena

  - **Data\_DstDoc\_Ext:string –** dokumento plėtinys

  - **Data\_DstDoc\_Extension:string –** dokumento plėtinys

  - **Data\_DstDoc\_FileFormat:long –** iš anksto nustatytų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

  - **Data\_DstDoc\_Fqdn:string –** vieta, kurioje saugomas dokumentas (SharePoint.com, live.net) galima tik „Office 365“ domenams

  - **Data\_DstDoc\_FqdnHash:string –** dokumento saugojimo vietos maiša

  - **Data\_DstDoc\_IdentityTelemetryId:string –** unikalus vartotojo GUID

  - **Data\_DstDoc\_IdentityUniqueId:string –** unikalus tapatybės identifikatorius, naudojamas veiksmui su bendrinamais dokumentais

  - **Data\_DstDoc\_IOFlags:long –** šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

  - **Data\_DstDoc\_IrmRights:long –** iš anksto nustatytų reikšmių, nurodančių kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)

  - **Data\_DstDoc\_IsCloudCollabEnabled:bool –** „true“, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

  - **Data\_DstDoc\_IsIncrementalOpen:bool –** ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

  - **Data\_DstDoc\_IsOcsSupported:bool –** ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

  - **Data\_DstDoc\_IsOpeningOfflineCopy:bool –** tikrina, ar dokumentas atidarytas iš vietinės talpyklos

  - **Data\_DstDoc\_IsSyncBacked:bool –** ar dokumentas atidarytas iš aplanko, naudojančio „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai

  - **Data\_DstDoc\_Location:long –** iš anksto apibrėžtų dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

  - **Data\_DstDoc\_LocationDetails:long –** iš anksto apibrėžtų išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

  - **Data\_DstDoc\_NumberCoAuthors:long –** bendraautorių skaičius dokumento atidarymo metu

  - **Data\_DstDoc\_PasswordFlags:long –** iš anksto apibrėžtų dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit)

  - **Data\_DstDoc\_ReadOnlyReasons:long –** iš anksto apibrėžtų dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

  - **Data\_DstDoc\_ResourceIdHash:string –** debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data\_DstDoc\_ServerDocId:string –** debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data\_DstDoc\_ServerProtocol:long –** iš anksto apibrėžtų reikšmių, nurodančių kuris protokolas naudojamas kreiptis į serverį, rinkinys (Http, „Cobalt“, WOPI ir kt.)

  - **Data\_DstDoc\_ServerType:long –** iš anksto apibrėžtų serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI)

  - **Data\_DstDoc\_ServerVersion:long –** tikrina, ar serveryje naudojama „Office14“, „Office15“ arba „Office 16“

  - **Data\_DstDoc\_SessionId:long –** generuotas GUID, identifikuojantis dokumento egzempliorių to paties proceso seanso metu

  - **Data\_DstDoc\_SharePointServiceContext:string –** nepermatoma eilutė, paprastai GridManagerID.FarmID. Tinkanti kliento ir serverio įvykių žurnalų koreliacijai

  - **Data\_DstDoc\_SizeInBytes:long –** dokumento dydis baitais

  - **Data\_DstDoc\_SpecialChars:long –** šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

  - **Data\_DstDoc\_StorageProviderId:string –** eilutė, nurodanti dokumento saugyklos teikėją, pvz., „DropBox“

  - **Data\_DstDoc\_StreamAvailability:long –** iš anksto apibrėžtų dokumentų srauto būsenos reikšmių rinkinys (available, permanently disabled, not available)

  - **Data\_DstDoc\_UrlHash:string –** debesyje saugomų dokumentų visų URL maiša

  - **Data\_DstDoc\_UsedWrsDataOnOpen:bool –** „true“, jei failas buvo atidarytas palaipsniui naudojant iš anksto pagrindinio kompiuterio talpykloje saugomus WRS duomenis

  - **Data\_DstDoc\_WopiServiceId:string –** WOPI tarnybos identifikatorius, pvz., „Dropbox“

  - **Data\_FileType:long –** iš anksto apibrėžtas failo vidinio tipo reikšmių rinkinys

  - **Data\_fLifeguarded:bool –** ar kada dokumentui buvo naudojama apsauginė funkcija (funkcija, automatiškai taisanti dokumento klaidas nepranešant vartotojui)?

  - **Data\_FWebCreated:bool –** ar šiame dokumente yra WebCreator žymė?

  - **Data\_SaveReason:long –** iš anksto apibrėžtas reikšmių, nurodančių įrašymo atlikimo priežastis, rinkinys (AutoSave, ToOCSTransitionSave, ToCSITransitionSave ir kt.)

  - **Data\_SaveType:long –** iš anksto nustatytų įrašymo tipo reikšmių rinkinys (SaveAs, Publish, Manual, OMSave ir kt.)

  - **Data\_SrcDoc\_AccessMode:long –** kaip šis dokumentas buvo atidarytas (tik skaityti | skaityti ir rašyti)

  - **Data\_SrcDoc\_AssistedReadingReasons:long –** iš anksto apibrėžtų reikšmių, nurodančių dokumento atidarymo pagalbiniu skaitymo režimu priežastis, rinkinys

  - **Data\_SrcDoc\_ChunkingType:long –** kaip dokumentas saugomas programoje „SharePoint“

  - **Data\_SrcDoc\_EdpState:long –** dokumento įmonės duomenų apsaugos būsena

  - **Data\_SrcDoc\_Ext:string –** dokumento plėtinys

  - **Data\_SrcDoc\_Extension:string –** dokumento plėtinys

  - **Data\_SrcDoc\_FileFormat:long –** iš anksto apibrėžtų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

  - **Data\_SrcDoc\_Fqdn:string –** vieta, kurioje saugomas dokumentas (SharePoint.com, live.net) galima tik „Office 365“ domenams

  - **Data\_SrcDoc\_FqdnHash:string –** dokumento saugojimo vietos maiša

  - **Data\_SrcDoc\_IdentityTelemetryId:string –** unikalus vartotojo GUID

  - **Data\_SrcDoc\_IdentityUniqueId:string –** unikalus tapatybės identifikatorius, naudojamas veiksmui su bendrinamais dokumentais

  - **Data\_SrcDoc\_IOFlags:long –** šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

  - **Data\_SrcDoc\_IrmRights:long –** iš anksto apibrėžtų reikšmių, nurodančių kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)

  - **Data\_SrcDoc\_IsCloudCollabEnabled:bool –** „true“, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

  - **Data\_SrcDoc\_IsIncrementalOpen:bool –** ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

  - **Data\_SrcDoc\_IsOcsSupported:bool –** ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

  - **Data\_SrcDoc\_IsOpeningOfflineCopy:bool –** tikrina, ar dokumentas atidarytas iš vietinės talpyklos

  - **Data\_SrcDoc\_IsSyncBacked:bool –** ar dokumentas atidarytas iš aplanko, naudojančio „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai

  - **Data\_SrcDoc\_Location:long –** iš anksto apibrėžtų dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

  - **Data\_SrcDoc\_LocationDetails:long –** iš anksto apibrėžtų išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

  - **Data\_SrcDoc\_NumberCoAuthors:long –** bendraautorių skaičius dokumento atidarymo metu

  - **Data\_SrcDoc\_PasswordFlags:long –** iš anksto apibrėžtų dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit) –

  - **Data\_SrcDoc\_ReadOnlyReasons:long –** iš anksto apibrėžtų dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

  - **Data\_SrcDoc\_ResourceIdHash:string –** debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data\_SrcDoc\_ServerDocId:string –** debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data\_SrcDoc\_ServerProtocol:long –** iš anksto apibrėžtų reikšmių, nurodančių kuris protokolas naudojamas kreiptis į serverį, rinkinys (Http, „Cobalt“, WOPI ir kt.)

  - **Data\_SrcDoc\_ServerType:long –** iš anksto apibrėžtų serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI)

  - **Data\_SrcDoc\_ServerVersion:long –** patikrina, ar serveryje naudojama „Office14“, „Office15“ arba „Office16“ Data\_SrcDoc\_SessionId:long sukurtas GUID, identifikuojantis dokumento egzempliorių tame pačiame proceso seanse

  - **Data\_SrcDoc\_SharePointServiceContext:string –** nepermatoma eilutė, paprastai GridManagerID.FarmID. Tinkanti kliento ir serverio įvykių žurnalų koreliacijai

  - **Data\_SrcDoc\_SizeInBytes:long –** dokumento dydis baitais

  - **Data\_SrcDoc\_SpecialChars:long –** šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

  - **Data\_SrcDoc\_StorageProviderId:string –** eilutė, nurodanti dokumento saugyklos teikėją, pvz., „DropBox“

  - **Data\_SrcDoc\_StreamAvailability:long –** iš anksto apibrėžtų dokumentų srauto būsenos reikšmių rinkinys (available, permanently disabled, not available)

  - **Data\_SrcDoc\_UrlHash:string –** debesyje saugomų dokumentų visų URL maiša

  - **Data\_SrcDoc\_UsedWrsDataOnOpen:bool –** „true“, jei failas buvo atidarytas palaipsniui naudojant iš anksto pagrindinio kompiuterio talpykloje saugomus WRS duomenis

  - **Data\_SrcDoc\_WopiServiceId:string –** WOPI tarnybos identifikatorius, pvz., „Dropbox“

  - **Data\_StopwatchDuration:long –** visas veiklos laikas

  - **Data\_TypeOfSaveDialog:long –** iš anksto apibrėžtų dialogo lango reikšmių rinkinys (RUN\_SAVEAS\_DLG, RUN\_SAVEMEDIA\_DLG, RUN\_SAVEAS\_VIDEO\_DLG ir kt.)

  - **DstDoc –** nauja dokumento vieta

  - **SrcDoc –** pradinė dokumento vieta

#### <a name="officepowerpointdocoperationsavelegacy"></a>Office.PowerPoint.DocOperation.SaveLegacy

Surinkti kiekvieną kartą, kai „PowerPoint“ įrašo naudodama senesnį kodo kelią. Apima sėkmingai arba nesėkmingai atlikto našumo metrikų ir susijusio dokumento metaduomenų įrašymo rezultato tipą. Nepavykus įrašymui, duomenys gali būti prarasti. „Microsoft“ naudoja šiuos duomenis, kad užtikrintų, jog funkcija veikia kaip priklauso ir vartotojo turinys yra sėkmingai išlaikomas.

Renkami šių laukų duomenys:

  - **Data\_AddDocTelemetryResult:long –** ar šis žurnalo įrašas turi visą reikiamą dokumento telemetriją (Data\_Doc\_\* laukus)? Jei ne, kodėl?

  - **Data\_CppUncaughtExceptionCount:long –** veiklos veikimo metu neaptiktos vietinės išimtys

  - **Data\_DetachedDuration:long –** veiklos atskyrimo / neveikimo trukmė

  - **Data\_Doc\_AccessMode:long –** kaip šis dokumentas buvo atidarytas (tik skaityti | skaityti ir rašyti)

  - **Data\_Doc\_AssistedReadingReasons:long –** iš anksto apibrėžtų reikšmių, nurodančių dokumento atidarymo pagalbiniu skaitymo režimu priežastis, rinkinys

  - **Data\_Doc\_ChunkingType:long –** kaip dokumentas saugomas programoje „SharePoint“

  - **Data\_Doc\_EdpState:long –** dokumento įmonės duomenų apsaugos būsena

  - **Data\_Doc\_Ext:string –** dokumento plėtinys

  - **Data\_Doc\_Extension:string –** dokumento plėtinys

  - **Data\_Doc\_FileFormat:long –** iš anksto nustatytų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

  - **Data\_Doc\_Fqdn:string –** vieta, kurioje saugomas dokumentas (SharePoint.com, live.net) galima tik „Office 365“ domenams

  - **Data\_Doc\_FqdnHash:string –** dokumento saugojimo vietos maiša

  - **Data\_Doc\_IdentityTelemetryId:string –** unikalus vartotojo GUID

  - **Data\_Doc\_IdentityUniqueId:string –** unikalus tapatybės identifikatorius, naudojamas veiksmui su bendrinamais dokumentais

  - **Data\_Doc\_IOFlags:long –** šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

  - **Data\_Doc\_IrmRights:long –** iš anksto nustatytų reikšmių, nurodančių kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool –** „true“, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

  - **Data\_Doc\_IsIncrementalOpen:bool –** ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

  - **Data\_Doc\_IsOcsSupported:bool –** ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

  - **Data\_Doc\_IsOpeningOfflineCopy:bool –** tikrina, ar dokumentas atidarytas iš vietinės talpyklos

  - **Data_Doc_IsRtcAlwaysOn –** „true“, jei šiam failui visada yra įjungtas realiojo laiko kanalas (RTC).

  - **Data\_Doc\_IsSyncBacked:bool –** ar dokumentas atidarytas iš aplanko, naudojančio „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai

  - **Data\_Doc\_Location:long –** iš anksto apibrėžtų dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

  - **Data\_Doc\_LocationDetails:long –** iš anksto apibrėžtų išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

  - **Data\_Doc\_NumberCoAuthors:long –** bendraautorių skaičius dokumento atidarymo metu

  - **Data\_Doc\_PasswordFlags:long –** iš anksto apibrėžtų dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit)

  - **Data\_Doc\_ReadOnlyReasons:long –** iš anksto apibrėžtų dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

  - **Data\_Doc\_ResourceIdHash:string –** debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data\_Doc\_ServerDocId:string –** debesyje saugomų dokumentų nekeičiamas identifikatorius

  - **Data\_Doc\_ServerProtocol:long –** iš anksto apibrėžtų protokolo naudojimas kreiptis į serverį reikšmių rinkinys (Http, „Cobalt“, WOPI ir kt.)

  - **Data\_Doc\_ServerType:long –** iš anksto apibrėžtų serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI)

  - **Data\_Doc\_ServerVersion:long –** tikrina, ar serveryje naudojama „Office14“, „Office15“ arba „Office 16“

  - **Data\_Doc\_SessionId:long –** generuotas GUID, identifikuojantis dokumento egzempliorių to paties proceso seanso metu

  - **Data\_Doc\_SharePointServiceContext:string –** nepermatoma eilutė, paprastai GridManagerID.FarmID. Tinkanti kliento ir serverio įvykių žurnalų koreliacijai

  - **Data\_Doc\_SizeInBytes:long –** dokumento dydis baitais

  - **Data\_Doc\_SpecialChars:long –** šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

  - **Data\_Doc\_StorageProviderId:string –** eilutė, nurodanti dokumento saugyklos teikėją, pvz., „DropBox“

  - **Data\_Doc\_StreamAvailability:long –** iš anksto apibrėžtų dokumentų srauto būsenos reikšmių rinkinys (available, permanently disabled, not available)

  - **Data\_Doc\_UrlHash:string –** debesyje saugomų dokumentų visų URL maiša

  - **Data\_Doc\_UsedWrsDataOnOpen:bool –** „true“, jei failas buvo atidarytas palaipsniui naudojant iš anksto pagrindinio kompiuterio talpykloje saugomus WRS duomenis

  - **Data\_Doc\_WopiServiceId:string –** WOPI tarnybos identifikatorius, pvz., „Dropbox“

  - **Data\_DstDoc\_AccessMode:long –** kaip šis dokumentas buvo atidarytas (tik skaityti | skaityti ir rašyti)

  - **Data\_DstDoc\_AccessMode:long –** iš anksto apibrėžtų reikšmių, nurodančių dokumento atidarymo pagalbiniu skaitymo režimu priežastis, rinkinys

  - **Data\_DstDoc\_ChunkingType:long –** kaip dokumentas saugomas programoje „SharePoint“

  - **Data\_DstDoc\_EdpState:long –** dokumento įmonės duomenų apsaugos būsena

  - **Data\_DstDoc\_Ext:string –** dokumento plėtinys

  - **Data\_DstDoc\_Extension:string –** dokumento plėtinys

  - **Data\_DstDoc\_FileFormat:long –** iš anksto nustatytų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

  - **Data\_DstDoc\_Fqdn:string –** vieta, kurioje saugomas dokumentas (SharePoint.com, live.net) galima tik „Office 365“ domenams

  - **Data\_DstDoc\_FqdnHash:string –** dokumento saugojimo vietos maiša

  - **Data\_DstDoc\_IdentityTelemetryId:string –** unikalus vartotojo GUID

  - **Data\_DstDoc\_IdentityUniqueId:string –** unikalus tapatybės identifikatorius, naudojamas veiksmui su bendrinamais dokumentais

  - **Data\_DstDoc\_IOFlags:long –** šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

  - **Data\_DstDoc\_IrmRights:long –** iš anksto nustatytų reikšmių, nurodančių kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)

  - **Data\_DstDoc\_IsCloudCollabEnabled:bool –** „true“, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

  - **Data\_DstDoc\_IsIncrementalOpen:bool –** ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

  - **Data\_DstDoc\_IsOcsSupported:bool –** ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

  - **Data\_DstDoc\_IsOpeningOfflineCopy:bool –** tikrina, ar dokumentas atidarytas iš vietinės talpyklos

  - **Data\_DstDoc\_IsSyncBacked:bool –** ar dokumentas atidarytas iš aplanko, naudojančio „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai

  - **Data\_DstDoc\_Location:long –** iš anksto apibrėžtų dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

  - **Data\_DstDoc\_LocationDetails:long –** iš anksto apibrėžtų išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

  - **Data\_DstDoc\_NumberCoAuthors:long –** bendraautorių skaičius dokumento atidarymo metu

  - **Data\_DstDoc\_PasswordFlags:long –** iš anksto apibrėžtų dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit)

  - **Data\_DstDoc\_ReadOnlyReasons:long –** iš anksto apibrėžtų dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

  - **Data\_DstDoc\_ResourceIdHash:string –** debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data\_DstDoc\_ServerDocId:string –** debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data\_DstDoc\_ServerProtocol:long –** iš anksto apibrėžtų reikšmių, nurodančių kuris protokolas naudojamas kreiptis į serverį, rinkinys (Http, „Cobalt“, WOPI ir kt.)

  - **Data\_DstDoc\_ServerType:long –** iš anksto apibrėžtų serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI)

  - **Data\_DstDoc\_ServerVersion:long –** tikrina, ar serveryje naudojama „Office14“, „Office15“ arba „Office 16“

  - **Data\_DstDoc\_SessionId:long –** generuotas GUID, identifikuojantis dokumento egzempliorių to paties proceso seanso metu

  - **Data\_DstDoc\_SharePointServiceContext:string –** nepermatoma eilutė, paprastai GridManagerID.FarmID. Tinkanti kliento ir serverio įvykių žurnalų koreliacijai

  - **Data\_DstDoc\_SizeInBytes:long –** dokumento dydis baitais

  - **Data\_DstDoc\_SpecialChars:long –** šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

  - **Data\_DstDoc\_StorageProviderId:string –** eilutė, nurodanti dokumento saugyklos teikėją, pvz., „DropBox“

  - **Data\_DstDoc\_StreamAvailability:long –** iš anksto apibrėžtų dokumentų srauto būsenos reikšmių rinkinys (available, permanently disabled, not available)

  - **Data\_DstDoc\_UrlHash:string –** debesyje saugomų dokumentų visų URL maiša

  - **Data\_DstDoc\_UsedWrsDataOnOpen:bool –** „true“, jei failas buvo atidarytas palaipsniui naudojant iš anksto pagrindinio kompiuterio talpykloje saugomus WRS duomenis

  - **Data\_DstDoc\_WopiServiceId:string –** WOPI tarnybos identifikatorius, pvz., „Dropbox“

  - **Data\_FileType:long –** iš anksto apibrėžtas failo vidinio tipo reikšmių rinkinys

  - **Data\_fLifeguarded:bool –** ar kada dokumentui buvo naudojama apsauginė funkcija (funkcija, automatiškai taisanti dokumento klaidas nepranešant vartotojui)?

  - **Data\_SaveReason:long –** iš anksto apibrėžtas reikšmių, nurodančių įrašymo atlikimo priežastis, rinkinys (AutoSave, ToOCSTransitionSave, ToCSITransitionSave ir kt.)

  - **Data\_SaveType:long –** iš anksto nustatytų įrašymo tipo reikšmių rinkinys (SaveAs, Publish, Manual, OMSave ir kt.)

  - **Data\_SrcDoc\_AccessMode:long –** kaip šis dokumentas buvo atidarytas (tik skaityti | skaityti ir rašyti)

  - **Data\_SrcDoc\_AssistedReadingReasons:long –** iš anksto apibrėžtų reikšmių, nurodančių dokumento atidarymo pagalbiniu skaitymo režimu priežastis, rinkinys

  - **Data\_SrcDoc\_ChunkingType:long –** kaip dokumentas saugomas programoje „SharePoint“

  - **Data\_SrcDoc\_EdpState:long –** dokumento įmonės duomenų apsaugos būsena

  - **Data\_SrcDoc\_Ext:string –** dokumento plėtinys

  - **Data\_SrcDoc\_Extension:string –** dokumento plėtinys

  - **Data\_SrcDoc\_FileFormat:long –** iš anksto apibrėžtų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

  - **Data\_SrcDoc\_Fqdn:string –** vieta, kurioje saugomas dokumentas (SharePoint.com, live.net) galima tik „Office 365“ domenams

  - **Data\_SrcDoc\_FqdnHash:string –** dokumento saugojimo vietos maiša

  - **Data\_SrcDoc\_IdentityTelemetryId:string –** unikalus vartotojo GUID

  - **Data\_SrcDoc\_IdentityUniqueId:string –** unikalus tapatybės identifikatorius, naudojamas veiksmui su bendrinamais dokumentais

  - **Data\_SrcDoc\_IOFlags:long –** šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

  - **Data\_SrcDoc\_IrmRights:long –** iš anksto apibrėžtų reikšmių, nurodančių kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)

  - **Data\_SrcDoc\_IsCloudCollabEnabled:bool –** „true“, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

  - **Data\_SrcDoc\_IsIncrementalOpen:bool –** ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

  - **Data\_SrcDoc\_IsOcsSupported:bool –** ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

  - **Data\_SrcDoc\_IsOpeningOfflineCopy:bool –** tikrina, ar dokumentas atidarytas iš vietinės talpyklos

  - **Data\_SrcDoc\_IsSyncBacked:bool –** ar dokumentas atidarytas iš aplanko, naudojančio „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai

  - **Data\_SrcDoc\_Location:long –** iš anksto apibrėžtų dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

  - **Data\_SrcDoc\_LocationDetails:long –** iš anksto apibrėžtų išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

  - **Data\_SrcDoc\_NumberCoAuthors:long –** bendraautorių skaičius dokumento atidarymo metu

  - **Data\_SrcDoc\_PasswordFlags:long –** iš anksto apibrėžtų dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit)

  - **Data\_SrcDoc\_ReadOnlyReasons:long –** iš anksto apibrėžtų dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

  - **Data\_SrcDoc\_ResourceIdHash:string –** debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data\_SrcDoc\_ServerDocId:string –** debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data\_SrcDoc\_ServerProtocol:long –** iš anksto apibrėžtų reikšmių, nurodančių kuris protokolas naudojamas kreiptis į serverį, rinkinys (Http, „Cobalt“, WOPI ir kt.)

  - **Data\_SrcDoc\_ServerType:long –** iš anksto apibrėžtų serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI)

  - **Data\_SrcDoc\_ServerVersion:long –** tikrina, ar serveryje naudojama „Office14“, „Office15“ arba „Office 16“

  - **Data\_SrcDoc\_SessionId:long –** generuotas GUID, identifikuojantis dokumento egzempliorių to paties proceso seanso metu

  - **Data\_SrcDoc\_SharePointServiceContext:string –** nepermatoma eilutė, paprastai GridManagerID.FarmID. Tinkanti kliento ir serverio įvykių žurnalų koreliacijai

  - **Data\_SrcDoc\_SizeInBytes:long –** dokumento dydis baitais

  - **Data\_SrcDoc\_SpecialChars:long –** šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

  - **Data\_SrcDoc\_StorageProviderId:string –** eilutė, nurodanti dokumento saugyklos teikėją, pvz., „DropBox“

  - **Data\_SrcDoc\_StreamAvailability:long –** iš anksto apibrėžtų dokumentų srauto būsenos reikšmių rinkinys (available, permanently disabled, not available)

  - **Data\_SrcDoc\_UrlHash:string –** debesyje saugomų dokumentų visų URL maiša

  - **Data\_SrcDoc\_UsedWrsDataOnOpen:bool –** „true“, jei failas buvo atidarytas palaipsniui naudojant iš anksto pagrindinio kompiuterio talpykloje saugomus WRS duomenis

  - **Data\_SrcDoc\_WopiServiceId:string –** WOPI tarnybos identifikatorius, pvz., „Dropbox“

  - **Data\_StopwatchDuration:long –** visas veiklos laikas

  - **Data\_TypeOfSaveDialog:long –** iš anksto apibrėžtų dialogo lango reikšmių rinkinys (RUN\_SAVEAS\_DLG, RUN\_SAVEMEDIA\_DLG, RUN\_SAVEAS\_VIDEO\_DLG ir kt.)

  - **Doc –** dabartinis dokumentas įrašymui

  - **DstDoc –** nauja dokumento vieta (kai naudojama funkcija SaveAs)

  - **SrcDoc –** pirminė dokumento vieta (kai naudojama funkcija SaveAs)

#### <a name="officepowerpointpptsharedslideshowfailure"></a>Office.PowerPoint.PPT.Shared.SlideShow.Failure

Triktys renkamos skaidrių demonstravimo metu. Skaidrių demonstravimas yra pagrindinė „PowerPoint“ funkcija. „Microsoft“ skaidrių demonstravimo metu renka informaciją apie klaidos įvykimą, kad padėtų tobulinti naudotojo patirtį skaidrių demonstravimo metu. „Microsoft“ šiuos duomenis naudoja gauti diagnostinę informaciją apie tai, kur su klaida įvyksta, kai vartotojas naudoja skaidrių demonstravimą

Renkami šių laukų duomenys:

  - **CountSlideShowErrors** – bendrą skaidrių demonstravimo klaidų skaičius

  - **CountPPTErrors** – bendras PPT klaidų skaičius

  - **CountOArtErrors** – bendras OArt klaidų skaičius

  - **CountOtherErrors** – bendras kitų klaidų skaičius

  - **FirstSlideShowError** – pirma klaida įvykusi skaidrių demonstravimo metu

  - **FirstOArtError** – pirma klaida įvykusi OArt

  - **FirstPPTError** – pirma klaida įvykusi PPT

  - **FirstOtherError** – pirma klaida įvykusi kitoje srityje

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

  - **Data.actionSource –** kaip buvo paleistas vertimas

  - **Data.bodyBackgroundColor –** „Office“ temos konteinerio fono spalva –

  - **Data.bodyForegroundColor –** „Office“ temos konteinerio priekinio plano spalva –

  - **Data.browserLang –** dabartinė naršyklės rodoma kalba –

  - **Data.browserOnline –** nebenaudojamas –

  - **Data.browserPlatform –** naršyklės platforma –

  - **Data.browserUserAgent –** naršyklės vartotojo agentas –

  - **Data.colorDepth –** sistemos spalvos gylis –

  - **Data.contentLanguage –** aptikta verstino turinio kalba –

  - **Data.controlBackgroundColor –** „Office“ temos valdiklio fono spalva –

  - **Data.controlBackgroundColor –** „Office“ temos valdiklio priekinio plano spalva –

  - **Data.correlationId –** tarnybai siųstos užklausos unikalus identifikatorius –

  - **Data.crossSessionId –** unikalus vartotojo identifikatorius –

  - **Data.crossSessionStartTime –** vertimo seanso pradžios UTC laiko žyma –

  - **Data.currentTime –** telemetrijos laiko pranešimos UTC laiko žyma –

  - **Data.displayLanguage –** rodoma „Office“ kalba –

  - **Data.documentSourceLang –** dokumento turinio kalba –

  - **Data.documentTargetLang –** kalba, į kurią bus išverstas dokumentas –

  - **Data.Environment –** tarnybos aplinka, kuriai išsiųsta užklausa –

  - **Data.errorMessage –** tarnybos pateiktas klaidos pranešimas –

  - **Data.eventActionType –** telemetrijos įvykio tipas –

  - **Data.eventTagId –** kodo eilutės, sukūrusios šį telemetrijos pranešimą, unikalus identifikatorius

  - **TestuojamoVarianto.Duomenys –** įgalinti testuojami variantai –

  - **Data.fileSize –** „Word“ failo, skirto versti, dydis –

  - **Data.fileSource –** „Word“ failo laikymo vieta (offline, online) –

  - **Data.fileType –** „Word“ failo plėtinys –

  - **Data.innerHeight"–** šoninės srities konteinerio aukštis –

  - **Data.innerWidth"–** šoninės srities konteinerio plotis –

  - **Data.lookupSourceLang –** nenaudojama dokumentui versti –

  - **Data.lookupTargetLang –** nenaudojama dokumentui versti –

  - **Data.officeHost –** „Office“ taikomoji programa, esanti šoninėje srityje –

  - **Data.officeLocale –** vartotojo „Office“ kalba –

  - **Data.officeMachineId –** unikalus įrenginio identifikatorius –

  - **Data.officePlatform –** įrenginio platforma –

  - **Data.officeSessionId –** „Office“ seanso identifikatorius –

  - **Data.officeUserId –** „Office“ vartotojo unikalus identifikatorius –

  - **Data.officeVersion –** „Office“ versija –

  - **Data.pageXOffset –** kairėje šoninėje srityje esančios šoninės srities horizontalios slinkties padėtis –

  - **Data.pageYOffset –** viršutinėje šoninėje srityje esančios šoninės srities vertikalios slinkties padėtis –

  - **Data.pixelDepth –** ekrano spalvų skiriamoji geba –

  - **Data.responseCode –** HTTP atsakymo iš tarnybos kodas –

  - **Data.responseTime –** praėjęs užklausos laikas –

  - **Data.resultType –** užklausos rezultatas –

  - **Data.screenHeight –** ekrano aukštis pikseliais –

  - **Data.screenLeft –** lango horizontali koordinatė ekrano atžvilgiu –

  - **Data.screenTop –** lango vertikali koordinatė ekrano atžvilgiu –

  - **Data.screenWidth –** ekrano plotis pikseliais –

  - **Data.selectedTab –** pasirinktas skirtukas: Selection arba Document -

  - **Data.serverUrl –** vertimo tarnybos URL –

  - **Data.sessionId –** šoninės srities seanso identifikatorius –

  - **Data.sessionStartTime –** vertimo seanso pradžios UTC laiko žyma –

  - **Data.sourceTextHash –** verstino teksto maiša –

  - **Data.sourceTextLength –** verstino teksto ilgis –

  - **Data.sourceTextWords –** žodžių skaičius verstiname tekste –

  - **Data.warningMessage –** tarnybos pateiktas įspėjimo pranešimas –

#### <a name="officetranslatortexttranslated"></a>Office.Translator.TextTranslated

Renka informaciją apie tai, ar pasirinktos dalies vertimas, kurį vartotojas įjungė Translator SDX, atliktas sėkmingai. Labai svarbu įvertinti vertimo funkcijos sveikatą ir reaguoti į bet kokius sutrikimus, kurie gali atsirasti. Naudojama stebėti „Excel“, „PowerPoint“ ir „Word“ scenarijaus „Vertimo pasirinkimas“ sveikatą.

Renkami šių laukų duomenys:

  - **Data.actionSource –** kaip buvo paleistas vertimo pasirinkimas

  - **Data.bodyBackgroundColor –** „Office“ temos konteinerio fono spalva

  - **Data.bodyForegroundColor –** „Office“ temos konteinerio priekinio plano spalva

  - **Data.browserLang –** dabartinė naršyklės rodoma kalba

  - **Data.browserOnline -** nebenaudojamas

  - **Data.browserPlatform –** naršyklės platforma

  - **Data.browserUserAgent –** naršyklės vartotojo agentas

  - **Data.colorDepth –** sistemos spalvos gylis

  - **Data.contentLanguage –** aptikta verstino turinio kalba

  - **Data.controlBackgroundColor –** „Office“ temos valdiklio fono spalva

  - **Data.controlBackgroundColor –** „Office“ temos valdiklio priekinio plano spalva

  - **Data.correlationId –** tarnybai siųstos užklausos unikalus identifikatorius

  - **Data.crossSessionId –** unikalus vartotojo identifikatorius

  - **Data.crossSessionStartTime –** vertimo seanso pradžios UTC laiko žyma

  - **Data.currentTime –** telemetrijos laiko pranešimos UTC laiko žyma

  - **Data.displayLanguage –** rodoma „Office“ kalba

  - **Data.documentSourceLang –** nenaudojama pasirinkti

  - **Data.documentTargetLang –** nenaudojama vertimo atrankai

  - **Data.Environment –** tarnybos aplinka, kuriai išsiųsta užklausa

  - **Data.errorMessage –** tarnybos pateiktas klaidos pranešimas

  - **Data.eventActionType –** telemetrijos įvykio tipas

  - **Data.eventTagId"–** kodo eilutės, sukūrusios šį telemetrijos pranešimą, unikalus identifikatorius

  - **TestuojamoVarianto.Duomenys –** įgalinti testuojami variantai

  - **Data.innerHeight –** šoninės srities konteinerio aukštis

  - **Data.innerWidth –** šoninės srities konteinerio plotis

  - **Data.lookupSourceLang –** dabartinio pasirinkto teksto kalba

  - **Data.lookupTargetLang –** kalba, į kurią bus verčiamas pasirinktas tekstas

  - **Data.officeHost –** „Office“ taikomoji programa, esanti šoninėje srityje

  - **Data.officeLocale –** vartotojo „Office“ kalba

  - **Data.officeMachineId –** unikalus įrenginio identifikatorius

  - **Data.officePlatform –** įrenginio platforma

  - **Data.officeSessionId –** „Office“ seanso identifikatorius

  - **Data.officeUserId –** „Office“ vartotojo unikalus identifikatorius

  - **Data.officeVersion –** „Office“ versija

  - **Data.pageXOffset –** kairėje šoninėje srityje esančios šoninės srities horizontalios slinkties padėtis

  - **Data.pageYOffset –** viršutinėje šoninėje srityje esančios šoninės srities vertikalios slinkties padėtis

  - **Data.pixelDepth –** ekrano spalvų skiriamoji geba

  - **Data.responseCode –** HTTP atsakymo iš tarnybos kodas

  - **Data.responseTime –** praėjęs užklausos laikas

  - **Data.resultType –** užklausos rezultatas

  - **Data.screenHeight –** ekrano aukštis pikseliais

  - **Data.screenLeft –** lango horizontali koordinatė ekrano atžvilgiu

  - **Data.screenTop –** lango vertikali koordinatė ekrano atžvilgiu

  - **Data.screenWidth –** ekrano plotis pikseliais

  - **Data.selectedTab –** pasirinktas skirtukas: Selection arba Document

  - **Data.serverUrl –** vertimo tarnybos URL

  - **Data.sessionId –** šoninės srities seanso identifikatorius

  - **Data.sessionStartTime –** vertimo seanso pradžios UTC laiko žyma

  - **Data.sourceTextHash –** verstino teksto maiša

  - **Data.sourceTextLength –** verstino teksto ilgis

  - **Data.sourceTextWords –** žodžių skaičius verstiname tekste

  - **Data.warningMessage –** tarnybos pateiktas įspėjimo pranešimas

#### <a name="officewordexperimentationdocumentstatsoncloseandsuspend"></a>Office.Word.Experimentation.DocumentStatsOnCloseAndSuspend

Šis įvykis registruoja dokumentų statistiką kiekvienam dokumentui, kai „Office Word“ yra uždaryta ar sustabdyta.

Įvykis naudojamas susieti dokumento keitimus, dydį ir t. t. su dokumento įrašymo, dokumento bendrinimo ir dokumento internetinio bendradarbiavimo klaidomis.

Renkami šių laukų duomenys:

  - **Data\_BkmkRefCount –** žymelių nuorodų skaičius dokumente

  - **Data\_CharacterCount –** simbolių skaičius dokumente

  - **Data\_CharactersWithSpaceCount –** simbolių ir tarpų skaičius dokumente

  - **Data\_ChartCount –** diagramų skaičius dokumente

  - **Data\_CitationCount –** citatų skaičius dokumente

  - **Data\_DocumentLocation –** nurodo tarnybą, pateikusią dokumentą („OneDrive“, „File Server“, „SharePoint“ ir kt.)

  - **Data\_ETW\_TrackbackTag –** nurodo kodo vietą, iš kurios šis įvykis buvo išleistas (Close ar Suspend)

  - **Data\_EndnoteDocCount –** dokumentų išnašų skaičius dokumente

  - **Data\_FootnoteDocCount –** puslapio išnašų skaičius dokumente

  - **Data\_HasBibliography –** nurodo, ar dokumente yra bibliografija

  - **Data\_HasHeader –** nurodo, ar dokumente yra antraštė

  - **Data\_IsImeUsed –** nurodo, ar įvesties metodo rengyklė buvo naudota dokumente

  - **Data\_IsPageCountInProgress –** nurodo, ar šiuo metu dokumentui yra skaičiuojamas puslapių skaičius.

  - **Data\_IsTouchUsed –** nurodo, ar dokumente buvo naudojama lietimo įvestis

  - **Data\_IsTrackChangesOn –** nurodo, ar dokumentui buvo įjungtas keitimų sekimas

  - **Data\_LineCount –** dokumento eilučių skaičius

  - **Data\_MainPdod –** „Office Word“ proceso dokumento identifikatorius.

  - **Data\_PageCount –** dokumento puslapių skaičius

  - **Data\_PageNumberFieldCount –** puslapio numerių laukų skaičius dokumente

  - **Data\_ParagraphCount –** paragrafų skaičius dokumente

  - **Data\_PicCount –** paveikslėlių skaičius dokumente

  - **Data\_RsidCount –** įrašytų peržiūrų identifikatorių skaičius dokumente

  - **Data\_TocCount –** turinio lentelių skaičius dokumente

  - **Data\_UrlHash –** vienpusė maiša, skirta „naïve“ dokumento identifikatoriui

  - **Data\_UserActionID –** šis duomenų laukas nenaudojamas (reikšmė visada yra 0).

  - **Data\_UserActionName –** visada „DocumentStatsOnCloseAndSuspend“

  - **Data\_UserInteractionTimeMsec –** vartotojo aktyvios sąveikos su dokumentų skaičius milisekundėmis

  - **Data\_WordCount –** žodžių skaičius dokumente

#### <a name="officewordfilenewcreatenewfile"></a>Office.Word.FileNew.CreateNewFile

Šis įvykis nurodo, kad sukurtas naujas dokumentas „Office Word“ ir sekamas sėkmingas arba nesėkmingas operacijų atlikimas. Įvykis naudojamas stebėti, ar naujų dokumentų kūrimas veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti.

Renkami šių laukų duomenys:

  - **Data\_DirtyState** – ar dokumentas buvo sukurtas neatnaujintoje būsenoje (su pakeitimais, kurie turi būti įrašyti)

  - **Data\_ErrorID** – klaidų identifikatorius operacijos gedimo atveju

  - **Data\_MainPdod –** dokumento identifikatorius šio proceso seanso metu

  - **Data\_UsesCustomTemplate** – nurodo, ar dokumentas buvo sukurtas naudojant pasirinktinį šabloną

#### <a name="officewordfilesaveactcmdgosubsaveas"></a>Office.Word.FileSave.ActCmdGosubSaveAs

Šis įvykis nurodo, kad vartotojas įrašo savo pakeitimus į naują dokumentą. Įvykis stebi, ar įrašymas į naują dokumentą veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti.

Renkami šių laukų duomenys:

  - **Data\_AddDocTelemRes –** nurodo, ar įvykyje galima tinkamai užpildyti kitų dokumentų telemetrijos susijusias reikšmes. Naudojama duomenų kokybės diagnostikai.

  - **Data\_DetachedDuration –** kiek laiko gijoje nebuvo veiklos

  - **Data\_Doc\_AccessMode –** dokumentas yra skirtas tik skaityti / redaguoti

  - **Data\_Doc\_AssistedReadingReasons –** iš anksto nustatytų dokumento atidarymo pagalbiniu skaitymo režimu priežasčių reikšmių rinkinys

  - **Data\_Doc\_ChunkingType –** vienetai, naudojami nuosekliam dokumento atidarymui

  - **Data\_Doc\_EdpState –** dokumentui taikomas elektroninių duomenų apsaugos parametras

  - **Data\_Doc\_Ext –** dokumento plėtinys (docx / xlsb / pptx ir kt.)

  - **Data\_Doc\_FileFormat –** failo formato protokolo versija

  - **Data\_Doc\_Fqdn –** „OneDrive“ arba „SharePoint“ interneto domeno vardas

  - **Data\_Doc\_FqdnHash –** kliento identifikuojamo domeno vardo vienpusė maiša

  - **Data\_Doc\_IOFlags -** Informuoja apie į talpyklą įtrauktas žymes, naudotas užklausos parinktims nustatyti 

  - **Data\_Doc\_IdentityTelemetryId –** atidarymui naudojamos vartotojo tapatybės maiša

  - **Data\_Doc\_InitializationScenario –** įrašo, kaip dokumentas buvo atidarytas

  - **Data\_Doc\_IrmRights –** veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kurie buvo taikyti dokumentui / vartotojui

  - **Data\_Doc\_IsIncrementalOpen -** Žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

  - **Data\_Doc\_IsOcsSupported -** Žyma, nurodanti, kad dokumentas palaikomas bendradarbiavimo tarnybos

  - **Data\_Doc\_IsOpeningOfflineCopy -** Žyma, nurodanti, kad autonominė dokumento kopija atidaryta

  - **Data_Doc_IsRtcAlwaysOn –** „true“, jei šiam failui visada yra įjungtas realiojo laiko kanalas (RTC).

  - **Duomenų\_ad\_IsSyncBacked -** žyma, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

  - **Data\_Doc\_Location –** nurodo tarnybą, pateikusią dokumentą („OneDrive“, „File Server“, „SharePoint“ ir kt.)

  - **Data\_Doc\_LocationDetails –** nurodo vietoje saugomo dokumento žinomą aplanką

  - **Data\_Doc\_NumberCoAuthors -** Skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

  - **Data\_Doc\_PasswordFlags –** nurodo, ar nustatytas skaitymo arba skaitymo / rašymo slaptažodžio žymų rinkinys

  - **Data\_Doc\_ReadOnlyReasons –** dokumento atidarymo tik kaip skaitomo priežastys

  - **Data\_Doc\_ResourceIdHash –** anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_Doc\_ServerDocId –** nekintamų anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_Doc\_ServerProtocol –** protokolo versija, naudojama norint susisiekti su tarnyba

  - **Data\_Doc\_ServerType –** tarnybą siūlančio serverio tipas („SharePoint“, „OneDrive“, WOPI ir kt.)

  - **Data\_Doc\_ServerVersion –** Serverio versija, siūlanti tarnybą

  - **Data\_Doc\_SessionId –** nustato konkretų viso seanso dokumentų redagavimo seansą

  - **Data\_Doc\_SharePointServiceContext –** „SharePoint Online“ užklausų diagnostinė informacija

  - **Data\_Doc\_SizeInBytes –** dokumento dydžio indikatorius

  - **Data\_Doc\_SpecialChars –** dokumento URL arba kelio specialiųjų simbolių indikatorius

  - **Data\_Doc\_StreamAvailability –** indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas arba išjungtas

  - **Data\_Doc\_SyncBackedType –** dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba)

  - **Data\_Doc\_UrlHash –** vienpusė maiša, skirta „naïve“ dokumento identifikatoriui

  - **Data\_EditorDisablingRename –** pirmojo redaktoriaus, dėl kurio buvo išjungtas pervardijimas, identifikatorius

  - **Data\_EditorsCount –** dokumento redaktorių skaičius

  - **Data\_LastLoggedTag –** unikali kodo iškvietimo žymės vieta, naudojama nustatyti, kada dukart nepavyksta bandymas įrašyti (naudojama duomenų kokybės diagnostikai)

  - **Data\_MoveDisabledReason –** klaida, išjungianti dokumento perkėlimą

  - **Data\_MoveFlightEnabled –** ar yra įgalinta testuojamo varianto perkėlimo funkcija

  - **Data\_RenameDisabledReason –** klaida, dėl kurios išjungiamas dokumento pervardijimas

  - **Data\_RenameFlightEnabled –** ar įgalinta testuojamo varianto pervardijimo funkcija

#### <a name="officewordfilesaveactfconfirmsavedoccoreautorecoverysave"></a>Office.Word.FileSave.ActFConfirmSaveDocCoreAutoRecoverySave

Šis įvykis nurodo, kad „Office Word“ įrašo automatinio atkūrimo dokumentą, kuris anksčiau nebuvo įrašytas. Tai suteikia galimybę „Microsoft“ aptikti automatinio atkūrimo klaidas, svarbias dokumento duomenų saugumui.

Įvykis stebi, ar automatinio atkūrimo įrašymo funkcija veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti.

Renkami šių laukų duomenys:

  - **Data\_DetachedDuration –** kiek laiko gijoje nebuvo veiklos

  - **Data\_Doc\_AccessMode –** dokumentas yra skirtas tik skaityti / redaguoti

  - **Data\_Doc\_AssistedReadingReasons –** iš anksto nustatytų dokumento atidarymo pagalbiniu skaitymo režimu priežasčių reikšmių rinkinys

  - **Data\_Doc\_ChunkingType –** vienetai, naudojami nuosekliam dokumento atidarymui

  - **Data\_Doc\_EdpState –** dokumentui taikomas elektroninių duomenų apsaugos parametras

  - **Data\_Doc\_Ext –** dokumento plėtinys (docx / xlsb / pptx ir kt.)

  - **Data\_Doc\_FileFormat –** failo formato protokolo versija

  - **Data\_Doc\_Fqdn –** „OneDrive“ arba „SharePoint“ interneto domeno vardas

  - **Data\_Doc\_FqdnHash –** kliento identifikuojamo domeno vardo vienpusė maiša

  - **Data\_Doc\_IdentityTelemetryId –** atidarymui naudojamos vartotojo tapatybės vienpusė maiša

  - **Data\_Doc\_InitializationScenario –** įrašo, kaip dokumentas buvo atidarytas

  - **Data\_Doc\_IOFlags -** Informuoja apie į talpyklą įtrauktas žymes, naudotas užklausos parinktims nustatyti 

  - **Data\_Doc\_IrmRights –** veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kurie buvo taikyti dokumentui / vartotojui

  - **Data\_Doc\_IsIncrementalOpen -** Žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

  - **Data\_Doc\_IsOcsSupported -** Žyma, nurodanti, kad dokumentas palaikomas bendradarbiavimo tarnybos

  - **Data\_Doc\_IsOpeningOfflineCopy -** Žyma, nurodanti, kad autonominė dokumento kopija atidaryta

  - **Data_Doc_IsRtcAlwaysOn –** „true“, jei šiam failui visada yra įjungtas realiojo laiko kanalas (RTC).

  - **Duomenų\_ad\_IsSyncBacked -** žyma, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

  - **Data\_Doc\_Location –** nurodo tarnybą, pateikusią dokumentą („OneDrive“, „File Server“, „SharePoint“ ir kt.)

  - **Data\_Doc\_LocationDetails –** nurodo vietoje saugomo dokumento žinomą aplanką

  - **Data\_Doc\_NumberCoAuthors -** Skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

  - **Data\_Doc\_PasswordFlags –** nurodo, ar nustatytas skaitymo arba skaitymo / rašymo slaptažodžio žymų rinkinys

  - **Data\_Doc\_ReadOnlyReasons –** dokumento atidarymo tik kaip skaitomo priežastys

  - **Data\_Doc\_ResourceIdHash –** anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_Doc\_ServerDocId –** nekintamų anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_Doc\_ServerProtocol –** susisiekimui su tarnyba naudojama protokolo versija

  - **Data\_Doc\_ServerType –** tarnybą siūlančio serverio tipas („SharePoint“, „OneDrive“, WOPI ir kt.)

  - **Data\_Doc\_ServerVersion –** tarnybą siūlančio serverio versija

  - **Data\_Doc\_SessionId –** nustato konkretų viso seanso dokumentų redagavimo seansą

  - **Data\_Doc\_SharePointServiceContext –** „SharePoint Online“ užklausų diagnostinė informacija

  - **Data\_Doc\_SizeInBytes –** dokumento dydžio indikatorius

  - **Data\_Doc\_SpecialChars –** dokumento URL arba kelio specialiųjų simbolių indikatorius

  - **Data\_Doc\_StreamAvailability –** indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas arba išjungtas

  - **Data\_Doc\_SyncBackedType –** dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba)

  - **Data\_Doc\_UrlHash –** vienpusė maiša, skirta „naïve“ dokumento identifikatoriui

  - **Data\_Doc\_WopiServiceId –** apima unikalų WOPI tarnybos teikėjo identifikatorių

  - **Data\_FailureClass –** sveikasis skaičius, nurodantis „Office“ bendradarbiavimo tarnybos (OCS) perėjimo trikties klasę

  - **Data\_MainPdod –** „Office Word“ proceso dokumento identifikatorius.

  - **Data\_MoveFlightEnabled -** Ar įjungta perkėlimo testavimo funkcija

  - **Data\_OCSSyncbackSaveStarted –** žymė, nurodanti, kad šis įrašymas susijęs su sinchronizuotu atsarginės kopijos įrašymu

  - **Data\_RenameDisabledReason –** klaida, dėl kurios šiam dokumentui išjungtas pervardijimas

  - **Data\_RenameFlightEnabled -** Ar įjungta pervardijimo testavimo funkcija

  - **Data\_SaveInitiateKind –** sveikasis skaičius, nurodantis, kaip inicijuotas įrašymas

  - **Data\_SrcDocIsUnnamedOrNew –** nurodo, ar įrašomas dokumentas yra naujas

#### <a name="officewordfilesaveactfconfirmsavedoccorequerysave"></a>Office.Word.FileSave.ActFConfirmSaveDocCoreQuerySave

Šis įvykis nurodo, kad „Office Word“ ragina vartotoją įrašyti keitimus, kai programa bando uždaryti dokumentą. Tai leidžia „Microsoft“ stebėti, ar įrašymas išėjimo metu veikia tinkamai, kad neprarasti dokumento duomenų. Įvykis stebi, ar funkcija įrašyti išėjimo metu veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti.

Renkami šių laukų duomenys:

  - **Data\_AddDocTelemRes –** nurodo, ar įvykyje galima tinkamai užpildyti kitų dokumentų telemetrijos susijusias reikšmes. Naudojama duomenų kokybės diagnostikai.

  - **Data\_DetachedDuration –** kiek laiko gijoje nebuvo veiklos

  - **Data\_Doc\_AccessMode –** dokumentas yra skirtas tik skaityti / redaguoti

  - **Data\_Doc\_AssistedReadingReasons –** iš anksto nustatytų dokumento atidarymo pagalbiniu skaitymo režimu priežasčių reikšmių rinkinys

  - **Data\_Doc\_ChunkingType –** vienetai, naudojami nuosekliam dokumento atidarymui

  - **Data\_Doc\_EdpState –** dokumentui taikomas elektroninių duomenų apsaugos parametras

  - **Data\_Doc\_Ext –** dokumento plėtinys (docx / xlsb / pptx ir kt.)

  - **Data\_Doc\_FileFormat –** failo formato protokolo versija

  - **Data\_Doc\_Fqdn –** „OneDrive“ arba „SharePoint“ interneto domeno vardas

  - **Data\_Doc\_FqdnHash –** kliento identifikuojamo domeno vardo vienpusė maiša

  - **Data\_Doc\_IdentityTelemetryId –** atidarymui naudojamos vartotojo tapatybės vienpusė maiša

  - **Data\_Doc\_InitializationScenario –** įrašo, kaip dokumentas buvo atidarytas

  - **Data\_Doc\_IOFlags -** Informuoja apie į talpyklą įtrauktas žymes, naudotas užklausos parinktims nustatyti 

  - **Data\_Doc\_IrmRights –** veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kurie buvo taikyti dokumentui / vartotojui

  - **Data\_Doc\_IsIncrementalOpen -** Žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

  - **Data\_Doc\_IsOcsSupported -** Žyma, nurodanti, kad dokumentas palaikomas bendradarbiavimo tarnybos

  - **Data\_Doc\_IsOpeningOfflineCopy -** Žyma, nurodanti, kad autonominė dokumento kopija atidaryta

  - **Data_Doc_IsRtcAlwaysOn –** „true“, jei šiam failui visada yra įjungtas realiojo laiko kanalas (RTC).

  - **Duomenų\_ad\_IsSyncBacked -** žyma, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

  - **Data\_Doc\_Location –** nurodo tarnybą, pateikusią dokumentą („OneDrive“, „File Server“, „SharePoint“ ir kt.)

  - **Data\_Doc\_LocationDetails –** nurodo vietoje saugomo dokumento žinomą aplanką

  - **Data\_Doc\_NumberCoAuthors -** Skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

  - **Data\_Doc\_PasswordFlags –** nurodo, ar nustatytas skaitymo arba skaitymo / rašymo slaptažodžio žymų rinkinys

  - **Data\_Doc\_ReadOnlyReasons –** dokumento atidarymo tik kaip skaitomo priežastys

  - **Data\_Doc\_ResourceIdHash –** anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_Doc\_ServerDocId –** nekintamų anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_Doc\_ServerProtocol –** susisiekimui su tarnyba naudojama protokolo versija

  - **Data\_Doc\_ServerType –** tarnybą siūlančio serverio tipas („SharePoint“, „OneDrive“, WOPI ir kt.)

  - **Data\_Doc\_ServerVersion –** tarnybą siūlančio serverio versija

  - **Data\_Doc\_SessionId –** nustato konkretų viso seanso dokumentų redagavimo seansą

  - **Data\_Doc\_SharePointServiceContext –** „SharePoint Online“ užklausų diagnostinė informacija

  - **Data\_Doc\_SizeInBytes –** dokumento dydžio indikatorius

  - **Data\_Doc\_SpecialChars –** dokumento URL arba kelio specialiųjų simbolių indikatorius

  - **Data\_Doc\_StreamAvailability –** indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas arba išjungtas

  - **Data\_Doc\_SyncBackedType –** dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba)

  - **Data\_Doc\_UrlHash –** vienpusė maiša, skirta „naïve“ dokumento identifikatoriui

  - **Data\_Doc\_WopiServiceId -** Apima unikalų WOPI tarnybos teikėjo identifikatorių

  - **Data\_DstDoc\_AccessMode -** Paskirties dokumentas yra skirtas tik skaityti / redaguoti

  - **Data\_DstDoc\_EdpStatee – Elektroninių duomenų apsaugos nustatymas, skirtas paskirties dokumentui-**

  - **Data\_DstDoc\_Ext -** Paskirties dokumento plėtinys (docx / xlsb / pptx ir kt.)

  - **Data\_DstDoc\_FileFormat -** Paskirties dokumento failo formato protokolo versija

  - **Data\_DstDoc\_Location -** Nurodo, kuri tarnyba teikia paskirties dokumento saugyklą („OneDrive“, failų serveris, „SharePoint“, kt.)

  - **Data\_DstDoc\_LocationDetails -** Nurodo, kuriuose žinomuose aplankuose yra paskirties dokumentas

  - **Data\_DstDoc\_SessionId -** Nustato konkretų viso seanso dokumentų redagavimo seansą

  - **Data\_DstDoc\_UrlHash -** Vienpusė maiša, skirta paskirties dokumento „naïve“ dokumento identifikatoriui sukurti

  - **Data\_FailureClass -** Sveikasis skaičius, nurodantis OCS perėjimo trikties klasę

  - **Data\_LocationPickerSaveStatus -** Sveikojo skaičiaus reikšmė, kuri nurodo veiksmą, suaktyvinantį įrašymą naudojant įrašymo arba išėjimo dialogo langą

  - **Data\_MainPdod -** Dokumento identifikatorius vykstant „Office Word“ procesui.

  - **Data\_MoveFlightEnabled -** Ar įjungta perkėlimo testavimo funkcija

  - **Data\_OCSSyncbackSaveStarted –** žymė, nurodanti, kad šis įrašymas susijęs su sinchronizuotu atsarginės kopijos įrašymu

  - **Data\_RenameDisabledReason –** klaida, dėl kurios šiam dokumentui išjungtas pervardijimas

  - **Data\_RenameFlightEnabled -** Ar įjungta pervardijimo testavimo funkcija

  - **Data\_SaveInitiateKind –** sveikasis skaičius, nurodantis, kaip inicijuotas įrašymas

  - **Data\_SrcDocIsUnnamedOrNew -** Nurodo, ar įrašomas dokumentas yra naujas

#### <a name="officewordfilesavesaveassavefile"></a>Office.Word.FileSave.SaveAsSaveFile

Šis įvykis nurodo, kad „Office Word“ įrašo dokumentą į naują dokumentą. Tai leidžia „Microsoft“ aptikti funkcijos Įrašyti kaip klaidas, o tai svarbu norint išvengti dokumento duomenų praradimo. Įvykis stebi, ar funkcija Įrašyti kaip veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti.

Renkami šių laukų duomenys:

  - **Data\_AddDocTelemRes –** nurodo, ar įvykyje galima tinkamai užpildyti kitų dokumentų telemetrijos susijusias reikšmes. Naudojama duomenų kokybės diagnostikai.

  - **Data\_AddDocTelemResDst -** Nurodo, ar paskirties dokumento įvykyje galima tinkamai užpildyti kitų dokumentų telemetrijos susijusias reikšmes. Naudojama duomenų kokybės diagnostikai.

  - **Data\_AddDocTelemResDst -** Nurodo, ar šaltinio dokumento įvykyje galima tinkamai užpildyti kitų dokumentų telemetrijos susijusias reikšmes. Naudojama duomenų kokybės diagnostikai.

  - **Data\_DetachedDuration –** kiek laiko gijoje nebuvo veiklos

  - **Data\_Doc\_AccessMode –** dokumentas yra skirtas tik skaityti / redaguoti

  - **Data\_Doc\_AssistedReadingReasons –** iš anksto nustatytų dokumento atidarymo pagalbiniu skaitymo režimu priežasčių reikšmių rinkinys

  - **Data\_Doc\_ChunkingType –** vienetai, naudojami nuosekliam dokumento atidarymui

  - **Data\_Doc\_EdpState –** dokumentui taikomas elektroninių duomenų apsaugos parametras

  - **Data\_Doc\_Ext –** dokumento plėtinys (docx / xlsb / pptx ir kt.)

  - **Data\_Doc\_FileFormat –** failo formato protokolo versija

  - **Data\_Doc\_Fqdn –** „OneDrive“ arba „SharePoint“ interneto domeno vardas

  - **Data\_Doc\_FqdnHash –** kliento identifikuojamo domeno vardo vienpusė maiša

  - **Data\_Doc\_IdentityTelemetryId -** Vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša

  - **Data\_Doc\_IOFlags -** Informuoja apie į talpyklą įtrauktas žymes, naudotas užklausos parinktims nustatyti 

  - **Data\_Doc\_IrmRights –** veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kurie buvo taikyti dokumentui / vartotojui

  - **Data\_Doc\_IsIncrementalOpen -** Žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

  - **Data\_Doc\_IsOcsSupported -** Žyma, nurodanti, kad dokumentas palaikomas bendradarbiavimo tarnybos

  - **Data\_Doc\_IsOpeningOfflineCopy -** Žyma, nurodanti, kad autonominė dokumento kopija atidaryta

  - **Data_Doc_IsRtcAlwaysOn –** „true“, jei šiam failui visada yra įjungtas realiojo laiko kanalas (RTC).

  - **Duomenų\_ad\_IsSyncBacked -** žyma, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

  - **Data\_Doc\_Location –** nurodo tarnybą, pateikusią dokumentą („OneDrive“, „File Server“, „SharePoint“ ir kt.)

  - **Data\_Doc\_LocationDetails –** nurodo vietoje saugomo dokumento žinomą aplanką

  - **Data\_Doc\_NumberCoAuthors -** Skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

  - **Data\_Doc\_ReadOnlyReasons -** Priežastys, kodėl dokumentas buvo atidarytas tik kaip skaitomas

  - **Data\_Doc\_ResourceIdHash –** anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_Doc\_ServerDocId –** nekintamų anonimiškai pateiktų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_Doc\_ServerProtocol –** susisiekimui su tarnyba naudojama protokolo versija

  - **Data\_Doc\_ServerType –** tarnybą siūlančio serverio tipas („SharePoint“, „OneDrive“, WOPI ir kt.)

  - **Data\_Doc\_ServerVersion –** tarnybą siūlančio serverio versija

  - **Data\_Doc\_SessionId –** nustato konkretų viso seanso dokumentų redagavimo seansą

  - **Data\_Doc\_SharePointServiceContext –** „SharePoint Online“ užklausų diagnostinė informacija

  - **Data\_Doc\_SizeInBytes –** dokumento dydžio indikatorius

  - **Data\_Doc\_SpecialChars –** dokumento URL arba kelio specialiųjų simbolių indikatorius

  - **Data\_Doc\_StreamAvailability -** Indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas / išjungtas

  - **Data\_Doc\_UrlHash -** Vienpusė maiša, skirta „naïve“ dokumento identifikatoriui

  - **Data\_DstDoc\_AccessMode -** Paskirties dokumentas yra skirtas tik skaityti / redaguoti

  - **Data\_DstDoc\_AssistedReadingReasons -** Iš anksto nustatytų reikšmių rinkinys, kodėl dokumentas buvo atidarytas pagalbiniu skaitymo režimu

  - **Data\_DstDoc\_ChunkingType -** Vienetai, naudojami nuosekliam dokumento atidarymui

  - **Data\_DstDoc\_EdpState -** Elektroninių duomenų apsaugos nustatymas, skirtas paskirties dokumentui

  - **Data\_DstDoc\_Ext -** Dokumento plėtinys (docx / xlsb / pptx ir kt.)

  - **Data\_DstDoc\_FileFormat -** Failo formato protokolo versija

  - **Data\_DstDoc\_Fqdn -** „OneDrive“ arba „SharePoint Online“ paskirties dokumento domeno vardas

  - **Data\_DstDoc\_FqdnHash -** Vienpusė kliento identifikuojamo paskirties dokumento domeno vardo maiša

  - **Data\_DstDoc\_IdentityTelemetryId -** Vartotojo tapatybės, naudojamos atidaryti, vienpusė maiša

  - **Data\_DstDoc\_InitializationScenario -** Įrašo, kaip paskirties dokumentas buvo atidarytas

  - **Data\_DstDoc\_IOFlags -** Informuoja apie į talpyklą įtrauktas žymas, naudotas paskirties dokumento užklausos parinktims nustatyti 

  - **Data\_DstDoc\_IrmRights -** Veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kurie buvo taikyti paskirties dokumentui / vartotojui

  - **Data\_DstDoc\_IsIncrementalOpen -** Žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

  - **Data\_DstDoc\_IsOcsSupported -** Žymė, nurodanti, kad dokumentą palaiko bendradarbiavimo tarnyba

  - **Data\_DstDoc\_IsOpeningOfflineCopy -** Žymė, nurodanti, kad autonominė dokumento kopija atidaryta

  - **Data\_DstDoc\_IsSyncBacked -** Žymė, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

  - **Data\_DstDoc\_Location -** Nurodo, kuri tarnyba teikia paskirties dokumento saugyklą („OneDrive“, failų serveris, „SharePoint“, kt.)

  - **Data\_DstDoc\_LocationDetails -** Nurodo, kuriuose žinomuose aplankuose yra vietoje saugomų dokumentų

  - **Data\_DstDoc\_NumberCoAuthors -** Skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

  - **Data\_DstDoc\_PasswordFlags -** Nurodo, ar nustatytas paskirties dokumento skaitymo arba skaitymo / rašymo slaptažodžio žymių rinkinys

  - **Data\_DstDoc\_ReadOnlyReasons -** Priežastys, kodėl paskirties dokumentas buvo atidarytas tik kaip skaitomas

  - **Data\_DstDoc\_ResourceIdHash -** Anonimizuotų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_DstDoc\_ServerDocId -** Nekintamų anonimizuotų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_DstDoc\_ServerProtocol -** Protokolo versija, naudojama norint susisiekti su tarnyba

  - **Data\_DstDoc\_ServerType -** Serverio tipas, siūlantis tarnybą („SharePoint“, „OneDrive“, WOPI ir kt.)

  - **Data\_DstDoc\_ServerVersion -** Serverio versija, siūlanti tarnybą

  - **Data\_DstDoc\_SessionId -** Nustato konkretų viso seanso dokumentų redagavimo seansą

  - **Data\_DstDoc\_SharePointServiceContext -** Diagnostinė informacija iš „SharePoint Online“ užklausų

  - **Data\_DstDoc\_SizeInBytes -** Dokumento dydžio indikatorius

  - **Data\_DstDoc\_SpecialChars -** Dokumento URL arba kelio specialiųjų simbolių indikatorius

  - **Data\_DstDoc\_StreamAvailability -** Indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas / išjungtas

  - **Data\_DstDoc\_SyncBackedType -** Dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba)

  - **Data\_DstDoc\_UrlHash -** Vienpusė maiša, skirta paskirties dokumento „naïve“ dokumento identifikatoriui sukurti

  - **Data\_Doc\_WopiServiceId -** Apima unikalų WOPI tarnybos teikėjo identifikatorių

  - **Data\_FailureClass -** Sveikasis skaičius, nurodantis OCS perėjimo trikties klasę

  - **Data\_LocationPickerPropagateToSaveTime,spLapsedMsec -** Matuoja laiką milisekundėmis, kiek trunka įrašymo sužadinimas gavus vietos duomenų rinkiklio rezultatus

  - **Data\_LocationPickerSaveStatus -** Vietos parinkiklio pateikiama būsena

  - **Data\_MainPdod -** Dokumento identifikatorius vykstant „Office Word“ procesui.

  - **Data\_MoveDisabledReason -** Klaida, kuri yra išjungia dokumento perkėlimą

  - **Data\_MoveFlightEnabled -** Ar įjungta perkėlimo testavimo funkcija

  - **Data\_RenameDisabledReason -** Klaida, atsirandanti, kai pervardijimas šiam dokumentui išjungtas

  - **Data\_RenameFlightEnabled -** Ar įjungta pervardijimo testavimo funkcija

  - **Data\_SaveInitiateKind -** Sveikasis skaičius, nurodantis, kaip inicijuojamas įrašymas

  - **Data\_SrcDoc\_AccessMode -** Šaltinio dokumentas yra skirtas tik skaityti / redaguoti

  - **Data\_SrcDoc\_AssistedReadingReasons -** Iš anksto nustatytų reikšmių rinkinys, kodėl dokumentas buvo atidarytas pagalbiniu skaitymo režimu

  - **Data\_SrcDoc\_ChunkingType -** Vienetai, naudojami nuosekliam dokumento atidarymui

  - **Data\_SrcDoc\_EdpState -** Šaltinio dokumentui taikomas elektroninių duomenų apsaugos parametras

  - **Data\_SrcDoc\_Ext -** Šaltinio dokumento plėtinys (docx / xlsb / pptx ir kt.)

  - **Data\_SrcDoc\_FileFormat -** Šaltinio dokumento failo formato protokolo versija

  - **Data\_SrcDoc\_Fqdn -** „OneDrive“ arba „SharePoint Online“ šaltinio dokumento domeno vardas

  - **Data\_SrcDoc\_FqdnHash -** Vienpusė kliento identifikuojamo šaltinio dokumento domeno vardo maiša

  - **Data\_SrcDoc\_IdentityTelemetryId -** Vartotojo tapatybės, naudojamos atidaryti, vienpusė maiša

  - **Data\_SrcDoc\_InitializationScenario -** Įrašo, kaip dokumentas buvo atidarytas

  - **Data\_SrcDoc\_IOFlags -** Informuoja apie į talpyklą įtrauktas žymes, naudotas užklausos parinktims nustatyti 

  - **Data\_SrcDoc\_IrmRights -** veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kurie buvo taikyti dokumentui / vartotojui

  - **Data\_SrcDoc\_IsIncrementalOpen -** Žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

  - **Data\_SrcDoc\_IsOcsSupported -** Žymė, nurodanti, kad dokumentą palaiko bendradarbiavimo tarnyba

  - **Data\_SrcDoc\_IsOpeningOfflineCopy -** Žymė, nurodanti, kad autonominė dokumento kopija

  - **Data\_SrcDoc\_IsSyncBacked -** Žymė, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

  - **Data\_SrcDoc\_Location -** Nurodo, kuri tarnyba teikia šaltinio dokumentą („OneDrive“, failų serveris, „SharePoint“, kt.)

  - **Data\_SrcDoc\_LocationDetails -** Nurodo, kuriuose žinomuose aplankuose yra vietoje saugomų dokumentų

  - **Data\_SrcDoc\_NumberCoAuthors -** Skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

  - **Data\_SrcDoc\_PasswordFlags -** Nurodo, ar nustatytas skaitymo arba skaitymo / rašymo slaptažodžio žymių rinkinys

  - **Data\_SrcDoc\_ReadOnlyReasons -** Priežastys, kodėl dokumentas buvo atidarytas tik kaip skaitomas

  - **Data\_SrcDoc\_ResourceIdHash -** Anonimizuotų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_SrcDoc\_ServerDocId -** Nekintamų anonimizuotų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_SrcDoc\_ServerProtocol -** Protokolo versija, naudojama norint susisiekti su tarnyba

  - **Data\_SrcDoc\_ServerType -** Serverio tipas, siūlantis tarnybą („SharePoint“, „OneDrive“, WOPI ir kt.)

  - **Data\_SrcDoc\_ServerVersion -** Serverio versija, siūlanti tarnybą

  - **Data\_SrcDoc\_SessionId -** Nustato konkretų viso seanso dokumentų redagavimo seansą

  - **Data\_SrcDoc\_SharePointServiceContext -** Diagnostinė informacija iš „SharePoint Online“ užklausų

  - **Data\_SrcDoc\_SizeInBytes -** Dokumento dydžio indikatorius

  - **Data\_SrcDoc\_SpecialChars -** Dokumento URL arba kelio specialiųjų simbolių indikatorius

  - **Data\_SrcDoc\_StreamAvailability -** Indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas / išjungtas

  - **Data\_SrcDoc\_SyncBackedType -** Dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba)

  - **Data\_SrcDoc\_UrlHash -** Vienpusė maiša, skirta „naïve“ dokumento identifikatoriui

  - **Data\_SrcDoc\_WopiServiceId -** Apima unikalų WOPI tarnybos teikėjo identifikatorių

  - **Data\_SrcDocIsUnnamedOrNew -** Nurodo, ar įrašomas dokumentas yra naujas

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

#### <a name="officevisiosharedfeatureexperimentation"></a>Office.Visio.Shared.FeatureExperimentation

Stebi funkcijos testavimą vartotojams. Šis įvykis padės mums nustatyti, ar funkcija testuojama sėkmingai.

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

  - **Data\_DataSourceType:string** - Šioje srityje nurodoma, ar diagrama sukurta naudojant „Lentelė“, ar „Pasirinkitnis diapazonas“

  - **Data\_DialogError:string** - Pasirinktinis klaidos tipas kuriant išmaniąją diagramą „Excel“

  - **Data\_NoOfShapesAdded:int** - Figūrų, kurios pridėtos įrašant „Excel“ funkcijos kopiją skaičius

  - **Data\_NoOfShapesDeleted:int** - Figūrų, kurios panakintos įrašant „Excel“ funkcijos kopiją skaičius

  - **Data\_OverwriteSelected:bool** - „True“ nurodo, ar vartotojas pasirinko duomenų perrašymo parinktį

  - **Data\_SourceDataModified:bool** - „True“ nurodo, kad pakeisti šaltinio duomenys

  - **Data\_WarningShown:bool** - „True“ reiškia, kad vartotojui rodomas duomenų naujinimo įspėjimas

  - **Data\_WarningShownBecauseOfPresenceOfFormula:bool** - „True“ nurodo vartotojui rodomą įspėjimą dėl formulės programoje „Excel“

  - **Data\_WarningShownToAddNextStepID:bool** - „True“ nurodo vartotojui rodomą įspėjimą dėl kitų identifikavimo priemonės programoje „Excel“ praleistų veiksmų

  - **Data\_WarningShownToConvertToTable:bool** - „True“ nurodo vartotojui rodomą įspėjimą konvertuoti „Excel“ duomenis į lentelės formatą

### <a name="application-status-and-boot-subtype"></a>*Taikomosios programos būsena ir įkrovos potipis*

Nustatymas, ar įvyko specifiniai funkcijų įvykiai, pvz., paleidimas ar sustabdymas, ir ar funkcija veikia.

#### <a name="officeextensibilityofficejsappactivated"></a>Office.Extensibility.OfficeJS.Appactivated

Įrašo informaciją apie netikėtą „Office“ uždarymą. Tai leidžia mums nustatyti produkto gedimus ir pakibimus programoje, kad juos būtų galima pašalinti.

Renkami šių laukų duomenys:

  - **Data\_AirspaceInitTime:integer-** Laikas, skirtas inicijuoti „Airspace Office“ komponentui

  - **Data\_AllShapes:integer -** Figūrų skaičius dokumente

  - **Data\_APIInitTime:integer -** Laikas, skirtas inicijuoti „Visio API“ moduliui

  - **Data\_AppSizeHeight –** Prideda**-** lango dydžio aukštį

  - **Data\_AppSizeWidth –** Prideda**-** lango dydžio plotį

  - **Data\_AppURL -** Papildinio URL; Registruoja parduotuvėje esančio papildinio visą URL ir ne parduotuvėje esančio papildinio URL domeną

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

  - **Data_Doc_IsRtcAlwaysOn –** „true“, jei šiam failui visada yra įjungtas realiojo laiko kanalas (RTC).

  - **Data\_Doc\_IsSyncBacked:bool-** „True“, kai tai yra serverio dokumentas, kuris yra vietoje, ir yra sinchronizuotas su serveriu (pvz., per „OneDrive“ arba ODB kliento programas)

  - **Data\_Doc\_Location:long-** : Iš anksto nustatytų reikšmių, kur saugomas dokumentas (vietoje, „SharePoint“, WOPI, tinkle ir kt.) rinkinys

  - **Data\_Doc\_LocationDetails:long -** Iš anksto nustatytų išsamesnės informacijos apie vietą (laikinas aplankas, atsisiuntimų aplankas, „One Drive“ dokumentai, „One Drive“ paveikslėliai) rinkinys

  - **Data\_Doc\_ResourceIdHash:string -** Debesyje saugomų dokumentų maišos išteklių identifikatorius

  - **Data\_Doc\_ResourceIdHash:string -** Debesyje saugomų dokumentų maišos išteklių identifikatorius

  - **Data\_Doc\_SessionId:long -** Generuotas GUID, kuris identifikuoja dokumento egzempliorių to paties seanso metu

  - **Data\_Doc\_SizeInBytes:long -** Dokumento dydis baitais

  - **Data\_Doc\_SpecialChars:long -** Ilgasis šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

  - **Data\_Doc\_SyncBackedType -** Dokumento tipo (vietinių arba pagrįstų tarnybomis) indikatorius 

  - **Data\_Doc\_UrlHash:string -** Debesyje saugomų dokumentų viso URL maiša

  - **Data\_DpiAwarenessTime:integer -** Laikas, kurio reikia įgalinti monitoriaus DPI informacijos surinkimo tarnybą 

  - **Data\_DurationToCompleteInMilliseconds:double-** Trukmė milisekundėmis, kol atliekamas įrašymas

  - **Data\_ErrorCode:int -** : 0, jei sėkminga, sveikasis skaičius – gedimo atveju

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

  - **Data\_InitBrandTime:integer -** Laikas, kurio reikia inicijuoti ekrano užsklandai ir prekės ženklo „Office“ komponentams

  - **Data\_InitGimmeTime:integer -** Laikas, skirtas inicijuoti „Office“ komponentui

  - **Data\_InitLicensingTime:integer -** Laikas, skirtas inicijuoti „Office“ komponento licencijai

  - **Data\_InitMsoUtilsTime:integer -** „MSOUTILS Office“ komponento inicijavimo laikas

  - **Data\_InitPerfTime:integer -** „Office“ komponento veikimo inicijavimo laikas

  - **Data\_InitTCOTime:integer -** Laikas, reikalingas „Office“ komponento tvarkytuvui inicijuoti

  - **Data\_InitTrustCenterTime:integer -** Laikas, skirtas inicijuoti „Office“ komponento patikimumo centrui

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

  - **Data\_LoadProfileTime:integer -** Laikas, kurio reikia, kad įkeltų „Office“ analizės įrankį

  - **Duomenų\_LoadRichEditTim:integer-** daug redaguoti komponentas įkėlimo laiką

  - **Data\_LoadVisIntlTime:integer -** Laikas, kurio reikia „Visio“ tarptautiniam DLL įkelti

  - **Data\_Location:integer -** Vietą failo, iš kurio buvo atidaryta 0 vietos, 1, tinklo, 2, „SharePoint“, 3 – žiniatinklio

  - **Data\_MasterCount:integer -** Ruošiniai skaičius diagramoje

  - **Data\_MaxCoauthUsers:integer -** Maksimalus vartotojų skaičius, bendradarbiavusių bet kuriuo seansų Filesystem, Registry, First Party, SDX metu

  - **Data\_MaxTilesAutoSizeOn:integer -** Puslapio, kuriame įjungtas automatinis dydžio nustatymas, maksimalus plytelių skaičius

  - **Data\_MsoBeginBootTime:integer -** MSO paleidimo laikas

  - **Data\_MsoDllLoadTime:integer -** Laikas, kurio reikia MSO DLL įkelti

  - **Data\_MsoEndBootTime:integer -** Laikas, kurio reikia MSO įkelti

  - **Data\_MsoInitCoreTime:integer -** Laikas, kurio reikia „MSO Office“ komponentui inicijuoti

  - **Data\_MsoInitUITime:integer -** Laikas, kurio reikia „MSO Office“ komponento UI inicijuoti

  - **Data\_MsoMigrateTime:integer -** Laikas, kurio reikia vartotojo parametrams perkelti pirmo paleidimo metu, jei vartotojas atnaujino iš ankstesnės versijos

  - **Data\_NetworkIOBytesRead:int -** Perskaitytų tinklo baitų skaičius įrašant

  - **Data\_NetworkIOBytesReadSquared:int -** kvadratu pakelta duomenų reikšmė\_NetworkIOBytesRead

  - **Data\_NetworkIOBytesWritten:int -** Bendrasis tinklo baitų kiekis išsaugant

  - **Data\_NetworkIOBytesWrittenSquared :int-** kvadratu pakelta duomenų reikšmė NetworkIOBytesWritten

  - **Data\_OartStartupTime:integer -** Laikas, skirtas inicijuoti „OART Office“ komponentui

  - **Data\_OleInitTime:integer -**„OLE Office“ komponento inicijavimo laikas

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

  - **Data\_SDX\_AssetId -** TIK parduotuvės papildiniams. OMEX suteikia papildiniams AssetId, kai jie siunčiami parduotuvę

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

  - **Office.Visio.FileCharacteristicsVisio -** Fiksuoja failo ypatybes failo įkrovimo metu „Visio C2R“ ir „Dev16“. Šis įvykis padeda kategorizuoti ir ištaisyti klaidas, susijusias su dokumento ypatybėmis, o tai savo ruožtu leidžia greičiau išspręsti svarbias problemas ir pagerinti klientų pasitenkinimą.

  - **Office.Visio.Shared.BootStats -** Šis įvykis renka „Visio Win32“ programos įkrovos laiką. Jis renka skirtingus įvairių komponentų įkėlimo laukus, pvz., juostos įkelties laiką, programos inicijavimo laiką. Šis įvykis skirtas įkelties našumui matuoti „Visio“.

  - **Office.Visio.Shared.FileOpen -** Šis įvykis renka failo atidarymo statistiką „Visio“. Šis įvykis naudojamas stebėti rodikliams, ar failas atidarytas sėkmingai / nesėkmingai, ir susieti juos su keliomis ypatybėmis, pvz., failo dydžiu. Failo ypatybės leidžia greičiau pašalinti ir šalinti problemas.

  - **Office.Visio.Shared.Filesave -** Šis įvykis renka failo įrašymo statistiką „Visio“. Šis įvykis naudojamas stebėti rodikliams, ar failas įrašytas sėkmingai / nesėkmingai, ir susieti juos su keliomis ypatybėmis, pvz., failo dydžiu ir vieta, kurioje jis įrašytas, pvz., debesis, vietinis įrašymas. Failo ypatybės leidžia greičiau pašalinti ir šalinti problemas.

  - **Office.Visio.Shared.FilesaveAs -** Šis įvykis renka failo įrašymo statistiką „Visio“. Šis įvykis naudojamas stebėti rodikliams, ar failas įrašytas sėkmingai / nesėkmingai, ir susieti juos su keliomis ypatybėmis, pvz., failo dydžiu ir vieta, kurioje jis įrašytas, pvz., debesis, vietinis įrašymas. Failo ypatybės leidžia greičiau pašalinti ir šalinti problemas.

  - **Office.Visio.Shared.PostSave -** Šis įvykis užfiksuoja trikties priežastis, susijusias su failo įrašymu.

  - **Office.Visio.VisioFileSaveAs -** Šis įvykis renka failo įrašymo statistiką „Visio Dev16“. Šis įvykis naudojamas stebėti rodikliams, ar failas įrašytas sėkmingai / nesėkmingai, ir susieti juos su keliomis ypatybėmis, pvz., failo dydžiu ir vieta, kurioje jis įrašytas, pvz., debesis, vietinis įrašymas. Failo ypatybės leidžia greičiau pašalinti ir šalinti problemas.

  - **Office.Visio.VisioFileSaveAsync -** Šis įvykis renka failo asinchroninio įrašymo statistiką „Visio Dev16“. Šis įvykis naudojamas stebėti rodikliams, ar failas asinchroniškai įrašytas sėkmingai / nesėkmingai, ir susieti juos su keliomis ypatybėmis, pvz., failo dydžiu ir vieta, kurioje jis įrašytas, pvz., debesis, vietinis įrašymas.eing saved to e.g., cloud/local. Failo ypatybės leidžia greičiau pašalinti ir šalinti problemas.

  - **Office.Visio.VisioFileSaveSync -** Šis įvykis renka failo asinchroninio įrašymo statistiką „Visio Dev16“. Šis įvykis naudojamas stebėti rodikliams, ar failas sinchroniškai įrašytas sėkmingai / nesėkmingai, ir susieti juos su keliomis ypatybėmis, pvz., failo dydžiu ir vieta, kurioje jis įrašytas, pvz., debesis, vietinis įrašymas. Failo ypatybės leidžia greičiau pašalinti ir šalinti problemas. Šis įvykis padeda stebėti failo įrašymo nesėkmės priežastis.

#### <a name="officeoutlookdesktopexchangepuidandtenantcorrelation"></a>Office.Outlook.Desktop.ExchangePuidAndTenantCorrelation

Kartą per seansą renka vartotojo PUID ir nuomotojo identifikatorių. PUID ir nuomininko ryšys yra būtinas norint suprasti ir diagnozuoti „Outlook“ problemas, atsižvelgiant į nuomotoją.

Renkami šių laukų duomenys:

  - **CollectionTime** - Įvykio laiko žyma

  - **ConnId** - Ryšio identifikatorius: ryšio, analizuojančio PUID ir OMS nuomininko identifikatorių, identifikatorius

  - **OMSTenantId** – „Microsoft“ sugeneruotas unikalusis nuomotojo identifikatorius

  - **PUID** – „Exchange“ PUID, skirtas unikaliai identifikuoti vartotojus

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

#### <a name="officepowerpointdocoperationopen"></a>Office.PowerPoint.DocOperation.Open 

Renkama, kai „PowerPoint“ atidaro failą. Pateikiama sėkmingo veikimo informacija, išsami gedimo informacija, našumo metrika ir pagrindinė informacija apie failą, įskaitant failo formato tipą ir dokumento metaduomenis. Ši informacija būtina norint užtikrinti, kad „PowerPoint“ gali sėkmingai atidaryti failus nemažinant našumo. Tai leidžia mums diagnozuoti bet kokias aptiktas problemas.

Renkami šių laukų duomenys:

  - **Data\_AddDocTelemetryResult -** Ar šis žurnalo įrašas turi visą reikiamą dokumento telemetriją (Data\_Doc\_\* laukus)

  - **Data\_AddDocumentToMruList -** Metodo AddDocumentToMruList vykdymo trukmė

  - **Data\_AlreadyOpened -** Ar šis dokumentas anksčiau buvo atidarytas (to paties proceso seeanso kontekste)

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

  - **Data\_ContentTransaction -** Iš anksto nustatytų reikšmių rinkiniai, kai galima sukurti transakciją (AllowedOnLoadDocument, AllowedOnOpenComplete ir kt.)

  - **Data_CorrelationId -** GUID, kurį ProtocolHandler perdavė programai „PowerPoint“ telemetrijai susieti. ProtocolHandler yra atskiras procesas, kuris tvarko „Office“ saitus, skirtus OS.

  - **Data\_CppUncaughtExceptionCount:long -** Nepriimtos vietinės išimtys, kai veikla buvo vykdoma

  - **Data\_CreateDocumentTimeMS -** Metodo CreateDocumentTimeMS vykdymo trukmė milisekundėmis

  - **Data\_CreateDocumentToken -** Metodo CreateDocumentTimeMS vykdymo trukmė milisekundėmis

  - **Data\_CreateDocumentToW -** Metodo CreateDocumentTimeMS vykdymo trukmė milisekundėmis

  - **Data\_CreateDocWindow -** Metodo CreateDocumentTimeMS vykdymo trukmė milisekundėmis

  - **Data\_CreateLocalTempFile -** Metodo CreateDocumentTimeMS vykdymo trukmė milisekundėmis

  - **Data\_DetachedDuration:long -** veiklos atskyrimo / neveikimo trukmė

  - **Data\_DetermineFileType -** Metodo DetermineFileType vykdymo trukmė milisekundėmis

  - **Data\_Doc\_AccessMode:long -** Kaip buvo atidarytas šis dokumentas (tik skaityti / skaityri ir rašyti)

  - **Data\_Doc\_AssistedReadingReasons:long -** Iš anksto apibrėžtų reikšmių, nurodančių dokumento atidarymo pagalbiniu skaitymo režimu priežastis, rinkinys

  - **Data\_Doc\_ChunkingType:long -** Kaip dokumentas saugomas programoje „SharePoint“

  - **Data\_Doc\_EdpState:long -** Įmonės duomenų apsaugos dokumento būsena

  - **Data\_Doc\_Ext:string -** Dokumento plėtinys

  - **Data\_Doc\_Extension:string -** Dokumento plėtinys

  - **Data\_Doc\_FileFormat:long -** Iš anksto nustatytų failo formato reikšmių rinkinys (detalesnis nei plėtinio)

  - **Data\_Doc\_Fqdn:string – -** Vieta, kurioje saugomas dokumentas (SharePoint.com, live.net) galima tik „Office 365“ domenams

  - **Data\_Doc\_FqdnHash:string – -** Dokumento saugojimo vietos maiša

  - **Data\_Doc\_IdentityTelemetryId:string – -** Unikalus vartotojo GUID

  - **Data\_Doc\_IdentityUniqueId:string –** unikalus tapatybės identifikatorius, kuris buvo naudojamas veiksmui su bendrinamais dokumentais

  - **Data\_Doc\_IOFlags:long –** šablonas įvairiems pateikto dokumento IO, susietiems su žymėmis

  - **Data\_Doc\_IrmRights:long –** iš anksto nustatytų reikšmių, nurodančių kokio tipo informacijos teisių valdymas taikomas šiam dokumentui, rinkinys (Forward, Reply, SecureReader, Edit ir kt.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool –** teisinga, jeigu HTTP antraštė „IsCloudCollabEnabled“jau buvo gauta iš PARINKČIŲ užklausos.

  - **Data\_Doc\_IsIncrementalOpen:bool –** Ar dokumentas buvo atidarytas palaipsniui (nauja funkcija, kuri atidaro dokumentą be būtinybės atsisiųsti visą dokumentą)

  - **Data\_Doc\_IsOcsSupported:bool –** Ar dokumentas palaiko redagavimą vienu metu, naudojant naują OCS paslaugą

  - **Data\_Doc\_IsOpeningOfflineCopy:bool –** Ar dokumentas atidarytas iš vietinės talpyklos?

  - **Data_Doc_IsRtcAlwaysOn –** „true“, jei šiam failui visada yra įjungtas realiojo laiko kanalas (RTC).

  - **Data\_Doc\_IsSyncBacked:bool –** Ar dokumentas atidarytas iš aplanko, naudojančio „OneDrive“ taikomosios programos sinchronizavimo atsarginei kopijai

  - **Data\_Doc\_Location:long –** Iš anksto apibrėžtų dokumento saugojimo vietos reikšmių rinkinys (Local, SharePoint, WOPI, Network ir kt.)

  - **Data\_Doc\_LocationDetails:long –** Iš anksto apibrėžtų išsamesnės vietos informacijos reikšmių rinkinys (Temp folder, Downloads folder, One Drive Documents, One Drive Pictures ir kt.)

  - **Data\_Doc\_NumberCoAuthors:long –** Bendraautorių skaičius dokumento atidarymo metu

  - **Data\_Doc\_PasswordFlags:long –** iš anksto apibrėžtų dokumento užšifravimo slaptažodžiu reikšmių rinkinys (None, Password to read, Password to edit)

  - **Data\_Doc\_ReadOnlyReasons:long –** Iš anksto apibrėžtų dokumento žymėjimo tik skaityti reikšmių rinkinys (Locked on server, final document, password protected to edit ir kt.)

  - **Data\_Doc\_ResourceIdHash:string –** Debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data\_Doc\_ResourceIdHash:string –** Debesyje saugomų dokumentų išteklių identifikatoriaus maiša

  - **Data\_Doc\_ServerProtocol:long –** Iš anksto apibrėžtų protokolo naudojimo kreipimuisi į serverį reikšmių rinkinys (Http, „Cobalt“, WOPI ir kt.)

  - **Data\_Doc\_ServerType:long –** iš anksto apibrėžtų serverio tipo reikšmių rinkinys („SharePoint“, „DropBox“ ar WOPI)

  - **Data\_Doc\_ServerVersion:long -** Ar serveris pagrįstas „Office14“, „Office15“ arba „Office 16“?

  - **Data\_Doc\_SessionId:long –** Generuotas GUID, identifikuojantis dokumento egzempliorių to paties proceso seanso metu

  - **Data\_Doc\_SharePointServiceContext:string –** nepermatoma eilutė, paprastai GridManagerID.FarmID. Tinkanti kliento ir serverio įvykių žurnalų koreliacijai

  - **Data\_Doc\_SizeInBytes:long –** Dokumento dydis baitais

  - **Data\_Doc\_SpecialChars:long –** šablonas, nurodantis specialiuosius dokumento URL arba kelio simbolius

  - **Data\_Doc\_StorageProviderId:string –** Eilutė, nurodanti dokumento saugyklos teikėją, pvz., „DropBox“

  - **Data\_Doc\_StreamAvailability:long –** Iš anksto apibrėžtų dokumentų srauto būsenos reikšmių rinkinys (available, permanently disabled, not available)

  - **Data\_Doc\_UrlHash:string –** Debesyje saugomų dokumentų visų URL maiša

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

  - **Data\_FailureComponent:long -** Iš anksto nustatytų verčių, dėl kurių komponentų įvyko šio protokolo triktis, rinkinys (Conflict, CSI, Internal ir kt.)

  - **Data\_FailureReason:long –** iš anksto nustatytų reikšmių, nurodančių trikties priežastis, rinkinys (FileIsCorrupt, BlockedByAntivirus ir kt.)

  - **Data\_FCreateNew -** Ar tai naujas tuščias dokumentas

  - **Data\_FCreateNewFromTemplate -** Ar tai naujas dokumentas, sukurtas naudojant šablonus

  - **Data_FErrorAfterDocWinCreation:boolean –** ar įvyko bet kokia klaida arba išimtis po dokumento lango sukūrimo.

  - **Data\_FileUrlLocation -** Iš anksto nustatytų reikšmių, kur saugomas dokumentas (NetworkShare, LocalDrive, ServerOther ir kt.) rinkinys

  - **Data\_FirstSlideCompressedSize -** Suglaudintas pirmos skaidrės dalies (paprastai Slide1.xml) dydis

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

  - **Data\_IsOCS -** Ar dokumentas OCS režimu yra paskutinės žinomos būsenos

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

- **ProgramosSeansoVedikl** – konkrečios taikomosios programos seanso pradžios identifikatorius, naudojamas nuo proceso kūrimo pradžios ir iki proceso pabaigos. Jis yra suformuotas kaip standartinis 128 bitų GUID, tik sudarytas iš 4 dalių. Šios keturios dalys eil4s tvarka yra (1) 32 bitų proceso ID (2) 16 bitų seanso ID (3) 16 bitų įkrovos ID (4) 64 bitų proceso sukūrimo laikasm išreikštas UTC 100ns

- **processSessionId** - Atsitiktinai sugeneruotas žinynas, skirtas programos seansui identifikuoti 

- **UTCReplace_AppSessionGuid** - Pastovi Bulio logikos vertė. Visuomet „True“.

#### <a name="officetelemetryengineisprelaunch"></a>Office.TelemetryEngine.IsPreLaunch

Tinka Office UWP taikomosioms programoms.  Šis įvykis sužadinamas, kai „Office“ programa paleidžiama pirmą kartą po atnaujinimo / įdiegimo iš parduotuvės. Tai yra pagrindinės diagnostikos duomenų dalis, naudojama seansui stebėti, ar jis pradėtas.

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

#### <a name="officewordfileopenopencmdfilemrupriv"></a>Office.Word.FileOpen.OpenCmdFileMruPriv

Šis įvykis nurodo „Office Word“ atidaryti dokumentą iš vėliausiai naudoto (MRU) sąrašo. Jame taip pat yra svarbūs failo atidarymo našumo duomenys ir yra programėlės pradžios įvykis vertinant iš vartotojo perspektyvos. Įvykis stebi ar file-open-from-MRU veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti.

Renkami šių laukų duomenys:

  - **Data\_AddDocTelemRes –** nurodo, ar įvykyje galima tinkamai užpildyti kitų dokumentų telemetrijos susijusias reikšmes. Naudojama duomenų kokybės diagnostikai.

  - **Data\_BytesAsynchronous -** Baitų (suglaudintų), kurie, kaip manoma, gali atidaryti failą, skaičius, nepaisant, ar mes juos gausime, kol vartotojas nori pradėti redaguoti arba galbūt įrašyti

  - **Data\_BytesAsynchronousWithWork -** Baitų (suglaudintų), kuriuos naudodami galėtume atidaryti failą, skaičius, tačiau norint, kad tai įvyktų, reikės daug investuoti į kodą

  - **Data\_BytesSynchronous -** Baitų (suglaudintų) skaičius, kuriuos privalome turėti prieš pradėdami atidaryti failą

  - **Data\_BytesUnknown -** Baitų skaičius dokumentų dalyse, kurių nesitikėjome rasti

  - **Data\_DetachedDuration -** Kiek laiko gijoje nebuvo veiklos

  - **Data\_Doc\_AccessMode -** Dokumentas yra skirtas tik skaityti / redaguoti

  - **Data\_Doc\_AssistedReadingReasons -** Iš anksto nustatytų reikšmių rinkinys, kodėl dokumentas buvo atidarytas pagalbiniu skaitymo režimu

  - **Data\_Doc\_ChunkingType –** vienetai, naudojami nuosekliam dokumento atidarymui

  - **Data\_Doc\_EdpState –** dokumentui taikomas elektroninių duomenų apsaugos parametras

  - **Data\_Doc\_Ext –** dokumento plėtinys (docx / xlsb / pptx ir kt.)

  - **Data\_Doc\_FileFormat –** failo formato protokolo versija

  - **Data\_Doc\_Fqdn –** „OneDrive“ arba „SharePoint“ interneto domeno vardas

  - **Data\_Doc\_FqdnHash –** kliento identifikuojamo domeno vardo vienpusė maiša

  - **Data\_Doc\_IOFlags -** Informuoja apie į talpyklą įtrauktas žymes, naudotas užklausos parinktims nustatyti 

  - **Data\_Doc\_IdentityTelemetryId –** atidarymui naudojamos vartotojo tapatybės maiša

  - **Data\_Doc\_InitializationScenario –** įrašo, kaip dokumentas buvo atidarytas

  - **Data\_Doc\_IrmRights –** veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kurie buvo taikyti dokumentui / vartotojui

  - **Data\_Doc\_IsIncrementalOpen -** Žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

  - **Data\_Doc\_IsOcsSupported -** Žyma, nurodanti, kad dokumentas palaikomas bendradarbiavimo tarnybos

  - **Data\_Doc\_IsOpeningOfflineCopy -** Žyma, nurodanti, kad autonominė dokumento kopija atidaryta

  - **Data_Doc_IsRtcAlwaysOn –** „true“, jei šiam failui visada yra įjungtas realiojo laiko kanalas (RTC).

  - **Data\_Doc\_IsSyncBacked -** Žymė, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

  - **Data\_Doc\_Location -** Nurodo, kuri tarnyba teikia dokumentą („OneDrive“, failų serveris, „SharePoint“, kt.)

  - **Data\_Doc\_LocationDetails –** nurodo vietoje saugomo dokumento žinomą aplanką

  - **Data\_Doc\_NumberCoAuthors -** Skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

  - **Data\_Doc\_PasswordFlags –** nurodo, ar nustatytas skaitymo arba skaitymo / rašymo slaptažodžio žymų rinkinys

  - **Data\_Doc\_ReadOnlyReasons -** Priežastys, kodėl dokumentas buvo atidarytas tik kaip skaitomas

  - **Data\_Doc\_ResourceIdHash -** Anonimizuotų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_Doc\_ServerDocId -** Nekintamų anonimizuotų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_Doc\_ServerProtocol -** Protokolo versija, naudojama norint susisiekti su tarnyba

  - **Data\_Doc\_ServerType -** Serverio tipas, siūlantis tarnybą („SharePoint“, „OneDrive“, WOPI ir kt.)

  - **Data\_Doc\_ServerVersion -** Serverio versija, siūlanti tarnybą

  - **Data\_Doc\_SessionId –** nustato konkretų viso seanso dokumentų redagavimo seansą

  - **Data\_Doc\_SharePointServiceContext –** „SharePoint Online“ užklausų diagnostinė informacija

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

  - **Data\_Measurements -** Užkoduota eilutė, kurioje yra skirtingų dalių atidarymo laiko suskirstymas. Skirtas našumui vertinti.

  - **Data\_MoveDisabledReason -** Klaida, kuri yra išjungia dokumento perkėlimą

  - **Data\_MoveFlightEnabled -** Ar įjungta perkėlimo testavimo funkcija

  - **Data\_PartsUnknown -** Dokumentų dalių, iš kurių nepavyko gauti duomenų, skaičius

  - **Data\_RecoverableFailureInitiationLocationTag -** Unikali kodo iškvietimo vietos žymė, naudojama vietai kode, kurioje stengiamės sutvarkyti failą prieš jį atidarant, identifikuoti

  - **Data\_RenameDisabledReason -** Klaida, atsirandanti, kai pervardijimas šiam dokumentui išjungtas

  - **Data\_RenameFlightEnabled -** Ar įjungta pervardijimo testavimo funkcija

  - **Data\_SecondaryTag -** Unikali kodo iškvietimo vietos žymė, naudojama papildomiems trikties duomenims atidaryti

  - **Data\_TemplateFormat -** Šablono failo formatas, kuriuo pagrįstas dokumentas.

  - **Data\_UsesNormal -** Nurodo, ar atidarytas dokumentas pagrįstas įprastu šablonu

#### <a name="officewordfileopenopenffileopenxstzcore"></a>Office.Word.FileOpen.OpenFFileOpenXstzCore

Šis įvykis nurodo, kad „Office Word“ atidaro dokumentą, kurį vartotojas dukart spustelėjo. Jame taip pat yra svarbūs failo atidarymo našumo duomenys ir yra programėlės pradžios įvykis vertinant iš vartotojo perspektyvos. Įvykis stebi, ar file-open-from-file-double-click veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti.

Renkami šių laukų duomenys:

  - **Data\_AddDocTelemRes -** Nurodo, ar įvykyje galima tinkamai užpildyti kitų dokumentų telemetrijos susijusias reikšmes. Naudojama duomenų kokybės diagnostikai

  - **Data\_BytesAsynchronous -** Baitų (suglaudintų), kurie, kaip manoma, gali atidaryti failą, skaičius, nepaisant, ar mes juos gausime, kol vartotojas nori pradėti redaguoti arba galbūt įrašyti

  - **Data\_BytesAsynchronousWithWork -** Baitų (suglaudintų), kuriuos naudodami galėtume atidaryti failą, skaičius, tačiau norint, kad tai įvyktų, reikės daug investuoti į kodą

  - **Data\_BytesSynchronous -** Baitų (suglaudintų) skaičius, kuriuos privalome turėti prieš pradėdami atidaryti failą

  - **Data\_BytesUnknown -** Baitų skaičius dokumentų dalyse, kurių nesitikėjome rasti

  - **Data\_DetachedDuration -** Kiek laiko gijoje nebuvo veiklos

  - **Data\_Doc\_AccessMode -** Dokumentas yra skirtas tik skaityti / redaguoti

  - **Data\_Doc\_AssistedReadingReasons -** Iš anksto nustatytų reikšmių rinkinys, kodėl dokumentas buvo atidarytas pagalbiniu skaitymo režimu

  - **Data\_Doc\_ChunkingType –** vienetai, naudojami nuosekliam dokumento atidarymui

  - **Data\_Doc\_EdpState –** dokumentui taikomas elektroninių duomenų apsaugos parametras

  - **Data\_Doc\_Ext –** dokumento plėtinys (docx / xlsb / pptx ir kt.)

  - **Data\_Doc\_FileFormat –** failo formato protokolo versija

  - **Data\_Doc\_Fqdn –** „OneDrive“ arba „SharePoint“ interneto domeno vardas

  - **Data\_Doc\_FqdnHash –** kliento identifikuojamo domeno vardo vienpusė maiša

  - **Data\_Doc\_IOFlags -** Informuoja apie į talpyklą įtrauktas žymes, naudotas užklausos parinktims nustatyti 

  - **Data\_Doc\_IdentityTelemetryId -** Vartotojo tapatybės, naudojamos atidarymui, vienpusė maiša

  - **Data\_Doc\_InitializationScenario -** Įrašo, kaip dokumentas buvo atidarytas

  - **Data\_Doc\_IrmRights –** veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kurie buvo taikyti dokumentui / vartotojui

  - **Data\_Doc\_IsIncrementalOpen -** Žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

  - **Data\_Doc\_IsOcsSupported -** Žyma, nurodanti, kad dokumentas palaikomas bendradarbiavimo tarnybos

  - **Data\_Doc\_IsOpeningOfflineCopy -** Žyma, nurodanti, kad autonominė dokumento kopija atidaryta

  - **Data_Doc_IsRtcAlwaysOn –** „true“, jei šiam failui visada yra įjungtas realiojo laiko kanalas (RTC).

  - **Duomenų\_ad\_IsSyncBacked -** žyma, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

  - **Data\_Doc\_Location –** nurodo tarnybą, pateikusią dokumentą („OneDrive“, „File Server“, „SharePoint“ ir kt.)

  - **Data\_Doc\_LocationDetails –** nurodo vietoje saugomo dokumento žinomą aplanką

  - **Data\_Doc\_NumberCoAuthors -** Skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

  - **Data\_Doc\_PasswordFlags –** nurodo, ar nustatytas skaitymo arba skaitymo / rašymo slaptažodžio žymų rinkinys

  - **Data\_Doc\_ReadOnlyReasons -** Priežastys, kodėl dokumentas buvo atidarytas tik kaip skaitomas

  - **Data\_Doc\_ResourceIdHash -** Anonimizuotų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_Doc\_ServerDocId -** Nekintamų anonimizuotų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_Doc\_ServerProtocol -** Protokolo versija, naudojama norint susisiekti su tarnyba

  - **Data\_Doc\_ServerType –** tarnybą siūlančio serverio tipas („SharePoint“, „OneDrive“, WOPI ir kt.)

  - **Data\_Doc\_ServerVersion -** Serverio versija, siūlanti tarnybą

  - **Data\_Doc\_SessionId -** Serverio versija, siūlanti tarnybą

  - **Data\_Doc\_SharePointServiceContext-**

  - **Data\_Doc\_SizeInBytes -** Dokumento dydžio indikatorius

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

  - **Data\_Measurements -** Užkoduota eilutė, kurioje yra skirtingų dalių atidarymo laiko suskirstymas. Skirtas našumui vertinti.

  - **Data\_MoveDisabledReason -** Klaida, kuri yra išjungia dokumento perkėlimą

  - **Data\_MoveFlightEnabled -** Ar įjungta perkėlimo testavimo funkcija

  - **Data\_PartsUnknown -** Dokumentų dalių, iš kurių nepavyko gauti duomenų, skaičius

  - **Data\_RecoverableFailureInitiationLocationTag -** Unikali kodo iškvietimo vietos žymė, naudojama vietai kode, kurioje stengiamės sutvarkyti failą prieš jį atidarant, identifikuoti

  - **Data\_RenameDisabledReason -** Klaida, atsirandanti, kai pervardijimas šiam dokumentui išjungtas

  - **Data\_RenameFlightEnabled -** Ar įjungta pervardijimo testavimo funkcija

  - **Data\_SecondaryTag -** Unikali kodo iškvietimo vietos žymė, naudojama papildomiems trikties duomenims atidaryti.

  - **Data\_TemplateFormat -** Šablono failo formatas, kuriuo pagrįstas dokumentas.

  - **Data\_UsesNormal -** Nurodo, ar atidarytas dokumentas pagrįstas įprastu šablonu


#### <a name="officewordfileopenopenifrinitargs"></a>Office.Word.FileOpen.OpenIfrInitArgs

Šis įvykis nurodo, kad „Office Word“ atidaro dokumentą naudojant COM aktyvinimą arba komandinę eilutę. Jame taip pat yra svarbūs failo atidarymo našumo duomenys ir yra programėlės pradžios įvykis vertinant iš vartotojo perspektyvos. Įvykis stebi, ar file-open-from-command-line veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti.

Renkami šių laukų duomenys:

  - **Data\_AddDocTelemRes –** nurodo, ar įvykyje galima tinkamai užpildyti kitų dokumentų telemetrijos susijusias reikšmes. Naudojama duomenų kokybės diagnostikai.

  - **Data\_BytesAsynchronous -** Baitų (suglaudintų), kurie, kaip manoma, gali atidaryti failą, skaičius, nepaisant, ar mes juos gausime, kol vartotojas nori pradėti redaguoti arba galbūt įrašyti.

  - **Data\_BytesAsynchronousWithWork -** Baitų (suglaudintų), kuriuos naudodami galėtume atidaryti failą, skaičius, tačiau norint, kad tai įvyktų, reikės daug investuoti į kodą

  - **Data\_BytesSynchronous -** Baitų (suglaudintų) skaičius, kuriuos privalome turėti prieš pradėdami atidaryti failą

  - **Data\_BytesUnknown -** Baitų skaičius dokumentų dalyse, kurių nesitikėjome rasti.

  - **Data\_Doc\_AccessMode -** Dokumentas yra skirtas tik skaityti / redaguoti

  - **Data\_Doc\_AssistedReadingReasons –** iš anksto nustatytų dokumento atidarymo pagalbiniu skaitymo režimu priežasčių reikšmių rinkinys

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

  - **Data_Doc_IsRtcAlwaysOn –** „true“, jei šiam failui visada yra įjungtas realiojo laiko kanalas (RTC).

  - **Duomenų\_ad\_IsSyncBacked -** žyma, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

  - **Data\_Doc\_Location -** Nurodo, kuri tarnyba teikia dokumentą („OneDrive“, failų serveris, „SharePoint“)

  - **Data\_Doc\_LocationDetails -** Nurodo, kuriuose žinomuose aplankuose yra vietoje saugomų dokumentų

  - **Data\_Doc\_NumberCoAuthors -** Skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

  - **Data\_Doc\_PasswordFlags –** nurodo, ar nustatytas skaitymo arba skaitymo / rašymo slaptažodžio žymų rinkinys

  - **Data\_Doc\_ReadOnlyReasons -** Priežastys, kodėl dokumentas buvo atidarytas tik kaip skaitomas

  - **Data\_Doc\_ResourceIdHash -** Anonimizuotų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

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

  - **Data\_PartsUnknown -** Dokumentų dalių, iš kurių nepavyko gauti duomenų, skaičius

  - **Data\_RecoverableFailureInitiationLocationTag -** Unikali kodo iškvietimo vietos žymė, naudojama vietai kode, kurioje stengiamės sutvarkyti failą prieš jį atidarant, identifikuoti

  - **Data\_RenameDisabledReason -** Klaida, atsirandanti, kai pervardijimas šiam dokumentui išjungtas

  - **Data\_RenameFlightEnabled -** Ar įjungta pervardijimo testavimo funkcija

  - **Data\_SecondaryTag -** Unikali kodo iškvietimo vietos žymė, naudojama papildomiems trikties duomenims atidaryti.

  - **Data\_TemplateFormat -** Šablono failo formatas, kuriuo pagrįstas dokumentas.

  - **Data\_UsesNormal -** Nurodo, ar atidarytas dokumentas pagrįstas įprastu šablonu.


#### <a name="officewordfileopenopenloadfile"></a>Office.Word.FileOpen.OpenLoadFile

Šis įvykis nurodo, kad „Office Word“ atidaro dokumentą naudojant dialogo langą Atidaryti. Jame taip pat yra svarbūs failo atidarymo našumo duomenys ir yra programėlės pradžios įvykis vertinant iš vartotojo perspektyvos. Įvykis stebi ar file-open-from-the-open-file-dialogas veikia tinkamai. Jis taip pat naudojamas mėnesio aktyviems vartotojams / įrenginiams ir debesies patikimumo rodikliams apskaičiuoti.

Renkami šių laukų duomenys:

  - **Data\_AddDocTelemRes –** nurodo, ar įvykyje galima tinkamai užpildyti kitų dokumentų telemetrijos susijusias reikšmes. Naudojama duomenų kokybės diagnostikai.

  - **Data\_BytesAsynchronous -** Baitų (suglaudintų), kurie, kaip manoma, gali atidaryti failą, skaičius, nepaisant, ar mes juos gausime, kol vartotojas nori pradėti redaguoti arba galbūt įrašyti

  - **Data\_BytesAsynchronousWithWork -** Baitų (suglaudintų), kuriuos naudodami galėtume atidaryti failą, skaičius, tačiau norint, kad tai įvyktų, reikės daug investuoti į kodą

  - **Data\_BytesSynchronous -** Baitų (suglaudintų) skaičius, kuriuos privalome turėti prieš pradėdami atidaryti failą

  - **Data\_BytesUnknown -** Baitų skaičius dokumentų dalyse, kurių nesitikėjome rasti

  - **Data\_DetachedDuration -** Kiek laiko gijoje nebuvo veiklos

  - **Data\_Doc\_AccessMode –** dokumentas yra skirtas tik skaityti / redaguoti

  - **Data\_Doc\_AssistedReadingReasons –** iš anksto nustatytų dokumento atidarymo pagalbiniu skaitymo režimu priežasčių reikšmių rinkinys

  - **Data\_Doc\_ChunkingType –** vienetai, naudojami nuosekliam dokumento atidarymui

  - **Data\_Doc\_EdpState –** dokumentui taikomas elektroninių duomenų apsaugos parametras

  - **Data\_Doc\_Ext –** dokumento plėtinys (docx / xlsb / pptx ir kt.)

  - **Data\_Doc\_FileFormat –** failo formato protokolo versija

  - **Data\_Doc\_Fqdn –** „OneDrive“ arba „SharePoint“ interneto domeno vardas

  - **Data\_Doc\_FqdnHash -** Kliento identifikuojamo domeno vardo vienpusė maiša

  - **Data\_Doc\_IdentityTelemetryId -** Vartotojo tapatybės, naudojamos atidaryti, vienpusė maiša

  - **Data\_Doc\_InitializationScenario -** Įrašo, kaip dokumentas buvo atidarytas

  - **Data\_Doc\_IOFlags -** Informuoja apie į talpyklą įtrauktas žymes, naudotas užklausos parinktims nustatyti 

  - **Data\_Doc\_IrmRights –** veiksmai, leidžiami elektroninių duomenų apsaugos strategijos, kurie buvo taikyti dokumentui / vartotojui

  - **Data\_Doc\_IsIncrementalOpen -** Žymė, nurodanti, kad dokumentas buvo palaipsniui atidarytas

  - **Data\_Doc\_IsOcsSupported -** Žyma, nurodanti, kad dokumentas palaikomas bendradarbiavimo tarnybos

  - **Data\_Doc\_IsOpeningOfflineCopy -** Žyma, nurodanti, kad autonominė dokumento kopija atidaryta

  - **Data_Doc_IsRtcAlwaysOn –** „true“, jei šiam failui visada yra įjungtas realiojo laiko kanalas (RTC).

  - **Duomenų\_ad\_IsSyncBacked -** žyma, nurodanti, kad automatiškai sinchronizuota dokumento kopija yra kompiuteryje

  - **Data\_Doc\_Location –** nurodo tarnybą, pateikusią dokumentą („OneDrive“, „File Server“, „SharePoint“ ir kt.)

  - **Data\_Doc\_LocationDetails –** nurodo vietoje saugomo dokumento žinomą aplanką

  - **Data\_Doc\_NumberCoAuthors -** Skaičiuoja bendro redagavimo seanso metu bendradarbiaujančių vartotojų skaičių

  - **Data\_Doc\_PasswordFlags –** nurodo, ar nustatytas skaitymo arba skaitymo / rašymo slaptažodžio žymų rinkinys

  - **Data\_Doc\_ReadOnlyReasons -** Priežastys, kodėl dokumentas buvo atidarytas tik kaip skaitomas

  - **Data\_Doc\_ResourceIdHash -** Anonimizuotų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_Doc\_ServerDocId -** Nekintamų anonimizuotų dokumentų identifikatorius, naudojamas problemoms diagnozuoti

  - **Data\_Doc\_ServerProtocol -** Protokolo versija, naudojama norint susisiekti su tarnyba

  - **Data\_Doc\_ServerType -** Serverio tipas, siūlantis tarnybą („SharePoint“, „OneDrive“, WOPI ir kt.)

  - **Data\_Doc\_ServerVersion -** Serverio versija, siūlanti tarnybą

  - **Data\_Doc\_SessionId –** nustato konkretų viso seanso dokumentų redagavimo seansą

  - **Data\_Doc\_SharePointServiceContext –** „SharePoint Online“ užklausų diagnostinė informacija

  - **Data\_Doc\_SizeInBytes –** dokumento dydžio indikatorius

  - **Data\_Doc\_SpecialChars –** dokumento URL arba kelio specialiųjų simbolių indikatorius

  - **Data\_Doc\_StreamAvailability –** indikatorius, nurodantis, ar dokumentų srautas yra pasiekiamas arba išjungtas

  - **Data\_Doc\_SyncBackedType –** dokumento tipo indikatorius (vietinis arba pagrįstas tarnyba)

  - **Data\_Doc\_UrlHash -** Vienpusė maiša, skirta „naïve“ dokumento identifikatoriui

  - **Data\_EditorDisablingRename -** Pirmojo redaktoriaus, dėl kurio buvo išjungtas pervardijimas, identifikatorius

  - **Data\_EditorsCount -** Dokumento redaktorių skaičius

  - **Data\_ForceReadWriteReason -** Sveikojo skaičiaus vertė, nurodanti priežastį, kodėl failas buvo priverstinai atidarytas skaitymo / rašymo režimu

  - **Data\_FSucceededAfterRecoverableFailure -** Nurodo, kad atidaryti pavyko pašalinus triktį, įvykusią atidarant dokumentą

  - **Data\_LastLoggedTag -** Unikali kodo iškvietimo žymės vieta, naudojama nustatyti, kada dukart nepavyksta bandymas įrašyti (naudojama duomenų kokybės diagnostikai)

  - **Data\_LinkStyles -** Nurodo, ar mes susieti su šablono stiliais

  - **Data\_MainPdod -** Dokumento identifikatorius vykstant „Office Word“ procesui.

  - **Data\_Measurements -** Užkoduota eilutė, kurioje yra skirtingų dalių atidarymo laiko suskirstymas. Skirtas našumui vertinti.

  - **Data\_MoveDisabledReason -** Klaida, kuri yra išjungia dokumento perkėlimą

  - **Data\_MoveFlightEnabled -** Ar įjungta perkėlimo testavimo funkcija

  - **Data\_PartsUnknown -** Dokumentų dalių, iš kurių nepavyko gauti duomenų, skaičius

  - **Data\_RecoverableFailureInitiationLocationTag -** Unikali kodo iškvietimo vietos žymė, naudojama vietai kode, kurioje stengiamės sutvarkyti failą prieš jį atidarant, identifikuoti

  - **Data\_RenameDisabledReason -** Klaida, atsirandanti, kai pervardijimas šiam dokumentui išjungtas

  - **Data\_RenameFlightEnabled -** Ar įjungta pervardijimo testavimo funkcija

  - **Data\_SecondaryTag -** Unikali kodo iškvietimo vietos žymė, naudojama papildomiems trikties duomenims atidaryti

  - **Data\_TemplateFormat -** Šablono failo formatas, kuriuo pagrįstas dokumentas

  - **Data\_UsesNormal -** Nurodo, ar atidarytas dokumentas pagrįstas įprastu šablonu


### <a name="office-accessibility-configuration-subtype"></a>*„Office“ pritaikymo neįgaliesiems konfigūracijos potipis*

„Office“ pritaikymo neįgaliesiems funkcijos

#### <a name="officeaccessibilityaccessibilitytoolsessionpresencewin32"></a>Office.Accessibility.AccessibilityToolSessionPresenceWin32

Leidžia mums nustatyti, ar vartotojas turi pagalbinių technologijų įrankį ir jo pavadinimą. Tai leidžia mums suprasti, ar „Office“ vartotojui kyla konkrečių pagalbinių technologijų įrankio problemų.

Renkami šių laukų duomenys:

  - **Data\_Data\_Jaws -** Nurodo, ar „Jaws“ veikė seanso metu**Data\_Data\_Magic -** Nurodo, ar „Magic“ veikė seanso metu

  - **Data\_Data\_Magnify -** Nurodo, ar Didinimas veikė seanso metu

  - **Data\_Data\_Narrator -** Nurodo, ar Diktorius veikė seanso metu

  - **Data\_Data\_Narrator -** Nurodo, ar Diktorius veikė seanso metu

  - **Data\_Data\_SA -** Nurodo, ar SA veikė seanso metu

  - **Data\_Data\_Supernova -** Nurodo, ar „Supernova“ veikė seanso metu

  - **Data\_Data\_SuperNovaessSuite -** Nurodo, ar „SuperNovaAccessSuite“ veikė seanso metu

  - **Data\_Data\_WinEyes -** Nurodo, ar „WinEyes“ veikė seanso metu

  - **Data\_Data\_ZoomText -** Nurodo, ar Teksto mastelis veikė seanso metu

#### <a name="officewordaccessibilitylearningtoolsreadaloudplayreadaloud"></a>Office.Word.Accessibility.LearningTools.ReadAloud.PlayReadAloud

Šis įvykis nurodo, ar „Office Word“ garsiai perskaito tekstą dokumente. Šis įvykis yra pasikartojantis naudojant pritaikymo neįgaliesiems funkciją, kuri leidžia „Microsoft“ įvertinti skaitymo garsiai būseną.

Renkami šių laukų duomenys:

  - **Data\_CharacterCount -** dokumento simbolių skaičius

  - **Data\_CharactersWithSpaceCount -** dokumento simbolių ir tarpų skaičius

  - **Data\_IsPageCountInProgress -** Skaičiuojami puslapiai

  - **Data\_LineCount -** Dokumento eilučių skaičius

  - **Data\_PageCount -** Dokumento puslapių skaičius

  - **Data\_ParagraphCount -** Dokumento pastraipų skaičius

  - **Data\_Play -** Ar tai pirmas kartas, kai „Word“ perskaito garsiai

  - **Data\_ViewKind -** Dokumento peržiūros tipas

  - **Data\_WordCount -** Dokumento žodžių skaičius

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

  - **Data_ControllerConnectedServicesState –** papildomų prijungtų funkcijų vartotojo politikos parametras

  - **Data_DownloadedContentServiceGroupState –** atsisiųsto turinio vartotojo parametras 
 
  - **Data_ForwardLinkId –** saitas į vartotojo scenarijaus privatumo dokumentaciją

  - **Data_HRESULT –** klaidų, įvykusių sąveikos su privatumo dialogo langu metu, įrašas

  - **Data_IsEnterpriseUser –** vartotojo licencijos kategorija

  - **Data_OfficeServiceConnectionState –** prijungtų tarnybų vartotojo parametras

  - **Data_RecordRegistry –** įmonės privatumo dialogo lango rodymo įrašas

  - **Data_Scenario –** pirmojo paleidimo scenarijus pagal vartotojo licenciją ir kategoriją

  - **Data_SeenInsidersDialog –** „Insider“ privatumo dialogo lango rodymo įrašas

  - **Data_SendTelemetryOption –** telemetrijai skirtas vartotojo parametras

  - **Data_SendTelemetryOptionPolicy –** telemetrijai skirtas vartotojo politikos parametras

  - **Data_UserCategory –** vartotojo paskyros tipas  

  - **Data_UserCCSDisabled –** vartotojo nepaisymas papildomoms pasirinktinėms prisijungus naudojamoms funkcijoms

   - **Data_UserContentServiceGroupState –** vartotojo parametrai, skirti turiniui analizuoti

  - **Data_WillShowDialogs –** vartotojo, kuriam reikia matyti privatumo pirmojo paleidimo dialogo langus, įrašas



## <a name="product-and-service-performance-data-events"></a>Produktų ir tarnybų našumo duomenų įvykiai

Toliau pateikiami šios kategorijos duomenų potipiai:
- [Netikėtas taikomosios programos uždarymas (gedimas)](#unexpected-application-exit-crash-subtype)
- [Taikomosios programos funkcijų našumas](#application-feature-performance-subtype)
- [Taikomosios programos veiklos klaida](#application-activity-error-subtype)

### <a name="unexpected-application-exit-crash-subtype"></a>*Netikėtas taikomosios programos uždarymo (gedimas) potipis*

Nenumatytas programų uždarymas ir programos būsena, kai taip nutinka.

#### <a name="officeappdomainunhandledexceptionhandlerfailed"></a>Office.AppDomain.UnhandledExceptionHandlerFailed

Renka bet kokių neapdorojamų išimčių informaciją naudodama duomenų srautinio duomenų siųstuvo programą. Šie duomenys naudojami programos sveikatai stebėti. Šis įvykis sugeneruojamas iš „Microsoft“ srautinio duomenų siųstuvo, skirto „Excel“ papildiniui.

Renkami šių laukų duomenys:

- **Exception** – Išimties iškvietimų rietuvė

- **Event Name** – Įvykio pavadinimas yra įvykio kategorija ir įvykio etiketė.

#### <a name="officeextensibilitycomaddinunhandledexception"></a>Office.Extensibility.COMAddinUnhandledException

Įvykis generuojamas, kai sugenda COM papildinys

Kompiuterio „Analytics“: naudojama kaip skaitiklis apskaičiuojant konkrečių įmonių sveikatos būklę papildiniams, kurie naudojami bandomajam rezultatui, jei papildinys „parengtas atnaujinti“ gamybos metu.  
Visuotinės įžvalgos: naudojama apskaičiuoti visuotiniam, su įmone nesusijusiam papildinio „pasirengimui“, papildinys tada skelbiamas readyforwindows.com ir kitose priemonėse, pvz., „Readiness Toolkit“

Renkami šių laukų duomenys:

**ScopeId** – taikoma dabartinės gijos apimtis

**Method** – „Office“ metodas, kur įvyko išimtis

**Interface** – „Office“ sąsaja, kur įvyko išimtis

**AddinId** – papildinio klasės ID

**AddinProgId** – papildinio programos ID

**AddinFriendlyName** – papildinio draugiškas vardas

**Add-inTimeDateStamp** – papildinio laiko žyma iš DLL metaduomenų

**AddinVersion** – papildinio versija

**AddinFileName** – papildinio failo vardas, išskyrus failo kelią

**VSTOAddIn** – ar papildinys yra VSTO

**Add-inconnectFlag** – dabartinio įkėlimo veiksena

**LoadAttempts** – bandymų įkelti papildinį skaičius

#### <a name="officeextensibilityvbatelemetrybreak"></a>Office.Extensibility.VbaTelemetryBreak

Įvykis, generuojamas, kai makrokomandas palaikantis failas susiduria su kompiliavimo arba vykdymo klaida

Kompiuterio „Analytics“: naudojama kaip skaitiklis apskaičiuojant konkrečių įmonių sveikatos būklę makrokomandų tipams (pvz., „Word“, „Excel“ makrokomandoms ir pan.), kurios naudojamos bandomajam rezultatui, jei papildinys „parengtas atnaujinti“ gamybos metu.

Renkami šių laukų duomenys:

**TagId** – telemetrijos žymės ID

**BreakReason** – nurodyta trikties priežastis (vykdymo, kompiliavimo, kita klaida)

**SolutionType** – sprendimo tipas (dokumentas, šablonas, programos papildinys, COM papildinys)

**Data.ErrorCode** – klaidos kodas, kurį nurodė VBA modulis

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

#### <a name="officepowerpointsession"></a>**Office.PowerPoint.Session**

Renka kiekvieno „PowerPoint“ seanso funkcijos naudojimą.Šie duomenys naudojami apskaičiuoti „PowerPoint“ netikėto uždarymo santykį naudojant funkciją. „PowerPoint“ netikėto uždarymo santykis yra pagrindinis signalas, užtikrinantis, kad „PowerPoint“ veikia taip, kaip tikėtasi.

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

Renkama, kokia funkcija buvo naudota dokumente, kai „PowerPoint“ netikėtai uždaryta. Šios funkcijos apima skaidrių demonstraciją, dokumento atidarymą, įrašymą, redagavimą, bendraatorystę, išjungimą. Ši informacija yra labai svarbi norint pastebėti, kada „PowerPoint“ netikėtai uždaroma naudojant funkciją. „Microsoft“ naudoja šiuos duomenis, kad diagnozuotų problemą, siekiant užtikrinti kad „PowerPoint“ veikia tinkamai.

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

Renkama, kokią funkciją naudojote, kai „PowerPoint“ seansas buvo netikėtai uždarytas.Ši informacija yra labai svarbi norint pastebėti, kada „PowerPoint“ netikėtai uždaroma. „Microsoft“ naudoja šiuos duomenis, kad diagnozuotų problemą, siekiant užtikrinti kad „PowerPoint“ veikia tinkamai.

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

#### <a name="officethisaddinstartupfailed"></a>Office.ThisAddIn.StartupFailed

Renka išimties informaciją, kuri įvyko paleidžiant Srautinio duomenų siųstuvo programą. Šie duomenys naudojami programos sveikatai stebėti. Šis įvykis sugeneruojamas iš „Microsoft“ srautinio duomenų siųstuvo, skirto „Excel“ papildiniui.

Renkami šių laukų duomenys:

- **Exception** – Išimties iškvietimų rietuvė

- **Event Name** – Įvykio pavadinimas yra įvykio kategorija ir įvykio etiketė.


### <a name="application-feature-performance-subtype"></a>*Taikomosios programos funkcijų našumo potipis*

Scenarijų, tokių kaip programos paleidimas ar failo atidarymas, prastas atsakymo laikas ar našumas.

#### <a name="officemanageabilityserviceapplypolicy"></a>Office.Manageability.Service.ApplyPolicy

Svarbi telemetrija, skirta gedimams stebėti\\Sėkmingas debesijos strategijos nustatymų registravimas. „LastError“ nurodo, kodėl ir kur nepavyko taikyti registro strategijos.

Renkami šių laukų duomenys:

  - **Data.ApplyLogMsg** – išimties pranešimas, jei strategija buvo taikoma

  - **Data.Cid** – dinamiškai sukurtas sąsajos identifikatorius, siunčiamas į tarnybą, kai buvo atliktas tarnybos iškvietimas, kad gautų debesijos strategiją. Naudojamas nustatyti, kuris iškvietimas sukėlė problemą taikant strategiją debesyje.

  - **Data.Last Error** – Viena iš penkių eilučių reikšmių (surašytuvai), norint užregistruoti, kuris strategijos taikymo etapas buvo įvykdytas, kai įvyko išimtis

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

#### <a name="officeperformanceboot"></a>Office.Performance.Boot

Surinkta taikomosios programos „Office“ paleidimo metu. Nurodoma, ar paleidimas buvo pradėtas atidarant failą, ar paleidžiant per meniu Pradžia, ar tai buvo pirmasis taikomosios programos paleidimas, kiek atminties naudoja taikomoji programa, ir ar vartotojui buvo parodyta blokuojama vartotojo sąsaja. Naudojama išmatuoti, kaip greitai veikia taikomosios programos „Office“ paleidimas ir kiek atminties naudojama paleidimo metu, kad užtikrinti priimtiną vartotojo patirtį.

Renkami šių laukų duomenys:

  - **Activationkind** – ar taikomoji programa buvo pradėta paleidžiant meniu Pradžia, atidarant failą arba naudojant OLE automatizavimą.

  - **Firstboot** – ar tai buvo pirmas taikomosios programos įkrovimas.

  - **Initializationduration** – pirmojo „Office“ inicijavimo proceso trukmė mikrosekundėmis.

  - **InterruptionMessageId** – ar paleidimas buvo pertrauktas dialogo lango, prašančio naudotojo atlikti įvestį, dialogo lango ID.

  - **Totalworkingsetmb** – proceso darbinio paketo atminties kiekis megabaitais.

  - **VirtualSetMB** – proceso paketo atminties kiekis megabaitais. (tik „MacOS“/ „iOS“)

  - **Workingsetpeakmb** – didžiausias atminties kiekis megabaitais, kuris iki šiol yra buvęs proceso darbiniame rinkinyje.

#### <a name="officeuxofficeinsidercanshowofficeinsiderslab"></a>Office.UX.OfficeInsider.CanShowOfficeInsiderSlab

Veiklos stebėjimas nustatyti, ar „Office Insider“ informacijos dalis gali būti rodoma vartotojui „Office Backstage UI“ skirtuke Paskyra.

Renkami šių laukų duomenys:

  - **Data_CanShow** – nurodo, ar „Office Insider“ informacijos dalis gali būti rodoma vartotojui „Office Backstage UI“ skirtuke Paskyra.
  
  - **Data_Event** – nenaudojamas

  - **Data_EventInfo** – nenaudojamas

  - **Data_Reason** – nenaudojamas

#### <a name="officeuxofficeinsidershowofficeinsiderdlg"></a>Office.UX.OfficeInsider.ShowOfficeInsiderDlg

„Office Insider“ dialogo lango naudojimo ir vykdymo veiklos sekimas.

Renkami šių laukų duomenys:

  - **Data_AcceptedContactMeNew** – kai pasirenkamas „Insider“ lygis, bei kai buvo sėkmingai įrašytas vartotojo pasirinkimas, nurodo, ar vartotojas sutiko, kad su juo susisiektų „Microsoft“.

  - **Data_DialogChoice** = nenaudojamas
  
  - **Data_DialogId** = nenaudojamas
  
  - **Data_Event** – nenaudojamas
  
  - **Data_EventInfo** – nenaudojamas
  
  - **Data_InsiderLevel** – „Insider“ lygis, kai vartotojui pirmą kartą rodomas dialogo langas.
  
  - **Data_InsiderLevelNew** – naujas vartotojo pasirinktas „Insider“ lygis.
  
  - **Data_IsInternalUser** – nurodo, ar taikomoji programa vykdoma naudojant @microsoft.com paskyros kredencialus.
  
  - **Data_IsInternalUser** – nurodo, ar kodas gali nustatyti, ar taikomoji programa vykdoma naudojant @microsoft.com paskyros kredencialus.
  
  - **Data_OpenNewsletterWebpage** – kai įgalinta „Office Insider“ naujienlaiškio prenumeratos funkcija ir vartotojas pereina į „Insider“ lygį iš gamybos, nurodo, ar buvo pradėtas naršyklės nukreipimas į „Office Insider“ naujienlaiškio prenumeratos saitą.

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

### <a name="application-activity-error-subtype"></a>*Taikomosios programos veiklos klaidos potipis*

Funkcijos ar vartotojo patirties veikimo klaidos.

#### <a name="officeairspacebackendwin32graphicsdriversofthang"></a>Office.AirSpace.Backend.Win32.GraphicsDriverSoftHang 

Padeda „Microsoft“ atskirti ilgą vaizdo plokštės tvarkyklės „pakibimą“ nuo trumpo, o tai savo ruožtu padeda priimti sprendimus apie tai, kurios vaizdo plokštės tvarkyklės gali turėti problemų. Dėl vartotojo vaizdo plokštės tvarkyklės„pakibo“„Office“, bet „pakibimo“ poveikis dar nežinomas

Renkami šių laukų duomenys:

  - **Data\_InDeviceCall** – Vaizdo plokštės metodas, dėl kurio įvyko „pakibimas“

  - **Data\_Timeout** – kiek laiko truko „pakibimas“

#### <a name="officegraphicsarcexceptions"></a>Office.Graphics.ARCExceptions 

Ši išimties ataskaitų teikimo informacija yra svarbi vertinant bendrą grafikos rietuvės sveikatą, taip pat nustatant kodo dalis, kuriose dažniai pasitaiko gedimų, siekiant nustatyti tyrimo prioritetą. Ši išimties ataskaitų teikimo informacija yra svarbi vertinant bendrą grafikos rietuvės sveikatą, taip pat nustatant kodo dalis, kuriose dažniai pasitaiko gedimų. Tai padeda inžinieriui nustatyti, kurios generavimo problemos turi įtakos daugeliui vartotojų, leidžia mums nustatyti mūsų prioritetą sprendžiant problemas, kurios aktualios didžiausiam vartotojų skaičiui.

Renkami šių laukų duomenys:

  - **Data\_HResult** – Trikties pateiktas klaidos kodas

  - **Data\_TagCount** – Visų įvykusių klaidų skaičius

  - **Data\_TagID** – Įvykusios klaidos identifikatorius

#### <a name="officeoutlookdesktopcalendaracceptcalsharenavigatetosharedfoldererror"></a>Office.Outlook.Desktop.Calendar.AcceptCalShareNavigateToSharedFolder\_Klaida

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

  - **CountExceptionForward- Persiųstų susitikimų išimčių skaičius**

  - **CountExceptionForwardAsiCal- Kaip „iCal“ persiųstų susitikimų išimčių skaičius**

  - **CountExceptionForwardInSplit- Iš išskaidyto juostelės meniu persiųstų susitikimų išimčių skaičius**

  - **CountExceptionForwardWithAttach- Kaip priedų persiųstų susitikimų išimčių skaičius**

  - **CountRecurringForward Persiųstų pasikartojančių susitikimų skaičius**

  - **CountRecurringForwardAsiCal- Kaip „iCal“ persiųstų pasikartojančių susitikimų skaičius**

  - **CountRecurringForwardInSplit**- Iš išskaidyto juostelės meniu persiųstų pasikartojančių susitikimų skaičius

  - **CountRecurringForwardWithAttach- Kaip priedas persiųstų pasikartojančių susitikimų skaičius**

  - **CountSingleForward- Persiųstų atskirų susitikimų skaičius**

  - **CountSingleForward- Kaip „iCal“ persiųstų atskirų susitikimų skaičius**

  - **CountSingleForwardInSplit- Iš išskaidyto juostelės meniu persiųstų atskirų susitikimų skaičius**

  - **CountSingleForwardWithAttach- Kaip priedas persiųstų atskirų susitikimų skaičius**

  - **HResult- ErrorCode**

  - **OlkViewName – nurodo pašto, kalendoriaus ar inspektorius rodinį**

#### <a name="officeoutlookdesktopoutlookcalendarusageerrmeetrcptreplyactionsruleo16"></a>Office.Outlook.Desktop.OutlookCalendarUsageErr.MeetRcpt.ReplyActions.Rule.O16

Renka sėkmingus ir nesėkmingus funkcijų Atsakyti, Atsakyti visiems, Atsakyti IM ir Atsakyti visiems IM atvejus, skirtus vienam, pasikartojančiam ir išskirtinio susitikimo atsakymui pašte, kalendoriuje ir „Inspector Outlook“ rodinyje. Funkcijų Atsakyti, Atsakyti visiems, Atsakyti IM ir Atsakyti visiems IM nepavykusių atvejų rodiklis aktyviai stebimas, ar nėra sutrikimų. Neįprasti statistikos duomenys rodo, kad „Outlook“ nesugeba atlikti pagrindinių kalendoriaus operacijų. Šie duomenys taip pat naudojami kitoms su kalendoriumi susijusioms problemoms nustatyti.

Renkami šių laukų duomenys:

  - **CountExceptionReply -susitikimų atsakymų dėl išimčių skaičius**

  - **CountExceptionReplyAll - Susitikimų atsakymų dėl išimčių skaičius**

  - **CountExceptionReplyAllWithIM- Susitikimų atsakymų Atsakyti visiems IM skaičius**

  - **CountExceptionReplyWithIM-- Susitikimų atsakymų Atsakyti IM skaičius**

  - **CountRecurringReply – Pasikartojančių susitikimų atsakymų Atsakyti IM skaičius**

  - **CountRecurringReplyAll- Pasikartojančių susitikimų atsakymų Atsakyti visiems skaičius**

  - **CountRecurringReplyAllWithIM- Pasikartojančių susitikimų atsakymų Atsakyti visiems IM skaičius**

  - **CountRecurringReplyWithIM- Pasikartojančių susitikimų atsakymų Atsakyti IM skaičius**

  - **CountSingleReply- skaičių Atskirų susitikimais atsakymų skaičius**

  - **CountSingleReplyAll- Atskirų susitikimų atsakymų Atsakyti visiems skaičius**

  - **CountSingleReplyAllWithIM- Atskirų susitikimų atsakymų Atsakyti visiems IM skaičius**

  - **CountSingleReplyWithIM- Atskirų susitikimų atsakymų Atsakyti IM skaičius**

  - **HResult- ErrorCode**

  - **OlkViewName – nurodo pašto, kalendoriaus ar inspektorius rodinį**

#### <a name="officeoutlookdesktopoutlookprivsdlgsingleuserloadfail"></a>Office.Outlook.Desktop.OutlookPrivsDlgSingleUser.LoadFail

Ši taisyklė renka kalendoriaus bendrinimo klaidas įtraukiant naują vartotoją (EX arba SMTP tipo) iš adresų knygelės. Šie duomenys naudojami diagnozuoti ir išspręsti problemas, aptiktas dialogo lange Kalendoriaus bendrinimas

Renkami šių laukų duomenys:

  - **CountAccountWizardEnd** – Kiek kartų baigėsi pasenęs vediklio dialogo langas

  - **CountCreatePIMAccount** – Kiek kartų vartotojas sukūrė PIM profilį

#### <a name="officesystemsystemhealthasserts"></a>Office.System.SystemHealthAsserts

Šio įvykio nurodytos klaidos padeda suprasti, kada blogėja klientų patirtis. Daugelis šių „ShipAsserts“ veda yra gedimų priežastis ir ši informacija leidžia daugelį jų išspręsti. Renka produkto, kuris padeda nustatyti klaidas, „ShipAsserts“.

Renkami šių laukų duomenys:

Skaičiavimas – kiekvieno pasireiškimo, apie kurį pranešta, skaičius

  - **EndTime** – Laikas, kai užfiksuotas paskutinis pasireiškimas, apie kurį pranešta

  - **ErrorGroup** – Kiekvieno pasireiškimo identifikatoriaus spragos

  - **FirstTimeStamp** – Pirmas kartas, kai įvyko pasireiškimas

  - **Trackback** – Konkretaus pasireiškimo unikalus identifikatorius

#### <a name="officesystemsystemhealtherrorsetwshim"></a>Office.System.SystemHealthErrorsEtwShim

Naudojamas nustatyti klientams, kurie daro įtaką problemų atsiradimui, kai veikia programa, kuri gali pasireikšti kaip gedimai ar blogėjančios funkcijos. Įrašo klaidas, įvykstančias proceso metu.

Renkami šių laukų duomenys:

  - **EndTime** – Laikas, kai užfiksuotas paskutinis pasieiškimas, apie kurį pranešta

  - **Trackback** – Konkrečios klaidos unikalus identifikatorius

  - **ErrorGroup** – Kiekvienos klaidos spragų identifikatorius

  - **Count** – Visų klaidų skaičius

  - **FirstTimeStamp** – Pirmas kartas, kai įvyko klaida

#### <a name="officesystemsystemhealtherrorsulsandasserts"></a>Office.System.SystemHealthErrorsUlsAndAsserts

Naudojamas nustatyti klientams, kurie daro įtaką problemų atsiradimui, kai veikia programa, kuri gali pasireikšti kaip gedimai ar blogėjančios funkcijos. Įrašo klaidas, įvykstančias proceso metu.

Renkami šių laukų duomenys:

  - **EndTime** – Laikas, kai užfiksuotas paskutinis pasieiškimas, apie kurį pranešta

  - **Trackback** – Konkrečios klaidos unikalus identifikatorius

  - **ErrorGroup** – Kiekvienos klaidos spragų identifikatorius

  - **Count** – Visų klaidų skaičius

  - **FirstTimeStamp** – Pirmas kartas, kai įvyko klaida

#### <a name="officesystemsystemhealtherrorsulsworkaround"></a>Office.System.SystemHealthErrorsUlsWorkaround

Naudojamas nustatyti klientams, kurie daro įtaką problemų atsiradimui, kai veikia programa, kuri gali pasireikšti kaip gedimai ar blogėjančios funkcijos. Įrašo klaidas, įvykstančias proceso metu

Renkami šių laukų duomenys:

  - **EndTime** – Laikas, kai užfiksuotas paskutinis pasieiškimas, apie kurį pranešta

  - **Trackback** – Konkrečios klaidos unikalus identifikatorius

  - **ErrorGroup** – Kiekvienos klaidos spragų identifikatorius

  - **Count** – Visų klaidų skaičius

#### <a name="officesystemsystemhealtherrorswithouttag"></a>Office.System.SystemHealthErrorsWithoutTag

Naudojamas nustatyti klientams, kurie daro įtaką problemų atsiradimui, kai veikia programa, kuri gali pasireikšti kaip gedimai ar blogėjančios funkcijos. Įrašo klaidas, įvykstančias proceso metu.

Renkami šių laukų duomenys:

Skaičiavimas – kiekvienos klaidos skaičius

  - **EndTime** – Laikas, kai užfiksuotas paskutinis pasireiškimas, apie kurį pranešta

  - **ErrorCode** – Klaidos identifikatorius

  - **ErrorGroup** – Kiekvienos klaidos spragų identifikatorius

  - **ErrorId** – Klaidos identifikatorius

  - **FirstTimeStamp** – Pirmas kartas, kai įvyko klaida

  - **Trackback** – Konkrečios klaidos unikalus identifikatorius

#### <a name="officesystemsystemhealtherrorswithtag"></a>Office.System.SystemHealthErrorsWithTag

Naudojamas nustatyti klientams, kurie daro įtaką problemų atsiradimui, kai veikia programa, kuri gali pasireikšti kaip gedimai ar blogėjančios funkcijos. Įrašo klaidas, įvykstančias proceso metu.

Renkami šių laukų duomenys:

  - **Count** – Visų klaidų skaičius

  - **EndTime** – Laikas, kai užfiksuotas paskutinis pasireiškimas, apie kurį pranešta

  - **ErrorCode** – Klaidos identifikatorius

  - **ErrorGroup** – Kiekvienos klaidos spragų identifikatorius

  - **ErrorId** – Klaidos identifikatorius

  - **FirstTimeStamp** – Pirmas kartas, kai įvyko klaida

  - **Trackback** – Konkrečios klaidos unikalus identifikatorius

## <a name="device-connectivity-and-configuration-data-events"></a>Įrenginių jungiamumo ir konfigūracijos duomenų įvykiai

Toliau pateikiami šios kategorijos duomenų potipiai:

- [Įrenginių jungiamumas ir konfigūracija](#device-connectivity-and-configuration-subtype)


### <a name="device-connectivity-and-configuration-subtype"></a>*Įrenginių jungiamumo ir konfigūracijos potipis*

Tinklo ryšio būsena ir įrenginio parametrai, tokie kaip atmintis.

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

Renkama, kai „PowerPoint“ aptinka, kad nėra interneto ryšio. „Microsoft“ naudoja šiuos duomenis, kad gautų diagnostinę informaciją apie vartotojo interneto ryšį, kad galėtų suprasti, kokią tai daro įtaką ryšiui su „Office“ paslaugomis.

Renkami šių laukų duomenys:

- **Data\_IsNexusDetected:bool** - Rodo, ar turime interneto ryšio būseną skambinant „Nexus“ tarnybai (reikšmė TRUE (teisinga) arba iškviečiant bendrosios žiniatinklio tarnybos API iškvietimą (reikšmė FALSE (klaidinga)
