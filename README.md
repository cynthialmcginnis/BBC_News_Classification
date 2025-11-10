# BBC News Classification with Matrix Factorization (NMF) + Supervised Baselines

**Goal.** Classify BBC news articles into {business, entertainment, politics, sport, tech}.  
**Methods.** Unsupervised NMF topic modeling + supervised baselines (NB, Linear SVM, LogReg, RF).  
**Deliverables.** Three Jupyter notebooks (Parts I–III), figures, and optional Kaggle submissions.

## Repo structure
- `notebooks/01_part1_EDA.ipynb` – EDA, text pipeline, TF–IDF
- `notebooks/02_part2_NMF_and_models.ipynb` – NMF topics, mapping, supervised baselines, comparisons
- `notebooks/03_part3_supervised_vs_unsupervised.ipynb` – fair comparison, data-efficiency study (10–100%)
- `src/` – reusable helpers
- `submissions/` – Kaggle CSVs
- `models/` – saved vectorizer/model artifacts (optional via Git LFS)
- `environment.yml` – reproducible environment

## Data
This repo does **not** commit raw data. Place files as:
