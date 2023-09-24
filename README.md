# Coffee (Worldwide) - Data Visualization

This is a simple data visualization project in Jupyter Notebook using Python language with various libraries, measurements, and graphs.

## Table of Contents
1. [Used Libraries](#used-libraries)
2. [Functions](#functions)
3. [Connecting to Database](#connecting-to-database)
4. [Loading Data](#loading-data)
5. [Creating Tables](#creating-tables)
6. [Analysis](#analysis)
7. [Contributing to the Dataset](#contribute)

### 1. Used Libraries
- csv
- sqlite3
- matplotlib
- pandas
- numpy

### 2. Functions
- **createTable:** Creates database tables.
- **queryToList:** Converts database queries to lists.

### 3. Connecting to Database
Establishes a connection to the "coffee.db" SQLite database.

### 4. Loading Data
Loads data from CSV files into corresponding database tables.

### 5. Creating Tables
Defines table structure and inserts data into tables.

### 6. Analysis
#### Analysis Goals
1. Total summary
2. Summary of average values over the years
3. Summary of chosen country
4. Summary of chosen year

Used measurements:
- Number of records (count)
- Mean value (mean)
- [Standard deviation (std)](https://en.wikipedia.org/wiki/Standard_deviation)
- Minimum (min) and maximum (max) value
- [First (25%), second (50%), and third (75%) quartile](https://en.wikipedia.org/wiki/Quartile)

Used graphs:
- Linear
- Column (Horizontal)

### 7. Contributing to the Dataset
If you would like to contribute to this dataset, please visit the [contribution page](https://www.kaggle.com/datasets/yamaerenay/ico-coffee-dataset-worldwide) for detailed instructions on how to contribute.

This page provides an overview of the project's structure and key functionalities. For detailed code and analysis, please refer to the Jupyter Notebook.
