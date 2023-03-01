# BatimentProject
La lecture des Notebooks se fait de maniére chronologique de 1 à 12.
- **Notebook "Partie 1"** : Extraction et sélection des données depuis les bases de données CEREMA (DVF) et BDNB + Création de la variable Etaban qui servira de clé de fusion entre les datasets.
- **Notebook "Partie 2"** : Identification des lots qui correspondent aux appartements pour obtenir une ligne par mutation d'appartement + Création de la variable cible qui déterminera si un bien a été revendu au moins une fois sur la période 2014-2021.
- **Notebook "Partie 3"** : Feature engineering sur la 1ère sélection de variables.
- **Notebook "Partie 4"** : Recherche des variables les plus significatives à présenter en data visualisation.
- **Notebook "Partie 5"** : Premières data visualisation.
- **Notebook "Partie 6 - Sélection de features pour modelisation par régression - Target = qty_of_mut"** : Utilisation de Lasso - Variance Threshold - SelectKBest.
- **Notebook "Partie 6 - Sélection de features pour modelisation par classification - Target = Revente"** : Utilisation de la RFE - SelectFromModel - SelectKbest.
- **Notebook "Partie 7"** : Premières tentatives de modélisation et optimisation du meilleur modèle obtenu.
- **Notebook "Partie 8"** : Tentatives de réduction de dimension par PCA/LDA.
- **Notebook "Partie 9"** : Feature engineering sur la 2ème sélection de variables.
- **Notebook "Partie 10"** : Data Visualisation de cette 2ème sélection de variables.
- **Notebook "Partie 11"** : Modélisation à partir des variables explicatives exclusivement liées aux caractéristiques du bâtiment. Optimisation du meilleur modèle obtenu.
- **Notebook "Partie 12"** : Modélisation en ajoutant deux variables créées à partir de variables issues de DVF: "durée_de_détention" et "evol_val". Optimisation du meilleur modèle obtenu.
