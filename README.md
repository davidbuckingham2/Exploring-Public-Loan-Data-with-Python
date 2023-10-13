# Exploring Public Loan Data with Python

This is a data exploration project that focuses on analyzing a dataset related to Small Business Administration (SBA) loans. The project uses Python and various data analysis libraries to perform data cleaning, visualization, and statistical analysis on the dataset.

## Skills Used

This project showcases the following skills:

- Data Cleaning and Preprocessing
- Data Visualization using Matplotlib and Seaborn
- Univariate and Bivariate Analysis
- Handling Categorical Variables
- Descriptive Statistics
- Handling Outliers
- Pandas Dataframe Manipulation

## Project Overview

The project starts by importing essential libraries such as pandas, numpy, matplotlib, and seaborn. It then loads the dataset into a pandas dataframe and displays the first few rows using `df.head()`. The dataframe contains information about SBA loans, including loan details, borrower information, and loan status.

### Data Cleaning

To ensure data quality, we check for missing values using `df.isnull().sum()`. Null values are present in several columns, and we remove rows with null values, primarily focusing on the 'BorrowerName' column, using `df = df.loc[df['BorrowerName'].notnull()]`.

### Data Exploration

#### Categorical Variables

Univariate and bivariate analysis is conducted on several categorical variables, including:
- `ProcessingMethod`
- `BorrowerState`
- `LoanStatus`
- `Ethnicity`
- `BusinessType`
- `Race`

The analysis includes count plots and cross-tabulations to explore relationships and trends in the data.

#### Numerical Variables

Descriptive statistics are computed for the 'CurrentApprovalAmount' variable, and outliers are identified and visualized using box plots and distribution plots.

## Conclusion

This data exploration project demonstrates a range of data analysis and data visualization skills. It offers insights into the characteristics of SBA loans and can serve as a foundation for further analysis or modeling. 

