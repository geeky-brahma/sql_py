**README.md**

# Connecting to PostgreSQL and Inserting Data from CSV Files using Pandas

## Overview
This Jupyter Notebook demonstrates how to connect to a PostgreSQL database and insert data from three CSV files using the Pandas library in Python. The CSV files used in this demonstration are:
- Wealth-AccountData.csv
- Wealth-AccountSeries.csv
- Wealth-Accountscountry.csv

## Prerequisites
Before running this notebook, ensure you have the following:
- Python installed on your system
- Pandas library installed (`pip install pandas`)
- Psycopg2 library installed (`pip install psycopg2-binary`)
- PostgreSQL installed and running on your system
- Access to create databases and tables in your PostgreSQL instance

## Instructions
1. **Clone Repository**: Clone this repository to your local machine.

2. **Set Up PostgreSQL Database**: Make sure you have a PostgreSQL database set up where you want to insert the data. Update the connection parameters in the notebook to match your database credentials.

3. **Run the Notebook**: Open the Jupyter Notebook `SQL_using_python.ipynb` and run each cell sequentially. Make sure to update the file paths according to the location of your CSV files.

4. **Verify Data Insertion**: After running the notebook, connect to your PostgreSQL database and verify that the data has been inserted correctly.

## Files
- **Connect_and_Insert_Data.ipynb**: Jupyter Notebook containing the code to connect to PostgreSQL and insert data from CSV files.
- **Wealth-AccountData.csv**: CSV file containing data related to wealth account data.
- **Wealth-AccountSeries.csv**: CSV file containing data related to wealth account series.
- **Wealth-Accountscountry.csv**: CSV file containing data related to wealth accounts by country.
