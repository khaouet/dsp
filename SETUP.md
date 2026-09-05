# Guide de configuration du cours DSP

Ce guide explique comment démarrer avec le dépôt et exécuter les notebooks DSP localement.

## Prérequis

- Python 3.10 ou plus récent
- Jupyter Notebook ou VS Code avec prise en charge de Jupyter
- Git

## Paquets Python recommandés

Installez la pile scientifique principale :

```bash
pip install numpy scipy matplotlib jupyter notebook
```

Optionnel mais utile :

```bash
pip install pandas seaborn
```

## Environnement recommandé

Utilisez un environnement virtuel, par exemple :

```bash
python -m venv .venv
source .venv/bin/activate
pip install numpy scipy matplotlib jupyter notebook
```

Sous PowerShell Windows :

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install numpy scipy matplotlib jupyter notebook
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
