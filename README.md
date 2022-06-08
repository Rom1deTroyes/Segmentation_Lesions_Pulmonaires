---
created: 2022-06-08T09:12:09 (UTC +02:00)
tags: []
source: https://simplonline.co/briefs/de49feec-ea0b-4a4d-97b4-972dac84b261
author: 
---

![](https://simplonline.co/_next/image?url=https%3A%2F%2Fsimplonline-v3-prod.s3.eu-west-3.amazonaws.com%2Fmedia%2Fimage%2Fjpg%2Fcb4b9733-3fff-43d0-a1c7-e469e016b978.jpg&w=1280&q=75)

# Segmentation des lésions pulmonaires

Mohammed El Amine BECHAR

07.06.2022

## Contexte du projet

Ce brief a pour objectif de manipuler une architecture CNN pour réaliser la segmentation.

Dans ce brief, nous appliquons un apprentissage supervisé pour détecter les lésions pulmonaires à partir d’une image.

Challenges

- Maitriser l’architecture Unet
- Appliquer le Transfer Learning en utilisant la bibliothèque segmentation-models.

Phases de brief

### Partie 1 : Base de données

Pour aborder cette problématique, il est primordial d’avoir une DataSet. Pour cela, la DataSet se trouve sur : https://drive.google.com/file/d/1TVQ5a-IOdn95eAAT8QLVA45s8WBAW1re/view?usp=sharing

Par la suite, il faut développer les étapes suivantes :

- [ ] Charger les images.
- [ ] Penser à redimensionner les images selon le modèle souhaité.
- [ ] Splitter les données en données d’apprentissage, validation et test.
- [ ] Visualiser les images de CT et sa vérité terrain (segmentation manuelle).
- [ ] Appliquer la data augmentation.


### Partie 2 : Transfer Learning

Cette deuxième partie est réservée pour préparer le modèle de segmentation et d’appliquer un Transfer Learning votre architecture.

Calculer le F1-Score sur la base de test.


## Modalités pédagogiques

Le projet est réalisé individuellement.


## Critères de performance

- [ ] Un code python bien structuré, avec les commentaires nécessaires.
- [ ] Le choix de l’architecture du modèle.
- [ ] Évaluation des performances du modèle.


## Modalités d'évaluation

- [ ] Un rapport sur le projet réalisé qui explique les différentes étapes du code.
- [ ] Description des données (dans le rapport).
- [ ] Présentation de l'architecture utilisée (dans le rapport).
- [ ] Revue de code avec le formateur.


## Livrables

Un dépôt Github avec :
- [ ] Un dossier qui contient le nécessaire pour exécuter votre Notebook.
- [ ] Un Readme.md pour mettre en avant votre application.

