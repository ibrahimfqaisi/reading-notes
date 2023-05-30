## **Q1: What is the purpose and basic functionality of the Pandas library?**


### Pandas is a Python library for data analysis and manipulation. It provides high-level data structures and operations for working with structured (tabular, multidimensional, potentially heterogeneous) and time series data.

## **Q2: What are the primary data structures in Pandas, and how do they differ in terms of use cases?**


### The primary data structures in Pandas are Series, DataFrame, and Panel. Series is a one-dimensional array of data, DataFrame is a two-dimensional array of data, and Panel is a three-dimensional array of data.

## **Q3: Describe the process of loading a dataset into a Pandas DataFrame. What are some common file formats that can be used, and which Pandas functions are utilized to read these formats?**


## To load a dataset into a Pandas DataFrame, you can use the read_csv() function. This function can read CSV files, JSON files, and a variety of other file formats.

Here are some other common file formats that can be read by Pandas:
```
JSON: pd.read_json()
HTML: pd.read_html()
SQL: pd.read_sql()
```