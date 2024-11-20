# ❤️ Heart Disease Prediction

## Description
Ce projet utilise des algorithmes de Machine Learning pour prédire la présence de maladies cardiaques chez des patients en fonction de leurs caractéristiques médicales et personnelles.  
L'objectif principal est de développer un modèle fiable qui peut être utilisé pour aider à la détection précoce des maladies cardiaques. 



## 📊 Dataset
- **Source** : [Kaggle Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset/data)
- **Caractéristiques principales** :
  - `age` : Âge du patient.
  - `sex` : Sexe du patient.
  - `cp` : Type de douleur thoracique.
  - `trestbps` : Tension artérielle au repos.
  - `chol` : Cholestérol sérique (mg/dl).
  - `thalach` : Fréquence cardiaque maximale atteinte.
  - Et bien d'autres...
- **Target** : Une variable binaire indiquant si une maladie cardiaque est présente (`1`) ou non (`0`).



## 🔍 Analyse et Approche
Voici les étapes principales du projet :
1. **Exploration des données** 
   - Analyse descriptive des données (distributions, statistiques).
   - Gestion des valeurs manquantes et traitement des anomalies.
2. **Visualisation des données** 
   - Analyse des corrélations entre les caractéristiques.
   - Visualisation des variables clés (par exemple, âge, cholestérol, fréquence cardiaque).
3. **Préparation des données** 
   - Normalisation et standardisation des données.
   - Encodage des variables catégoriques.
   - Division des données en ensembles d'entraînement et de test.
4. **Modélisation** 
   - Algorithmes utilisés :
     - Random Forest.
     - Logistic Regression.
     - Support Vector Machine (SVM).
   - Évaluation avec des métriques comme l'accuracy, le F1-score et la matrice de confusion.
5. **Optimisation** 
   - Ajustement des hyperparamètres (GridSearchCV, RandomSearchCV).
   - Analyse des performances.



## 🏆 Résultats
- **Modèle le plus performant** : Random Forest Classifier.
- **Précision moyenne** : 88%.
- **Insights clés** :
  - La fréquence cardiaque maximale (`thalach`) est fortement corrélée avec la maladie.
  - Le cholestérol n'est pas toujours un facteur décisif selon les analyses.


## 🛠️ Technologies et Librairies
- **Langage** : Python 
- **Librairies principales** :
  - `pandas` : Manipulation des données.
  - `numpy` : Calculs numériques.
  - `matplotlib` & `seaborn` : Visualisation des données.
  - `scikit-learn` : Implémentation des algorithmes de Machine Learning.

# A bientôt !
