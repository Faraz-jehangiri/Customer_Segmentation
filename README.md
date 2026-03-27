<div align="center">

# 🛍️ Customer Segmentation
### Unsupervised Learning · K-Means Clustering · Dimensionality Reduction

<br>

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

<br>

> *"Not all customers are created equal — the data knows the difference."*

<br>

</div>

---

## 📌 Objective

Cluster mall customers based on their **annual income** and **spending behavior** using unsupervised machine learning. The goal is to uncover hidden patterns in customer data and translate them into **actionable marketing strategies** for each segment.

This project is part of the **DevelopersHub Corporation — Data Science & Analytics Advanced Internship (Task 2)**.

---

## 📂 Dataset

| Property | Detail |
|----------|--------|
| **Name** | Mall Customers Dataset |
| **File** | `Mall_Customers.csv` |
| **Records** | 200 customers |
| **Features** | CustomerID, Gender, Age, Annual Income (k$), Spending Score (1–100) |
| **Source** | Kaggle |

---

## 🧠 Approach

```
Raw Data
   │
   ▼
Exploratory Data Analysis (EDA)
   │  ├── Distribution plots
   │  ├── Gender breakdown
   │  └── Correlation heatmap
   │
   ▼
Preprocessing & Encoding
   │
   ▼
Optimal K Selection
   │  ├── Elbow Method (WCSS)
   │  └── Silhouette Score Analysis
   │
   ▼
K-Means Clustering (K = 5)
   │
   ▼
Dimensionality Reduction
   │  ├── PCA (2D projection)
   │  └── t-SNE (2D projection)
   │
   ▼
Cluster Profiling + Marketing Strategies
```

---

## 📊 Results

Five distinct customer segments were identified:

| Cluster | Profile | Label | Strategy |
|---------|---------|-------|----------|
| 0 | Low Income · Low Spending | 💤 Careful Spenders | Budget deals, value-for-money promos |
| 1 | High Income · Low Spending | 💼 Untapped Potential | Premium previews, personalized offers |
| 2 | Mid Income · Mid Spending | 😊 Average Customers | Seasonal campaigns, bundled discounts |
| 3 | Low Income · High Spending | 🛍️ Impulsive Buyers | Flash sales, FOMO marketing |
| 4 | High Income · High Spending | 👑 Prime Customers | VIP memberships, luxury campaigns |

**Silhouette Score: ~0.55** — indicating well-separated, meaningful clusters.

---

## 📁 Repository Structure

```
Customer_Segmentation/
│
├── Task2_Customer_Segmentation.ipynb   # Full notebook with code, plots & insights
├── Mall_Customers.csv                  # Dataset
└── README.md                           # You are here
```

---

## ⚙️ Installation & Usage

```bash
# 1. Clone the repository
git clone https://github.com/Faraz-jehangiri/Customer_Segmentation.git
cd Customer_Segmentation

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

# 3. Launch the notebook
jupyter notebook Task2_Customer_Segmentation.ipynb
```

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **Pandas & NumPy** — data manipulation
- **Matplotlib & Seaborn** — visualizations
- **Scikit-learn** — K-Means, PCA, t-SNE, StandardScaler, Silhouette Score

---

## 👤 Author

**Faraz Jehangiri**
Data Science Intern @ DevelopersHub Corporation
BS Computer Science — SSUET, Karachi

[![GitHub](https://img.shields.io/badge/GitHub-Faraz--jehangiri-181717?style=flat-square&logo=github)](https://github.com/Faraz-jehangiri)

---

<div align="center">
<sub>DevelopersHub Corporation · Data Science & Analytics Internship · Task 2</sub>
</div>
