# Diwali Sales Data Analysis

An Exploratory Data Analysis (EDA) project analyzing festive retail sales data to uncover customer purchasing patterns, demographic trends, and top-performing product categories.

---

## Project Overview
The goal of this project is to clean, process, and visualize a retail dataset of **11,251 transactions** across **15 attributes** to identify high-value customer segments and key revenue drivers during the Diwali festive season.

---

## Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

---

## Data Cleaning & Preprocessing
* **Dropped Null Columns:** Removed completely empty columns (`Status` and `unnamed1`).
* **Handled Missing Values:** Dropped 12 rows containing null values in the `Amount` column, resulting in **11,239 clean records**.
* **Data Type Conversion:** Converted the `Amount` column from `float64` to `int64` for cleaner numerical aggregation and visualization.

---

## Exploratory Data Analysis & Key Insights
* **Gender:** Female buyers outnumber male buyers in total order volume and exhibit significantly higher overall purchasing power.
* **Age Group:** Customers in the **26–35 years** age bracket generate the highest total sales and order counts, followed by the 36–45 and 18–25 age groups.
* **Marital Status:** Unmarried customers (`0`) account for higher order counts and total spending compared to married customers (`1`).
* **Top Performing States:** **Uttar Pradesh, Maharashtra, and Karnataka** lead in both total orders placed and overall revenue generated.
* **Occupation:** Professionals working in the **IT Sector, Healthcare, and Aviation** represent the highest-spending occupational segments.
* **Product Categories:** **Food, Clothing & Apparel, and Electronics & Gadgets** are the top revenue-generating product categories.

---

## Conclusion
Unmarried women aged **26–35 years** from **Uttar Pradesh, Maharashtra, and Karnataka** working in the **IT, Healthcare, and Aviation** sectors are the primary customer demographic and are most likely to purchase products from the **Food, Clothing & Apparel, and Electronics & Gadgets** categories.

---

## Repository Structure
```text
├── diwali_sales_analysis.ipynb   # Main Jupyter Notebook containing data cleaning & EDA
├── Diwali Sales Data.csv         # Dataset (11,251 records)
├── requirements.txt              # Python package dependencies
└── README.md                     # Project documentation
```

---

## How to Run Locally
1. **Clone the repository:**
```bash
git clone https://github.com/mrunmayeebuilds/diwali-sales-analysis.git
cd diwali-sales-analysis
```
2. **Install dependencies:**
```bash
pip install -r requirements.txt
```
3. **Launch Jupyter Notebook:**
```bash
jupyter notebook diwali_sales_analysis.ipynb
```
