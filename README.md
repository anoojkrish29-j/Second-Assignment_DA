# Second-Assignment_DA
Assignment 2 - Data Cleaning and Transformation.

1. Check for missing values in the 'Price' column. How would you handle products with missing price information?
    Ans: Find out the median price range and gave to the missing price fields - median().
2. If there are products with missing categories, propose a strategy to impute or deal with these missing values effectively.
    Ans: Missing categories given as Unknown.
3.  Identify any inconsistent text formats present in the "Product Name" column.
    Ans: formatted using proper().
4. Identify any typos present in the "Category" column./ Use the find and replace function to standardize the text formats in the "Product Name" column and fix any typos or misspellings in the "Category" column.
    Ans: Replaced by find and replace.
5. Identify any duplicate rows within the dataset based on the entirety of each row, and remove them if any.
    Ans: Removed using Remove Duplicates from Data tab.
6.  Split the "Product ID" column into two separate columns for " Manufacturing Date" and "Country Code". Remove unnecessary characters, if any.
    Ans: Used Text to Coloumn to split data seperated by hyphens.
7.  Merge the "Brand Name" and "Product Name" columns into one column named "Product Brand".
    Ans: Used Concatenate()
8.   Format the data type of the "Price" column to currency format. /Format the "Manufacturing Date" column to display dates in the "DD-MM-YYYY " format.
    Ans: Chnaged price from General to currency and Date given using date(),mid(),left().
9.   Apply data bar or color scales conditional formatting in the "Price" column./ Create a custom rule for conditional formatting in the "Category" column to highlight cells where the category is "Electronics."
   Ans: Applied data bars from conditional formatting to price / using conditional formatting highlighted the cell contains Electronics.
