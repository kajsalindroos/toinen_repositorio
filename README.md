Git-versionhallinta - SOF013AS2A-3001, 
Kajsa Lindroos, 
index.html sisältää ajan näyttävän javascript-ohjelman,
ja git-oppimispäiväkirjasta löytyy kurssin aikana tehdyt päiväkirjamerkinnät.
______________________________________________________________________________
Päiväkirjamerkinta 1

# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__
Uuden hakemiston luonti ja tiedostojen lisäys sinne oli minulle jo ennalta tuttua, ja tehtävien aloitus oli helppoa. Mielenkiintoisinta olivat haarat ja niiden välillä siirtyminen. Ennen kurssin aloitusta pohdin, miten useampi henkilö voi tehdä muutoksia samaan aikaan, ja haarat vastasivat tähän kysymykseen. Haluaisin oppia käyttämään niitä vieläkin paremmin tulevaisuudessa.

Eniten haasteita ilmeni harjoituksessa kolme, tiedostojen poistamisessa. Itselleni jäi epäselväksi, tuliko ylimääräiset harjoitusta varten luodut tehtävät poistettua vai ei. Lisäksi en ollut varma poistinko liikaa vanhoja muutoksia vahingossa edellisistä tehtävistä.

Oppimateriaalit antoivat usein vastaukset kaikkiin kysymyksiini, ja lisäksi pohdin tehtäviä yhdessä kaverin kanssa. Edellä mainitussa muutosten poistossa turvauduin myös googleen, josta ei lopulta ollutkaan niin paljon apua.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
|git add| lisää tiedostoon tehdyt muutokset |
|git commit -m | siirtää uudet muutokset lopullisesti päähaaraan |
|git init| luo uuden git repositorion|
|cd| siirtää sijaintisi valittuun tiedostoon |
|git mkdir| luo uuden hakemiston|
|git branch| luo uuden haaran |
|git checkout| vaihtaa sijaintisi toiseen haaraan |
|git status| kertoo tämän hetkisen tilanteen, esim. onko muutoksia joita ei ole lisätty päähaaraan|
|ls| listaa hakemiston sisällön |
|git log | antaa listan aiemmista muutoksista ja lisäyksistä|
______________________________________________________________________________
Päiväkirjamerkintä 2

# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Tehtävässä 5 tuli haasteita vastaan, kun minulla ei ollut oikeuksia puskea master haaraa githubiin. Vaikka kurssin alussa konfiguroitiin käyttäjätiedot, tietokoneeni väittää minun olevan henkilökohtaisella github-tililläni koulun tilin sijaan. Päädyin ratkaisemaan ongelman jakamalla oikeudet repositorioon henkilökohtaisen tilini kanssa, jolloin sain puskettua master haaran githubiin.

Käyttäjäoikeus haasteet veivät eniten aikaa tehtävän tekemiseen, mutta muuten tehtävä sujui ilman erityisiä ongelmia.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git clone | luo uuden repositorion valmiiksi annetuilla tiedostoilla |
| git remote add origin | luo etärepositorion nimellä origin |
| git remote -v | näyttää etärepositorion asetukset  |
| git fetch| tuo haaran tiedot paikalliseen repositorioon |
| git push origin master| puskee paikallisen repositorion githubiin |
| git merge origin/master | yhdistää paikallisen ja etärepositorion toisiinsa |
| git status | näyttää onko tällä hetkellä mitään tehtävää |

______________________________________________________________________________
Päiväkirjamerkintä 3

# Oppimispäiväkirja: Git projektissa

__Mitä hyötyä voisi olla versionhallinnasta, jos kehität projektia yksin?__

Versionhallinta antaa projektille hyvän suunnitelman jo ennen aloitusta, siitä missä tiedostojen kuuluisi olla. Versionhallinta myös mahdollistaa virheiden tapahtuessa edelliseen versioon palaamisen, ja toimii hyvin ns varmuuskopiona projektille.

__Mitä hyötyä voisi olla versionhallinnasta, jos projektissa on useita kehittäjiä?__

Versionhallinnan avulla useampi kehittäjä voi tehdä muutoksia samaan aikaan, ja niistä valitaan halutut lopulliset muutokset viimeiseen versioon. Muutokset eivät voi vahingossa mennä lopulliseen versioon ilman hyväksyntää, joka ehkäisee virheitä.

__Miten järjestäisit projektitiimin versionhallinnan 3-4 hengen ohjelmistoprojektikurssilla? Laadi tiimiläisille lyhyt ohje, miten projektissa toimitaan.__

Aluksi luomme kehityshaaran, johon muutoksia aktiivisesti tehdään. Kehityshaarasta yhdessä hyväksytyt muutokset siirretään main-haaraan. Main-haaraan siirretään ainoastaan lopulliset muutokset, ja kaikki testailu tapahtuu kehityshaarassa. Muutospyyntöihin tulee lisätä selkeä aihe sekä syy sen lisäykselle.

__Kommenttini opintojaksosta, esim. sisällöstä, materiaalista, työmäärästä, hyödyllisyydestä, työmäärästä. Mitä toivoisit olevan enemmän, mitä vähemmän?__

Opintojakso sisälsi sopivan määrän erilaisia git-komentoja, joihin pääsimme tutustumaan opintojakson aikana. Tämänkaltaiset kurssit voivat usein olla haastavia, joten pidin siitä että komentoja ei usein tarvinnut itse lähteä etsimään netistä. Uskon versionhallinnan tulevan tutuksi matkalla ohjelmistokehittäjäksi. 

Viimeinen osio oli kaikista haastavin ja soveltavin, ja tehtävien tekemisen jälkeen jäi epävarma olo siitä, tulivatko ne tehtyä oikein. Ehkäpä viimeiset tehtävät hyötyisivät lisäohjeistuksesta.
