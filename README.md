# Projets Jedha Machine Learning
3 projets de Machine Learning : Supervisé régression, Supervisé classification, Non supervisé 

## Structure des dossiers

Les sources sont organisés de la manière suivante :
 - *root* :
   - *.gitignore* : configuration Git
   - *README.md* : documentation générale du projet 
   - *requirements.txt* : dépendances nécessaires à l'exécution du projet en local
 - *Supervised_ML* : deux exercices de ML supervisé Jedha
   - *Walmart* : projet d'EDA et de régression linéaire régularisée sur des données de chiffres de ventes
      - *correlation_matrix.png* : une des figures d'EDA
      - *FeaturesImportance_LassoModel.png* : une des figures du meilleur modèle 
      - *Projet_Walmart.ipynb* : Notebook d'exploration des données et de run de modèles de régression (contient les consignes Jedha du projet)
      - *Walmart_Store_sales.csv* : données brutes pour cet exercice
   - *Conversion_Rate* : projet de challenge machine learning, basé sur un exercice réel Kaggle de classification binaire sur des données unbalanced
      - *ConfusionMatrix_LogisticRegression.png* : une des figures du meilleur modèle
      - *EDA_ConcersionVSAge.png* : une des figures d'EDA
      - *conversion_data_test.csv* : données brutes pour cet exercice (pour la soumission au leaderboard)
      - *conversion_data_train.csv* : données brutes pour cet exercice
      - *Projet_Conversion_rate_EDA.ipynb* : Notebook d'exploration des données (contient les consignes Jedha du projet)
      - *Projet_Conversion_rate_models.ipynb* : Notebook de run des modèles de classification 
 - *Unsupervised_ML* : projet de clustering de données spatiales
   - *Uber* : 
     - *Baseline_KMeans5clusters.png* : une des figures du modèle baseline
     - *EDA_pickups_per_hour_and_month.png* : une des figures d'EDA
     - *Projet_Uber_EDA.ipynb* : Notebook d'exploration des données (contient les consignes Jedha du projet)
     - *Projet_Uber_models.ipynb* : Notebook d'exploration des données et de run des modèles 
     - *TileMap_perhour_and_weekday.png* : une des figures du meilleur modèle


## Environnement local

### Prérequis

- python 3.12.x

### Lien de téléchargement des fichiers bruts pour le projet Unsupervised_ML/Uber

- https://full-stack-bigdata-datasets.s3.eu-west-3.amazonaws.com/Machine+Learning+non+Supervis%C3%A9/Projects/uber-trip-data.zip