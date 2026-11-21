# Guide de configuration du cours DSP

Ce guide explique comment démarrer avec le dépôt et exécuter les notebooks DSP localement.

## Prérequis

- Python 3.10 ou plus récent
- Jupyter Notebook ou VS Code avec prise en charge de Jupyter
- Git

## Installation depuis les dépendances du dépôt

Installez toutes les bibliothèques nécessaires depuis la racine :

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
python -m ipykernel install --user --name dsp --display-name "Python (DSP)"
```

## Environnement recommandé

Utilisez un environnement virtuel, par exemple :

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
python -m ipykernel install --user --name dsp --display-name "Python (DSP)"
```

Sous PowerShell Windows :

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
python -m ipykernel install --user --name dsp --display-name "Python (DSP)"
```

## Lancer les notebooks

Depuis la racine du dépôt :

```bash
jupyter notebook
```

Ensuite, ouvrez les fichiers du dossier `notebooks/`.

## Structure du dépôt

- `README.md` — vue d’ensemble du cours et page d’accueil
- `syllabus/` — syllabus et planning hebdomadaire
- `lectures/` — notes de cours et diapositives
- `workshops/` — supports de laboratoire et d’ateliers
- `homework/` — devoirs et exercices
- `projects/` — projets et livrables du projet final
- `notebooks/` — notebooks Jupyter utilisés pour le travail en classe
- `stm32/` — exemples DSP embarqués sur STM32
- `references/` — documentation et lectures recommandées
- `images/` — schémas et ressources visuelles

## Parcours d’apprentissage conseillé

1. Lisez le syllabus.
2. Consultez le notebook correspondant.
3. Complétez l’atelier ou le devoir associé.
4. Validez les résultats avec des graphiques et analyses.
5. Passez au module suivant.

## Remarques

Ce dépôt est conçu pour soutenir à la fois la théorie et la mise en pratique. Les notebooks doivent servir de documents de travail principaux pour les exercices et la compréhension des concepts.

## Validation des notebooks

Depuis la racine du dépôt :

```bash
python scripts/validate_notebooks.py
```

Ce contrôle vérifie le JSON de chaque notebook et compile toutes les cellules Python.
