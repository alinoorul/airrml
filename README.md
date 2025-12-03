# Adaptive Immune Profiling
Models for AIRR-ML-25: Adaptive Immune Profiling Challenge on Kaggle

Challenge link: [https://www.kaggle.com/competitions/adaptive-immune-profiling-challenge-2025/overview](https://www.kaggle.com/competitions/adaptive-immune-profiling-challenge-2025/overview)

## `baseline-pred.ipynb` is main script
This script is modified to add new models. It has data loaders.

## Steps

1. Install Python 3.12
2. Create a folder (project root directory) 
3. Open terminal and create virtual environment with Python 3.12 in that folder
   ``` python312 -m venv venv ```
4. Start virtual environment:
   Windows:
   ``` ./venv/bin/activate ```
   Mac/Linux:
   ``` source ./venv/bin/activate ```
5. Install libraries
   ``` pip install notebook pandas numpy tqdm polars torch torchvision scikit-learn```

    If using AMD GPU, use Linux and install ROCm. See [PyTorch docs](https://pytorch.org/get-started/locally/) 
6.  Copy `baseline-pred.ipynb` to project root directory
7.  Download dataset from Kaggle by clicking the Download All button on this page: [Dataset link](https://www.kaggle.com/competitions/adaptive-immune-profiling-challenge-2025/data)
8.  Extract dataset in project root directory
9.  Project root directory should contain `adaptive-immune-profiling-challenge-2025` folder and `baseline-pred.ipynb` script
10.  Run `jupyter notebook` in terminal
11.  Open `baseline-pred.ipynb` in Jupyter Notebook and run cells
