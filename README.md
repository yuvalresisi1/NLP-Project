# 🧬 DNABERT-2 vs ProteinBERT: Sequence Embedding for Gene and Organism Classification
**Tomer Oron & Yuval Resisi**

This project explores the use of **DNABERT-2** and **ProteinBERT** models to generate embeddings for biological sequences and evaluate their utility in downstream classification, clustering and phylogenetic tasks. The models are compared on their ability to classify:

- The **organism** (full species and genus-level)
- The **gene** from which a sequence originates

We also use the embeddings to construct **phylogenetic trees** that visually reflect relationships between genes and organisms.

## 📁 Contents

- `create_DNABERT2_embeddings.ipynb`: Notebook for generating embeddings using DNABERT-2
- `create_ProteinBERT_embeddings.ipynb`: Notebook for generating embeddings using ProteinBERT
- `analysis_tasks.ipynb`: Main analysis notebook for the bacterial dataset
- `human_analysis_tasks.ipynb`: Main analysis notebook for the human dataset
- `figures/`: Folder containing the project's figures
- `data/`: Folder containing raw DNA and protein sequences (embeddings not included due to size constraints)

## 🧰 Requirements

A `requirements.txt` file is included for convenience.


Install dependencies:
```bash
pip install -r requirements.txt
```

