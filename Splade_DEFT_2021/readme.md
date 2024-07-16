- **txt** : Les fichiers originels de DEFT 2021
- **txt_trad** : La traduction de certains documents de DEFT2021 en anglais en utilisant le modele OPUS
- **txt_trad_vectorized3** : Chaque fichier contient des passages d'un même document original, qui ont été vectorisés chacun de leur coté à cause d'une restriction de taille de Splade
- **txt_trad_vectorized_all** : Dans chaque fichier, les termes ont été regroupés en une seule liste qui représentera tout le document. Si un terme se répète, on prend le plus grand score

Ensuite, dans le notebook, j'ai écrit une requête en me basant sur un des documents, je l'ai vectorisée avec Splade et calculé une similarité par produit scalaire avec chaque document. Le fichier qu'il était censé me retourner était le N° 190, mais il est tout en bas de la liste.