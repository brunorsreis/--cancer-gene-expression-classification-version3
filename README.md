# --cancer-gene-expression-classification-version3
# Link https://www.techdatabasket.com/2026/03/17/conceptualising-an-ai-system-for-cancer-type-classification-using-gene-expression-data-version-3-integrating-oracle-ai-database-26ai-oracle-apex-and-a-claude-powered-chat-interface/

#  AI System for Cancer Type Classification Using Gene Expression Data

This project presents a complete end-to-end architecture for analysing cancer gene expression data using:

- Oracle AI Database 26ai
- Python (Machine Learning & Data Science)
- Oracle APEX (Interactive dashboards)
- Claude (LLM-powered natural language querying)

---

##  Overview

This system evolves across three versions:

- **Version 1** – Python-only analytics (PCA, t-SNE, clustering)
- **Version 2** – Oracle AI Database + APEX dashboards
- **Version 3** – Adds a Claude-powered conversational interface

The goal is to enable both technical and non-technical users to explore cancer genomics data efficiently.

---

##  Architecture

The system consists of four main layers:

1. **Oracle AI Database 26ai**
   - Stores:
     - `patient_labels`
     - `gene_expression`
     - `pca_results`
     - `tsne_results`
     - `cluster_results`

2. **Python Analytics Layer**
   - Data preprocessing
   - PCA and t-SNE dimensionality reduction
   - K-Means clustering
   - Statistical testing (ANOVA)

3. **Oracle APEX Dashboard Layer**
   - Interactive visualisations
   - PCA and t-SNE scatter plots
   - Cluster summaries

4. **Claude LLM Chat Layer (Version 3)**
   - Natural language → SQL conversion
   - Conversational querying of the database
   - Plain-English explanations of results

---

##  Features

- Gene expression data exploration
- PCA and t-SNE visualisation
- Cluster analysis (K-Means)
- Statistical validation (ANOVA)
- Oracle-based data storage and querying
- Interactive dashboards in APEX
- Natural language querying using Claude

---

##  Project Structure
