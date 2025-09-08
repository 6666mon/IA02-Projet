# IA02 – Classification non linéaire grâce à l’IA avancée

📌 Description du projet

Ce projet a été réalisé dans le cadre du cours IA02 à l’UTT.
L’objectif était de développer et comparer des algorithmes d’intelligence artificielle non linéaires appliqués à deux types de données :

Partie 1 – Vision : Classification d’images avec le dataset CIFAR-10 (60 000 images en 10 classes).

Partie 2 – Signaux : Détection de chutes à partir de données de capteurs (dataset de signaux multidimensionnels).

# 🧩 Partie 1 – Classification d’images (CIFAR-10)

Analyse exploratoire du dataset (répartition, visualisations).

Implémentation et comparaison de :

2 algorithmes de Machine Learning classiques 

3 CNN avec différentes architectures.

1 CNN hybride combinant plusieurs approches.

Évaluation en termes de précision et de temps de calcul.

# 🧩 Partie 2 – Détection de chutes

Nous avons choisi le Dataset 2 : Fall Detection.

## Dataset :

757 échantillons de signaux multidimensionnels représentant la variation du champ électromagnétique.

Collectés sur 22 participants dans 4 environnements différents.

321 échantillons correspondent à des chutes.

## Objectif : Développer des algorithmes de classification binaires pour distinguer chute / non-chute.

Contraintes d’évaluation :

Entraînement sur les 22 participants et 4 environnements, puis test sur des signaux nouveaux.

Entraînement avec uniquement certains environnements/participants, et test sur des participants inconnus dans des environnements nouveaux.

## Travail réalisé :

Analyse des signaux et préparation des données.

Implémentation de plusieurs algorithmes de classification (DL).

Mise en place de techniques d’augmentation des données pour améliorer la robustesse.

Comparaison des performances sur données vues et non vues.

## 📊 Méthodologie

Prétraitement des données (normalisation, segmentation, transformations).

Test de différents modèles de Deep Learning.

Ajustement des hyperparamètres pour chaque modèle.

Évaluation : exactitude, F1-score, robustesse sur environnements/participants nouveaux.

## 🚀 Résultats attendus

Comparaison détaillée des performances des modèles.

Impact des techniques d’augmentation de données.

Discussion sur les limites et perspectives (généralisation, surapprentissage, robustesse).

## 👥 Équipe

Projet réalisé en binôme dans le cadre du cours IA02 – Printemps 2025
