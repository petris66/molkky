# Mölkky tulostaulu

Staattinen GitHub Pages -versio iPhonelle.

## Käyttö

1. Lataa nämä tiedostot GitHub-repositorion juureen:
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `icon.svg`

2. Avaa GitHubissa:
   Settings → Pages → Deploy from a branch → main / root

3. Avaa sivu iPhonen Safarilla ja valitse:
   Jaa → Lisää Koti-valikkoon

## Puhekirjaukset

Paina kirjauskenttää, paina iPhonen näppäimistön mikrofonia ja sano esimerkiksi:

- Niina 10
- Mikko 3
- Sanna huti
- undo

## Säännöt

- Täsmälleen 50 pistettä voittaa.
- Jos menee yli 50, tulos palautuu 25 pisteeseen.
- Kolme peräkkäistä hutia pudottaa pelaajan pelistä.


## Päivitys

Tämä versio ymmärtää myös suomenkieliset numerosanat:

- Jari kaksi
- Niina kahdeksan
- Mikko kymmenen


## Tavoitepisteet

Aloitusnäkymässä voit valita voittopistemäärän. Normaali peli on 50 pistettä, mutta lyhyessä pelissä voit käyttää esimerkiksi 25, 30, 35 tai 40.


## Vuorossa olevan pelaajan esitäyttö

Kun peli alkaa, kirjauskenttään täytetään automaattisesti vuorossa olevan pelaajan nimi. Voit sanoa tai kirjoittaa pelkän tuloksen:

- kaksi
- 8
- huti

Kirjauksen jälkeen sovellus siirtyy seuraavaan aktiiviseen pelaajaan ja täyttää tämän nimen kenttään.


## Live-tulostaulu Firebase Realtime Databasella

Kirjaajan näkymä:
https://petris66.github.io/molkky/?game=vappu2026

Katsojanäkymä:
https://petris66.github.io/molkky/?game=vappu2026&view=score

Kirjaajan näkymässä näkyy katsojalinkki, jonka voi kopioida ja lähettää muille pelaajille.
