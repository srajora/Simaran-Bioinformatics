# 🧬 Machine Learning–Driven Glioma Grading

## Overview
This project analyzes RNA-Seq and clinical data from **The Cancer Genome Atlas (TCGA)** to classify glioma samples into **Low-Grade Glioma (LGG)** and **Glioblastoma Multiforme (GBM)** using differential expression analysis and machine learning models.

## Objectives
- Download and preprocess TCGA glioma RNA-Seq data  
- Perform normalization and differential gene expression analysis  
- Select top genes as features  
- Train machine learning models (Random Forest, SVM, Neural Network)  
- Visualize performance metrics and biologically relevant genes  

## Folder Structure

## Tools & Packages
- **R:** `TCGAbiolinks`, `DESeq2`, `caret`, `ggplot2`, `ComplexHeatmap`
- **Python (optional):** `scikit-learn`, `matplotlib`, `seaborn`

## Workflow Diagram
1. **Data Acquisition:** Fetch TCGA-LGG and TCGA-GBM datasets  
2. **Preprocessing:** Normalize counts and filter low-expressed genes  
3. **Differential Expression:** Identify DEGs between LGG and GBM  
4. **Machine Learning:** Train models using top DEGs  
5. **Evaluation:** Compare models using accuracy, AUC, and ROC plots  

## References
- TCGA: https://portal.gdc.cancer.gov/
- TCGAbiolinks R package: https://bioconductor.org/packages/release/bioc/html/TCGAbiolinks.html
