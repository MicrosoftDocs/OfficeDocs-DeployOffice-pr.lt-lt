---
title: Pagrindinės „Office“ paslaugos
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
description: Informacija „Office“ administratoriams apie pagrindines „Office“ paslaugas, pvz., Spustelėkite ir naudokitės ir licencijavimą, taip pat pateikiamas šių pagrindinių paslaugų įvykių bei duomenų laukų sąrašas.
hideEdit: true
ms.openlocfilehash: 14b2426d021e5c559cabd3c969f80df9131cc9b9
ms.sourcegitcommit: 22ae0005d3106ff02949fb613b82e0245abfa49f
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 07/22/2019
ms.locfileid: "35817974"
---
# <a name="essential-services-for-office"></a>Pagrindinės „Office“ paslaugos

> [!IMPORTANT]
> Šiame straipsnyje pateikta informacija taikoma 1904 arba naujesnės versijos „Office“ kliento programinei įrangai, įdiegtai „Windows“ kompiuteryje:
> - „Office 365 ProPlus“ ir „Office 365 Business“
> - „Office 365 Personal“, „Office 365 Home“ arba kitos „Office“ versijos, kurios yra „Office 365“ prenumeratos dalis.
> - „Project“ ir „Visio“, kurios įtrauktos į kai kuriuos prenumeratos planus, pvz., planą „Project Online Professional“ arba „Visio Online“ 2 planą.


„Office“ sudaro kliento programinės įrangos programos ir prisijungus naudojamos funkcijos, kurios sukurtos, kad galėtumėte kurti, bendrauti ir bendradarbiauti efektyviau. Jei esate organizacijos administratorius, galite valdyti daugelį jums arba jūsų vartotojams pasiekiamų prisijungus naudojamų funkcijų, bet yra paslaugų, kurios yra būtinos, kad „Office“ veiktų, ir kurių išjungti negalima. Pavyzdžiui, licencijavimo paslauga, kuri patvirtina, kad turite reikiamą licenciją naudotis „Office“. Reikalingi tarnybų duomenys apie šias tarnybas yra renkami ir siunčiami „Microsoft“, nepaisant jokių kitų jūsų sukonfigūruotų su privatumu susijusios strategijos parametrų. Šiuos duomenis galite peržiūrėti naudodami diagnostikos duomenų peržiūros programą.

Jei reikia daugiau informacijos, žr.:

- [Reikalingi „Office“ tarnybų duomenys](required-service-data.md)
- [Diagnostikos duomenų peržiūros programos naudojimas su „Office“](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)
- [„Office“ prisijungus naudojamos funkcijos](connected-experiences.md)

Jei esate organizacijos administratorius, jus gali dominti šios temos:

- [„Office 365 ProPlus“ privatumo valdiklių apžvalga](overview-privacy-controls.md)
- [„Office 365 ProPlus“ privatumo valdiklių valdymas naudojant strategijos parametrus](manage-privacy-controls.md)

## <a name="list-of-essential-services-for-office"></a>Pagrindinių „Office“ paslaugos sąrašas 

Šioje lentelėje pateiktas pagrindinių „Office“ paslaugų sąrašas ir kiekvienos paslaugos aprašas.

| **Paslauga**  | **Aprašas**  |
| ------ | ---- |
| [Autentifikavimas](#authentication-events) | Autentifikavimas yra keliose platformose veikianti paslauga, kurią naudojant patvirtinama jūsų „Office“ vartotojo tapatybė. Ji reikalinga, kad galėtumėte prisijungti prie „Office“, suaktyvinti „Office“ licenciją ir pasiekti debesyje saugomus failus. Ji veikia vienodai visuose „Office“ seansuose ir įrenginiuose.    |
| [Spustelėkite ir naudokitės](#click-to-run-events) | Spustelėkite ir naudokitės yra diegimo technologija, naudojama diegiant ir naujinant „Office“ sistemoje „Windows“. Ji tikrina, ar išleista naujų „Office“ versijų, o kai nauja versija pasiekiama, ją atsisiunčia ir įdiegia.Paslauga Spustelėkite ir naudokitės aptiks, kada reikia naujinti „Office“, atsiųs naujinimus, įskaitant saugos naujinimus, ir juos įdiegs.     |
| [Patobulinta konfigūravimo paslauga (ECS)](#enhanced-configuration-service-ecs-events) | ECS suteikia „Microsoft“ galimybę perkonfigūruoti „Office“ įdiegtis, išvengiant poreikio iš naujo visuotinai įdiegti „Office“. Ji naudojama valdyti palaipsniui diegiamas funkcijas arba naujinimus, o diegimo poveikis stebimas pagal renkamus diagnostikos duomenis. Ji taip pat naudojama siekiant sumažinti saugos arba veikimo problemas diegiant funkcijas arba naujinimus. Be to, ECS palaiko su diagnostikos duomenimis susijusius konfigūracijos keitimus, kad užtikrintų, jog būtų renkami tinkami įvykiai. |
| [Licencijavimas](#licensing-events)     | Licencijavimas yra debesų technologija pagrįsta paslauga, kuri palaiko naujų „Office“ įdiegčių aktyvinimą ir išlaiko licenciją įrenginiuose suaktyvinus „Office“. Ji užregistruoja visus jūsų įrenginius ir suaktyvina „Office“, patikrina „Office“ prenumeratos būseną ir valdo produktų raktus.    |
| [Paslaugų konfigūravimas](#services-configuration-events)  | Paslaugų konfigūravimo paslauga suteikia galimybę naujinti „Office“ konfigūracijos parametrus ir įgalinti arba išjungti kliento funkcijas. Ji iškviečiama kaskart paleidus „Office“ programą ir suteikia informacijos apie kitas „Office“ konfigūracijas ir paslaugas. Paslaugų konfigūravimo paslauga taip pat valdo, kurios paslaugos laikomos pagrindinėmis paslaugomis.  |
| [Telemetrija ](#telemetry-events)  | Naudojant telemetrijos paslaugą renkami diagnostikos duomenys iš „Office“ programų. Ji suteikia galimybę rinkti „Office“ sugeneruotus diagnostikos duomenis (tiek būtinuosius, tiek pasirinktinius). Ji taip pat atsakinga už reikalingų „Office“ tarnybų diagnostikos duomenų dalies rinkimą.  |

## <a name="events-and-data-fields-for-essential-services-for-office"></a>Pagrindinių „Office“ paslaugų įvykiai ir duomenų laukai

Tolesniuose skyriuose pateikiama ši informacija:

- Kiekvienos pagrindinės paslaugos įvykių sąrašas
- Kiekvieno įvykio aprašas
- Kiekvieno įvykio duomenų laukų sąrašas
- Kiekvieno duomenų lauko aprašas

Šiuos įvykius galite peržiūrėti naudodami diagnostikos duomenų peržiūros programą.



## <a name="authentication-events"></a>Autentifikavimo įvykiai

Šie diagnostikos duomenų įvykiai renkami, kai „Office“ bando gauti autentifikavimo atpažinimo ženklą (tyliai arba pateikdamas raginimus).

### <a name="officeidentityfbapromptwin32"></a>Office.Identity.FbaPromptWin32

Renkama, kai „Office“ rodo vartotojui formomis pagrįsto autentifikavimo prisijungimo raginimą.

Kartu su tyliu atpažinimo ženklų gavimu, naudojami autentifikavimo raginimai siekiant nustatyti, ar vartotojo autentifikavimo būsena yra netinkama. Tai vartotojui iš esmės reiškia, kad kliento būsena bus Neprisijungęs, arba, blogiausiu atveju, dėl netinkamo autentifikavimo gali būti negauta licencija ir bus visiškai negalima naudoti kliento.

Formomis pagrįsto autentifikavimo (FBA) prisijungimo raginimai naudojami kai kuriais vietinio autentifikavimo scenarijais ir paprastai norime įsitikinti, kad tai nevyksta, nes visi turėtų naudoti šiuolaikinį autentifikavimą dėl su FBA siejamų saugos pažeidžiamumų.

**Renkami šių laukų duomenys:**

  - **AuthScheme** – naudojama autentifikavimo schema

  - **DocumentUrlHash** – prašomas užšifruotas URL

  - **EndTag** – FBA formos pabaigos žymė

  - **Flags** – nebenaudojama

  - **FlowTag** – FBA formos pradžios žymė

  - **LastError** – pateiktas klaidos kodas

  - **PromptEndTime** – raginimo pabaigos laikas

  - **PromptStartTime** – raginimo pradžios laikas

  - **Result** – ar autentifikavimas sėkmingas

  - **SessionEndTime** – įvykio seanso pabaigos laikas

  - **Timeout** – raginimo skirtojo laiko pabaigos laikas

### <a name="officeidentitysignoutevent"></a>Office.Identity.SignOutEvent

Renkama, kai vartotojas atsijungia nuo „Office“.

Žinant, kad vartotojas atsijungė, galima klasifikuoti kitus įvykius, pvz., raginimus, kaip numatyta, kad šie įvykiai būtų tinkamai apskaičiuoti patikimumo / parengimo pateikti metrikoje ir būtų išvengta įspėjimų arba komponavimo versijų keitimų atšaukimo darant klaidingą prielaidą, kad vartotojui pateikiami netikėti prisijungimo raginimai.

Renkami šių laukų duomenys:

  - **FlowEndTime** – atsijungimo veiksmo pabaigos laikas

  - **FlowStartTime** – atsijungimo veiksmo pradžios laikas

  - **IdentityErrorState** – bet kokia tapatybės klaidos būsena atsijungiant

  - **IdentityHashedUniqueId** – užšifruotas tapatybės ID, kurio atsijungimo procesas vykdomas

  - **IdentityProviderType** – tapatybės, kurios atsijungimo procesas vykdomas, tapatybės teikėjas

  - **IdentityUniqueID** – tapatybės ID, kurio atsijungimo procesas vykdomas

  - **SessionEndTime** – įvykio seanso pabaigos laikas

  - **SignOutUserAction** – nurodo, kad vartotojas inicijuoja atsijungimo veiksmą

### <a name="officeidentitysspipromptwin32"></a>Office.Identity.SspiPromptWin32

Renkama, kai „Office“ rodo vartotojui „Windows“ SSPI prisijungimo raginimą. Kartu su tyliu atpažinimo ženklų gavimu, autentifikavimo raginimai lemia, ar vartotojo autentifikavimo būsena yra netinkama (dėl jos kliento būsena tampa Neprisijungęs). Dėl netinkamo autentifikavimo gali būti negauta licencija ir gali visiškai nepavykti naudoti kliento.

„Windows“ SSPI raginimai naudojami autentifikuojant per „Exchange“ (el. paštui sinchronizuoti), kai vartotojo „Exchange“ išteklius nebuvo nustatytas naudoti kelių dalių autentifikavimą.

Šie įvykiai, kartu su „Office.MATS“ vardų srities įvykiais, naudojami šiais tikslais:

1\) Siekiant nustatyti, ar klientai gali sėkmingai gauti autentifikavimo atpažinimo ženklą, ar jų autentifikavimo būsena yra netinkama.

2\) Siekiant įvertinti, ar kliente arba paslaugose padaryti keitimai lėmė kritinį vartotojo autentifikavimo patirties ir patikimumo suprastėjimą.

3\) Kai įvyksta triktis, šie signalai perduoda svarbius trikties kodus iš atsakingo komponento („Office“ kliento kodo, autentifikavimo bibliotekų arba tarnybų), kuriuos galima naudoti nustatant, diagnozuojant ir mažinant poveikį.

4\) Šie signalai siunčiami į įvairias parengimo pateikti ir sveikatos stebėjimo programas, kurios suaktyvina įspėjimus, kad mūsų inžinieriai galėtų greitai imtis problemos sprendimo ir būtų greičiau sumažintas kritinių vartotojams dirbti neleidžiančių trikčių poveikis.

Renkami šių laukų duomenys:

  - **AllowSavedCreds** – ar nauji kredencialai išlaikomi

  - **AuthScheme** – naudojama autentifikavimo schema

  - **CredsSaved** – ar nauji kredencialai įrašomi

  - **DocumentUrlHash** – prašomas užšifruotas URL

  - **EndTag** – raginimo pabaigos žymė

  - **NewIdentity**\_ErrorState – ar nauja tapatybė yra galiojanti

  - **NewIdentity\_HashedUniqueId** – užšifruotas naujas tapatybės ID užbaigus raginimą

  - **NewIdentity\_ProviderType** – naujas tapatybės teikėjas užbaigus raginimą

  - **NewIdentity\_UniqueID** – naujas tapatybės ID užbaigus raginimą

  - **OutStatus** – ar raginimo išvestis yra galiojanti

  - **PromptEndTime** - raginimo pabaigos laikas

  - **PromptFailedTag** – žymė, nurodanti SSPI raginimo triktį

  - **PromptFlow** – žymė, kuri iškvietė SSPI raginimą

  - **PromptStartTime** – raginimo pradžios laikas

  - **Proxy** – ar naudojamas tarpinis serveris

  - **ServerHash** – užšifruotas serverio adresas

  - **SessionEndTime** – įvykio seanso pabaigos laikas

  - **Timeout** – raginimo skirtojo laiko pabaigos laikas

  - **UiMessage** – vartotojo sąsajos pranešimas raginime

  - **UserNameHash** – užšifruotas vartotojo vardas

### <a name="officeidentitywin32prompt"></a>Office.Identity.Win32Prompt

Renkama, kai „Office“ rodo vartotojui kelių dalių autentifikavimo prisijungimo raginimą. Kartu su tyliu atpažinimo ženklų gavimu, autentifikavimo raginimai lemia, ar vartotojo autentifikavimo būsena yra netinkama (dėl jos kliento būsena tampa Neprisijungęs). Dėl netinkamo autentifikavimo gali būti negauta licencija ir gali visiškai nepavykti naudoti kliento.

Šie įvykiai, kartu su „Office.MATS“ vardų srities įvykiais, naudojami šiais tikslais:

1\) Siekiant nustatyti, ar klientai gali sėkmingai gauti autentifikavimo atpažinimo ženklą, ar jų autentifikavimo būsena yra netinkama.

2\) Siekiant įvertinti, ar kliente arba paslaugose padaryti keitimai lėmė kritinį vartotojo autentifikavimo patirties ir patikimumo suprastėjimą.

3\) Kai įvyksta triktis, šie signalai perduoda svarbius trikties kodus iš atsakingo komponento („Office“ kliento kodo, autentifikavimo bibliotekų arba tarnybų), kuriuos galima naudoti nustatant, diagnozuojant ir mažinant poveikį.

4\) Šie signalai siunčiami į įvairias parengimo pateikti ir sveikatos stebėjimo programas, kurios suaktyvina įspėjimus, kad mūsų inžinieriai galėtų greitai imtis problemos sprendimo ir būtų greičiau sumažintas kritinių vartotojams dirbti neleidžiančių trikčių poveikis.

Renkami šių laukų duomenys:

  - **AdalWAMUsed** – žymė, kuri nurodo rezultatą, jei naudojamas ADAL-atop-WAM

  - **CallTag** – žymė, kuri nurodo, kas iškviečia prisijungimo vartotojo sąsają

  - **Context** – raginimo prisijungimo kontekstas

  - **EndTagIdentityProviderRequested** – žymė, kur prašomas tapatybės teikėjas

  - **HrdShownTag** – žymė, kur rodomas HRD prisijungimo dialogo langas

  - **IdentityProviderResulted** – prašomas tapatybės teikėjo tipas

  - **IdPFlowTag** – žymė, kuri nurodo tapatybės užklausos rezultatą

  - **LastLoginDelta** – laiko pokytis nuo paskutinio sėkmingo prisijungimo

  - **NewIdentity\_ErrorState** – ar tapatybė galioja po raginimo

  - **NewIdentity\_ProviderType** – naujas tapatybės teikėjo tipas po raginimo

  - **NewIdentity\_UniqueID** – naujas tapatybės ID, pateiktas po raginimo

  - **PromptCorrelation** – raginimo sąsajos ID diagnostikos tikslais

  - **PromptEndTime** - raginimo pabaigos laikas

  - **PromptStartTime** – raginimo pradžios laikas

  - **SessionEndTime** – įvykio seanso pabaigos laikas

  - **ShowUIResult** – rezultato kodas, pateiktas iš raginimo vartotojo sąsajos

  - **StartTag** – žymė, kur pradėtas „Win32“ raginimas

  - **Timeout** – raginimo skirtojo laiko pabaigos laikas

  - **WasIdentitySignedOut** – ar vartotojas atsijungęs

### <a name="officematsactionofficewin32-officematsactionofficewinrt"></a>Office.MATS.actionofficewin32, Office.MATS.actionofficewinrt

Tolesnis aprašas taikomas ir „Win32“, ir „WinRT“ įvykiams (pavadinimas priklauso nuo platformos)

„Microsoft“ autentifikavimo telemetrijos sistemos (MATS) įvykiai renkami, kai „Office“ bando gauti autentifikavimo atpažinimo ženklą (tyliai arba pateikdamas raginimus). Kai bandymas gauti nepavyksta, įtraukiama klaidos informacija. Šie įvykiai padeda vartotojams išvengti netinkamos autentifikavimo būsenos:

1\) Nustatant, ar klientai gali sėkmingai gauti autentifikavimo atpažinimo ženklą, ar jų autentifikavimo būsena yra netinkama.

2\) Įvertinant, ar kliente arba paslaugose padaryti keitimai lėmė kritinį vartotojo autentifikavimo patirties ir patikimumo suprastėjimą.

3\) Kai įvyksta triktis, šie signalai perduoda svarbius trikties kodus iš atsakingo komponento („Office“ kliento kodo, autentifikavimo bibliotekų arba tarnybų), kuriuos galima naudoti nustatant, diagnozuojant ir mažinant poveikį.

4\) Šie signalai siunčiami į įvairias parengimo pateikti ir sveikatos stebėjimo programas, kurios suaktyvina įspėjimus, kad mūsų inžinieriai galėtų greitai imtis problemos sprendimo ir būtų greičiau sumažintas kritinių trikčių poveikis.

