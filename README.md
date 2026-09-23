# ☕ Dirty Cafe Sales — Data Cleaning & Analysis
with Python
A practical data analytics project by KeDataLab demonstrating how to take a messy cafe sales dataset,
clean it with Python, explore the data, and extract useful business insights.
The project is designed to reflect a common real-world analytics workflow: raw data → data cleaning →
exploration → analysis → insights.
## 📌 Project Overview
Real-world datasets are rarely clean.
This project uses a deliberately messy cafe sales dataset containing issues such as missing values,
inconsistent entries, incorrect data types, and invalid values.
The goal is to use Python and Pandas to transform the raw data into a dataset that can be reliably
analyzed.
The analysis covers:
1. Understanding the structure of a dataset
2. Identifying missing and invalid values
3. Cleaning and transforming data
4. Working with categorical and numerical variables
5. Handling dates
6. Exploring sales patterns
7. Identifying popular products
8. Calculating sales metrics
9. Extracting business insights from data
## 🎯 Project Objectives
By completing this project, we aim to:
1. Understand the quality of raw sales data.
2. Identify problems that could affect analysis.
3. Clean and standardize the dataset.
4. Perform exploratory data analysis (EDA).
5. Analyze product and sales performance.
6. Communicate findings using Python visualizations.
7. Demonstrate a complete practical data analytics workflow.
## 📊 Dataset
The project uses the Dirty Cafe Sales dataset, which contains approximately 10,000 cafe transaction
records.
The dataset includes information such as:
1. Transaction ID
2. Item
3. Quantity
4. Price Per Unit
5. Total Spent
6. Payment Method
7. Location
8. Transaction Date
The dataset intentionally contains data quality problems that make it suitable for practicing data cleaning.
Original dataset: Kaggle — Cafe Sales: Dirty Data for Cleaning Training
🧹 Data Cleaning
The notebook demonstrates several common data-cleaning techniques using Pandas.
Some of the tasks include:
1. Inspecting the dataset
2. Checking data types
3. Identifying missing values
4. Identifying duplicate records
5. Detecting invalid values
6. Converting columns to appropriate data types
7. Handling missing numerical values
8. Handling missing categorical values
9. Cleaning date columns
10. Standardizing inconsistent data
11. Creating new analytical columns
The objective is not simply to remove problematic rows, but to understand why the data is problematic
and how it should be handled.
## 🔎 Exploratory Data Analysis
After cleaning the dataset, the project explores questions such as:
### Product Performance
1. Which products are sold most frequently?
2. Which products generate the most revenue?
3. What is the typical quantity purchased?
4. How does product performance vary?
### Sales Performance
1. What are the overall sales patterns?
2. How do sales change over time?
3. Which periods have higher or lower sales?
### Customer & Transaction Behaviour
1. Which payment methods are most commonly used?
2. How do transaction characteristics differ across categories?
3. What patterns can be identified from the available data?
## 📈 Visualizations
The analysis uses Python visualizations to make patterns easier to understand.
Examples include:
1. Bar charts
2. Histograms
3. Pie charts
4. Line charts
5. Distribution plots
6. Category comparisons
The focus is on using visualizations to answer business questions, rather than creating charts simply for
presentation.
## 🛠️ Tools & Technologies
ToolPurpose
PythonData analysis
ToolPurpose
PandasData manipulation and cleaning
NumPyNumerical operations
MatplotlibData visualization
SeabornStatistical visualization
Jupyter NotebookAnalysis environment
Git & GitHubVersion control and project sharing
## 📁 Repository Structure
dirty-cafe-sales/
│
├── Data/
│
└── cafe sales dataset
│
├── dirty cafe sales analysis.ipynb
│
└── README.md
## 🚀 How to Run the Project
1. Clone the repository
git clone https://github.com/KeDataLab/dirty-cafe-sales.git
2. Navigate into the project
cd dirty-cafe-sales
3. Install the required libraries
pip install pandas numpy matplotlib seaborn jupyter
4. Start Jupyter Notebook
jupyter notebook
5. Open the notebook
Open:
dirty cafe sales analysis.ipynb
Run the notebook cells from top to bottom.
### 🧠 What You Will Learn
This project demonstrates an important principle in data analytics:
Good analysis starts with good data.
Before creating dashboards or building machine-learning models, analysts need to understand the quality
of their data and make appropriate decisions about missing, inconsistent and invalid values.
The project therefore focuses on the complete analytical process rather than jumping directly into
visualization.
### 💼 Business Value
Although this is a learning project, the workflow represents tasks commonly performed by data analysts in
real organizations.
The same process can be applied to:
1. Retail sales
2. Financial transactions
3. Customer data
4. Inventory records
5. Marketing data
6. Business operations
7. E-commerce data
The objective is to turn raw transactional data into information that can support business decisions.
