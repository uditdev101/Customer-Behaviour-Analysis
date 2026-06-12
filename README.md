# Customer Behaviour Analysis using Python, MySQL & Power BI

##  Project Overview

This project performs an end-to-end customer behaviour analysis using Python, MySQL, SQL, and Power BI. The objective is to transform raw shopping data into meaningful business insights by performing data cleaning, exploratory analysis, SQL-based querying, and interactive dashboard visualization.

The project demonstrates a complete analytics workflow:

Dataset → Python (Pandas) → MySQL Database → SQL Analysis → Power BI Dashboard

---

##  Objectives

- Analyze customer purchasing patterns and shopping behaviour.
- Understand revenue distribution across customer segments.
- Identify trends based on product categories, seasons, and purchase frequency.
- Measure the impact of discounts and promotional offers.
- Build an interactive dashboard for business decision-making.

---

##  Tools & Technologies Used

- Python
- Pandas
- Jupyter Notebook
- MySQL
- SQLAlchemy
- PyMySQL
- MySQL ODBC Connector
- Power BI

---

##  Project Workflow

### 1. Data Cleaning and Preparation (Python)

- Imported the raw customer shopping dataset.
- Performed data cleaning and preprocessing.
- Handled missing values and checked data quality.
- Transformed data using Python libraries.
- Exported the processed dataset into a MySQL database using SQLAlchemy.

File: `customer_shopping_behaviour_analysis.ipynb`

---

### 2. Database Management and SQL Analysis

The cleaned data was stored in MySQL, where SQL queries were used to perform business analysis, such as:

- Revenue analysis by gender.
- Revenue trends by product category.
- Seasonal purchase behaviour.
- Customer purchase frequency analysis.
- Discount usage analysis.
- Top products based on discount adoption and sales patterns.

File: `sql_queries.sql`

---

### 3. Interactive Dashboard Development (Power BI)

The MySQL database was connected to Power BI using the MySQL ODBC Connector. An interactive dashboard was created to visualize key insights using charts, cards, and filters.

Dashboard features:

- Revenue analysis.
- Customer demographic insights.
- Product performance analysis.
- Seasonal trends.
- Purchase frequency analysis.
- Discount impact analysis.

File: `Customer_Behaviour_Dashboard.pbix`

---

##  Repository Contents

| File/Folder | Description |
|------------|-------------|
| `data/` | Original customer behaviour dataset |
| `notebooks/` | Python data cleaning and preprocessing |
| `sql/` | SQL analysis queries |
| `powerbi/` | Power BI dashboard file |
| `report/` | Detailed project report |
| `README.md` | Project documentation |

---

##  Key Insights Generated

Some examples of insights obtained from the analysis:

- Customer groups contributed differently to total revenue.
- Certain product categories generated higher sales.
- Discount strategies influenced purchasing behaviour.
- Shopping patterns varied across seasons and customer segments.
- Purchase frequency provided insights into customer loyalty.

---

##  How to Run This Project

1. Open the Jupyter Notebook and execute the data preprocessing steps.
2. Configure the MySQL connection using SQLAlchemy and load the dataset into MySQL.
3. Execute SQL queries provided in the `.sql` file for additional analysis.
4. Open the Power BI `.pbix` file to explore the interactive dashboard.

---


##  Author

Developed as an end-to-end Data Analytics project using Python, SQL, MySQL, and Power BI.
