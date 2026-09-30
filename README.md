# 🪔 Diwali Sales Analysis

**Exploratory Data Analysis (EDA)** of Diwali sales data using **Python (Pandas, Matplotlib, Seaborn)**.
The project finds out **which customers, states and product categories drive the most sales** during the Diwali season.

## 📌 Objective
**Understand customer behaviour to help improve sales**, by analysing:
**Gender • Age Group • State • Marital Status • Occupation • Product Category**

## 🛠️ Tools & Libraries
**Python 3**, **NumPy**, **Pandas**, **Matplotlib**, **Seaborn**, **Jupyter Notebook**

## 📂 Project Structure
```
Diwali-Sales-Analysis/
├── Diwali_Sales_Analysis.ipynb   # Main analysis notebook
├── Diwali Sales Data.csv         # Dataset
├── requirements.txt
├── .gitignore
└── README.md
```

## 🔄 Workflow
1. **Data Cleaning**: dropped blank columns (`Status`, `unnamed1`), **removed null values**, converted `Amount` to **integer**.
2. **Descriptive Statistics**: summary of **Age, Orders and Amount** using `describe()`.
3. **EDA & Visualisation**: **Gender, Age Group, State, Marital Status, Occupation, Product Category, Product ID**.
4. **Extra Analysis**: **correlation heatmap**, **average spend per category**, **occupation × gender sales**, **age-group share of total sales**.

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
