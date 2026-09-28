# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Git on minulle vielä todella uutta, olen käyttänyt sitä vasta yhdellä tai kahdella kurssilla. Ennen näitä opintoja, en ole käyttänyt sitä lainkaan. Komentokehote ei ole minulle täysin vieras, mutta erilaiset toiminnot siellä ovat.

Johtuen siitä, että melkein kaikki on uutta, jouduin hakemaan paljon tietoa, jotta sain tehtyä tehtävät. Tietoa hakiessa toki oppii. Vaikeaa oli se, etten tiennyt, teenkö asiat oikein vai en. Vaikka katsoin lähes joka välissä git statusta, oli tekeminen epävarmaa.

Sanoisin kuitenkin oppineeni Git perustoimintoja.Jos en heti ymmärtänyt, mitä jossakin tehtävän osassa kuului tehdä, tiedonhaulla pääsin jyvälle. Komennot, kuten git status, git add ja git commit olivat minulle jo ennestään tuttuja, mutta tehtävien edetessä opin paremmin hahmottamaan, mitä kukin toiminto tekee ja missä kohtaa tekemäni muutokset tallentuvat.

Repositorion kanssa työskentely oli sellaista, jota olen tehnyt todella vähän. Repositorion tilannetta opin tarkistamaan git status komennon kanssa ja opin näkemään, mitä oli vielä tallentamatta.

Kohtasin tehtävien aikana myös paljon täysin minulle uutta, kuten tiedostojen lisääminen, nimeäminen ja poistaminen Gitin kautta. Gitissä tehdään siis paljon muutakin kuin vain talletetaan valmista työtä. Myös haarat olivat minulle uudempi asia. Eri haarojen välillä liikkuminen avasi niitä kuitenkin minulle työn edetessä.

Virheilmoitukset sekä ohjaavat tekstit auttoivat paljon työskentelyssä. Uskon, että joudun vielä käyttämään materiaalia ja hakemaan tietoa jonkun aikaa ennen kuin eri komennot alkavat hiljalleen jäämään mieleen. Pystyn kuitenkin jo tekemään erilaisia asioita joko esimerkiksi VS Codessa tai komentorivillä tai GitHubissa.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| mkdir git-harjoitukset | Luo uuden kansion |
| cd .. | Siirtyy ylempään kansioon |
| cd git-harjoitukset| Avaa kansion |
| git status| Näyttää repositorion tilanteen |
| dir| Näyttää kansion sisällön |
| git add | Lisää tiedostot odottamaan seuraavaa commitia |
| git commit -m | Tallettaa muutokset commitiksi |
| git add hello.html | Lisää nimetyn tiedoston commitia varten |
| git mv| Muuttaa tiedoston nimen |
| git rm| Poistaa tiedoston |
| git log | Näyttää repositorion commitit |
| git tag | Lisää tagin / näyttää tagit |
| echo > | Lisää tiedoston |
| notepad text2.txt | Avaa kyseisen tiedoston notepadissa |
| code .| Avaa repositorion VS Codessa |
| git reset text2.txt / git reset | Poistaa tiedoston / kaikki tiedostot seuraavalta commitilta |
| git restore | Palauttaa takaisin talletukseen |
| git revert | Peruu aiemman commitin muutokset ja tekee uuden commitin |
| git reset --hard | Palauttaa kaikki tracked tilassa olevat edelliseen commit tilaan |
| git branch | Näyttää haarat |
| git switch haaran nimi | Vaihtaa haaraa |
| git switch -c haaran nimi | Luo uuden haaran ja siirtyy siihen |
| git merge --no-ff haara | Yhdistää haarat |