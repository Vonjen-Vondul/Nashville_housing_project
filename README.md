# Exploratory Data Preparation (EDP) for Nashville Housing Dataset
In the realm of data analysis, preparing your dataset for in-depth analysis is a crucial step. Let's walk through the process of Exploratory Data Preparation (EDP) for the Nashville Housing Dataset using SQL. We'll explain the reasons behind various SQL operations performed on the dataset.

1. Standardizing Date Format
Reason: This code standardizes the date format in the SaleDate column by converting it to the 'date' data type. Consistent date formatting makes it easier to work with date-related operations and queries.

2. Populating Property Address
Reason: This code populates missing property addresses by comparing records with the same ParcelID and updating the missing values. Complete property address information is essential for analysis.

3. Breaking Out Address into Individual Columns

Reason: This code separates the property address into individual columns for better data structure and ease of analysis. Splitting address information into parts like street address, city, and state allows for more granular querying.

4. Splitting Owner Address

Reason: This code splits the owner's address into individual columns for better data organization. Separating owner address components (street, city, state) allows for more straightforward analysis and querying.

5. Changing 'Y' and 'N' to 'Yes' and 'No' in "Sold as Vacant" Column

Reason: This code updates the 'SoldAsVacant' column to standardize values. This standardization simplifies analysis and improves data consistency.

6. Removing Duplicates

Reason: This code identifies and removes duplicate records based on specific columns. Eliminating duplicates ensures that the dataset contains only unique observations for accurate analysis.

7. Deleting Unused Columns

Reason: This code removes columns that are no longer needed for analysis, reducing the dataset's complexity and improving performance.

With these data preparation steps, the Nashville Housing Dataset is now well-structured and ready for in-depth analysis using SQL. Clean and organized data is essential for extracting valuable insights and making data-driven decisions.
