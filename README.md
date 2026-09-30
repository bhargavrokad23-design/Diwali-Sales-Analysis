# 🪔 Diwali Sales Analysis

**Exploratory Data Analysis (EDA)** of Diwali sales data using **Python (Pandas, Matplotlib, Seaborn)**.
The project finds out **which customers, states and product categories drive the most sales** during the Diwali season.

## 📌 Objective
**Understand customer behaviour to help improve sales**, by analysing:
**Gender • Age Group • State • Marital Status • Occupation • Product Category**

## 🛠️ Tools & Libraries
* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📂 Project Structure
```
Diwali-Sales-Analysis/
├── Diwali_Sales_Analysis.ipynb   # Main analysis notebook
├── Diwali Sales Data.csv         # Dataset
├── requirements.txt
├── .gitignore
└── README.md
```

## 🧾 What Was Done

### 1. Data Loading & Understanding
- **Imported** the required libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`.
- **Loaded the dataset** (`Diwali Sales Data.csv`) using `pd.read_csv()` with `unicode_escape` encoding.
- **Explored the data** using `df.shape`, `df.head()`, `df.info()` and `df.columns` to understand the size, columns and data types.

### 2. Data Cleaning
- **Dropped unrelated/blank columns**: `Status` and `unnamed1`.
- **Checked null values** using `pd.isnull(df).sum()` and **removed them** using `dropna()`.
- **Changed data type** of the `Amount` column from float to **integer**.
- **Renamed a column** (`Marital_Status` → `Shaadi`) to practise the `rename()` method.

### 3. Descriptive Statistics
- Used `describe()` on the full dataset and on **Age, Orders and Amount** to get **count, mean, std, min, max and quartiles**.

### 4. Exploratory Data Analysis (EDA)
Each column was analysed with **count plots** (number of buyers) and **bar plots** (total sales amount):

| Column | What was analysed | Finding |
|---|---|---|
| **Gender** | Buyer count and total amount spent | **Women buy more and spend more** |
| **Age Group** | Buyer count by gender, total amount | **26–35 age group** is the biggest |
| **State** | Top 10 states by orders and by sales | **UP, Maharashtra, Karnataka** lead |
| **Marital Status** | Buyer count, amount by gender | **Married women** spend the most |
| **Occupation** | Buyer count and total amount | **IT, Healthcare, Aviation** lead |
| **Product Category** | Count and top 10 by amount | **Food, Clothing, Electronics** lead |
| **Product ID** | Top 10 most sold products | Best-selling individual products identified |

### 5. Extra Analysis
- **Correlation heatmap** of Age, Marital Status, Orders and Amount.
- **Average spend** per product category (top 10).
- **Sales by Occupation × Gender** (top 10 combinations).
- **Share of total sales** by age group (pie chart).

### 6. Conclusion
- Combined all findings into **one customer profile** of the most likely Diwali buyer (see below).

## 📊 Key Insights
- 👩 Most buyers are **women**, and their **total spending is higher than men's**.
- 🎂 The **26–35 age group** has the **most buyers**.
- 📍 **Uttar Pradesh, Maharashtra and Karnataka** lead in **orders and sales**.
- 💍 **Married women** are the **biggest spenders**.
- 💼 Most buyers work in **IT, Healthcare and Aviation**.
- 🛍️ Top-selling categories: **Food, Clothing and Electronics**.

## ✅ Conclusion
> **Married women aged 26–35** from **Uttar Pradesh, Maharashtra and Karnataka**, working in **IT, Healthcare or Aviation**, are the **most likely to buy Food, Clothing and Electronics** products during Diwali.

## ▶️ How to Run
```bash
git clone https://github.com/<your-username>/Diwali-Sales-Analysis.git
cd Diwali-Sales-Analysis
pip install -r requirements.txt
jupyter notebook Diwali_Sales_Analysis.ipynb
```

## 👤 Author
**Bhargav Rokad**
GitHub: [bhargavrokad23](https://github.com/bhargavrokad23-design)
