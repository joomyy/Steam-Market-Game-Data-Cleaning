# **Original Data Source:**

Platform: Kaggle | **Steam Games Dataset**  
Made by Martin Bustos  
Downloaded on June 19, 2026  
Data Cleaning: Josh Jumuad

## **Documentation**

Organizing Data

* Discover that some columns do not contain any valuable data within each cell  
* Standardized column formats for analysis (e.g., bold, centered, colored)  
* Verified game titles remained matched with their corresponding release dates  
* Formatted release dates to be in a standardized format  
* Removed unnecessary columns that were not relevant to the analysis  
* Centered estimated owners, peak CCU columns  
* Removed unnecessary misc texts within strings


Currency / Numbers:

* Formatted the numbers in the prices column into currency  
* Deleted rows with 0 estimated owners for more accurate results  
* Verified price values contained no invalid negative entries

Filtering:

* Deleted rows with 0 estimated owners for more accurate results by filtering rows that had “0 \- 0”  
* Filtered to all column data are sorted by the game titles from A-Z  
* Filled in missing values under publishers with the text “None”  
* Filled in missing game descriptions under " About the Game "   
* Filled in missing values under tags with “ No Tags “  
* Filled in missing values under genre with “ Unknown “