Renkami šių laukų duomenys:

  - **Actiontype** – kuri autentifikavimo biblioteka naudojama

  - **Appaudience** – ar programa sukurta vidiniam, ar išoriniam naudojimui

  - **Appforcedprompt** – ar programa perrašė talpyklą ir priverstinai parodė raginimą

  - **Appname** – programos, kurią naudojant autentifikuojama, pavadinimas

  - **Appver** – programos, kurią naudojant identifikuojama, versija

  - **Askedforcreds** – ar programa paprašė vartotojo įvesti kredencialus atliekant šį veiksmą

  - **Authoutcome** – ar autentifikavimo bandymas pavyko, nepavyko, ar buvo atšauktas

  - **Blockingprompt** – ar programa pateikė raginimą, reikalaujantį vartotojo sąveikos

  - **Correlationid** – GUID, naudojamas siejant su paslaugų duomenimis

  - **Count** – įvykių skaičius agregavimo atvejais

  - **Data\_accounttype** – vartotojo ar organizacijos paskyra

  - **Devicenetworkstate** – ar vartotojas buvo prisijungęs

  - **Deviceprofiletelemetryid** – anoniminis įrenginio ID, naudojamas vertinant įrenginio patirtį

  - **Duration** – kiek laiko truko autentifikavimas

  - **Endtime** – kada baigtas autentifikavimo įvykis

  - **Error** – klaidos kodas, jei autentifikavimas nepavyko

  - **Errordescription** – trumpas klaidos aprašas

  - **Errorsource** – ar klaida įvyko iš paslaugos, autentifikavimo bibliotekos, ar programos

  - **Identityservice** – ar buvo iškviesta „Microsoft“ tarnybos paskyra (MSA), ar „Azure Active Directory“ (AAD) paslauga

  - **Interactiveauthcontainer** – kokio tipo raginimas buvo parodytas

  - **Issilent** – ar raginimas buvo parodytas

  - **Microsoft**\_**ADAL**\_**adal**\_**version** – „Azure Active Directory“ autentifikavimo bibliotekos (ADAL) versija

  - **Microsoft\_ADAL\_api\_error\_code** – šio autentifikavimo bandymo klaidos kodas, perduotas autentifikavimo bibliotekos

  - **Microsoft\_ADAL\_api\_id** – iškviesta šio autentifikavimo bandymo API

  - **Microsoft\_ADAL\_authority** – „Azure Active Directory“ tarnybos, atsakingos už vartojo autentifikavimą, URL

  - **Microsoft\_ADAL\_authority\_type** – vartotojo / „Microsoft“ paslaugų teikimo sutartis (MSA) ar organizacijos / „Azure Active Directory“ (AAD); šiuo metu visada AAD

  - **Microsoft\_ADAL\_authority\_validation\_status** – pasako, ar autentifikavimas baigtas paslaugos pusėje

  - **Microsoft\_ADAL\_broker\_app** – pasako, ar ADAL naudojo autentifikavimo tvarkytuvę

  - **Microsoft\_ADAL\_broker\_app\_used** – pasako tvarkytuvės pavadinimą (pvz., „Windows“ paskyros tvarkytuvė)

  - **Microsoft\_ADAL\_broker\_version** – pasako tvarkytuvės versiją (jei naudota)

  - **Microsoft\_ADAL\_cache\_event\_count** – ADAL įvykdytų talpyklos įvykių skaičius gaunant atpažinimo ženklą

  - **Microsoft\_ADAL\_cache\_event\_count\_max** – jei šis signalas yra agreguotas, didžiausias vieno iš agreguotų įvykių talpyklos įvykių skaičius.

  - **Microsoft\_ADAL\_cache\_event\_count\_min** – jei šis signalas yra agreguotas, mažiausias vieno iš agreguotų įvykių talpyklos įvykių skaičius.

  - **Microsoft\_ADAL\_cache\_event\_count\_sum** – jei šis signalas yra agreguotas, visų agreguotų įvykių talpyklos įvykių suma.

  - **Microsoft\_ADAL\_cache\_read\_count** – kiek kartų API skaitė iš disko talpyklos. Pateikiamas, jei skaityta bent vieną kartą.

  - **Microsoft\_ADAL\_cache\_read\_error\_count** – kiek kartų nepavyko skaitymo iš disko talpyklos procesas. Pateikiamas, jei buvo bent viena klaida.

  - **Microsoft\_ADAL\_cache\_read\_last\_error** – ADAL klaidos kodas. Pateikiamas, jei buvo bent viena skaitymo klaida.

  - **Microsoft\_ADAL\_cache\_read\_last\_system\_error** – sistemos klaidos kodas. Pateikiamas, jei buvo bent viena skaitymo klaida.

  - **Microsoft\_ADAL\_cache\_write\_count** – kiek kartų API rašė į disko talpyklą. Pateikiamas, jei rašyta bent vieną kartą.

  - **Microsoft\_ADAL\_cache\_write\_error\_count** – kiek kartų nepavyko rašymo į disko talpyklą procesas. Pateikiamas, jei buvo bent viena klaida.

  - **Microsoft\_ADAL\_cache\_write\_last\_error** – ADAL klaidos kodas. Pateikiamas, jei buvo bent viena rašymo klaida.

  - **Microsoft\_ADAL\_cache\_write\_last\_system\_error** – sistemos klaidos kodas. Pateikiamas, jei buvo bent viena rašymo klaida.

  - **Microsoft\_ADAL\_client\_id** – AAD programos ID, kuriam pritaikyta maiša

  - **Microsoft\_ADAL\_extended\_expires\_on\_setting** – ar atpažinimo ženklo egzistavimo laikotarpis pailgintas (teisinga arba klaidinga).

  - **Microsoft\_ADAL\_http\_event\_coun**t – ADAL atliktų HTTP iškvietimų skaičius.

  - **Microsoft\_ADAL\_http\_event\_count\_max** – jei šis signalas yra agreguotas, bet kurio agreguoto įvykio maksimalus ADAL atliktų HTTP iškvietimų skaičius.

  - **Microsoft\_ADAL\_http\_event\_count\_min** – jei šis signalas yra agreguotas, bet kurio agreguoto įvykio minimalus ADAL atliktų HTTP iškvietimų skaičius.

  - **Microsoft\_ADAL\_http\_event\_count\_sum** – jei šis signalas yra agreguotas, visų agreguotų įvykių ADAL atliktų HTTP iškvietimų suma.

  - **Microsoft\_ADAL\_is\_silent\_ui** – ar ADAL parodė vartotojo sąsają (raginimą) (teisinga arba klaidinga).

  - **Microsoft\_ADAL\_is\_successful** – ar ADAL API pavyko (teisinga arba klaidinga).

  - **Microsoft\_ADAL\_logging\_pii\_enabled** - ar įgalintas visas ADAL registravimo žurnale režimas (teisinga arba klaidinga). Šie duomenys registruojami tik vietoje; jie neperduodami telemetrijoje.

  - **Microsoft\_ADAL\_oauth\_error\_code** – „OAuth“ protokolo klaidos kodas, kurį pateikė paslauga.

  - **Microsoft\_ADAL\_prompt\_behavior** – HTTP parametras (Prisijungimas / Nėra), perduotas į paslaugą, siekiant nurodyti, ar galima parodyti vartotojo sąsają.

  - **Microsoft\_ADAL\_request\_id** – ADAL į paslaugą perduotos užklausos operacinis GUID.

  - **Microsoft\_ADAL\_response\_code** – HTTP atsakymo kodas iš paslaugos.

  - **Microsoft\_ADAL\_response\_time** – per kiek laiko paslauga atsakė ADAL.

  - **Microsoft\_ADAL\_response\_time\_max** – jei signalas yra agreguotas, maksimalus laikas, per kurį API atsakė ADAL, tarp visų agreguotų įvykių.

  - **Microsoft\_ADAL\_response\_time\_min** – jei signalas yra agreguotas, minimalus laikas, per kurį paslauga atsakė ADAL, tarp visų agreguotų įvykių.

  - **Microsoft\_ADAL\_response\_time\_sum** – jei signalas yra agreguotas, laiko, per kurį API atsakė ADAL, suma tarp visų agreguotų įvykių.

  - **Microsoft\_ADAL\_rt\_age** – atnaujinimo atpažinimo ženklo terminas

  - **Microsoft\_ADAL\_server\_error\_code** – serverio pateiktas klaidos kodas

  - **Microsoft\_ADAL\_server\_sub\_error\_code** – serverio pateiktas antrinis klaidos kodas, padedantis išsiaiškinti, kodėl nepavyko įvykdyti užklausos.

  - **Microsoft\_ADAL\_spe\_ring** – ar vartotojas naudojo „Secure Production Enterprise“ vidinį ratą (tik „Microsoft“ darbuotojai) (teisinga arba klaidinga).

  - **Microsoft\_ADAL\_start\_time** – ADAL API iškvietimo laikas

  - **Microsoft\_ADAL\_stop\_time** – ADAL API iškvietimo atsakymo laikas

  - **Microsoft\_ADAL\_telemetry\_pii\_enabled** – ar įgalintas visas ADAL telemetrijos režimas (teisinga arba klaidinga). Pavadinimas yra neteisingas, nes neperduodama PII / EUII.

  - **Microsoft\_ADAL\_tenant\_id** – GUID, identifikuojantis nuomotoją, kuriam priklauso autentifikuotas vartotojas.

  - **Microsoft\_ADAL\_token\_acquisition\_from\_context** – apibūdina ADAL veikimo būdą pagal atpažinimo ženklus autentifikavimo kontekste.

  - **Microsoft\_ADAL\_token\_type** – atnaujinimo atpažinimo ženklas (RT) arba kelių išteklių atnaujinimo atpažinimo ženklas (MRRT).

  - **Microsoft\_ADAL\_ui\_event\_count** – vartotojui rodomų raginimų skaičius. Galėjo būti tylūs.

  - **Microsoft\_ADAL\_user\_cancel** – ar vartotojo sąsajos langas buvo atšauktas (teisinga arba klaidinga).

  - **Microsoft\_ADAL\_x\_ms\_request\_id** – papildomas užklausos ID, kurį ADAL pateikė paslaugai HTTP antraštėje.

  - **Platform** – „Win32“ / „WinRT“ / „Android“ / „iOS“ / „Mac“

  - **Scenarioid** – GUID. Vienam scenarijui gali priklausyti keli įvykiai, pvz., scenarijus gali įtraukti naują paskyrą, bet vykstant tam scenarijui pateikiami keli raginimai. Šis ID įgalina sąsają.

  - **Sessionid** – GUID, identifikuojantis įkrovos seansą

  - **Skdver** – MATS kliento SDK, naudojamo šiems duomenims sukurti, versija

  - **Starttime** – Start\*Action MATS API iškvietimo laikas

  - **Tenantid** – GUID, identifikuojantis nuomotoją, kuriam priklauso autentifikuotas vartotojas (ne ADAL atvejais).

  - **Uploadid** – šio įvykio unikalusis GUID, naudojamas dublikatams naikinti

  - **Wamapi** – identifikuoja, kuri WAM API iškviesta

  - **Wamtelemetrybatch** – šiuo metu nenaudojamas. Ateityje leis WAM komponentui pateikti papildomą informaciją, susijusią su autentifikavimo įvykiu.

## <a name="click-to-run-events"></a>Spustelėkite ir naudokitės įvykiai

### <a name="officeclicktorunbootstrapper"></a>Office.ClickToRun.Bootstrapper 

„Office“ sąrankos ir aprašų duomenys, renkami vartotojui paleidus „Office“ setup.exe, kad modifikuotų įdiegtus „Office“ produktus. Naudojami vertinant viso vartotojo inicijuoto „Office“ diegimo sėkmingumą, įskaitant būtinąsias patikras.

Renkami šių laukų duomenys:

  - **Data\_BootStrapperStateFailure\_ErrorCode** – įvykusios klaidos kodas

  - **Data\_BootStrapperStateFailure\_ErrorSource** – funkcija, kurios klaida įvyko

  - **Data\_BootStrapperStateFailure\_FailingState** – įkėlimo įrankio dalis, kurioje įvyko klaida

  - **Data\_BootStrapperStateFailure\_OExceptionType** – išimties tipas

  - **Data\_Culture** – kultūra, su kuria vykdomas šis „exe“, pvz., „en-us“

  - **Data\_HashedOLSToken** – atpažinimo ženklo SHA-256 maiša, kurią mums nurodo OLS paslauga

  - **Data\_Platform** – „x64“ arba „x86“ įdiegtis

  - **Data\_PrereqFailure\_Type** – įvykusi būtinųjų sąlygų triktis, pvz., nepalaikoma operacinė sistema

  - **Data\_ProductReleaseId** – diegiamas produktas, pvz., „Office 365 ProPlus“

### <a name="officeclicktoruncorruptioncheck"></a>Office.ClickToRun.CorruptionCheck

„Office“ sąrankos ir inventoriaus duomenys, renkami Spustelėkite ir naudokitės klientui vykdant patikrą dėl sugadinimo, siekiant įsitikinti, kad „Office“ dvejetainiai failai yra teisingi. Naudojami vertinant, ar „Office“ dvejetainiai failai yra sugadinti ir kurie dvejetainiai failai yra sugadinti.

Renkami šių laukų duomenys:

  - **Data\_Active –** dabartinė srauto deklaracija, kurią tikriname diske

  - **Data\_ActivePackages –** kokie paketai yra deklaracijoje

  - **Data\_ActiveVersion –** deklaracijos versija

  - **Data\_AddFileCount –** kiek failų įtraukiame

  - **Data\_AddFileFiles –** įtraukiamų failų imtis

  - **Data\_CompressionLevel –** kaip failai suglaudinti

  - **Data\_CorruptionCheckLevel –** kaip nuodugniai tikriname dėl sugadinimo (etapai)

  - **Data\_CorruptSizeCount –** kelių failų dydis yra sugadintas

  - **Data\_CorruptSizeFiles –** failų, kurių dydis sugadintas, imtis

  - **Data\_CorruptVersionCount –** kelių failų versija sugadinta

  - **Data\_CorruptVersionFiles –** failų, kurių versija sugadinta, imtis

  - **Data\_FileBadDigestCount –** kiek failų nepavyko atidaryti

  - **Data\_FileBadDigestFiles –** failų, kurių nepavyko atidaryti, imtis

  - **Data\_FileNotSignedCount –** kiek failų nėra pasirašyti

  - **Data\_FileNotSignedFiles –** failų, kurie nėra pasirašyti, imtis

  - **Data\_FileNotTrustedCount –** kiek failų nėra patikimi

  - **Data\_FileNotTrustedFiles –** nepatikimų failų imtis

  - **Data\_IncompleteFileCount –** kiek failų atrodo nepilni

  - **Data\_IncompleteFileFiles –** nepilnų failų imtis

  - **Data\_KeepFileCount –** dėl kiek failų nieko nedaroma

  - **Data\_KeepFileFiles –** paliekamų failų imtis

  - **Data\_KeepIncompleteFileCount –** kiek failų nekeičiama, nepaisant to, kad jie yra nepilni

  - **Data\_KeepIncompleteFileFiles –** paliekamų nepilnų failų imtis

  - **Data\_MismatchSizeCount –** kelių failų dydis neatitinka mūsų deklaracijos

  - **Data\_MismatchSizeFiles –** failų, kurių dydis neatitinka, imtis

  - **Data\_MismatchVersionCount –** kelių failų versija skiriasi nuo mūsų deklaracijos

  - **Data\_MismatchVersionFiles –** failų, kurių versijos neatitinka, imtis

  - **Data\_MissingFileCount –** kiek failų trūksta

  - **Data\_MissingFileFiles –** trūkstamų failų imtis

  - **Data\_NotToBeStreamedFileCount –** kiek failų neperduodama srautu

  - **Data\_RemoveFileCount –** kiek failų šalinama

  - **Data\_RemoveFileFiles –** šalinamų failų imtis

  - **Data\_StreamUnitsMismatchCount –** kiek failų vienetų neatitinka deklaracijos

  - **Data\_StreamUnitsMismatchFiles –** failų, kurių srauto vienetai neatitinka, imtis

  - **Data\_TimeElapsed –** kiek užtruko patikra dėl sugadinimo

  - **Data\_UpdateFileCount –** kiek failų naujiname

  - **Data\_UpdateFileFiles –** failų, kuriuos įtraukiame, imtis

  - **Data\_Working –** nauja tikrinama deklaracija

  - **Data\_WorkingVersion –** naujos deklaracijos versija

### <a name="officeclicktorunmachinemetadata"></a>Office.ClickToRun.MachineMetadata

„Office“ sąrankos ir inventoriaus duomenys, kurie pateikia reikiamus metaduomenis ir naudojami siekiant nustatyti tikslią diegimo bazę.

Renkami šių laukų duomenys:

  - **Data\_C2RClientVer** – OfficeClickToRun.exe versija kompiuteryje

  - **Data\_OfficeBitness** – sistemos, kurioje įdiegtas „Office“, bitų skaičius (x86 arba x64)

  - **Data\_OfficeVersion** – sistemos, kurioje įdiegtas „Office“, versija

  - **Data\_Sku** – įdiegtas SKU, pvz., Office 365 ProPlus.en-us

  - **Data\_SqmMachineID** – unikalusis kompiuterio ID, kurį naudoja „Windows SQM Data“\_SusClientID – kompiuterio „Office“ naujinimo identifikatoriaus

### <a name="officeclicktorunodt"></a>Office.ClickToRun.ODT

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai IT administratorius vykdo „Office“ diegimo įrankio Spustelėkite ir naudokitės setup.exe, kad modifikuotų vartotojų įdiegtus „Office“ produktus. Naudojamas vertinant visų IT administratoriaus inicijuotų „Office“ diegimų sėkmingumą, įskaitant būtinųjų sąlygų patikras.

Renkami šių laukų duomenys:

  - **Data\_BootStrapperStateFailure\_ErrorCode –** įvykusios klaidos kodas

  - **Data\_BootStrapperStateFailure\_ErrorSource –** funkcija, kurios klaida įvyko

  - **Data\_BootStrapperStateFailure\_FailingState –** įkėlimo įrankio dalis, kurioje įvyko klaida

  - **Data\_BootStrapperStateFailure\_OExceptionType –** išimties tipas

  - **Data\_ConfigurationHost –** pagrindinis kompiuteris, iš kurio gautas configuration.xml

  - **Data\_ConfigurationId –** iš configuration.xml gautas ID

  - **Data\_ConfigurationSource –** iš kur gautas configuration.xml

  - **Data\_Culture –** kultūra, su kuria vykdomas šis „exe“, pvz., „en-us“

  - **Data\_HashedOLSToken –** atpažinimo ženklo SHA-256 maiša, kurią mums nurodo OLS paslauga

  - **Data\_MigrateArchRequest –** jei perkeliame vartotoją iš x86 į x64 arba atvirkščiai

  - **Data\_MigrateArchRequestValid –** ar manome, kad perkėlimo užklausa yra galiojanti

  - **Data\_Platform –** x64 arba x86 įdiegtis

  - **Data\_PlatformMigratedFrom –** pradinė platforma, pvz., x86

  - **Data\_PlatformMigratedTo–** galutinė platforma, pvz., x64

  - **Data\_PrereqFailure\_Type –** įvykusi būtinosios sąlygos triktis

  - **Data\_ProductReleaseId –** diegiamas produktas, pvz., „Office 365 ProPlus“

