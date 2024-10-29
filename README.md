# Projet de Prédiction et Classification des Billets

Ce projet vise à prédire et classifier des billets en fonction de leurs caractéristiques géométriques afin de distinguer les billets authentiques des faux. Utilisant des modèles de machine learning supervisés et non supervisés, le projet comprend une analyse approfondie et une documentation détaillée des choix méthodologiques et des résultats obtenus.

## Objectifs

1. **Prédiction avec un Modèle Supervisé** :
   - Imputer des valeurs manquantes par régression linéaire.
   - Vérifier et interpréter les hypothèses du modèle (colinéarité, homoscédasticité, normalité des résidus).
   - Évaluer la pertinence des variables et interpréter les coefficients pour comprendre les relations entre caractéristiques des billets.

2. **Classification des Billets avec un Modèle de Machine Learning** :
   - Implémenter et ajuster un modèle supervisé pour classer les billets.
   - Utiliser des techniques de validation croisée et la courbe ROC pour évaluer la robustesse.
   - Justifier le modèle final et interpréter les probabilités de prévision.

3. **Segmentation des Billets avec Clustering** :
   - Appliquer le clustering non supervisé pour regrouper les billets et analyser les clusters.
   - Justifier le nombre de clusters et interpréter chaque groupe.

## Contenu du Notebook

Le notebook contient une analyse détaillée, divisée en plusieurs sections :

1. **Exploration et Préparation des Données** :
   - Chargement, exploration, traitement des valeurs manquantes et vérification des types de données.
   - Prétraitement incluant la normalisation et l’encodage des variables.

2. **Analyse Exploratoire (EDA)** :
   - Visualisation des distributions des variables et analyse des corrélations pour comprendre les relations entre caractéristiques.

3. **Modélisation et Évaluation des Modèles** :
   - Implémentation de modèles de régression pour l'imputation et la prédiction.
   - Utilisation de modèles de classification avec validation croisée et optimisation.
   - Application de méthodes de clustering pour la segmentation, avec visualisation et interprétation des clusters.

4. **Validation des Modèles et Optimisation** :
   - Validation croisée, GridSearch et évaluation des performances avec des métriques adaptées.
   - Comparaison des modèles pour sélectionner la meilleure solution.

## Technologies et Bibliothèques Utilisées

- **Python** pour l'implémentation des analyses et des modèles.
- **Bibliothèques principales** :
  - `pandas`, `numpy` : manipulation et analyse des données.
  - `matplotlib`, `seaborn` : visualisation des données.
  - `scikit-learn` : modélisation et validation.
  - `statsmodels` : régression et vérification des hypothèses statistiques.


## Résultats et Interprétation

Les résultats finaux permettent de comprendre les caractéristiques distinctives des billets authentiques par rapport aux faux, tout en fournissant un modèle de classification fiable.


## Auteurs et Contributeurs

Projet réalisé dans le cadre d'une la formation Data Analyst. Les contributions et suggestions d’amélioration sont les bienvenues.
Merci
