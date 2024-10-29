# Prédiction du nombre mensuel de passagers aériens

Ce projet vise à prédire le nombre mensuel de passagers internationaux d'une compagnie aérienne sur une période de 12 ans, allant de janvier 1949 à décembre 1960, avec un total de 144 observations.
## Description du problème
La compagnie aérienne souhaite prédire le nombre de passagers mensuels afin d'optimiser ses opérations, y compris la planification des vols et la gestion des ressources. Ce projet utilise des techniques de séries temporelles pour réaliser ces prédictions.

## Analyse des données
Les données utilisées pour ce projet contiennent le nombre de passagers mensuels. Diverses analyses exploratoires ont été effectuées, notamment :
- **Graphique linéaire :** Visualisation des tendances au fil du temps.
- **Décomposition multiplicative :** Analyse des composantes saisonnières.
- **Diagramme de densité :** Visualisation de la distribution des passagers.
- **Box and Whisker Plots :** Identification des valeurs aberrantes et de la variation.

## Modèles utilisés
1. **ARIMA (AutoRegressive Integrated Moving Average) :**
   - Utilisation du test Augmented Dickey-Fuller (ADF) pour évaluer la stationnarité.
   - Application de deux niveaux de différenciation pour rendre la série stationnaire.
   - Sélection des paramètres AR et MA à l'aide des graphiques ACF et PACF.
   - RMSE obtenu : 43.53.

2. **Réseaux de Neurones Artificiels (ANN) :**
   - Description de l'architecture utilisée et des hyperparamètres choisis.
   - Résultats de la performance du modèle.

3. **Modèle LSTM (Long Short-Term Memory) :**
   - Description de l'architecture LSTM et de son fonctionnement.
   - Performance et évaluation des résultats.

## Comparaison des modèles
Une comparaison des performances des modèles a été réalisée en utilisant le RMSE comme métrique principale.
