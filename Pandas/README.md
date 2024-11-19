# Pandas Data Analysis

This Jupyter Notebook demonstrates basic data analysis techniques using the Pandas library in Python. It includes operations for creating series and data frames, reading and writing data, performing basic data exploration, and manipulating data. The dataset used for analysis consists of car sales data, including details like make, color, odometer reading, doors, and price.

## Key Features

### 1. **Creating a Pandas Series and DataFrame**
- Creation of a Pandas Series for car manufacturers and colors.
- Construction of a DataFrame combining the Series for car data.

### 2. **Reading and Writing Data**
- Importing data from a CSV file using `pd.read_csv()`.
- Exporting data to CSV using `to_csv()`.
  
### 3. **Basic Data Exploration**
- Calculating the mean of numeric columns.
- Using `dtypes` and `info()` to check data types and general information.
- Displaying the first few rows of the dataset with `head()`.
  
### 4. **Selecting and Filtering Data**
- Using `.loc[]` and `.iloc[]` to access data based on labels and positions.
- Boolean indexing to filter data, such as selecting rows where the "Make" column is "Toyota".

### 5. **Data Aggregation**
- Grouping data by a column (e.g., "Make") and calculating the mean of numeric columns using `groupby()`.
- Creating cross-tabulations with `pd.crosstab()`.

### 6. **Data Visualization**
- Basic plotting of numeric columns like "Odometer (KM)" and "Price".
- Generating histograms using `.hist()`.

### 7. **Data Cleaning and Transformation**
- Removing symbols from the "Price" column and converting it to numeric.
- Handling missing data with `fillna()` and `dropna()`.
- Adding new columns (e.g., "Fuel per 100KM" and "total fuel used").

## Installation

To run this notebook, you need to have Python and Pandas installed. You can install Pandas using pip:

```bash
pip install pandas
