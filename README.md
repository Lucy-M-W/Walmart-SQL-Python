# Walmart Sales Data Analysis Project
This project analyzes Walmart sales data to uncover insights into sales performance, customer behavior, and operational trends. Using Python for data cleaning, exploration, and visualization, alongside SQL for querying and analyzing relational databases, the project aims to identify key patterns and provide actionable recommendations. The goal is to demonstrate how data-driven insights can inform business strategies and improve decision-making.

# Project Highlights

## 1. Set Up the Environment
* **Tools Used:** Visual Studio Code (VS Code), Python, SQL (MySQL and PostgreSQL)
* **Goal:** Create a structured workspace within VS Code and organize project folders for smooth development and data handling.
## 2. Set Up Kaggle API
* **API Setup:** Obtaining the Kaggle API token from Kaggle by navigating to account profile settings and downloading the JSON file.

* **Configured Kaggle file:** 
   * Saved the downloaded ```kaggle.json``` file in the local ```.kaggle``` folder.
   * Used the command ```kaggle datasets download -d <dataset-path>``` to pull datasets directly into your project.
## 3. Download Walmart Sales Dataset
* Data Source: Kaggle's Walmart Sales Dataset
* Storage: Saved the data in the data folder for easy reference and access.
## 4. Install Required Libraries and Load Data
* **Libraries:** Installed necesary Python libraries using:
```pip install pandas numpy sqlalchemy mysql-connector-python psycopg2```
* **Loading Data:** Read the data into a Pandas Dataframe for intial analysis and transformation.

## 5. Explore the Data
* **Goal:** Conducted an initial data exploration to understand data distribution, check column names, types and indentify potential issues.
* **Analysis:** Used functions like ```.info(), .describe(), and .head()``` to get a quick overflow of the data structure and statistics.

## 6. Data Cleaning
* **Remove duplicate:** Identify and remove duplicate entries to avoid skewed results.
* **Handle missing values:** Drop rows or columns with missing values if they are insignificant and fill values where it was essential.
* **Fix data types:** Ensured all columns have consistent data types for example, dates as ```datetime```, prices as ```float```.
* **Currency formatting:** Used ```.replace()``` to handle and format currency values for analysis.
* **Validation** Checked for any remaining inconsistencies and verified the cleaned data.

## 7. Load data into MySQL 
* **Set up connections:** Connected to MySQL using ```sqlalchemy``` and loaded the cleaned data into each database.
* **Table creation:** Set up tables in MySQL using Python SQLAlchemy to automate table creation and data insertion.
* **Verification:** Run initial SQL queries to confirm that the data has been loaded accurately.

## 8. SQL analysis - Complex queries and business problem solving
* **Business problem-solving:** Wrote and executed complex SQL queris to answer critical business questions such as:
  * Revenue trends accross branches and categories.
  * Identify best-selling products categories.
  * Sales perfomance by time, city, and payment method.
  * Analyzing peak sales periods and customer buying patterns.
  * Profit margin nalaysis by branch and category.
## 9. Project publishing and documentation
* **Dumentation:** Maintained well-structured domunetation of the entire process in Jupyter Notebook.
* **Project publishing:** Published the completed project on GitHub and my portfolio website.
 * The ```README.md``` file.
 * Jupyter Notebooks.
 * SQL query script file.
    
