# Projet : Détection des Fissures (Crack Detection)

## Introduction

Ce projet a pour but de détecter automatiquement les fissures sur des surfaces en béton à l’aide d’un modèle de réseau de neurones convolutif (CNN).  
Les images sont classées en deux catégories : **avec fissures** et **sans fissures**.

## Données

- Dataset : [Surface Crack Detection (Kaggle)](https://www.kaggle.com/datasets/arunrk7/surface-crack-detection/data)
- 40 000 images (227x227 pixels), réparties à parts égales entre les deux classes.

## Étapes du projet

1. Préparation des données (train, validation, test)
2. Conception et entraînement du modèle
3. Évaluation des performances

## Installation des dépendances

Pour installer les bibliothèques nécessaires, exécutez :

```bash
pip install -r requirements.txt
