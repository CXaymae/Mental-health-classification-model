# Mini-Projet IA (Classification): Santé Mentale (Sautes d'humeur)

## Objectif
Le mini-projet vise à créer et comparer les performances de plusieurs modèles de classification en appliquant l'apprentissage automatique sur un ensemble de données concernant la santé mentale. Vous utiliserez Python et ses bibliothèques d'apprentissage automatique pour ce projet.

## Organisation et Déroulement
- **Date de Présentation:** Mercredi 22 mai 2024
- **Format:** Jupyter Notebook
- **Fichier à Remettre:** Notebook (.ipynb) avec cellules Markdown pour expliquer chaque étape.

## Ensemble des Données (Data Set)
Les données proviennent d'une enquête sur la santé mentale, comprenant des données médicales et démographiques sur différentes nationalités et leurs niveaux de sautes d'humeur (faible, moyenne, élevée).

## Spécifications Techniques
- **Langage:** Python
- **Environnement:** Jupyter Notebook
- **Packages Requis:** numpy, pandas, matplotlib (ou seaborn), scikit-learn

## Spécifications Fonctionnelles
### 1. Compréhension des Données
- Chargement et exploration initiale des données.
- Description des statistiques et visualisation pour comprendre les corrélations potentielles.

### 2. Nettoyage des Données
- Détection et suppression des doublons.
- Traitement des valeurs manquantes avec justification des méthodes utilisées.

### 3. Transformation des Données
- Suppression d'attributs non discriminants.
- Création de nouveaux attributs pertinents si nécessaire.
- Normalisation des valeurs numériques et conversion des attributs catégoriels en numériques.

### 4. Création et Validation des Modèles
- Création de modèles de classification (k-NN, Arbres de Décision, Régression Logistique, SVM).
- Optimisation des hyperparamètres avec validation croisée.
- Évaluation des performances (Accuracy, Précision, Rappel, F1-Score) et sélection du meilleur modèle.

### 5. Test du Modèle
- Application du meilleur modèle sur l'ensemble de test.
- Évaluation finale des performances avec matrice de confusion et mesures de performance.
