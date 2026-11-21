# Digital Signal Processing (DSP) Training

![License](https://img.shields.io/badge/License-Educational-blue)
![Python](https://img.shields.io/badge/Python-3.10+-green)
![STM32](https://img.shields.io/badge/STM32-CMSIS--DSP-orange)
![Duration](https://img.shields.io/badge/Duration-14%20Weeks-red)

## Overview

A 14-week hands-on Digital Signal Processing course covering theory,
Python implementation, and embedded DSP using STM32.

## Course Structure

```text
Weeks 1-2   Foundations
Weeks 3-4   Sampling & LTI Systems
Weeks 5-6   Frequency Analysis (Z, DTFT, DFT, FFT) Part 1
Week  7     Intermediate Evaluation
Weeks 8-10  Frequency Analysis and Digital Filters
Week 11     STM32 CMSIS-DSP and Embedded DSP
Weeks 12-13 Practical Evaluation
Week 14     Final Review and Capstone Wrap-up
```

## Getting Started

Follow [SETUP.md](./SETUP.md) to create the Python environment and install the dependencies.
Run `python scripts/validate_notebooks.py` before publishing notebook changes.

## Repository Structure

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

## Weekly Course Map

| Week | Main notebook | Practical / assessment |
|---|---|---|
| 1 | [dsp_notes_week01.ipynb](./notebooks/dsp_notes_week01.ipynb) | Introduction and DSP applications |
| 2 | [dsp_notes_week02.ipynb](./notebooks/dsp_notes_week02.ipynb) | [Weeks 1–2 exercises](./homework/hw_weeks_1_2.ipynb) |
| 3 | [dsp_notes_week03.ipynb](./notebooks/dsp_notes_week03.ipynb) | Sampling and ADC |
| 4 | [dsp_notes_week04.ipynb](./notebooks/dsp_notes_week04.ipynb) | LTI systems and convolution |
| 5 | [dsp_notes_week05.ipynb](./notebooks/dsp_notes_week05.ipynb) | Z-transform |
| 6 | [dsp_notes_week06.ipynb](./notebooks/dsp_notes_week06.ipynb) | Fourier analysis |
| 7 | [dsp_notes_week07.ipynb](./notebooks/dsp_notes_week07.ipynb) | 40-question intermediate MCQ |
| 8 | [dsp_notes_week08.ipynb](./notebooks/dsp_notes_week08.ipynb) | [FIR practice](./notebooks/dsp_notes_week08_practice.ipynb) |
| 9 | [dsp_notes_week09.ipynb](./notebooks/dsp_notes_week09.ipynb) | [IIR practice](./notebooks/dsp_notes_week09_practice.ipynb) |
| 10 | [dsp_notes_week10.ipynb](./notebooks/dsp_notes_week10.ipynb) | [Filter implementation practice](./notebooks/dsp_notes_week10_practice.ipynb) |
| 11 | [dsp_notes_week11.ipynb](./notebooks/dsp_notes_week11.ipynb) | [Supplementary embedded DSP](./notebooks/dsp_notes_week_supp.ipynb) |
| 12 | [dsp_notes_week12.ipynb](./notebooks/dsp_notes_week12.ipynb) | Practical evaluation – Part 1 |
| 13 | [dsp_notes_week13.ipynb](./notebooks/dsp_notes_week13.ipynb) | Practical evaluation – Part 2 |
| 14 | [dsp_notes_week14.ipynb](./notebooks/dsp_notes_week14.ipynb) | Final review and capstone |

The standalone [FIR STM32 example](./homework/stm32f407vg_fir_example.ipynb) and [IIR STM32 example](./homework/stm32f407vg_iir_example.ipynb) extend Weeks 11–13.

## Tools

- Python
- NumPy
- SciPy
- Matplotlib
- Jupyter
- STM32CubeIDE
- CMSIS-DSP
- Visual Studio Code

## Recommended References

- Oppenheim & Schafer
- Proakis & Manolakis
- Richard Lyons
