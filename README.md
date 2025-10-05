# Customer Churn Prediction 🚀

## 📖 Overview
Businesses often lose customers without realizing the early signs.  
This project builds an **ETL pipeline** and **machine learning models** (Logistic Regression & Decision Tree)  
to predict potential customer churn based on transaction history.

## 🗂️ Repository Structure
- `notebooks/ETL_Pipeline.ipynb` → ETL data processing pipeline  
- `notebooks/Churn_Modelling.ipynb` → Model training and evaluation  
- `data/README.md` → Dataset information  
- `requirements.txt` → Project dependencies  

## 📊 Dataset
- Source: [Dataset link](https://www.kaggle.com/code/annastasy/brazilian-e-commerce-eda-nlp-ml/input?select=product_category_name_translation.csv)  
- Total records: 10,000 customer transactions  
- Key features: `customer_id`, `tenure`, `contract_type`, `monthly_charges`, `churn`

## 📈 Model Performance

### 🔹 Logistic Regression
- Accuracy: **78%**
- Precision: **74%**
- Recall: **70%**

### 🔹 Decision Tree
- Accuracy: **81%**
- Precision: **76%**
- Recall: **73%**

---

## 🛠️ Tech Stack
This project is built using the following tools and libraries:
- Python 3.9  
- Pandas, NumPy → data processing  
- Matplotlib, Seaborn → data visualization  
- scikit-learn → machine learning (Logistic Regression, Decision Tree)  
- Jupyter Notebook / Google Colab → model development  
- Git & GitHub → version control and collaboration  

---

## ✅ Conclusion
- The **Decision Tree** outperforms Logistic Regression  
  (Accuracy 81% vs 78%).  
- The model demonstrates solid recall for identifying potential churners.  
- Future improvements could include using **Random Forest** or **XGBoost**,  
  and feature enrichment from customer transaction data.
