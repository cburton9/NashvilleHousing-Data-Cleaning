# NashvilleHousing-Data-Cleaning Project


This SQL project cleans data in a table named NashvilleHousing to prepare it for analysis. Here are the key steps:

The script demonstrates techniques for:
- Standardizes date format in the SaleDate column.
- Populates missing values in the PropertyAddress column using data from potentially duplicate entries.
- Creates separate columns for address, city, and state from the original combined PropertyAddress and OwnerAddress columns.
- Converts "Y" and "N" values in the "Sold as Vacant" field to "Yes" and "No" for better readability.
- Identifies and removes potential duplicate entries.
- Includes commented-out steps for deleting unused columns (consider future analysis needs).


By cleaning the data, the script ensures its accuracy and usability for future data exploration and analysis related to Nashville housing information.
