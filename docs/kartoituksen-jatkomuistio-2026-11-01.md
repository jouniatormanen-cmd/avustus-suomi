# Avustus Suomi – kartoituksen jatkomuistio (2026-11-01)

## Tila
Kartoitus pysäytetty käyttäjän pyynnöstä. Verkkosivustoa ei muuteta. GitHub-repo: jouniatormanen-cmd/avustus-suomi, haara main. Pääaineisto: data/palvelut.json, 198 merkintää, 63 erilaista municipality-arvoa (mukana valtakunnalliset tunnisteet; ei yhtä kuin katetut kunnat). Pääaineiston blob-SHA 61be7c8afc9fed7c49c5cbc2b30646591116651e. Viimeisin tietokantapäivitys lisäsi Pitäjänmäen diakonisen kaupan kartoituskohteen ja merkitsi Inkoon A-killan jäsenmaksullisen ruokajaon julkaisuun kelpaamattomaksi.

## Muut erilliset tiedostot
- data/kartoitus-jyvaskyla-2026-11-01.json: 7 Jyväskylän ruoka-avun palvelukohdetta, EI yhdistetty pääaineistoon.
- data/kartoitus-jyvaskyla-tarkennukset-2026-11-01.json: 4 tarkennusta samoihin kohteisiin, EI 4 uutta palvelua.
- Varmuuskopio: varmuuskopiot/avustus-suomi-kartoitus-2026-11-01.json sisältää täydellisen kopion kaikista kolmesta tiedostosta.

## Työn tavoite ja rajaukset
Kartoita järjestelmällisesti KAIKKI Suomen kunnat ja kaikki kuusi luokkaa: Ruoka-apu, Kotiapu, Raha-asiat, Keskusteluapu, Asuminen, Vaatteet ja tavarat. Kerää JOKAINEN konkreettinen maksuton palvelu ja tapahtuma, ei pelkkiä yleisiä organisaatiolinkkejä. Mukaan seurakunnat, diakonia, SPR, hyväntekeväisyysjärjestöt, A-killat ja paikalliset toimijat. Facebook-ryhmiä ei käytetä. Tallenna järjestäjä, palvelu, osoite, aika, yhteystiedot, osallistumisehdot, maksuttomuus, lähde ja toistuvien tapahtumien yksittäiset vahvistetut tapahtumakerrat. Älä keksi puuttuvia tietoja. Poista kaksoiskappaleet.

## Laadunvarmistus ja avoimet ongelmat
- 198 merkintää EI tarkoita 198 varmistettua tai julkaisuvalmista maksutonta palvelua. Monilla tiedot ovat puutteelliset ja publication_ready=false.
- Inkoon A-killan ruokajako av-0120: jäsenmaksu 40 €/aikuinen/vuosi; free_service=false, publication_ready=false. Tarkista muidenkin kohteiden maksuttomuus ennen julkaisua.
- Jyväskylän 7 erillistä merkintää yhdistettävä pääaineistoon lähteet ja päällekkäisyydet tarkistaen; neljä tarkennusta kohdistuvat samoihin palveluihin.
- Tarkista olemassa olevien palveluiden osoitteet, aukioloajat, yhteyshenkilöt, ehdot, tapahtumakerrat, ajantasaisuus ja luokitus. Esimerkiksi läksyapu ei ole automaattisesti Kotiapu; kriisiapu ei automaattisesti rahallista avustusta.
- Yleisiä seurakuntadiakonian kartoituskohteita: av-0094–av-0101, av-0106, av-0107; SPR Joensuun ruoka-apu av-0119 vaatii täsmennyksen.
- Sivustoa EI muuteta. 'Tarjoa apua' ja 'Vinkkaa palvelusta' -painikkeet myöhemmin. Käyttäjä tarkastaa lopuksi maksut ja ehdot.

## Jatkamisen työjärjestys
1. Lue tämä muistio sekä kolme lähtötiedostoa GitHubista.
2. Yhdistä Jyväskylän 7 palvelua ja 4 tarkennusta pääaineistoon vain kerran; varmista ajantasaiset alkuperäislähteet.
3. Jatka kuntakohtaista kartoitusta isoina erinä kaikissa kuudessa kategoriassa. Älä lisää pelkkiä yleisluontoisia kartoitusmerkintöjä määrän kasvattamiseksi.
4. Vahvista yksittäiset tapahtumakerrat vain julkaistuista tapahtumaluetteloista. Älä päättele niitä pelkästä viikkorytmistä.
5. Tallenna jokainen erä GitHubiin ja tarkista commit. Jos suuren tiedoston päivitys epäonnistuu, tallenna uusi erillinen kartoitustiedosto, jota ei lasketa pääaineiston merkinnöiksi ennen yhdistämistä.
6. Kun koko maa on käyty läpi, tee kattavuus- ja laatuauditointi käyttäjän kanssa.

## Keskustelun käytäntö
Käyttäjä haluaa pitkää, keskeytymätöntä työskentelyä ilman että joutuu jatkuvasti sanomaan 'jatka'. Työkalut eivät kuitenkaan jatka automaattisesti viestin päättymisen jälkeen: älä väitä taustatyötä. Raportoi toteutunut tallennus, ei keksittyä edistymistä.

## Uuden keskustelun aloitus
'Jatketaan Avustus Suomen kartoitusta GitHubissa. Lue ensin docs/kartoituksen-jatkomuistio-2026-11-01.md ja varmuuskopiot/avustus-suomi-kartoitus-2026-11-01.json. Jatka tietojen keruuta sovitulla tavalla, älä muuta sivustoa.'
