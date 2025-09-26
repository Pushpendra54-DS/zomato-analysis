# Badges

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Colab](https://img.shields.io/badge/Open%20in-Colab-orange?logo=googlecolab&logoColor=white)](https://colab.research.google.com/drive/your_colab_file_id)
[![Project](https://img.shields.io/badge/Project-Data%20Science-purple)](#)

# Zomato EDA and ML Model

## 📑 Table of Contents

- [📝 Overview](#-overview)
- [📁 Folder Structure](#-folder-structure)
- [⚡ How to Run](#-how-to-run)
- [📊 Dataset](#-dataset)
- [🏆 Results](#-results)
- [📈 Metric Summary](#-metric-summary)
- [🚀 Future Work](#-future-work)
- [📜 License](#-license)


## 📝 Overview
This project contains Exploratory Data Analysis (EDA) and a Machine Learning model built on the Zomato dataset.

## 📁 Folder Structure
- [notebooks/](notebooks/) – Jupyter notebooks
- [data/](data/) – Dataset files
- [models/](models/) – Saved ML models (if any)
- [plots/](plots/) – Visualizations and graphs from EDA
- [results/](results/) – Model results and outputs

## ⚡ How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/).  
2. Or click directly on the notebooks in this repository:  
   [ZOMATO EDA and Modelling](notebooks/ZOMATO%20EDA%20and%20modelling.ipynb)  
3. Make sure you have the required libraries installed:

```python
!pip install pandas numpy matplotlib seaborn scikit-learn

```
##  📊  Dataset

Dataset is too big to upload to GitHub. You can download it here:

[Download Zomato dataset from Google Drive](https://drive.google.com/file/d/1XtwdPLLNdIOMI5xps5z2sQFuCryNATbE/view?usp=sharing)

##  🏆 Results

The performance of different models was compared using this plot:

![Model Comparison](results/Model%20Comparision.png)

###  📈 Metrics Summary

| Model           | MAE           | R²           |
|-----------------|---------------|-------------|
| Linear Regression (LR) | 0.2828        | 0.302       |
| Decision Tree (DT)     | 0.0481        | 0.856       |
| Random Forest (RF)     | 0.0637        | 0.915       |
| XGBoost                | 0.1517        | 0.750       |

**Observations:**  
- Random Forest (RF) performed the best overall with the highest R².  
- Linear Regression (LR) had the lowest R² and the highest MAE.  
- Decision Tree (DT) and XGBoost performed moderately well.  

For detailed analysis, see the [notebooks](notebooks/ZOMATO%20EDA%20and%20modelling.ipynb).

##  📜 Future Work

- Save and upload trained model files for reproducibility.  
- Add more advanced models or hyperparameter tuning.  
- Deploy the model using Flask, Streamlit, or another web framework.  
- Expand analysis with more features or datasets.  
- Add automated evaluation reports and dashboards.

##  📜 License

This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

