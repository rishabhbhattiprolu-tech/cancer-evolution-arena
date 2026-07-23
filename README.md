# 🧬 Cancer Evolution Arena

> A computational framework for modeling tumor ecosystems and inferred evolutionary state transitions from static cancer genomics data.

## Overview

Cancer Evolution Arena is an independent computational oncology project that explores whether cross-sectional cancer genomics data can be used to model tumor evolution.

Using mutation profiles from **230 TCGA Lung Adenocarcinoma (LUAD)** patients, this project integrates statistical mutation analysis, graph theory, clustering, and progression inference to identify recurring tumor ecosystems and construct an exploratory framework of tumor evolutionary state transitions.

Rather than treating tumors as isolated collections of mutations, Cancer Evolution Arena models them as dynamic genomic systems connected through probable evolutionary pathways.

---

## Key Features

- Statistical mutation co-occurrence analysis using Fisher's Exact Test and Odds Ratios
- Mutation interaction network construction
- Discovery of recurrent tumor ecosystems
- Probabilistic progression inference from cross-sectional genomic data
- Evolution simulator for exploring candidate mutation trajectories
- Evolutionary State Space modeling
- Interactive Cancer Evolution Arena visualization

---

## Dataset

- **Cancer Type:** Lung Adenocarcinoma (LUAD)
- **Source:** TCGA via cBioPortal
- **Patients:** 230
- **Mutation Events:** ~72,000
- **Final Analysis Panel:** 50 clinically relevant driver and resistance-associated genes

---

## Project Pipeline

```text
TCGA Mutation Data
        ↓
Patient × Gene Matrix
        ↓
Mutation Co-occurrence Analysis
        ↓
Mutation Interaction Network
        ↓
Tumor Ecosystem Discovery
        ↓
Progression Inference
        ↓
Evolution Simulator
        ↓
Evolutionary State Space
        ↓
Cancer Evolution Arena
```

---

## Repository Structure

```
.
├── notebooks/
├── figures/
├── results/
├── data/
├── README.md
└── requirements.txt
```

---

## Technologies

- Python
- Pandas
- NumPy
- SciPy
- NetworkX
- Scikit-learn
- Lifelines
- PyVis
- Matplotlib

---

## Current Status

- ✅ Core computational framework completed
- ✅ Tumor ecosystem discovery
- ✅ Progression inference
- ✅ Evolution simulator
- ✅ Evolutionary State Space
- 🚧 Interactive web interface (planned)

---

## Future Work

- Validate across additional cancer cohorts
- Integrate transcriptomic and pathway information
- Develop a web-based interactive interface
- Incorporate treatment response and drug sensitivity data

---

## Disclaimer

Cancer Evolution Arena is a computational research framework intended for exploratory analysis and hypothesis generation. It is **not** designed for clinical decision-making or patient-specific prediction.
