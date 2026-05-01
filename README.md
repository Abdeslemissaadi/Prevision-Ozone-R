# Prévision des concentrations d'Ozone

## Description du Projet
Ce projet porte sur la modélisation statistique et la prévision de la concentration d'ozone (O3) en milieu local. L'objectif est d'utiliser des variables climatiques pour prédire les seuils de pollution et améliorer la précision des modèles déterministes à grande échelle. 

Ce travail compare différentes techniques d'apprentissage automatique (Machine Learning) pour évaluer leur efficacité en termes de régression et de classification.

## Pipeline de Données
Le projet couvre l'intégralité du cycle de vie d'un projet de data science :
1. **Analyse Exploratoire (EDA)** : Visualisation des distributions, identification des asymétries et des corrélations.
2. **Feature Engineering** : Transformations logarithmiques et racines carrées pour stabiliser la variance ; création d'une variable cible binaire pour la classification.
3. **Modélisation Comparative** :
    - **Modèles Gaussiens** : Linéaire simple vs Quadratique.
    - **Classification** : Régression logistique (avec interactions) et arbres de décision (CART).
    - **Deep Learning** : Implémentation de réseaux de neurones (via `nnet`) pour tester la captation de relations non-linéaires complexes.
4. **Évaluation** : Utilisation de la RMSE, courbes ROC et AUC, et élagage des arbres pour optimiser la généralisation.

## Technologies Utilisées
- **Langage** : R
- **Packages principaux** : `tidyverse`, `FactoMineR` (ACP), `rpart` (Arbres), `glmnet` (Régression pénalisée), `nnet` (Réseaux de neurones), `pROC` (Évaluation).

## Points Forts et Compétences
- **Rigueur Statistique** : Comparaison systématique des modèles via ANOVA et RMSE.
- **Transparence** : Utilisation d'outils de visualisation (`ggplot2`, `gridExtra`) pour rendre les résultats compréhensibles.
- **Contrôle du Sur-apprentissage** : Application de techniques d'élagage pour améliorer la fiabilité des modèles.

---
*Ce projet démontre ma capacité à traiter des données environnementales et à sélectionner le modèle le plus adapté à une problématique de prédiction métier.*
