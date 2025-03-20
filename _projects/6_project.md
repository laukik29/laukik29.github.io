---
layout: page
title: "Machine Learning in Autoimmune Diseases"
description: "Machine Learning approach for the classification and genetic correlation analysis of autoimmune diseases"
img: assets/img/autoimmune.jpg
importance: 1
category: work
related_publications: false
---



## Overview


This project explores **machine learning applications in autoimmune disease classification and genetic analysis**, focusing on **Pediatric Inflammatory Bowel Disease (PIBD),Rheumatoid arthritis and Narcolepsy**. By integrating **supervised learning, genetic analysis, and feature selection techniques**, the study enhances disease prediction and biomarker identification.

---

## **Classification of Pediatric Inflammatory Bowel Disease (PIBD)**
**Objective**
- Classify PIBD subtypes: **Crohn's Disease (CD), Ulcerative Colitis (UC), and Inflammatory Bowel Disease Unclassified (IBDU)**.
- Improve diagnostic precision using **histological and endoscopic data**.

**Methodology**
- **Dataset:** 287 patients with gastrointestinal abnormalities at 10 specific locations.
- **Machine Learning Approach:**
  - Implemented **Random Forest** for supervised learning.
  - **Numerical encoding of gastrointestinal features** to enhance model interpretability.
  - Applied **Principal Component Analysis (PCA)** for dimensionality reduction.
  
**Results & Optimizations**
- Achieved **65% accuracy** in PIBD subtype classification.
- Applied **feature engineering and hyperparameter tuning** for optimization.
- Investigating **Support Vector Machines (SVMs)** and **ensemble learning** to improve classification performance.

---

## **Genetic Correlation Approach for Disease Diagnosis**
**Objective**
- Identify **key genes associated with autoimmune diseases**.
- Develop a **robust diagnosis model** using genetic data.

**Methodology**
- **Data Collection:** Genetic profiles of healthy and affected individuals.
- **Statistical Gene Analysis:**
  - Computed **corrected p-values** to identify significant genetic markers.
  - Key genes identified: **STAT1, IFI44, HLA-DRB1**, and others.

**Results & Insights**
- **Random Forest model** achieved **73% prediction accuracy** for disease classification.
- Identified **critical genetic pathways** influencing autoimmune conditions.
- Explored **environmental triggers** that contribute to disease progression.

---
## **Machine Learning-Based Identification of Narcolepsy Predictive Genes**
**Objective**
- Develop an **ML framework** to predict **narcolepsy susceptibility genes**.
- Enhance diagnostic strategies using genomic data.

**Methodology**
- **Data Sources:**
  - **Gene Expression Omnibus (GEO) database**:
    - **Training Dataset:** GSE69371
    - **Validation Dataset:** GSE69370
- **Data Preprocessing:**
  - Filtered and normalized raw gene expression data.
- **Gene Analysis:**
  - Identified **21,154 differentially expressed genes (DEGs)**.
  - Extracted **309 autoimmune-related genes (ARGs)** from the **Gene and Autoimmune Disease Association Database (GAAD)**.
  - Merged **DEGs and ARGs** to refine **309 differentially expressed autoimmune-related genes (DEARGs)**.
  
**Gene Prioritization**
- Ranked genes based on **statistical significance and tissue-specific expression**.
- Top identified genes:
  - **HLA-DQB1, MOG, CTSH, CHKB, TAC1, PENK, HLA-DQA1, DNMT1, MAP3K7, NRXN1**.

**Machine Learning Integration**
- Utilized **SVM-RFE (Support Vector Machine-Recursive Feature Elimination)**, **Lasso Logistic Regression**, and **Random Forest** for gene selection and classification.

**Results**
- Identified a refined set of genes with **high predictive power for narcolepsy**.
- Demonstrated **associations between gene expression and disease pathology**.

---

**Tools and Techniques**
- **Machine Learning Algorithms:** Random Forest, SVM, Lasso Regression.
- **Statistical Analysis:** p-value computation, feature importance analysis.
- **Data Processing:** Principal Component Analysis (PCA) for dimensionality reduction.
- **Performance Metrics:** Accuracy, Precision, Recall, F1-score, Confusion Matrix.
- **Bioinformatics Databases:** 
  - **Gene Expression Omnibus (GEO)**
  - **Gene and Autoimmune Disease Association Database (GAAD)**

---


**Repository & Additional Resources**

GitHub Repository: [PIBD](https://github.com/laukik29/Machine-Learning-/tree/main/ML\%20in\%20Autoimmune\%20Diseases)  
GitHub Repository: [Narcolepsy](https://github.com/laukik29/Machine-Learning-Based-Identification-of-Narcolepsy-Predictive-Genes)  
Project Report: [PDF](assets/pdf/REPORT-Autoimmune Diseases.pdf)  
  


