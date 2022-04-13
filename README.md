# Naravno gibanja prebivalstva
Število prebivalcev nekega območja je odvisno od naravnega gibanja števila prebivalcev in selitev. Naravno gibanje števila prebivalcev je odvisno od rodnosti in umrljivosti. Razlika med njima je naravni prirastek. Na število prebivalcev pa vplivajo tudi odselitve in priselitve.

## Opis podatkov
Za podatke seminarske naloge smo uporabili [Naravno Gibanje prebivalstva v Slovenkih občinah](https://podatki.gov.si/dataset/surs05i1002s?resource_id=dba45097-b4aa-45e8-914c-7d41a49269c4), [Povrpečne mesečne plače po občinah](https://podatki.gov.si/dataset/surs0772615s/resource/a3b2e662-9a14-4b8f-ab50-9a703f8db73e) ter [Delovno aktivno prebivalstvo po občinah](https://podatki.gov.si/dataset/surs0764720s/resource/e1993089-ac98-4695-b7b8-f2e10d86a331).
Iz prve množice podatkov smo izbrali samo iste primere za ketere imamo zadostno število meritev, manjjkajoče podatke pa smo poskušali dopolniti iz ostalih virov.
Podatko so v formatu PCAXIS in sicer opisujejo:

* Podatke o naravnem prirastu ljudi v občinah z letom meritve, tipom meritve ter vrednostjo meritve.
* Podatke o delovno aktivnem prebivalstvu, kjer zapisi povejo leto meritve, samostojno občino kjer je bilo merjeno ter izobrazbo, spol in Število primerkov.
* Podatki o poovprečni mesečni plači, zapisi pa prkazujejo posamično občino, tip meritve, leto meritve ter povprečno plačov le tej občini.

## Opis problema
S to seminarsko nalogo smo si zastavili odgovoriti vprašanja: 
1.  Ali je mogoče napovedati naravni prirast prebivalstva za prihodnost.
2.  Ali obstaja povezava med povprečno plačo in številom živorojenih otrok.
3.  Ali obstaja povezava med doseženo izobrazbo in naravnim prirastom  

Ko smo podatke rabili za skupne primerjave, smo uporabljali samo podatke po letu 2005, saj takrat se komaj vse podatkovne strukture začnejo prekrivati. 
Po združitvi podatkov smo odstanili nekatere najnovejše nastale občine. do sedaj nismo opazili nobenih prevelikih napak v podatkih.

## Cilj in metode
Za doseganje zastavljenih ciljev smo se odločili uporabiti različne načine in sicer, za izračuna naravnega prirasta bomo s pomočjo linearne regresije skušali zgradutu model, ki bo napovedal gibanje naravnega prirasta v prihodnosti in s pomočjo korelacije bomo skušali najti povezavi med plačo in številom živorojenih otrok ter med doseženo izobrazbo in naravnim prirastom. 

## Vizualizacija
