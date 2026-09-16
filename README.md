# 🛒 RetailRocket E-Commerce Recommendation System

## 📌 Project Overview

This project uses the RetailRocket E-Commerce Dataset to analyze user behavior, build machine learning models, generate product recommendations, and implement a Graph Neural Network (GNN) recommendation engine.

The project covers the complete machine learning workflow from data preprocessing to advanced recommendation systems.

---

## 🎯 Objectives

- Analyze customer interactions
- Understand user purchasing behavior
- Build machine learning models
- Generate personalized recommendations
- Implement Graph Neural Networks (GNNs)
- Visualize recommendations and embeddings

---

## 📂 Dataset

Dataset: RetailRocket E-Commerce Dataset

Features:

- Visitor ID
- Item ID
- Event Type (view, addtocart, transaction)
- Timestamp

---

## 🧹 Data Cleaning

Performed:

- Removed missing values
- Removed duplicates
- Converted timestamps
- Cleaned event records
- Prepared data for analysis

Output:

- cleaned_events.csv

---

## 📊 Exploratory Data Analysis (EDA)

Performed:

- Dataset overview
- Event distribution analysis
- User activity analysis
- Product popularity analysis
- Daily activity trends
- Conversion funnel analysis

Generated Visualizations:

- event_distribution.png
- daily_activity_trend.png
- top_products.png
- conversion_funnel.png

---

## ⚙️ Feature Engineering

Created:

- User interaction counts
- Product interaction counts
- Purchase behavior features
- Product popularity metrics
- Recommendation features

Generated Files:

- user_features.csv
- item_features.csv

---

# 🌳 Decision Tree Model

Built a Decision Tree Classifier to predict user interactions.

Steps:

- Train-Test Split
- Stratified Sampling
- Model Training
- Evaluation

Results:

- High classification performance
- Classification Report generated

---

# 🌲 Random Forest Model

Implemented Random Forest for improved performance.

Features:

- Ensemble Learning
- Reduced Overfitting
- Feature Importance Analysis

Generated Outputs:

- feature_importance.png
- random_forest_results.csv

---

# 🚀 XGBoost Model

Applied XGBoost for advanced prediction.

Advantages:

- High Accuracy
- Gradient Boosting
- Better Generalization

Generated Outputs:

- confusion_matrix.png
- xgboost_results.csv

---

# 🎯 Recommendation System

Built a recommendation engine using user-item interactions.

Workflow:

User → Interaction History
↓
Similarity Analysis
↓
Top-N Recommendations

Generated Outputs:

- top_5_recommended_items.csv
- top_5_recommended_items.png

---

# 🧠 Graph Neural Network (GNN) Recommendation System

Implemented a Graph Convolutional Network (GCN) using PyTorch Geometric.

### Graph Construction

Users → Nodes

Items → Nodes

Interactions → Edges

### GNN Architecture

GCNConv(1827 → 64)

↓

ReLU

↓

GCNConv(64 → 32)

### Process

User-Item Graph

↓

Graph Convolution

↓

Node Embeddings

↓

Similarity Calculation

↓

Top Recommendations

### Generated Outputs

- GNN_recommendations.csv
- GNN_recommendations_with_scores.csv
- GNN_top_recommendations.png
- GNN_recommendation_scores.png
- gnn_embeddings_pca.png

---

## 📈 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Decision Tree
- Random Forest
- XGBoost
- PyTorch
- PyTorch Geometric
- Graph Neural Networks (GCN)

---

## 📊 Project Workflow

Data Collection

↓

Data Cleaning

↓

EDA

↓

Feature Engineering

↓

Decision Tree

↓

Random Forest

↓

XGBoost

↓

Recommendation System

↓

Graph Neural Network

↓

Visualization & Evaluation

---

## 🏆 Key Learnings

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Classification Models
- Ensemble Learning
- Recommendation Systems
- Graph Neural Networks
- Node Embeddings
- Recommendation Visualization
- PyTorch Geometric

---

## 📁 Project Files

- RetailRocket_Recommendation_System.ipynb
- cleaned_events.csv
- user_features.csv
- item_features.csv
- feature_importance.png
- confusion_matrix.png
- top_5_recommended_items.csv
- top_5_recommended_items.png
- GNN_recommendations.csv
- GNN_recommendations_with_scores.csv
- GNN_top_recommendations.png
- GNN_recommendation_scores.png
- gnn_embeddings_pca.png

---

## 👨‍💻 Author

**Varun Kumar**

GitHub Profile:

https://github.com/varunkumarr2005

---
