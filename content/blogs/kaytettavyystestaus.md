---
categories:
- blog
date: '2023-10-31'
title: Digitaalisen palvelun käytettävyytestaus
---

# Mitä, miksi ja miten?

Käytettävyystestaus on olennainen osa palvelun suunnittelua sekä oiva keino löytää palvelun, kuten verkkosivun tai mobiilisovelluksen, käytettävyyden kipukohdat ja lisätä asiakasymmärrystä. Käytettävyystestauksia voidaan toteuttaa koko palvelulle, jollekin palvelun osalle tai vaikka vain tietylle ominaisuudelle. On hyvä kuitenkin pitää mielessä, että mitä tarkemmin testaus kohdennetaan, sitä parempia tuloksia myös saadaan.

Käyttäjätestaus vai käytettävyystestaus? Kyseisiä termejä käytetään usein tarkoittamaan samaa asiaa. Näiden välillä kuitenkin on ero: käyttäjätestaus on sateenvarjokäsite, jolla viitataan erilaisiin menetelmiin joilla voidaan testata esimerkiksi mobiilisovelluksen käyttökokemusta. Käytettävyystesti taas on yksi testausmenetelmä muiden joukossa. Muita käyttäjätestauksen menetelmiä ovat mm. a/b testaus, fokusryhmähaastattelu, katseenseuranta (eyetracking), kenttätutkimus (field study) ja card sorting.

## **Milloin käyttäjätestauksia kannattaa tehdä?**

**Juuri nyt!**
: Tee käyttäjätestausta oli palvelusi kehitystyö missä vaiheessa tahansa. 

**Kaikissa vaiheissa!**
: Käyttäjätestauksista saat hyötyä kaikissa palvelun kehitysvaiheissa.

**Aikaisin!**
: Käyttäjätestauksista saatava hyöty on suurimmillaan mitä aiemmassa vaiheessa palvelun kehitystyötä niitä tehdään.

## Miten digitaalista palvelua kannattaa testata?

Erilaisten käyttäjätestausmenetelmien valikoima on suuri ja juuri omiin tarpeisiin soveltuvan metodin valinta voi olla vaikeaa. Oikeanlainen metodi riippuu esim. siitä missä vaiheessa palvelun kehitys on. Palvelun ollessa vasta idean asteella on esim. kenttätutkimus hyvä valinta. Kun palvelusta on olemassa jo jotain konkreettista (esim. prototyyppi) käytettävyystestaus ja card sorting ovat mahdollisia valintoja käyttäjätestausmenetelmäksi. Palvelun valmistuttua puolestaan A/B testaus on hyvä tapa mitata palvelun toimintaa. Esittelen seuraavaksi lyhyesti muutamia yleisimpiä käyttäjätestausmenetelmiä, ja kirjoituksen lopuksi kerron tarkemmin käytettävyystestauksesta yleisesti ja siitä miten me Agendalla käytettävyystestauksia toteutamme.

**A/B testauksen** avulla voidaan testata kahta erilaista versiota palvelusta, jotta nähdään kumpi versio toimii paremmin kohderyhmässä. Lyhyesti selitettynä A/B testaus toteutetaan julkaisemalla esimerkiksi verkkopalvelun etusivusta 2 eri versiota (versio A ja versio B) ja ohjaamalla puolet käyttäjistä versioon A ja toinen puoli versioon B. Kun testiä on jatkettu riittävän pitkään, voidaan tuloksista selvittää kumpi versioista toimi valittuun mittariin verrattuna paremmin ja ottaa tämä versio käyttöön kaikille käyttäjille.

**Fokusryhmähaastattelut** ovat menetelmä, jossa ryhmä palvelun kohderyhmään kuuluvia käyttäjiä keskustelee fasilitaattorin johdolla etukäteen määritellyistä aiheista liittyen testattavaan palveluun. Fokusryhmähaastatteluja ei ole suositeltavaa käyttää selvittämään suoranaisia käytettävyyteen tai palvelun käyttöön liittyviä asioita vaan metodi on parhaimmillaan kun pyritään selvittämään, mitä käyttäjät haluavat palvelulta.

**Katseenseuranta** vaatii oman erityisen laitteiston, joka seuraa mihin käyttäjä katsoo, kun hän käyttää testattavaa palvelua esim. Verkkosivua. Katseenseurannan avulla voidaan saada selville mm. huomaavatko käyttäjät tiettyjä käyttöliittymän osioita ollenkaan ja mitkä käyttöliittymän osiot vievät käyttäjien huomion.

**Kenttätutkimus (field study)** eroaa muista käyttäjä tutkimusmenetelmissä siinä, että tutkimus suoritetaan sellaisessa ympäristössä ja tilanteessa, jossa käyttäjän oikeasti käyttäisivät testattavaa palvelua. Kenttätutkimuksia voidaan toteuttaa käyttäen monia erilaisia tutkimusmetodeja. Myös tutkijan rooli voi vaihdella suuresti erilaisten kenttätutkimusten välillä.

