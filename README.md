# Labo 2

Petit dépôt de travail pour le laboratoire 2, avec:

- un script Python minimal dans `main.py`
- un notebook de traitement dans `traitement.ipynb`
- des données et captures dans `assets/`
- une trame de rapport LaTeX dans `rapport/`

## Structure

```text
.
├── assets/          # Images et fichiers CSV de mesures
├── rapport/         # Rapport LaTeX
├── main.py          # Point d'entrée Python
├── pyproject.toml   # Métadonnées et dépendances
├── traitement.ipynb # Notebook d'analyse
└── uv.lock          # Verrouillage des dépendances uv
```

## Prérequis

- Python 3.14+
- `uv` pour recréer l'environnement facilement

## Installation

```bash
uv sync
```

## Lancer le script

```bash
uv run python main.py
```

## Contenu du dépôt

Le dépôt mélange du code, des données expérimentales et une trame de rapport. Les assets sont relativement volumineux, mais aucun fichier ne dépasse la limite standard de GitHub.

## État actuel

- `main.py` est encore un squelette
- `traitement.ipynb` contient les notes de travail pour les exercices
- `rapport/` est une base de rapport LaTeX à compléter

## Bonnes pratiques GitHub

Le fichier `.gitignore` exclut déjà:

- l'environnement virtuel local
- les fichiers temporaires Python
- les checkpoints Jupyter
- les fichiers générés par LaTeX
- les fichiers locaux d'éditeur

## Publication

Exemple de commandes pour publier le dépôt sur GitHub:

```bash
git add .
git commit -m "Prepare repository for GitHub"
git branch -M main
git remote add origin <url-du-repo>
git push -u origin main
```

## Licence

Aucune licence n'est définie pour l'instant. Si tu veux rendre le projet réutilisable publiquement, il faudra en ajouter une (`MIT`, `Apache-2.0`, etc.).
