# Customer Churn Prediction 🚀

![Customer Churn Prediction](assets/banner.png)

## 📖 Deskripsi
Perusahaan sering kehilangan pelanggan tanpa disadari.  
Proyek ini membangun **ETL pipeline** dan **machine learning model** (Logistic Regression & Decision Tree)  
untuk memprediksi pelanggan yang berpotensi churn berdasarkan riwayat transaksi.

## 🗂️ Struktur Repository
- `notebooks/ETL_Pipeline.ipynb` → ETL pipeline
- `notebooks/Churn_Modelling.ipynb` → Modelling churn
- `data/README.md` → Info dataset
- `requirements.txt` → Library

## 📊 Dataset
- Sumber: [Link ke dataset](https://drive.google.com/...)  
- Jumlah data: 10.000 transaksi pelanggan  
- Fitur penting: `customer_id, tenure, contract_type, monthly_charges, churn`


## 📈 Hasil Model

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
Project ini dibuat dengan tools & library berikut:

- Python 3.9
- Pandas, NumPy → data processing
- Matplotlib, Seaborn → visualisasi
- scikit-learn → machine learning (Logistic Regression, Decision Tree)
- Jupyter Notebook → development
- Google Colab → eksekusi notebook di cloud
- Git & GitHub → version control & kolaborasi

---

## ✅ Kesimpulan
- **Decision Tree** memiliki performa lebih baik dibanding Logistic Regression  
  (Accuracy 81% vs 78%).  
- Recall model cukup baik untuk mendeteksi pelanggan yang berpotensi churn.  
- Project ini bisa dikembangkan lebih lanjut dengan model lain (Random Forest, XGBoost)  
  atau penambahan fitur baru dari data transaksi pelanggan.


