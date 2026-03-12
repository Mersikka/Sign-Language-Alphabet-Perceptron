# Määrittelydokumentti
Toteutan projektin Pythonilla. Kykenen vertaisarvioimaan Python-projektien lisäksi JavaScript/TypeScript-projekteja.

Projektin tavoitteena on luoda multilayer perceptron -neuroverkko, joka kykenee tunnistamaan mahdollisimman suuren osan Suomen viittomakielen aakkosista, mukaan lukematta liikettä vaativia kirjaimia J, Z, Å, Ä ja Ö. Lähtökohtaisen tavoitteen asetan kymmenen kirjaimen (A-K, pois lukien J) tunnistamiseen tyydyttävällä tarkkuudella (Sopivaa tarkkuutta vaikeaa määrittää etukäteen, tarkentunee myöhemmin). Näillä rajoituksilla pyrin pitämään projektin laajuuden kurssin vaatimuksiin sopivana. Mikäli aikaa näyttäisikin riittävän loppua kohden, saatan lisätä muitakin kirjaimia.

Ohjelma tulee sisältämään yksinkertaisen graafisen käyttöliittymän kamerasyötteellä. Käyttäjä voi näyttää haluamaansa viittomakielen kirjainta kameralleen, jolloin neuroverkko pyrkii arvaamaan käyttäjän esittämän kirjaimen. Arvaus tulee käyttöliittymään näkyviin (ainakin lähes) reaaliajassa.

Lähtökohtana käytän aiempaa samanaiheista [projektinalkuani](https://github.com/Mersikka/FSLI). Lähteinä käytän kurssimateriaalissa mainittuja resursseja, kuten "[Michael Nielsenin kirjoittama arikkeli MNISTin numeroiden tunnistuksesta neuroverkoilla](http://neuralnetworksanddeeplearning.com/chap1.html)" ja "[3Blue1Brownin erittäin hyvin tehdyt videot neuroverkoista](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)". Lähdelista täydentyy projektin edetessä.
