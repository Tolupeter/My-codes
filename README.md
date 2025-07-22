# Single-Cell RNA-seq Analysis Toolkit for Skeletal Muscle

This repository contains a collection of 55 Python scripts developed for single-cell RNA sequencing (scRNA-seq) analysis of skeletal muscle samples. The codebase includes modules for preprocessing, quality control, integration, clustering, differential expression analysis, enrichment analysis, pseudotime inference, and visualization.

## Contents

Each script is modular and corresponds to a specific step in the scRNA-seq pipeline. Key functionalities include:

- 📦 **Data Preprocessing**  
  Filtering, normalization, log transformation, and batch correction.

- 🧬 **Doublet Detection and Quality Control**  
  Identification and removal of low-quality cells and potential doublets.

- 🧭 **Dimensionality Reduction & Clustering**  
  PCA, UMAP, Leiden clustering for cell population identification.

- 📊 **Differential Gene Expression (DGE)**  
  Pseudo-replicate-based DGE analysis between conditions.

- 🔁 **Trajectory Inference**  
  Pseudotime ordering of cells to explore lineage dynamics.

- 🔍 **Pathway and Gene Set Enrichment Analysis**  
  Functional interpretation of differentially expressed genes.

- 🧪 **Data Visualization**  
  Violin plots, dot plots, heatmaps, correlation plots, density plots, and UMAPs.

## Getting Started

### Requirements

- Python 3.8 or later
- Recommended libraries:
  - `scanpy`
  - `scvi-tools`
  - `anndata`
  - `seaborn`
  - `matplotlib`
  - `pandas`
  - `numpy`

Install required packages using:

```bash
pip install scanpy scvi-tools anndata seaborn matplotlib pandas numpy

How to Run
You can run each script independently. Recommended order:

Preprocessing and QC

Doublet removal

Integration and annotation

Clustering and dimensionality reduction

Differential gene expression

Enrichment analysis

Trajectory inference

Visualization

Each script file is named to indicate its function (e.g., DGE_analysis_YSham_vs_YOV.py, Trajectory_inference_Aged.py, ViolinPlot_Cluster4.py)
├── Preprocessing/
├── QC_and_Doublets/
├── Clustering/
├── DGE_Analysis/
├── Enrichment/
├── Pseudotime/
├── Visualization/
├── utils/
└── README.md

Author
Tolulope Saliu, PhD
Postdoctoral Researcher, University of Kentucky
📧 Contact: tpsa222@uky.edu

This toolkit was developed to support the analysis of skeletal muscle mononuclear cell heterogeneity and responses to physiological perturbations. The scripts can be adapted to other single-cell datasets with minor modifications.
