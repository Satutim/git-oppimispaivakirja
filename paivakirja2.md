# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Uuden reposition luominen githubissa on tuttua, mutta koska sitäkään en ole tehnyt usein, sain lukea ohjeista, miten se tehtiin. Sisällöltään tyhjä repositio oli kuitenkin selkeä luoda.

Haarojen luominen sekä niiden välillä vaihtaminen oli aiemmasta tehtävästä tuttua. Jouduin kuitenkin edelleen turvautumaan ohjeisiin, jotta tein askeleet oikein.

Haarojen tarkastelu ja luominen kahdessa eri paikassa oli aluksi hieman hämäävää sekä se, mitä pitää tehdä komentorivillä ja mitä githubissa ja miten toisessa tehty muutos näkyy toisessa, mutta tehtävä selkeytti sitä.

Yritin vaihtaa päiväkirja 1 päiväkirja 2, mutten ollut vielä tehnyt kaikkia tallennuksia päiväkirja 1, joten en voinut suoraan vaihtaa haaraa. Virheviesti kertoi onneksi jo valmiiksi, miten pääsin tästä etenemään.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| git remote -v | näyttää mihin etärepoon paikallinen repo on yhdistetty|
| git push | vie muutokset githubiin |
| git push -u origin new-feat | vie kokonaan uuden haaran githubiin ja yhdistää sen etärepoon |
| git fetch | hakee etärepoon tehdyt muutokset |
| git switch new-feat |	vaihtaa new-feat haaraan |
| git switch --detach origin/new-feat |	siirtyy etärepon haaraan |
| git merge origin/new-feat	| yhdistää etärepon omaan haaraan |
| git merge new-feat| yhdistää new-feat haaran masteriin |
| git branch -a	| näyttää kaikki haarat |