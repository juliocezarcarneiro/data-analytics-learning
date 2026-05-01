# 🏡 Home Sales Analysis with SparkSQL

This project uses PySpark and SparkSQL to analyze home sales data, focusing on various metrics like average prices by house features and build year. In this project, temporary views, partition data, cache and uncache tables, and measure performance with Spark was developed.

## 📁 Repository Setup

1. Clone this repo: git clone https://github.com/juliocezarcarneiro/Home_Sales.git

2. Navigate into the repo: cd Home_Sales

3. Launch the Jupyter Notebook: jupyter notebook

## 📄 File Structure

* Home_Sales.ipynb – Main notebook with PySpark analysis

* home_sales_revised.csv – Dataset (loaded from AWS S3)

* README.md – Project overview

## 📊 Objectives

* Load and process a large CSV dataset using PySpark.

* Create a temporary table and execute SparkSQL queries to answer:

* Average price of 4-bedroom houses by year.

* Average price of 3 bed/3 bath homes by build year.

* Homes with 3 bed/3 bath, 2 floors, ≥2000 sq ft.

* Average price by view rating for homes ≥ $350,000.

* Cache and uncache tables and compare query runtimes.

* Partition data by date_built and read/write Parquet format.

## 🧪 Technologies Used

* Python

* PySpark

* SparkSQL

* AWS S3 (for dataset access)

* Jupyter Notebook

## 📦 Dataset
The dataset home_sales_revised.csv is stored in an AWS S3 bucket and should be read directly in the notebook using PySpark.

## 📚 References

* Apache Spark. PySpark Documentation. https://spark.apache.org/docs/latest/api/python/

* Apache Spark. Spark SQL Guide. https://spark.apache.org/docs/latest/sql-programming-guide.html

* edX Boot Camps LLC. (2022). Home Sales Dataset and Course Materials.