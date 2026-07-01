# Benchmarks

L'unité atomique de réputation de ClaborIA. Chaque benchmark évalue des modèles
ouverts sur des données ouvertes, avec un protocole reproductible.

## Structure d'un benchmark

Un sous-dossier par benchmark, cloné depuis [`../templates/repro-template/`](../templates/repro-template).
Chaque benchmark DOIT fournir :

- un protocole documenté,
- un `make reproduce` qui rejoue tout en une commande,
- un leaderboard (tableau de résultats),
- les liens repo / paper.

## Public / privé

Le champ `visibility` du frontmatter (`public` ou `private`) indique si le
benchmark est prêt à être partagé ou encore en cours de validation.
