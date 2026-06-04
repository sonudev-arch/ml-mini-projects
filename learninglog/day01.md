---
# Learning
## Date - June 04, 2026


### Data Cleaning

I have already learnt about Conda Environments there need (Isolation and Conflict resolve), Downloading datasets from Kaggle and Loading it in notebook with pd.read_csv("filepath").

- Dataset shape

    df.shape - Display Number of Rows and Columns

    df.columns - Display name of each column

- Dataset Info

    df.info() - Display each column with number of Non-Null value count and Data type of values

    df.describe() - Display each non categorical column count, mean, standard deviation(std), minimum value(min), 25%(Q1), 50%(Q2), 75%(Q3)and maximum value(max)

    Quartiles shows that percent data is below this value

- Missing Values Handling

    df.isnull().sum()- Displaying Sum of Missing values for each column

    df["column"].value_counts - Display the each of unique value counts
    
    df["column"].fillna(df["column"].mean()/median()/mode()[0],any value) - This fills Null values with the respective value provided in it

- Median is not affected by outliers but Mean is affected
- Use Mode for categorical data
- Drop column with high percent of values are null

    