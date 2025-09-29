# Organoid Data Analysis Framework
A modular framework addressing reproducibility, heterogeneity, fidelity, integration, and predictive modeling in organoid systems. Organoid systems pose analysis requirements that go beyond standard single-omics workflows. This repository consolidates five research-grade notebooks that tackle the core computational challenges in organoid analysis, from rigorous QC to multi-omic integration and predictive modeling.

## Challenges Addressed (and how they’re handled here)

- **Reproducibility** — Organoid datasets often exhibit technical noise and batch effects that obscure biological signals. We apply structured QC and correction strategies to stabilize downstream analyses.
- **Heterogeneity** — Even within the same culture, organoids display substantial variability in composition and state. We characterize intra- and inter-organoid variation using clustering and low-dimensional embeddings.
- **Fidelity** — A key question is how well organoids recapitulate target tissues. We benchmark organoid profiles against fetal/tissue references to quantify biological fidelity.
- **Integration** — Multi-omic measurements offer complementary views of organoid biology. We integrate RNA and protein modalities to identify shared programs and modality-specific signals.
- **Prediction** — Beyond description, we train machine-learning models on integrated features to predict organoid quality and expose the drivers behind those predictions.

All results, figures, and interpretations are embedded directly in the notebooks.  
Each analysis is fully documented step by step, with outputs saved in `data/processed/` and `figures/` (not tracked in the repository).

## Repository Structure
The repository is organized into five modules, each with its own notebook and README:

1. **QC & Batch Correction** (`nb1_QC.ipynb`)  
2. **Organoid Heterogeneity** (`nb2_heterogeneity.ipynb`)  
3. **Organoid Fidelity vs Reference** (`nb3_reference.ipynb`)  
4. **Multi-Omic Integration** (`nb4_multiomics.ipynb`)  
5. **Predicting Organoid Quality with ML** (`nb5_quality_ml.ipynb`)

## What this demonstrates

- **Integrated multi-omics**: RNA + protein factorization with clear hand-off from integration (nb4) to prediction (nb5).  
- **Interpretable ML**: factor-level features and loadings enable feature-importance and biological attribution.  
- **Reproducible practice**: consistent foldering, documented decisions, and embedded outputs; heavy data excluded.  
- **Modular design**: each notebook stands alone yet composes into a pipeline from QC → heterogeneity → fidelity → integration → prediction.

## Data
Raw datasets and large intermediates are not included in this repository due to size constraints. See each module’s README for dataset notes and assumptions. The notebooks contain complete outputs and figures for review.

## Author
Sally Yepes (<sallyepes233@gmail.com>)

## License
MIT

    

