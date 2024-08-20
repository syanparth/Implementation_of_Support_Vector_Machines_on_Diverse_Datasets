# SVM Classification Projects

## Table of Contents
1. [Cancer Cell Classification](#cancer-cell-classification)
   - [Dataset Overview](#dataset-overview)
   - [Loading the Data](#loading-the-data)
   - [Data Preprocessing](#data-preprocessing)
   - [Training the SVM Model](#training-the-svm-model)
   - [Evaluation](#evaluation)
2. [Iris Flower Classification](#iris-flower-classification)
   - [Dataset Overview](#dataset-overview-1)
   - [Loading the Data](#loading-the-data-1)
   - [Data Preprocessing](#data-preprocessing-1)
   - [Training the SVM Model](#training-the-svm-model-1)
   - [Evaluation](#evaluation-1)

---

## Cancer Cell Classification

### Dataset Overview
This project uses a dataset of cell samples to classify whether the cells are benign (non-cancerous) or malignant (cancerous). The dataset consists of 10 attributes like:

- Identifier (ID)
- Clump Thickness
- Uniformity of Cell Size
- Uniformity of Cell Shape
- Marginal Adhesion
- Single Epithelial Cell Size
- Bare Nuclei
- Bland Chromatin
- Normal Nucleoli
- Mitoses
- Class (Benign/Malignant)

### Loading the Data
```python
import pandas as pd

df = pd.read_csv('/content/cell_samples(10).csv')
df.head()


