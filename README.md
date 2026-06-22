# 📊 Customer Behavior Analysis

## 📖 Overview

**Customer Behavior Analysis** is an end-to-end data analytics project that explores customer purchasing patterns and preferences using **Python, MySQL, and Power BI**. The project involves data preprocessing, exploratory data analysis (EDA), SQL-based querying, and interactive dashboard creation to uncover meaningful insights and support data-driven business decisions. The findings are summarized through a professional report and presentation created using **Gamma**.

---

## 📁 Dataset

* **Source:** Customer Behavior Analysis Dataset
* **Type:** Customer demographics and purchasing behavior data
* **Size:** **3,900 records × 18 columns**
* **Description:** The dataset contains **18 features** related to customer demographics, purchase history, product preferences, payment methods, and review ratings. It was used for data cleaning, exploratory data analysis (EDA), SQL querying, and Power BI dashboard development. Missing values were present only in the **`Review Rating`** column and were imputed using the **median** to maintain data quality.

---

## 🛠️ Tools & Technologies

* **Python** – Data loading, cleaning, and analysis
* **Pandas & NumPy** – Data manipulation
* **Matplotlib & Seaborn** – Data visualization
* **MySQL** – SQL querying and database analysis
* **Power BI** – Interactive dashboard development
* **Gamma** – Presentation creation
* **Jupyter Notebook** – Data analysis and experimentation

---

## 🔄 Project Workflow

### 1. Data Loading

* Import the dataset into Python.
* Inspect the data structure and column information.

### 2. Exploratory Data Analysis (EDA)

* Generate summary statistics.
* Analyze customer demographics and purchasing behavior.
* Visualize trends and relationships using charts.

### 3. Data Cleaning

* Handle missing values and duplicates.
* Correct inconsistent data formats.
* Impute missing values in the **`Review Rating`** column using the median.

### 4. SQL Analysis (MySQL)

* Load the cleaned dataset into MySQL.
* Execute SQL queries to answer business questions.
* Perform aggregations, filtering, and trend analysis.

### 5. Dashboard Development

* Connect MySQL data to Power BI.
* Build interactive dashboards with KPIs, charts, and filters.
* Present customer insights through visual analytics.

### 6. Report & Presentation

* Prepare a detailed analytics report.
* Create a presentation using Gamma to communicate key findings and recommendations.

---

## 📈 Dashboard Features

* Key Performance Indicators (KPIs)
* Customer demographics analysis
* Purchase trend visualization
* Product category insights
* Interactive filters and slicers
* Business-focused visual reports

---

## 📊 Results

* Cleaned and prepared the dataset for analysis.
* Performed comprehensive EDA to identify customer behavior patterns.
* Used MySQL queries to extract actionable business insights.
* Developed an interactive Power BI dashboard for visualization.
* Delivered findings through a professional report and Gamma presentation.

---

## ▶️ How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/Nithya-47/Customer_Behavior_Analysis.git
   ```

2. **Navigate to the project directory**

   ```bash
   cd Customer_Behavior_Analysis
   ```

3. **Open `Customer_Shopping_Behavior_Analysis.ipynb`**

   * Load the dataset
   * Perform EDA
   * Clean and preprocess the data
   * Prepare the data for SQL analysis

4. **Load the cleaned data into MySQL**

   * Create a MySQL database
   * Import the processed dataset
   * Run `customer_behavior_sql_queries.sql` to answer business questions

5. **Open the Power BI dashboard**

   * Launch `customer_behavior_dashboard.pbix`
   * Explore interactive visualizations and KPIs

6. **Review the project deliverables**

   * Read the analytics report
   * View the Gamma presentation summarizing key insights

---

## 📂 Project Structure

```text
Customer_Behavior_Analysis/
│── Customer_Shopping_Behavior_Analysis.ipynb
│── customer_behavior_sql_queries.sql
│── customer_behavior_dashboard.pbix
│── dataset/
│── report/
│── presentation/
└── README.md
```
