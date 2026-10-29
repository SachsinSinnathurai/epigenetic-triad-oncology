# epigenetic-triad-oncology
Computational multi-omic pipeline mapping SWI/SNF chromatin remodeling and hypoxic resistance in solid tumors.

Rational Polypharmacology Reverses Epigenetic and Metabolic Drivers of Chemotherapy Resistance Across Hypoxic Solid Tumors

Author: Sachsin Sinnathurai
Institution: Department of Anatomy & Cell Biology, McGill University
Status: Submitted / Preprint Architecture

Overview

This repository contains the complete analytical pipeline, data assets, structural docking metrics, and manuscript sources for investigating non-genetic therapy resistance in hypoxic solid tumors. The framework integrates DepMap 24Q2 functional genomics, TCGA clinical transcriptomics, LINCS L1000 perturbational state reversal, and AutoDock Vina molecular redocking.

Repository Structure

• data/processed/: Harmonized tabular datasets and supplementary Excel workbooks
• figures/: Vector-rendered PDF plates depicting ChIP occupancy, survival hazard landscapes, and drug synergy manifolds
• manuscript/: Complete LaTeX source (manuscript.tex) and compiled academic preprint (manuscript.pdf)

System Requirements

• Python >= 3.10 (pandas, numpy, scipy, lifelines)
• R >= 4.2.0 (survival, survminer, tidyverse)
