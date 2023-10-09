# Prédiction du Gagnant de Matchs de Tennis

## Description du Projet
Ce projet vise à prédire les gagnants de matchs de tennis basés sur un jeu de données contenant des matchs ayant eu lieu entre 2016 et 2018.

## Processus

### 1. Nettoyage des Données
- **Vérification du Type de Variables** : Avant tout traitement, une inspection initiale a été réalisée pour s'assurer que les colonnes du jeu de données étaient du bon type. Les colonnes ont été converties au type approprié selon les besoins.
- **Analyse des Valeurs Manquantes** : Une exploration des valeurs manquantes a été réalisée pour identifier leur origine et décider des actions à entreprendre.
- **Duplication des Lignes** : Les lignes ont été dupliquées pour pouvoir effectuer des prédictions sur des matchs de tennis.

### 2. Préparation des Données pour la Modélisation
- **Sélection du Jeu de Test** : Les matchs ayant eu lieu entre 2016 et 2017 ont été utilisés comme ensemble d'entraînement, tandis que les matchs de 2017 à 2018 ont été utilisés comme ensemble de test.
- **Analyse de la Corrélation** : Une analyse de corrélation a été effectuée pour comprendre les relations entre différentes variables.
- **Encodage des Variables** : Les variables catégorielles ont été encodées pour être adaptées à l'entraînement des modèles.

### 3. Modélisation et Évaluation
- Différents modèles ont été entraînés et comparés sur différentes métriques.



