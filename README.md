# customer_behavior_analysis
# Data Analytics Project

## Overview

This project demonstrates an end-to-end data analytics workflow, from data extraction and cleaning to visualization and reporting. The objective was to transform raw data into actionable insights using Python, PostgreSQL, and Power BI.

## Dataset

The dataset contains business-related records used for analysis and reporting. It includes multiple attributes such as customer information, transactions, sales metrics, and other relevant business indicators.

### Key Features

* Structured tabular data
* Multiple variables for analysis
* Suitable for data cleaning, SQL querying, and dashboard creation

## Tools & Technologies

* **Python** – Data loading, cleaning, and exploratory data analysis (EDA)
* **Pandas** – Data manipulation and transformation
* **Matplotlib / Seaborn** – Data visualization during EDA
* **PostgreSQL** – Data storage and SQL analysis
* **Power BI** – Interactive dashboard development
* **Gamma** – Presentation creation
* **Jupyter Notebook** – Development environment

## Project Workflow

### 1. Data Loading

* Imported dataset into Python using Pandas.
* Inspected data structure, columns, and data types.

### 2. Exploratory Data Analysis (EDA)

* Analyzed data distributions and trends.
* Identified missing values and outliers.
* Created visualizations to understand key patterns.

### 3. Data Cleaning

* Handled missing values.
* Removed duplicates.
* Corrected data types and formatting issues.
* Prepared the dataset for analysis.

### 4. PostgreSQL Analysis

* Loaded cleaned data into PostgreSQL.
* Wrote SQL queries to:

  * Aggregate data
  * Identify trends
  * Calculate key metrics
  * Generate business insights

### 5. Power BI Dashboard

Developed an interactive dashboard featuring:

* KPI Summary
* Trend Analysis
* Category Performance
* Filters and Slicers
* Visual Insights

### 6. Reporting

* Created a detailed analytical report summarizing findings.
* Highlighted business recommendations and key observations.

### 7. Presentation

* Developed a professional presentation using Gamma.
* Presented project objectives, methodology, insights, and recommendations.

## Dashboard Highlights

* Interactive visualizations
* User-friendly navigation
* Dynamic filtering
* Business-focused KPIs
* Clear data storytelling

## Key Results

* Identified major trends and patterns in the dataset.
* Improved data quality through cleaning and validation.
* Generated actionable insights using SQL and Power BI.
* Delivered findings through a report and executive presentation.

## Project Structure

```text
project/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   └── eda_and_cleaning.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── reports/
│   └── final_report.pdf
│
├── presentation/
│   └── gamma_presentation.pdf
│
└── README.md
```

## How to Run

### Prerequisites

* Python 3.x
* PostgreSQL
* Power BI Desktop

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/project-name.git
```

2. Install required packages:

```bash
pip install -r requirements.txt
```

3. Open and run the Jupyter Notebook:

```bash
jupyter notebook
```

4. Load the cleaned dataset into PostgreSQL.

5. Execute SQL scripts from the `sql` folder.

6. Open the Power BI file (`.pbix`) to explore the dashboard.

## Future Improvements

* Automate ETL processes.
* Deploy dashboard to Power BI Service.
* Integrate real-time data sources.
* Add predictive analytics and machine learning models.

## Author

Manik Adhikari

Data Analytics Portfolio Project



