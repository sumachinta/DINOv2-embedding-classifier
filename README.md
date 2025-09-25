# 🦁 DINOv2 Embedding Classifier

This repository demonstrates how to extract embeddings from a pretrained [DINOv2](https://arxiv.org/abs/2304.07193) model and apply dimensionality reduction (PCA/UMAP) and classification (e.g., Cat vs Dog from CIFAR-10).

---

## ⚙️ Environment Setup

### 1. Install Conda (if you don’t have it)
We recommend [Miniforge](https://github.com/conda-forge/miniforge) (lightweight Conda installer).  
Download and install Miniforge, then restart your terminal.

### 2. Create the environment
From the repository root:

conda env create -f environment.yml
conda activate dino
python -m ipykernel install --user --name dino --display-name "Python (dino)"


### 3. Running the Notebook

Open test.ipynb in Jupyter Notebook or VS Code.
Switch the kernel (top-right menu) to Python (dino).
Run all cells to generate embeddings, visualize them with PCA/UMAP, and experiment with classifiers.
