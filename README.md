# Miniprojet Titanic

Ce projet analyse le célèbre dataset du Titanic pour explorer les facteurs ayant influencé la survie des passagers.

## Structure du projet

- `code.ipynb` : Notebook principal contenant le code d'analyse, de nettoyage et de visualisation des données.
- `Titanic-Dataset.csv` : Jeu de données original.
- `titanic_clean.csv` : Jeu de données nettoyé après preprocessing.
- `journal.sh` : Script ou journal des commandes utilisées.
- `env_tit/` : Environnement virtuel Python pour isoler les dépendances.

## Installation

1. Clone ce dépôt.
2. Crée un environnement virtuel (optionnel si tu utilises déjà `env_tit`) :
   ```sh
   python3 -m venv env_tit
   source env_tit/bin/activate
   ```
3. Installe les dépendances nécessaires :
   ```sh
   pip install pandas numpy matplotlib seaborn jupyter
   ```

## Utilisation

1. Lance Jupyter Notebook :
   ```sh
   jupyter notebook
   ```
2. Ouvre le fichier [`code.ipynb`](code.ipynb) et exécute les cellules pour reproduire l'analyse.

## Étapes principales

- Chargement et exploration du dataset
- Nettoyage des données (gestion des valeurs manquantes, suppression de colonnes inutiles comme `Cabin`)
- Analyse exploratoire (statistiques, visualisations)
- Sauvegarde du dataset nettoyé

## Résultats

Le projet met en évidence les corrélations entre différentes variables (classe, sexe, âge, etc.) et la survie des passagers.

## Auteur

Alan

---

*Projet réalisé dans le cadre d'un exercice d'analyse de données avec Python et