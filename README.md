# Data Cleaning using Pandas

Data cleaning, also known as data cleansing or scrubbing, is the process of identifying and correcting errors, inconsistencies, and irrelevant data in datasets to ensure their accuracy and reliability for analysis purposes.

This project demonstrates the process of data cleaning using the **pandas** library of python for a given dataset that contains customer call list information.

The various steps involved include:
1. **Dropping duplicates** - removing duplicate rows in the data using the drop_duplicates function
2. **Dropping columns** - removing column that is not useful and not required for analysis purposes using the drop function
3. **Cleaning/Standardizing values** - using the replace and apply functions
    1. removing unwanted characters from text values
    2. standardizing phone numbers into a single consistent format
    3. standardizing yes/no values as Y or N only 
5. **Splitting column** - splitting the address into street address, state and zip code using the split function
6. **Filling Null values** - replacing null values using the fillna function
7. **Filtering rows** - removing rows using conditional indexing based on a criteria being that rows for which 'Do-Not_Contact' column has value 'Y' to be removed.Similarly, for 'Phone_Number' column rows having blank entries to be removed.
8. **Resetting Index** - resetting row indices using the reset_index function
