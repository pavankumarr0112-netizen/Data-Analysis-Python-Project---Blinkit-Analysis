# Data-Analysis-Python-Project---Blinkit-Analysis

## 📌 Project Overview

This project focuses on performing data analysis on the Blinkit sales dataset using Python. The main objective is to understand sales performance, product distribution, and outlet characteristics through data cleaning, exploration, and visualization.

The notebook covers complete data analysis steps, from importing raw data to generating business insights using charts and KPIs.

---

## 🛠 Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📂 Project Workflow

### 1️⃣ Import Libraries

The required libraries such as Pandas, NumPy, Matplotlib, and Seaborn are imported for data manipulation and visualization.

### 2️⃣ Load Dataset

The dataset (`blinkit_data.csv`) is loaded using `pd.read_csv()`.

### 3️⃣ Initial Data Exploration

Basic data exploration is performed:

* `head()` and `tail()` to view sample data
* `shape` to check rows and columns
* `columns` to list all column names
* `dtypes` to understand data types

### 4️⃣ Data Cleaning

Data cleaning steps include:

* Checking unique values
* Standardizing inconsistent values in the **Item Fat Content** column
* Replacing short forms like "LF" and "low fat" with "Low Fat"
* Ensuring consistent category labels

This ensures better accuracy in analysis and visualization.

---

## 📊 Business Requirements & KPI Analysis

The notebook includes multiple business-focused visualizations:

### 1. Total Sales by Fat Content

Shows how different fat content categories contribute to overall sales.

### 2. Total Sales by Item Type

Analyzes which product categories generate the highest revenue.

### 3. Fat Content by Outlet for Total Sales

Breaks down how outlet types perform based on item fat categories.

### 4. Total Sales by Outlet Establishment Year

Displays sales distribution based on outlet establishment year.

### 5. Sales by Outlet Size

Visualizes how outlet size impacts sales performance (Pie Chart).

### 6. Sales by Outlet Location Type

Shows total sales across different location categories (Bar Chart).

---

## 📈 Key Insights Generated

* Identification of top-performing product categories
* Comparison of sales across outlet sizes and locations
* Impact of item fat content on total sales
* Sales performance based on outlet establishment year

---

## 🎯 What This Project Demonstrates

* Basic to intermediate data analysis skills
* Data cleaning and preprocessing techniques
* Business KPI understanding
* Data visualization using Matplotlib and Seaborn
* Ability to convert raw data into meaningful business insights

---

## 🚀 Conclusion

This project demonstrates how raw retail data can be transformed into actionable insights through structured data analysis. It highlights practical data cleaning techniques and business-driven visualization approaches.
