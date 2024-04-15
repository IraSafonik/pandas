# pandas
Pandas: Zero to Hero🥇✌️🏆

# Pandas
Pandas is a powerful and popular open-source Python library for data manipulation and analysis. It is built on top of NumPy and provides easy-to-use data structures and functions for working with structured data, making it an essential tool in the data science and data analysis toolkit. Here's a more detailed explanation of what pandas is and what it offers:

1. Data Structures:
- DataFrame: The primary data structure in pandas is the DataFrame, which is a 2-dimensional, size-mutable, and tabular data structure. Think of it as a table or spreadsheet where you can store and manipulate data. Each column in a DataFrame is a Series, which is a one-dimensional labeled array with data of any type.

2. Key Features:
- Data Loading: Pandas can read data from various sources, including CSV files, Excel spreadsheets, SQL databases, and more. It can also connect to online data sources, making it versatile for data ingestion.
- Data Cleaning: It provides powerful tools for handling missing data, transforming data, and dealing with outliers.
- Data Indexing and Selection: Pandas offers flexible indexing methods, including label-based, integer-based, and Boolean-based indexing, allowing you to select and filter data easily.
- Data Aggregation and Grouping: You can group and aggregate data based on certain criteria using pandas, which is essential for performing summary statistics and analysis.
- Merging and Joining: Pandas can merge and join datasets similar to SQL databases, enabling you to combine data from multiple sources.
- Time Series Analysis: It has built-in support for time series data, making it suitable for financial and temporal data analysis.
- Data Visualization: While pandas is primarily a data manipulation library, it can also work seamlessly with data visualization libraries like Matplotlib and Seaborn for creating charts and plots.

3. Use Cases:
- Data Analysis: Pandas is widely used for data exploration and analysis, allowing data scientists and analysts to perform tasks like data cleaning, transformation, and statistical analysis.
- Data Preparation: Before feeding data into machine learning models, you often need to preprocess and structure it correctly. Pandas is invaluable for this purpose.
- Data Wrangling: When working with real-world data, it's common to have data in messy formats. Pandas helps clean and prepare this data for analysis.
- Data Reporting and Visualization: While not a data visualization library in itself, pandas can be combined with libraries like Matplotlib and Seaborn to create informative visualizations.

4. Community and Documentation:
- Pandas has a large and active community, which means that there is plenty of support, documentation, and online resources available. This makes it easy to find solutions to common data-related problems.

In summary, pandas is an indispensable tool for data manipulation and analysis in Python. It simplifies the handling of structured data, making it more accessible for users to perform various data-related tasks, from basic data cleaning to complex data analysis.


Pandas provides a wide range of functions and methods for data manipulation and analysis. Here's a list of some of the most commonly used basic functions and methods in pandas:

### DataFrame and Series Creation:
1. pd.DataFrame(data): Create a new DataFrame from data (e.g., a dictionary or a 2D array).
2. pd.Series(data): Create a new Series from data.

### Data Loading and Input/Output:
1. pd.read_csv(filename): Read data from a CSV file.
2. pd.read_excel(filename): Read data from an Excel file.
3. pd.read_sql(query, connection): Read data from a SQL database.
4. df.to_csv(filename): Write data to a CSV file.
5. df.to_excel(filename): Write data to an Excel file.

### Data Exploration and Information:
1. df.head(n): Display the first n rows of the DataFrame.
2. df.tail(n): Display the last n rows of the DataFrame.
3. df.info(): Display information about the DataFrame, including data types and missing values.
4. df.describe(): Generate summary statistics of the DataFrame.
5. df.shape: Get the dimensions (rows, columns) of the DataFrame.

### Indexing and Selection:
1. df[column]: Select a single column by name.
2. df[[column1, column2]]: Select multiple columns by name.
3. df.iloc[row, column]: Select data by integer-based location.
4. df.loc[row_label, column_label]: Select data by label-based location.

### Data Cleaning and Transformation:
1. df.drop(labels, axis): Remove rows or columns.
2. df.fillna(value): Fill missing values with a specified value.
3. df.dropna(): Remove rows with missing values.
4. df.rename(columns): Rename columns.
5. df.sort_values(by): Sort DataFrame by column(s).
6. df.groupby(column): Group data based on a column.
7. df.pivot_table(): Create a pivot table.

### Filtering and Querying:
1. df[df['column'] > value]: Filter data based on a condition.
2. df.query('condition'): Query data using a SQL-like syntax.

### Aggregation and Statistics:
1. df.mean(), df.median(), df.sum(), df.min(), df.max(): Compute various statistics.
2. df.groupby(column).agg(func): Perform custom aggregation.

### Data Visualization:
1. df.plot(): Create basic plots using Matplotlib.
2. df.hist(), df.plot.hist(): Create histograms.
3. df.plot.scatter(): Create scatter plots.

### Merging and Joining:
1. pd.concat([df1, df2]): Concatenate DataFrames.
2. df1.merge(df2, on='key'): Perform SQL-like joins.

### Time Series and Datetime Handling:
1. pd.to_datetime(series): Convert a series to datetime.
2. df.resample('D').sum(): Resample time series data.

### Serialization:
1. df.to_pickle(filename): Serialize the DataFrame to a pickle file.
2. pd.read_pickle(filename): Deserialize a pickle file to a DataFrame.

These are some of the basic functions and methods in pandas. The library offers many more functions for specialized data operations, so be sure to consult the official pandas documentation for more detailed information and examples.
