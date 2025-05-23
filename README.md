  # detection_precoce_troubles_sante_mentale

## Detection Précoce des Troubles de Santé Mentale

## Table des Matières

- [Aperçu](#aperçu)
- [Prise en Main](#prise-en-main)
  - [Prérequis](#prérequis)
  - [Installation](#installation)
  - [Utilisation](#utilisation)
- [Objectifs du Projet](#objectifs-du-projet)
- [Datasets Utilisés](#datasets-utilisés)
- [Modèles Implémentés](#modèles-implémentés)
- [Métriques d'Évaluation](#métriques-dévaluation)
- [Fonctionnalités](#fonctionnalités)

## Aperçu

Le projet **detection_precoce_troubles_sante_mentale** permet aux développeurs et chercheurs de s'attaquer aux problèmes de santé mentale grâce à des solutions novatrices basées sur les données.

### Pourquoi detection_precoce_troubles_sante_mentale ?

Ce projet facilite la détection précoce des problèmes de santé mentale, améliorant la sensibilisation des utilisateurs et favorisant des interventions opportunes. Les fonctionnalités principales incluent :

 **Framework Complet** : Une approche structurée pour analyser les données de santé mentale.

 **Notebooks Interactifs** : Outils pratiques pour explorer et évaluer les modèles d'apprentissage automatique.

 **Préparation des Données** : Processus rationalisés pour nettoyer et équilibrer les datasets afin d'améliorer la précision.

 **Évaluation des Modèles** : Frameworks robustes pour évaluer les performances des classificateurs par validation croisée.

 **Outils de Visualisation** : Interprétabilité améliorée des résultats pour soutenir la prise de décision éclairée.

## Prise en Main

### Prérequis

Ce projet nécessite les dépendances suivantes :

**Langage de Programmation** : JupyterNotebook

### Installation

Construisez detection_precoce_troubles_sante_mentale à partir du source et installez les dépendances :

1. **Clonez le dépôt** :
```bash
git clone https://github.com/abramezzakhi/detection_precoce_troubles_sante_mentale
```

2. **Naviguez vers le répertoire du projet** :
```bash
cd detection_precoce_troubles_sante_mentale
```
### Utilisation

Exécutez le projet avec :

```bash
jupyter notebook
```


## Objectifs du Projet

### Objectifs Principaux

- **Classification binaire** : Distinction entre contenus dépressifs et non-dépressifs
- **Classification multiclasse** : Identification de troubles mentaux spécifiques (Anxiété, BPD, Bipolaire, Dépression, Schizophrénie)
- **Détection de contenu suicidaire** : Classification des contenus à risque
- **Analyse comparative** : Évaluation de différents algorithmes de machine learning

## Datasets Utilisés

### 1. Reddit Depression Dataset
- **Source** : Kaggle
- **Taille** : 85,170 entrées
- **Structure** : Classification binaire (Dépressif/Non-dépressif)
- **Distribution** : Parfaitement équilibrée (42,585 échantillons par classe)

### 2. Mental Disorders Identification Dataset
- **Source** : Reddit (Kaggle)
- **Taille** : 50,000 entrées
- **Classes** : 5 troubles mentaux
  - Anxiety (10,000 échantillons)
  - BPD (10,000 échantillons)
  - Bipolar (10,000 échantillons)
  - Depression (10,000 échantillons)
  - Schizophrenia (10,000 échantillons)

### 3. Dataset Combiné Final
- **Taille** : 23,974 entrées
- **Classes** :
  - Depression (10,652 échantillons)
  - Normal (10,652 échantillons)
  - Anxiety (2,670 échantillons)

## Modèles Implémentés

### Algorithmes de Machine Learning

1. **Support Vector Machine Linéaire (LinearSVC)**
2. **AdaBoost (Adaptive Boosting)**
3. **Random Forest**
4. **Régression Logistique**
5. **Naive Bayes Multinomial**

## Métriques d'Évaluation

### Indicateurs de Performance

- **Précision (Precision)** : Proportion de vrais positifs parmi les prédictions positives
- **Rappel (Recall)** : Proportion de vrais positifs parmi tous les cas positifs réels
- **Score F1** : Moyenne harmonique de la précision et du rappel
- **Exactitude (Accuracy)** : Proportion de prédictions correctes

## Fonctionnalités

### Caractéristiques Principales

- **Préprocessing avancé** : Nettoyage des données textuelles
- **Feature Engineering** : Extraction de caractéristiques pertinentes (TF-IDF, N-grams)
- **Validation croisée** : Évaluation robuste des modèles
- **Visualisation des résultats** : Graphiques 
- **Analyse comparative** : Comparaison des performances entre modèles