### <a name="officeclicktorunscenarioinstalltaskconfigure"></a>Office.ClickToRun.Scenario.InstallTaskConfigure

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai „Office“ diegimo programa įdeda naujai atsisiųstus failus. Naudojami vertinant „Office“ diegimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida 

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –** unikalusis kompiuterio ID, kurį naudoja „Windows SQM“ 

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenarioinstalltaskconfigurelight"></a>Office.ClickToRun.Scenario.InstallTaskConfigurelight

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai „Office“ diegimo programa sprendžia, kokius failus reikia atsisiųsti. Naudojami vertinant „Office“ diegimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida 

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –** unikalusis kompiuterio ID, kurį naudoja „Windows SQM“ 

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenarioinstalltaskfinalintegrate"></a>Office.ClickToRun.Scenario.InstallTaskFinalintegrate

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai „Office“ diegimo programa diegia licencijas ir registro parametrus. Naudojami vertinant „Office“ diegimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –** unikalusis kompiuterio ID, kurį naudoja „Windows SQM“ 

  - **Data\_SusClientID –**  kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenarioinstalltaskfonts"></a>Office.ClickToRun.Scenario.InstallTaskFonts

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai „Office“ diegimo programa diegia šriftus. Naudojami vertinant „Office“ diegimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida 

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –** unikalusis kompiuterio ID, kurį naudoja „Windows SQM“ 

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenarioinstalltaskinitupdates"></a>Office.ClickToRun.Scenario.InstallTaskInitupdates

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai „Office“ diegimo programa kuria parametrus, kurių reikia, kad tinkamai veiktų naujinimai. Naudojami vertinant „Office“ diegimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida 

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –** unikalusis kompiuterio ID, kurį naudojama „Windows SQM“ 

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenarioinstalltaskintegrateinstall"></a>Office.ClickToRun.Scenario.InstallTaskIntegrateinstall

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai „Office“ diegimo programa kuria „Office“ programų registro įrašus. Naudojami vertinant „Office“ diegimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida 

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –** unikalusis kompiuterio ID, naudojamas „Windows SQM“

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenarioinstalltasklastrun"></a>Office.ClickToRun.Scenario.InstallTaskLastrun

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai „Office“ diegimo programa baigia diegti, prisega nuorodas ir kuria galutinius registro parametrus. Naudojami vertinant „Office“ diegimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida 

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –**  kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –** unikalusis kompiuterio ID, naudojamas „Windows SQM“

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenarioinstalltaskmigrate"></a>Office.ClickToRun.Scenario.InstallTaskMigrate

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai „Office“ diegimo programa perkelia parametrus iš ankstesnių „Office“ versijų. Naudojami vertinant „Office“ diegimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –** unikalusis kompiuterio ID, naudojamas „Windows SQM“

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenarioinstalltaskpublishrsod"></a>Office.ClickToRun.Scenario.InstallTaskPublishrsod

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai „Office“ diegimo programa skelbia „AppV“ virtualizavimo sluoksnio virtualųjį registrą. Naudojami vertinant „Office“ diegimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas, pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –** unikalusis kompiuterio ID, naudojamas „Windows SQM“

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenarioinstalltaskremoveinstallation"></a>Office.ClickToRun.Scenario.InstallTaskRemoveinstallation

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai „Office“ šalinimo programa šalina „Office“ dalis iš įrenginio. Naudojami vertinant „Office“ diegimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –**  į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida 

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –** unikalusis kompiuterio ID, naudojamas „Windows SQM“

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenarioinstalltaskstream"></a>Office.ClickToRun.Scenario.InstallTaskStream

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai „Office“ diegimo programa atsisiunčia naujus „Office“ failus. Naudojami vertinant „Office“ diegimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –**  į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida 

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –**  kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –**  unikalusis kompiuterio ID, kurį naudoja „Windows SQM“ 

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenarioinstalltaskuninstallcentennial"></a>Office.ClickToRun.Scenario.InstallTaskUninstallcentennial

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai „Office“ diegimo programa šalina ankstesnę iš parduotuvės įdiegtą „Office“ versiją. Naudojami vertinant „Office“ diegimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida 

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –**  unikalusis kompiuterio ID, kurį naudoja „Windows SQM“

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenariorepairtaskfinalintegrate"></a>Office.ClickToRun.Scenario.RepairTaskFinalintegrate

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai „Office“ taisymo klientas iš naujo publikuoja .msi failus ir „Office“ plėtinius. Naudojami vertinant „Office“ taisymo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –**  į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida 

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –**  unikalusis kompiuterio ID, kurį naudoja „Windows SQM“ 

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenariorepairtaskfullrepair"></a>Office.ClickToRun.Scenario.RepairTaskFullrepair

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai „Office“ taisymo klientas atsisiunčia naujausią Spustelėkite ir naudokitės kliento versiją, kad paruoštų kompiuterį šalinti ir diegti iš naujo. Naudojami vertinant „Office“ taisymo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida 

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –**  unikalusis kompiuterio ID, kurį naudoja „Windows SQM“ 

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenariorepairtaskintegraterepair"></a>Office.ClickToRun.Scenario.RepairTaskIntegraterepair

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai „Office“ taisymo klientas bando pataisyti žinomus problemų keliančius registro įrašus. Naudojami vertinant „Office“ taisymo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida 

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –**  unikalusis kompiuterio ID, kurį naudoja „Windows SQM“ 

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenariorepairtaskremoveinstallation"></a>Office.ClickToRun.Scenario.RepairTaskRemoveinstallation

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai „Office“ taisymo klientas pašalina „Office“ iš įrenginio, kad paruoštų diegti iš naujo, per taisymo procesą. Naudojami vertinant „Office“ taisymo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida 

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –**  kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –**  unikalusis kompiuterio ID, kurį naudoja „Windows SQM“ 

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenarioupdatetaskintegrateupdate"></a>Office.ClickToRun.Scenario.UpdateTaskIntegrateupdate 

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai Spustelėkite ir naudokitės klientas naujina licencijas (jei būtina). Naudojami vertinant „Office“ naujinimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida 

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –**  unikalusis kompiuterio ID, kurį naudoja „Windows SQM“ 

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenarioupdatetaskpublishrsod"></a>Office.ClickToRun.Scenario.UpdateTaskPublishrsod

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai Spustelėkite ir naudokitės klientas naujina naujų dvejetainių failų registro parametrus. Naudojami vertinant „Office“ naujinimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida 

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –**  unikalusis kompiuterio ID, kurį naudoja „Windows SQM“ 

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenarioupdatetaskupdateapply"></a>Office.ClickToRun.Scenario.UpdateTaskUpdateapply

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai Spustelėkite ir naudokitės klientas išjungia veikiančias programas (jei būtina) ir įdiegia naujus atsisiųstus failus. Naudojami vertinant „Office“ naujinimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_AvailableVersion to –** kokią „Office“ versiją galima naujinti

  - **Data\_CompletedWithoutActionInfo –** kodėl neužbaigėme scenarijaus, pvz., buvo atidarytos programos

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Duomenų\_CorruptionChecksOnly –** jei tik tikrinama dėl sugadinimo, o ne naujinama

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida

  - **Data\_ExceptionType –** išimtis 

  - **Data\_HardlinkingException –** išimtis, įvykusi bandant sukurti tiesioginius saitus

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_PackageOperationSuccessful –** teisinga, jei sėkmingai užbaigta užduotis „Office“ pakete

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID  -**  unikalusis kompiuterio ID, kurį naudojama „Windows SQM“

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

  - **Data\_WorkstationLockState –** teisinga, jei manome, kad kompiuteris užrakintas

### <a name="officeclicktorunscenarioupdatetaskupdateclientdownload"></a>Office.ClickToRun.Scenario.UpdateTaskUpdateclientdownload

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai Spustelėkite ir naudokitės klientas atsisiunčia naujesnę kliento versiją. Naudojami vertinant „Office“ naujinimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida 

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –** unikalusis kompiuterio ID, naudojamas „Windows SQM“

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenarioupdatetaskupdatedetection"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatedetection

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai Spustelėkite ir naudokitės klientas tikrina, ar yra naujas naujinimas. Naudojami vertinant „Office“ naujinimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –** į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_AvailableVersion -** į kokią „Office“ versiją galima naujinti

  - **Data\_ComAction –** sveikasis skaičius, nurodantis atliekamą „com“ veiksmą

  - **Data\_CompletedWithoutActionInfo –** kodėl neužbaigėme scenarijaus, pvz., buvo atidarytos programos

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_PackageUpdateAvailable –** teisinga, jei yra nauja „Office“ versija

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –**  kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –**  unikalusis kompiuterio ID, kurį naudoja „Windows SQM“ 

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenarioupdatetaskupdatedownload"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatedownload

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai Spustelėkite ir naudokitės klientas atsisiunčia naują naujinimą. Naudojami vertinant „Office“ naujinimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –**  į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_AvailableVersion -** į kokią „Office“ versiją galima naujinti

  - **Data\_CompletedWithoutActionInfo –** kodėl neužbaigėme scenarijaus, pvz., buvo atidarytos programos

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_CorruptionChecksOnly –** jei tik tikrinama dėl sugadinimo, o ne naujinama

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida

  - **Data\_ExceptionType –** išimtis 

  - **Data\_FoundCorruptFiles –** teisinga, jei radome sugadintų failų

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_PackageOperationSuccessful –** teisinga, jei sėkmingai užbaigta užduotis „Office“ pakete

  - **Data\_PipelineExitCode –** failų srauto pateiktas išėjimo kodas

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –** unikalusis kompiuterio ID, naudojamas „Windows SQM“ 

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktorunscenarioupdatetaskupdatefinalize"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatefinalize

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai Spustelėkite ir naudokitės klientas valo po naujinimo ir atkuria anksčiau atidarytas programas. Naudojami vertinant „Office“ naujinimo sėkmingumą.

Renkami šių laukų duomenys:

  - **Data\_15\_SourceType –** kur yra „Office 15“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_15\_UpdatesEnabled –** ar įgalinti „Office 15“ naujinimai 

  - **Data\_15\_UpdateVersion –**  į kokią „Office 15“ versiją naujinama 

  - **Data\_15\_Version –** „Office 15“ versija 

  - **Data\_16\_SourceType –** kur yra „Office 16“ šaltinis, pvz., CDN arba vietoje 

  - **Data\_16\_UpdatesEnabled –** ar įgalinti „Office 16“ naujinimai 

  - **Data\_16\_UpdateVersion –** į kokią „Office 16“ versiją naujinama 

  - **Data\_16\_Version –** „Office 16“ versija 

  - **Data\_AddingFixedProducts –** įtraukiami produktai 

  - **Data\_AddingProducts –** kokius produktus mūsų prašoma įtraukti 

  - **Data\_CompletionState –** ar įvykdėme užduotį

  - **Data\_ErrorCode –** įvykusios klaidos kodas 

  - **Data\_ErrorDetails –** papildoma informacija apie klaidą 

  - **Data\_ErrorMessage –** klaidos pranešimas 

  - **Data\_ErrorSource –** kur įvyko klaida 

  - **Data\_ExceptionType –** išimtis 

  - **Data\_IsErrorCodeIgnorable –** ar klaidos kodą galima ignoruoti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** ar, mūsų manymu, klaidos kodą galima ignoruoti 

  - **Data\_NewestPackageVersion –** naujausia „Office“ versija kompiuteryje 

  - **Data\_OldestPackageVersion –** seniausia „Office“ versija kompiuteryje 

  - **Data\_ProductsToAdd –** kokius „Office“ produktus įtraukiame 

  - **Data\_ProductsToRemove –** kokius „Office“ produktus šaliname 

  - **Data\_RemovingFixedProducts –** šalinami produktai 

  - **Data\_RemovingProducts –** produktai, kuriuos mūsų rašoma pašalinti 

  - **Data\_ScenarioInstanceID –** vykdomo scenarijaus unikalusis GUID 

  - **Data\_ScenarioName –** koks scenarijus vykdomas. Pvz., diegimas 

  - **Data\_ScenarioSubType –** kokio tipo scenarijus vykdomas, pvz., pašalinimas, diegimas iš naujo 

  - **Data\_SourceType –** kur yra šaltinis, pvz., CDN 

  - **Data\_SqmMachineID –**  unikalusis kompiuterio ID, kurį naudoja „Windows SQM“ 

  - **Data\_SusClientID –** kompiuterio „Office“ naujinimo identifikatorius 

  - **Data\_TaskState –** kokia užduoties būsena, pvz., vykdoma arba atšaukta 

  - **Data\_TotalClientCabSize –** kliento .cab failo dydis 

  - **Data\_TriggeringUI –** kas suaktyvino vartotojo sąsają 

  - **Data\_UpdatesEnabled –** ar „Office“ naujinimai įgalinti 

  - **Data\_Version –** „Office“ versija 

### <a name="officeclicktoruntransportexperimentaltransportpipelinecreatetransport"></a>Office.ClickToRun.Transport.ExperimentalTransport.PipelineCreateTransport

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai Spustelėkite ir naudokitės klientas kuria perdavimo srautą, kad atsisiųstų „Office“ failus. Naudojami nustatant įvairių perdavimo technologijų (pvz., HTTP, BITS, DO) sveikatą. Tai svarbu, kad „Office“ būtų tinkamai atsisiųsta diegiant ir naujinant.

Renkami šių laukų duomenys:

  - **Data\_IsForeGroundStreaming** – jei perduodama srautu priekiniame plane arba fone

  - **Data\_IsInstallMode** – 1, jei diegiami ir atsisiunčiami failai, 0, jei ne

  - **Data\_SourceProtocol –** jei atsisiunčiame iš turinio duomenų tinklo, CDN, kompiuterio, kuriame diegiama, vietinio katalogo arba iš ištekliaus vietiniame tinkle

  - **Data\_Status** – pavyko ar nepavyko 

### <a name="officeclicktorunupdatestatus"></a>Office.ClickToRun.UpdateStatus

„Office“ sąrankos ir inventoriaus duomenys, renkami, kai Spustelėkite ir naudokitės klientas baigia naujinti būseną.

Renkami šių laukų duomenys:

  - **Data\_build** – šiuo metu įdiegta „Office“ versija

  - **Data\_channel** – kanalas, kuriame yra vartotojas

  - **Data\_errorCode** – sveikųjų skaičių kodas, nurodantis įvykusios klaidos (jei buvo) kodą

  - **Data\_errorMessage** – eilutė, kurioje pateikiamas įvykusios klaidos (jei buvo) aprašas

  - **Data\_status** – trumpa naujinimo būsena, pvz., Pavyko arba Atsisiųsta

  - **Data\_targetBuild** –„Office“ versija, į kurią bandoma atnaujinti


## <a name="enhanced-configuration-service-ecs-events"></a>Patobulintos konfigūravimo paslaugos (ECS) įvykiai

### <a name="officeexperimentationfeaturequerybatched"></a>Office.Experimentation.FeatureQueryBatched

Renka informaciją apie funkcijų prievadus / keitimo prievadus, kurių užklausą pateikė vykdytas kodas.

Renkami šių laukų duomenys:

  - **Count** – užklaustų funkcijų prievadų skaičius šiame paketiniame įvykyje

  - **Features** – informacija apie užklaustą prievadą.

  - **Sequence** – FeatureGate užklausimo tvarka

### <a name="officeexperimentationflightnumberline"></a>Office.Experimentation.FlightNumberLine

Renka konfigūracijų, kurias klientas gavo iš ECS, sąrašą

Renkami šių laukų duomenys:

  - **ECSConfigs** – kableliu atskirtų ECS konfigūracijų sąrašas

  - **LockType** – FlightManager užrakto tipas.

  - **TasFlightingVersion** – versijos numeris

  - **TimeToLock** – laikas nuo „liblet“ inicijavimo iki FlightManager užrakto

  - **UnmergedConfigs** – nesujungtų konfigūracijų sąrašas


## <a name="licensing-events"></a>Licencijavimo įvykiai

### <a name="officelicensingaccepteulaforcurrentlicense"></a>Office.Licensing.AcceptEulaForCurrentLicense 

Renkami, kai vartotojas licencijuojamas ir sutinka su dabartinės licencijos GVLS

Jie naudojami nustatant, ar vartotojo būsena yra tinkama, taip pat sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą

Renkami šių laukų duomenys:

  - **ACID** – GUID identifikatorius, nurodantis „Office“ produktą, kurio licencija suteikta vartotojui

  - **DwEulaId** – GVLS, su kuriomis vartotojas ką tik sutiko, tipo skaitinis identifikatorius

### <a name="officelicensingactivation"></a>Office.Licensing.Activation 

Nustatę licenciją kompiuteryje, bandome suaktyvinti licenciją iškviesdami AVS paslaugą. Tai praneša apie aktyvinimo iškvietimo rezultatą

Svarbu nustatyti, kiek vartotojų turi aktyvinimo problemų. Anomalijų aptikimo funkcija aptinka suprastėjimą. Tai ypač svarbu, nes yra išorinė priklausomybė nuo AVS ir šis signalas nurodo, ar mūsų išorinių partnerių būklė yra gera. Tai taip pat naudojama diagnostikos ir sistemos sveikatos tikslais, jei vartotojas praneša apie kompiuterio problemą

Renkami šių laukų duomenys:

  - **Acid** – GUID identifikatorius, nurodantis „Office“ produktą, kurio licencija suteikta vartotojui

  - **ReferralData** – OĮG, kuris įdiegė „Office“ kompiuteryje, identifikatorius

### <a name="officelicensingactivationwizard"></a>Office.Licensing.ActivationWizard 

