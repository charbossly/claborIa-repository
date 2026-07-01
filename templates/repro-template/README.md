# Repro template

Gabarit minimal pour un benchmark ou un PoC reproductible. À cloner dans
[`../../benchmarks/`](../../benchmarks) et à étoffer au fur et à mesure.

## Arborescence cible

```
mon-benchmark/
├── README.md          # protocole, résultats, limites
├── Makefile            # cible `reproduce` qui rejoue tout en une commande
├── data/                # données ou scripts de téléchargement (non versionné si lourd)
├── src/                 # code d'évaluation
└── results/             # sorties, tableaux, logs
```

## Principe

`make reproduce` doit suffire, de zéro, à retrouver les résultats annoncés.
