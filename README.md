# Machinelearning_project_A4

This repository contains our **A4 Machine Learning project** delivered through **three separate Jupyter notebooks**.  
Each notebook corresponds to a different contributor and a different stage/approach of the project.

Because one team member refactored the pipeline significantly, the notebooks are **not fully compatible** with each other.  
For this reason, we keep them separated to preserve clarity and avoid forcing an artificial merge.

## Notebooks overview

### 1) `1RenduML.ipynb` — Victor (initial version)
- First complete version of the project.
- Covers the initial data preparation, baseline modeling, and first results.
- This notebook is the starting point of our work.

### 2) `RenduML_Cyprien.ipynb` — Cyprien (model comparison pipeline)
- Implements a **reworked pipeline** focused on **systematic comparison of multiple models**.
- Includes a more advanced structure and different preprocessing choices.
- Due to the major refactoring, it is **not directly mergeable** with `1RenduML.ipynb`.

### 3) `RenduMLavecRN.ipynb` — Victoire (neural networks extension)
- Based on the initial notebook `1RenduML.ipynb`.
- Extends the project with **Neural Network models** (deep learning experiments).

## Important note about compatibility

The repository contains **two different codebases**:
- The “initial pipeline” (Victor) and its Neural Network extension (Victoire).
- The “refactored comparison pipeline” (Cyprien).

Since `RenduML_Cyprien.ipynb` was heavily modified compared to `1RenduML.ipynb`, combining all notebooks into a single unified notebook would require a full rewrite. We chose to keep the notebooks separate to maintain clean, readable, and reproducible work.

## Dataset

The dataset used for this project is too large to be stored directly on GitHub.  
It can be downloaded from the following source:

https://data.mendeley.com/datasets/8gx2fvg2k6/5

After downloading, place the dataset file(s) in your google drive or update the file path inside the notebooks.

## Contributors

- Victor Barthelemy
- Cyprien Lucas
- Victoire Bourdet