Jei dėl kokios nors priežasties negalime automatiškai suaktyvinti licencijos, vartotojui parodomas aktyvinimo vediklis. Tai praneša, kad vartotojui rodomas vediklis. Tai svarbu nustatant, ar vartotojo būsena yra tinkama ir jam veikia visos funkcijos, taip pat naudojama sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą

Šis įvykis nerenka jokių laukų duomenų.

### <a name="officelicensingenforcesigninqualified"></a>Office.Licensing.EnforceSignInQualified 

Signalas, kuris nurodo, ar sėkmingas eksperimentas, kurį vykdant vartotojų reikalaujama prisijungti licencijuojant. Tai svarbu nustatant, ar sėkmingas eksperimentas, kurį vykdant vartotojų reikalaujama prisijungti; tai reikalaujamas šiuolaikinio licencijavimo proceso veiksmas. Nesėkmingo prisijungimo atveju vartotojai negalės naudoti programą.

Renkami šių laukų duomenys:

  - **Qualified** – identifikuojama, ar vartotojo gali būti reikalaujama prisijungti

### <a name="officelicensingexpirationdialogshown"></a>Office.Licensing.ExpirationDialogShown

Renkama, kai rodome galiojimo pabaigos dialogo langą vartotojui, kuriame sakoma, kad licencijos galiojimas baigėsi. Tai svarbu nustatant, ar vartotojo būsena yra tinkama ir jam veikia visos funkcijos, taip pat naudojama sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą

Renkami šių laukų duomenys:

  - **LicNotificationState** – numeris, kuris pasako mums, koks pranešimas rodomas vartotojui

### <a name="officelicensingfullvalidation"></a>Office.Licensing.FullValidation 

Renkama kiekviename seanse, kuriame pranešama kompiuterio licencijavimo būsena ir vartotojo matomos klaidos, dėl kurių jis negali naudoti programos. Šis įvykis nurodo, ar vartotojo kompiuterio sveikata gera, ar ne. Šio įvykio anomalijų aptikimo funkcija nurodo, ar netinkamą vartotojo elgseną kelia veikimo suprastėjimas. Tai taip pat svarbu diagnozuojant vartotojo problemas ir stebint sistemos sveikatą

Renkami šių laukų duomenys:

  - **Acid** – GUID identifikatorius, nurodantis „Office“ produktą, kurio licencija suteikta vartotojui 

  - **IsSessionLicensing** – ar šiuo metu vykdomas bendrai naudojamo kompiuterio aktyvinimo režimas, ar ne 

  - **LicenseCategory** – „Office“ licencijos, kurią naudoja vartotojas, kategorija 

  - **Licenses** – visų „Office“ licencijų, kurios yra kompiuteryje, pavadinimų sąrašas 

  - **LicenseStatuses** – visų „Office“ licencijų, kurios yra kompiuteryje, būsena 

### <a name="officelicensinggetentitlement"></a>Office.Licensing.GetEntitlement 

Renkame, kai vartotojas nustato įrenginį, ir iškviečiame licencijavimo paslaugą, kad aptiktume, ar prisijungęs vartotojas turi teisę naudotis „Office“, ar ne. Tai praneša apie to iškvietimo rezultatą. Tai svarbu nustatant, ar vartotojo būsena yra tinkama ir jam veikia visos funkcijos, taip pat naudojama sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą

Šis įvykis nerenka jokių laukų duomenų.

### <a name="officelicensingheartbeat"></a>Office.Licensing.Heartbeat 

Kiekviename seanse tikriname, ar praėjo 72 valandos nuo paskutinio licencijos atnaujinimo, ir bandome pratęsti dabartinės licencijos galiojimą. Šis įvykis praneša, ar sėkmingas iškvietimas, kurį atlikome, siekdami užtikrinti, kad galime pratęsti licencijos galiojimą ir kad vartotojo „Office“ įdiegtis yra veikianti. Tai svarbu diagnozuojant vartotojo su prenumerata susijusias ir paslaugų problemas, taip pat aptinkant veikimo suprastėjimą jau prenumeratą suaktyvinusiems vartotojams.

Renkami šių laukų duomenys:

  - **Mode** – numeris, nurodantis šiame kompiuteryje naudojamą „Office“ licencijavimo procesą

### <a name="officelicensinginrfm"></a>Office.Licensing.InRFM 

Jei įjungiamas įrenginio sumažinto funkcionalumo režimas, išsiunčiame šį signalą, kad nurodytume, jog įrenginio sveikata nėra gera. Tai svarbu nustatant, ar vartotojo būsena yra tinkama ir jam veikia visos funkcijos, taip pat naudojama sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą

Renkami šių laukų duomenys:

  - **ACID** – GUID identifikatorius, nurodantis „Office“ produktą, kurio licencija suteikta vartotojui

  - **DaysRemaining** – iki dabartinės „Office“ licencijos galiojimo pabaigos likusių dienų skaičius

  - **Mode** – numeris, nurodantis šiame kompiuteryje naudojamą „Office“ licencijavimo procesą

  - **ProductName** – šiuo metu vartotojo naudojamo produkto pavadinimas

  - **Reason** – klaidos kodas, nurodantis dabartinės licencijos būsenos priežastį

### <a name="officelicensinginstallkey"></a>Office.Licensing.InstallKey

Renkama, kai bandome įdiegti raktą įrenginyje, kad licencijuotume kompiuterį. Tai praneša, ar diegimas sėkmingas ir ar nebuvo gautas klaidos kodas. Tai svarbu nustatant, ar vartotojo būsena yra tinkama ir jam veikia visos funkcijos, taip pat naudojama sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą

Renkami šių laukų duomenys:

  - **Prid** – produktų grupės, kurios raktas diegiamas, pavadinimas

  - **SkuId** – GUID identifikatorius, nurodantis „Office“ produktą, kurio kodas diegiamas 

### <a name="officelicensinginvokelicensewizard"></a>Office.Licensing.InvokeLicenseWizard

Jei matome problemų dėl aktyvinimo darbo eigos, suaktyviname licencijos vediklį ir išsiunčiame šį signalą, kad tai nurodytume. Tai svarbu nustatant, ar vartotojo būsena yra tinkama ir jam veikia visos funkcijos, taip pat naudojama sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą

Renkami šių laukų duomenys:

  - **Acid** – GUID identifikatorius, nurodantis „Office“ produktą, kurio licencija suteikta vartotojui

  - **LicenseStatus** – „Office“ licencijos, kurią naudoja vartotojas, būsena

  - **MachineKey** – vartotojui išduoto licencijos rakto iš raidžių ir skaitmenų sudarytas identifikatorius

### <a name="officelicensinglicensingbar"></a>Office.Licensing.LicensingBar

Jei įrenginyje kyla licencijavimo problemų ir vartotojui parodoma licencijavimo juosta, išsiunčiame šį signalą, kuris taip pat praneša apie vartotojui parodytos licencijavimo juostos tipą. Tai svarbu nustatant, ar vartotojo būsena yra tinkama ir jam veikia visos funkcijos, taip pat naudojama sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą.

Renkami šių laukų duomenys:

  - **SuppressNotification** – nurodo, ar nerodėme licencijavimo juostos

  - **Title** – vartotojui parodytos licencijavimo juostos pavadinimas

  - **Type** – vartotojui parodytos licencijavimo juostos tipas

### <a name="officelicensinglicexitofficeprocess"></a>Office.Licensing.LicExitOfficeProcess 

Jei uždarome „Office“ arba įvyksta jo gedimas dėl licencijavimo problemos, išsiunčiame šį signalą, kad tai nurodytume. Tai svarbu nustatant, ar vartotojo būsena yra tinkama ir jam veikia visos funkcijos, taip pat naudojama sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą.

Renkami šių laukų duomenys:

  - **ExitCode** – vidinis kodas, dėl kurio programa išjungta

### <a name="officelicensingloadidentityticket"></a>Office.Licensing.LoadIdentityTicket

Bandant licencijuoti įrenginį programa bando įkelti vartotojo tapatybę, kad galėtų sužinoti, ar jis turi teisę naudoti „Office“, ar ne. Šis įvykis praneša apie sėkmingą įvykdymą arba triktį kartu su klaidos kodu. Tai svarbu nustatant, ar vartotojo būsena yra tinkama ir jam veikia visos funkcijos, taip pat naudojama sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą.

Renkami šių laukų duomenys:

  - **FederationProvider** – eilutė, kurioje identifikuojamas šiuo metu prisijungusio vartotojo susiejimo teikėjas

  - **IdentityProvider** – eilutė, kurioje identifikuojamas šiuo metu prisijungusio vartotojo tapatybės teikėjas

### <a name="officelicensinglvuxeulaexplicitcrash"></a>Office.Licensing.LVUX.EULAExplicitCrash 

Renkama, jei parodėme GVLS vartotojui ir vartotojas pasirinko su ja nesutikti, dėl ko uždarėme programą arba įvyko jos gedimas. Tai svarbu nustatant, ar vartotojo būsena yra tinkama ir jam veikia visos funkcijos, taip pat naudojama sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą.

Renkami šių laukų duomenys:

  - **Acid** – GUID identifikatorius, nurodantis „Office“ produktą, kurio licencija suteikta vartotojui

  - **OptInShown** – nurodo, ar pasirinkimo dialogo langas, rodomas per pirmąją programos įkrovą, jau buvo parodytas

  - **Office.Licensing.NextUserLicensingEligible –** šis signalas pasako, ar vartotojas atitinka perkėlimo į mūsų naują licencijavimo procesą reikalavimus. Tai svarbu vertinant poveikį esamiems vartotojams, kai diegiame naują licencijavimo procesą, ir siekiant užtikrinti, kad vartotojams veiktų visos funkcijos

Šis įvykis nerenka jokių laukų duomenų.

### <a name="officelicensingnulfetcherfetchmodelfromols"></a>Office.Licensing.Nul.Fetcher.FetchModelFromOls

Kai įrenginiui taikomas šiuolaikinis licencijavimo procesas, bandome gauti licencijos failą tiesiai iš paslaugos. Šis įvykis praneša apie sėkmingą įvykdymą arba triktį kartu su paslaugos iškvietimo klaidos kodu. Tai svarbu nustatant, ar vartotojo būsena šiuolaikiniame licencijavimo procese yra tinkama, taip pat naudojama sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą.

Renkami šių laukų duomenys:

  - **MetadataValidationResult** – licencijos metaduomenų patikrinimo, siekiant patvirtinti, kad licencija nėra piktavališkai pakeista, rezultatas

  - **SignatureValidationResult** – licencijos parašo patikrinimo, siekiant patvirtinti, kad licencija nėra piktavališkai pakeista, rezultatas

### <a name="officelicensingnulvalidationfullvalidation"></a>Office.Licensing.Nul.Validation.FullValidation 

Renkama kiekviename įrenginio, kuriam taikomas šiuolaikinis licencijavimo procesas, seanse. Pranešama kompiuterio licencijavimo būsena ir vartotojo matomos klaidos, dėl kurių jis negali naudoti programos. Šis įvykis nurodo, ar vartotojo kompiuterio sveikata šiuolaikiniame licencijavimo procese yra gera. Šio įvykio anomalijų aptikimo funkcija nurodo, ar netinkamą vartotojo elgseną kelia veikimo suprastėjimas. Tai taip pat svarbu diagnozuojant vartotojo problemas ir stebint sistemos sveikatą.

Renkami šių laukų duomenys:

  - **Acid** – GUID identifikatorius, nurodantis „Office“ produktą, kurio licencija suteikta vartotojui 

  - **AllAcids** – visų produkto, kurio licenciją vartotojas šiuo metu turi, GUID sąrašas 

  - **Category** – „Office“ licencijos, kurią naudoja vartotojas, kategorija 

  - **DaysRemaining** – iki dabartinės „Office“ licencijos galiojimo pabaigos likusių dienų skaičius 

  - **LicenseId** – vartotojui išduotos licencijos iš raidžių ir skaitmenų sudarytas identifikatorius 

  - **LicenseType** – „Office“ licencijos, kurią naudoja vartotojas, tipas 

### <a name="officelicensingofficeclientlicensingdolicensevalidation"></a>Office.Licensing.OfficeClientLicensing.DoLicenseValidation 

Licencijavimo metaduomenys, renkami iš įrenginio per kiekvieną įkrovą, kurie praneša licencijos ACID, licencijos būseną, tipą ir kitas licencijos ypatybes, kurios svarbios identifikuojant vartotojui pasiekiamų funkcijų rinkinį. Tai svarbu identifikuojant vartotojui pasiekiamų funkcijų rinkinį ir vartotojui trūkstamas funkcijas. Tai taip pat naudojama apskaičiuojant dienos / mėnesio aktyvių vartotojų skaičių ir pateikiant įvairias kitas ataskaitas įvairioms „Office“ komandoms, nes tai praneša vartotojo naudojamo produkto tipą, ar tai produkto prenumerata ir ar jam netrūksta svarbių funkcijų.

Renkami šių laukų duomenys:

  - **FullValidationMode** – režimas, nurodantis, kad vykdomas išsamus licencijos patikrinimas 

  - **IsRFM** – nurodo, ar vartotojas dirba sumažinto funkcionalumo režimu, ar ne 

  - **IsSCA** – nurodoma, ar veikia bendrai naudojamo kompiuterio aktyvinimo režimas 

  - **IsSubscription** – nurodo, ar vartotojas naudoja prenumeratos licenciją, ar ne 

  - **IsvNext** – nurodo ar naudojame naują šiuolaikinį licencijavimo procesą, ar ne 

  - **LicenseCategory** – „Office“ licencijos, kurią naudoja vartotojas, kategorija 

  - **LicenseStatus** – „Office“ licencijos, kurią naudoja vartotojas, būsena 

  - **LicenseType** – „Office“ licencijos, kurią naudoja vartotojas, tipas 

  - **LicensingACID** – GUID identifikatorius, nurodantis „Office“ produktą, kurio licencija suteikta vartotojui 

  - **OlsLicenseId** – vartotojui išduotos licencijos iš raidžių ir skaitmenų sudarytas identifikatorius 

  - **SkuIdIsNull** – nurodo, ar įvyko klaida ir nežinome, kokį produktą naudoja vartotojas 

  - **SlapiIsNull** – nurodo, ar kilo problema kuriant vieną iš licencijavimo objektų 

### <a name="officelicensingonlinerepair"></a>Office.Licensing.OnlineRepair 

Jei dėl kokios nors priežasties negalime suaktyvinti vartotojo ir turime parodyti dialogo langą, kuriame jo prašoma prisijungti ir bandyti atlikti taisymo veiksmus, suaktyvinamas šis įvykis. Tai svarbu nustatant, ar vartotojo būsena yra tinkama ir jam veikia visos funkcijos, taip pat naudojama sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą

Šis įvykis nerenka jokių laukų duomenų.

### <a name="officelicensingpurchase"></a>Office.Licensing.Purchase 

Yra eksperimentas, kuris suteikia vartotojui galimybę bandyti nustatyti „Office“ automatinį paleidimą tiesiai iš programos, nepaliekant programos konteksto. Tai praneša apie sėkmingą to eksperimento įvykdymą arba triktį kartu su klaidos kodu. Tai svarbu nustatant, ar vartotojo būsena yra tinkama ir jam veikia visos funkcijos, taip pat naudojama sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą.

Renkami šių laukų duomenys:

  - **StorePurchaseStatus** – pateikia pirkimo iškvietimo, kuris buvo pateiktas „Windows“ parduotuvėje, klaidos kodą / sėkmingo įvykdymo kodą

### <a name="officelicensingsearchforsessiontoken"></a>Office.Licensing.SearchForSessionToken

Bendrai naudojamo kompiuterio režimo atveju bandome ieškoti seanso atpažinimo ženklo kompiuteryje. Tai leidžia vartotojui naudoti programą. Šis įvykis praneša apie sėkmingą scenarijaus įvykdymą arba triktį kartu su klaidos kodu. Tai svarbu nustatant, ar vartotojo būsena yra tinkama ir jam veikia visos funkcijos, taip pat naudojama sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą.

Renkami šių laukų duomenys:

  - **LoadLicenseResult** – pateikia klaidos kodą / sėkmingo įvykdymo kodą, susijusį su tuo, ar mums pavyko įkelti dabartinio vartotojo licencijas

  - **OpportunisticTokenRenewalAttempted** – nurodo, ar bandėme atnaujinti vartotojo seanso atpažinimo ženklą oportunistiškai

  - **SetAcidResult** – pateikia klaidos kodą / sėkmingo įvykdymo kodą, susijusį su tuo, ar mums pavyko nustatyti ACID kaip numatytą reikšmę

### <a name="officelicensingshownewdeviceactivationdialog"></a>Office.Licensing.ShowNewDeviceActivationDialog

Pirmąjį kartą įkraunant „Office“ programą bandome parodyti prisijungimo dialogo langą, kuriame iš anksto įvesti atsisiunčiant „Office“ vartotojo naudoti kredencialai. Vartotojas gali tęsti prisijungimą naudodamas tuos kredencialus, naudoti kitokius kredencialus arba išjungti dialogo langą. Šis įvykis praneša apie vartotojo atliktą veiksmą, kai jam buvo parodytas šis dialogo langas. Tai svarbu nustatant, ar vartotojo būsena šiuolaikiniame licencijavimo procese yra tinkama, taip pat naudojama sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą

Renkami šių laukų duomenys:

  - **UserAction** – vartotojo atlikto veiksmo, kai jam buvo parodytas dialogo langas, identifikatorius.

### <a name="officelicensingskutoskuconversion"></a>Office.Licensing.SkuToSkuConversion

Jei licencijuodami vartotoją turime pakeisti vartotojo SKU iš vieno SKU į kitą, išsiunčiame šį signalą kartu su sėkmingo įvykdymo arba trikties kodu. Tai svarbu nustatant, ar vartotojo būsena yra tinkama ir jam veikia visos funkcijos, taip pat naudojama sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą.

Renkami šių laukų duomenys:

  - **DestinationSku** – SKU, į kurį turi būti konvertuotas šiuo metu įdiegtas produktas, pavadinimas

  - **PendingAcid** – produkto, kurio SKU konvertavimas laukia, ID

  - **SourceSku** – pradinio SKU, kuris buvo įdiegtas kompiuteryje, pavadinimas

  - **UninstallProduct** – nurodo, ar senasis produktas bus pašalintas konvertuojant

