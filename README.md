# Group project for Network science course


download data [here](https://nrvis.com/download/data/dynamic/rec-amz-Books.zip)

link to overleaf pdf [here](https://www.overleaf.com/7695275431ghcqqqzqrwhp)


## Denník prác (môžeme potom presunúť inam, toto je len pre info, aby sme o sebe navzájom vedeli):

### (Naty + Katka) -> štrukturálna podobnosť 
->cieľ: vytvoríme algoritmus, ktorý odporučí užívateľovi knihu 

    - na základe podobnosti (štrukturálna ekvivalencia), využijeme kosínosovú podobnosť
    - použijeme knižnicu isbntools - vieme zistiť názov knihy, autora, rok a vydavateľstvo 
    - navrhneme podobným čitateľom knihy od iných čitateľov aj na základe toho či obľubujú konkrétne vydavateľstvo alebo čítajú knihy z nejakého roku/desaťročia/iný časový úsek 
    
    
->Class Predictor():

    -funkcia do ktorej vložíme daný graf 
    -funkcia na vypočítanie pravdepodobnosti
    -funkcia na predikovanie podobnej knihy 


### (Kika + Hana) –> projekcia grafu + základné charakteristiky + klasifiácia
    - hustota grafu
    - najkratsia cesta medzi 2ma vrcholmi
    - diameter
    - zhlukovy koeficient
    - viacere typy centralít(degree, betweenness, eigenvectors, ...)
    - modularita - klasifikácia
