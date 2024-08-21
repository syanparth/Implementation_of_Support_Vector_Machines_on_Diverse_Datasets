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
## For the Iris dataset using `scikit-learn`:
Ensure the Iris dataset is in the `data/` directory.
---
## Cancer Cell Classification

### Dataset Overview
This project involves classifying cell samples as either benign (non-cancerous) or malignant (cancerous). The dataset includes the following attributes:
- **Identifier (ID)**
- **Clump Thickness**
- **Uniformity of Cell Size**
- **Uniformity of Cell Shape**
- **Marginal Adhesion**
- **Single Epithelial Cell Size**
- **Bare Nuclei**
- **Bland Chromatin**
- **Normal Nucleoli**
- **Mitoses**
- **Class (Benign/Malignant)**


### Loading the Data
```python
import pandas as pd

# Load the dataset
df = pd.read_csv('/content/cell_samples(10).csv')

# Display the first few rows of the dataset
df.head()