### <a name="officelicensingusegracekey"></a>Office.Licensing.UseGraceKey

Jei dėl kokios nors priežasties nepavyksta licencijuoti vartotojo, įdiegiame atidėjimo raktą ir išsiunčiame šį signalą. Tai svarbu nustatant, ar vartotojo būsena yra tinkama ir jam veikia visos funkcijos, taip pat naudojama sistemos sveikatos ir diagnostikos tikslais, jei vartotojas praneša apie kompiuterio problemą

Renkami šių laukų duomenys:

  - **OpportunisticTokenRenewalAttempted** – nurodo, ar bandėme oportunistiškai atnaujinti vartotojui bendrai naudojamo kompiuterio aktyvinimo režimu

  - **ReArmResult** – nurodo įdiegto rakto, kuris gali pratęsti dabartinės licencijos galiojimą, pradinės licencijavimo būsenos atkūrimo rezultatą

## <a name="services-configuration-events"></a>Paslaugų konfigūravimo įvykiai

Tarnybų konfigūravimo paslauga nerenka būtinųjų tarnybų diagnostikos duomenų įvykių.

## <a name="telemetry-events"></a>Telemetrijos įvykiai

### <a name="officesystemidentitychanged"></a>Office.System.IdentityChanged

Vartotojo tapatybės informacija, reikalinga siekiant įvykdyti duomenų subjekto užklausas.

Renkami šių laukų duomenys:

  - **IdentityChanged** – visada teisinga. Tapatybė pakeista.

  - **TimerDetectedChange** – ar keitimas aptiktas pateikus reguliariai atliekamą ryšio užklausą.

### <a name="officesystemprivacyfallbacktosettingsstore"></a>Office.System.PrivacyFallbackToSettingsStore

Naudojamas norint nustatyti, ar yra trikčių nuskaitant vartotojo privatumo parametrus iš tarptinklinio ryšio saugyklos.

Renkami šių laukų duomenys:

  - **Tag –** kodo žymė, rodanti, kuris parametras vėl grąžintas į parametrų saugyklą.

### <a name="officesystemsessiondatao365"></a>Office.System.SessionDataO365

Metaduomenys, reikalingi siekiant izoliuoti trikties atkartojimą.

Renkami šių laukų duomenys:

  - **AppId –** „Office“ programos, su kuria susiję šie duomenys, identifikatorius.

  - **ApplicationArchitecture –** kokiai procesoriaus architektūrai sukurtas „Office“.

  - **AppVersionBuild –** „Office“ programos komponavimo versija.

  - **AppVersionMajor –** „Office“ programos pagrindinė versija.

  - **AppVersionMinor –** „Office“ programos papildoma versija.

  - **AppVersionUpdate –** „Office“ programos komponavimo versijos peržiūra.

  - **CollectorVersion –** kliento rinkimo logikos versijos identifikatorius.

  - **DeviceHash –** operacinės sistemos įrenginio identifikatoriaus vienpusė maiša.

  - **DeviceName -** įrenginio, kuriame naudojamas „Office“, pavadinimas.

  - **Domain –** įrenginio, kuriame naudojamas „Office“, domenas.

  - **IsCeip –** ar „Office“ įdiegtis buvo užregistruota nebenaudojamoje tobulinimo pagal vartotojų patirtį programoje.

  - **IsDebug –** ar tai „Office“ derinimo komponavimo versija.

  - **IsImmersive –** ar „Office“ programa yra „Universal Windows“, ar „Immersive“ programa.

  - **IsLaptop –** ar „Office“ naudojamas nešiojamajame kompiuteryje.

  - **IsMicrosoftInternal –** ar „Office“ naudojantis „Windows“ vartotojas yra „Microsoft“ darbuotojas.

  - **IsO365 –** ar „Office“ įdiegtas pagal nebenaudojamą „Outlook 365“ programą.

  - **IsTablet –** ar „Office“ naudojamas planšetiniame kompiuteryje.

  - **IsTerminalServer –** ar tai terminalų serverio klientas (teisinga arba klaidinga)

  - **MaxMemory –** maksimalus laisvosios kreipties atminties kiekis, pasiekiamas įrenginyje, kuriame naudojamas „Office“.

  - **OsArchitecture –** operacinės sistemos CPU architektūra, kuriai sukurtas „Office“.

  - **OsVersionBuild –** operacinės sistemos komponavimo versija.

  - **OsVersionMajor –** operacinės sistemos pagrindinė versija.

  - **OsVersionMinor –** operacinės sistemos papildoma versija.

  - **OsVersionUpdate –** OS komponavimo versijos peržiūra

  - **ProcessFileName –** veikiančios programos vykdomojo failo pavadinimas.

  - **ProcessorArchitecture –** kokios architektūros procesorių naudojant veikia „Office“.

  - **ProcessorFrequency –** procesoriaus sparta įrenginiuose, kuriuose naudojamas „Office“, megahercais.

  - **SessionStart -** „Office“ vykdymo proceso pradžios laikas.

  - **UserName –** paskyros, kurioje naudojamas „Office“, pavadinimas.

### <a name="officesystemsystemhealthcoremetadata"></a>Office.System.SystemHealthCoreMetadata

Metaduomenys, reikalingi siekiant izoliuoti trikties atkartojimą.

Renkami šių laukų duomenys:

  - **AppBuild –** „Office“ programos komponavimo versija.

  - **AppBuildRevision –** „Office“ programos komponavimo versijos peržiūra.

  - **AppMajorVer –** „Office“ programos pagrindinė versija.

  - **AppMinorVer –** „Office“ programos papildoma versija.

  - **CID –** pseudoniminė vartotojo tapatybė

  - **CollectibleClassifications –** duomenų klasifikacijų rinkinys, kurį galima rinkti.

  - **CollectionTime –** metaduomenų surinkimo laikas.

  - **DeviceManufacturer –** įrenginio, kuriame naudojamas „Office“, gamintojas.

  - **DeviceModel –** įrenginio, kuriame naudojamas „Office“, modelis.

  - **FirstRunTime –** kada pirmą kartą paleista „Office“ programa.

  - **IsClickToRunInstall –** ar „Office“ programa buvo įdiegta naudojant Spustelėkite ir naudokitės

  - **IsDebug –** ar tai „Office“ derinimo komponavimo versija.

  - **IsLabMachine –** ar „Office“ naudojama „Microsoft“ laboratorijoje.

  - **IsLaptop –** ar „Office“ naudojamas nešiojamajame kompiuteryje.

  - **IsMsftInternal –** ar „Office“ naudojantis „Windows“ vartotojas yra „Microsoft“ darbuotojas.

  - **IsSubscription –** ar „Office“ programa įdiegta pagal prenumeratos licenciją.

  - **IsTablet –** ar „Office“ naudojamas planšetiniame kompiuteryje.

  - **IsTerminalServer –** ar „Office“ naudojama terminalų serveryje.

  - **MsoAppId –** „Office“ programos, su kuria susiję šie duomenys, identifikatorius.

  - **OfficeArchitectureText –** kokiai procesoriaus architektūrai sukurtas „Office“.

  - **OsBuild –** operacinės sistemos komponavimo versija.

  - **OsBuildRevision –** OS komponavimo versijos peržiūra

  - **OSEnvironment –** aplinkos, kurioje naudojamas „Office“, identifikatorius.

  - **OsMajorVer –** operacinės sistemos pagrindinė versija.

  - **OsMinorVer –** operacinės sistemos papildoma versija.

  - **OSVersionString –** operacinės sistemos versija kaip eilutė.

  - **ProcessorArchitecture –** kokios architektūros procesorių naudojant veikia „Office“.

  - **ProcessorCount –** procesorių skaičius įrenginyje, kuriame naudojamas „Office“.

  - **ProcSpeedMHz –** procesoriaus sparta įrenginiuose, kuriuose naudojamas „Office“, megahercais.

  - **RamMB –** RAM kiekis, pasiekiamas įrenginyje, kuriame naudojamas „Office“.

  - **SqmUserId –** „Office“ įdiegties atsitiktinis identifikatorius.

### <a name="officesystemsystemhealthdesktopsessionlifecycleandheartbeat"></a>Office.System.SystemHealthDesktopSessionLifecycleAndHeartbeat

Pateikiama informacija apie sistemos sveikatos metriką.

Renkami šių laukų duomenys:

  - **InstallMethod** – ar į dabartinę „Office“ komponavimo versiją buvo atnaujinta, ji buvo įdiegta atšaukus keitimus, ar tai nauja įdiegtis.

  - **PreviousBuild** – „Office“ versija, į kurią ši komponavimo versija buvo atnaujinta arba kuri buvo įdiegta atšaukus keitimus.

  - **State** – būsena, į kurią pakeistas seansas.

  - **Time** – seanso būsenos pakeitimo laikas.

### <a name="officesystemsystemhealthessentialidentitycount"></a>Office.System.SystemHealthEssentialIdentityCount

Renkamas prisijungusių vartotojų tapatybių skaičius

Renkami šių laukų duomenys:

  - **AllIdentityCount** – visų tapatybių skaičius

  - **ValidIdentityCount** – patikrintų tapatybių skaičius

### <a name="officesystemsystemhealthessentialmetadataallidentities"></a>Office.System.SystemHealthEssentialMetadataAllIdentities

Stebima paskyrų, kurias „Office“ atpažįsta, būsena šiame seanse. Naudojama siekiant izoliuoti paskyros prisijungimo tipo triktį, jei triktis susijusi su konkrečiu tipu.

Renkami šių laukų duomenys:

  - **CollectionTime** – tapatybės informacijos surinkimo laikas.

  - **IdentityType** – autentifikavimo arba paskyros tipas

  - **IdentityUniqueId** – pseudoniminis tapatybės identifikatorius

  - **IdentityUniqueIdHashed** – tapatybės unikaliojo ID vienpusė maiša

### <a name="officesystemsystemhealthmetadataapplicationadditional"></a>Office.System.SystemHealthMetadataApplicationAdditional

Metaduomenys, reikalingi siekiant izoliuoti trikties atkartojimą.

Renkami šių laukų duomenys:

  - **Alias –** jei „Office“ naudojantis vartotojas yra „Microsoft“ darbuotojas, jo įmonės vidinis pseudonimas.

  - **AppBuild –** „Office“ programos komponavimo versija.

  - **AppBuildRevision –** „Office“ programos komponavimo versijos peržiūra.

  - **AppMajorVer –** „Office“ programos pagrindinė versija.

  - **AppMinorVer –** „Office“ programos papildoma versija.

  - **CID –** pseudoniminė vartotojo tapatybė

  - **CollectibleClassifications –** duomenų klasifikacijų rinkinys, kurį galima rinkti.

  - **DeviceManufacturer –** įrenginio, kuriame naudojamas „Office“, gamintojas.

  - **DeviceModel –** įrenginio, kuriame naudojamas „Office“, modelis.

  - **DeviceProcessorModel –** įrenginio, kuriame naudojamas „Office“, procesoriaus modelis.

  - **DigitizerInfo -** informacija apie skaitmeninį keitiklį įrenginyje, kuriame naudojamas „Office“.

  - **DomainName –** domeno, prie kurio prijungtas įrenginys, kuriame naudojamas „Office“, vardas (jei yra).

  - **FirstRunTime –** kada pirmą kartą paleista „Office“ programa.

  - **HorizontalResolution –** horizontali ekrano skiriamoji geba

  - **IsDebug –** ar tai „Office“ derinimo komponavimo versija.

  - **IsImmersive –** ar „Office“ programa yra „Universal Windows“, ar „Immersive“ programa.

  - **IsJoinedToDomain –** ar įrenginys, kuriame naudojamas „Office“, prijungtas prie domeno.

  - **IsLabMachine –** ar „Office“ naudojamas „Microsoft“ laboratorijoje.

  - **IsLaptop –** ar „Office“ naudojamas nešiojamajame kompiuteryje.

  - **IsMsftInternal –** ar „Office“ naudojantis „Windows“ vartotojas yra „Microsoft“ darbuotojas.

  - **IsOEMInstalled –** ar veikiančią „Office“ programą įdiegė OĮG.

  - **IsRunAsAdmin –** ar „Office“ programa paleista kaip administratoriaus.

  - **IsSubscription –** ar „Office“ programa įdiegta pagal prenumeratos licenciją.

  - **MsoAppId –** „Office“ programos, su kuria susiję šie duomenys, identifikatorius.

  - **NumProcPhysCores –** procesoriaus fizinių branduolių skaičius.

  - **OfficeBuild –** „Office“ bendrai naudojamų bibliotekų komponavimo versija.

  - **OfficeBuildRevision –** „Office“ bendrai naudojamų bibliotekų komponavimo versijos peržiūra.

  - **OfficeMajorVer –** „Office“ bendrai naudojamų bibliotekų pagrindinė versija.

  - **OfficeMinorVer –** „Office“ bendrai naudojamų bibliotekų papildoma versija.

  - **OsBuild –** operacinės sistemos komponavimo versija.

  - **OsBuildRevision –** OS komponavimo versijos peržiūra

  - **OsMajorVer –** operacinės sistemos pagrindinė versija.

  - **OsMinorVer –** operacinės sistemos papildoma versija.

  - **PowerPlatformRole –** įrenginio, kuriame naudojamas „Office“, OĮG pageidaujamo kompiuterio vaidmens identifikatorius.

  - **ProcessFileName –** veikiančios programos vykdomojo failo pavadinimas.

  - **ProcessorCount –** procesorių skaičius įrenginyje, kuriame naudojamas „Office“.

  - **RamMB –** RAM kiekis, pasiekiamas įrenginyje, kuriame naudojamas „Office“.

  - **SqmUserId –** „Office“ įdiegties atsitiktinis identifikatorius.

  - **StudyId –** programinės įrangos metrikos tyrimo identifikatorius.

  - **VerticalResolution –** vertikali ekrano skiriamoji geba

  - **WinUserActType –** ar „Office“ naudojantis „Windows“ vartotojas yra vietinis administratorius, įgaliotas vartotojas, ar paprastas vartotojas.

### <a name="officesystemsystemhealthmetadataapplicationandlanguage"></a>Office.System.SystemHealthMetadataApplicationAndLanguage

Metaduomenys reikalingi siekiant izoliuoti trikties atkartojimą.

Renkami šių laukų duomenys:

  - **AppBuild –** „Office“ programos komponavimo versija.

  - **AppBuildRevision –** „Office“ programos komponavimo versijos peržiūra.

  - **AppMajorVer –** „Office“ programos pagrindinė versija.

  - **AppMinorVer –** „Office“ programos papildoma versija.

  - **AppState –** „Office“ programos būsenos identifikatorius.

  - **Click2RunPackageVersionBuild –** Spustelėkite ir naudokitės diegimo paketo komponavimo versija.

  - **Click2RunPackageVersionMajor –** Spustelėkite ir naudokitės diegimo paketo pagrindinė versija.

  - **Click2RunPackageVersionMinor –** Spustelėkite ir naudokitės diegimo paketo papildoma versija.

  - **Click2RunPackageVersionRevision –** Spustelėkite ir naudokitės diegimo paketo komponavimo versijos peržiūra.

  - **DistributionChannel –** kanalas, kuriuo platintas „Office“.

  - **InstallType –** būdo, kuriuo įdiegtas „Office“, identifikatorius.

  - **IsClickToRunInstall –** ar „Office“ programa buvo įdiegta naudojant Spustelėkite ir naudokitės

  - **IsDebug –** ar tai „Office“ derinimo komponavimo versija.

  - **IsImmersive –** ar „Office“ programa yra „Universal Windows“, ar „Immersive“ programa.

  - **IsMsftInternal –** ar „Office“ naudojantis „Windows“ vartotojas yra „Microsoft“ darbuotojas.

  - **IsOEMInstalled –** ar veikiančią „Office“ programą įdiegė OĮG.

  - **IsRunAsAdmin –** ar „Office“ programa paleista kaip administratoriaus.

  - **IsSubscription –** ar „Office“ programa įdiegta pagal prenumeratos licenciją.

  - **MsoAppId –** „Office“ programos, su kuria susiję šie duomenys, identifikatorius.

  - **OfficeArchitectureText –** kokiai procesoriaus architektūrai sukurtas „Office“.

  - **OfficeBuild –** „Office“ bendrai naudojamų bibliotekų komponavimo versija.

  - **OfficeBuildRevision –** „Office“ bendrai naudojamų bibliotekų komponavimo versijos peržiūra.

  - **OfficeMajorVer –** „Office“ bendrai naudojamų bibliotekų pagrindinė versija.

  - **OfficeMinorVer –** „Office“ bendrai naudojamų bibliotekų papildoma versija.

  - **OfficeMuiCount –** įdiegtų „Office“ kalbos paketų skaičius.

  - **OfficeSkuLanguage –** įdiegta SKU kalba.

  - **OfficeSkuLanguageTag –** įdiegta SKU kalba.

  - **OfficeUiLang –** „Office“ programos vartotojo sąsajos kalba.

  - **OfficeUiLangTag –** „Office“ programos vartotojo sąsajos kalba.

  - **ProcessFileName –** veikiančios programos vykdomojo failo pavadinimas.

  - **SqmAppId –** „Office“ programos, su kuria susiję šie duomenys, identifikatorius.

### <a name="officesystemsystemhealthmetadatadelayedlogin"></a>Office.System.SystemHealthMetadataDelayedLogin

Vartotojo tapatybės informacija, reikalinga siekiant įvykdyti duomenų subjekto užklausas.

Renkami šių laukų duomenys:

  - **CID –** pseudoniminė vartotojo tapatybė

### <a name="officesystemsystemhealthmetadatadevice"></a>Office.System.SystemHealthMetadataDevice

Metaduomenys, reikalingi siekiant izoliuoti trikties atkartojimą.

