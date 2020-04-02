# Vmesno poročilo

## Uvod in problem
Do sedaj smo se večinoma ukvarjali s problemom naše domene. Dosti časa smo posvetili medsebojnemu posvetovanju in razvijanju idej. Naredili smo ogromno vizualizacij naših podatkov. Odločili smo se, da se bomo osredotočili na uvoz in izvoz dobrin v Sloveniji. Pogledali si bomo, kaj se je dogajalo v zadnjih letih, katerih dobrin se je uvozilo, izvozilo več oz. manj. Tekom raziskovanja bomo poizkusili odgovoriti na vprašanje, kako je to vplivalo na cene dobrin in ali se je poraba določenih dobrin s časom povečala oz. zmanjšala. Poizkusili bomo odgovoriti tudi na vprašanje, ali se je potrošnja gospodinjstev povečala za določene dobrine ali zmanjšala glede na količino uvoza oz. izvoza v nekem letu. Pogledali bomo, katera podjetja oziroma industrije so čez leta uvozila oz. izvozila več dobrin.

## Podatki

Še vedno vztrajamo pri izbranih podatkovnih zbirkah. Izbrali smo si dve, in sicer:
* zbirka podatkov za uvoz oz. izvoz podjetij,
* zbirka podatkov o izdatkih gospodinjstev.

Opis podatkov se nahaja v osnutku. Pri pripravljanju podatkov smo večinoma obdržali vse atribute. Nekaj sprememb smo opravili pri prvoomenjeni podatkovni zbirki, saj je bilo navedenih nekaj nepotrebnih podatkov oz. podatkov, ki jih ne bomo potrebovali. Za delo smo večinoma uporabljali Python knjižnico *pandas*.

## Analize

Tekom druge faze projekta smo opravili ogromno vizualizacij. Namen tega je seveda, da bi iz ogromno podanih podatkov izluščili kaj zanimivega in uporabnega. S tem smo tudi bolje spoznali naši dve podatkovni zbirki. Zaenkrat smo opravljali vizualizacije za vsako podatkovno zbirko posebej, ker sta precej široki. Tekom razvoja projekta bomo rezultate skušali tudi združiti, da bi prišli do nekaj bolj zanimivih odgovorov. Razlika med podatkovnima zbirkama je v obsegu, in sicer prva pokriva svetovno merilo, medtem ko druga pokriva zgolj Slovenijo. Tudi ta vpliv bomo poizkusili prikazati. Izmed vseh opravljenih vizualizacij smo izluščili nekaj osnovnih in nekaj zanimivejših.


#### Vizualizacija 1 (uvoz, izvoz)

Graf prikazuje povprečno število izvozov podjetij znotraj EU in izven EU. Ugotovimo, da države znotraj EU izvozijo več dobrin oz. produktov kot države izven EU. Število izvoza pomeni cena v evrih.
![alt text](https://github.com/rokserak/PR20-SOHG/raw/master/grafi/EUvsNEEU.png "Izvoz EU vs ne-EU")


#### Vizualizacija 2 (uvoz, izvoz)

Graf prikazuje vrednost izvoza raznih panog. Podatki so zbrani glede na vse države oz. podjetja skupaj (torej znotraj EU in zunaj EU). Kategorije panog v podatkovni zbirki so štiri in še ena dodatna kategorija, ki skupaj pokrije 9 ostalih oz. neznanih panog. Ugotovimo, da proizvodnja (angl. manufacturing) pokrije največji delež izvoza. Temu sledi izvoz trgovin na debelo in na drobno ter popravilo vozil. Izvoz je izražen kot vrednost v evrih. 
![alt text](https://github.com/rokserak/PR20-SOHG/raw/master/grafi/izvoz_panoge.png "Izvoz po panogah")


#### Vizualizacija 3 (uvoz, izvoz)

Graf prikazuje medsebojno primerjavo števila izvozov in uvozov, in sicer za najboljših tisoč podjetij svetovnega merila skupaj. Vizualizacija je bila opravljena za leto 2018, saj gre za najnovejši podatek iz podatkovne zbirke. Vidni so preskoki v določenih časovnih obdobjih. Preskoki so podobni tako pri uvozih, kot tudi pri izvozih. Vidimo lahko še, da so podjetja načeloma uvozila nekoliko več kot izvozila.   
![alt text](https://github.com/rokserak/PR20-SOHG/raw/master/grafi/izviz2018.png "Izvoz 2018")


#### Vizualizacija 4 (uvoz, izvoz)

Graf prikazuje podobno zadevo kot prejšnji. Tu je prikazana primerjava uvozov med letom 2008 in letom 2018 za najboljših 1000 podjetij. S tem smo želeli pokazati, ali se je trend v desetletju spremenil. Ugotovimo, da je trend podoben, le da se je število uvozov skozi desetletje povečalo. To v bistvu na nek način pomeni tudi večjo dobičkonosnost in gospodarsko rast. Preskoki pa so v 2018 ostali podobni kot desetletje prej.
![alt text](https://github.com/rokserak/PR20-SOHG/raw/master/grafi/uvoz20082018.png "Izvoz 2018")


#### Vizualizacija 5 (gospodinjstvo)

Graf prikazuje, koliko smo Slovenci porabili za posamezno kategorijo od leta 1995 do vključno leta 2018. Podatki so bili zbrani glede na posamezno gospodinjstvo. Torej, koliko evrov na leto smo skupaj namenili posamezni kategoriji. To je eden zanimivejših grafov, ki nam pove marsikaj uporabnega. Največ denarja smo namenili za prevozna sredstva, sledi zdravstvo, nato alkohol. Zanimivo je, da smo več denarja zapravili za lakohol kot pa za izobraževanje. Prav tako je zanimivo, da smo skozi leta namenili več denarja prostituciji kot pa vzdrževanju stanovanja. Ta trend se je sicer nekoliko obrnil v letu 2018. Daleč največ denarja smo torej namenili prevoznim sredstvom. 
![alt text](https://github.com/rokserak/PR20-SOHG/raw/master/grafi/tavlk%20gospodinstvo.png "gospodinjstvo")


#### Vizualizacija 6 (gospodinjstvo)

Graf prikazuje...
![alt text](https://github.com/rokserak/PR20-SOHG/raw/master/grafi/bolnca%20scatter.png "Poraba bolnica vs ne bolnice za zdravljenje")


#### Vizualizacija 7 (gospodinjstvo)

Graf prikazuje...
![alt text](https://github.com/rokserak/PR20-SOHG/raw/master/grafi/pjaca%20scatter.png "Alkohol vs brezalkoholn")

