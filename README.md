# Naravno gibanja prebivalstva
Število prebivalcev nekega območja je odvisno od naravnega gibanja števila prebivalcev in selitev. Mi se bomo v seminarski nalogi osredotočili na naravno gibanje. To je odvisno od rodnosti in umrljivosti. Razlika med rodnostjo in umrljivostjo je naravni prirastek.

## Opis podatkov
Za podatke seminarske naloge smo uporabili podatke iz 3 virov: [Naravno gibanje prebivalstva v Slovenskih občinah](https://podatki.gov.si/dataset/surs05i1002s?resource_id=dba45097-b4aa-45e8-914c-7d41a49269c4), [Povprečne mesečne plače po občinah](https://podatki.gov.si/dataset/surs0772615s/resource/a3b2e662-9a14-4b8f-ab50-9a703f8db73e) ter [Delovno aktivno prebivalstvo po občinah](https://podatki.gov.si/dataset/surs0764720s/resource/e1993089-ac98-4695-b7b8-f2e10d86a331).

Podatki so v formatu PCAXIS in sicer opisujejo:

* Podatke o naravnem prirastu ljudi v občinah z letom meritve, tipom meritve ter vrednostjo meritve.
* Podatke o delovno aktivnem prebivalstvu, kjer zapisi povejo leto meritve, samostojno občino kjer je bilo merjeno ter izobrazbo, spol in Število primerkov.
* Podatki o poovprečni mesečni plači, zapisi pa prkazujejo posamično občino, tip meritve, leto meritve ter povprečno plačov le tej občini.

Ko smo podatke rabili za skupne primerjave, smo uporabljali samo podatke po letu 2005, saj takrat se komaj vse podatkovne strukture začnejo prekrivati.
Izbrali smo tiste primere za katere imamo zadostno število meritev, nekatere manjkajoče podatke pa smo poskušali dopolniti iz ostalih virov. Podatke smo nato grupirali. V podatkih zaenkrat nismo opazili nobenih napak.

## Opis problema
S to seminarsko nalogo smo si zastavili vprašanja: 
1.  Ali je mogoče napovedati naravni prirast prebivalstva za prihodnost.
2.  Ali obstaja povezava med povprečno plačo in številom živorojenih otrok.
3.  Ali obstaja povezava med doseženo izobrazbo in naravnim prirastom  
4.  
Poleg teh glavnih vprašanj bomo skušali postaviti še več manjših podvprašanj, tako da lahko iz podatkov razberemo čimveč.

## Cilj in metode
Za doseganje zastavljenih ciljev smo se odločili uporabiti različne načine in sicer: za izračun naravnega prirastka bomo s pomočjo linearne regresije skušali zgraditi model, ki bo napovedal gibanje naravnega prirasta v prihodnosti in s pomočjo korelacije bomo skušali najti povezavi med plačo in številom živorojenih otrok ter med doseženo izobrazbo in naravnim prirastom. 

## Vizualizacija
