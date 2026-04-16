# Unity – 3D Level-Based Runner

Tento priečinok obsahuje zdrojový projekt hry vytvorenej v prostredí Unity s využitím Unity Visual Scripting (Bolt). Projekt vznikol ako súčasť bakalárskej práce zameranej na porovnanie no-code a low-code nástrojov na vývoj hier.

## Charakteristika projektu
Na rozdiel od ostatných 2D hier ide o 3D level-based runner. Hráč ovláda objekt pohybujúci sa dopredu, zbiera mince, vyhýba sa prekážkam a snaží sa dokončiť úroveň.

## Implementované mechaniky
- automatický pohyb dopredu
- pohyb do strán pomocou klávesnice
- využitie Rigidbody pre fyzikálny pohyb
- kolízie s prekážkami
- zóny smrti
- zber mincí
- reštart scény po kolízii alebo páde
- hlavné menu
- cieľová zóna úrovne

## Štruktúra projektu
- `Assets/` – herné assety, scény a Visual Scripting grafy
- `Packages/` – balíčky Unity
- `ProjectSettings/` – projektové nastavenia

## Požiadavky
- Unity Hub
- Unity 2022.3 LTS alebo kompatibilná verzia
- nainštalovaný balík Visual Scripting

## Spustenie projektu
1. Otvorte Unity Hub.
2. Zvoľte možnosť pridania existujúceho projektu.
3. Vyberte priečinok `Unity_Projekt`.
4. Po načítaní otvorte hlavnú scénu projektu.

## Poznámka
Projekt využíva výhradne vizuálne skriptovanie bez potreby písania klasického C# kódu pre základnú logiku hry.
