# Rezistory
Rezistory jsou elektrické součástky, které omezují nebo regulují tok elektrického proudu v elektrickém obvodu.

#### Jednotky:
Odpor se měří v ohmech (Ω).


#### Tolerance:
Rezistory mají určenou toleranci, která určuje povolené odchylky od stanovené hodnoty odporu (například 5%, 1%).

#### Hodnocení výkonu:
Udává, kolik tepla může rezistor odvádět, aniž by se poškodil, a měří se v wattech (W).

#### Typy:

Existuje několik typů rezistorů, včetně uhlíkových, filmových, cívkových a proměnných (potenciometry).
Aplikace:

Rezistory se používají v obvodech k omezení proudu, dělení napětí, úpravě signálu a dalším.

#### Ohmův zákon:

Je zásadní pro porozumění vztahu mezi napětím (V), proudem (I) a odporem (R) v obvodu ($V = IR$).

#### Závislost na teplotě:

Některé rezistory mohou měnit hodnotu odporu s teplotou, což je důležité zvážit v určitých aplikacích.

#### Kódování barev:

Mnoho rezistorů je kódováno barvami na těle rezistoru, což indikuje hodnotu odporu.

#### Účel:

Jsou základními součástmi elektroniky, které slouží k řízení a tvarování elektrických proudů v různých elektronických zařízeních a obvodech.

## Sériové spojení rezistorů:

Při sériovém spojení rezistorů jsou rezistory spojeny za sebou v jediné cestě, vytvářející lineární řetězec.

1. Proud: **V sériovém spojení proudí stejný proud všemi rezistory, protože existuje pouze jedna cesta pro tok proudu.**

2. Součet odporu: Celkový odpor v sériovém spojení je součtem hodnot jednotlivých rezistorů. 

$$
R_c = R_1 + \dots + R_n
$$

3. Rozdělení napětí: **Napětí na každém rezistoru v sériovém spojení se sčítá na celkové napětí aplikované na obvod.**

$$
V_c = V_1 + \dots + V_n
$$

4. Konstantní proud: **Protože stejný proud protéká všemi rezistory v sérii, pokud jeden rezistor selže (sepnutí), celý obvod je přerušen.**

5. Aplikace: Sériová spojení se používají, když chcete zvýšit celkový odpor v obvodu nebo když je nutné rozdělení napětí.

## Paralelní spojení rezistorů:

Definice: V paralelním spojení rezistorů jsou rezistory spojeny vedle sebe, přičemž každý rezistor má svou vlastní cestu pro proud.

Rozdělení proudu: V paralelním spojení se celkový proud vstupující do spojení rozděluje mezi jednotlivé rezistory. Každý rezistor nese část celkového proudu.

Výpočet odporu: Výpočet celkového odporu v paralelním spojení je složitější. 

$$
\frac{1}{R_c} = \frac{1}{R_1} + \dots + \frac{1}{R_n}
$$

$$
R_c = \frac{R_1R_2}{R_1 + R_2}
$$

$$
R_c = \frac{1}{\frac{1}{R_1} + \dots + \frac{1}{R_n}}
$$

Napětí: Napětí na každém rezistoru v paralelním spojení je stejné a odpovídá celkovému aplikovanému napětí.

Redundance: Pokud jeden rezistor v paralelním nastavení selže (sepnutí), ostatní rezistory budou stále fungovat, a obvod zůstává neporušený.

Aplikace: Paralelní spojení se používají, když chcete snížit celkový odpor v obvodu, nebo když potřebujete zajistit, aby selhání jednoho rezistoru neovlivnilo celý obvod.

V souhrnu, sériová (sériová) spojení rezistorů přidávají odpor a udržují stejný proud, zatímco paralelní spojení rezistorů snižují odpor a dělí proud. Tyto dvě typy spojení jsou základní pro návrh obvodů a určení, jak rezistory interagují v těchto obvodech.