# 📊 Préparer efficacement vos données avec Skrub

Ce dépôt accompagne l’article publié sur le blog de Stat4Decision :  
**“Préparer efficacement vos données : une solution Python pour le machine learning avec Skrub”**  
Il contient un **notebook Jupyter complet** illustrant les fonctionnalités clés de la bibliothèque [Skrub](https://skrub-data.org/).

## 🧰 Contenu du dépôt

- `skrub_tutorial.ipynb` : le notebook principal avec des exemples concrets
- `README.md` : ce fichier de documentation

## 🚀 Objectif

Skrub est une bibliothèque Python conçue pour faciliter la préparation de données tabulaires hétérogènes. Ce projet vous guide à travers les étapes suivantes :
- Chargement de jeux de données réels
- Nettoyage automatique avec `Cleaner`
- Vectorisation intelligente avec `TableVectorizer`
- Jointures floues avec `fuzzy_join`
- Construction d’un pipeline complet avec scikit-learn

## 🔧 Installation

Créez un environnement virtuel (recommandé), puis installez les dépendances :

```bash
pip install skrub pandas scikit-learn
```

Ou avec `conda` :

```bash
conda install -c conda-forge skrub pandas scikit-learn
```

## 📓 Utilisation

1. Lancez Jupyter :

```bash
jupyter lab
```

2. Ouvrez le fichier `skrub_tutorial.ipynb`
3. Exécutez les cellules pour explorer les fonctionnalités pas à pas

## 🧪 Jeu de données

Nous utilisons `fetch_employee_salaries`, un jeu de données intégré à Skrub.
Il s'agit d’un exemple réaliste contenant des colonnes numériques, catégorielles, et de texte.

## 📣 Pour aller plus loin

➡️ Lire l’article complet sur le blog de Stat4Decision :
https://www.stat4decision.com/fr/skrub-preparer-donnees-python-ml/

## 🤝 Contributeurs

* Emmanuel Jakobowicz

---

Ce dépôt est librement utilisable à des fins pédagogiques ou professionnelles.
N'hésitez pas à nous contacter pour un accompagnement sur vos projets Python et machine learning.
