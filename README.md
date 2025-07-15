# DATA-CLEANING-WITH-PYSPARK

*COMPANY*: CODTECH IT SOLUTIONS.

*NAME*: ROHIT PAHADIA

*INTERN ID*: CT04DG1490

*DOMAIN*: BIG DATA

*DURATION*: 4 WEEKS

*DESCRIPTION*:
📌 Project Title:
Use PySpark to Clean and Preprocess a Large Dataset, Handling Missing Values and Duplicates

🧾 Project Description:
This project focuses on a fundamental step in any data science or big data pipeline — data cleaning and preprocessing. Using Apache PySpark, this project demonstrates how to handle missing values, duplicate records, and create a clean dataset ready for analysis or machine learning tasks.

Working with large-scale data requires tools that are built for scalability, speed, and parallel processing. Apache Spark is one of the most widely used big data frameworks, and PySpark is its Python API that allows easy integration with Python's data ecosystem.

This beginner-level project simulates a real-world scenario where raw data is collected from different sources and often contains inconsistencies like null values, repeated entries, and incomplete records. The goal is to clean such data efficiently using PySpark's DataFrame operations.

🎯 Objective:
✅ Load and inspect a raw dataset using PySpark

✅ Identify and remove duplicate rows

✅ Detect and handle missing or null values

✅ Create a clean and consistent version of the dataset

✅ Provide a simple, reproducible PySpark script or notebook for beginners

🔧 Technologies Used:
Python

Apache Spark (PySpark)

Google Colab / Jupyter Notebook (for execution)

CSV file (for demonstration dataset)

🔍 Key Operations Performed:
1. Loading the Dataset
A sample dataset (in-memory or CSV format) is used, containing fields like Name, Age, and City. The dataset includes missing values (None) and duplicate rows to simulate real-world issues.

2. Removing Duplicates
Using dropDuplicates(), we eliminate repeated records to maintain data integrity.

3. Handling Missing Values
With PySpark's dropna() method, rows with null or missing values are removed. This is the simplest and most commonly used approach to handle missing data when cleaning is prioritized over imputation.

📁 Folder Structure:
├── data_cleaning_with_pyspark.ipynb   # Jupyter Notebook (or .py file) with full code
├── sample_dataset.csv                 # Optional: Sample input dataset
├── README.md                          # Project explanation and documentation


✅ Outcome:
By the end of this project, we obtain a clean dataset that:

Has no missing/null values

Is free from duplicates

Can be further used for data analysis or model training

This project demonstrates that even with basic PySpark operations, powerful and scalable data cleaning workflows can be built. It's a great starting point for students and beginners in data science who want to get hands-on experience with PySpark and big data basics.