**Card sorting** on hyvin yksinkertainen, mutta tehokas menetelmä, jonka avulla voidaan joko luoda tai parannella testattavan palvelun [informaatioarkkitehtuuria](https://web.archive.org/web/20200806195047/https://www.nngroup.com/articles/ia-vs-navigation/). Menetelmässä käyttäjät järjestävät erilaiset aiheet heidän mielestään loogisiin ryhmiin ja antavat näille ryhmille nimet.

## Käytettävyystestauksesta yleisesti

Käytettävyystestauksessa palvelun prototyyppi (tai valmis palvelu) annetaan oikeille käyttäjille testattavaksi ohjatussa tilanteessa, jonka jälkeen asiantuntija analysoi palvelun käytössä esiintyneet ongelmat. Käytettävyystestaus on yksi suuritöisimmistä käyttäjätestausmenetelmistä, mutta sen avulla saadaan myös parhaiten palvelun käyttäjien ääni kuuluviin jo palvelun suunnittelu- ja kehitysvaiheessa. Olisi ehkä helppo kuvitella että mahdollisimman suuri testaajien määrä tuottaisi parhaita tuloksia, mutta jo 5 testaajaan avulla löydetään 85% käytettävyysongelmista.

Käytettävyystestauksesta saadaan irti suurin hyöty teettämällä testauksia useita kertoja suunnittelu- ja kehitysvaiheessa. Näin saadaan jo aikaisessakin vaiheessa tärkeää palautetta palvelun käyttökokemuksesta. Palautteen avulla suunnittelua ja kehitystä voidaan viedä oikeaan suuntaan ja vältytään aikaavieviltä ja kalliilta korjaus- ja muutostoimenpiteiltä myöhemmissä vaiheissa. Useamman testin toteuttaminen yhden projektin aikana on tietenkin optimaalinen tilanne, joka harvoin toteutuu oikeassa elämässä. Vaikka resurssit eivät riittäisikään toteuttamaan useita testauksia, jo yhdelläkin oikein ajoitetulla testillä voidaan löytää suurin osa palvelun kipupisteistä. Näin vältytään suurilta korjaus- ja muutostoimenpiteiltä palvelun julkaisun jälkeen.

## Esimerkki Käytettävyystestaus toteuttamisesta

**Testaussuunnitelma**

Käytettävyystestausprosessi alkaa testaussuunnitelman luomisella. Testaussuunnitelmassa määritellään mm. testataanko jokin tietty palvelun ominaisuus vai yleisesti koko palvelua, mitä tavoitteita testaukselle on asetettu, mitkä ovat palvelun keskeisimpiä toimintoja ja mitkä ovat suurimmat tiedossa olevat riskit, haasteet ja ongelmat. Näiden pohjalta luodaan sopivat tehtävät ja haastattelukysymykset, joiden avulla voidaan testata määriteltyjä asioita.

**Rekrytointi**

Käytettävyystestausprosessi jatkuu rekrytoimalla oikeaan kohderyhmään kuuluvat henkilöt testaukseen. Mikäli palvelua varten on olemassa valmiiksi luotuja asiakaspersoonia, näitä voidaan hyvin käyttää apuna oikean kohderyhmän valinnassa.

**Testaus**

Ennen varsinaisia käyttäjien kanssa toteutettuja testejä, on syytä “koeajaa” vielä suunniteltu testaustilanne, jotta voidaan varmistua tehtävien toteuttamiskelpoisuudesta ja haastattelukysymysten sopivuudesta tavoitteisiin. Tämä vaihe on erittäin tärkeää, koska usein tässä vaiheessa testaussuunnitelmaan ja etenkin suunniteltuihin tehtäviin tulee tehdä vielä muutoksia ja ilman tätä “koeajoa” mahdolliset ongelmat ja puutteet tehtävissä huomattaisiin vasta ensimmäisen varsinaisen testauksen aikana. Testaussuunnitelman hiomisen jälkeen on aika suorittaa testit oikeiden käyttäjien kanssa. Testaustilanne on syytä nauhoittaa (käyttäjän suostumuksella), jotta voidaan tarkemmin analysoida miten käyttäjä missäkin vaiheessa tehtäviä käyttäytyi ja näin löytää erilaiset kipukohdat palvelussa. Testauksen lopuksi voidaan tehdä vielä lyhyt debrief käyttäjän kanssa jossa käydään läpi mm. palvelun käyttöä ja siinä esiintyneitä ongelmia ja kehitysehdotuksia.

**Analysointi ja raportointi**

Kun testaukset on hoidettu aloitetaan tulosten analysointi, jossa mm. määritellään mitkä käyttäjien kokemat ongelmat olivat yleisimpiä ja kriittisimpiä palvelun käytössä. Analyysin perusteella kijroitetaan testausraportti joka sisältää havaitut ongelmat ja suositukset ongelmien korjaamiseksi.

- Kirjoitettu: 8.8.2019
- Tehty alunperin Agenda Digitalin sivuille. Kirjoitusta muokattu 29.10.2025.
