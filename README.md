# Title - Zomato Dataset Analysis

This project contains Exploratory Data Analysis (EDA), preprocessing, and machine learning models on the Zomato dataset.
---
## 📌 Overview
This project explores the **Zomato Restaurants dataset** to perform:
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Machine Learning Models for Classification & Prediction
 The main objective is to analyze restaurant trends and build models that can predict ratings/labels effectively.
---

## Dataset
The dataset is available on Google Drive:  
[ Download Zomato Dataset ](https://drive.google.com/file/d/1XtwdPLLNdIOMI5xps5z2sQFuCryNATbE/view?usp=drive_link)
---
## Tools Used
- Python (Pandas, Numpy, Matplotlib, Seaborn)
- Machine Learning (Scikit-learn, XGBoost)
- Google Colab

---
## 📊 EDA Insights

Some key insights from the exploratory data analysis (EDA):

- **Top 10 Cuisines**: Identified the most popular cuisines in the dataset.  
- **Average Rating by Location**: Found areas with higher/lower customer satisfaction.  
- **Cost for Two Distribution**: Analyzed spending patterns of customers.  
- **Correlation Between Numeric Features**: Explored relationships like rating vs. cost, votes vs. rating.  

📂 All related plots can be found in the [`plots/eda/`](plots/eda/) folder.

---

## 🔄 Project Workflow

The workflow of this project is structured as follows:

1. **Data Cleaning & Preprocessing**  
   - Handled missing values and inconsistencies  
   - Encoded categorical variables and scaled numeric features  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions, correlations, and patterns in data  
   - Derived key insights about cuisines, ratings, and cost trends  

3. **Feature Engineering**  
   - Created meaningful features for model training  

4. **Model Building (Upcoming)**  
   - Logistic Regression  
   - Decision Tree  
   - XGBoost  

5. **Model Evaluation (Upcoming)**  
   - Accuracy, Precision, Recall, F1-score, ROC-AUC  
   - Confusion Matrices and ROC Curves  

📂 Model-related visualizations will be stored in [`plots/models/`](plots/models/).
