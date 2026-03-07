Student Performance Regression

Ce projet analyse les facteurs qui influencent la note finale d’élèves à l’aide d’un modèle de régression linéaire en Python.

Objectif

L’objectif du projet est de prédire la note finale d’un élève (G3) à partir de plusieurs variables académiques et personnelles, notamment :

* le temps d’étude
* le nombre d’absences
* les échecs scolaires précédents
* les notes intermédiaires (G1 et G2)

Dataset

Les données utilisées proviennent du **Student Performance Dataset** disponible sur le UCI Machine Learning Repository.

Le jeu de données contient :

* 395 observations (élèves)
* 33 variables décrivant des caractéristiques académiques, sociales et personnelles

Méthodologie

Le projet suit les étapes classiques d’un workflow d’analyse de données :

1. Chargement et nettoyage des données avec pandas
2. Analyse exploratoire des données (distributions et corrélations)
3. Préparation des variables pour le modèle
4. Séparation des données en ensemble d’entraînement et de test
5. Entraînement d’un modèle de régression linéaire avec scikit-learn
6. Évaluation du modèle à l’aide de métriques statistiques

Analyses réalisées

* étude de la distribution des notes
* analyse des corrélations entre variables
* visualisation des relations entre certaines variables et la note finale
* entraînement et évaluation d’un modèle de régression linéaire

Résultats

Les résultats montrent que les notes intermédiaires (G1 et G2) sont les variables les plus fortement corrélées avec la note finale (G3).
Cela indique que les performances académiques précédentes sont les meilleurs indicateurs de la réussite finale d’un élève.

Technologies utilisées

* Python
* pandas
* NumPy
* Matplotlib
* scikit-learn

Auteur
Md Al Amin HOSSAIN
Projet réalisé dans le cadre d’un apprentissage personnel en analyse de données et statistiques appliquées.

