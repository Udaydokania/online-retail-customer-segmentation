# Online Retail Customer Segmentation 📊

## 📌 Project Overview
This project performs an in-depth customer analytics study using a large-scale online retail dataset. The analysis centers on implementing **RFM (Recency, Frequency, Monetary)** modeling to evaluate customer behavior. [cite_start]By applying **K-Means Clustering**, the project segments the customer base into distinct, actionable groups to facilitate data-driven marketing and retention strategies [cite: 3110-3118].

## 🛠 Tech Stack
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** Scikit-learn (StandardScaler)
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## 📖 Data Dictionary
The analysis utilizes a comprehensive retail dataset with the following key attributes:
| Column | Description |
| :--- | :--- |
| **Invoice** | [cite_start]A 6-digit unique number assigned to each transaction[cite: 1]. |
| **StockCode** | [cite_start]A unique identifier for each distinct product[cite: 1]. |
| **Description** | [cite_start]The name of the product[cite: 1]. |
| **Quantity** | [cite_start]The quantities of each product per transaction[cite: 1]. |
| **InvoiceDate** | [cite_start]The day and time when a transaction was generated[cite: 1]. |
| **Price** | [cite_start]Product price per unit in sterling[cite: 1]. |
| **Customer ID** | [cite_start]A unique identifier assigned to each customer[cite: 1]. |
| **Country** | [cite_start]The name of the country where a customer resides[cite: 1]. |

## 🧹 Data Cleaning & Preprocessing (Day 2 Update)
The second phase of the project focused on transforming raw transactional data into a clean, model-ready format:
- [cite_start]**Dataset Ingestion:** Loaded a large-scale retail dataset containing over 500,000 records[cite: 2].
- [cite_start]**Missing Value Management:** Conducted a thorough audit of null values, specifically addressing gaps in `Customer ID` and `Description`[cite: 1947, 1999].
- [cite_start]**Anomaly Filtration:** Filtered out negative `Quantity` and `Price` entries representing cancellations or debts to ensure model accuracy [cite: 2073-2084].
- [cite_start]**Data Quality Assurance:** After rigorous cleaning, approximately **77.3%** of the original data was retained for the clustering phase [cite: 2350-2351].

## 📂 Repository Structure
- `dataset_link.txt`: External link to the primary retail dataset.
- `requirements.txt`: Environment dependencies.
- `.gitignore`: Python-specific exclusion rules.
- `README.md`: Project documentation and progress updates.
