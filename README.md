# Organoid Data Analysis Framework

[![Reproducible](https://img.shields.io/badge/Reproducible-End--to--End-brightgreen)](#)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17268384.svg)](https://doi.org/10.5281/zenodo.17268384)

A modular analytical framework addressing **reproducibility, heterogeneity, fidelity, integration, and predictive modeling** in organoid systems.  
Organoid models present analytical challenges that extend beyond standard single-omics workflows.  
This repository consolidates **five research-grade notebooks**, each designed as an executable, interpretable analysis that combines code, rationale, and results in a single, transparent workflow.

---

## Analytical focus

- **Reproducibility** — addresses technical variation and batch effects through structured QC and correction.  
- **Heterogeneity** — quantifies intra- and inter-organoid variability in cell composition and state.  
- **Fidelity** — benchmarks organoid profiles against fetal and adult tissue references to measure biological accuracy.  
- **Integration** — combines RNA and protein modalities to uncover shared and unique molecular programs.  
- **Prediction** — applies interpretable machine-learning models to predict organoid quality and identify molecular drivers.

---

## Repository structure

The framework includes five core modules, each with its own notebook and README:

1. **Quality Control & Batch Correction** — `nb1_QC.ipynb`  
2. **Organoid Heterogeneity** — `nb2_heterogeneity.ipynb`  
3. **Organoid Fidelity vs Reference** — `nb3_reference.ipynb`  
4. **Multi-Omic Integration** — `nb4_multiomics.ipynb`  
5. **Predictive Modeling of Organoid Quality** — `nb5_quality_ml.ipynb`

Each notebook integrates code, commentary, and figures, forming a reproducible pipeline from data QC → heterogeneity → fidelity → integration → predictive modeling.

---

## Key features

- **Transparent analyses:** every step documented with rationale and inline results.  
- **Multi-omic integration:** RNA–protein factorization linking expression and proteomic signals.  
- **Interpretable ML:** model features mapped back to biological factors and pathways.  
- **Reproducible workflow:** consistent directory structure, deterministic setup, and complete outputs within notebooks.  
- **Modular design:** individual modules stand alone but form a coherent end-to-end framework.

---

## Data availability

Raw datasets and large intermediates are excluded due to size constraints.  
Each module’s README specifies dataset sources and assumptions.  
All notebooks contain embedded results and figures for review.

---

## Citation

> Yepes, S. (2025). *Organoid Data Analysis Framework: Reproducibility, Heterogeneity, and Fidelity in Organoid Systems.* GitHub.  
> DOI: [10.5281/zenodo.17268384](https://doi.org/10.5281/zenodo.17268384)

--- 
📧 [sallyepes233@gmail.com](mailto:sallyepes233@gmail.com)

