# Python-Project-for-Data-Analysis

This project performs **Exploratory Data Analysis (EDA)** on a Diwali sales dataset to uncover customer purchasing behavior and sales trends. The analysis focuses on demographic factors, product categories, and regional insights to help understand what drives higher sales during the Diwali season.

---

## 📌 Project Overview

The notebook analyzes Diwali sales data using Python data analysis and visualization libraries. Key objectives include:

- Cleaning and preprocessing the dataset  
- Understanding customer demographics  
- Identifying top-performing product categories and products  
- Analyzing sales patterns by gender, age group, occupation, and state  

---

## 📂 Dataset

- **File name:** `Diwali Sales Data.csv`
- **Encoding:** UTF-8 (with encoding errors ignored)
- **Key columns include:**
  - Gender
  - Age Group
  - State
  - Marital Status
  - Occupation
  - Product Category
  - Product ID
  - Orders
  - Amount

---

## 🛠️ Tools & Libraries Used

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔄 Data Cleaning Steps

- Removed unnecessary columns (`Status`, `unnamed1`)
- Handled missing values by dropping null entries
- Verified data types and dataset shape
- Ensured clean and consistent data for analysis

---

## 📊 Analysis & Visualizations

The notebook includes visual analysis such as:

- Sales distribution by gender
- Age group vs purchase amount
- State-wise total sales
- Occupation-based purchasing trends
- Product category-wise sales
- Top 10 most sold products by number of orders

All visualizations are created using **Matplotlib** and **Seaborn**.

---

## 🔍 Key Insights

- Married women aged **26–35 years** are the highest contributors to sales
- Customers from **Uttar Pradesh, Maharashtra, and Karnataka** generate the most revenue
- Occupations such as **IT, Healthcare, and Aviation** show higher purchasing power
- **Food, Clothing, and Electronics** are the most popular product categories
- A small number of products account for a large portion of total orders

---

## ▶️ How to Run the Project

1. Clone the repository or download the files
2. Place `Diwali Sales Data.csv` in the same directory as the notebook
3. Install required libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn
