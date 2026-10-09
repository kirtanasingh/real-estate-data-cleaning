# Real Estate Data Cleaning and Transformation

## Overview

This project demonstrates data cleaning and preprocessing techniques on a real estate property dataset using Python. The dataset contains intentionally introduced data quality issues to simulate real-world data preprocessing scenarios.

## Objectives

* Profile the dataset and identify data quality issues.
* Handle missing values and duplicate records.
* Standardize inconsistent city and locality names.
* Parse and transform mixed date formats.
* Detect and remove price outliers using the Interquartile Range (IQR) method.
* Compare dataset quality before and after cleaning.

## Technologies Used

* Python
* Pandas
* NumPy
* Jupyter Notebook

## Dataset

The dataset contains real estate property information, including:

* Property ID
* City and locality
* Number of bedrooms (BHK)
* Area in square feet
* Property price
* Listing date

The raw dataset includes missing values, inconsistent text formats, invalid dates, duplicate records, and unusual property prices.

## Methodology

1. **Data Generation:** Create a sample real estate dataset with simulated data quality issues.
2. **Data Profiling:** Examine data types, missing values, descriptive statistics, and duplicates.
3. **Data Cleaning:** Remove duplicates, standardize text, parse dates, and handle missing values.
4. **Outlier Detection:** Apply the IQR method to property prices and price per square foot.
5. **Data Transformation:** Convert columns to appropriate data types and derive the price-per-square-foot feature.
6. **Comparison:** Evaluate data quality and statistical differences before and after cleaning.

## Output

The experiment generates a cleaned dataset and a before-and-after comparison report to demonstrate the impact of data preprocessing.

## How to Run

Install the required libraries:

```bash
pip install pandas numpy jupyter
```

Run the notebook in Jupyter Notebook or Google Colab to execute the experiment.

## Conclusion

This experiment demonstrates how data cleaning and transformation improve dataset consistency, reliability, and suitability for further analysis and machine learning applications.