Renkami šių laukų duomenys:

  - **CollectionTime –** metaduomenų surinkimo laikas.

  - **ComputerSystemProductUuidHash –** pagrindinės plokštės UUID vienpusė maiša.

  - **DeviceClass –** įrenginio, kuriame naudojamas „Office“, tipo identifikatorius.

  - **DeviceMake –** įrenginio, kuriame naudojamas „Office“, aparatūros sistemos šeimos identifikatorius.

  - **DeviceManufacturer –** įrenginio, kuriame naudojamas „Office“, gamintojas.

  - **DeviceModel –** įrenginio, kuriame naudojamas „Office“, modelis.

  - **DigitizerInfo -** informacija apie skaitmeninį keitiklį įrenginyje, kuriame naudojamas „Office“.

  - **IsLaptop –** ar „Office“ naudojamas nešiojamajame kompiuteryje.

  - **IsTablet –** ar „Office“ naudojamas planšetiniame kompiuteryje.

  - **LicensingACID –** „Office“ įdiegties licencijavimo identifikatorius.

  - **MachineName –** įrenginio, kuriame naudojamas „Office“, pavadinimas.

  - **NumProcPhysCores –** procesoriaus fizinių branduolių skaičius.

  - **NumProcShareSingleCache –** procesorių, bendrai naudojančių vieną talpyklą, skaičius įrenginyje, kuriame naudojamas „Office“.

  - **NumProcShareSingleCore –** procesorių vienam fiziniam branduoliui skaičius įrenginyje, kuriame naudojamas „Office“.

  - **OlsLicenseId –** „Office“ įdiegties licencijavimo paslaugos identifikatorius.

  - **Platform –** aplinkos, kurioje naudojamas „Office“, identifikatorius.

  - **PowerPlatformRole –** įrenginio, kuriame naudojamas „Office“, OĮG pageidaujamo kompiuterio vaidmens identifikatorius.

  - **ProcessorCount –** procesorių skaičius įrenginyje, kuriame naudojamas „Office“.

  - **ProcSpeedMHz –** procesoriaus sparta įrenginyje, kuriame naudojamas „Office“, megahercais.

  - **ProcType –** procesoriaus architektūra.

  - **ProcTypeText –** įrenginio, kuriame naudojamas „Office“, procesoriaus tipas.

  - **RamMB –** RAM kiekis, pasiekiamas įrenginyje, kuriame naudojamas „Office“.

  - **SusClientId –** įrenginio, kuriame naudojamas „Office“, „Windows Update“ ID.

  - **SystemFamily –** įrenginio, kuriame naudojamas „Office“, aparatūros sistemos šeimos identifikatorius.

  - **SystemSKU –** įrenginio, kuriame naudojamas „Office“, aparatūros sistemos SKU identifikatorius.

  - **SysVolFreeSpaceMB –** sistemos diske likusios laisvos vietos kiekis megabaitais.

  - **SysVolSizeMB –** sistemos disko vietos kiekis megabaitais.

  - **WindowsErrorReportingMachineId –** įrenginio, kuriame naudojamas „Office“, „Windows“ klaidų ataskaitų priskirto kompiuterio identifikatorius.

  - **WindowsSqmMachineId –** įrenginio, kuriame naudojamas „Office“, „Windows“ priskirto kompiuterio identifikatorius.

### <a name="officesystemsystemhealthmetadatadeviceconsolidated"></a>Office.System.SystemHealthMetadataDeviceConsolidated

Metaduomenys, reikalingi siekiant izoliuoti trikties atkartojimą.

Renkami šių laukų duomenys:

  - **BootDiskType –** diskas arba netrinusis loginis diskas

  - **ComputerSystemProductUuidHash –** pagrindinės plokštės UUID vienpusė maiša.

  - **DeviceClass –** įrenginio, kuriame naudojamas „Office“, tipo identifikatorius.

  - **DeviceManufacturer –** įrenginio, kuriame naudojamas „Office“, gamintojas.

  - **DeviceModel –** įrenginio, kuriame naudojamas „Office“, modelis.

  - **DeviceProcessorModel –** įrenginio, kuriame naudojamas „Office“, procesoriaus modelis.

  - **DigitizerInfo -** informacija apie skaitmeninį keitiklį įrenginyje, kuriame naudojamas „Office“.

  - **HasSpectreFix –** ar įrenginio, kuriame naudojamas „Office“, procesoriui pritaikyta „Spectre“ pataisa.

  - **IsLaptop –** ar „Office“ naudojamas nešiojamajame kompiuteryje.

  - **IsTablet –** ar „Office“ naudojamas planšetiniame kompiuteryje.

  - **MachineName –** įrenginio, kuriame naudojamas „Office“, pavadinimas.

  - **NumProcPhysCores –** procesoriaus fizinių branduolių skaičius.

  - **NumProcShareSingleCache –** procesorių, bendrai naudojančių vieną talpyklą, skaičius įrenginyje, kuriame naudojamas „Office“.

  - **NumProcShareSingleCore –** procesorių vienam fiziniam branduoliui skaičius įrenginyje, kuriame naudojamas „Office“.

  - **Platform –** aplinkos, kurioje naudojamas „Office“, identifikatorius.

  - **PowerPlatformRole –** įrenginio, kuriame naudojamas „Office“, OĮG pageidaujamo kompiuterio vaidmens identifikatorius.

  - **powerPlatformRole –** įrenginio, kuriame naudojamas „Office“, OĮG pageidaujamo kompiuterio vaidmens identifikatorius.

  - **ProcessorCount –** procesorių skaičius įrenginyje, kuriame naudojamas „Office“.

  - **ProcSpeedMHz –** procesoriaus sparta įrenginyje, kuriame naudojamas „Office“, megahercais.

  - **ProcType –** procesoriaus architektūra.

  - **ProcTypeText –** įrenginio, kuriame naudojamas „Office“, procesoriaus tipas.

  - **RamMB –** RAM kiekis, pasiekiamas įrenginyje, kuriame naudojamas „Office“.

  - **SusClientId –** įrenginio, kuriame naudojamas „Office“, „Windows Update“ ID.

  - **SysVolFreeSpaceMB –** sistemos diske likusios laisvos vietos kiekis megabaitais.

  - **SysVolSizeMB –** sistemos disko vietos kiekis megabaitais.

  - **sysVolSizeMB –** sistemos disko vietos kiekis megabaitais.

<!-- end list -->

  - **WindowsErrorReportingMachineId** – įrenginio, kuriame naudojamas „Office“, „Windows“ klaidų ataskaitų priskirto kompiuterio identifikatorius.

  - **WindowsSqmMachineId** – įrenginio, kuriame naudojamas „Office“, „Windows“ priskirto kompiuterio identifikatorius.

### <a name="officesystemsystemhealthmetadataoperatingsystem"></a>Office.System.SystemHealthMetadataOperatingSystem

Metaduomenys, reikalingi siekiant izoliuoti trikties atkartojimą.

Renkami šių laukų duomenys:

  - **CollectionTime** – šio įvykio įtraukimo į nusiuntimo eilę laikas

  - **IsTerminalServer** – ar tai terminalų serverio klientas (teisinga arba klaidinga)

  - **OsBuild** – operacinės sistemos komponavimo versija.

  - **OsBuildRevision** – OS komponavimo versijos peržiūra

  - **OSEnvironment** – „Windows“, „iOS“, „Mac“, „Android“ ir pan.

  - **OsMajorVer** – operacinės sistemos pagrindinė versija.

  - **OsMinorVer** – operacinės sistemos papildoma versija.

  - **OSSDKVersionCode** – operacinės sistemos SDK versijos identifikatorius.

  - **OsSku** – OS SKU

  - **OsSuite2** – operacinės sistemos paketo identifikatorius.

  - **OSVersionString** – operacinės sistemos versijos identifikatorius.

  - **ServicePackMajorVer** – OS pakeitimų paketo pagrindinė versija

  - **ServicePackMinorVer** – OS pakeitimų paketo papildoma versija

### <a name="officesystemsystemhealthmetadataoperatingsystemdevice"></a>Office.System.SystemHealthMetadataOperatingSystemDevice

Metaduomenys, reikalingi siekiant izoliuoti trikties atkartojimą.

Renkami šių laukų duomenys:

  - **CollectionTime –** šio įvykio įtraukimo į nusiuntimo eilę laikas

  - **DeviceClass –** įrenginio, kuriame naudojamas „Office“, tipo identifikatorius.

  - **DeviceManufacturer –** įrenginio, kuriame naudojamas „Office“, gamintojas.

  - **DeviceModel –** įrenginio, kuriame naudojamas „Office“, modelis.

  - **DigitizerInfo -** informacija apie skaitmeninį keitiklį įrenginyje, kuriame naudojamas „Office“.

  - **IsLaptop –** ar „Office“ naudojamas nešiojamajame kompiuteryje.

  - **IsTablet –** ar „Office“ naudojamas planšetiniame kompiuteryje.

  - **IsTerminalServer –** ar tai terminalų serverio klientas (teisinga arba klaidinga)

  - **MachineName –** įrenginio, kuriame naudojamas „Office“, pavadinimas.

  - **NumProcPhysCores –** procesoriaus fizinių branduolių skaičius.

  - **NumProcShareSingleCache –** procesorių, bendrai naudojančių vieną talpyklą, skaičius įrenginyje, kuriame naudojamas „Office“.

  - **NumProcShareSingleCore –** procesorių vienam fiziniam branduoliui skaičius įrenginyje, kuriame naudojamas „Office“.

  - **OsBuild –** operacinės sistemos komponavimo versija.

  - **OsBuildRevision –** OS komponavimo versijos peržiūra

  - **OSEnvironment –** „Windows“, „iOS“, „Mac“, „Android“ ir pan.

  - **OsMajorVer –** operacinės sistemos pagrindinė versija.

  - **OsMinorVer –** operacinės sistemos papildoma versija.

  - **OSSDKVersionCode –** operacinės sistemos SDK versijos identifikatorius.

  - **OsSku –** OS SKU

  - **OsSuite2 –** operacinės sistemos paketo identifikatorius.

  - **OSVersionString –** operacinės sistemos versijos identifikatorius.

  - **Platform –** aplinkos, kurioje naudojamas „Office“, identifikatorius.

  - **PowerPlatformRole –** įrenginio, kuriame naudojamas „Office“, OĮG pageidaujamo kompiuterio vaidmens identifikatorius.

  - **ProcessorCount –** procesorių skaičius įrenginyje, kuriame naudojamas „Office“.

  - **ProcSpeedMHz –** procesoriaus sparta įrenginyje, kuriame naudojamas „Office“, megahercais.

  - **ProcTypeText –** procesoriaus tipas

  - **RamMB –** RAM kiekis, pasiekiamas įrenginyje, kuriame naudojamas „Office“.

  - **ServicePackMajorVer –** OS pakeitimų paketo pagrindinė versija

  - **ServicePackMinorVer –** OS pakeitimų paketo papildoma versija

  - **SysVolFreeSpaceMB –** sistemos diske likusios laisvos vietos kiekis megabaitais.

  - **SysVolSizeMB –** sistemos disko vietos kiekis megabaitais.

### <a name="officesystemsystemhealthmetadataos"></a>Office.System.SystemHealthMetadataOS

Metaduomenys, reikalingi siekiant izoliuoti trikties atkartojimą.

Renkami šių laukų duomenys:

  - **CountryRegion –** šalies / regiono identifikatoriaus operacinės sistemos parametras.

  - **HorizontalResolution –** horizontali ekrano skiriamoji geba

  - **IsTerminalServer –** ar tai terminalų serverio klientas (teisinga arba klaidinga)

  - **KeyboardLanguage –** įrenginio klaviatūros kalbos identifikatorius

  - **KeyboardLanguageTag –** įrenginio klaviatūros kalbos identifikatorius

  - **OfficeWvd –** nurodo „Windows“ virtualiojo darbalaukio būseną.

  - **OsBuild –** operacinės sistemos komponavimo versija.

  - **OsBuildRevision –** OS komponavimo versijos peržiūra

  - **OSEnvironment –** „Windows“, „iOS“, „Mac“, „Android“ ir pan.

  - **OsLocale –** operacinės sistemos lokalės identifikatorius.

  - **OsLocaleTag –** operacinės sistemos lokalės identifikatorius.

  - **OsMajorVer –** operacinės sistemos pagrindinė versija.

  - **OsMinorVer –** operacinės sistemos papildoma versija.

  - **OSSDKVersionCode –** operacinės sistemos SDK versijos identifikatorius.

  - **OsSku –** operacinės sistemos SKU identifikatorius.

  - **OsSuite2 –** operacinės sistemos paketo identifikatorius.

  - **OsUiLang –** operacinės sistemos vartotojo sąsajos kalba.

  - **OSVersionString –** operacinės sistemos versijos identifikatorius.

  - **ScreenDepth –** ekrano spalvų gylis

  - **ScreenDpi –** ekrano taškų colyje skaičius

  - **ServicePackMajorVer –** OS pakeitimų paketo pagrindinė versija

  - **ServicePackMinorVer –** OS pakeitimų paketo papildoma versija

  - **SystemLocale –** operacinės sistemos numatytoji lokalė

  - **SystemLocaleTag –** operacinės sistemos numatytoji lokalė

  - **TimeZoneBiasInMinutes –** skirtumas tarp vietos laiko ir UTC minutėmis.

  - **VerticalResolution –** vertikali ekrano skiriamoji geba

### <a name="officesystemsystemhealthmetadatascreencultureusersqmid"></a>Office.System.SystemHealthMetadataScreenCultureUserSqmId

Metaduomenys, reikalingi siekiant izoliuoti trikties atkartojimą.

Renkami šių laukų duomenys:

  - **Alias –** „Microsoft“ darbuotojas arba automatizuotas vartotojo pseudonimas

  - **CID –** pseudoniminė vartotojo tapatybė

  - **CollectibleClassifications –** duomenų klasifikacijos, kurias galima rinkti pagal kliento privatumo parametrus

  - **CollectionTime –** šio įvykio įtraukimo į nusiuntimo eilę laikas

  - **CountryRegion –** šalies / regiono identifikatoriaus operacinės sistemos parametras.

  - **DomainName –** „Microsoft“ domeno vardas

  - **HorizontalResolution –** horizontali ekrano skiriamoji geba

  - **IntegratedScreenSize –** integruotojo ekrano dydis.

  - **IsJoinedToDomain –** ar klientas prijungtas prie domeno (teisinga arba klaidinga)

  - **IsLabMachine –** ar tai „Microsoft“ testavimo laboratorijos kompiuteris

  - **IsMsftInternal –** ar tai kompiuteris „Microsoft“ įmonės domene (teisinga arba klaidinga)

  - **IsSubscription –** ar „Office“ programa įdiegta pagal prenumeratos licenciją.

  - **KeyboardLanguage –** įrenginio klaviatūros kalbos identifikatorius

  - **KeyboardLanguageTag –** įrenginio klaviatūros kalbos identifikatorius

  - **OsLocale –** operacinės sistemos lokalės identifikatorius.

  - **OsLocaleTag –** operacinės sistemos lokalės identifikatorius.

  - **OsUiLang –** operacinės sistemos vartotojo sąsajos kalba.

  - **ScreenDepth –** ekrano spalvų gylis

  - **ScreenDpi –** ekrano taškų colyje skaičius

  - **ScreenXDpi –** X ekrano taškų colyje skaičius

  - **ScreenYDpi -** Y ekrano taškų colyje skaičius

  - **SqmUserId –** „Office“ įdiegties atsitiktinis identifikatorius.

  - **StudyId –** programinės įrangos metrikos tyrimo identifikatorius.

  - **SystemLocale –** operacinės sistemos numatytoji lokalė

  - **SystemLocaleTag –** operacinės sistemos numatytoji lokalė

  - **TimeZoneBiasInMinutes –** skirtumas tarp vietos laiko ir UTC minutėmis.

  - **VerticalResolution –** vertikali ekrano skiriamoji geba

  - **WinUserActType –** ar „Office“ naudojantis „Windows“ vartotojas yra vietinis administratorius, įgaliotas vartotojas, ar paprastas vartotojas.

### <a name="officesystemsystemhealthofficelensidentity"></a>Office.System.SystemHealthOfficeLensIdentity

Vartotojo tapatybės informacija, reikalinga siekiant įvykdyti duomenų subjekto užklausas.

Renkami šių laukų duomenys:

  - **CID –** pseudoniminė vartotojo tapatybė

### <a name="officesystemsystemhealthrollbacksessionmetadata"></a>Office.System.SystemHealthRollbackSessionMetadata

Metaduomenys, reikalingi siekiant izoliuoti trikties atkartojimą.

Renkami šių laukų duomenys:

  - **InstallMethod** – naujas diegimas, naujinimas arba keitimų atšaukimas

  - **IsSubscription** – ar „Office“ programa įdiegta pagal prenumeratos licenciją.

  - **PreviousBuild** – anksčiau įdiegta komponavimo versija

### <a name="officesystemsystemhealthsessionlifecycleandheartbeat"></a>Office.System.SystemHealthSessionLifecycleAndHeartbeat

Pateikiama informacija apie sistemos sveikatos metriką.

Renkami šių laukų duomenys:

  - **InstallMethod** – ar į dabartinę „Office“ versiją buvo atnaujinta, ji buvo įdiegta atšaukus keitimus, ar tai nauja įdiegtis.

  - **InteractionSessionID** – seanso identifikatorius.

  - **PreviousBuild** – „Office“ versija, į kurią ši komponavimo versija buvo atnaujinta arba kuri buvo įdiegta atšaukus keitimus.

  - **State** – būsena, į kurią pakeistas seansas.

  - **Time** – taškas, kuriame pasikeitė seanso būsena.

### <a name="officesystemsystemhealthsessionstarttime"></a>Office.System.SystemHealthSessionStartTime

Naudojama su gedimo duomenimis, siekiant atskirti ankstyvus ir vėlyvus gedimus (t. y. nustatyti, ar vartotojas kurį laiką naudojo programą prieš gedimą)

Renkami šių laukų duomenys:

  - **SessionStart** – laikas, kada telemetrija pradeda apdoroti duomenis.

### <a name="officesystemsystemhealthungracefulappexitdesktop"></a>Office.System.SystemHealthUngracefulAppExitDesktop

Naudojama gaunant gedimo metriką.

