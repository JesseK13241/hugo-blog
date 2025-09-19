+++
title="Kohti pienempää internettiä"
date=2025-09-19
lastmod=2025-09-19
tags=['Small web', 'Blogging', 'Privacy']
draft=false
+++



Internet on muutakin kuin kourallinen digijättien kaupallisia alustoja ja appeja.

Varhaisen internetin vahvuuksia käsittävä termi *small web* on osa hiljaista kapinaa modernin internetin haittapuolia vastaan.

## Moderni internet

Mainosteknologian kehittyminen kutsui mainostajat, markkinoijat ja muut kaupalliset julkaisijat ryminällä sisään bittiavaruuteen.

Lyhytnäköinen voitontavoittelu toi kuitenkin ajan myötä mukanaan inhottavia lieveilmiöitä.

### Valvontakapitalismi

Ilmainen sosiaalinen media (Facebook) valloitti internetin lyhyessä ajassa. 
Todellista hintaa maksetaan vielä pitkään takaisin.

> Valvontakapitalismi (Surveillance Capitalism) on käsite, joka kuvaa voitontavoitteluun tähtäävää henkilökohtaisen datan hyödykkeistämistä. Koska henkilötietoja voidaan kaupallistaa, niistä on tullut yksi arvokkaimmista resursseista. Termi sai alkunsa siitä, kun mainosalan yritykset tarttuivat tilaisuuteen käyttää henkilötietoja markkinoinnin entistä yksilöidympään kohdentamiseen.
> - https://fi.wikipedia.org/wiki/Valvontakapitalismi

