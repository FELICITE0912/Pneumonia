# 🫁 Détection et classification de la pneumonie à partir de radiographies thoraciques


## 🎯 Objectif du projet qwem


L’objectif de ce projet est de développer un modèle d’intelligence artificielle capable d’analyser des radiographies thoraciques (Chest X-ray) afin de détecter automatiquement la présence de pneumonie.
Ce travail s’inscrit dans le domaine de la santé numérique et vise à :
- Identifier les caractéristiques visuelles associées à la pneumonie
- Automatiser un diagnostic préliminaire à partir d’images médicales
- Évaluer les performances des modèles de deep learning dans un contexte réel

  
## 📂 Données utilisées
Les données proviennent du dataset Chest X-Ray Images (Pneumonia) disponible sur Kaggle.
#### 🔹 Description
Environ 5 800 images au format JPEG
Deux classes :
- NORMAL : poumons sains
- PNEUMONIA : poumons infectés
#### 🔹 Organisation
Les données sont réparties en trois ensembles :
- Train (entraînement)
- Validation
- Test
Cette séparation garantit une évaluation fiable des performances du modèle.

## 🔄 Méthodologie

Le projet a été réalisé selon une approche inspirée de CRISP-DM :

#### 1. Compréhension du problème
Analyse du contexte médical, 
Définition de l’objectif de classification
#### 2. Exploration des données
Visualisation des radiographies, 
Analyse de la distribution des classes
#### 3. Préparation des données
Redimensionnement des images, 
Normalisation des pixels, 
Encodage des labels
#### 4. Augmentation des données (Data Augmentation)
Rotation; 
Zoom
#### 5. Modélisation
Conception d’un réseau de neurones convolutif (CNN), 
Entraînement sur les données d’entraînement, 
Ajustement des hyperparamètres
#### 6. Évaluation
Accuracy, 
Précision, 
Recall, 
F1-score, 
Matrice de confusion

## 📈 Résultats
Les analyses et la modélisation ont permis de développer un système capable de classifier les radiographies en pneumonie ou normal.

## 🔍 Analyse
- Bon niveau de performance globale
- Bonne capacité de détection des cas de pneumonie
- Impact possible du déséquilibre des classes

## 📊 Visualisations
Courbes d’apprentissage (loss et accuracy);
Matrice de confusion. 
Ces éléments permettent d’identifier :
- Les points forts du modèle
- Les axes d’amélioration

  
## 🧠 Conclusion
Ce projet a permis de développer des compétences en :
- Analyse et traitement d’images médicales
- Apprentissage profond (Deep Learning)
- Conception et entraînement de modèles CNN
- Évaluation de modèles de classification


## 🛠️ Technologies utilisées
- Python
- NumPy
- Pandas
- Matplotlib
- TensorFlow / Keras
- Scikit-learn

## 👥 Travail en équipe

Projet réalisé en collaboration avec des camarades de classe dans le cadre de notre fin du programme.

## 🚀 Améliorations apportées

Contrairement à une approche de base, plusieurs améliorations ont déjà été mises en place dans ce projet :
- Utilisation de techniques de Data Augmentation pour améliorer la généralisation
- Optimisation du modèle CNN
- Ajustement des hyperparamètres
- Amélioration de la performance globale du modèle

