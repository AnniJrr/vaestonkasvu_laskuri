# vaestonkasvu_laskuri
Väestölaskuri-verkkosovellus visualisoi väestönkasvua eri maissa Maailmanpankin avoimen rajapinnan avulla.

Sovellus on tehty huhtikuussa 2020 Sympan järjestämällä verkkokurssilla "Web Coding for Beginners: Population Graphs". 

**Tekniikat:** HTML, CSS, JavaScript

**In English:** A project for a web course “Web Coding for Beginners: Population Graphs", which was organized by Sympa. The web application visualizes population graphs for different countries using data from a live World Bank API. 

# Käyttöohje:
- Kirjoita tekstikenttään haluamasi valtion maakoodi (esim. FIN, ITA tai USA).
- Klikkaa painiketta ” Render population graph”.
- Tämän jälkeen sovellus piirtää kaavion halutun maan väestönkasvusta 50 vuoden ajalta.


# Lisätietoja sovelluksesta:
Väestölaskuri-sovellus hakee datan ottamalla yhteyden Maailmanpankin avoimeen rajapintaan, josta se pyytää käyttäjän syöttämän valtion tiedot. Väestötiedot palautetaan viimeisen 50 vuoden ajalta (vuosilta 1970-2019). 

Maailmanpankin rajapinta (https://world-bank-data.appspot.com) siirtää datan sovellukselle json-muodossa. Datan visualisoinnissa hyödynnetään Chart.js:ää, joka on avoimen lähdekoodin JavaScript-kirjasto. Ulkoasuun on käytetty valmista Bootstrap-tyylitiedostoa. CSS-tiedostoon on määritelty verkkosivun elementtien asettelu. JavaScript-tiedosto sisältää ohjelman toiminnallisuuden. 

Sovelluksen kieli on englanti, ainakin toistaiseksi.

Väestölaskuri on keskeneräinen projekti, yksinkertaisella perustoiminnallisuudella. 
Sovellukseen on tulossa vielä: 
- siistimpi ulkoasu muokkaamalla sivun elementtejä (väriä, kokoa, sijaintia) 
- käyttäjälle mahdollisuuksia datan rajaamiselle (väestön sukupuolen, ikäryhmien ja vuosilukujen mukaan) 
- pudotusvalikko, josta käyttäjä voi valita haluamansa valtion maakoodin kirjoittamisen sijaan 
- poikkeusten käsittely mahdollisia virhetilanteita varten.

Suunnitelmissa on myös kokeilla Väestölaskuri-projektin tekniikkaa muihin vastaaviin sisältöihin, kuten Helsingin kaupungin tarjoamaan avoimen rajapinnan dataan. Siellä kiinnostavia visualisointikohteita ovat esimerkiksi jatkuvasti päivittyvä data Helsingin uimavesien lämpötiloista ja talven liukastumisvaroitukset eri puolilla kaupunkia. Pienillä muokkauksilla sovelluksella saisi visualisoitua myös ajankohtaista tietoa koronaviruksesta. Dataa tähän tarjoavat niin Maailmanpankki kuin THL ja Helsinkin Sanomatkin.


