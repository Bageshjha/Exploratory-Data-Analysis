# Exploratory-Data-Analysis
Great! You can adjust the README to include a link to the dataset and update any relevant sections. Here’s the updated README draft:

---

# Diwali Sales Analysis

This project involves analyzing sales data from a Diwali sales campaign. The analysis includes data cleaning, exploration, and visualization to gain insights into customer behavior and sales patterns.

## Table of Contents

1. [Introduction](#introduction)
2. [Dependencies](#dependencies)
3. [Data](#data)
4. [Data Cleaning](#data-cleaning)
5. [Data Exploration and Analysis](#data-exploration-and-analysis)
6. [Conclusion](#conclusion)
7. [License](#license)

## Introduction

This project aims to analyze sales data from a Diwali sales campaign to understand customer demographics, purchasing behavior, and sales trends. The analysis uses Python libraries such as Pandas, Matplotlib, and Seaborn to clean and visualize the data.

## Dependencies

Make sure to install the following libraries before running the analysis:

- pandas
- matplotlib
- seaborn
- numpy

You can install these using pip:

```bash
pip install pandas matplotlib seaborn numpy
```

## Data

The dataset used in this project is the [Diwali Sales Dataset](https://www.kaggle.com/datasets/saadharoon27/diwali-sales-dataset) from Kaggle. It contains the following columns:

- `User_ID`
- `Cust_name`
- `Product_ID`
- `Gender`
- `Age Group`
- `Age`
- `Marital_Status`
- `State`
- `Zone`
- `Occupation`
- `Product_Category`
- `Orders`
- `Amount`
- `Status`
- `unnamed1`

The dataset originally has 11251 rows and 15 columns.

## Data Cleaning

1. **Dropping Unnecessary Columns**: The columns `Status` and `unnamed1` were dropped as they contain only missing values.
2. **Removing Duplicates**: 8 duplicate rows were identified and removed.
3. **Handling Missing Values**: 12 missing values in the `Amount` column were dropped.

After cleaning, the dataset contains 11231 rows and 13 columns.

## Data Exploration and Analysis

### Gender

- **Count of Buyers by Gender**: A count plot was created to visualize the number of buyers by gender.
- **Sales by Gender**: A bar plot was used to show the total sales amount by gender.

### Age Group

- **Count of Buyers by Age Group**: A count plot was created to visualize the number of buyers by age group and gender.
- **Sales by Age Group**: A bar plot was used to show the total sales amount by age group.

### State

- **Orders by State**: A bar plot visualized the total number of orders by state for the top 10 states.
- **Sales by State**: A bar plot visualized the total sales amount by state for the top 10 states.

### Marital Status

- **Count of Buyers by Marital Status**: A count plot was created to visualize the number of buyers by marital status.
- **Sales by Marital Status**: A bar plot was used to show the total sales amount by marital status and gender.

### Occupation

- **Count of Buyers by Occupation**: A count plot was created to visualize the number of buyers by occupation.
- **Sales by Occupation**: A bar plot was used to show the total sales amount by occupation.

### Product Category

- **Count of Sales by Product Category**: A count plot was created to visualize the number of sales by product category.
- **Sales by Product Category**: A bar plot was used to show the total sales amount by product category.

## Conclusion

The analysis reveals that:

- Married women aged 26-35 years from Uttar Pradesh, Maharashtra, and Karnataka, working in the IT, Healthcare, and Aviation sectors, are more likely to purchase products from the Food, Clothing, and Electronics categories.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

This should give users a good overview of the project and how to get started with the analysis!
