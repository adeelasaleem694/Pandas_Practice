
# Adult Dataset Analysis

This project involves analyzing the **Adult dataset** (from Kaggle) using various data manipulation techniques with Pandas. The goal is to demonstrate important data analysis skills, such as data cleaning, univariate and bivariate analysis, handling missing values, and more.

## Key Concepts Covered

- **Fetching Random Samples** from the dataset.
- **Using `isin`, `between`, `unique`, `dropna`, `replace`, `duplicated`, `drop_duplicates`, `astype`, and `apply`** methods for various data transformations.
- **Univariate Analysis**: Analyzing individual columns or features.
- **Bivariate Analysis**: Exploring relationships between two variables.
- **Memory Optimization**: Techniques to reduce memory usage when handling large datasets.

## Questions Solved

1. Displayed the top 10 rows of the dataset.
2. Checked the last 10 rows of the dataset.
3. Found the shape of the dataset (number of rows and columns).
4. Gathered information about the dataset, such as the total number of rows, columns, data types, and memory usage.
5. Fetched a random sample from the dataset (50%).
6. Checked for null values in the dataset.
7. Performed data cleaning by replacing `?` values with NaN.
8. Dropped all rows with missing values.
9. Checked for duplicate data and removed them.
10. Generated overall statistics about the dataframe.
11. Dropped the columns `education-num`, `capital-gain`, and `capital-loss`.
12. Analyzed the distribution of the `Age` column.
13. Found the total number of persons with ages between 17 to 48 (inclusive) using the `between` method.
14. Analyzed the distribution of the `Workclass` column.
15. Counted the number of persons with a Bachelor's and Master's degree.
16. Performed bivariate analysis to examine relationships between variables.
17. Replaced salary values with `0` (<= 50K) and `1` (> 50K).
18. Identified which `Workclass` has the highest salary.
19. Analyzed which gender (Male or Female) has a better chance of earning a salary greater than 50K.
20. Converted the `workclass` column's datatype to a categorical datatype for optimization.

## Dataset Information

- **Source**: Kaggle - Adult Income Dataset
- **Columns**: The dataset includes columns such as `age`, `workclass`, `education`, `hours-per-week`, `salary`, etc.
- **Rows**: The dataset contains information about adults, including demographic and employment data, used to predict income categories (<=50K or >50K).


## Usage

1. Clone this repository.
2. Download the dataset from [Kaggle - Adult Income Dataset](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset).
3. Load the dataset in your Python environment.
