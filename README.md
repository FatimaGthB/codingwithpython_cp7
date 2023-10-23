# codingwithpython_cp7

Utilisez le web scraping pour collecter des données sur les 250 meilleurs films d'IMDb, puis analysez et visualisez ces données dans un Notebook Jupyter. Tout au long de ce point de contrôle, vous acquerrez une expérience pratique du web scraping, de l'analyse de données et des techniques de visualisation. De plus, vous vous entraînerez à modulariser votre code à l'aide de fonctions Python.

Configuration :

Assurez-vous que les bibliothèques suivantes sont installées dans votre Jupyter Notebook :
pip install beautifulsoup4 requests numpy pandas matplotlib


Créer un nouveau Notebook Jupyter dédié à ce point de contrôle.

Tâches :

#### 1. Web Scraping :

Fonction get_movie_details() :
   Concevoir une fonction qui récupère les détails suivants de la page des 250 meilleurs films d'IMDb (lien) :
Rang
Titre du film
Année de sortie
Note IMDb
Cette fonction doit retourner une liste de dictionnaires, où chaque dictionnaire représente un film.

#### 2. Analyse de données avec Numpy et Pandas :

   
Fonction create_dataframe(movie_details) :
   Avec la liste des détails du film, créez un DataFrame pandas.
Fonction average_rating(df) :
 Calcule et renvoie la note IMDb moyenne pour les 250 premiers films.
Fonction movies_per_decade(df) :
Renvoie un dictionnaire indiquant le nombre de films sortis chaque décennie.
Fonctions film le mieux noté(df) et film le moins bien noté(df) :
Identifient et renvoient les détails des films les mieux notés et les moins bien notés par IMDb, respectivement.


#### 3. Visualisation :

   
Fonction plot_rating_distribution(df) :
   Trace un histogramme qui visualise la distribution des classements IMDb parmi les 250 meilleurs films.
Fonction plot_movies_per_decade(df) :
 Affiche un diagramme à barres montrant le nombre de films de la liste des 250 premiers films sortis chaque décennie.

Documentation et présentation :

Utilisez des cellules markdown dans votre Jupyter Notebook pour :
Décrire votre approche.
Mettre en évidence les résultats intéressants.
Partager les défis rencontrés et la manière dont vous les avez surmontés.

Défis bonus :

Améliorez l'interaction avec l'utilisateur : Dans votre Jupyter Notebook, utilisez la fonction input() pour permettre aux utilisateurs d'indiquer la décennie qui les intéresse. Affichez uniquement les films de cette décennie avec leur classement IMDb.
Fonction plot_top_10_movies(df) : Concevoir une fonction permettant de visualiser les 10 meilleurs films dans un diagramme circulaire en fonction de leur classement IMDb.
