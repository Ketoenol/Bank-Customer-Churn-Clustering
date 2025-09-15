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

##🧠 Methodology

1. Data preprocessing & feature scaling


2. Dimensionality reduction (PCA)


3. Clustering with DBSCAN


4. Evaluation using Silhouette Score


5. Visualization of customer segments



🚀 How to Run

1. Clone the repo:
   git clone https://github.com/Ketoenol/Bank-Customer-Churn-Clustering.git
cd Bank-Customer-Churn-Clustering

2. Install Dependencies:
   pip install -r requirements.txt

3. Open the Notebook:
   jupyter notebook Bank_Churn_Clustering.ipynb

4. Follow the notebook to explore clustering results.


##📈 Outcome

Identified distinct customer segments

Highlighted high-risk churn groups

Insights to improve customer retention strategies


   


