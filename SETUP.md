# DSP Course Setup Guide

This guide explains how to start the repository and run the DSP notebooks locally.

## Prerequisites

- Python 3.10 or newer
- Jupyter Notebook or VS Code with Jupyter support
- Git

## Install the environment

From the repository root:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
python -m ipykernel install --user --name dsp --display-name "Python (DSP)"
```

For Linux/macOS:

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
python -m ipykernel install --user --name dsp --display-name "Python (DSP)"
```

## Launch the notebooks

```bash
jupyter notebook
```

Open files from `notebooks/`, `homework/`, or the linked course material.

## Repository structure

- `README.md` — course overview and weekly map
- `syllabus/` — English and French syllabi
- `lectures/` — course notes and slides
- `workshops/` — laboratory activities
- `homework/` — assignments and STM32 examples
- `projects/` — capstone project material
- `notebooks/` — weekly Jupyter notebooks
- `stm32/` — embedded DSP examples
- `references/` — recommended references
- `images/` — course diagrams
- `scripts/` — repository validation utilities

## Validate notebooks

Run the structural and syntax validation from the repository root:

```bash
python scripts/validate_notebooks.py
```

This check verifies every notebook JSON document and compiles every Python code cell.
