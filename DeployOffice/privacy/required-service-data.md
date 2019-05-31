---
title: Privalomieji „Office“ tarnybų duomenys
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Leidžia „Office“ administratoriams apžvelgti privalomuosius tarnybų duomenis, kurie renkami apie „Office“ prijungtąsias funkcijas.
hideEdit: true
ms.openlocfilehash: 88f8aadc098af6e167206486566e32af1767c741
ms.sourcegitcommit: 894a18676566981183dbe2d78f7466c9bb2c6354
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 04/29/2019
ms.locfileid: "33468553"
---
# <a name="required-service-data-for-office"></a>Privalomieji „Office“ tarnybų duomenys 

> [!IMPORTANT]
> Šiame straipsnyje pateikta informacija taikoma 1904 arba naujesnės versijos „Office“ kliento programinei įrangai, įdiegtai „Windows“ kompiuteryje:
> - „Office 365 ProPlus“ ir „Office 365 Business“
> - „Office 365 Personal“, „Office 365 Home“ arba kitos „Office“ versijos, kurios yra „Office 365“ prenumeratos dalis.
> - „Project“ ir „Visio“, kurios įtrauktos į kai kuriuos prenumeratos planus, pvz., planą „Project Online Professional“ arba „Visio Online“ 2 planą.

„Office“ sudaro kliento programinės įrangos programos ir prisijungus naudojamos funkcijos, kurios sukurtos, kad galėtumėte kurti, bendrauti ir bendradarbiauti efektyviau. Prisijungus naudojamų funkcijų pavyzdžiai yra „OneDrive“ verslui saugomo dokumento redagavimas su kitais arba „Word“ dokumento turinio vertimas į kitą kalbą.

Privalomieji tarnybų duomenys yra labai svarbūs, nes jie įgalina šių debesų technologija pagrįstų prijungtųjų funkcijų veikimą, leidžia jas apsaugoti ir užtikrinti, kad klientams jos veiktų, kaip numatyta. Privalomuosius tarnybų duomenis sudaro trijų tipų informacija.

- **Kliento turinys** – turinys, kurį sukuriate naudodami „Office“, pvz., „Word“ dokumente įvestas tekstas; naudojamas kartu su prisijungus naudojamomis funkcijomis.
- **Funkciniai duomenys** apima informaciją, kurios reikia, kad prisijungus naudojama funkcija galėtų atlikti užduotį, pvz., programos konfigūracijos informacija.
- **Tarnybų diagnostikos duomenys** – duomenys, kurių reikia, kad tarnyba būtų apsaugota, atnaujinta ir veiktų, kaip numatyta. Kadangi šie duomenys glaudžiai susiję su prijungtosiomis funkcijomis, jie atskirti nuo privalomųjų arba pasirinktinių diagnostikos duomenų lygių.

## <a name="example-of-required-service-data-for-a-connected-experience"></a>Prijungtosios funkcijos privalomųjų tarnybos duomenų pavyzdys

Kad geriau suprastumėte privalomuosius tarnybos duomenis, pateikiame pavyzdinį scenarijų, kuriame naudojamas „PowerPoint“ dizaino įrankis – prijungtoji funkcija, padedanti kurti pateikties skaidres. „PowerPoint“ dizaino įrankis patobulina skaidres automatiškai generuodamas dizaino idėjas, iš kurių galite rinktis. Kai keliate turinį į skaidrę, dizaino įrankis veikia fone, kad pritaikytų turinį prie profesionalių maketų.

Privalomieji tarnybos duomenys, kurie siunčiami „Microsoft“, kad ši prijungtoji funkcija veiktų, gali apimti nurodytuosius toliau.

- *Kliento turinį*, kuris yra tekstas arba vaizdai, kuriuos įtraukiate į skaidrę.
- *Funkcinius duomenis*, pvz., informaciją, kurioje skaidrėje dirbate, ir jos maketą.
- *Paslaugos diagnostikos duomenis*, pvz., įvykius, kurie pasako mums, ar dizaino idėja buvo tinkamai pritaikyta skaidrėje ir ar paslauga buvo tinkamai iškviesta.

## <a name="view-and-manage-required-service-data"></a>Privalomųjų tarnybos duomenų peržiūra ir valdymas

