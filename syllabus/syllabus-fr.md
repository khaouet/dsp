# Programme de formation en Traitement Numérique du Signal (TNS) – Programme sur 14 semaines

## Durée

**14 semaines**

## Organisation du cours

- **Cours magistral :** 1,5 heure par semaine (21 heures au total)
- **Atelier (laboratoire pratique) :** 3 heures toutes les deux semaines (6 ateliers = 18 heures)
- **Devoirs / Travaux pratiques :** 2 heures par semaine (28 heures au total)
- **Évaluation intermédiaire :** 1 heure (Semaine 7) – QCM de 40 questions
- **Évaluation pratique :** 01 session × 1 heure (Semaines 12–13)
- **Révision finale et projet de fin d'études :** Semaine 14

**Total d'heures encadrées :** ~69 heures

---

## Calendrier hebdomadaire

| Semaine | Cours magistral (1,5 h) | Atelier (3 h, bi-hebdomadaire) | Devoirs / Évaluation (2 h) |
|---------|-------------------------|--------------------------------|----------------------------|
| **1**   | Introduction au TNS, signaux, applications du TNS | — | Classification des signaux et applications du TNS |
| **2**   | Fondements mathématiques : nombres complexes, formule d'Euler, sinusoïdes | Configuration Python, génération de signaux, nombres complexes | Exercices Python sur les sinusoïdes |
| **3**   | Théorie de l'échantillonnage, CAN, Nyquist, quantification | — | Exercices sur l'échantillonnage et la CAN |
| **4**   | Signaux à temps discret, systèmes LTI, convolution | Opérations sur les signaux, convolution, filtre moyenneur | Exercices de convolution |
| **5**   | Transformée en Z, ROC, pôles et zéros | — | Transformée en Z et analyse de stabilité |
| **6**   | Séries de Fourier, DTFT, spectre fréquentiel | TFD, analyse spectrale, traitement audio | Interprétation du spectre |
| **7**   | **Évaluation intermédiaire (QCM)** | — | **40 questions QCM (1 heure)** couvrant les semaines 1 à 6 |
| **8**   | TFD, FFT, fenêtrage, fuite spectrale | Exercices sur FFT et fenêtrage | Exercices sur FFT et fenêtrage |
| **9**   | Filtres numériques RIF et RII | — | Exercices de conception de filtres numériques |
| **10**  | Implémentation et analyse des filtres RIF/RII | Implémentation et analyse de filtres RIF/RII | Conception et analyse de filtres |
| **11**  | Applications du TNS et CMSIS‑DSP sur STM32 | Configuration STM32 CMSIS‑DSP et implémentation de base | Travail sur TNS embarqué et proposition de projet |
| **12**  | **Évaluation pratique – Partie 1** (en laboratoire) | — | **Mise en œuvre pratique du TNS** (1,5 h) |
| **13**  | **Évaluation pratique – Partie 2** (en laboratoire) | — | **Mise en œuvre pratique du TNS** (1,5 h) |
| **14**  | Révision pour l'examen final | Projet de fin d'études (dernier atelier) | Préparation du rapport final et de la présentation |

---

## Ateliers

1. Python et génération de signaux (Semaine 2)
2. Signaux discrets et convolution (Semaine 4)
3. FFT et analyse spectrale (Semaine 6)
4. Conception de filtres numériques (Semaine 10)
5. Implémentation CMSIS‑DSP sur STM32 (Semaine 11)
6. Projet final de TNS (Semaine 14)

---

## Répartition des évaluations

| Composante | Poids | Détails |
|------------|-------|---------|
| Devoirs / Travaux pratiques | 20 % | Exercices hebdomadaires et travaux |
| Évaluation intermédiaire (QCM) | 20 % | 40 questions, 1 heure, couvre les semaines 1 à 6 |
| Évaluation pratique (Semaines 12–13) | 30 % | Mise en œuvre pratique du TNS (deux sessions) |
| Projet final | 20 % | Projet de fin d'études avec rapport et présentation |
| Participation en classe | 10 % | Assiduité et engagement |

