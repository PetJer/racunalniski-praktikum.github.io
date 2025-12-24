# Učbenik za predmet Računalniški praktikum na FMF

## Kloniranje repozitorija

1. Predlagamo, da si v izbranem imeniku ustvarite virtualno okolje.

```shell
python -m venv .venv
```

2. Virtualno okolje aktivirajte.

| Windows       | `source .venv\Scripts\activate` |
|---------------|---------------------------------|
| MacOS / Linux | `source .venv/bin/activate`     |

3. Namestite Jupyter Book vsaj verzijo 2.

```shell
pip install "jupyter-book>=2.0.0"
```

4. Klonirajte repozitorij.

```shell
git clone git@github.com:racunalniski-praktikum/racunalniski-praktikum.github.io.git
```

> [!NOTE]
> Predlagamo, da vse spremembe delate na svoji veji.

## Zaganjanje projekta

1. Premaknite se v imenik `ucbenik`.

```shell
cd racunalniski-praktikum.github.io/ucbenik/
```

2. Zaženite Jupyter Book stran.

```shell
jupyter book start
```