
# Digital Signal Processing (DSP) Training Program – 14‑Week Syllabus

## Duration

**14 Weeks**

## Course Organization

- **Lecture:** 1.5 hours per week (21 hours total)
- **Workshop (Hands‑on Lab):** 3 hours every two weeks (6 workshops = 18 hours)
- **Homework / Assignments:** 2 hours per week (28 hours total)
- **Intermediate Evaluation:** 1 hour (Week 7) – 40‑question MCQ
- **Practical Evaluation:** 01 session × 1 hour (Weeks 12–13)
- **Final Revision & Capstone:** Week 14

**Total Contact/Guided Hours:** ~69 hours

---

## Weekly Schedule

| Week | Lecture (1.5 h) | Workshop (3 h, bi‑weekly) | Homework / Evaluation (2 h) |
|------|-----------------|---------------------------|----------------------------|
| **1** | Introduction to DSP, Signals, DSP Applications | — | Signal classification and DSP applications |
| **2** | Mathematical Foundations: Complex Numbers, Euler's Formula, Sinusoids | Python setup, Signal generation, Complex numbers | Python exercises on sinusoids |
| **3** | Sampling Theory, ADC, Nyquist, Quantization | — | Sampling and ADC exercises |
| **4** | Discrete‑Time Signals, LTI Systems, Convolution | Signal operations, Convolution, Moving‑average filter | Convolution exercises |
| **5** | Z‑Transform, ROC, Poles & Zeros | — | Z‑transform and stability analysis |
| **6** | Fourier Series, DTFT, Frequency Spectrum | FFT, Spectrum analysis, Audio processing | Spectrum interpretation |
| **7** | **Intermediate Evaluation (MCQ)** | — | **40 MCQ questions (1 hour)** covering Weeks 1–6 |
| **8** | DFT, FFT, Windowing, Spectral Leakage | FFT and Windowing exercises | FFT and windowing exercises |
| **9** | FIR and IIR Digital Filters | — | Digital filter design exercises |
| **10** | FIR/IIR Implementation and Filter Analysis | FIR/IIR implementation and filter analysis | Filter design and analysis |
| **11** | DSP Applications and STM32 CMSIS‑DSP | STM32 CMSIS‑DSP setup and basic implementation | Embedded DSP assignment and project proposal |
| **12** | **Practical Evaluation – Part 1** (lab‑based) | — | **Hands‑on DSP implementation** (1.5 h) |
| **13** | **Practical Evaluation – Part 2** (lab‑based) | — | **Hands‑on DSP implementation** (1.5 h) |
| **14** | Final Exam Revision | Capstone Project (Final Workshop) | Final report and presentation preparation |

---

## Workshops

1. Python & Signal Generation (Week 2)
2. Discrete Signals and Convolution (Week 4)
3. FFT and Spectrum Analysis (Week 6)
4. Digital Filter Design (Week 10)
5. STM32 CMSIS‑DSP Implementation (Week 11)
6. Final DSP Project (Week 14)

---

## Evaluation Breakdown

| Component | Weight | Details |
|-----------|--------|---------|
| Homework / Assignments | 20% | Weekly exercises and assignments |
| Intermediate Evaluation (MCQ) | 20% | 40 questions, 1 hour, covers Weeks 1–6 |
| Practical Evaluation (Weeks 12–13) | 30% | Hands‑on DSP implementation (two sessions) |
| Final Project | 20% | Capstone project with report and presentation |
| Class Participation | 10% | Attendance and engagement |

---

## Intermediate Evaluation Details (Week 7)

**Format:** 40 Multiple Choice Questions  
**Duration:** 1 hour  
**Coverage:** Topics from Weeks 1–6

### Topics Covered:

1. **Introduction to DSP** – definition, applications, signal classification.
2. **Mathematical Foundations** – complex numbers, Euler’s formula, sinusoids, phasors.
3. **Sampling Theory** – Nyquist theorem, aliasing, quantization, ADC.
4. **Discrete‑Time Signals & LTI Systems** – impulse/step signals, system properties, convolution, impulse response.
5. **Z‑Transform** – definition, ROC, poles/zeros, stability.
6. **Frequency Domain** – Fourier series, DTFT, frequency spectrum interpretation.

### Example Question Formats:
- Conceptual MCQs (e.g., “What is the Nyquist rate for a signal with bandwidth B?”)
- Numerical problems (e.g., “Compute the Z‑transform of x[n] = a^n u[n]”)
- True/False statements (e.g., “Aliasing occurs when sampling below the Nyquist rate.”)
- Signal property identification and block diagram analysis.

---

## Practical Evaluation Details (Weeks 12–13)

**Format:** Hands‑on lab‑based evaluation  
**Duration:** 1.5 hours per session (two sessions)

### Session 1 (Week 12):
- Signal generation and analysis in Python
- Sampling and reconstruction exercises
- FFT implementation and spectrum analysis
- FIR/IIR filter design and application

### Session 2 (Week 13):
- Real‑time DSP implementation on STM32 using CMSIS‑DSP
- Audio / ECG signal processing
- Embedded filtering and performance optimisation

---
## Final Exam Details (Final exam evaluation Week)

**Format:** 60 Multiple Choice Questions  
**Duration:** 1.5 hours  
**Coverage:** Comprehensive – all topics from Weeks 1–13, with **emphasis on Weeks 8–13** (DFT/FFT, digital filters, embedded DSP).

### Key Areas for the Final Exam:
- DFT, FFT, windowing, spectral leakage
- FIR vs IIR filters – design, stability, frequency response
- Filter implementation (direct form, cascaded, etc.)
- STM32 CMSIS‑DSP – basic functions, FFT, filter blocks
- Practical DSP applications (audio, sensor processing)
- Integration of theory with hands-on lab concepts

---
## Learning Outcomes

By the end of the course, students will be able to:

- Explain DSP fundamentals and mathematical foundations.
- Perform sampling and frequency‑domain analysis.
- Design FIR and IIR filters.
- Analyse signals using FFT and interpret spectra.
- Develop DSP applications in Python.
- Implement DSP algorithms on STM32 using CMSIS‑DSP.
- Complete an end‑to‑end DSP project.
- **Demonstrate theoretical understanding through a formal MCQ assessment.**
- **Apply practical DSP skills in lab‑based evaluations.**

---

## Recommended References

- Oppenheim & Schafer, *Discrete‑Time Signal Processing*
- Proakis & Manolakis, *Digital Signal Processing*
- Richard Lyons, *Understanding Digital Signal Processing*
- CMSIS‑DSP Documentation