---

## Détails de l'évaluation intermédiaire (Semaine 7)

**Format :** 40 questions à choix multiples  
**Durée :** 1 heure  
**Couverture :** Sujets des semaines 1 à 6

### Sujets abordés :

1. **Introduction au TNS** – définition, applications, classification des signaux.
2. **Fondements mathématiques** – nombres complexes, formule d'Euler, sinusoïdes, phaseurs.
3. **Théorie de l'échantillonnage** – théorème de Nyquist, repliement de spectre, quantification, CAN.
4. **Signaux à temps discret et systèmes LTI** – signaux impulsion/échelon, propriétés des systèmes, convolution, réponse impulsionnelle.
5. **Transformée en Z** – définition, ROC, pôles/zéros, stabilité.
6. **Domaine fréquentiel** – séries de Fourier, DTFT, interprétation du spectre fréquentiel.

### Exemples de formats de questions :
- QCM conceptuels (ex. « Quel est le taux de Nyquist pour un signal de bande passante B ? »)
- Problèmes numériques (ex. « Calculez la transformée en Z de x[n] = a^n u[n] »)
- Vrai/Faux (ex. « Le repliement de spectre se produit lorsque l'échantillonnage est inférieur à la fréquence de Nyquist. »)
- Identification de propriétés de signaux et analyse de schémas fonctionnels.

---

## Détails de l'évaluation pratique (Semaines 12–13)

**Format :** Évaluation pratique en laboratoire  
**Durée :** 1,5 heure par session (deux sessions)

### Session 1 (Semaine 12) :
- Génération et analyse de signaux en Python
- Exercices d'échantillonnage et de reconstruction
- Implémentation de la FFT et analyse spectrale
- Conception et application de filtres RIF/RII

### Session 2 (Semaine 13) :
- Implémentation temps réel du TNS sur STM32 avec CMSIS‑DSP
- Traitement de signaux audio / ECG
- Filtrage embarqué et optimisation des performances

---

## Détails de l'examen final (Semaine d'évaluation finale)

**Format :** 60 questions à choix multiples  
**Durée :** 1,5 heure  
**Couverture :** Complète – tous les sujets des semaines 1 à 13, avec **accent sur les semaines 8 à 13** (TFD/FFT, filtres numériques, TNS embarqué).

### Principaux domaines pour l'examen final :
- TFD, FFT, fenêtrage, fuite spectrale
- Filtres RIF vs RII – conception, stabilité, réponse fréquentielle
- Implémentation des filtres (forme directe, cascade, etc.)
- CMSIS‑DSP sur STM32 – fonctions de base, FFT, blocs de filtrage
- Applications pratiques du TNS (audio, traitement de capteurs)
- Intégration de la théorie avec les concepts pratiques de laboratoire

---

## Résultats d'apprentissage

À l'issue du cours, les étudiants seront capables de :

- Expliquer les fondamentaux du TNS et ses bases mathématiques.
- Effectuer l'échantillonnage et l'analyse fréquentielle.
- Concevoir des filtres RIF et RII.
- Analyser des signaux à l'aide de la FFT et interpréter les spectres.
- Développer des applications de TNS en Python.
- Implémenter des algorithmes de TNS sur STM32 à l'aide de CMSIS‑DSP.
- Réaliser un projet complet de TNS de bout en bout.
- **Démontrer leur compréhension théorique par une évaluation QCM formelle.**
- **Appliquer leurs compétences pratiques en TNS lors d'évaluations en laboratoire.**

---

## Références recommandées

- Oppenheim & Schafer, *Discrete‑Time Signal Processing*
- Proakis & Manolakis, *Digital Signal Processing*
- Richard Lyons, *Understanding Digital Signal Processing*
- Documentation CMSIS‑DSP