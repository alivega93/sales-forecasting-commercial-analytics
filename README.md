# Sales Forecasting & Commercial Analytics

End-to-end sales analytics project focused on data cleaning, exploratory analysis, dashboarding, cloud analytics and sales prediction to support commercial decision-making.

## Business Problem

How can historical sales data be leveraged to identify commercial patterns, evaluate regional performance and generate future sales estimates to improve strategic decision-making?

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- SQL Server
- Looker Studio
- AWS S3
- AWS Athena
- Excel

## Project Architecture

Data Sources → Excel / SQL Server → Python Processing → AWS Storage → Dashboard & Reporting

The project follows an end-to-end analytics workflow including data extraction, cleaning, transformation, exploratory analysis, machine learning modeling and cloud querying. :contentReference[oaicite:0]{index=0}

## Methodology

### 1. Data Exploration in Excel

Initial exploration was performed using pivot tables, charts and descriptive analysis to identify:

- Sales trends
- Regional behavior
- Weekly patterns
- Top performing products

### 2. SQL Server Commercial Analysis

SQL queries were developed to analyze:

- Sales by region
- Top products
- Weekly trends
- Regional averages

### 3. Data Cleaning & Transformation with Python

Python and Pandas were used to:

- validate data types
- review null values and duplicates
- transform numerical variables
- generate derived metrics

A new feature (`VALUE_PER_UNIT`) was created to support business analysis. :contentReference[oaicite:1]{index=1}

### 4. Exploratory Data Analysis (EDA)

EDA techniques were used to analyze:

- sales distributions
- outliers
- regional comparisons
- temporal trends
- top selling products

### 5. Interactive Dashboard in Looker Studio

An interactive dashboard was developed including:

- dynamic filters
- KPI monitoring
- regional distribution analysis
- trend visualization
- product performance analysis

### 6. Machine Learning — Sales Prediction

A Linear Regression model was implemented to estimate future sales using historical commercial behavior and numerical predictors. :contentReference[oaicite:2]{index=2}

### 7. Cloud Analytics with AWS

AWS services were used for:

- Amazon S3 storage
- Athena SQL querying
- cloud-based analytics workflow

## Key Insights

- Significant differences exist between commercial regions.
- A reduced group of products concentrates a large portion of sales.
- Weekly sales behavior presents identifiable temporal patterns.
- Data quality preparation enabled reliable analytical modeling.
- Dashboarding improved interpretation and business monitoring. :contentReference[oaicite:3]{index=3}

Author

Ali Vega
Cloud Computing / Data Analytics

## Repository Structure

```text
sales-forecasting-commercial-analytics/
│
├── README.md
├── report/
├── datasets/
├── notebooks/
├── screenshots/
└── assets/