Kulutuksen ohjaamisen lisäksi mainosalgoritmeja käytetään esimerkiksi poliittiseen vaikuttamiseen.
Tästä tähän mennessä kuuluisin tapaus on [Cambridge Analytica](https://en.wikipedia.org/wiki/Facebook%E2%80%93Cambridge_Analytica_data_scandal), jossa 87 miljoonan ihmisen tietoja ja nettikäyttäytymistä käytettiin mikrokohdennettuun vaikuttamiseen.
Demokraattisten periaatteiden murentamisen lisäksi mainoskoneisto vaarantaa ihmisten yksityisyyden jatkuvien tietovuotojen muodossa (Exactis, Oracle's BlueKai, ...).

### Huomiotalous

Mainosten kohdentamisen lisäksi alustat alkoivat ikuisen kasvun perässä maksimoimaan seuraavaksi käyttäjien huomion ja alustalla vietettävän ajan.

Kun psykoteknologisille algoritmeille annetaan nämä yksinkertaiset tavoitteet, löytää se nopeasti optimit parametrit suosittelemalla ihmisille vahvoja tunteita herättävää sisältöä.
Ihmisen luontainen kielteisyysvinouma suosii negatiivista sisältöä, ja raivosoppa on valmis.

Tämä huomaamaton ja hidas käyttäjien mädätys ajaa osaltaan yhteiskunnallista kahtiajakoa ja yleistä (mielen)terveydellistä rappeamaa.

### Kehitys

Alustat ja palvelut eivät tietenkään toimi näin heti syntyessään, sillä käyttäjävihamielinen maine ei ole toimiva kasvustrategia.
Termi [enshittification](https://en.wikipedia.org/wiki/Enshittification) (paskiintuminen) kuvaa sitä prosessia, jossa yleishyödyllinen alusta muovautuu pikkuhiljaa käyttäjämassan saavuttamisen jälkeen nettohaitalliseksi hirviöksi jatkuvaa taloudellista voittoa tavoitellessaan. 

Sosiaalisen median alustojen vaihtoa on osaltaan hankaloittanut verkostovaikutus (Network Effect), sillä sovellusten välistä kommunikaatiota ei yleensä olla tuettu millään tapaa.
Tähän epäkohtaan on esimerkiksi EU puuttunut regulaation avulla (DMA, Messaging Interoperability), mutta asia on loppupeleissä kollektiivinen valintakysymys.

Toinen aita vihreämmän ruohon edessä on riittämätön datasiirrettävyys (data portability).
Jos sovellus tallentaa käyttäjän datan epästandardissa tai patentoidussa formaatissa, on se käyttökelvoton muille vaihtoehdoille. Myös tähän ovat regulaatiot onnistuneesti purreet (GPDR, DMA, Data Act).

Perusongelma haitallisten alustojen suosiossa on [digitaitojen](/blog/tietokoneen-peruskäyttö) 🚧  puute, vaikkakin kynnys on yleistä mielikuvaa paljon matalammalla.
Muita merkittäviä esteitä ovat huomio, ajanpuute ja energia, joiden imeminen on modernien internetalustojen kulmakivi.
### Hyvät puolet

Ennen konkreettisia korjausohjeita haluan mainita [positiivisuuden tärkeyden](/blog/optimismin-merkitys) 🚧  vuoksi muutaman modernin internetin hyvän puolet:

- Internet on nykyään merkittävästi laajempi sisällön ja vaihtoehtojen suhteen.
- Tietoturva on parantunut mm. selainstandardien myötä.
- Suurilta osin (edelleen) ilmainen, mikä on nettimainonnan yksi harvoista hyvistä puolista.

## Korjausohjeet

Korjausliike kohti pienempää internettiä koostuu ihmisistä, jotka tekevät osansa.

Voit heti parantaa omaa autonomiaa ja yksityisyyttä [tukkimalla internettiä tuhoavan mainostykin](https://www.youtube.com/watch?v=_ErjCOv2AYA):

- [FireFox](https://www.mozilla.org/fi/firefox/new/) tai muu selain, jossa [Manifest V2](https://blog.mozilla.org/en/firefox/firefox-manifest-v3-adblockers/) on tuettuna, jotta selain kykenee estämään mainokset ja muut vakoiluscriptit.
- [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) (toimii myös mobilessa)

[Pi-hole](https://pi-hole.net/) ja muut DNS/firewall -ratkaisut toimivat tilanteissa, joissa laitteeseen ei ole suoraa/helppoa kontrollia (esim. älytelkkarit).

Oman yksityisyyden suojaaminen on pitkä ja jatkuva prosessi, eikä sitä tarvitse tehdä kertarysäyksellä.
Etsi [vaihtoehtoja](https://en.wikipedia.org/wiki/DeGoogle) hakukoneille, sähköposteille, käyttöjärjestelmille jne.
Mieti missä menee sopiva tasapaino vaivannäön ja muiden elämänkiireiden suhteen.
[Seuraa ihmisiä](https://www.youtube.com/watch?v=u_Lxkt50xOg), jotka jo ovat tällä polulla.

Vältä sovelluksia ja alustoja, joiden sisältövirtaa et voi itse kuratoida.

> Unless we make conscious, strategic decisions about what we consume, we’ll always be at the mercy of what others want us to see.
> - https://fortelabs.com/blog/basboverview/

## Pieni internetti

Teollisen internetin vastakohtana voidaan pitää artisaanihenkistä pientä internettiä. 
Molemmille on nyky-yhteiskunnassa paikkansa. 
Pieni internetti merkitsee eri ihmisille eri asioita:
Autonomiaa, estetiikkaa, laatua, minimalismia, nopeaa latausnopeutta, persoonallisuutta, ihmislähtöisyyttä, ...
Omat blogisivustot ovat yksi osa pienen internetin käsitettä. 

Nämä blogitekstit antavat aiheeseen monipuolisen perspektiivin:
- https://neustadt.fr/essays/the-small-web/
- https://www.ssp.sh/blog/self-host-self-independence/
- https://benhoyt.com/writings/the-small-web-is-beautiful/

Pienen internetin sivuja voi löytää monella tapaa:
- https://blog.kagi.com/small-web
- https://neocities.org/browse?sort_by=views&tag=
- https://wiby.me/

Oman blogin tai nettisivun tekemiseen on lukuisia ohjeita. Matalin kynnys on todennäköisimmin tällä tutoriaalilla: https://make.yourownwebsite.org/

Omaa blogiani vastaava ohjeistus tulee aikanaan tänne: [Blogi - Miten](/blog/blogi-miten) 🚧 

