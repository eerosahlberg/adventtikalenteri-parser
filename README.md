# adventtikalenteri-parser
Python-skripti partiolaisten adventtikalenterien myyntikampanjan seuraamiseen ja helppoon kirjanpitoon.

## Ominaisuudet:
* Hankalasti luettavista forms-lomakkeiden vastaustiedostoista tietojen hakeminen ja niiden parsiminen.
* Tietojen jaottelu jakokerran, henkilön ja vartion mukaan, sekä em. tietojen viesti csv-tiedostoihin lisätarkastelua varten.
* Tietojen automaattinen visualisointi 
* Mahdollisuus vertailla kuluvan vuoden tuloksia edellisiin vuosiin (beta)
* Mahdollisuus ladata generoidut csv-tiedostot automaattisesti Google Driveen (beta)

Jupyter notebook-muotoisesta tiedostosta voi ajaa vain käytön kannalta tarpeellisia soluja, ja koodia voi muokata helposti eri käyttötarkoitusten mukaiseksi (esim. kalenterimyynnin eri maksutavat)

## Esivalmistelut
Skriptin käyttö vaatii Google Drivessä saatavilla olevat sheets-taulukot, joista luetaan kirjanpidolle tarpeelliset tiedot. Varmista jakamisasetuksista, että taulukot ovat saatavilla linkin kautta tarkastellessa. Tiedot sheets-taulukoihin voidaan syöttää manuaalisesti, tai esimerkiksi Google Forms-lomakkeen avulla. Oikein formatoidut esimerkkitiedostot ja jaettujen sekä partiokokouksissa myytyjen kalenterien kirjaamiseen tarkoitetun forms-lomakkeen löytää [täältä](https://drive.google.com/drive/folders/13HdHvY2r0BYls6KIXyI85DGaW3gja3FK?usp=sharing)

## Käyttö
Lataa kalenterit.ipynb-tiedosto tietokoneelle. Asenna tiedoston ensimmäisessä solussa määritetyt python-kirjastot. Ensimmäisellä suorituskerralla skripti kysyy tarvittavien taulukoiden id:t (löytyy taulukon URL:ista kohdasta /spreadsheets/d/{id}/) sekä tiedot sisältävän välilehden nimen (oletuksena Vastauksista 1 tai Taulukko1) ja luo lokaalin konfiguraatiotiedoston näiden tietojen avulla.

Beta-tiedoston kommenteista löytyy ohjeet vuosien välisen vertailun tekemiseen sekä automaattiseen Drive-uploadiin, lähtökohtaisesti nämä ominaisuudet ovat vain kehitysasteella ja niiden käyttö vaatii tarkempaa perehtymistä asiaan.

## Lisätiedot
[eero.sahlberg@pitkajarvenvaeltajat.fi](mailto:eero.sahlberg@pitkajarvenvaeltajat.fi)
