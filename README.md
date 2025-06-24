
# Car Sales Analysis and Interactive Dashboard

## Overview

This project provides a comprehensive analysis of a car sales dataset containing over 23,000 transactions. The primary goal is to clean and process the raw data using Python and then build a dynamic, interactive dashboard in Microsoft Excel to visualize key performance indicators (KPIs) and uncover sales trends.

This repository showcases a practical, hybrid approach to data analysis, leveraging the strengths of Python's Pandas library for robust data manipulation and Excel's powerful visualization tools for reporting.

## Key Features & Analysis Highlights

-   **Hybrid Analysis:** Combines Python for backend data processing and Microsoft Excel for frontend visualization and reporting.
-   **Comprehensive Data Cleaning:** Implements data cleaning techniques in Python to handle null values, remove duplicates, correct data types, and create new features like a `Year` column for time-based analysis.
-   **In-depth Exploratory Data Analysis (EDA):** Uses Python to generate statistical summaries and aggregations to answer key business questions regarding sales performance, customer demographics, and vehicle trends.
-   **Interactive Excel Dashboard:** Presents the cleaned data in a user-friendly dashboard with dynamic slicers, charts, and KPIs to track sales by region, car model, customer income, and more[1].

---

## A Hybrid Approach: Python and Excel

This project intentionally uses both Python and Excel to demonstrate a versatile and common real-world workflow:

#### **Python for Data Processing (`project.ipynb`)**

-   The Jupyter Notebook is used for the heavy lifting of data preparation[1].
-   **Loading:** The raw dataset is loaded into a Pandas DataFrame.
-   **Cleaning:** Efficiently handles large-scale data cleaning tasks that would be cumbersome in Excel, such as programmatic removal of duplicates and nulls[1].
-   **Transformation:** Creates new columns and converts data types to ensure data integrity[1].
-   **Aggregation:** Groups and summarizes data to prepare it for visualization[1][2].

#### **Excel for Visualization (`Car Analysis.xlsx`)**

-   The cleaned data from the Python script is used as the source for the Excel analysis[1].
-   **Pivot Tables:** Power Pivot is used to create flexible data summaries.
-   **Dynamic Dashboard:** The dashboard sheet connects to the Pivot Tables, allowing for interactive filtering with slicers.
-   **Reporting:** A separate report sheet provides tabular data views for detailed analysis[1].

---

## Project Structure

-   `Car sales.xlsx`: The raw, unprocessed source data[1].
-   `Car Analysis.xlsx`: The final Excel file containing:
    -   **Dashboard:** The main interactive dashboard with charts and KPIs.
    -   **Report:** Tabular data views for detailed analysis.
    -   **Data:** The cleaned and processed dataset imported from the Python script[1].
-   `project.ipynb`: The Jupyter Notebook containing all Python code for data cleaning, preprocessing, and EDA[1].

---

## Technical Workflow

1.  **Data Loading & Initial Exploration:** The dataset is loaded in Python, and its structure, dimensions, and data types are examined.
2.  **Data Cleaning & Preprocessing:** Null values and duplicates are removed. Unnecessary columns are dropped, a `Year` column is created from the `Date` field, and data types are corrected[1][3].
3.  **Exploratory Data Analysis (EDA):** The data is aggregated by different features (e.g., car company, gender, region) to derive insights and answer business questions.
4.  **Data Export:** The cleaned DataFrame is exported (e.g., to a CSV or copied into Excel).
5.  **Visualization & Reporting in Excel:** The cleaned data is used to build Pivot Tables, an interactive dashboard, and summary reports[1].

---

## How to Use This Project

#### **To Run the Python Analysis:**

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/MariamAsall/Car-Sales-Analysis-.git
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy jupyterlab
    ```
3.  **Launch Jupyter and open `project.ipynb`** to view the data processing steps.

#### **To View the Excel Dashboard:**

1.  Navigate to the repository files.
2.  Open `Car Analysis.xlsx` using Microsoft Excel.
3.  Interact with the slicers on the **Dashboard** sheet to filter the data.

---
