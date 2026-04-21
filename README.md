# practical14

Aim: To perform Data Binning and Data Formatting using Python.

Theory:

Data binning (also called discretization or bucketing) is the process of transforming continuous numerical values into discrete categorical groups called bins or intervals. Instead of working with raw numbers that have many possible values, binning groups them into a manageable number of labeled categories.
Pandas provides powerful functions for binning, formatting text, changing data types, rounding numerical values, sorting records, and analyzing unique categories. These techniques are widely used in business analytics, sales analysis, and operational data processing to simplify interpretation and improve decision-making.

DataFrame() – Creates a structured tabular dataset from dictionary data.

cut() – Converts continuous numerical values into categorical bins.

astype() – Changes the data type of a selected column.

dtypes – Displays the data types of all columns.

str.upper() – Converts text values in a column to uppercase.

str.lower() – Converts text values in a column to lowercase.

round() – Rounds numerical values to the specified number of decimal places.

sort_values() – Sorts the dataset based on selected columns.

unique() – Returns all unique values present in a column.

value_counts() – Counts the frequency of each category.

print() – Displays the transformed dataset or output values.

The following logic was applied to both the "Product" and "Food Delivery" datasets:

Define the Data: Create a dictionary with numerical and textual fields and load it into a DataFrame.

Define Bin Intervals: * Create a list for Bins (the numerical boundaries).

Create a list for Labels (the names assigned to each bin).

Apply Binning: Use the pd.cut() function to map continuous values into the defined categories.

Format Text: Use the .str.upper() or .str.lower() methods to standardize string columns.

Adjust Data Types: Use .astype() to convert columns (e.g., converting an integer Units_Sold to a float).

Sort and Filter: Use sort_values() to organize the data based on specific criteria like sales volume or delivery time.

Summarize: Use value_counts() to see the distribution of data across the newly created bins.

Conclusion:

Data Binning and Data Formatting operations using Python and the Pandas library were successfully performed.
