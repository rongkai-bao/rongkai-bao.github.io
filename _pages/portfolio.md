---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

## 🔬 Research Projects

I organize my research by **scientific domain**. Each project demonstrates the integration of experimental design, computational analysis, and biological interpretation.

---

## 🧬 Transcriptomics & Gene Expression Analysis

### 1. Pesticide-Induced Developmental Toxicity (Transcriptomic Mechanisms)

**Period**: 2023-2025 | **Status**: Published (3 papers)

**Overview**
Investigating how pesticides (benfuracarb, diafenthiuron, tralomethrin) disrupt zebrafish development through transcriptomic profiling and mechanistic validation.

**Key Publications**
- **Bao et al. (2025)** Pesticide Biochemistry and Physiology - *Benfuracarb impairs swim bladder development via JNK2-mediated autophagy inhibition* (Cover article, IF=4.2)
- **Su et al. (2023)** Chemosphere - *Diafenthiuron causes developmental toxicity in zebrafish* (IF=8.9)
- **Huang et al. (2025)** Journal of Environmental Management - *Tralomethrin degradation via advanced oxidation impacts zebrafish development* (IF=8)

**Methods & Skills Demonstrated**
- Bulk RNA-seq data processing and differential expression analysis (DESeq2, edgeR)
- Functional annotation (Gene Ontology, KEGG pathway enrichment)
- Protein-protein interaction (PPI) network visualization (String, Cytoscape)
- Statistical validation and biological interpretation

**Key Findings**
- Identified JNK2 as a critical node in pesticide-induced toxicity
- Characterized autophagy dysregulation as a central mechanism
- Discovered intergenerational epigenetic effects in F2 larvae

---

### 2. Single-Cell RNA-seq (scRNA-seq) Pipeline Development

**Period**: 2024-Present | **Status**: In Development

**Overview**
Building standardized scRNA-seq workflows for zebrafish developmental studies, with focus on pesticide-exposed embryos and larvae.

**Techniques**
- Cell QC, normalization, and integration (Seurat, Scanpy)
- Batch effect correction (Harmony, scanorama)
- Dimensionality reduction (UMAP, t-SNE)
- Cell type annotation and marker gene discovery
- Developmental trajectory inference (Monocle3, RNA velocity)

**Current Objectives**
1. Multi-tissue characterization of toxicant-exposed larvae
2. Identify cell-type-specific vulnerability to pesticide exposure
3. Compare transcriptomic signatures across developmental stages

**Skills Developed**
- High-dimensional data analysis
- Python/R programming for single-cell workflows
- Batch effect detection and correction

---

## 🎨 Epigenomics & Chromatin Analysis

### 3. Single-Cell ATAC-seq (scATAC-seq) Analysis

**Period**: 2024-Present | **Status**: Exploratory

**Overview**
Profiling chromatin accessibility at single-cell resolution to identify dysregulated cis-regulatory elements in toxicant-exposed development.

**Techniques**
- Fragment processing and peak calling (CellRanger-ATAC, MACS2)
- Quality control and downstream analysis (Signac, ArchR)
- Motif enrichment and TF activity inference
- Multi-omics integration with scRNA-seq (WNN approach)

**Planned Applications**
- Characterize epigenetic signatures of toxicant-exposed cell types
- Identify key transcription factors driving toxicity responses
- Link regulatory changes to gene expression alterations

**Skills Developed**
- Chromatin biology principles
- Multi-omics data integration
- Advanced bioinformatics workflow design

---

## 🧪 Computational Chemistry & Molecular Dynamics

### 4. Target Protein Screening for Pesticide Mechanisms

**Period**: 2022-2025 | **Status**: Patent Pending

**Innovation**: Entropy-weighted TOPSIS algorithm for ranking candidate targets

**Overview**
Developed a computational framework to screen and rank putative pesticide target proteins, enabling rational mechanistic hypothesis generation.

**Methods**
- Molecular docking (Schrödinger Suite - Glide, Maestro)
- Protein structure preparation and active site identification
- Multi-criteria decision analysis (TOPSIS algorithm with entropy weighting)
- Consensus ranking from multiple docking poses and evaluation metrics

**Patent Details**
- **CN119181425A**: Method and System for Pesticide Target Protein Screening Based on Entropy-Weighted TOPSIS Algorithm

**Key Outcomes**
- Identified JNK2 as primary target (later validated experimentally)
- Computational predictions achieved 85% correlation with experimental results
- Algorithm reduced computational screening time by 40%

**Skills Demonstrated**
- Structural biology and structure-function relationships
- Algorithm design and optimization
- Python implementation of novel computational approaches

---

### 5. Molecular Dynamics (MD) Simulations

**Period**: 2023-Present | **Status**: Ongoing

**Overview**
Simulating protein-ligand interactions at atomic resolution to understand chemical mechanisms of action and validate docking predictions.

**Techniques**
- Simulation setup using GROMACS
- Force field parameterization (AMBER, CHARMM)
- Trajectory analysis (RMSD, RMSF, hydrogen bonding networks)
- Free energy calculations (FEP, TI) for binding affinity prediction
- Visualization with VMD and GROMACS tools

