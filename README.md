# London Housing Data Analysis using Python

## Project Overview

This project focuses on exploratory data analysis (EDA) of the London Housing Dataset using Python. The analysis was performed in a Jupyter Notebook and includes data cleaning, preprocessing, visualization, and insights extraction from housing-related data across different areas of London.

The dataset contains information related to:

* Monthly average house prices
* Yearly number of houses sold
* Monthly number of crimes committed
* Different areas in London
* Data ranging from 1995 to 2019

---

## Files in this Repository

| File Name                    | Description                                                    |
| ---------------------------- | -------------------------------------------------------------- |
| `Housing_data.ipynb`         | Jupyter Notebook containing the complete data analysis process |
| `5. London Housing Data.csv` | Dataset used for analysis                                      |
| `README.md`                  | Project documentation                                          |

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* Matplotlib
* Seaborn

---

## Dataset Information

The dataset includes the following important columns:

* `date` – Date of the record
* `area` – Area name in London
* `average_price` – Average house price
* `houses_sold` – Number of houses sold
* `no_of_crimes` – Number of crimes recorded

---

## Project Workflow

### 1. Importing Libraries

The project starts by importing the required Python libraries such as:

* Pandas
* Matplotlib
* Seaborn

### 2. Loading the Dataset

The CSV file is loaded into a Pandas DataFrame for analysis.

### 3. Data Cleaning

The following preprocessing steps were performed:

* Checked missing values
* Verified data types
* Converted the `date` column into datetime format

### 4. Feature Engineering

Additional columns were created:

* `year`
* `month`

### 5. Data Analysis Performed

The notebook includes analysis such as:

* Records where number of crimes is zero
* Maximum and minimum average house prices in England by year
* Average house prices by year
* Maximum and minimum number of crimes per area
* Areas where average house price is less than 100000

### 6. Data Visualization

A heatmap was generated to visualize missing values in the dataset.

---

## Key Insights

* Housing prices in England increased significantly over the years.
* Some areas recorded zero crimes for specific periods.
* Crime rates and housing prices vary across different London areas.
* The dataset provides useful insights for real estate and urban analysis.

---

## Sample Analysis Questions

* What is the maximum average house price in England per year?
* Which area has the highest number of crimes?
* Which areas have housing prices below 100000?
* How does housing price change over time?

---

## Learning Outcomes

Through this project, the following concepts were practiced:

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization
* GroupBy Operations in Pandas
* Working with Date and Time data

