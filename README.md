# Exploratory Data Analysis (EDA) on Stock Prices Dataset

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a stock prices dataset to uncover meaningful patterns, trends, and relationships within the data. EDA is an important step in the data analysis process because it helps analysts understand the structure and quality of a dataset before applying advanced analytical or machine learning techniques.

The dataset contains historical stock market information, including opening price, highest price, lowest price, closing price, trading volume, and stock symbols.


## Objectives

The main objectives of this project were to:

* Explore and understand the structure of the dataset.
* Identify missing values and data quality issues.
* Calculate descriptive statistics such as:

  * Mean
  * Median
  * Mode
  * Standard Deviation
* Analyze the distribution of numerical variables.
* Detect potential outliers using boxplots.
* Examine relationships between stock price variables.
* Measure correlations among numerical features.
* Generate insights that can support further financial analysis and predictive modeling.

---

## Dataset Features

The dataset contains the following variables:

| Feature | Description                    |
| ------- | ------------------------------ |
| Symbol  | Stock ticker symbol            |
| Date    | Trading date                   |
| Open    | Opening stock price            |
| High    | Highest stock price of the day |
| Low     | Lowest stock price of the day  |
| Close   | Closing stock price            |
| Volume  | Number of shares traded        |


## Tools and Libraries Used

The analysis was performed using Python and the following libraries:

* Pandas – Data manipulation and analysis
* NumPy – Numerical computations
* Matplotlib – Data visualization
* Seaborn – Statistical visualization


## Analysis Performed

### 1. Data Inspection

The dataset was loaded into a Pandas DataFrame and inspected to understand its structure, data types, and overall quality.

Key checks included:

* Viewing the first few rows
* Checking dataset dimensions
* Reviewing data types
* Identifying missing values


### 2. Descriptive Statistics

Summary statistics were generated to understand the central tendency and spread of the data.

Metrics calculated:

* Mean
* Median
* Mode
* Standard Deviation
* Minimum and Maximum Values

These statistics provided insights into the typical stock prices and trading volumes within the dataset.


### 3. Distribution Analysis

Histograms were used to visualize the distribution of:

* Open Prices
* High Prices
* Low Prices
* Close Prices
* Trading Volume

This helped identify:

* Skewness
* Concentration of values
* Potential anomalies

### 4. Outlier Detection

Boxplots were created to identify unusual observations in stock prices and trading volumes.

The analysis revealed whether extreme values existed and how widely the data was distributed.


### 5. Relationship Analysis

Scatter plots were used to explore relationships between stock price variables such as:

* Open vs Close
* High vs Low
* Close vs Volume

These visualizations helped determine whether variables moved together and whether strong associations existed.

### 6. Correlation Analysis

A correlation matrix and heatmap were generated to quantify relationships between numerical variables.

This analysis showed:

* Strong positive correlations among stock price features.
* The strength and direction of relationships between variables.

## Key Findings

* Stock price variables (Open, High, Low, and Close) showed strong positive correlations.
* Trading volume exhibited a different distribution compared to price variables.
* A few outliers were observed in trading volume, indicating unusually active trading days.
* Price-related features followed similar patterns, reflecting the interconnected nature of stock market prices.

## Conclusion

This Exploratory Data Analysis provided a comprehensive understanding of the stock prices dataset. Through statistical analysis and visualization techniques, important patterns, distributions, and relationships were identified. The insights gained from this analysis can serve as a foundation for future projects such as time series forecasting, stock price prediction, and machine learning modeling.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook


This version is detailed enough for recruiters, hiring managers, internship supervisors, and anyone viewing your GitHub portfolio.
