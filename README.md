📊 Bank Marketing Analysis
📌 Project Overview

This project analyzes the Bank Marketing Dataset to understand customer behavior and predict whether a client will subscribe to a term deposit.
The goal is to apply Exploratory Data Analysis (EDA) and Machine Learning models to extract insights and improve marketing strategies

---

## 📂 Dataset
- **Target Variable:** `deposit` (yes/no)  
- **Main Features:**
  - Demographics: `age`, `job`, `marital`, `education`
  - Financial: `balance`, `housing`, `loan`
  - Campaign: `contact`, `day`, `month`, `duration`, `campaign`, `pdays`, `previous`, `poutcome`

---

## ⚙️ Approach
1. **Data Preprocessing**
   - Handle missing/unknown values
   - Encode categorical features
   - Normalize numerical features  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of features
   - Relationship between variables and `deposit`
   - Correlation analysis & visualizations  

3. **Modeling**
   - Logistic Regression
   - Decision Trees
   - Random Forest
   - XGBoost / LightGBM  

4. **Evaluation**
   - Compare models on Accuracy, Precision, Recall, F1, ROC-AUC
   - Confusion matrix & classification report  

---

## 📊 Results
- Best model: `______` (fill after training)  
- Accuracy: `__%`  
- ROC-AUC: `__`  
- Key insights:
  - Which features most influence deposits
  - Recommendations for targeted marketing campaigns  

---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, Scikit-learn, XGBoost, LightGBM)  
- **Visualization:** Matplotlib, Seaborn  
- **Jupyter Notebook**  

---

## 🚀 How to Run
```bash
# Clone the repo
git clone https://github.com/Gyanendra98180/Python_Bank_Marketing_Analysis.git

# Navigate into folder
cd Bank_Marketing_Analysis

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook

