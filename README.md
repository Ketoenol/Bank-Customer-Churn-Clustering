# Bank Customer Churn — Clustering & Segmentation

This project applies **unsupervised learning techniques** (DBSCAN, PCA, and Silhouette Score) to segment bank customers based on demographic and financial features.  
The aim is to identify meaningful customer groups that can help the bank understand churn behavior and design better retention strategies.

---

## 📂 Project Structure
- `Bank_Churn_Clustering.ipynb` — Jupyter Notebook with full workflow (preprocessing, PCA, clustering, evaluation, visualization).
- `requirements.txt` — List of Python dependencies.
- `README.md` — Project documentation.
- `BankChurners.csv` — Dataset file (to be placed in the project folder).

---

## 📊 Dataset
We use a bank customer churn dataset (commonly available from Kaggle/UCI).  
Key columns include:

- **Demographics**: Age, Gender, Geography  
- **Account info**: CreditScore, Balance, Tenure, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary  
- **Churn label**: Exited (1 = churned, 0 = retained) — *not used in clustering*  

---

## 🔧 Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/bank-customer-churn-clustering.git
   cd bank-customer-churn-clustering
