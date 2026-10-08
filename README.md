#Power BI projekt: Analýza Formule 1
##Interaktivní Power BI dashboard zaměřený na analýzu historických dat Formule 1 z období 1950–2026.

Projekt vznikl jako závěrečný projekt v rámci datové akademie ENGETO. Cílem bylo vytvořit přehledný report, který umožňuje analyzovat závody, jezdce, týmy a závodní okruhy.

##Obsah dashboardu
###Přehled Formule 1
základní statistiky závodů, jezdců a týmů,
TOP jezdci, týmy a národnosti,
vývoj celkových bodů podle sezóny,
mapa závodních okruhů.
###Analýza jezdců
vývoj bodů podle sezóny,
porovnání startovní a cílové pozice,
průměrná cílová pozice,
nejlepší sezóna jezdce,
rozdělení umístění na vítězství, pódia, TOP 10 a výsledky mimo TOP 10,
filtrování podle roku, národnosti, jezdce a věku při závodě.
###Týmy a okruhy
body a vítězství týmů,
počet závodů týmů,
výkonnost týmů podle sezóny a okruhu,
průměrná rychlost nejrychlejších kol.
Datový model

###Hlavní tabulkou datového modelu je results, která je propojena s tabulkami:
races,
drivers,
constructors,
circuits.
Vztahy jsou vytvořené pomocí identifikátorů raceId, driverId, constructorId a circuitId.

###Použité technologie
Microsoft Power BI Desktop
Power Query
DAX
Azure Maps
datové modelování
interaktivní průřezy
záložky a navigační tlačítka
vlastní tooltipy
podmíněné formátování
Zdroj dat
Projekt využívá veřejně dostupný dataset historických dat Formule 1 od roku 1950.

Projekt byl vytvořen jako portfolio ukázka práce v Power BI.


