# Formation en Traitement du Signal Numérique (DSP)

![License](https://img.shields.io/badge/License-Educational-blue)
![Python](https://img.shields.io/badge/Python-3.10+-green)
![STM32](https://img.shields.io/badge/STM32-CMSIS--DSP-orange)
![Durée](https://img.shields.io/badge/Durée-14%20semaines-red)

## Vue d’ensemble

Une formation pratique de 14 semaines en traitement du signal numérique, couvrant la théorie, l’implémentation en Python et le DSP embarqué avec STM32.

## Structure du cours

```text
Semaines 1-2   Fondements
Semaines 3-4   Échantillonnage et systèmes LTI
Semaines 5-6   Analyse fréquentielle (Z, DTFT, DFT, FFT) partie 1
Semaine 7      Évaluation intermédiaire
Semaines 8-10  Analyse fréquentielle et filtres numériques
Semaine 11     CMSIS-DSP STM32 et DSP embarqué
Semaines 12-13 Évaluation pratique
Semaine 14     Révision finale et conclusion du projet
```

## Pour commencer

Suivez [SETUP-fr.md](./SETUP-fr.md) pour créer l’environnement Python et installer les dépendances.
Exécutez `python scripts/validate_notebooks.py` avant de publier des modifications de notebooks.

## Structure du dépôt

```text
.
├── syllabus/
├── lectures/
├── workshops/
├── homework/
├── projects/
├── notebooks/
├── stm32/
├── images/
└── references/
```

## Parcours hebdomadaire

| Semaine | Notebook principal | Pratique / évaluation |
|---|---|---|
| 1 | [dsp_notes_week01.ipynb](./notebooks/dsp_notes_week01.ipynb) | Introduction et applications |
| 2 | [dsp_notes_week02.ipynb](./notebooks/dsp_notes_week02.ipynb) | [Exercices semaines 1–2](./homework/hw_weeks_1_2.ipynb) |
| 3 | [dsp_notes_week03.ipynb](./notebooks/dsp_notes_week03.ipynb) | Échantillonnage et CAN |
| 4 | [dsp_notes_week04.ipynb](./notebooks/dsp_notes_week04.ipynb) | Systèmes LTI et convolution |
| 5 | [dsp_notes_week05.ipynb](./notebooks/dsp_notes_week05.ipynb) | Transformée en Z |
| 6 | [dsp_notes_week06.ipynb](./notebooks/dsp_notes_week06.ipynb) | Analyse de Fourier |
| 7 | [dsp_notes_week07.ipynb](./notebooks/dsp_notes_week07.ipynb) | QCM intermédiaire de 40 questions |
| 8 | [dsp_notes_week08.ipynb](./notebooks/dsp_notes_week08.ipynb) | [Pratique RIF](./notebooks/dsp_notes_week08_practice.ipynb) |
| 9 | [dsp_notes_week09.ipynb](./notebooks/dsp_notes_week09.ipynb) | [Pratique RII](./notebooks/dsp_notes_week09_practice.ipynb) |
| 10 | [dsp_notes_week10.ipynb](./notebooks/dsp_notes_week10.ipynb) | [Pratique d’implémentation](./notebooks/dsp_notes_week10_practice.ipynb) |
| 11 | [dsp_notes_week11.ipynb](./notebooks/dsp_notes_week11.ipynb) | [Complément DSP embarqué](./notebooks/dsp_notes_week_supp.ipynb) |
| 12 | [dsp_notes_week12.ipynb](./notebooks/dsp_notes_week12.ipynb) | Évaluation pratique – Partie 1 |
| 13 | [dsp_notes_week13.ipynb](./notebooks/dsp_notes_week13.ipynb) | Évaluation pratique – Partie 2 |
| 14 | [dsp_notes_week14.ipynb](./notebooks/dsp_notes_week14.ipynb) | Révision finale et projet |

Les exemples [RIF STM32](./homework/stm32f407vg_fir_example.ipynb) et [RII STM32](./homework/stm32f407vg_iir_example.ipynb) complètent les semaines 11 à 13.

## Outils

- Python
- NumPy
- SciPy
- Matplotlib
- Jupyter
- STM32CubeIDE
- CMSIS-DSP
- Visual Studio Code

## Références recommandées

- Oppenheim & Schafer
- Proakis & Manolakis
- Richard Lyons
