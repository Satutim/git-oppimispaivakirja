# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Olen luonut uuden repositorion GitHubissa ennenkin, mutta koska sitäkään en ole tehnyt usein, sain lukea ohjeista, miten se tehtiin. Sisällöltään tyhjä repositorio oli kuitenkin selkeä luoda, koska GitHub ohjasi siinä hyvin.

Haarojen luominen sekä niiden välillä vaihtaminen oli aiemmasta tehtävästä tuttua. Jouduin kuitenkin edelleen turvautumaan ohjeisiin, jotta tein askeleet oikein. Haarojen tarkastelu ja luominen kahdessa eri paikassa oli aluksi hieman hämäävää. Ajatustyötä vaati varsinkin se, mitä pitää tehdä komentorivillä ja mitä GitHubissa ja miten toisessa tehty muutos näkyy toisessa. Tehtävä kuitenkin selkeytti tätä ja opin hakemaan GitHubissa olevat muutokset git fetch -komennolla tarkasteltavaksi sekä hakemaan muutokset etärepositoriosta ja yhdistämään ne paikalliseen haaraan git pull komennolla.

Haastetta tuotti esimerkiksi se, kun yritin vaihtaa päiväkirja ykkösestä päiväkirja kakkoseen, mutten ollut vielä tehnyt kaikkia tallennuksia päiväkirja ykköseen, joten en voinut suoraan vaihtaa haaraa. Virheviesti kertoi onneksi jo valmiiksi, miten pääsin tästä etenemään.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git remote -v | Näyttää mihin etärepositoioon paikallinen repositorio on yhdistetty |
| git push | Vie muutokset GitHubiin |
| git push -u origin new-feat | Vie kokonaan uuden haaran GitHubiin ja yhdistää sen etärepositorioon |
| git fetch | Hakee etärepositorion muutokset |
| git switch -c new-feat | Luo uuden haaran ja siirtyy siihen |
| git switch new-feat |	Vaihtaa nimettyyn haaraan |
| git switch master | Vaihtaa master-haaraan
| git switch --detach origin/new-feat |	Siirtyy etärepositorion haaraan |
| git merge origin/new-feat	| Yhdistää etärepositorion paikalliseen haaraan |
| git merge new-feat | Yhdistää new-feat haaran masteriin / muuhun haaraan |
| git branch -a	| Näyttää kaikki haarat |
| git branch | Näyttää paikalliset haarat |
| git tag harjoitus | Lisää nimetyn tunnisteen commitiin |