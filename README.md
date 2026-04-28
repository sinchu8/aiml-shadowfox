#ShadowFox AI/ML Internship Projects

**Welcome to this repository containing three complete Machine Learning projects developed during the ShadowFox AI/ML Internship Programme**.

This repository highlights a progressive journey from **basic regression models** to **advanced transformer-based NLP systems**, demonstrating practical skills in Machine Learning, Data Science, and Deep Learning.******



##Repository Overview

```bash
aiml-shadowfox/
│── Beginner.ipynb        # Task 1 - Boston Housing Price Prediction
│── Intermediate.ipynb   # Task 2 - Car Selling Price Prediction
│── Advanced.ipynb       # Task 3 - BERT NLP Analysis
│── README.md
```

---

## Project Roadmap

| Task   | Level        | Domain              | Core Techniques                             |
| ------ | ------------ | ------------------- | ------------------------------------------- |
| Task 1 | Beginner     | Regression          | Linear Regression, Decision Trees, Boosting |
| Task 2 | Intermediate | Regression          | Random Forest, Hyperparameter Tuning        |
| Task 3 | Advanced     | NLP / Deep Learning | BERT Transformers                           |

---

# Task 1 — Boston Housing Price Prediction


## Objective

Build a regression model to predict the **median housing prices in Boston suburbs** using socioeconomic and structural features.

## Dataset Details

* **Rows:** 506
* **Columns:** 14
* **Target Variable:** `PRICE`

## Workflow

* Data Cleaning & Missing Value Handling
* Outlier Detection using IQR
* Feature Scaling using StandardScaler
* Exploratory Data Analysis
* Model Training & Comparison

## Models Used

* Linear Regression
* Decision Tree Regressor
* Gradient Boosting Regressor 

## Metrics Used

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

## Best Performing Model

**Gradient Boosting Regressor**

---

# Task 2 — Car Selling Price Prediction


## Objective

Predict the **selling price of used cars** based on important vehicle specifications.

## Features Used

* Present Price
* Kilometers Driven
* Fuel Type
* Seller Type
* Transmission
* Owner Count
* Manufacturing Year

## Workflow

* Data Cleaning
* Feature Engineering
* Label Encoding
* Outlier Removal
* Train/Test Split
* Hyperparameter Tuning using RandomizedSearchCV

## Model Used

**Random Forest Regressor**

## Metrics Used

* MAE
* RMSE
* R² Score

## Best Performing Model

**Tuned Random Forest Regressor**

---

# Task 3 — Advanced BERT NLP Analysis



## Objective

Explore and analyze the **BERT Transformer Model** across multiple NLP tasks using HuggingFace Transformers.

## Tasks Performed

* Masked Language Modeling
* Sentiment Analysis
* Sentence Embeddings
* Text Similarity using Cosine Similarity
* PCA Visualization of Embeddings
* Attention Heatmaps
* Performance Dashboard

## Models Used

* `bert-base-uncased`
* `distilbert-base-uncased-finetuned-sst-2-english`

---

# Technologies & Libraries

```bash
Python
pandas
numpy
matplotlib
seaborn
plotly
scikit-learn
joblib
gdown
transformers
torch
```

---

# How to Run the Projects

## Option 1: Google Colab (Recommended)

1. Open Google Colab

2. Upload any notebook:

   * Beginner.ipynb
   * Intermediate.ipynb
   * Advanced.ipynb

3. Click **Run All**

> For Task 3, enable GPU:
> Runtime → Change runtime type → GPU

---

## Option 2: Local Setup

```bash
git clone https://github.com/YOUR_USERNAME/shadowfox-ai-ml-projects.git

cd shadowfox-ai-ml-projects

pip install pandas numpy matplotlib seaborn plotly scikit-learn joblib gdown
pip install transformers torch

jupyter notebook
```

---

# Skills Demonstrated

✅ Data Preprocessing
✅ Exploratory Data Analysis
✅ Regression Modeling
✅ Ensemble Learning
✅ Hyperparameter Tuning
✅ Deep Learning
✅ NLP with Transformers
✅ Attention Visualization
✅ Model Evaluation

---

# Learning Journey

```text
Beginner      → Regression Fundamentals
Intermediate  → Ensemble Models & Optimization
Advanced      → Transformers & NLP Research
```

If you found this repository useful, consider giving it a **star** on GitHub!
