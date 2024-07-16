Le notebook contient un moteur de recherche utilisant Splade sur un ensemble de papiers de recherche.
**pdfs** contient les papiers et **Abstracts** contient les résumés contenus dans les papiers.

- J'ai vectorisé les documents dans le dossier **Vectors_all** qui contient une liste de termes pondérés pour chaque document.
- J'ai récupéré des mots-clés procurés par certains des papiers.
- J'ai créé des requêtes à partir des mots-clés (appartenant au même papier) que j'ai vectorisées.
- Produit scalaire entre la requête et tous le documents

## Résultat
Pour chaque requête que j'ai essayée, **le document retourné en 1er était le bon**, et parfois ceux qui suivaient étaient des papiers très proches (ex. Splade, SpladeV2 et SparTerm).

On pourrait aussi essayer avec des variations sur les requêtes (remplacer par des synonymes etc.)

