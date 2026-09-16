# Customer Behaviour Analysis

## Overview

This project analyzes customer purchasing behaviour using **Python, PostgreSQL, and Power BI**. The objective is to clean and explore the data, identify meaningful customer and sales patterns, perform SQL-based business analysis, and present the findings through an interactive Power BI dashboard and report.

## Dataset

The dataset contains customer transaction information, including fields related to:

* Customer information
* Purchase amount
* Product category
* Location
* Purchase behaviour
* Other relevant transaction attributes

The dataset was first loaded into Python for inspection, cleaning, and exploratory data analysis.

## Tools & Technologies

* **Python** – Data loading, cleaning, and EDA
* **Pandas & NumPy** – Data manipulation and analysis
* **Jupyter Notebook** – Python analysis
* **PostgreSQL** – SQL-based data analysis
* **Power BI** – Interactive dashboard and visualization
* **Excel/CSV** – Dataset handling and data storage

## Project Steps

### 1. Data Loading

* Imported the dataset into Python using Pandas.
* Inspected rows, columns, data types, and dataset structure.

### 2. Exploratory Data Analysis (EDA)

* Analyzed numerical and categorical variables.
* Checked distributions and customer behaviour patterns.
* Identified trends and potential data-quality issues.

### 3. Data Cleaning

* Handled missing values.
* Removed duplicate records where required.
* Corrected data types.
* Standardized and cleaned column values.
* Prepared the dataset for further analysis.

### 4. PostgreSQL Analysis

The cleaned data was loaded into PostgreSQL and analyzed using SQL queries.

Key SQL concepts used:

* `SELECT`, `WHERE`
* `GROUP BY`, `HAVING`
* Aggregate functions
* `CASE WHEN`
* Joins
* Subqueries
* Window functions
* Business-oriented analytical queries

### 5. Power BI Dashboard

Created an interactive Power BI dashboard to visualize important customer and purchasing insights.

The dashboard includes:

* KPI cards
* Customer behaviour analysis
* Purchase amount analysis
* Product/category analysis
* Interactive filters and slicers
* Charts and trend visualizations

### 6. Report

A report was prepared to summarize the analysis, key findings, and business insights obtained from Python, PostgreSQL, and Power BI.

## Dashboard

The Power BI dashboard provides an interactive view of customer behaviour and purchasing patterns.

**Dashboard Preview:**


```markdown
![Power BI Dashboard](Dashboard/dashboard.png)
```

## Results

The project helped identify important patterns in customer purchasing behaviour and provided data-driven insights through:

* Customer-level analysis
* Purchase amount analysis
* Category-level trends
* SQL-based business insights
* Interactive Power BI visualizations

The combination of **Python, SQL, and Power BI** demonstrates an end-to-end data analytics workflow from raw data to business insights.

## Project Structure

```text
Customer-Behaviour-Analysis/
│
├── Python/
│   └── customer_behaviour_analysis.ipynb
│
├── SQL/
│   └── customer_behaviour_analysis.sql
│
├── PowerBI/
│   └── customer_behaviour_dashboard.pbix
│
├── Dashboard/
│   └── dashboard.png
│
├── Report/
│   └── project_report.pdf
│
└── README.md
```

## How to Run

### Python

1. Install Python and Jupyter Notebook.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the `.ipynb` file in Jupyter Notebook.
4. Update the dataset path if required.
5. Run the notebook cells sequentially.

### PostgreSQL

1. Install PostgreSQL.
2. Create a database.
3. Import/load the dataset.
4. Open the SQL file from the `SQL` folder.
5. Execute the queries in PostgreSQL.

### Power BI

1. Install Power BI Desktop.
2. Open the `.pbix` file.
3. Update the data source path if required.
4. Refresh the dataset.
5. Explore the interactive dashboard.

## Key Skills Demonstrated

**Python | Pandas | EDA | Data Cleaning | PostgreSQL | SQL | Power BI | Data Visualization | Business Analysis**

---

**Author:** Mamta Verma
**Project:** Customer Behaviour Analysis
**Tools:** Python | PostgreSQL | Power BI