Renkami šių laukų duomenys:

  - **AffectedProcessAppBuild –** paveikto proceso komponavimo versijos identifikatorius.

  - **AffectedProcessAppBuildRevision –** paveikto proceso komponavimo versijos peržiūros identifikatorius.

  - **AffectedProcessAppMinorVer –** paveikto proceso papildomos versijos identifikatorius.

  - **AffectedProcessAppName –** paveikto proceso pavadinimas.

  - **AffectedProcessExeBuildVersion –** paveikto proceso komponavimo versijos numeris.

  - **AffectedProcessExeMajorVersion –** paveikto proceso pagrindinės versijos numeris.

  - **AffectedProcessExeMinorVersion –** paveikto proceso papildomos versijos numeris.

  - **AffectedProcessExeRevisionVersion –** paveikto proceso komponavimo versijos peržiūros numeris.

  - **AffectedProcessIsDebug –** ar paveiktas procesas yra derinimo komponavimo versijoje.

  - **AffectedProcessIsLabMachine –** ar paveiktas procesas yra „Microsoft“ laboratorijoje.

  - **AffectedProcessOsEnvironment –** paveikto proceso operacinės sistemos identifikatorius.

  - **AppName –** paveiktos programos pavadinimas.

  - **CrashedAssignedFlights –** procesams, kuriuose įvyko gedimas, priskirti variantai.

  - **CrashedConfigIds –** procesui, kuriame įvyko gedimas, priskirta konfigūracija.

  - **CrashedEcsETag -** proceso, kuriame įvyko gedimas, eksperimento identifikatorius.

  - **CrashedImpressionId –** proceso, kuriame įvyko gedimas, parodymo identifikatorius.

  - **CrashedProcessSessionID –** proceso, kuriame įvyko gedimas, unikalusis identifikatorius.

  - **CrashedProcessSessionInitTime –** paveikto proceso pradžios laikas.

  - **CrashType –** gedimo tipo skirstymo identifikatorius.

  - **DetectionTime –** netikėto išėjimo aptikimo laikas.

  - **ErrorString –** klaidos aprašas.

  - **ExceptionAddress –** adresas programoje, kur įvyko triktis.

  - **ExceptionCode –** išimties skirstymo identifikatorius.

  - **FaultAppName –** programos su klaida pavadinimas.

  - **InstallMethod –** ar į dabartinę „Office“ komponavimo versiją buvo atnaujinta, ji buvo įdiegta atšaukus keitimus, ar tai nauja įdiegtis.

  - **InstallType –** būdo, kuriuo įdiegtas „Office“, identifikatorius.

  - **InstallTypeName –** būdo, kuriuo įdiegtas „Office“, identifikatorius.

  - **IsLabMachine –** ar „Office“ naudojamas „Microsoft“ laboratorijoje.

  - **IsMsftInternal –** ar „Office“ naudojantis „Windows“ vartotojas yra „Microsoft“ darbuotojas.

  - **ModuleBaseAddress –** modulio su klaida bazinis adresas.

  - **ModuleBuildVersion –** modulio su klaida komponavimo versijos numeris.

  - **ModuleMajorVersion –** modulio su klaida pagrindinės versijos numeris.

  - **ModuleMinorVersion –** modulio su klaida papildomos versijos numeris.

  - **ModuleName –** modulio su klaida pavadinimas.

  - **ModuleOffset –** poslinkis baitais nuo bazinio adreso, kur įvyko triktis.

  - **ModuleRevisionVersion –** modulio su klaida komponavimo versijos peržiūros numeris.

  - **ModuleSize –** modulio su klaida dydis baitais.

  - **OSEnvironment –** aplinkos, kurioje naudojamas „Office“, identifikatorius.

  - **PreviousBuild –** anksčiau įdiegta komponavimo versija

  - **UAETypeName –** programos netinkamo išjungimo skirstymo identifikatorius.

  - **VerifyElseCrashTag –** programos gedimo vietos unikalusis identifikatorius.

### <a name="officesystemsystemhealthungracefulappexitimmersive"></a>Office.System.SystemHealthUngracefulAppExitImmersive

Naudojama gaunant gedimo metriką.

Renkami šių laukų duomenys:

  - **AffectedProcessAppBuild –** paveikto proceso komponavimo versijos identifikatorius.

  - **AffectedProcessAppBuildRevision –** paveikto proceso komponavimo versijos peržiūros identifikatorius.

  - **AffectedProcessAppMajorVer –** paveikto proceso pagrindinės versijos identifikatorius.

  - **AffectedProcessAppMinorVer –** paveikto proceso papildomos versijos identifikatorius.

  - **AffectedProcessAppName –** paveikto proceso pavadinimas.

  - **AffectedProcessExeBuildVersion –** paveikto proceso komponavimo versijos numeris.

  - **AffectedProcessExeMajorVersion –** paveikto proceso pagrindinės versijos numeris.

  - **AffectedProcessExeMinorVersion –** paveikto proceso papildomos versijos numeris.

  - **AffectedProcessExeRevisionVersion –** paveikto proceso komponavimo versijos peržiūros numeris.

  - **AffectedProcessIsDebug –** ar paveiktas procesas yra derinimo komponavimo versijoje.

  - **AffectedProcessIsLabMachine –** ar paveiktas procesas yra „Microsoft“ laboratorijoje.

  - **AffectedProcessOsEnvironment –** paveikto proceso operacinės sistemos identifikatorius.

  - **AppName –** paveiktos programos pavadinimas.

  - **CrashedAssignedFlights –** procesams, kuriuose įvyko gedimas, priskirti variantai.

  - **CrashedConfigIds –** procesui, kuriame įvyko gedimas, priskirta konfigūracija.

  - **CrashedImpressionId –** proceso, kuriame įvyko gedimas, parodymo identifikatorius.

  - **CrashedInteractionSessionID –** paveikto proceso sąveikos seanso identifikatorius.

  - **CrashedInteractionSessionTime –** laikas, kada su paveiktu procesu buvo galima sąveikauti.

  - **CrashedProcessSessionID –** proceso, kuriame įvyko gedimas, unikalusis identifikatorius.

  - **CrashedProcessSessionInitTime –** paveikto proceso pradžios laikas.

  - **DetectionTime –** netikėto išėjimo aptikimo laikas.

  - **IsLabMachine –** ar „Office“ naudojamas „Microsoft“ laboratorijoje.

  - **IsMsftInternal –** ar „Office“ naudojantis „Windows“ vartotojas yra „Microsoft“ darbuotojas.

  - **OSEnvironment –** aplinkos, kurioje naudojamas „Office“, identifikatorius.

  - **PreviousLifecycleState –** paveikto proceso būsena, kai įvyko jo gedimas.

  - **UAETypeName –** programos netinkamo išjungimo skirstymo identifikatorius.

### <a name="officesystemsystemhealthungracefulapplicationexitwin32"></a>Office.System.SystemHealthUngracefulApplicationExitWin32

Naudojama gaunant gedimo metriką.

Renkami šių laukų duomenys:

  - **CrashedAppBuild –** paveikto proceso komponavimo versijos identifikatorius.

  - **CrashedAppMajor –** paveikto proceso pagrindinės versijos identifikatorius.

  - **CrashedAppMinor –** paveikto proceso papildomos versijos identifikatorius.

  - **CrashedAppRevision –** paveikto proceso komponavimo versijos identifikatorius.

  - **CrashedConfigIds –** procesui, kuriame įvyko gedimas, priskirta konfigūracija.

  - **CrashedEcsETag -** proceso, kuriame įvyko gedimas, eksperimento identifikatorius.

  - **CrashedImpressionId –** proceso, kuriame įvyko gedimas, parodymo identifikatorius.

  - **CrashedModuleName –** modulio su klaida pavadinimas.

  - **CrashedSessionId –** proceso, kuriame įvyko gedimas, unikalusis identifikatorius.

  - **CrashedSessionInitTime –** paveikto proceso pradžios laikas.

  - **CrashType –** gedimo tipo skirstymo identifikatorius.

  - **DetectionTime –** netikėto išėjimo aptikimo laikas.

  - **ExceptionAddress –** adresas programoje, kur įvyko triktis.

  - **ExceptionCode –** išimties skirstymo identifikatorius.

  - **HexExceptionAddress –** šešioliktainis adresas programoje, kur įvyko triktis.

  - **HexExceptionCode –** išimties šešioliktainis skirstymo identifikatorius.

  - **HexModuleBaseAddress –** modulio su klaida šešioliktainis bazinis adresas.

  - **HexModuleOffset –** poslinkis baitais (šešioliktainis) nuo bazinio adreso, kur įvyko triktis.

  - **HexModuleSize –** modulio su klaida dydis baitais (šešioliktainis).

  - **HexVerifyElseCrashTag –** programos gedimo vietos šešioliktainis unikalusis identifikatorius.

  - **InstallMethod –** ar į dabartinę „Office“ komponavimo versiją buvo atnaujinta, ji buvo įdiegta atšaukus keitimus, ar tai nauja įdiegtis.

  - **IsLabMachine –** ar „Office“ naudojamas „Microsoft“ laboratorijoje.

  - **ModuleBaseAddress –** modulio su klaida bazinis adresas.

  - **ModuleOffset –** poslinkis baitais nuo bazinio adreso, kur įvyko triktis.

  - **ModuleSize –** modulio su klaida dydis baitais.

  - **PreviousBuild –** anksčiau įdiegta komponavimo versija

  - **UAEOSEnvironment –** operacinės sistemos aplinkos identifikatorius.

  - **VerifyElseCrashTag –** programos gedimo vietos unikalusis identifikatorius.

### <a name="officesystemungracefulapplicationexitdesktopappexit"></a>Office.System.UngracefulApplicationExit.DesktopAppExit

Naudojama gaunant gedimo metriką.

Renkami šių laukų duomenys:

  - **AppBuildVersion –** paveikto proceso komponavimo versijos identifikatorius.

  - **AppMajorVersion –** paveikto proceso pagrindinės versijos numeris.

  - **AppMinorVersion –** paveikto proceso papildomos versijos identifikatorius.

  - **AppName –** paveiktos programos pavadinimas.

  - **AppRevisionVersion –** paveikto proceso komponavimo versijos peržiūros identifikatorius.

  - **CrashedAssignedFlights –** procesams, kuriuose įvyko gedimas, priskirti variantai.

  - **CrashedConfigIds –** procesui, kuriame įvyko gedimas, priskirta konfigūracija.

  - **CrashedImpressionId –** proceso, kuriame įvyko gedimas, parodymo identifikatorius.

  - **CrashedInteractionSessionId –** proceso, kuriame įvyko gedimas, sąveikos seanso identifikatorius.

  - **CrashedProcessSessionID –** proceso, kuriame įvyko gedimas, unikalusis identifikatorius.

  - **CrashType –** gedimo tipo skirstymo identifikatorius.

  - **ErrorString –** klaidos aprašas.

  - **ExceptionAddress –** adresas programoje, kur įvyko triktis.

  - **ExceptionCode –** išimties skirstymo identifikatorius.

  - **FaultAppName –** programos su klaida pavadinimas.

  - **InstallMethod –** ar į dabartinę „Office“ komponavimo versiją buvo atnaujinta, ji buvo įdiegta atšaukus keitimus, ar tai nauja įdiegtis.

  - **InstallType –** būdo, kuriuo įdiegtas „Office“, identifikatorius.

  - **IsDebug –** ar tai „Office“ derinimo komponavimo versija.

  - **IsHandledCrash –** ar gedimo apdorojimo programa buvo iškviesta per gedimo seansą.

  - **IsLabMachine –** ar „Office“ naudojamas „Microsoft“ laboratorijoje.

  - **ModuleBaseAddress –** modulio su klaida bazinis adresas.

  - **ModuleName –** modulio su klaida pavadinimas.

  - **ModuleOffset –** poslinkis baitais nuo bazinio adreso, kur įvyko triktis.

  - **ModuleSize –** modulio su klaida dydis baitais.

  - **OSEnvironment –** aplinkos, kurioje naudojamas „Office“, identifikatorius.

  - **PreviousBuild –** anksčiau įdiegta komponavimo versija

  - **PreviousInteractionSessionTime –** ankstesnio sąveikos seanso pradžios laikas.

  - **PreviousLifecycleState –** ankstesnio seanso ciklo būsenos identifikatorius.

  - **PreviousSessionInitTime –** ankstesnio seanso pradžios laikas.

  - **StackHash –** identifikatorius, nurodantis, kur kode įvyko proceso gedimas.

  - **VerifyElseCrashTag –** programos gedimo vietos unikalusis identifikatorius.

### <a name="officesystemuserchangeddiagnosticlevel"></a>Office.System.UserChangedDiagnosticLevel

Informacija, kurios reikia siekiant užtikrinti, kad pritaikomi vartotojo privatumo strategijos keitimai.

Renkami šių laukų duomenys:

  - **DiagnosticLevelChanged**: nurodo, kad vartotojas pakeitė diagnostikos lygį.

  - **NewDiagnosticLevel**: lygis po vartotojo keitimo.

  - **OldDiagnosticLevel**: lygis, kurį vartotojas naudojo prieš keitimą.

### <a name="officetelemetryariaeventsinkhandlemsadevicetokenresponse"></a>Office.Telemetry.AriaEventSink.HandleMsaDeviceTokenResponse

Trikties „Microsoft“ paskyros paslaugoje signalas.

Renkami šių laukų duomenys:

  - **RetryCount** – pakartotinių bandymų jungiantis prie MSA paslaugos skaičius.

### <a name="officetelemetryariaeventsinkrequestmsadevicetoken"></a>Office.Telemetry.AriaEventSink.RequestMsaDeviceToken

Trikties „Microsoft“ paskyros paslaugoje signalas.

Renkami šių laukų duomenys:

  - **RetryCount** – pakartotinių bandymų jungiantis prie „Microsoft“ paskyros paslaugos skaičius.

### <a name="officetelemetryclientsamplingoverridden"></a>Office.Telemetry.ClientSamplingOverridden

Reikia siekiant gauti tinkamus atkartojimo rodiklius. Paprastai netaikoma gamybos auditorijos grupei.

Renkami šių laukų duomenys:

  - **OverriddenMeasureEnabled** – ar klientas nustatytas siųsti daugiau nei neatrinktus įvykius

  - **OverriddenNumberlinePosition** – nauja numerio eilutės padėtis atrankai

  - **OverriddenReportedSampleRate** – naujas praneštas atrankos dažnis

  - **OverriddenSampleRate** – naujas atrankos dažnis

  - **PreviousNumberlinePosition** – atrankos padėtis numerio eilutėje.

  - **PreviousSampleRate** - atrankos dažnis prieš perrašant.

  - **WasMeasureEnabled** – ar klientas buvo nustatytas siųsti daugiau nei neatrinktus įvykius

### <a name="officetelemetrycomplianceeventnotinbasicallowlist"></a>Office.Telemetry.Compliance.EventNotInBasicAllowList

Praneša apie netinkamą telemetrijos diegimą

Renkami šių laukų duomenys:

  - **EventName** – įvykio, kurio nėra sąraše, pavadinimas

### <a name="officetelemetrycompliancemissingdatacategory"></a>Office.Telemetry.Compliance.MissingDataCategory

Praneša apie netinkamą telemetrijos diegimą

Renkami šių laukų duomenys:

  - **EventName** – įvykio pavadinimas, kuriam trūksta kategorijos

  - **IsFromRule** – ar įvykis gautas iš telemetrijos taisyklės

### <a name="officetelemetrycompliancemissingdatacategoryinrule"></a>Office.Telemetry.Compliance.MissingDataCategoryInRule

Praneša apie netinkamą telemetrijos diegimą

Renkami šių laukų duomenys:

  - **RuleId** – taisyklės ID, kuriam trūksta duomenų kategorijos

  - **RuleVersion** – taisyklės versija, kuriai trūksta duomenų kategorijos

### <a name="officetelemetrydiagnosticdataviewerstatechanged"></a>Office.Telemetry.DiagnosticDataViewerStateChanged

Patikrina, ar vartotojai gali peržiūrėti duomenis, kai jie palieka kompiuterį, naudodami diagnostikos duomenų peržiūros programą.

Renkami šių laukų duomenys:

  - **DialogCancelled** – ar diagnostikos duomenų peržiūros programos dialogo langas buvo atšauktas

  - **NewState** – nauja diagnostikos duomenų peržiūros programos būsena

  - **WasDialogUsed** – ar diagnostikos duomenų peržiūros programos dialogo langas buvo naudojamas

### <a name="officetelemetrydynamicconfigfetchconfigs"></a>Office.Telemetry.DynamicConfig.FetchConfigs

Duomenys, kurių reikia vertinant telemetrijos konfigūravimo paslaugos sveikatą.

Renkami šių laukų duomenys:

  - **ParsedConfigCount** – išanalizuotų dinaminių konfigūracijų skaičius

  - **ParsedConfigs** – išanalizuotų dinaminių konfigūracijų skaičius

  - **RejectedConfigCount** – atmestų konfigūracijų skaičius

  - **RejectedConfigs** – atmestų konfigūracijų skaičius

  - **RejectedConfigsList** – kableliu atskirtų atmestų konfigūracijų sąrašas.

### <a name="officetelemetrydynamicconfigparsejsonconfig"></a>Office.Telemetry.DynamicConfig.ParseJsonConfig

Duomenys, kurių reikia vertinant telemetrijos konfigūravimo paslaugos sveikatą

Renkami šių laukų duomenys:

  - **ErrorMessage** – analizės klaidos pranešimas

  - **NodeName** – mazgas, kurio nepavyko išanalizuoti

### <a name="officetelemetrydynamicconfigpopulatetreecalledagain"></a>Office.Telemetry.DynamicConfig.PopulateTreeCalledAgain

Duomenys, kurių reikia vertinant telemetrijos konfigūravimo paslaugos sveikatą.

Šis įvykis nerenka jokių laukų duomenų.

### <a name="officetelemetryeventquarantined"></a>Office.Telemetry.EventQuarantined

Naudojama tikrinant, ar kiti NSD įvykiai veikia tinkamai.

Renkami šių laukų duomenys:

  - **EventName** – sulaikyto įvykio pavadinimas

  - **Reason** – sulaikymo priežastis

### <a name="officetelemetryflusheventbuffer"></a>Office.Telemetry.FlushEventBuffer 

Praneša įvykio buferio dydį ir gali nurodyti telemetrijos triktis, susijusias su dideliu buferio naudojimu.

Renkami šių laukų duomenys:

  - **EventCount** – įvykių skaičius buferyje

  - **FirstPassCount** – pirmojo apdorojimo įvykių skaičius

  - **SecondPassCount** – antrojo apdorojimo įvykių skaičius

### <a name="officetelemetrygetfilteredpayloadsfromdisk"></a>Office.Telemetry.GetFilteredPayloadsFromDisk

Tikrina, ar tam tikros senstelėjusio telemetrijos srauto dalys veikia platformose, kuriose jis dar naudojamas.

Šis įvykis nerenka jokių laukų duomenų.

### <a name="officetelemetryinvaliddatacontractname"></a>Office.Telemetry.InvalidDataContractName

Praneša apie netinkamą telemetrijos diegimą

