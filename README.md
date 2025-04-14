# 📘 Value Group Portrait – Customer Segmentation with K-Means

## 📌 Overview

This project focuses on **customer segmentation** using **K-Means clustering** based on key behavioral and demographic features. The goal is to uncover distinct customer groups by computing:

- **Recency** – How recently a customer made a purchase  
- **Frequency** – How often they purchase  
- **Monetary Value** – How much they spend

These RFM metrics are engineered from transactional data and used to identify behavioral segments for better targeting and strategy.

---

## 🔍 Exploratory Data Analysis (EDA)

The dataset contains:
- 135,080 missing `CustomerID`s  
- 1,454 missing `Description`s  

Insights:
- Missing `CustomerID`s can be problematic for grouping but might be inferred via `InvoiceNo`.
- Initial visualization and checks help assess data quality and distribution.

---

## ⚙️ Methodology

- **Clustering Algorithm**: K-Means  
  Chosen for its simplicity and effectiveness with numerical features.
- **Features Used**:  
  - Recency  
  - Frequency  
  - Monetary value  
- **Steps**:
  1. Data Cleaning
  2. Feature Engineering (RFM)
  3. Scaling
  4. Optimal K selection via Elbow Method
  5. K-Means clustering
  6. Cluster interpretation and visualization

---

## 📈 Results

Each customer is assigned to a cluster that reflects their behavior profile. These insights can help in:
- Targeted marketing campaigns
- Customer retention strategies
- Personalized communication

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (for K-Means and scaling)
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-repo/value-group-portrait.git
   cd value-group-portrait
   ```

2. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   Open `regression.ipynb` in Jupyter and run all cells.

---

