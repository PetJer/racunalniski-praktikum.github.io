# Visual Studio Code

**Visual Studio Code (VSCode)** je [integrirano razvojno okolje](https://sl.wikipedia.org/wiki/Integrirano_razvojno_okolje), namenjeno predvsem razvijalcem programske opreme, saj omogoča urejanje izvorne kode programov.

:::{tip} Uporaba
- Pisanje programov v različnih programskih jezikih.
- Pisanje [Markdown](https://en.wikipedia.org/wiki/Markdown), [HTML](https://sl.wikipedia.org/wiki/HTML) in [LaTeX](https://en.wikipedia.org/wiki/LaTeX) datotek.
:::

## Namestitev

::::{tab-set}
:::{tab-item} Windows
:sync: win
Urejevalnik si namestite preko [uradne spletne strani](https://code.visualstudio.com/download).

![gif](static/gif.gif)
:::
:::{tab-item} Mac
:sync: mac
...
:::
:::{tab-item} Linux
:sync: lin
...
:::
::::

## Ustvarjanje tekstovne datoteke

::::{tab-set}
:::{tab-item} Windows
:sync: win
1. Uporabite tipko {kbd}`⊞ Win`, da odprete Windows iskalno vrstico.
2. V iskalno vrstico vpišite `vscode`.
3. Odprite aplikacijo **Visual Studio Code**.
4. Uporabite bližnjico {kbd}`Ctrl+N`, da ustvarite novo datoteko.
5. Zapišite poljubno besedilo.
6. Uporabite bližnjico {kbd}`Ctrl+S`, da shranite datoteko.
7. Datoteki dodajte končnico `.txt`, da se bo datoteka shranila kot [golo besedilo](https://en.wikipedia.org/wiki/Plain_text).

![gif](static/gif.gif)
:::
:::{tab-item} Mac
:sync: mac
...
:::
:::{tab-item} Linux
:sync: lin
...
:::
::::

## Bližnjice na tipkovnici

Izkaže se, da pogosta uporaba tipkovnice in bližnjic na njej, pripomore k hitrejši in učinkoviti uporabi računalnika ter programov nameščenih na njem.

:::{attention} Bližnjice na izpitu
Uporaba bližnjic je zelo priporočena že zaradi hitrejšega reševanja izpita.
:::

:::::{tab-set}
::::{tab-item} Windows
:sync: win
### Splošni ukazi

|                               |                 |
|-------------------------------|-----------------|
| Ustvari novo datoteko         | {kbd}`Ctrl + N` |
| Odpri datoteko ali imenik     | {kbd}`Ctrl + O` |
| Shrani datoteko               | {kbd}`Ctrl + S` |
| Razveljavi zadnje dejanje     | {kbd}`Ctrl + Z` |
| Ponovi razveljavljeno dejanje | {kbd}`Ctrl + Y` |

:::{dropdown} 🛠️ Prikaz uporabe
![gif](static/gif.gif)
:::

### Urejanje z besedilom

|                              |                          |
|------------------------------|--------------------------|
| Kopiraj izbrano besedilo     | {kbd}`Ctrl + C`          |
| Izreži izbrano besedilo      | {kbd}`Ctrl + X`          |
| Prilepi izbrano besedilo     | {kbd}`Ctrl + V`          |
| Premakni vrstico gor ali dol | {kbd}`Alt + ↑/↓`         |
| Podvoji vrstico gor ali dol  | {kbd}`Alt + Shift + ↑/↓` |
| Izbriši trenutno vrstico     | {kbd}`Ctrl + Shift + K`  |

:::{dropdown} 🛠️ Prikaz uporabe
![gif](static/gif.gif)
:::

### Iskanje po besedilu

|                               |                         |
|-------------------------------|-------------------------|
| Išči po besedilu              | {kbd}`Ctrl + F`         |
| Išči po besedilu in zamenjaj  | {kbd}`Ctrl + H`         |
| Išči po datotekah             | {kbd}`Ctrl + Shift + F` |
| Išči po datotekah in zamenjaj | {kbd}`Ctrl + Shift + H` |

:::{dropdown} 🛠️ Prikaz uporabe
![gif](static/gif.gif)
:::

### Premikanje po besedilu

|                                |                    |
|--------------------------------|--------------------|
| Premakni se vzdolž cele besede | {kbd}`Ctrl + ←/→`  |
| Skoči na začetek vrstice       | {kbd}`Home`        |
| Skoči na konec vrstice         | {kbd}`End`         |
| Skoči na začetek dokumenta     | {kbd}`Ctrl + Home` |
| Skoči na konec dokumenta       | {kbd}`Ctrl + End`  |

:::{dropdown} 🛠️ Prikaz uporabe
![gif](static/gif.gif)
:::

### Označevanje besedila

Če med premikanjem po besedilu držimo tipko {kbd}`Shift`, označimo besedilo med začetkom in koncem premikanja.

:::{dropdown} 🛠️ Prikaz uporabe
![gif](static/gif.gif)
:::

::::
::::{tab-item} Mac
:sync: mac
...
::::
::::{tab-item} Linux
:sync: lin
...
::::
:::::

:::{hint} Bližnjice izven VSCode-a
Uporaba bližnjic seveda ni omejena na urejevalnike besedila, temveč jih lahko uporabljamo tudi v spletnih brskalnikih, na operacijskih sistemih idr.
Pri tem moramo biti pozorni na morebitne razlike v kombinacijah tipk, ki so odvisne od aplikacije.
:::

## Večkratni kurzorji

VSCode omogoča uporabo večih kurzorjev hkrati, kar dopušča učinkovitejšo urejanje datotek.

::::{tab-set}
:::{tab-item} Windows
:sync: win
|                                          |                         |
|------------------------------------------|-------------------------|
| Dodaj kurzor na mestu klika              | {kbd}`Alt` + levi klik  |
| Dodaj kurzor zgoraj ali spodaj           | {kbd}`Ctrl + Alt + ↑/↓` |
| Dodaj kurzor pri vseh rezultatih iskanja | {kbd}`Alt + Enter`      |

![gif](static/gif.gif)
:::
:::{tab-item} Mac
:sync: mac
...
:::
:::{tab-item} Linux
:sync: lin
...
:::
::::

(paleta-ukazov)=
## Paleta ukazov

Paleta ukazov je mesto, kjer lahko dostopate do vseh funkcionalnosti v VSCode-u.

:::{tip} Uporaba
- Izvajanje ukazov, ki nam zmanjšajo količino tipkanja.
- Urejanje nastavitev urejevalnika.
:::

Pokazali bomo primer uporabe za spreminjanje označenega besedila v velike začetnice.

::::{tab-set}
:::{tab-item} Windows
:sync: win
1. Odprite poljuben tekstovni dokument v VSCode-u.
2. Z uporabo tipkovnice ali miške izberite poljuben odsek besedila.
3. Uporabite bližnjico {kbd}`Ctrl+Shift+P`, da odprete paleto ukazov.
4. V paleto ukazov zapišite `upper`.
5. Prikazala se vam bo izbira za ukaz **Transform to Uppercase**, ki ga izvedete s tipko {kbd}`Enter`.

![gif](static/gif.gif)
:::
:::{tab-item} Mac
:sync: mac
...
:::
:::{tab-item} Linux
:sync: lin
...
:::
::::