**Current Projects**
1. **JNK2-pesticide binding dynamics** - Understanding how different agrochemicals stabilize different protein conformations
2. **Comparative MD studies** - Predicting structural basis for differential toxicity between pesticide analogs
3. **Conformational ensemble analysis** - Linking MD-derived structural insights to experimental biochemistry

**Skills Developed**
- Simulation parameterization and equilibration
- Convergence testing and quality assessment
- Time-series analysis and interpretation

---

## 🕸️ Network Analysis & Systems Biology

### 6. Protein-Protein Interaction (PPI) Network Analysis

**Period**: 2023-2025 | **Status**: Active

**Overview**
Constructing and analyzing pesticide-responsive networks to identify functional modules and hub proteins mediating toxicity.

**Methods**
- Network construction from multi-source databases (STRING, IntAct, KEGG, Reactome)
- Integration with transcriptomic data
- Topological analysis (centrality metrics, clustering coefficients)
- Community detection algorithms
- Visualization (Cytoscape, Gephi, force-directed layouts)

**Key Case Studies**

**Case 1: JNK2 Signaling Network**
- Mapped kinase signaling cascade responsive to benfuracarb exposure
- Identified autophagy as downstream effector
- Network-guided hypothesis for mechanism

**Case 2: Pesticide-Responsive Gene Modules**
- Discovered co-regulated gene clusters across multiple datasets
- Functional enrichment analysis revealed pathway overlap
- Predicted novel pesticide-regulated genes for validation

**Skills Demonstrated**
- Graph theory and network science
- Systems-level biological interpretation
- Functional module discovery

---

## 📊 Data Mining & Machine Learning

### 7. Customer Satisfaction Prediction (Machine Learning)

**Competition**: MathorCup Big Data Analytics Competition 2023 | **Award**: 🥇 National First Prize

**Project Summary**
Developed machine learning pipeline to predict customer satisfaction from survey data with feature engineering.

**Methods**
- Exploratory data analysis (pandas, NumPy)
- Feature engineering: correlation analysis, dimensionality reduction
- Model comparison: stepwise regression, random forest, gradient boosting
- Cross-validation and hyperparameter optimization
- Feature importance interpretation

**Results**
- Achieved highest prediction accuracy among all competing teams
- Identified top 15 most influential satisfaction drivers
- Generated actionable business insights for stakeholder communication

**Skills Demonstrated**
- End-to-end ML pipeline development
- Real-world data preprocessing and cleaning
- Statistical validation and model interpretation

---

### 8. Mathematical Modeling & Optimization

**Competition Projects** (2022-2024)

| Competition | Year | Award | Title |
|---|---|---|---|
| MathorCup Mathematical Modeling | 2022 | 🥇 National 1st | Base Station Location Optimization via Multi-objective Programming & Clustering |
| CUMCM | 2022 | 🥈 Provincial 2nd | UAV Localization in TDOA Systems using Simulated Annealing |
| APMCM | 2024 | 🥈 National 2nd | Sustainable Development Analysis of China's Pet Industry via International Trade |

**Key Techniques Used**
- Mathematical formulation of real-world problems
- Optimization algorithms (linear/nonlinear programming, heuristic methods)
- Large-scale data analysis and statistical modeling
- Technical report writing and visualization

**Representative Methods**
- Multi-objective optimization with Pareto frontier analysis
- Simulated annealing for global optimization
- Sensitivity analysis and robustness testing

---

## 🚀 Emerging Research Directions

### AI & Machine Learning in Toxicology

**Motivation**: Scale computational toxicity predictions to chemical libraries

**Current Exploration**
- Deep learning basics for chemical property prediction
- Multimodal learning for integrating chemical structure + omics data
- Transfer learning from public toxicology datasets

**Tools**: PyTorch, TensorFlow, RDKit (cheminformatics)

---

### Network Medicine & Digital Twins

**Vision**: Build computational models of hematopoietic systems for personalized medicine

**Concepts Under Investigation**
- Agent-based modeling (ABM) of hematopoietic stem cells
- Integrating spatial omics for tissue-level understanding
- Digital twin frameworks for disease modeling

**Relevant Tools**: NetLogo (ABM), Vispy (visualization)

---

### Open Science & Reproducible Research

**Commitment**: Share code, data, and workflows openly

- GitHub repositories for all major projects
- Docker containers for computational reproducibility
- Detailed methods documentation and code comments

---

## 📈 Project Statistics

| Category | Count |
|---|---|
| **Published Papers** | 6 (including 3 first/co-author) |
| **Patent Applications** | 2 pending |
| **Active Research Projects** | 6+ |
| **Bioinformatics Tools Developed** | 3+ |
| **Mathematical Models** | 4+ |
| **Programming Languages** | 5 (Python, R, Java, MATLAB, Bash) |

---

## 🎯 Future Project Roadmap

**PhD Phase (2026-2030)**
1. Multi-omics integration for hematologic malignancies
2. Computational modeling of leukemic cell evolution
3. Network medicine approaches for treatment resistance
4. Development of open-source bioinformatics tools

**Postdoctoral Phase (2030+)**
1. Translational oncology and precision medicine
2. Biomarker discovery and validation
3. Clinical trial design optimization
4. Mentoring junior researchers

---

Interested in collaboration? Feel free to [**reach out**](/about/)! 🤝
