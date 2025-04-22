# Country_Income_Model

This project is part of a data science assignment at UNAM.  
We built and evaluated three supervised learning models to classify countries based on their income level using GDP and other economic indicators.

## Objective

Classify countries into:
- Low income
- Middle income
- High income

…based on their GDP (Gross Domestic Product) and additional socio-economic features.

## Models

We trained and evaluated the following models:
- Support Vector Machine (SVM) with linear, ploy and RBF Kernels 

Evaluation was done using **5-fold cross-validation**, comparing:
- Accuracy
- Precision
- Recall
- F1 score

## Result

The model with the best overall performance across all metrics was: **SVM with RBF kernel**

## 📁 Files

- `MetricasYcv.ipynb`: Jupyter notebook with the full code and results.
- `Métricas_y_validación_cruzada.pdf`: Project description (in Spanish).

## Tools

- Python
- Scikit-learn
- Pandas
- Jupyter Notebook
