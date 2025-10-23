# 🍷 Type of Wine Detection

This project predicts whether a wine is *Red* or *White* based on its physicochemical characteristics.  
It uses *data cleaning, visualization, and classification techniques* to explore and model the Wine Quality dataset.

---

## 📌 Overview

Wine type detection is a common machine learning problem that helps in understanding how chemical properties influence wine classification.  
This notebook focuses on:
- Cleaning and preparing raw wine data
- Performing exploratory data analysis (EDA)
- Detecting and handling outliers
- Building a model to classify wine type

---

## 🧠 Dataset

The dataset used is *winequalityN.csv*, which includes features like:

| Feature | Description |
|----------|-------------|
| fixed acidity | Acidity level of the wine |
| volatile acidity | Volatile acid content |
| citric acid | Citric acid concentration |
| residual sugar | Amount of sugar left after fermentation |
| chlorides | Salt content |
| free sulfur dioxide | Free SO₂ concentration |
| total sulfur dioxide | Total SO₂ concentration |
| density | Density of the wine |
| pH | Acidity level |
| sulphates | Sulphate content |
| alcohol | Alcohol percentage |
| type | Red (1) or White (0) |

---

## ⚙️ Technologies Used

- *Python 3*
- *Pandas, **NumPy* – Data handling  
- *Matplotlib, **Seaborn* – Data visualization  
- *Scikit-learn* – (For data preprocessing or model building)
- *Jupyter Notebook* – Development environment

---

## 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:
- *Boxplots* for outlier detection  
- *Scatter plots* for feature relationships  
- *Heatmap* for feature correlation  
- *IQR method* to identify outliers  

Key insights:
- Alcohol and sulphates show strong correlation with wine type  
- Outliers were detected mainly in alcohol and residual sugar columns  
- White wines are more frequent in the dataset than red wines  

---

## 🧩 Model Training

(Include this if your notebook includes model training)  
A classification model such as *Decision Tree* or *Logistic Regression* can be trained to predict the wine type.  
Evaluation metrics like *accuracy, **confusion matrix, and **classification report* can be used to measure performance.

---

## 📈 Results

- Dataset cleaned and visualized successfully  
- Clear separation observed between red and white wines based on key chemical properties  
- Model accuracy: 
