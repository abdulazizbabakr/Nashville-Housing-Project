# Nashville-Housing-Project

**Data Cleaning and Transformation
This series of SQL queries demonstrates data cleaning and transformation tasks on the dataset named "NashvilleHousing." The steps include:
1. Standardizing Date Format: Converts the "SaleDate" column to a consistent date format and creates a new column "SaleDateConverted."
2. Populating Property Address Data: Fills missing property addresses based on ParcelID matches with non-null addresses.
3. Breaking Out Property Address: Splits the property address into individual columns for address, city, and state.
4. Breaking Out Owner Address: Divides the owner address into columns for address, city, and state.
5. Changing 'Y' and 'N' to 'Yes' and 'No': Replaces 'Y' with 'Yes' and 'N' with 'No' in the "SoldAsVacant" column.
6. Removing Duplicates: Removes duplicate rows based on specific columns.
7. Deleting Unused Columns: Drops selected columns that are no longer needed.

**EDA
These SQL queries involve analyzing the cleaned data in the "NashvilleHousing" dataset for various insights:
1. Properties per City: Counts the number of properties sold per city and presents the data in descending order of properties sold.
2. Properties per Owner: Counts the number of properties owned by each owner, excluding cases with null owner names.
3. Sold Properties per Year: Counts the number of properties sold in each year and presents the data in descending order.
4. Creating Price Categories: Divides the data into price categories ("Cheap," "Average," "Expensive") based on the SalePrice column and counts properties in each category.
5. Price Range per City: Counts the properties in different price ranges per city and presents the data in descending order.
6. Category Count per City: Presents a breakdown of property counts in different price categories ("Cheap," "Average," "Expensive") per city.

These queries demonstrate how the cleaned and transformed data can be used to extract meaningful insights related to property sales, prices, ownership, and more in the Nashville housing dataset.
