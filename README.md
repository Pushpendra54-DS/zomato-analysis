# Zomato EDA and ML Model

## Overview
This project contains Exploratory Data Analysis (EDA) and a Machine Learning model built on the Zomato dataset.

## Folder Structure
- [notebooks/](notebooks/) – Jupyter notebooks
- [data/](data/) – Dataset files
- [models/](models/) – Saved ML models (if any)
- [plots/](plots/) – Visualizations and graphs from EDA
- [results/](results/) – Model results and outputs

## How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/).  
2. Or click directly on the notebooks in this repository:  
   [ZOMATO EDA and Modelling](notebooks/ZOMATO%20EDA%20and%20modelling.ipynb)  
3. Make sure you have the required libraries installed:

```python
!pip install pandas numpy matplotlib seaborn scikit-learn

```
## Dataset

Dataset is too big to upload to GitHub. You can download it here:

[Download Zomato dataset from Google Drive](https://drive.google.com/file/d/1XtwdPLLNdIOMI5xps5z2sQFuCryNATbE/view?usp=sharing)

## Results

The performance of different models was compared using this plot:

![Model Comparison](result/model_comparison.png)

- Models included: Linear Regression (LR), Decision Tree (DT), Random Forest (RF), XGBoost
- This plot shows the accuracy or evaluation metrics of all models for easy comparison.
