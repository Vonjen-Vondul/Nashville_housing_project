# Nashville Housing Data Exploration using SQL

This repository contains a set of SQL queries used to explore and preprocess Nashville housing data. The queries aim to standardize data, clean and organize information, and prepare it for further analysis. These queries use SQL features such as data conversion, string manipulation, case statements, and removal of duplicates.

## Table of Contents

- [Overview](#overview)
- [Data Source](#data-source)
- [Queries](#queries)
- [Data Preprocessing](#data-preprocessing)
- [Data Standardization](#data-standardization)
- [Removing Duplicates](#removing-duplicates)
- [Unused Columns](#unused-columns)
- [Contributing](#contributing)
- [License](#license)

## Overview

The SQL queries in this repository are designed to work with housing data from Nashville. They perform various operations to clean and standardize the data, including converting date formats, handling missing values, splitting address fields, standardizing "Sold as Vacant" values, and removing duplicate entries.

## Data Source

The data used in these queries is sourced from the `ProjectPortfolio` database and the `NashvilleHousing` table. This table contains information related to property sales, addresses, and ownership in Nashville.

## Queries

The queries are categorized into different sections, each with a specific focus. Here's a summary of the sections:

- **Data Preprocessing**: Initial queries to standardize date formats and populate property addresses.
- **Data Standardization**: Queries to standardize "Sold as Vacant" values and split address fields into individual columns.
- **Removing Duplicates**: Queries to identify and remove duplicate records.
- **Unused Columns**: Queries to drop unused or redundant columns from the dataset.

## Data Preprocessing

Data preprocessing is an essential step in these queries, involving tasks such as data conversion, populating missing values, and splitting address fields. The preprocessing ensures that the data is ready for further analysis and reporting.

## Data Standardization

These queries focus on standardizing values in the "Sold as Vacant" column and breaking down the property address and owner address into separate columns for better organization and analysis.

## Removing Duplicates

To maintain data integrity, these queries identify and remove duplicate records from the dataset, ensuring accurate and reliable results.

## Unused Columns

Queries in this section aim to clean the dataset by removing columns that are no longer needed for analysis.

## Contributing

Contributions are welcome! If you have additional SQL queries, improvements, or suggestions for data preprocessing, please feel free to open an issue or create a pull request. Your contributions can help enhance the Nashville housing data exploration process.

Feel free to explore the SQL queries and adapt them to your own data exploration needs. If you have any questions or need assistance, please don't hesitate to reach out.

Happy data exploration!
