# ☕ Dirty Cafe Sales — Data Cleaning & Analysis with Python

A practical data analytics project by KeDataLab demonstrating how to take a messy cafe sales dataset, clean it with Python, explore the data, and extract useful business insights.

The project is designed to reflect a common real-world analytics workflow: raw data → data cleaning → exploration → analysis → insights.

## Project Overview

Real-world datasets are rarely clean.

This project uses a deliberately messy cafe sales dataset containing issues such as missing values, inconsistent entries, incorrect data types, and invalid values.

The goal is to use Python and Pandas to transform the raw data into a dataset that can be reliably analyzed.

The analysis covers:

- Understanding the structure of a dataset

- Identifying missing and invalid values

- Cleaning and transforming data

- Working with categorical and numerical variables

- Handling dates

- Exploring sales patterns

- Identifying popular products

- Calculating sales metrics

- Extracting business insights from data

## Project Objectives

By completing this project, we aim to:

-  Understand the quality of raw sales data.

-  Identify problems that could affect analysis.

-  Clean and standardize the dataset.

-  Perform exploratory data analysis (EDA).

-  Analyze product and sales performance.

-  Communicate findings using Python visualizations.


7. Demonstrate a complete practical data analytics workflow.

## Dataset

The project uses the Dirty Cafe Sales dataset, which contains approximately 10,000 cafe transaction records.

The dataset includes information such as:

- Transaction ID

- Item

- Quantity

- Price Per Unit

- Total Spent

- Payment Method

- Location

- Transaction Date

The dataset intentionally contains data quality problems that make it suitable for practicing data cleaning.

Original dataset: Kaggle — Cafe Sales: Dirty Data for Cleaning Training

## Data Cleaning

The notebook demonstrates several common data-cleaning techniques using Pandas.

Some of the tasks include:

- Inspecting the dataset

- Checking data types

- Identifying missing values

- Identifying duplicate records

- Detecting invalid values

- Converting columns to appropriate data types

- Handling missing numerical values

- Handling missing categorical values

- Cleaning date columns

- Standardizing inconsistent data

- Creating new analytical columns

The objective is not simply to remove problematic rows, but to understand why the data is problematic and how it should be handled.


## Exploratory Data Analysis

After cleaning the dataset, the project explores questions such as:

## Product Performance

- Which products are sold most frequently?

- Which products generate the most revenue?

- What is the typical quantity purchased?

- How does product performance vary?

## Sales Performance

- What are the overall sales patterns?

- How do sales change over time?

- Which periods have higher or lower sales?

## Customer & Transaction Behaviour

- Which payment methods are most commonly used?

- How do transaction characteristics differ across categories?

- What patterns can be identified from the available data?

## Visualizations

The analysis uses Python visualizations to make patterns easier to understand.

## Examples include:

- Bar charts

- Histograms

- Pie charts

- Line charts

- Distribution plots

- Category comparisons

The focus is on using visualizations to answer business questions, rather than creating charts simply for presentation.

## Tools & Technologies

| Tool | Purpose |
| --- | --- |
| Python | Data analysis |


| Tool | Purpose |
| --- | --- |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Analysis environment |   |
| Git & GitHub | Version control and project sharing |

## Repository Structure

```
dirty-cafe-sales/
│
├── Data/
│ └── cafe sales dataset
│
├── dirty cafe sales analysis.ipynb
│
└── README.md
```

## How to Run the Project

## 1. Clone the repository

```
git clone https://github.com/KeDataLab/dirty-cafe-sales.git
```

## 2. Navigate into the project

cd dirty-cafe-sales

## 3. Install the required libraries

pip install pandas numpy matplotlib seaborn jupyter


## 4. Start Jupyter Notebook

jupyter notebook

## 5. Open the notebook

Open:

dirty cafe sales analysis.ipynb

Run the notebook cells from top to bottom.

## What You Will Learn

This project demonstrates an important principle in data analytics:

## Good analysis starts with good data.

Before creating dashboards or building machine-learning models, analysts need to understand the quality of their data and make appropriate decisions about missing, inconsistent and invalid values.

The project therefore focuses on the complete analytical process rather than jumping directly into visualization.

## Business Value

Although this is a learning project, the workflow represents tasks commonly performed by data analysts in real organizations.

The same process can be applied to:

- Retail sales

- Financial transactions

- Customer data

- Inventory records

- Marketing data

- Business operations

- E-commerce data

The objective is to turn raw transactional data into information that can support business decisions.
GitHub: https://github.com/KeDataLab

## If You Find This Project Useful

If this project helps you learn data cleaning and analysis, consider giving the repository a on GitHub and exploring the other KeDataLab projects.
