# Oppimispäiväkirja: Paikallinen git

__Mitä uutta opin osiossa? Miten voisin hyödyntää oppimaani käytännössä?__

Opin komentoja siitö, miten varmistan että versionhallinnassa sekä paikallisesti poistamani ja muokkaamani tiedostot poistuvat molemmista (git rm ja git mw). Aikaisemmin sorruin usein siihen, että poistan tiedostoja manuaalisesti resurssien hallinnassta, jolloin versionhallinnan kanssa tulee ongelmia




__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

En kokenut haasteita juurikaan, jostain syystä hello hakemisto poistui kun yritin poistaa pelkästään yhtä siellä olevaa tiedostoa. Onneksi on restore ja reset komennot

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git add . / git add <tiedosto> | Lisää tiedoston/tiedostot siirrettäväksi versionhallintaan|
| git commit | Siirtää tiedostot versionhallintaan |
| git status | Näyttää hakemiston ja sen muutokset|
| git log ja git log --stat| Listaa talletukset käänteisessä järjestyksessä|
| git rm <tiedosto> | poistaa tiedoston työhakemistosta sekä versionhallinnasta|
| git mv <tiedosto> | nimeä' tiedoston uudelleen tai siirtää toiseen hakemistoon|
| git checkout | Komennolla voi siirtyä tiettyyn tallennukseen tunnustenimellä|
| git switch - | Komennolla pääsee pois detached HEAD' state  - tilasta |
| git reset | Komennolla poistetaan talletukseen lisätty tiedosto pois talletuksesta |
| git restore | Palauttaa tiedoston versionhallinnan tuoreimman version tasalle|