# WasteImagePreprocessing

Pipeline de nettoyage, d'audit et de préparation d'un dataset d'images de déchets destiné à la classification automatique.

## Overview

La classification automatique des déchets nécessite un jeu de données fiable, cohérent et homogène.

Les images provenant de différentes sources peuvent présenter de nombreuses anomalies :

- résolutions et dimensions différentes ;
- formats de fichiers différents ;
- images RGB, grayscale ou RGBA ;
- images trop petites ;
- images corrompues ou illisibles ;
- images vides ;
- images dupliquées ;
- images placées dans la mauvaise classe ;
- déséquilibre entre les classes.

Ce projet fournit un pipeline permettant d'**auditer, nettoyer et standardiser** ces données avant leur utilisation pour entraîner un modèle de Machine Learning ou de Deep Learning.

---

## Objectives

Le projet couvre les principales étapes de préparation d'un dataset d'images :

- Explorer la structure et le contenu du dataset.
- Analyser la distribution des classes.
- Vérifier les dimensions et résolutions des images.
- Identifier les différents formats et extensions.
- Détecter les images corrompues ou illisibles.
- Détecter les images vides.
- Identifier les images trop petites.
- Analyser le nombre de canaux de chaque image.
- Détecter les doublons.
- Identifier les éventuelles erreurs de classification.
- Identifier les classes déséquilibrées.
- Redimensionner les images.
- Uniformiser les canaux.
- Normaliser les valeurs des pixels.
- Appliquer de la data augmentation.

---

## Dataset

Le dataset contient six catégories de déchets :

| Classe | Description |
|---|---|
| `cardboard` | Cartons ondulés, cartons plats, emballages en carton |
| `glass` | Bouteilles et objets en verre |
| `metal` | Canettes, boîtes et objets métalliques |
| `paper` | Feuilles, journaux et documents |
| `plastic` | Bouteilles et emballages plastiques |
| `trash` | Emballages de bonbons, tasses jetables et autres déchets |

---

## Project Structure

```text
waste-image-preprocessing/
│
├── notebooks/
│   └── atelier_prepa_donnees_images.ipynb
│
├── reports/
│   └── audit_images.csv
│
├── data/
│   ├── raw/
│   │   ├── cardboard/
│   │   ├── glass/
│   │   ├── metal/
│   │   ├── paper/
│   │   ├── plastic/
│   │   └── trash/
│   │
│   └── cleaned/
│       ├── cardboard/
│       ├── glass/
│       ├── metal/
│       ├── paper/
│       ├── plastic/
│       └── trash/
│
└── README.md

```
## ✍️ Auteur

**Harouna MBAYE**
- GitHub : [@harounambaye](https://github.com/harounambaye)
- LinkedIn : [Harouna Mbaye](https://www.linkedin.com/in/harouna-mbaye-088926239/)
- Portfolio :[harouna-mbaye](https://harouna-mbaye.netlify.app/)
- Email : roonmbaye5@gmail.com
