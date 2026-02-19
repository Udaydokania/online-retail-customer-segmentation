# Online Retail Customer Segmentation 📊

## 📌 Project Overview
This project performs an in-depth customer analytics study using an online retail dataset. The analysis centers on implementing **RFM (Recency, Frequency, Monetary)** modeling to evaluate customer behavior. [cite_start]By applying **K-Means Clustering**, the project segments the customer base into distinct groups—such as **NURTURE**, **RETAIN**, and **RE-ENGAGE**—to facilitate data-driven marketing strategies [cite: 3110-3118].

## 🛠 Tech Stack
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** Scikit-learn (K-Means, StandardScaler)
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## 📖 Data Dictionary
[cite_start]The analysis utilizes a comprehensive retail dataset with the following key attributes[cite: 1943]:
| Column | Description |
| :--- | :--- |
| **Invoice** | [cite_start]A 6-digit unique number assigned to each transaction[cite: 1943]. |
| **StockCode** | [cite_start]A unique identifier for each distinct product[cite: 1943]. |
| **Description** | [cite_start]The name of the product[cite: 1943]. |
| **Quantity** | [cite_start]The quantities of each product per transaction[cite: 1943]. |
| **InvoiceDate** | [cite_start]The day and time when a transaction was generated[cite: 1943]. |
| **Price** | [cite_start]Product price per unit in sterling[cite: 1943]. |
| **Customer ID** | [cite_start]A unique identifier assigned to each customer[cite: 1943]. |
| **Country** | [cite_start]The name of the country where a customer resides[cite: 1943]. |

## 📂 Repository Structure
- `requirements.txt`: Environment dependencies.
- `.gitignore`: Python-specific exclusion rules.
- `README.md`: Project documentation and overview.
