+++
title="Aikavälikertauksen rooli opiskelussa"
date=2025-08-07
tags=['Spaced repetition', 'Learning']
draft=false
+++

Tämä on [opiskeluaiheisen blogisarjan](/blog/tehokas-ja-kestävä-opiskelu) neljäs osa.

Opiskelu koostuu karkeasti kahdesta tasosta: intuitiivisen ymmärryksen ja hahmottamisen saavuttamisesta ja yksittäisten faktojen pänttäämisestä.
Esimerkkinä kielioppi & sanasto.
Tai historian syy-seuraussuhteet ja henkilöiden nimet.

Faktojen pänttäämiseen toimii parhaiten aktiivinen oppiminen (*Active Recall*), jossa muistia haastetaan vastaus piilotettuna.
Uusia asioita on oppimisvaiheessa kerrattava useammin, ja jo kertaalleen opittuja entistä harvemmin.
Tällaisen aikavälikertauksen ja opiskelun jaksottamisen merkitys havaittiin jo [vuonna 1885](https://en.wikipedia.org/wiki/Hermann_Ebbinghaus).

Paperilappujen muodossa kysymys-vastausparien hallinta ja aikataulutus kasvaisi ennen pitkää mahdottomaksi työvuoreksi, ja ongelmaan onkin löydetty toimiva teknologinen ratkaisu.

Aikavälikertausta tukevista ohjelmistoista ylivoimaisesti suosituin on avoimeen lähdekoodiin perustuva ja ilmainen Anki-sovellus.
[Selaimen](https://ankiweb.net/) ja tietokonesovelluksen lisäksi Anki on käytössä kännykkäsovelluksena ([AnkiDroid](https://play.google.com/store/apps/details?id=com.ichi2.anki)), mikä mahdollistaa opiskelun vaikkapa vessanpytyllä istuen, mikä on yksi harvoista kännyköiden pedagogisista hyödyistä.
Etenkin [lääketieteen alalla](https://old.reddit.com/r/medicalschoolanki/) Ankin käyttö on yleistä.

Uusia kortteja luodessa on hyvä pitää mielessä muutamia muotoilusääntöjä:

1) Älä pänttää asioita, joiden sisältöä tai roolia et ymmärrä.
2) Pidä kysymykset yksinkertaisina ja lyhyinä.
3) Luo omia muistisääntöjä vastauskortteihin.
4) Älä opettele listoja.
5) Yhdistä liian lähekkäiset kortit, ja korosta niiden erot (esim. Indonesian ja Monacon liput).
6) Sanastoja varten generoi automaattisesti molemminsuuntaiset kortit.

Irrallisista kysymys-vastauspareista koostuvan pakan voi luoda helposti esimerkiksi taulukkolaskentaohjelman kautta (`import .csv`), ja [valmiita jaettuja pakkoja](https://ankiweb.net/shared/decks) on myös pilvin pimein.

Omien korttipakkojen luomiseen ja hallintaan [kakkosaivot](/blog/kakkosaivojen-rakentaminen) vaikuttavat parhaimmalta vaihtoehdolta.
Kortit voi integroida muuhun opiskeltuun tietoon ja omaan "tietoavaruuteen".
Korttien muokkaaminen jälkikäteen on myös triviaalia, eikä korttien aikataulutusta menetä.
Tämän mahdollistava laajennus löytyy nimellä [Obsidian_to_Anki](https://github.com/ObsidianToAnki/), joka tukee muokkattavaa syntaksia:

```
TARGET DECK: Suomi-Englanti esimerkki
Kissa::Cat (Tämä syntaksi generoi molemminsuuntaiset kortit)

Q: Mitä tämä syntaksi generoi?
A: Yksinkertaisen kysymys-vastausparin (Q-A).
```

--> `Obsidian Command: 'Obsidian_to_Anki: Scan Vault'`
