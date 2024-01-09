Elections Scraper
------------------

Tento projekt Elections Scraper má za úkol vyhledat výsledky voleb z roku 2017 z odkazu 'https://volby.cz/pls/ps2017nss/ps3?xjazyk=CZ' dle územního celku, který je potřeba zadat jako první argument v příkazovém řádku. Dále je potřeba zadat druhý argument název souboru .csv do kterého budou výsledky zapsány.

Jak spustíš script:
1. Zadejte název územního celku --mesto : Kladno "první velké písmeno"
2. Zadejte název souboru .csv --soubor : vysledky_voleb2017_kladno.csv

```python main.py --mesto "Kladno" --soubor "vysledky_voleb2017_kladno.csv"```


Částečný výstup:
```
Kód obce,Název obce,Voliči v seznamu,Vydané obálky,Platné hlasy,Občanská demokratická strana,Řád národa - Vlastenecká unie,CESTA ODPOVĚDNÉ SPOLEČNOSTI,Česká str.sociálně demokrat.,Radostné Česko,STAROSTOVÉ A NEZÁVISLÍ,Komunistická str.Čech a Moravy,Strana zelených,"ROZUMNÍ-stop migraci,diktát.EU",Strana svobodných občanů,Blok proti islam.-Obran.domova,Občanská demokratická aliance,Česká pirátská strana,Unie H.A.V.E.L.,Referendum o Evropské unii,TOP 09,ANO 2011,Dobrá volba 2016,SPR-Republ.str.Čsl. M.Sládka,Křesť.demokr.unie-Čs.str.lid.,Česká strana národně sociální,REALISTÉ,SPORTOVCI,Dělnic.str.sociální spravedl.,Svob.a př.dem.-T.Okamura (SPD),Strana Práv Občanů
535010,Běleč,262,181,181,"12,70","0,00","0,00","10,49","0,00","7,18","6,07","0,55","1,10","0,00","0,00","0,00","12,15","0,00","0,00","6,07","33,70","0,00","0,00","3,31","0,00","0,55","0,55","0,55","4,41","0,55"
532070,Běloky,135,102,101,"11,88","0,00","0,00","9,90","0,00","5,94","11,88","0,99","0,00","2,97","0,00","0,00","15,84","0,00","0,00","7,92","20,79","0,00","0,00","2,97","0,00","0,00","0,00","0,00","8,91","0,00"
532088,Beřovice,272,152,152,"13,81","0,00","0,00","7,89","0,00","8,55","3,94","1,97","1,97","1,31","0,65","0,00","11,84","0,00","0,00","3,28","32,89","0,00","0,65","0,00","0,00","0,00","0,00","0,00","11,18","0,00"
535125,Bílichov,155,99,99,"7,07","0,00","0,00","9,09","0,00","10,10","14,14","0,00","0,00","4,04","0,00","0,00","8,08","0,00","0,00","4,04",...
```

