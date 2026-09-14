# RetailRocket E-Commerce Recommendation System

## Project Overview

This project analyzes user behavior from the RetailRocket E-Commerce dataset and builds a recommendation system along with machine learning models to identify high-value customers.

The project covers the complete machine learning pipeline including data cleaning, exploratory data analysis (EDA), feature engineering, customer segmentation, recommendation systems, and predictive modeling.

---

## Dataset

Dataset: RetailRocket E-Commerce Dataset

The dataset contains user interactions such as:

- View Events
- Add-to-Cart Events
- Transactions

These interactions were used to understand customer behavior and generate product recommendations.

---

## Project Objectives

- Analyze customer behavior patterns
- Perform exploratory data analysis
- Create customer-level features
- Identify high-value customers
- Build recommendation systems
- Compare multiple machine learning models
- Generate personalized product recommendations

---

## Exploratory Data Analysis (EDA)

Performed:

- Dataset exploration
- Event distribution analysis
- Conversion funnel analysis
- Daily activity trends
- Top purchased products analysis

Key Findings:

- Cart Rate: 2.59%
- Purchase Rate: 0.84%

---

## Feature Engineering

Created customer-level features:

- View Count
- Add-to-Cart Count
- Transaction Count
- Cart Rate
- Purchase Rate

Created target variable:

- High Value User

---

## Recommendation System

Implemented:

### User-Based Collaborative Filtering

Steps:

1. User-Item Matrix Creation
2. Cosine Similarity Calculation
3. Similar User Identification
4. Product Recommendation Generation

Output:

- recommended_items.csv
- top_5_recommended_items.png

---

## Machine Learning Models

### Decision Tree

Applied SMOTE to handle class imbalance.

Result:

- Accuracy: 97.7%
- Recall (High Value Users): 90%

### Random Forest

Improved performance using ensemble learning.

Result:

- Accuracy: 98%

### XGBoost

Built an advanced boosting model for customer classification.

Result:

- Accuracy: 98%
- Recall (High Value Users): 91%

---

## Class Imbalance Handling

Applied:

### SMOTE (Synthetic Minority Oversampling Technique)

This balanced the minority class and significantly improved the detection of high-value users.

---

## Model Evaluation

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

Files:

- xgboost_confusion_matrix.png
- model_comparison.csv

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- XGBoost
- Imbalanced-Learn (SMOTE)

---

## Project Structure

```text
RetailRocket-Recommendation-System/


 - Feature_engineering.ipynb
 - Recommendation_System.ipynb

 - recommended_items.csv
 - model_comparison.csv

 - top_5_recommended_items.png
 - xgboost_confusion_matrix.png

README.md


## Results

Successfully built:

- Customer Recommendation System
- High Value User Prediction System
- Multiple Machine Learning Models
- Product Recommendation Engine

The final XGBoost model achieved approximately 98% accuracy while maintaining strong recall for identifying high-value customers.

---

## Future Improvements

- Deep Learning Recommendation Models
- Real-Time Recommendation Engine
- Hybrid Recommendation Systems
- Deployment using Streamlit or Flask

---

Dataset Downloaded from Kaggle RetailRocket E-commerece Dataset

## Author

Varun Kumar

GitHub:
https://github.com/varunkumarr2005
