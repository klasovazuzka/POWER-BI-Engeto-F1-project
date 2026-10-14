# Analýza Formule 1 (1950–2026)
Cílem projektu je vytvořit interaktivní analýzu historických dat Formule 1 v období 1950–2026 se zaměřením na vývoj závodů, výkonnost jezdců a týmů a analýzu závodních okruhů.

Report je vytvořen v Power BI a skládá se z několika propojených stránek s interaktivním filtrováním a navigací. Uživatel může data filtrovat například podle roku, jezdce, týmu, národnosti nebo závodního okruhu.

Zdrojová data pocházejí z veřejně dostupného datasetu Complete Formula 1 Dataset (1950–2026).

## Příprava a zpracování dat
Před vytvořením reportu byla data načtena a upravena v Power Query. Následně byl vytvořen relační datový model propojující hlavní tabulky:

results
races
drivers
constructors
circuits
Pro analýzu byly vytvořeny vlastní DAX míry a kalkulované sloupce, například pro celkové body, počet závodů, počet vítězství, průměrnou cílovou pozici, věk jezdce při závodě nebo kategorizaci výsledků.

## Struktura reportu
Stránka 1 — Úvodní stránka
Titulní stránka projektu s navigačními tlačítky umožňujícími přechod mezi jednotlivými částmi reportu.

Stránka 2 — Přehled Formule 1
Souhrnný přehled historie Formule 1. Obsahuje hlavní KPI, TOP jezdce, týmy a národnosti, vývoj celkových bodů podle sezóny a mapu závodních okruhů.

Stránka 3 — Analýza jezdců
Detailnější pohled na výkonnost jezdců. Stránka obsahuje vývoj bodů podle sezóny, porovnání startovní a cílové pozice, průměrné cílové umístění a rozdělení výsledků na vítězství, pódia, TOP 10 a umístění mimo TOP 10.

Součástí stránky jsou také interaktivní průřezy umožňující analýzu konkrétního jezdce nebo období.

Stránka 4 — Týmy a okruhy
Analýza zaměřená na týmy a závodní okruhy. Obsahuje informace o bodech a vítězstvích týmů, počtu závodů, vývoji týmů podle sezóny a analýzu závodních okruhů včetně rychlostních statistik.

### Použité nástroje
Power BI Desktop
Power Query
DAX
Azure Maps
relační datový model
interaktivní průřezy
záložky a navigace
vlastní tooltipy
podmíněné formátování

Projekt byl vytvořen jako závěrečný Power BI projekt v rámci datové akademie ENGETO.
Data zdroj: Kaggle