Tarnybų diagnostikos duomenis galite matyti naudodami diagnostikos duomenų peržiūros programą. Daugiau informacijos žr. [Tarnybų diagnostikos duomenų įvykių pavyzdžiai](#examples-of-events-for-service-diagnostic-data).

Suteikiame jums galimybę pasirinkti, kokių tipų prijungtąsias funkcijas norite naudoti „Office“ programose. Nuo to priklauso, kokie privalomieji tarnybų duomenys mums siunčiami. Pavyzdžiui, „PowerPoint“ dizaino įrankis yra viena iš prijungtųjų funkcijų, kurios analizuoja jūsų turinį. Jei pasirinksite išjungti prijungtąją funkciją, kuri analizuoja turinį, mums nebus siunčiami jokie privalomieji „PowerPoint“ dizaino įrankio tarnybos duomenys, nes „PowerPoint“ dizaino įrankio nebus galima naudoti.

Taip pat renkami ir įmonei „Microsoft“ siunčiami pagrindinių „Office“ tarnybų, pvz., licencijavimo tarnybos, kuri patvirtina, kad turite tinkamą licenciją naudoti „Office“, privalomieji tarnybų duomenys. Šie pagrindinių tarnybų duomenys siunčiami neatsižvelgiant į kitus su privatumu susijusius parametrus, kuriuos sukonfigūravote.

Jei reikia daugiau informacijos, žr.:

- [„Office“ prisijungus naudojamos funkcijos](connected-experiences.md)
- [Pagrindinės „Office“ tarnybos](essential-services.md)
- [Diagnostikos duomenų peržiūros programos naudojimas su „Office“](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

Jei esate organizacijos administratorius, galbūt jus domina šios temos:

- [„Office 365 ProPlus“ privatumo valdiklių apžvalga](overview-privacy-controls.md)
- [„Office 365 ProPlus“ privatumo valdiklių valdymas naudojant strategijos parametrus](manage-privacy-controls.md)

## <a name="examples-of-events-for-service-diagnostic-data"></a>Tarnybų diagnostikos duomenų įvykių pavyzdžiai

Tarnybų diagnostikos duomenys rodomi diagnostikos duomenų peržiūros programoje ir yra skirstomi į tas pačias kategorijas, kurias naudoja būtinieji ir pasirinktiniai diagnostikos duomenys. Pavyzdžiui, *Produktų ir tarnybų naudojimas* ar *Produktų ir tarnybų našumas*.

Tarnybų diagnostikos duomenų įvykiai suteikia mums reikiamą informaciją apie tai, ar prisijungus naudojama funkcija veikia taip, kad tikisi klientas. Pavyzdžiui, ar tarnyba, kurią naudoja prisijungus naudojama funkcija, buvo paleista sėkmingai ir prireikus ją buvo galima pasiekti, ar naudojant tarnybą kilo klaidų ar kitų netikėtų problemų (gedimų) bei tarnybos reagavimas ir našumas.

Šioje lentelėje pateikiama keletas tarnybų diagnostikos duomenų pavyzdžių.

| **Pavadinimas**      | **Aprašas**    |
| ---------- | --------------------- |
| Office.Excel.Coauth.SaveXrr     | Įvykis, suaktyvintas programoje „Excel“ naudojant bendradarbiavimo tarnybą, kuris pateikia išsamią informaciją apie atskirus pakeitimus, kurie įrašomi į pakeitimų žurnalą. Jis vykdo gaišties stebėjimą ir nurodo „Excel“ klaidas, susijusias su bendradarbiavimu  |
| Office.Excel.Coauth.CloseWorkbook  | Įvykis, suaktyvintas programoje „Excel“ naudojant bendradarbiavimo tarnybą, kuris praneša, kai uždaroma darbaknygė. To reikia norint nustatyti, ar yra pakartotinio įkėlimo ir automatinio atnaujinimo klaidų. Šis įvykis matuoja bendradarbiavimo tarnybų veiksmų sėkmę.   |
| Office.Security.OCX.NonTrustedEncounter    | „Office“ programose (įskaitant „Word“, „Excel“, „Outlook“, „PowerPoint“ ir „Visio“) suaktyvinamas įvykis, kai vartotojas atidaro nepatikimą dokumentą su „ActiveX“ valdikliu. Jis naudojamas siekiant plačiai įvertinti „ActiveX“ valdiklių, įdėtų „Office“ dokumentuose, naudojimą ir imtis rizikos sumažinimo veiksmų kilus saugos incidentui.  |
| Office.Security.UrlReputation.GetUrlReputation | „Office“ programose (įskaitant „Word“, „Excel“, „PowerPoint“, „Visio“ ir „Publisher“) suaktyvinamas įvykis, kuris seka saugiųjų saitų iškvietimus. Jis naudojamas siekiant užtikrinti, kad saugiųjų saitų tarnyba veiktų tinkamai, ir diagnozuoti kilusias problemas.  |
| Office.Voice.VoiceManager.StreamingAudio   | „Office“ programose (įskaitant „Word“, „Outlook“ ir „PowerPoint“) suaktyvinamas įvykis, kuris suteikia informacijos apie garso transliacijos sveikatą kalbos tarnybai. Jame yra informacijos apie garso srauto dydį ir visas klaidas, kurios galėjo kilti. Ši informacija naudojama stebėti tarnybos sveikatą ir diagnozuoti visas problemas, apie kurias galėjo pranešti klientai. |
