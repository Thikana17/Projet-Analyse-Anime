# Projet Data Anime : Analyse de Données

Ce projet est une initiation à l'analyse de données avec Python. L'objectif était de prendre une liste brute d'animes et d'en tirer des informations claires grâce à des graphiques.

## Les fichiers du projet
- `Mon_Analyse.ipynb` : Le code Python (Notebook) avec tous les graphiques.
- `animes_clean.csv`: Le tableau de données que j'ai nettoyé et exporté.

## Ce que j'ai fait 

J'ai procédé en plusieurs étapes pour comprendre les données :

 1. Exploration et Correction
Au début, j'ai eu des problèmes avec les noms des colonnes (minuscules/majuscules). J'ai utilisé Python pour afficher la liste exacte des colonnes (`df.columns`) afin de trouver les bons noms comme `Nb_Episodes` et `Source`.

 2. Création de Graphiques (Visualisation)
J'ai créé plusieurs visuels pour répondre à des questions précises :
- La qualité globale (Histogramme) : J'ai vu que la majorité des animes de cette liste ont une très bonne note (autour de 8/10).
-  L'origine (Camembert) : Pour voir si les animes viennent de Mangas ou sont des créations originales.
- La durée vs la note (Nuage de points) : J'ai comparé le nombre d'épisodes avec la note. Conclusion : ce n'est pas parce qu'un anime est long qu'il est mieux noté (la plupart sont courts).

 3. Nettoyage des données 
J'ai remarqué que le fichier CSV de base s'ouvrait mal dans Excel (tout était mélangé). J'ai donc écrit un code pour sauvegarder une version propre (`animes_clean.csv`) en utilisant des points-virgules, pour qu'il soit lisible sur un Excel français.

##  Outils utilisés
- Langage: Python
- Logiciel : Jupyter Notebook
- Librairies : Pandas (pour les tableaux), Matplotlib & Seaborn (pour les images).
