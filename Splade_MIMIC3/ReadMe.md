**txt_clean** : Les comptes rendus extraits de MIMIC3 dont j'ai enlevé des séquences récurrentes de caractères inutiles
**Vectors_all** : La vectorisation de chaque document avec Splade
**Vectors_all_tri_poids** : La même vectorisation mais triée par poids

A noter qu'il est possible, comme l'a dit Adam la dernière fois, que dans le cas de Splade il ne faille pas juger la qualité du résultat en fonction de quels termes ont les plus grands poids, mais plutôt si cette vectorisation permet de retrouver le document si on lui donne une requête qui lui correspond, car Splade a bien marché lorsque je l'ai utilisé pour faire la similarité entre une requête et les documents.