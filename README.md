# Netflix
Steps that used to to clean the data set is mentined below:

1. Loaded data: Imported pandas and loaded the dataset from a CSV file.
2. Explored data: Checked the first and last few rows, data shape, unique values, and column names.
3. Handled missing values: Replaced missing values in specific columns with 'Unknown' or the most frequent rating. Removed rows with remaining missing values.
4. Removed duplicates: Checked for duplicate rows and found none.
5. Standardized text: Stripped and title-cased 'type' and 'country' columns, and uppercased 'rating'.
6. Formatted dates: Converted 'date_added' to datetime and formatted it to dd-mm-yyyy.
7. Renamed columns: Lowercased and replaced spaces with underscores in column headers.
8. Changed data type: Converted 'release_year' from integer to string.

Now the data is clean, and ready for analysis.
