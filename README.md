# Customer Churn Prediction using Logistic Regression  

This project builds a **machine learning model** to predict customer churn in a banking environment. The goal is to identify customers who are likely to leave the bank based on their attributes and usage patterns.  

---

## 🔑 Key Steps  

### 1. Data Preparation  
- Loaded the customer churn dataset.  
- Explored dataset shape, summary statistics, and column details.  
- Handled categorical variables using **Label Encoding** and **One-Hot Encoding**.  
- Standardized numerical features with **StandardScaler**.  
- Split the dataset into **training and test sets**.  

### 2. Modeling  
- Implemented **Logistic Regression** as the classification algorithm.  
- Trained the model on the prepared data.  

### 3. Evaluation  
Model performance was assessed using:  
- ✅ **Accuracy Score**  
- ✅ **Confusion Matrix** (visualized with heatmap)  
- ✅ **Classification Report** (Precision, Recall, F1-score)  
- ✅ **ROC Curve** and **AUC Score**  

### 4. Visualization  
- Confusion Matrix heatmap for error analysis.  
- ROC Curve for classifier performance evaluation.  

---

## 📊 Outcome  
This notebook demonstrates how **Logistic Regression** can be applied to churn prediction, covering the full pipeline:  
**data preprocessing → model training → evaluation → visualization**.  

---
## 🛠️ Technologies Used

Python (Pandas, NumPy)

Scikit-learn (Logistic Regression, Preprocessing, Metrics)

Matplotlib & Seaborn (Visualizations)

Jupyter Notebook

## ⚡ How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/customer-churn-logistic.git
   cd customer-churn-logistic


