# RNA-Seq-Cancer-Classification
There are three notebooks 1-CNN, 2.Transformer+wrapper, 3. Transformer+XGBOOST
# RNA-Seq Cancer Classification Using Deep Learning

This repository contains the source code afor multi-class classification of RNA-Seq data from five cancer types.

## Overview

The study investigates a deep learning-based framework for cancer classification using RNA-Seq gene expression data. The workflow includes data preprocessing, feature selection, class balancing using SMOTE, and deep learning-based classification.

## Cancer Types

The dataset includes five cancer types:

* BRCA — Breast Invasive Carcinoma
* KIRC — Kidney Renal Clear Cell Carcinoma
* LUAD — Lung Adenocarcinoma
* LUSC — Lung Squamous Cell Carcinoma
* UCEC — Uterine Corpus Endometrial Carcinoma

## Repository Structure

```text
RNA-Seq-Cancer-Classification/
│
├── README.md
├── notebooks/
│   ├── cnn_model.ipynb
│   └── Transformer+wrapper.ipynb
         Transformer+XGBOOST
│
├── data/
│   └── README.md
│

```

## Notebooks

### Data Preprocessing and Feature Selection
 cnn_model.ipynb


This notebook includes:

* Data loading
* Data preprocessing
* Label encoding
* Train-test splitting
* Feature selection
* SMOTE-based class balancing
* Preparation of the selected gene features for classification
* This notebook includes:

* CNN model implementation
* Model training
* Hyperparameter configuration
* Model evaluation
* Accuracy, precision, recall, and F1-score
* Confusion matrix
* ROC-AUC analysis
  
### TransformerClassification





## Dataset

The RNA-Seq dataset used in this study is publicly available through Mendeley Data:

Ferles, C., Papanikolaou, Y. & Naidoo, K. (2018). *Cancer types: RNA sequencing values from tumor samples/tissues*. DOI: 10.17632/SF5N64HYDT.1.

The dataset is not included in this repository. Please refer to the original data source for data access.

## Software and Libraries

The experiments were implemented in Python using the following major libraries:

* Python
* TensorFlow / Keras
* Scikit-learn
* imbalanced-learn
* XGBoost
* NumPy
* Pandas
* Matplotlib
* Seaborn

## Reproducibility

The notebooks provide the main preprocessing, feature selection, model development, training, and evaluation steps used in this study. Users can run the notebooks in Google Colab or a compatible Python environment.

## Code Availability

The code is provided to support the reproducibility of the results reported in the associated manuscript.






This repository is intended for research and academic purposes.

