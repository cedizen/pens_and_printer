![Python](https://img.shields.io/badge/Python-blue?logo=python) ![Jupyter](https://img.shields.io/badge/Jupyter-orange?logo=jupyter) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

# Pens and Printer

Ce petit projet tourne autour d'un problème simple : choisir des stylos et une imprimante en respectant certaines contraintes (budget, quantités, etc.), et voir comment on peut le modéliser proprement.

L'objectif est d'illustrer une démarche de résolution de problème avec un peu de code et/ou des outils d'optimisation, plutôt que de rester sur un énoncé théorique.

## À propos du projet

À partir de données ou d'hypothèses de départ (prix, quantités, contraintes), le projet cherche à répondre à une question du type :

> Que peut-on acheter (stylos, imprimante) en respectant un budget donné, tout en maximisant ou en respectant certaines conditions ?

Selon la version du projet, cela peut être traité :
- par une approche “brute” en Python ;
- avec des outils d’optimisation ;
- ou simplement via une modélisation plus claire du problème.

## Ce qu'on trouve dans ce repo

- un notebook ou un script principal avec la résolution du problème ;
- éventuellement des fichiers de données (prix, contraintes, etc.) ;
- ce `README.md` pour expliquer l’idée générale.

Tu peux adapter cette section avec les vrais noms de fichiers, par exemple :

- `pens_and_printer.ipynb` : notebook principal ;
- `data/` : données éventuelles.

## Outils utilisés

Le projet utilise principalement :

- Python
- `pandas` si des données tabulaires sont manipulées
- éventuellement des bibliothèques d’optimisation ou de calcul
- Jupyter Notebook pour la partie interactive

À adapter selon les packages que tu utilises vraiment dans le code.

## Lancer le projet

1. Cloner le dépôt :

```bash
git clone https://github.com/cedizen/pens_and_printer.git
cd pens_and_printer
```

2. Créer un environnement virtuel si besoin :

```bash
python -m venv .venv
source .venv/bin/activate
```

Sous Windows :

```bash
.\.venv\Scripts\activate
```

3. Installer les dépendances (si un `requirements.txt` est présent) :

```bash
pip install -r requirements.txt
```

4. Lancer Jupyter Notebook ou exécuter le script :

```bash
jupyter notebook
# ou
python nom_du_script.py
```

## Objectif du projet

Le projet sert surtout d’exemple pour :

- poser clairement un problème avec contraintes ;
- le traduire en code / en modèle ;
- tester une façon de le résoudre de manière reproductible.

C’est un projet court, mais utile pour montrer une démarche de résolution pas à pas.

## Auteur

Projet réalisé par Cédric Berthezene.

GitHub : [cedizen](https://github.com/cedizen)
