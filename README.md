# Credit Card Fraud Detection

### Overview
This project focuses on detecting fraudulent credit card transactions using machine learning and advanced feature selection techniques. The goal is to identify the most important features and build a reliable model to predict fraudulent transactions.

---

### Technologies
- **Language:** Python  
- **Libraries:**  
  - Data Handling: `pandas`, `numpy`  
  - Visualization: `matplotlib`, `seaborn`  
  - Machine Learning: `scikit-learn`  
- **Techniques:**  
  - Data cleaning and missing value handling  
  - Label encoding for categorical features  
  - Exploratory Data Analysis (EDA) with correlation heatmaps  
  - Feature selection: Variance Threshold, SelectKBest (ANOVA F-value & Mutual Information), Model-based selection (RandomForest), Recursive Feature Elimination (RFE & RFECV)  
  - Dimensionality reduction using PCA  
  - Genetic Algorithm for feature optimization  
  - Model training with Logistic Regression  
  - Model evaluation using Accuracy, F1 Score, Confusion Matrix, and Classification Report  

---

### Dataset
- **File:** `creditcard.csv`  
- **Source:** Public credit card fraud detection dataset (Kaggle)  
- **Description:** Contains features of credit card transactions and a target column `Class` indicating fraud (1) or normal (0) transactions.

---

### Notebook
- `CreditCardFraud.ipynb`: Contains the full workflow from data preprocessing, EDA, feature selection, model training, and evaluation.

---

### Project Structure
CreditCardFraudDetection/
│
├── `CreditCardFraud.ipynb`: Contains the full workflow from data preprocessing, EDA, feature selection, model training, and evaluation.
├── README.md # Project description