Renkami šių laukų duomenys:

  - **DataContractName** – telemetrijos duomenų sutarties pavadinimas

  - **EventName** – įvykio, kurio duomenų sutartis yra netinkama, pavadinimas

  - **IsRuleEvent** – ar įvykį įdiegė telemetrijos taisyklė (teisinga arba klaidinga)

### <a name="officetelemetryinvaliddatafieldname"></a>Office.Telemetry.InvalidDataFieldName 

Praneša apie netinkamą telemetrijos diegimą

Renkami šių laukų duomenys:

  - **DataFieldName** – telemetrijos duomenų lauko pavadinimas

  - **EventName** – įvykio, kurio laukas yra netinkamas, pavadinimas

  - **IsRuleEvent** – ar įvykį įdiegė telemetrijos taisyklė (teisinga arba klaidinga).

### <a name="officetelemetryinvalideventcontractname"></a>Office.Telemetry.InvalidEventContractName 

Praneša apie netinkamą telemetrijos diegimą

Renkami šių laukų duomenys:

  - **EventContractName** – netinkamos telemetrijos sutarties pavadinimas

  - **EventName** – įvykio, kurio sutartis yra netinkama, pavadinimas

  - **IsRuleEvent** – ar įvykį įdiegė telemetrijos taisyklė (teisinga arba klaidinga)

### <a name="officetelemetryloadxmlrules"></a>Office.Telemetry.LoadXmlRules

Praneša, ar sėkmingai įvykdyta telemetrijos taisyklių analizė

Renkami šių laukų duomenys:

  - **DetachedDuration** – atjungties trukmė mikrosekundėmis

### <a name="officetelemetrymissingfielddetails"></a>Office.Telemetry.MissingFieldDetails

Praneša apie trūkstamą laukų informaciją, siekiant diagnozuoti telemetrijos konfigūracijos klaidas.

Renkami šių laukų duomenys:

  - **ErrorRuleId** – telemetrijos taisyklės, kuri pateikė trūkstamo lauko užklausą, ID

  - **ErrorRuleVersion** – telemetrijos taisyklės, kuri pateikė trūkstamo lauko užklausą, versija

  - **EtwEventGuid** – užklausto lauko ETW GUID

  - **EtwEventId** – užklausto lauko ETW įvykio ID

  - **MissingFieldName** – užklausto lauko pavadinimas

  - **UlsTagId** – trūkstamo lauko kodo žymė

### <a name="officetelemetryprocessidlequeuejob"></a>Office.Telemetry.ProcessIdleQueueJob

Praneša, kad telemetrijos laukimo būsenos apdorojimas pradėtas, kaip numatyta.

Renkami šių laukų duomenys:

  - **DetachedDuration** – atjungties trukmė mikrosekundėmis

  - **FailureDiagnostic** – nepavykusi operacija

### <a name="officetelemetryredstoneinboxsampling"></a>Office.Telemetry.RedstoneInboxSampling

Kliento atrankos būsena, reikalinga siekiant tiksliai interpretuoti kitą metriką.

Renkami šių laukų duomenys:

  - **MeasuresEnabled** – ar šiame seanse įgalinti vertinimai?

  - **SamplingClientIdValue** – šio kliento atrankos reikšmė

  - **SamplingKey** – šio kliento atrankos raktas

  - **SamplingMethod** – šio kliento atrankos metodas

### <a name="officetelemetryredstoneinboxsamplingcritical"></a>Office.Telemetry.RedstoneInboxSamplingCritical

Kliento atrankos būsena, kurios gali reikėti siekiant tiksliai interpretuoti kitą metriką.

Renkami šių laukų duomenys:

  - **MeasuresEnabled** – ar šiame seanse įgalinti vertinimai?

  - **SamplingClientIdValue** – šio kliento atrankos reikšmė

  - **SamplingKey** – šio kliento atrankos raktas

  - **SamplingMethod** – šio kliento atrankos metodas

### <a name="officetelemetryruleerrorsaggregated"></a>Office.Telemetry.RuleErrorsAggregated

Telemetrijos sveikatos klaidų pranešimas. Reikia siekiant patikrinti kitus duomenis (įskaitant NSD).

Renkami šių laukų duomenys:

  - **ErrorCount** – šios klaidos skaičius agregavimo laikotarpiu

  - **ErrorInfo** – klaidos diagnostikos informacijos numeris

  - **ErrorRuleId** – telemetrijos taisyklės, kuri sukėlė klaidą, ID

  - **ErrorRuleVersion** – telemetrijos taisyklės, kuri sukėlė klaidą, versija

  - **WarningInfo** – įspėjimo diagnostikos informacijos numeris

<!-- end list -->

  - **QueueFlushCount** – eilės išvalymų skaičius

  - **QueueFlushDueToSizeLimit** – dydis, kurį pasiekus telemetrija išvalo eilę

  - **QueueFlushesDueToSize** – eilės išvalymų dėl buferio dydžio skaičius

  - **QueueHardLimit** – telemetrijos išjungimo riba

  - **QueueLimitHitTime** – kada buvo pasiekta išjungimo riba

  - **ResultTime** – šio įvykio laikas

### <a name="officetelemetryrulesenginediskthrottled"></a>Office.Telemetry.RulesEngineDiskThrottled

DQ metrikos ribojimas. Reikia dėl visų kitų duomenų patikimumo.

Renkami šių laukų duomenys:

  - **DiskWriteLimit** – telemetrijos duomenų disko dydžio riba

  - **DiskWriteTotal** – telemetrijos duomenų rašymo į diską suma

  - **SessionDiskWriteTotal** – telemetrijos duomenų seanso rašymo į diską suma

  - **ThrottlingTimestamp** – seanso ribojimo laikas

### <a name="officetelemetryrulesenginemediumcostthrottled"></a>Office.Telemetry.RulesEngineMediumCostThrottled

DQ metrikos ribojimas. Reikia dėl visų kitų duomenų patikimumo.

Šis įvykis nerenka jokių laukų duomenų.

### <a name="officetelemetryrulesenginespikethrottled"></a>Office.Telemetry.RulesEngineSpikeThrottled

DQ metrikos ribojimas. Reikia dėl visų kitų duomenų patikimumo.

Renkami šių laukų duomenys:

  - **CurrentLimit** – dabartinė padidėjimo riba

  - **Duration** – padidėjimo trukmė

  - **Factor** – padidėjimo koeficientas

  - **HighestImpactingRuleBytes** – didžiausias telemetrijos taisyklės įrašytų baitų skaičius

  - **HighestImpactingRuleId** – taisyklės, kuri įrašė daugiausia baitų, ID

  - **HighestImpactingRuleVersion** – taisyklės, kuri įrašė daugiausia baitų versija

  - **MaxLimit** – maksimali riba

  - **ThrottlingTimestamp** – kada telemetrija buvo apribota

### <a name="officetelemetryrulesenginethrottled"></a>Office.Telemetry.RulesEngineThrottled

DQ metrikos ribojimas. Reikia dėl visų kitų duomenų patikimumo.

Renkami šių laukų duomenys:

  - **ThrottlingTimestamp** – kada telemetrija buvo apribota

### <a name="officetelemetryrulesengineulsqueuesizebackgroundprocessinglevelreached"></a>Office.Telemetry.RulesEngineUlsQueueSizeBackgroundProcessingLevelReached

Praneša, kad eilėje yra per daug įvykių, kad būtų galima apdoroti programos laukimo būsenos laiku.

Renkami šių laukų duomenys:

  - **BackgroundProcessingLevelInBytes** – eilės dydis, kad būtų pradėta apdoroti fone.

  - **CurrentQueueSize** – įvykių nULS eilėje skaičius.

  - **CurrentQueueSizeInBytes** – nULS eilės dydis baitais.

  - **ReachedTimestamp** – apdorojimo fone pradžios laikas.

### <a name="officetelemetryrulesresultuploadlatencyrule"></a>Office.Telemetry.RulesResultUploadLatencyRule

Taisyklės rezultatų turinio nusiuntimo kas valandą vidutinė, minimali ir maksimali gaištis

Renkami šių laukų duomenys:

  - **AverageLatency** – vidutinė nusiuntimo gaištis.

  - **CollectionTime** – laikas, kada surinkti duomenys vykdant taisyklės nusiuntimą.

  - **LatencyGE201LE400** – nusiuntimų, kurių gaištis didesnė nei 201 ms arba jai lygi ir mažesnė nei 400 ms arba jai lygi, skaičius

  - **LatencyGE3001** – nusiuntimų, kurių gaištis didesnė nei 3001 ms arba jai lygi, skaičius.

  - **LatencyGE401LE600** - nusiuntimų, kurių gaištis didesnė nei 401 ms arba jai lygi ir mažesnė nei 600 ms arba jai lygi, skaičius.

  - **LatencyGE601LE800** – nusiuntimų, kurių gaištis didesnė nei 601 ms arba jai lygi ir mažesnė nei 800 ms arba jai lygi, skaičius.

  - **LatencyLE200** – nusiuntimų, kurių gaištis mažesnė nei 200 milisekundžių, skaičius.

  - **MaxLatency** – didžiausia pastebėta gaištis.

  - **MinLatency** – mažiausia pastebėta gaištis.

### <a name="officetelemetrysamplingpolicy"></a>Office.Telemetry.SamplingPolicy

Kliento atrankos būsena, reikalinga siekiant tiksliai interpretuoti kitą metriką.

Renkami šių laukų duomenys:

  - **MeasuresEnabled** – ar šiame seanse įgalinti vertinimai?

  - **SamplingClientIdValue** – šio kliento atrankos reikšmė

  - **SamplingKey** – šio kliento atrankos raktas

  - **SamplingMethod** – šio kliento atrankos metodas

### <a name="officetelemetrysamplingpolicyeventtrigger"></a>Office.Telemetry.SamplingPolicyEventTrigger

Kliento atrankos būsena, reikalinga siekiant tiksliai interpretuoti kitą metriką.

Renkami šių laukų duomenys:

  - **MeasuresEnabled** – ar šiame seanse įgalinti vertinimai?

  - **SamplingKey** – šio kliento atrankos raktas

  - **SamplingMethod** – šio kliento atrankos metodas

### <a name="officetelemetrysessiontelemetryruleschanged"></a>Office.Telemetry.SessionTelemetryRulesChanged

Praneša, kad pasikeitė telemetrijos taisyklių rinkinys

Renkami šių laukų duomenys:

  - **ChangedRuleId** – telemetrijos taisyklės, kuri pakeista vykdant dabartinį naujinimą, ID

  - **ChangedRuleVersion** – telemetrijos taisyklės, kuri pakeista vykdant dabartinį naujinimą, versija

  - **OperationType** – operacijos žymės įtraukimas arba pašalinimas

### <a name="officetelemetrysessiontelemetryrulescount"></a>Office.Telemetry.SessionTelemetryRulesCount

Praneša įkeltų telemetrijos taisyklių skaičių

Renkami šių laukų duomenys:

  - **CountOfLoadedRules** – kiek telemetrijos taisyklių įkelta

  - **HadRuleFileAtBoot** – ar per programos įkrovą buvo telemetrijos taisyklių failas

### <a name="officetelemetrysessiontelemetryrulesinitialstate"></a>Office.Telemetry.SessionTelemetryRulesInitialState

Praneša, kokios telemetrijos taisyklės buvo įkeltos seanso pradžioje

Renkami šių laukų duomenys:

  - **HadRuleFileAtBoot** – ar per programos įkrovą buvo telemetrijos taisyklių failas

  - **LoadedRulesCount** – kiek telemetrijos taisyklių įkelta

  - **LoadedRulesList** – įkeltų telemetrijos taisyklių sąrašas

### <a name="officetelemetrysystemhealthmetadatanetworkcost"></a>Office.Telemetry.SystemHealthMetadataNetworkCost

Tinklo sąnaudos nurodo, ar galime gauti duomenis, ar ne.

Renkami šių laukų duomenys:

  - **NetworkCost** – naujo apskaičiuotų duomenų arba ne apskaičiuotų duomenų tinklo sąnaudos

  - **OldNetworkCost** – ankstesnio apskaičiuotų duomenų arba ne apskaičiuotų duomenų tinklo sąnaudos

  - **Tag** – šaltinio kodo žymė, kuri aptiko keitimą

### <a name="officetelemetrysystemhealthmetadatanetworkcostchange"></a>Office.Telemetry.SystemHealthMetadataNetworkCostChange

Tinklo sąnaudos nurodo, ar galime gauti duomenis, ar ne.

Renkami šių laukų duomenys:

  - **NewNetworkCost** – naujo apskaičiuotų duomenų arba ne apskaičiuotų duomenų tinklo sąnaudos

  - **OldNetworkCost** – ankstesnio apskaičiuotų duomenų arba ne apskaičiuotų duomenų tinklo sąnaudos

  - **Tag** – šaltinio kodo žymė, kuri aptiko keitimą

### <a name="officetelemetrytelemetryactivityaggregationwindowstatistics"></a>Office.Telemetry.TelemetryActivityAggregationWindowStatistics

Praneša agreguotų veiklos grupių ir egzempliorių kiekvienoje nusiunčiamoje veikloje skaičių.

Renkami šių laukų duomenys:

  - **GroupCount** – duomenis siunčiančių agreguotų veiklų skaičius.

  - **InstancesToSend** – duomenis siunčiančių agreguotų veiklų egzempliorių skaičius.

### <a name="officetelemetrytelemetryulsqueueusage"></a>Office.Telemetry.TelemetryUlsQueueUsage

Telemetrijos sveikatos klaidų pranešimas. Reikia siekiant patikrinti kitus duomenis (įskaitant NSD).

Renkami šių laukų duomenys:

  - **AverageEventCount** – vidutinis įvykių skaičius eilėje

  - **AverageQueueCB** – vidutinis atminties dydis eilėje

  - **PeakEventCount** – eilės didžiausias įvykių skaičius

  - **PeakQueueCB** – eilės didžiausias atminties dydis

  - **QueueDisableRuleLimit** – riba, kurią pasiekus telemetrijos taisyklės išjungiamos

### <a name="officetelemetryulsqueuetopthrottlingtags"></a>Office.Telemetry.UlsQueueTopThrottlingTags

Praneša, kokios žymės labiausiai prisidėjo prie išjungiamos ULS eilės.

Renkami šių laukų duomenys:

  - **Tag0 –** žymė, kuri sunaudojo daugiausia eilės

  - **Tag0Percent –** 0 žymės sunaudotos eilės procentinė išraiška

  - **Tag1 –** žymė, kuri sunaudojo antrąjį pagal dydį eilės kiekį

  - **Tag10 –** žymė, kuri sunaudojo 11-ąjį pagal dydį eilės kiekį

  - **Tag10Percent –** 10 žymės sunaudotos eilės procentinė išraiška

  - **Tag11 –** žymė, kuri sunaudojo 12-ąjį pagal dydį eilės kiekį

  - **Tag11Percent –** 11 žymės sunaudotos eilės procentinė išraiška

  - **Tag12 –** žymė, kuri sunaudojo 13-ąjį pagal dydį eilės kiekį

  - **Tag12Percent –** 12 žymės sunaudotos eilės procentinė išraiška

  - **Tag13 –** žymė, kuri sunaudojo 14-ąjį pagal dydį eilės kiekį

  - **Tag13Percent –** 13 žymės sunaudotos eilės procentinė išraiška

  - **Tag14 –** žymė, kuri sunaudojo 15-ąjį pagal dydį eilės kiekį

  - **Tag14Percent –** 14 žymės sunaudotos eilės procentinė išraiška

  - **Tag1Percent –** 1 žymės sunaudotos eilės procentinė išraiška

  - **Tag2 –** žymė, kuri sunaudojo trečiąjį pagal dydį eilės kiekį

  - **Tag2Percent –** 2 žymės sunaudotos eilės procentinė išraiška

  - **Tag3 –** žymė, kuri sunaudojo ketvirtąjį pagal dydį eilės kiekį

  - **Tag3Percent –** 3 žymės sunaudotos eilės procentinė išraiška

  - **Tag4 –** žymė, kuri sunaudojo penktąjį pagal dydį eilės kiekį

  - **Tag4Percent –** 4 žymės sunaudotos eilės procentinė išraiška

  - **Tag5 –** žymė, kuri sunaudojo šeštąjį pagal dydį eilės kiekį

  - **Tag5Percent –** 5 žymės sunaudotos eilės procentinė išraiška

  - **Tag6 –** žymė, kuri sunaudojo septintąjį pagal dydį eilės kiekį

  - **Tag6Percent –** 6 žymės sunaudotos eilės procentinė išraiška

  - **Tag7 –** žymė, kuri sunaudojo aštuntąjį pagal dydį eilės kiekį

  - **Tag7Percent –** 7 žymės sunaudotos eilės procentinė išraiška

  - **Tag8 –** žymė, kuri sunaudojo devintąjį pagal dydį eilės kiekį

  - **Tag8Percent –** 8 žymės sunaudotos eilės procentinė išraiška

  - **Tag9 –** žymė, kuri sunaudojo dešimtąjį pagal dydį eilės kiekį

  - **Tag9Percent –** 9 žymės sunaudotos eilės procentinė išraiška

### <a name="officetelemetryvolumetrackingdata"></a>Office.Telemetry.VolumeTrackingData

Telemetrjos įvykių kiekio stebėjimo metrika

Renkami šių laukų duomenys:

  - **EventThreshold** – didžiausias vieno įvykio egzempliorių, kuriuos galima išsiųsti laikotarpiu, skaičius.

  - **HighestEventCount** – didžiausias vieno įvykio egzempliorių, išsiųstų šiuo laikotarpiu, skaičius.

  - **HighestEventName** – įvykio, kurio egzempliorių skaičius šiuo laikotarpiu didžiausias, skaičius.

  - **TimeWindowInSeconds** – laikotarpio trukmė sekundėmis.

  - **TotalEvents** – bendras įvykių, išsiųstų laikotarpiu, skaičius.

  - **UniqueEvents** – unikalių įvykių, išsiųstų laikotarpiu, skaičius.

### <a name="officetelemetrywritepayloadstodisk"></a>Office.Telemetry.WritePayloadsToDisk

Tikrina, ar tam tikros senstelėjusio srauto dalys veikia platformose, kuriose jis dar naudojamas.

Renkami šių laukų duomenys:

  - **DetachedDuration** – atjungties trukmė mikrosekundėmis
