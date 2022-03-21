# PVA2 - Programování a vývoj aplikací
## Cvičení 12: OOP

### 1
Deklarujte třídu zaměstnanec. Ve třídě mějte definované

*vlastnosti:*

* osobní číslo
* jméno
* příjmení
* plat
* pozice
* počet dnů dovolené (nárok 25)


*metody:*
výpis - zobrazí _Zaměstnanec jméno příjmeni pracuje na pozici n_
výběr dovolené - parametricky udávané množství dnů
změna mzdy - parametricky udávaná nová výše mzdy.

### 2
Vytvořte tři různé objekty, kde jedním z nich naplníte své osobní údaje.

### 3
Ve třídě zaměstnanec sestavte převod na řetězec. Výsledek bude zobrazovat ve tvaru _Zaměstnanec jméno příjmeni pracuje na pozici n_


### 4
Zapracujte do výběru dovolené kontrolu počtu zbývajících dnů a nedovolte zaměstnanci vybrat více, než je jeho zůsatek.
Vyzkoušejte vybrat dovolenou v délce 5,7,15 a 10 dnů.


### 5
Rozšiřte třídu zaměstnanec o konstruktor. Povinnými atributy bude osobní číslo, příjmení výše platu. Nezapomeňte upravit vytváření objektů.

### 6
Definujte novou třídu osoba. Třída osoba bude nadřazená třídě zaměstnanec a bude mít evidovány základní vlastnosti jméno a příjmení.

### 7
a) Definujte novou třídu vedouci. Třída vedoucí bude podřízená třídě zaměstnanec.

b) Ve třídách deklarujte metodu Výpis. Každá třída bude zobrazovat jiný výstup:

Osoba: _Osoba jméno příjmeni_
Zaměstnanec: _Zaměstnanec jméno příjmeni pracuje na pozici n_
Vedoucí: _Vedoucí jméno příjmeni pracuje na pozici n_

c) Pro každý objekt zavolejte metodu výpis
