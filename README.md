Customer Personality Analysis - Data Cleaning and Preprocessing
This project is part of an internship task to demonstrate data cleaning and preprocessing skills using Python (Pandas). The dataset simulates a real-world customer database with various issues such as missing values, inconsistent formatting, and duplicate entries.

Dataset Overview
Filename: customer_personality_extended.csv
Rows: ~2,000
Columns: 28

The dataset includes detailed customer attributes such as:

Demographics: Year of Birth, Education, Marital Status, Income, Country

Household: Number of kids and teens

Spending behavior: Monthly spend on wine, fruits, meat, fish, sweets, and gold products

Engagement: Number of purchases via web, store, catalog, etc.

Campaign Response: Whether they accepted any of the 5 campaigns or not

Customer since date (Dt_Customer), Recency, and Country

Objectives
Clean and prepare raw customer data for analysis

Standardize formatting and structure

Eliminate data inconsistencies

Ensure the dataset is suitable for modeling and business insights

Tools Used
Python

Pandas

Jupyter Notebook / PyCharm

(Optional) NumPy, Matplotlib

Cleaning Steps Performed
Removed Duplicates

Dropped repeated customer records using drop_duplicates().

Handled Missing Values

Used .isnull() to identify nulls.

Replaced missing numerical values with median.

Replaced missing categorical values with mode.

Standardized Text Fields

Cleaned inconsistent capitalization/spacing in:

Education (e.g., “phd” to “PhD”)

Marital_Status

Country

Formatted Dates

Converted Dt_Customer to uniform dd-mm-yyyy format using pd.to_datetime().

Renamed Columns

Standardized headers to lowercase and snake_case (e.g., Year_Birth to year_birth).

Converted Data Types

Ensured correct data types for:

year_birth as int

income as float

Dt_Customer as datetime

Final Output
Cleaned file saved as: customer_personality_cleaned.csv

Dataset is now ready for:

Customer segmentation

Exploratory Data Analysis (EDA)

Predictive modeling

How to Run
Install required package:

nginx
Copy
Edit
pip install pandas
Run the cleaning script:

nginx
Copy
Edit
python clean_customer_data.py
(Or run the notebook version if available.)

Summary of Cleaning Results
Removed: 10 duplicate rows

Filled: ~300 missing values

Cleaned: inconsistent text fields in 3+ columns

Fixed: column names and date formats

Total rows (after cleaning): ~1990

Contact
Prateek Rahut
Email: prateek.rahut1990@gmail.com
LinkedIn: https://www.linkedin.com/in/prateek-rahut-453586138/
GitHub: https://github.com/CoolPratee
