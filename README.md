# 📊 Customer Churn Prediction  
This project predicts customer churn using a **Logistic Regression Model**. The goal is to analyze customer data and identify factors contributing to churn, improving customer retention strategies.

---

## 🚀 **Project Overview**  
- Developed a classification model to predict customer churn.  
- Cleaned and preprocessed customer data.  
- Trained a logistic regression model and evaluated performance using a confusion matrix and classification report.  

---

## 🛠️ **Tech Stack**  
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  

---

## 📂 **Dataset**  
- **Filename**: `WA_Fn-UseC_-Telco-Customer-Churn.csv` (Contains Data of a Telecom Company)
- Contains customer demographics, service subscriptions, and churn status.  

---

## 🏗️ **Project Workflow**  

### 🔹 **1. Data Cleaning & Preprocessing**  
✔️ Handled missing values  
✔️ Mapped categorical data to numeric values using `LabelEncoder`  
✔️ Dropped irrelevant columns  

---

### 📊 **2. Data Visualization**  
✔️ Plotted bar graphs and pie charts to understand the distribution of churn, gender, and contract type  

---

### 🎯 **3. Model Building**  
✔️ Split data into training and test sets  
✔️ Scaled data using `StandardScaler`  
✔️ Trained logistic regression model  

---

### 📈 **4. Model Evaluation**  
✔️ Generated confusion matrix and classification report  
✔️ Achieved **81% accuracy**  

---

## 🎯 **Results**  

| Metric | Class 0 (Non-Churn) | Class 1 (Churn) |  
|--------|---------------------|-----------------|  
| **Precision** | 85% | 68% |  
| **Recall** | 91% | 56% |  
| **F1-Score** | 88% | 61% |  
| **Support** | 1036 | 373 |  

✅ The model performs better at predicting **non-churn cases** than churn cases.  

---

## 📎 **How to Run**  
1. Clone the repository:  
```bash
git clone https://github.com/your-username/customer-churn-prediction.git
