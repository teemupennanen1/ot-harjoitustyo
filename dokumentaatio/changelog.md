## Viikko 3

- Käyttäjä voi laskea yksinkertaisia yhteenlaskutoimituksia

## Viikko 4

- Käyttäjä voi laskea myös vähennys-, kerto- ja jakolaskuja (Ei tosin toimi vielä)
- Jos kerto- tai jakolaskun tulos on kokonaisluku, palautetaan kokonaisluku liukuluvun sijaan. Laskin ei tosin vielä osaa käsitellä liukulukuja.

## Viikko 5

- Peruslaskutoimitukset toimivat
- Tulos on aina liukuluku
- Laskimen sammutustoiminto käynnistetään antamalla tyhjä merkkijono
- Tämä tulostaa "Suljetaanko K/e"
- Laskin sammuu komennoilla K ja k
- Laskimen käyttöä voidaan jatkaa komennoilla E ja e
- Jos kaava ei pääty "="-merkkiin, tulostetaan "Muista = merkki loppun"

## Viikko 6

- Pakkausrakennetta järkevöitetty
- Laskin käsittelee lukuja likulukuina kokonaislukujen sijaan, joten desimaalilukujen laskenta onnistuu
- komennolla poetry run invoke html-report tehdään coverage testi, luodaa raportt ja avataan html raportti firefoxilla
- Ensimmäinen jäsenkin voi olla negatiivinen
- Ohjelma osaa tulkita useita peräkkäisiä "+" ja "-" merkkejä, ja antaa oikean tuloksen "-" merkkien parillisuuden perusteella

## Viikko 7
- Komennolla Ohjeet ohjelma tulostaa ohjeet erilaisille toiminnoille, joita ohjelmaan on rakennettu
- Ohjelma pitää muistissa edellisen laskutoimituksen tuloksen. Tätä voidaan käyttää seuraavassa laskutoimituksella kirjoittamalla kenttään vakion tilalle ans
- Ohjelma tallentaa repositorioon vanhat laskutoimitukset ja niihin liittyvän kellonajan ja päivämäärän.
  