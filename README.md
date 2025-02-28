# Gaussian Discriminant Analysis
Implementations of a GDA model (LDA, QDA) for MNIST and Spam email classification\
Author: Michael Eugene Ng (SID: 3037857201)

This repository contains 2 files:
1. **featurize.py**:
    - Performs feature engineering on a corpus of emails to return a feature vector for each email
2. **cs189-hw3.ipynb**:
    - Performs data partitioning and evaluation metrics
    - Contains code used to generate GDA test predictions for MNIST and SPAM kaggle competition

**Directory Structure**
To reproduce my results, include them in the following directory structure:
```
gaussian-discriminant-analysis/
│
│── data/
│   │── spam-data.npz
│   │── mnist-data-hw3.npz
│   |── spam-data-hw3.npz
│   |── spam (folder containing .txt files)
│   |── ham (folder containing .txt files)
│   |── test (folder containing .txt files)
│
│── scripts/
    │── cs189-hw3.ipynb (in this repository)
    │── featurize.py (in this repository)
    │── check.py
    │── load.py
    │── save_csv.py

```
