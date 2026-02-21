# Online Retail Customer Segmentation 📊

## 📌 Project Overview
This project performs an in-depth customer analytics study using a large-scale online retail dataset. The primary objective is to implement **RFM (Recency, Frequency, Monetary)** modeling to evaluate customer purchasing behavior. [cite_start]By applying **K-Means Clustering**, the project segments the customer base into distinct, actionable groups to facilitate data-driven marketing and retention strategies [cite: 3110-3118].

## 🛠 Tech Stack
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** Scikit-learn (K-Means, StandardScaler)
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Environment:** Jupyter Notebook

## 🧪 Machine Learning Workflow
1. [cite_start]**Data Cleaning:** Handled missing values and filtered out transactional anomalies (cancellations/bad debts), retaining **77.3%** of high-quality records for the model [cite: 2073-2084, 2350-2351].
2. [cite_start]**Feature Engineering:** Aggregated raw transactions into **RFM metrics** (Recency, Frequency, and Monetary Value) at the customer level [cite: 2471-2473].
3. [cite_start]**Clustering Logic:** Utilized the **Elbow Method** and **Silhouette Scores** to determine the optimal number of clusters[cite: 2769, 2775].
4. [cite_start]**Segmentation:** Grouped customers into specific behavioral categories including **RETAIN**, **NURTURE**, **RE-ENGAGE**, and **DELIGHT** [cite: 3110-3118].

## 📈 Key Findings & Insights
- [cite_start]**Optimal Clusters:** Based on Silhouette analysis, the customer base was most effectively segmented into 4 primary clusters [cite: 2785-2808].
- [cite_start]**Customer Profiles:** - **RETAIN:** High-frequency, high-spending customers who have shopped recently[cite: 3110].
  - [cite_start]**RE-ENGAGE:** Customers with high past value but low recent activity, targeted for win-back campaigns[cite: 3112].
  - [cite_start]**NURTURE:** Emerging customers with steady frequency who require engagement to increase their lifetime value[cite: 3114].
- [cite_start]**Visual Evidence:** Developed 3D scatter plots and violin plots to confirm clear separation between segments based on RFM distributions [cite: 2926, 2983-2994].

## 📂 Repository Structure
- `dataset_link.txt`: External link to the primary retail dataset (due to file size).
- `Online_Retail_Clustering.ipynb`: Full implementation of RFM modeling and K-Means.
- `Online_Retail_Analysis_Report.pdf`: Comprehensive project report with visualizations.
- `requirements.txt`: Environment dependencies.
- `.gitignore`: Python-specific exclusion rules.
